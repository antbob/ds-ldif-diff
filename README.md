# ds-ldif-diff
LDIF DIFF

Dependencies: python-ldap, python-lib389

```
usage: ds-ldif-diff [-h] [-v] -s SLDIF -t TLDIF [-i IGNORE] [-o FILE]

LDIF Comparison Tool (v2.0). This script can be used to compare two LDIF files for differences.

options:
  -h, --help            show this help message and exit
  -v, --verbose         Verbose output
  -s SLDIF, --source-ldif SLDIF
                        Source LDIF file
  -t TLDIF, --target-ldif TLDIF
                        Target LDIF file
  -i IGNORE, --ignore IGNORE
                        Comma separated list of attributes to ignore
  -o FILE, --out-file FILE
                        The output file
```
