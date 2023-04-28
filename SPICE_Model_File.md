`````
//Use the following SPICE model for MOSFETs to simulate the circuits:
.model nch NMOS
+ LEVEL = 3
+ VTO = 0.70
+ UO = 660
+ TOX = 1.40E-08
+ NSUB = 3E+16
+ XJ = 2.0e-7

+ LD = 1.6E-08
+ NFS = 7e+11
+ VMAX = 1.8e5
+ DELTA = 2.40
+ ETA = 0.1
+ KAPPA = 0.15
+ THETA = 0.1
+ CGDO = 2.20E-10
+ CGSO = 2.20E-10
+ CGBO = 7.00E-10
+ MJ = 0.50
+ CJSW = 3.50E-10
+ MJSW = 0.38
.model pch PMOS
+ LEVEL = 3
+ VTO = -0.70
+ UO = 210
+ TOX = 1.40E-08
+ NSUB = 6.00e16
+ XJ = 2.0e-7
+ LD = 1.5E-08
+ NFS = 6E+11
+ VMAX = 2.00e5
+ DELTA = 1.25
+ ETA = 0.1
+ KAPPA = 2.5
+ THETA = 0.1
+ CGDO = 2.20E-10
+ CGSO = 2.20E-10
+ CGBO = 7.00E-10
+ MJ = 0.50
.end

`````
