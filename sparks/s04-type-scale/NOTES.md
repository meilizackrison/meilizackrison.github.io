# NOTES — <typography spark>

## Intent
The theme for the typography should be "a cool girl's literary magazine--elegant, fun, and not too trendy." The text should be accesible--no cursive, nothing unreadable. 

## AI use
I gave it the above theme and then asked it to propose a plan that fit the requirements of the done list. Then I asked it to proceed.

DONE LIST
 sparks/s04-type-scale/ has its own index.html and CSS file, and it’s a new page, not a copy of an earlier Spark.
 The page names its theme and shows the type in use: headings at three levels (h1, h2, h3), a paragraph of body text, a quote, a list, and a link.
 A “Why these fonts” section on the page gives a reason from the theme for each font, the heading sizes, and the line height.
 One web font (for example, from Google Fonts) is linked, loading only the weights the page uses.
 Every font-family ends in a fallback stack with a generic family, like system-ui, sans-serif.
 Every font-size is in rem (or em for something that should scale with its parent). No px font sizes.
 Body text has a unitless line-height of at least 1.5, and text blocks are capped at about 65ch wide.
 No box that holds text has a fixed height.
 At 200% zoom, nothing is cut off, overlapping, or hidden.
 With the browser’s default font size set to 20px, the text gets bigger.
 The page passes the W3C validator with no errors.
 Your hub index.html links to it under Sparks.
 NOTES.md covers every section, in your own words.
 It’s committed with a meaningful message, pushed, and the live page loads.


## Accepted / changed / rejected
What I kept from the agent, what I changed, and why.

## Dig deeper
One thing I looked up (MDN link) and what I learned.

## Open questions
What I still don't fully understand.