# HR CRM

HR CRM is a PowerApps application designed to facilitate Human Resources management tasks. It caters to two distinct security roles: employees and HR personnel, offering tailored features for each.

## Description

**Employees** can log worked hours into a weekly timesheet and create leave requests.<br>
The screens available for them are:
- A dashboard with two charts: a line chart with the leave requests for the current year and a column chart with the hours worked on each project for the current month;
- A list where he can see all his leave requests and a screen to create a new one;
- A calendar where he can log his hours onto the timesheet on the projects he is assigned.

**HR** can manage projects and employees and view their timesheets. They can also view the leave requests and validate the ones where they are assigned as approvers.<br>
The screens available for them are:
- A dashboard with information like the number of projects, tasks, and employees and two charts: a pie chart with the hours worked on each project and a column chart with the number of leaves, both of them for a selected date;
- A list of the leave requests he has to validate and all the requests created. They can open one to view the details and also approve/reject it;
- A list of all the projects and the employees assigned to them;
- A gallery of all the employees and the possibility to view, for each of them, their details and their timesheets.

  #### Other features
- Some of the components (DetailsList, CommandBar, Pivot, Persona) are from the Creator Kit library.
- HR can export as a PDF a selected timesheet for a specific user. This is done with the help of an instant Power Automate workflow that uses an existing connector of the publisher CraftMyPDF.
- The project also has a custom connector used to call the Nager.Date API to retrieve the public holidays and display them in the calendar.
