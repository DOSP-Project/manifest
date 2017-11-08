<p align="center">
<img src="https://raw.githubusercontent.com/DOSP-Project/Desi_Goodness/n7x/DOSP-Logo.png" width="1000px" height="180px" alt="DOSP logo" > 
</p>


DOSP-OS (The Desi OS)
---------------

Getting Started
---------------
To get started with the DOSP-OS sources, you'll need to get familiar with [Git and Repo](https://source.android.com/source/using-repo). 

Initialize the Repositories 
---------------------------
```bash
    repo init -u https://github.com/DOSP-project/manifest.git -b n7x
```

Initialize the Repositories with reduced download size
------------------------------------------------------
```bash
    repo init --depth=1 -u https://github.com/DOSP-project/manifest.git -b n7x
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
* [**TeamSubstratum (Theme Engine)**](https://github.com/Substratum)
* [**SlimRoms**](https://github.com/SlimRoms)
* [**Nitrogen Project**](https://github.com/nitrogen-project)
* [**Pure Nexus**](https://github.com/PureNexusProject)
* [**OmniROM**](https://github.com/omnirom/)


