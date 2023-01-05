#VM-Sentinel-Attack-Map
Security Analyst Project


Created this project to learn how to use SIEM on Azure.
Credit goes to Josh Makador for teaching this project.

API Key from https://ipgeolocation.io/

Custom PowerShell script was used to extract metadata from Windows Event Viewer, which was forwarded to a third-party API to determine geolocation data.

Log Analytics Workspace in Azure was configured to accept custom logs containing geographic information, including latitude, longitude, state/province, and country

Custom fields were configured in the Log Analytics Workspace with the aim of mapping geolocation data in Azure Sentinel

Azure Sentinel Workbook was configured to display global attack data, including RDP brute force attacks, on a world map based on physical location and number of attacks

Screenshots of World Map and Powershell scripts in folders
