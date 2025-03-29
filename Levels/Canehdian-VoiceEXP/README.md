# *WARNING*
This actionpack does not play well with Join to Create voice channels or any other voice channel that disconnects the user immediately after joining.
To bypass this issue, it is recommended to blacklist any of these voice channels from both actions.
![blacklist](https://micro.sylo.digital/i/9EDJsQ)

# Info

This Action pack will enable Atlas to give users Experience for the time spent in a voice channel.

# Getting Started

BE SURE TO READ THE WARNING AT THE TOP OF THIS README

There are 3 variables you need to change in total to start using these Actions.
1. EXPPerTime: the amount of Experience gained based on the set IntervalForEXPGain variable
2. IntervalForEXPGain: the amount of time it takes in a voice channel for a user to gain the set EXPPerTime variable (by default, the user gains 5 exp for every 120 seconds they are in a voice channel)
3. AFKChannel: This lets the script know what channel is the AFK Channel so it can blacklist users from gaining EXP there
