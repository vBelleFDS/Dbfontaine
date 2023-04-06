# README

This README file provides an overview of the code structure of my third assignment, the final version of my website for my career as a music producer.

Most of this code was reused from A1/A2, with some minor adjustments to accommodate for new features added. More details are provided in the code review and this document.

## HTML

The website contains three HTML pages:

- index.html: Home page of the website.
- about.html: About me page containing information about my work and how to reach me.
- videos.html: Page containing music videos where I showcase some of my beats.

Very little of this code was changed from the past assignments. Certain things were removed like the contact form as I would be implementing features that would make it redundant.
I also had to implement button tags for the download button and colour pickers on each page, the img tag on index had to be replaced with a div of class photo-gallery to 
hold my gallery images. 

Also found in the HTML is the JS code. I wanted to keep it inline as the code implemented is fairly minimal, and by putting it inline I can put the script tags next to the code
it's working with to improve the readability of my code and make the functions clear (except for the download button script, which can be found in the head of about).

# CSS

There is one external stylesheet used named styles.css which contains almost all of the CSS for this assignment. Largely, it is the same as A1/A2 with some minor adjustments. I removed small things
that were inhibiting my code like the universal selector that was changing the background colour of the pages to beige. I added the dynamic window sizing as inline CSS on the respective pages
so it was clear which code was for which page. Some other new additions to my CSS are present for the buttons, gallery, splash, and other new features.

## JavaScript

All of the necessary features have been implemented: 

- Notifications: Several alert notifications are being used on this website, but a unique example can be found upon visiting videos.html. The responsible code
can be found on lines 13-15 within the <script> tag.
- Conditional: I implemented a conditional statement on the index page. I'm using an if statement to check if it's the user's first time on the site by checking
the flag in localStorage. If it's their first time, an alert notification pops up saying to scroll down from the splash image. After the first time, however, this will
not happen. This was an intentional decision so this pop-up wouldn't reoccur if returning to the home page.
- Colour Changer: The code for the colour pickers on each page can be found near the top, next to the colour button tags. I used event listeners to check for button clicks
which then implement the new colours of the chosen theme, replacing the background colour and font colour. I also implemented a clear button after getting the idea post-wireframe
creation so the user can revert to the default theme. 
- Event Handler: Event handlers can be found in the script tags relating to the colour pickers and the download button.

## File Structure

The following files make up my website:

├── assets
│   ├── gallery
│   │   ├── image1.jpg
│   │   ├── image2.jpg
│   │   ├── image3.jpg
│   │   └── image4.jpg
│   ├── soundcloud_logo.png
│   ├── mel 143 dbfontaine tgwog.mp3
│   ├── me.jpg
│   ├── keyboards.png
│   └── alyx beat.mp4
├── favicon.ico
├── about.html
├── index.html
├── styles.css
└── videos.html

There are a few more files in the folder, but they are not integral to the site and are for the assignment only (wireframes and code review).

## Relative Paths 

- gallery folder: ./assets/gallery/
- image1.jpg: ./assets/gallery/image1.jpg
- image2.jpg: ./assets/gallery/image2.jpg
- image3.jpg: ./assets/gallery/image3.jpg
- image4.jpg: ./assets/gallery/image4.jpg
- soundcloud_logo.png: ./assets/soundcloud_logo.png
- keyboards.png: ./assets/keyboards.png
- me.jpg:  ./assets/me.jpg
- mel 143 dbfontaine tgwog.mp3: ./assets/mel 143 dbfontaine tgwog.mp3
- alyx beat.mp4: ./assets/alyx beat.mp4
- index.html: ./index.html
- about.html: ./about.html
- videos.html: ./videos.html
- favicon.ico: ./favicon.ico
- styles.css: ./styles.css
- jquery-3.6.0.min.js: https://code.jquery.com/jquery-3.6.0.min.js
- jquery.fancybox.min.js: https://cdnjs.cloudflare.com/ajax/libs/fancybox/3.5.7/jquery.fancybox.min.js
- jquery.fancybox.min.css: https://cdnjs.cloudflare.com/ajax/libs/fancybox/3.5.7/jquery.fancybox.min.css

## References

- JQuery. (2021). JQuery Library. Retrieved from https://code.jquery.com/jquery-3.6.0.min.js

- FancyApps. (2021). Fancybox Library. Retrieved from https://cdnjs.cloudflare.com/ajax/libs/fancybox/3.5.7/jquery.fancybox.min.js

- FancyApps. (2021). Fancybox Stylesheet. Retrieved from https://cdnjs.cloudflare.com/ajax/libs/fancybox/3.5.7/jquery.fancybox.min.css

- Lorem Ipsum. (n.d.). Retrieved from https://www.lipsum.com/feed/html

- Special thanks to my friend Spencer Allen for letting me use his photographs as placeholders in my photo gallery.