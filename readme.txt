Co-located crosshole tomographic data sets: Horstwalde (Uni Potsdam), Seismic P-wave tt, seismic S-wave tt, Radar

Cross-borehole tomography, PSO inv in 1D fuzzy space, objectives: rms and Pham, individual inversion
forward solver: FD Eikonal equation

Boreholes x position: 0 m, 5.01 m, 10.96 m, vertical trajectories assumed
Depth below surface range covered: [4.5 16] m

File structure:
grid_cell_centers.txt: x and z coordinates of tomographic grid cell centers in meters in column 1 and column 2, respectively

*_objs.txt: rms error in column 1, Pham misfit in column 2, each line is objective function size for one tomogaphic model, random order, rms error in traveltime units

*_finamod.txt: 253x30 matrices with velocities, one column corresponds to a columnwise representation of one 2D velocity model with grid cell centers according to grid_cell_centers.txt, order of columns corresponds to order of rows in *.objs.txt
 

