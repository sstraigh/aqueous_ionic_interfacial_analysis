This series of codes is designed to extract the probability density
of finding ions and water as a function of the distance, z, away from
the center of mass of the water molecules.

Given a set of nvt trajectories, the workflow proceeds as follows:

	1. Concatenate all NVT HISTORY files
	2. Extract all z-components of atomic coordinates
	3. Compute histograms of relative distance away from water center-of-mass

The codes used to follow this workflow are (in order):

1) ./
2) ./
3) ./COM_density_profile.py or ./COM_density_profile_water-only.py
