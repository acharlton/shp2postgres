ogr2ogr -f PostgreSQL -t_srs EPSG:900913 PG:'user=postgres host=localhost dbname=sl password=postgres' -nlt PROMOTE_TO_MULTI ~/Downloads/sri-lanka-latest.shp/roads.shp -overwrite

