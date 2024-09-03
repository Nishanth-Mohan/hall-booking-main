# Hall-Booking-API-Task

## Back-end Deployed URL:
https://hall-booking-main-7n13.onrender.com


## 1. Create Room

Endpoint to create a new room with specified number of seats, amenities, and price per hour

POST-Method
https://hall-booking-main-7n13.onrender.com/rooms

        { "seats":6,
          "amenities":["ThreeDoubleBed","fridge","WaterHeater"],
          "pricePerHour":12000 
        }

------------------------------------------------------------------------------------------------------------------

## 2. Book a Room

Endpoint to book a room, checks for availability and creates a booking if available

POST-Method
https://hall-booking-main-7n13.onrender.com/bookings

   {
    "customerName":"Nisha",
    "date": "05-09-2024", 
    "startTime": "14:00", 
    "endTime": "17:00", 
    "roomId": 3
  }

----------------------------------------------------------------------------------------------------------------------

## 3. List all rooms with booked data
 
Endpoint to list all rooms along with their booking details

GET - Method
https://hall-booking-main-7n13.onrender.com/rooms


-----------------------------------------------------------------------------------------------------------------------

## 4. List all customers with booked data

Endpoint to list all customers along with their booking details

GET - Method
https://hall-booking-main-7n13.onrender.com/customers

--------------------------------------------------------------------------------------------------------------------

## 5. List how many times a customer has booked the room

Endpoint to list all bookings made by a specific customer with detailed booking information

GET - Method
https://hall-booking-main-7n13.onrender.com/customer/Nishanth

----------------------------------------------------------------------------------------------------------------------

