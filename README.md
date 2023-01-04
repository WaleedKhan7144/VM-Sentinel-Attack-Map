# Failed-RDP-World-Map
Security Analyst Project


Created this project to learn how to use SIEM on Azure.

Used custom PowerShell script to extract metadata from Windows Event Viewer to be forwarded to third-party API to derive geolocation data

API Key from https://ipgeolocation.io/
To convert the metadata of failed logins (IP addresses) into geographic locations

Configured Log Analytics Workspace in Azure to ingest custom logs containing geographic information (latitude, longitude, state/province, and country)

Configured custom fields in Log Analytics Workspace with the intent of mapping geo data in Azure Sentinel

Configured Azure Sentinel (Microsoft’s cloud SIEM) workbook to display global attack data (RDP brute force) on a world map according to physical location and magnitude of attacks
Screenshots of World Map and Powershell scripts in folders
