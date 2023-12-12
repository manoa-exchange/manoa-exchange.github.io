---
title: Manoa Exchange
---

### Important Links 
* <a href = "https://github.com/manoa-exchange">Github Organization</a>
*  <a href = "https://github.com/orgs/manoa-exchange/projects/1">M1 Project Page</a>
*  <a href ="https://github.com/orgs/manoa-exchange/projects/3/views/1">M2 Project Page</a>
* [M3 Project Page](https://github.com/orgs/manoa-exchange/projects/4)
* <a href= "https://manoaexchange.com/">Digital Ocean</a>
* <a href = "https://docs.google.com/document/d/1nteX543kMCYJGZ1wz_qUCjIUVHeU8d_F11VFqwEwwdI/edit">Team Contract</a>

## Table of contents

* [Description](#description)
* [Goals](#goals)
* [Installation Guide](#installation-guide)
* [Continuous Integration](#continuous-integration)
* [Community Feedback](#community-feedback)
* [Developmental Progress](#developmental-progress)
* [Deployment](#deployment)
* [Team](#team)

## Description

### Problem Statement

There are students who want to travel abroad, but have no prior experience, and there are students who have traveled abroad with lots of experience. These people don’t have a dedicated platform to interact with each other, leading prospective exchange students to have unrealistic perceptions of a given study abroad program.

### Our Solution

Our solution is a peer-to-peer study abroad experience sharing site which is an application designed for UH Manoa students to post about the experiences they had in traveling/studying in other countries. This enables and promotes student discussion on the topic of studying abroad.

### Landing

The landing page is presented when users first enter the site. There are several links to the Sign Up page, and it lists the features of the application. Additionally, there will be a carousel of resources available at the bottom of the page.

<img src="doc/screencapture-manoaexchange-2023-12-11-22_56_27.png" alt="concept-landing">

### Signed In Landing 

Students can post a picture to be shared with other users. The post component consist of an image, captions, likes, comments, saves, reports, tags, profile picture, and a comment section.

<img src="landinghome.png" alt="landing-home">


### Profile Page

The profile page displays the user's personal information as well as other social links. Their posts are visible.

<img src="doc/profilepageFinale.png" alt="concept-profile-page">

### Sign Up Page

Users can use the Register Button on the right hand corner of the navbar to register for a new account. Students will need to enter their UH Manoa email and ID in order to create new posts.

<img src="doc/registerM1.png" alt="concept-sign-up-page">

### Sign In Page 

To sign in, students can either use the link at the top of the navbar or in the Register page. 

<img src="doc/signinM1.png" alt="concept-sign-in-page">

### Add Post 
<img src= "doc/addPostFinal.png" alt="concept-add-post">

### Edit Post 
<img src="doc/EditpostFinal.png" alt="concept-edit-post">

### Comment Section

<img src="doc/commentsectionfinal.png" alt="concept-comments">

### Sign Out Page

<img src="doc/SignedOutPage.png" alt="sign-out">

### Saved Posts Page

<img src="doc/SavedPostFinal.png" alt="saved-posts">

### Moderation Page

<img src="doc/ModerationFinal.png" alt="saved-posts">

## Goals

Our aim is to make it easier for prospective study abroad students and former/current study abroad students to connect and share experiences with the ultimate goal of creating a realistic perception of UH Manoa's available exchange programs.

Create a site that allows users to:
- Register and sign into their account
- Have personal profile pages
- Create posts with images, descriptions, and tags
- Like, save, and reply to posts
- Report inappropriate posts and comments

Create a site that:
- Looks attractive and modern
- Is easy to navigate
- Allows special permissions for moderators


## Installation Guide
 
 First, [install Meteor](https://www.meteor.com/install).

Second, visit the [Manoa Exchange application github page](https://github.com/manoa-exchange/manoa-exchange-meteor-app), and click the "Use this template" button to create your own repository initialized with a copy of this application. 

Third, cd into the Manoa Exchnage /app directory and install libraries with:

```
$ meteor npm install
```

```
$ npm install obscenity
```

```
$ npm install cloudinary
```

```
$ npm install react-router-dom  
```

Fourth, run the system with:

```
$ meteor npm run start
```

If all goes well, the application will appear at [http://localhost:3000](http://localhost:3000).

## Continuous Integration

![ci-badge](https://github.com/manoa-exchange/manoa-exchange-meteor-app/actions/workflows/ci.yml/badge.svg)

Manoa Exchange uses [GitHub Actions](https://github.com/manoa-exchange/manoa-exchange-meteor-app/actions/workflows/ci.yml) to automatically run ESLint and TestCafe each time a commit is made to the default branch.  You can see the results of all recent "workflows" at [https://github.com/manoa-exchange/manoa-exchange-meteor-app/actions](https://github.com/manoa-exchange/manoa-exchange-meteor-app/actions).


## Community Feedback
 - " Cool features I like that the country names change, I was confused signing up and didn't realize I could scroll through the countries at the top."
 - "I really like it, but I wish there was more to look at like adding specific places in the countries."
 - "Very functional but easier to see on a laptop."
 - "Good looking, but maybe make it more mobile friendly, better fonts, and ability to see posts without logging in"
 - "Changing the colors for country tags to match their theme may look better"
 - "This website is super cool for the people who wants to study abroad and connect with one another. I also really like the color scheme of the website." -Josh C.
 - "It's easy to sign up. But the sign up page lands on the menu of the page, no the sign up part of the page" -Dom K.

## Developmental Progress

[Milestone 1](https://github.com/orgs/manoa-exchange/projects/1)

For M1, we will largely be focusing on implementing a UI. We will also implement a Profiles collection to hold data related to each user profile.
 <img src="doc/M1-done.png" alt="M1-page">


[Milestone 2](https://github.com/orgs/manoa-exchange/projects/3/views/1)

M2 Project page showing the issues expected to be addressed during the second Milestone for this project. Implement admin page, signed in home page, post/profile components, add saved post component and improve styling.
 <img src="doc/M2-done.png" alt="M2-page">
 
[Milestone 3](https://github.com/orgs/manoa-exchange/projects/4)

M3 Project Page, showing issues addressed for our last Milestone for this project. We improved forms, implemented adding images and filtering features in the home page, and made the viewing experience better on mobile
 <img src= "doc/M3complete.png" alt="M3-page">


## Deployment

We acquired the domain name manoaexchange.com and made it secure with an HTTPS.

[manoaexchange.com](https://manoaexchange.com)

## Team

<a href = "https://docs.google.com/document/d/1nteX543kMCYJGZ1wz_qUCjIUVHeU8d_F11VFqwEwwdI/edit">Team Contract</a>

Manoa Exchange is designed, implemented, and maintained by [Kelly Sato](https://kelly-sato.github.io), [Richard Baltazar](https://RichardBzar.github.io), [Kayla-Marie Torres](https://kaylamarietorres.github.io), [Josiah Kila](https://josiahkila.github.io) and [Lauren Clayton](https://laurenjc.github.io/).
