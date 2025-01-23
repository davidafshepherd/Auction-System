'AuctionSystem' is the project directory. 

Specification of the online auction service:   
1. The online auction service allows users to submit items for auction and to bid for items that are being auctioned.
2. Users must be registered with the system in order to be able to submit items for auction and in order to place bids. Thus, a user can take both seller and bidder roles. The user’s name, status, login id and password are recorded. User status records feedback given to the user by other users, and any penalty points the system has added.
3. The system should be able to manage multiple auctions.
4. A user (seller) with no more than two penalty points may submit an item for auction. The system creates a new auction and opens the auction to bids from other users (bidders). The system makes available the auction information the seller’s feedback and penalties. An auction has only one seller. No user may be a bidder for an auction for which they are the seller.
5. When a seller submits an item for auction, they must provide a name for the item, start and end times for the auction and a reserve price for the item.
6. The seller may cancel their auction without penalty at any time until a bid no less than the reserve price is accepted. They may cancel after such a point and before auction closure but will then receive a penalty point. When an auction is cancelled all bidders are informed.
7. When a bidder makes a bid on an auction, the bid must be higher than the current highest bid for that auction.
8. When an auction duration has passed, that auction is closed.
9. For a defined period after auction cancellation or closure, bidders may provide feedback on the seller.
10. A closed auction succeeds if the highest bid is at least as high as the reserve price, otherwise it fails. When a closed auction succeeds, the winning (highest) bidder is informed.
11. A seller should be able to see the status of their auction at any stage after their auction has started.





