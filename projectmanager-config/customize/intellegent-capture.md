# Intelligent Capture
## Project Manager Intelligent Capture Forms

* **Project Budget**. Record the project's budget and its budget currency.
* **Project Dates**. Record the planned Start and Finish dates for the project.
* **Project Details**. Capture the main details or description of the project.
* **Project Scope**. Capture the details that describe the scope of the project.
* **Project Status**. Select the status under which this project will be at once created. Options include Draft, Active, Completed, and Canceled.
* **Project Template**. Select the project template which contains a pre defined project configuration such as details, stakeholders, risks and more.
* **Project Type**. Set the type of Project which will be used. The list of available Types is governed by the Project Types you have defined and are currently marked as Active.

## Customized Forms
Using the intelligent capture designer, you can add in custom forms, then ask custom questions and in turn map, the answers to your custom fields on the project details view on your projects.

In your custom forms, use the custom question field id to set your mapping to the required custom field on your project details view.

Example of mapping to a date/time custom field below:

![Project Manager Custom Field Mapping](/_books/projectmanager-config/images/ic-custom-field-mapping.png)

The table below gives you the field types for each of the custom fields.

|Available Columns|Data Type/Capacity|Description|
|-|-|-|
|customA1 - customA5|VARCHAR/255 characters|VARCHAR custom fields a - o each suitable for holding up to 255 characters of any type.|
|customB1 - customB5|TEXT/unlimited*|TEXT custom fields p - t each suitable for holding large amounts of text characters of any type.|
|customC1 - customC5|DATETIME/a single date-time stamp|DATETIME custom fields 21 - 25 each suitable for holding a single date-time stamp (YYYY-MM-dd HH:mm:ss). These columns should ONLY be used in conjunction with a date-time picker.
|customD1 - customD5|INTEGER/any whole number|INTEGER custom fields 26 - 30 each suitable for holding whole numbers. When mapping to these columns, ensure the following RegEx is specified in your Custom field settings: [0-9]|

unlimited* - TEXT fields have a maximum capacity of 65000 characters.

More information on managing customized forms can be found [here](/esp-config/automation/customized-forms).

If you have mapped custom questions to the custom fields on the details of the project, remember to use the form designer to expose the custom fields to see any values which mapped to them, more info here

## Intelligent Capture Default
By default when Project Manager is installed, a new project Intellegent Capture is provided. This can be edited, and new ones added. To change which Intellegent Capture which is used for creating new projects, update the value in the following system setting

`app.com.hornbill.projectmanager.progressiveCapture.newProject`