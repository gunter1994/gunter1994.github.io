---
layout: default
---

In this website I will give you a quick walkthrough of my projects, and experiences in coding. As well as some of my personal interests

# About Me

I'm a computer science graduate from UOIT (or as they tell me, it's "OnTechU" now), after my graduation I spent another year doing research and teaching, to figure out where my core interests in computer science lied. Afterwords I decided what I had the most fun doing was software development, and web design. I'm currently working freelance trying to hone my skills for the workplace.

In my free time I like playing guitar, and sing in a band, just for fun. I also work on fun programming projects like physics sims, or teaching AI to play games. But hey, this isn't a recipe for my grandmas famous apple pie so enough intro.

# Undergraduate Projects

First I'm going to go through my most notable projects from my undergrad.

## Snake Frenzy

The first project worth mentioning was one from my second year, a game called snake frenzy. Obviously the game of snake isn't very complex, and I've recreated it in a much more efficient manner now in an hour or so in pygame. However, this was my first group programming project, and it had a few extra features such as menu's, music and sound effects, and an online leaderboard.

For more information check it out here

## Robot Hockey

This project was for an open ended class about learning new programming languages, you were to create whatever you wanted in a language you had no experience in. I chose to create a physics based hockey game, using square robots. The game features full controller support, and was built primarily in Kotlin with some Java backend.

For more information check it out here

## Water Sim

This is actually 2 projects in 1. The first was a rather slow running simulation of water droplets interaction together, to actually view it properly it was designed to save frames to file, and than combine them to video at the end for real time playback. This was an extremely challenging project, and took a lot of math understanding to run.

The second part was where I combined with a partner, originally we were going to have a kind of fish tank. Where I simulated the water, and they simulated the AI for the fish. It became quickly apparent however my current setup was much much too slow to render for an entire tank. This meant I had to change my model from being particle based, to using stationary pixels of water. Since the water now couldn't move, it instead gave a force in a direction based on how the fish were moving through it (creating wakes).

For both implimentations look here

## Undergrad Thesis - Video Summarization

I decided to complete an optional undergrad thesis, where I created a program for automatically summarizing video. This involved learning OpenCv2, and some basic AI. Essentially, I would cut the video into segments, than move the start and end times of the segments based on camera movement. This means all cuts are done when hopefully nothing is happening on screen (or as little as possible). Than every segment is rated based on several categories of quality. Finally the program decides which categories are the most important, and creates a final decision on which segments to choose. 

Than based on how much we wish to shrink the video, we create a new summarization which uses an algorithm to weigh length against importance.

For more information check it out here

## Graduate Project - User Study

