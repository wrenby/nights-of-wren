- [x] inform browser on which srcset image to use in what circumstances
- [x] adjust srcset sizes reflect the normal 4096 side length instead of 6000
  - this ended up being stupid and i did someting better instead
- [ ] show map of where this image is in the night sky
  - ~~html5 canvas overlay??~~ nope, swap to astrometry.net output on hover
- [x] show RA/DEC in post header
  - [x] create an svg of a compass or something to hint at its meaning
  - [x] why is there added whitespace??
  - [o] if i put AKAs here, i can do a disguise svg
    - nah
- [x] revert to regular blist article header if no ra/dec in front matter
- [x] add opengraph meta tags for embeds
  - [x] swap between content types depending on
- [x] why does the gallery page say "Galleries"?
  - [x] still need to fix for blog -- i want a general solution!
    - nvm i don't fucking care; hugo changes .Title automatically
- [ ] hugo archetype
- [o] show more detailed information somewhere else
  - [o] do aliases go here or in post header?
- [x] define glossary terms on hover
  - [x] fix text size and width of tooltip
  - [ ] disable for json/rss output *******
    - lazy load?
  - [ ] reposition to -999 -999 on page resize or end of fadeout animation
  - [o] add dark/light formatting
    - tbh i don't think it actually needs it
  - [x] throw error if the word is missing from dictionary
  - [x] make it work if there are no params and only inner text
  - [x] add javascript to keep the tooltip from being offscreen
    - https://medium.com/carwow-product-engineering/building-a-simple-tooltip-component-that-never-goes-off-screen-c7039dcab5f9#3b6a
- [ ] distinguish between date taken and date posted
- [x] use partialCached
- [x] srcset on the featured image
- [x] link to full-res images on click
- [ ] annotate on hover, like astrobin does
  - i need to buy pixinsight to do this efficiently
- [ ] fix datetime formatting in search results
- [x] fix search ui below 768px viewport width, when it turns to hamburger mode
- [ ] buttons on the side of each image to take to the previous/next posts
- [x] social media links: cloudynights, instagram, rss, github?
  - [x] add something for rss
  - [x] edit instagram svg to something that doesn't suck
- [ ] change 404 page
  - black hole?
- [x] do i want to keep the header on the landing page?
  - current decision: no
- [x] fix accentColor typo
- [ ] check if color scheme preference respects light as a preference
- [ ] i'm losing a ton of time in postcss -- can i get rid of it?


pagination viewport width breakpoints:
1536
1280
1024
768
640
100%

max width: 576 x 208
min width: 328.5

viewport width to max thumbnail width:
\>1536: 459
1280-1536: 368.33-373.33
1024-1280: 283-288
768-1024: 328.5-336
500- 768: 421-576

WHAT CAPS THE VIEWPORT WIDTH AT 500? i think this is a browser limit
