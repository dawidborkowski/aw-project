## Favorites

### Context:
This micro-frontend is responsible for presentation of user's favorite products.

### Decision Drivers:
- divide the overall application frontend into functionality oriented micro-frontends
- ensure the ability to change application parts without affecting others

### Considered Options:
1. Combining this functionality with functionalities responsible for presenting product and its details
2. Separating this functionality as its own micro-frontend

### Decision Outcome:
We have decided to divide this functionality into a separate micro-frontend to facilitate further development and independent testing when more functionalities would be added such as filtering.

### Consequences:
- Good: facilitates further development by providing possibility to develop and test independently, increases flexibility enabling enhancing favorites functionalities without affecting other parts of the application
- Bad: increases initial overhead and application granularity by adding another micro-frontend

### More Information:
We believe that the initial overhead is acceptable at this stage in order to make further development and maintenance easier as prevents issues arising in the future. 
