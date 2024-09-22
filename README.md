# Forex-DRL

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/your_username/repo_name">
    <img src="images/gators.jpg" alt="Logo" width="150" height="150">
  </a>

  <h3 align="center">Forex Algorithmic Trading with Deep Reinforcement Learning</h3>

  <p align="center">
    This project implements a Deep Q-Network (DQN) for algorithmic trading in the Forex market, inspired by the research paper "An Application of Deep Reinforcement Learning to Algorithmic Trading" by Thibaut Théate and Damien Ernst. The project aims to create a full-stack application utilizing machine learning, Python, and web technologies.
    <br />
    <a href="https://github.com/your_username/repo_name/docs.txt"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="#usage">View Demo</a>
    ·
    <a href="https://github.com/your_username/repo_name/issues">Report Bug</a>
    ·
    <a href="https://github.com/your_username/repo_name/issues">Request Feature</a>
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
        <li><a href="#dependencies">Dependencies</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#authors">Authors</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

This project is an ongoing implementation of a **Deep Reinforcement Learning** solution to solve algorithmic trading in the Forex market. It builds on the ideas presented in the research paper "[An Application of Deep Reinforcement Learning to Algorithmic Trading](https://arxiv.org/abs/2004.06627)" by Thibaut Théate and Damien Ernst. The objective is to implement a **Deep Q-Network (DQN)** that optimizes trading positions (buy, sell, hold) in a Forex market, leveraging historical Forex data for training the model. The project will grow over time to include more advanced features, such as real-time trading, data visualization, and predictive analytics.

The tools and frameworks used in this project include:
- **PyTorch** for machine learning and deep reinforcement learning
- **Django** for backend web development and API creation
- **React** for frontend user interface
- **MongoDB** for database management
- **Oanda** for accessing live Forex market data
- **Machine Learning** for advanced financial forecasting

### Built With
* [PyTorch](https://pytorch.org/)
* [Django](https://www.djangoproject.com/)
* [React](https://reactjs.org/)
* [MongoDB](https://www.mongodb.com/)
* [OANDA API](https://www.oanda.com/)
* [Django Rest Framework](https://www.django-rest-framework.org/)

<!-- GETTING STARTED -->
## Getting Started

This section provides instructions for setting up and running the project locally. The instructions assume you have Python, Node.js, and MongoDB installed on your system.

### Dependencies

Below are the dependencies required to run this project:
- **Python 3.8+**
- **Django 4.0+**
- **PyTorch 1.9+**
- **Node.js 14+**
- **MongoDB**

Here are the specific libraries and how to install them:

* Django
  ```sh
  pip install django
  ```
* Django Rest Framework
  ```sh
  pip install djangorestframework
  ```
* PyTorch
  ```sh
  pip install torch torchvision torchaudio
  ```
* MongoDB Python Driver (PyMongo)
  ```sh
  pip install pymongo
  ```
* Axios (for API calls in React)
  ```sh
  npm install axios
  ```

### Alternative: Export your Environment

Alternatively, you can export your Python environment to a `requirements.txt` file for easy setup by others:

```sh
pip freeze > requirements.txt
```

To install dependencies using the `requirements.txt` file:

```sh
pip install -r requirements.txt
```

### Installation

To get a local copy up and running, follow these simple steps:

1. Clone the repository
   ```sh
   git clone https://github.com/your_username/repo_name.git
   ```
2. Install Python packages
   ```sh
   pip install -r requirements.txt
   ```
3. Install Node.js dependencies for the React frontend
   ```sh
   cd frontend
   npm install
   ```
4. Run the backend Django server:
   ```sh
   python manage.py runserver
   ```
5. Run the React frontend:
   ```sh
   npm start
   ```



<!-- ROADMAP -->
## Roadmap

Current roadmap includes the following milestones:
- [ ] Implement full DQN model with historical Forex data
- [ ] Integrate real-time data feed via Oanda API
- [ ] Develop interactive data visualizations (Plotly, D3.js)
- [ ] Implement MongoDB for storing trading history and model logs
- [ ] Build out user authentication and secure APIs with Django
- [ ] Add live trading bot functionality for Forex using Oanda

See the [open issues](https://github.com/your_username/repo_name/issues) for a list of proposed features (and known issues).



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.

<!-- Authors -->
## Authors

Harishawn Ramrup - [@your_twitter](https://twitter.com/your_username) - ramrupshawn@gmail.com

Project Link: [https://github.com/ramruph/Forex-DRL/]([https://github.com/ramruph/Forex-DRL/])

<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* [An Application of Deep Reinforcement Learning to Algorithmic Trading](https://arxiv.org/abs/2004.06627)
* [PyTorch Documentation](https://pytorch.org/docs/)
* [Django Documentation](https://docs.djangoproject.com/en/stable/)
* [Oanda API Documentation](https://developer.oanda.com/rest-live-v20/introduction/)


