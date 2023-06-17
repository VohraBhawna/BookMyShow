# BookMyShow
This includes Low Level Design of BookMyShow application. 

Following are the Actors involved and their usecases.

1. User

   1.1 Logged in User

       1. Search movie by - name, genre, language, release date
       2. Create Booking includes usecase - selecting seats
       3. Buy ticket includes usecase payments and create ticket
       4. View ticket
 
   1.2 Guest User

       1.  Search movie by - name, genre, language, release date

2. CinemaManager   

   1. Add audis[CRUD] includes adding seating arrangement
   2. Add shows[CRUD]
   3. Create Cinema

3. System

   1. Add movies
   2. Create ticket
   3. Handle payment
