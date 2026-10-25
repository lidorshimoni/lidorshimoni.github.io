# SO-101 hero model data

Generated from the official SO-101 follower-arm CAD meshes and URDF
(`so101_new_calib.urdf`) in https://github.com/TheRobotStudio/SO-ARM100
(`Simulation/SO101`, Apache License 2.0, (c) TheRobotStudio).

- `so101.json`: joint tree (origins, axes, limits) copied from the URDF.
- `<link>.pos` / `.idx`: welded triangle mesh per URDF link, Int16-quantised.
- `<link>.bin`: crease edges (30 deg) per link, Int16-quantised.

Units are metres in the URDF frame (Z up). No geometry was redrawn or approximated.
