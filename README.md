## Airport

#### TypeScript Challenge

## Purpose

My personal goal with this project was to learn and practice the following technologies:
- TypeScript
- React Testing Library

## Requirements

"Airport"
1. Create a Passenger type with the following properties (+ = required)
   - first name+
   - last name+
   - gender
   - race
   - tested negative for covid+
   - ticket+
2. Create a Friend type that has all of the same properties of a Passenger except for ticket
3. Create a VIP type that has all of the same properties of a Passenger and also has a drink tickets property that tells how many free drink tickets they have.
4. Create a Ticket type. A ticket has the following properties (+ = required)
   - passenger name+
   - departing airport+
   - destination airport+
   - airline+
   - flight date/time+
   - seat number
   - number of bags
NOTE: Some airlines have seat numbers that are just numbers (i.e. 42). Others have a row number (i.e. C42)
5. Valid airlines are: American Airlines, Delta, Southwest, Spirit, United
6. Write an issueTicket function that returns a Ticket with all the necessary properties (passenger name, airline, etc). 
7. Create a variable named Sam that is a Passenger, a variable named Sally that is a Friend, and a variable named Sarah that is a VIP.
8. Write a boardPlane function. You should be able to call this function on Sam or Sarah, but not Sally.