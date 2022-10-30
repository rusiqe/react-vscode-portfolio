<!-- ABOUT THE PROJECT -->
## About The Project

The project is inspired by [Visual Studio Code](https://github.com/microsoft/vscode) and [caglarturali.github.io](https://github.com/caglarturali/caglarturali.github.io). The pages of the portfolio are powered by `markdown`, which make them easy to modify or add your own contents.

<p align="right">(<a href="#top">back to top</a>)</p>

### Built With

* [React.js](https://reactjs.org/)
* [Material UI](https://github.com/mui/material-ui)
* [react-markdown](https://github.com/remarkjs/react-markdown)

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- GETTING STARTED -->
## Getting Started

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/noworneverev/react-vscode-portfolio.git
   ```
2. Install NPM packages
   ```sh
   npm install
   ```
3. Enter your name in `.env.development`
   ```js
   REACT_APP_NAME=<your_name>
   ```
4. Add your markdown pages in `public/pages`
5. Add your routes in `src/app/pages/page.ts`, make sure the names of pages are consistent with markdown files.
    ```ts
    export const pages = [
      { index: 0, name: 'overview.md', route: '/overview' },
      { index: 1, name: 'skills.md', route: '/skills' },
      { index: 2, name: 'experience.md', route: '/experience' },
      { index: 3, name: 'education.md', route: '/education' },
      { index: 4, name: 'projects.md', route: '/projects' },  
      { index: 5, name: 'certificates.md', route: '/certificates' },
      { index: 6, name: 'accomplishments.md', route: '/accomplishments' },
    ];
    ```
6. Add your social links in `src/app/pages/link.tsx`, which will appear in both sidebar and homepage.
    ```ts
    export const links = [
      {
        index: 0,
        title: "Find me on Github",
        href: "https://github.com/noworneverev",
        icon: <FaGithub />,
      },
    ];
    ```
7. Runs the app in the development mode
   ```sh
   npm start
   ```
8. If you would like to deploy your own portfolio, don't forget to change Google Analytic measurement id in `.env.production`
   ```
   REACT_APP_NAME=<your_name>
   REACT_APP_MEASUREMENT_ID=<your_measurement_id>
   ```

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->
## Features

- Powered by markdown
- Dark mode and light mode available
- Closable tabs
- Collapsible explorer
- Responsive web design
- Google Analytics supported
- Auto-deploy to gh-pages with github actions ready

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.md` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [Img Shields](https://shields.io)
* [GitHub Pages](https://pages.github.com)
* [React Icons](https://react-icons.github.io/react-icons/search)
* [caglarturali.github.io](https://github.com/caglarturali/caglarturali.github.io)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[forks-shield]: https://img.shields.io/github/forks/noworneverev/react-vscode-portfolio
[forks-url]: https://github.com/noworneverev/react-vscode-portfolio/network/members
[stars-shield]: https://img.shields.io/github/stars/noworneverev/react-vscode-portfolio
[stars-url]: https://github.com/noworneverev/react-vscode-portfolio/stargazers
[issues-shield]: https://img.shields.io/github/issues/noworneverev/react-vscode-portfolio
[issues-url]: https://github.com/noworneverev/react-vscode-portfolio/issues
[license-shield]: https://img.shields.io/github/license/noworneverev/react-vscode-portfolio
[license-url]: https://github.com/noworneverev/react-vscode-portfolio/blob/master/LICENSE.md
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/yan-ying-liao/
[product-screenshot]: ./src/static/screenshot.gif
[gh-pages-shield]: https://img.shields.io/github/deployments/noworneverev/noworneverev.github.io/github-pages
[gh-pages-url]: https://github.com/noworneverev/noworneverev.github.io/deployments
[website-shield]:https://img.shields.io/website?url=https%3A%2F%2Fnoworneverev.github.io%2F
[website-url]: https://noworneverev.github.io/
