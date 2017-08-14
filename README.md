DOSP-OS (The Desi OS)
---------------

Getting Started
---------------
To get started with the DOSP-OS sources, you'll need to get familiar with [Git and Repo](https://source.android.com/source/using-repo). 

Initialize the Repositories 
---------------------------
    repo init -u https://github.com/DOSP-project/Desi_Goodness.git -b n7.x

Then to sync up:
---------------
    repo sync --force-sync --force-broken --no-clone-bundle -jxx (Ur Choice)


Finally to build:
-----------------
    . build/envsetup.sh
     lunch desi_<device>-userdebug
     mka desi

  
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


