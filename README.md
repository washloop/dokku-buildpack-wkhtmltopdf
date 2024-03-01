<h1 align="center">dokku-buildpack-wkhtmltopdf</h3>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

## 📝 Table of Contents

- [About](#about)
- [Feature](#feature)
- [Getting Started](#getting_started)
- [Usage](#usage)
- [Acknowledgements](#acknowledgement)
- [License](#license)
- [Changelog](#changelog)


##  About <a name = "about"></a>

This buildpack downloads and extracts the
[wkhtmltopdf](https://wkhtmltopdf.org/) binaries.

- This buildpack downloads wkhtmltopdf v0.12.6.1-3.

## Features <a name = "feature"></a>
- Downloads wkhtmltopdf binaries from [wkhtmltopdf.org](http://wkhtmltopdf.org)
- It doesnot add new environment variables or shell scripts.

## Getting Started <a name = "getting_started"></a>
Just add the buildpack to your dokku app. [Buildpack documentation](https://dokku.com/docs/deployment/builders/herokuish-buildpacks/).

## Usage <a name="usage"></a>

The binaries `wkhtmltopdf` and `wkhtmltoimage` will be available on `/app/bin`,
you can just execute `/app/bin/wkhtmltopdf ` and `/app/bin/wkhtmltoimage`  from your app.


## Acknowledgements <a name = "acknowledgement"></a>

- All thanks to [heroku-buildpack-apt](https://github.com/ddollar/heroku-buildpack-apt) project.
- This project is a fork of [heroku-buildpack-wkhtmltopdf](https://github.com/RohanDebroy/heroku-buildpack-wkhtmltopdf) trimmed and simplified for dokku deployment.

## License <a name="license"></a>
MIT
