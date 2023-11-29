# Book-Store

I.	Overview setup project Local:
This document is guiding how to setup Project Local.
Requirement:
1.	Install Eclipse IDE
2.	Install Java SE Runtime Enviroment 8u202
3.	Download Apache Maven
4.	Install MYSQL  Community Downloads
5.	Download Apache Tomcat 9

II.	Project Overview:
Technologies : 
+  Using Java Servlet, JSP, JSTL and Hibernate framework, HTML, CSS, Javascript and jQuery
+  Design and manage Database with MySQL
On the front-end side (shopping website), develop the following features:
•	Homepage: List newly published books; best-selling books; most-favored books
•	List books in a category
•	View book details
•	Search books
•	Shopping Cart
•	Customer Registration
•	Write reviews for books
•	Place order (Checkout)
•	PayPal Payment Integration (include credit card payment)

On the back-end side (Admin control panel):
•	Users management (include admin login/logout)
•	Category management.
•	Book management.
•	Review management.
•	Customer management.
•	Order management.
•	Statistics (admin dashboard)

III.	Source Code:

1.  Import project into Eclipse -> Open file persistence.xml and hibernate.cfg.xml

 
 
Change value username & password already setup in Mysql Workbench
2. Open Mysql Workbench ->  run script bookstoredb.sql . Attached inside the folder SQL project.
3. Open Eclipde -> Right click AmazonBookStore -> Run As -> Run on Server
Home Page:   http://localhost:8080/AmazonBookStore/
Admin:  http://localhost:8080/AmazonBookStore/admin/
User: admin@gmail.com
Pass: 12345678

