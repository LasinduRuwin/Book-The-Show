## Book a show

<p>This is an movie booking Application created  using ASP.Net 6 (backend) and angular 14 (frontend). The database is created using SQL Server. </p>

<p>This app allows users to book a show for a movie and allows searching via movie name and available dates. It also allows users to view their bookings and cancel the booking if the booking date is in the future. after the booked date, the users can rate the movie. Furthermore the admin users can add, edit, delete both shows and movies</p>

### Setup Guide

- To run the Angular front-end, simply extract the files and run "ng serve" or "ng s".
- To run the .Net backend, extract the files and run using Visual Studio 'BookTheShowAPI.WEB' project.
- To initialize the database, in Visual Studio, change the connection string in both setting.json files to your own. Then inside the package manager console, select the 'BookTheShowAPI.DAL' run the command "update-database".
- The added database can be used to get the test data or it is possible to add new data.
- To create an admin account use the .Net api or edit an existing record in the database. This can be done by editing the IsAdmin column in the database.

Note: please refer to the below link on instruction on how to restore the database backup
link: https://learn.microsoft.com/en-us/sql/relational-databases/backup-restore/quickstart-backup-restore-database?view=sql-server-ver16&tabs=ssms

### Admin Email

- alan@gmail.com
- taylor@gmail.com

### User Email

- ed@gmail.com
- selena@gmail.com
- luke@gmail.com
- Edgar@gmail.com

<p>password : '123456789'</p>

Note : All user passwords are set to same for ease of testing.
