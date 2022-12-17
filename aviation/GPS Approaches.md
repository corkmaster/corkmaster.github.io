## Non-Precision (2D Approaches)

Where things like terrain or obstacles prohibit vertical guidance, lateral only approaches can be published:

### LNAV: Lateral Navigation

A traditional GPS approach with lateral guidance only. MDA will typically be as high as 400ft.

### LP: Localiser Performance

The newest type of approach, introduced in 2009. The lateral guidance is angular, with increasing sensitivity closer to the MAP, like a localiser. 
This differs from traditional LNAV where the sensitivity is constant from the FAF to the MAP. LP therefore gets a lower MDA usually.

## APV: Approach with Vertical Guidance (3D Approaches)


#### LPV: Localiser Performance with Vertical Guidance

Require [WAAS/SBAS] capable receivers. Technically still 'non-precision', but can get you down to a low decision altitude, like an ILS, often 200 feet.


#### LNAV/VNAV: Lateral Navigation/Vertical Navigation

They were the first GPS approaches with vertical guidance and designed for use with [baro-aided GPS] originally, but can also be used with [WAAS/SBAS] capable recievers these days.
They are less sensitive than LPV so don't get you as low.

#### LNAV +V: LNAV with 'advisory vertical guidance'

A [WAAS/SBAS] capable receiver can offer advisory guidance on a traditional LNAV only 'step-down' approach. This is not displayed on the chart but the GPS receiever will display it if it is capable.
The minimum altitidue is still the LNAV MDA. 
