# Excel-Data-Cleaning-Manipulation-and-Reports-Financial-Industries-
I create a pivot table to show 2018 and 2019 Total revenue of each industry in National Capital Region, Philippines.
![Screenshot 2022-11-17 151250](https://user-images.githubusercontent.com/118483157/202579823-f28f99fd-287b-4829-ac11-c26abd87f26e.png)
Scenario 1

Create a pivot table showing 2018 and 2019 Total revenue of each industry in the NCR. Did the total revenue for all industries increase or decrease? Which industry has a stable revenue for 2018-2019 (no drastic change)?

1. Create a pivot table using the dataset as data source. Click INSERT from the ribbons, then click Pivot Table, then select the dataset as Table/Range. Choose New Workheet for where you want the Pivot table to be placed.

2. Now that you have created a new worksheet with the pivot table, feel free to drag it wherever you want it to be placed.

3. The fields that will be used here are FY 2018 Revenue, FY 2019 Revenue, and Industry. Region is also needed to filter NCR.

4. Drag each field to the respective pivot table field box.
     a. Industry in Rows
     b. FY 2018 Revenue in Values
     c. FY 2019 Revenue in Values
     d. Region in Filters

6. Make sure that the you are getting the SUM of the values. To change it to SUM, right click on the field, click Value Field Settings, click Sum under Summarize Value by tab and then click OK

7. To answer the queston "Did the total revenue for all industries increase or decrease?" --compare the revenues for each indurstry. There are multiple ways to do this. For example, you can create another column and get the difference between 2018 Revenue and 2019 Revenue by subtracting 2018 from 2019.  Alternatively, you may also get the increase/decrease percentage by subtracting 2018 from 2019 and then dividing by 2018 Revenue.

8. From direct subtraction, you would notice that there will be negative values. Negative values mean the revenue decreased from 2018 to 2019. Positive values mean that the revenue increased from 2018 to 2019.

9. To answer the queston "Which industry has a stable revenue for 2018-2019 (no drastic change)?" -- the goal is to find the industry with the least change from 2018 to 2019. You may refer to the computed field in Step 7.

10. ENERGY is the industry with the least change as seen from the computation.

Scenario 2:

Now the client decides to explore the Energy Industry and needs further information. Create another pivot table to show 2018 and 2019 Total Revenue of each Energy Company in the National Capital Region. Which company would you recommend if the client wants the one with the highest total revenue for 2018 and 2019 combined?

1. Create a new pivot table and repeat Step 1 in Scenario 1 or copy the pivot table in Scenario 1 and paste it in another cell.

2. The fields that will be used here are FY 2018 Revenue, FY 2019 Revenue, Industry, Region, Company.

3. Drag each field to the respective pivot table field box.

    a. Company in Rows
    b. FY 2018 Revenue in Values
    c. FY 2019 Revenue in Values
    d. Region and Industry in Filters

4. In the Region filter, select only NCR, while in the Industry filter, select only Energy.

5. Make sure that the you are getting the SUM of the values. To change it to SUM, right click on the field, click Value Field Settings, click Sum under Summarize Value by tab, then click OK.

6. To answer the queston "Which company would you recommend if the client wants the one with the highest total revenue for 2018 and 2019 combined?" --get the sum of 2018 and 2019 revenue first, then find the highest computed value. There are multiple ways to do this. 

— You can create another colum beside the pivot table and do the manual calculation there; 
— You can create a Calculated Field and do the computation there; 
— You can also compute in the raw data itself by adding a new column, updating the pivot table source, and then refreshing the pivot table. This wil give you a new field, which is your newly created column in the raw data. Drag this new field to the Values box and get the sum.

8. PETRON Corporation has the highest combined revenue
7. Once you have the sum of 2018 and 2019 revenue, compare the values. The goal is to find the highest value.
