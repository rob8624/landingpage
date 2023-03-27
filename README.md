# landingpage
A landing page for the Odin Project

After initially building the landing page project I wasn't happy with how everything broke on mobile so I built it again with a responive layout as you see here in this repo.

- The site now looks nice on mobile
- I made the body 100vh and a Flex column
- I broke each part of the design down into sections with this      structure
            Header
            Main
                Welcome
                Staff
                Quote
                CTA
                Footer
- Each section had a full width div, within this div I nested an inner-div to contain the content of each section
- The inner-div was used to centre the content within the body using
            max-width: 1200px;
            margin-right: auto;
            margin-left: auto;
- section structure was mainly made using flex 
- I designed it mobile first, then adding media queries to adjust the flex direction once passed 900px breakpoint.

Things that could be improved.

- padding could be adjusted across the project
- fonts and colours could be adjusted to improve the look
- footer needs work as it doesn't quite go 100% width
- a logo could be added, but when I tired this, it broke the header
- there is some inline css but very minimal. This could be added to the main css style sheet.

Things I have learn't

- It is imperative to build a skeleton of the design you are working on. 
- Break everything down into it's boxes and nested boxes
- Get the initial setup of the body correct.
- make a note of eveything that you do, I started to get confused towards the end by what div was doing what.

Summary

This was a really fun thing to complete. It is the first full web page that I have built with stand alone CSS, not using any kind of framework, and I really enjoyed the benefits of writing very specific CSS.
