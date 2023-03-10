---
id: full-text
title: Full Text
sidebar_label: Full Text
---

# Introduction

**Project Title:** HokieRide

**Authors:** Aparna Ganesh, Mayur Dhepe, Purna Srivatsa, Rama Krishna Pinnimty

## Background

Our motivation stems from the need of university students trying to find rides when traveling short or long distances, especially during busy days when events take place (e.g game days, fests) or even late nights. It shares close resemblance to existing ride-hailing apps on the market however, our service prioritizes safety and the concept of carpooling more. We aim to address safety by developing HokieRide, an application that includes a verification system for the drivers and riders as authenticated students or faculty of Virginia Tech. In addition, the system will be linked to the campus police department in the case of any emergencies. The details regarding the location of the driver's car and the identity of the driver and passengers during a ride sharing trip will be shared. If successful, we hope to market this service to other universities and recruit members to fine-tune our system as needed for each university. In addition, we’d like to incorporate a credit system for those who offer rides by having some reward provided by the university to encourage carpooling. Our vision is to offer something different than the popular apps like Uber and Lyft by creating an affordable option and allowing students to feel greater safety by riding with their fellow university peers or staff.

The proposed system is relatively novel as it tries to address a unique set of transportation demands and challenges of the university. While there are applications like Uber and Lyft that are developed to primarily serve the general public, rise in their fares poses yet another obstacle for college students. Furthermore, the design of these applications is rather complex with a lot of irrelevant features. Additionally, our system also includes a mechanism to easily reach out to Virginia Tech’s campus police department for additional safety and security.


<figure>
  <img src="assets/hokieride.png" alt="VT Carpool system." width="600px"/>
</figure>

<div style="text-align: center">
  <a href="https://vtx.vt.edu/articles/2010/09/091510-tcs-rideboard.html">Students carpooling at Virginia Tech. </a>
</div>

# Requirements Summary
## Use Cases

The following use cases presented are examples of different situations that are quite common cases for students in Virginia Tech. They provide realistic scenarios under which they explain how our application could be of service to the needs specified in each scenario. 

### Use Case #1 - Game Day

Ben is a sophomore student at Virginia Tech majoring in Business Information Technology. He is attending his first college football game that is happening on November 8th against the University of Virginia at the Lane Stadium. The game commenced at 3:30pm and will end at 7:00pm. Once the game finishes, everybody rushes to catch the nearest bus, uber or get a lift from their friends to their desired destination. Ben has been waiting at the 1127 Lane Stadium bus stop to catch the HXP bus to Newman Hall since there is  no direct bus to his apartment. Once he reaches Newman, he waits for the next UCB bus to arrive. He sees that the bus is already nearly full and very few people are able to get on. He waits for the next bus to arrive in the next 15 minutes. Upon arrival, he notices that the new bus is running at full capacity as well. Frustrated, he tries to find an Uber but the next one available is 20 minutes away and the pricing is much higher than normal. He gets worried that the situation in the next hour or so is not going to improve due to the sheer amount of students that are trying to commute to different places. Ben notices that there are other students who have had the opportunity and liberty to have had a car to go to their destination or have had someone they know, with a car, pick them up. He wishes there was a system that would allow a safe and easy way to carpool with other students who are also heading in the same direction as him during this busy time.


### Use Case #2 - Long Distance Travel

Alizeh is an international student in her senior year. She has graduated with a degree in Computer Engineering and her commencement day was a week ago. She is planning to travel back home for the summer and needs to get to Dulles International Airport to take her flight back to Dubai.  Alizeh does not have a car to use to commute. She looks at her 4 primary options that are commonly known which are the Virginia Breeze, Amtrak, Uber/Lyft, or find another student with a car who is also traveling through her social circle or through facebook pages (e.g, a popular one being Hoos Riding UVA/VT Edition). She is traveling with two medium-size suitcases. The Virginia Breeze option, although affordable, does not allow for more than one suitcase per passenger, so this eliminates this option. Amtrak is also another affordable choice, however, it involves many stops as it involves her going to Roanoke first and then catching the train. Amtrak does not have a stop near the airport, so there is another commute that needs to be done. Due to the two extra trips needed, it makes the trip to the airport stressful for the flight that she has to catch at 3:30pm. This makes Amtrak a difficult choice to opt for. Additionally, Uber/Lyft is another easy option that would take her straight from her choice of Point A to Point B, however, this is a very unfeasible option because it would cost easily more than $500.  As a college student, this is not an affordable option. Facebook pages are difficult to track because posts can happen at any time and there is no guarantee of getting a ride at the time and day you want. She knows that many VT students live in the Northern Virginia area which pass by the airport and she wishes there was an easy and quick way to find and book rides with people who were willing to give her a ride.


## Stakeholder Analysis

There are three primary stakeholders associated with the HokieRide application: the riders,  drivers, and  Virginia Tech campus police department. Understanding their technical background and familiarity, along with what their expectations and preferences would be from this product is important in order to tailor the system design to meet their requirements to the best possible extent. 

### Riders

Those who are eligible riders of the application would be students and faculty of Virginia Tech, hence their technical knowledge to use a mobile application would be at a sufficient level for them to easily navigate through the app. As a rider, it is crucial that they are able to search and view all nearby available drivers along with the driver’s ratings. If they choose to accept a driver, they should have the ability to cancel, or should they choose to continue, they should be able to see a map with the driver’s real-time location as they approach the pickup spot and an estimated time of arrival. Riders should also indicate whether they are traveling solo or as a group to ensure that the driver is able to pick up all passengers in his/her car. Email and/or SMS notifications should be received to indicate the driver’s arrival and another should be sent out when the trip has been completed. Upon completion of the trip, the rider should be able to rate the driver. Additionally, due to unforeseen circumstances, if there occurs an accident or a threat to the rider’s safety, they should be able to quickly contact the campus police department for assistance.

### Drivers

Verified drivers are also going to be those who are students and faculty of Virginia Tech and therefore, would also be very comfortable with a smartphone and mobile applications. Drivers should be able to create a ride depending on the location that they are at and where they are going to, and should get requests as riders choose them. They should be able to choose the number of riders based on their car seat availability. If at full capacity or the driver chooses to not accept any more riders, he/she should be marked as unavailable to other riders searching for a ride. Additionally, based on the number of rides that drivers give to other Virginia Tech students and faculty, they should be able to see their credits accumulate and be used as either deposits into their Hokie Wallet or for free parking during school hours. Lastly, if there is any serious emergency, the driver should be able to notify the Virginia Tech campus police department for help.

### Virginia Tech Campus Police

Similar to the other stakeholders involved, the campus police department would be very familiar with technology of this degree, both with web and mobile-based applications. It is important that the campus police department is able to easily access data regarding students and faculty who are using the HokieRide app. Therefore, there should be options to search up information about a user's ride history and ride information by looking up their name or through HokieID. There should be sufficient information displayed about each user and their ride in the case of any emergency. This involves the user’s name, email, mobile phone number, HokieID and identification photo. Moreover, details about their past and current ride(s) should be visible with details regarding the start and end destination, current location, registered car model, and license plate. If the emergency alert button is clicked by any user, the web application will notify the department in a quick manner so action can be taken.The alert will contain details about the ride it is occurring on.


## Requirements

The requirements of this software application will be recognized as to cater to the students and faculty, especially at Virginia Tech. The customer of this application will  be the university that is willing to participate with the application built. Although there is scope to expand this application to many universities, in order to keep it as narrow and focused as possible, the customer will be Virginia Tech. The intended user will be the students and faculty that attend Virginia Tech. Since, there is potential for other universities to link up with our product, we will take this into consideration when designing our system. 


### Functional Requirements

- **FR-1** - Students and faculty of Virginia Tech can self-register for an account on the HokieRide app by providing first name, last name, email address, HokieID, and optionally their phone number.
- **FR-2** - In order to use the application, the system must verify all accounts to be identified as Virginia Tech students and faculty.
- **FR-3** - After verification, all users may login with unique credentials (username and password).
- **FR-4** - Riders should be able to search for all nearby available drivers that are heading in the same direction or within a 2 mile radius of the driver’s chosen destination.
- **FR-5** - Riders and drivers should be able to request and cancel a ride if needed.
- **FR-6** - Once a ride is accepted by a driver, riders and driver should be able to see each other’s location and riders should view an estimated time of arrival (ETA) until the trip is completed.
- **FR-7** - The location and ETA should constantly be updated as the driver moves.
- **FR-8** - Drivers should be able to create a ride and specify source, destination and number of riders he/she is able to accommodate in their car.
- **FR-9** - Email and/or SMS notifications should be sent out when the driver has arrived and when the trip has been completed.
- **FR-10** - Riders and drivers should be able to rate each other at the end of the trip.
- **FR-11** - Users should be able to view their history - rides taken and rides offered.
- **FR-12** - System should provide a credit system, agreed upon by Virginia Tech, that accumulates points to be transferred as a deposit into Hokie Wallet or provided as parking spots during weekdays for free.
- **FR-13** - All users will be able to use a “Alert VT Police” button which will send a notification to the campus police department for assistance.
- **FR-14** - The system will provide a web-based application to display an interactive database for the Virginia Tech Campus Police Department.
- **FR-15** - The web-based application will allow officers to look up users by first name and last name, and also HokieID.
- **FR-16** - Search results will show information about the user such as name, email, phone number and picture. Additionally, the user’s ride history, current trip details (if on a trip) which includes start location, destination, car mode, license plate number, and current location will be displayed.
- **FR-17** - Should there be an emergency, the system should send out a notification to the web-based application to alert the police of a potential incident.


### Non-functional Requirements

- **NR-1** - The application should be scalable in order to meet the user demand.
- **NR-2** - Both mobile and web applications should abide by the Web Content Accessibility Guidelines 2.0 (WCAG).
- **NR-3** - Use SSL Certificates with HTTPs for APIs and Web Content Accessibility
- **NR-4** - Use a common package to handle both Cookies and Session maintenance. Initial stage of security is modular.
- **NR-5** - Validate users by email addresses. Send verification email to the user with a clickable link to validate authentication.
- **NR-6** - Use Virginia Tech API(s) to validate active accounts (active students and staff) upon email account verification.
- **NR-7** - Design a highly decoupled system to facilitate connections with external third-party APIs, services and more. 
- **NR-8** - Data backups must be made on a daily basis.
- **NR-9** - Data backup storage containers should be of low cost. Speeds can be reduced to minimum. Only enough for daily traffic updates.  
- **NR-10** - Use MongoDB to store Documents (JSONs). Better storage management of routes taken.
- **NR-11** - Efforts towards obtaining real-time updates on searches, locations, ETAs and other notifications with little-to-no lag.
- **NR-12** -	Prioritize speeds to searching for rides compared to other minor features like fetching ride histories for users.
- **NR-13** - Any and all operations related to security and safety such as emergency notifications, ride searches on web-application, should be quick (< 2 seconds) and seamless.
- **NR-14** -	Store ride availability status details in a separate Database table to increase read writes for the sole purpose of searching for rides. Maximizes speeds by reducing calls made to the database by other features. 
- **NR-15** -	Encrypt all customer data using 1 encryption type. As this data can be set as Confidential.
- **NR-16** -	Encrypt passwords with another stronger encryption type. This is crucial for minimizing password hacks.
- **NR-17** -	Allow for error logs to be made so that maintenance can be done once/twice a week.
- **NR-18** -	Develop all functionality using APIs as it can be used between all platforms (Browser and Apps). No major in-app/in-browser computing and processing.


# High-Level Design

## Layered View of our system

Based on the requirements of the system, we have identified five core components: a non-relational cloud database, a relational cloud database, REST API, a web application and a mobile application. Furthermore, the distribution of these modules into Data, Application and Presentation Layers is done following a 3-tier architectural pattern. The Data Layer is responsible for storage and retrieval of the data. We plan to use MongoDB and SQL cloud databases since it offers high reliability and availability, considering the large number of expected connections. The Application Layer is composed of REST APIs developed internally along with those provided by various third parties (Google Map API etc.). Apart from this, the layer is also responsible for all of the business logic, including authorization and access control. Lastly, the Presentation Layer enables the end-users to interact with the system using web and mobile interfaces. Particularly, the system has to be used by users in mobility, so the access to the system has to be guaranteed by mobile devices. Accordingly, the design of the system architecture takes this into account, and the front-end layer will be designed for mobile devices, considering the major operating systems (iOS and Android). Overall, the applications in the presentation layer communicate with the REST API in the application layer to interact with the data within the databases in the data layer.

As already mentioned, the system follows the mobile-cloud paradigm. The mobile client allows the users (drivers and riders) to access the carpooling service. Its sensors (e.g., GPS) are used to simplify the access to the service and to enhance the user experience. The web client provides useful information concerning trips and users to the police and emergency services. For all communications toward the server, JSON format will be used. The REST API is the core of the system as it enables the access of users, processes all requests, calculates the matching between requests and available drivers and offers rides. Additionally, the push notification services are used to send real-time messages to the smartphones. The cloud database has the task to store all data useful for the service: user profile, ride offers, ride requests, trips, payments, feedback and other information.


<figure>
  <img src="assets/layered-arch.png" alt="Three-layer diagram of system." width="700px"/>
  <figcaption>Three-layer architecture: Presentation Layer, Application Layer, and Data Layer.</figcaption>
</figure>


## System Interface

The following sections will go into depth of the design of the four core components. All of the decisions that were made were directly or indirectly in support of the functional and non-functional requirements. Lastly, to realize the design and maintain high customer satisfaction, we aim to use the latest cutting-edge technologies.


The overall system can be broken down into Ride, Driver, Rider, and Global Data components. Specifically, the Ride component will have the Trip Status, Payment and Map interfaces. The Driver component will have interfaces for handling Profile, Cab and History information. The Rider component will have interfaces to process the Profile and History related information. Finally the Global Data component will have an interface to calculate the metrics concerning rides and drivers.


<figure>
  <img src="assets/sys-interface.png" alt="System Interface Diagram" width="700px"/>
  <figcaption>System Interface Diagram</figcaption>
</figure>


All the essential functionality in our HokieRide application can be broadly classified as Profile, Ride and Metric related information. First, the Profile functionality is common to both drivers and riders and should include their personal information, profile photo, credentials etc. Additionally, the driver profile should also have details about the model and type of the car they wish to serve the customers. Second, the Ride functionality should always indicate the current status of the trip which could be cancelled, not yet started, in progress, or completed. If the ride is in progress, all the concerned parties should be able to view the estimated time of arrival, map of the ride so far and links to emergency services. And after the successful completion of the trip, the rider should be presented with the total fare and the available payment options. Lastly, to motivate hesitant riders, we plan to show the longest and shortest rides taken by fellow customers to show the flexibility of our service. Also, to reward the drivers, we plan to show information about the top rated drivers within the month and local to a given area.


<figure>
  <img src="assets/system-func.png" alt="System Functionality Diagram." width="700px"/>
  <figcaption>System Functionality Diagram</figcaption>
</figure>


## System Architecture

<figure>
  <img src="assets/system-arch.png" alt="System Architecture Diagram" width="700px"/>
  <figcaption>System Architecture Diagram</figcaption>
</figure>

The above diagram represents the high level design of HokieRide application. Load balancers will be used to redirect and distribute the traffic to web servers. Web servers would route requests to various application servers like Ride Availability servers, Notification servers, etc. Fanout service would push the data requested or the available rides data to the messaging queue. Cache DBs would be used to store ride availability data for fast retrieval and querying of active rides data. Notification requests from messaging queues would be processed by Notification server and delivered across various channels.

We also propose to use a content delivery network(CDN) that is directly connected to the client or the presentation layer to deliver static files and assets that need not be stored in persistent DBs and accessed from there every time. The architecture would also aim to be stateless in the sense that the state of the client is stored and persisted at the data layer making it accessible to all the servers in the application layer. This allows for every server to operate and process every client and can lead to efficient distribution of requests and load. As the product spreads to multiple universities in different geographic locations, the entire application and data layer can be replicated at the infrastructure level in multiple data centers strategically located to cater best to all the universities that the product serves. We also propose our data layer to be following the master-slave DB architecture where there is one master DB that is used for all write  operations and multiple slave DBs that are used for read operations as in this appplication read operations are more intensive and frequent compared to write operations. The master slave architecture allows for less downtime too as master and each slave maintain data integrity and veracity so that the load can be distributed and a slave can also act as temporary master in the case that the master DB fails. We use a noSQL database for faster serialization and deserialization of data.

## Database Design

Databases can have two main types: SQL and NoSQL (or relational databases and non-relational databases). They are both different in terms of how they were built, the kind of information they hold, and the storage technique they employ. We will be using MongoDB as our primary database and MySQL or any other relational database as a cache that can provide fast IOs.

For the application to scale for millions of users, databases need to be horizontally scalable so that we can add more servers easily in our NoSQL database infrastructure to handle a lot of traffic. Cloud-based storage is an excellent cost-saving solution but requires data to be easily spread across multiple servers to scale up and databases like MongoDB are designed to be scaled across multiple data centers. The database would have separate collections to store data about various entities on our application i.e. Drivers, Riders, Past Rides, Cars, Location related data which would not be queried that frequently.

However, the driver location information and ride availability status details need to be read and updated frequently to search for available rides. We should be able to prioritize speeds to searching for rides compared to other minor features like fetching ride histories for users. For this purpose, we are storing ride availability status details in a separate database table to increase read writes for the sole purpose of searching for rides. This is called Database caching strategy since it assists in reducing the burden on the primary database. Caches are high-speed data storage layers that keep a subset of the data that is frequently requested for reading. The most typical instance of this is when frequently accessed data is redirected from the main database to the cache itself. The cache itself could be an independent access layer or sit in a database or application. 


<figure>
  <img src="assets/database.png" alt="Database Table Diagram." width="700px"/>
  <figcaption>Prototype of database table design.</figcaption>
</figure>

The diagram above represents a prototype of our database design where the primary database is MongoDB and the cache database i.e. Ride Availability DB is SQL. Primary DB is for storing user related information like Name, Email, HokieID, Rating, etc of both kinds of users i.e. drivers and riders. There would be a separate collection to store the Ride history related data that would consist of driver, riders, source, destination, and other details regarding a specific ride. The location would be stored in terms of latitude and longitude and would constantly be updated for an active ride.

The secondary DB or the cache would have 2 SQL tables to store information about active rides and these tables would frequently get updated and read to determine the availability of rides as per the request from the riders.
Data backups will be made on a daily basis and the data would be replicated across multiple servers to ensure high availability.


## REST API Design

All functionality will be developed using APIs as it can be used between all platforms meaning mobile applications, web-based applications or any other user interface.
In a client-server architecture, Representational state transfer (REST) is a kind of software architecture that describes a consistent interface between physically distinct components, frequently over the Internet. 
REST API is designed around resources which can be business entities of your application. In our case the entities are mainly the users of the application - drivers and riders, Ride, Location and Car.
The most common operations on these resources are GET, POST, PUT, PATCH, and DELETE.

We will be using the Data Access Object (DAO) design pattern in our REST API, as shown in the diagram below.


<figure>
  <img src="assets/dao.png" alt="DAO design pattern for REST API." width="700px"/>
  <figcaption>DAO design pattern for REST API.</figcaption>
</figure>

### DAO

DAO stands for Data Access Object. The data persistence logic is separated into a distinct layer using the DAO Design Pattern. The service is fully kept in the dark regarding how the low-level actions to access the database are carried out in this fashion. This is known as the principle of Separation of Logic.


### MVC pattern

The overall architecture of the system would be similar to MVC architecture where View would be the client side of the application - mobile/web application, Controller, Service and DAO would be the server side of the application or the REST API layer of the application. Services contain the business logic of the application and DAO layer would contain the data persistence logic and each entity would have its own DAO class. The diagram below shows the MVC design pattern that can be applied to the current system.


<figure>
  <img src="assets/mvc.png" alt="MVC pattern for the system." width="700px"/>
  <figcaption>MVC pattern for the system</figcaption>
</figure>

### System Components and General Flow

The diagram below represents various components or services and their relationship within the application.

<figure>
  <img src="assets/components.png" alt="System Components." width="800px"/>
  <figcaption>System Components and general flow</figcaption>
</figure>


- Initially, both riders and drivers will have to verify their accounts through the external Virginia Tech API. The Hokie ID would be used as an identifier. 
- Riders and drivers can view or update their profiles and UserService would be used for these operations. It would fetch/update records from the primary DB (MongoDB).
- Rider Availability Service would process requests from riders to search for all nearby available drivers that are heading in the same direction or within a 2 mile radius of the driver’s chosen destination. It would get the data from the cache i.e. the Ride Availability database (SQL).
- Riders and drivers can view their past rides taken or rides offered using the Ride History Service which would retrieve data from Primary DB.
- Drivers can view their credits earned in their Hokie Wallet based on the rides offered. This processing would be done by the Driver Credits Service. 
- The location and ETA would be constantly updated as the driver moves. The Driver Location Service would constantly update the location coordinates of the driver’s car using GPS and store the latest coordinates into the cache.
- The Notification Service would process notification requests to various channels like SMS, email, VT campus police web applications.
- The Emergency Alert Service will send a notification to the campus police department for assistance.


### API Endpoints

All REST API endpoints should be private or protected in some fashion for the initial set of requirements. We don't want any anonymous sources to be able to use the API.

Some of the API endpoints would be as follows:

- Mobile application for drivers and riders -

<table>
  <thead>
    <tr>
      <th>API Endpoint</th>
      <th>Method</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>/user/login</td>
      <td>POST</td> 
      <td>Accepts credentials from driver/rider and returns API token.</td> 
    </tr>
    <tr>
      <td>/user/register</td>
      <td>POST</td>
      <td>Accepts registration details from drivers and riders.</td>
    </tr>
    <tr>
      <td>/user/:id</td>
      <td>GET</td>
      <td>Gets user profile information.</td>
    </tr>
    <tr>
      <td>/user/:id</td>
      <td>POST</td>
      <td>Updates user profile information.</td>
    </tr>
    <tr>
      <td>/user/:id/rides</td>
      <td>GET</td>
      <td>Fetches history rides - rides offered for driver and ride taken for rider.</td>
    </tr>
    <tr>
      <td>/user/:id/verify</td>
      <td>POST</td>
      <td>Verifies the rider/driver account through an external API call to Virginia Tech’s system/API using HokieID as the identifier.</td>
    </tr>
    <tr>
      <td>/ride/search/:{request}</td>
      <td>POST</td>
      <td>Search for all nearby available drivers that are heading in the same direction of the driver’s chosen destination.</td>
    </tr>
    <tr>
      <td>/ride/cancel/:id</td>
      <td>POST</td>
      <td>Cancels a ride - rider and notifies on SMS and Email</td>
    </tr>
    <tr>
      <td>/ride/start/:id</td>
      <td>POST</td>
      <td>Starts a ride - driver and notifies on SMS and Email</td>
    </tr>
    <tr>
      <td>/ride/end/:id</td>
      <td>POST</td>
      <td>Ends a ride - rider and driver and notifies on SMS and Email</td>
    </tr>
    <tr>
      <td>/ride/join/:id</td>
      <td>POST</td>
      <td>Join a ride - rider and notifies on SMS and Email</td>
    </tr>
    <tr>
      <td>/ride/update</td>
      <td>POST</td>
      <td>Constantly updates the ride's current location and the ETA to the destination.</td>
    </tr>
    <tr>
      <td>/ride/create</td>
      <td>POST</td>
      <td>Creates a ride with specific source, destination, car capacity - driver</td>
    </tr>
    <tr>
      <td>/ride/driver/rate</td>
      <td>POST</td>
      <td>Rate the driver for the particular ride</td>
    </tr>
    <tr>
      <td>/ride/rider/rate</td>
      <td>POST</td>
      <td>Rate the rider for the particular ride</td>
    </tr>
    <tr>
      <td>/driver/processCredits</td>
      <td>POST</td>
      <td>Accumulates points to be transferred as a deposit into Hokie Wallet.</td>
    </tr>
    <tr>
      <td>/sendAlert</td>
      <td>POST</td>
      <td>Send out a notification to the web-based application to alert the police of a potential incident.</td>
    </tr>
  </tbody>
</table>

- Web-based application for VT campus police -

<table>
  <thead>
    <tr>
      <th>API Endpoint</th>
      <th>Method</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>/user/search/{param}</td>
      <td>GET</td> 
      <td>Allows officers to look up users by {param} - first name and last name, and also HokieID.</td> 
    </tr>
     <tr>
      <td>/user/rideHistory</td>
      <td>GET</td> 
      <td>Gets driver/rider’s ride history.</td> 
    </tr>
     <tr>
      <td>/user/currentRide</td>
      <td>GET</td> 
      <td>Gets driver/rider’s current ride details.</td> 
    </tr>
  </tbody>
</table>


## Requirement Traceability Matrix

A variety of functional and non-functional requirements have been mentioned in the previous design sections as necessary. Some of the specifications are broad and challenging to assign to a specific system component. The following traceability matrices for requirements should serve as a quick reference for the connections between requirements and system components.


### Functional Requirements

<style>
  .row-header {
    width: 5rem
  }
</style>

<table class="traceability-matrix">
  <thead>
    <tr>
      <th></th>
      <th><div><span>Database Component</span></div></th>
      <th><div><span>REST API Component</span></div></th>
      <th><div><span>Presentation layer (Web / Mobile App)</span></div></th>
      <th><div><span>Additional AWS Services</span></div></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th class="row-header">FR-1</th>
      <td>X</td>
      <td>X</td>
      <td>X</td>
      <td></td>
    </tr>
    <tr>
      <th class="row-header">FR-2</th>
      <td>X</td>
      <td>X</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th class="row-header">FR-3</th>
      <td>X</td>
      <td>X</td>
      <td>X</td>
      <td></td>
    </tr>
    <tr>
      <th class="row-header">FR-4</th>
      <td>X</td>
      <td>X</td>
      <td>X</td>
      <td></td>
    </tr>
    <tr>
      <th class="row-header">FR-5</th>
      <td>X</td>
      <td>X</td>
      <td>X</td>
      <td></td>
    </tr>
    <tr>
      <th class="row-header">FR-6</th>
      <td>X</td>
      <td>X</td>
      <td>X</td>
      <td></td>
    </tr>
    <tr>
      <th class="row-header">FR-7</th>
      <td>X</td>
      <td>X</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th class="row-header">FR-8</th>
      <td>X</td>
      <td>X</td>
      <td>X</td>
      <td></td>
    </tr>
    <tr>
      <th class="row-header">FR-9</th>
      <td>X</td>
      <td>X</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th class="row-header">FR-10</th>
      <td>X</td>
      <td>X</td>
      <td>X</td>
      <td></td>
    </tr>
    <tr>
      <th class="row-header">FR-11</th>
      <td>X</td>
      <td>X</td>
      <td>X</td>
      <td></td>
    </tr>
    <tr>
      <th class="row-header">FR-12</th>
      <td>X</td>
      <td>X</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th class="row-header">FR-13</th>
      <td></td>
      <td>X</td>
      <td>X</td>
      <td></td>
    </tr>
    <tr>
      <th class="row-header">FR-14</th>
      <td>X</td>
      <td>X</td>
      <td>X</td>
      <td></td>
    </tr>
     <tr>
      <th class="row-header">FR-15</th>
      <td>X</td>
      <td>X</td>
      <td>X</td>
      <td></td>
    </tr>
     <tr>
      <th class="row-header">FR-16</th>
      <td>X</td>
      <td>X</td>
      <td>X</td>
      <td></td>
    </tr>
     <tr>
      <th class="row-header">FR-17</th>
      <td>X</td>
      <td>X</td>
      <td>X</td>
      <td></td>
    </tr>
  </tbody>
</table>

### Non-functional Requirements

<table class="traceability-matrix">
  <thead>
    <tr>
      <th></th>
      <th class="rotate"><div><span>Database Component</span></div></th>
      <th class="rotate"><div><span>REST API Component</span></div></th>
      <th class="rotate"><div><span>Presentation layer (Web / Mobile App)</span></div></th>
      <th class="rotate"><div><span>Additional AWS Services</span></div></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th class="row-header">NR-1</th>
      <td>X</td>
      <td>X</td>
      <td></td>
      <td>X</td>
    </tr>
    <tr>
      <th class="row-header">NR-2</th>
      <td></td>
      <td>X</td>
      <td>X</td>
      <td></td>
    </tr>
    <tr>
      <th class="row-header">NR-3</th>
      <td></td>
      <td>X</td>
      <td>X</td>
      <td></td>
    </tr>
   <tr>
      <th class="row-header">NR-4</th>
      <td></td>
      <td>X</td>
      <td>X</td>
      <td></td>
    </tr>
   <tr>
      <th class="row-header">NR-5</th>
      <td></td>
      <td>X</td>
      <td>X</td>
      <td></td>
    </tr>
  <tr>
      <th class="row-header">NR-6</th>
      <td></td>
      <td>X</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th class="row-header">NR-7</th>
      <td>X</td>
      <td></td>
      <td></td>
      <td>X</td>
    </tr>
   <tr>
      <th class="row-header">NR-8</th>
      <td>X</td>
      <td></td>
      <td></td>
      <td>X</td>
    </tr>
   <tr>
      <th class="row-header">NR-9</th>
      <td>X</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
   <tr>
      <th class="row-header">NR-10</th>
      <td>X</td>
      <td>X</td>
      <td></td>
      <td></td>
    </tr>
   <tr>
      <th class="row-header">NR-11</th>
      <td>X</td>
      <td>X</td>
      <td></td>
      <td></td>
    </tr>
     <tr>
      <th class="row-header">NR-12</th>
      <td></td>
      <td>X</td>
      <td></td>
      <td></td>
    </tr>
     <tr>
      <th class="row-header">NR-13</th>
      <td>X</td>
      <td>X</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th class="row-header">NR-14</th>
      <td>X</td>
      <td>X</td>
      <td>X</td>
      <td></td>
    </tr>
    <tr>
      <th class="row-header">NR-15</th>
      <td></td>
      <td>X</td>
      <td></td>
      <td></td>
    </tr>
     <tr>
      <th class="row-header">NR-16</th>
      <td>X</td>
      <td>X</td>
      <td></td>
      <td></td>
    </tr>
     <tr>
      <th class="row-header">NR-17</th>
      <td></td>
      <td>X</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th class="row-header">NR-18</th>
      <td></td>
      <td>X</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>


# Design Rationale

## System Architecture Rationale

Provided below are the key design decisions, derived from the functional and nonfunctional requirements that we use as evaluation criteria for our architecture. We explain in detail how each of them relate to the requirements and how the architecture chosen aims to achieve these design decisions in the best possible way.

## Evaluation criteria/ key design decisions - 

### Ability to sync with university’s authentication systems/APIs

This caters to requirements FR1 and FR2. We require that the users are able to register and be authenticated by the university systems and then be able to login to use the app. We achieve this in our architecture by the layered approach where the authentication and authorization are controlled by specific REST APIs in the application layer.


### Ability to integrate with third party authentication methods like gmail, facebook etc

This design decision also relates to FR1 and FR2 requirements. This also caters to NR7 where we require the system to be decoupled and easily interact with third party systems like google authentication or facebook authentication. This is achieved in our design by separating the presentation and the application layers where we handle the separate authentication methods and routes based on the request from the presentation layer.

### Ability to extend authentication systems/APIs to more universities 

This design decision stems from the need to make FR1 and FR2 easily interoperable and modifiable for when the product needs to extend the authentication system to more universities. This is achieved in the architecture by decoupling authentication service from other services in the application layer and by designing separate APIs for each university’s authentication request for redirecting to required external university authentication APIs.


### Fast password encryption and decryption

This relates to FR3 where we require secure password encryption and decryption. This is achieved by using load balancers to distribute password validation requests optimally across servers in the application layer. This is also supported in the data layer by using database sharding where we distribute the user data across multiple data shards and read/write from/to the shards using a hashing/sharding algorithm. This could help distribute user data across database servers and all operations would only be performed on the shard the user is present in, instead of on the entire data.

### Fast and real-time driver search

This design decision relates to FR4 where riders can search and see all available drivers. This is achieved in our architecture by creating a separate rider availability service that responds to all rider availability requests. This is also helped by using geographically placed data centers that cater to closest regions. Intelligent caching by identifying available drivers and placing them in cache can help speed up driver search.

### Ability to expand search with added search specifications( distance, prices, only VT drivers etc)

This design decision stems from FR4 where the riders are able to search for nearby drivers based on distance and other parameters. Our architecture allows for expanding to more advanced searches by separating the data and application layer. Thus allowing the data layer to scale independently and horizontally with increasing attributes of ride data. Caching currently available rides helps access these rides faster when searching.


### Support for faster notification system when ride requested/canceled

This design decision caters to FR5 where riders need to be notified on status of rides. Notification system is made reliable and faster by creating a separate notification service in the application layer. Notifications are also improved in speed by using a  load balancer to distribute notification requirements across web servers and by using a message queue to allow multiple workers to process notifications.


### Ability to expand notification service to include more events in future
This criteria comes from NR1 which requires the system to be scalable to increasing demand.
We are able to achieve this by creating a separate notification service to handle notifications in the application layer. This is also achieved by using messaging queues to increase or decrease the number of workers needed to process messages in the queue based on demand.

### Support for switching third party location APIs used

FR6,FR7,NR7
This criteria stems from FR6 ,FR7 and NR7 that require real time location updates in the app and ability to obtain location information from external systems and to be able to switch third party location APIs accessed if needed. This is achieved by using a separate location service that connects to external APIs to obtain location information to pass on to the presentation layer. The location service would be decoupled from the external service it interacts with to allow for each modification in future.

### Ability to expand/improve ETA calculation based on more external data( current traffic data) or changing data statistics results(analysis of historical data)

This design decision is related to FR7 where the location and ETA should be constantly updated for the riders. This is achieved in the architecture by using a separate location service in the application layer to handle everything related to location service and by keeping it well connected and synchronized with rider availability service. The REST APIs of each service interact with each other and with external location APIs with the help of messaging queues to optimize and speed up processing time.

### Support to expand ride schema to include additional information like ‘number of passengers’, ‘reached within ETA’ etc

This is related to FR8 and NR9. This can be achieved in our architecture by the separation of the data layer from other layers for independent scaling when need for data storage servers increases. We can horizontally scale by adding more database servers to handle increased data size without affecting performance.


### Faster SMS/Email dispatch or ability to queue SMS/Email for later dispatch if SMS/Email cannot be sent immediately( due to network failure, high number of SMS requested etc)

This is related to FR9 where SMS/Email should be sent for required ride status changes. This is achieved by using a separate notification service in the application layer and using messaging queues to allow for concurrent processing of incoming notification requests. Speed can also be achieved by using separate data centers and allocating geographically closes data center to a user and rider. The ride status in the presentation layer can be propagated down till the data layer in order to keep the application and presentation layers stateless so that user load can be redirected to any of the servers(as every server would have access to state) for faster processing.

### Ability to gain faster access to driver details and rider details of the currently ongoing rides.

This is related to FR14,FR15,NR12,NR13 where campus police can search all rides and currently ongoing rides in a fast and reliable manner.
This is achieved by separating the data layer firstly for easier optimization. Secondly, we would be using master slave database separation where the master would be used for write operations(which are less frequent) and the multiple slaves support read operrations( more frequent ). We also implement cache DBs that dynamically update to contain the currently ongoing rides for faster access.

### Ability to integrate with university wallets or credit systems and update user wallets in HokieRide app as well as user wallet/credits in university based on user activity.

FR12
This is related to FR12 where the user can use and connect with a university wallet or credit system. This is achieved in the application layer that can identify incoming requests based on university specific information added in the headers by the presentation layer and appropriately redirect requests to university wallet systems. 

### Ability to scale all real time services to increased number of users in same university and to increased number of universities without affecting speed in the services -

- Ride matching
- Notification service
- Live location and ETA 

This is related to FR5,FR9 AND NR1 where integration with university services should be possible and should be easily extendable with increasing universities or increasing users in a university. This is achieved by using the load balancer to distribute processing requests across servers and by using multiple data centers in different geographical locations. Each data center would have its own cache that prioritizes different data depending on the universities it is closest to. The master slave architecure in the DB allows for increased read/write calls to the DB withou affecintg performance.

### Allow for easy change of university and all university affiliated services  -

- Authentication
- Credits
- Campus police to connect to database

This is related to FR2, FR12 and NR1 where users can access different university services and also easily be able to change universities. This is achieved by using multiple data centers that replicate entire user data. Changing university would lead to change in the university field in the data layer of the user and the separate services (authentication, credits, campus police ) would seamlessly work with updated user data as they would redirect to appropriate university services based on incoming request headers.

### Ability to add a real time two way communication channel between rider and campus police department (like live chat) to access during the ride

This is related to FR13 where a live chat can be enabled between rider and campus police if needed during the ride. This would be possible by having a separate emergency alert service that handles all processes and requests related to emergency services. The messaging queues can be customized to prioritize all messages or requests with an emergency tag over every other request. The application can support faster and seamless chat by using Content delivery network to temporarily render all static content in the app to reduce load from other other services. Having a stateless architecture also helps here as the rider state at the presentation layer is at the data layer and can be accessed by any server thus allowing all servers to be available for the chat.

### Ability to increase/decrease resource usage(increase servers or reduce) based on load and demand

This is related to NR1,NR10 and NR11 to allow for faster search by campus police and seamless emergency and notification related services at scale. This is achieved in the architecture by usage of the load balancer to distribute load across servers, messaging queues to concurrently process requests and increase or decrease processors required based on load in the queue and by the ability to horizontally scale the data layer when required.

### Support for automating user management/permission management system for campus police department(deactivate when employee resigned or add user with permissions to app when new employee joined)

This is related to FR13, FR14 and NR1 which requires efficient emergency handling services that can scale. This is achieved in the architecture by creating a separate campus police application that interacts with the user service in the application layer through the REST APIs. Messaging queues can be set up to listen to data layer changes in campus police databases to automatically update campus police applications as well as rider applications with the changes.


### Ability to modify search algorithms for rides in the ride database to include more parameters or to modify the algorithm itself for faster search.

This is related to FR4, FR5 and NR11 where riders can search for drivers in real time. This is achieved by using the separate rider availability service in the application layer that can be modifiable in its search algorithm.

### Ability to reuse user input validation in multiple places across app - during signup, during login, during user profile editing, during campus police search

This is related to FR2 and FR15 where the users can register themselves on the app and campus police can search for users based on some user identification fields. By separating the presentation layer we allow reusability of components wherever needed. Here the input forms and validation logic can be reused during registration, login and when searching for driver. This logic can also be modified based on university specifications for the fields like university ID character lengths etc.

### Ability to allow user to share live location to campus police before or during the ride

This is related to FR7 and NR14 where live location needs to be updated in real time for riders and drivers and it should be shareable with campus police if needed during the ride. This is achieved by allocating a separate location service that can handle and optimize live location sharing requests. The CDN ensures static content is quickly dispatched to the application to reduce processing time for other components of the app. By allocating closest geographics data centers to the client also speeds up all requests related to location updates.

### Ability to re-purpose more resources to rides that have requested emergency help from campus police . Prioritize these rides in notification, live location tracking and overall network requests.

This design criteria caters to FR14,NR1,N11,NR12 where campus police can access the application and interact with riders during a ride seamlessly during an emergency situation.
This can be achieved by customizing the load balancer to prioritize emergency service related requests over every other request. Use of cache to always have ongoing ride data along with frequently accessed data for faster access. Applications can switch to Content delivery networks for static assets on low priority pages and components of the app and finally messaging queues can also be customized to prioritize all emergency requests, whether it is read operations from DB or search requests or location requests.

### Ability to automatically notify police of suspicious rides that have failed normal network checkpoints for too long or display abnormal activity( like location not changed for too long, well behind ETA for long time, or lacking network pings from rider or driver phones).

This is related to FR13, NR7,NR13 and NR17 where the campus police have access to a web application to check all rides and ongoing rides and respond to emergency requests in real time and reliably. This is achieved in the architecture by using a separate notification service that can subscribe to current ride data stored in cache for faster access. The notification service can be specified to define and identify suspicious activity automatically from the ongoing rides based on the data obtained from cache and connect with emergency service to initiate an emergency request.

### Ability to switch data backup service used and frequency of backups.

NR8,NR9
This is related to NR8 and NR9 which require frequent data backups efficiently and with low cost. This is achieved by using an separate data layer with master slave DB architecture. Since each slave has the same data and as in master, backup can be distributed across the DBs to minmize downtime and increase back up speed. Or one of the slaves can be used for backup while others are fully available and this can be rotated on a daily basis.


### Support for determining resource usage and computation power to allocate for different services during regular usage and ability to set this at different levels for different universities.

NR1,NR11
This design criteria stems from NR1 and NR11 where the application is required to be real time in services like search, location, rider availability and also be scalable without affecting speed of these services. We are able to achieve this by using load balancer, cache and messaging queues to keep the load distributed always across servers and in an optimal manner to be able to increase or decrease resource usage based on demand. 

### Ability to expose APIs to data that can be shared publicly like ride start, end, ride duration, etc in the future.

NR7,NR18
This design criteria is related to NR7 and NR18 which require a highly de coupled system to facilitate ease of interoperability with external systems and to develop all functionalities using APIs so it is decoupled from the type of presentation layer that needs to access it. This is achieved by the layered architecture that separates the presentation layer and the application layer and by using REST APIs in the application layer for all communication. The REST API endpoints can be decided to be made public in which case user authentication would not be required to access them.


## Conclusion

The HokieRide is a system that is dedicated to find rides when traveling short or long distances, especially during busy days when events take place (e.g game days, fests) or even late nights. This system will address safety by developing HokieRide, an application that includes a verification system for the drivers and riders as authenticated students or faculty of Virginia Tech. In addition, the system will be linked to the campus police department in the case of any emergencies.
Based on the requirements of the system, we have identified five core components: a non-relational cloud database, a relational cloud database, REST API, a web application and a mobile application. Implementing a layered architecture was an informed decision based on the requirements and use cases identified. It provides benefits regarding maintainability, modifiability, testability, and scalability which are some of the key attributes that help boost a system's software quality. Addressing these factors will be crucial for the success of the system and to expand the use of ridesharing app beyond Virginia Tech.