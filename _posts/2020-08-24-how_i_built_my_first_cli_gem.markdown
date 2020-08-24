---
layout: post
title:      "How I Built My First CLI Gem"
date:       2020-08-24 16:20:18 +0000
permalink:  how_i_built_my_first_cli_gem
---

My first CLI Gem is a fun directory of Harry Potter characters and spells. I utilized the Harry Potter API  for my “Potter World” gem. Continue reading if you’re curious about the magic behind Ruby’s Object Oriented Programming as it relates to “Potter World”, and what I learned after completing this project!

Planning
 
I opted to use an API instead of scraping data because I wanted to learn more about consuming API’s, and this was a great opportunity to do so. After finding the proper API and reading the documentation, I chose two endpoints to acquire character data and spell data. Rather than jumping straight to the code, I wrote down a detailed flow of the application from the user’s perspective (I “stubbed out” my program). 

Development - Phase 1

Setting up my gem dependencies, files, and folders to communicate with each other was the first phase of development. I created folders, and within those folders I had separate files for each class and complied with the single responsibility principle. It was crucial that my files and folders were all speaking with each other. Once I confirmed my executable file was properly running, I continued with the next part of development. 

Development - Phase 2

I used Rest-Client to get the data from my API, and JSON to parse. Once I had my data, I added methods and logic to my classes. I used pry to debug, and jumped from one class to the next to bring my program to life. The end result was a program that contained excessively long conditionals, oddly-named variables, and arbitrary methods. Despite this inelegant looking code, my program worked as desired! My work was far from done - I wanted to refactor this Riddikulus code. 


Refactoring

I revisited previous labs that I’ve completed, such as the Student Scraper Lab and Music CLI for guidance. Instead of using conditionals, I used a loop to output messages and prompt the user on what to do. I renamed variables to be more descriptive and provide some context. With the help of technical coaches and other Flatiron students, my Potter World gem is more dynamic, streamlined, and user-friendly!



