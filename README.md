# Monocide Website
<div align="center"> 

[To wiew in github pages](https://jourm.github.io/Monocide/merch.html)
</div>

A website for Monocide, a metal band from Gothenburg, Sweden. The Website showcases the band's music and overall vibe.
The goal is to serve as a professional looking website with a "metal edge", to promote the band and serve as a place where
announcements of upcoming shows and releases can be made, aswell as businiss connections, booking requests and merchendise requests.

The number of requests for merchendise are expected to be quite small in the forseable future wich is why the site does not
warrant a full web shop, but rather a contact form. The band does not have a large scale merchendise production or inventory,
and all request will be answered manually thruogh email.

Businiss goals of the site are:
* Promote Band Awareness and overall internet prescence.
* Serve as an official means of contact, where the band can be reached for Businiss (booking, schedualing interviews, offering collaboration) 
* Serve as a way of announcing new projects or shows.

The visitor goals of the site are:
* Information about Monocide.
* Information about Upcoming shows or releases.
* Contacting the band regarding booking, intewiews or other oppurtunities
* Contacting the band with intetion of puchasing Merchandise(t-shits, vinyl)

## UX:
####  Visitors of the site:
There are two main categories of visitors:
* Professinal, this could be a booker for a venue, producer, journalist etc.
* Casual, a fan of the band

##### Proffessional Visitor:
1. As a professional visitor of the site, I want to find some information about the band, so that I can write about them on my
blog/magazine/promotional poster ,etc.
2. As a professional visitor of the site, I want to contact the band, so that I can book them for my venue/party/interwiew etc.

#####  Casual Visitor (Fan):
1. As a casual visitor of the site, I want to see if there are any upcoming shows, so that I can go to them.
2. As a casual visitor of the site, I want to listen to Monocide, so that i can rock out.
3. As a casual visitor of the site, I want to find out more bout the band.

From the owners point of wiew the main objective of the site is to provide a more proffessional place (than instagram and facebook),
to promote future shows, projects, mechendise. As there are no current shows or tours planned the site will start of as mainly an official
way to get in contact with the band for prespective buisniss partners or show promoters.

#### Wireframe Mockups
Wireframe mockups were created using Balsamic  Mockups 3
- [Landing Page](https://github.com/jourm/Monocide/tree/master/assets/images/mockups/landing-page.wireframes.png)
- [About](https://github.com/jourm/Monocide/tree/master/assets/images/mockups/about.wireframes.png)
- [Media](https://github.com/jourm/Monocide/tree/master/assets/images/mockups/media.wireframes.png)
- [Merch](https://github.com/jourm/Monocide/tree/master/assets/images/mockups/merch.wireframes.png)
- [Contact](https://github.com/jourm/Monocide/tree/master/assets/images/mockups/contact.wireframes.png)
## Features: 

#### General Features
- Navbar - Exists on every page and allows users to easily navigate between pages. It features the bands Logo and links to all the pages in dark orange,
one of the bands signiture colors. The navbar is made responsive using bootstrap and collapses into a burger menu for small screens.
- Footer - Exists on every page and features links to the bands social media accounts. It is fixed to the bottom of the page so its allways aviable.
- Flavicon - The band logo in orange is the flavicon for all pages and gives a more professional feel.
- No effects - To keep the site cool and minimalistic, no hover or clicked effects have been implemented. 

#### Landing page:
A place to set up the overall feel of the site and a place to put banners with new important features. 
It features a picture of the band on stage and their logo hovers over the crowd. It currently does not have any banners,
but that can be implemented if the band releases new music or has a show to promote.
	
#### Bios page:
A page with some information about the band and its members. It features some text about the band in its whole,
picutres and text about the band members. The images are laid out in a responsive grid using bootstrap,
and the text is in a box with dark background to improve readabillity

#### Media:
A page where you can listen to the bands music via embedded players, either youtube or spotify.
it features an imbedded spotify player where visitors can play the band's latest music,
As well as a youtube window were music and music videos can be played.
(currently no videos exist so it will start of as music)
Embedded windows are made responsive using bootstrap to asure that videos keep their standard 16by9 aspect ratio.

#### Merch:
A page with pictures of merchendise and a contact form where fans can submit requests for merch, and get answers via email.
The images are laid out in a responsive grid using bootstrap,
and the text is in a box with dark background to improve readabillity.
The form is triggered by modal to keep the page clean. 


#### Contact:
A Page with official Contact form were the band can be reached with any iquiries about gigs, intevievs,
collaboration request or other businiss opportunities. 	

## Features To Implement
- add CAPTCHA to contact and merch forms to prevent spam.
- Connect forms to emailserver so that filled out forms get sent as emails to the bands address.
- If a tour is planned or more gigs are booked, add tour/gigs page with information and links to buy tickets.
- Add banner or jumbotron to landing page to promote said tour page.
- Possibly add Gallery page to feature more pictures.


## Technologies Used
- This project uses HTML5 and CSS3 programminga languages.
- This project was developed in [GitPod Online IDE](https://www.gitpod.io/) using a provided [Code Institute Template](https://github.com/Code-Institute-Org/gitpod-full-template)
- This project uses fonts imported from [Google Fonts](https://fonts.google.com/)
- This project uses icons imported from [FontAwesome](https://fontawesome.com/)
- This Project uses [Bootsrap4](https://getbootstrap.com/) for its responsive layout and certain featues from its content library.
- This project uses Embedded [Spotify](https://www.spotify.com/se/) and [Youtube](https://www.youtube.com/) for playing music and video.

	
## Testing:
the code has been run through and validated without errors by :
- For HTML:[W3C validator](https://validator.w3.org/) 
- For CSS: [Css Jigsaw validator](https://jigsaw.w3.org/css-validator/)
### Testing of User Stories
##### Professional visitor:
1. A visitor looking for some information about the band and its members can no matter what page they start on easily navigate 
to the [About page](https://jourm.github.io/Monocide/about.html) to find some information.
[Here](https://github.com/jourm/Monocide/tree/master/assets/images/screenshots/user-stories.information) is an example of the
path one would take. Starting from landingpage on the left and the clicking about to end up on the About page on the right.
2. A Visitor looking to get in contact with the band can easily navigate to the [Contact page](https://jourm.github.io/Monocide/contact.html) using the nav bar avaliable on top of all pages.
[Here]((https://github.com/jourm/Monocide/tree/master/assets/images/screenshots/user-stories.professional)) is an example of the path one could take, Starting on the landing page and then clicking contact in the nav bar and ending up on the contact page where there is a contactform to fill out.

##### Casual Visitor (Fan)
1. A visitor coming to the page looking for information about upcoming shows will be dissapointed, because there are none planned.
As soon as there are plans for a new show a jumbotron will be added to the Landing page with information and a link to it. Having an emty "tour" page would not improve the bands image.
2. A visitor coming to the site looking to buy some merchendise will easily be able to navigate to the [Merchendise](https://jourm.github.io/Monocide/merch.html) page using the navbar avaliable on all pages.
[Here](https://github.com/jourm/Monocide/tree/master/assets/images/screenshots/user-stories.fan.merch) is an example of what path on could take, starting from the landing page on the left and clicking Merchendise 
in the nav bar to then end up on the Merchendis page on the right.
3. A visitor looking for some information about the band and its members can no matter what page they start on easily navigate 
to the [About page](https://jourm.github.io/Monocide/about.html) to find some information.
[Here](https://github.com/jourm/Monocide/tree/master/assets/images/screenshots/user-stories.information) is an example of the
path one would take. Starting from landingpage on the left and the clicking about to end up on the About page on the right.

## Deployment

This project was pushed to github using git and deployed to GitHub Pages using the following method:
1. Go to [GitHub repository](https://github.com/jourm/Monocide)
2. Under the repository name in the top right, click Settings.
3. Scroll down to GitHub Pages.
4. Under Source, click the dropdown menu and select Master Branch.
5. The site is then published at https://jourm.github.io/Monocide/.

## Credits
#### Photos
All photos on the site were taken and edited by [Nina Melander](https://www.instagram.com/n__marguerite/)
#### Media
All text, Music and logos were obtained from Monocide.
