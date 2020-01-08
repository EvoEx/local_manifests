## Samsung Galaxy Note 4 and Tab S2 (Exynos) Lineage 17.1-Based ROMs

* Download supported sources (LineageOS, AOSCP, RR, etc...)
* Once this is download, clone this repo to .repo/local_manifests then sync repositories again
* Do the command . build/env*
* Launch your build (brunch treltexx)

## Repo picks
* Required picks to compile and boot lineage-17.0

* repopick 256150 -P bionic/ # Use legacy pthread_mutex_init() behavior on pre-P API levels
* repopick 256151 # Actually restore pre-P mutex behavior
* repopick 256219 # Handle empty thread names
* repopick 256444 -P art/ # Don't fail dual map if memfd isn't supported
* repopick 256960 # add TARGET_NEEDS_NETD_DIRECT_CONNECT_RULE

## Copyright

* Copyright (C) 2019 ananjaser1211 (AnanJaser)
* Copyright (C) 2019 bonuzzz
* Copyright (C) 2019 McFy49 (Matt Grf)
* Copyright (C) 2019 ripee
* Copyright (C) 2019 sayedather (Ather Akber)

## License
Apache License 2.0 (Apache-2.0) (Located at LICENSE, read more at [tldrlegal.com/license/apache-license-2.0](https://tldrlegal.com/license/apache-license-2.0-%28apache-2.0%29))

Short (no legal advice) summary of the used license:


**Can**

 * Commercial Use
 * Modify
 * Distribute
 * Sublicense
 * Private Use
 * Use Patent Claims
 * Place Warranty


**Cannot**

 * Hold Liable
 * Use Trademark


**Must**

 * **Include Copyright**
 * **Include License**
 * **State Changes**
 * **Include Notice**
