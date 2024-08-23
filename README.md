# FlightBookingSystem

## Overview

The **FlightBookingSystem** is a backend project developed using a microservice architecture. This system allows users to search for flights, book tickets, manage bookings, and receive reminders. Each microservice is designed to handle specific functionalities, making the system scalable and easier to maintain.

## Microservices

This repository integrates the following microservices as submodules:

1. **FlightsAndSearchService**: Handles the search for available flights, filtering based on criteria like date, destination, and airline.

2. **BookingService**: Manages the booking process, including seat selection and payment processing.

3. **AuthService**: Provides authorization and authentication services, ensuring secure access to the system.

4. **ReminderService**: Sends reminders and notifications to users about their upcoming flights and other relevant information.

## Structure

The repository is structured as follows:

- **FlightsAndSearchService**: [Link to FlightsAndSearchService Repository](https://github.com/jardaanii/FlightsAndSearchService)
- **BookingService**: [Link to BookingService Repository](https://github.com/jardaanii/AirTicketBookingService)
- **AuthService**: [Link to AuthService Repository](https://github.com/jardaanii/Auth_Service)
- **ReminderService**: [Link to ReminderService Repository](https://github.com/jardaanii/ReminderService)

## Getting Started

### Prerequisites

Ensure you have the following installed:

- **Node.js** (v14.x or later)
- **Git** (for cloning repositories)

### Cloning the Repository

Clone the main repository along with its submodules:

```bash
git clone --recurse-submodules https://github.com/jardaanii/FlightBookingSystem.git
cd FlightBookingSystem
and then do npm install

