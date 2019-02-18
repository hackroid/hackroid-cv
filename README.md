# Hackroid's CV >_<

##About

Hackroid's latest version resume made with XeLaTeX. It's forked from [**friggeri-cv-a4**](https://github.com/depressiveRobot/friggeri-cv-a4) under MIT license.

> Fork of the ShareLateX version of the [Friggeri CV](https://www.sharelatex.com/templates/cv-or-resume/fancy-cv) from Adrien Friggeri changed to render in A4 paper format. There is also a new option `nocolors` to disable use of colors in section headers.

## Usage

Run `make pdf` to create the PDF (`cv.pdf`).
See `make help` for an overview of available targets.

##Dependencies

* TikZ (header)
* XeTex and fontspec (custom fonts)
* biblatex/biber (publications)
* textpos (aside)

## Options

* `print`: renders in black and white, and reverts the header to dark on light
* `nocolors`: no colors in section headers (but still use dark header)

## License

[MIT License](https://opensource.org/licenses/MIT), Copyright (C) 2019, Hackroid

[MIT License](https://opensource.org/licenses/MIT), Copyright (C) 2017, Marvin Frommhold

[MIT License](https://opensource.org/licenses/MIT), Copyright (C) 2012, Adrien Friggeri

Copyrighted fonts are not subjected to this License.
