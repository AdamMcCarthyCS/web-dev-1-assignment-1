#### Name: Adam McCarthy
#### Student Number: XXXXXXXX (Redacted for Github)
---
## Project Goal: 
**Create a website about the three Brontë sisters**, potentially extending it to their literary influence, works, and where they lived. This will be brief and summarised but contain the main information.

First I will build a 5 page website. If that works out I will extend it to 8 pages. I intend to use the same nav on each page, have colour themes for each page, and use grid and flexbox.

---
## Initial design decisions:

- Site font: serif family as it looks literary, quotes in italic, captions small. All text is centered
- Grid: All grid items have the same gaps throughout
- Padding is consistent throughout in the major sections
- Cards: rounded corners and consistent padding, effect (shadow?)
- Images: captions underneath? Same size throughout, border and rounded corners, hover on main page?
- Quotes: different background? Border effects?

---
## References
    
- ### index.html
    - [directory structure](https://www.geeksforgeeks.org/javascript/file-and-folder-organization-best-practices-for-web-development/)

    - [parchment background colour](https://htmlcolorcodes.com/colors/parchment/)
    - [12 column grid](https://www.w3schools.com/css/css_grid_12column.asp)
    - [css repeat function](https://www.theodinproject.com/lessons/node-path-intermediate-html-and-css-advanced-grid-properties#repeat)
    - [grid column span shorthand syntax](https://developer.mozilla.org/en-US/docs/Web/CSS/Guides/Grid_layout/Line-based_placement#the_grid-column_and_grid-row_shorthands)
    - [flexbox - styling a nav](https://github.com/AdamMcCarthyCS/css-exercises/tree/main/foundations/flex)
    - I took the max container width used with [bootstrap](https://getbootstrap.com/docs/4.4/layout/overview/) for the max-width value
    - [transparent colour creation. Making black opaque](https://www.w3schools.com/css/css_colors_rgb.asp)
    - [HTML arrow used in hero](https://www.w3schools.com/charsets/ref_utf_arrows.asp)
    - [font properties and syntax](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Properties/font#syntax)
    #### Photo credit
    - [Yorkshire Moors near Haworth](https://i0.wp.com/www.independentpeople.net/wp-content/uploads/2017/02/England-Dales-Bronte10.jpg?fit=1500%2C1000&ssl=1)
    - [Charlotte Brontë portrait](https://www.facebook.com/groups/LoveIrelandGroup/posts/1942904032913418/)
    - [Photograph of Emily Brontë portrait](https://www.flickr.com/photos/harshlight/49529075162)
    - [Portrait of Anne Brontë](https://en.wikipedia.org/wiki/Anne_Bront%C3%AB#/media/File:Anne_Bront%C3%AB_by_Patrick_Branwell_Bront%C3%AB_restored.jpg)

    #### Reflections:
    Page 1:
    - I started with the idea of using grid for the main container and ended up not using it! Lets hope that doesn't evolve into a disaster!
    - Keep the spacing the same between sections now throughout all the site pages
    - Don't use * properties again besides for box-sizing. Absolute headache.
    - Use classes when you want to reuse CSS properties for items that change (ie cards, Heros) Nav, Header and Footer stay the same so IDs work
    - Font colours are annoying. You could decide every colour at the start but sometimes you need too see how they look as you build the page. This is unfortunate as it ends up leading to refactoring and hunting down individual color: statements.
    - When you start the overview page, try to use every possible inherited property you can from the landing page styling. Thats what I had in mind when I started but it takes ages.
    - I've spent 11 hours and only built one page?!! I'm going with the glass half full and saying I got many silly mistakes out of the way early.


    