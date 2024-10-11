# OverTheWire Bandit Guide for CCDC 2025 Linux Training

https://overthewire.org/wargames/bandit/

### Objectives

1) Develop an understanding of how to use Linux.  
   1) Move around to different directories  
   2) Find files under certain parameters  
   3) Understand networking basics (ports, ips)  
   4) Understand shell scripting basics  
   5) Know the purpose of config files  
2) Feel comfortable knowing how to find information when you don’t know what to do  
   1) Use built-in manuals and ask each other questions when stuck.  
3) Have fun\!

Note: This may be a lot of information, but the goal isn’t to remember everything. The most important thing is to get familiar with using Linux and enhance problem solving skills.

### Import Information

1) In each task you connect to a remote network via SSH and look for the password to the next level. SSH is the Secure Shell Protocol and is used via the command ‘ssh’.  
2) Each stage you will be given a list of potentially useful commands. In Linux, there is a manual for most built-in commands. To access it, use the ‘man’ command.  
   1) To learn about the ‘ls’ command for instance, you run: ‘man ls’  
   2) Alternatively, you can also use the help flag like so: ‘ls \--help’  
      1) Note, there are two dashes before the help flag  
3) As you work through the levels, make sure to write down the commands you used to solve each task as well the password you obtain from each level.  
4) When you complete a task and find the next password, use that to connect via ssh to the next stage.  
5) To connect to a level use the following command:   
   ssh bandit\<LEVEL\>@bandit.labs.overthewire.org \-p 2220  
   1) Replace \<LEVEL\> with the stage you are working on  
   2) We use the ssh command to connect to the   
      bandit.labs.overthewire.org network on port 2220 as user bandit\<LEVEL\>.   
   3) For example, to begin, use the following command:  
      ssh bandit0@bandit.labs.overthewire.org \-p 2220

### Deliverables (Proof of progress)

1) Command used to solve each task  
2) Password for each level
