<p align="center">
  <img src="https://github.com/butlerc9/Docker-Data-Science/blob/main/images/readme/vertical-logo-monochromatic.webp" width="200" title="hover text">
</p>

<h3 align="center">Dublin Air Quality Hackathon</h3>

---

<p align="center">This is our repo for our shared analysis, this will include links to all data and a link to JupyterHub.</p>

## 📝 Table of Contents
- [Prerequisites](#prerequisites)
- [Getting Started](#getting_started)
- [Authors](#authors)

## 🧐 Prerequisites <a name = "Prerequisites"></a>

1. Install git and clone this repo
2. Install docker
3. Start docker and navigate to this repo on your computer via terminal e.g. git bash or powershell
4. Build the docker image using your terminal by typing ```docker build -t butlerc9/air_quality_jupyter .``` (this building will take a few minutes)
4. Run command "docker compose up"
5. In your terminal there will be a url similar to:
```
  airquality_hackathon_2023-data_science_container-1  |         http://cd4b6e099fea:8888/lab?token=06a17014f4873287007fb090df9c10da375ad0b3f1c46d45
  airquality_hackathon_2023-data_science_container-1  |      or http://127.0.0.1:8888/lab?token=06a17014f4873287007fb090df9c10da375ad0b3f1c46d45
```
6. If you go to this url in your browser you can access Jupyter (you may need to try both)

## 🏁 Downloading Datasets <a name = "getting_started"></a>

You then need to download the datasets and put them in the "/data/raw/" folder in this repository.

The files can be found here: https://data.gov.ie/dataset/google-airview-data-dublin-city

## Connecting to API

1. Create a .env file in your root directory
2. Include one line for any api keys or variables that you need ```GOOGLE_API_KEY=<your key here>```
