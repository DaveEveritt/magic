# Magic Squares

Don't forget to set up a .env file with login info.



## Todo

- [x] update design docs with rev if needed
- [x] test and check the new createOrder function
- [x] upload single input to DB
- [x] create design doc for each display style
- [x] query doc? see contribute
- [x] contribute, check for transformations
- [x] add other higher order displays
- [x] check sharedLengths in index - broken
- [x] use db.view('order', 'numeric') to get sorted list
- [x] save contributions in log file too (with dates, etc)
- [x] mobile style
- [x] selectively update only changes for bulk index (not possible)
- [x] improve gallery style
- [x] sort local source file every time a new square is added
- [x] tetris shapes for digital roots
- [x] stroke width
- [x] add size options
- [x] add colour options
- [x] add padding options
- [x] add themes
- [x] fix 880/383 options for quadvertex4
- [x] themes load only after page reload
- [x] order option "change" event needs adding, so both wheel and change work
- [x] add option to overlap all completely
- [x] fix eventListeners and that for overlapAmount
- [x] add share button
- [x] enable query parameters for bookmarking and sharing
- [x] PWA stuff, service workers, etc
- [x] couch sharedLengths reducer for all orders
- [x] couch remove shared lengths from index (not needed)
- [x] reverse update sources from COUCH to LOCAL (for stuff added online but not via localhost)
- [x] still a problem with local having more new items than server and then ignoring and overwriting server... needs cross checking both ways, item by item
- [x] update/push cache with changes
- [x] move generateSharedLengths to mapreduce filter view in couch?
- [x] use indexedDB to be able to access settings via service worker
- [ ] add printing options
- [ ] add pin-to-top / favourite feature for individual squares
- [ ] hover info for each square or put into modal
- [ ] number overlay?
- [ ] fix line width for arc and altarc
- [ ] fix mobile style again
- [ ] manual order change triggers two draws of squares
- [ ] finish defining data lists for ranges
- [ ] insert intersection observer sooner? at 150?
- [ ] digital root, connect number pairs
- [ ] art sketch, basic dasharray len / order^2
- [ ] animation broken?
- [ ] couch don't regen index on contribute - change _ids and sorting
- [ ] check if contribute allows higher orders than exist on server at that point
- [ ] enable a fixed width rather than percentage to allow different line breaks in svg grid
- [ ] merge sharedLengths into one file via couch? to simplify caching






add dropdown for shared lengths per order
add search box for single input and multiple inputs





filters:
  - length
  - id/order + ranges

hover info modal?:
  - id
  - order
  - style
  - numbers
  - similar ids?
  - numbers overlay?





## Nano CouchDB

https://jo.github.io/couchdb-best-practices/
