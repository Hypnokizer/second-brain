# Developing Your Own Mapped ALI
Dave Eaton, Maricopa Region 911

350 call taking positions

Web maps just request data. We give a location and the server returns the data.

GraniteDS *(Granite Data Services)* - library used to push ALI data

Adobe Local Shared Object - used to identify a workstation/position

* They update the map cache, with no shapefiles at the client!
* ALI and maps are available from (2) network centers
* YAJSW *(Yet Another Java Service Wrapper)* - wrapping a java service as a Windows service
* Apache Tomcat 7
* ArcGIS Server
* Google Chrome - most resilient browser


## Next Steps

* The production environment *(moving forward)* will need to use the Javascript client
* new push methods; instead of Apache Tomcat, Node.js and websockets
* new position naming methods; cookies


**They have the ability to send a broadcast message to all the PSAPs in the jurisdiction.**

(12) man technical team to administrate it.