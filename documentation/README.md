# README DOCUMENTATION

# Milestone Project 1 - User Centric Frontend Development

## Project website link (GitHub Pages): https://jackalexanderclark.github.io/Valeries-art-gallery-/frontpage.html

## NEED TO REWRITE WHY I SWAPPED TO BOOTSTRAP TEMPLATES


### UX - First time visitors
1. First time visitors should immediately understand the purpose of the website. It should clearly represent an art gallery and shop to purchase paintings and cards.
2. It should be very simplistic to navigate between the different pages; home, gallery and the shop.
3. I have integrated a YouTube video from my channel, this demonstrates Tintagel's beautiful coast-line to immerse the visitor in the landscape and mindset.
4. The interactive gallery is easy to use by simply hovering your mouse over the images to reveal text about the item you are currently looking at, such as the title and the name.

### UX - Planning and Implementation 
1. For the website I want a classic and simple 3 block design for each html page; being a header containing the page title and universal navigation bar, the main middle content block which will contain the image galleries and paragraphs of information and then the bottom footer with an anchor link to take the user back to the top of the page and basic footer information and credits to the painter.
2. To test the websites funcitonality, I took feedback from a couple user stories and then implemented their feedback.
3a) User Story 1: Lewis - Understood the website immediately, liked the colour scheme and quickly found their way around to explore the galleries and biography to learn more. But thou
![cards gallery](https://user-images.githubusercontent.com/97599832/180780315-3c10b16c-9e3d-4a45-9d9d-194a7da112bb.JPG)

## Wireframes and planning using Balsamiq - Webpage layout
![Wireframe](https://user-images.githubusercontent.com/97599832/180777531-687a10f0-2b01-47cc-b4ae-8c9e61623ef1.JPG)

### Themes and Design
1. The primary design theme is a painting frame border to illustrate the artistic purposes - it is present throughout to provide continuity.
2. Similarly, the colours have been kept to a basic and consistent pallete. Such as light blue (#add8e6) and dark blue (#410cd3).
3. Another design philosophy was to only use a single h1 tag for each html page for aesthetics and to make important information prominant. 
4. Finally, the other design pillar was that of simplicity - there is a biography, an interactive gallery and a shop with a contact form to directly contact the artist with an item request, feedback or to purchase an item chosen from the gallery.

### Features
1. Interactive elements such as; navigation bars and scrollable gallery. 
2. To allow site users to contact the artist, I implemented a flask backend to take data from the shop form and display the information on a web page to communicate and store information pertaining to peoples interest in the products or their contact information.
Furthermore, this flask backend to receive data from form submission will be able to be viewed by myself the web developer and then relayed to my grandmother, when I check the file.
3. I have included facebook links that take the user to facebook, however after speaking to the artist who is my grandmother, she did not want the form.html painting request details to go anywhere or have her personal facebook be attached to this project. Therefore, both the facebook link which works but does not directly take it to her profile and similarly the flask and form.html data is not connected to her email or anything etc. The purpose of this website is to create a "Static" website for a real world artist, therefore I have decided not to make these links live.
4. Responsive navigation bar: 
![responsive nav bar](https://user-images.githubusercontent.com/97599832/180781300-f5931121-69e4-4325-ba2d-b219787861fb.JPG)


# Life Cycle of Project Development and Feedback
## First Design
1. Please follow attached link to the attached PDF in which I have included my website wireframe, early gallery concepts and also the different HTML page wireframes.
2. I firstly created the home-page first that explains the ethos of the artist and gives people an idea of the "purpose" of the website.
3. After receiving feedback on flaws and limitations on the website I entered the second phase of the life cycle of the website, illustrated by the description of git commits starting in june/july. In this phase I did a rehaul of the front-end of the website and added a small backend process to capture form data for the artist from users expressing their comments and interest.
4. To have a detailed look at the project life cycle, read the project repository file on GitHub ("https://github.com/JackAlexanderClark/user-centric-project-1") and the associated messages to each commit update - to get an idea of the website life cycle process.
![all-devices-black](https://user-images.githubusercontent.com/97599832/180784528-fb95d9a9-796f-4e52-99db-767aa7cd71aa.png)
5. However, as can be seen above I received some constructive criticism from test users and my code institute tutor that the design looked dated (early 2000's) style and that it needed a more modern appeal, it also lacked responsiveness and had a lot of whitespace.
This feedback led me to my second design of the website.

## Second and Final Design
1. After receiving feedback from tutors I decided that there were issues with the responsiveness of my orignal design, maining it being static HTML and CSS. I then decided it would be better to use a "getbootstrap" template that will have pre-built containers for responsive and then build my content inside.
2. I used two templates from the getbootstrap library that I felt were eye catching and modern that would neatly contain the artwork and descriptions. I went for the "product" template for the homepage as it allowed images and text in a grid like window. For the two gallery pages and I went for the "album" templates which I edited to make custom image holders that scaled nicely between all kinds of devices from computer screens to iphones.

## Known Bugs and Improvements
1. Discovered in google dev tools was the broken youtube embedment, which I was able to fix after seeing the error in the console.
2. Another area of improvement for the website comes from the slow loading of the high resolution images on the gallery.html page. This was brought to my attention and to keep the loading times high I created a new html page to display the cards and the other html page to display the oil paintings - this will reduce the amount of loading on each page by half and also allow me to keep the high resolution on the images and to not sacrifice the quality of the images, which is a highlight of the project. 
3. I did some rudimentary testing by using a timer on webpage load to when all images were fully loaded on the screen. When all the images were on the lone gallery.html page it took on average (3 repeat tests) 11.4 seconds. Once I split the images between the two new html pages (cards.html and paintings.html) it was reduces to approximately 6.2 seconds between the two - increasing the responsiveness of the website.


## Code
1. Code for the flask (app.py and form.html) credited to -> https://developer.mozilla.org/en-US/docs/Learn/Forms/Sending_and_retrieving_form_data.
2. Responsive navigation bar credited to -> https://www.w3schools.com/howto/howto_js_topnav_responsive.asp
3. Extra code from the responsive nav bar credited to -> https://adiati.com/how-to-create-a-responsive-navigation-bar-with-flexbox-and-media-queries
4. CSS media queries credited to stackoverflow -> https://stackoverflow.com/questions/6370690/media-queries-how-to-target-desktop-tablet-and-mobile 

## Technologies, Frameworks and Libraries
1. HTML
2. CSS
3. Bootstrap 
4. GitHub and GitPod Cloud IDE
5. Font Awesome
6. Bootstrap Icons

## Testing
1. W3C CSS Validator
2. Chrome Dev Tools

## Credits
1. Jack Clark 
2. Valerie Turner



