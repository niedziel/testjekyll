---
layout:  default
title: Page 1
---

#Welcome to ServiceNow!
In this course, you will develop your first application on ServiceNow's powerful application platform.  The Innovate application you will create allows employee to make suggestions that are directed to the appropriate organization within the company or organization.  The suggestions include process improvements, teambuilding activities, and cost cutting.
As with any application, the key to success is to design the application before starting to build the application.
**Requirements**
* Users must be able to submit ideas for innovations to processes, teambuilding, and cost savings so the company can benefit from their suggestions.* Administrators must be able to determine from the records if the innovation was implemented or not so a determination can be made about total cost savings.* Administrators must be able to filter records by innovation type, keywords, and implementation status so they can see which categories are receiving the most suggestions.
**Data Model**

Field Name			| Data Type	| Notes
----------			| ----------	| ------
Number					| String		| Unique record string.  Combination of letters and numbers
Created				| Date/Time	| When the record was created.Updated				| Date/Time	| Time of most recent record update.Idea type				| Choice		| Cost savings, Team building, Process improvement
Idea Implemented		| True/False	| When selected indicates that the innovation was implemented.Short Description	|	String		| A brief description of the innovation.  125 character maxDescription			| String		| Detailed description of the innovation. 1k character max