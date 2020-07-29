# NaigusAssgnment1
PHP project
1. Database Connection file named as Server.php 
2. To Register new user Register.php is responsible which sends data to database and stores for next login by the same user.
here, we ensure that same user and email can't use. for this we check these fields with existing data
3. Login takes place by login.php file where we check username associated with password if matches then redirect to index.php page 
otherwise give notification as not matched details.
4. for error handling error.php
5. After succesful login we can book our slot using calendar from calendar.php file which will send data to book.php. In this page you can also see that given seat is booked or not if "Seat is booked" is written over any date of calendar that means you can't book that particular slot for you.
6. If seat is already booked then it will notify that seat is already booked otherwise your seat will booked for specific time with your name and email address.

If someone try to access book.php or calendar.php without login message will throw that "You need to login first" by index.php file.
