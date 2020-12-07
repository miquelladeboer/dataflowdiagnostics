# Dataflow Power Automate Connector 
In this **[POST]** you can read about the new connector to:
* Refresh Power BI and Power Platform dataflows based on a trigger
* Trigger an action based on the completion of a dataflow refresh.

In this blog, we are going to discuss some use cases with corresponding templatrs, to quick-start the use of this connector. We are going to discuss the following templates:

Notifications:
* Send an email notification when a dataflow refresh status changes
* Send email notification on succes or failure of a dataflow
* When a dataflow refresh status changes, sends a Teams notification

Support tickets:
* When a dataflow refresh fails, send a message to service bus queue to open a support ticket


Trigger Dataflows/Datasets sequentially
* When you click on button, a dataflow refresh starts
* When an analytical dataflow succeeds refreshing, trigger a standard dataflow
* When a dataflow refresh succeeds, trigger a power BI dataset
* When a file in SharePoint gets updated, trigger a dataflow

[See some examples here](https://miquelladeboer.github.io/dataflowdiagnostics/all_dataflow_templates.html)

Save dataflow meta-data
* [When a dataflow refresh completes, save meta-data to Dataverse Table](https://miquelladeboer.github.io/dataflowdiagnostics/dataflow_monitoring_with_data_in_dataverse.html)
* [When a dataflow refresh completes, save meta-data to Exel online](https://miquelladeboer.github.io/dataflowdiagnostics/dataflow_monitoring_with_excel.html)
* [When a dataflow refresh completes, save meta-data to Power BI Streaming dataset](https://miquelladeboer.github.io/dataflowdiagnostics/dataflow_monitoring_with_powerbi_streaming_dataset.html)

