table
  | Entity | Attribute | Data Type | Description |
  |-----|------|------|------|
  | AccommodationOffice | id | int | Primary key |
  | name | varchar(255) | | Name of the accommodation office |
  | address | varchar(255) | | Address of the accommodation office |
  | phone | varchar(255) | | Phone number of the accommodation office |
  | email | varchar(255) | | Email address of the accommodation office |


  |-----|------|------|------|
  | Accommodation | id | int | Primary key |
  | type | varchar(255) | | Type of accommodation (e.g., single room, double room, apartment) |
  | size | int | | Number of beds in the accommodation |
  | price | int | | Price of the accommodation per night |
  | availability | boolean | | Whether the accommodation is available |


  |-----|------|------|------|

  | Booking | id | int | Primary key |
  | studentId | int | Foreign key to Student.id | ID of the student who made the booking |
  | accommodationId | int | Foreign key to Accommodation.id | ID of the accommodation that was booked |
  | startDateTime | datetime | | Start date and time of the booking |
  | endDateTime | datetime | | End date and time of the booking |
