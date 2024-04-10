## User Profile

### Context:
This micro-frontend contains account management functionalities as well as form to contact application support.

### Decision Drivers:
- divide the overall application frontend into functionality oriented micro-frontends
- ensure the ability to change application parts without affecting others

### Considered Options:
1. Divide this functionality into separate micro-frontend
2. Combine this with login functionality into a single micro-frontend.

### Decision Outcome:
We have separated these functionalities into separate micro-frontend.

### Consequences:
- Good: facilitates division of work, promotes independent development and testing, development can be held until more crucial functionalities are implemented
- Bad: increases granularity

### More information
This micro-frontend is rather a nice detail than a backbone of the application. This being said, we believe that  ...
