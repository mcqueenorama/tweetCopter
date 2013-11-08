tweetCopter
===========

An node.js AR Drone script that pulls commands from twitter,

Send commmands by sending tweets to @yourself so it won't pollute
your timeline.  The commands are shortened because I sent them via
the old 40404 SMS interface when I did the demo.

takeoff: @yourself to
land: @yourself la
counter clockwise: @yourself cc
clockwise: @yourself cw
stop: @yourself st

It allows an unruly mob to all send commands to the copter at once.

I didn't enable many commands because the demo would get too chaotic.

One tricky thing is the drone is on wifi, but twitter is on the
internet, so you need to be plugged in to the internet or else the
program can't reach twitter.  Your puter needs to be able to handle
two networks, one for the drone and one for the internet.

I got most of the code from this repo:  https://github.com/felixge/node-ar-drone

I had to install this:

npm install twit
