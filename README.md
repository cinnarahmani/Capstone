# Capstone
##PDX Coding Guild
##MADRISAH Veteran Discussion Panels
#Project Overview
##The major featrure of this web application is connectioning veterans by hosting discussion panels
##The problem the web application is attempting to solve is centralizing communication, resources, and community during the transition to civilian. Furthermore, the web application (madrisah.org) seeks to provide networking, mentorship, and comradery needed to sustain and endure hardships of civilian life.   
###The library that will be utilized are django for backend need and vanilla javascript, html, css for front end needs.
#Features
###The user's perspective will be a general chatroom interface with specific panels that contain specific topics, moderators, and hosts. Furthermore, the user will be able to utilized archived resources that other users determined useful based on topics. The user may suggest a topic as hosts, but would not be required to moderate the panel. The panels members would decide on a moderator based on the moderator's rating. The panels member will set a date and time then conduct their panel. At the conclusion of the panel, the panel members will be asked to rate their overall experience. The actual panels would be conducted by third party applications ie zoom, teams, or other video chatting applications, but the panel will be reviewed by the panel members for feedback and data 
##User Stories
###As a panel member, I want a password protect profile via login because I want my personal information to be secure.
####-username
####-password
###As a panel member, I want to be able to propose a topic because I want to inquire if others are also interested in a panel on that topic.
####-post topic
####-join a topic
####-with enough panel members becomes a pre-panel
####-3 members or more is a panel and less than 20 (ideally 14)
###As a panel member, I want to vote for the moderator because some people are better moderators than others.
####-vote for moderator
###As a panel member, I want to be able to review the experience of panel because I want to give feedback.
####-rate a moderator
###As a panel member, I want to review fellow panel members and be reviewed by them because it's important to get feeback on profressional, respect, and courtesy.
####-rate panel members
###As a panel member, I want to search for resources from previous posts because I want resources vetted and centralized
####-search resources
####-establish API for resources
###As a panel member, I want be able to partipate in chats if the topic is not private because I want others in future to benefit from the discussion.
####-be able to choose between chatroom format and discussion panel
###As a panel member, I want to be able to join comradery because I want to be able to decompress via humor, emotional support or friendship.
####-join a group
####-panel members join a group
###As a panel member, I want to be able to form comradery by transitioning to a host member because I want to be able to decompress via humor, emotional support or friendship.
####-become a host member
####-register a group
###As a host member, I want to be able transition back to panel member because I may not want to host the zoom, team, or other communication platform.
####-leave group
####-stop hosting
####-transition to panel member during discussion panel
###As a host member, I want to be able to post my hosted platform because after the moderator and panel members have been formed, it's my responsiblity to host.
####-post platform hosting plan
####-confirm number of panel members
###As a host member, I want to review fellow panel members and be reviewed by them because it's important to get feeback on profressional, respect, and courtesy.
####-rate host member
####-rate fellow panel members
###As a host member, I want to be able to moderate my group because to set group culture.
####-allow posts to be flagged
####-notify admin of flag
####-review flag by admins
####-delete flagged post
####-warn host for inappropriate flag
###As a host member, I want to to be able to delete flagged posts, because it's my job to set the stanard for the group culture.
####-delete posts
###As a moderator member, I want to be able transition back to panel member because I may not want to moderate a panel discussion.
####-cancel being moderator
###As a moderator member, I want to be able to moderate the discussion panel because I want to get a good review and demostrate my ability to moderate.
####- rate panel members
###As a moderator member, I want to review fellow panel members and be reviewed by them because it's important to get feeback on profressional, respect, and courtesy.####-rate panel members
####-rate discussion
###As a host/moderator member, I want to be able to be the moderator/host because I prefer to take the lead on making the discussion panel happen.
####-be host and moderator
###As a moderator member, I want to be able to flagged users who have violated the moderators review and report to admin because that's my job.
####-flag users
###As an admin member, I will review with other admin members to vote on decisions concerning flagged users for violations in the community, whether that's in the groups, during discussion panels, or other engagements, because there needs to be judicary decisions made by the community for the community
####-ban user
####-temp ban user
####-reject flag
##Functionalities
###Admin User will see pending flags that will needed to be voted upon after all votes from determined then if majority vote for a ban, then user will be temp, perm, or warned.
###Panel User will see topics, moderator, nav bar, their profile, resources, and panel information. They can click to join a panel or chat, which will be recorded prompting rating and reviews.
###Host User will see topics, moderator, nav bar, their profile, resources, and panel information. They can click to join a panel or chat, which will be recorded prompting rating and reviews. They can host groups, flag, and delete posts or users. They can post the hosting link confirm date and time.
###Moderator User will see topics, moderator, nav bar, their profile, resources, and panel information. They can click to join a panel or chat, which will be recorded prompting rating and reviews. They can flag users. They can confirm the date and time of the discussion panel.
#Data Model
The data that I will need as part of application will be User via Network Model as te Databse Schema Designs. I was also use messages via the chatroom/panel discussion via Flat Model Schema to record the moderator, host, topic, and members. 
#Schedule for Iterative Development by Morning of Each Day
##April 4, 2022
###Finish previous labs
###Custom User ie similar to Pokedex Lab
##April 5, 2022
###Finish Django backend just panel members ie login, register, and posting ability with discussion panel chatrooms based on topic and feed for working back-end.
##April 6, 2022
###Finish the flat model Schema ie with styling and javascript for working front-end.
##April 7, 2022
###Finish the flat model Schema ie just panel members with discussion panel chatrooms based on topic, moderator, and host.
##April 9, 2022
###Internal API
##April 11, 2022
###Rating Features
##April 14, 2022
###Flagging Features
###Group Features
##April 15, 2022
###API resource feature

#Setting up MVP
##Essential features
###Panel users
###Discussion Panel Chatroom
##Really great to haves
###Peer Rating system
###Post Panel review rating
##Nice to Haves
###Admin users
###Flagging features by hosts and moderators
###group ability by hosts
###resources API
