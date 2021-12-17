# Proyect Name:
RestaurantMe

## Description
RestaurantMe is an app where you can easily save and prioritize restaurants you want to visit. It’s your restaurant wishlist. When you don’t know where to eat tonight RestaurantMe will quickly help you find a good place.

## User Interactions
Sign-up
Log-in
Log-out
Menu/Homepage
User Profile
My Restaurants list
Add a restaurant
Search/See restaurant
Edit restaurant
Delete restaurant

## Backlog
Reservation/booking
Discount offers
Menu images 

## Models
Restaurant model
```
{
    name: String,
    img: String,
    budget: Number,
    rating: Number,
    openHours: Array,
    veganMenu: String,
    address: String,
}
```
User model
```
{
    name: String,
    email: String,
    hashedPassword: String,
    age: Number,
    city: String,
}
```
