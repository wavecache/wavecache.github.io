## Table of contents

* [Overview](#overview)
* [User Guide](#user-guide)

## Overview

![ci-badge](https://github.com/wavecache/sharkbreaks/workflows/wave-cache/badge.svg)

WaveCache is a project designed to list and categorize various beaches and Surfbreaks around UH Manoa and Oahu.  The breaks could be listed by distance from campus, by skill level, wave direction (lefts or rights), ideal swell directions, and ideal swell sizes.  This app could be helpful for the students who have come to UH Manoa from other places and would like to know which beaches would be ideal to surf for their skill level.  Maybe we could include potential hazards as well and a basic descirption of the location.  We could also add additional information to the app such as other activities that could be done at the beaches, such as swimming, snorkeling, volleyball or scuba diving.  We plan on having two roles, an administrative role as well as a basic user role.  Users can view the places while admins can make changes.  Different tabs could be used to reflect different skill level or other categories.  A user can specify skill level and get various suggestions based on their skill level.  User logs in, sets up profiles and can browse or receive suggestions.  We could also implement a rating system where users can rate the breaks.  Depending on how far we get maybe some beyond the basics features could be implemented, user generated reviews of places or maybe a chat area where people can discuss.

The current mock up can be found <a href="https://studntnu-my.sharepoint.com/:b:/g/personal/lassetw_ntnu_no/ER4MvZZXC5VJkEwnQwLg744BxYV8sqoXK-FxqbB4tIq1rw?e=dQj4tf">here</a>.

The GitHub organization associated with this project and all of its repositories can be found at <a href="https://github.com/wavecache">this link</a>.

Our first project board, M1, can be found <a href="https://github.com/wavecache/sharkbreaks/projects/1">here</a>.
  
Our second project board, M2, can be found <a href="https://github.com/wavecache/sharkbreaks/projects/2">here</a>.

Our third project board, M3, can be found <a href="https://github.com/wavecache/sharkbreaks/projects/3">here</a>.

## Community Feedback

### Andreas Fosse, UH Renewable Energy Engineering(Exchange Student)
I like the way the site showes me breaks I did not know about, and that I can filter easily if I am looking for a specific one. I also like that you can add your own breaks and that it is connected to your profile. However, I would like if some of the community features were more expanded. I think this would have been fixed with time, but it would certainly have lifted the experience.  

### Jack Walter, Local Surfer and Student at UH
I’d like to have the website include real time footage of what the surf is like at the most popular surfing spots. I´d also like some information on what breaks are used by the locals and experienced surfers, and which ones that are suitable for beginners.

### Justin Silver, CTAR Student at UH
I really love the user interface. The overall aesthetic of the website is very pleasing to look at and its easy to navigate through as well.

My favorite part of this website though is the up to date weather reports. It comes in handy when a few friends and I want to go out and surf but aren't sure of the conditions.

Thanks a lot!

### Nick Kwon, Engineering Student at UH
1) the front page, this is kinda nit picky, but the sentence that starts with and just seems kinda funky. I think it would be better if you just said welcome

2) i dont actually know how to become friends with other people, so the friends page seems kinda odd

3) when i got to my profile it looks like it pulls up someones else's profile or something? not really too sure how to describe so ill send a picture.

4) does the filter actually work? might be another instance like the account registering where it is filtering results, but i didnt see any visual queues, so i didnt seem like it was working.(This feature has been improved based on the feedback)

other wise looks really great! i really the like the color palette you chose, everything looks clean, very informative and overall seems like some thing i would really wanna use if i was into surfing! I like the logo you found/made. especially love the site name, i always appreciate a good punny/catchy name xD

### Ryan Vizcarra, Computer Engineering Student at UH
My initial thoughts of the design and first impression of wave cache.surf is “wow” after it loaded for the very first time for me. I like the massive picture in the middle that coincides with the color scheme of the site. Your eyes tend to just focus on the central point in the picture which is what wave cache is compared to other websites that’s way way too busy, which tends to overwhelm me but not wave cache which is good.  The sign-up page looks great all fields looks to be working nice touch on making the color for “stay informed about” that really helped make it stand out. In the find your break tab everything is nicely executed.  Clicking on area opens up a new page that gives you a lot more information about the location. I like how each section has an introduction I like knowing what i’m getting into. haha. Overall I can tell a lot of thought has gone into creating this awesome website. As with any developing website there are some really minor issues that i’m sure given a little bit of more time would have been fixed. For example, the filter function in find your break doesn’t seem to work but it doesn’t take away from the site a whole lot cause there are other ways to find what you need.(This feature has been improved based on the feedback)

## Deployment

The site is located at <a href="http://www.wavecache.surf/#/">Wave Cache</a>, come join us! 

## Installation

First, [install Meteor](https://www.meteor.com/install).

Second, go to [https://github.com/wavecache/sharkbreaks](https://github.com/wavecache/sharkbreaks), and click the "Code" button. Then clone the directory to your local computer. Using [GitHub Desktop](https://desktop.github.com/) is a great choice if you use MacOS or Windows.

Fourth, cd into the app/ directory of your local copy of the repo, and install third party libraries with:

```
$ meteor npm install
```

## Running the system

Once the libraries are installed, you can run the application by invoking the "start" script in the [package.json file](https://github.com/ics-software-engineering/meteor-application-template-react/blob/master/app/package.json):

```
$ meteor npm run start
```

## User Guide

This section provides a walkthrough of the Bowfolios user interface and its capabilities.


### Landing page

This page will have the navbar, a surfing background and some basic welcoming info about the site.
The following is a current screenshot of our Landing Page.
![Picture of the landing screen](/Images/LandingPage11-18.png)


### Sign in page

Where returning users sign in.


### Sign up page

Where new users sign up.
<a href="http://www.wavecache.surf/#/signup">Here</a>

<img src="/Images/Register.JPG">

### Profile page

Where your profile is displayed, (must be signed in the view)
<a href="http://www.wavecache.surf/#/profile">Here</a>

<img src="/Images/Profile.JPG">



### Friends list

Where you can see the contact info of people you've talked to before.


### List of breaks

![Surf Breaks](/Images/SurfBreaks.png)

A list of all the breaks in the system. If you are logged in, you are able to add a new break. In addition you can edit and delete the breaks made by yourself. By clicking on the card title, it takes you to the surf break page.

By writing in the filter section, you can find the break you are looking for.

### Add surf break page

Add a surf break if logged in. The changes is sent to the Mongo database and updated throughout the app. 

![Surf Breaks](/Images/addPage.png)

### Edit surf break page

Edit a page made by the logged in user. The changes is sent to the Mongo database and updated throughout the app. 

![Surf Breaks](/Images/editPage.png)


### Page for each Break


![Surf Break Page](/Images/surfBreakPage.png)

Each break will have its own page with all the information known on it, as well as an overview of the friends who have liked the break.

Currently the page can get information about the break from the Mongo data base. It is also fetching data from an API every 10th second. The like fuctionality is missing, but will be implemented once the friends list fuctlionality is done. 

You can also click on the map which directs you to the correct location on Google Maps.

On the bottom of your page you can see all the users who follow the break.


### Public forums board

Public exchange of ideas, where there will be a list in order of recency, of all the threads of conversation people have about things like the best beaches, best beaches for new surfers, meetups and whatever else people want to talk about.


### Page for each public forum

Each discussion will have its own page.


### Admin homepage

The page where admins can see all of the information across the site, such as users, activity etc.

## Developers

### Quinn Bianchi-Lawson

A computer engineering student at UH CoE, Quinn is scheduled to graduate in Spring 2022.

### Constantine Peros

Constantine is an ICS student, interested in game development, AR, VR, Cryptocurrency, Robotics, and Surfing.

### Chase Miyasato

Chase was born and raised in Hawaii and has been surfing from a young age.

### Lasse Wardenær

Lasse is a graduate student doing an MSc in control engineering.

-----
