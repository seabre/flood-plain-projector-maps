# Flood Plain Projector Maps

[Mapnik](http://mapnik.org/) style (flood.xml) for the FEMA NFHL data for [Flood Plain Projector](https://github.com/seabre/flood-plain-projector)

Includes an example config for [TileStache](http://tilestache.org/) for serving the tiles.

This style assumes that the NFHL data has been pulled in through the [FEMA NFHL PostGIS load script](https://github.com/seabre/fema-nfhl-postgis-load) written by the Flood Plain Projector team.

You will need to change the `user`, `password`, and `dbname` parameters in flood.xml according to the user you are using for PostGIS and where your NFHL data is stored.
