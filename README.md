# Robotic_Process_Automation
This is the master branch.

SQL Server Installation Guide
1) Go to microsoft.com/en-us/sql-server/sql-server-downloads# and download the free trial. Provide your information as necessary.


2) After submitting your information, SQL2019-SSEI-Eval.exe should be automatically downloaded.


3) Run SQL2019-SSEI-Eval.exe and select the basic installation type when prompted.


4) Accept the terms and conditions.


5) Use the default install location and select "Install." The installation will take a long time (15-20 minutes)









6) Once the installation is complete, a screen like the one shown below should appear. Click on "Install SSMS"










7) You will be brought to the microsoft website. Click on the link "Download SQL Server Management Studio (SSMS)" (If you are not brought to the microsoft website, follow this URL: https://docs.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?redirectedfrom=MSDN&view=sql-server-ver15)







8) Once the download is complete, run the SSMS-Setup-ENU.exe file. Install at the default location.











9) Once the installation is complete, you will be prompted to restart your computer. Restart your computer.









10) Once your computer has restarted, run the Microsoft SQL Server Management Studio. The first time you open SSMS, connect using Windows Authentication. The "server name" field should be automatically populated with the name of your computer.











11) Expand the security folder and right click on "Logins" and select "New Login..."








12) *use replacement picture* Ensure all of you fields match those highlighted in the image below. The password field should be "RPAcapstone"





13) Right click on Databases and select "New Databse..."


14) To fill out the "Owner" field, click on "..."


15) From the "Select Database Owner" window, click "Browse..."

16) From the "Browse for Objects" window, check mark the [admin] object and then click "OK"


17) Once you see [admin] appear in the "Select Database Owner" window, click "OK" on the "Select Database Owner" window.

18) Now that the "Owner" field is populated, select "OK" on the "New Database" window.




19) Right click on your SQL server. For example, mine is "RUSTY-BOI (SQL Server 15.0.2000.5 ...)" and select properties.










20) Click on "Properties" in the panel on the left. Then ensure that "SQL Server and Windows Authentication mode" is selected. Click "OK."



21) You will likely need to restart SQL Server for the change to take effect. To do this, open the SQL Server Configuration Manager. Right click on "SQL Server (MSSQLSERVER)" and select "Restart"


22) From now on, when you run SSMS, you can choose to connect using "SQL Server Authentication" with the "admin" login username and the "RPAcapstone" password.


