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
of high\_voltage\_divider.html and run it in any browser that supports modern
Javascript and HTML/CSS.

## Contributing

I would love to receive bug reports and user
feedback. If you have improvements to the code,
please get in touch.

## Author

Ben Tesch - [slugrustle](https://github.com/slugrustle)

## License

high\_voltage\_divider.html contains the functions download\_csv and download\_xlsx,
which are modified from [this Stack Overflow post](https://stackoverflow.com/a/33542499)
and are therefore distributed under the 
[CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).

The remainder of the high\_voltage\_divider project is distributed under the 
[CC0 1.0 Universal Public Domain Dedication](https://creativecommons.org/publicdomain/zero/1.0/).
See also LICENSE.txt or the first comment in high\_voltage\_divider.html.

## Acknowledgment

[svgo](https://github.com/svg/svgo) was handy
for reducing the size of the inline .svg images
used in this project.
