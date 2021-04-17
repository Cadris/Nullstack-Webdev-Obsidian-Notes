#basics , #defination
#MVC 
# MVC Architecture 
## Model
- The Central Component of the pattern. Its the application's dynamic data stucture, independent of the user interface.
- It directly manages the data, logic and rules of the application.

## View
- The View component is used for all the UI logic of the application. For example, the Customer view will include all the UI components such as text boxes, dropdowns, etc. that the final user interacts with.

## Controller 
- Controllers act as an interface between Model and View components to process all the business logic and incoming requests, manipulate data using the Model component and interact with the Views to render the final output. For example, the Customer controller will handle all the interactions and inputs from the Customer View and update the database using the Customer Model. The same controller will be used to view the Customer data.