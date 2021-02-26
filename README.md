# exceptions_java
Creating custom exceptions with three different solutions: First solution - Very bad; Second solution - Bad; Third solution - Good.
Solution 1 (very bad): validation logic in the main program.
Solution 2 (bad): method returning String.
Solution 3 (good): exception handling.

This program reads the data of a hotel reservation (room number, date of entry, and date of departure) and shows the data of the reservation, including its duration in days. 
Then, read new check-in and check-out dates, update the reservation, and show the reservation again with the updated data. The program must not accept invalid data for the 
reservation, according to the following rules:
- Reservation changes can only occur for future dates.
- The departure date must be greater than the arrival date.
