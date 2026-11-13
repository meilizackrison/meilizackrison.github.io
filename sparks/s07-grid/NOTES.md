# NOTES — <s07 grid>

## Intent
A web page for people choosing between four different bed and breakfasts in Wayne, PA with a list of things to do in Main Line Pennsylvania in a sidebar. Four cards which fit as many columns as the screen allows, the facts sit beside the cards, a header above and a footer below. 

Prediction: we could use grid template areas to organize the header, main, aside, and footer. Then we could style the main to specifically have the 2 columns, I suspect autofit could be a player here. 
 
## AI use
I gave it my intent and asked it to plan a webpage, but I initially forgot to give it the done list which is interesting, I'm normally quite good at that. I also in my initial prompt forgot to ask it to give me strings and for that I am sorry. 

## Accepted / changed / rejected
The first round of code had media queries so I needed to get rid of those. Then I also decided to delete the h1 and the random captions around the h1. Then I wanted to expand the gap between the content and the header and the footer, so I changed that.

## Dig deeper
I looked up media queries and learned that they help apply the user's styles to the page, and you can decide to only use specific user styles (like hover) on your page. https://developer.mozilla.org/en-US/docs/Web/CSS/Guides/Media_queries/Using

## Open questions
Why is there a gap between my footer and the bottom of the page when I scroll all the way down? That confuses me. 