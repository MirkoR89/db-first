# database name: Hotel Little Italy

# table name: Rooms
- roomID PRIMARYKEY
- name string
- floor_number TINYINT
- room_number number TINYINT
- price_for_night FLOAT (5,2)
- status string VARCHAR (20)

# table name: Rooms details
- pictures string VARCHAR (200)
- descriprion string TEXT
- beds_number number TINYINT
- bed_type string VARCHAR (30)
- bathroom_type string VARCHAR (30)

# table customers
- customerID PRIMARYKEY
- name string VARCHAR (50)
- lastname string VARCHAR (50)
- genre string VARCHAR (10)
- email_address string VARCHAR (30)
- phone_number number TINYINT
- document_number VARCHAR (30)

# table Customers address details
- customer_detailsID PRIMARYKEY
- address string VARCHAR (50)
- city string VARCHAR (20)
- state string VARCHAR (20)
- zipCode number TINYINT
- country string VARCHAR (20)

# booking
- bookingID PRIMARYKEY
- date DATE
- nightsNumbers number TINYINT
- checkIn TIME 
- checkOut TIME
- total_Amount number FLOAT (5,2)

# Payments
- PaymentID
- amount number FLOAT (5,2)
- date_transiction DATE
- time_transiction TIME
- payment_type VARCHAR (20)