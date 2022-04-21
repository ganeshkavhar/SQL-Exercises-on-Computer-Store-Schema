# SQL-Exercises-on-Computer-Store-Schema
![image](https://user-images.githubusercontent.com/20369800/164385682-7671a284-c376-403f-9e56-03758698a54f.png)
## Questions

1. Select the names of all the products in the store ? </br>
SELECT Name FROM Products;

2. Select the names and the prices of all the products in the store ? </br>
SELECT Name, Price FROM Products;

3. Select the name of the products with a price less than or equal to 200 ? </br>
SELECT Name FROM Products WHERE Price <= 200;

4. Select all the products with a price between 60 and 120 ? </br>
 /* With AND */ </br>
   SELECT * FROM Products </br>
   WHERE Price >= 60 AND Price <= 120;  </br> 
 
 /* With BETWEEN */ </br> 
   SELECT * FROM Products </br> 
   WHERE Price BETWEEN 60 AND 120; </br>
