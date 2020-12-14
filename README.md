Dataflows Power Automate Connector 
In this **[POST]** you can read about the new connector to:
* Trigger a flow when a dataflow refresh completes
* Take action to initiate a dataflow refresh

In this blog, we are going to discuss some use cases with corresponding templates, to quickstart the use of this connector. We are going to discuss the following templates:

[Notifications](https://github.com/miquelladeboer/dataflowdiagnostics/blob/master/send%20notification%20when%20dataflow%20refresh%20completes.md):
* Send an email notification when a dataflow refresh status changes
* Send email notification on success or failure of a dataflow
* When a dataflow refresh status changes, sends a Teams notification

[Support tickets](https://github.com/miquelladeboer/dataflowdiagnostics/blob/master/open%20support%20ticket%20when%20dataflow%20refresh%20completes.md):
* When a dataflow refresh fails, send a message to service bus queue to open a support ticket

[Refresh Dataflows/Datasets sequentially](https://github.com/miquelladeboer/dataflowdiagnostics/blob/master/trigger%20dataflows%20and%20power%20bi%20dataset%20sequentially.md):
* When you click on button, initiate a dataflow refresh
* When an analytical dataflow refresh succeeds, initiate a standard dataflow refresh
* When a dataflow refresh succeeds, initiate a Power BI dataset refresh
* When a file in SharePoint gets updated, initiate a dataflow refresh

Save dataflow refresh meta-data:
* [When a dataflow refresh completes, save meta-data to Dataverse Table](https://github.com/miquelladeboer/dataflowdiagnostics/blob/master/load%20data%20into%20dataverse%20table.md)
* [When a dataflow refresh completes, save meta-data to Exel online](https://github.com/miquelladeboer/dataflowdiagnostics/blob/master/load%20data%20into%20excel%20online.md)
* [When a dataflow refresh completes, save meta-data to Power BI Streaming dataset](https://github.com/miquelladeboer/dataflowdiagnostics/blob/master/load%20data%20into%20power%20bi%20dataset.md)

Tutorial: Create a Dataflow Monitoring Dashboard

![An example of folder structure](images/dashboard.PNG)


## Downloads:
[Download excel .pbit file](https://github.com/miquelladeboer/dataflowdiagnostics/blob/master/diagnostics-template-excel.pbit),
[Download Dataverse .pbit file](https://github.com/miquelladeboer/dataflowdiagnostics/blob/master/diagnostics-template-cds.pbit),
[Dowload .xlsx file](https://github.com/miquelladeboer/dataflowdiagnostics/blob/master/dataflow_monitoring.xlsx)