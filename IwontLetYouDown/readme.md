# Challenge

OK Go take a look at this IP:
Connect here: http://155.138.162.158 # USING ANY OTHER TOOL OTHER THAN NMAP WILL DISQUALIFY YOU. DON'T USE BURPSUITE, DON'T USE DIRBUSTER.

# solution

- started with simple nmap Scan showed that there is port open : 8888

```bash
└─$ nmap -sT 155.138.162.158 -vv                                                                                                                              
Starting Nmap 7.93 ( https://nmap.org ) at 2023-10-05 11:49 EDT
Initiating Ping Scan at 11:49
Scanning 155.138.162.158 [2 ports]
Completed Ping Scan at 11:49, 0.11s elapsed (1 total hosts)
Initiating Parallel DNS resolution of 1 host. at 11:49
Completed Parallel DNS resolution of 1 host. at 11:49, 0.03s elapsed
Initiating Connect Scan at 11:49
Scanning 155.138.162.158.vultrusercontent.com (155.138.162.158) [1000 ports]
Discovered open port 22/tcp on 155.138.162.158
Discovered open port 8888/tcp on 155.138.162.158
```

- Connecting to that port using nc would give u the flag

```bash
└─$ nc 155.138.162.158 8888
We're no strangers to love
You know the rules and so do I (do I)
A full commitment's what I'm thinking of
You wouldn't get this from any other guy
I just wanna tell you how I'm feeling
Gotta make you understand
Never gonna give you up
Never gonna let you down
Never gonna run around and desert you
Never gonna make you cry
Never gonna say goodbye
Never gonna tell a lie and hurt you
We've known each other for so long
Your heart's been aching, but you're too shy to say it (say it)
Inside, we both know what's been going on (going on)
We know the game and we're gonna play it
And if you ask me how I'm feeling
Don't tell me you're too blind to see
Never gonna give you up
Never gonna let you down
Never gonna run around and desert you
Never gonna make you cry
Never gonna say goodbye
Never gonna tell a lie and hurt you
Never gonna give you up
Never gonna let you down
Never gonna run around and desert you
Never gonna make you cry
Never gonna say goodbye
Never gonna tell a lie and hurt you
We've known each other for so long
Your heart's been aching, but you're too shy to say it (to say it)
Inside, we both know what's been going on (going on)
We know the game and we're gonna play it
I just wanna tell you how I'm feeling
Gotta make you understand
Never gonna give you up
Never gonna let you down
Never gonna run around and desert you
Never gonna make you cry
Never gonna say goodbye
Never gonna tell a lie and hurt you
Never gonna give you up
Never gonna let you down
Never gonna run around and desert you
Never gonna make you cry
Never gonna say goodbye
Never gonna tell a lie and hurt you
Never gonna give you up
Never gonna let you down
Never gonna run around and desert you
Never gonna make you cry
Never gonna say goodbye
Never gonna tell a lie and hurt you
flag{93671c2c38ee872508770361ace37b02}

```
