# Trade Trendy Change Log
Change Log to Trade Trendy (Private Repo), because I need to be more organized

### Menu
- [Todo List](#todo-list)
- [Ideas](#ideas-for-the-future)
- [Changes](#change-log)
  - [2016](#2016)
    - [April](#april-2016)
    - [March](#march-2016)

## Todo List
- [ ] Fix mobile grid/map to float right correctly
- [ ] Finalize FAQ page and questions
- [ ] Minify all scripts and css before launch
- [ ] Fix height of Star/grid item for Firefox
- [ ] Add Admin controls for trade view
- [ ] Add notifications for Stripe to users
- [ ] Get feedback from initial users

## Ideas for the future
* Checkbox onclick refreshes the grid: Need to figure out AJAX for that
* Filter inbox by Trade Requests
  * Inbox Row change trade request to trade finished?
* Dropdown Menu for shipping tracking postal company
  * If company, then link to their tracking.
  * EX:  %a{:href => "https://tools.usps.com/go/TrackConfirmAction.action?tLabels=#{usps_code_other.to_s.delete(' ')}", :target => "\_blank"}
* Search by people's names + Brand
* Make username can't have a curse word
* Notification for Followed person's new listing
* Notification for new comments on posts
* Can't post listing without at least one photo
* Make it so conversations can be hidden
  * Hide button in inbox rows. Make a column for conversations for hide, and if hidden is true, then dont show
  * Link to hidden conversations where they can unhide (Update attributes hide: true or false)
  * Need to make it so that is is marked as read as well for incoming messages.
* Change settings -> account view
  * Make it so that the changing/cancelling is better. Probably using popup instead of alert

## Change Log
### 2016
#### April 2016
##### Quick Summary:
* Add Multiple Trading feature
* Admins can view conversations if reported
* Add username to FB Registration
* Change name to username in views for users
* For full change log, [CLICK HERE](changes/april2016.md)

#### March 2016
##### Quick Summary:
* Remove Free Trial for business purposes
* Add Homepage and New Listing Javascripts
* Change layout of listings and star
* Remove auto trade feature and users can choose which listings to trade
* Add Shipping Tracking Code
* Add more signup features (Address, Gender, Birthday)
* Major changes to Stripe payment controller
* Change entire trading interface
* For full change log, [CLICK HERE](changes/march2016.md)
