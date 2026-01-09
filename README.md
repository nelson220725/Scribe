<a name="readme-top"></a>
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/AndrewCheung360/Scribe">
    <img src="https://github.com/AndrewCheung360/HackChallengeSP24/assets/67351739/bd1d5da6-452c-487f-a8e0-d05457850133" alt="Logo" width="250" height="250">
  </a>

<h1 align="center">Scribe</h1>

  <p align="center">
    Collaborative note-sharing for student success.
    <br />
    <a href="https://github.com/AndrewCheung360/Scribe"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/AndrewCheung360/Scribe">View Demo</a>
    ·
    <a href="https://github.com/AndrewCheung360/Scribe/issues/new?labels=bug&template=bug-report---.md">Report Bug</a>
    ·
    <a href="https://github.com/AndrewCheung360/Scribe/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a>
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
    <li><a href="#authors">Authors</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
# About The Project

## Scribe
### Missed Class? Forgot to make a study guide? Don't Worry! Get notes for all your classes with Scribe!

Cornell App Dev Hack Challenge Spring 2024

## Description
Scribe is a mobile application designed to revolutionize the way students share and access lecture notes and study guides. Whether you're looking to catch up on missed lectures or enhance your understanding with supplementary materials, Scribe has you covered. Join Scribe today and embark on a journey of collaborative learning and academic excellence!
## Screenshots

<p align="center">
  <img src="https://github.com/AndrewCheung360/Scribe/assets/67351739/6344c9c4-98eb-40cf-897a-7992f414a19e" width="200" alt="Sign In Screen"/>
  <img src="https://github.com/AndrewCheung360/Scribe/assets/67351739/f1b01e87-5540-4c2a-b5d1-385eb7a4ae16" width="200" alt="Course Selection"/>
  <img src="https://github.com/AndrewCheung360/Scribe/assets/67351739/84b59956-a3e2-4a92-8703-40ad68f12f3c" width="200" alt="Home Screen"/>
</p>

<p align="center">
  <img src="https://github.com/AndrewCheung360/Scribe/assets/67351739/85235d09-7c8b-4f7f-ac48-0654e4530684" width="200" alt="Course Notes"/>
  <img src="https://github.com/AndrewCheung360/Scribe/assets/67351739/7f844580-ce61-40b2-adc6-40feffbfbed1" width="200" alt="Note Viewer"/>
  <img src="https://github.com/AndrewCheung360/Scribe/assets/67351739/d46901a3-9582-4b68-949f-54ec00708e82" width="200" alt="Profile Screen"/>
</p>
 


## Key Features
Scribe is an Android app that allows Cornell students to share and view notes that others have made for their classes. When users log into the app, they select the courses that they are taking. For each course, users can view the notes uploaded by other users taking the same course. Users can also upload their own notes as pdfs to a class they're enrolled in. 












<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* ![Kotlin](https://img.shields.io/badge/kotlin-%237F52FF.svg?style=for-the-badge&logo=kotlin&logoColor=white)
* ![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white)
* ![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
* ![Supabase](https://img.shields.io/badge/Supabase-181818?style=for-the-badge&logo=supabase&logoColor=white)
* ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Getting Started

To get a local copy up and running, follow these steps.

### Prerequisites

- Android Studio (latest version recommended)
- JDK 8 or higher
- Android SDK with minimum API level 24
- A device or emulator running Android 7.0 (Nougato) or higher

### Installation

1. Clone the repository
   ```sh
   git clone https://github.com/AndrewCheung360/Scribe.git
   ```

2. Open the project in Android Studio
   - Select "Open an Existing Project"
   - Navigate to the cloned repository folder

3. Configure your Google OAuth credentials
   - Create a project in the [Google Cloud Console](https://console.cloud.google.com/)
   - Enable the Google Sign-In API
   - Add your OAuth 2.0 Client ID to the project

4. Sync the project with Gradle files
   - Android Studio should prompt you to sync automatically
   - If not, click "File" > "Sync Project with Gradle Files"

5. Build and run the project
   - Connect an Android device or start an emulator
   - Click the "Run" button or press Shift+F10

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Usage

1. **Sign In**: Launch the app and sign in with your Google account
2. **Add Courses**: Search for and add the courses you're enrolled in
3. **Browse Notes**: Tap on any course to view notes shared by other students
4. **Upload Notes**: Share your own notes by uploading PDF files to your courses
5. **View Profile**: Access your uploaded notes and manage your account from the profile screen

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Future Features
- [ ] **Comments and likes for notes**: Share your thoughts on others user's notes!
- [ ] **Starred Notes**: Save your favorite notes for later!
- [ ] **Note tags**: Sort your notes by lecture, prelim, study guide, etc
- [ ]  **User Karma**: Discover who's the best note-taker!

See the [open issues](https://github.com/AndrewCheung360/Scribe/issues) for a full list of proposed features (and known issues).

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



<!-- AUTHORS -->
## Authors

- **Nelson Zhang**
- **Andrew Cheung**
- **James Tu**
- **Edward Lee**

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Project Link: [https://github.com/AndrewCheung360/Scribe](https://github.com/AndrewCheung360/Scribe)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

This project was created for Cornell App Dev Hack Challenge Spring 2024.

* [Jetpack Compose](https://developer.android.com/jetpack/compose)
* [Supabase](https://supabase.com/)
* [Ktor Client](https://ktor.io/docs/client.html)
* [Best README Template](https://github.com/othneildrew/Best-README-Template)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[Kotlin]: (https://img.shields.io/badge/kotlin-%237F52FF.svg?style=for-the-badge&logo=kotlin&logoColor=white)
[contributors-shield]: https://img.shields.io/github/contributors/AndrewCheung360/Scribe.svg?style=for-the-badge
[contributors-url]: https://github.com/AndrewCheung360/Scribe/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/AndrewCheung360/Scribe.svg?style=for-the-badge
[forks-url]: https://github.com/AndrewCheung360/Scribe/network/members
[stars-shield]: https://img.shields.io/github/stars/AndrewCheung360/Scribe.svg?style=for-the-badge
[stars-url]: https://github.com/AndrewCheung360/Scribe/stargazers
[issues-shield]: https://img.shields.io/github/issues/AndrewCheung360/Scribe.svg?style=for-the-badge
[issues-url]: https://github.com/AndrewCheung360/Scribe/issues
[license-shield]: https://img.shields.io/github/license/AndrewCheung360/Scribe.svg?style=for-the-badge
[license-url]: https://github.com/AndrewCheung360/Scribe/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/linkedin_username
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
