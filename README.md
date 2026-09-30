# GAME_PROGRAM-EX--1
EXP:1 Implementing various effects in a material such as emissive, roughness and metallic properties in Unreal Engine

## Aim

To implement and demonstrate various material effects in Unreal Engine, including emissive, roughness, and metallic properties, using the Material Editor.

# Procedure

***1.Create a New Material:***

Open Unreal Engine.
In the Content Browser, right-click and select Material.
Name it M_EffectsDemo.

***2.Apply Base Color:***

Open the material.
Add a Vector Parameter or Constant3Vector node and connect it to the Base Color input.

***3.Add Emissive Effect:***

Add a Multiply node.
Connect a Constant3Vector (for emissive color) and a Scalar Parameter (for intensity).
Connect the result to the Emissive Color input.

***4.Control Roughness:***

Add a Scalar Parameter node and connect it to the Roughness input.
Lower values = shinier surface, higher values = rougher surface.

***5.Control Metallic Property:***

Add a Scalar Parameter node and connect it to the Metallic input.
0 = non-metal, 1 = fully metallic.

***6.Save and Apply Material:***

Save the material.
Apply it to any mesh in the scene (like a sphere or cube) to preview the results.
Output

# Output
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/74dd91c6-de7f-4c08-8f8c-e29b2f37cac8" />
<img width="1192" height="791" alt="image" src="https://github.com/user-attachments/assets/63eb13d7-6aeb-4a5f-8906-ea6c2fab1dc2" />

## Result
Successfully implemented a material in Unreal Engine showcasing:
- Emissive glow using emissive color and intensity.
- Variable surface roughness to simulate different textures.
- Metallic appearance adjustment to reflect light like real-world metals.

This setup enables dynamic, realistic materials suitable for use in environments, characters, and VFX in Unreal Engine projects.
