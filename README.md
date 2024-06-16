# UberBackend
Uber Backend in SpringBoot

## MVP (Minimum Viable Product)

### Type of Users
    1. Passenger
    2. Rider
    3. Admin

### Onboarding 

Onboarding of a rider is different from onboarding of a passenger.

Onboarding as a PASSANGER:

    1. Phone Number
    2. Email Id
    3. Password

Oboarding as a RIDER: 

    1. Phone No
    2. Email
    3. Additional Docs
    4. Subject to approval

### Flows to tackle

1. Booking a ride
```
    1. Pickup & drop point
    2. Type of ride
        1. Uber go
        2. Auto
        3. Boat
        4. Black
        5. Luxury ... etc
```
2. Selecting vehicle for a ride : Request goes to all the nearby drivers who have registered themselves in the category or beyond. If the individual has registered itself as Uber Auto then Uber Auto cannot be used as Uber Black.

3. Payments : 3rd Party payments application

```
    1. prepaid
    2. postpaid
```

4. Read OTP
5. Price Calculation
6. Rating System (May or May Not)
7. Passenger should be able to see past rides. Drivers should be able to see their income daily, weekly, & monthly.