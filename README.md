<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<p align="center">

<img src="https://github.com/edingc/ansible-gophish-ubuntu/raw/master/images/screenshot.png" alt="ansible-gophish-ubuntu Screen Shot" />

</p>

  <h3 align="center">ansible-gophish-ubuntu</h3>

  <p align="center">
    An Ansible playbook to setup Gophish quickly on an Ubuntu 18.04 system. Comes complete with working SSL, DKIM and TLS. Instructions for DNS requirements provided upon completion.
    <br />
    <a href="https://github.com/edingc/ansible-gophish-ubuntu/issues">Report Bug</a>
    ·
    <a href="https://github.com/edingc/ansible-gophish-ubuntu/issues">Request Feature</a>
  </p>





<!-- TABLE OF CONTENTS -->
## Table of Contents

* [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Usage](#usage)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)

### Built With/On

* [Ansible](https://github.com/ansible/ansible)
* [Gophish](https://github.com/gophish/gophish)
* [Ubuntu](https://ubuntu.com/)
* [Atom](https://github.com/atom/atom)


<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

As this is an Ansible playbook, Ansible is required to be installed on a control
machine. [Ansible is available for almost every platform.](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)

This playbook was developed using a Digital Ocean Ubuntu 18.04 instance, but should
work on any Ubuntu 18.04 installation.

### Installation

1. Clone the ansible-gophish-ubuntu
```sh
git clone https://github.com/edingc/ansible-gophish-ubuntu.git
```
2. Run the Ansible playbook
```sh
ansible-playbook site.yml
```

<!-- USAGE EXAMPLES -->
## Usage

After the playbook has been run against the target host, a file containing needed
DNS entries will be placed in the home directory of Gophish user. Place these
entries into your DNS.

The use guide for Gophish can be found at the [Gophish documentation website](https://getgophish.com/documentation/).

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

Distributed under the MIT License. See `LICENSE` for more information.

<!-- CONTACT -->
## Contact

Your Name - [@edingc](https://twitter.com/edingc) - cody@codyeding.com

Project Link: [https://github.com/edingc/ansible-gophish-ubuntu](https://github.com/edingc/ansible-gophish-ubuntu)

<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* [Digital Ocean Community](https://www.digitalocean.com/community) for the basis of the "common" task
* [Gophish](https://github.com/gophish/gophish) for the bits that download and extract Gophish
* [Othneil Drew](https://github.com/othneildrew/Best-README-Template) for the great README.md template
* Numerous other websites, Google searches and StackOverflow posts that yielded individual bits and bobs
necessary to get OpenDKIM, Postfix, SSL and TLS all playing nicely together


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/edingc/ansible-gophish-ubuntu.svg?style=flat-square
[contributors-url]: https://github.com/edingc/ansible-gophish-ubuntu/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/edingc/ansible-gophish-ubuntu.svg?style=flat-square
[forks-url]: https://github.com/edingc/ansible-gophish-ubuntu/network/members
[stars-shield]: https://img.shields.io/github/stars/edingc/ansible-gophish-ubuntu.svg?style=flat-square
[stars-url]: https://github.com/edingc/ansible-gophish-ubuntu/stargazers
[issues-shield]: https://img.shields.io/github/issues/edingc/ansible-gophish-ubuntu.svg?style=flat-square
[issues-url]: https://github.com/edingc/ansible-gophish-ubuntu/issues
[license-shield]: https://img.shields.io/badge/License-MIT-yellow.svg
[license-url]: https://github.com/edingc/ansible-gophish-ubuntu/blob/master/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/codyeding
[product-screenshot]: images/screenshot.png
