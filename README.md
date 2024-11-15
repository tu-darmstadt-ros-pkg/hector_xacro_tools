# Hector XACRO Tools - ROS2 Jazzy

This packages contains various XACRO macros. A list is given below.

### inertia_tensors.urdf.xacro

- inertial_cuboid [mass, x_length, y_length, z_length]
- inertial_cuboid_with_pose [mass, x_length, y_length, z_length, *origin]
- inertial_sphere [mass, diameter]
- inertial_sphere_with_pose [mass, diameter, *origin]

### joint_macros.urdf.xacro

- joint_standard_transmission [name]
- joint_position_transmission [name]
- joint_velocity_transmission [name]

### sensor_macros.urdf.xacro

- add_optical_frame [name]

