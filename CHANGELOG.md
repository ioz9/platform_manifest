### 01/30/2012
* Added changelog to list what varies in this repo from the CM repos (for any device specific changes please see the device trees).
* Removed non-used branches.
* Back entry: removed all CM supported devices (I may add some of these back in if I ever find myself working on them but for the meantime the only things I forsee are non-supported such as the Kindle Fire). The product make files are still included in vendor/cyanogen but you will have the clone the device folders if you wish to try to build for something not in this repo (currently there are no device repos listed).
* Back entry: I have added another build config to use as oppse to common_full; referred to as 'not_so_common' this will build without the CM support apps (CM stats, Update Notifier and Rom Manager).

### 01/31/2012
* Using a local frameworks/base instead of the CM repo. Currently the only change is a statusbar fix for when the lockscreen is disabled.
* Ok so this fix was merged about 2 hours after my changing it here, reverting back to Cyanogen framework repo to easier keep up w/ other changes.

### 02/01/2012
* Using a local [build](https://github.com/IngCr3at1on/android_build) repo instead of the CM one. See the readme/history markdowns for more information.

