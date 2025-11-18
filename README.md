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

    ### overview.html
    - [Cards Layout](https://github.com/AdamMcCarthyCS/css-exercises/tree/main/intermediate-html-css/advanced-grid/02-holy-grail-mockup)
    #### Photo credit
    - [Overview hero image of Haworth Parsonage](https://www.countrylife.co.uk/out-and-about/theatre-film-music/bronte-sisters-parsonage-haworth-146543)

    ### charlotte.html
    - Hero image generated using chatGPT prompt "Give me an image of Jane Eyre meeting Rochester for the first time on his horse"
    - Quote styling using MDN page [here](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/blockquote#try_it)
    - I learned flex-column layout [here](https://www.theodinproject.com/lessons/foundations-axes#axes)
    - You can see all my flexbox practice in the past [here](https://github.com/AdamMcCarthyCS/css-exercises/tree/main/foundations/flex) and some more use of flex in a landing page [here](https://github.com/AdamMcCarthyCS/project-odin-landing-page/tree/main)
    - I learned how to use google fonts [here](https://www.w3schools.com/css/css_font_google.asp)
    - [Allura Font](https://fonts.google.com/specimen/Allura) for the quote section
    ### emily.html
    - Hero image generated using chatGPT "Create an image of Catherine and Heathcliff in waist high grass in the rain in Wuthering Heights"
    - Cancelled out dark overlay using filter: brightness() which I learned [here](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Values/filter-function/brightness)
    

    #### Reflections:
- ### landing.html
    - I started with the idea of using grid for the main container and ended up not using it! Lets hope that doesn't evolve into a disaster!
    - Keep the spacing the same between sections now throughout all the site pages
    - Don't use * properties again besides for box-sizing. Absolute headache.
    - Use classes when you want to reuse CSS properties for items that change (ie cards, Heros) Nav, Header and Footer stay the same so IDs work
    - Font colours are annoying. You could decide every colour at the start but sometimes you need too see how they look as you build the page. This is unfortunate as it ends up leading to refactoring and hunting down individual color: statements.
    - When you start the overview page, try to use every possible inherited property you can from the landing page styling. Thats what I had in mind when I started but it takes ages.
    - I've spent 11 hours and only built one page?!! I'm going with the glass half full and saying I got many silly mistakes out of the way early.
- ### overview.html
    - Add photo reference
    - Was there any technique i need to reference from project odin? Similarly mdn.
    - I need to change up the style now for the three sisters pages. I have shown I can inherit properties from the CSS sheet. Now its time to make try some flex-direction: column timelines 
    - You can use the same css for different pages with changes by taking just that property (i.e border-color and making it a class like landing-hr or overview-hr). This applies to using different background images also. Isolate the one property that makes the change and style the rest of the properties for all pages in a single rule as they dont change.
    - Separate sections with hr's to make the layout clearer
    - I didn't really give the pages different accents for the first two pages. How can I do that better? Borders look too hackish when i colour them?
    - I dont want to reinvent the wheel when I'm styling the sisters pages. Try to use some of the section classes to take care of the font, spacing, etc. The text-section should be reusable.
- ### charlote.html
    - Tinting the background-colour of a div looks cool and is simple to do with RGBA and making the colours more transparent!
    - Adding a link to a google font is straightforward and most of them can be downloaded so you dont need to save them locally. 
    - I can mix up the three bio pages by changing the colours in the timeline and quote sections and also switching the timeline from right to left and vice versa
    - I'm still undecided on the last three pages. Potentially three from: 
        - Literary influence
        - Movie Adaptations
        - All their books covers using grid layout
        - Info about Brontë visits and societies like the one in Banagher, Offaly
        - 

    