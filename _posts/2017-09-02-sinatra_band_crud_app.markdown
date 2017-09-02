---
layout: post
title:  "Sinatra Band CRUD app"
date:   2017-09-02 19:09:36 -0400
---


Much like the CLI gem that I created a little over a month ago, this project was a joy to work on! I must say that I did enjoy making the CLI gem a bit more than this Sinatra app because with that project, I felt at the end like I had created more of a realistic, viable product (as tiny as it may have been in scale), whereas this Sinatra app felt quite contrived. However, what I gained the most from it was the learning experience of building my first web app! 

The Band CRUD app is a very simple web app that allows a user, or musician, to create an account and become part of a virtual band and create virtual instruments for themself. Once a musician, band, or instrument has been created, they are permanently saved in a database that keeps track of all the musical data. Bands can have multiple members, or musicians, and musicians can have multiple instruments, creating a tree-like data structure with bands at the top and instruments at the bottom. 

The web app has a log in function for all musicians who've previously created accounts. When logged in a musician may edit the name or style of the band that they are a member of and the name and value of any of their instruments. A musician may not edit any information about a band they don't belong to or an instrument they don't own. A visitor to the site may edit no information while not logged in.

I can't say that creating this app was ever super conceptually difficult, but it felt slightly tedious to create so many different routes and views for the various data types. In the process, I definitely gained a greater appreciation for the big, powerhouse apps on the web like Facebook, Amazon, Twitter etc. I can understand why these companies now require literally thousands of coders to build and maintain their apps. What I can't quite wrap my head around is how someone like Mark Zuckerberg could create a viable app that was the scale of the original Facebook site. Of course it was far more minimalistic at the time, but it must have taken a while nonetheless. I now better understand why he had to skip classes at Harvard to code the project. 

It's not much, but just like the Stock Checker CLI gem, I'm proud of my little app! Sinatra's been a good hands-on learning experience, but now it's time for a more powerful tool....Ruby on Rails!
