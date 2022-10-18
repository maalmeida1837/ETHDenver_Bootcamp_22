Homeworks
A decentralized version of a game like monopoly
What are the essential pieces of functionality ? 
How would people cheat ?
 How could you prevent them from cheating ? 

This is just a general discussion, there is no need to write any code or do any detailed design.

My answer

functionality :  layers
DSW "dynamic shared world" (everything who changes during the game and everyone sees at same time). Ex the list of gamers and his attributes (cartesian posicion, value of attributes, etc.)
SSW "Static shared world" (the static building blocks)
LOG - all events who change the DSW.
Rules (business) layer. Code acting over events (transactions)
Random : to give a chance 
How would people cheat/ prevent them from cheating ? IRL people cheat when anyone is not watching. Then if we assegure everybody could  audit events, seeing what is happening maybe we prevent cheating.
