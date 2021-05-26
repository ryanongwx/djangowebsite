# djangowebsite
Django website project


SQL, Models and Migrations Project To Do List:

For models.py:
- [x] Need to add at least 3 models
- [x] One for auction listing
- [x] One for making bids
- [x] One for comments

Creating of create listing page:
- [x] Input tittle, description, starting bid 
- [x] Url for the attaching of picture
- [x] Category


Active Listing page:
- [x] Default route which means the home page should show all the current active listings
- [x] Active listing should show details such as title description, current price, and photo if have


Listing page:

- [x] When clicked into one of the active listing one the homepage, users should be redirected into the specific item listing page where more details of the listing can be viewed
- [x] If user signed in there is a different page that is shown as stated must use the if user.is_authenticated function to generate a different html based on that
- [x] Function to add for those already signed in is “Add to watchlist”. If item is already on the watchlist, they instead can press “Remove from Watchlist”
- [x] Another function to add for those signed in is the function to bid on the item. The bid cannot be lower than the starting bid
- [x] Once a bid is placed the minimum bid increases accordingly to that price
- [x] Error should be presented if the price is lower than the current bid
- [x] If user is signed in and is the one that has placed the listing, the can “Close the Auction” which makes the highest bidder of the auction the winner and remove the listing from the active listing list.
- [x] If a user is signed in and visits the closed listing page, it should notify him that he has won the auction
- [x] User signed in should be able to add comments to the listing page. Once added the listing page should display all the comments that have been posted


Watchlist
- [x] Signed in users should be able to visit a “Watchlist” page which displays all the listing that the user has added into their watchlist 
- [x] Clicking on the listings should bring them to the listing page

Categories
- [x] A page that shows all the listing categories
- [x] Clicking on any category should bring users to a page where it shows all the active listings in that category

