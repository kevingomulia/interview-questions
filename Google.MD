### Question 1 - Coding

Given an input string like below:
```
1532926994 User01 LogOutSuccessful
1532926981 User02 LogInSuccessful
1532926982 User04 LogInFailed
...
1532926992 User01 LogInSuccessful
1532926986 User02 LogOutSuccessful
1532927003 User03 LogOutSuccessful
```
Create a method that will churn out this output:
```
{ "username": "User02”, "session_duration": 5 }
```

Note: The order of the strings' timestamp might not be in order.
Note2: You might encounter 2 messages saying LogOutSuccessful before
encountering the matching LogInSuccessful message.

### Question 2 - Database Design
You are managing a cinema. A cinema has different movies that are screened
on different halls with different seating arrangements at different timings.

How would you design the database schema?
