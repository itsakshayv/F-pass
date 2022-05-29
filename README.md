<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#compatible-platforms">Compatible Platforms</a></li>
      </ul>
    </li>
    <li>
      <ul>
      <a href="#getting-started">Getting Started</a>
</li>
       <ul>
        <li><a href="#login">Registration</a></li>
        <li><a href="#chat-window">Login</a></li>
        </ul>

  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project
   2FA, is an extra layer of protection used to ensure the security of online accounts beyond just a username and password
  
  As of today, we use mobile number, email id, mobile apps, RSA tokens, ping Id, etc.  for 2 factor authentication. A rather simple way to authenticate is by using facial recognition which I have implemented as a MVP. Though this saves only few seconds, this comes in handy especially in the digital world where ever second counts.

* Design phase: •Research about the various libraries that can be used for facial recognition and suitable programming language to use the library with.
•Pros and cons of using biometrics as a second factor authentication method.
•A minimum viable product for the login which is a dashboard with login, face set up and home pages

* Development Phase :Python language is selected as it blends well for deep learning/machine learning libraries
Flask is a light weight python based framework which effectively renders html pages. Hence it has been leveraged to render as well as authenticate the facial images.


* Testing/Documentation: The app is tested with negative as well as edge cases to make sure it doesn’t abruptly err out.
Errors are properly handled with readable alerts thrown to the user




### Compatible Platforms
Laptops, Desktops and Tablet PCs








<!-- INSTALLATIONS -->

## Getting Started
To install and run the project on your local system, following are the requirements:
### Prerequisites
Install python 3.8 or less as higher versions need visual studio c++ to install dlib packages.
```sh
  pip install FLASK
  pip install requests
  pip install cmake
  pip install dlib
  pip install face_recognition
```
<!-- APP TUTORIAL-->
## Navigating Through The App
### Registration
First Register by creating a new username and password.After Registration Set Up your F-pass (it is compulsory).make sure that your are in Good Lighting Condition for better Results 

### Login

After setting your F-pass,you can login into App using your username , password and F-pass As 2FA







