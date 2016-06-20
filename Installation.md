This page includes all of the tasks that are required to set up the application, getting you from downloading the application to the processes detailed in the Workflows section. This will include:

Publishing Feature Services
Configuring Geoevent Extension for ArcGIS Server
Publishing Web Map and Dashboard
Testing the Installation

Before you start publishing services, download the template and unzip it to your local machine. The folder you unzip the template into is refered to a TemplateInstall in all the setup steps.

Publish Feature Services
The Movement Analysis service contains all the layers for analysis and visualization layer. Select a deployment method (ArcGIS for Server or ArcGIS Online hosted service) and follow the steps below to publish the required service for the Damage Collector map.

Movement Analysis Service
Use the MovementAnalysis.mxd found in TemplateInstall/Maps to publish the Movement Analysis map service. Complete the following steps:

Publish the map as a hosted feature layer using ArcGIS Online or as a feature service using ArcGIS for Server.
Sign in to your ArcGIS Online organization.

Note:If you published the service with ArcGIS for Server, you'll have to add the service to your ArcGIS Online organization before completing the remaining steps.

Browse to the service and edit the item details:
Title:MovementAnalysis
Thumbnail image: 
Summary: The movement analysis service presents a real time picture about movement of individuals or groups.
Description: The movement analysis service is used to depict derived information about the movement of individuals or group. The information in this service is the result of real-time analysis of patterns of movement. This information can be used to visualize and understand the patterns of activity or be used to alert for activity around monitored locations. This service includes several key layers which are used to normalize complex movement data and prepare it for visualization or analysis. This include:
Stay Locations – Point and Polygon layers which represent any location where a monitored individual spends any amount of time.
Pattern Locations – Areas created based on frequently used stay locations. These can be derived from statistical methods or just observed activity.
Suspicious Locations – Areas which have been defined based on the knowledge of the individual or group and include areas where they are likely to frequent. Examples of suspicious locations include:
Meeting Locations
Suspect Home and Workflow Locations
Public Venues that a suspect is known to frequent
Tags: MovementAnalysis, FeatureServer, Movement, Patterns, POL, Lifestyle, Stay Location, Crossing Point, Transits, Suspicious, Meeting, Suspect, Monitoring
Editing properties: Enable editing and allows editors to add, update, and delete features.
