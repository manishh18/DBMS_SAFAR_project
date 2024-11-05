# Project SAFAR

## Overview
Project SAFAR is a data management project for managing a ride and courier service system. This project includes schema design, normalization, and various data tables to store information about drivers, vehicles, schedules, bookings, and customers.

## Features
- **ER Diagram**: Visual representation of entity relationships in the system.
- **Relational Schema**: Detailed schema for each table to organize the data.
- **Normalization Proofs**: Verification of each table to ensure it conforms to BCNF (Boyce-Codd Normal Form).
- **DDL Scripts**: SQL scripts for creating each table in the system.

## Database Tables

The project includes the following tables:
1. **Driver**: Information on drivers including ID, name, availability, and ratings.
2. **Vehicle**: Data about vehicles, including type and inspection status.
3. **Schedule**: Shifts and schedules for each driver.
4. **Owner**: Information about vehicle owners.
5. **Rents and Hires**: Records for renting or hiring vehicles.
6. **Customer**: Customer details such as contact information, membership, and ratings.
7. **Membership**: Membership data including type, benefits, and dates.
8. **Booking**: Details on each booking, including locations, fare, and ratings.
9. **Penalty**: Penalties issued during bookings.
10. **Courier Service**: Data for courier-based bookings.
11. **Service Type**: Types of services offered (ride, courier, etc.).

Each table is in BCNF, ensuring that each non-trivial functional dependency has a superkey.


## Usage
After setting up the database, users can interact with the tables for managing bookings, driver schedules, and more. 

## Contributing
Contributions are welcome. Please fork the repository and create a pull request.

