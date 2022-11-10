<a name="readme-top"></a>


<!-- PROJECT SHIELDS -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![License][license-shield]][license-url]

<!-- PROJECT LOGO -->
<br />
<div align="center" style="text-align: center">
	<a href="https://github.com/amuzil/docs">
		<img src="https://raw.githubusercontent.com/amuzil/docs/main/docs/assets/brand/logo.png" alt="Logo" width="80" height="80">
	</a>
	<h3>Amuzil Docs</h3>
	<p>
        The documentation for all Amuzil projects, open source so all can contribute.
        <br />
        <a href="https://docs.amuzil.com"><strong>Check it out »</strong></a>
        <br />
        <br />
        <a href="https://github.com/amuzil/docs/issues">Report Bug</a>
        ·
        <a href="https://github.com/amuzil/docs/issues">Request Feature</a>
	</p>
</div>


<!-- TABLE OF CONTENTS -->
<details>
	<summary>Table of Contents</summary>
	<ol>
		<li>
			<a href="#about-the-project">About The Project</a>
			<ul>
				<li><a href="#why-open-source-the-documentation">Why open source the documentation?</a></li>
				<li><a href="#built-with">Built with</a></li>
			</ul>
		</li>
		<li>
			<a href="#getting-started">Getting Started</a>
			<ul>
				<li><a href="#prerequisites">Prerequisites</a></li>
				<li><a href="#installation">Installation</a></li>
			</ul>
		</li>
		<li><a href="#contributing">Contributing</a></li>
		<li><a href="#license">License</a></li>
		<li><a href="#contact">Contact</a></li>
		<li><a href="#acknowledgments">Acknowledgments</a></li>
	</ol>
</details>


<!-- ABOUT THE PROJECT -->

## About The Project

[![Banner][banner]][docs-url]

[![GitHub repo file count][github-repo-file-count]][github-repo-url]
[![GitHub repo size][github-repo-size]][github-repo-url]
[![GitHub repo last commit][github-repo-last-commit]][github-repo-url]
[![GitHub repo languages][github-repo-languages]][github-repo-url]

[![GitHub open milestones][github-open-milestones]][github-open-milestones-url]
[![GitHub closed milestones][github-closed-milestones]][github-closed-milestones-url]

[![GitHub open pull requests][github-open-pull-requests]][github-open-pull-requests-url]
[![GitHub closed requests][github-closed-pull-requests]][github-closed-pull-requests-url]

[![GitHub open issues][github-open-issues]][github-open-issues-url]
[![GitHub closed issues][github-closed-issues]][github-closed-issues-url]

The Amuzil Docs is a documentation site for all Amuzil projects.
It is and will probably always be a work in progress, as we are always adding new features to our projects.
The documentation is made with [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/),
a Material Design theme for [MkDocs](https://www.mkdocs.org/).

<p align="right" style="text-align: right">(<a href="#readme-top">back to top</a>)</p>

### Why open source the documentation?

We believe that open source is the future, and that everyone should be able to contribute to the projects they use.
Documentation is a very important part of any project; a project is useless if no one knows how to use it.
By open sourcing the documentation, we hope to achieve the following:

- [ ] **Better documentation**: The documentation is written by the community, for the community. The community will
  write much better documentation than a small team of developers, as they are the end users of the documentation.
- [ ] **More contributors**: By open sourcing the documentation, we hope to attract more contributors to the project.
  Contributors can help us improve the documentation, and they can also help us improve the projects themselves.
- [ ] **Reduced workload**: By open sourcing the documentation, we hope to reduce the workload of the developers.
  The developers can focus on developing the projects, and the community can focus on improving the documentation.
- [ ] **Open Source**: Open source is one of the core pillars of our community. We believe that everyone should be able
  to contribute to the projects they use, so that they can improve it and learn from it.
- [ ] **Community**: We want to build a community around our projects, and open sourcing the documentation is a great
  way to do that. It gives active contributors a sense of ownership, and it gives people a reason and way to contribute
  without necessitating technical knowledge or skills.

<p align="right" style="text-align: right">(<a href="#readme-top">back to top</a>)</p>

### Built with

[![Material for MkDocs][mkdocs-material-shield]][mkdocs-material-url]
[![MkDocs][mkdocs-shield]][mkdocs-url]
[![GitHub Pages][github-pages-shield]][github-pages-url]
[![Node.js][nodejs-shield]][nodejs-url]
[![PNPM][pnpm-shield]][pnpm-url]

[![Markdown][markdown-shield]][markdown-url]
[![Python][python-shield]][python-url]
[![HTML5][html5-shield]][html5-url]
[![SCSS][scss-shield]][scss-url]
[![TypeScript][typescript-shield]][typescript-url]

[![PyCharm][pycharm-shield]][pycharm-url]
[![Visual Studio Code][vscode-shield]][vscode-url]
[![Git][git-shield]][git-url]
[![GitHub][github-shield]][github-url]

<p align="right" style="text-align: right">(<a href="#readme-top">back to top</a>)</p>


<!-- GETTING STARTED -->

## Getting started

This guide is not yet finalised and may not be complete. It is also not yet tested.

### Prerequisites

Before you begin, ensure you have met the following requirements:

* [Python 3](https://www.python.org/downloads/)
	* To check if you have Python installed, run the following command:

	  ```bash
	  python --version
	  ```

	  It should return a version number, such as 3.11.0. Ensure that the version number is 3.

* [Node.js](https://nodejs.org/en/download/)
  / (We recommend using NVM ([Linux/macOS](https://github.com/nvm-sh/nvm)
  / [Windows](https://github.com/coreybutler/nvm-windows)) to install Node.js)
	* To check if you have Node.js installed, run the following command:

	  ```bash
	  node --version
	  ```

	  It should return a version number, such as 18.11.0. Ensure that the version number is at least 18.

* [PNPM](https://pnpm.io/installation)
	* To check if you have PNPM installed, run the following command:

	  ```bash
	  pnpm --version
	  ```

	  It should return a version number, such as 7.14.2. Ensure that the version number is at least 7.

* [Git](https://git-scm.com/downloads)
	* To check if you have Git installed, run the following command:

	  ```bash
	  git --version
	  ```

	  It should return a version number, such as 2.33.0. Ensure that the version number is at least 2.

* (Windows only) [GTK+](https://github.com/tschoonj/GTK-for-Windows-Runtime-Environment-Installer/releases)

### Installation

While the below guide details specific `git` commands, you also can (and probably should) use a GUI for Git.
Options include any [JetBrains IDE](https://www.jetbrains.com/products.html) (such
as [IntelliJ IDEA](https://www.jetbrains.com/idea/)), [GitHub Desktop](https://desktop.github.com/),
or [GitKraken](https://www.gitkraken.com/).

1. Clone the repo

   ```bash
   git clone https://github.com/amuzil/docs.git
   ```

2. Create a Python virtual environment and activate it

   ```bash
   # All platforms
   python -m venv venv
   # Linux/macOS
   source venv/bin/activate
   # Windows
   venv\Scripts\activate
   ```

3. Install the dependencies

   ```bash
   pnpm install
   ```

4. Serve the live preview

   ```bash
   pnpm serve
   ```
   
This will start a live preview of the site. You can access it at <http://localhost:8000>.

<p align="right" style="text-align: right">(<a href="#readme-top">back to top</a>)</p>

### Installation (Insiders)

If you have access to the Insiders version of Material for MkDocs, the installation process is slightly different.

1. Clone the repo

   ```bash
   git clone https://github.com/amuzil/docs.git
   ```

2. Create a `.env` file and set your Insiders access token

   ```env
   MKDOCS_MATERIAL_INSIDERS_TOKEN={YOUR_TOKEN}
   ```

3. Create a Python virtual environment and activate it

   ```bash
   # All platforms
   python -m venv venv
   # Linux/macOS
   source venv/bin/activate
   # Windows
   venv\Scripts\activate
   ```

4. (Windows only) Install LXML binaries
   1. Download the [latest (CPython) Wheel file](https://www.lfd.uci.edu/~gohlke/pythonlibs/#lxml) to your `venv/Lib` folder
   2. Run the following command:

	  ```bash
	  pip install venv\Lib\{WHEEL_FILE}
	  ```

5. Install the dependencies

   ```bash
   pnpm install
   # Remember to replace {YOUR_TOKEN} with your actual token
   pip install git+https://{YOUR_TOKEN}@github.com/squidfunk/mkdocs-material-insiders.git
   ```

6. Serve the live preview

   ```bash
   pnpm serve:insiders
   ```

<!-- CONTRIBUTING -->

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create.
Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request.
You can also simply open an issue.
If you really like the project, consider giving it a star!

> Something we like to use it [Gitmoji](https://gitmoji.dev/), which is an emoji guide for Git commit messages.
> It makes it easier to see what kind of changes have been made at a glance.
> While not required, we heavily recommend using it.
>
> To make things easier, check
> out [Gitmoji Plus: Commit Button](https://plugins.jetbrains.com/plugin/12383-gitmoji-plus-commit-button),
> a plugin for JetBrains IDEs that adds a button to the commit dialog that allows you to easily add a Gitmoji to your
> commit message.

While the below guide details specific `git` commands, you also can (and probably should) use a GUI for Git.
Options include any [JetBrains IDE](https://www.jetbrains.com/products.html) (such
as [IntelliJ IDEA](https://www.jetbrains.com/idea/)), [GitHub Desktop](https://desktop.github.com/),
or [GitKraken](https://www.gitkraken.com/).

1. Fork the Project
2. Create your Feature Branch

   ```bash
   git checkout -b feature/AmazingFeature
   ```

3. Commit your Changes

   ```bash
   git commit -m ":sparkles: Add some AmazingFeature"
   ```

4. Push to the Branch

   ```bash
   git push origin feature/AmazingFeature
   ```

5. Open a Pull Request

<p align="right" style="text-align: right">(<a href="#readme-top">back to top</a>)</p>


<!-- LICENSE -->

## License

Distributed under the Unlicense. See [`license.md`](license.md) for more information.

<p align="right" style="text-align: right">(<a href="#readme-top">back to top</a>)</p>


<!-- CONTACT -->

## Contact

[![Book a meeting][cal-shield]][cal-url]

Main contact: **Luka "Mahtaran" Leer**

[![LinkedIn][luka-linkedin-shield]][luka-linkedin-url]
[![Mail][luka-mail-shield]][luka-mail-url]
[![Website][luka-website-shield]][luka-website-url]

[![Follow on GitHub][luka-github-followers-shield]][luka-github-followers-url]
[![Follow on Reddit][luka-reddit-shield]][luka-reddit-url]
[![Follow on Twitter][luka-twitter-shield]][luka-twitter-url]

<p align="right" style="text-align: right">(<a href="#readme-top">back to top</a>)</p>


<!-- ACKNOWLEDGMENTS -->

## Acknowledgments

* [Readme template by Othneil Drew](https://github.com/othneildrew/Best-README-Template)

<p align="right" style="text-align: right">(<a href="#readme-top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->

[contributors-shield]: https://img.shields.io/github/contributors/amuzil/docs.svg?style=for-the-badge

[contributors-url]: https://github.com/amuzil/docs/graphs/contributors

[forks-shield]: https://img.shields.io/github/forks/amuzil/docs.svg?style=for-the-badge

[forks-url]: https://github.com/amuzil/docs/network/members

[stars-shield]: https://img.shields.io/github/stars/amuzil/docs.svg?style=for-the-badge

[stars-url]: https://github.com/amuzil/docs/stargazers

[hacktoberfest-shield]: https://img.shields.io/github/hacktoberfest/2022/amuzil/docs?style=for-the-badge

[hacktoberfest-url]: https://hacktoberfest.com/

[license-shield]: https://img.shields.io/github/license/amuzil/docs.svg?style=for-the-badge

[license-url]: https://github.com/amuzil/docs/blob/main/license.md


[banner]: https://raw.githubusercontent.com/amuzil/docs/main/docs/assets/brand/banner.png

[docs-url]: https://docs.amuzil.com


[github-repo-url]: https://github.com/amuzil/docs/

[github-repo-file-count]: https://img.shields.io/github/directory-file-count/amuzil/docs?style=for-the-badge

[github-repo-size]: https://img.shields.io/github/repo-size/amuzil/docs?style=for-the-badge

[github-repo-last-commit]: https://img.shields.io/github/last-commit/amuzil/docs?style=for-the-badge

[github-repo-languages]: https://img.shields.io/github/languages/count/amuzil/docs?style=for-the-badge

[github-open-issues]: https://img.shields.io/github/issues/amuzil/docs?style=for-the-badge

[github-open-issues-url]: https://github.com/amuzil/docs/issues

[github-closed-issues]: https://img.shields.io/github/issues-closed/amuzil/docs?style=for-the-badge

[github-closed-issues-url]: https://github.com/amuzil/docs/issues?q=is%3Aissue+is%3Aclosed

[github-open-pull-requests]: https://img.shields.io/github/issues-pr/amuzil/docs?style=for-the-badge

[github-open-pull-requests-url]: https://github.com/amuzil/docs/pulls

[github-closed-pull-requests]: https://img.shields.io/github/issues-pr-closed/amuzil/docs?style=for-the-badge

[github-closed-pull-requests-url]: https://github.com/amuzil/docs/pulls?q=is%3Apr+is%3Aclosed

[github-open-milestones]: https://img.shields.io/github/milestones/open/amuzil/docs?style=for-the-badge

[github-open-milestones-url]: https://github.com/amuzil/docs/milestones

[github-closed-milestones]: https://img.shields.io/github/milestones/closed/amuzil/docs?style=for-the-badge

[github-closed-milestones-url]: https://github.com/amuzil/docs/milestones?q=is%3Aclosed


[mkdocs-material-shield]: https://img.shields.io/badge/MkDocs%20Material-4051B5?style=for-the-badge&logo=read-the-docs&logoColor=white

[mkdocs-material-url]: https://squidfunk.github.io/mkdocs-material/

[mkdocs-shield]: https://img.shields.io/badge/MkDocs-54B4EB?style=for-the-badge&logo=mdbook&logoColor=white

[mkdocs-url]: https://www.mkdocs.org/

[github-pages-shield]: https://img.shields.io/badge/GitHub%20Pages-181717?style=for-the-badge&logo=github&logoColor=white

[github-pages-url]: https://pages.github.com/

[nodejs-shield]: https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white

[nodejs-url]: https://nodejs.org/en/

[pnpm-shield]: https://img.shields.io/badge/pnpm-CC3534?style=for-the-badge&logo=pnpm&logoColor=white

[pnpm-url]: https://pnpm.io/


[markdown-shield]: https://img.shields.io/badge/Markdown-4a525a?style=for-the-badge&logo=markdown&logoColor=white

[markdown-url]: https://daringfireball.net/projects/markdown/

[python-shield]: https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white

[python-url]: https://www.python.org/

[html5-shield]: https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white

[html5-url]: https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5

[scss-shield]: https://img.shields.io/badge/SCSS-CC6699?style=for-the-badge&logo=sass&logoColor=white

[scss-url]: https://sass-lang.com/

[typescript-shield]: https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white

[typescript-url]: https://www.typescriptlang.org/


[pycharm-shield]: https://img.shields.io/badge/PyCharm-000000?style=for-the-badge&logo=pycharm&logoColor=white

[pycharm-url]: https://www.jetbrains.com/pycharm/

[vscode-shield]: https://img.shields.io/badge/Visual_Studio_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white

[vscode-url]: https://code.visualstudio.com/

[git-shield]: https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white

[git-url]: https://git-scm.com/

[github-shield]: https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white

[github-url]: https://github.com/


[cal-shield]: https://img.shields.io/badge/Cal.com-1DA1F2?style=for-the-badge&logo=google-calendar&logoColor=white&label=Book+a+meeting

[cal-url]: https://app.cal.com/team/amuzil


[luka-linkedin-shield]: https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white

[luka-linkedin-url]: https://linkedin.com/in/luka-leer

[luka-mail-shield]: https://img.shields.io/badge/Mail-D14836?style=for-the-badge&logo=gmail&logoColor=white

[luka-mail-url]: mailto:mahtaran@amuzil.com

[luka-website-shield]: https://img.shields.io/badge/Website-FF7139?style=for-the-badge&logo=firefox&logoColor=white

[luka-website-url]: https://mahtaran.amuzil.com/

[luka-github-followers-shield]: https://img.shields.io/github/followers/Mahtaran?style=for-the-badge&logo=github&logoColor=white&label=Follow+on+GitHub

[luka-github-followers-url]: https://github.com/Mahtaran

[luka-reddit-shield]: https://img.shields.io/reddit/user-karma/link/Mahtaran?style=for-the-badge&logo=reddit&logoColor=white&label=Follow+on+Reddit

[luka-reddit-url]: https://reddit.com/user/Mahtaran

[luka-twitter-shield]: https://img.shields.io/twitter/follow/mahtaransocial?style=for-the-badge&logo=twitter&logoColor=white&label=Follow+on+Twitter

[luka-twitter-url]: https://twitter.com/mahtaransocial
