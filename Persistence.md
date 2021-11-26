# Persistence
## List of entities, properties
|  Entity 	|   Property	|   Comments	|
|---	|---	|---	|
|  Admin 	|   AdminID	| Admin's identification number. The key property of this entity type.	|
|   	|  Admin user name 	| Admin user's name. All instances of this entity type have this property.	|
|   	|  Password 	|  This attribute will help the user to provide security to his profile and helps the user to secure his personal contents from forgery. 	|
|  Customer 	|   CustomerID	|   Customer's identification number. The key property of this entity type. 	|
|   	|   Name	|  This attribute will describe the name of the members and as we know name consists of first name and last name, so this attribute is a composite attribute that further derives first name and last name.	|
|   	|   Email	|  This attribute will provide us with a global name of the member which is unique at the global level so we will use the attribute as the username of the member which helps him during login. 	|
|   	|   Password	|  This attribute will describe the name of the members and as we know name consists of first name and last name, so this attribute is a composite attribute that further derives first name and last name. 	|
|   	|  Phone Number 	|  This is an important attribute from the admin’s point of view. If the admin has phone number of the user, then only, he can contact with customer. 	|
| Book  	|  Book ID 	|   This will help us to identify the books uniquely, which is having the same copy present in stock. This will help us to get track of copies which have been sold in the market.	|
|   	|   Author	|   This will inform you about the author’s name.	|
|   	| Price  	|  This will inform you about the price of book. 	|
|   	|  Description 	|   This attribute will make you has the overall view of selected book	|
|   	|   Title	|  This will inform you about the name of book. 	|
|   Order	|   	Order ID|  Order's identification number. The key property of this entity type. 	|
|   	|  Customer Name 	|   This will inform you about the name of customer.	|
|   	|   Book Name	|  This will inform you about the name of selected book. 	|
|   	|   Order ammount	|  This will imform us the number of books sold, control the items 	|
## Entity Relationship Diagram
![image](https://user-images.githubusercontent.com/85243027/143510487-9b6dc286-5860-4f44-b662-7b858eae7587.png)
## Database model
![image](https://user-images.githubusercontent.com/85243027/143510211-ef83d412-afe8-469a-85cd-edf2ad92a228.png)



