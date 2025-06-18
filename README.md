# PROTO: Concise Layout Utility Library for Data-Dense Web Applications.

This library provides condensed utility classes (Flexbox and CSS Grid) for rapid layout of data-dense UI prototypes. All units are in 'rem' for responsiveness and accessibility. Proto CSS focuses purely on layout, leaving styling of individual components (buttons, inputs, etc.) to other libraries.

## Installation
URL
```
https://cdn.jsdelivr.net/gh/f39d/proto/css/proto_layout.min.css
```
Link tag
```
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/f39d/proto/css/proto_layout.css"/>
```

## Basic Grid Layout Utility Example
Include the `grid` class on the top level container. Then set the custom css props for rows, cols, areas, and gap. Available grid areas are `top`, `left`, `center`, `right`, and `bottom`.
```
<div class="grid" 
     style="--grid-cols: 60px 1fr 10vw;
            --grid-rows: 60px 1fr 60px;
            --grid-areas: 
              'top top top' 
              'left center right'
              'bottom bottom bottom';
            --grid-gap: 8px;
            height:100dvh;">
  <div class="top">top</div>
  <div class="left">left</div>
  <div class="center">center</div>
  <div class="right">right</div>
  <div class="bottom">bottom</div>
</div>
```

## Basic Flex Utility Example
Utility classes are available for most flex css attributes. Example:
Use `df` for `display:flex`
`jc-fe` for `justify-content: flex-end`
`ai-c` for `align-items: center`
```
<div class="df jc-fe ai-c">content aligned right</div>
```

## Flex Utility List
See section 3 of the `proto_layout.css` file for alignment & distribution classes.






