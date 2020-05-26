# fastfil
Fast filamentary/linear structure recognition tool for 2D/3D arrays

## Spine recognition
This package recognizes the spines of filamentary/linear structures first by identifying local maxima in 1D rays shot through each location (pixel/voxel).  These are called spine candidates.

Then fastfil finds the longest simple path through each connected regions (8-neighbors in 2D/26-neighbors in 3D) and defines this path as the filament spine.
