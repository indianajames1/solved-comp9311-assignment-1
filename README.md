Download Link: https://assignmentchef.com/product/solved-comp9311-assignment-1
<br>
5/5 - (1 vote)

An online food delivery company hires you to design a small database to store information about the online orders. You’re given the following requirements:

<ul>

 <li>&#x26ab;  A customer is uniquely identified by his/her email. For each customer, we also record his/her name, phone number and address. The address is composed of suburb and street.</li>

 <li>&#x26ab;  A rider is uniquely identified by his/her ID. We will keep record of the rider’s age, gender, phone number and available working periods. Each rider can have multiply available working periods.</li>

 <li>&#x26ab;  A restaurant is uniquely identified by its ID. For each restaurant, the location, the contact person and the contact number will be recorded. The location is composed of suburb and street.</li>

 <li>&#x26ab;  Each restaurant must have one or more dishes and each dish must be provided by exact one restaurant. Each dish contains a name, a short description and a price. A dish is uniquely identified by a restaurant ID and a dish ID.</li>

 <li>&#x26ab;  An order is uniquely identified by an order ID. An order must be created by exact one customer and allocated with exact one rider. A customer can have zero or more orders, but a rider must have delivered at least one order. An order must involve one restaurant, but a customer cannot order from multiple restaurant in one order. For each order, it must contain one or more dishes, and we record the quantities of each dish and the order time. Besides, each restaurant and dish can be included in zero or more orders.Draw an ER diagram to represent the scenario, clearly state the assumptions you make if any.Question 2 (6 marks)Convert your ER-diagram from Question 1 into a relational model.Question 3 (9 marks)Consider the following relational schemas: Song (sID, title, releaseDate) GenreOfSong (sID, genre)Artist (aID, name, age, gender) SongCreating (aID, sID, role)Company (cID, Name, location) JoinIn (aID, cID, joinDate)</li>

</ul>

Please make sure that you always use notations consistent with lecture notes. Different notations will not be accepted. The deadline for assignment 1 is:Fri 11 Oct, 5:00 pm

Write relational algebra expression to answer the following questions:

<ol>

 <li>1)  Find the titles of pop songs that are composed by Taylor Swift. (2 marks)</li>

 <li>2)  Find the titles of songs that are composed by Taylor Swift or Ed Sheeran. (2 marks)</li>

 <li>3)  Find the names of female artists in Universal Music Group who have participated increating some pop songs but have never participated in creating any hip-hop songs. (2marks)</li>

 <li>4)  Find the names of the artists who have participated in creating all genres of songs andhave cooperated with Taylor Swift at least once when creating songs. Note that, Taylor Swift herself should be excluded from the result. (3 marks)</li>

</ol>