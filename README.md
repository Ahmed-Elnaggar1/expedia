
# Expedia.com

A simple Expedia.com implementation in c++
applying some polymorphism and OOP concepts.

#### Expedia user have several *itineraries*, each consist of
* 0 or more flights, hotels, cars, etc. E.g. 4 flights, 2 hotels and 2 cars.
#### An itinerary item  -e.g a filght- has :
* Its own cost
* Its info: E.g. A flight has request from user, and his selected flight details
  - E.g. Hotel cost: total nights x price per night
* Itinerary cost is the sum of all internal items cost.
#### For Simplicity
* Dummy data is used
* 2 Types of users: Admin & customer. Our code focus is on customer part
* Local APIs is used to call for flights and hotels 



