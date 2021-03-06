# uncensor-bars
A small CSS stylesheet for dynamic hide/show censor bars.

__[Live demo](https://charliecharlieo-o.github.io/uncensor-bars/)__

## Description
While browsing a website I came across an interesting overload of the HTML *\<s\>* element that made it look like a censor bar.
If you don't know what a censor bar is you can read it here: https://en.wikipedia.org/wiki/Censor_bars

I took that as inspiration to create the following simple styles, all done with CSS.

## Usage
Using the stylesheet is as easy as linking the *cbars.css* file and using the following custom elements:

- **\<s\>**: A simple black censor bar that shows the hidden text on white when you hover the pointer upon it.
- **\<sg\>**: Just as the former but grey colored.
- **\<sw\>**: A white censor bar that shows black hidden text when hovered over.
- **\<s-blur\>**: Even tho not exactly a bar, it's a simple element that blurs and unblurs the text you wan't to *"hide"*
