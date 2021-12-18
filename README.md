# Proyect Name:
RestaurantMe

## Description
RestaurantMe is an app where you can easily save and prioritize restaurants you want to visit. It’s your restaurant wishlist. When you don’t know where to eat tonight RestaurantMe will quickly help you find a good place.

## User Interactions
Log-in;
Log-out;
Sign-up;
Homepage;
User Profile;
My Restaurants list;
Add a restaurant;
Search/See restaurant;
Edit restaurant;
Delete restaurant;

## Backlog
Reservation/booking link;
Link to restaurant web page;
Discount offers;
Menu images;

## Models
Restaurant model
```
{
    name: String,
    img: String,
    budget: Number,
    priority: Number,
    openHours: Array,
    veganMenu: String,
    address: String,
    cuisine: String,
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
