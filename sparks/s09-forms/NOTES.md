# NOTES — <forms>

## Intent
An RSVP form for a Friendsgiving party, with a place to put name, email, which side you're bringing, and which dessert you're bringing. 

Prediction: user invalid solves the problem of red before you've even typed, a label solves the problem of vanishing gray labels, legend gives the radio buttons an actual question

What is used: we did use user invalid, labels, and the legend yay!

## AI use
I wrote the base code so that I could make all of the written copy myself and structure it how I wanted. Then I asked the agent to edit the base code so that the webpage meets the "done" list. Once that was done, I checked the code myself using the code validator and contrast checker. 

## Accepted / changed / rejected
I didn't let it write written copy for me but I kept the styles and code. 

## Dig deeper
https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/div

I looked up divs because the agent used them to style the questions and I wanted to ensure that it was okay for it to be a div instead of an article. I think that it is still okay especially because the questions are already pretty clearly questions semantically so it's not like the div is replacing a more descriptive tag, but it was interesting. 

## Open questions
aria labels! I think I've sort of had the impression that they are bad, but in this instance we were totally encouraged to use them. Maybe that's my next dig deeper. 