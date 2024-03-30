# REAL MADRID LANDING PAGE

*** AMIRESPONSIVE SCREENSHOT ***

## INTRODUCTION

Real Madrid F.C. are one of the most successful clubs in football history. This site was created for anyone wanting to know more about the club's recent history, and was designed with the aim that a user feels like they are accessing a fan club extension of the official website.

The reason for choosing to build a site around such a big entity as Real Madrid was that when I visited their site, the main focus is on the latest news, results and upcoming fixtures. The club also have a Women's Team, at least two professional youth squads and a basketball team. Because of this diversity I didn't feel that the current mens first team squad and their most recent accolades were easily accessible on the official site. 

I hope you enjoy your experience on the site and find it reflects the passion and feelings that Madridistas feel when supporting our team.

Find out our most recent trophy hauls, check out the Bernabeu's renovations on the main page and meet the squad by accessing the site - [Real Madrid](https://j95ortiz.github.io/Real-Madrid-Portfolio-project-1/index.html)

## USER EXPERIENCE

### Overview

The user's experience and feel was the priority of the design, with the main aim being that they are able to identify exactly what the site was about when they visit as well as feeling confident navigating around the full site.

### Wireframes Created

The wireframes created to represent what the initial structure and layout for the site were created on Balsmiq. Although the layout of the final site does vary slightly from the initial wireframes these can be seen below:

*** BALSAMIQ SCREENSHOTS ***

### Site Structure

This Real Madrid site is split into 3 main pages:

1. The Main Landing page
2. The Squad page
3. The Lotto page

All of these are accessible for the user regardless on what page of the site they're on via the navigation menu at the top of their screen. 

There is also a 4th page which will only be visible to the user once they complete and submit the form in the Lotto page. Following comments from a user, links were added to this page so they can return to any of the main pages directly from the menu rather than have to go back.

### Design Choices

This Real Madrid landing/tribute page was designed to reflect the spirit of the club as much as possible. The colour combinations used in the design were inspired by the club colours and also those of some of their kits.

Even though the Club's main colour is white, the site was designed with a darker theme in mind as people tend to find this more appealing. This alternatice colour scheme should work as a nice contrast to the Official Real Madrid page which has a light theme with navy highlighted elements. The final colour scheme for the site prioritises navy, black and gold.

*** COLOUR SCHEME SCREENSHOTS ***

## FEATURES

By constantly putting the user's experience at the forefront of the design, the site ensures that they have access to all three main pages of the site at all times by adding a flexible menu in the header which displays as a dropdown on mobile and smaller devices, and as direct links on bigger screen sizes. 

On bigger screens the page the user is currently on will be underlined in the top bar so that they know exactly what section they are on. By doing this the intention is that the user feels confident moving around the site, knowing what section they are in at all times, and feels happy to explore the site fully.

Should the user also wish, links are provided which allows them to visit the official site and store. 

Social media links are displayed on the footer so the user knows what site they're accessing.

### Main Features

The Site is split into three main sections and a landing page which the user will see when the lotto form is submitted.

Any external links have been designed to open in a new tab so that the user always has access to the landing page should they wish to return.

The Navigation Menu and Footer are displayed on all 4 pages of the site.

#### Navigation bar and Dropdown Menu

The navigation bar contains an image of the club's crest, the club's name and links to all three main pages. 

It was designed to be flexible and appears differently across different devices depending on the screen size of the display.

The club's crest and name both work the same way regardless of the screen size and will return the user to the main page when clicked on. 

On mobile screens (unless landscape), the links menu will appear as a dropdown where the user can then select which page they want to visit. 

On larger screens and landscape phone the bar will appear as a menu instead with links to all the pages on display, and easily accessible.

*** SCREENSHOTS OF NAV MENU ON PHONE AND LAPTOP ***

#### Footer

The footer was created to provide the user with links to the Club's social platforms and when clicked on these links open in a new tab for an increased user experience.

*** SCREENSHOTS ***

#### Index Page

This is the main page the user will see when opening the site and is split into 4 main sections.

The top section contains a table showing the club's all time goalscorers and the colour scheme used is based on their 22/23 away kit.

*** SCREENSHOTS ***

The top section also includes the trophies won by the first team in the last 5 years. The colour scheme for this information was based on this season's third kit.

*** SCREENSHOTS ***

The middle section is taken up by a video showing the renovatoins on Real Madrid's Santiago Bernabeu stadium.

The video was set up so it doesn't autoplay when the page is loaded, increasing the user's experiencce by making them feel they have full control over the site's behaviour.

*** SCREENSHOTS ***

The section below the video includes links to the other pages of the site, giving the user even more autonomy over how they choose to access these.

*** SCREENSHOTS ***

The last section on the main page contains two more links from which the user can visit the Official site of the club as well as the store on their website.

*** SCREENSHOTS ***

#### Squad Page

This page of the site contains the names and a photo of the first team's head coach and each of their members. 

The page is split into 5 sections based on the main positions on a football pitch, with each squad member having their name and image in their respective section.

The page is set out to be responsive and the amount of squad members' cards per row depends on the viewer's screen size. 

*** SCREENSHOTS ***

#### Form Page

This page is a form that the user can fill and submit for a chance to meet a Real Madrid player.

The form includes a section for the user to input their contact details and this section is required.

The form also includes a dropdown with a list of the squad members, a radio option box for them to say what position  the squad member they choose to meet plays in, as long as a text box for them to include any additional information as to why they chose that player.

Once completed, if they submit the form by pressing the button on the bottom of the form, the landing page is then displayed, and this is the only way the user would be able to access this page.

*** SCREENSHOTS ***

#### Submitted Form Page

The submitted form page is really simple and its only features are the navigation menu and footer present across all pages, as well as an image with a message wishing them good luck in the lotto. 

From here they can return to any of the three main pages using the navitgation menu.

*** SCREENSHOTS ***

#### Future Features

A feature I initially wanted to add was a quiz where the user could test their knowledge of the club and where a message would pop up when they completed it and based on their score it would compare them to a Real Madrid legend if they got a good score, or a flop if they didn't. When looking into this Javascript was required in order to store the answers, and as I don't know this language yet I'm unable to implement it at this stage. However it is an idea I'm keen on and would like to add once I'm capable.

## TESTING

### Validator Testing

*** HTML VALIDATION RESULTS FOR ALL PAGES ***

The [W3C Markup Validation Service](https://validator.w3.org/#validate_by_input) was used to check the HTML code on all 4 pages, and they all passed. 

INDEX PAGE

SQUAD PAGE

LOTTO PAGE

FORM SUBMISSION PAGE

*** CSS VALIDATION RESULT ***

The [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/) was used to check the CSS code and it also passed.

CSS VALIDATION SCREENSHOT

### Troubleshooting

Throughout the building process a few bugs were identified and ultimately resolved.

The first one was an issue with the settings on my Google Chrome application. The settings made the colours not appear correctly on my screen, so when the site was being built the colours I was seeing weren't the ones that users would see when deploying the site their end. 

The main issue with this was that text which appeared white to me and contrasted well with the black in the header, would show as black for other users. This bug was identified by my mentor Precious Ijege when he loaded the deployed site on his device. 

SCREENSHOTS OF SITE WITH WRONG COLOURS

Attempts to resolve this included specifying the colour in the code but this didn't resolve the issue. It was finally resolved by searching for the issue online, and the [solution](https://support.google.com/chrome/thread/213362947/chrome-is-changing-color-theme-each-day-on-its-own?hl=en) was found on the Chrome Support page.  

*** HIGHLIGHT HOW THE SITE IS FLEXIBLE ACROSS DIFFERENT SIZES ***

In order to ensure that the website's responsiveness worked consistently regardless of screen size the site was tested on different devices. 

*** OUTLINE WHAT TESTING DONE ***

Once the site had been deployed, links to it were sent to people I knew who had access to different devices such as tablets and different sized phones so they could test the site.

Testing was also carried out to make sure that the links to Social Platforms and the Official Site all worked fine. 

Initially the link to the Madrid Store linked to the Adidas store, but when carrying out testing it didn't always work. Therefore this link was changed to the store on the Madrid Site. This actually worked out better as when testers were asked they felt it made this site feel more like an extension of the Official one.

## DEPLOYMENT

*** STEPS A USER WOULD HAVE TO TAKE TO DEPLOY ***

## CREDIT

### Content Credits

*** ICONS, TOP SCORERS & TROPHIES INFO ***

### Media Credits

*** IFRAMES, IMG SOURCES & SOCIAL LINKS  ***

## ADDITIONAL INFO

Real Madrid is the football team I've always supported. Football as a whole, and Real specifically are areas I'm very passionate about. As this site is the first site I've built, I chose Real Madrid as my inspiration because I believe that building anything around a subject you have a strong passion and affinity for, makes the ability to convey these feelings across a lot easier.

### Acknowledgements

*** MENTION PRECIOUS, THE WAWASWOOD GUY ***

### Learning Outcomes

Better nunderstanding around flexbox, CSS & Positioning.

Learned how to link different pages together & proved to myself I have the initiative to look for solutions online when I get stuck.

It's a great learning processand helped me become better at planning and gave me exposure to various technologies and platforms which I'll be using in my future Web Development Career such as wireframes, repositories, favicons etc.



