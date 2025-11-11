# in-class-activities
## Devlogs
### W1
//hello world!

### W2
Create future Devlog sub-headers with the three # symbols, then write your Devlogs below them.

1. The values R, G, and B, usually evaluate to decimal values, making floats the most legible option for the computer.
2. _bounce is counting the amount of times the ball touches another surface, making it a whole number integer each time.
3. The presence of the semicolon indicates a line end which is critical for the computer to interpret individual lines of code (syntax error). 

### W3
Table 18
Void setLightDimness(float x){
		Float lightLevel = 100 * x;
}

1. The relationship between classes and components is like a russian nesting doll. Inside the game is the scene, inside the scene is the components, inside the components is the scripts, and finally, inside the scripts is the classes. Creating and altering classes within a script that is assigned to a component creates new attributes within the inspector (after serializing) that can be altered affecting gameplay. Such attributes include object velocity and color as seen in this activity. Understanding this nesting doll relationship allows a programmer to alter gameplay efficiently.

2. There is no if statement preventing the brightness attribute from becoming too high, so as the ball increases in speed, it bounces more often, leading to increasingly consistent increases in brightness.

### W4
17. Line 17 is declaring a boolean variable and assigning it to true as an initial value
28. Line 28 is getting the input of the player whenever they hit the space button and checking if the player is grounded before executing a jump
32. Line 32 reassigns the value of _isGrounded to false as the payer is mid-jump, preventing them from double jumping.

1. We added colliders to all three major game objects and we only checked is trigger on for the goal
2. I was having the issue of being unable to detect when a goal was scored. It turns out my issue was as simple as not having an additional "=" in the if statement which was preventing the program from creating a proper comparison using the game tag.

### W5
How does GetComponent() work?
GetComponent() is a method integrated within Unity's library which can be called in order to alter a GameObject's components. Inside <> symbols, the programmer specifies what component is being interferred with.
How does Vector3 work?
Vector3 spevifically targets 3d movement whereas Vector2 targets 2d movement

### W6

https://docs.google.com/document/d/1h_Y8rCF_le6ZcYOcLBTVEpvMZH8OPQ4Jag5PKy7dbnk/edit?tab=t.0

In Class Activity
	- Must serialize field
	- Member variables: speed, determine if bats chase (distance)
	- Will need both start() update()
	- The methods need to determine whether or not the bats should chase the player 
	- They also need to actually move the bats

### W7
The code in step 2 wasn't working properly because the muskrat was not moving relative to its rotated orientation. By using transform.translate instead, the direction in which the gameobject translates is adjusted upon rotation.

## Open-Source Assets
### W1
- Animals: https://assetstore.unity.com/packages/3d/characters/animals/animals-free-animated-low-poly-3d-models-260727 
- Low-poly environment: https://assetstore.unity.com/packages/3d/environments/landscapes/low-poly-simple-nature-pack-162153 
