## Store

### Context:
This micro-frontend serves the purpose of finding given product by browsing available products divided into categories based on the supermarket location. 

### Decision Drivers:
- divide the overall application frontend into functionality oriented micro-frontends
- ensure the ability to change application parts without affecting others

### Considered Options:
1. Combining those functionalities with the ones responsible with presenting product information and its details
2. Dividing store selection, choosing category and browsing product into a separate micro-frontend
3. Dividing it into two smaller micro-frontends - one being the home page with store selection and the second one enabling choosing the meat category within selected supermarket and browsing the available products

### Decision Outcome:
We have decided to opt for the second option as it wouldn't keep make the app too granular while still adhering to the single responsibility principle, which in this case is browsing products available in chosen supermarket.

### Consequences:
- Good: enables independent development and testing, adheres to single responsibility principles, provides flexibility for future application development such as possibility to add filters without affecting other parts of the application, opens possibility for future reusability
- Bad: -

### More Information:
We think that this division makes sense especially that all the logic behind this can be reused in other applications. Also by making this division we are adhering to best practices used in applications development.