## Depth Sorting Method
- Performs the following basic functions: 
1. Surfaces are sorted in  order of  decreasing depth. 
2.  Surfaces are scan  converted  in  order, starting with  the surface  of greatest 
depth.

- Assuming we are wewing along the-z direction, surfaces are ordered on the first  pass according to the smallest z  value o n   each surface.

# Illumination Models
- **Illumination models** are used to calculate the intensity of a light reflected at a given point on the surface of an object.
- **Surface rendering algorithm** uses intensity calculation form an illumination model to determine light intensity for all projected pixels for various surfaces in the scene.

# Computer Animation
- Animation is the rapid display of a sequences of images of 2D or 3D artwork to create an illusion of movement.

## Design of Animation Sequences
- An animation sequence is designed in the following steps

1. **Storyboard Layout:** 
    - Outline of an action
    - Contains the sequences of motion or action to be performed
2. **Object Description:**
    - Shapes in motion
    - A great degree of realism is added by shading
3. **Key Frame:**
    - Key Frame is the detail drawing of a scene at a specific moment.
    - Each object is position at a particular keyframe.
4. **Generation in between frames:**
    - incorporation of many frames in between any two key frames for smooth animation
5. **Line Testing:**
    - To check the quality of movements produced
    - It refers to checking of keyframes to check motion, timing, and flow before finalizing the animation.
6. **Recording:**
    - compiling or merging all individual frames into a continuous video or animation sequence.

**Raster Animation**
-  Transformations carried out by simply moving pixel values from one location to other

## Types of Animation
### 1. Traditional Animation
- Frames are drawn on paper or clicked and rotated
- It has the following types:
1. **Full Animation:**
- to produce high quality traditionall animated films using detailed drawings and plausible movements.
2. **Limited Animation:**
- use of less detailed or style drawings and methods of movement
3. **Rotoscoping:**
- animators trace live action movements frame by frame.  

### 2. Stop Motion Animation
-  Here objects are explicitly moved frame by frame to create an illusion of movement
- It's types are Clay Animation(uses clay),Graphic Animation(uses non drawn flat graphic materials)

### 3. Computer Animation
1. **2D Animation:**
- Analog computer animation,flash animation,power point animation
2. **3D Animation:**
- **Rigging:** It is a method of giving a skeleton to a 3D odject to customise it's movement.

## Keyframe Animation vs Procedural Animation
|Keyframe Animation|Procedural Animation|
|-|-|
|It refers to transition between keyframes,by defining starting and end point|Used to automatically generate animations in real time using physics concepts or other algorithms|
|Used for general film making or video editing purposes|Used for simulating particle system(smoke,fire,water,cloth,etc.) in video games|

## Methods of Controlling Animation
1. **Full Explicit Control**
- Animator provides details of everything occuring in an animation,like scaling,translation,rotation and interpolation details.
2. **Procedural Control**
- It defines the communation between various objects to determine their properties.
- Eg,balls cannot pass through walls
3. **Constraint Based Systems**
- to provide motion where constraints are specified
4. **Tracking Live Action**
- tracking the events occuring in an animation
5. **Kinematics and Dynamics**

## Morphing
- Transformation of object shapes to one form to another is called morphing.
- Techniques used in Morphing are of 2 types:
1. **Mesh Based Methods:** Features of an image is specified by a non uniform mesh.
2. **Feature Based Methods:** Features of an image is specified by set of points or line segments.

- The following Morphing techniques are used:
1. Interpolating color of each pixel from one value to other value.
2. Feature interpolation by combining geometric transformations along with color interpolation.
