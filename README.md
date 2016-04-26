# pymgrs
Pure Python MGRS coordinate converter.

This is a python port of javascipt utiliy for converting between WGS84 lat/lng and MGRS coordinates. Which can be found at https://github.com/proj4js/mgrs

```
if __name__ == '__main__':
    print(getMinNorthing('T'))
    print(LLtoUTM(37.65398996452414, 44.00628471597047))
    print(encode(LLtoUTM(37.65398996452414, 44.00628471597047),5))
    print(UTMtoLL(decode("38SMG12345678")))
```

Licensed under the MIT license except:

Portions of this software are based on a port of components from the OpenMap
com.bbn.openmap.proj.coords Java package. An initial port was initially created
by Patrice G. Cappelaere and included in Community Mapbuilder
(http://svn.codehaus.org/mapbuilder/), which is licensed under the LGPL license
as per http://www.gnu.org/copyleft/lesser.html. OpenMap is licensed under the
[following license agreement](openmap.md):
