Summary
=======

cues - Utility that splits one huge file into single files using a CUE sheet.
It can split WAV, FLAC and WavPack files. Also you can specify an encoding of
a CUE sheet file (UTF-8 is using by default and CP1251 would be detected
automatically).

Usage
=====

```
cues <cue_path>

Optional arguments:
    -e ENCODING: Encoding, like 'koi8-r';
```

Requirements
============

* Python >= 3.5
* setuptools (for installation only)

Build and install
=================

```
$ python setup.py install
```

License
=======

GPL
