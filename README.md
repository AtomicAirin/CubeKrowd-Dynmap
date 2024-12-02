# CubeKrowd Dynmap

Image formats:

`suSurface-{timestamp}.png` and `suFlat-{timestamp}.png` are original zoomed in version -- IS included in timelapse but needs special treatment

`suSurface58-{timestamp}.png` and `suSurface40-{timestamp}.png` are interim full-size version  -- IS included in timelapse but needs special treatment

`suFlatHD-{timestamp}.png` and `suSurfaceHD-{timestamp}.png` are delta (diff) testing -- NOT to be included in a timelapse

`Q#-suFormat-{timestamp}.png` are quadrants of the map's delta that are stiched into `stitched-suFormat-{timestamp}.png` -- IS included in stitched form

`-delta.png` suffix indicates it is a delta from the prior version (note initial map also has this suffix)

`-master.png` suffix indicates it is the latest full map save, from which map deltas are determined
