# ISE-OpenAPI-Postman-Collection

This repo contains the Postman collection for the ISE OpenAPI APIs. 

## Postman

[Postman](https://www.postman.com/) is a popular collaboration platform for learning, development, and testing of REST APIs.

## Cisco ISE API Service

Cisco ISE allows API access to manage Cisco ISE nodes through two sets of API formats: External Restful Services (ERS) APIs & Open APIs.  ERS and Open APIs are REST APIs based on HTTPS.  From Cisco ISE Release 3.1, newer APIs are available in the Open API format.

## Resources

[ISE API Documentation](https://developer.cisco.com/docs/identity-services-engine/latest/)  
Complete documentation for the APIs  

[ISE @ Cisco DevNet](https://developer.cisco.com/site/ise/)  
Site for ISE APIs, sample code, and sandboxes to learn and play  

[ERS, MNT, pxGRID APIs](https://github.com/CiscoISE/postman)  
GitHub repository containing the Postman collections for the ISE ERS, MNT, and pxGRID APIs  


## Installing the Postman Collection

In Postman, under Collections, choose Import. You may then import via drag-and-drop of a downloaded collection file (*.postman_collection.json) or with a URL of a collection file in the GitHub repository.

## Enable API Service in ISE

In ISE, API services are disabled by default.  Follow these steps to enable API services for ERS and/or Open API.

1. In the Cisco ISE GUI, click the Menu icon and choose Administration > System > Settings > API Settings > API Service Settings.
2. In the API Service Settings for Primary Administration Node area, click the ERS (Read/Write) toggle button to enable ERS and/or click the Open API (Read/Write) toggle button to enable API services on the PAN.
3. In the API Service Settings for All Other Nodes area, click the ERS (Read) toggle button to enable the ERS on all other nodes, and/or click the Open API (Read) toggle button to enable Open API service.
   
