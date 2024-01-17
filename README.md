
1) roles of users
    -Admin (
        -List of users and with department
        -Adding users with password 
        -Changing the password of users
        -Changing the department of users 
        -reports
    )
    -CEO (
        -Actual tasks all department and users by date of create and target date
        -Adding tasks for Managers, users, own
        -reports all kind
    )
    -Manager (
        -Actual tasks his/her department and users
        -Adding tasks own, users
        -reports by own department and users
    )
    -user (
        -Actual tasks own
        -reports by user own
    )

2) database
    -Tasks table
        ID | Date of wrote | Task name | Description | Who wrote | For who | Date of done |  
    -roles of access
        ID | Type of user | type of access
        1  | Admin        | full access
        2  | Manager      | 
        3  | CEO          | 
        4  | User         | user

    -Logs of operations
        -all actions must be saved in data
        ID | When | Who | Department | What happened
        
3) tamplates (html) (all pages must login for using)
    -login page 
        1) username -----
        2) password -----
    -user page
        -actual task(only own) with filter
        -Old tasks with filter 
        -task page
        -report page 
    -manager page
        -actual task for all users
        -create task
        -report task with department
        -report task with user
    -admin page
5) report types with period:
    -by department
        -report with done tasks by department
        -report with not done by department
        -total report in diagrem by department
    -by user
        -report with done tasks by users
        -report with not done by user
        -total report in diagram by user
