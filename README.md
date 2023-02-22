# HEVC_deblock_FIilter_RAMP
unofficial implement for Paper ["HEVC-BASED DEBLOCKING FILTER WITH RAMP PRESERVATION PROPERTIES"](https://ieeexplore.ieee.org/document/7025744/)

My implement is based on Official HM.16.15(Windows10 Visual Studio 2022) and I just modified the deblockFilter part according to the paper I refered above.
So if you want to implement it in other HM version, my advice is to use TortoiseSVN to download HM softwares with the url(https://hevc.hhi.fraunhofer.de/svn/svn_HEVCSoftware/tags/), and right click on "check out" to download the version you like.

## TEST
> 1.download this repository
```
git clone 
```
> 2.make sure files are set down.
open Folder `./build` and find `HM_vc2015.sln`.
> 3.get ready.
open `HM_vc2015.sln` with Visual Studio
> 4.set and select your own configs.
you can use cfg files in Folder `./cfg` or rewrite your own one.
> 5.prepare your own images.
you can place your images in folder `./dataset`
> 6.build and test.


## HEVC-BASED DEBLOCKING FILTER WITH RAMP PRESERVATION PROPERTIES

