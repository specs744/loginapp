A version of an app that will allow you to register. 
Once logged in you will be able to update password

Jump24 - Apprentice Developer Task

The Approach

After reading through the requirements the goal was to achieve as many bonus points as possible. This meant that the build would be on Laravel.

My first objective was to install Laravel and to get it working in order to use it once I had gained a better understanding of what it was. Once installed which was done using the Laravel online documentation, laracasts, Youtube and just some general google searches to troubleshoot my problems, I then proceeded to serve the project in order to see what was being edited. After making and breaking several apps I had decided on the install of Laravel that would be best used to match the requirements of the throwing of errors on incorrect details, accessing a database securely, giving the ability to register, sign in and update password, include ReCaptcha and then finally testing it all before committing it to a Github repo.

My next problem was getting a database and connecting it to the project. Again using online documentation from Laravel, Youtube and reading I found solutions to the following problems; installing and running MySQL, setting up privileges for database users, connecting database to Laravel project, getting Xampp installed and working, getting phpmyadmin working and creating and destroying a database.

My next objective was setting password update rules to conform with requirements. As stated in documentation the steps were followed resulting in a new password rule of min 10 characters, including a special character and at least one number.

Finally all that was left was ReCaptcha and testing. I tried both v3 and v2 of ReCaptcha and followed the steps of both but could not succeed in incorporating it into the login page. Testing was completed after research into the built in testing features of Laravel and running autonomous tests. Finally I have committed the project to GitHub in a public repo and have added my approach to the README.md file
