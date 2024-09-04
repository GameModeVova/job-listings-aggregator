<a id="readme-top"></a>


<!-- PROJECT SHIELDS -->
<!--
-->
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/gamemodevova/job-listings-aggregator">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Job Listings Aggregator</h3>

  <p align="center">
    <a href="https://github.com/gamemodevova/job-listings-aggregator">View Demo</a>
    ·
    <a href="https://github.com/gamemodevova/job-listings-aggregator/issues/new?labels=bug&template=bug-report---.md">Report Bug</a>
    ·
    <a href="https://github.com/gamemodevova/job-listings-aggregator/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
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
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

The Job Listings Aggregator is a Python-based project that scrapes job listings from multiple job boards like Indeed, LinkedIn, and Glassdoor. It aggregates job titles, companies, locations, salary ranges, and descriptions into a structured dataset, providing valuable insights and data analysis on job market trends. 

<p align="right">(<a href="#readme-top">back to top</a>)</p>


### Built With

* ![Python][python-shield]
* ![BeautifulSoup][beautifulsoup-shield]
* ![Requests][requests-shield]
* ![Pandas][pandas-shield]
* ![Selenium][selenium-shield]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites
Make sure you have Python 3.8+ installed. Install the necessary packages using pip.
  ```sh
  pip install requests beautifulsoup4 pandas
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/yourusername/job-listings-aggregator.git  
   ```
2. Navigate to the project directory 
   ```sh
   cd job-listings-aggregator
   ```
3. Install the required dependencies
   ```sh
   pip install -r requirements.txt
   ```
4. Change git remote url to avoid accidental pushes to base project
   ```sh
   git remote set-url origin gamemodevova/job-listings-aggregator
   git remote -v # confirm the changes
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

To run the scraper, execute the main script:
```sh
python scripts/scrape_jobs.py
```
The scraped data will be saved in the ``data/`` directory


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

 - [ ] Phase 1: Set up the basic scraper for a single job board.
 - [ ] Phase 2: Expand to multiple job boards and combine datasets.
 - [ ] Phase 3: Implement filtering options and data storage in CSV.
 - [ ] Phase 4: Add data analysis and visualization features.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Top contributors:

<a href="https://github.com/gamemodevova/job-listings-aggregator/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=gamemodevova/job-listings-aggregator" alt="contrib.rocks image" />
</a>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Vladimir Azarov - magicazarus@gmail.com

Project Link: [https://github.com/gamemodevova/job-listings-aggregator](https://github.com/gamemodevova/job-listings-aggregator)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/gamemodevova/job-listings-aggregator.svg?style=for-the-badge

[contributors-url]: https://github.com/gamemodevova/job-listings-aggregator/graphs/contributors

[forks-shield]: https://img.shields.io/github/forks/gamemodevova/job-listings-aggregator.svg?style=for-the-badge

[forks-url]: https://github.com/gamemodevova/job-listings-aggregator/network/members

[stars-shield]: https://img.shields.io/github/stars/gamemodevova/job-listings-aggregator.svg?style=for-the-badge

[stars-url]: https://github.com/gamemodevova/job-listings-aggregator/stargazers

[issues-shield]: https://img.shields.io/github/issues/gamemodevova/job-listings-aggregator.svg?style=for-the-badge

[issues-url]: https://github.com/gamemodevova/job-listings-aggregator/issues

[license-shield]: https://img.shields.io/github/license/gamemodevova/job-listings-aggregator.svg?style=for-the-badge

[license-url]: https://github.com/gamemodevova/job-listings-aggregator/blob/master/LICENSE.txt

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555

[linkedin-url]: https://linkedin.com/in/linkedin_username

[product-screenshot]: images/screenshot.png

[python-shield]: https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white

[beautifulsoup-shield]: https://img.shields.io/badge/BeautifulSoup-4-green?style=for-the-badge&logo=python&logoColor=white

[requests-shield]: https://img.shields.io/badge/Requests-2.25+-blue?style=for-the-badge&logo=python&logoColor=white

[pandas-shield]: https://img.shields.io/badge/Pandas-1.1+-green?style=for-the-badge&logo=pandas&logoColor=white

[selenium-shield]: https://img.shields.io/badge/Selenium-3.141.0+-green?style=for-the-badge&logo=selenium&logoColor=white