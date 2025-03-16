# GOLANG_PROJ
# Booking Application - Go Conference

This is a simple booking application written in Go. It allows users to book tickets for a conference by providing their details and the number of tickets they want to purchase.

## Features
- User-friendly CLI interface for booking tickets.
- Validates the user input (name, email, ticket count).
- Concurrent ticket booking using Goroutines.
- Email confirmation simulation with a delay.
- Tracks remaining tickets and prevents overbooking.

## How It Works
1) The application greets users and provides details about available tickets.
2) Users enter their details.
3) Input validation ensures correct data entry.
4) Successful bookings update the available tickets and stores the user data.
5) Tickets are "sent" using a simulated delay of 50 seconds with Goroutines.
6) If tickets run out, the application notifies users.

## Future Enhancements
- Implement database storage for bookings.
- Add a web interface using Go’s `net/http` package.

