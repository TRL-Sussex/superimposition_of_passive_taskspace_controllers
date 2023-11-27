# Stack of Task Space Controllers Framework

This framework implements the *Superimposition of Task Space Controllers* concept introduced in:

> Tiseo, C., Merkt, W., Wolfslag, W. et al. Safe and compliant control of redundant robots using superimposition of passive task-space controllers. Nonlinear Dyn (2023). [doi:10.1007/s11071-023-09045-x](https://doi.org/10.1007/s11071-023-09045-x)

It is split in several packages:

1. `stack_of_task_space_controllers_core` which implements the core library for the stack of controllers and the passive Fractal Impedance Controller described in the above paper.
2. `stack_of_task_space_controllers_ros_control` which provides a ROS-Control controller.
3. `stack_of_task_space_controllers_kuka_lwr` which includes a Gazebo simulation using the ROS-Control controller as well as a node communicating with the IPAB-SLMC `lwr_driver` for hardware experiments.
<!-- 4. `stack_of_task_space_controllers_rocoma` which wraps the framework for use with the RoCo control framework. -->
