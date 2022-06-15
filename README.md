<div id="top"></div>

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
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <h3 align="center">FilmApp</h3>

  <p align="center">
    A film application to show a real application applying the [Jetpack Architecture](https://developer.android.com/jetpack).
    <br />
    <a href="https://github.com/HenestrosaConH/FilmApp/issues">Report Bug</a>
    ·
    <a href="https://github.com/HenestrosaConH/FilmApp/issues">Request Feature</a>
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
    </li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

[![Main Screen shot][main-screenshot]](https://github.com/HenestrosaConH/FilmApp)

As the description of the repository says, this is a project made with the Jetpack Architecture that makes use of libraries such as Room or Hilt.

The project structure is as follows:
 
- `databases`: All the files related to the Room database. Its `entities` subdirectory contains the data structure of the database entities. If the project had more tables, each table should have its respective package.
- `di`: Dependency injections modules. It only has one module that acts as a singleton component that provides the Room and Retrofit instances to the whole application.
- `mappers`: Contains the mappers that convert the DTO, Entity and model of each model.
- `models`: Holds the models of the application.
- `network`: All the code related to the Retrofit client. Its `dto` subdirectory contains the data structure of the JSON obtained. If the project needed more DTOs, each one should have its respective package.
- `repositories`: Contains the repositories that contains the code for operating with the database.
- `services`: Its files link the `network` layer with the `viewmodels` to retrieve the data.
- `ui`: Contains the application's views.
- `viewmodels`: It's the layer that connects the logic of the application with its respective view.
 
<p align="right">(<a href="#top">back to top</a>)</p>

<!-- BUILT WITH -->

### Built With

- [Jetpack Architecture](https://developer.android.com/jetpack)
- [Room](https://developer.android.com/jetpack/androidx/releases/room)
- [Hilt](https://developer.android.com/training/dependency-injection/hilt-android)
- [Retrofit 2](https://square.github.io/retrofit/)
- [Coroutines](https://kotlinlang.org/docs/coroutines-overview.html)
- [LiveData](https://developer.android.com/topic/libraries/architecture/livedata)
- [ViewBinding](https://developer.android.com/topic/libraries/view-binding)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->

## Getting Started

You just need to clone the project and open it with [Android Studio](https://developer.android.com/studio). Once you open it, you just need to execute it by pressing the shortcut <kbd>Shift</kbd> + <kbd>F10</kbd>.

<p align="right">(<a href="#top">back to top</a>)</p>

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

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTACT -->

## Contact

Author of this repository: henestrosaconh@gmail.com - [LinkedIn](https://www.linkedin.com/in/henestrosaconh/)

Project Link: [https://github.com/HenestrosaConH/FilmApp](https://github.com/HenestrosaConH/FilmApp)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->

## Acknowledgments

I've made use of the following repositories to make this README:

-   [Best-README-Template](https://github.com/othneildrew/Best-README-Template/)
-   [Img Shields](https://shields.io)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/HenestrosaConH/FilmApp.svg?style=for-the-badge
[contributors-url]: https://github.com/HenestrosaConH/FilmApp/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/HenestrosaConH/FilmApp.svg?style=for-the-badge
[forks-url]: https://github.com/HenestrosaConH/FilmApp/network/members
[stars-shield]: https://img.shields.io/github/stars/HenestrosaConH/FilmApp.svg?style=for-the-badge
[stars-url]: https://github.com/HenestrosaConH/FilmApp/stargazers
[issues-shield]: https://img.shields.io/github/issues/HenestrosaConH/FilmApp.svg?style=for-the-badge
[issues-url]: https://github.com/HenestrosaConH/FilmApp/issues
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/henestrosaconh
[main-screenshot]: readme-files/main.png
