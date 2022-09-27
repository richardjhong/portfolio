# Portfolio

# Purpose
In this project, I further cemented my knowledge of CSS and HTML. In particular, there are different css displays (grid, flex, block), different interactions based on whether an element is hovered over (e.g. each project card starts out default of gray-scale and resumes color after being hovered on), and media query rules to handle different viewport sizes. For the visual hierarchy/architecture of the HTML, I viewed the page in the following way from top down:

1. Header
  - English Name and Korean Name
  - Navbar with clickable sections that jump the user to respective part of page
  - Clickable Github and LinkedIn icons

2. Main section
  - The first portion within main is the Projects section. I used the CSS grid layout in particular to handle this section. For a crude visual breakdown of the grid, when the viewport has a screenwidth of at least 1201 pixels:

Viewport of screenwidth of at least 1201 pixels               
        
          
<pre><code>First First   | Second Second                 
First First   | Third Third
     Fourth Fourth | Fifth Fifth</code></pre>

Viewport of screenwidth of less than 1201 pixels

<pre> First
      ------
      Second
      ------
      Third
      ------
      Fourth
      ------
      Fifth </pre>








Stock photo credit:
Project container background photo: https://www.pexels.com/photo/abstract-backdrop-of-multicolored-tiled-floor-7794425/