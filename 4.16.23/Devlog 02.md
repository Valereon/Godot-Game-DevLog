

//The Guns and their frustations

So i started today with trying to make the most extensible gun script i could so that i could just edit a few Varibles and then have a new gun with spread no spread stuff like this 

![AltText](GUN SCRIPT SS)

After i spent most of my free time making that i decided i wanted to make a scope in feature where you could scope in to the iron sights/sight and see better than just a crosshair and a gun to the side perosnally i love scoping in makes me feel more badass

![AltText](SCOPED IN SS)

i also spent a shit ton of time trying to figure out how to make the bullets shoot in the direction you are facing which was a task all on its own you know gotta find the Z rotation and basis to shoot forward i dont really understand it it just works

"instanced.set_linear_velocity(instanced.get_global_transform().basis.y * 50)"

is the line that really got me messed up it took me some help and a while till i figured it out but nonetheless 

i also made a shotgun which was a whole nother thing in of itself i had to use some [stack overflow](https://stackoverflow.com/questions/5837572/generate-a-random-point-within-a-circle-uniformly/5838055#5838055) and googling to figure out how to make a random point on the unit circle godot dosent really have a method for that so i made this

![AltText](PointOnCirlce)


i also had some trouble with controlling the spread on the cirlce, the example gave it with radius = 1. i had to do some *experimenting*

![AltText](ShotgunHell gif)


overall i had a fun time today allbeit frustrating at times i cant really say that i dont love it

