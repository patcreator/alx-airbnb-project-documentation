# Airbnb Clone Backend Features & Functionalities

This document provides an overview of the core features, technical requirements, and non-functional requirements of the Airbnb Clone backend project. The accompanying diagram visually represents the system architecture and relationships between modules.

## Core Functionalities

- **User Management**
  - Registration and login (JWT, OAuth)
  - Profile management
- **Property Listings Management**
  - Add, edit, delete property listings
  - Property details: title, description, location, price, amenities
- **Search & Filtering**
  - Search by location, price, guests, amenities
  - Pagination support
- **Booking Management**
  - Create and cancel bookings
  - Track booking status
- **Payment Integration**
  - Secure payments (Stripe, PayPal)
  - Automatic payouts to hosts
  - Multi-currency support
- **Reviews & Ratings**
  - Guests can leave reviews; hosts can respond
- **Notifications**
  - Email and in-app notifications for bookings and payments
- **Admin Dashboard**
  - Manage users, listings, bookings, and payments

## Technical Requirements

- **Database**: Users, Properties, Bookings, Reviews, Payments
- **API**: RESTful endpoints, optional GraphQL
- **Authentication & Authorization**: JWT, Role-Based Access Control (RBAC)
- **File Storage**: Property images, profile photos
- **Third-Party Services**: Email (SendGrid/Mailgun)
- **Error Handling & Logging**

## Non-Functional Requirements

- **Scalability**: Modular architecture, load balancing
- **Security**: Encryption, firewalls, rate limiting
- **Performance**: Caching (Redis), optimized queries
- **Testing**: Unit, integration, and automated API testing
