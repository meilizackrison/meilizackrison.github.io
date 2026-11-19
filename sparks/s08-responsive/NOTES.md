# NOTES — <responsiveness spark>

## Intent
This is a webpage for a campus club fair: the clubs, a sidebar with how to sign up, and a table of meeting times and rooms. The clubs will be boxing club, dnd club, kpop club, creative writing club, and sword dance club. 


Prediction: we'll use @media (min-width: …) to add layout only when the screen has reached laptop size, minmax(0, 1fr) to make sure the table won't push the page, overflow-x: auto so the table scrolls in its own box, 

## AI use
What is used: I wrote the base code so I did use @media (min-width: …) to add layout only when the screen has reached laptop size, minmax(0, 1fr) to make sure the table won't push the page, overflow-x: auto so the table scrolls in its own box. However I forgot how to style the table with an aria label. 

I then gave the agent my done list and my intent with the request to style it using a better color palette as well as put things in boxes with padding.  

## Accepted / changed / rejected
I kept everything from the agent (container styling, font sizing and typography, adding link to the hub). I handwrote the base code so I could understand it better and to stay more engaged while completing the assignment. 

## Dig deeper
I looked up media queries (https://developer.mozilla.org/en-US/docs/Web/CSS/Guides/Media_queries/Using) and learned that you can use these guys to target a printer if you so desired, which I don't but it was interesting. 

## Open questions
Would there be any point in styling for a fridge or an apple watch? Like what about styling for those stupid meta glasses? When the hologram tech revolution comes, will html develop for that? 
