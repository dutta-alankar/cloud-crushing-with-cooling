# cloud-crushing-with-cooling
This is the place which has the codes for the run and visualization in the paper `Growth and structure of multiphase gas in the cloud-crushing problem with cooling`

The file `cooltable.dat` has the cooling function we used in our simulations. We use Solar metallicity values from Asplund et al. 2009
`X, Y, Z = 0.7154, 0.2703, 0.0143`

Here's a list of what each program does

`GOLi-compare.py`: Plots `Figure 1` from the paper. It compares the Gronke-Oh and Li criterion in terms of the run prameters of our simulations.

`overlay.py`: Plots `Figure 2` from the paper. It superimposes our cloud crushing result on to that of Li et al. (their bottom panel of `Figure 3`)
