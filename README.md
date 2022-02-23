# 6500_clamp_vent_02

This applies the model of 6500_clam_02 to a 3D geometry of a ventilated sugar beet clamp.

The geometry was constructed in Blender, and meshing is done with snappyHexMesh (don't forget to run blockMesh first, and snappyHexMesh with the -overwrite flag).

Beyond the 3D geometry, the major difference is the inlet: there are 12 inlets in the 3D model, with air speed set at 20 m/sec.

Please note that there is no 6500_clamp_vent_01.
