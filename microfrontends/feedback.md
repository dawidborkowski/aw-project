## Feedback

### Context:
This micro-frontend contains part of the application responsible for presenting product ratings and enabling user to leave their own feedback on the meat.

### Decision Drivers:
- divide the overall application frontend into functionality oriented micro-frontends
- ensure the ability to change application parts without affecting others

### Considered Options:
1. Combining this functionality with functionalities responsible for displaying product and its details
2. Dividing this as into its own micro-frontend

### Decision Outcome:
We have decided to separate this functionality into a distinct micro-frontend as we felt that combining this with product displaying functionality would violate the single responsibility principle. Additionally, it would unnecessarily complicate the the application development process. Dividing this functionality into its own micro-frontend opens the possibility to develop this independently of other parts of the application.

### Consequences:
- Good: eases the division of work, facilitates independent development and testing, adheres to single responsibility principle
- Bad: -

### More Information:
We find this micro-frontends as one of the main the elements of this app having its own story. That's why it makes sense in our opinion to separate it as its own micro-frontend and develop and test it independently.
