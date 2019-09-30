# H5P-Demo

---

# This Repository is deprecated and everything was moved to [https://github.com/Lumieducation/H5P-Nodejs-library](https://github.com/Lumieducation/H5P-Nodejs-library).

---

[![Build Status](https://travis-ci.org/Lumieducation/H5P-Demo.svg?branch=master)](https://travis-ci.org/Lumieducation/H5P-Demo)

This repository demonstrates the integration of the [H5P Player](https://github.com/Lumieducation/H5P-Nodejs-library) and [H5P Editor](https://github.com/Lumieducation/H5P-Editor-Nodejs-library) libraries.

## Installation

To install this project, run the following commands in a terminal

    git clone https://github.com/Lumieducation/H5P-Demo.git
    cd H5P-Demo
    npm install

This will install all dependencies, including the H5P Player and Editor libraries and core files from the H5P.org repositories.

## Usage

### Run Demo

After installation, you can start the demo with

    npm start

and browsing to http://localhost:8080.

### Run Tests

To run the integration tests locally (using Chromium and Puppeteer), use the command

    npm run ci

### Content Tests

To run the integration test, simply use

```
npm run test:content
```

This command will do the following:

1. download all H5P-Examples specified in the [examples/examples.json](examples/examples.json).
2. start a local webserver on port 8080
3. start a chromium instance via [puppeteer](https://github.com/GoogleChrome/puppeteer)
4. checks every example if it throws errors when openend in a browser

## Contributing

Lumi tries to improve education wherever it is possible by providing a software that connects teachers with their students. Every help is appreciated and welcome.Feel free to create pull requests.

Lumi has adopted the code of conduct defined by the Contributor Covenant. It can be read in full [here](./CODE-OF-CONDUCT.md).

### Get in touch

[Slack](https://join.slack.com/t/lumi-education/shared_invite/enQtMjY0MTM2NjIwNDU0LWU3YzVhZjdkNGFjZGE1YThjNzBiMmJjY2I2ODk2MzAzNDE3YzI0MmFkOTdmZWZhOTBmY2RjOTc3ZmZmOWMxY2U) or [c@Lumi.education](mailto:c@Lumi.education).

## License

This project is licensed under the GNU GENERAL PUBLIC LICENSE v3 License - see the [LICENSE](LICENSE) file for details

## Support

This work obtained financial support for development from the German BMBF-sponsored research project "CARO - Care Reflection Online" (FKN: 01PD15012).

Read more about them at the following websites:
CARO - https://blogs.uni-bremen.de/caroprojekt/
University of Bremen - https://www.uni-bremen.de/en.html
BMBF - https://www.bmbf.de/en/index.html
