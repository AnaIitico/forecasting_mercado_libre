
<!-- Find and Replace All [repo_name] -->
<!-- Replace [product-screenshot] [product-url] -->
<!-- Other Badgets https://naereen.github.io/badges/ -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
<!-- [![License][license-shield]][license-url] -->


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
	<!-- <li><a href="#license">License</a></li> -->
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

This is an application that can be used to analyze company's financial and user data in clever ways to identify areas to improve and help the company grow. So, you want to find out if the ability to predict search traffic can translate into the ability to successfully trade the stock.

### Built With

<!-- This section should list any major frameworks that you built your project using. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples. -->

* [Python](https://www.python.org/)
* [Python CSV Reading/Writing](https://docs.python.org/3/library/csv.html)
* [Python pandas](https://pandas.pydata.org/)
* [Python hvplot.pandas](https://hvplot.holoviz.org/index.html)
* [Python conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html)
* [Python JupyterLab](https://jupyter.org/)

<!-- GETTING STARTED -->
## Getting Started

<!-- This is an example of how you may give instructions on setting up your project locally. To get a local copy up and running follow these simple example steps. -->
* Install and import the required libraries and dependencies ONLY as needed!

* This is an Advanced step and you should only install fbprophet locally if you understand devops, otherwise please change the code to use google.colab to load the files and run the app.  The fbprophet install only runs on python version 3.8 and below.

* You don't need Python installed in your computer. You can install Anaconda and JupyterLab normally just like any other application on your computer. Follow the instructions for Anaconda, ensure that its working, then install JupyterLab.

* I have placed Comments throughout the code so that you can follow the code and be able to replicate the app on your own. Also, so that you're able to contribute in the future :-)

### Prerequisites

<!-- This is an example of how to list things you need to use the software and how to install them. -->
A text editor such as [VS Code](https://code.visualstudio.com/) or [Sublime Text](https://www.sublimetext.com/)


### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/AnaIitico/forecasting_mercado_libre.git
   ```

2. You don't need to install pip - Conda comes with pip and you can also use the command
    conda install 'package name'
   
3. Install Conda according to the instructions based on your operating system.
    For windows users you MUST use the Administrator PowerShell. Users with AMD Processors MUST use the Administrator PowerShell 7 (X64) version
  
    Once installed Conda has an Admin PowerShell version shortcut - look on your Start menu for it.
    This shortcut will prove very useful at times when you need to install other apps or make adjustments to your installation

    Once installed you will see (base) on your terminal
   
4. Activate Conda Dev environment
   ```sh
   conda activate dev
   ```
   You should now see (dev) on your terminal

5. Install JupyterLabs
   ```sh
   pip install jupyterlab
   ```

6. Run JupyterLabs
   ```sh
   jupyter lab
   ```
   A browser window should open on localhost:8888/lab

<!-- USAGE EXAMPLES -->
## Usage
  
<!-- Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources. -->

<!-- ROADMAP -->

## Roadmap

  The app is finished
<!-- Here are some screenshots and code snippets of the working app

#### Exchange Comparison January 2018
![Exchange January Screen Shot][exchange-january-screenshot]

#### Exchange Comparison March 2018 - With Analysis
![Exchange March Screen Shot][exchange-march-screenshot]


#### Calculate Arbitrage Profits Snippet - for January 16 only
#### you can see the full code (with outputs) in the [crypto_arbitrage.ipynb](https://github.com/AnaIitico/forecasting_mercado_libre/blob/main/crypto_arbitrage.ipynb) file
  *This code has been summarized into one block for convenience*
  *and there's an analysis at the end*
```sh
  # some cool code here
 ``` -->

See the [open issues](https://github.com/AnaIitico/forecasting_mercado_libre/issues) for a list of proposed features (and known issues).

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<!-- LICENSE -->
<!-- ## License

Distributed under the MIT License. See `LICENSE` for more information.
 -->

<!-- CONTACT -->
## Contact

Jose Tollinchi - [@josetollinchi][linkedin-url] - jtollinchi1971@gmail.com

Project Link: [https://github.com/AnaIitico/forecasting_mercado_libre](https://github.com/AnaIitico/forecasting_mercado_libre)

<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

Other Dependencies used to build the project.
##### Search google for the correct conda install command

* numpy
* fbprophet
* holoviews
* pystan

* [Img Shields](https://shields.io)
* [Choose an Open Source License](https://choosealicense.com)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/AnaIitico/forecasting_mercado_libre.svg?style=for-the-badge
[contributors-url]: https://github.com/AnaIitico/forecasting_mercado_libre/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/AnaIitico/forecasting_mercado_libre.svg?style=for-the-badge
[forks-url]: https://github.com/AnaIitico/forecasting_mercado_libre/network/members
[stars-shield]: https://img.shields.io/github/stars/AnaIitico/forecasting_mercado_libre.svg?style=for-the-badge
[stars-url]: https://github.com/AnaIitico/forecasting_mercado_libre/stargazers
[issues-shield]: https://img.shields.io/github/issues/AnaIitico/forecasting_mercado_libre/network/members?style=for-the-badge
[issues-url]: https://github.com/AnaIitico/forecasting_mercado_libre/issues
<!-- [license-shield]: 
[license-url]:  -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/josetollinchi/
<!-- [exchange-january-screenshot]: /images/exchange_january_2018.JPG
[exchange-march-screenshot]: /images/exchange_march_2018.JPG -->
