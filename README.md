# gabii_gis

gabii_gis
These files are numbered with hexadecimal. Refer to the table below for the full key to the file titles example:. file 15 "SU_pts" is a0000000f.gdbtable

|File name         |GDB number | GDB Title | Vector type | Comments |
|---               | --- | ---| ---| ---|
|a00000001.gdbtable|1 |GDB_SystemCatalog|||
|a00000002.gdbtable|2|GDB_DBTune|||
|a00000003.gdbtable|3|GDB_SpatialRefs|||
|a00000004.gdbtable|4|GDB_Items|||
|a00000005.gdbtable|5|GDB_ItemTypes|||
|a00000006.gdbtable|6|GDB_ItemRelationships|||
|a00000007.gdbtable|7|GDB_ItemRelationshipTypes|||
|a00000008.gdbtable|8|GDB_ReplicaLog|||
|a00000009.gdbtable|9|EXCAV|||
|a0000000a.gdbtable|10|finds|points|finds|
|a0000000b.gdbtable|11|Fixed_Points| points|a few fixed points|
|a0000000c.gdbtable|12|PM| points| many points SU_Number PM_Number|
|a0000000d.gdbtable|13|core_sample_points| points| core_sample_points 1 point|
|a0000000e.gdbtable|14|SU_poly| poly| Polys of the main structures|
|a0000000f.gdbtable|15|SU_pts| point| |
|a00000010.gdbtable|16|Topo|||
|a00000011.gdbtable|17|micromorphology_samples|||
|a00000012.gdbtable|18|sections|||
|a00000013.gdbtable|19|section_points|||
|a00000014.gdbtable|20 soil_samples|||
|a00000015.gdbtable|21|BM|||
|a00000016.gdbtable|22|BS|||
|a00000017.gdbtable|23|Q2010_Concession_line|||
|a00000018.gdbtable|24|Quarrying|||
|a00000019.gdbtable|25|SU_lines|lines||
|a0000001a.gdbtable|26|quarry_points|||
|a0000001b.gdbtable|27|Surface_topography|points||
|a0000001c.gdbtable|28|SU_digital_poly|||
|a0000001d.gdbtable|29|core_sample_SU|||
|a0000001e.gdbtable|30|Core_Samples|||
|a0000001f.gdbtable|31|Church|||


|a00000020.gdbtable|
|a00000021.gdbtable|
|a00000022.gdbtable|
|a00000023.gdbtable| points, infrastructure, infrastructure
|a00000024.gdbtable|
|a00000025.gdbtable|
|a00000026.gdbtable|
|a00000027.gdbtable|
|a00000028.gdbtable| poly, ap_feats, large polys of a few features
|a00000029.gdbtable| poly, SU_Feat, polys of main features
|a0000002a.gdbtable|
|a0000002b.gdbtable| poly, su_outlines, su outlines
|a0000002c.gdbtable|
|a0000002d.gdbtable|
|a0000002e.gdbtable| poly, ORG_illustration_conventions
|a0000002f.gdbtable| poly, ORG_SU_poly, The road past the church, the south east
|a00000001.gdbtable| GDB_SystemCatalog

wkt_geom ID Name FileFormat


35 infrastructure 0
34 Infra_lines 0
33 INFRA 0
32 Church_points 0
39 geophys_feats 0
38 interpolated_polylines 0
37 interpolated_polygons 0
36 ext_bs 0
43 su_outlines 0
42 illustration_conventions 0
41 SU_Feat 0
40 ap_feats 0
47 ORG_SU_poly 0
46 ORG_illustration_conventions 0
45 GDB_ReplicaChanges 0
44 GroundPenetratingRadar 0







au_dga tifs
+ Created a gcp .points file with 6 geo reference points from layer a0000000e SU_poly
+ Open georeferencer
+ Check target SRS is EPSG:102093
+ change output file name to _102093
+ File | Load GCP Points... AU DGA_00_template.points
+ Move 6 points to correct place on image
+ Start georefererncing
+ Check results in QGIS
