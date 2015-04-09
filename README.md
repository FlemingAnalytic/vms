# vms
Volunteer Management System Source Code
<HTML>
<head>
<title>Volunteer Management System</title>
</head>
<body>
<h2>Volunteer Management System</h2>
<p>
This is an application I refer to as Volunteer Management System. I originally developed it for use in some volunteer organizations I am involved with, and thought this might be of use to others.
<p>You can use the template located in lib/sql/vms.sql  to create the database structure.</p>
<p>You can then edit the model login information in model/include.php and move it to include from wherever you want (I normally put this up a path so it is less susceptible to breaking, but that’s up to you..)</p>
<p>I use facebook login exclusively to control users. You will need to create a facebook app and post that id in the lib/js/fb.js file.<br/>

FB.init({   appId      : '',//your  Facebook app id here!
</p>
 A user needs to be manually given the status of Admin to add events. Volunteers will only be able to volunteer for an open role in an event.</p>
<p>Once logged in,  an ADMIN will have the ability to create a new event  (note this works in desktop mode only. A screen width of 800 chars or less will switch the app into mobile mode, and only volunteering is possible in this mode).  Once Create Event is pressed, a form will be presented to either create a new event from scratch, or to clone an existing event to a new day (this saves may steps if it is a repeatable event).</p>
<p>
After filling in event info, an admin can add roles for each event. Once the role is added, an Admin can then assign users to each need for the role (Note: This functionality will be removed in the future, volunteers should be required to sign up themselves!).</p>
<p>Currently no reports are being produced to show what roles are still open, who has signed up, etc. </p>
<p>VOLUNTEERS can see any event that is open. A volunteer can then look at what roles are still in need of help, and sign up, after seeing the  pre and post- minutes that  would be expected, as well as any qualifications that may be required for fulfilling the role (must be a registered nurse, experienced carptenter, etc).</p>
<p>An email is sent to the volunteer confirming their volunteer effort. No further emails or reminders are being sent at this time.</p>
<p>A volunteer can choose to cancel their assignment if they choose, and the need is then open again.</p>
<p>You are free to use this code for non-profit charitable purposes. All rights are reserved by me, John Fleming, Fleming Analytic Resources.</p>
</body>
</HTML>
