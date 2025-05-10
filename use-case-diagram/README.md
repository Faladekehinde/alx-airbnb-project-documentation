##  Airbnb Clone - Use Case Diagram

This document presents the Use Case Diagram for the backend of the Airbnb Clone project. It visualizes the key interactions between users and the system, offering a clear overview of functional requirements and user roles.

## Objective
To model system interactions through a use case diagram that reflects essential features such as user registration, property listing, booking, and payment workflows.

## 👥 Actors
Guest: A user who searches for properties, books listings, and submits reviews.
Host: A user who manages property listings and handles booking requests.
Admin: Oversees the platform by managing users, listings, and handling reports.

## ✅ Use Cases

## 🧑‍💼 User Management
-   Register as a Guest or Host
-   Login via Email/Password or OAuth (Google, Facebook)
-   Update user profile and contact info
-   View user dashboard

##  🏠 Property Management (Host)
-   Add new listings
-   Edit listing details (price, description, availability)
-   Delete listings
-   View listing performance

## 🔍 Search and Discovery

*  Search listings by location, date, price, or amenities
*  Filter and sort results
*  View detailed listing pages

## 📅 Booking System
*  Book available properties for specific dates
*  Cancel existing bookings
*  View booking status: Pending, Confirmed, Cancelled, Completed

## 💳 Payments
*  Make payments via Stripe or PayPal
*  Process automatic payouts to hosts
*  Handle refunds
*  View payment history

## 🌟 Reviews & Ratings
-  Submit a review and rating post-stay
-  View reviews on listings
-  Hosts can respond to guest reviews

#  🔔 Notifications
-  Receive email/in-app notifications for:
-  Booking confirmations
-  Cancellations
-  Payment events

## 🛠️ Admin Controls
-  Monitor and manage:
-  User accounts
-  Listings
-  Payments and bookings
-  Deactivate or ban accounts
-  Review flagged content

#  🧰 Tools Used
-  Draw.io – for diagram creation
-  Markdown – for structured documentation
-  GitHub – for project collaboration