# Email Template
This is the starting point for creating your own emails.

## Overview

Here you can find an email template made with [HEML](https://heml.io/), an XML-based markup language designed for building emails.

![Example Mail](https://github.com/zejiran/email-template/blob/main/assets/images/example-mail.png?raw=true)

## Usage

1. Install heml package by using `npm install heml -g`.
2. Create your HEML email in src folder. For example: `email.heml`.
3. For develop, run `heml develop src/email.helm --open`.
4. Once you're ready use `heml build src/email.heml -o dist/email.html`.

## License

[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

- **[MIT license](LICENSE)**
- Copyright 2021 © Juan Alegría.
