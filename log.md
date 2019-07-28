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

### Day 23: June 23, 2019

**Today's Progress**: Ran tests on quote machine. Added quotation marks inside textToTweet variable for quote machine. Set up pen and files for Markdown Previewer. Set up code files for sample portfolio site. Started adding HTML to the sample portfolio site.

**Thoughts:** First 30 minutes were doing final testing on the quote machine. When the tests run right when the page starts, only 11/12 tests pass. One situation had 10/12 tests passing. It seems when the buttons aren't pressed, the tests failed. However after testing the buttons and running the Free Code Camp tests, all 12 tests passed. It seems that the tests will fail if the buttons aren't used but will work when they do. After running several tests, I decided to leave my code since they all met the user stories. I might revisit this project in the future to see if I can get the tests the first time without any issues. The rest of that 30 minute session was getting the Markdown Previewer project set up. I admit I'm confused at what this project is about. So I might play around with the example project Free Code Camp has to just get an idea what they want me to build. I think this is a good project to use React so I spent some time just reading the documentation on the React site to make sure I'm setting things up correctly. I managed to add two HTML tags on the Markdown Previewer but I don't feel inspired building this project since I'm not sure what I'm suppose to build. For the second 30 minute session I decided to redo some of the sites I've been making for 30 Days, 30 Sites to do alongside the Free Code Camp projects. I was feeling overwhelmed and confused with the project overview for the Markdown Previewer so I thought the 30 Days, 30 Sites project would help me clear my head plus create projects to show as examples for a coding challenge I'm creating. First few minutes in this session were just getting everything organized and doing the setup. I've got a good start on the HTML code and have some of the tags added. I will try finishing the HTML tomorrow. My goal for the 30 Days, 30 Sites portfolio is to get a better sense of Bootstrap and getting it to work on mobile devices so I'll be focusing more on Bootstrap with this portfolio than the portfolio site I just made updates on.

**Link to work:** [Random Quote Machine](https://codepen.io/BritishPandaChick/pen/oLzoBG?editors=1011)

### Day 24: June 24, 2019

**Today's Progress**: Add more HTML code to the Markdown Previewer. Finished set up on Markdown Previewer. Add more HTML to 30 days 30 sites portfolio site. Began adding CSS styles.

**Thoughts:** After yesterday's session I played around with other people's markdown previewers including the Free Code Camp example to get a better understanding how the project works. This helped me get a better idea of what I will be building. I did add some more HTML tags to the Markdown Previewer. Some of the tags will just be reference for what when I'm building so they won't be in the project the entire time. The first 30 minutes were really just trying to get react set up on CodePen correctly. This took more time than I anticipated since I added some of the wrong links for React in CodePen so I double checked the documentation to make sure I was doing it right. I didn't start a lot of the JavaScript yet. My goal tomorrow is to just make sure everything is connected before I even start trying to figure out the user stories. During the last 30 minutes I added more HTML to the 30 Days, 30 Sites portfolio site. I added Google Fonts and Font Awesome. I did start some of the CSS styles but some of my text isn't changing. I'm going to double check my style sheet links tomorrow when I start adding more styles. I also would like to play around with the layout and start putting together the different versions of this website to see what Bootstrap classes I can use.

**Link to work:** [Markdown Previewer](https://codepen.io/BritishPandaChick/pen/YoVaZm?editors=1010)

### Day 25: June 25, 2019

**Today's Progress**: Made sure React was connected to pen. Started using some of the React documentation. Remove contact section from 30 Days, 30 Sites portfolio site. Began adding CSS styles to portfolio site.

**Thoughts:** The React documentation lied. The setup took me way longer than a minute to set up. It turns out the HTML code I had added earlier was throwing off everything in React. So I changed around classes and removed most of the original code I added a few days ago. As soon as I changed the classes to ids and removed all the extra code, everything slowly started working. I spent the first 30 minutes just trying to get "Hello World" to appear so I mostly was troubleshooting all the errors from the setup. So I was mostly reading the documentation and using the documentation sample code to just get "Hello World" to appear. Once "Hello World" appeared, I started a bit of work trying to get the first user story done. Last 30 minutes were adding styles for the 30 Days, 30 Sites portfolio page. I figured out why my fonts weren't appearing on my site. It turns out I used font-size instead of font-family. I didn't work too much with the HTML today but I did remove the contact section at the bottom. I began adding styles. I spent a lot of time trying to change the color of jumbotron. Tomorrow I'm going to play around with the header's container class to see if I can add a background color for the header. Once I've got most of the styles done, I want to use the time to start playing around with the Bootstrap classes to see how everything looks on different mobile devices.

**Link to work:** [Markdown Previewer](https://codepen.io/BritishPandaChick/pen/YoVaZm?editors=1010)

### Day 26: June 26, 2019

**Today's Progress**: Made an HTML & CSS blog for Khan Academy Project Blog. Create a React Component for Markdown Previewer. Added more CSS styles and Bootstrap classes to 30 Days, 30 Sites Portfolio.

**Thoughts:** First 10 minutes were building a project for a Khan Academy course. Building this project keeps getting me thinking about building my very own blog site. The Khan Academy version is very simple since the project is meant to give users practice with font-family, font-style, and line-height. Working on this project was simple, but I was thinking throughout the process of building my own blog site again. Once the blog site was finished, I spent the rest of the first 30 minute session working on the Markdown Previewer. Most of this time was starting to set up the React Component. I didn't do a lot of coding since I was reading the documentation on React and looking at posts on StackOverflow. I realized that the best way to start user story one is creating a form. So in the render() I began setting up the form for the editor and preview areas. I did manage to find some documentation on the ReactJS site for textarea tag. I'm going to try the documentation's example tomorrow and see how I can customize it to be the editor for this project. The last 30 minutes were making more CSS updates to the 30 Days, 30 Sites portfolio. I added some more CSS for the highlights and footer sections. Today I went back to HTML to start playing around with the Bootstrap classes. Right now I'm working on the mobile version of my portfolio site. So far everything isn't looking all over the place like most of my previous Bootstrap projects. All I need to do is finish the footer then I'll move onto styling the responsive tablet version of this portfolio. I just need to add the float property to the footer.

**Link to work:** [Markdown Previewer](https://codepen.io/BritishPandaChick/pen/YoVaZm?editors=1010)
[Khan Academy](https://www.khanacademy.org/computing/computer-programming/html-css/css-text-properties/pp/project-blog)

### Day 27: June 27, 2019

**Today's Progress**: Added React Component to Markdown Previewer then deleted it. Spent time troubleshooting React Component render method. Attempted to fix footer. Added navbar to 30 Days, 30 Sites portfolio site.

**Thoughts:** The textarea documentation wasn't working for me. After finishing the documentation, I wasn't getting any results. I kept looking at the React documentation, but I also looked at a couple of YouTube videos just to double check my setup. I thought my original HTML was throwing off my code so I deleted it. It turns out that I was writing JSX wrong the entire time especially in the render method. I kept getting an error message in CodePen throughout today's session. Originally I was using h1 and h2 tags inside the render element and the error message saying adjacent tags must be wrapped in enclosing tags. After several attempts, the error message finally turned off as soon as I changed the h1 and h2 tags into div tags. I decided to just keep the header tags just in the HTML and concentrate on building the react inside the render(). In the last 30 minutes, I played around with the footer in the 30 Days, 30 Sites portfolio site. I wasn't able to accomplish my vision yet for the footer. I need to use row class on some of my elements to get them in a row. I will try that tomorrow. I didn't work on the mobile version of the portfolio today. I saw Colt Steele using Bootstrap to make a navbar in an app when I was working on my coding tutorials and I wanted to try it for this project. So most of my time was spent looking at the Bootstrap documentation and getting a navbar at the top of the page. I removed the jumbotron classes and some of the header styles but I have a start on the navbar. I just need to figure out how to get the nav links to line up besides each other just like in the documentation instead on top of each other. Once the navbar is finished, I'll go back to working on getting the site on different screen sizes.

**Link to work:** [Markdown Previewer](https://codepen.io/BritishPandaChick/pen/YoVaZm?editors=1010)

### Day 28: June 28, 2019

**Today's Progress**: Solved user stories 3 and 4 for Markdown Previewer. Added some basic CSS to previewer to see what I'm working with. Finished working on header navbar on 30 Days, 30 Sites portfolio. Add row classes to header, highlights, and footer.

**Thoughts:** First 30 minutes were working on getting the editor to show text and for the previewer to show the results. I did use some documentation and Ben Brooke's YouTube tutorial to help. My biggest issue was the editor disappearing as I was working. As I was working, my editor and preview kept trying to disappear as I as working in the JS file. I put the container element inside a div tag and everything stayed on a page. I forgot an underscore when I was setting the dangerouslySetInnerHTML attribute for the preview editor. This gave me more errors in CodePen. I also need to remember when working with React I can use self closing tags. While reading the documentation and watching Ben's video, I noticed some of the divs and textarea tags could be used as self closing tags. Right now my tags in React have opening and closing tags but I'll have to remember for future React projects to try some of the self closing tags. During the last 30 minutes, I finished working on the navbar. I rearranged some of the nav classes and added a div with the row class. This got everything on the navbar lined up. However the headline and navigation items seem very close. I tried using justify-content-end to see if this would right align the list items while I float the items right. It didn't work. The items just stayed in the same place. I decided to just leave them the way they are now so I can concentrate on other areas of the portfolio. I added more div tags with the row class to highlights and footer. Initially the highlights items weren't in a row. This was due to the classes I was using for the columns. Once I changed the columns from col-xs to col the elements lined up nice and neatly in a row. Tomorrow I will play around with the column sizes so everything doesn't look so cramped on the page.

**Link to work:** [Markdown Previewer](https://codepen.io/BritishPandaChick/pen/YoVaZm?editors=1010)

### Day 29: June 29, 2019

**Today's Progress**: Trying to solve user story 5 for Markdown Previewer. Set markdown for elements in the user story. Add overflow property to previewer. Update highlights section for 30 Days, 30 Sites portfolio page. Add headline and new div class. Fix footer.

**Thoughts:** I spent 30 minutes trying to solve the fifth user story for the Markdown Previewer. Right now the test is failing. I have been using Ben Brooke's tutorial and doing some googling for documentation to see what I'm doing wrong. I'm not having much luck. Right now the list markdowns are what are being addressed in the error message. Tomorrow I'm going to read through the list documentation to see what I'm doing wrong. I'll still check the rest of the markdowns to make sure they pass but the tests are pointing to the lists items so I'll see what I can find on Google. But I enjoyed learning about the markdown documentation. I'll definitely have to try out some of the markdowns in the future when I get a chance. The last 30 minutes were more work on the 30 Days, 30 Sites portfolio page. I fixed the footer by changing the column sizes. I played around mostly with the highlights section of the portfolio site. I added a headline Latest Posts and an h4 tag for the dates of each posts. I removed the video I added earlier and replaced the p tags with images. I did add some styling to these elements but most of the style changes were adding padding and height properties. I did add some styles to the navbar at the top of the header such as changing the colors, adding a background color. Most importantly I removed a container class the navbar and headline were wrapped around so it would extend the entire container just like the footer. Tomorrow I'm going to fix the padding for the images in the highlights and do some final style changes for the footer before I start seeing how the site looks on different screen sizes.

**Link to work:** [Markdown Previewer](https://codepen.io/BritishPandaChick/pen/YoVaZm?editors=1010)

### Day 30: June 30, 2019

**Today's Progress**: Fix issue with the list markdown for the Markdown Previewer. Pass tests for optional user stories. Start adding styles and Bootstrap classes to 30 Days, 30 Sites portfolio so it can work responsively.

**Thoughts:** During the first 30 minutes, I managed to get all the functionality for the Markdown Previewer done. I did some more googling and used the Ben Brooke's YouTube tutorial to help me. It turns out that I forgot a space between the text and the hyphen. As soon as I put a space, the previewer showed bullet points for the list items and the tests passed. The rest of the time was spent trying to get the optional tests to passed. I felt kind of silly about the break testing since I spent a lot of time googling how to use JavaScript to render carriage returns into line breaks when all along there Marked.js documentation how to do it in a much simpler way. I was on the right track with the renderer object. I initially tried using inside marked.setOptions. However Ben Brooke's method was much easier which involved creating a renderer variable then creating a function which sets the renderer's link and target attributes. All the mandatory tests pass and the optional ones pass as well now so I just need to focus on styling the page. The last 30 minutes were making changes to the 30 Days, 30 Sites portfolio site. I took a few minutes to play around with the padding for the highlights images and footer. Most of the time was spent on seeing how the site worked different screen sizes. This mean playing with the Bootstrap classes and seeing how they looked in Dev Tools. I managed to get the mobile version done since there weren't too many changes. I mostly had issues trying to get the right Bootstrap classes for the footer and highlight posts. Tomorrow I'm going to see if I need to make any changes for tablet screen size and make sure the desktop version needs any changes.

**Link to work:** [Markdown Previewer](https://codepen.io/BritishPandaChick/pen/YoVaZm?editors=1010)

### Day 31: July 1, 2019

**Today's Progress**: Trying to set up React locally on computer. Updated CSS styles for mobile version of 30 Days, 30 Sites portfolio.

**Thoughts:** First 30 minutes were mostly reading the React documentation. I wanted to try setting up React on my computer so I could see how the markdown previewer project worked locally. I wasn't having any luck getting the project working. I tried 4-5 tutorials to get everything set up but it wasn't working. I'll try the Create React App method again later to see if I can get it to work. During the last 30 minutes, I was working on the CSS for the 30 Days, 30 Sites portfolio. The mobile styles were not appearing on Dev Tools preview. Once I exited out of the preview and played with the window sizes, the styles began appearing. At the end of the session, I checked to the previewer again to see what appeared and the styles I've been adding over the past 30 minutes were appearing in different sections throughout the page. However the styles are just fine when I adjust the browser window according to the pixel size. I've been adding most of the CSS styles for the mobile version of the site so I'll check tomorrow how everything looks in Dev Tools and see if I can fix it.

**Link to work:** [Markdown Previewer](https://codepen.io/BritishPandaChick/pen/YoVaZm?editors=1010)

### Day 32: July 2, 2019

**Today's Progress**: Start adding and updating styles for Markdown Previewer. Add more Bootstrap and CSS to 30 Days, 30 Sites portfolio site.

**Thoughts:** The first 30 minutes were adding styles to the Markdown Previewer. I took a couple of minutes to run through the tests and make sure everything was passing both on the CodePen pen and on my local computer. I changed around some of the variable names and added some documentation for specific parts of the code. Writing the comments was a little bit harder than I anticipated since the code wasn't appearing in the editor right away but I managed to add a couple of comments. The rest of the time was adjusting the CSS. I added a paragraph tag in the HTML for the directions and changed the columns for the container to rows. Then I just played around with the padding and the height. I just need to make a few smaller changes this project's CSS tomorrow then it should be ready to be submitted. Last 30 minutes were making more changes and updates to the 30 Days, 30 Sites portfolio page. I figured out what was wrong with the site preview in dev tools. I forgot to add a meta tag for the view port. As soon as I added this in the head tag, the preview inside Dev Tools changed to reflect the changes I was adding. After fixing the viewport, I managed to get the mobile version of my site done. I was having issues with the buttons still trying to be right beside the images. However adding the btn-block class immediately put the buttons underneath the images in the highlight class. Tomorrow I need to finish adding styles to the tablet version of my site then see how everything looks in the desktop version.

**Link to work:** [Markdown Previewer](https://codepen.io/BritishPandaChick/pen/YoVaZm?editors=1010)

### Day 33: July 3, 2019

**Today's Progress**: Add remaining CSS styles to Markdown Previewer. Add header, main and footer tags to HTML. Finish adding CSS styles for 30 Days, 30 sites portfolio. Started preparing code files for 30 Days, 30 Sites event invitation.

**Thoughts:** During the first 30 minutes, I finished updating the CSS styles for the Markdown Previewer project. These styles were less adding colors but getting the layout just right and playing with the padding. Any styling was for the newest additions such as header, footer and main tags. I did rearrange the markdowns in the JS Pen file. The CodePen file is done but I am going to test all the changes I made locally on my computer to see how everything looks. The last 30 minutes were just wrapping up final projects. The first few minutes were just adding the rest of the changes to the local version of the Markdown Previewer and running the tests to makes sure everything worked. I didn't need one line of code at the top for the React Component so I deleted it and just used import React from 'react'. Once the Markdown Previewer was done, I wrapped up styles for 30 Days, 30 Sites portfolio. I add mostly Bootstrap classes so it would work on medium and large size screens but I did add a little bit of padding to certain elements for the large screen size. Once those changes were done, I used the leftover time to start setting up for one of tomorrow's new projects. Tomorrow my goal is to focus on getting the event invitation completely set up and ready so I can get most of the HTML done.

**Link to work:** [Markdown Previewer](https://codepen.io/BritishPandaChick/pen/YoVaZm?editors=1010)
[30 Days 30 Sites Portfolio](https://codepen.io/BritishPandaChick/full/OjoKjL)

### Day 34: July 4, 2019

**Today's Progress**: Setting up code files for Drum Machine project. Add HTML for drum machine, display and drum pads. Update HTML for 30 Days, 30 Sites event invitation. Started to style the header.

**Thoughts:** First 30 minutes were setting up the Drum Machine. I was setting up both the CodePen and a local one. After the debacle with the Markdown Previewer, setting up the local version was much easier and quicker. I managed to get two user stories to pass. These stories were mostly the elements for the drum-machine and display. I was working on the drum pad elements. I wasn't sure where to get the sounds so I was looking at Ben Brooke's tutorial just to see where he got his sounds. I found the link in his comments section and managed to add one sound in a sounds objects. Tomorrow I'll finish adding the sounds then I'll see getting audio element test to pass. The last 30 minutes were finishing organizing the 30 Days, 30 Sites event invitation. I started adding the HTML code for the project. I'm still using parts of the original version during the first round of 100 days of Code but most of the time was getting most of the code organized. I'll add more Bootstrap as I go throughout the project. I did add some additions such as the navbar at the top of the page. I did start some CSS styles for the project. Right now I'm working on getting the navbar ready before I move onto the rest of the header.

**Link to work:** [Drum Machine](https://codepen.io/BritishPandaChick/pen/mZjxWN)

### Day 35: July 5, 2019

**Today's Progress**: Debug issues with Drum Machine. Finish adding sounds to sounds object. Add React Component for DrumPad element. Finish adding styles for navbar on 30 Days, 30 Sites event invitation. Started adding styles for header.

**Thoughts:** During the first 30 minutes, all my tests for the drum machine I completed yesterday failed during one test run. At the time, I had individual drum pad elements within the display div tag which were passing as part of the initial tests. When I was adding a React Component, all the tests suddenly started to fail. So I spent a good chunk of the time figuring out why the tests weren't passing. I had to rewrite my original code several times but the original tests I passed yesterday turned green again. While watching the Ben Brooke's tutorial, I decided to try out his React Component method for the Drum Pad element. I set up most of the React Component so far. I just need to figure out to create the unique ids and get the drum pad elements to trigger. In the last 30 minutes, I was trying to figure out how to style the navbar. The links were still stacked up on each other so I was playing around with the Bootstrap classes. I was trying to use the documentation examples to troubleshoot the issues. Eventually I managed to get the link elements to be inline with each other by rearranging the Bootstrap classes. I did start adding styles for the header. Tomorrow I will concentrate on getting the header to work particularly getting the text in the middle of the background image if possible.

**Link to work:** [Drum Machine](https://codepen.io/BritishPandaChick/pen/mZjxWN)

### Day 36: July 6, 2019

**Today's Progress**: Work on the DrumPad react component. Added Bootstrap classes and CSS styles for header, story and celebration sections on 30 Days, 30 Sites event invitation page.

**Thoughts:** I did some more work on the react components for the drum machine. Before I started working, I ran more tests to see if all the tests I passed yesterday were still green. At first they weren't so I did some debugging. It turns out the errors were coming from the sounds variable and how they were called in the return method. As soon as I fixed the issue, the tests passed. Most of my time was spent trying to get the fourth test to pass. At the end of the 30 minute session, I was getting errors for the user story test five. The Q id isn't triggering when it is called which is causing both tests five and six to fail. So far I checked Q object to see if there were any errors. Tomorrow I'll do more debugging to see if I can fix the issue. I finished the header. Although I used some of my original code from the first round of 100 Days of Code, I played around with the styles for the background image. A lot of time was spent on the story section. The columns were stacking on top of each other. It turns out that I forgot the row class which helps get the elements inline with each other. Tomorrow I'll have to remember to use the row class when I work on the location. I added styles for three sections today. I just need to finish the celebration section then I can start tackling the location one tomorrow. I need to start thinking of how to add JavaScript to this project. I might create a modal for RSVP like the W3Schools example but I'm not sure yet.

**Link to work:** [Drum Machine](https://codepen.io/BritishPandaChick/pen/mZjxWN)

### Day 37: July 7, 2019

**Today's Progress**: Pass user story 5 for drum machine. Started adding CSS styles and set a handleClick function to trigger audio sounds. Add more Bootstrap classes and CSS styles to 30 Days, 30 Sites event invitation. Finished styles for location and info sections.

**Thoughts:** During the first 30 minutes, I spent a lot of time running the tests and making sure everything was passing. After some debugging, I focused on getting user story 5 to pass to get the audio to trigger when the drum pad element is clicked. I started adding some CSS styles for the drum pad elements. Initially they didn't appear on the screen because I misspelled the id name. Right now these styles are temporary. I plan on updating the styles once all the React is done. I spent a few minutes trying to fix the padding for the header greeting. I managed to get it centered in the middle of the background image, but I tried getting the text over towards the left so it wasn't covering Emma's face. However I ran into issues with the text editor so I just left it the way it is for now. I might play around with it again later. I added a new p tag in the location section. Out of the two sections I did today, location is where I spent most of my time. I was playing around with the columns, image and text to get all the elements the right size and spaced right. I decided I am going to make a modal for the invitation. Tomorrow I'm going to finish adding styles for the rest of the site before I tackle of the JavaScript. I'll do the responsive design once the JavaScript is all done.

**Link to work:** [Drum Machine](https://codepen.io/BritishPandaChick/pen/mZjxWN)

### Day 38: July 8, 2019

**Today's Progress**: Pass user stories six and seven for drum machine. Add some temporary styles for the drum machine display. Add Bootstrap and CSS styles for response and footer sections in 30 Days, 30 Sites event invitation. Started to add JavaScript for modal.

**Thoughts:** I passed the remaining user stories for the drum machine. Before I started working on the user story tests, I did run the tests to make sure the existing tests still passed. The hardest test to pass was the user story six. I put charCodeA instead of CharCodeAt in my handleKeyDown function. This messed up the componentDidMount and componentWillUnmount. Now that the JavaScipt is done, tomorrow I will be doing more updates on the CSS. Response and footer sections in the event invitation are now styled. Most of the time was spent getting started on the modal. I added the modal to my HTML and started adding the styles. I began adding some of the JavaScript to the modal. Right now the modal isn't showing when I click the button so I'm going to have to do some troubleshooting tomorrow. The console is saying the issue is for the close button. Tomorrow I'm going to debug JavaScript and see if I can get it to appear.

**Link to work:** [Drum Machine](https://codepen.io/BritishPandaChick/pen/mZjxWN)

### Day 39: July 9, 2019

**Today's Progress**: Began add CSS and Bootstrap to drum machine. Change data variable to sounds. Update HTML, CSS and JavaScript for modal in 30 Days, 30 Sites event invitation. Tried to get the modal to appear on the screen when button is clicked.

**Thoughts:** I started tweaking some of the JavaScript for the drum machine app. Biggest change was the sounds variable. I changed around some of the sounds and replaced the variable data to sounds. I made changes in the rest of the JavaScript file. I did run lots of tests to make sure everything was still passing. The rest of the time was starting to add styles for the app. The header styles are done and I'm halfway through the styles for the app. Tomorrow I'll finish the app styles and the footer. I was trying to get the drum pads to be in rows of three but I was putting the Bootstrap classes in the render function for the app instead of the drum pads. Tomorrow I'd like to try adding Bootstrap classes for the DrumPad render function to see what happens. I spent 30 minutes working on the modal. I didn't have much success. I did resolve the error with the close button. However the modal is still not appearing on the screen. When I opened Dev Tools, everything is working smoothly. I spent lots of the time looking at JavaScript documentation and reading articles to try different techniques but nothing changed. I think the issue might be in the event listeners and functions. Right now I am trying another tutorial to see if that works. If it doesn't, I'm going to redo the pseudo code and take away the CSS to see if I can get a basic version to appear.

**Link to work:** [Drum Machine](https://codepen.io/BritishPandaChick/pen/mZjxWN)

### Day 40: July 10, 2019

**Today's Progress**: Finish adding CSS styles to Drum Machine. Made final changes to Drum Machine code and ran final tests to make sure everything is consistent. Remove JavaScript code I've been using. Rewrote all modal code in HTML. Add links for jQuery and Bootstrap for JavaScript.

**Thoughts:** I finished the drum machine in the first 30 minutes. I looked over the notes from yesterday's log and thought about trying to put the drum pads in columns stacked on top of each other. However I decided not to try it since I played around with the padding and height for the drum pads in a way I liked and I didn't want to change it. Maybe some day I'll revisit the project and try putting the drum pads rows of three. I ran the tests to make sure everything passed on CodePen then I ran the tests for my local file to ensure everything was consistent. When I saw the local preview, the id was still close to the border so I made a few adjustments to the padding, height and margins for the drum pad elements. I added the rest of the remaining styles for the footer and drum pads. I spent all my time trying to get the RSVP button to work. The original documentation I was trying to use wasn't working. So I did some googling to see what I could find. In the end, I decided to start over completely. I removed all the CSS and JavaScript code I had written. I began to redo the modal code itself. I read online to add links to the jQuery and Bootstrap JS file so I added those links to see if they would help. Right now I'm going back to using the W3Schools documentation. I'm going to also check out the Bootstrap documentation to see if I can at least get something to appear on the site.

**Link to work:** [Drum Machine](https://codepen.io/BritishPandaChick/pen/mZjxWN)

### Day 41: July 11, 2019

**Today's Progress**: Fixed dependencies issues on Github.

**Thoughts:** I got more notifications of issues for some Github projects so I spent today's sessions troubleshooting these errors instead of getting started on a brand new project. I spent most of the time reading documentation and googling in order to fix the issues.

### Day 42: July 12, 2019

**Today's Progress**: Made an basic invitation for Khan Academy Event Invite project. Add more div tags to 30 Days, 30 Sites modal. Update CSS styles. Managed to get modal to toggle on with JavaScript. Began adding JS code to get the modal to close.

**Thoughts:** First few minutes were building another Khan Academy project. The event invite project is similar to the 30 Days, 30 Sites project I'm working so I made a basic version. I didn't play with a lot of the CSS properties in the lesson and instead focused on creating a basic version that resembles an invite you might see. Khan Academy limits most of the styling you can do on their platform so I wasn't able to do as much as I would like. Perhaps someday I'll make a better invite on CodePen or locally on my computer. After the Khan Academy invite, I started to do set up for the JavaScript calculator. I'm not going to use React for this project and am going to use jQuery as well as regular vanilla JavaScript if possible. I just need to finish the rest of the set up tomorrow. This includes adding code for the first three user stories. Perhaps I'll be able to start tackling the JavaScript tomorrow. I finished removing the Bootstrap modal code. I organized the modal code into different div tags for the modal header, body and footer. I started to add more CSS to the modal code. I originally had padding and height set for some of the modal elements but I removed them in order to play around with the .modal padding to see why it was moving the modal into the center of the page. I revisited the W3Schools modal tutorial and began having better luck with adding most of the CSS. I started adding the JavaScript. So far the variables are done. I am getting an error saying the onclick property isn't working so tomorrow I'm going to be doing some debugging to see onclick isn't working despite the button allowing the modal to open when it is clicked.

**Link to work:** [Khan Academy](https://www.khanacademy.org/computing/computer-programming/html-css/css-layout-properties/pp/project-event-invite)
[JavaScript Calculator](https://codepen.io/BritishPandaChick/pen/ZpZZEX?editors=1010)

### Day 43: July 13, 2019

**Today's Progress**: Continue setting up JavaScript Calculator HTML code. Fix issues for modal in 30 Days, 30 sites event invitation. Got modal to close. Move modal code closer to the RSVP button.

**Thoughts:** First 30 minutes were just setting up the JavaScript Calculator. I'm starting to second guess what I'm doing based on reading the user stories but I decided to try seeing if I can make the tests without React. Most of the time was spent trying to get the HTML organized the way I wanted to and just trying to get the buttons to mimic what you would see on an calculator. I added a button for the AC but I'm leaning towards deleting it since it isn't required by the user stories. I think I'm going to DRY up the code I have tomorrow before I tackle the JavaScript and particularly see about getting the calculator centered in the middle of the page. Right now everything is on the left side. While the display can be center in the page, the buttons weren't cooperating. I don't want to start doing lots of styling but I might need to add some temporary CSS so I can see what I'm doing as I move into the JS. I'm almost in the home stretch with the modal. I figured out why I was getting errors in the console. It turns out that I added the punctuation for the IDs and classes was causing the onclick errors. As soon as I removed the punctuation in the variables, everything started to pass and it began start acting as a modal. The only issue I have now when the modal closes, the backdrop still remains dark. I will try playing around with some of the JS code to see if I can get the backdrop to get back to normal. I started playing with the JS a little bit, but I wasn't having much luck. I think I might have to try setting the data attributes but I'm not 100% sure if that is the right solution.

**Link to work:** [JavaScript Calculator](https://codepen.io/BritishPandaChick/pen/ZpZZEX?editors=1010)

### Day 44: July 14, 2019

**Today's Progress**: Add temporary CSS styles to JavaScript Calculator. Reorganized HTML code. Fixed modal backdrop. Tried making responsive styles for 30 Days, 30 sites event invitation. Started set up for next project.

**Thoughts:** I'm having issues getting the calculator to look just the way I want in HTML. I removed some of the Bootstrap classes and started playing around with the tags to see if I could get them in the center of the page. I added some CSS styles to help me see where everything is on the page. This is mostly old code I used before but it is temporary. Once all the JavaScript is added, I'll replace all the old styles with brand new code. Tomorrow I'm going to play around with the CSS to see if I can get it to look like a calculator on CodePen instead of a bunch of buttons grouped together in the middle of the page. I fixed the modal backdrop. After reading some of the documentation and some articles, I decided to just remove the data attributes on the modal button. Once I removed the data attributes I added some background color to the modal. This make a huge difference and would be removed when the modal closed. I tried working on the responsive styles for the site but Dev Tools was acting up. When I was refreshing my site preview, Dev Tools immediately paused the site in the debugger. I tried googling for a solution but I wasn't having much luck. I finally got frustrated and decided to switch gears by starting set up on the next project. Tomorrow I'm going to try again to see if I can get the responsive styles to work in the previewer but if I can't I'll just move onto the next project.

**Link to work:** [JavaScript Calculator](https://codepen.io/BritishPandaChick/pen/ZpZZEX?editors=1010)

### Day 45: July 15, 2019

**Today's Progress**: Finished adding HTML and CSS code for JavaScript Calculator. Started adding JS variables. Remove Bootstrap classes for navbar in 30 Days, 30 Sites invitation. Start adding mobile CSS styles.

**Thoughts:** First 30 minutes were playing with the Bootstrap for the JavaScript Calculator. I added back the divs with the row class for the buttons. I tried playing with the margin for the a tags but it was creating too big of a space between the buttons. I decided to wrap all the buttons in a container with the buttons class. I used the buttons class to add styles and play with the margins. This worked and got the buttons in the center of the calculator. I don't think the padding I set for the display is going to work as I start doing calculations with the JS later, but I'll wait until all the JS code is done to fix. it. I did start on some of the JS. Right now I'm adding the variables. Tomorrow I'd like to get user story 8 to pass in the tests. I did some googling before starting this coding session to see what was going on with Dev Tools. I did manage to get it fixed, but I was just clicking around with elements in the source window. Whatever I did do I fixed everything. During the session, the navbar wasn't fitting on the entire page when it was on a mobile screen. I ended up removing the navbar Bootstrap classes which fixed the problem. I'll just need to use CSS to replicate what I originally had. I started adding the mobile styles to the site. I was originally was going put all the styles in the same style sheet, but I decided to add a CSS folder and create separate files for different stylesheets for each. Right now I'm working on the mobile styles. Biggest issue I have is the input is cutting off near the left side of the screen when the modal is open. Tomorrow I'll see if I can change the CSS so that doesn't happen on the mobile version of the modal.

**Link to work:** [JavaScript Calculator](https://codepen.io/BritishPandaChick/pen/ZpZZEX?editors=1010)

### Day 46: July 16, 2019

**Today's Progress**: Pass the user story test seven for JavaScript Calculator. Started working on getting user story 8 to pass. Tried to fix input for mobile modal. Add styles for responsive version of 30 Days, 30 Sites invitation.

**Thoughts:** First 30 minutes were working on getting the user story seven to pass. I managed to get the test to pass and get the preliminary code up for the buttons working. Right now nothing is able to display when the buttons are clicked. Tomorrow I'm going to do some debugging for the functions I added to see if I can get something to appear on the span tag. Finished the mobile and responsive CSS styles. The input on the mobile still looks like it is being cut off near the left side. I tried fixing the CSS but wasn't having much luck so I'll just leave it the way it is. I did start adding CSS styles for the responsive tablet version of the site. I spent a lot of time deciding on specific Bootstrap classes for the location and story sections. I decided to use col-md-12 instead of col-md-6 since the columns looked as if the images were being squashed together. I added some padding for the p tag in the location section so there was a little bit of space between the image and text. Tomorrow I'm going to tackle the navbar on the desktop version. Without the Bootstrap classes, I'm going to need to figure out how to recreate the same thing using CSS.

**Link to work:** [JavaScript Calculator](https://codepen.io/BritishPandaChick/pen/ZpZZEX?editors=1010)

### Day 47: July 17, 2019

**Today's Progress**: Tried to debug JavaScript Calculator. Removed JS code and started from scratch. Played around with screen sizes for media attribute in HTML file for 30 Days, 30 Sites event invitation. Tried getting CSS for main stylesheet to appear on website.

**Thoughts:** First 30 minutes were trying to fix my JavaScript Calculator. I tried getting the calculator to show the inputs but nothing was appearing on the screen. I didn't spent much time coding but reading documentation and googling. After several attempts, I decided to remove my original JS code and start over. Right now the tests say all 9 tests are passing but in reality only 6 tests pass. Tomorrow I'm going to see if I can get user story seven to pass again. I didn't have much luck with getting the navigation to appear. I thought the problem was the screen sizes so I tried playing around with the media attribute in the head tag for all the stylesheets to see if I could fix it this way. It didn't work. In the end, I moved the h1 navbar from the nav and added a class to the row for styling. So far it is working. As I was checking the mobile section, the background image is now moving towards the middle of the page. I'll see if I can get it to move a little bit to the left side of the page.

**Link to work:** [JavaScript Calculator](https://codepen.io/BritishPandaChick/pen/ZpZZEX?editors=1010)

### Day 48: July 18, 2019

**Today's Progress**: Added variables for JavaScript Calculator. Started working on getting clear button to work. Fixed mobile and responsive stylesheets for 30 Days, 30 Sites event invitation. Tried fixing main desktop style sheet.

**Thoughts:** First 30 minutes were getting the variables written down in the JS file. I looked mostly at the user stories to get a sense of what variables might be needed. So far I've got at least five variables. I might need more but for now I'm picking ones that I will need to pass user story seven. Oddly the tests are still passing for user story 7 and 10. I think that is due to the display already being set to 0 in the HTML. I was working on getting the clear button to work for user story seven but I'm debating on focusing on a different user story to pass first to see if the calculator button works. I spent all my time working on the CSS for the invitation. It took some time copying and pasting code but I managed to fix the issues with the mobile website. I managed to get the responsive version done since there weren't too many changes. The one that is proving to be the biggest challenge is the main desktop version. Somehow the styles aren't appearing for the navigation bar. I played with the screen sizes and even removed the links for the main style sheet but the styles I want still aren't appearing. I double checked all my styles for the other two stylesheets and they are working just fine. So tomorrow I'm going to figure out what is wrong with the main stylesheet and get something to appear. I have removed the code I was using and am slowly adding it back to see what my site looks like without any of the styles.

**Link to work:** [JavaScript Calculator](https://codepen.io/BritishPandaChick/pen/ZpZZEX?editors=1010)

### Day 49: July 19, 2019

**Today's Progress**: Fixed main styles for 30 Days, 30 Sites event invitation. Double check all HTML, CSS and JS code. Tried more work getting user story seven to pass for JavaScript Calculator.

**Thoughts:** I finally finished the event invitation. It turns out that I created another style file not in the assets folder. This code was mixing with the styles in the style.css folder in the assets folder. So I deleted the style file outside of the assets folder and updated the CSS in the style file in the assets folder. This fixed everything and the styles appeared. I did the last checks of all the code files before pushing to the git repo. I ran into problems here and got an error saying "error: cannot stat 'assets/css': Permission denied" so I had to google a bit to figure out what was wrong. I decided the best thing to do was close out of all my files and text editor then restart everything. As soon as I did this, everything worked just fine. Tomorrow it is time to get back to the tourist attraction website! Last 30 minutes were more work on the JavaScript Calculator. I didn't do as much coding instead was reading jQuery documentation and using the Jon Duckett JavaScript & jQuery book to help me. I watched Dylan Israel's Calculator video and felt maybe that was the right direction to go. Tomorrow I'm going to use what I've learned from Dylan's video to help with the JavaScript.

**Link to work:** [JavaScript Calculator](https://codepen.io/BritishPandaChick/pen/ZpZZEX?editors=1010)
[30 Days, 30 Sites Event Invitation](https://codepen.io/BritishPandaChick/pen/eEPQza)

### Day 50: July 20, 2019

**Today's Progress**: Finished set up for 30 Days, 30 Sites tourist attraction website. Began adding HTML code to index file. Used Dylan Israel's JS Calculator tutorial to get items displaying on the calculator.

**Thoughts:** I got a good head start on some of the HTML code. It isn't completely done. I finished all the set up. I'm debating on if I should add some JavaScript to this site or not. The plan for this project is working with CSS Flexbox mostly. I still have some Bootstrap because I do want some practice but mostly I'd like to use Flexbox the right way this time. Right now I've added the header and footer for the website. I started adding sections to the website. I'm not quite sure what to add so I did look as some other tourist attraction websites on the website to get an idea of what sections I can add to my site. Hopefully tomorrow I can finish the HTML and get a good start on the CSS. During the last 30 minutes, I worked on the JavaScript Calculator. I revisited and coded along with Dylan's calculator to see how that works. It kind of worked. I was able to get items to display on the calculator. It was all text though but I was proud to get at least something to appear on the display. The totals were not appearing either when I pressed the equal sign. However I can use Dylan's code as a base to see what I can do to further add and change so it can work as a true calculator.

**Link to work:** [JavaScript Calculator](https://codepen.io/BritishPandaChick/pen/ZpZZEX?editors=1010)

### Day 51: July 21, 2019

**Today's Progress**: Tried debugging JavaScript Calculator. Worked on trying to get user story seven to pass. Finish adding HTML sections to 30 Days, 30 Sites tourist attraction website. Began adding CSS styles.

**Thoughts:** I spent the first 30 minutes trying to get the JavaScript Calculator tests to pass. I wasn't having much luck. So I restarted my code over again and set up the pseudo code for user story seven. I decided to remove 0 from the HTML since it was throwing off my tests. So far I've set up variables for the input and outputs. I was setting up an onclick function for the clear button to see if that might work. Tomorrow I'm going to finish the onclick function and see how to clear the values with JavaScript. I'll be using lots of the documentation tomorrow to see what I can find on doing this and getting 0 to show up in the display id without putting one in the HTML. I managed to get all the HTML added. I get a feeling I'll be adding more HTML as I go so I'll probably add more as I add more CSS. I started adding CSS to the website. So far I've managed to get some of the navbar done. I'm using some of the colors I used in the original version I made from round one. Right now my plan is to get most of the CSS on the site before I start playing around with Flexbox since that will impact lots of responsive styles. I added a form element in the HTML this time. It won't actually work but I want to practice putting a form element on a website. I'm also using this project to use the iframe tag more by adding sections for Google Maps or video.

**Link to work:** [JavaScript Calculator](https://codepen.io/BritishPandaChick/pen/ZpZZEX?editors=1010)

### Day 52: July 22, 2019

**Today's Progress**: Passed user story seven for JavaScript Calculator. Started working on user story eight. Add CSS to header, navbar and discover sections for 30 Days, 30 Sites tourist attraction website. Start adding CSS styles for map.

**Thoughts:** First 30 minutes of the JavaScript Calculator didn't have a whole lot of coding. I was looking through Jon Duckett's JavaScript & jQuery book to get some help on how to pass user story seven. I eventually set up an on click event handler which set the inputs and outputs to zero. I used the html method to set everything to 0. This passed the test. Right now I'm working on user story 8. I didn't have much luck today since it would cause the tests for user story seven to pass. Tomorrow I'll see if I can get the numbers I input to appear on the calculator without messing up user story seven test. Mostly worked on the CSS styles for 30 Days, 30 Sites for tourist attraction website. I did go back into the HTML a little bit to change two classes into ids as well as adding some Bootstrap classes. I managed to get most of the styles done for header, navbar and discover sections. I spent a lot of time trying to get the header background image and text just right. It took more padding than I expected to get the h2 headline in the center of the page. Biggest thing I've learned today is to keep headlines out of the row div tag. The row class causes the headlines and any elements that follow it to be mixed up all over the page. Putting the headlines outside of the row class prevents this from happening and allows Bootstrap to get the columns just right.

**Link to work:** [JavaScript Calculator](https://codepen.io/BritishPandaChick/pen/ZpZZEX?editors=1010)

### Day 53: July 23, 2019

**Today's Progress**: Added styles for map, video and festivals sections. Tried adding margin and padding between discover elements. Worked on trying to get user story 8 to pass.

**Thoughts:** Mostly used CSS for today's activities. At the beginning of the session I went back into the discover section and tried adding some padding between the three p tags so there was a little more space between them. It didn't work so I just left them the way they are for now. I spent most of the time working on the map, video and festivals section. The iframe tags were a little bit harder to style than I anticipated. I found myself spending lots of time moving back and forth between the width and height to get everything looking just right. Padding proved to be a big issue for the festivals section. I spent a lot of time adjusting the padding so the text wasn't near the top of the background image. The last 30 minutes were more attempts on trying to get the user story 8 test to pass. I didn't do too much testing except to make sure everything I worked on yesterday was still passing. Today I was working on getting the input numbers to display. I didn't do too much coding since I was using the Jon Duckett book to see what I could use. Based on the user story, there needs to be if-else statements to see if number begins with zeros and to look out for decimals. With the way my code is written, I need to use the push method to add the inputs to the array. I just am not sure how to get the numbers to display. I started a for loop but I'm thinking about going back to the switch statement where I'll have each case joining the inputs together. Then I'll use the html method to trying get them to show on the display.

**Link to work:** [JavaScript Calculator](https://codepen.io/BritishPandaChick/pen/ZpZZEX?editors=1010)

### Day 54: July 24, 2019

**Today's Progress**: Finish adding styles to main style file. Create new stylesheets for responsive styles. Started adding styles for mobile version of site. Continued working on the JavaScript Calculator user story eight test.

**Thoughts:** I got the main stylesheet finished with all the styles. Although these styles are done, I commented them out in the index file to play around with the Flexbox. I'm not sure if Flexbox will be 100% effective with Bootstrap so I'm debating on deleting Bootstrap off this project and just using Flexbox only. I started to play around with Flexbox on the mobile of the site. It is taking me awhile since I'm using the CSS Tricks blog to review the properties. I did decide this website won't have any JavaScript so I can give all my attention on getting Flexbox working on the site. Last 30 minutes were working on the JS calculator. I decided the for loop wasn't the best way to go so I was trying to make the switch statement work. I think the number ids need to be selected when they are clicked then added into the inputs array. Then the inputs array is updated to display everything on the calculator. I spent time trying to get the switch statement to work but I gave up when it wasn't working. I think tomorrow I'm going to try the switch statement again and set up some pseudo code. Then I'll see if I can get a least zero working on the screen.

**Link to work:** [JavaScript Calculator](https://codepen.io/BritishPandaChick/pen/ZpZZEX?editors=1010)

### Day 55: July 25, 2019

**Today's Progress**: Created a flowchart to help figure out the user story tests. Started adding if-else statements for numbers so they might display on the page. Add more CSS to mobile stylesheet for 30 Days, 30 Sites tourist attraction website. Add Bootstrap classes for small screens in HTML file.

**Thoughts:** First 30 minutes didn't really involve any coding but preparing for coding. I spent most of the time using paper and pencil to create a flowchart to help me figure out some of the user stories. After the flow chart was finished, I used the last few minutes of that session to start trying to get the buttons for the numbers to work. So far I'm trying to use if-else statements if the a tag is clicked. Right now I'm trying to do it individually with a couple of numbers to see it will work then trying with the other numbers. I did some googling before starting this session and it turns out that Flexbox is already included in Bootstrap 4 so I don't need to add more Flexbox classes to this site. Therefore I'm going to just use this project as a way to get more practice with Bootstrap. The next project will be the Flexbox project without any Bootstrap. Mostly worked with the CSS today. Mobile CSS is almost done. I just need to finish adding CSS to two sections and it will be done. I had some issues checking the preview in Dev Tools. The previewer looked as if it was cutting off parts of my site. Eventually I just exited out of the previewer view and played with the window sizes with Dev Tools on to double check my styles. Tomorrow before I start the responsive styles I'm going to use the previewer one last time to see how everything looks.

**Link to work:** [JavaScript Calculator](https://codepen.io/BritishPandaChick/pen/ZpZZEX?editors=1010)

### Day 56: July 26, 2019

**Today's Progress**: Finish adding CSS styles to 30 Days, 30 Sites tourist attraction website. Spent more time working on getting user story 8 to pass on JS Calculator.

**Thoughts:** I finished the tourist attraction website. I added the remaining CSS styles for mobile, responsive and main stylesheets. I checked the previewer in Dev Tools to see how everything looked on the screen. I had no problems with the previewer today. Only HTML I added were the Bootstrap classes for medium and large screens. I didn't have to make too many tweaks to the CSS but I did use the CSS to play around with the width and height of the iframe, video and input tags. Last 30 minutes were spent working on the JS calculator. Still not having much success getting the calculator to work. I decided to scrap what I was originally working and use a function with a for loop that would look at the inputs. So first if statement checks to see if the input begins with zero. If that is false, then it would push the input to inputs array. It didn't work but I think I need the jQuery selector I was using to select the buttons then have the function run the for loop.

**Link to work:** [JavaScript Calculator](https://codepen.io/BritishPandaChick/pen/ZpZZEX?editors=1010)
[30 Days, 30 Sites Tourist Attraction Website](https://codepen.io/BritishPandaChick/full/wqNGKL)

### Day 57: July 27, 2019

**Today's Progress**: Started to set up 30 Days, 30 Sites product website. Created new stylesheets. Began adding HTML code for header, footer, navigation and some of the website sections. Tried using regular vanilla JavaScript to get JavaScript Calculator to work. Add data-action attribute on div tags calculator buttons.

**Thoughts:** Today was all about setting up for the project and getting everything ready. This mean setting up the Github repo, organizing CSS folders, getting all the links needed to make this project and more. I'm not using Bootstrap on this project and am going to instead use Flexbox. Right now the focus is on getting the HTML on the page. The challenge with this website is trying to figure out what Mr. Gold would want on his website. I started looking at a couple of examples to get an idea of what to possibly put. So far I'm planning on using the images from the round one version of the site but it is hard knowing what to put on the website since he's a mysterious character on the show so I'm going to look at a few real life examples to see how to model this website for Mr. Gold. Last 30 minutes were doing more work on the JavaScript Calculator. I spent most of the time googling where I found a Free Code Camp article about using the data-action attribute in HTML only using JavaScript. So I commented out the jQuery code I've been working with and started using the Free Code Camp article as a guide to setting up the HTML with the data-action attribute. So far it isn't working but tomorrow I'm going to keep trying with this article's suggestion and see if that works. I'll see outside of the challenge if I can get some advice on my code in the meantime to see if I was heading in the right direction with my code.

**Link to work:** [JavaScript Calculator](https://codepen.io/BritishPandaChick/pen/ZpZZEX?editors=1010)
