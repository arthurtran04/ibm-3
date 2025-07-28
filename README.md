<div align="center"><h1>🎤 Voice Assistant</h1></div>

## Introduction



## Table of Contents

- [Introduction](#introduction)
- [Prerequirements](#prerequirements)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Prerequirements

- Skills Network Labs

## Features



## Installation

To run this project on Skills Network Labs, open the Terminal and follow these steps:

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

<div align="center"><img width="600rem" alt="Webpage" src="https://github.com/user-attachments/assets/afaef88c-98fc-4c04-bf54-29f9cd4e2d91" /></div>

You can choose the character voice you like, then use your voice to ask questions. The assistant will respond in the voice of the character you chose:

<div align="center"><img width="600rem" alt="Example" src="https://github.com/user-attachments/assets/6fa5d8df-d5ca-4d17-969b-09fd847f5f39" /></div>

To stop the application, use `Ctrl + C` in the Terminal

## License

This project is licensed under the Apache-2.0 License. See the LICENSE file for more details.
