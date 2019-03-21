# GoPro Sensor Parser

After buying a GoPro Karma Drome I was dismayed the tools for parsing and handling the GoPro flight logs were lacking. 

GoPro Quick can read the data contained in the .SES files that are written out by the GoPro camera. GoPro Quick is unfortunately only available for Windows / MacOS though. I also wanted to use the data more for past flight analysis than just enriching video shot during drone flights.

Fortunately [GoPro has made a library for parsing files encoded with GPMF available](https://github.com/gopro/gpmf-parser) on their github page. This repo is a modifed version of their "demo" application and can be used to export sensor data for a flight on the command line.

## Usage 

_cd src/_

_make_

_./gpmfdemo ../sample_data/sample_flight.SES_

## License Terms

GoPro Sensor Parser is licensed under either:

* Apache License, Version 2.0, (LICENSE-APACHE or http://www.apache.org/licenses/LICENSE-2.0)