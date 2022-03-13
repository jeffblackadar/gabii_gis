# gabii_gis

gabii_gis
These files are numbered with hexadecimal. Refer to the table below for the full key to the file titles example:. file 15 "SU_pts" is a0000000f.gdbtable

|File name |GDB number | GDB Title | Vector type | Comments |
|--- | --- | ---| ---| ---|
|a00000001.gdbtable|1 |GDB_SystemCatalog|||



|a00000002.gdbtable
|a00000003.gdbtable
|a00000004.gdbtable
|a00000005.gdbtable
|a00000006.gdbtable
|a00000007.gdbtable
|a00000009.gdbtable
|a0000000a.gdbtable, points, finds
|a0000000b.gdbtable, points, a few fixed points
|a0000000c.gdbtable, points, many points SU_Number, PM_Number
|a0000000d.gdbtable, points, core_sample_points, 1 point
|a0000000e.gdbtable, poly, SU_poly, polys of the main structures
|a0000000f.gdbtable, points, SU_points,
|a00000010.gdbtable
|a00000011.gdbtable
|a00000012.gdbtable
|a00000013.gdbtable
|a00000014.gdbtable
|a00000015.gdbtable
|a00000016.gdbtable
|a00000017.gdbtable
|a00000018.gdbtable
|a00000019.gdbtable, lines, SU_lines
|a0000001a.gdbtable
|a0000001b.gdbtable, points, Surface_topography,
|a0000001c.gdbtable
|a0000001d.gdbtable
|a0000001e.gdbtable
|a0000001f.gdbtable
|a00000020.gdbtable
|a00000021.gdbtable
|a00000022.gdbtable
|a00000023.gdbtable, points, infrastructure, infrastructure
|a00000024.gdbtable
|a00000025.gdbtable
|a00000026.gdbtable
|a00000027.gdbtable
|a00000028.gdbtable, poly, ap_feats, large polys of a few features
|a00000029.gdbtable, poly, SU_Feat, polys of main features
|a0000002a.gdbtable
|a0000002b.gdbtable, poly, su_outlines, su outlines
|a0000002c.gdbtable
|a0000002d.gdbtable
|a0000002e.gdbtable, poly, ORG_illustration_conventions
|a0000002f.gdbtable, poly, ORG_SU_poly, The road past the church, the south east
|a00000001.gdbtable GDB_SystemCatalog

wkt_geom ID Name FileFormat
9 EXCAV 0
8 GDB_ReplicaLog 2
15 SU_pts 0
14 SU_poly 0
13 core_sample_points 0
12 PM 0
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
19 section_points 0
18 sections 0
17 micromorphology_samples 0
16 Topo 0
23 Q2010_Concession_line 0
22 BS 0
21 BM 0
20 soil_samples 0
27 Surface_topography 0
26 quarry_points 0
25 SU_lines 0
24 Quarrying 0
31 Church 0
30 Core_Samples 0
29 core_sample_SU 0
28 SU_digital_poly 0
3 GDB_SpatialRefs 0
2 GDB_DBTune 0

7 GDB_ItemRelationshipTypes 0
6 GDB_ItemRelationships 0
5 GDB_ItemTypes 0
4 GDB_Items 0
11 Fixed_Points 0
10 finds 0

au_dga tifs
+ Created a gcp .points file with 6 geo reference points from layer a0000000e SU_poly
+ Open georeferencer
+ Check target SRS is EPSG:102093
+ change output file name to _102093
+ File | Load GCP Points... AU DGA_00_template.points
+ Move 6 points to correct place on image
+ Start georefererncing
+ Check results in QGIS
