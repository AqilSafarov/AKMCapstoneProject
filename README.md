
<p align="right">(<a href="https://github.com/AqilSafarov/hgg/tree/master">Project Report and Slide</a>)</p>




<!-- ABOUT THE PROJECT -->
## About The Project

<img width="600" alt="Screenshot 2023-07-15 231903" src="https://github.com/AqilSafarov/AKMCapstoneProject/assets/75013710/9ebf17ed-e483-4e9f-9b9b-370200ee7480">



The objective of this project was to develop a detection mechanism for brute force attacks using Splunk, a powerful security information and event management (SIEM) platform. The scope of the project focused specifically on identifying and mitigating brute force attacks against user accounts and passwords within an Active Directory Domain Services (AD DS) environment

## Objective and Scope
Brute force attacks are one of the most common methods used by attackers to gain unauthorized access to systems and sensitive data. By systematically attempting multiple combinations of usernames and passwords, attackers exploit weak credentials and security vulnerabilities. The consequences of successful brute force attacks can be severe, including unauthorized access, data breaches, and compromised user accounts.

The primary objective of this project was to enhance the security posture of the organization by developing an effective detection mechanism for brute force attacks within the AD DS environment. The focus was on quickly identifying and mitigating such attacks to prevent unauthorized access to user accounts and passwords.

## Importance of Detecting and Mitigating Brute Force Attacks

In an AD DS environment, detecting and mitigating brute force attacks is crucial for protecting user accounts and resources. By effectively responding to these attacks, organizations can mitigate risks, prevent unauthorized access, and safeguard sensitive data, IP, and reputation.

<img width="731" alt="Screenshot 2023-07-15 232232" src="https://github.com/AqilSafarov/AKMCapstoneProject/assets/75013710/245d478d-557a-4f32-8208-3c133cb582fa">

### Methodology and Approach
To achieve the project objective, a systematic and comprehensive approach was adopted. The methodology involved the following key steps:

* Environment Setup: A fully featured AD DS environment was created, including the deployment of domain controllers, user accounts, and associated policies. This environment closely resembled a real-world scenario, ensuring the validity and accuracy of the project findings.
* SIEM Deployment: A centralized SIEM server was deployed, leveraging the capabilities of Splunk. The SIEM server acted as a central hub for collecting and analyzing logs from various endpoints within the AD DS environment
* Brute Force Attack Simulations: Various types of brute force attacks were simulated against the AD DS environment, targeting user accounts and passwords. These simulated attacks represented common techniques used by attackers and helped evaluate the effectiveness of the detection mechanism



<p align="right">(<a href="#readme-top">back to top</a>)</p>




### System Specifications for All Machines


* **Domain Controller (Windows Server 2019)**
- [x] CPUs: 2 CPUs.
- [x] RAM: 2048 MB (2GB).
- [x] Disk Space: 40 GB.
- [x] Hyper-V Virtual Machine: Generation 1
- [x] Network Connection: Connected to the Capstone NAT network

* **Splunk Machine (Windows Server 2019)**
- [x] CPUs: 4 CPUs.
- [x] RAM: 8 GB.
- [x] Disk Space: 40 GB.
- [x] Hyper-V Virtual Machine: Generation 1
- [x] Network Connection: Connected to the Capstone NAT network

* **Windows 10 Machines (3)**
- [x] CPUs: 4 CPUs.
- [x] RAM: 2048 MB (2GB) each.
- [x] Disk Space: 40 GB each.
- [x] Hyper-V Virtual Machine: Generation 1
- [x] Each machine is connected to the Capstone NAT network

* **Commando VM Machine (Windows 10 21H1)**
- [x] CPUs: 4 CPUs.
- [x] RAM: 4+ GB.
- [x] Disk Space: 80+ GB.
- [x] Hyper-V Virtual Machine: Generation 1
- [x] Network Connection: Initially, select the Default Switch during Commando VM installation. After installation, change this to the Capstone NAT network


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

1. Get a free API Key at [https://example.com](https://example.com)
2. Clone the repo
   ```sh
   git clone https://github.com/your_username_/Project-Name.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```js
   const API_KEY = 'ENTER YOUR API';
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [x] Add Changelog
- [x] Add back to top links
- [ ] Add Additional Templates w/ Examples
- [ ] Add "components" document to easily copy & paste sections of the readme
- [ ] Multi-language Support
    - [ ] Chinese
    - [ ] Spanish

See the [open issues](https://github.com/othneildrew/Best-README-Template/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Your Name - [@your_twitter](https://twitter.com/your_username) - email@example.com

Project Link: [https://github.com/your_username/repo_name](https://github.com/your_username/repo_name)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Malven's Flexbox Cheatsheet](https://flexbox.malven.co/)
* [Malven's Grid Cheatsheet](https://grid.malven.co/)
* [Img Shields](https://shields.io)
* [GitHub Pages](https://pages.github.com)
* [Font Awesome](https://fontawesome.com)
* [React Icons](https://react-icons.github.io/react-icons/search)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
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
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
