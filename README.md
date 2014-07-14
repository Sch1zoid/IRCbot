 _____              __ _                       _   _            
/  __ \            / _(_)                     | | (_)
| /  \/ ___  _ __ | |_ _  __ _ _   _ _ __ __ _| |_ _  ___  _ __  
| |    / _ \| '_ \|  _| |/ _` | | | | '__/ _` | __| |/ _ \| '_ \
| \__/\ (_) | | | | | | | (_| | |_| | | | (_| | |_| | (_) | | | |
 \____/\___/|_| |_|_| |_|\__, |\__,_|_|  \__,_|\__|_|\___/|_| |_|
                          __/ |
                         |___/
 
Configuring IRCbot's name, channel and network is very simple. Change lines 7-8 to your liking, currently IRCbot is a 1-network bot meaning each instance can run 
on only one network.

7. server = "rizon.mibbit.org" # Server
8. channel = "#TheFusion" # Channel
9. botnick = "IRCbot678787859" # Your bots nick

 _____                                           _               
/  __ \                                         | |
| /  \/ ___  _ __ ___  _ __ ___   __ _ _ __   __| |___
| |    / _ \| '_ ` _ \| '_ ` _ \ / _` | '_ \ / _` / __|
| \__/\ (_) | | | | | | | | | | | (_| | | | | (_| \__ \
 \____/\___/|_| |_| |_|_| |_| |_|\__,_|_| |_|\__,_|___/
 
There are currently 7 commands the bot has; these are !rr, !help, !tough, hello, !pl, !def and !salute. 

!rr: This is the command to play russian roulette, simply type !rr and you'll have a 1 out of 6 chance of getting shot.

!help: This command links to https://github.com/cblankenship97/IRCbot/blob/master/commands.txt and returns "You think this crappy bot has documentation?" to the channel.

!tough: This command returns "Fite me IRL" to the channel.

hello: hello is simply used to greet the bot, and vice versa. Saying Hello botname will cause the bot to reply with "hello".

!pl: This is a simple Pyglatin translator, simple use it like so: !pl test.

!def: Get the definition and post it in the channel. Used by saying: !def test.

!salute: The bot will salute you.

______                  _
| ___ \                (_)
| |_/ /   _ _ __  _ __  _ _ __   __ _
|    / | | | '_ \| '_ \| | '_ \ / _` |
| |\ \ |_| | | | | | | | | | | | (_| |
\_| \_\__,_|_| |_|_| |_|_|_| |_|\__, |
                                 __/ |
                                |___/ 
Run IRCbot with the following command: python IRCbot.py
