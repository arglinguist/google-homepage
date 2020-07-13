# google-homepage
Mini-task for The Odin Project

Goal: Create a static copy of the Google homepage -- visually identical, but links and search bar not functional.

Challenges:
---Overall Layout: Getting navigation bars to split & spread to edges, and making space between header, footer, and central content. 
    1 First attempt: 'div everything
    
    2 Second attempt: 'header', 'footer', classes for left/right, overall layout based on blocks with some floating elements and constant margin-tweaking
    
    3 Third attempt: CSS Grid layout. Rusty on details, referred to https://css-tricks.com/snippets/css/complete-guide-grid/. Excellent solution for layout, worked well. 

--Lower navbar sticking -- how to make it stick to lower end of screen? "sticky" not working.
    --> Used calculated height for central area as 100vh - 100px to ensure the footer would be stuck at the bottom (source: https://css-tricks.com/couple-takes-sticky-footer/)

--Searchbar -- how to simulate appearance? 
    --> Used https://www.mikedane.com/web-development/css/styling-search-bar/ as inspiration, took images from Google homepage (screenshot 50x50px), and played with CSS to achieve correct border, hover, etc.

--how to make "clear" x on searchbar disappear unless text entered?
    --> looks like I need some Javascript for this; removing. 
--how to make searchbar not light up blue when clicked?
    --> Outline is the property. Source: https://www.bitdegree.org/learn/css-form#styling-input-fields

--What to do about the 3x3 grid?
    -->set 2 options as background image of 'div', one for regular, one for hover.

    
Concepts and skills learned:
    CSS Grid layout
    Styling approaches with CSS: 
        -border smoothing (radius)
        -glow effects on hover
        -inclusion of images in search bar 'div' for customized/softer apperance
        -div background images that change on hover
