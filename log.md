# 100 Days Of Code - Log

### Day 1: June 1, 2019

**Today's Progress**: Create two shooting stars in Khan Academy Project Shooting Star. Started removing code from portfolio website.

**Thoughts:** Trying to do some JavaScript animations today. The biggest issue was trying to get the stars to go into different directions. Most of the time the stars just wanted to go in the same direction. I revisited the previous lessons and took several attempts at tweaking the xPos and yPos for the different stars to get them to go into different directions. I revisited my portfolio site and started removing some of the div tags in my code for the full-width, half-width, and third-width. I made some tweaks to the head tag such as the Google fonts link and style tags. I did create an assets folder to move my stylesheets and images to live in for the project. I'm not quite sure how to tackle the portfolio site quite yet so I need to wireframe my website before I tackle more code tomorrow.

**Link to work:** [Khan Academy](https://www.khanacademy.org/computing/computer-programming/programming/animation-basics/pp/project-shooting-star)

### Day 2: June 2, 2019

**Today's Progress**: Build Animal Attack Project in Khan Academy. Create animal with more JS animations. Added div tags to portfolio website.

**Thoughts:** Did more practice with JavaScript animations today. I made an animal in the Khan Academy Resizing Variables lessons. I found I was repeating code a lot often as I was putting together the animals so I went back over my code and change variables for any code I was going to repeat again. I did a little bit better job with the animations today. Originally the code in my animations was moving to the right side of the screen instead of staying in place, but I played around with the variables and numbers for the X and Y for the ellipse to keep everything in place. I started making tweaks to my portfolio website. I'm debating on adding more pages to my website and some JavaScript. I'm not sure what JavaScript to add to my website though. For now I'm going to see if I can focus on getting the HTML the way I'd like before I make bigger changes.

**Link to work:** [Khan Academy](https://www.khanacademy.org/computing/computer-programming/programming/resizing-with-variables/pp/project-animal-attack)

### Day 3: June 3, 2019

**Today's Progress**: Create an fictional advertisement for Khan Academy project Ad Design. Add two pages to portfolio site. Update index.html code for home page.

**Thoughts:** This project didn't have a lot of JS animations but I did add an animation as a bonus to the project to get more practice. I had an easier time getting the eyeSize variable to animate in this project. Although the mouth is still visible when the animation for the eyes is working, I am pretty proud that I was able to get the eyes animated today. The ad itself was kept very simple so I could practice using text(), draw(), and textSize(). I spend a lot of my time adjusting the x, y, w, and h when I add shapes or text. I spent the last 30 minutes working on my portfolio site. I did the wireframe last night so I'm updating the HTML code. I created two new folders for the new pages of my portfolio website and started adding code to the about page. I managed to get the navigation in the about page working. The styles are a mess, but I'll change the styles once I get all the HTML done for all three pages.

**Link to work:** [Khan Academy](https://www.khanacademy.org/computer-programming/spin-off-of-project-ad-design/5268645682446336)

### Day 4: June 4, 2019

**Today's Progress**: Build fishes for Khan Academy Project Fish Tank. Add more HTML tags to About and Portfolio pages. Update navigation on all pages.

**Thoughts:** Khan Academy outlines specific steps students to do in this project, but I spent most of my time making the fish. Refactoring the code was quite easy and I got a better sense of how parameters work in JS functions this way. The only issue was getting the fish to be different colors. Initially they were all turning white when I called the drawFish function. I eventually commented out the starter code Khan Academy provided including the variables and changed the fill() to color instead of bodyColor. I eventually realized when I was calling the function, I was using "purple" instead of color(). Once I used color() and changed the rgb values, the fishes started to change colors. I added the rest of the HTML for About and Portfolio pages. I added the rest of the sections on these pages. I had to change the navigation on the pages so no errors popped up when trying to move from one page to another. I tested each page locally to see if there were any errors. I'm going to start playing with the CSS tomorrow. I created a main.css file for all the base styles. This way I don't repeat the same code all on the stylesheets.

**Link to work:** [Khan Academy](https://www.khanacademy.org/computing/computer-programming/programming/functions/pp/project-fish-tank)

### Day 5: June 5, 2019

**Today's Progress**: Made a magic 8 ball for the Khan Academy project Magic 8 Ball. Fix vulnerable dependencies with Github repositories.

**Thoughts:** I made all the if-else statements for the magic 8 ball. Most of my time was spent playing around with the position of the text in the magic 8 ball. I was having a hard time getting the words centered the way I wanted in the triangle. I did start over this project twice because I was playing around with the > or < operators first then tried using the === to do each of the individual numbers. Originally I was planning on working on my portfolio website but I got an e-mail with some security vulnerabilities on a few of my repositories. So I used the time to do some googling to see how to fix them with the Github documentation and help.

**Link to work:** [Khan Academy](https://www.khanacademy.org/computing/computer-programming/programming/logic-if-statements/pp/project-magic-8-ball)

### Day 6: June 6, 2019

**Today's Progress**: Made a house in Khan Academy's Build a House project. Added bushes to the house.

**Thoughts:** The house project was a bit tougher than I was planning. I spent a lot of time trying to figure out how to get the windows to repeat on the house. I tried using a variable at first, but that wasn't working. I realized the fill() and rect() need to be inside the for loop, but I wasn't sure how to get them to repeat on the site. I figured I had to use the i somewhere in the rect() but I wasn't 100% sure if this was the right way of thinking. I did some googling and found some videos of people doing the same project. One of the videos was using the same method I was thinking about using. I was planning on making grass, but I spent a lot of time trying to get the triangles to look the exact shape I wanted. So I just used two rect() to make bushes instead. Started to work on the CSS for my portfolio. I was going to use a fourth stylesheet for the base styles but I decided it might get too confusing so I deleted the main.css file. I did start making some changes to the mobile.css and have some of the styles added to the home page. I spent a lot of time trying to get my Google Fonts to work. Tomorrow I'd like to play with the images on the mobile site to see if I can find the right size for them or find a position for them.

**Link to work:** [Khan Academy](https://www.khanacademy.org/computing/computer-programming/programming/looping/pp/project-build-a-house)

### Day 7: June 7, 2019

**Today's Progress**: Create rain drops for Khan Academy project Make it Rain. Added mobile CSS styles to home and about pages.

**Thoughts:** This has been the toughest JS project I've done for Khan Academy. Making the arrays for the rain droplets were easy. However I wasn't sure how to go about getting the rain drops to get back to the top. After trying different for loops, I searched YouTube to see what other devs have done. Amy Prosser's tutorials helped quite a lot. After using her tips, I played around with the code a bit to see how different numbers in the array worked and trying to see if I could get the raindrops to change color. I added more CSS styles to home and about pages. I played with the image sizes on the home page as best as I could, but I decided to make things bigger than I planned so they stand out on a mobile screen. The padding for the social media icons wasn't work very well. The padding made the icons move onto another row or go too far over to the left even when I tried to make spaces between them. I decided to just leave them the way they are for now. I just need to make some final tweaks to the about page's mobile css then I'm going to tackle the portfolio tomorrow.

**Link to work:** [Khan Academy](https://www.khanacademy.org/computing/computer-programming/programming/arrays/pp/project-make-it-rain)

### Day 8: June 8, 2019

**Today's Progress**: Made three books on a bookshelf for Khan Academy project Bookshelf.

**Thoughts:** This was a good exercise to get practice with on JS objects. Making the objects were easy. However I had trouble getting the books to appear on the bookshelf. After spending sometime playing with the for loop, I did some googling and used another Amy Prosser video to see what I was doing wrong. It turns out that I wasn't using the variables I made correctly. I needed to add them to the x and y positions then multiply them by 100 to get them to appear on the shelf and get the stars to appear. I tried changing the colors of the books, but I didn't have much luck since I kept getting errors trying to use the fill(). So I decided to just skip the color property for the books. I added the remaining CSS styles for the About page. I added h3 tags on the portfolio page for projects and changed the p tags into ul tags for projects. Most of the time was spent on getting the mobile CSS done. I removed CSS flexbox and checked everything in Dev Tools. So far everything is working fine without it. I started updating the responsive CSS for the home page. Right now the headers are not appearing on the page so I'll play with it more tomorrow and see if I can get it to appear on my site.

**Link to work:** [Khan Academy](https://www.khanacademy.org/computing/computer-programming/programming/objects/pp/project-bookshelf)

### Day 9: June 9, 2019

**Today's Progress**: Change some of the CSS styles in mobile style sheet. Add more CSS styles for responsive CSS style sheet so all HTML pages work on tablets. Began working on styles for the desktop version of my portfolio site.

**Thoughts:** I made some small changes to the mobile style sheet so I wasn't repeating a lot of code. Most of the time was spent on updating my portfolio's responsive style sheet. I can't get the navigation to look quite like I was planning so I visited my current portfolio site and realized I faced similar issues with the current version. So I'm leaving the navigation the way it is now and trying to update the rest of the styles for the site. So far responsive site preview I'm seeing in dev tools is looking quite similar to what I'm seeing on the mobile version of my website. I might play with the font sizes to see if I can make things bigger for the tablet version. I started to work on the styles for the desktop version of my website. My career compass section was indented when I added the padding to the navigation. I tried playing around with the padding, but it remained indented. I finally changed the height size of the header and everything moved into the right place.

**Link to work:** [Portfolio Website](https://github.com/BritishPandaChick/britishpandachick.github.io)

### Day 10: June 10, 2019

**Today's Progress**: Adding more CSS styles to the desktop portfolio site. Change font sizes for the mobile version of site.

**Thoughts:** I'm not happy with the font size on my portfolio site. I might play around with the font sizes once I get all the pages updated. Many of the elements are floating in the wrong places so I changed some of the heights of sections which resolved the problem. This isn't the case with the portfolio page. One of the projects it still floating in the wrong place despite these changes. I changed some of the div tags to see if the names were correct but things didn't improve. I eventually found a solution by creating separate full-width div tags for each project. I also created a project class for the div tags change the height and bottom padding for each project. I played around with the font sizes for the mobile CSS. Tomorrow I'm going to play around with the font sizes for the responsive and desktop CSS style sheets.

**Link to work:** [Portfolio Website](https://github.com/BritishPandaChick/britishpandachick.github.io)

### Day 11: June 11, 2019

**Today's Progress**: Add buttons to Portfolio page. Tweak CSS on pages.

**Thoughts:** Still updating all the CSS on the portfolio site. Some of the sections on the desktop pages were indented so I played around the CSS such as the padding and height. I removed some of the styles I had added previously. Biggest addition were the buttons for the portfolio page. I set up a script file for the entire site and added the link to all index files. I set up a script file for JavaScript and added jQuery to my website. I didn't work much with the JavaScript since I was looking at the documentation for JavaScript and jQuery to see what would the best way moving forward with making the button. At the moment jQuery seems like the best option but I think I'm going to try just using regular JavaScript to get it to work. I found one answer on StackOverflow that I've started. I'm going to test it with one of the blog buttons to see if it works. If it doesn't, I'll google to see if I find another way.

**Link to work:** [Portfolio Website](https://github.com/BritishPandaChick/britishpandachick.github.io)

### Day 12: June 12, 2019

**Today's Progress**: Added onclick attribute to button tags. Create separate functions for every button's onclick attribute. Change sizes of icons on HTML pages. Added more sections to About and Portfolio pages.

**Thoughts:** I made more changes to the index and CSS files. I removed the jQuery links I added yesterday and change the sizes to the Font Awesome icons. I added another li tag for my Github. I used the StackOverflow method I found yesterday. I tested it with some of the buttons on my website and everything worked perfectly. I added onclick attribute to each button and created separate functions for each button. I'm not sure how else I can add JavaScript to my portfolio site so I was doing some research on MDN web docs to see what else I could do. The last 30 minutes were adding new sections to the portfolio and about pages. I went into the CSS to add more styling on these sections so they would work on all devices. I'm going to wrap up most of the coding for the portfolio tomorrow since all that is left to do is change the copy.

**Link to work:** [Portfolio Website](https://github.com/BritishPandaChick/britishpandachick.github.io)

### Day 13: June 13, 2019

**Today's Progress**: Set up code files for Random Quote Machine project. Add content for Home and About pages. Tried fixing CSS issues for skills section on Home page.

**Thoughts:** I set up the code files for my next project Random Quote Machine for 30 minutes. I didn't get quite a lot of coding done on this project due to my computer running slow plus I wasn't sure if I should use React or not. I originally added React to the project, but I decided at the last minute to not use it in favor of getting more practice with basic vanilla JavaScript and some jQuery. In the CodePen I added some of the first few items from the test and made sure my files were connected. After fixing my computer, I started doing more revisions on my portfolio site. I removed some of the placeholder text to see how items would look with the real text added in there. As soon as I changed the text for the skills third-width elements, the skills summary at the bottom indented. I tried fixing it with the playing by adding padding to the skills p tags but it didn't do much. I will play around with the padding and height for the skills summary tomorrow.

**Link to work:** [Random Quote Machine](https://codepen.io/BritishPandaChick/pen/oLzoBG?editors=1011)

### Day 14: June 14, 2019

**Today's Progress**: Made a basic travel website for Khan Academy's Travel webpage project. Added quote array with objects inside Random Quote Machine. Made new section tag for other-skills. Change images to icons on home page.

**Thoughts:** The basic travel website isn't too fancy. I focused on doing the styling rather than making a fancy looking project. I just need to remember to watch the names of my classes and ids since I forgot to change the selectors after I changed the names for different tags. I used a little bit of time to start add more HTML to the Random Quote Machine. I added buttons for the clickable elements and started an array of quotes in my script file. I'm going to see if I can get the quotes to appear tomorrow in the quote box and name the buttons in the quote box. The last 30 minutes were making more updates and changes to my portfolio site. I removed the portfolio images and used Font Awesome icons instead. The design icon wasn't appearing on my website so I added the updated version of Font Awesome to my site. Once the style sheet was added, I started changing the padding and height to the Skills section. I decided to create a separate section for the other-skills instead of keeping in within the skills section id tag. This fixed a lot of the indenting that came from changing the padding. I made changes to the rest of the skills icons on mobile and responsive style sheets. I need to finish adding styles to the new #other-skills section on all the style sheets tomorrow.

**Link to work:** [Random Quote Machine](https://codepen.io/BritishPandaChick/pen/oLzoBG?editors=1011)
[Khan Academy](https://www.khanacademy.org/computing/computer-programming/html-css/intro-to-css/pp/project-travel-webpage)

### Day 15: June 15, 2019

**Today's Progress**: Changed quotes in Quote Machine. Created function for displaying quote. Added more copy to Home and Portfolio pages. Adjusted CSS for skills and other-skills sections on Home page for responsive and style files.

**Thoughts:** I decided to change directions on my quote machine project so I changed all the quotes I added yesterday. As soon as I did this, I started second guessing myself again on the quotes but decided to leave them the way they are now. I started to work on the first user story which is upon loading the machine a random quote is displayed in the text element. I managed to set up the function and create variables for the random number and random quote. However I'm wondering if I should just use a regular array for the quotes instead of objects. I did some googling and am looking in JavaScript & jQuery to read a bit more on JS objects. During the last 30 minutes I adjusted the height and padding for the skills and other-skills sections on the home page on all the style sheets. I started adding more copy to p tags on the Home page to see how this would impact the styles for the sections. It was a good thing I checked since the other-skills section indented as soon as I changed the height of the skills section. I started changing the padding on the portfolio page. This caused the elements to stack up on each other instead of being side by side. I'm going to play around with them tomorrow to see if I can improve the spacing a bit.

**Link to work:** [Random Quote Machine](https://codepen.io/BritishPandaChick/pen/oLzoBG?editors=1011)

### Day 16: June 16, 2019

**Today's Progress**: Change variables in Quote Machine. Managed to get author and quotes to appear on site. Continued to play with CSS styles for portfolio page on portfolio site.

**Thoughts:** After giving things lots of thought, I decided to change directions again on the quote machine. I changed the objects to separate variables for the quotes and the authors. I was having issues getting any text to appear on my site. It turns out that I forgot the quotation marks around the ids which is why nothing was appearing. As soon as I added the quotation marks everything started to appear on the browser. I managed to get the new quote button to work. I'm not sure how to get the tweets to open so I did some googling to see what I could find. During the last 30 minutes I tried adjusting the spacing and padding for the project bullet points. I ended up adjusting the height of the sections and padding on the images to make a few improvements. I added more content to the portfolio page. I need to double check mobile and responsive pages tomorrow to see how the new content impacts the styles. I was adjusting the community section and managed to switch the two half-width sections around. I need to double check the height of these sections in the desktop file to see if the contact section doesn't indent itself.

**Link to work:** [Random Quote Machine](https://codepen.io/BritishPandaChick/pen/oLzoBG?editors=1011)

### Day 17: June 17, 2019

**Today's Progress**: Trying to get tweet-quote button to work. Ran tests to see what works and still needs work on quote machine. Finish work on portfolio page on portfolio site.

**Thoughts:** Spent 30 minutes working on the tweet-quote button. Did lots of googling to just see how to get the window to open. The biggest challenge was getting the href attribute to work. So far I've managed to get the quote and the author to appear in the Tweet window. At first I kept getting undefined in the window. After looking at the Twitter Developers documentation and doing more searching on Stack Overflow, I was able to get the quote to appear. When I tried getting the quotation marks to appear, my site stopped working. I ran the tests and only one test isn't passing and that is the tweet button test. I'm going to see tomorrow if there is a better way to get the tweet button to work. During the last 30 minutes I removed ul and li tags for publications, awards and certifications. I used p tags for most of these elements. I created a brand new section for awards and added styles to all the style sheets. I changed some font sizes for li tags on my responsive style sheet so everything stayed consistent. Tomorrow I'd like to play with the padding of sections to see if I can push elements further away from the left side of the screen.

**Link to work:** [Random Quote Machine](https://codepen.io/BritishPandaChick/pen/oLzoBG?editors=1011)

### Day 18: June 18, 2019

**Today's Progress**: Tried getting the tweet button to work. Start adding padding and height to sections. Currently trying add height to mobile portfolio sections.

**Thoughts:** The first 30 minutes were trying to get the tweet button to work. I wasn't able to get much progress. I did read some of the forum posts for people's tweet button to see if I could have better luck. I tried using the attr() method for the link. I even created a global tweet variable to put part of the Twitter url inside. However none of my attempts worked. I'll keep googling and reading through the Free Code Camp documentation. Right now the button doesn't work at all and the tweet window doesn't even open. Luckily the other tests are still passing which means I can dedicate more time to the tweet button. The last 30 minutes were trying to get spacing for my portfolio page. I'm not 100% satisfied with the images on my mobile and responsive portfolio sites. I might remove the padding and just not make the icons centered in each section. Right now I'm working on adding height to the portfolio items in my mobile version of my portfolio site to see if it will it will help with the spacing. I'll play around with the padding for these elements tomorrow and see if I can make improve the spacing on the responsive version of my portfolio site.

**Link to work:** [Random Quote Machine](https://codepen.io/BritishPandaChick/pen/oLzoBG?editors=1011)

### Day 19: June 19, 2019

**Today's Progress**: Continue to work on tweet button work and pass the Free Code Camp tests. Added padding and height to responsive and main versions of portfolio site.

**Thoughts:** First 30 minutes were on getting the tweet button to work. I added back the original code I was using and began playing around with creating different functions to get them to work. It didn't work. I did more research on the Free Code Camp forums where I found about encodeURIComponent on one of the posts. I tried this with creating two variables for the text and the link. This managed to work. However the Free Code Camp tests still didn't pass. It turns out Free Code Camp wants the intent part of the URL in the href attribute on the HTML. I did more research on the Free Code Camp forums and found a method I'd like to try which adds the href attribute to a link in JavaScript. I saved the link to read tomorrow in my code and will try using the attr() again to see how it works. Last 30 minutes were updating styles for the responsive and desktop versions of the website. I just need to make some small changes to the portfolio page's award section on the main style sheet then portfolio updates will be done. I checked all versions of my site on Dev Tools and was getting mixed results when I looked at specific versions of the site. My responsive site initially didn't fill the entire screen. It would stay like this even when I refreshed the page. However when I exited out of Dev Tools and reopened it, it went back to the version I saw yesterday. I'll need to double check all versions of my site tomorrow before it goes live on the web.

**Link to work:** [Random Quote Machine](https://codepen.io/BritishPandaChick/pen/oLzoBG?editors=1011)

### Day 20: June 20, 2019

**Today's Progress**: Build a recipe book for Khan Academy project. Made final tweaks to the portfolio site. Got the tweet button to work and pass tests.

**Thoughts:** In the first 30 minutes I began building a recipe book for one of the Khan Academy HTML projects. I made a very basic version of this site on the Khan Academy platform. I spent a lot time trying organizing my HTML tags. I decided to add section tags to organize the recipes a little bit better. The lesson limited a lot of the styling I could do on the page so I might make a better version someday later. The last few minutes of this session were doing the final tweaks on my portfolio site. Now that is done, I have now made everything live on my site. Last 30 minutes were figuring out the tweet button. I read the article I saved in the pen and tried it in my code. It didn't work so I went back into the forums to see I could get more help. I tried my theory with the tweet intent URL in the HTML and strangely all my tests passed this way but the button didn't work. It took a few minutes, but I finally figured it out. I used what I originally planned which was putting the tweet intent link in a variable. I then used the attr() method to set the href attribute then created the URL with the tweet intent, randomQuote and randomAuthor variables. This made the last test pass. All I have left to do is add styles to the page. I'm going to play with the Bootstrap tomorrow.

**Link to work:** [Random Quote Machine](https://codepen.io/BritishPandaChick/pen/oLzoBG?editors=1011)
[Khan Academy](https://www.khanacademy.org/computing/computer-programming/html-css/html-tags-continued/pp/project-recipe-book)

### Day 21: June 21, 2019

**Today's Progress**: Started to add CSS styles to the Quote Machine. Add more HTML tags to organize code.

**Thoughts:** First 30 minutes were adding styles. I managed to get the fonts changed. I was trying out some of the Bootstrap classes to see if they could get the quote and author side by side for a few minutes. Bootstrap isn't one of my favorite things to work with in code since my project always looks different depending on the screen size so I find myself regularly looking at the page in several sizes to see how everything looks. I added an h3 and img tags for parts of my header. I organized the HTML with header and main tags. I spent some time trying to figuring out the sizing of the quote box but decided to play around with the height first and get the header organized the way I want before moving to the quote box. I tried centering the image with some of the Bootstrap documentation but found I was having better luck with the padding. In the last 30 minutes, I added the Twitter icon to the tweet button and make other final tweaks to the project. This included adding a footer at the bottom of the page and adding color. I tried putting some spacing between the new quote and tweet buttons for the mobile version. However the changes weren't showing up on Dev Tools when I checked the iphone preview. For now I'm going to leave it the way it is now but perhaps someday I'll go back into the project to change it. The style of this project is kept very simple. I thought about adding quotation marks around the quotes on the page but decided to leave it the way it is. When I ran final tests, the tweet button test failed. When I ran the tests again a couple more times, all the tests passed. While playing around with the page, it turns out that the tweet quote button just keeps showing the same quote even if the text on the page is showing a different quote. Tomorrow I'll see if I can fix the issue and get the button to reset the quote each time the new quote button is clicked.

**Link to work:** [Random Quote Machine](https://codepen.io/BritishPandaChick/pen/oLzoBG?editors=1011)

### Day 22: June 22, 2019

**Today's Progress**: Fix tweet button on quote machine project so tweets change with new quote.

**Thoughts:** First 30 minutes was just trying to use tips from the Free Code Camp forums to fix the tweet quote issue. Right now when you click the tweet button the window opens to show the quote that was on the page when the button was first clicked. If the quote changes, the tweet won't change when the button is clicked and still shows the quote from the first time the button is clicked. So far I've not been able to find much advice on the Free Code Camp forums for this issue. Right now I'm trying to use a function and create separate variables based on a method I saw in the forums. I have a second method I used during the last 30 minutes. This method involved using a widget but it didn't work. I found a complicated method in the Free Code Camp forums that went back to using the encodeURIComponent method. At first it didn't work. I kept being taken to another page saying there was an error. However this was due to me using some of the variables I used from a previous attempt. Once I changed the variables, everything began working. Right now the tweet button is working again. I am thinking about adding quotation marks around the quote in the tweet tomorrow to see how that works. My biggest issue is the testing. My tests were failing at first for the new-quote button and the tweet button. Yet running the tests again passed everything. Tomorrow I'll use sometime run through the tests and double check everything.

**Link to work:** [Random Quote Machine](https://codepen.io/BritishPandaChick/pen/oLzoBG?editors=1011)
