# 1 Introduction

We appreciate your interest in ACL Digital's Workforce Scheduler. This document will help you understand the planner and its navigation. The Workforce Scheduler automates the rostering process thus saving people's time. Using advanced AI algorithms, the roster planner considers the business rules and employee preferences to propose an optimized roster plan for a period ranging from 1 month to 3 months.

Some of the features of the Workforce Scheduler are:

<div style="background-color: #DAE3F3;border:2px solid black; width: 320px;padding: 10px; border-radius: 1px; margin: 20px";

* Leverage industry-standard business rules
* Enure equal distribution of night shifts
* Customize the look and feel of the roster 
</div>

<div style="background-color: #DAE3F3;border:2px solid black; width: 321px;padding: 10px; border-radius: 1px;margin: 20px";"
   
*	Revise roster for last-minute changes 
*	Improve roster based on AI’s feedback 
*	Previous rosters can serve as input reports 
</div>

<div style="background-color: #DAE3F3;border:2px solid black; width: 321px;padding: 10px; border-radius: 1px;margin: 20px";"

* Use visual check for quick inspection.
* Analyse roster with user-friendly reports
</div>

<div style="background-color: #DAE3F3;border:2px solid black; width: 321px;padding: 10px; border-radius: 1px;margin: 20px";"

* Communicate roster with calendar invite
* Receive training from our experts 
</div>

<!--- End of Section 1 Introduction -->

# 2 Access Workforce Scheduler

Open the link in the Workforce Scheduler Team's welcome email to access the Workforce Scheduler application.
The username is the email id. The system admin provides the initial password.


![](https://sapschedular.blob.core.windows.net/wfs/wfs/Quick%20Start%20Guide%20-%20WFS/Images/Image%201_Login%20Page.png "Login Page")
***Image 1: Login Page***

In case of any issues or problems while logging in, reach out to the support team for assistance at wfssupport@acldigital.com

<!--- End of Section 2 Access Workforce Scheduler -->

# 3 User Profile 
The Workforce Scheduler application supports two User Profiles, Company Admin and Roster Planner.

## 3.1 Company Admin
The Company Admin manages all aspects of the company assigned to them. Company Admin has full access to all branches, teams, and user data.
The Company Admin can perform any task related to company management, including:
>
*	Creating and editing branches
*	Creating and managing teams within branches
*	Creating and editing team schedules
*	Viewing team reports and analysis

![](https://sapschedular.blob.core.windows.net/wfs/wfs/Quick%20Start%20Guide%20-%20WFS/Images/Image%202_Landing%20page%20for%20Company%20Admin.png "Landing page for Company Admin")
***Image 2: Landing page for Company Admin***

Upon login, the Company Admin will see a landing page focused on the entire company.
For detailed information on the functions of each tab on the company page, refer to [Section 4 Workforce Scheduler Layout](https://github.com/jaiacl/Workforce-Scheduler-User-Mnual/blob/main/UserManual_1.md#4-workforce-scheduler-layout).


## 3.2 Roster Planner 
The Roster Planner manages the schedules and rosters for teams assigned to them, as well as perform tasks such as:


* Creating and editing branches
* Viewing information about their assigned teams (employees, skills, leaves)
* Creating and editing team schedules
* Viewing team reports and analysis


![](https://sapschedular.blob.core.windows.net/wfs/wfs/Quick%20Start%20Guide%20-%20WFS/Images/Image%203_Landing%20page%20for%20Roster%20Planner.png "Landing page for Roster Planner")
***Image 3: Landing page for Roster Planner***

When the roster planner logs in, they land on a dedicated page focused on the team.
For detailed information on the functions of each tab on the planner page, refer to [Section 4 Workforce Scheduler Layout](https://github.com/jaiacl/Workforce-Scheduler-User-Mnual/blob/main/UserManual_1.md#4-workforce-scheduler-layout).
, refer to Section 4 Workforce Scheduler Layout.

<div style="background-color: #DAE3F3;;border:2px solid black; width: 500px;padding: 1px; border-radius: 1px; margin: 20px";

<p><b>If the user is assigned to both Company Admin and Roster Planner roles, the user will be logged in as Company Admin.</b></p>
</div>


<!--- End of Section 3 User Profile   -->

# 4 Workforce Scheduler Layout 
The chart illustrates the Workforce Scheduler application in a glance.

![](https://sapschedular.blob.core.windows.net/wfs/wfs/Quick%20Start%20Guide%20-%20WFS/Images/Image%204_Workforce%20Scheduler%20Layout.png "Workforce Scheduler Layout")

***Image 4: Workforce Scheduler Layout***

## 4.1 Company
The Company is the container for all the branches and teams in the application.

![](https://sapschedular.blob.core.windows.net/wfs/wfs/Quick%20Start%20Guide%20-%20WFS/Images/Image%205_Company%20screen.png "Company screen")
***Image 5: Company Screen***

The support team will manage the initial setup of the company. Once the company is set up, the branches will be created.

## 4.2 Branch
In the Branch screen, the planner can create Teams. Apart from teams, Holiday calendars are created which would apply to all the teams associated in the branch.

![](https://sapschedular.blob.core.windows.net/wfs/wfs/Quick%20Start%20Guide%20-%20WFS/Images/Image%206_Branch%20screen.png "Branch screen")
***Image 6: Branch Screen***


## 4.3 Holiday
Each Holiday List contains the list of holidays for a given year.

![](https://sapschedular.blob.core.windows.net/wfs/wfs/Quick%20Start%20Guide%20-%20WFS/Images/mage%207_Holiday%20List%20screen.png "Holiday List Screen")

***Image 7: Holiday List Screen***

<div style="background-color: #DAE3F3;;border:2px solid black; width: 500px;padding: 1px; border-radius: 1px; margin: 20px";

<p><b>Only one Holiday List can be assigned for a given year.</b></p>
</div>

![](https://sapschedular.blob.core.windows.net/wfs/wfs/Quick%20Start%20Guide%20-%20WFS/Images/Image%208_Holiday%20screen.png "Holiday Screen")***Image 8: Holiday Screen***


## 4.4 Team
The Planner generates rosters in the team screen of the application.

![](https://sapschedular.blob.core.windows.net/wfs/wfs/Quick%20Start%20Guide%20-%20WFS/Images/Image%209_Planner%20Screen.png "Planner Screen")

***Image 9: Planner Screen***

>>1. The **Planner Calendar** depicts the calendar view with the assigned shift to each employee. The generated Roster is analysed in the Planner Analysis page. The exceptions to the business rules are available in the Planner Screen.
2. The **Employees** section includes the employees listing, their Leave plan and Skills.
3.	In the **Shifts** section, Shifts and Shift Groups are created. These shifts are assigned to Employees.
4.	In the **Constraints** section, various restrictions are configured such as the required number of Working Days, Weekly Offs, and Shifts to be assigned to the Employees.
5.	All the required configurations for the Roster generation can be adjusted in the **Settings** section, including the visual appearance of the Roster and other highlights such as Alerts.
6.	The **Filter** section is used to filter out the Employees based on *Gender, Join Date, Exit Date, and Skills* and group them accordingly.
7.	**Reports** sections allow the Planner to download the reports to a Microsoft Excel file.
8.	**Roster Pins** are pre-determined assignments the Planner uses to assign the employee shifts manually.

<!--- End of Section 4 Workforce Scheduler Layout  -->


# 5 Prerequisite actions to generate a Roster
The following are the mandatory sequential steps required for generating a roster:
>>1.	Create Company 
2.	Create Skills
3.	Create Branch
4.	Create Holiday
5.	Create Team
6.	Add Employees
7.	Create Shifts

The following sections describe the major components of the Workforce Scheduler application.

