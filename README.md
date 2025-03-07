# PatchMerge
Py script to merge patches_[OC/Clover].plist contents from SSDTTime or FixScopes with a selected config.plist.

***

```
usage: PatchMerge.py [-h] [-c CONFIG] [-r RESULTS] [-o] [-i]

PatchMerge - py script to merge patches_[OC/Clover].plist with a config.plist.

options:
  -h, --help            show this help message and exit
  -c, --config CONFIG   path to target config.plist - required if running in non-interactive mode
  -r, --results RESULTS
                        path to Results folder containing patches_[OC/Clover].plist - required if running in non-
                        interactive mode
  -o, --overwrite       overwrite the original config.plist
  -i, --no-interaction  run in non-interactive mode - requires -c and -r
```
