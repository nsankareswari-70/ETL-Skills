# ETL-Skills
## Importing Data from Access File to Excel
- Open the Access file to import
- Click on the External Data tab in the Menu
- Click the excel option
  ![img alt](https://github.com/nsankareswari-70/ETL-Skills/blob/f2a58c9672b9877cd4b8c96c249e57e5b8d09b97/ex94.png)

  Specify the destination and click ok.

  Now you can view the converted Excel file by going to the destination location and clicking the Excel file. Here it's the Office_Address_List.xlsx

  ## How to bring Excel data to Access
  - Open the Access Application
  - From the External Data tab - Click on the New Data Source
    
  - And then click Excel   
 ![img alt]( https://github.com/nsankareswari-70/ETL-Skills/blob/0df50c502711865b46838835aea01cc8d186c683/ex95.png)

   ![img alt]( https://github.com/nsankareswari-70/ETL-Skills/blob/0df50c502711865b46838835aea01cc8d186c683/ex96.png)

Now specify the destination file location and file name, and click the "Link to the data source by creating a linked table" option from the wizard.

   ![img alt]( https://github.com/nsankareswari-70/ETL-Skills/blob/0df50c502711865b46838835aea01cc8d186c683/ex97.png)
Select the sheets you want to copy to Access and click "Next"   

![img alt]( https://github.com/nsankareswari-70/ETL-Skills/blob/0df50c502711865b46838835aea01cc8d186c683/ex98.png)

Check the first row contains Headings and click "Next"    
![img alt]( https://github.com/nsankareswari-70/ETL-Skills/blob/0df50c502711865b46838835aea01cc8d186c683/ex99.png)

Give your table a new name to use in Access. Click Finish.
![img alt]( https://github.com/nsankareswari-70/ETL-Skills/blob/0df50c502711865b46838835aea01cc8d186c683/ex100.png)
 Now you can view your new table in Access. Now close this access file. Go to excel and make some changes in the original file. Here i changed the ID3 name from Lu.Mr.Phil to Lu.Mr.Philipo. And that change in excel is automatically reflected in 
 Access table ...Awesome right! That's because we used "Link to the data source by creating a linked table" option from the wizard.
 ![img alt]( https://github.com/nsankareswari-70/ETL-Skills/blob/0df50c502711865b46838835aea01cc8d186c683/ex101.png)


## Getting Data from a folder 
select Data Menu - Get data from File - File folder
 ![img alt](https://github.com/nsankareswari-70/ETL-Skills/blob/df59d41363d47255c88d47f00c9b364040d1b72d/ex102.png)
 
 ![img alt](https://github.com/nsankareswari-70/ETL-Skills/blob/df59d41363d47255c88d47f00c9b364040d1b72d/ex103.png)

 

  ![img alt](https://github.com/nsankareswari-70/ETL-Skills/blob/df59d41363d47255c88d47f00c9b364040d1b72d/ex104.png)

   ![img alt](https://github.com/nsankareswari-70/ETL-Skills/blob/df59d41363d47255c88d47f00c9b364040d1b72d/ex105.png)
The files inside the folder are displayed.     
Click combine and transform data       
click ok      


## Getting Data from sqlserver database to excel
From the Data tab - Get data - From Database -  Sql server Database
Give the server name and the database name - in the advanced options area -    
select top 100 * from Person.Address;  

Type the above to get only the 100 records (optional)

Then click Load - The data is now loaded in to the excel power query.
Now click the close and load button - to view the sql server data in excel file.  

## Getting Data from a csv file using Legacy wizard in excel
   ![img alt](https://github.com/nsankareswari-70/ETL-Skills/blob/253809018528be0734a0a1d27b9c10d4f4f17434/ex106.png)
From the options menu - click the Data settings. Then click    
From Text legacy import Wizard. Click Ok.    
Select Delimiter and the location you want to copy your data. 

## Connecting Mysql database to excel

To get the books table data from hello_world_db database from Mysql to excel
 ![img alt](https://github.com/nsankareswari-70/ETL-Skills/blob/44ce4107d2d6a375ec9d5e6f3a2d84a3ef3b4c54/ex118.png)

 Open a New excel workbook - From the home tab click Get Data-> From other sources -> From ODBC

 
 ![img alt](https://github.com/nsankareswari-70/ETL-Skills/blob/44ce4107d2d6a375ec9d5e6f3a2d84a3ef3b4c54/ex119.png)

 
 From ODBC dialogue box select the Data Source Name(DSN) - hello_world_db

 
 ![img alt](https://github.com/nsankareswari-70/ETL-Skills/blob/44ce4107d2d6a375ec9d5e6f3a2d84a3ef3b4c54/ex120.png)

 
 In the Navigator window find and click on the hello_world_db to view the tables

 
  ![img alt](https://github.com/nsankareswari-70/ETL-Skills/blob/44ce4107d2d6a375ec9d5e6f3a2d84a3ef3b4c54/ex121.png)
  Now select the "Books" table and click "Load"

  
   ![img alt](https://github.com/nsankareswari-70/ETL-Skills/blob/44ce4107d2d6a375ec9d5e6f3a2d84a3ef3b4c54/ex122.png)
   
Now the data will be loaded to excel
 ![img alt](https://github.com/nsankareswari-70/ETL-Skills/blob/44ce4107d2d6a375ec9d5e6f3a2d84a3ef3b4c54/ex123.png)

 ## Converting Excel Data to a CSV File
 
From the excel file - From File menu - Export - Change File Type - select CSV and click "Save as" and give a new name for the file
click ok

 ![img alt](https://github.com/nsankareswari-70/ETL-Skills/blob/07f9bdb0c56b9e9385248a799ad64ebb42c11113/ex124.png)

 From the destination, you can open and read your CSV file


 ![img alt](https://github.com/nsankareswari-70/ETL-Skills/blob/403621436d4cf1ce9a9a5ef1beb07bc53fe89ffd/ex125.png)


 ## Import CSV file to excel
  ![img alt](https://github.com/nsankareswari-70/ETL-Skills/blob/861ed8b47dab117b4ef05fd53c1cf5f25ee5a7ae/ex126.png)

From the Data menu select from Text/CSV. Select the CSV file to convert and click import. 
Preview of the data is shown in the window - If everything looks ok. Click the load button.                 
Data will be now loaded in to excel in a table format.             
  
   ![img alt](https://github.com/nsankareswari-70/ETL-Skills/blob/861ed8b47dab117b4ef05fd53c1cf5f25ee5a7ae/ex127.png)

 ![img alt](https://github.com/nsankareswari-70/ETL-Skills/blob/2bf329f9701756cbdbb1aabc1729b29f3397eb88/ex128.png)

## Collecting data from multiple web pages

### Pick a webpage and copy its URL, paste it in the box to retrieve data
![img alt](https://github.com/nsankareswari-70/ETL-Skills/blob/a3ba27e6eb7bf0e6a0a22e16c500cd4a581d56fa/ex130.png)
### Create a table for page numbers if you want data from multiple pages (In this example from reviews page 1 -10)

![img alt](https://github.com/nsankareswari-70/ETL-Skills/blob/a3ba27e6eb7bf0e6a0a22e16c500cd4a581d56fa/ex131.png)


![img alt](https://github.com/nsankareswari-70/ETL-Skills/blob/a3ba27e6eb7bf0e6a0a22e16c500cd4a581d56fa/ex132.png)
![img alt](https://github.com/nsankareswari-70/ETL-Skills/blob/a3ba27e6eb7bf0e6a0a22e16c500cd4a581d56fa/ex133.png)
![img alt](https://github.com/nsankareswari-70/ETL-Skills/blob/a3ba27e6eb7bf0e6a0a22e16c500cd4a581d56fa/ex134.png)
![img alt](https://github.com/nsankareswari-70/ETL-Skills/blob/a3ba27e6eb7bf0e6a0a22e16c500cd4a581d56fa/ex135.png)

