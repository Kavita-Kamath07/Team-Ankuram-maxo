<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/Karthik-Shenoy/Team-Ankuram-maxo/blob/main/README.md">
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Python-logo-notext.svg/768px-Python-logo-notext.svg.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Team-Ankuram</h3>

  <p align="center">
    A website to enhance your coding and aptitude abilities
    <br />
    <a href="https://github.com/Karthik-Shenoy/Team-Ankuram-maxo/blob/main/README.md"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/Karthik-Shenoy/Team-Ankuram-maxo/blob/main/README.md">View Demo</a>
    ·
    <a href="https://github.com/Karthik-Shenoy/Team-Ankuram-maxo/issues">Report Bug</a>
    ·
    <a href="https://github.com/Karthik-Shenoy/Team-Ankuram-maxo/issues">Request Feature</a>
  </p>
</p>

<!-- TABLE OF CONTENTS -->
<details open="open">
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
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

Hello, welcome to Abc. Extremely glad you’re here. Have you ever been frustrated/discouraged while looking out for a bunch of aptitude questions? Were the level of questions not able to meet your expectations? Ever felt the need of an associate to discuss and clear your doubts? This portal has been designed to guide you through this strenuous journey and pave an easier path for the destination.

### Built With
[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

<a href="http://www.djangoproject.com/"><img src="https://www.djangoproject.com/m/img/badges/djangopowered126x54.gif" border="0" alt="Powered by Django." title="Powered by Django." /></a>

* [Bootstrap](https://getbootstrap.com)
* HTML
* CSS
* [Python](https://www.python.org/downloads/)
* [Django](https://www.djangoproject.com/)

<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

1. Fork and Clone
    <ol>
    <li>Fork sushiksha-website the Repo</li>
    <li>Clone the repo to you computer.</li>
    </ol>

2. Create a Virtual Environment for the Project

    In Windows
    ```bash
    python -m venv venv
    
    venv\Scripts\activate
    ```

    In Ubuntu/MacOS
    ```bash
    python -m virtualenv venv
    
    source venv/bin/activate
    ```
   
   If you are giving a different name then `venv`, then please mention it in `.gitigonre` first
   
   3. Install all the requirements

    ```bash
    pip install -r requirements.txt
    ```
   
   ### Installation
   


  4. Checkout to develop branch
       ```git
      git status
      git pull
      git branch
      git checkout develop
      ```

  5. Create a `setting.py` in `sushiksha-website/djangoProject/`

      Copy paste the code from below document to `settings.py`

      settings.py

      Change the config parameters,
      ```python

     SECRET_KEY = 'Enter random character string'
     EMAIL_USER = 'your email username'
     EMAIL_PASS = 'Enter you email password'

      ```

  6. Make migrations/ Create db.sqlite3

      ```bash
      python manage.py makemigrations
      python manage.py migrate
      ```
  7. Create a super user.
      In django if you want to access admin page, you need to create an account first.
      ```djangotemplate
      python manage.py createsuperuser
      ```
     Then select your username and password.

  8. Run server
      ```bash
      python manage.py runserver
      ```
