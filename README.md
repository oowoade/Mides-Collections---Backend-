Abstract
This project details the design and implementation of a web-based Digital Order Booking System for Mides Collection, a hair and accessories enterprise. The system addresses inefficiencies in manual order handling, inventory inaccuracies, and fragmented staff–customer communication. 
A Python backend manages business logic, validation, and transaction processing, while a Java frontend delivers an interactive user interface. Data persistence is achieved through Microsoft SQL Server, ensuring referential integrity and optimised query performance. 
UML modelling informed architectural design, and role-based access control strengthened security. The solution demonstrates applied competence in full-stack development, relational database design, and scalable systems engineering.


 Introduction
Seeing as the industry for wigs and hair accessories is rapidly rising in demands for either custom or standard products, a structured yet efficient customer service is needed. In this field, many small hair businesses rely heavily on taking orders manually, and for the most part can result in delays either from both business owners and consumers, errors, hence leading to loss of continuous sales opportunities.
5.1 AIM 
By the end of my project, I aim to create and develop a feasible, user-friendly digital order booking system that simplifies and automates the process of ordering, managing and meeting the customers needs. It will improve all things accuracy in ordering, delivery, communication between the staff and customers. I will make use of Python to develop the backend logic, as it visualises everything behind the scenes and will use Java to make the interface interactive and engaging for the users, bringing the frontend to life. A secure relational database (such as MSSQL) will be used to store and manage all business data.
5.1.1 Objectives	
●	Design and develop a web-based order booking system tailored for hair & accessories business
●	Allow customers to search products, place orders, and receive confirmations online automatically
●	Automate purchase orders for staff, including order tracking and sending, inventory updates, and notifications
●	Integrate reporting tools to provide business insights on sales, inventory, and customer trends
●	System security, flexibility, and easy to use for both customers and business staff.
5.1.2 Scope and Approach
●	The system will support order placement, order status tracking and basic inventory management
●	Administrative features will include order overview and inventory adjustment
●	The solution will be accessible via standard web browsers on desktop and mobile devices
5.1.2 Out of scope
●	Developing real payment systems/gateways, instead I will mimic payments for examples
●	Advanced customer management/marketing tools are not included in this project
5.2. Analysis of the Current System
5.2.1.Current Operations
Using an interview style, I identified how orders are currently taken and tracked. Orders are taken online via Instagram direct messages or WhatsApp and manually tracked via WhatsApp. Orders received are tracked and stored using a notepad and WhatsApp messaging platform, leading to lost or missing orders 
When suppliers are contacted, this process includes manually texting via WhatsApp messaging platform and once again orders requested from suppliers are storing using a notepad, leading to delayed or uncertain orders.
5.2.2.Flaws of the Current System
Problems faced during manual processing of orders include the tendency to forget to update the customers on their orders placed, leaving customers dissatisfied and lack of trust for the business. There is very slow communication when the business manually contacts the wholesaler via Whatsapp to ship products, and sometimes lose track of orders or forget to confirm back to the customers.

5.3. Proposed Solutions
To create and develop a feasible, user-friendly digital order booking system that simplifies and automates the process of ordering, managing and meeting the customers needs. It will improve all things accuracy in ordering, delivery, communication between the staff and customers.

5.4 Requirement Specifications
Requirement gathering is important as it captures the needs of a business and ensures the system meets the requirements my client is after. I conducted an informal interview with my client, who is the small business owner and analysed ways to automate the purchase orders for staff, including order tracking and sending, inventory updates, and notifications system that is not in place. 
These were a few questions asked:
1.	What features would be most useful in a digital system? I want customers to see what products are available, place their order themselves, which goes directly to myself and the wholesaler and get an instant confirmation. For me, I’d like to log in and see all the orders in one place and update stock easily
2.	What is the most important for you as the business owner? Saving time and not having to repeat the same mistakes with orders and stocks
3.	How do you want the system to protect customer information? I want my customers details kept safe and not exposed, so only the staff should see them and their passwords should remain secure
4.	Do you need advanced features like marking and customer loyalty tools? That would be nice, but most importantly is a simple working order system and maybe extra features can be a plus in the future
Summary
The business currently takes manual orders and tracked online, instagram direct messaging and Whatsapp, which often leads to errors and inefficiencies. Issues recorded include delays in updating customers, forgotten confirmations, slow communication with wholesalers and occasional loss of order details, leading to dissatisfied customer experience and reduced trust in business. The most important factor for the business owner is saving time and avoiding repeated mistakes with orders and stock management. Security was also identified as a priority, with customer details needing to be kept safe, accessible only to staff, and supported by secure password management
5.4.1 Functional Requirements (What the system must do)
●	Customers can search for products
●	Customers can place orders online
●	Customers receive confirmation
●	Orders are sent automatically to both the staff and wholesaler
●	Staff can view/manage orders
●	Staff can update inventory
●	Secure login for staff

5.4.2 Non-Functional Requirements (Qualities the system must have)
●	Usability: The system must be simple and user friendly for customers and staff - eg, get 5 stars from staffs
●	Security: Customer details must be protected, with restricted access only to staff and passwords must be securely stored (hashing) - using hashing algorithm and no encrypted password
●	Reliability: Orders and stock updates must be recorded accurately without loss of information
●	Performance: The system must be quick with response when customer search or place for orders
●	Scalability: The system should handle potential increase in order placing and search of products
5.4.3 Requirements Prioritisation
Must-Have Features (MVP)
●	Customers can browse and view available products
●	Customers can place orders directly online (without needing Instagram/WhatsApp)
●	Customers receive instant order confirmations
●	Orders are sent automatically to both the business owner and the wholesaler
●	Staff can log in securely to access the system
●	Staff can view all customer orders in one central dashboard
●	Staff can update product stock levels easily
●	Customer details are kept secure, with access limited to staff only

Nice-to-Have Features (Future Development)
●	Advanced business reports (e.g., sales trends, customer behaviour)
●	Automated stock alerts when inventory runs low
●	Marketing tools (promotions, newsletters, loyalty programs)
●	Multi-channel notifications (e.g., SMS, email beyond order confirmation)
●	Integration with payment gateways for real transactions
 




