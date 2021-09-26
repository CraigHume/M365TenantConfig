# M365TenantConfig

PowerShell Microsoft.Graph scipts to backup configuration settings to JSON files.    To be run as a scheduled task.   Change detection mechanism is based on comparing last known good against present values.
If file contents don't match, details are recorded in both file share used by script, as well as in form of SharePoint list items in M365 Automation.  There is on channel per workload.
