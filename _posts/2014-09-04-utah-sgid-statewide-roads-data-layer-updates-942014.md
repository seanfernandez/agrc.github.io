---
layout: post
status: publish
published: true
title: Utah SGID Statewide Roads Data Layer Updates 9/4/2014
author:
  display_name: Data Queen
  login: kgreen
  email: agrc@utah.gov
  url: ''
author_login: kgreen
author_email: agrc@utah.gov
wordpress_id: 15473
wordpress_url: http://gis.utah.gov/?p=15473
date: '2014-09-04 10:26:11 -0600'
date_gmt: '2014-09-04 16:26:11 -0600'
categories:
- Data
- Featured
tags:
- Geocoding
- utah
- gis
- map
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
- geographic
- information
- database
- vector
- arcgis
- road
- centerlined
- ata
- sdes
- gid
- stateiwide
---
<p>Updates were made recently to the SGID10.Transportation.Roads feature class that resides on the <a href="{{ "/data/how-to-connect-to-the-sgid-via-sde/" | prepend: site.baseurl }}">Utah SGID ArcSDE database server</a>.</p>
<p>The updated Roads data is also available as shapefiles and file geodatabase files for download on the <a href="ftp://ftp.agrc.utah.gov/UtahSGID_Vector/UTM12_NAD83/TRANSPORTATION/PackagedData/_Statewide/UtahRoadAndHighwaySystem/">SGID FTP site</a>.</p>
<p>Geocoding services and ArcGIS Server Applications & Web Services are now using the updated SGID10.Transportation.Roads feature class.</p>
<p>The following highlights what has been updated:</p>
<p><span style="text-decoration: underline;">County Updates:</span></p>
<ul>
<li><strong>Davis:</strong> Received centerline update 8/8/2014: added new roads, road name and address range changes since last update on 7/1/2014; geocoding improvements</li>
<li><strong>Salt Lake:</strong> Received VECC's centerline update 8/27/2014: added new roads since last update on 7/23/2014; geocoding improvements</li>
<li><strong>Tooele:</strong> Received centerline update 8/12/2014: added new roads since last update on 9/10/2013; geocoding improvements</li>
<li><strong>Utah:</strong> Received centerline update 8/7/2014: added new roads, road name and address range changes; geocoding improvements</li>
<li><strong>Weber:</strong> Received centerline update 8/28/2014: added new roads, road name and address range changes since last update on 6/24/2014; geocoding improvements</li>
</ul>
<p><span style="text-decoration: underline;">Blue Stakes of Utah Feedback:</span></p>
<ul>
<li><strong>Carbon:</strong> geocoding improvements</li>
<li><strong>Iron:</strong> geocoding improvements</li>
<li><strong>Salt Lake:</strong> geocoding improvements</li>
<li><strong>Summit:</strong> geocoding improvements</li>
<li><strong>Tooele:</strong> geocoding improvements</li>
<li><strong>Utah:</strong> geocoding improvements</li>
<li><strong>Washington:</strong> geocoding improvements</li>
</ul>
<p><span style="text-decoration: underline;">UDOT Route System:</span></p>
<ul>
<li>The DOT_F_MP (From Milepost) and DOT_T_MP (To Milepost) fields that store the milepost attributes of the UDOT state and federal routes in SGID10.Transportation.Roads were updated</li>
<li>The DOT_RTID field that stores UDOT's unique numeric route identifiers was updated</li>
</ul>
