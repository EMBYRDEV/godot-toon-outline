# Post-processing outline shader Godot.
![screenshot](https://github.com/EMBYRDEV/godot-toon-outline/assets/20043270/5785e727-dd71-468d-be67-87e71835b4e6)

HOW TO USE:

  1. Create a MeshInstance3D node with a QuadMesh and place it in your scene.
  2. Set it's size to 2x2.
  3. Enable the "Flip Faces" option and add the maximum extra cull margin.
  4. Create a new shader material with this shader.
  5. Assign the material to the MeshInstance3D

LIMITATIONS:

- Does not work well with TAA enabled.

TESTED ENGINE VERSION: 4.0.3
