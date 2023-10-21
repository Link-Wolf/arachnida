<div id="top"></div>

<div align="center">
 <a href="https://github.com/Link-Wolf/arachnida" title="Go to GitHub repo"><img src="https://img.shields.io/static/v1?label=Link-Wolf&message=arachnida&color=blue&logo=github&style=for-the-badge" alt="Link-Wolf - arachnida"></a>
 <a href="https://"><img src="https://img.shields.io/badge/42_grade-100_%2F_100-brightgreen?style=for-the-badge" alt="42 grade - 100 / 100"></a>
 <a href="https://"><img src="https://img.shields.io/badge/Year-2022-ffad9b?style=for-the-badge" alt="Year - 2022"></a>
 <a href="https://github.com/Link-Wolf/arachnida/stargazers"><img src="https://img.shields.io/github/stars/Link-Wolf/arachnida?style=for-the-badge&color=yellow" alt="stars - arachnida"></a>
 <a href="https://github.com/Link-Wolf/arachnida/network/members"><img src="https://img.shields.io/github/forks/Link-Wolf/arachnida?style=for-the-badge&color=lightgray" alt="forks - arachnida"></a>
 <a href="https://github.com/Link-Wolf/arachnida/issues"><img src="https://img.shields.io/github/issues/Link-Wolf/arachnida?style=for-the-badge&color=orange" alt="issues - arachnida"></a>
 <a href="https://www.apple.com/macos/" title="Go to Apple homepage"><img src="https://img.shields.io/badge/OS-macOS-blue?logo=apple&logoColor=white&style=for-the-badge&color=9cf" alt="OS - macOS"></a>
</div>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a>
    <img src="https://www.42mulhouse.fr/wp-content/uploads/2022/06/logo-42-Mulhouse-white.svg" alt="Logo" width="192" height="80">
  </a>

  <h3 align="center">Piscine Cybersecurity - Arachnida</h3>

  <p align="center">
   <em>spider..scorpion..or both</em><br/>
    A web scrapper that extract images and a metadata/ExIF extractor
    <br />
    <br />
    <a href="https://github.com/Link-Wolf/arachnida/issues">Report Bug</a>
    ·
    <a href="https://github.com/Link-Wolf/arachnida/issues">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#goal">Goal</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage-examples">Usage examples</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- GOAL -->
## Goal

<div align="center">
  <a>
	<img src="https://1zootree.weebly.com/uploads/2/4/2/5/24255946/spider-png37_orig.png" alt="arachnida">
  </a>
</div>
</br>

This cybersecurity project is composed by two differents executables.
The first one, spider, is a web scrapper that extract and download images (jpeg, png, gif and bpm) from a website, and is able to act recursively on the links found in the website.
The second one, scorpion, is an ExIF tool that extract metadata from images (jpeg, png, gif and bpm)
> Both are written using NodeJS and use a minimal amount of external libraries, the logic is mostly homemade.


<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started


### Prerequisites

- [NodeJS](https://nodejs.org/en/download/)


### Installation

1. Clone the repo

   ```sh
   $> git clone https://github.com/Link-Wolf/arachnida.git
   ```

2. Launch one of the two executables

	
   ```sh
   $> cd arachnida
   $> ./spider [-r] [-l level] [-p path] url
   ```
   > -r : recursive mode
   > -l : level of recursion
   > -p : path to save images
   > url : url to scrap
   ---
   ```sh
   $> cd arachnida
   $> ./scorpion FILE1 [FILE2 ...]
   ```
   > FILE : path to image

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->
## Usage examples

#### Spider

![spider](https://media.discordapp.net/attachments/907303542438629406/1129005675645775913/image.png?width=1353&height=166)

#### Scorpion

![scorpion](https://media.discordapp.net/attachments/907303542438629406/1129007322111414372/image.png?width=666&height=821)

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- CONTRIBUTING -->
## Contributing

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

Mail : xxxxxxx@student.42mulhouse.fr

Project Link: [https://github.com/Link-Wolf/arachnida](https://github.com/Link-Wolf/arachnida)

<p align="right">(<a href="#top">back to top</a>)</p>
