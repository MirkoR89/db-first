# database name: Hotel Little Italy
# table name: Rooms
- id PRIMARYKEY
- name string
- pictures string VARCHAR (200)
- descriprion string TEXT
- floorNumber TINYINT
- roomNumber number TINYINT
- bedsNumber number TINYINT
- bedType string VARCHAR (30)
- bathroomType string VARCHAR (30)
- priceNumber FLOAT (5,2)
- status string VARCHAR (20)

# table user
- customerID PRIMARYKEY
- name string VARCHAR (50)
- lastname string VARCHAR (50)
- genre string VARCHAR (10)
- address string VARCHAR (50)
- city string VARCHAR (20)
- state string VARCHAR (20)
- zipCode number TINYINT
- country string VARCHAR (20)
- emailAddress string VARCHAR (30)
- phoneNumber number TINYINT
- documentNumber VARCHAR (30)

# booking
- booking ID PRIMARYKEY
- date DATE
- nightsNumbers number TINYINT
- checkIn TIME 
- checkOut TIME
- paymentType string VARCHAR (20)
- tltAmount number FLOAT (5,2)

# extra
- 

