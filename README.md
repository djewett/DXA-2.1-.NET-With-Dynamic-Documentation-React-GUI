# DXA-2.1-.NET-With-Dynamic-Documentation-React-GUI
This is a working .NET version of DXA 2.1 with the Core Module installed and all preliminary issues resolved. In addition, this repository is also set up to run the Dynamic Documentation DXA module for Tridion Docs. The intention is that this should run out-of-the-box with minimal configurations (just discovery service URL and credentials, and update the main project's startup URL to match Topology Manager BaseUrls). This repository was created by first building the DXA web application with core module:

https://github.com/djewett/DXA-2.1-.NET-With-Core-Module

Then by installing the Dynamic Documentation module with React GUI, by following the steps here:

https://docs.sdl.com/LiveContent/web/pub.xql?action=home&pub=SDL%20DXA-v11&lang=en-US#docid=GUID-897D2A66-9B64-41D7-A72A-9B28435005B8&addHistory=true&query=installing%2520dynamic%2520documentation&scope=&tid=5e5a6be1-e605-41df-9b2b-2848646fef68&filename=GUID-897D2A66-9B64-41D7-A72A-9B28435005B8.xml&resource=&inner_id=&toc=false&eventType=lcContent.loadDocGUID-897D2A66-9B64-41D7-A72A-9B28435005B8&url=/LiveContent/web/search.xql%3Fc%3Dt%26pub%3DSDL+DXA-v11%26lang%3Den-US%26action%3Dsearch%26query%3Dinstalling%2520dynamic%2520documentation&sid=lcSearch.runSearch1558328004324&currentQuery=installing%2520dynamic%2520documentation&currentScope=

i.e.
Get the module from:
https://docs.sdl.com/DXA/2.1/Modules/Download/
Then run:
web-install.ps1 -distDestination "C:\inetpub\wwwroot\mysite"
(replacing mysite by the folder of the DXA Site project folder)
