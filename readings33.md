## Model, View, ViewModel (MVVM pattern)
- Model − It simply holds the data and has nothing to do with any of the business logic.

- ViewModel − It acts as the link/connection between the Model and View and makes stuff look pretty.

- View − It simply holds the formatted data and essentially delegates everything to the Model.

### Binder
- Declarative data and command-binding are implicit in the MVVM pattern.
-  The binder frees the developer from being obliged to write boiler-plate logic to synchronize the view model and view. 
- When implemented outside of the Microsoft stack, the presence of a declarative data binding technology is what makes this pattern possible


#### In practice, you normally want some other class sitting between the user interface and the model. This has two important roles.

1. First, it adapts your application model for a particular user interface view.

1. Second, it's where any nontrivial interaction logic lives, and by that, I mean code required to get your user interface to behave in the way you want.

