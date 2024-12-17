Questo progetto simula un E-commerce di arredamento

![image](https://github.com/user-attachments/assets/a21e0fe7-ab6b-44e0-97c7-58de9633d694)

Le tecnologie utilizzate per questa applicazione sono:


   ![image](https://github.com/user-attachments/assets/3de06bbc-9012-449b-afd9-622ea7a43aeb)


  
- Le dipendenze di SpringBoot utilizzate sono:
  
- Spring Web
  ![image](https://github.com/user-attachments/assets/7c2dd333-ba15-4e58-9488-f8096b7827fe)


- Spring Security
 ![image](https://github.com/user-attachments/assets/2b96fb94-10de-4735-bcf8-7b5ced3d2493)


- Spring Boot DevTools
  ![image](https://github.com/user-attachments/assets/31df0832-1433-477f-89d2-67ca19a7ca87)


- Spring Data JDBC
 ![image](https://github.com/user-attachments/assets/2d0474f7-bd25-45af-8f4d-8deb3fc4a474)


- My SQL Driver
  ![image](https://github.com/user-attachments/assets/ccb24487-8fed-4f0f-92a3-aea56e534318)


- Thymeleaf
  ![image](https://github.com/user-attachments/assets/25ad47bd-6bf0-4226-a390-da6f03adc7db)


- Java Mail Sender
 ![image](https://github.com/user-attachments/assets/b02bbc4f-1006-43e8-9d5f-941a000a5644)

Dependencies
Thymeleaf, Spring Web, Spring Boot Web Tools, MySql Driver, Spring Data JDBC

### Java
  - [Database Config](DatabaseConfig.java) - _configures the connection to the MySql database_
  - [Mail Config](MailConfig.java) - _configures the connection to gmail_
  - [Email Service](EmailService.java) - _provides some useful mail templates_
  - [Pc](Pc.java) - _is the personal computer in store class: it has model name, brand,description, price, image, quantity available in store and quantity sold. reflects the columns of the database table_
  - [PcSelezionato](PcSelezionato.java) - _is the personal computer in shopping cart class: it has model name, brand,description, price, image, quantity selected for purchase_
  - [PcJdbcTemplate](PcJdbcTemplate.java) - _is the class containing the database queries: select, insert, delete and update quantity (to update the available number and sold number of a given pc)_
  - [MyController](MyController.java) - _a class that handles HTTP requests and responses, facilitating the interaction between the front end and the back end of the application._
### Html
  - [Layout](templates/layout/layout.html) - _the layout of every html page. It contains the css libraries, JavaScript scripts, a navbar, a sidebar and a footer_
  - [Index](templates/index.html) - _the homepage: it contains a shop description, the card of the item sold in shop and a div with a random mario card obtained interrogating an API_
  - [Carrello](templates/carrello.html) - _the cart page: it contains a table with the list of every item purchased. The user can modify the quantity, remove from cart and purchase the selected items_
  - [Fattura](templates/fattura.html) - _the order confirmation page: it contains a table with the list of every item purchased and a box where the user can put the email address to recieve an order recap_

<p align="right">(<a href="#readme-top">back to top</a>)</p>

Contacts:

Linkedin: www.linkedin.com/in/marco-cerilli
Github: https://github.com/MarcoCerilli/ProgettoArredo.git
