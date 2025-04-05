I put the two springs (colorRect nodes) as the children of a control node which is the child of the platform itself. I did this so I could have control of the position of the anchors which are crucial for the calculation of the distance var. I put the anchors in the middle and the colorRect itself at the edges of the platform.

The two @export variables I added ( on_platform_pos and norm_pos) help me control the y position of the springs, when the spring_destination was set to 0 the y position was also set to 0 so this is what I came up with, might not be the best way but it works great.

I wanted the platform to sink whenever the player is on it so I made sure the on_platform_pos var will be smaller than the norm_pos var.

I used Godot 4.4 but I'm sure it would work with any that is 4+.
 
If something I said wasn't clear you can of course ask, and I'll do my best to help (I'm new to this too :)


Thank you Dreamjob Gamedev!
