Dataflows Power Automate Connector 
In this **[POST]** you can read about the new connector to:
* Trigger a flow when a dataflow refresh completes
* Take action to initiate a dataflow refresh

In this blog, we are going to discuss some use cases with corresponding templates, to quickstart the use of this connector. We are going to discuss the following templates:

Notifications:
* Send an email notification when a dataflow refresh status changes
* Send email notification on success or failure of a dataflow
* When a dataflow refresh status changes, sends a Teams notification

Support tickets:
* When a dataflow refresh fails, send a message to service bus queue to open a support ticket

Refresh Dataflows/Datasets sequentially:
* When you click on button, initiate a dataflow refresh
* When an analytical dataflow refresh succeeds, initiate a standard dataflow refresh
* When a dataflow refresh succeeds, initiate a Power BI dataset refresh
* When a file in SharePoint gets updated, initiate a dataflow refresh

Save dataflow refresh meta-data:
* When a dataflow refresh completes, save meta-data to Dataverse Table
* When a dataflow refresh completes, save meta-data to Exel online
* When a dataflow refresh completes, save meta-data to Power BI Streaming dataset

Tutorial: Create a Dataflow Monitoring Dashboard

![An example of folder structure](images/dashboard.PNG)


## Downloads:
[Download excel .pbit file](https://github.com/miquelladeboer/dataflowdiagnostics/blob/master/diagnostics-template-excel.pbit),
[Download Dataverse .pbit file](https://github.com/miquelladeboer/dataflowdiagnostics/blob/master/diagnostics-template-cds.pbit),
[Dowload .xlsx file](https://github.com/miquelladeboer/dataflowdiagnostics/blob/master/dataflow_monitoring.xlsx)