# Read-Me-Generator
README.md Generator

* Checking Off: 

THEN this information is added to the sections of the README entitled Description, Installation, Usage, Contributing, and Tests
WHEN I choose a license for my application from a list of options
THEN a badge for that license is added near the top of the README and a notice is added to the section of the README entitled License that explains which license the application is covered under
WHEN I enter my GitHub username
THEN this is added to the section of the README entitled Questions, with a link to my GitHub profile
WHEN I enter my email address
THEN this is added to the section of the README entitled Questions, with instructions on how to reach me with additional questions
WHEN I click on the links in the Table of Contents
THEN I am taken to the corresponding section of the README



* Needs Work

# README.md Generator 

## Description

This code will prompt the user for the usual README sections and generate a README.md file for their project. The generated README will be able to include emojis, a table of contents (TOC), and proper formatting. It supports multiple screenshots, which must be located in either the /assets/images or src/assets/images folder of the project. The README.md file is assumed to be output or manually moved to the root of the project's directory. The output location for the README.md can be selected using inquirer-select-directory and placed anywhere on the user's machine.

* Edit
Now with support for adding tech badges. 

* This README.md was created using this program, and therefore I have my screenshots in the /assets/images folder.


## Table of Contents 📖

- [Installation](#Installation)

- [Usage](#usage)

* [Issues](#known-issues)

* [Contributing](#how-to-contribute)

* [Tests](#tests)

* [Credits](#credits)

* [Questions](#questions)

## Installation

To install necessary dependencies, run the following command:

```
npm i
```

## Usage

After you clone the repo, install using "npm i" and update the default email to your own. Then you will be able to run this CLI using the command.

```
readme
```

You can run this code from any directory on your computer. The code will ask for the output directory, starting from the level you are currently running the 'readme' command from. It assumes your terminal is open to your project's root directory and you want your README in the root. You may navigate up and down directories as needed to select a different location for the README.md file.

### Deployed Link

CLI only.

### Screenshots

* Add Sreenshots...

_____________________________________________________________________
* ## Known Issues

Currently there are only two directories to choose from for where the images are located in your app.
'assets/images'  or 
'src/assets/images'  

There is no validation on input yet!

## How To Contribute

Fork the repository and make a pull request with your new code.


## Tests

To run tests, run the following command:
```
No tests at this time.
```


## Credits

This project uses 2 npm packages:

[inquirer](https://www.npmjs.com/package/inquirer)

[inquirer-select-directory](https://classic.yarnpkg.com/en/package/inquirer-select-directory)



## Questions

If you have any questions about the repository or opt for contributing to improvemnet please don't hesitate to open an issue or contact me directly at ChelseaJarvis3301@icloud.com


