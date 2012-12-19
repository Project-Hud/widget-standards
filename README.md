# widget-standards

This project specifies the design and technical standards for building widgets for project HUD.

## Getting Started

Each widget is its own entity which runs totally independantly from the main HUD project. 

To be able to test widgets it recomended to use [@serby](https://github.com/serby)'s [Yonder](https://github.com/serby/yonder) however this 
is currently not working for the latest release of express so a fork is available [here](https://github.com/serby/yonder).  

## Design

This is under construction and not yet finalised.

### Fonts

-

### Colour Pallete

-

### Sample HTML, CSS and assets

Check the samples folder in this repository for examples of styles and markup.

## Technical

### Graphing Libraries

Various graphing libraries have been tried and tested by [@tomgco](https://github.com/tomgco/) and [@lukewilde](https://github.com/lukewilde)
However the general consensus has been to utilise as much of [d3.js](http://d3js.org/) as possible, but with most things
we shouldn't allow this to become a Golden Hammer.

### Development Platform

- Node.js
- Basic Express Application
- Websockets for realtime
- Ajax for dynamic updates

### Coding Standards

See https://github.com/bengourley/js-style-guide
