# Hi there, I'm Jérémy Olivier 👋

## 🌱 About Me
- **Working On:** XAI with SHAP.
- **Interests:** Data science and machine learning.
- **Location:** Lausanne, part of the Groupe Mutuel team.

## 🔭 My Projects
- [**42Lausanne:**](https://github.com/jreivilo/42Lausanne) Comprehensive project from Piscine to Transcendence in C/C++ and more...
- [**Deep Neural Network for Bitcoin Price Prediction with Tweet Sentiment Analysis:**](https://github.com/jreivilo/Deep-neural-network-for-Bitcoin-price-prediction-with-tweet-sentiment-analysis) Analyzing Bitcoin trends using a deep neural network and sentiment analysis.
- [**Does Race and Politics Impact Police Violence in the US?:**](https://github.com/jreivilo/Does-race-and-politics-have-an-impact-on-police-violence-in-the-United-States-) A data-driven exploration of social issues in the US.

## 🛠️ Skills
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=Python&logoColor=white)
![R](https://img.shields.io/badge/-R-276DC3?style=flat&logo=R&logoColor=white)
![C](https://img.shields.io/badge/-C-239120?style=flat&logo=C&logoColor=white)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat&logo=git&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat&logo=MySQL&logoColor=white)
![WSL](https://img.shields.io/badge/-WSL-4EAA25?style=flat&logo=Windows&logoColor=white)

- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9
