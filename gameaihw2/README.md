Game Ai HW 2 Collision

This homework assginment ask for a collision check and path follow behavior. My project behaves two different group of objects, each follows a line of objects and try to avoid collision. The program consists of those basci functions: conecheck, collisionprediction, pathfollow, evasion.

Conecheck taks two objects and a coneangle. It checks if one object is in a certain angle of shade area of another object. It returns true if the object is in the area, and false if the obejct is not.

CollisionPrediction taks one Character and a set of objects. It checks the time to reach cloest distance between Character and each object in the set and returns the cloest object. Then apply evasion of Character from this object.

Pathfollow and evasion are two algorithms inherited from hw1. Pathfollow takes in a Character a set of dots, considering that is a path. It then checks the cloest dot to the Character and apply seek to the dot.

Evasion takes two objects, a Character and a Target. It predicts the future point of target and apply flee to Character from that point. 

The program turns out to have one object in each group going ahead, and the rest just turn into a group and go forward together. 

And an online version can be found here: IMCJuryd.github.io/gameaihw2


Yifan Xu
