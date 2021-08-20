# aimassist

** DEVELOPMENT HAS SLOWED DOWN **

#Description

Aim Assist is a quick, simple way to keep track of EPR/OPR bullets for Airmen and Supervisors.

Aim Assist uses a postgreSQL database running on an express server, with a React frontend for a simple, mobile friendly user interface. Our site navigates to the users' dashboard and shows a list of bullets that include the date and AIR (Action, Impact, and Result). To add a new bullet, users will click on the button 'Add Bullet' and fill out the proper information for it to pop up on their list below. Aim Assist uses a 'Delete' feature in case an Airmen no longer needs a specific bullet. 

On the left hand side bar, users can select to see their profile. Selecting the profile takes users to their information such as their ID/referal code, full name, email, password, and their role. If the user sees an error or needs to update their information, they can type in the specific field and click the button 'Submit update'. The only field you will not be able to change is your ID/referal code since this keeps track of you in the system specifically.

For users in a Supervisor role, they also have the ability to see their Airmen's bullet page as well and check what/how many bullets are being created. Airmen's names will be listed below the tab 'My Tracker'. 

#Installation

A postgres image inside of Docker at port 8080

npm install nodemon for Back-End

#Usage

Aim Assist is simple and user friendly. Login to be taken to your dashboard:
![Dashboard](https://github.com/jltackett2/aimassist/blob/bullet-form/images/Dashbard.png) 

From your dashboard, you can see you previously submited bullets. You can also add new a new bullet by clicking on the add bullet button. This will open the add bullet form:
![Add Bullet](https://github.com/jltackett2/aimassist/blob/bullet-form/images/Add%20Bullet.png =250x315)


Once the form is filled out, simply click submit and you will see your new bullet added to your dashboard:
![Bullet Submitted](https://github.com/jltackett2/aimassist/blob/bullet-form/images/Bullet%20Added%20.png =250x250)


You can also delete a bullet from your dashboard by clicking on the delete button next to the bullet you wish to delete:
![See Delete Button](https://github.com/jltackett2/aimassist/blob/bullet-form/images/Bullet%20Added%20.png =250x250)


Once you click the button, the bullet is removed:
![Bullet Deleted](https://github.com/jltackett2/aimassist/blob/bullet-form/images/Dashbard.png =250x250)


You can also update your profile by clicking on the profile button on the left sidebar, this will bring up the profile view:
![Profile View](https://github.com/jltackett2/aimassist/blob/bullet-form/images/View%20Profile.png =250x250)


You can then update your profile like the email shown below:
![Profile Updated](https://github.com/jltackett2/aimassist/blob/bullet-form/images/Update%20Profile.png =250x250)


This will change the users information in the database:
![Updated User Database](https://github.com/jltackett2/aimassist/blob/bullet-form/images/Updated%20User.png =250x250)


Thats it, as you can see, this application is simple and user friendly.

#Team Members

Jordan T - Back-End Developer

Jacob W - Back-End Developer

Oleg K - Front-End Developer

Michelle C - Front-End Developer

