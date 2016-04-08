# March 2016 Changes
## Started to log progress on March 17. Previous changes were not logged :disappointed:

### 3/31/2016
  Add description to trading interface  
  Change mobile text and link for homepage  
  Add reset filters on homepage
  Fix datepicker for signup  

### 3/30/2016
  Add webhook notifications for stripe  
  Add Notification for trade request when starred
  Remove 30 day free trial  
  Remove checkbox and terms of conditions iframe  

### 3/29/2016
  Add trade request on user's profile
  Change Followed Person text
  Subcategories are on by default
  Add Star to people's profile listings
  Default Email Notifications to false.
  Add buyer id and seller id to MySQL
  Change trading interface  
  Change listing image to 990x660
  Change image pictures to be higher quality  
  Add Overlay for star and date updated/uploaded for people listings  
  Add terms and conditions  

### 3/28/2016
  If user is logged in, they can't log in again.  
  Add color coding to inbox!  
  Edit suspect fraud text
  Add mobile for Tawk contact
  Change text for reason for Tawk

### 3/24/2016
  Major update!
  Users can choose the listings they want to trade rather than it being random.

### 3/22/2016
  Added Column to MySQL with new conversation type  
  Add USPS Code update  
  Can't reply to notification type in conversations
  Link to listings in trading UI  
  Link to USPS Code in trading UI
  Change Testimonial link button  
  Change inbox to Notification and display type
  Change inbox/message icon to notifications. Bell icon added.  
  Remove Invitation from menu
  Change notification message to "I"  
  Users can review only once per convo  

### 3/19/2016
  Add check for prepaid/gift cards for subscription
  Non subscribed people cant get messages from likes  
  Added Better checkbox for terms and conditions  
  Added Cardholder Name to subscriptions  
  Add Birthday and Gender
  Add Parental Consent for under 18
  Added terms for facebook login  

### 3/18/2016
  Stripe will also be deleted when user deletes account
  Starred only appears when you are subscribed  
  Filters scrolls back to user location
  Make function to get card from Person model
  Added Last 4 digits of card to account settings
  Fix starring for closed listings  
  Change map preferences  
  Change Listing Image Size to 990x660?

### 3/17/2016
  Changed the entire user trading interface.  
  Added State to the address.
  Also added addresses needed to controller
  Added state and divider
  Added new thing for signup  
  Added id for sign up button
  Change email placement for signup
  Added Cookie Values for sign up with email  
  Changed expiration time for cookies to 15 min
  Move code to custom.js  
  Add js cookie
  Only subscribed users can write comments  
  Change the small text.  
  Removed Map for user settings
  Remove irrelevant notifications EMAIL_NOTIFICATION_TYPES  
  Added Trial and Discount checks
  Add Subscription Values
  Change Menu Links
  Stripe (So that previous people who cancel will have no free trial. This also makes it so that when ppl cancel during free trial, they wont have it.)
  Also changed so that card declined doesnt work  
