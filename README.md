# All-Cure-Medical

## Introduction :
* Functionalities: The Java web application will provide an intuitive interface for managing wholesale and retail operations of medicines. It will include features like inventory management, order processing, customer management.
* User Roles and Access Control: The application will have distinct user roles such as administrators, wholesale supplier, and customers. Each role will have specific permissions and access levels to ensure proper control and security over sensitive data and functionalities.
* Inventory Management: The system will allow users to efficiently manage medicine inventory, including functionalities for adding new stock and automatically updating stock levels based on sales and purchases.
* Transaction Processing: The application will facilitate seamless transactions, enabling users to create and process wholesale orders from suppliers and retail sales to customers.


## Technologies used :
* Java
* Spring boot
* Spring JPA
* Hibernate
* Microservices
* Swagger
* Mysql
* Thymaleaf
* Javascript
* HTML
* CSS

## Technical overview :
* **Service-Oriented Architecture**: The project is structured around **four key services**: customer, customerService, orderService, and product, each responsible for distinct functionalities such as managing customer data, handling orders, and overseeing product inventory.
* Integration with **AllCureMedical** via **Feign Client**: AllCureMedical's APIs are seamlessly integrated into the project through a Feign client. This integration allows for easy communication with AllCureMedical's services, enabling functionalities and data exchange critical to the project.
* Data Management with **DAO** and **DTO** Patterns: The project employs robust design patterns like DAO (Data Access Object) and DTO (Data Transfer Object) for efficient data management. DAO patterns streamline data access, while DTO patterns optimize data transfer across different layers or services within the project.
* Dynamic Frontend with **Thymeleaf**: The frontend of the application is developed using Thymeleaf, a powerful templating engine. This choice ensures a dynamic and interactive user interface, enabling seamless integration with the Java-based backend services. Thymeleaf empowers the creation of responsive web interfaces, enhancing user experience in managing wholesale and retail aspects of medicine transactions.
  
## Snapshots:
