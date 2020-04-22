# How to load into a T-Pose in Blender.
## Needed:
-	Blender and CM3D2 Converter in working order.
-	A model to load.
-	A minimum understanding of Blender

## How to proceed:
-	Load T Pose Body included in CM3D2 Converter

![Step1](https://i.imgur.com/8LpVOFX.jpg)
-	From there you can switch from sitting-Pose to T-Pose with the right and left arrow keys
-	Make sure your body is in sitting-Pose
-	Go into Pose mode
-	Select the entire armature (A key)
-	Press CTRL-A

![Step2](https://i.imgur.com/VB91Ko3.jpg)
-	Apply Prime Field
-	You can now hide the body mesh (keep the armature though)
-	Import your .model
-	Select your model and while maintaining SHIFT select the T-Body armature
-	Press CTRL-P
![Step3](https://i.imgur.com/P6cB6nE.jpg)
-	Set parent to: Armature deform.
-	Done, now your .model will follow the T-pose armature and change position with LEFT and RIGHT keys.
![Step4](https://i.imgur.com/ST2eZ79.jpg)

## Notes:
-	You might want to parent the .model to its original armature, It won’t break the T-pose function. And you will need that anyway before exporting.
-	If the stance doesn’t change at one point, you’re probably too far right in the animation timeline. Just Press LEFT Key until it changes again.
-	No need to keep the T-Pose armature shown, hide it once done.
-	The original armature won’t move, only the model will, that’s expected.
-	Sometimes the model twist in a weird way, this is due to different bone roll.
-	Tested with blender 2.79b.

