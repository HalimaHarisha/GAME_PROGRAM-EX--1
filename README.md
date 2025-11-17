# GAME_PROGRAM-EX--1
# IMPLEMENTING VARIOUS EFFECTS IN A MATERIAL SUCH AS EMISSIVE, ROUGHNESS AND METALLIC PROPERTIES IN UNREAL ENGINE
# AIM
To implement and demonstrate various material effects in Unreal Engine, including emissive, roughness, and metallic properties, using the Material Editor.
# PROCEDURE


**1. Create a New Material:**
  ● Open Unreal Engine.
  ● In the Content Browser, right-click and select **Material**.
  ● Name it **M_EffectsDemo**.

**2. Apply Base Color:**
  ● Open the material.
  ● Add a **Vector Parameter** or **Constant3Vector** node and connect it to the **Base Color** input.

**3. Add Emissive Effect:**
  ● Add a **Multiply** node.
  ● Connect a **Constant3Vector** (for emissive color) and a **Scalar Parameter** (for intensity).
  ● Connect the result to the **Emissive Color** input.

**4. Control Roughness:**
  ● Add a **Scalar Parameter** node and connect it to the **Roughness** input.
  ● Lower values = shinier surface, higher values = rougher surface.

**5. Control Metallic Property:**
  ● Add a **Scalar Parameter** node and connect it to the **Metallic** input.
  ● 0 = non-metal, 1 = fully metallic.

**6. Save and Apply Material:**
  ● Save the material.
  ● Apply it to any mesh in the scene (like a sphere or cube) to preview the results.
# OUTPUT 

<img width="498" height="472" alt="image" src="https://github.com/user-attachments/assets/5c9901fc-3375-43c8-8a75-f6856eda23e5" />

<img width="624" height="601" alt="image" src="https://github.com/user-attachments/assets/d15008df-df2c-40b6-8b30-758aa4d613ad" />

# RESULT
Successfully implemented a material in Unreal Engine showcasing:

● Emissive glow using emissive color and intensity.
● Variable surface roughness to simulate different textures.
● Metallic appearance adjustment to reflect light like real-world metals.

This setup enables dynamic, realistic materials suitable for use in environments, characters, and VFX in Unreal Engine projects.
