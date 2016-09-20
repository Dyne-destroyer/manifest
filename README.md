Cardinal-AOSP
===================

To initialize your local repository using the CARDINAL-AOSP trees, use a command like this:

To sync Cardinal-AOSP
````bash
repo init -u git://github.com/Cardinal-AOSP/manifest.git -b crd6.0
```
Then to sync up:
````bash
repo sync -c --force-sync -f --no-tags
```
