<h1 align="center">Notes</h1>

⚔️ -------------------------------------------------------------------------🛡️-----------------------------------------------------------------------------------------------------⚔️
## Week 8, Friday

The header was squished on a phone.

I fixed it by adding flex-wrap so it can stack.

## Week 9, Wednesday

1) My three pages start with an index homepage with my information, a projects second page describing the projects I've been a part of, and a third now page explaining my current efforts.

2) I set defaults in styles.css for everything to reduce redundancy and mistakes throughout building each page. This allowed me to make changes in one location and have them automatically apply to all three pages, instead of updating each page separately.

3) One thing I don't know how to change yet is adding transitions and movement to my pages.

## Week 9, Friday

1) I used a breakpoint of 40rem. I chose it because it was the width used in class and it worked well when testing my layout.

2) Two things I found and fixed at phone width. The header was squished on smaller screens. I added flex-wrap so the image and text could stack. Secondly, I added max-width: 100% and height: auto to images so they resize properly on smaller screens and do not overflow the page.

3) Justify-content controls how items are spaced in the direction they are flowing, while align-items controls how they line up across that flow. In flexbox, justify-content works on the main axis and align-items works on the cross axis.

4) The narrow layout is the default because most phones have smaller screens. The media query changes the layout when there is more room available on larger screens.

## AI use

I used Copilot to answer questions about HTML, CSS, Flexbox, media queries, Git, and to verify that my work met the assignment requirements. I wrote and modified the code and content myself.

## Week 10, Wednesday

1) The HTML is the visualization of the code. The CSS formatting and colorization of the code. The JavaScript is the functions/methods of the code.

2) I don't know what 'defer' is doing.

3) Dark mode was passed from a parent to a child making it so we didn't have to hard code every instance.

4) The if statement declaring the value of x and not comparing it. we fixed it by using the proper expression.

5) The dark mode won't pass between pages but light mode will. There is a syntax error I have not been able to correct yet.


## Week 10, Friday

1) event.preventDefault() stops the page from refreshing when the form is submitted and losing everything.

2) JavaScript was trying to use something that wasn't on the page. The if statemenet checks if it exists first so it doesn't blow up.

3) I made the messafe require at least 10 characters. If somebody is contacting me, they can put in at least a little effort.

4) I changed the navigation so it stays horizontal and wraps instead of stacking. I also fixed the form width and made the Send button bigger so it is easier to use on mobile with big fingers.

5) Library implementation for a method to handle the message to its location.