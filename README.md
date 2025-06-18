# PROTO
The F39 utility css library for rapid prototyping.

## Installation
URL
```
https://cdn.jsdelivr.net/gh/f39d/proto/css/proto_layout.min.css
```
Link tag
```
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/f39d/proto/css/proto_layout.css"/>
```

## Basic Grid module Use
Include the `grid` class on the top lvl container. Then set the custom css props for rows, cols, areas, and gap. 
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
