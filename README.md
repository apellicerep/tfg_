# Holiday reporting system

![.](https://github.com/apellicerep/intro/blob/master/vista.png)

This project was born due to my universities need to have a customized holiday reporting system for their employers. To meet their needs and provide them with a software that only contains the requested features I built it and designed this software as my thesis.

This is a summary of the project all details are not share since the project it's going to be delivered in May 2020. If you wish to have more details don't hesitate to contact me. 

Features:

* Authentication and authorization for users through credentials.
* 3 roles: User, Supervisor and Administrator.
* Register new academic courses with their respective holidays.
* Register new users and assign them their respective supervisors and available holidays.
* When creating a new academic course, users will be automatically added to it.
* Delete users from the system or unsubscribe from the active academic course.
* Maintain historical academic courses and their respective holidays.
* Make request directly from the calendar.
* Send email automatically to the respective supervisors of the applicant when a request is made.
* Register status of the requests.
* keep a history of requests by academic year.
* keep track of available number of holidays left and red days flexi time of users.
* Authorize request by accepting or denying them, in case of denying them, a comment will be provided with the reason for the applicant to view it.
* Register authorization status.
* view the requests in the calendar of the users which is monitored.

Technologies:

* Material-Ui
* React Hooks.
* Custom Authentication with Context, useReducer, useEffect and JWT.
* Express
* MySql
* Sequelize
* Deployment through Linux, PM2 and Ngnix.


