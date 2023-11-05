## How to Run MSSQL ON MAC M1

Watch this YT Video: https://www.youtube.com/watch?v=glxE7w4D8v8&t=636s

From the Video:

1. Install the Docker.

2. Run MySQL Server on Docker (Proper Instruction with commands in Video)

3. Download Azure Data Studio

4. Connecting Azure Data Studio to SQL Server running on Docker.

5. Go to Azure Data Studio. Create the Connection

IMPORTANT - Not in the Video (Restoring the .Bak File Provided in the Course)

5. You have to import the Bak File inside the Docker SQL Server Image Running. To do so --> Open Docker, Find the SQL container and click on three dots in right and select to View Files. Upload the Bak file in any folder.

You have to do this because the when you will click on restore in Azure Data Studio, it will only allow you to preview the Files only present in the Docker sql container and will not let you search inside the local files.

6. Go to Azure Data Studio. Make sure to select Yes on preview feature the popup in the begining it shows everytime.

7. Click on any Database and select Restore.

8. Choose the Backup from dropdown and select the .bak files that we have placed in the docker.
