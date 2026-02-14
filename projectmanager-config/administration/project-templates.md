---
url: https://wiki.hornbill.com/index.php?title=Project_Templates
title: Project Templates
---
# Project Templates

The Project Templates allow you to define re-usable settings that can be used to quickly create new projects. Project Templates can be invoked when raising a new project via Intelligent Capture, and or when raising a Project through a Business Process and the Project Manager options available in the Hornbill Integration Bridge (iBridge)

## Manage Project Templates

From the Project Template Landing page, you can search, view, edit and create new Project Templates

* **Search** \- Find project templates
* **+** \- Create a new project template
* **Remove All** \- Permanently remove all project templates

### Project Template List

View all existing project templates, including name, description, status and last modified by

* **Copy** \- Copy an existing project template and save it with a new name
* **Edit** \- Open an existing project template to edit it's content
* **Delete** \- Permanently remove the the project template

## Project Template Options

The options that can be pre-defined include the following

* **Template Name**

This will be the name of the template which can be selected when using Project Template form in Intelligent Capture

* **Description**

This describes the template and how or where it might be used.

* **Status**

The starting status for the project

* **Details**

Optionally add project name, description, quality statement, scope, type, supporting business process, type and budget, as well as the currency for any costs associated to the project

* **Logic**

Configure project logic settings when creating a project from a project template. Individual project managers have the rights to amend this once the project has been created from the template, should they wish to enable or disable settings for specific projects.

* **Visibility**

Configure which of the main project tabs, and smaller tabs will be visible to project members when creating a project from a project template. Individual project managers have the rights to amend this once the project has been created from the template, should they wish to enable or disable tabs for specific projects.

* **Milestones**

Add any standard milestones that would be common to a project. If you are following PMP or Prince2 you may want to pre-establish some of the typical milestones used in these structure project methodologies.

* Set due dates relative to the project start date
* Decide if the Project Manager should receive a notification when the milestone is completed - Off by default, this default setting can be managed under the following app setting: **app.com.hornbill.projectmanager.milestones.notification.notifyProjectManagerOnCompletion**

* **Tasks**

Create common tasks that would be required in this project, define relationships to milestones and or other tasks and set start and end dates relative to the project creation date.

* Owned By: Select a named project stakeholder, or use the select box to have the Owned by be assigned automatically to the user who is assigned the Project Manager Role for the Project where this template is used
* Assigned To: Select a named project stakeholder, or use the select box to have the Assigned To be assigned automatically to the user who is assigned the Project Manager Role for the Project where this template is used
* Decide if the Project Manager should receive a notification when the task is completed - Off by default, this default setting can be managed under the following app setting: **app.com.hornbill.projectmanager.projectTasks.notification.notifyProjectManagerOnCompletion**

* **Costs**

Create any default costs

* **Risks**

Create any default Risks

* **Stakeholders**

Add stake holders, their roles and hourly rates. Useful if you have anyone that is commonly involved in all projects.

The Project Manager stakeholder role grants the stakeholder some additional capability when working with a Project. This is as follows; when creating a new project task, the owner defaults to the project manager. Only the project manager can take gantt chart snapshots. The other available stakeholder roles don't offer any special capability to the user.

* **Links**

Add useful clickable links to your project.

* **Roles**

Define the permissions the different roles assigned to users in a project raised against a project template need.

* Assign view, edit, add and delete permissions against each project feature per role
* The configured permissions will be applied to the project roles on project creation. Users assigned a project role, will have their permissions governed by what is configured in this section

* The Project Manager of a project created from a project template will be able to edit and amend the role permissions from the **Project Settings** in the side panel of a project created from a project template

* Project Template Roles do not replace project manager security roles, they simply enable more granular controls on both projects raised against a project template, and or individual projects.
  
:::info
Once you have defined project templates, you can invoke these by adding the **Project Template** form to your Intelligent Capture flow which is followed when raising and initiating new projects.
:::
