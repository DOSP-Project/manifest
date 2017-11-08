<p align="center">
<img src="https://raw.githubusercontent.com/DOSP-Project/Desi_Goodness/o8x/DOSP-Logo.png" width="1000px" height="180px" alt="DOSP logo" > 
</p>


DOSP Oreo (The Desi OS)
--------------------------
DOSP ( Desi Open Source Project ) is an AOSP based rom which provides Customized UI with various customizations features. The project has been made with help of various commits from various other projects like (LineageOS/CyanogenMOD, AOSiP, DirtyUnicorns, Pure Nexus, Aosp Extended). We will constantly try to add more features and make it even better in future updates. Thanks for being the part of our family. #TeamDOSP

Getting Started
---------------
To get started with the DOSP-OS sources, you'll need to get familiar with [Git and Repo](https://source.android.com/source/using-repo). 

Initialize the Repositories 
---------------------------
```bash
    repo init -u https://github.com/DOSP-project/manifest.git -b o8x
```

Initialize the Repositories with reduced download size
------------------------------------------------------
```bash
    repo init --depth=1 -u https://github.com/DOSP-project/manifest.git -b o8x
```
Then to sync up:
---------------
```bash
    repo sync --force-sync --force-broken --no-clone-bundle -jx ( here "x" is the number of threads )
```

Finally to build:
-----------------
```bash
    . build/envsetup.sh
     lunch desi_<device>-userdebug
     mka desi (or) make desi
```
  
Credits
-------
* [**AOSP-JDC (Base)**](https://github.com/AOSP-JF-MM)
* [**LineageOS**](https://github.com/LineageOS)
* [**DirtyUnicorns**](https://github.com/DirtyUnicorns)
* [**AospExtended**](https://github.com/AospExtended)
* [**SlimRoms**](https://github.com/SlimRoms)
* [**Nitrogen Project**](https://github.com/nitrogen-project)
* [**Pure Nexus**](https://github.com/PureNexusProject)
* [**OmniROM**](https://github.com/omnirom/)


