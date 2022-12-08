# RBE 501 Term Project

In this work, an analysis is performed to verify
whether the Safe Flight Corridors (SFC) trajectory planner
combined with the Jump Point Search (JPS) path planning
algorithm is more robust and efficient than the commonly used
Rapidly Exploring Random Tree, henceforth RRT, as well as the
A* path planning algorithms. This analysis was conducted using
MATLAB where the algorithms were executed on identical 2D
occupancy maps where efficiency was measured in terms of time
and robustness was measured by the ability for the algorithm to
direct a simulated Unmanned Vehicle (UV) to reach a specified
end point in the map. The results of the study show that SFC
requires a larger elapsed time in comparison to RRT and A* to
find a path, but the path length and nodes visited are about the
same for both maps used. SFC is shown to be as robust as A*
where RRT has the worst robustness in comparison

Link to IEEE format report: ([PDF](https://github.com/tarizzo/pathPlanning/blob/main/report.pdf))

MATLAB Toolboxes Utilized:

1) Parallel Computing Toolbox
2) Automated Driving Toolbox
3) Symbolic Math Toolbox
4) Mapping Toolbox
