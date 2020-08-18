# Mathml
Author: Cameron Skaggs
Date: 8/18/2020
Description:
An application that reads from an xml file named 'math.xml' and performs calculations
based on the parameters.

Additional Notes:
- Includes unit tests in separate project.
- The specifications didn't mention how to handle incorrect inputs so I decided to warn the user by printing to console.
- This is extendable, all that would need to be added to read json files is a function called getJsonFile.
  Adding a power functionality would be as simple as adding a new parameter into the operation class and operationType enum.

How to test:
- Edit the math.xml file with new values. Use high numbers, use negative numbers.
- Go into the unit tests and change the hardcoded values I put in there
- Enter invalid numbers or strings where numbers should be
