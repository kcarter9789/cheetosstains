# SVG Logo Generator

A Node.js command-line application for generating logos and saving them as SVG files.

## Table of Contents

- [SVG Logo Generator](#svg-logo-generator)
  - [Table of Contents](#table-of-contents)
  - [Description](#description)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Walkthrough Video](#walkthrough-video)
  - [License](#license)
  - [Output](#output)
    - [Logo](#logo)
    - [Triangle](#triangle)
    - [Circle](#circle)
    - [Square](#square)

## Description

As a freelance web developer, you want to be able to generate simple logos for your projects without having to pay a graphic designer. This command-line application allows you to do just that! You will be prompted to enter text (up to three characters), text color, shape (choose from a list of Triangle, Circle, or Square), and shape color. Once you have entered your input, the application will generate an SVG logo and save it as a file named "logo.svg".

This application uses Jest for unit testing and Inquirer for collecting user input. It includes Shape classes for Triangle, Circle, and Square, as well as tests for each of these classes. It also includes a class for handling user input, a class for generating the logo, and tests for both of these classes.

## Installation

To install this application, you will need to have Node.js and npm installed on your computer. Clone this repository and run the following command in your terminal:

```sh
npm install
```

This will install the necessary dependencies (Jest and Inquirer).

## Usage

To use this application, run the following command in your terminal:
```sh
node index.js
```

You will then be prompted to enter text, text color, shape, and shape color. Once you have entered your input, the application will generate an SVG logo and save it as a file named "logo.svg" in the same directory as the application.

## Walkthrough Video

[Here](./svg%20logo%20generator.mp4) is a walkthrough video that demonstrates the functionality of this application and passes all tests.

## License

This project is licensed under the MIT license.

## Output
### Logo 
![`logo`](logo.svg)

### Triangle
![`trianle`](examples/triangle.svg)

### Circle
![`circle`](examples/circle.svg)

### Square
![`square`](examples/square.svg)