## Product

### Context:
This micro-frontend is responsible for displaying information about chosen meats. It also contains contains functionalities enabling to see the details about meat origin as well as QR code scanner to facilitate finding the products faster.

### Decision Drivers:
- divide the overall application frontend into functionality oriented micro-frontends
- ensure the ability to change application parts without affecting others

### Considered Options:
1. Dividing the part with meat information and details and QR code scanner into separate micro-frontends
2. Combining the meat information, details and QR code scanner into a single micro-frontend
3. Combining the store and category selection, product browsing, meat information, details and QR code scanner into a micro-frontend

### Decision Outcome:
We have decided to combine the meat information, details and QR code scanner into a single micro-frontend without adding the functionalities such as store and category selection and product browsing. This way we are making this frontend only responsible for getting information about selected product adhering to single responsibility principle.

### Consequences:
- Good: this part of the application can be developed and tested independently of the others part, adhering to single responsibility principle
- Bad: -

### More Information:
This micro-frontend plays the pivotal role in the application being the one that implements main story of the application. We believe that with the current division we are not making the application neither monolithic nor too granular.