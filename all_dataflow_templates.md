# Power Automate Dataflow Connector Templates
In this [post] you can read about the new connector to:
* Refresh Power BI and Power Platform based on a trigger
* Trigger an action based on the completion of a dataflow refresh.

In this blog, we are going to discuss some use cases with corresponding templatrs, to quick-start the use of this connector. We are going to discuss the following templates:

Notifications:
* When you click on button, a dataflow refresh starts
* Send an email notification when a dataflow refresh status changes
* Send email notification on succes or failure of a dataflow
* When a dataflow refresh status changes, sends a Teams notification

Support tickets:
* When a dataflow refresh fails, send a message to service bus/ques/open support ticket
* When dataflow refresh took longer than 2 hours, open supprt ticket

Chain dataflows/Datasets
* Shen an analytical dataflow succeeds refreshing, trigger a standard dataflow (power platform)
* When a dataflow refresh succeeds, trigger a power BI dataset
* When a file in SharePoint gets updated, trigger a dataflow

Save dataflow meta-data
* When a dataflow refresh completes, save meta-data to Dataverse Table
* When a dataflow refresh completes, save meta-date to 
