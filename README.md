# Booking App

The Booking application is a command-line program that allows users to book tickets for the Go Conference event. It has a set number of conference tickets available, and users can enter their details, including their first name, last name, email address, and the number of tickets they want to book.

The application validates the user input to ensure that the name is not too short, the email address contains the "@" sign, and the number of tickets is valid and within the available ticket range. If the input is valid, the application books the tickets, updates the remaining ticket count, and adds the user's booking information to the list of bookings.

Additionally, the application uses goroutines to simulate the process of sending the ticket confirmation email. It prints the list of bookings, the number of remaining tickets after each booking, and sends the ticket confirmation email after a 10-second delay.

Users are provided with informative messages throughout the booking process, including a welcome message with the available ticket count and an indication when the conference is fully booked.

The Booking application provides a simple and interactive way for users to book tickets for the conference while maintaining the integrity of the booking process and ensuring valid input.
