# README DOCUMENTATION

# **Milestone Project 1 - User Centric Frontend Development**
# Author: Jack Clark (Contact Me - jackalexanderclark@protonmail.com)

# Project website link (GitHub Pages): https://jackalexanderclark.github.io/Valeries-art-gallery-/frontpage.html

## Website Device Mockup
<img width="879" alt="image" src="https://user-images.githubusercontent.com/97599832/203627868-9015279e-3bf7-4872-ab1a-57f437ab7bae.png">


# **I) Introduction and Project Goals**
1. For my user centric frontend project, I decided to build a website to display my grandmothers artwork, from the start I knew I wanted a 3 page layout; firstly an introductory home page with a basic biography and information related to influences and styles, a second gallery page for her card collection and a third page for her framed paintings.
2. The main story for design I had was two pillars; viewing and learning. That it is easily accessible to straight away understand the kind of art displayed. I also refrained from adding to many effects that would over-saturated the artwork and hence kept a modest and simplistic approach.
3. My project went through two phases of iteration. I originally designed my art gallery website statically with HTML and CSS without bootstrap. Primarily, through the lens of my laptop - which would later lead to issues with mobile and iPad devices etc.
4. After feedback from users and my Code Institute tutors, I rebuilt my website from the ground up but this time using Bootstrap templates (product and album), this gave my second website a much better flow and layout and all scaled well with other devices.

# **II) Planning and Design Philosophy**
1. I took a lot of input from my grandmother "Valerie Turner", she gave me her ideas and agreed with my approach of a 3 page layout. She also was clear that her favourite colours lie within the purple and violet family. This directed me to use shades of purples and violets in the website backgrounds. I used the tool: "https://redketchup.io/color-picker" to find HEX colours and related shades for visual appeal and consistency.
2. This was my first wireframe plan, for my first prototype and layout. Made using software from: "https://balsamiq.com/wireframes/":
![Wireframe](https://user-images.githubusercontent.com/97599832/180777531-687a10f0-2b01-47cc-b4ae-8c9e61623ef1.JPG)

# **III) Improvements from User Feedback**
1. I asked a variety of people from my workplace to my family and for the most impartial feedback tutors from Code Institute - to give me their initial thoughts and feedback as users of my website. 
2. **User 1**: Liked the appearance of my original gallery design:
![cards gallery](https://user-images.githubusercontent.com/97599832/180780315-3c10b16c-9e3d-4a45-9d9d-194a7da112bb.JPG)
However, this gallery did not display well at certain breakpoints. Also suggested the front-page could be improved.
3. **Code Institute Tutor 1**: Thought the design was like early 2000 era websites (in essence that it looked out-dated), which I did agree with. It was also brought to my attention that there was no way to return to the top of the website and that the navigation bar did not scroll down with the user meaning navigation was more difficult.
4. **Code Institute Tutor 2**: Found issues with the navigation bar that it was not responsive and would break at certain points when testing using Chrome Developer Tools:

<img width="209" alt="image" src="https://user-images.githubusercontent.com/97599832/203626100-0eadb67d-7160-4a5d-8c3c-97cf8d05690a.png">

5. From this feedback the most important lesson learned was building a website with html and CSS for a laptop screen first then trying to build in responsive elements was the wrong approach and made it very hard to improve. This is what led me to rebuildingfrom the ground up, but this time using bootstrap templates and building my elements into it.
6. I used two templates from the getbootstrap library that I felt were eye catching and modern that would neatly contain the artwork and descriptions. I went for the "product" template for the homepage as it allowed images and text in a grid like window. For the two gallery pages and I went for the "album" templates which I edited to make custom image holders that scaled nicely between all kinds of devices from computer screens to iPhone.
7. Another area of improvement for the website comes from the slow loading of the high-resolution images on the gallery page. I originally had the cards and paintings on one page. This was brought to my attention and to keep the loading times high I created a new html page to display the cards and the other html page to display the oil paintings - this will reduce the amount of loading on each page by half and allow me to keep the high resolution on the images and to not sacrifice the quality of the images, which is a highlight of the project. 

# **New UX and UI Website with User Feedback**
1. With the above feedback in mind, I chose the “getbootstrap” template "album" for my image galleries (cards and paintings). The images are inside of containers that scale as you decrease the pixel width using Chrome Developer Tools but also stack nicely one on top of the other, when using smaller devices such as an iPhone or Pixel Phone.
<img width="918" alt="image" src="https://user-images.githubusercontent.com/97599832/203628193-9e4d1707-89ea-46b0-acf9-1424605cbc44.png">

2. Similarly, I redesigned the front page into a four-panel design, with each panel window containing an image and also a paragraphs worth of text outlining 4 principles I wanted to outline for the user. These being a biography, an origin story (where I am from), Style and Influences pertaining to the artists philosophy.
3. I also included a YouTube video embedded within the page that does not require an external tab being opened to illustrate the area the artist lives in and its stunning views. Similarly, as can be seen below, the navigation bar is now sticky and will scroll down the page with the user so you can always see which page you are on.
<img width="932" alt="image" src="https://user-images.githubusercontent.com/97599832/203628690-e28aa90d-a971-4051-a3c8-95fa2500e022.png">

4. I also added a return to top of the page anchor for ease of use, as this was an issue made clear from user feedback.
<img width="581" alt="image" src="https://user-images.githubusercontent.com/97599832/203629083-2e56be0d-1a35-4b08-b549-6117d37b745e.png">

5. There is a contact email address for users to request items they like from the website. This is apart of the overall story of the website, that you can learn, broswer and contact the artist - that is the purpose.

6. I also changed the front-page to have text in columns together to make the overall page more cohesive and to reduce on the amount of empty space.
<img width="886" alt="image" src="https://user-images.githubusercontent.com/97599832/204019084-4cbec2d1-7a46-4e1e-a911-da613f1a23c0.png">

8. I fixed an issue with a disparity between mobile and smaller device Navbars, as seen below the navbar breaks at a pixel width of 762px:
![mobile-white](https://user-images.githubusercontent.com/97599832/204100084-bd2eea2f-c1db-4524-8a6d-4467c25f033d.png)
By using Chrome Dev Tools, I added media queries for this certain width to hide the navbar and instead show a mobile designed navbar with a smaller logo and and text. Examples shown below:
Laptop: 
<img width="570" alt="image" src="https://user-images.githubusercontent.com/97599832/204100188-2102a40e-7c58-4158-a02c-af2ec06e2635.png">
Mobile: 
<img width="435" alt="image" src="https://user-images.githubusercontent.com/97599832/204100220-9c18d986-1e41-40e2-abf0-6c3c2da80277.png">

# **IV) Technology and Tools Used**
1. HTML
2. CSS
3. JavaScript
4. Chrome Dev Tools
5. Version Control, IDE and Deployment: GitHub, GitPod and GitHub Pages
6. Bootstrap Framework
7. Font Awesome (icons)
8. Testing: Chrome Dev Tools and W3C CSS Validator

# **V) Acknowledgements and Code Credit**
1. Credit and thanks to Valerie Turner for his Artwork featured on this website.
2. Credit for GetBootstrap Templates; Album and Product. Source: "https://getbootstrap.com/docs/4.6/examples/album/", "https://getbootstrap.com/docs/4.6/examples/product/".
3. Credit for Sticky Navigation Bar. Source "https://www.w3schools.com/howto/howto_js_navbar_sticky.asp"






