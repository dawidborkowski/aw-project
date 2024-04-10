## User Authentication

### Context:
This micro-frontend contains a login form that allows users to log in into their accounts.

### Decision Drivers:
- divide the overall application frontend into functionality oriented micro-frontends
- ensure the ability to change application parts without affecting others

### Considered Options:
1. Divide this functionality into separate micro-frontend
2. Combine this with functionalities providing access to user settings.

### Decision Outcome:
We have decided to separate the login functionality into a separate micro-frontend, preventing too much granularity in the application and facilitating team division.

### Consequences:
- Good: facilitates division of work, promotes independent development and testing, adheres to single responsibility principle, provides possibility to reuse this in other applications
- Bad: -

### More Information:
The decision to create this micro-frontend was straightforward to us as it is a basic functionality that is widely implemented in almost every application and could be reused across different apps simply by changing the UI design.