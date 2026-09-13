# Benchmarks-of-the-mVRP-DTVT-problem
Benchmarks of the mVRP-DTVT problem

**The meaning of variables**:<br> 
Depot_x[km]: position of the UAV base (x-coordinate);<br>
Depot_y[km]: position of the UAV base (y-coordinate);<br>
UAV_num: number of UAVs;<br>
UAV_type: type of the UAVs, with 0 for rotary-wing rescue UAV and 1 for fixed-wing supervision UAV;<br>
FUAV_num: number of fixed-wing supervision UAVs;<br>
RUAV_num: number of rotary-wing rescue UAVs;<br>
UAV_spd[km/h]: cruising speed of UAVs;<br>
UAV_abi4st: supervision capability of UAVs;<br>
UAV_abi4rt: rescue capability of UAVs;<br>
Task_num: number of tasks;<br>
Task_type: type of the tasks, with 0 for rescue tasks $rt$ and 1 for supervision tasks $st$;<br>
Task_x[km]: position of the tasks (x-coordinate);<br>
Task_y[km]: position of the tasks (y-coordinate);<br>
STask_num: number of the supervision tasks;<br> 
STask_type: type of unidentified vessel in the supervision tasks, with 0 for standard boat and 1 for speedboat;<br> 
STask_nsb: number of speedboats;<br> 
STask_dmd: task demands of the supervision tasks;<br> 
STask_velx[knots]: velocity of unidentified vessel (x-axis component);<br> 
STask_vely[knots]: velocity of unidentified vessel (y-axis component);<br> 
STask_tr[km]: threat radius of the vessel in the supervision tasks;<br> 
RTask_num: number of rescue tasks;<br>
RTask_idmd: initial demands of the rescue tasks;<br>
RTask_rrt: inherent demand growth rate of the rescue tasks;<br>
### Variable Definitions

| Variable | Description |
| :--- | :--- |
| `Depot_x` | Position of the UAV base (x-coordinate) |
| `Depot_y` | Position of the UAV base (y-coordinate) |
| `UAV_num` | Number of UAVs |
| `UAV_type` | Type of the UAVs (0: rotary-wing rescue UAV, 1: fixed-wing supervision UAV) |
| `FUAV_num` | Number of fixed-wing supervision UAVs |
| `RUAV_num` | Number of rotary-wing rescue UAVs |
| `UAV_spd` | Cruising speed of UAVs |
| `UAV_abi4st` | Supervision capability of UAVs |
| `UAV_abi4rt` | Rescue capability of UAVs |
| `Task_num` | Number of tasks |
| `Task_type` | Type of the tasks (0: rescue tasks $rt$, 1: supervision tasks $st$) |
| `Task_x` | Position of the tasks (x-coordinate) |
| `Task_y` | Position of the tasks (y-coordinate) |
| `STask_num` | Number of supervision tasks |
| `STask_type` | Type of unidentified vessel in supervision tasks (0: standard boat, 1: speedboat) |
| `STask_nsb` | Number of speedboats |
| `STask_dmd` | Task demands of supervision tasks |
| `STask_velx` | Velocity of unidentified vessel (x-axis component) |
| `STask_vely` | Velocity of unidentified vessel (y-axis component) |
| `STask_tr` | Threat radius of the vessel in supervision tasks |
| `RTask_num` | Number of rescue tasks |
| `RTask_idmd` | Initial demands of rescue tasks |
| `RTask_rrt` | Inherent demand growth rate of rescue tasks |
