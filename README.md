# arcgis-osm-editor

ArcGIS Editor for OpenStreetMap - Welcome!

ArcGIS Editor for OpenStreetMap is a toolset for GIS users to access and contribute to OpenStreetMap through their ArcGIS Desktop or Server environment.  Learn more at [the ArcGIS Editor for OSM wiki page](https://github.com/Esri/arcgis-osm-editor/wiki).

## Features
* Download data from OSM into a file geodatabase - get data from the current extent or load from an .osm file
* Create your own planet (.osm) files
* Edit OSM data in ArcGIS
* Upload edits back to OSM
* Create routing networks from OSM data
* Create custom feature services based on OSM data

## Download Instructions
1. You can download the ArcGIS Editor for OSM Desktop setup from arcgis.com at the following links:
a) [ArcGIS Editor for OpenStreetMap, 10.2 and 10.2.1] (http://www.arcgis.com/home/item.html?id=16970017f81349548d0a9eead0ebba39)
b) [ArcGIS Editor for OpenStreetMap, 10.1] (http://www.arcgis.com/home/item.html?id=6a2a3c3cece749558393d4e80241ef51)
c) [ArcGIS Editor for OpenStreetMap, 10.0] (http://www.arcgis.com/home/item.html?id=620e5a4c4e3d4125aed3f66110870257)


2. Once downloaded, install as described in the http://github.com/Esri/arcgis-osm-editor/wiki/System-requirements%2C-installation%2C-%26-working-with-the-code documentation.
	
3. Read documentation at http://github.com/Esri/arcgis-osm-editor/wiki/Documentation on how to use the tools

4. If you want to work with the code:
	
	a) Fork and then clone the repo. 
	
	b) See the documentation on working with the code ("Working with the code" section of this topic: http://github.com/Esri/arcgis-osm-editor/wiki/System-requirements,-installation,-&-working-with-the-code).
	
	c) *If you want to work with the Server Component code, then do the following*: 
		1) Please read the web.config to run the server and make sure all paths are correct.
		2) Please make sure you install Visual Studio 2010 Service Pack 1. Best way to know you got the latest of Visual Studio is to install it from here: http://www.microsoft.com/web/gallery/install.aspx?appid=VWDorVS2010SP1Pack
		3) Make sure you have ArcGIS 10.1 installed to run the Server part.
		4) The application needs a SDE connection.You can change in the web.config where the sde file is:
    	 	 add key="DatabaseConnection" value="C:\Data\OSM\Mxds\osmdevsde.sde"

## Requirements

* An OpenStreetMap login (create at https://www.openstreetmap.org/user/new)
* ArcGIS for Desktop 10.1 (Desktop Component)
* ArcGIS Server 10.1, ArcSDE 10.1, and IIS (Server Component)
* Visual Studio 2010 (if you're working with the code)

## Resources

* [OpenStreetMap](http://www.openstreetmap.org)
* [OpenStreetMap wiki] (http://wiki.openstreetmap.org/wiki/ArcGIS_Editor_for_OSM)

## Issues

Find a bug or want to request a new feature?  Please let us know by submitting an issue.

## Contributing

Anyone and everyone is welcome to contribute. 

## Licensing
Copyright 2012 Esri

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

A copy of the license is available in the repository's [license.txt]( https://github.com/Esri/arcgis-osm-editor/blob/master/license.txt) file.

[](Esri Tags: ArcGIS Editor OpenStreetMap)
[](Esri Language: C-Sharp)
