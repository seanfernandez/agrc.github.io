---
layout: post
status: publish
published: true
title: Utah SGID Statewide Roads Data Layer Updates 12/3/2015
author:
  display_name: Data Queen
  login: kgreen
  email: agrc@utah.gov
  url: ''
author_login: kgreen
author_email: agrc@utah.gov
wordpress_id: 18241
wordpress_url: http://gis.utah.gov/?p=18241
date: '2015-12-03 14:55:21 -0700'
date_gmt: '2015-12-03 21:55:21 -0700'
categories:
- Data
- Featured
tags:
- SDE
- sgid
- Geocoding
- Data
- utah
- gis
- map
- mapping
- Cartography
- Roads
- Streets
- location
- address
- dataset
- download
- agrc
- layer
- shapefile
- geodatabase
- shp
- gdb
- lyr
- digital
- geographic
- information
- database
- state
- statewide
- centerlines
- vector
- arcgis
---
<p>Updates were made recently to the SGID10.Transportation.Roads feature class that resides on the <a href="{{ "/data/how-to-connect-to-the-sgid-via-sde/" | prepend: site.baseurl }}">Utah SGID ArcSDE database server</a>.</p>
<p>The updated Roads data is also available as shapefiles and file geodatabase files for download on the <a href="ftp://ftp.agrc.utah.gov/UtahSGID_Vector/UTM12_NAD83/TRANSPORTATION/PackagedData/_Statewide/UtahRoadAndHighwaySystem/">SGID FTP site</a>.</p>
<p>Geocoding services and ArcGIS Server Applications & Web Services are now using the updated SGID10.Transportation.Roads feature class.</p>
<p>The following highlights what has been updated:</p>
<p><span style="text-decoration: underline;">County Updates:</span></p>
<ul>
<li><strong>Davis:</strong> Received centerline update 12/2/2015: added new roads, road name and address range changes since last update on 10/7/2015; geocoding improvements</li>
<li><strong>Emery:</strong> Received centerline update 11/19/2015: added new roads, road name and address range changes since last update on 11/24/2014; geocoding improvements</li>
<li><strong>Grand:</strong> Received Thompson Springs Master Address List (MAL) 10/15/2015: joined MAL addresses to parcel data layer and generated address points from the parcel centroid: added new roads, road name and address range changes; geocoding improvements</li>
<li><strong>Salt Lake:</strong> Received VECC's centerline update 11/23/2015: added new roads, road name and address range changes since last update on 10/27/2015; geocoding improvements</li>
<li><strong>Utah:</strong> Received centerline update 11/25/2015: added new roads, road name and address range changes since last update on 11/3/2015; geocoding improvements</li>
<li><strong>Washington:</strong> Received centerline update 11/25/2015: added new roads, road name and address range changes since last update 10/27/2015; geocoding improvements</li>
<li><strong>Wayne:</strong> Received centerline update 11/24/2015: added new roads, road name and address range changes since last comprehensive update on 5/20/2014; geocoding improvements</li>
</li>
<li><strong>Weber:</strong> Received centerline update 11/11/2015: added new roads, road name and address range changes since last comprehensive update on 5/19/2015; geocoding improvements</li>
</li>
</ul>
<p><span style="text-decoration: underline;">Blue Stakes of Utah Feedback:</span></p>
<ul>
<li><strong>Salt Lake:</strong> geocoding improvements</li>
<li><strong>Tooele:</strong> geocoding improvements</li>
</ul>
<p><span style="text-decoration: underline;">UDOT Route System:</span></p>
<ul>
<li>The DOT_F_MP (From Milepost) and DOT_T_MP (To Milepost) fields that store the milepost attributes of the UDOT state and federal routes in SGID10.Transportation.Roads were updated</li>
<li>The DOT_RTID field that stores UDOT's unique numeric route identifiers was updated</li>
