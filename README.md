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
---    
- ### index.html
    - [directory structure](https://www.geeksforgeeks.org/javascript/file-and-folder-organization-best-practices-for-web-development/)

    - [parchment background colour](https://htmlcolorcodes.com/colors/parchment/)
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
    - Text Content can be found [here](https://haworthguide.co.uk/bronte-sisters)
- ### overview.html
    - [Cards Layout](https://github.com/AdamMcCarthyCS/css-exercises/tree/main/intermediate-html-css/advanced-grid/02-holy-grail-mockup)
    - Content on the moors and sisters writing styles can be found [here](https://haworthguide.co.uk/bronte-sisters)
    #### Photo credit
    - [Overview hero image of Haworth Parsonage](https://www.countrylife.co.uk/out-and-about/theatre-film-music/bronte-sisters-parsonage-haworth-146543)

- ### charlotte.html
    - Hero image generated using chatGPT prompt "Give me an image of Jane Eyre meeting Rochester for the first time on his horse"
    - Quote styling using MDN page [here](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/blockquote#try_it)
    - I learned flex-column layout [here](https://www.theodinproject.com/lessons/foundations-axes#axes)
    - You can see all my flexbox practice in the past [here](https://github.com/AdamMcCarthyCS/css-exercises/tree/main/foundations/flex) and some more use of flex in a landing page [here](https://github.com/AdamMcCarthyCS/project-odin-landing-page/tree/main)
    - Content on Charlotte Bronte can be found [here](https://www.britannica.com/biography/Charlotte-Bronte)
    - I learned how to use google fonts [here](https://www.w3schools.com/css/css_font_google.asp)
    - [Allura Font](https://fonts.google.com/specimen/Allura) for the quote section
    
- ### emily.html
    - Hero image generated using chatGPT "Create an image of Catherine and Heathcliff in waist high grass in the rain in Wuthering Heights"
    - Cancelled out dark overlay using filter: brightness() which I learned [here](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Values/filter-function/brightness)
    - Content on Emily Brontë can be found [here](https://emilybronte.com/biography/)
- ### anne.html
    - Hero image generated using the following prompt in ChatGPT "Create an image of Helen in The Tenant of Wildfell Hall shielding her child from her drunken husband"
    - Content on Anne Brontë can be found [here](https://www.penguin.co.uk/discover/articles/anne-bronte-the-sister-history-overlooked)
- ### letters.html
    - Image for hero taken from [here](https://editions.covecollective.org/sites/default/files/styles/gallery_zoom/public/gallery/WritingRoom2.jpg?itok=wc7B1qLP)
    - Quote from Biographical notice of Ellis and Acton Bell can be found [here](https://www.gutenberg.org/cache/epub/771/pg771-images.html)
    - Quote from Ellen Nussey about Emily bronte can be found [here](https://library.leeds.ac.uk/special-collections/view/413)
    - Anne Bronte letter to Ellen Nussey can be seen [here](https://www.facebook.com/BronteParsonageMuseum/posts/on-this-day-in-1849-anne-bront%C3%AB-died-from-tuberculosis-at-the-age-of-29this-lett/1126313282868540/)
- ### notable-works.html
    - The fr unit was used to give whatever space divided equally between the two columns. I learned that [here](https://www.theodinproject.com/lessons/node-path-intermediate-html-and-css-advanced-grid-properties#fractional-units)
    - Notes on Jane Eyre can be found [here](https://www.penguin.co.uk/books/34231/jane-eyre-by-bronte-charlotte/9780141040387)
    - Notes of Villette can be found [here](https://www.fantasticfiction.com/b/charlotte-bronte/villette.htm)
    #### Images
    - Four of the images are low res amazon thumbnails. I have not downloaded the images, just used their links. As far as I can tell thats okay going by this [webpage](https://www.osborneclarke.com/insights/can-link-frame-third-party-content-without-permission?) 
    - [Poems by Currer, Ellis, and Acton Bell](https://en.wikipedia.org/wiki/Poems_by_Currer,_Ellis,_and_Acton_Bell#/media/File:Bronte_poems2.jpg)
    - [Jane Eyre, Penguin Edition](https://m.media-amazon.com/images/I/81pwJjgcwwL._SY385_.jpg)
    - [Villette](ttps://m.media-amazon.com/images/I/61qk4BTy82L._SY385_.jpg)
    - [Wuthering Heights](https://m.media-amazon.com/images/I/81T34Sem-tL._SY385_.jpg)
    - [The Tenant of Wildfell Hall](https://m.media-amazon.com/images/I/51gJaXujOBL._SY385_.jpg)
- ### haworth.html
    - Hero image: [Haworth Village](https://commons.wikimedia.org/wiki/File:Main_Street_in_Haworth_-_geograph.org.uk_-_2649201.jpg)
    - The old school house [image](https://commons.wikimedia.org/wiki/File:Haworth,_the_old_school_house.JPG)
    - St Michaels and All Angels church [image](https://commons.wikimedia.org/wiki/File:St_Michael_and_All_Angel%27s_Church,_Haworth_-_geograph.org.uk_-_922569.jpg)
    - Bronte Waterfall [image](https://commons.wikimedia.org/wiki/File:Bronte_bridge_and_waterfalls_-_geograph.org.uk_-_630928.jpg)
    - Top Withens in the moors near Haworth [image](https://www.flickr.com/photos/marthaelhadidi/8010394987/)
    - Bronte Sculpture at Bronte Parsonage Museum [image](https://commons.wikimedia.org/wiki/File:Sculpture_of_the_Bront%C3%AB_Sisters,_Haworth.jpg)
    - Content on the brontes love for Haworth can be found [here](https://haworthguide.co.uk/bronte-sisters)
    - Content on the old schoolroom can be found [here]
    - Content on St Michaels and All Angels can be found [here](https://www.haworthchurch.co.uk/history/the-brontes/)
    - Content on the Bronte Waterfall can be found [here](https://haworthguide.co.uk/bronte-waterfall-and-bridge)
    - Content on Top Withens can be found [here](https://haworthguide.co.uk/top-withens)
    - Bronte Parsonage Museum content can be found [here](https://web.archive.org/web/20150623085401/http://www.bronte.org.uk/bronte-society/history)

- ### Refactoring
    - Added commenting to show reuse of classes throughout
    - Validated html for all .html pages using [W3C-Validator](https://validator.w3.org/nu/#textarea)
    - Validated all CSS pages using [W3C-Validator](https://jigsaw.w3.org/css-validator/#validate_by_input)

