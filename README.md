# HEVC_deblock_Filter_RAMP
unofficial implement for Paper ["HEVC-BASED DEBLOCKING FILTER WITH RAMP PRESERVATION PROPERTIES"](https://ieeexplore.ieee.org/document/7025744/)

My implement is based on Official HM.16.15(Windows10 Visual Studio 2022) and I just modified the deblockFilter part according to the paper I refered above.
So if you want to implement it in other HM version, my advice is to use TortoiseSVN to download HM softwares with the url(https://hevc.hhi.fraunhofer.de/svn/svn_HEVCSoftware/tags/), and right click on "check out" to download the version you like.

All my work is done in Folder `HM16.15_modify` and is built on Project `HM16.15_origin` which is downloaded from TortoiseSVN.

## TEST 
> 1.download this repository
```
git clone https://github.com/giaogiao-1-a/HEVC_deblock_Filter_RAMP.git
```
> 2.make sure files are set down.
```
open Folder `./HM16.15_modify/build` and find `HM_vc2015.sln`.
```
> 3.get ready.
```
open `HM_vc2015.sln` with Visual Studio
```
> 4.set and select your own configs.
```
you can use cfg files in Folder `./HM16.15_modify/cfg` or rewrite your own one.
```
> 5.prepare your own images.
```
you can place your images in folder `./HM16.15_modify/dataset`
```
> 6.build and test.
###### MyExample
set workplace in Folder `./HM16.15_modify/workplace`  
use cfg files in `./HM16.15_modify/workplace/cfgfiles`  
yuv files in Folder `./HM16.15_modify/workplace/dataset` for demostration  
## REMEMBER to set the img size Correctly!
(P.S. you can look over how to use TAPPEnc or TAPPDec by input `TAppEncoder` in cmd)  

## HEVC-BASED DEBLOCKING FILTER WITH RAMP PRESERVATION PROPERTIES

###### pics for better understanding  
![image](https://github.com/giaogiao-1-a/HEVC_deblock_FIilter_RAMP/blob/main/demo.PNG)  

Results and effect of the method in this paper(from the paper).  
![image](https://github.com/giaogiao-1-a/HEVC_deblock_FIilter_RAMP/blob/main/demo2.PNG)  




