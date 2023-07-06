# HatFBX
The Blender FBX import/export plugin modified to support the FBX files from A Hat in Time.

The original code has been modified in order to account for the bones' RootNode tag when importing and exporting the models. This means the root bones will no longer be treated as armatures on import, and the models will be exported without adding an extra root bone.

Supported Blender versions:

io_scene_ahitfbx_279 - Blender 2.79, previous versions untested.<br>
io_scene_ahitfbx_290 - Blender 2.80 - Blender 3.2.0.<br>
io_scene_ahitfbx_320 - Blender 3.2.0 - Blender 3.6.0.<br>
io_scene_ahitfbx_360 - Blender 3.6.0 - Present.
