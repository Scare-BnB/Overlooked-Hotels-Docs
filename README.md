![logo](/docs/logo_docs.png)

The documentation for 'The Overlooked Hotels' MERN project by Kelsey Hardy and Alex Karacsay

# MERN Application

### Deployments:

- Netlify: https://theoverlookedhotels.netlify.app
- Heroku: https://the-overlooked-hotels-fa14e4d47922.herokuapp.com/

### Repos:

- Client: https://github.com/Scare-BnB/overlooked-hotels-client
- Server: https://github.com/Scare-BnB/overlooked-hotels-server

### Trello:
https://trello.com/b/9n8WNsKs


## Start Server

To run the server, open the terminal and change into the server folder `cd server`. 
To install the dependencies for this server, type `npm install` into the command line. To seed the relevant data for this application enter `npm run seed` into the terminal. This will store the locations and create user dummy data for both admin and non-admin accounts. 
To run the server, enter `npm start` which wil operate on `localhost:4000`.

## Start Client

To get the client running, move into the client folder `cd client` in the terminal. To install the relevant packages type, `npm install` into the command line. In the terminal, follow with `npm run dev` with will use `localhost:5173`.

## R1. Description of your website, including:
### Purpose

Our application serves as a strategic solution crafted for a business aiming to modernize their approach to accommodation management. With a focus on bringing their business into the digital age, our platform provides an intuitive and efficient way for customers to explore and secure bookings at an intriguing range of accommodations. Tailored to meet the needs of a forward-thinking company, the application streamlines the booking process, encouraging customers to engage online and fostering increased customer numbers. By embracing technology, our goal is to empower the business to efficiently manage bookings, keep information current, and ultimately elevate their business in the competitive landscape of the hospitality industry.

### Functionality / features

Our application redefines the way users experience accommodations with a feature-rich and user-friendly platform. Key functionalities include:

**Immersive Booking System**:
Browse a selection of fascinating locations and easily book an unforgettable stay with our intuitive booking system.

**User-Friendly Interface**:
Enjoy a visually captivating and responsive interface designed with HTML, CSS, and JavaScript, ensuring a seamless and enjoyable user experience across all devices.

**JWT-based Authentication**:
Prioritize user security with JWT (JSON Web Token) authentication, ensuring a secure and efficient process for user identification and authorization in the application's API.

**Backend Efficiency with Node.js and Express.js**:
Benefit from a robust and efficient backend infrastructure powered by Node.js and Express.js, offering scalability and streamlined server-side processes.

**Flexible Data Management**:
Utilize MongoDB for flexible and scalable data management, ensuring that information is current and readily accessible.

**Calendar Integration**:
Seamlessly integrate a calendar feature, allowing users to view availability, schedule bookings, and plan their getaways with ease.

### Target audience

Our accommodation booking website is designed for individuals seeking a hassle-free and convenient way to plan and book their stays. Whether you're a business traveler in need of efficient lodging solutions, a family planning a vacation, or an individual embarking on a spontaneous getaway, our platform caters to a diverse audience looking for simplicity in the accommodation booking process. With a user-friendly interface and an array of options, our target audience includes anyone seeking a reliable and straightforward platform to discover and reserve accommodations that suit their unique preferences and travel needs.

Our target audience also encompasses forward-thinking business owners within the hospitality industry seeking to embrace technology for a competitive edge. Tailored for entrepreneurs keen on modernizing their accommodation management approach, our platform caters to those eager to increase online bookings. Our platform enables business owners to efficiently manage bookings, attract a broader customer base, and transition into the era of online accommodation reservations.

### Tech stack

Our application harnesses a robust and innovative tech stack to deliver a seamless and immersive user experience. Leveraging the power of modern web development, we employ HTML and CSS for a visually engaging and responsive interface. The dynamic client-side interactions are crafted using JavaScript, ensuring a fluid and interactive user journey.

On the server side, we rely on Node.js to handle the backend, providing a scalable and efficient runtime environment. Express.js complements this setup, simplifying the development of robust web applications. Our data is managed and stored securely using MongoDB that offers flexibility and scalability.

Our tech stack combines server-side efficiency with Node.js and Express.js, and secure data management with MongoDB.

**Frameworks**: 
- React
- ExpressJS

**Database**:
- MongoDB

**Development Servers**: 
- Vite (Front-end)
- Nodemon (Back-end)

**Packages and libraries**: 
- react-router-dom
- Tailwind CSS
- Mongoose
- Daisy UI (Header and Footer elements)
- react-responsive-carousel
- react-calendar
- Axios
- CORS
- BcryptJS
- Json-Web-Token

**Software**:
- Postman
- Pixelmator Pro 
- Figma

## R2. Dataflow Diagram

![DFD](/docs/diagrams/DFD.png)

## R3. Application Architecture Diagram

![AAD](/docs/diagrams/AAD.png)

## R4. User Stories

### Customer Side

**Stephen, 76 - Author**

*"I want an easy way to book stays in unique and inspiring locations. I want to view and support local businesses instead of large chain hotels."*

**Georgie, 21 - Tourist**

*"I'm a penny-wise frequent traveller who wants to book affordable accomodation without needing to speak on the phone."*

**Randall, 50 - Frequent business traveller**

*"I constantly travel for business looking for an efficient way to view and book acommodation during my busy day"**

**Requirements:**

**User Registration**:
As a new user, I want to create an account with my email and password, so I can access personalized features and view my booking history.

**User Authentication**:
As a registered user, I want to log in using my credentials so that I can securely access the application.

**Book Accommodations**:
As a user, frequent traveler, or vacation planner, I want to select an accommodation, choose my dates, and make a booking, ensuring a seamless and straightforward process.

**View Booking History**:
As a user, I want to view my booking history, including details on upcoming stays, for reference and planning.

**Manage Account Settings**:
As a user, I want to update my profile information, change my password, or modify preferences to tailor the application to my needs.

**Check Availability**:
As a user, I want to check the availability of accommodations for specific dates, ensuring I can plan my stay efficiently.

**Receive Booking Confirmation**:
As a user, I want to receive a notification after making a booking to ensure my reservation is successful.

**Cancel Booking**:
As a user, I want the ability to cancel a booking within a reasonable timeframe, providing flexibility in my plans.

**Calendar Integration**:
As a user, I want to view a calendar that displays the availability of accommodations, making it easier for me to plan my stay.

**User Assistance and Support**:
As a user, I want access to customer support or an FAQ section to get help with any issues or questions I may have.

### Business Side

**Jack, 43 - Director of *The Overlooked Hotels* and owner of *The Grand Lodge***

*"I’ve been in the hotel management game since 1980 when I took over as caretaker of the Grand Lodge. Back then we were the biggest and busiest hotel on the mountain. In the last few years however,  we’ve noticed a sharp decline in patronage due to heavy competition in the local town. All of those businesses had one thing in common, an “online presence”. I decided to hire a team to build a website promoting the business and provide a way for guests to book a stay at the Lodge without needing to phone ahead.*

*Two fellow business managers in a similar position heard what I was doing and contacted me regarding my website idea. We decided to join forces and create a business collective, The Overlooked Hotels. We agreed that I would be the admin in charge of managing the website and bookings."*

**Annie, 44 - Manager of *The Wilkes Cabin***

*"I’m a new business owner who has recently entered into the bed and breakfast game. I understand the importance of having my business available to view online but have no idea how to make it happen. My good friend Jack has engaged the services of a development team and I decided to collaborate with him. He will take care of the technical side of things and I will be able to view the bookings."*

**Norman, 25 - Manager of *The Fairvale Motel***

*"I have just become the manager of my family's motel and needed help with running a business. I found out about Jack's Overlooked Hotels collective and decided to join. Our motel doesn't have a website and I want to promote it!"*


**Requirements:**

**Optimize Booking Process**:
As a business owner, I want to streamline the booking process to improve efficiency and reduce the time it takes for users to complete a reservation, ultimately increasing the number of successful bookings.

**Improve Customer Support**:
As a business owner, I want to enhance the customer support features, providing quick and effective assistance to users, ultimately improving overall satisfaction and trust in our services.

**Increase Booking Conversion Rates**:
As a business owner, I want to implement strategies to increase the conversion rates of users browsing the application to actual bookings, ultimately maximizing revenue.

**Efficient Calendar Management**:
As a business owner, I want an efficient calendar management system to handle accommodation availability, allowing us to maximize bookings and minimize conflicts.

**Ensure Data Security and Privacy**:
As a business owner, I want to prioritize the security and privacy of user data, implementing measures to protect sensitive information and build trust among users.

## R5. Wireframes
![Home](/docs/wireframes/homepage.png)
![Locations](/docs/wireframes/locations.png)
![Contact](/docs/wireframes/contactpage.png)
![Bookings](/docs/wireframes/bookings.png)
![Login](/docs/wireframes/login.png)

### Design updates from PART B
- Header is completely opaque in order to have animated image carousel underneath
- Removed drop-down menu for locations, consolidated on single page
- Removed 'About' link and consolidated on index page
- Removed 'Bookings' link as not required for users not logged-in
- No 'back-to-top' button. Was a nice-to-have but culled due to lack of time
- Colour scheme changed to darker theme for easier viewing overall.
- Site font set to sans serif for ease of reading


## Endpoints and Testing

This API was developed to implement CRUD operations throughout the different model controllers in this application. The different endpoints focus on the four models that have been established in the database: Users, Accommodation, Bookings and Reviews.
Provided a User is logged in, the following operations will execute unless they require Administrative Access.

### User

#### GET/ allows Admin User to access all Users stored in the database
![get](/docs/endpoints/Get%20All%20Users.png)

#### POST/ creates a new User in the database
![post](/docs/endpoints/Create%20User%20in%20Postman.png)

#### PATCH/ updates a User's data
![patch](/docs/endpoints/Update%20User%20Data.png)

#### DELETE/ deletes a User's account in the database
![delete](/docs/endpoints/Delete%20User%20Account.png)

### Accommodation

#### GET/ shows all location data for Accommodation
![get](/docs/endpoints/Get%20All%20Locations.png)

#### POST/ creates a new Accommodation if the user isAdmin
![postAdmin](/docs/endpoints/Create%20Accommodation%20as%20Admin.png)
`Error if not admin.`
![post](/docs/endpoints/Try%20Create%20Accommodation%20-%20not%20Admin.png)

#### PATCH/ updates information in location data for Admin only
![patch](/docs/endpoints/Update%20Accommodation%20as%20Admin%20-After.png)

#### DELETE/ removes a location from the Accommodation database
![delete](/docs/endpoints/Delete%20Accommodation%20as%20Admin.png)

### Booking

#### GET/ shows all Booking in the database as Admin
![get](/docs/endpoints/Get%20All%20Bookings%20as%20Admin.png)

#### POST/ creates a Booking provided a User is logged in
![post](/docs/endpoints/Create%20Booking%20with%20JWT.png)

#### PATCH/ updates an existing Booking 
![patch](/docs/endpoints/Update%20Booking%20data.png)

#### DELETE/ removes a Booking entry from the database
![delete](/docs/endpoints/Delete%20Booking.png)

### Review

#### GET/ shows all Reviews for theOverlookedHotels
![get](/docs/endpoints/Get%20All%20Reviews.png)

#### POST/ creates a new User Review
![post](/docs/endpoints/Create%20Review.png)

#### PATCH/ updates an existing Review
![patch](/docs/endpoints/Update%20Review.png)

#### DELETE/ deletes a Review from the database
![delete](/docs/endpoints/Delete%20Review.png)

### Manual testing
![front-end](/docs/testing/front-end-testing.png)
![back-end](/docs/testing/back-end-testing.png)


## R6. Screenshots of your Trello board throughout the duration of the project

![Concept](/docs/trello/Concept.png)
![StandUps](/docs/trello/StandUps.png)
![Requirements](/docs/trello/requirements.png)
![Overview](/docs/trello/partb-trello1.png)
![Front-end](/docs/trello/partb-trello2.png)
![CRUD](/docs/trello/partb-trello3.png)


**References**

'The Overlooked Hotels' original logo design by Alex

Royalty-free images used in wireframes and site from [Unsplash.com](https://unsplash.com/)

Thanks to: 
- Nick Hillier
- Clay Banks
- Steve Harvey
- Dylan Fout
- Mathis Jrdl
- Eberhard Grossgasteiger

