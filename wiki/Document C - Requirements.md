# **C - Requirements-Definition** #



## **Use case (UC) model** ##


### **Use case 1** ###
 
The following use case diagram shows the use cases of the customer.

![Use case 1.png](https://bitbucket.org/repo/AXreney/images/2549561330-Use%20case%201.png)



### **Use case 2** ###


Use cases for supermarket product manager:
![UseCase2DocC.PNG](https://bitbucket.org/repo/AXreney/images/3476421975-UseCase2DocC.PNG)



Brief description of use cases:

**UC1.01** — Login/Logout - The customer can access his account via login, and log out if he whishes for security reasons

**UC1.02** — Product reservation - The user selects the product(s) they wish to buy.

**UC1.03** — Buying products - The user makes the purchase.



**UC2.01** - Login/Logout - The person in charge of the supermarket account can login and log out

**UC2.02** - Add/Remove products - User can add and remove avaliable products.

**UC2.03** - Listing - User can see a list of products that are avaliable, reserved or bought, concerning his store.



## **Business rules** ##

The Business Rules (BR) are the source of many business decisions. They can change over time and can have impact on more than on use cases. Therefore, it is important to identify and track them.

**BR01** — End of shelf life — Closing in on the respective end of shelf life of the products, they will be donated to third parties. They will no longer be avaliable for purchase.

**BR02** — Product selection — People can buy as much as they want, as long as it is still in stock.



## ***Technical requirements*** ##

In this section are grouped the business rules, non-functional requirements, and other constraints. It also includes the assumptions that the team will embody in the project.

**Non-functional requirements**

Most of the Non-Functional Requirements (NFR) are implicit in the condition:

**NFR01** — Web platform — The "purchase of products" component should run in a Web platform - HTML/CSS/JS + Servers for website and database(MySQL);

**NFR02** — User account — The users should verify their email account to login;

**NFR03** — Web browser — The system must be compatible with the most popular and used browsers: Chrome, Safari, IE/Edge, Firefox and Opera.



## **Assumptions and constraints** ##

All constraints and decisions that have a relevant impact on the project, should be explicitly mentioned and documented:

**AC01** — Deadlines — The project should be ready for deployment by the end of the 1st semester;

**AC02** — Open Source — The team will use open source technology, as much as possible.

**AC03** — Languages — The "product purchase" component will support the Portuguese language at the beginning, and depending on the degree of adherence, new languages ​​could be introduced!

[Back Home](https://bitbucket.org/ws-18861-19256-19377/repo_18861_19256_19337/wiki/Home)