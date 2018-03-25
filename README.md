# High Voltage Divider Calculator

This program finds three-resistor voltage dividers
created from real-world resistor values (EIA E24
and/or E96) with divider ratios closest to some
target. There are two upper resistors in the divider
circuit to provide current limiting even if one of
them shorts. Resistor tolerance and overall divider
string resistance are taken into account. The
calculator is a single .html file with inline Javascript.

## Getting Started

Download Download the [latest release](https://github.com/slugrustle/high_voltage_divider/releases)
of high_voltage_divider.html and run it in any browser that supports modern
Javascript and HTML/CSS.

The Javascript function solveDivider() forms
the core of the program. It contains code to
parse the user input, to find candidate voltage
divider solutions, and to deduplicate, sort,
and display the most relevant solutions.

## Contributing

I would love to receive bug reports and user
feedback. If you have improvements to the code,
please get in touch.

## Author

Ben Tesch - [slugrustle](https://github.com/slugrustle)

## License

This project is released under Creative Commons
[CC0](https://creativecommons.org/publicdomain/zero/1.0/)
1.0 Universal Public Domain Dedication. See LICENSE.txt or
the first comment in high_voltage_divider.html.

## Acknowledgment

[svgminify](http://www.svgminify.com/) was handy
for reducing the size of the inline .svg images
used in this project.
