## CANDIDBOT

<div align="center", width="75%">
   ![candidbot](https://github.com/Umesh8878/candidbot/assets/115473268/8c49230c-e0c1-4830-8deb-930ef3fdd265)
</div>div>

## Overview

The **CANDIDBOT** is a Java-based Spring Boot application designed to automate the interview process by generating interview questions, capturing candidate responses, and evaluating candidates using OpenAI's GPT-3 model. This application can be used for both mock interviews (using predefined questions and answers) and real interviews (capturing live candidate responses).

## Features

- Conduct automated interviews with candidates.
- Choose between mock interview mode and real interview mode.
- Randomize questions for interviews.
- Limit the number of questions asked.
- Automatically evaluate candidate responses using OpenAI's GPT-3 model.
- Provides text-to-speech functionality for communication.
- Flexible configuration options.

![247566147-21715a66-a8aa-47aa-82f1-69220fbe876a](https://github.com/Umesh8878/candidbot/assets/115473268/b7fa0bbd-3316-4114-93d2-b5220acb40c7)


## Getting Started

To get started with the Interview Automation Application, follow these steps:

## Prerequisites

- Java Development Kit (JDK) installed on your system.
- Maven build tool for building the application.
- OpenAI API credentials (API key) for using the GPT-3 model.
- Speech synthesis engine (e.g., `TextToSpeech`) set up for audio communication.

## Installation

1. Clone this repository to your local machine.
   
    git clone (https://github.com/Umesh8878/candidbot)

1. Navigate to the project directory:

    cd interview-automation

2. Configure your OpenAI API credentials by setting the `openai.api.key` in `application.properties` or using environment variables.

3. Build the application using Maven:

    mvn clean install

4. Run the application:

    mvn spring-boot:run

## Usage

1. Access the application by opening a web browser and navigating to http://localhost:8080/openai/v1/interview.

2. Follow the on-screen instructions to configure interview modes, start interviews, and evaluate candidates.

3. Provide the interview transcript when prompted for evaluation.

4. View the candidate's evaluation generated by the GPT-3 model.

## Configuration

You can customize the behavior of the Interview Automation Application by modifying the configuration files, such as `application.properties`. Here are some important configuration options:

- `openai.api.key`: Your OpenAI API key for accessing the GPT-3 model.
- `openai.model`: The GPT-3 model to use for evaluation.
- `openai.api.url`: The API endpoint for the OpenAI service.
- Other configuration options for interview modes, paths to question files, and more.

## Acknowledgments

- This application leverages the OpenAI GPT-3 model for automated candidate evaluation.
- Special thanks to the developers and contributors who made this project possible.

## Contact
For questions or inquiries about this application, please contact us.

## Thank You!
