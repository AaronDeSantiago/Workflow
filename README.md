# Workflow

## About the Project

This is a time invester manager for **software development**. Record in a simple and fast way the time that is currently being invested in each project. Share through reports this information with clients, superiors, or colleagues.

> Currently an MVP version is being developed so things are staying simple.

## Customers

A customer includes the contact information and is used to group separate projects for a single person or organization. The application allows the user to administrate the catalog of customers.

## Projects

Projects are grouped by customer and are the main unit for the system. Name your project and capture important information like starting date, budget, deadlines, and create activity records.

Records contain the following information:
* Time invested on the activity.
* Description of the activity.
* Category to help group the activities in the same project. These categories autocomplete to help use the same naming within the project.
* Date of the activity – editable in case this activity is being recorded from a different date.
* Tag to create another layer of grouping, tags are different from categories because this are predefined in the system (error, coding, meeting).
* Indicator to let the system know if this activity should count towards the available hours for the project.

## Reports

Summary of the activities performed during a certain timeframe deciding what amount of information should be displayed, specify the columns. Depending on the amount of information some of the rows will be grouped on a single one. 

# Technology 

SPA Application developed with Next.js with a PHP backend API and a MySQL database for saving all the information.