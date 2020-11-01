# Bunny-Kill

n the underground world of bunnies, mafia and corruption have taken over. Snowball is on a mission to infiltrate a certain deserted military hanger, supposedly filled with convict bunnies.  

You will be given a matrix of integers, each integer separated by a single space, and each row on a new line, which will represent the current situation in the hangar. Then on the last line of input you will receive indexes - coordinates to several cells in the hangar separated by a single space, in the following format: row1,column1  row2,column2  row3,column3…  
On those cells there are bunnies with bombs. Snowball is smart and knows that the bombs are an easy way to neutralize enemies, especially when they are the enemy’s own bombs. 

Snowball will proceed to eliminate every bunny with a bomb, one by one in the order they were given. When a bunny with a bomb is killed, it explodes and deals damage equal to its own integer value, to all the cells around it (in every direction and in all diagonals). If a bomb bunny is caught in the explosion and killed, that bomb is no longer valid and will not explode. When a bunny is damaged, it reduces its integer value by the damage value. When a bunny’s value reaches 0, it dies. When a bunny explodes, it dies. 

When Snowball is done with all the bomb bunnies, he will proceed to kill any other convict bunny which has remained alive. You must count all the damage Snowball did in the hangar. Note that bomb explosion damage does not count as Snowballs damage, but the killing of bomb bunnies and other bunnies DOES. Snowball’s damage for every bunny is equal to the bunny at that cell’s integer value. 
