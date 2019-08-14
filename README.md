# PyChart
PyChart is a tool to map from netcdf output

# Christopher Bull notes
This is a fork from PMathiot:
    https://github.com/pmathiot/PyChart

# Example
    python plot_maps.py --dir /home/chris/VBoxSHARED/ --mapf nemo_bc337o_1y__19761201-19771201-19841201-19851201_grid_T.nc --mapv sossheig --cblvl -2 2 0.4 --mesh  /home/chris/VBoxSHARED/mesh_mask_eORCA025-GO7.nc -p ant
    python plot_maps.py --dir /nerc/n02/shared/chbull/NEMO_JRAspinup4DAVECHK/u-bl504/onm.nc.file/g07_means/ --mapf 2018_2026_grid-T.nc  --mapv sossheig --cblvl -2 2 0.4 --mesh  /nerc/n02/n02/chbull/nemo/bld_configs/input_WED12_mathiot_eORCA025-GO7/mesh_mask_eORCA025-GO7.nc  -p ant -o /nerc/n02/shared/chbull/NEMO_JRAspinup4DAVECHK/u-bl504/onm.nc.file/g07_means/sossheig_2018_2026_grid-T
