Car DB
Table: CARS
Entity: CAR

id (BIGINT, PRIMARY KEY, AUTO_INCREMENT)
brand (VARCHAR 50) NOT NULL
model (VARCHAR 50) NOT NULL
year (YEAR) NOT NULL
mileage (INT) NOT NULL
license_plate (VARCHAR 10) NULL, UNIQUE
fuel_type (VARCHAR 20) NOT NULL
euro_class (VARCHAR 6) NOT NULL
price (FLOAT 8,2) NULL
color (VARCHAR 30) NOT NULL
transmission (VARCHAR 20) NOT NULL
engine_capacity (VARCHAR 6) NOT NULL
engine_power (VARCHAR 6) NOT NULL
new_license_holders (TINY INT 0/1) NOT NULL
horse_power (VARCHAR 4)
description (TEXT) NULL
year (YEAR) NOT NULL
created_at (DATETIME) 
updated_at (DATETIME) 