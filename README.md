# GPMDB_GIS_version
Here is the GIS shapefile for the latest Global Paleomagnetic Database (GPMDB)
4.6b. It can be opened using QGIS or ArcGIS. **Please note that here the points
visulized are sampling sites**.

![GPMDB 4.6b opened in QGIS](gpmdb46b_qgis_demo.png?raw=true)

Use

```shell
tar xvfz gpmdb46b_shp.tar.gz
```

to decompress the *.tar.gz file. You may need to install tar first. For example, if
you are using ubuntu Linux, use

```shell
apt-get install tar
```

. For other Linux distros, the command should be similar.

The original file is in Microsoft Access *.MDB format (See its source [here][1]).

This version includes published data up to Dec 2004, all Australian
published data up to Jan 2011, and some additional data published
in 2005-2010. The total number of included paleomagnetic poles is 9360.

GPMDB was originally created by [Michael McElhinny and Jo Lock (1996)][2], and
recently maintained by [Sergei A. Pisarevsky][3].

[1]: https://confluence.csiro.au/display/cmfr/Palaeomagnetism+and+Rock+Magnetism
[2]: https://link.springer.com/article/10.1007%2FBF01888979
[3]: http://onlinelibrary.wiley.com/doi/10.1029/2003EO200007/full
