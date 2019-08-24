# fields/GL_EXTENTS

The [GL_EXTENTS](gl_extents.md) field looks something like this:

|CB_ID|GL_EXTENTS|
|-|-|
|98|2002:3 2003:4 2003:7 2004:4 2005:4 2006:4 2006:7 2007:4 2007:7 2008:4 2008:7 2009:4 2009:7 2010:4 2010:7 2011:4 2012:4 2012:7|
|99|2003: 5, 2006:5|

The [GL_EXTENTS](gl_extents.md) field is made up of a `GEOLOCATION` part and an `EXTENTS` part. In the case where `GL_EXTENTS = 2002:3`, `2002` and `3` would be the `GEOLOCATION` and `EXTENTS` respectively. This means that the data is available on the `Country` level (`2002`) and for `England and Wales as a single entity` (`3`).

## GEOLOCATIONS

- 2000 - **United Kingdom**
- 2001 - **Great Britain**
- 2002 - **England and Wales as a single entity**
- 2003 - **Countries**
- 2004 - **Regions**
- 2005 - **Counties**
- 2006 - **Local Authorities**
- 2007 - **Wards and Electoral Divisions**
- 2008 - **Middle Super Output Areas & Intermediate Zones**
- 2009 - **Lower Super Output Areas & Data Zones**
- 2010 - **Output Areas and Small Areas**
- 2011 - **Merging Local Authorities**
- 2012 - **Merging Wards & Electoral Division**
- 2013 - **Workplace Zone Layer**

## EXTENTS

- 1 - **United Kingdom**
- 2 - **Great Britain**
- 3 - **England and Wales as a single entity**
- 4 - **England**
- 5 - **Northern Ireland**
- 6 - **Scotland**
- 7 - **Wales**

In short what this all means is that if you were to have a [GL_EXTENTS](gl_extents.md) of `2005:3, 2010:2, 2013:4` this would mean that for this specific combination the data would be available for:

- Counties in England and Wales as a combined authority
- Output Areas and Small Areas in Great Britain
- Workplace Zone Layers in England

