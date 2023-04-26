<!-- TABLE OF CONTENTS -->

# 📗 Table of Contents

- [📖 About the Project](#about-project)
    - [Tech Stack](#tech-stack)
    - [Key Features](#key-features)
- [💻 Getting Started](#getting-started)
  - [Setup](#setup)
  - [Prerequisites](#prerequisites)
  - [Install](#install)
  - [Usage](#usage)
  - [Run tests](#run-tests)
- [👥 Authors](#authors)
- [🔭 Future Features](#future-features)
- [🤝 Contributing](#contributing)
- [⭐️ Show your support](#support)
- [🙏 Acknowledgements](#acknowledgements)
- [📝 License](#license)

# 📖 Hello Microverse <a name="about-project"></a>

**Hello Microverse** is a project I completed on Day 2 of Module 1 as a student in Microverse. This project was created to practice utilizing linters, GitHub Flow, and requesting code reviews.

As a summary, Hello Microverse is a simple project that includes a basic HTML structure and a CSS stylesheet. The HTML and CSS code are both validated with linters to ensure code quality and consistency. The project follows the GitHub Flow, with branches for features, bug fixes, and pull requests for code review.

Overall, Hello Microverse provided a great introduction to the Microverse program and allowed me to practice essential skills for software development.

### Tech Stack <a name="tech-stack"></a>

<details>
  <summary>Client</summary>
  <ul>
    <li>HTML and CSS</li>
  </ul>
</details>

<!-- Features -->

### Key Features <a name="key-features"></a>

- **Configured Linters**
- **Added an HTML File**
- **Added a CSS file**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->

## 💻 Getting Started <a name="getting-started"></a>

### Prerequisites

In order to run this project you need:
1. git
2. VS Code or any code editor
3. NPM intalled


### Setup

Clone this repository to your desired folder:
```sh
  cd my-folder
  git clone git@github.com:rubydevi/Hello-Microverse.git
  cd Hello-Microverse
```

### Install

Install this project with:

**Weblint**

1. Run this code:
```sh
 npm install --save-dev hint@7.x
```
2. Don't forget to copy [.hintrc](.hintrc) to the root directory of your project.

3. Run this code after you write your html code.
```sh
 npm hint .
```
4. It will show you errors, fix all the errors shown.

**Stylelint**


1. Run this code:
```sh
 npm install --save-dev stylelint@13.x stylelint-scss@3.x stylelint-config-standard@21.x stylelint-csstree-validator@1.x
```
2. Don't forget to copy [.stylelintrc.json](./.stylelintrc.json) to the root directory of your project.

3. Run this code after you write your html code.
```sh
 npx stylelint "**/*.{css,scss}"
```
4. It will show you errors, fix all the errors shown.

### Usage

To run this project in the browser, simply open the index.html file in your preferred browser.

### Run tests

To run tests, run the following command:
```sh
 npm hint .
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 👥 Authors <a name="authors"></a>

👤 **Chongtham Ruby Devi**

- GitHub: [@githubhandle](https://github.com/rubydevi)
- Twitter: [@twitterhandle](https://twitter.com/ariesabyss)
- LinkedIn: [LinkedIn](https://www.linkedin.com/in/chongtham-bhoomika/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- FUTURE FEATURES -->

## 🔭 Future Features <a name="future-features"></a>

- Integration with a continuous integration/continuous deployment (CI/CD) pipeline
- The addition of linters for other programming languages such as JavaScript
- Implementation of an automatic code formatter

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

<!-- SUPPORT -->

## ⭐️ Show your support <a name="support"></a>

If you like this project please leave a star, I'd really appreciate it.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Acknowledgments <a name="acknowledgements"></a>

- I'd like to thank Microverse for this wonderful README template.

<!-- LICENSE -->

## 📝 License <a name="license"></a>

This project is [MIT](./MIT.md) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>