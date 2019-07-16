# O-G---
title: "Gulf_OG_Wells_README"
author: "Laurie F. Muzzy"
date: "7/9/2019"
output:
  pdf_document: default
  html_document: default
---
METADATA for Gulf_OG_Wells:
Created for use by Healthy Gulf and Earthjustice employees, members, and associates. 
Purpose: to determine location and pertinent information about oil and gas well permits in the Gulf if Mexico.
Source data: https://www.data.boem.gov/Plans/Files/PlansRawData.zip
Definitions://www.data.boem.gov/Plans/Plans/FieldDefinitions.aspx


Attributes: 
Field Name	 Data Type	 Field Length	 Definition	 
BOTM_AREA_CODE	VARCHAR2	6	The designated abbreviation assigned to Outer Continental Shelf (OCS) geographical units for identification purposes and for use on maps and in data bases as applied to the bottomhole location of a well.
BOTM_BLOCK_NUM	VARCHAR2	18	Identifies a subdivision of an Official Protraction Diagram as applied to the subdivision containing the bottomhole location of a well.
BOTM_LEASE_NUM	VARCHAR2	21	The number assigned to the lease that contains the bottom location of a well.
PLAN_CTRL_CD	VARCHAR2	3	An indicator of the status of the plan application.
PLAN_CTRL_NUM	NUMBER	22	A number identifying the plan being submitted. This number is assigned by the Plans Unit.
PLAN_FNL_ACTN_CD	VARCHAR2	3	Indicates the final action was taken on a plan submittal.
PLAN_FNL_ACTN_DT	DATE	7	Date that final action was taken on a plan submittal.
PLAN_SITE_NAME	VARCHAR2	24	Name of Plan Site
PLAN_SITE_TYPE	VARCHAR2	9	Identifies the site as either a well or a structure site.
SITE_CANCEL_DT	DATE	7	The date approval to use a structure or well site designated in a plan is cancelled.
SURF_AREA_CODE	VARCHAR2	6	The indicator used to identify an area name.
SURF_BLOCK_NUM	VARCHAR2	18	Identifies a subdivision of an Official Protraction Diagram\ as applied to the subdivision containing the surface location of a well.
SURF_E_W_CODE	VARCHAR2	3	East/West descriptor that indicates the direction of a measurement from an identifiable line./Indicates whether the surface borehole location is measured from either the east (E) or west (W) block boundary.
SURF_E_W_DIST	NUMBER	22	East_West footage or distance that represents the length of a measurement from an identifiable line./The distance from the borehole surface location to either the east or west block boundary.
SURF_LATITUDE	NUMBER	22	The latitude value of a location in the borehole. A positive value denotes north. Angle subtended with equatorial plane by a perpendicular from a point on the surface of a spheriod.
SURF_LEASE_NUM	VARCHAR2	21	The number assigned to a lease by the regulatory agency having jurisdiction over mineral activity in the territory where the lease is located.
SURF_LONGITUDE	NUMBER	22	The longitude value of a location in a borehole. A positive value denotes east. Angle measured about the spheroid axis from a local prime meridian to the meridian through the point.
SURF_N_S_CODE	VARCHAR2	3	North/South descriptor that indicates the direction of a measurement from an identifiable line. /Indicates whether the surface borehole location is measured from the north (N) or south (S) block boundary.
SURF_N_S_DIST	NUMBER	22	North/South footage or distance that represents the length of a measurement from an identifiable line. /The distance from the borehole surface location to either the north or south block boundary.
SURF_PROJ_ZONE	VARCHAR2	9	Indicates the map projection system zone code for the surface X, Y coordinate location of the proposed well descibed in an Application for Permit to Drill (APD).
SURF_X_COORD_LOC	NUMBER	22	X coordinate for a surface location (east-west measurement).
SURF_Y_COORD_LOC	NUMBER	22	Y coordinate for a surface location (north-south measurement).
WATER_DEPTH	NUMBER	22	The depth of the water at a well/platform location from the water level to the mud line.

Questions we want to answer: 
Have locations of permitted wells moved into different areas in recent years?
Have there been more or fewer permits approved at certain periods of time? 
Where have recent permits been approved?
What might cause an approved permit to be cancelled?
...and other things
