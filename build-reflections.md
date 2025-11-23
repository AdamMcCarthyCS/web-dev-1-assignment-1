#### Reflections:

  These are some notes I wrote myself along the way to try to reflect on what I was doing as I was building the website

---
### Inital starting point:
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
- ### index.html
    - I started with the idea of using grid for the main container and ended up not using it! Lets hope that doesn't evolve into a disaster!
    - Keep the spacing the same between sections now throughout all the site pages
    - Don't use * properties again besides for box-sizing. Absolute headache.
    - Use classes when you want to reuse CSS properties for items that change (ie cards, Heros) Nav, Header and Footer stay the same so IDs work
    - Font colours are annoying. You could decide every colour at the start but sometimes you need too see how they look as you build the page. This is unfortunate as it ends up leading to refactoring and hunting down individual color: statements.
    - When you start the overview page, try to use every possible inherited property you can from the landing page styling. Thats what I had in mind when I started but it takes ages.
    - I've spent 11 hours and only built one page?!! I'm going with the glass half full and saying I got many silly mistakes out of the way early.
- ### overview.html
    - Add photo references for all images. Use the search tools > creative commons to find images that can be used
    - Was there any technique i need to reference from project odin? Similarly mdn.
    - I need to change up the style now for the three sisters pages. I have shown I can inherit properties from the CSS sheet. Now its time to make try some flex-direction: column timelines 
    - You can use the same css for different pages with changes by taking just that property (i.e border-color and making it a class like landing-hr or overview-hr). This applies to using different background images also. Isolate the one property that makes the change and style the rest of the properties for all pages in a single rule as they dont change.
    - Separate sections with hr's to make the layout clearer
    - I didn't really give the pages different accents for the first two pages. How can I do that better? Borders look too hackish when i colour them?
    - I don't want to reinvent the wheel when I'm styling the sisters pages. Try to use some of the section classes to take care of the font, spacing, etc. The text-section should be reusable.
- ### charlotte.html
    - Tinting the background-colour of a div looks cool and is simple to do with RGBA and making the colours more transparent!
    - Adding a link to a google font is straightforward and most of them can be downloaded so you don't need to save them locally. 
    - I can mix up the three bio pages by changing the colours in the timeline and quote sections and also switching the timeline from right to left and vice versa
    - I'm still undecided on the last three pages. Potentially three from: 
        - Literary influence
        - Movie Adaptations
        - All their books covers using grid layout
        - Info about Brontë visits and societies like the one in Banagher, Offaly
- ### emily.html
    - Remember that you can have elements naturally flow into the right places (vertically) when only defining grid-template-columns (not rows) by the order that the content appears in the html page. This is how I got the order right on the emily page for the text-bio and the timeline!
    - This repeatable page paid off. Just swapping the sides and adding some colour did make the pages a bit more distinct without reinventing the wheel
    - Anne's page will have three links to TBAs at that point. Should I just have those bottom links going between the sisters? I think if I stuck with what I'm doing people would find the 6th, 7th, and 8th pages more easily. The fact that the sisters names come in the leftmost links makes them obvious sequential next stops.
    - I made an absolute mess of the links that took half an hour to figure out. Basically if I want to use this more advanced folder structure I need to be careful that when I am on a page in the /pages folder I remember that I need to go up a level to go to assets/css (ie ../assets/css/styles.css), similarly...the other pages in the Pages folder can be reached with ./page while the index page needs ../index.html as its contained in the top level
    - Github pages will not show background images also if the links are not right relative to where the page html file is. For example if you have a page in /pages, first you need to go up a level to root level (../) then you need to pass through assets into images (../assets/images/somephoto.jpg)
    - Accents such as the ë in landing-anne-brontë.jpg also break github pages sometimes. Its better to keep the lettering standard for image naming
- ### anne.html
    - Reusing the classes made it relatively painless to create anne's page. In fact I just had to copy Charlottes page and then change the content and accent colours
    - I need to do a final check through of all the links and grammar of the text at the very end before submitting. Twice probably to make sure I dont miss anything.
    - I think I have finally settled on the last three pages
        - Quotes from personal letters of the Brontës which further highlight their character. Should they all have different accent colours or the same accent? I think I would like to reuse the font from the individual quotes to make them stand out as different?
            - inkwell and paper hero
            - Hero link -> Most famous works
            - Link to most famous works, bronte societies and overview
        - A page with each of their most famous novels
            - Old books hero
            - Jane Eyre and Vilette for Charlotte
            - Wuthering Heights for emily
            - The Tenant of Wildfell Hall for Anne
            - Each section should have a wrapped image of the book covers
            - Hero link -> Bronte societies
            - Links Bronte societies, home page, overview
        - A page on Bronte Societies for more information
            - Statue of the bronte sisters hero
            - Hero link -> Home
            - The one in Offaly
            - The one most associated with the Brontes in the UK
            - Perhaps the quote from Anne about being tired after reading to finish the site
            - Also only two links. One to the home page and one to the overview
- ### letters.html
    - Reusing the quotes section css worked well. I think sticking with an easier to read font was a good idea as the language used in the letters is quite archaic
    - For the next section I think I should include the poetry book they published together as its their first publication
    - I have rearranged the css into separate files. The main learning from this is that the @import url() has to be at the top of the main styles.css and can only be preceded by other @import statements, no comments, or css can come before it
    - The headers for the letter quote sections are a bit basic. Could I come up with something more fancy? Or am I just overthinking it? What do people generally do on other sites that are content heavy? Look some up, but look at similar genre, i.e. literature sites/bronte sites
    - My experience of using chatGPT generated Hero images has been fairly positive. However, there is the argument that that is generated from other peoples artwork embedded in in generative model. I really like the images though. My friends in Lighthouse studios and Cartoon Saloon would not be happy. I don't know what the answer to this is.
- ### notable-works.html
    - Using a grid layout with two columns worked well here. Now that I'm basically at the end I feel that I didnt lose out by not going with my 12 column grid idea that I had at the beginning. It turned out fairly good.
    - I didn't realise that you can link amazon thumbnails without breaching copyright. You just use a live link to the thumbnail on amazon and don't actually download the image and its allowed. Thats great for a literary page.
    - I was a bit confused about how to reuse the .text-section again as i wanted the line spacing and width properties. So I ended up adding another css page. I guess you cant DRY everything? I will keep an eye out on how to break this down further so I can reuse as much as possible. I think it will just come with practice.