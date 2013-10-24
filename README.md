podwalk
=======
Podwalk is a learning project for me to experiment with the cowboy web server project:
https://github.com/extend/cowboy

My plan is to try and make a podwalking app for mobile devices.
Podwalking is where a group of awesome people go on urban hikes
whilst listening to a variety of podcasts.

A backend app would allow users to join an existing podwalk, at which
point they can be broadcast a variety of messages over web sockets.
For example, playback could be synchronized by updating player states
from a "master" client to everyone else in the group.

The current repo is a somewhat mangled copy of the bullet project's example app:
https://github.com/extend/bullet

I plan on building on this to create an implementation of the IRC Lite
project from jaerlang, so I can improve my erlang, and to create a base
from which I can extend an actual Podwalk API.
