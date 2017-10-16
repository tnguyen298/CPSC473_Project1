# Travel Voters


# Team Tadak

+ James Giang 
+ Angel Jimenez 
+ Josh Marvel 
+ Thao Nguyen 
+ Justin Shelley







# Overview of the Project


1. Project Scope

2. Installation and Configuration

3. User Documentation

4. Technology We Used

5. Reference Links











# Project Scope

Project scope

Tourism is one of the fastest growing industry in the world. There is a high degree of widening the services in this industry with the help of technology and infrastructure in connection with the globalization process. Following the path of the current market trend, we come up with a project to create an effective way of spreading information on well-known travel destinations that is specially catered to and contributed by the end-users. As such, we would like to introduce a website that allows user to post their travel destination and let other users review and vote on them. This website focuses on famous travel destinations worldwide, not just in America. It also comes with user-friendly and elegant design, helping travelers near and far gather information about a travel destination in a quick, easy, simple, inexpensive, and accurate fashion.

Project functionality 

Our website, Travel Voters, allows travelers near and far to go visit, read up on new trending travel destinations, post their favorite travel destinations, and upload their photo with their post. In addition, they can also vote for the destinations based on their personal criteria. The top 10 most favorite destinations will be featured on the homepage of our website. For privacy concerns, we require the users to login before accessing the page. Membership has always been free and will always be free, for unlimited time!



	






# Installation and Configuration

System requirements 
Intel or AMD processor (VT-x/AMD-V extension support required)
At least 8 GB of RAM
Stable Internet connection (20 Mbps or higher is recommended)
A 64-bit host operating system 
Apple's OS X 10.7 or greater
Microsoft's Windows XP 64 bit or newer
Software requirements
VirtualBox version 5 or greater (not version 4)
https://www.virtualbox.org/wiki/Downloads
Ubuntu MATE 64-bit VM
https://www.dropbox.com/s/9frc9x5blloo7a4/CSUF_Ubuntu_Mate_16_04_01_amd64_20170122.ova?dl=0
MongoDB
Deployd
Internet Browser (Chrome 60 and above is highly recommended)

Follow the following steps to obtain MongoDB and Deployd:
1. Download VirtualBox version 5: https://www.virtualbox.org/wiki/Downloads
2. Download Ubuntu MATE 64-bit: https://www.dropbox.com/s/9frc9x5blloo7a4/CSUF_Ubuntu_Mate_16_04_01_amd64_20170122.ova?dl=0
3. Install VirtualBox version 5 
4. Click on File>import Appliance
5. Point to the CSUF_Ubuntu_Mate_16_04_01_amd64_20170122.ova
6. Click on start
7. Use the following information username and password
    + username: 'me' 
    + password: 'me123'.
8. Installing MongoDB and Deployd:
    + For Windows, please go to this link and follow the listed installation instructions. 
    + For Linux/AppleOS, please follow these steps:
      -- Open terminal
      -- Enter each command line by line:
         $ sudo apt update
         $ sudo apt install -y mongodb nodejs nodejs-legacy npm
         $ sudo systemctl stop mongodb
         $ sudo systemctl disable mongodb
         $ sudo npm install deployd-cli -g
9. Creating a database using Deployd:
   After installing MongoDB, NodeJS, and Deployd, please open the terminal and enter these commands:
         $ dpd create NAME_OF_DATABASE
         $ cd NAME_OF_DATABASE
         $ dpd -d
10. Installing dpd-fileupload:
    In project root directory:
         $ npm install dpd-fileupload --save 
11. In Deployd dashboard, create a new Fileupload collection.




# User Documentation

Downloading the Source Code:
  Please follow the Configuration and Installation Steps, making sure all the software requirements are met.
  Please go to https://github.com/aJimmer/FE-Project-1 
  Clone or download the source code from the Github
  Open a terminal, navigate to the root folder of the cloned / downloaded source code
  Type the following command:
    npm install dpd-fileupload --save 
    dpd -d
  On the browser that displays Deployd dashboard, selects Open button on the top right corner to start accessing the page.

Login page 
  This page will allow user to gain access to post, edit, and review
  Sign in
  Sign out
  Allow user to go to the signup page

Signup page
  Create username and password
  Allow user to go back to the Login page

User homepage (or Welcome page)
  After logging successfully the home page will appear with their name and Logout button (show name allow Posting, or plus sign)
  Homepage with the posted destination photos
  User will be able to hover mouse over each thumbnail to see the enlarged picture of the destination at the bottom.
  Clicking on a photo shows a modal window of the destination, description, and rating and allow user to rate the post from other users. 
  Clicking on the X icon (top right) or the Close button (bottom right) will close the modal 
  User will be able to vote on an existing destination, upload pictures, and/or leave a review.
  User Post function 
  On the top left there is a “post” icon to get to the posting function
  User will be able to type in the location, description, rate the location and upload pictures of the destination


# Technology We Used

Back-End
    Ajax
    Deployd
    MongoDB
    NodeJS
Development Tools
    Atom
Languages 
    HTML5
    JavaScript
    CSS3
Front-End 
    Bootstrap 3.3.7
    Google Fonts APIs
    Mustache










# Reference Links


http://www.travelandleisure.com/trip-ideas/best-places-to-travel-in-2017
http://www.travelandleisure.com/trip-ideas/solo-travel/best-places-for-women-to-travel-alone
https://v4-alpha.getbootstrap.com/components/modal/
http://html-tuts.com/html-photo-gallery-simple-javascript/
http://docs.deployd.com/docs/
https://gist.github.com/elmariachi111/5407282

