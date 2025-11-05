Aim:
To check if a given password string meets a specific set of security rules and classify it as either "Strong" or "Weak".

Algorithm:

1.Define a function check_password that takes one parameter, password.

2.Check multiple conditions for the password simultaneously:

3.Is the length of the password greater than or equal to 8?

4.Does the password contain at least one uppercase character?

5.Does the password contain at least one lowercase character?

6.Does the password contain at least one digit?

7.Does the password contain at least one special character from the set !@#$%^&*()?

8.If all five conditions are true, return the string "Strong".

9.Otherwise (if even one condition is false), return the string "Weak".
