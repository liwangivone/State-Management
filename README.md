# State Management
 Ephemeral state management and app state management

This repository consists of two projects of state management: ephemeral state management and app state management.

The ephemeral state management uses stateful widgets to manage local state that only applicable for certain widgets. This method is relatively simple and suitable for small cases such as the counter button, because the change of state is done by using "setState()". However, if the state is required to be accessed by lots of widgets or is globally used, stateful widget might be difficult to manage and ended up being not eficient. In the other hand, scoped model is a state management method that allows the sate to be accessed and shared globally throughout the application. Using the model class and "scoped_model" library, the state can be managed centrally, hence, it is more organized and suitable for larger Flutter applications.

The use of state management with scoped model gives many advantages, especially for those large application that are more complex, like requires user authentication or shopping carts. Using this method, global state can be accessed easily within parts of the application, enhancing eficiency and delivers well-organized code. Not only that, this state management reduces unnecessary renders, eases debugging process, and making it easier to run the code.