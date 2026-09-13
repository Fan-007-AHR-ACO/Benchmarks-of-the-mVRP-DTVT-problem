# Benchmarks-of-the-mVRP-DTVT-problem
Benchmarks of the mVRP-DTVT problem

**The meaning of variables**:<br> 
Depot_x: position of the UAV base (x-coordinate);<br>
Depot_y: position of the UAV base (y-coordinate);<br>
UAV_num: number of the UAVs;<br>
UAV_type: type of the UAVs, with 0 for rotary-wing rescue UAV and 1 for fixed-wing supervision UAV;<br>
FUAV_num: number of fixed-wing supervision UAVs;<br>
RUAV_num: number of rotary-wing rescue UAVs;<br>
UAV_spd: cruising speed of UAVs;<br>
UAV_abi4st: supervision capability of UAVs;<br>
UAV_abi4rt: rescue capability of UAVs;<br>
Task_num: number of tasks;<br>
Task_type: type of the tasks, with 0 for rescue tasks $rt$ and 1 for supervision tasks $st$;<br>
Task_x: position of the tasks (x-coordinate);<br>
Task_y: position of the tasks (y-coordinate);<br>
STask_num: number of the supervision tasks;<br> 
STask_type: type of unidentified vessel in the supervision tasks, with 0 for standard boat and 1 for speedboat;<br> 
STask_nsb: number of speedboats;<br> 
STask_dmd: task demands of the supervision tasks;<br> 
STask_velx: velocity of unidentified vessel (x-axis component);<br> 
STask_vely: velocity of unidentified vessel (y-axis component);<br> 
STask_tr: threat radius of the vessel in the supervision tasks;<br> 
RTask_num: number of rescue tasks;<br>
RTask_idmd: initial demands of the rescue tasks;<br>
RTask_rrt: inherent demand growth rate of the rescue tasks;<br>
