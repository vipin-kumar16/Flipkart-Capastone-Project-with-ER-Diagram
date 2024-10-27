https://docs.google.com/document/d/1xUh2QBA6xNVzebcFTZD-G5NvCw8jQBQwOBRDMs9IE_E/edit?usp=sharing

Company Overview:
Flipkart Private Limited is an Indian e-commerce company, headquartered in Bangalore,
and incorporated in Singapore as a private limited company. The company initially
focused on online book sales before expanding into other product categories such as
consumer electronics, fashion, home essentials, groceries, and lifestyle products.
The service competes primarily with Amazon India and domestic rival Snapdeal. As of
FY23, Flipkart held a 48% market share in the Indian e-commerce industry. Flipkart has a
dominant position in the apparel segment, bolstered by its acquisition of Myntra, and
was described as being "neck and neck" with Amazon in the sale of electronics and
mobile phones.
Product Dissection and Real-World Problems Solved by Flipkart:
Problem1: The pandemic has changed consumer behavior with evolving trends on both
demand and supply sides. Businesses are being forced to rethink their product offerings as well
as delivery models.
Solution: Leading Indian e-commerce brand Flipkart scaled up its supply chain along
with strengthening safety and hygiene measures to meet the demand of the new
consumer who is preferring to stay indoors.
● The company launched its hyperlocal delivery service to provide consumers with
a handpicked assortment of more than 2,000 products in daily usage categories
such as grocery, fresh, dairy, meat, and other essentials.
● It prioritized grocery deliveries across hundreds of cities to cater to the
burgeoning home demand.
● To help first-time e-commerce users through the purchase journey, Flipkart
launched two new technological features: a search and voice assistant, and
regional-language interfaces.
Vikas Gupta, head of customer, marketing and digital businesses, Flipkart said, “The
role of engagement and communication has never been more important. Post the
nationwide panic and apprehension caused by the pandemic, our marketing approach
has hinged on rebuilding the confidence of consumers, wish masters (as field
executives are known internally at the company), and sellers.”
Business Challenges of Flipkart:
1. Service professionals get many phone calls they are only sometimes able to answer
right away. Thus, customers are experiencing delays and need responses back on
service issues.
2. A few customers added that they needed to be heard correctly. (Swiggy users
register the same issue)
3. Most of the users had their orders canceled.
Indians have been accelerating and waiting for festive sales to purchase their
favorite products from e-commerce websites such as Amazon, Flipkart, AJIO, and
more. Flipkart, in particular, has been a pain for consumers due to a number of
issues.
It is the largest e-commerce marketplace in India, launched in 2007 aims to
provide customers with the most trusted products at the best price and services to
support user experience on their online shopping journeys.
Flipkart shows the best revenue data in its search performance, with customers who
searched for a specific, desired product on the website finding exactly what they
needed. But there was room for growth in its category performance metrics and
service side.
A Product Manager, along with the Engineering team, needs to fix the solution in a
way that validates future success as well. The best way is to first understand the
problem statement by:
1. Evaluating the need
2. Validating the need
3. Set a goal for the feature
4. Decision making for the solution
So, customers often felt that they were not getting the recommendations right and
didn’t hear back for the queries. The service department that assists by learning
more about the customer and recommending a relevant product may need help to
fulfill customers’ needs and get the right solution.
As a Product Manager, I will first focus on solving the problems that customers are
facing and complaining about. The role of the PM is to identify the situation in the
early stage, where communicating with customers is the key. To hear customers out
and understand their queries is critical to offer the best solution, keep customers
loyal, and retain them as soon as possible, providing them with the best digital
experience.
What I understand is that customers are coming to get the best deal in less time and
effort. So, as a Product Manager, I will keep the vision and mission in mind as it will
help gain the outcome of solving all the queries.
Here are some questions I have considered to solve the problem statement:
● How do I validate that the problem exists?
● How do I validate the solution?
● What is the solution?
● How to make multiple prototypes for the Solution?
● How do I bring the solution to market?
● How do I measure success?
● How do I monetize this solution?
Solution:
To tackle this challenge, Flipkart may have used tools like Bloomreach Search,
kissmetrics, and Google Analytics to optimize the issue and get the metrics of
on-site visitors learning and what stage users are facing problems.
-> Another way to optimize and validate the problem is to constantly be in touch
with your customers through direct calls/emails, sales teams, pre-sales demos, and
more on the support side of the product.
Flipkart started using MachineLearning to solve customers’ queries by identifying
the process flow and how to optimize it quickly.
1. As a Product Manager, I focus on Flipkart’s customer support screen to identify
the source of the problem. Ticket resolution is key when support staff is flooded
with multiple tickets.
To automate the tickets to reach the right person, a tickets category is to be added
to identify the priority of the assigned tickets, and employees load on tickets based
on automation.
2. And a solution here is that the Flipkart support and delivery team should start to
work with field executives and supervisors to collect and validate data sets and then
start to label these addresses.
3. Flipkart can scale up its order integration stage and strengthen safety measures to
meet the consumer’s demand-facing the failed order. The right thing to do is to
solve the bug from the order page and make it more lively by reducing the load from
other unprioritized JS code when the festival session starts.
Schema Description:
The schema for Flipkart involves multiple entities that represent different aspects of the platform.
These entities include User, Product, Order, Payment, Review, Recommendation, and more.
Each entity has specific attributes that describe its properties and relationships with other
entities.
Seller Entity:
A Flipkart seller is a person or business that sells products on Flipkart, India's largest online
store.
● Seller_name: Name of the seller who wants to sell the product on flipkart.
● seller_rating: It measures the product quality and service quality.
● Seller_id (Primary key): A unique identifier for each seller.
Users Entity:
Users are at the core of Flipkart. The user entity contains information about each user:
● UserID (Primary Key): A unique identifier for each user.
● Username: The chosen username for the user's account.
● Email: The user's email address for account-related communication.
● Phone_number: The user's phone number as they login into their profile.
● Address: This address is used to order any product and the product will deliver
To this address.
Product Entity:
The company offers a wide range of products including electronics ,fashion items , groceries ,
home and kitchen products , automobiles , books and stationery.
● product_id (Primary Key): A unique identifier for each product.
● product_name: The chosen product name for any particular product.
● description: Listing a product in simple words means filling out all the necessary
information about the goods and adding images.
● Category: Product category refers to the process of classifying and organizing products
into distinct categories based on shared characteristics,attributes.
● Price: This entity is used to show how costly our product is !
● seller_id (Foreign Key Referencing Seller Entity ) : unique id generated for each
seller by Flipkart.
Orders Entity:
Order contains details about the product , like price , order id and name of the product.
● order_id (Primary Key): A unique identifier for each order.
● User_id (Foreign key Referencing User entity): A unique identifier for each user.
● Product_id (Foreign key Referencing Product Entity): A unique identifier for each
product.
● quantity: On Flipkart, quantity refers to the number of items ordered.
● order_date: An estimated delivery time that depends on several factors, including the
seller, the product's availability, and the destination.
Review Entity: A review on Flipkart is a user-written post that includes a rating, title, text,
author's name and location, and upvotes and downvotes.
● Review_id (Primary Key): A unique identifier for each Reviewer.
● User_id (Foreign key Referencing User entity): A unique identifier for each user.
● Product_id (Foreign key Referencing Product Entity):A unique identifier for each
product.
● Rating: Flipkart's rating system allows customers to rate products with 1–5 stars.
● Review_text: This is the actual review written by a user.
Recommendation Entity: Flipkart's recommendation system uses a combination of
collaborative filtering and content matching to suggest products based on a customer's
preferences.
● Recommendation_id (Primary Key): A unique identifier for each Recommender.
● User_id (Foreign key Referencing User entity): A unique identifier for each user.
● Product_id (Foreign key Referencing Product Entity):A unique identifier for each
product.
● Recommendation_Score: A new item is recommended according to the maximum
number of ratings given by the user in a genre.
Payment Entity: Apart from Credit and Debit Cards, we accept payments via Internet Banking
(covering 44 banks), Cash on Delivery, Equated Monthly Installments (EMI), E-Gift Vouchers,
Flipkart Pay Later, UPI, Wallet, and Paytm Postpaid.
● Payment_id (Primary key): A unique identifier for each payment.
● order_id (Foreign key Referencing Order Entity): A unique identifier for each order.
● Total_amount: It is the total amount of the orders.
● Payment_date: It is the date for the payment of the payment method like Flipkart Pay
later , Cash On Delivery.
● Payment_method: It depends on the payment method like Flipkart Pay later , Cash On
Delivery , UPI etc.
Relationships are:
● Users place Orders
○ Each user can place multiple orders.
● Products are included in Orders
○ Each product can be included in multiple orders.
● Users make Payments
○ Each user can make multiple payments.
● Orders have Payments
○ Each order can have one payment.
● Users write Reviews
○ Each user can write multiple reviews.
● Products have Reviews
○ Each product can have multiple reviews.
● Users receive Recommendations
○ Each user can receive multiple recommendations.
● Products have Recommendations
○ Each product can have multiple recommendations.
● Sellers sell Products
○ Each seller can sell multiple products.
User places Order (One-to-Many)
Product is included in Order (One-to-Many)
User makes Payment (One-to-Many)
Order has Payment (One-to-One)
User writes Review (One-to-Many)
Product has Review (One-to-Many)
User receives Recommendation (One-to-Many)
Product has Recommendation (One-to-Many)
ER Diagram:
Let's construct an ER diagram that vividly portrays the relationships and attributes of the entities
within the Flipkart schema. This ER diagram will serve as a visual representation, shedding light
on the pivotal components of Flipkart's data model. By employing this diagram, you'll gain a
clearer grasp of the intricate interactions and connections that define the platform's dynamics.
Conclusion
In this case study, we delved into the design of Flipkart's schema and Entity-Relationship
diagram.
To sum up, the database schema covers how users interact with the platform and the products
available. It captures relationships like users placing orders, making payments, writing reviews,
and receiving recommendations. It also shows how products, orders, users, payments, reviews,
recommendations, and sellers are connected. These connections are important for making the
e-commerce platform work smoothly
