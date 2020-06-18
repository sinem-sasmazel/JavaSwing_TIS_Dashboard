# JavaSwing_TIS_Dashboard

This dashboard can be used to manage material delivery dates and delivery status. It is developed using Java Swing and MySql database.

# Functionalities of the Application
- MRP excel file is exported from the SAP L22 into a shared folder via /SAPLOM/MRP transaction once a month.

- TiS application converts excel file into MySql Database. You can transfer the excel file to the MySql DB by clicking on "Excel to DB" button.

- You can login to the TiS application via EMEA ID and TiS password. The password is based on the TiS database. 

![Login](https://github.com/sinem-sasmazel/JavaSwing_TIS_Dashboard/blob/master/Screenshots/Login.JPG)

- You can put the material number and press enter, then related fields come out like material text, delivery dates, disponent, dispomerkmal and status history. Delivery date is calculated by adding 42 days to creation date.

- If this is a new material in the TiS, new ID is assigned to material and "Erstellt am" will be current date.

- You can also enter new delivery date and change the delivery status using "Status Update" area.

- After new material entry or updates, you can use "Save" button.

![Dashboard](https://github.com/sinem-sasmazel/JavaSwing_TIS_Dashboard/blob/master/Screenshots/Dashboard.JPG)

- The sample MRP excel could be like below. It consists material number, material text, disponent and dispomerkmal.
other fields like creation date, delivery date and history come from TiS based on your entries. 

![Sample MRP Excel](https://git.daimler.com/SSASMAZ/TIS_Dashboard/blob/master/Screenshots/Sample%20MRP%20Excel.JPG)









