# CS260-projects-
The company eBid Nashville are looking to expand their website. eBid is a company that does online auction online that sales a wide range of items. The company would like to expand their website to show past items that were sold on their website. My goal in the document is to show you some data structures and algorithms that I built to test, and in the end to give you my final opinion on what is best for eBid websites.  

The first program that I have in our report shows how we can store and show their data. The data that is stored in this vector comes from the excel sheet of the monthly sales since January 2014. We do use CSVparser.cpp and CSVparser.hpp to help separate the information in the file for it to be viewed easier in our program. Each item is divided by its bid Id, title, fund and amount.  As for sizes for vectors they can keep growing without needing a set size. This is great for eBid since the sales data will keep growing over time, which helps us from needing to go back and change the program in this area. The constraint that we come across vectors is that they can be very slow. The way we can fix this is by optimizing the code and allowing the vector to resize.  

Another good data structure that can be considered are hash tables. This data structure gives key to each item in the excel sheet and will use that information to store it on the hash table. This runs faster than using a vector, because it has fewer areas where it needs to look. However, not everything is going to be perfect, and collision does happen.  One way to handle collision is to use chaining. Chaining allows more than one item to be stored in a single bucket. When you search for an item, it will go with the first item and will go to the next item in the bucket until the item is found. Another way to handle the collision is linear probing. Linear probing keeps the item in a single bucket while if collision would happen the item would go into the next empty bucket. As for these solutions are made, it gives more opportunity for eBid to run their website much faster than just having a regular vector.  As for the company to create more sales, would the hash table be able to keep up with demand? At the worst the program could keep up being linear leaving a long search.  

For data that will be coming from eBid it could wise to consider a binary tree for our data structure. Binary trees allow the information to split into two sections with one side having higher values and the other having smaller values.  This is done by having a parent node that creates two child nodes and then those child nodes make more child nodes until there are no more.  In the end you have a tree full of information showing the relationship of everything. As for eBid this could be best to put all their past information in.  Separate the values of each bid id and put down the side of the tree to create a perfect path for the structure. Doing this does great for searching for the values since it can go down a list of yes and no to find a path that is faster to get to the data. However, it could cause issues when deleting information because it can make big changes to the data structure. Another big issue with binary trees is that it could have a large height and can take it a long time to find an item if it’s down the tree. 

Algorithms are great to help run your program. Having the right algorithm will bring faster results and have your program run smoothly. A search algorithm is one of the simplest ways of achieving results in your program. The first search I will explain is linear.  A linear search starts at index 0 and will keep going down the list until item. As stated, before linear searches are okay, but they can lead to a long wait time, especially with dealing with data like eBids. Another way you can use searches are binary.  Binary will search by having two values looking into and finding the value so it could reduce the time.  

Dealing with the history of sales, it could be a good idea to use a sorting algorithm. Sorting takes all the information from a database and sorts it into ascending or descending order.  This could be a good way to show on the website of eBid’s sales over a certain period. Sorting has great ways to insert an item and still find the correct spot for it. The only problem I can see with its sorting is that it could be slow as linear, but you can sort lists.  

Hashing and chaining is the only algorithm that works with hash tables.  As stated above, hash tables give hash number to each of the values and put aligns themselves in a spot. One way that this happens is by chaining. Chaining works by using the hash number and putting it in that spot. However, that spot may be filled and what it does next will fill itself in the next open space. Hashing does the complete the opposite and add the item into the list to help reduce time to find item. 

Overall, all these algorithms and structures are great and can help a database. However, having the right structure and algorithm allows a program to run at its best. This is not only good for us but also for our client. In my opinion I believe hash tables and hashing would be the best to deal with eBid database. Out of all the testing hash tables they turned out to be the fastest and most officiant for what eBid would need. Displaying all the bids in this format does leave with a lot of empty slots, but I think would help with the code being reusable and those spots possibly being filled in the future.  While making this code I created a formula to show the hash number in the excel file so that in the future when others work on this program, they will be able to see and play around with the information.  We can check our program and see while doing the hashing that the program is putting the data structure in a correct way. Not only that, but the code is also explained in detail where all the areas of the script are and what they do. If eBid decides to add extra information on each bid the program only needs to add that into the structure to the Bid.  Finally, as eBids sales grow we have ability to resize the hash table in our hash table variable  

This course not only helped me understand the value of C++ but also gave me insight on the importance of a good data structure.  My last classes we always try to build a good rough draft and draw it out in a diagram. These diagrams are important especially with data structure. We need to have an idea what our data is going to look like. I think it wise that we are at the point where we should continue to practice a good structure, so when we get to a job, we can get the program done at its best.  This also goes with the algorithm. We need to continue to draw out and practice making them so we can have a better experience with them. Honestly, I do need to work more on my portfolio so I can have something that I could give to the company that I decide to work for.The company eBid Nashville are looking to expand their website. eBid is a company that does online auction online that sales a wide range of items. The company would like to expand their website to show past items that were sold on their website. My goal in the document is to show you some data structures and algorithms that I built to test, and in the end to give you my final opinion on what is best for eBid websites.  

The first program that I have in our report shows how we can store and show their data. The data that is stored in this vector comes from the excel sheet of the monthly sales since January 2014. We do use CSVparser.cpp and CSVparser.hpp to help separate the information in the file for it to be viewed easier in our program. Each item is divided by its bid Id, title, fund and amount.  As for sizes for vectors they can keep growing without needing a set size. This is great for eBid since the sales data will keep growing over time, which helps us from needing to go back and change the program in this area. The constraint that we come across vectors is that they can be very slow. The way we can fix this is by optimizing the code and allowing the vector to resize.  

Another good data structure that can be considered are hash tables. This data structure gives key to each item in the excel sheet and will use that information to store it on the hash table. This runs faster than using a vector, because it has fewer areas where it needs to look. However, not everything is going to be perfect, and collision does happen.  One way to handle collision is to use chaining. Chaining allows more than one item to be stored in a single bucket. When you search for an item, it will go with the first item and will go to the next item in the bucket until the item is found. Another way to handle the collision is linear probing. Linear probing keeps the item in a single bucket while if collision would happen the item would go into the next empty bucket. As for these solutions are made, it gives more opportunity for eBid to run their website much faster than just having a regular vector.  As for the company to create more sales, would the hash table be able to keep up with demand? At the worst the program could keep up being linear leaving a long search.  

For data that will be coming from eBid it could wise to consider a binary tree for our data structure. Binary trees allow the information to split into two sections with one side having higher values and the other having smaller values.  This is done by having a parent node that creates two child nodes and then those child nodes make more child nodes until there are no more.  In the end you have a tree full of information showing the relationship of everything. As for eBid this could be best to put all their past information in.  Separate the values of each bid id and put down the side of the tree to create a perfect path for the structure. Doing this does great for searching for the values since it can go down a list of yes and no to find a path that is faster to get to the data. However, it could cause issues when deleting information because it can make big changes to the data structure. Another big issue with binary trees is that it could have a large height and can take it a long time to find an item if it’s down the tree. 

Algorithms are great to help run your program. Having the right algorithm will bring faster results and have your program run smoothly. A search algorithm is one of the simplest ways of achieving results in your program. The first search I will explain is linear.  A linear search starts at index 0 and will keep going down the list until item. As stated, before linear searches are okay, but they can lead to a long wait time, especially with dealing with data like eBids. Another way you can use searches are binary.  Binary will search by having two values looking into and finding the value so it could reduce the time.  

Dealing with the history of sales, it could be a good idea to use a sorting algorithm. Sorting takes all the information from a database and sorts it into ascending or descending order.  This could be a good way to show on the website of eBid’s sales over a certain period. Sorting has great ways to insert an item and still find the correct spot for it. The only problem I can see with its sorting is that it could be slow as linear, but you can sort lists.  

Hashing and chaining is the only algorithm that works with hash tables.  As stated above, hash tables give hash number to each of the values and put aligns themselves in a spot. One way that this happens is by chaining. Chaining works by using the hash number and putting it in that spot. However, that spot may be filled and what it does next will fill itself in the next open space. Hashing does the complete the opposite and add the item into the list to help reduce time to find item. 

Overall, all these algorithms and structures are great and can help a database. However, having the right structure and algorithm allows a program to run at its best. This is not only good for us but also for our client. In my opinion I believe hash tables and hashing would be the best to deal with eBid database. Out of all the testing hash tables they turned out to be the fastest and most officiant for what eBid would need. Displaying all the bids in this format does leave with a lot of empty slots, but I think would help with the code being reusable and those spots possibly being filled in the future.  While making this code I created a formula to show the hash number in the excel file so that in the future when others work on this program, they will be able to see and play around with the information.  We can check our program and see while doing the hashing that the program is putting the data structure in a correct way. Not only that, but the code is also explained in detail where all the areas of the script are and what they do. If eBid decides to add extra information on each bid the program only needs to add that into the structure to the Bid.  Finally, as eBids sales grow we have ability to resize the hash table in our hash table variable  

This course not only helped me understand the value of C++ but also gave me insight on the importance of a good data structure.  My last classes we always try to build a good rough draft and draw it out in a diagram. These diagrams are important especially with data structure. We need to have an idea what our data is going to look like. I think it wise that we are at the point where we should continue to practice a good structure, so when we get to a job, we can get the program done at its best.  This also goes with the algorithm. We need to continue to draw out and practice making them so we can have a better experience with them. Honestly, I do need to work more on my portfolio so I can have something that I could give to the company that I decide to work for.
