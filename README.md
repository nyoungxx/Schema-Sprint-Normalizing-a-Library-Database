- What redundancies did you identify in the original unnormalized table?
  The author and publisher data.
   
- How did you decide to split the data into separate tables? What benefits does this bring?
  We decided to make seperate tables from authors and publications. If the pusblisher moves shop or the author changes address  we can update one cell instead of several rows to reflect this in the database.
   
- What challenges did you face when defining relationships between tables?
  We needed to be able to refer to the author by something other than name, because they could always be able to have a name change or we could have two authors with the same name. An author id is created speccifically for each individual same as publishers. 
  
- How does normalization improve data integrity and maintenance?
  We will not have an inconsistent address or any author/publsher because it's only listed in one area. 
  
- How did using feature branches, pull requests, and merging help your team work together?
  It provides us the ability to create queries and not step on each other's toes while doing it. 
