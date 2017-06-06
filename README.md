# SCOrchHornbillIntegration
A collection of runbooks for Microsoft System Center Orchestrator 2012 R2, to demonstrate integration with the Hornbill Collaboration platform and Service Manager application.

## Installation
The file supplied is an export of a collection of runbooks, developed in SCOrch 2012 R2. This can be imported in to SCOrch by right-clicking on the Runbooks folder of your choice in the Orchestrator Runbook Designer, and click Import.

The runbooks use three global variables to identify the Hornbill instance and API key to use to invoke Hornbill API calls. These variables should be populated as so:

 - Hornbill\Hornbill API Key : This is the API key for the user account that should be used to perform the Hornbill API calls
 - Hornbill\Hornbill Instance ID : This is the (case sensitive) ID of your Hornbill instance (the yourinstancename part of your Hornbill URL: http://live.hornbill.com.yourinstancename)
 - Hornbill\Hornbill Instance Zone : This is the zone where your Hornbill instance resides:
    - eur - If your instance resides in the European zone
    - nam - If your instance resides in the North American zone

Please see the description against each imported runbook for more information about the runbook and APIs that they use. 
