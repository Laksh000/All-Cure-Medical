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
<p align="center">
<img width="1271" alt="Screenshot 2023-12-30 155816" src="https://github.com/Laksh000/All-Cure-Medical/assets/63722982/0011093b-3566-40a8-8217-f4e9b6af53d9">
</p>
<p align="center">
<img width="1261" alt="admin panel-homepage" src="https://github.com/Laksh000/All-Cure-Medical/assets/63722982/5e67ef93-708c-4ce9-8928-09e11472b2fa">
</p>
<p align="center">
<img width="1259" alt="admin panel-productspage" src="https://github.com/Laksh000/All-Cure-Medical/assets/63722982/df86b11f-69e8-4a14-b9a0-b6e85dd215ee">
</p>
<p align="center">
<img width="1261" alt="admin panel-userspage" src="https://github.com/Laksh000/All-Cure-Medical/assets/63722982/636e10b2-8467-49f6-90f1-f15adba73c21">
</p>
<p align="center">
<img width="1279" alt="admin panel-cartpage" src="https://github.com/Laksh000/All-Cure-Medical/assets/63722982/ff9c266b-0119-4bd4-8088-4669bfec65da">
</p>
<p align="center">
<img width="1267" alt="admin panel-orderspage" src="https://github.com/Laksh000/All-Cure-Medical/assets/63722982/499bd4c0-4246-4cec-a939-36d87941a3eb">
</p>
<p align="center">
<img width="1261" alt="Screenshot 2023-12-30 160527" src="https://github.com/Laksh000/All-Cure-Medical/assets/63722982/138ebba6-10b8-4b62-bbb3-dbdd2ce47f20">
</p>

