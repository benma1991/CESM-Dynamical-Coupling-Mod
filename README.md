# CESM-Dynamical-Coupling-Mod
These contain CESM new dynamical coupling scheme code:
1. Define and record new wind vectors on ATM-AD grid and wind tendency on ATM-AA grid (physics_types.F90; dp_coupling.F90; physpkg.F90).
2. Pass the added variables to CPL (camsrfexch.F90; cam_cpl_indices.F90; atm_comp_mct.F90).
3. Output new variables to history nc file (cam_diagnostics.F90).
4. Define and initialize 2 new interpolation operators (ccsm_comp_mod.F90; config_definition.xml; config_grid.xml; build_namelist; namelist_defaults_drv; namelist_definition_drv.xml).
5. Add wind vectors and wind physical dentency in CPL (ccsm_comp_mod.F90; m_AttrVect.F90; ccsm_comp_mod.F90).
