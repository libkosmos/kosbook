
<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#upcoming">Upcoming</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

<img src="https://github.com/libkosmos/kosbook/kosbook.png">

kosbook is a brute force application built on python3 which enables the tester to enter the victims account by using their API, it uses various libraries like optparse, re and more.

How does it work?
* kosbook is social engineering application, User can only hack the victims account if they are good in guessing and assuming other people trades and values.
* It uses wordlist to perform a sucessful hack, all the way the user have to update the wordlist.txt file which is already provided to make a hack attempt.


A list of commonly used resources that I find helpful are listed in the acknowledgements.

### Built With

* [Python](https://www.python.org/)


<!-- GETTING STARTED -->
## Getting Started

How to get this application run?

### Prerequisites

* For Linux installation 
  ```
  cd kosbook
  chmod +x setup.sh
  ./setup.sh
  ```
* For Windows installation
  * install python3 from python.org
  * install git from https://git-scm.com/downloads

### Usage

1. This program does not require any installation because of run-time.
2. Clone the repo
   ```sh
   git clone https://github.com/libkosmos/kosbook
   ```
3. Get into the directory of the program
   ```sh
   cd kosbook
   ```
4. Run your program
   ```sh
   python3 kosbook.py
   ```
5. Check the PATH and WAY
   ```sh
   python3 kosbook.py -h
   ```
   
  ### Upcoming
  
  1. Requirements.txt file {NEW FEATURE}
  2. .exe for Windows
  3. GUI for both env (Linux, Windows)

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under an open license. See `LICENSE` for more information.


<!-- CONTACT -->
## Contact

Twitter - [@gadrielgargard7](https://x.com/gadrielgargard7)


[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png

# 🔐 kosbook - Security Testing Tool

[![Python Version](https://img.shields.io/badge/python-3.6+-blue.svg)](https://www.python.org/downloads/)
[![License](https://img.shields.io/badge/license-Open%20Source-blue.svg)](LICENSE)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/libkosmos/kosbook/graphs/commit-activity)

<div align="center">
  <img src="https://github.com/libkosmos/kosbook/kosbook.png" alt="kosbook Logo" width="200"/>
  
  ### ⚠️ IMPORTANT LEGAL NOTICE ⚠️
  
  **kosbook is developed for educational and authorized security testing purposes only.**
  
  - 🔒 Use only on accounts you own or have explicit permission to test
  - ⚖️ Unauthorized access to computer systems is illegal
  - 🔍 Intended for security professionals and penetration testers
  - 📜 Users must comply with all applicable laws and regulations
</div>

## 📋 Table of Contents
- [About The Project](#about-the-project)
- [Features](#-features)
- [Legal & Ethical Guidelines](#-legal--ethical-guidelines)
- [Prerequisites](#-prerequisites)
- [Installation](#-installation)
- [Usage](#-usage)
- [Disclaimer](#-disclaimer)
- [Author](#-author)
- [License](#-license)

## 📖 About The Project

kosbook is a security assessment tool designed to test password strength and security awareness. It simulates brute force attacks to help identify weak passwords and improve overall account security.

This tool is developed to:
- Help security professionals test their own systems
- Assist in security awareness training
- Demonstrate the importance of strong passwords
- Test security measures in controlled environments

## ✨ Features

- 🎯 Multiple attack modes (wordlist-based)
- 🔄 Proxy support for testing network security
- 📊 Progress tracking and statistics
- 🛡️ Rate limiting awareness
- 🎨 User-friendly interface

## ⚖️ Legal & Ethical Guidelines

### ✅ Permitted Uses
- Testing your own accounts
- Security research with explicit permission
- Educational demonstrations
- Security awareness training

### ❌ Prohibited Uses
- Unauthorized access to accounts
- Illegal activities
- Malicious attacks
- Violation of terms of service

**By using this tool, you agree to use it only for legal and ethical purposes.**

## 🛠 Prerequisites

- Python 3.6 or higher
- pip (Python package manager)
- Required Python packages (will be installed automatically)

## 📥 Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/libkosmos/kosbook.git
   cd kosbook
   ```

2. Run the setup script:
   ```sh
   # For Linux/macOS
   chmod +x setup.sh
   ./setup.sh
   
   # For Windows
   setup.bat
   ```

## 🚀 Usage

### Basic Usage
```sh
python3 kosbook.py -t your-email@example.com -w path/to/wordlist.txt
```

### Options
```
-t, --target      Target email or Facebook ID
-w, --wordlist    Path to wordlist file
-s, --single      Test a single password
-p, --proxy       Use HTTP/S proxy (IP:PORT)
-h, --help        Show help message
```

### Example
```sh
python3 kosbook.py -t test@example.com -w passwords.txt -p 127.0.0.1:8080
```

## ⚠️ Disclaimer

This tool is provided for educational and security testing purposes only. The developers and contributors are not responsible for any misuse or damage caused by this program. Always obtain proper authorization before conducting security testing.

## 👨‍💻 Author

**Gadriel Borbor Gargard**  
Security Researcher & Developer

### 🌐 Connect with Me
- Twitter: [@gadrielgargard7](https://x.com/gadrielgargard7)
- Facebook: [Gadriel Borbor Gargard](https://facebook.com/gadrielgargard7)
- GitHub: [@libkosmos](https://github.com/libkosmos)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<div align="center">
  Made with ❤️ by Gadriel Borbor Gargard | Use responsibly!
</div>
