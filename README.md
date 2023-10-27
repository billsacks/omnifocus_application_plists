This repository contains plist files that I have modified from the OmniFocus Applications contents.

All of these files appear under the Contents subdirectory.

To apply these diffs to a new version of OmniFocus:

``` shell
git diff original -- Contents > $scratch/diff.patch
cd /Applications/OmniFocus.app/
patch -p1 < $scratch/diff.patch
```

