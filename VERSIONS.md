# OMF versioning

## Formatting

OMF does, like any other thing, come in versions  
The main difference is the version format, wich works as following:
```
OMF 1 2.3.4
```
Where `OMF` is the name, `1` is the biggest update, wich does not guarantee backwards compatablity nor even the same format at all as other versions.
The `2` is the major version, major versions ***must*** be backward compatible, but not forwards. The `3` is the minor, and specifies mostly minor changes in the specification, but can also be used for major updates. These are most commonly only for minor changes/fixes in the specification, and will most likely build across all versions. The `4` adresses sub-minor updates, and they will most likely be used for spelling fixes or some minor naming convention change.

## Version history

### OMF 1
1.0.0 - The initial release of OMF