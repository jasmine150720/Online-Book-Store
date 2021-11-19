# Online-Book-Store :books:
## List of actors
- **Customer**: The main customers are kids, students or working people, office workers... For each object will have a book to serve their needs more precisely. Their abilities to the website:
  - Return books
  - Add books to card
  - Make payment
  - Sell their old books
  - Registration
  - Login/Logout
  - Search books 
- **Admin**: An online bookstore manager, the admin account is pre-set. Their abilities to the website:
  - Update books, prices, book details
  - Get order information
  - Login/Logout
  - Search books
## UseCase Diagram
![Untitled Workspace (1)](https://user-images.githubusercontent.com/85243027/140451856-c89bb30a-5bd2-42e4-a24d-d2405333dfee.png)
## Use case specifications
### 🔥
| Use case  | Registration  |
|---|---|
| Description  | A user of the System creates an account  |
|  Characters | Guest  |   
| Preconditions  |  (none) |  
| Main stream  | This use case starts when a system user is not logged in to the system and goes to the login page.<br>- The System prompts the user for a username and password or register new account.  <br> - The user selects registration option.<br>-  The System prompts user for registration information, Username, password, etc <br> - The user enters in their information.<br> - System verifies information and creates account.	<br> - The use case ends.|   
|  Alternate streams |  Cancel Registration <br> Invalid Information Entered |   
|  Postconditions | **Success** - User entered successful information and is returned to the home page as a Logged In User. <br>**Failure** - User is unable to log in for one or more reasons and is returned to the home page as a Guest.|  
### 🔥
| Use case  | Log In |
|---|---|
| Description  |  A user of the System logs in to the System. |
|  Characters | Guest , Admin |   
| Preconditions  | (none)   |  
| Main stream  |This use case starts when a system user is not logged in to the system and goes to the login page. <br>	- The System prompts the user for a username and password or register new account <br> - The user enters his/her username and password.<br>	- The system validates the entered username and password, making sure that the entered username is a valid username in the System, and that the required password is entered for the entered username.<br> - The user is signed in and returned to the home page as a Logged In User. <br> - The use case ends.|   
|  Alternate streams | User Fails Authentication: The system prompts the User to re-enter the valid information. |   
|  Postconditions |**Success** - The User is authenticated and the system displays a home page based on the user type. <br>**Failure** -User is unable to log in for one or more reasons.|  
### 🔥
| Use case  | Search |
|---|---|
| Description  | A user searches  |
|  Characters | Guest, Admin |   
| Preconditions  | (none)  |  
| Main stream  |This use case starts when a Guest accesses the “Search” feature of the system. <br> - The System displays the search submission box <br>	- The Guest enters search criteria and submits <br> - The system displays results <br> - Use Case ends.|   
|  Alternate streams |	Guest selects the “Cancel” option. <br>	System returns Guest to Home page.|   
|  Postconditions |The system will display the books which matches the selected search criteria.A dataset is created as a result of select query. Later the dataset is binder to the data repeater to display the selected data. |  
### 🔥
| Use case  | Maintain the book records |
|---|---|
| Description  |  Add books, Remove books, Update books |
|  Characters | Admin |   
| Preconditions  | Admin is logged in <br> The Categories record exists for editing/view |  
| Main stream  | 	The use case begins when the actor indicates the intent to add, update, delete or view item is a record. Categories can be searched. It ends when the actor closes the form.|   
|  Alternate streams | (none) |   
|  Postconditions | The Categories record is added, removed or updated.<br> 	The item’s record is added or updated.|  
### 🔥
| Use case  |	Manage cart  |
|---|---|
| Description  | Add books to cart  |
|  Characters | Actor  |   
| Preconditions  | The Category record exists for editing/view.<br> The actor is logged in.  |  
| Main stream  | The use case begins when the actor indicates the intent to add items into the cart. It ends when the actor enters the next|   
|  Alternate streams | (none) |   
|  Postconditions |The Cart record is added or updated. |  
### 🔥
| Use case  |View Order Detail  |
|---|---|
| Description  | View Order Information  |
|  Characters | 	Admin |   
| Preconditions  |The order record exists for editing/view. <br> The actor is logged in  |  
| Main stream  | The use case begins when the actor indicates the intent to view orders detail of customers.|   
|  Alternate streams |  (none) |   
|  Postconditions | The actor dispatch or cancel the customer record.|  
### 🔥
| Use case  |Sell old books |
|---|---|
| Description  | Customers have the ability to sell their old books on the system  |
|  Characters | 	Costumer |   
| Preconditions  |The actor is logged in  |  
| Main stream  | The use case begins when the actor indicates the intent add their old books to Categories . It ends when the actor finishes the form. |   
|  Alternate streams |  (none) |   
|  Postconditions |The Categories record is added old books|  
### 🔥
| Use case  |Return books  |
|---|---|
| Description  |Customers have the ability to return the book after receiving it |
|  Characters | 	Costumer |   
| Preconditions  |The actor is logged in <br> The book has been delivered to the customer |  
| Main stream  | The use case begins begins when the customer intends to return the book and begins to fill out the return form: reason, address to pick up the book, ... |   
|  Alternate streams |  (none) |   
|  Postconditions |Return request accepted|  
### 🔥
| Use case  |Make payment |
|---|---|
| Description  |Choose the payment method for the invoice |
|  Characters | 	Costumer |   
| Preconditions  |The actor is logged in <br>  |  
| Main stream  | 	Fill in the delivery information and Choose the payment method |   
|  Alternate streams |  (none) |   
|  Postconditions |Order Success.|  
