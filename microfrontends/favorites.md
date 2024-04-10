## Favorites Microfrontend

### Context:
This microfrontend contains one view responsible for presentation of user's favorite products.

### Decision Drivers:
- divide the overall system into logical building blocks
- ensure the ability to change system parts with affecting others

### Considered Options:
1. Adding this to Product microfrontend
2. Separting this as its own microfrontend


### Decision Outcome:
We decided to keep it as a separate to one to faciliate further development and independent testing when more functionalities would be added.

### Consequences
- Good: faciliation of further development by providing possibility to develop and test independently
- Bad: increased initial overhead by adding another microfrontend

### More information
We believe that the inital overhead is useful for further development and makes the maintance easier as it solves future issues. 
