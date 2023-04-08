---
title: "Project List"
date: 2023-04-07T20:48:55-04:00
description: "Example article description"
menu:
  main:
    name: Projects
comments: false # Enable Disqus comments for specific page
---

Of the 70+ projects I have floating around on GitHub, here are a few I find most interesting...

<!--more-->

**Complex API [complexapi](https://github.com/FredLackey/complexapi)**  
Don't let the name fool you.  The API itself is incrediby simple.  The goal of this 'lil project was to have an easy-to-use sample API that I could use for training of various microservices concepts.  For example, the need to chain APIs together or testing upstream connectiviity.

**Cleaner Node [cleaner-node](https://github.com/FredLackey/cleaner-node)**  
A growing toolbox of helper functions with the goal of allowing you to write clearner NodeJS projects.  No extending prototypes.  No creation of messy `utils` folders in your projects.  Deal with both primatives (strings, numbers, etc.) and complex data objects with a single line of code.  Think Lodash but more useful.

**CICD.sh [cicd.sh](https://github.com/FredLackey/cicd.sh)**  
More of a teaching effort than anything, CICD.sh shows how to implement a complext CICD pipeline with a single BASH script.  The site it's hosted on ([http://cicd.sh](http://cicd.sh)) also provides a bunch of examples on Terraform (also single page examples) to think through how one might use Terraform in their efforts.

**Flowroute SMS Email Proxy [find-file-types](https://github.com/FredLackey/flowroute-sms-email-proxy)**  
Delivered as a Docker image, this simple project allows users of the Flowroute trunking provider to receive SMS and MMS messages and have those messages forwarded to a catchall email address.  Great for those moments when someone assumes your DID is a mobile number.

**Find File Types Utility [find-file-types](https://github.com/FredLackey/find-file-types)**  
Simple command line utility to locate and count the various file types in a directory structure so you know what you're dealing with.  Very helpful when working with multimedia files.

**File Date Organizer [file-date-organizer](https://github.com/FredLackey/file-date-organizer)**  
I take a lot of screenshots.  Sadly, they are all shoved into the same folder.  This command line utility seaks out the files with a date stamp in the name and reorganizaes that massive folder into a more managable heirarchy using the year, month, day, and so on.  As long as the file has a date in the title, it'll be organized.

**File Line Replacer [file-line-replacer](https://github.com/FredLackey/file-line-replacer)**  
Developers often need to replace parts of files while handling special scenarios.  From preserving whitespace, to creating backups of edited files, or dealing with case sensitivity, most of the existing command line utilities fall short.  This utility handles thos complex tasks while using an easy-to-read command line syntax.

-----

**RESTUtils [restuils](https://github.com/FredLackey/restutils) & RESTUtils Lib [restuils-lib](https://github.com/FredLackey/restutils-lib)**  
This one has taken on a life of it's own and has moved to it's own domain and GitHub account.  RESTUtils gives a developer to stand up a fully-functional API without writing a single line of code.  If they _do_ want to create something fully custom, they can cretea a web-based RESTful API by writig simple JavaScript functions without worry about the server logic (Express, Hapi, etc.).
