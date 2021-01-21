# T3A2-A - Full Stack App (Part A) - Larry's Lawncare

### Purpose
When it comes to a small lawn care business, the business owner may not have the capacity to hire a dedicated administrator to oversee the bookings.  
  
As the business owner will regularly be out on the road completing existing bookings, they may not be able to take calls for new bookings. The Larry's Lawncare website bridges the gap to allow a customer the self service option to make a booking online for a requested date and then allows the business to log in and manage these bookings with full CRUD operations (create/view/update and delete bookings).

The services page allows for a customer to see if Larry's Lawncare offers the services they need and then allows them the option to book the service, alleviating the need for follow up phone calls for any missed calls. It also allows the customer to make the booking at a time that is most convenient for them, not necessarily in business hours.

### Functionality / Features
* Business Owner Login
* Booking request form
* Contact Us page
* CRUD functionality for bookings
* Reschedule option for recurring bookings 
* Services list

### Target audience
Larry's Lawncare website is aimed at people who are needing assistance with cleaning up or maintaining their lawn and would like the ease of being able to book online hassle free.

### Tech stack

**Design & Planning**
* Trello
* Lucid Chart
* Adobe XD
* Indesign

**Source Control**
* Git
* Github (Hosting repository)

**Frontend**
* HTML
* CSS
* JavaScript
* React JS

**Backend**
* Rails API

**Database**
* PostgreSQL

**Deployment**
* Frontend - Netlify
* Backend - Heroku

**Testing**
* App testing - TBA
* Postman

### Dataflow Diagram
![Dataflow Diagram](/docs/DataFlowDiagram.jpeg)



### Application Architecture Diagram
![Application Architecture Diagram](/docs/AppArchitectureDiagram.png)


#### User Stories

## Persona
* **Business Owner:**
    * Larry is a sole trader who is managing his own lawn care business which includes managing all the bookings bookings. Due to an increase in bookings, Larry is wanting to enlist in a secure online booking system to help him manage both existing and incoming bookings. Larry is not technically savvy, therefore; he needs a booking system which is easy to use which also allows him to retrieve the bookings for a specific day. As Larry is a small business, he only services the Brisbane metro area so he does not want a customer to book outside of the areas he services. As Larry is a mobile business, he needs a website that is easy to access on a mobile or tablet. Larry currently posts his work on social media platforms such as Facebook and Instagram so he would like customers to be able to access these websites from his website.
* **Customer:** 
    Larry has received feedback from a couple of his current customers on how he can improve his services:
    * Carole is a night shift worker and struggles to make bookings during business hours, therefore; it is convenient for Carole to make bookings online during her breaks. Carole also likes to know an estimate as to what the cost of the service will be and sometimes waiting for a quote can take some time, therefore; she is more likely to book through a business where she can get a cost up front. Carole does not have a desktop computer or tablet, therefore; she needs a mobile friendly website in order to make a booking.
    * Daisy is an elderly customer of Larry's. She does have access to a desktop computer and can use the internet, however; she is not the best at technology so she needs a simple and easy to use website which does not require too much effort to navigate.


**User Stories**
* As a customer, I want to be able to complete a booking form so that I can make a booking for a lawn service
* As a customer, I want to be able to contact the company so that I can confirm/cancel my appointment
* As a prospective customer, I want to be able to view a service list so that I can see prices and check that the business caters to my lawn requirements
* As a prospective customer, I want to be able to view examples of the business' work so that I can see the quality of their work and choose whether I book with them
* As a business owner, I want to have a user friendly website so that my existing and potential new clients can make a booking and contact the business easily
* As a business owner, I want to be able to securely log on to the website so that I can view and manage (create/update/delete) my clients bookings accordingly
* As a business owner, I want my customers to have the ability to make their own booking online and select their service type so that I have their details recorded in the database and so they can make the booking at any time
* As a business owner, I want to ensure that only the areas which are serviceable can be booked so the business does not receive a booking for a location which is not serviced
* As a business owner, I want to be able to retrieve a list of bookings for a specified day so that I can see what jobs I have for that day and plan my day accordingly
* As a user, I want to access a website with a responsive layout so I can easily use the website on a number of devices

### Wireframes for multiple standard screen sizes, created using industry standard software
![Desktop about/landing page](/docs/desktop1.png)<br>
![Desktop services page](/docs/desktop2.png)<br>
![Desktop booking page](/docs/desktop3.png)<br>
![Desktop contact page](/docs/desktop4.png)<br>
![Desktop admin login page](/docs/desktop5.png)<br>
![Desktop admin view all page](/docs/desktop6.png)<br>
![Desktop admin view booking page](/docs/desktop7.png)<br>
![Desktop new booking page](/docs/desktop8.png)<br>
![Desktop edit booking page](/docs/desktop9.png)<br>
![Desktop admin delete confirmation alert page](/docs/desktop10.png)


![Tablet about/landing page](/docs/tablet1.png)<br>
![Tablet services page](/docs/tablet2.png)<br>
![Tablet booking page](/docs/tablet3.png)<br>
![Tablet contact page](/docs/tablet4.png)<br>
![Tablet admin login page](/docs/tablet5.png)<br>
![Tablet admin view all page](/docs/tablet6.png)<br>
![Tablet admin view booking page](/docs/tablet7.png)<br>
![Tablet new booking page](/docs/tablet8.png)<br>
![Tablet edit booking page](/docs/tablet9.png)<br>
![Tablet admin delete confirmation alert page](/docs/tablet10.png)


![Mobile about/landing page](/docs/mobile1.png)<br>
![Mobile services page](/docs/mobile2.png)<br>
![Mobile booking page](/docs/mobile3.png)<br>
![Mobile contact page](/docs/mobile4.png)<br>
![Mobile admin login page](/docs/mobile5.png)<br>
![Mobile admin view all page](/docs/mobile6.png)<br>
![Mobile admin view booking page](/docs/mobile7.png)<br>
![Mobile new booking page](/docs/mobile8.png)<br>
![Mobile edit booking page](/docs/mobile9.png)<br>
![Mobile admin delete confirmation alert page](/docs/mobile10.png)

#### Site walkthrough
![Relationships between screens](/docs/relationships.png)

#### Client changes
![Wireframe changes](/docs/changes.png)
1. Client requested a search bar to be added on the view all bookings page.
2. The submit button for the booking form had been omitted on the booking page.
3. The login button had been omitted on the Admin login page.
4. Client requested a section for testimonials be added. The image on the services page was replaced with a scrolling testimonials section.
5. Client requested social media icons be added to the contact page.
6. Client stated that the view all bookings page for tablet was too crowded. Font size was reduced to allow for more white space.


### Screenshots of Trello board throughout the duration of the project
![Day 1](/docs/Trello1.png)<br>
![Day 2](/docs/Trello2.png)<br>
![Day 3](/docs/Trello3.png)<br>