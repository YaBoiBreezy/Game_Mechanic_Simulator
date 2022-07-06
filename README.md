# Game_Mechanic_Simulator
Spend some coins to get an amulet, which gives you 3 attributes of random values 1-10  (health, damage, speed). 
Possible to have one better/equal another in all 3 attributes, in which case weaker one is obsolete, but also possible to have many that are good (1,1,10) vs (10,10,2), So how many can you have total, if you remove any obsolete ones? 1000 possible amulets, check all with recursion

Seems like the problem was a "Maximum independent set" problem, which is NP. I was able to simulate up to level 6, (level meaning each value is between 1 and 6)m found a pattern and in conclusion the answer for level 10 is probably 75 possible amulets.
