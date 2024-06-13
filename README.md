# Description of Business System Summary:


 ## Please note that all dataset are assumptions.

This Project will explore hospitality and accommodation industry by creating database on student lodging information management system for a business (Campusstay solutions). A business that helps students solves accommodation issue while on campus. This business has four hostels for reservation by students. A functional database will help the business increase satisfaction of users & operational efficiency. This database will optimise important process such as booking, payment, check-in and checkout date etc. Based on the database interface, data generated from users can be used by the business to draw insight on user preferences, revenue & cashflow management, resources allocation, inventory management and business forecast. Creating a student lodging information management system involves structured classification process of the entities, attributes, relationships and the cardinality to properly illustrate the scheme and functioning of the system. The key entities considered for creating the database were seven which are: 

- Student entity stores information about students such as name, age etc. which help to manage student service histories.
-  Hostel entity represents an individual hostel property within the system. It retains important information about each hostel such as name, email, etc.
-  Room type entity represents the different types of room available in the facilities(hostel) based on capacity. Data from room type can help make inform decision on inventory management.
-  Room entity defines each room in the hostel, The room is associated to Hostel and Room type which enables room allocation.
- Booking entity helps in managing reservation and allocations of rooms and payments.
 -Payment entity is linked to booking and store any financial transaction made by users.
- Staff entity represent the hostels representative, socio demographic characteristics such as name, age etc. were captured as attributes.
Through the aforementioned entities in the database the business can manage and have a smooth business evaluation for decision making.

## Schema Representation:
- Logical Schema

<img width="653" alt="framework" src="https://github.com/olaiyaaminat/Hostel-Lodging-Analysis/assets/150556677/d838f6db-144e-49c3-a56a-c4afbc9ee5bc">


- Physical Schema
  ![image](https://github.com/olaiyaaminat/Hostel-Lodging-Analysis/assets/150556677/9286496b-e8c7-4ced-a5cd-b7ca68e43e31)

  ## 	Representation of Tables from the Server:

  Structural Representation of “Student” table:
  
  ![image](https://github.com/olaiyaaminat/Hostel-Lodging-Analysis/assets/150556677/a88fc5fe-07d1-4d63-b6fc-b060e0782eff)

  Representation of “Student” table (Populated with Data):
  
![image](https://github.com/olaiyaaminat/Hostel-Lodging-Analysis/assets/150556677/329d02a7-7a6a-4275-a5bb-fc09d8dad97e)

Structural Representation of “Booking” table:

![image](https://github.com/olaiyaaminat/Hostel-Lodging-Analysis/assets/150556677/3be01b20-f8a1-4cb3-9c29-4bedd766eb1f)

Representation of “Booking” table (Populated with Data):

![image](https://github.com/olaiyaaminat/Hostel-Lodging-Analysis/assets/150556677/2d0bd6da-c5c3-404e-ac53-a73c2ebf7ea6)

Structural Representation of “Payment” table:

![image](https://github.com/olaiyaaminat/Hostel-Lodging-Analysis/assets/150556677/fc9e94ef-4799-48a6-ae2d-ff782e7b7aca)

Representation of “Payment” table (Populated with Data):

![image](https://github.com/olaiyaaminat/Hostel-Lodging-Analysis/assets/150556677/94dd3091-7e45-4a31-955d-225d4930cb75)

Structural Representation of “Room” table:

![image](https://github.com/olaiyaaminat/Hostel-Lodging-Analysis/assets/150556677/410ba75f-9a2d-4a4d-b7eb-221e641560b4)


Representation of “Room” table (Populated with Data):

![image](https://github.com/olaiyaaminat/Hostel-Lodging-Analysis/assets/150556677/fd553ad3-34b2-4816-ac8b-425ba7d80215)

Structural Representation of “Room Type” table:

![image](https://github.com/olaiyaaminat/Hostel-Lodging-Analysis/assets/150556677/ec195d19-e672-41dd-bbf4-ea612ac90db7)


Representation of “Room Type” table (Populated with Data):

![image](https://github.com/olaiyaaminat/Hostel-Lodging-Analysis/assets/150556677/d81bfd3b-c3a2-4b17-8d6b-81a479bc426f)

Structural Representation of “Hostel” table:

![image](https://github.com/olaiyaaminat/Hostel-Lodging-Analysis/assets/150556677/43e89ab0-305a-4be6-afaf-181647c97735)

Representation of “Hostel” table (Populated with Data):

![image](https://github.com/olaiyaaminat/Hostel-Lodging-Analysis/assets/150556677/c50106e0-5afe-4acb-9126-fdc9b116727a)

Structural Representation of “Staff” table:

![image](https://github.com/olaiyaaminat/Hostel-Lodging-Analysis/assets/150556677/20ccbc9e-3c50-4488-95d7-5d58946da843)

Representation of “Staff” table (Populated with Data):

![image](https://github.com/olaiyaaminat/Hostel-Lodging-Analysis/assets/150556677/f2072072-201b-4e9a-8541-a23c25f5fca4)



## Demonstration of Business Scenario and small Analysis:

### Data Query Language:1 
 - Finding the most booked room type by counting how many times each room type has been booked.

![image](https://github.com/olaiyaaminat/Hostel-Lodging-Analysis/assets/150556677/45d32e0a-dce2-4e63-8767-a5c30d9acd71)

  ### Justification of Data Query Language:1 
The report generated above from the DQL1 operation, will help CampusStay Solutions to draw meaningful insight by knowing the most frequently booked room type by student which will contribute to the success of the business. For the report generated, Ensuite is the most booked room by student while Single bed room was not booked at all. This is a valuable derivation which will help CampusStay Solutions to manage inventory by allocating more resources to maintain the rooms by providing more resources that could help student book the room (Single room) that wasn’t book at all and also optimise the highly booked room. 

### Data Query Language:2 
- Finding the occupancy ratio for each hostel by comparing the number of occupied rooms to the total of available rooms.

  ![image](https://github.com/olaiyaaminat/Hostel-Lodging-Analysis/assets/150556677/d0dd777e-cb0f-4d56-bf5b-2091f7b4c03e)

  ### Justification of Data Query Language:2
The report generated above from the DQL2 operation will help CampusStay Solutions to adjust pricing strategy for Hillside and Planters Inn as the two appears to have the lowest occupancy ratio. Discount and promotions can be offered to student when booking which can aid considering the two hostels. Similarly, the management can plan and allocate more resources such as sufficient staffs and maintenance services to the other two hostel with high occupancy rate which are Obsidian Sky and Rodeway Inn to maintain the standard. This will help in having a better occupancy ratio in the future and a well-maintained resource as well as student satisfaction.

### Data Query Language:3
- Finding the trend of booking and payment received for each hostel by estimating the total revenue generated by each hostel by name based on payment received.

  ![image](https://github.com/olaiyaaminat/Hostel-Lodging-Analysis/assets/150556677/b659f90d-1488-44a1-ae2e-ea2131bc4b58)
  
### Justification of Data Query Language : 3
CampusStay Solutions can use the report generated from DQL3 to track financial management as tracking accurate revenue is crucial for businesses. It appears Rodeway Inn have the lowest revenue followed by Planters Inn this appears the hostel is thriving and needs improvement in marketing strategy and special promotion for booking which can be embark on to boost revenue. Hillside is also striving but quite better for the aforementioned two hostels however Obsidean Sky have the highest revenue. Knowing the revenue for the hostels will help CampusStay Solutions to set goals, forecast and plan for the business.

### Data Query Language:4
- Finding students with late or overdue payment that is payment date greater than check out date.

![image](https://github.com/olaiyaaminat/Hostel-Lodging-Analysis/assets/150556677/7189c91d-1e41-4887-a2cc-9c51109a5318)


### Justification of Data Query Language : 4
The report generated above from the DQL4 operation will help CampusStay Solutions manage cash flow. Student Lauren Conner owe the highest debt while Student Bella Guerero owe lesser. With the information the management can reach out to the student affected to pay up debt. Also, by identifying and monitoring overdue payment CampusStay Solutions can ensure they have financial stability and ensure sustainability by preventing future occurrence.

### Data Query Language: 5
- Finding the total number of students in each hostel.
- 
![image](https://github.com/olaiyaaminat/Hostel-Lodging-Analysis/assets/150556677/abbeb086-7482-41df-8919-ba3e32536dc1)

### Justification of Data Query Language : 5
CampusStay Solutions can use the report generated from DQL5 to know numbers of students in each hostel. From the report Obsidian Sky and Hillside have the same allocation of students while Planters Inn have the lowest. This can be used to decide the allocation of resources among the hostels. Rodeway can have the highest allocation of resources. CampusStay Solutions can plan effectively drawing insight from DQL5 output and also determine the under or over utilization. It will help to forecast if expansion is required at any point.


### Data Query Language: 6
- Finding the payment methods used by students for payment after booking.
  
  ![image](https://github.com/olaiyaaminat/Hostel-Lodging-Analysis/assets/150556677/2bdf071d-015f-4edc-a468-6406c1385e24)

### Justification of Data Query Language : 6
The report generated above from the DQL6 operation, will help CampusStay Solutions know the most used payment method by students. The report revealed credit card is most used by students for booking payment transactions. Knowing the most used payment method, CampusStay Solutions can optimize payment process and ensure timely and cost-effective handing of transactions. Knowing the payment method will also contribute to the business success and smooth payment handling.



