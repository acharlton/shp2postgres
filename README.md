# notes to import shape files to postgres

import shp file directly into postgres, table is automatically created with the shp format

ogr2ogr -f PostgreSQL -t_srs EPSG:900913 PG:'user=postgres host=localhost dbname=sl password=postgres' -nlt PROMOTE_TO_MULTI ~/Downloads/sri-lanka-latest.shp/roads.shp -overwrite

