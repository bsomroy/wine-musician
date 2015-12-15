# Wine Musician User Stories

## Actors

###1. Anonymous User
* Register or Login
* Search for musicians by criteria:  
  -Location  
  -Price  
  -Style  
  -Reviews  
* Search for wineries by criteria:  
  -Location  
  -Budget  
  -Style 
* Prompt for registration - required prior to booking

    
###2. Musician
* Login
* Create profile  
    -bio    
    -upload picture  
    -genre  
    -hourly rate
* Connect to social  
    -Facebook  
    -Soundcloud  
    -Instagram  
    -Twitter
* Upload sample music 
* Set mood to white, red, or IPA
* Set availability as unavailable, ready, or available tonight
* Search for event by criteria:  
  -Location  
  -Duration  
  -Style  
  -Photos  
* CTA button to request winery's contact info

###3. Winery
* Login
* Search for musicians by criteria:   
  -Location  
  -Hourly rate or duration of event  
  -Style  
  -Reviews  
  -Photos  
* Musicians' contact e-mail and phone visible
* Post event info setting time, budget, style, photos

###4. Admin
* Login
* Add/Delete accounts
* Issue refunds 

---------------------------------
#### Feature: Request to book a wine-music event
As a **musician**  
I want to **search for wineries 50 miles near Sonoma, CA**  
So that **I can book a gig for tomorrow night**  

Scenario: Finding a winery on 12/15/15  
   Given **I have logged in**  
   And **I am on the "Search" page**  
   When **I click on the location bar**  
   Then **I type "sonoma, ca"**  
   And **The map sets a pin on sonoma, ca**  
   Then **I move the slider to 50 miles**  
   And **A 50 mile radius circle grows from the center outward around sonoma, ca**  
   Then **I press the current date in the field**  
   And **A pop-out calendar appears**  
   Then **I select 12/15/15**  
   And **A list of winery events appears below**  
   Then **I press the "$" column header**  
   And **The list is sorted from highest paid event to lowest**  
   Then **I select the top gig**
   And **A pop-up box shows detailed event info**  
   Then **I press the CTA button labeled "Request to Book"**  
   And **A confirmation box appears**  
   And **Then the detailed event info disappears**   
