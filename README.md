<div align="center">
  <a href="https://jsonvisio.com">
    <img width="512" alt="json visio logo" src="https://github.com/AykutSarac/jsonvisio.com/blob/main/public/logo.png">
  </a>
</div>

<div>
    <p align="center">
      <img alt="travis ci badge" src="https://img.shields.io/travis/com/AykutSarac/jsonvisio.com/main?style=flat-square" />
      <a href="https://github.com/AykutSarac/jsonvisio.com/blob/main/LICENSE">
      <img alt="license badge" src="https://img.shields.io/github/license/AykutSarac/jsonvisio.com?style=flat-square" />
      </a>
      <a href="https://github.com/AykutSarac/jsonvisio.com/releases">
      <img alt="version badge" src="https://img.shields.io/github/package-json/v/AykutSarac/jsonvisio.com?color=brightgreen&style=flat-square" />
      </a>
      <a href="https://opencollective.com/jsonvisio">
      <img alt="open collective backers" src="https://img.shields.io/opencollective/backers/jsonvisio?style=flat-square" />
      </a>
  </p>
  <p align="center">
    <i>Simple json visualization tool for your data.</i>
  </p>
  <img width="800" src="https://jsonvisio.com/jsonvisio-screenshot.png" alt="preview 1" />

  <p align="center">
    <h2 align="center">Support JSON Visio<h2>
    </p>
  <p align="center">
    <a href="https://www.producthunt.com/posts/json-visio?utm_source=badge-featured&utm_medium=badge&utm_souce=badge-json&#0045;visio" target="_blank"><img src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=332281&theme=light" alt="JSON&#0032;Visio - Simple&#0032;visualization&#0032;tool&#0032;for&#0032;your&#0032;JSON&#0032;data&#0046; | Product Hunt" style="width: 250px; height: 54px;" width="250" height="54" /></a>
    <a href="https://opencollective.com/jsonvisio" target="_blank">
    <img src="https://opencollective.com/webpack/donate/button@2x.png?color=blue" width=300 />
    </a>
  </p>
</div>

# JSON Visio (jsonvisio.com)

JSON Visio is data visualization tool for your json data which seamlessly illustrates your data on graphs without having to restructure anything, paste directly or import file.

> <b><a href="https://jsonvisio.com">JSON Visio - Directly onto graphs</a></b>

## ⚡️ Features
* PWA (Progressive Web App) with offline mode support
* Search Nodes
* Download as image
* Advanced Error Message
* Save JSON locally
* Multiple layout direction support
* Compressed view
* Representative colors for arrays & keys
* Friendly UI
* Light/Dark Mode


## 🧩 Preview

<div align="center">
  <img width="800" src="https://github.com/AykutSarac/jsonvisio.com/blob/main/public/preview_2.png" alt="preview 1" />
</div>


## 🛠 Development Setup

```console
  npm install --legacy-peer-deps
  npm run dev
```
  
## 🐳 Docker

```
A Docker file is provided in the root of the repository.
If you want to run JSON Visio locally:
  
* Build Docker image with `docker build -t jsonvisio .`
* Run locally with `docker run -p 8888:80 jsonvisio`
* Go to [http://localhost:8888]
```

## License

This project is open source and available under the [MIT License](LICENSE).
