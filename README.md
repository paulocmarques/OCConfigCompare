# OCConfigCompare
Python script to compare two plists and list missing keys in either.

***

```
usage: OCConfigCompare.py [-h] [-u USER_PLIST] [-s SAMPLE_PLIST] [-r]
                          [-w [SUPPRESS_WARNINGS]] [-v] [-x HIDE_PREFIX] [-n]
                          [-c [CASE_SENSITIVE]] [-m [COMPARE_VALUES]] [-d]

options:
  -h, --help            show this help message and exit
  -u, --user-plist USER_PLIST
                        Path to the local user plist.
  -s, --sample-plist SAMPLE_PLIST
                        Path to the sample plist - will get the latest commit
                        from OC if none passed.
  -r, --use-release     Get the latest release sample instead of the latest
                        commit if none passed.
  -w, --suppress-warnings [SUPPRESS_WARNINGS]
                        Yes/no (default: yes), sets if non-essential warnings
                        (empty lists, etc) show when comparing - overrides
                        settings.
  -v, --verbose         Print more verbose output - forces '-w yes' and '-n' -
                        overrides settings.
  -x, --hide-prefix HIDE_PREFIX
                        Prefix to hide when comparing.
  -n, --no-prefix       Clears all hide prefixes - overrides '-x' and
                        settings.
  -c, --case-sensitive [CASE_SENSITIVE]
                        Yes/no (default: yes), sets hide prefix case-
                        sensitivity - overrides settings.
  -m, --compare-values [COMPARE_VALUES]
                        Yes/no/array (default: no), check for value
                        differences as well - overrides settings.
  -d, --dev-help        Show the help menu with developer options visible.
```
