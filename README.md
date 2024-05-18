# Movement-of-Robot-Joints
## Aim:  
To move and drive the joints of the robot using python API.

## Equipment’s required:

Visual Components Premium 4.3

## Procedure:

1. 	In the eCatalog panel, Collections view, browse to Models by Type>Robots>Visual Components and then add a Generic Articulated Robot to the 3D world.
2. 	Click the Modeling tab, and then add a Python Script behaviour. The script editor will open automatically when you add the behaviour.
3. 	In the script editor, add the code and then compile the code.

## Program
```
Program Developed By: RITHISH P
Register Number: 212223230173
from vcScript import *
from vcHelpers.Robot2 import *
def OnRun():
  pos=[[1,30],[2,40],[3,90]]
  robot = getRobot()
  robot.driveJoints(0,0,0,0,0,0)
  delay(5)
  for i in pos:
    robot.Controller.moveJoint(i[0],i[1])
    delay(5)

```
## Output
### 1. Generic Articulated Robot
![Screenshot 2024-05-19 021249](https://github.com/RITHISHlearn/Movement-of-Robot-Joints/assets/145446645/c465e1fb-6c0a-431a-a352-c641a0be383d)

</br>
</br>
</br>
</br>

### 2. robot.driveJoints(0,0,0,0,0,0)
![Screenshot 2024-05-19 021304](https://github.com/RITHISHlearn/Movement-of-Robot-Joints/assets/145446645/e670a08f-306d-44d9-aa05-0e679bec4b8b)
</br>
</br>
</br>
</br>

### 3. Movement of Joint1
![Screenshot 2024-05-19 021315](https://github.com/RITHISHlearn/Movement-of-Robot-Joints/assets/145446645/93def00b-4e24-4279-9516-44eb74d86d3f)

</br>
</br>
</br>
</br>

### 4. Movement of Joint2
![Screenshot 2024-05-19 021329](https://github.com/RITHISHlearn/Movement-of-Robot-Joints/assets/145446645/47d99439-1919-4259-893d-f7cb35b7cedf)

</br>
</br>
</br>
</br>

### 5. Movement of Joint3
![Screenshot 2024-05-19 021343](https://github.com/RITHISHlearn/Movement-of-Robot-Joints/assets/145446645/ed9c4153-e83c-425c-9500-5b82034c9588)

</br>
</br>
</br>
</br>

## Result 
Thus the different robots joints are moved with the help of python list.


