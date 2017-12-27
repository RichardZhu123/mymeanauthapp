Start MongoDB service:
In Command Prompt with Admin Privileges enter the following commands:
cd C:\mongodb\bin
mongod

Start backend server (The MongoDB service must be started already for this to work properly)
In a separate Command Prompt with Admin Privileges enter the following commands:
cd C:\Users\RZ\Documents\AAANew\Projects\meanStackTutorial\meanauthapp
nodemon

Start frontend server (Angular server) (MongoDB and backend server should be initialized already)
cd C:\Users\RZ\Documents\AAANew\Projects\meanStackTutorial\meanauthapp\angular-src
ng serve


To stop one of these services, just press ctrl + 'c' in the command line window where the service
is being run.
