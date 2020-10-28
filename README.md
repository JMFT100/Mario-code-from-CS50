# Mario-code-from-CS50
For the record, this is just to see where I'm actually having a bug. The bug is: 
Error

Map.lua:141: attempt to index local 'tile' (a number value)


Traceback

Map.lua:141: in function 'collides'
Player.lua:117: in function <Player.lua:105>
Player.lua:144: in function 'update'
Map.lua:155: in function 'update'
main.lua:45: in function 'update'
[C]: in function 'xpcall'

This happens whenever my character jumps.

It also doesn't actually detect left and right collision, as well as collision below "Mario" or the little alien in the 'walking' state.
I would really appreciate it if you could help me solve my problem!
Cheers!
