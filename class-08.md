# Reading Notes
## June 24, 2020

__HTML Chapter 15: Layout__
* Block level elements start on a new line
* inline elements flow in between surrounding text.
* if block level elements are nested, then the outer box is the parent element.
* Normal flow (aka static positioning) is block level and inline elements are standard and where they are supppsed to be by default.
* relative positioning moves an element relative to the position it would be in with normal flow, so right of where it would be, left, top, bottom. 
* absolute positioning plants an element somewhere and doesnt move regardless of what happens to everything else. People can scroll and it stays put.
* position fixed is a form of absolute positioning and ignores the containing element. 
* floating elements get positioned outside of normal flow and float to far left or right of containing box. 
* z index elements move to the front in stacked elements. 
* fixed width and liquid layouts are opposites. 
* Layout grids can help us organize elements visually. 
* 960.GS is a template for stylesheet that uses a 12 column grid for layout.
* Multiple style sheets get run in the order they are in the html.