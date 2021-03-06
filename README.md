machine-learning-challenge
==============================
<!--
*** Thanks for checking out this README Template. If you have a suggestion that would
*** make this better, please fork the repo and create a pull request or simply open
*** an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
***
***
***
*** To avoid retyping too much info. Do a search and replace for the following:
*** github_username, repo_name, twitter_handle, email
-->




<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]


  <!-- PROJECT LOGO -->
  <br />
  <p align="center">
  <a href="https://github.com/github_username/repo_name">
    <img src="icons/edit.png" alt="Logo" width="80" height="80">
  </a>

  <h4 align="center">YOUR_TITLE</h4>
   

 This dataset is a cumulative record of all observed Kepler "objects of interest" — basically, all of the approximately 10,000 exoplanet candidates Kepler has taken observations on.

This dataset has an extensive data dictionary, which can be accessed here. Highlightable columns of note are:

kepoi_name: A KOI is a target identified by the Kepler Project that displays at least one transit-like sequence within Kepler time-series photometry that appears to be of astrophysical origin and initially consistent with a planetary transit hypothesis
kepler_name: [These names] are intended to clearly indicate a class of objects that have been confirmed or validated as planets—a step up from the planet candidate designation.
koi_disposition: The disposition in the literature towards this exoplanet candidate. One of CANDIDATE, FALSE POSITIVE, NOT DISPOSITIONED or CONFIRMED.
koi_pdisposition: The disposition Kepler data analysis has towards this exoplanet candidate. One of FALSE POSITIVE, NOT DISPOSITIONED, and CANDIDATE.
koi_score: A value between 0 and 1 that indicates the confidence in the KOI disposition. For CANDIDATEs, a higher value indicates more confidence in its disposition, while for FALSE POSITIVEs, a higher value indicates less confidence in that disposition.

<p> Another deep learning model, <strong> a Kepler production</strong> 
I loaded in 40 columns from the data set for the Category CANDIDATE realized by looking at other datasets online, alot of data could been maniuplated with more background Knowledge. After classifying the data based on the koi_plnt_tce_num. One hot encoding was not required in this case since the data was already classified based on the planet nums on filtering it by <strong> CANDIDATE</strong>, then split the data into Training & Test data sets.
The a Loss of 0.2194  and an Accuracy of   0.9086400866508484. 
Using GridSearchCV to tune the model's parameters and changing the grid parameters }<br /></p>

  <!-- [![Live Demo][demo-shield]][demo-url] -->
  
  <p align="center">
  <a href="https://github.com/github_username/repo_name">
    <img src="/reports/icons/live-demo.png" alt="Logo" width="80" height="80">
  </a>
   <h4 align="center">Live Demo</h4>

<!-- MARKDOWN LINKS & ICONS -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: icons/contributors.png
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: /reports/icons/fork.png
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: /reports/icons/half_star.png
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: /reports/icons/bug.png
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: /reports/icons/certified.png 
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
<!-- [demo-shield]: icons/live-demo.png 
[demo-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt -->
[snippet-shield]: /reports/icons/articles.png
[linkedin-url]: https://www.linkedin.com/in/donleygustave/
[linkedin-shield]: /reports/icons/linkedin.png
[twitter-url]: https://twitter.com/donley_cg
[twitter-shield]: /reports/icons/twitter.png
[facebook-url]: https://www.facebook.com/dgustave
[facebook-shield]: /reports/icons/facebook.png
[zoom-url]: https://calendly.com/donleyc-gustave/meeting
[zoom-shield]:  /reports/icons/zoom.png

<!-- MARKDOWN LINKS & IMAGES -->
[project-screenshot]: /reports/images/exoplanets.png

<!-- TABLE OF CONTENTS -->
## Table of Contents
* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
  * [Project Organization](#project-organization)
* [Articles](#articles)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)


<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][project-screenshot]](https://example.com)

Here's a blank template to get started:
**To avoid retyping too much info. Do a search and replace with your text editor for the following:**
`github_username`, `repo_name`, `twitter_handle`, `email`


### Built With
<!-- 
* []()
* []()
* []() -->


  | [![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=dgustave)](https://github.com/dgustave/github-readme-stats)         | [![Donley's github stats](https://github-readme-stats.vercel.app/api?username=dgustave)](https://github.com/dgustave/github-readme-stats)     |   [![Donleys's wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=dgustave)](https://github.com/dgustave/github-readme-stats)
  | ---------------------------------------- | ---------------------------------------- | --------------------------------------| 
  |                                          |                                          |                                       |
        

<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

## Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* pip
```sh
python -m pip install --upgrade pip
```

* conda
```sh
conda install -c anaconda pip
```

### Installation

1. Clone the repo
```sh
git https://github.com/dgustave/machine-learning-challenge.git
```
2. Install Pip packages
```sh
pip install tensorflow
```
```sh
pip install keras
```
```sh
pip install sklearn --upgrade
```
```sh
pip install joblib
```

## Articles

- ["Art of Readme - Learn the art of writing quality READMEs."](https://github.com/noffle/art-of-readme#readme) - *Stephen Whitmore*
- ["How To Write A Great README"](https://thoughtbot.com/blog/how-to-write-a-great-readme) - *Caleb Thompson (thoughtbot)*
- ["Readme Driven Development"](http://tom.preston-werner.com/2010/08/23/readme-driven-development.html) - *Tom Preston-Werner*
- ["Top ten reasons why I won’t use your open source project"](https://changelog.com/posts/top-ten-reasons-why-i-wont-use-your-open-source-project) - *Adam Stacoviak*
- ["What I learned from an old GitHub project that won 3,000 Stars in a Week"](https://www.freecodecamp.org/news/what-i-learned-from-an-old-github-project-that-won-3-000-stars-in-a-week-628349a5ee14/) - *KyuWoo Choi*

<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_



<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/github_username/repo_name/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Donley Gustave - [@donley_cg](https://twitter.com/donley_cg) - donleyc.gustave@gmail.com

Project Link: [https://github.com/dgustave/README-Template](https://github.com/dgustave/README-Template)

[![Zoom][zoom-shield]][zoom-url] 
* Schedule a meeting with me today!
* Leave a detailed message and I will confirm. 




<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Img Shields](https://shields.io)
* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Pages](https://pages.github.com)
* [Animate.css](https://daneden.github.io/animate.css)
* [Loaders.css](https://connoratherton.com/loaders)
* [Slick Carousel](https://kenwheeler.github.io/slick)
* [Smooth Scroll](https://github.com/cferdinandi/smooth-scroll)
* [Sticky Kit](http://leafo.net/sticky-kit)
* [JVectorMap](http://jvectormap.com)
* [Font Awesome](https://fontawesome.com)
* [code snippets][snippet-shield] 




[![Facebook][facebook-shield]][facebook-url]
[![Twitter][twitter-shield]][twitter-url]

<!-- Footer -->
<footer id="footer">
<p class="copyright">Copyright &copy; 2020 Gustave LLC
<br>Designed by <a rel="nofollow" href="https://www.facebook.com/dgustave">Donley Gustave</a></p>
</footer>
..


