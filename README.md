<div id="top"></div>

<!-- PROJECT SHIELDS -->

[<div align="center"> ![Contributors][contributors-shield]][contributors-url]
![Visitors](https://estruyf-github.azurewebsites.net/api/VisitorHit?user=wst24365888&repo=ez4o/github-contribution-graph&countColor=rgb(0,%20126,%20198))
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]</div>][license-url]

<br />

![github-contribution-graph](https://socialify.git.ci/ez4o/github-contribution-graph/image?description=1&font=KoHo&name=1&owner=1&pattern=Circuit%20Board&theme=Light)

<!-- PROJECT LOGO -->
<br />
<div align="center">
<p align="center">
    <a href="https://github.com/ez4o/github-contribution-graph#usage"><strong>Explore Usage »</strong></a>
    <br />
    <br />
    <a href="https://github.com/ez4o/github-contribution-graph/issues">Report Bug</a>
    ·
    <a href="https://github.com/ez4o/github-contribution-graph/issues">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#usage">Usage</a></li>
        <li><a href="#parameters">Parameters</a></li>
      </ul>
    </li>
    <li><a href="#deploy-your-own-server">Deploy Your Own Server</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

![screenshot][product-screenshot]

**GitHub-Contribution-Graph** is an awesome tool for dynamically generated
contribution graphs that show your GitHub contributions.

It can be used anywhere, you can download the image, share the link, or paste
the link in any markdown file, and it will render the image directly on the
website.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->

## Getting Started

<!-- USAGE EXAMPLES -->

### Usage

`https://github-contribution-graph.ez4o.com/?username=[YOUR_GITHUB_USERNAME]&last_n_days=[DAYS_YOU_WANT_TO_SHOW]&img_url=[ENCODED_IMAGE_URL]`

#### Example

`https://github-contribution-graph.ez4o.com/?username=wst24365888&img_url=https%3A%2F%2Fimages.unsplash.com%2Fphoto-1506744038136-46273834b3fb%3Fixid%3DMnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8%26ixlib%3Drb-1.2.1%26auto%3Dformat%26fit%3Dcrop%26w%3D1000%26q%3D80`

### Parameters

| Parameter     | Necessity | Description                                                               | Default Value |
| ------------- | --------- | ------------------------------------------------------------------------- | ------------- |
| `username`    | Required  | Your GitHub username.                                                     | None          |
| `last_n_days` | Optional  | The n days to show on the chart. **0 < n < 365**                          | 7             |
| `img_url`     | Optional  | Background image. Use url encode tool like <https://www.urlencoder.org/>. | A Cat Image   |

<p align="right">(<a href="#top">back to top</a>)</p>

## Deploy Your Own Server

These are some instructions on setting up your project locally, just follow
these simple steps.

### Prerequisites

- [GNU Make](https://community.chocolatey.org/packages/make)

- [Go](https://go.dev/doc/install)

- [npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)

### Installation

1. Clone the repo.

   ```sh
   git clone https://github.com/ez4o/github-contribution-graph.git
   cd github-contribution-graph
   ```

2. Install npm packages.

   ```sh
   npm i
   ```

3. Install Go packages.

   ```sh
   go get -u
   ```

4. Fill in the [GitHub token](https://github.com/settings/tokens/new) inside the
   configuration.

   ```sh
   cp config.json.example config.json
   ```

### Generate Dist-SSR

1. Use release command, and it will generate `dist-ssr/` with a executable file
   inside.

   ```sh
   make release-windows
   ```

   or

   ```sh
   make release-linux
   ```

2. Get `dist-ssr/`, and you can deploy it anywhere!

> When execute, GitHub-Contribution-Graph will use port 8686 and 8687.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- ROADMAP -->

## Roadmap

- [x] Customize Background Image
- [x] CSS Animation (actually, it's a SMIL animation lol)
- [x] New Parameter: `last_n_days`
- [ ] More Patameters...

See the [open issues](https://github.com/ez4o/github-contribution-graph/issues)
for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## Contributing

Contributions are what make the open source community such an amazing place to
learn, inspire, and create. Any contributions you make are **greatly
appreciated**.

If you have a suggestion that would make this better, please fork the repo and
create a pull request. You can also simply open an issue with the tag
"enhancement". Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feat/amazing-feature`)
3. Commit your Changes with
   [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)
4. Push to the Branch (`git push origin feat/amazing-feature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- LICENSE -->

## License

Distributed under the MIT License. See
[LICENSE](https://github.com/ez4o/github-contribution-graph/blob/main/LICENSE)
for more information.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->

## Acknowledgments

- [Design Inspiration](https://plotparade.com/)
- [Background Image Used in Examples](https://unsplash.com/photos/NRQV-hBF10M)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTACT -->

## Contact

### Author

- HSING-HAN, WU (Xyphuz)
  - Mail me: xyphuzwu@gmail.com
  - About me: <https://about.xyphuz.com>
  - Github: <https://github.com/wst24365888>

### Project Link

- <https://github.com/ez4o/github-contribution-graph>

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/ez4o/github-contribution-graph.svg?style=for-the-badge
[contributors-url]: https://github.com/ez4o/github-contribution-graph/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/ez4o/github-contribution-graph.svg?style=for-the-badge
[forks-url]: https://github.com/ez4o/github-contribution-graph/network/members
[stars-shield]: https://img.shields.io/github/stars/ez4o/github-contribution-graph.svg?style=for-the-badge
[stars-url]: https://github.com/ez4o/github-contribution-graph/stargazers
[issues-shield]: https://img.shields.io/github/issues/ez4o/github-contribution-graph.svg?style=for-the-badge
[issues-url]: https://github.com/ez4o/github-contribution-graph/issues
[license-shield]: https://img.shields.io/github/license/ez4o/github-contribution-graph.svg?style=for-the-badge
[license-url]: https://github.com/ez4o/github-contribution-graph/blob/main/LICENSE
[product-screenshot]: https://github-contribution-graph.ez4o.com/?username=wst24365888&img_url=https%3A%2F%2Fimages.unsplash.com%2Fphoto-1506744038136-46273834b3fb%3Fixid%3DMnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8%26ixlib%3Drb-1.2.1%26auto%3Dformat%26fit%3Dcrop%26w%3D1000%26q%3D80&fbclid=IwAR1AUDKHzjzBSjKle6J44dYRSrIbvBu8eTxtrfhpPxhBnBsOizgSq63bYbU
