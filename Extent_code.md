## Overview
This thread shows how to judge if a source is an extended source or a point source.
**Theoretical explanation:** [https://cxc.cfa.harvard.edu/csc/columns/srcextent.html#dcsrcextent](https://cxc.cfa.harvard.edu/csc/columns/srcextent.html#dcsrcextent)
**Technical realization:** [https://cxc.cfa.harvard.edu/ciao/PSFs/chart2/index.html](https://cxc.cfa.harvard.edu/ciao/PSFs/chart2/index.html)

Tips:
1. ds9 may not open，remember to download xquartz（[https://www.xquartz.org/](https://www.xquartz.org/)）
2. If there is no MARX，follow [https://space.mit.edu/ASC/MARX/inbrief/install.html](https://space.mit.edu/ASC/MARX/inbrief/install.html)to install it, especially the INSTALL document.

Step 1: enter ciao environment
```
conda activate ciao-4.15
```

Step 2: 
```
/Users/joey/Documents/Shell_scripts/extent_code_1.sh
```
Find coordinates: [http://cda.cfa.harvard.edu/cscweb/index.do](http://cda.cfa.harvard.edu/cscweb/index.do)
Find nH: [https://heasarc.gsfc.nasa.gov/cgi-bin/Tools/w3nh/w3nh.pl?Entry=F2M+J083011.13%2B375951.9&NR=GRB%2FSIMBAD%2BSesame%2FNED&CoordSys=Equatorial&equinox=2000&radius=0.1&usemap=0](https://heasarc.gsfc.nasa.gov/cgi-bin/Tools/w3nh/w3nh.pl?Entry=F2M+J083011.13%2B375951.9&NR=GRB%2FSIMBAD%2BSesame%2FNED&CoordSys=Equatorial&equinox=2000&radius=0.1&usemap=0)

Step 3
Run chaRT, uploading source_flux_chart.dat，set the number of iterations of 5.（虽然还不知道为啥。。）

Step 4
Set the path in .zprofile.  Input:
```
## <local_marx_directory>，如/Users/joey/MARX/marx-5.5.2
export MARX_DIR=<local_marx_directory> 

PATH=${PATH}:$MARX_DIR/bin

export MARX_DATA_DIR=$MARX_DIR/share/marx/data
```

Step 5
```
/Users/joey/Documents/Shell_scripts/extent_code_2.sh
```
##### Draw the radial profile

Step 1
```
ds9 bin1.fits &
ds9 cts_psf.fits &
```
画出annuli区域，分别保存为real.reg（真实数据），real_bgd.reg (背景)，match.reg（模拟结果），match_bgd.reg（背景）

Step 2
```
/Users/joey/Documents/Shell_scripts/extent_code_3.sh
```
radial profile图片保存为real_rprofile.png，real_rprofile_fit.png，match_rprofile.png，match_rprofile_fit.png

##### 结果展示