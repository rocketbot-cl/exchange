



# Exchange

Connect to Microsoft Exchange servers to send, read, and manage emails and folders via web services.

*Read this in other languages: [English](Manual_exchange.md), [Português](Manual_exchange.pr.md), [Español](Manual_exchange.es.md)*

![banner](imgs/Banner_exchange.png)
## How to install this module

To install the module in Rocketbot Studio, it can be done in two ways:
1. Manual: __Download__ the .zip file and unzip it in the modules folder. The folder name must be the same as the module and inside it must have the following files and folders: \__init__.py, package.json, docs, example and libs. If you have the application open, refresh your browser to be able to use the new module.
2. Automatic: When entering Rocketbot Studio on the right margin you will find the **Addons** section, select **Install Mods**, search for the desired module and press install.


## Description of the commands

### Email Configuration

Enter the credentials for configuration
|Parameters|Description|example|
| --- | --- | --- |
|User||User|
|Password||Password|
|Server||Server|
|Mail Address||Mail Address|
|Variable where to store the result|In this field we should put the name of the variable where we will store the result of the connection.|Variable|

![exchange](example\exchange.png)
### Send Email

Send email, before you must configurate the server
|Parameters|Description|example|
| --- | --- | --- |
|To||to@mail.com, to2@mail.com|
|Cc||cc@mail.com, cc2@mail.com|
|Subject||Nuevo mail|
|Body||Esto es una prueba|
|HTML|||
|Attached File||C:\User\Desktop\test.txt|
|Folder (Multiple files)||C:\User\Desktop\Files|

### get all email

Get ID from unread mail
|Parameters|Description|example|
| --- | --- | --- |
|Type of filter||Var without {}|
|Filter||test|
|Assign to Var||Variable|

### get new email

Get ID from unread mail
|Parameters|Description|example|
| --- | --- | --- |
|Type of filter||Var without {}|
|Filter||test|
|Assign to Variable||Variable|

### Read email for id

Read the content of mail for ID
|Parameters|Description|example|
| --- | --- | --- |
|Email ID||ID|
|Assign to Variable||Variable|
|Path for attached files|||

### Move email to folder

Move email with ID to especific folder
|Parameters|Description|example|
| --- | --- | --- |
|Email ID||ID|
|Destination folder||Folder name|

### Reply email for ID

Reply email for ID
|Parameters|Description|example|
| --- | --- | --- |
|Email ID||355|
|Reply all||355|
|Body||Esto es una prueba|
|Attached File||C:\User\Desktop\test.txt|

### Forward email for ID

Forward email for ID
|Parameters|Description|example|
| --- | --- | --- |
|Email ID||355|
|Email||test@email.com|
