# in-class-activities
## Devlogs
### W1
Write your W1 activity Devlog here.

### W2
1) The r, g, and b variables floats instead of ints, bools, or strings because they are decimal number that are mixed together to get specific shades of colors.
2) The _bounce variable an int instead of a float, bool, or string because it is the number of times that the ball bounces. Therefore, it need to be a whole number.
3) The error was the float missing the letter "f", making unity cannot convert it into the float type. This helps me remeber that float type always need the letter "f".

### W3
#### Activity 1:
1) The parameter should be a int and a bool. The return type should be string.
2) The parameter should be a float. The return type should be void.
3) The parameter should be float. The return type should be bool.

#### Activity 2: 
The class is like a gingerbrave cutter and the component is the gingerbrave. In that case, the member variables are the toppings of the gingerbrave, and the methods are what the gingerbrave could do, such us run, walk or be eaten. 

#### Activity 3:
1) The ball get extremely bright because everytime it bounces, cthe color get brighter, and its speed constantly multipled so the color get isanely bright.

### W4
Table #8, Partner: Yingjie Wang
1) I added the rigidbody for the cat and the ball because those two need to physical interact with each other. Meanwhile, the goal does not need one because it is only a zone for a ball to go in to trigger the goal. 
2) At first, the cat keep falling and rolling around because I did not constrain the axises. 

### W5-6
1) The script needs a Transform varibel "_target" to store the GameObject that the deer will walk toward. I will use "[SerializedField] so I can choose the target in the Unity Inspector. A NavMeshAgent variable called _agent to control the deer's movement.
2) I will use Unity's Start(), GetComponent<NavMeshAgent>(), SetDestination(). 
3) The Start() method should get the Deer GameObject's NavMeshAgent component using GetComponent<NavMeshAgent>(). It should then use SetDestination() to tell the deer to walk toward the target GameObject (the red mushroom) when the game starts.

## Open-Source Assets
### W1
- Animals: https://assetstore.unity.com/packages/3d/characters/animals/animals-free-animated-low-poly-3d-models-260727 
- Low-poly environment: https://assetstore.unity.com/packages/3d/environments/landscapes/low-poly-simple-nature-pack-162153 