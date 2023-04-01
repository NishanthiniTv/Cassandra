# Cassandra
Cassandra is an open source NoSQL distributed database trusted by thousands of companies for scalability and high availability without compromising performance. Linear scalability and proven fault-tolerance on commodity hardware or cloud infrastructure make it the perfect platform for mission-critical data.

**LIBRARY MANAGEMENT SYSTEM**

This project uses Cassandra, a distributed, non-relational database management system, for storing and accessing data. The project creates three tables - books ,users and borrow history- and inserts data into them and the datas are displayed using the Select command.

**BOOKS:**

  The book table contains the followings,
  
     1. book_id 
     2. title 
     3. author 
     4. publisher 
     5. publish_date
     
** USERS:**

  The users table contains the followings,
  
      1.user_id
      2.name
      3.email
      4.phone
    
**BORROW HISTORY:**

  The borrow history table contains the followings,
  
      1.book_id,
      2.user_id, 
      3.borrow_date
      4.return_date
