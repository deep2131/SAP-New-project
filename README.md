# SAP-New-project
Filters only iFlows with version tag formats:

v1.1.2.ReadyForDeployment
v1.1.2-ReadyForDeployment
v1.1.2_ReadyForDeployment


Downloads using SAP CPI artifact version active by default.
Pushes downloaded iFlows to a GitHub feature branch.
Includes validations and SAP error capture for troubleshooting.

SAP’s Integration Flow API examples confirm that IntegrationDesigntimeArtifacts is used for integration flow operations and that /api/v1 is the service root URI for these calls.  SAP Community examples also show the same design-time artifact endpoint structure using Id and Version, commonly with Version='active'
