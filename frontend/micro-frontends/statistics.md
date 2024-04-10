## Statistic

### Context:
This micro-frontend is responsible for displaying numerical statistics representing trends regarding meat production as well as animals' eating habits.

### Decision Drivers:
- divide the overall application frontend into functionality oriented micro-frontends
- ensure the ability to change application parts without affecting others

### Considered Options:
1. Join those functionalities with displaying the articles creating one unified micro-frontend
2. Divide this part of the application into a separate micro-frontend

### Decision Outcome:
We have decided to make it as a separate frontend as it serves completely different purpose than the news. Moreover, such decision facilitates further development of this part of application in terms of adding more advanced data visualization methods. 

### Consequences:
- Good: facilitates division of work, promotes independent development and testing, allows further development 
- Bad: increases granularity as it is not a core application functionality that could be possibly integrated into another micro-frontend

### More Information:
We believe that increased flexibility and possibility to increase statistics' complexity without affecting parts of application outweighs the disadvantage of increased granularity. 
