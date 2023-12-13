# Selenium Testing for Word Corners Game

This project contains Selenium tests for the Word Corners game.

## Table of Contents

- [Overview](#overview)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Running the Tests](#running-the-tests)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project aims to automate testing for the Word Corners game using Selenium. The tests are designed to cover various interactions with the game, ensuring its functionality.

## Project Structure

- `.github/workflows/selenium_test.yml`: GitHub Actions workflow file for running Selenium tests.
- `selenium_tests/test_script.py`: Selenium test script written in Python.
- `requirements.txt`: List of Python dependencies.

## Getting Started

### Prerequisites

Make sure you have the following installed on your system:

- [Python](https://www.python.org/downloads/) (version 3.x)
- [ChromeDriver](https://sites.google.com/chromium.org/driver/) executable

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/aliyaghmaie/GithubActionDemo1
   cd your-repository
## Running the Tests

- python selenium_tests/test_script.py

## Download ChromeDriver and set the PATH environment variable.

- mkdir -p $HOME/drivers
curl -L https://chromedriver.storage.googleapis.com/$(curl -s https://chromedriver.storage.googleapis.com/LATEST_RELEASE)/chromedriver_win32.zip -o $HOME/drivers/chromedriver_win32.zip
unzip -o $HOME/drivers/chromedriver_win32.zip -d $HOME/drivers
echo "C:\\Users\\your-username\\drivers" >> $GITHUB_PATH
