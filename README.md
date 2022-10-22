# Article CMS (FlaskWebProject)

This project is a Python web application built using Flask. The user can log in and out and create/edit articles. An article consists of a title, author, and body of text stored in an Azure SQL Server along with an image that is stored in Azure Blob Storage. You will also implement OAuth2 with Sign in with Microsoft using the `msal` library, along with app logging.

## Log In Credentials for FlaskWebProject

- Username: admin
- Password: pass

Or, once the MS Login button is implemented, it will automatically log into the `admin` account.

# Submission:
## Create a resoucre group with the following services:
<img width="1432" alt="Screen Shot 2022-10-22 at 4 34 33 PM" src="https://user-images.githubusercontent.com/50755701/197341939-82c254af-7525-4a40-9d34-d53ae45dbfab.png">

# Create an SQL Database in Azure that contains a user table, an article table, and data in each table (populated with the scripts provided in the SQL Scripts folder).
<img width="1426" alt="Screen Shot 2022-10-21 at 6 06 06 PM" src="https://user-images.githubusercontent.com/50755701/197342147-1374d7bc-9c66-4424-afa1-87c3d6d5217a.png">
<img width="1440" alt="Screen Shot 2022-10-21 at 6 06 40 PM" src="https://user-images.githubusercontent.com/50755701/197342153-4ba2507c-5592-40d2-91c1-b987d2a54b71.png">
<img width="1335" alt="Screen Shot 2022-10-21 at 6 07 02 PM" src="https://user-images.githubusercontent.com/50755701/197342160-af6d297c-ec5f-499b-bc99-295d8ad245b9.png">
<img width="1440" alt="Screen Shot 2022-10-21 at 6 07 14 PM" src="https://user-images.githubusercontent.com/50755701/197342162-9737baee-95fa-4f63-8a3e-aa36fb38e5f0.png">
<img width="1420" alt="Screen Shot 2022-10-22 at 4 37 24 PM" src="https://user-images.githubusercontent.com/50755701/197342175-8ec045ce-4376-4fb0-b41c-f7094cbafd6c.png">

## Create a Storage Container in Azure for `images` to be stored in a container.
<img width="1438" alt="Screen Shot 2022-10-21 at 6 25 34 PM" src="https://user-images.githubusercontent.com/50755701/197342393-e9906518-6382-48ca-a621-939a6a764ce2.png">
<img width="1389" alt="Screen Shot 2022-10-22 at 4 28 57 PM" src="https://user-images.githubusercontent.com/50755701/197342538-407ab1ed-10b2-4bf2-8b3b-71cd8d395028.png">

## Sign In With Microsoft button + username and password successful attemp:
<img width="1012" alt="Screen Shot 2022-10-22 at 4 22 19 PM" src="https://user-images.githubusercontent.com/50755701/197342594-e42d9946-74c2-44ed-a7ff-0e2fef927e13.png">
<img width="1308" alt="Screen Shot 2022-10-22 at 4 22 40 PM" src="https://user-images.githubusercontent.com/50755701/197342595-87269f90-2c97-426f-b674-b8d23576c01c.png">
<img width="1300" alt="Screen Shot 2022-10-22 at 4 21 33 PM" src="https://user-images.githubusercontent.com/50755701/197342576-b72eb450-59fd-4683-bf9e-279ab97415f4.png">
<img width="1309" alt="Screen Shot 2022-10-22 at 4 21 59 PM" src="https://user-images.githubusercontent.com/50755701/197342592-618801f1-32ea-417b-b3ed-72e2cbbaf930.png">

## Create an article with the following data
<img width="790" alt="Screen Shot 2022-10-22 at 4 26 19 PM" src="https://user-images.githubusercontent.com/50755701/197342672-405b6d41-da5c-429a-8c20-108d368a2856.png">
<img width="1203" alt="Screen Shot 2022-10-22 at 4 26 31 PM" src="https://user-images.githubusercontent.com/50755701/197342674-877b9766-0dd8-4b9c-952f-ada6eadfc0f0.png">

## Storage account after uploading the image from the app
<img width="1322" alt="Screen Shot 2022-10-22 at 4 58 12 PM" src="https://user-images.githubusercontent.com/50755701/197343078-8bae1c85-70f9-48e6-99b7-defe10f35e2f.png">

## Redirect URI for the registered app
<img width="1329" alt="Screen Shot 2022-10-22 at 4 55 13 PM" src="https://user-images.githubusercontent.com/50755701/197342922-020798b1-cddb-45eb-bac4-7fd56dfba302.png">

## Log stream of the application
<img width="1427" alt="Screen Shot 2022-10-22 at 4 33 23 PM" src="https://user-images.githubusercontent.com/50755701/197342941-7df77e47-3cf4-4e48-91be-c1d881fb947a.png">

## Dependencies

1. A free Azure account
2. A GitHub account
3. Python 3.7 or later
4. Visual Studio 2019 Community Edition (Free)
5. The latest Azure CLI (helpful; not required - all actions can be done in the portal)

All Python dependencies are stored in the requirements.txt file. To install them, using Visual Studio 2019 Community Edition:
1. In the Solution Explorer, expand "Python Environments"
2. Right click on "Python 3.7 (64-bit) (global default)" and select "Install from requirements.txt"

## Troubleshooting

- Mac users may need to install `unixodbc` as well as related drivers as shown below:
    ```bash
    brew install unixodbc
    ```
- Check [here](https://docs.microsoft.com/en-us/sql/connect/odbc/linux-mac/install-microsoft-odbc-driver-sql-server-macos?view=sql-server-ver15) to add SQL Server drivers for Mac.
