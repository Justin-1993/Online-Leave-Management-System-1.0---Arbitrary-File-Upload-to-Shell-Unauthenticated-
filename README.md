# Online-Leave-Management-System-1.0---Arbitrary-File-Upload-to-Shell-Unauthenticated-

Online-Leave-Management-System-1.0 
contains a file upload vulnerability in the admin/?page=user directory that allows for remote 
code execution via php file upload.  This exploit requires 
the user to be authenticated, however a SQL injection in the login form 
allows the authentication controls to be bypassed.
Files uploaded from "/admin/?page=user" have no validation check which allows us to upload any type of file
