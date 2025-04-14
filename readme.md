## Blender Visualize notes with Geometry nodes

This Blender file contains a geometry nodes group for generating visualization of piano notes over time.

### How It Works
In the object "SYNTEZIA", there's an implemented geometry nodes group that creates visualization from data in the "File" object. 

The "File" object contains vertices with data on each vertex about:
- Pitch
- Note start
- Note end
- Velocity

This data is loaded into the geometry nodes system and transformed into notes with various visual effects.

## Requirements
- Blender 3.4 or later

![Notes Visualization](notes.png)

