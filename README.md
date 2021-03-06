# Personal Trainer

## Code Institute Mile Stone 1 Project - Static Front End Site

The Code Institute project brief was to create a static front end project with a minimum of three separate pages (or page areas) using HTML and CSS while following UX industry conventions. As per the Code Institute course and methods, this was designed from a Desktop to Mobile site, so uses media queries within the CSS to have max-width break points. This project is for educational use only.

![alt text](https://github.com/luis198327/Personal-Trainer/blob/master/assets/wireframes/responsive-preview.JPG)

## Personal-Trainer [https://luis198327.github.io/Personal-Trainer/index.html](https://luis198327.github.io/Personal-Trainer/index.html)
The website has been created to provide a personal training service to the local and surrounding areas of Aylesbury, Buckinghamshire to keep fit with a personal training plan.

## User Experience (UX)

### Strategy - User Stories
#### Site Owners Goals
+ The main goal is to provide a bespoke training plan to all clients of all ages, no matter their fitness abilities.
+ Allow clients to contact for information and engage with their own training needs.

#### External User Goals
+ As a first time visitor to the site, I want to clearly understand what Personal Trainer offers.
+ I want to be able to know who the Personal Trainer is and what qualifications/experience the trainer is so I know that I am being trained well.
+ Able to do my own research and follow the trainer on social media so I can see feedback/recommendations on the service offered.
+ Able to make the necessary enquiries in how to initalise the training program or find more information and price of the service.

### Scope
In this release, I wanted to include:
+ Header section - this will contain company logo and basic navigations bar.
+ Body section - this will contain:
    + A welcome message with main image.
    + 3 main clickable box areas to navigate to the main content of the site, which are:
        + Services offered.
        + Information about the personal trainer including a location map.
        + An enquire page to submit details for the personal trainer to contact the user.
+ Footer section - this will include social media links for clients to follow the trainer.

### Structure
The layout of the site will have 4 HTML pages:
+ A home page
+ A services page
+ An about me page
+ An enquire page

The navigational bar would be used to offer links to get to the intended page at one click of a button (or via the hamburger menu on smaller devices).  This will enable a consistent look and feel to the user. 

The order of the pages and content is strategically ordered by Services offered > About me > Enquire, as this will allow a user to know what services are offered as the primary page having navigated away from the home page or viewing on smaller devices. 

The personal trainer about me page is next which enables a user to find further information about the trainer and location of the service before moving onto the enquiry page.

The use of social media links in the footer section of each web page will keep the consistent look and feel of the course.

### Skeleton
I used wireframes to put together a very basic mock-up of the site based on a desktop/tablet and mobile devices.

The wireframe can be found [here](https://github.com/luis198327/Personal-Trainer/blob/master/assets/wireframes/wireframe.pdf).

### Surface

#### Typography 
+ Montserrat is used for main headings, specifically h1, h2 and h3 headings.
+ All other text uses Raleway font type.
+ The fall back font type is Sans Serif should the imported fonts do not load correctly.

#### Colours
+ Font colour will be predominately black (unless hover over effects for example feature or the background is black, in which case white will be used).  The font colour allows the text to stand out against most backgrounds used. Hyperlinks will use default colours.
+ Background colours (if applicable) will be black, unless an image is used, which is the preferred approach for the site.
+ The navigational bar and footer bar will be consistent throughout with a grey bar and white border.
    + Within the navigational bar, a white background behind the page name will make it clear which page is currently active. 

#### Imagery
The background hero image on the home page is designed to catch the user's attention and make it obvious immediately what the site is all about; Personal Trainer.

The image on the aboutme page will show the Personal Trainer.  This is included so the user can easily identify the trainer.

Use of other images are used to provide meaning behind each page/content.

## Features
The site features 4 main HTML pages:
1. A home page which will have a welcome message on page landing.  It will have 3 boxes in the main content to act as site navigation, to the Services offered, About me, and Enquire web pages. 

![alt text](https://github.com/luis198327/Personal-Trainer/blob/master/assets/wireframes/home-page.JPG)

2. A page that will outline the Services offered, which is split into 4 sub-categories:
    + Beginner - aimed for people getting into their fitness routines.
    + Intermediate - aimed for people who have either had signed up to the beginner course or wish to challenge their fitness further.
    + Advanced - designed to be more specific training for a specific goal/upcoming event.
    + Group - aimed at providing a training plan for a small group in a public area.

    ![alt text](https://github.com/luis198327/Personal-Trainer/blob/master/assets/wireframes/services-page.JPG)
    
3. About me page to provide information about the personal trainer and experience including a welcome video to introduce the trainer.  For the purposes of this project, an example video was added.  Refer to Media section below for where this was taken from.

    The background provides a picture of the personal trainer.

    A location map will also be shown to provide clarity of where the service is offered.

![alt text](https://github.com/luis198327/Personal-Trainer/blob/master/assets/wireframes/about-me.JPG)

4. An Enquire page which will allow a user to contact the trainer for information and provide details to contact the client back in order to book a session separately. A checkbox will be available to be checked should a user wish to subscribe to a newsletter, which is optional and therefore the required attribute is not set within the code. 

    Feedback will be provided to the user where input fields are required prior to submission of the form.

![alt text](https://github.com/luis198327/Personal-Trainer/blob/master/assets/wireframes/enquire.JPG)

Each web page will contain a navigational bar which links to each of the 4 web pages.  The footer section will also be consistent for the user experience on each page with social media links. This will enable a user/client to follow the trainer for advice and information they share.

### Features Left To Implement
Additional features that I would like to include in a future release would be to:
+ Add a booking system for clients to rebook sessions, so they can do this and save the trainer time, which will also help the user experience and repeat business.
+ More information of prices and an ability to accept payments to book sessions (certainly more for regular clients if the service is more generic and not bespoke).
+ Add more online content with pictures/videos of training sessions and perhaps testimonials of regular clients. 

## Technologies Used
### Languages Used
+ HTML5
+ CSS3
+ Javascript - taken from W3Schools for the responsive navigational bar.

### Frameworks, Libraries & Programs Used
+ [GitPod](https://www.gitpod.io/) - used as the development environment for my website. I also used Git for Version Control in the project.
+ [GitHub](https://github.com/) - used to store the projects code after being pushed from GitPod.
+ [Balsamiq](https://balsamiq.com/) - used to create the wireframes during the design process.
+ [Google fonts](https://fonts.google.com/) - used to import the 'Raleway' and 'Montserrat' fonts into the style.css file which is used on all pages throughout the project.
+ [WebAim](https://webaim.org/resources/contrastchecker/) - used to check the contrast of foreground and background text/colours to ensure they pass.
+ [Font Awesome](https://fontawesome.com/) - used to import icons into my website for social media links as an example.
+ Google Images - used to search for images for website including logo and hero image.  Details can be found under the Credits section.
+ [W3Schools](https://www.w3schools.com/) - used to refer to as additional support and to insert code into my webpage.  The code used is referenced in the Code section below. 
+ [GIMP](https://www.gimp.org/) - used to assist in making the some images like the hero image transparent and setting the opacity to 75%.
+ Refer to the media section below for where individual pictures were taken from.  I used resources such as [Pexels](https://www.pexels.com/) as an example. 
+ [Google Maps](https://www.google.com/maps/) - used to embed a location map into the website. The code is reference below and in the aboutme.html page.
+ [TinyPNG](https://tinypng.com/) - used to compress my images so that they reduce file size and load faster within the site.
+ [Clideo](https://clideo.com/editor/compress-video) - used to compress my video by 60% so it reduces file size and load faster within the site.
+ [W3C HTML Validation Service](https://validator.w3.org/#validate_by_input) - used to check the markup validity of Web documents in HTML.
+ [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/#validate_by_input) - used to check the validity of my CSS in the project.
+ [Chrome Dev Tools](https://developer.chrome.com/docs/devtools/) - used to test site and run Lighthouse reports.
+ [Bitly](https://bitly.com/) - used to shorten web addresses such as the embeded Google map.
+ [Favicon](https://www.favicon-generator.org/search/---/P) - used to import favicon image (PT image).

## Testing
### Testing User Stories From User Experience (UX) Section
#### Site Owners Goals
+ The main goal is to provide a bespoke training plan. 

    The services page provides a base overview of what each service plan offers, and a clickable link to the enquire form to provide more details allowing the Personal Trainer to have the details to contact the client and provide a recommendation.

+ Allow clients to contact for information and engage with their own training needs.

    On each page there is a clickable link to take you to the enquire page which is one of the main goals to start the engagement process.  All links works and the easy navigation bar works too.  The enquire form ensures there is validation and appropriate feedback if required fields are not completed correctly or completed at all.

#### External User Goals
+ As a first time visitor to the site, I want to clearly understand what Personal Trainer offers.

    The home page provides a clear statement (or 'Mission Statement') of what the site aims to provide and clickable links to each of the three separate pages.  These have all been tested and work accordingly and the hover over effects provide clearer clarity on what option is selected.  

+ I want to be able to know who the Personal Trainer is and what qualifications/experience the trainer is so I know that I am being trained well.

    The about me page provides details about the trainers experience and displays a welcome/demonstration video which allows a user to control its feature, ie play and control the sound for a better user experience. Note - the video used is just a stock video which would be replaced with a video of the trainer if this was a proper website (ie not for the purpose of this educational project).  The background picture is the Personal Trainer which provides more meaning and openness to the page/site.

+ Able to do my own research and follow the trainer on social media so I can see feedback/recommendations on the service offered.

    Social media links are present on all pages with hover over effects, which open on new tabs, which allows the original website to remain available.

+ Able to make the necessary enquiries on how to initaliate the training program or find more information and price of the service.

    All pages link to the enquire form page which is easy to complete and with placeholder text, this provides clarity of what information is required and where.

### Further Testing
 I constantly tested the code in Chrome Dev Tools and ran Lighthouse to identify and fix issues that affected the site's performance, accessibility and user experience.  This highlighted a few things. A couple included:
 
 + No title attribute for my iframe for the google map.
 + Poor contrast for the text colour in the navigational bar (which was originally a white colour - changed to black).
 + Image file sizes. To reduce the size of these files, I used free software to compress these images and the video to save space (refer to the frameworks section for the software used).
 
 Running a lighthouse report against my website produces excellent results against its Performance, Accessibility, Best Practices and SEO. [Here](https://github.com/luis198327/Personal-Trainer/blob/master/assets/wireframes/lighthouse-report.JPG) is the results of the report.

The responsiveness of the site works fine on all screens sizes tested using Chrome Dev Tools (from a desktop/large laptop size of 1440px wide through to a mobile device of 320px wide). With the use of media queries within the CSS, there are a number of break points when elements are repositioned for tablets and mobile devices for each page. 

The site was also checked on Chrome, Edge and Firefox browsers to ensure compatability across these.

#### Validation
I used the W3C Markup Validation Service to check the Markup and W3C CSS Validation Service to check the CSS validity of the site.  I used these during and at the end of the project to regularly identify issues.  All HTML pages and the CSS styling page have passed with no errors/issues highlighted.

![alt text](https://github.com/luis198327/Personal-Trainer/blob/master/assets/wireframes/html-validation.JPG)

![alt text](https://github.com/luis198327/Personal-Trainer/blob/master/assets/wireframes/css-validation.JPG)

#### Issues I Overcome
I had 4 main issues that i manage to overcome:

1. I was struggling to get the navigational bar to display correctly or in a suitable way for responsiveness on small screen sizes. I was trying to use simple HTML5 structural elements and attributes but to no success.  My mentor referred me to the W3Schools website to use the responsive nav bar, which i used and maniputlated the code for my site. This used JavaScript which is something i am yet to learn but grateful for this piece of advice and to improve my understanding of the course further.  The code used is credited below under Credits > Code section.

2. Within the footer where the social media links are, it was allowing you to horizontally scroll which isn't great for an user experience perspective. I was using the Chrome Dev Tools to try and pin point why this was happening and after some time realised this was due to the padding which is auto set when inserting an unordered list, which the footer icons use.  The CSS was amended to inherit the padding to fix this.

3. One key item I wanted to include in the website was a google map. I spent some time trying to figure out how to embed this into the aboutme.html page as by applying my learning from the course on iframes wasn't working and I couldn't understand why. I was constantly getting the follow message **_"this page didn???t load google maps correctly"_**.

    After googling this, I realised that Google Maps require an API key (Application Programming Interface) to use this feature.  However a workaround solution was to use the 'embed map option' within Google Maps and embed the iframe code they provide.  This is credited below within the Credits > Code section. I was then able to manipulate the code in the HTML and CSS files to set the size and other key attributes, as well as using bitly to shrink the URL web address itself.

4. Testing on different browsers other than Chrome showed that the social media icons didn't have much of a colour effect/change when the mouse is hovered over the icons, like it does with Chrome. I therefore added a new blue base colour and updated the hover colour to purple in the CSS file, which made this feedback much clearer.

### Known Bugs/Improvements   
Two things that I would like to improve and correct in a future release would be:

+ On larger screens sizes, for example on 4K 2560px screen sizes, the content doesn't fill the full view port area. With more content that would be added in future releases, this will help to fill this on larger screen sizes.

+ I found it difficult to resize the logo image so that it wouldn't affect the layout/positioning of the navigational bar. Preferably this would be larger so that it is clear and provide more meaning, once the logo has been agreed.

## Deployment
My project was developed using the IDE, Gitpod. 

The site was deployed to GitHub pages. The steps to deploy are as follows:

+ Within the GitHub repository, navigate to the Settings tab.
+ Then select the Pages sub-menu option on the left, which takes you to GitHub Pages. 
+ Within the source section drop-down menu, select the Master Branch and click on save.
+ Once this has been saved, the page will confirm that the site is ready to be published and provides the URL address.
+ Refreshing the page will confirm the website has been deployed, again providing the URL address.
+ The deployed URL is [https://luis198327.github.io/Personal-Trainer/](https://luis198327.github.io/Personal-Trainer/).

The deployed site will update automatically upon new commits to the master branch. For the site to deploy correctly on GitHub pages, the landing page must be named index.html.

### Making A Local Clone
You can clone this repository by:
+ Logging into GitHub and locate the GitHub Repository luis198327/Personal-Trainer
+ Under the repository name and with the Code tab displayed by default, click the dropdown "Code" option.
+ This will give you the option to copy the repository using HTTPS by clicking the copy button.
+ Open Git Bash.
+ Change the current working directory to the location where you want the cloned directory to be made.
+ Type git clone and paste the URL i.e. $ git clone https://github.com/luis198327/Personal-Trainer
+ Press Enter, and your local clone will be created.

Or simply clone this repository directly into the editor of your choice by pasting $ git clone https://github.com/luis198327/Personal-Trainer into your terminal. To cut ties with this GitHub repository, type git remote rm origin into the terminal.

## Credits
### Content
+ All content was written by the developer, unless referenced below.

### Code
+ W3School - To produce a responsive navigational bar, W3Schools was used and code/script added to the HTML page to produce this.  This has then been tweaked accordingly to style for this project. 
+ Google Maps - To embed the google map under the About Me section, I used the embed a map option within google maps to copy the specific iframe HTML code into my aboutme.html page.  I have changed a couple of settings to size the map differently within the CSS and added a title attribute to the HTML (having notice this was failing the Markup validation).

### Media
+ The Personal Trainer logo was searched using google images and taken from [the hungry jpeg](https://thehungryjpeg.com/product/3804709-monogram-pt-logo-design) website.
+ The Personal Trainer hero image was searched using google images and taken from [elevate fitness](https://elevatesyracuse.com/ten-reasons-to-become-a-personal-trainer/) website.
+ The image used for the Services option box background is taken from [pikwizard](https://pikwizard.com/?q=trainer) website.
+ The image for the About Me options box background is taken from [mens nutrition](http://www.mensnutrition.com/page/4/) website, and then by scrolling to the Fitness Warnings article.
+ The image for the Enquire options box background is taken from [pexels](https://www.pexels.com/photo/crop-businessman-giving-contract-to-woman-to-sign-3760067/) website.
+ Video under the About Me page was taken from [Stock Adobe](https://adobe.ly/3u7EziI). Note - this does not have sound so the user control to enable the sound will not work.

### Acknowledgements
+ I used the Code Institute GitHub template as a basis for setting up my repository.
+ I used W3Schools to assist with some features and to develop my understanding.
+ I would like to thank my mentor Spencer Barriball for his review and ongoing support with this project.
+ This project is for educational use only and was created for the Code Institute Module of a Static Front End Site.