
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Issues][issues-shield]][issues-url]
<!-- [![LinkedIn][linkedin-shield]][linkedin-url] -->



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/Jalenleeruixian/NaviUS">
    <img src="images/logo.png" alt="Logo" width="384" height="216">
  </a>

<h3 align="center">NaviUS</h3>

  <p align="center">
    An interactive map for navigating NUS.
    <br />
    <a href="https://github.com/Jalenleeruixian/NaviUS"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/Jalenleeruixian/NaviUS">View Demo</a>
    ·
    <a href="https://github.com/Jalenleeruixian/NaviUS/issues/new?labels=bug&template=bug-report---.md">Report Bug</a>
    ·
    <a href="https://github.com/Jalenleeruixian/NaviUS/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
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
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

<!-- [![Product Name Screen Shot][product-screenshot]](https://example.com) -->

[Project Log](https://docs.google.com/spreadsheets/d/1bgl3p2TIc0YedqllvQV6E8wuXQSjLSq92cmZrmw-2sE/edit#gid=0)

As NUS students ourselves, we frequently rely on the various apps that are currently available to us, such as Google Maps, NUS NextBus and NUSMods for when we need to find our way around school. However, it always feels like these apps alone are not enough to fulfil all of our needs, and something more can be done to address the problem of navigating NUS. For example, NUS NextBus provides us with bus timings, but does not provide an interactive point-to-point guide to direct us from place to place.

Our app hopes to provide detailed information of the entire NUS campus, from its classrooms and lecture halls to its canteens. Think of Google Maps, but for NUS. Students and staff alike will be able to customise their apps to keep track of their most frequented locations and provide the fastest possible route to get from Point A to Point B. We hope that our app can be a all-in-one platform for anyone in NUS, be they students, staff or visitors.

We initially intended to create a website, much like NUSMods. But upon further consideration, we realised that a mobile app would be much more suited for the functionalilty of our idea. A mobile app will be much more convenient, especially for users, to customise their own accounts and for frequent usage when it comes to checking of bus timings and to keep track of their live location. We have decided to narrow down our initial development to support iOS, and have the possibility of extending support to Android in the future. Focusing on just iOS will allow us to dedicate our efforts to maximising the features and testing the feasibility of our app, rather than being caught up in trying to develop for two operating systems at the same time. Therefore, we have chosen iOS as the platform that our app will run on.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* [![Swift][swift.org]][swift-url]
* [![Firebase][firebase.google.com]][firebase-url]


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

Follow these steps to setup and run our code.

### Prerequisites
For MacOS:
* Install [XCode](https://apps.apple.com/us/app/xcode/id497799835?mt=12). It should come with a Simulator application that allows you to run .app files. Click on [this link](https://developer.apple.com/documentation/xcode/installing-additional-simulator-runtimes) if additional help is needed for downloading Simulator.

### Installation

For MacOS:
  1. Head to [Releases](https://github.com/Jalenleeruixian/NaviUS/releases) and download the latest version available.
  2. Run the Simulator application attached with XCode.
  3. Extract NaviUS.app from the zip file and drag it into the iOS device simulated by Simulator.
<!-- 1. Get a free API Key at 
2. Clone the repo
   ```sh
   git clone https://github.com/Jalenleeruixian/NaviUS.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```js
   const API_KEY = 'ENTER YOUR API';
   ``` -->

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [ ] **Core Feature 1:** Map showing location of classrooms, LTs, labs etc.
- [ ] **Core Feature 2:** Directions to specific location including bus routes and estimated time needed.
- [ ] **Core Feature 3:** Allow users to sign in and save their classes for the semester to easily locate their next class on various platforms.
- [ ] **Extension 1:** Create a multi-storey directory for each building detailing the positions of classrooms, lecture theatres, toilets etc.
- [ ] **Extension 2:** Provide options of different routes to users (sheltered routes when raining, bus/cycle when time is priority).
- [ ] **Extension 3:** Link to NUS NextBus to better estimate time needed.
- [ ] **Extension 4:** Provide a review system to allow students to give feedback , e.g. F&B reviews.
- [ ] **Extension 5:** Link to NUSMods to allow students to see scheduled lessons in each classroom / search for specific mods to see where the classes are.

See the [open issues](https://github.com/Jalenleeruixian/NaviUS/issues) for a full list of proposed features (and known issues).

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
<!-- ## License 

<p align="right">(<a href="#readme-top">back to top</a>)</p> -->



<!-- CONTACT -->
## Contact

Zhao Wenrui - e1122418@u.nus.edu
Jalen Lee - e1122262@u.nus.edu

Project Link: [https://github.com/Jalenleeruixian/NaviUS](https://github.com/Jalenleeruixian/NaviUS)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* []()
* []()
* []()

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/Jalenleeruixian/NaviUS.svg?style=for-the-badge
[contributors-url]: https://github.com/Jalenleeruixian/NaviUS/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Jalenleeruixian/NaviUS.svg?style=for-the-badge
[forks-url]: https://github.com/Jalenleeruixian/NaviUS/network/members
[issues-shield]: https://img.shields.io/github/issues/Jalenleeruixian/NaviUS.svg?style=for-the-badge
[issues-url]: https://github.com/Jalenleeruixian/NaviUS/issues
[product-screenshot]: images/screenshot.png
[swift.org]: https://img.shields.io/badge/swift-9BB5CE?style=for-the-badge&logo=swift&logoColor=white
[swift-url]: https://swift.org
[firebase.google.com]: https://img.shields.io/badge/firebase-F5820D?style=for-the-badge&logo=firebase&logoColor=white
[firebase-url]: https://firebase.google.com

