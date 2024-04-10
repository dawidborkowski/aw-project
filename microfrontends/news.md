## News

### Context:
This micro-frontend contains the functionalities enabling user to read articles regarding their meat.

### Decision Drivers:
- divide the overall application frontend into functionality oriented micro-frontends
- ensure the ability to change application parts without affecting others

### Considered Options:
This micro-frontend was straightforward to us as it offers additional functionality that isn't coupled with the core functionality of the application and we didn't consider any other options.

### Decision Outcome:
We have separated this part of the application into another micro-frontend.

### Consequences:
- Good: facilitates division of work, promotes independent development and testing, development can be held until more crucial functionalities are implemented
- Bad: -

### More Information:
This was a straightforward decision for us as this micro-frontend plays an important role in the application, having its own story. Yet, that being said by dividing this into a separate micro-frontend we are keeping the possibility to wait with the implementation until the core of application is developed.
