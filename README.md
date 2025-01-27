# Train-Transformation-and-Movement-AR-VR
This project involves designing, animating, and integrating a 3D train model using Blender and deploying it in Unity for AR/VR applications. The train model demonstrates smooth transformations such as translation, rotation, and scaling, along with realistic animations (e.g., movement along tracks).

The 3D assets are optimized for AR/VR environments with baked textures, lightweight geometry, and PBR materials for immersive rendering. Once exported (in glTF or FBX format), the model is imported into Unity, where further interactions, animations, and AR/VR-specific setups (e.g., XR Rig for user interaction) are implemented.

This project highlights real-time train movement simulations in AR/VR, showcasing its application in virtual tours, simulations, and gaming environments.


# Steps to Run train.blend in Blender and Unity

# In Blender

	1.Open the File:
		•Launch Blender.
		•Go to File > Open and select train.blend.
  
	2.Check the Scene:
		•Verify the transformations and animations in the 3D Viewport.
		•Play the animation using the Space bar or the Timeline at the bottom.
  
	3.Export the File for Unity:
		•Go to File > Export > glTF 2.0 (.glb/.gltf) (preferred for Unity).
		•Configure export settings:
		•Include: Check “Limit to Selected Objects” if you only want specific parts exported.
		•Animations: Ensure “Include Animations” is enabled.
		•Materials: Select “Export PBR Materials.”
		•Save the file in a Unity-compatible format (e.g., train.glb).

# In Unity

	1.Create a New Unity Project:
		•Open Unity Hub and create a 3D project.
  
	2.Import the glTF/FBX File:
		•Drag the train.glb or train.fbx file into the Unity Assets folder.
  
	3.Set Up the Model:
		•Drag the imported model from Assets to the Scene or Hierarchy.
		•If animations are included:
		•Select the model in the Inspector.
		•Enable Animation components under “Rig” or “Animation.”
  
	4.Adjust Materials:
		•Unity may require you to reassign materials. Use Unity’s Standard Shader for PBR materials.
  
	5.Test the Scene:
		•Press the Play button in Unity to view and test the model’s transformations and animations.
  
	6.Optimize for AR/VR (if applicable):
		•Add an XR Rig from Unity’s XR Interaction Toolkit for AR/VR interaction.
		•Assign the train model as part of the interactable or dynamic objects.
