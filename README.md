# Graze

[![image](https://github.com/pointySphere/graze/assets/140008493/5e501de4-8693-449f-a967-f6959f8cf54b)](https://ridgehacks-2024.devpost.com/)

> [!IMPORTANT]  
> **🥈 Graze won 2nd place overall at [RidgeHacks 2024](https://ridgehacks.us/), earning the developer team around $300-$500**

Devpost: https://devpost.com/software/graze

## A visually appealing database for you to share your art!

Graze is a web-based art database that allows you to upload your own art or just any image file you find important! This project contains HTML, CSS, and Flask files, along with an "images" folder that holds various images. In this README, we will guide both newcomers and experienced developers through the key aspects of this project.

This project is made for RidgeHacks 2024 by **Tharun Naguleswaran, Dhruv Rakhade, and Alex Sheng**. Special thanks to Calum Dingwall for recording our video.

## Table of Contents
- [Graze](#graze)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
    - [Key Features](#key-features)
  - [Getting Started](#getting-started)
  - [Usage](#usage)
  - [Customization](#customization)

## Introduction

Graze is a simple yet powerful tool that enables users to upload art files and instantly see their images online. Whether you are a art enthusiast, a student, or a developer looking to learn and experiment with Flask, this project offers something for everyone.

### Key Features

- Uploading files
- A user-friendly web interface
- Real-time file updates
- A modern and sleek signup and login page
- Beautifully curated user interface

## Getting Started

To start using Graze, follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/graze.git

2. Open the project directory:

    ```bash
    cd graze

3. Run the command

  ```bash
  flask --app app run
  ```

4. Open the URL given by Flask to access the website, or just open https://grazeart.xyz in your browser.

5. Follow the instructions on the website.

## Usage
For Newbies
If you're new to web development or just want to use the application, here's a simple guide:

Open the file uploader by following the "Getting Started" steps.

1. You'll see an input field labeled "Upload." Enter your files here. For example, you can upload dhruvrakhadeforpresident.png to get a stunning image of Dhruv!
2. Press the "Upload" button, and the file will appear on the internet.

Experiment with different files and see how the database changes in real-time.

## Customization
Experienced developers may want to customize the project further. You can modify the code to change the appearance of the homepage, add additional features, or integrate it into other web applications.

- The Flask code for this project can be found in the app.py file. We also use jQuery for sleek JavaScript operations.

- The code listens for form submissions using jQuery. When the form is submitted, it retrieves the file from the user's computer, and uploads it into our safe and secure database.

Happy coding! 💻
