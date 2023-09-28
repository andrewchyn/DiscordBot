# Hobbes Bot
A bot for the UBC Engineering Physics Discord Server. Written in Python 3.8.2 and hosted using [Heroku](https://devcenter.heroku.com/).

This bot was initially for my personal server, but was repurposed for use in the UBC Engineering Physics Discord.


## Features:
This bot is intended to replace common bots like MEE6 or Dyno. It mostly has entertainment commands as there isn't much moderation required in a school Discord server. Some highlights include role assignment through message reactions that only allows one selection at a time, logging the use of the word "pain" through sad cat images, and the ability to update everyone's year every September. 

## Planned Features:
- Basic Polls
- Game role assignment
- Better textbook system
- Remove Herobrine

## How to setup your own bot:
[I pretty much exclusively used the documentation, which includes decent examples](https://discordpy.readthedocs.io/en/latest/api.html). I also consulted the discord.py Discord for some difficult debugging.

## Pain
The pain logging became very popular, and to keep up with the output some of my classmates were putting out I had to learn about asynchronous programming patterns as well as database management in order to make sure all submissions were being parsed properly.
![pain](assets/pain.png) 
