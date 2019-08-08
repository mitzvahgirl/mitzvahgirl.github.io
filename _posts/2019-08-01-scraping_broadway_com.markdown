---
layout: post
title:      "Scraping Playbill.com"
date:       2019-08-01 21:34:10 -0400
permalink:  scraping_broadway_com
---





[![Screen-Shot-2019-08-08-at-9-16-52-AM.png](https://i.postimg.cc/9FdBMmnc/Screen-Shot-2019-08-08-at-9-16-52-AM.png)](https://postimg.cc/qz7KDTrF)






One of my goals for my portfolio and for the Flatiron School, is to relate each project to theatre, and to hopefully solve a "user problem." In this case, there is no evident user problem, as there are already a significant number of transactional theatre sites and apps that allow you to look for, select and purchase tickets online. 

The first project for the Flatiron School Software Engineering program includes creating a CLI data gem that provides a list of all shows playing on and off-Broadway. From that point, the user can get the theatre, address of theatre and the production's plot summary. For the purposes of this project, I will be scraping data from 
www.playbill.com, the online portal for the heritage brand of theatre programs.

The data from the site was scraped using Open-URI, which returns the HTML content and Nokogiri, a Ruby gem which parses the HTML and returns the selected production, using CSS selectors.

Step 1: (image to be inserted here)

The CLI will generate a numbered list of of shows. The user selects a show to see further details. The user can type **list**  to repeat the list or **exit** to end the program.

Step 2: (image to be inserted here)


Step 3:
A goodbye message will be generated upon user inputting the word **exit.**



Code for this gem can be found at:
[Github](https://github.com/mitzvahgirl/showbillgemCLI)
