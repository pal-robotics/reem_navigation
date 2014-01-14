reem_navigation
===============

Configuration and launch files for the navigation stack on REEM

There are two main launch files in the `reem_2dnav` package:

 * `navigation.launch`
 * `mapping.launch`

Both will use `move_base` for planning, but the first one will use `amcl`
to localize itself on a pre-recorded map, and the second will use `gmapping` to
perform SLAM.
