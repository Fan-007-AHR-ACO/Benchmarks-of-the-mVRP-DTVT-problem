# Benchmarks-of-the-mVRP-DTVT-problem
Benchmarks of the mVRP-DTVT problem

**The meaning of variables**:<br> 

| Variable | Description |
| :--- | :--- |
| `Depot_x` | Position of the UAV base (x-coordinate) [km]|
| `Depot_y` | Position of the UAV base (y-coordinate) [km]|
| `UAV_num` | Number of UAVs |
| `UAV_type` | Type of the UAVs (0: rotary-wing rescue UAV, 1: fixed-wing supervision UAV) |
| `FUAV_num` | Number of fixed-wing supervision UAVs |
| `RUAV_num` | Number of rotary-wing rescue UAVs |
| `UAV_spd` | Cruising speed of UAVs [km/h]|
| `UAV_abi4st` | Supervision capability of UAVs |
| `UAV_abi4rt` | Rescue capability of UAVs |
| `Task_num` | Number of tasks |
| `Task_type` | Type of the tasks (0: rescue tasks $rt$, 1: supervision tasks $st$) |
| `Task_x` | Position of the tasks (x-coordinate) [km]|
| `Task_y` | Position of the tasks (y-coordinate) [km]|
| `STask_num` | Number of supervision tasks |
| `STask_type` | Type of unidentified vessel in supervision tasks (0: standard boat, 1: speedboat) |
| `STask_nsb` | Number of speedboats |
| `STask_dmd` | Task demands of supervision tasks |
| `STask_velx` | Velocity of unidentified vessel (x-axis component) [knots]|
| `STask_vely` | Velocity of unidentified vessel (y-axis component) [knots]|
| `STask_tr` | Threat radius of the unidentified vessel in supervision tasks [km]|
| `RTask_num` | Number of rescue tasks |
| `RTask_idmd` | Initial demands of rescue tasks |
| `RTask_rrt` | Inherent demand growth rate of rescue tasks |
