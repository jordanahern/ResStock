This code is used to aggregate downloads from NREL's ResStock data viewer: https://resstock.nrel.gov/dataviewer/?datasetName=vizstock_resstock_amy2018_release_2022_1_by_state_view

My use case involved downloading 15-min profiles from numerous states, including numerous EE measures

This ocde turns each download into an 8760 profile, retains only baseline and electricity values, and provides sums across both for all end-uses. 
