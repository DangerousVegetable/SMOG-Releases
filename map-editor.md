# Map Editor
Use this app to create maps for SMOG.

## Key Bindings

### Camera Controls
- **W** / **A** / **S** / **D** + **SHIFT**: Move the camera
- **MOUSE SCROLL**: Adjust field of view (FOV)

### Layer Controls
- **Drag and Drop** an image: Create a new layer
- **LEFT ALT** + **BACKSPACE**: Make the layer non-solid
- **LEFT ALT** + **M** / **T** / **S** / **D** / **E**: Adjust layer settings (use console to input parameters)
- **ARROW LEFT** / **ARROW RIGHT**: Switch between layers
- **ARROW DOWN**: Preview the current layer
- **LEFT ALT**: Bake the layer (update particles based on new settings)
- **DELETE**: Delete the layer

### Texture Controls
- **Drag and Drop** an image: Add a new texture while the **Add texture** button is enabled
- **LEFT MOUSE CLICK** on a texture: Remove the texture

### Spawn Controls
- **MOUSE CURSOR** +  **1** / **2** / **3** / **4**: Place a new spawn for the selected team
- **RIGHT MOUSE CLICK** on a spawn: Remove the selected spawn

### Map Controls
- **Drag and Drop** a *.smoge* file: Load map from the file
- **ENTER**: Bake the map (update random connections between particles in solid layers)
- Hold **SPACE**: Apply physics
- **TAB**: Restart the simulation without updating the map
- **LEFT CONTROL** + **S**: Save the map
