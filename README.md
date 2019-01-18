# MathemticaForDFTnSPM
_Mathematica notebooks for processing, plotting and visualizition of outputs (and sometimes also inputs) of DFT codes (VASP, FHI-AIMS, Fireball, GPAW and maybe others) and results of SPM (simulations)_

__atomic_prop.dat__ : file with colours and radii for elements

__BAS_to_XYZ_to_IN_to_CAR.nb__ : Notebook for fast switching of geometry from xyz, bas, geometry.in, CONTCAR & POSCAR files. Possibility to change atomic order, according to element and/or _x_ and/or _y_ and/or _z_ coordinates.

__DOS_plot_and_view.nb__ : The notebook can read PDOS from different DFT codes (Fireball, VASP, GPAW, FHI-AIMS) and plot them in the same way. In the second part (VIEW) there is possibility to visualize the amount of PDOS per atom in 3D balls & sticks model.

__DOS_plot_and_view_spinpol.nb__ : The notebook can read spin-polarized PDOS from different DFT codes (VASP and FHI - AIMS) and plot them in the same way. For VASP also polarization in case of spin-orbit coupling can be plotted. In the second part (VIEW) there is possibility to visualize the amount of PDOS per atom in 3 D balls & sticks model.

__energy_path_plot.nb__ : Plotting of energy diagrams and barriers for Nudged Elastic Band calculations.

__Fast_WSxM_2D_view.nb__ : Notebook for 2D visualization of SPM data stored in WSxM format.

__Fast_XYZ_view.nb__ : Notebook for fast balls and sticks plotting of geometry from *.xyz file.

__geom_view_and_edit.nb__ : Notebook for view (balls and sticks) and possible edits of geometry from xyz, bas, geometry.in CONTCAR & POSCAR files.

__molecular_assembly_simple_check.nb__ : Simple check for supercell creation - if adsorbed molecule is affecting its periodical image.

__PP_XY_view_via_XSF.nb__ : ProbeParticle position view. This notebook is basically doing the same thing plot_results.py -- pos but in Mathematica Style. Done loong time ago.

__WSxM_and_geom_2n3D_view.nb__ : Notebook for 2D & 3D visualization of SPM (simulated) data stored in WSxM format together with balls and sticks model of geometry (from DFT calculations). Possible to obtain also any line-profile from SPM data.

