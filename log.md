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
