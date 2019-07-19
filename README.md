# Restyle website rapper Lange Frans

This is the repository of the frontend only (restyled) website of the Dutch rapper and tv-host Lange Frans. The primary focus of the website is to let fans and potential fans to see and hear video clips and songs and let them know about new music as it becomes available.
The aim of the website is also to link the target group to Spotify to let the fan base grow there. Another aim is to give information about upcoming events where Lange Frans is on stage.
Social media is also integrated to give social media platforms like YouTube, Instagram, Facebook and Twitter a presence.

## Demo

A live demo can be found [here](https://devricardotubbs.github.io/frontend-milestone-project/).

## UX

Giving fans and potential fans the ability to see and hear video clips and getting cohesion with Spotify were top of mind while designing. Therefore I created several user stories:

* As an existing fan I want to see video clips 
* As an existing fan I want to hear songs
* As an existing fan I want to follow Lange Frans easily on Spotify
* As an existing fan I want to know when are the upcoming events
* As an existing fan I want to buy tickets for upcoming events
* As a existing fan I want to read something from Lange Frans’ background/bio
* As potential fan I want to see video clips to see if I really like Lange Frans 
* As potential fan I want to hear songs to see if I really like Lange Frans
* As a potential fan I want to read something from Lange Frans’ background/bio
* As an potential fan I might want to follow Lange Frans easily on Spotify
* As an event organization I want to know who I can contact for bookings
* As a journalist I want to know how I can reach the management

The wireframe of the design you may find [here](../blob/master//documentation/User Centric Frontend_CI_v1_05072019.pdf)

## Features


In this section you will find all features and the details of it.

### Current features

**Navigation**
* The mobile friendly Bootstrap navigation bar allows users to have a navigation at all times: a hamburger menu on smaller devices and a one click navigation bar at the top for larger devices

**Button to Spotify**
* The Spotify button in the header allows users to navigate to the Spotify website in a new window
* From a design perspective the button is only available on screen sizes from 992px width

**Spotify follow widget**
* The Spotify follow widget allows users to follow Lange Frans easily on Spotify
* Originally this feature was an iframe which is coded to an object to pass the w3 validator test

**SoundCloud music player**
* The SoundCloud’s music player allows users to enable hearing a song without video. Also this feature was a design choice.
* Originally this feature was an iframe which is coded to an object to pass the w3 validator

**YouTube videos**
* The YouTube feature allows users to watch video clips
* While integrating this feature Bootstrap’s embedded classes were used

**Biography**
* The biography feature allows users to read more about Lange Frans’ history.
* The bio section is made of 2 columns. For design and functional reasons the image of Lange Frans on the left disappears on screen sizes below 992px

**Event section**
* The event feature allows users to see the agenda of upcoming events.
* This feature has 2 main columns which have a breakdown point on 992px to make it look good at all devices.

**Photo gallery**
* The photo gallery feature allows users to see some photos of Lange Frans
* For this feature Bootstrap’s img-thumbnail and img-fluid classes were used

**Spotify playlist**
* The Spotify playlist feature allows users to quickly select a song of there preference
* Originally this feature was an iframe which is coded to an object to pass the w3 validator

**Social links**
* The social media links allow users to surf quickly to the platform of their choice

**Modal**
* The modal feature in the code allows me to show the links are working

### Features Left to Implement
* Buy tickets online
* Purchase albums 
* Other activities than rapping


## Technologies Used

* HTML5 for structuring the website
* CSS for styling  the website including animation
* Bootstrap 4.3.1 (including the Javascript, jQuery and Popper.js)
-	Grid
-	Navigation bar
-	Responsiveness 
-	Modal
-	Specific Bootstrap classes 
* Animate.css for text animation in header 
* Google Fonts for using the font Source Sans Pro
* Font Awesome for social icons 
* Cloud9 as an IDE
* Atom as a fall back editor
* Git and GitHub for version control
* [DirtyMarkUp](https://www.10bestdesign.com/dirtymarkup/) for marking up HTML and CSS code 
* [Mockflow.com](https://www.mockflow.com} for making the wireframe
* GIMP and inPixio for editing images

## Testing

The website was tested in several browsers (Chrome, Firefox, Safari and Microsoft Edge) and on several mobile/tablet devices (Samsung Galaxy S5, iPhone 5/SE/6/7/8, iPhone 6/7/8 Plus, iPad and iPad Pro).

The HTML code was tested with the [W3 Validator service](https://validator.w3.org/) and issues, mostly related to some iframes, were solved. One warning relating to a header missing in the audio section I ignored with a reason: for design reasons I don’t need a header and from a coding perspective I want to be consistent in using semantic elements.

The CSS code was tested with the [CSS validator service](https://jigsaw.w3.org/css-validator/). No issues were found.

Testing was a continuous activity during the coding process. In an early stage there was a white space on the right on mobile devices. The solution for solving this issue was found on Stack Overflow in a post of [Rion Williams](https://stackoverflow.com/users/557445/rion-williams).

All external links are opening in a new tab using or have a modal popping up when the link is not available or when it is an email address. These links were tested manually to see if they are working and indeed opening in a new tab.

The user stories and related features were tested manually as well. By doing this at the end of project one more time it came out that I have to do a minor fix in the navigation.

## Deployment

The site is directly deployed from the master branch and hosted on [GitHub pages](https://devricardotubbs.github.io/frontend-milestone-project/index.html). New commits to the master branch will automatically be updated to the deployed version.

To run the website elsewhere it can be either downloaded on [GitHub](https://github.com/DevRicardoTubbs/frontend-milestone-project) or cloned by pasting ‘git clone https://github.com/DevRicardoTubbs/frontend-milestone-project.git’ into your terminal. 















This repo is for educational purposes only. 
