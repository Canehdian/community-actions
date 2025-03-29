# *WARNING*
This actionpack does not play well with Join to Create voice channels or any other voice channel that disconnects the user immediately after joining.
To bypass this issue, it is recommended to blacklist any of these voice channels from both actions.
![blacklist](https://micro.sylo.digital/i/9EDJsQ)

# Info

This Action pack will enable Atlas to give users Experience for the time spent in a voice channel.

# Getting Started

BE SURE TO READ THE WARNING AT THE TOP OF THIS README

There are 3 variables you need to change to start using these Actions.
The Voice Channel Leave action has 2 variables for the amount of Experience and duration to apply it across. (By default it adds 5 experience for every 120 seconds the user is in a voice channel)
The Voice Channel join action has 1 variable which should be the AFK channel's ID so users can't gain Experience for being AFK.
