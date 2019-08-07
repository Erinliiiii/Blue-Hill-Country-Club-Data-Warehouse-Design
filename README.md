# Blue-Hill-Country-Club-Data-Warehouse-Design
## Step 1: Created database which contains the 10 tables summarized below, with transactional data related to one year of operations of xxx Country Club.
**Membership data tables:**
memberships - one record per membership
members - one record per person (multiple family members can be included on the same membership account)
**Revenue data tables:**
dining - transaction records from dining room
golf - transaction records from golf course
pool - transaction records from pool
tennis - transaction records from tennis courts
other - transaction records from miscellaneous activities
**Other data tables:**
promoone - list of members who signed up for one of the club’s promotional offers
promotwo - list of members who signed up for the second of the club’s promotional offers
special - A series of Boolean variables indicating whether the member attended one of 4 special functions in 2018.
