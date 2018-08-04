# IEA-SITEPROVISIONER
2018 08 04: code repo for customer projects...
#IEA - Office 365 - SharePoint Online - Site Provisioning Solution # 
## OVERVIEW ##
THe Solution is a Microsoft-Flow-based solution for programmatically provisioning new websites in customer's o365 SharePoint Online environment.
A simple HTML button is displayed on a main landing page. 
Clicking the button opens a pop-up window with a simple form. 
Filling the form and clicking "CreateSite" form button triggers MS Flows (possibly multiple).
- One MSFLow (or MSF Action) provisions the new SPWeb; 
- One MSFlow (or MSF Action) creates an SPItem in an existing ProjectSiteInfo SPList

## Solution Components ##
The following components comprise The Solution...
1. BUTTON: btnCreateProjectSite 
2. BUTTON-CLICK-HANDLER: ? (actualy the TRIGGER of an MSFLOW - see below...)
3. LIST: PROJECT_SITES_INFO
4. LIST: PROJECT_SITE_COLLECTIONS_INFO
5. FLOW: btnCreateProjectSite_Click_Handler
