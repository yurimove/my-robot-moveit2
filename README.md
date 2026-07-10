# MoveIt 2 Crash Course

## Current Progress

- ROS 2 Jazzy
- Robot description completed
- Collision geometry added
- MoveIt Setup Assistant completed
- Motion planning works in RViz

## Current Blocker

Planning is successful, but trajectory execution fails.

Observed behavior:
- Plan succeeds.
- Execute aborts.
- arm_controller does not expose follow_joint_trajectory action.
- Controller manager appears unable to fully initialize the arm controller.

Any help debugging the ros2_control configuration would be appreciated.
