# Voice Assistant

## Introduction



## Table of Contents

- [Introduction](#introduction)
- [Prerequirements](#prerequirements)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Prerequirements

- IBM Cloud IDE
- IBM Watson NLP Library
- OpenAI account

## Features



## Installation

To run this project on IBM Cloud IDE, open the Terminal and follow these steps:

1. Clone the repository:

    ```sh
    $ git clone https://github.com/arthurtran04/ibm-voice-assistant.git
    ```

2. Install the required dependencies:

    ```sh
    $ pip install -r requirements.txt
    ```

## Usage

To start the Flask application, run the `cd` command to change the directory to `ibm-voice-assistant` and run the Dockerfile:

   ```sh
   $ cd ./ibm-voice-assistant
   docker build . -t voice-chatapp-powered-by-openai
   docker run -p 8000:8000 voice-chatapp-powered-by-openai
   ```
In the Skills Network Toolkit, launch your application at the port `8000`:

<img width="600rem" alt="Webpage" src="" />

To stop the application, use `Ctrl + C` in the Terminal

## License

This project is licensed under the Apache-2.0 License. See the LICENSE file for more details.
