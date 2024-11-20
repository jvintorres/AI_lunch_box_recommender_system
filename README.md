# Your Local Grocery Guide - On Demand by Text 

Push-to-text updates on your local grocery store's weekly deals and recipes 

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/cajjster/lunch_box_planner.svg)](https://github.com/cajjster/lunch_box_planner/stargazers)
[![Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://your-live-demo-link.com)

---

## Table of Contents

1. [About the Project](#about-the-project)
2. [Getting Started](#getting-started)
3. [Usage](#usage)
4. [Features](#features)
5. [Contributing](#contributing)
6. [License](#license)
7. [Acknowledgments](#acknowledgments)

---

## About the Project

Briefly explain:
- A useful way to view weekly deals from your local grocer by text 
- Read through weekly recipes and associated shopping lists in a concise text file

### Screenshots

Include relevant screenshots or a demo GIF:

![Screenshot of the project]([https://via.placeholder.com/800x400](https://thumbs.dreamstime.com/z/man-mobile-phone-grocery-paper-bag-portrait-happy-male-customer-store-36510379.jpg?ct=jpeg))

---

## Getting Started

1. Scrape your local grocery store

### Prerequisites

List tools and dependencies needed:
- Python 3.10+
- Twilio
- Open AI 

### Installation

Provide clear installation steps:

```bash
# Clone the repository
git clone https://github.com/yourusername/recommendations.git

# Navigate to the project directory
cd recommmendations

# Install dependencies

_In your terminal... _
 pip install
 pipenv install bs4
 pip install python-dotenv

# Activate the virtual environment (env)
pipenv shell

_In your project's working environment, install the libraries from below
_

# Assign your global variables (url, client, and client_twilio)

- You're your own client! 

- 1. Copy the page of your grocery store's deals and save that to a variable **"url"**
- 2. Assign your API key created from your OpenAI account into a variable **"client"**
- 3. Finally, your client username and token from Twilio must be saved and added into a variable **"client_twilio"**

Open AI: https://platform.openai.com/api-keys
Twilio: https://console.twilio.com/?frameUrl=/console 

# Scrape your local grocery store
- read the preview code for ways to...

 1. create a method to bypass a cookie-selector option with one click
 2. scroll to the bottom of a page
 3. generate a beautiful (and tasty) soup with the key from your website 
    - container method
 4. send a text to yourself with the number created on Twilio
    - via a user defined function 
 5. create a chat gpt bot

```

# Libraries
from selenium import webdriver
from selenium.webdriver.common.by import By
from selenium.webdriver.support.ui import WebDriverWait
import requests 
from bs4 import BeautifulSoup
from openai import OpenAI
from twilio.rest import Client
import os
from dotenv import load_dotenv

## Features

Highlight key features:

- 📊 Concise texts 
- ⚡ Push-to-text updates
- 🔐 Secure authentication
- 🌍 Localized content 

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/new-feature`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature/new-feature`).
5. Open a pull request.

Refer to [CONTRIBUTING.md](CONTRIBUTING.md) for detailed guidelines.

---

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Acknowledgments

Nod Coding Bootcamp 
