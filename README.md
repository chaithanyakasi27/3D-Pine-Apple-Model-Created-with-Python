# Pine Apple 3D Model in Maya using Python

![3D PineApple Model](https://github.com/chaithanyakasi27/3D-Pine-Apple-Model-Created-with-Python/blob/main/PineApple.jpg)
You Can see video in the repository.
## Description
This module creates a **Pine Apple** model and adds shaders procedurally using Python in **Autodesk Maya**.

## Features
- Creating Pine Apple shape using a sphere.
- Deforming polygonal primitives by moving vertices, extruding faces, and edges.
- Applying transformations such as move, scale, and rotate on polygonal objects.
- Applying color per vertex to prepare the object for rendering in **Arnold**.
- Using **aiStandardSurface** and **aiRamp** shaders for cones.
- Assigning **ColorPerVertex** to enhance shading effects.
- Parenting nodes and merging the leaves with the Pine Apple structure.

## Process Overview
1. Created a sphere, modified its shape, and extruded the surface to form the Pine Apple body.
2. Added multiple cones to simulate the texture of the Pine Apple.
3. Duplicated and grouped leaves to form branches.
4. Merged the grouped leaves and Pine Apple structure into a single object named **"FRUIT"**.

## Rendering
- Prepared the model for rendering using **Arnold Renderer**.
- Applied appropriate shaders and color attributes for realistic effects.

## Output
The final model is a fully textured **3D Pine Apple**, ready for rendering and further modifications.

## Requirements
- Autodesk Maya
- Python (for scripting in Maya)
- Arnold Renderer

## Usage
To execute the script in Maya:
1. Open Maya.
2. Run the Python script in the **Script Editor**.
3. Adjust transformations as needed.
4. Render using Arnold for the final output.

