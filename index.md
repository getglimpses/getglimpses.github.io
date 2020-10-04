---
layout: default
title: Quick Start Guide
nav_order: 1
description: "Documentation - glimpses - A simple and minimal journal app for windows"
permalink: /
---

# Keep memories alive
{: .fs-9 }

Welcome to glimpses!. With our minimalistic design, glimpses focuses on paving a simple journaling path for our users. In this guide we give an overview of how to get started with glimpses.
{: .fs-6 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

## Getting started with glimpses
### Pre-requisites
Below are the requirements to get started with glimpses.
- A Dropbox account
- Microsoft Windows 7, Windows 8, Windows 8.1 or Windows 10
Once  you have these at hand, you are all set to go!!.

### Download & Installation
glimpses can be downloaded when payment is made through our website, after which you will be receiving an e-mail with a link to download glimpses.

Once you have the `glimpses-setup.exe` file, you can double click to install it.
`glimpses-setup.exe` silently installs glimpses and will launch the app automatically.

### Log in
When glimpses is launched, you should see a welcome screen like below.
<img width="400" alt="glimpses welcome screen" src="https://getglimpses.github.io/assets/images/welcome-screen.png">

Click on **"Log in with Dropbox"** button. Then you will be prompted with the screen as shown below.

<img width="400" alt="glimpses login screen" src="https://getglimpses.github.io/assets/images/glimpses-auth.png">

Please press the **Open Dropbox Authorize page** button. Now app redirects the user to Dropbox authorize webpage.

After a successful sign in, you will be presented with a screen to authorize glimpses access to its own folder
**"Apps/glimpses"** in your Dropbox account.

<img alt="screen to authorize glimpses" src="https://getglimpses.github.io/assets/images/auth-page.png">

And once you authorize glimpses app, you will be provided with authorization code as shown below for a reusable token

<img alt="webpage with glimpses authorization code" src="https://getglimpses.github.io/assets/images/glimpses-code.png">

You need to copy this verification code and paste it on glimpses window (step2)

<img width="400" alt="step to complete authorization" src="https://getglimpses.github.io/assets/images/complete-auth.png">

Please be noted that we do not store your password anywhere in the application or in glimpses servers.
We use Dropbox OAuth 2 open specification for authentication and authorization. <br>
Please refer [here](https://www.dropbox.com/developers/reference/oauth-guide) for more details.

## Create a new journal entry
To create a new journal entry, click the **"+"** button on the menu bar or use key-board shortcut of `Cntrl + N`.

<img width="500" alt="glimpses add entry button" src="https://getglimpses.github.io/assets/images/add-entry.png">

Then glimpses sets a `distraction-free` mode. It hides all sidebar controls and lets you focus on the writing.

<img width="500" alt="glimpses distraction free mode" src="https://getglimpses.github.io/assets/images/distraction-free.png">

You can toggle the `distraction-free mode` by clicking on it again, which gives you acess to the side-bar.

## Add Image 

 Your entries can be made more memorable by adding an image to it. By clicking on the camera icon visible at the menu bar, you can choose your desired image from anywhere in your system. 
 
 <img width="500" alt="glimpses add image button" src="https://getglimpses.github.io/assets/images/add-image.png">
 
 The image you have chosen can also be changed by either delete & add or just by adding on top of it. 

## Favorites 

 Do you feel your journal entry for the day is special? Click on the star icon from the menu bar, and your entry will be added to the favorites list. 
 
 <img width="500" alt="glimpses mark favorite button" src="https://getglimpses.github.io/assets/images/mark-favorite.png">

 The star icon on the sidebar lists all your favorited entries. 

## Markdown 

glimpses comes with a support of ` common-mark ` compliant extensible markdown processor. The markdown button on menu bar is to preview you markdown entry, which on publishing will generate a private link, directing to an enriched HTML webpage.  

 <img width="500" alt="glimpses markdown preview button" src="https://getglimpses.github.io/assets/images/markdown-preview.png">

## PDF Export 

To export your journal entry to a pdf format, click on this icon.  

<img width="500" alt="glimpses pdf export button" src="https://getglimpses.github.io/assets/images/pdf-export.png">

Your entries can be saved to your system this way. 

## Publish 

Your journal entries can be published by clicking on the icon shown below.  

 <img width="500" alt="glimpses publish entry button" src="https://getglimpses.github.io/assets/images/publish-entry.png">

Once you click the button, a shareable link is created. Your default browser with this link is opened.
Link generated is completely private and is not saved anywhere on glimpses server. Copying this url helps you share your journal entry.  

This link is also uploaded to your Dropbox-links folder. If you no longer want the link to persist, you can simply delete the link file from Dropbox-links folder. 

## Delete entry 

Your journal entry can be deleted by clicking on the trash icon at the menu bar. The recycle bin icon on the sidebar gives access to all your deleted entries, which can either be restored or permanently deleted from glimpses.  

 <img width="500" alt="glimpses delete entry button" src="https://getglimpses.github.io/assets/images/delete-entry.png">
 

## Add tags to entries 

Tagging journal entries helps organize your entries based on any common theme. An entry can have multiple tags.  
Tags are added at the top of the editor, right below the menu bar as shown below. 

 <img width="700" alt="glimpses tags" src="https://getglimpses.github.io/assets/images/tags.png">

Tagged entries can be retrieved just by clicking on the tag icon at the side bar, where all your collective tags can be viewed. 

---
### Please help us to improve this docs.
If you think this documentation can be improved, feel free to discuss it in the issues.
Please fork our GitHub repository [here](https://github.com/getglimpses/getglimpses.github.io) and open pull request with improvements.















