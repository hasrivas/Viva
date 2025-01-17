---
title: Use Viva Glint's People page to view employee information
description: "The People page on the dashboard allows Viva Glint admins to view employee attributes, manage permissions and roles, and deactivate employees."
ms.author: SarahBerg
author: SarahAnneBerg
manager: pamgreen
audience: admin
f1.keywords: NOCSH
keywords: viva strengths and opportunities
ms.collection:  
- m365initiative-viva
- selfserve 
search.appverid: MET150 
ms.topic: article
ms.service: viva
ms.subservice: viva-glint
ms.localizationpriority: high pri
ms.date: 04/28/2023
---

# Use Viva Glint's People page to view employee information

The People page functionality allows admins to view employee attributes, manage permissions and roles, and deactivate employees. 

The  **People** section is accessed from the  **Employees** section on the admin dashboard and allows admins to: 

- View individual employee data  
- Manage positions by assigning User Roles 
- Manage employment status 
- Import an employee file 
- Export a file of active employees 

## Use the filter feature   

Employees are filtered by active/inactive status, login status, and User Role. 

### All People  

A count of present and past employees, listed by: 

- Active: Working within your organization presently 
- Inactive: No longer work within your organization or are currently on leave 

### Login Enabled 

A count of employees who may be available to participate in a survey, sorted by: 

- Not Invited: Employees who don't have login access; the employee may be inactive or currently suspended. Suspended employees can't log in to the dashboard, but they may still take surveys and retain any assigned user roles. All historical data for this user will be preserved. 
- Pending: Employee has been invited but has not yet set up a password, or the employee has been moved to a new User Role and won't become active until a certain date. 
- Active: Employee has login access. 

### User Roles 

A count of company admins, managers, Human Resource Business Partners (HRBPs), and HR business partners listed by User Roles. 

## Find information on a specific person 

Use one of the two following methods: 

- Begin to type the name of the employee in the search bar. When the name appears, select the name.   
- Scroll down the alphabetized list of names, but with hundreds or thousands of employees, that method won't be as efficient! 

For each employee, the following information is visible: 

- Employee Name: Editable by admin by selecting the pencil symbol. 
- Email Address: Editable by admin by selecting the pencil symbol. 
- Employee ID: Not editable. 
- Manager Hierarchy: The organization’s highest-ranking employee (generally the CEO) is listed first. The hierarchy progresses downward, following the organizational chart flow, ending with the employee’s immediate manager. Not editable. 
- Login Access: Determines if a user has login access. Not editable. 
- User Role(s): Determines what data and people for whom this user has visibility. Editable by selecting the pencil symbol. 
- Attributes and hierarchies (aside from the primary hierarchy, usually Manager): As defined in your organization’s latest Employee Data File. The Attributes section of an individual’s People page will always include required attributes (i.e., Employee ID, birthdate, hire date) and then customized attributes, as defined in Employee Data File. 

For employees with User Roles in addition to Active Employee, the following editable information will also appear: 

- Focus Area Access: Defines which people's data this user will see in Focus Area reports. Editable by selecting the pencil symbol.  
- Survey Access: Defines which people's data this user can see in selected survey programs. Editable by selecting the pencil symbol.

>[!CAUTION]
> Viewing and exporting raw data are governed by Microsoft rules protecting employee confidentiality. Review the guidance on [raw data exports](https://go.microsoft.com/fwlink/?linkid=2239587) within our Security and Privacy documents.

## Use the Login As function 

The Login As functionality allows you to open your Viva Glint program as if you were another employee. This functionality is helpful when wanting to view another User Role’s dashboard - typically a manager - and allows you to import their attributes information. 

**To log in as another person**: 

1. Locate the person you want to log in as and open their page by hovering over and selecting the name. 

1. Select  **Login As**. 

1. The dashboard indicates “You're logged in as  `<other person name>`." 

To return to your own account, select  **Return to your account**. 

## Use the Actions function 

The Actions button dropdown menu allows you to reset passwords and send surveys.

### Reset Password 

An email is sent to the employee’s email address with instructions for password reset.

### Send Survey 

You can send a survey to one employee (manually) from the People page. Use the Actions button and then  **Send Survey**. 

- Enabled and live surveys are displayed. Select the survey to send.  

   > [!NOTE]
   >A survey will not appear if it is not enabled or live. Go back into the program to re-enable or change the date of the survey, noting that it will take a few minutes for a survey to become live. 

- Select  **Send**.   

## Import your Employee Data File 

Use the  **Import**  button on the People page to import a *.csv* (UTF-8) or an *xlxs* to update employee lists and details - recommended prior to a launch. Customers who manually import employee data can also use this feature. 

Follow the on-screen guidance for uploading the file and then select  **Import File**. 

   > [!NOTE]
   >If you upload a user file during a live survey, employee information will not be altered for that survey. 


## Export an Active Employees report 

To make changes to an employee file, it's often easier to start with what's in the system first, so exporting from within the system, making changes, and then reimporting can occur beginning with the Export feature. 

Follow the on-screen guidance and then select  **Export**. 