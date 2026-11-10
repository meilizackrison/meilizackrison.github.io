# NOTES — <flexbox and box model>

## Intent
A page with cards for people deciding between the DnD 5e classes barbarian, fighter, paladin, and ranger. The page has a header with the site’s title and a nav, then a card for each of the classes, then a footer. Each card has the thing’s name as a heading, one or two sentences about it. 

## AI use
I gave the agent my intent and done list then asked it to generate a plan. I then asked it to proceed, then any changes I made were all my own. 

## Accepted / changed / rejected
I rejected its written copy, I kept the structure of the cards, I changed the link copy so that each said "learn more about _______" instead of kind of weird adventuring style words like "discover the _______" but that may have been a superfluous change. Also my written copy is not actually super informative, it's just me being funny, which I wonder if that is in the long run an accesibility issue? At the very least it's probably violating Gricean maxims. I also checked the color contrast on my own because I'll never truly trust the computer to. 

## Dig deeper
I looked into flexbox alignment and justifying content and learned that basically when you say to justify something what it's doing is looking at your extra space and then calculating what the space in between items needs to be. Very cool. https://developer.mozilla.org/en-US/docs/Web/CSS/Guides/Flexible_box_layout/Aligning_items

## Open questions
If you set your language as something other than english in the boilerplate, will the code understand to have things go from right to left when you tab through rather than left to right? Is that enough or do you need more code for that? 

0.75rem; 1.25rem; 2rem