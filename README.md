PhalangerSkeleton
=================

A skeleton for a Phalanger web configured for IIS

Notes
-----
* An example of how to configure Phalanger without the need to GAC the assemblies (so it can be used on a web server which you don't control, e.g. it SHOULD also work with Azure Web Sites)
* Using the latest Phalanger, which is version 4.0.0.0 (cloned and built locally)
* The binaries can be easily bin deployed (although I'm using the phalanger folder not the bin folder for the Phalanger Dlls)
* If you want to use an older version of Phalanger please replace the binaries in the phalanger directory and correct the version information for each assembly in the web.config and phalanger.config.
* The MySQL library is using version 3.0.0.0 (with an assemblyBinding to fix the issue with Phalanger version 4.0.0.0)

Usage (with WebMatrix)
----------------------
* Clone repository
* Launch [WebMatrix](http://www.microsoft.com/web/webmatrix/)
* Choose "open from folder" and open the previously cloned folder
* Do NOT install PHP when it says that PHP was detected
* Run it
