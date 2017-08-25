#Setting up a minimal tree for building TWRP


###To initialize the main repository:

````
repo init -u https://github.com/andrewgreen5610/TWRP-manifest.git -b master
````
```````
repo sync 
```````
BUILDING IT FOR ZTE AVID PLUS ACHILL 

$ cd [twrp source which synced from above]

$ source build/envsetup.sh 

$ lunch omni_achill-userdebug 

$ make clean && make -j# recoveryimage  [# : no. of cpu cores ] 
