
# Epam Lab, Final Java Web Task 2019
### abstaract store
###### graduate work

Online store

General:
- Spring MVC application for the purchase of any goods;
- Description of Spring entities: Annotation or Java approach;
- Java 8;
- Replace loop structures with Stream API capabilities;
- Application work on Apache Tomcat 9;
- Template - Thymeleaf;
- Should be: controllers, service layer, DAO layer;
- Database, for example, H2;
- Unit and integration tests are required;
- Provide your own hierarchy of exceptions;
- Provide for logging events to a file: log-in / log-out / registration of users, adding to the cart and paying for goods, adding / deleting / updating goods to the store;
- All literals used in the app are in English.

Functional:
- The ability to log in, log out (Spring security to choose from, you can through sessions);
- Only a logged in user has access to the store;
- Session lifetime - 3 minutes;
- If the user is not logged in, display the main page (with a login form), if logged in, then open the main page with products;
- In case of any error, open a separate page with an error in which there is a link to the main page;
- Add cart functionality (products can be deleted and added), adding an item to the cart does not reduce the number of items in the warehouse;
- Any payment system can be made. For example, just a button to pay and reduce the quantity of goods in stock;
- Each product has a name, picture, price and quantity in stock;
- When choosing a product, add the ability to view its description;
- Admin can add / remove / update products;
- Custom menu by product categories.
P.S. The emphasis should be placed not on UI special effects, but on the quality of Java code.
