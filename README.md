Aim:
To check if a given password string meets a specific set of security rules and classify it as either "Strong" or "Weak".

Algorithm:

Define a function check_password that takes one parameter, password.

Check multiple conditions for the password simultaneously:

Is the length of the password greater than or equal to 8?

Does the password contain at least one uppercase character?

Does the password contain at least one lowercase character?

Does the password contain at least one digit?

Does the password contain at least one special character from the set !@#$%^&*()?

If all five conditions are true, return the string "Strong".

Otherwise (if even one condition is false), return the string "Weak".
