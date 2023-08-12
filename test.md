table
  | Entity | Attribute | Data Type | Description |
  |-----|------|------|------|
  | Booking | id | int | Primary key |
  | studentId | int | Foreign key to Student.id | ID of the student who made the booking |
  | accommodationId | int | Foreign key to Accommodation.id | ID of the accommodation that was booked |
  | startDateTime | datetime | | Start date and time of the booking |
  | endDateTime | datetime | | End date and time of the booking |
