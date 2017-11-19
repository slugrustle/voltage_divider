# Voltage Divider Calculator

This program finds two-resistor voltage dividers 
created from real-world resistor values (EIA E24 
and/or E96) with divider ratios closest to some 
target. Tolerance and overall divider string 
resistance are also taken into account. The 
calculator is a single .html file with inline 
Javascript.

## Getting Started

Download a local copy of voltage_divider.html 
and run it in any browser that supports modern 
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

* Ben Tesch - [slugrustle](https://github.com/slugrustle)

## License

This project is released under Creative Commons 
[CC0](https://creativecommons.org/publicdomain/zero/1.0/) 
1.0 Universal Public Domain Dedication. See LICENSE.txt or 
the first comment in voltage_divider.html.

## Acknowledgments

* [svgminify](http://www.svgminify.com/) was handy 
for reducing the size of the inline .svg images 
used in this project.