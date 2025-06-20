# Bike-Sales-Dashboard
In this project, I explored some bike sales data, to find out purchase trends of customers.

Author: The author of this project is Fred Changi and can be reached at fredojiem@gmail.com .

To start, I created a working sheet. This is becasue the original data will always be availabe for reference whenever needed.

Next, I removed duplicates. This is to ensure my visualizations are accurate and there are no records that may skew the data.

Next, I realized the column on married information and gender information have data as M/S and M/F respectively.
I replaced the married information from M to Married and S to single, so as to make it easier to interprete quickly.

Next, I checked each of the column data types. I set the currency column to the currency data type.

Next, I noticed the ages of the customers in the records are there individually for each customer ranging from 20-60.
Since this might make my visualization cluttered and visually unappealing if I create visuals using age, I opte to create age brackets.
I set those ages <31 to be adolescents, the ages 31-54 to be middle age, and the ages >54 to be old.
This not based on any specific cateogrization, i just used my own creativity for creating the limits for these age brackets.

Next, I went about to build pivot tables.
In my first pivot table, using the average income, gender, and whether purchased or not information, I aimed to investigate the income of the people who did or did not buy a bike.
I had few insights. 
Insight: Generally men are making more money, which is a social issue that has been in debate for many years. 
![image](https://github.com/user-attachments/assets/a92635cc-b225-4a82-90f4-a9c856275a0e)

Also, those who bought bikes are making more money, and this promoted me to check the gender of customers who bought bikes.
Insight: It was interesting to see that the number of men vs women who buy bikes is very close. There is no gender gap.
![image](https://github.com/user-attachments/assets/28e7e877-53a1-442f-91b8-1fc8a5410ca1)

Next, I used a pivot table to investigate the distance of customers.
I met a challenge here when trying to make visuals, where the commute distance ordering was not fully incremental. The '10+ miles' came before '1-2 miles' and '3-4 miles'. 
![image](https://github.com/user-attachments/assets/314c1de5-63f2-4fe6-a591-3847acb66289)

This had a negative impact on the look of visualizations. It made it look like there is a dip in sales then an increase.
I had to find a way to get the software to sort 10+ miles to bottom.
So, the solution that finally worked was renaming '10 miles+' to 'More than 10 miles'.
![image](https://github.com/user-attachments/assets/3527e94b-ed98-42f6-b5ad-2c7da9ccd816)
The insight I found was that: the more the distance a customer needa to cover to work, the lower the chance the customer will purchase a bike.


Next, I created a pivot table to investigate the age brackets of customers.
![image](https://github.com/user-attachments/assets/d5b10587-6997-4557-988e-78e7ad9ecaeb)
Insight: People the age bracket of 31-53, are more likely to purchase a bike.

Now, I went on to create a dashbosrd that can be used by executives to see key information at a glance.
I removed gridlines for aesthetic purposes.
I inserted slicers and connected them to the visuals, so that the visuals can be manipulated.
![image](https://github.com/user-attachments/assets/f0a40a9a-40bc-42ae-87e4-080d72d2258e)

Insight: Married people are making more money on average.  they are more likely to buy a bike.
Insight from pivot tables indicated peope with more income are more likely to buy a bike.
Conslusion: Married people are more likely to buy a bike, which is supported also in the dashboard. 






