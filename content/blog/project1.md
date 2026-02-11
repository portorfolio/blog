---
title: Thought Process of Putting Together My First Blog
description: Typed
date: 2026-02-06
tags: ["where it all started"]
---

## Initial Thoughts
After making the first adjustments necessary and following the instructions in <code>home.njk</code>, I wasn't too sure where to start. When looking through the different files, I didn't find anything particularly intuitive. This was HTML and CSS, something I've already learned, yet there was a difference I couldn't adapt to. I figured I should go on Eleventy's official website, and did just that.

## Things Start Picking Up?
Unfortunately, I didn't absorb much on it. The next day, I went on some websites for inspiration, simply by typing in "blog inspos" in the Google search bar. I encountered awwwards and was a huge fan of <a href = "https://www.awwwards.com/inspiration/blog-stripe-dot-dev" target = "_blank">this one</a>. Neocities is a well known site, so I went on there as well. Visiting those websites were short lived (for now). No design ideas/sketches/wireframes were started. I went back to my code and realized I could not leave the code untouched simply because I was intimidated by it. I messed around with the <code>index.css</code> file, and accidentally landed on a very unappealing color. This led me to hop on <a href= "https://coolors.co" target="_blank">coolers</a> right away. Ideally I'd like the background to have an image or a collage of images, and the space that includes content will be a colored block over it. 

## Fonts fonts fonts...
Then, I looked into fonts. Something more...striking...is preferred. First, I went onto <a href="https://www.dafont.com" target="_blank">dafont</a> since it was already bookmarked. There were over 200 pages of fonts and I was NOT about to go through all of it, even if I fear I might find something better. I was unsure if this project was considered personal or commercial use, though I still downloaded the fonts I liked just in case. At this point, I was still unsure of how the CSS worked; in this case, importing fonts. I went onto the Eleventy documentation once again, and left feeling really confused. There was uncertainty about whether the CSS functions like how I know it does. Eventually I was able to solve my issue, and added the link of this <a href="https://fonts.google.com/specimen/Unkempt?query=unke" target = "_blank"> Google font </a> to <code>base.njk</code> and imported it into <code>index.css</code>. 

## Layout
Next came the layout. I wanted the title and nav bar to take up 20-30% of the left side, and everything else on the right. I didn't know how to go about it, especially with positioning things. I went onto <a href="https://learnlayout.com/inline-block" target="blank">learnlayout.come</a> to find quick and simple demonstrations on css layouts. I did dabble into w3 schools too, but this website feels like everything is quicker to navigate to. I was messing with border radius, because I kind of liked the look of each element being circular and having a background color behind it. The issue was that the words were now being cut off. I attempted to fix it with this code: 
```js
.header-nav, .main-content{
	display: flex;
	justify-content: center;
	align-items: center;
	border-radius: 25%;
	text-align: center;
	overflow: hidden;
}
```
But it didn't solve the issue, so I resorted to decreasing the border radius to 25%.

## Takeaways
I've learned that going in without a wireframe/sketch is not the best idea. Too much time was spent on trying to figure out the design, and not enough on research. My blog is still a work in progress and I'm hoping to make changes to it as I proceed with the course. 
