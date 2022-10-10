# Known Issues
### General
- Too low resolutions are unusable (below 1024x768)
- (Open GL \\ Vulkan) Materials might look different under same light level when compared to DX11/12
- (Vulkan) UI has weird lines around the edges
- Launching the build with specific rendering APIs that are not D3D11/12 will cause a crash
- DPI scaling isn't present, text might result small on low resolution

### UI
- Bumping a panel to the bottom will move it to the center instead of constraining it
- Dropdowns with entries that are too long will have clipping text
- Draggable panels will still bump over their previous docked/expanded position
- (Studio and Maker) "Return" button on settings panel doesn't reset it's size, opening and closing settings panel will make the size of the return text larger every time

### Settings
- Most settings are not implemented and will not do anything
- Master Volume doesn't work, you can set a different value on BGM slider but the master slider will not affect the overall volume

### Studio
- Upon selection of an object, if the gizmo appears on the cursor you are able to move the camera while moving the object
- An object being unselected does not clear the "Move" panels previous contents
- Created objects have "(Clone)" in their name
- Newly placed lights are not illuminating

### Gizmo
- Rotation with cursor can be unintuitive
- Rotation Gizmo has unaligned Green/Blue arcs

### Character Maker
- Sliders for eye and mouth opening are in reverse
- Cards save/load options are not implemented
- Accessories are not implemented
- Camera target does not get turned off for card screenshots
- Loaded cards character profile is not applied to the UI
- Upon unselecting an item, the miscellaneous customizer may not clear itself
- Saved and loaded cards do not include any modified materials properties
- Pick Image appears to accept only PNG, but renaming a jpg into a png would make it load nonetheless
- Loading an image that can't be loaded will make the bg texture disappear, showing the default skybox
- Character profile image does save chara info but they won't get restored when loading it back
- Saving a Mouth Expression and then loading it will not restore the correct mouth opening amount
-  Inputting text will still move character in the view when WASD keys are being pressed
- Saving an eye expression will not make it show up in the dropdown
- There is clipping of clothing and skin all over the place
- Some holes can be observed trough the skin mesh
