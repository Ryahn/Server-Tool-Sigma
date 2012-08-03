Server-Tool-Sigma
=================

Restart, Log Rotations and Heart Beat

I have been looking for a decent script or program to do server restarts and log rotations with ease but could never find one to suite my needs. So I decided to make my own and its based off the ideas of some current scripts already currently out there which I will give credit to in my work. The only down side to this, is that its only for dedicated servers only and I have no plans to make it available to managed servers. I will however be allowing server host companies use my program once its in full release. This script will not be in batch file form and will be in .exe.

Required programs: BEC (Battleye Extended Controls)

Features
Restart Server
Rotate Logs
Heart Beat
Anti-Crash
Crash Reports

TO-DO
Add the ability to add custom wildcards
Add specify log rotation folder
Add addon boot programs
Make crash reports more informative
All in one exe

Little FAQ
Q: What is a heart beat?
A: Think of the human heart. If someone wants to see if your alive, they check for a pulse. The same since is applied to servers. In my case, I use the "-pid=" argument in my server config. This allows you to run multiple servers.

Q: Anti-Crash? What?
A: Yes you hear right. There is an issue at times that popular servers like to crash or get the server has stopped responding. This means server owners have to RDP into their dedicated and restart it by hand.

Q: Why BEC? Why make it require?
A: Answer is pretty straight forward. BEC has everything already setup to what I was going to add to my script. You can schedule when you want things to run. You may use windows schedule tasks but this is way easier


Credits:
Stian Mikalsen (Maker of BEC): He as been a great help in helping me figure out how work BEC to its fullest. Once I have his permission, I will me packaging BEC in with my program.
Adam McKissock: Made the log rotation part of my script and troubleshooting since I am still a n00b to him.
R4Z0R49: The inspiration to make this program and had permission to use some of his to give me a good working ground.
Shawn-Dante: Because he is a ninja with Legecy

Disclaimer: I am not liable if this program causes files to delete, go missing or corrupt. You have been warned


Copyright: This work is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 3.0 United States License. To view a copy of this license, visit http://creativecommo...-nc-sa/3.0/us/. 

ETA: When I get volunteers to test it.