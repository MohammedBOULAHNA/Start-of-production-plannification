


# Start-of-production-plannification

Nowadays, the use of business process management software and applications as well as the development of custom software are recognized in most fields including the industrial field.
So, within the framework of an academic project in the field of piloting and integration of industrial systems, we are going to work on the development of a desktop application for the management and manipulation of manufacturing orders.
It is a graphical interface that will allow users to manage the data of production orders (SOP), allowing to add, delete, search, display, and modify production orders.
Data manipulation and access will be done in three different ways:
- Access and manipulate data from an Excel file.
- Access and manipulate data from a local database.
- Access and manipulate data from a remote database.

### 1.Requirements specification :
In this section, we will present the functional and non-functional requirements of the system to be developed. These are the needs that the end user specifically requests as basic functionalities that the system must offer.
In fact, the difference between the two types of requirements is that the functional requirements express the concrete functionalities of the product, while the non-functional requirements are indicators of the quality of the execution of the functional requirements.

| ID | Description |
| --- | --- |
| 01 | Consult the different production orders in the data source. |
| 02 |Add new OF|
| 03 | Modify the data of an existing OF. |
| 04 | Delete an OF |
| 05 | Search for an OF by its reference. |
| 06 | The possibility to reset the writing fields. |
| 07 | The possibility to inform the user of the non-existence of an OF.|

- ***Non-functional requirements :***
  The following table represents the various technical requirements to be taken into account for the realization and proper functioning of the project:
  
| ID | Description |
| --- | --- |
| 01 | Ergonomics: The interface of our application must be ergonomic and easy to use |
| 02 | Interface accessible by all users, regardless of their characteristics and their means of access to information.|
| 03 | The application must be easily accessible via any computer. |
| 04 | The availability of the application at any time to be used. |
| 05 | The results provided must be reliable|
| 06 | The respect of the rules related to the information system. |
| 07 |Quick access to information.|
| 08 |Guarantee the confidentiality and integrity of data.|

### 2. Tools Used:
In this part, we are going to present the different tools we used to develop the manufacturing order management application.

- ***Programming Language:*** There is not only one choice of programming language to use for the development of this project, in fact, but it can also be developed using different languages (Python, JAVA, Visual Basic, VBA ...).
 In the case of this project, we chose to use the Python language because of its simplicity for the development of desktop applications, as well as the availability of resources and explanations.
More specifically, we used the Python framework for the development of graphical user interfaces: Tkinter.

- ***Data*** : To manage the data of the OF inserted in the application in this project, we have chosen to work with :
- Excel: In order to store and manipulate the data in tables in a simple way. 

![image](https://user-images.githubusercontent.com/124175118/221961339-a8beb129-4bd3-4935-89cd-e3b898943b0a.png)

 
- PhpMyAdmin : 

![image](https://user-images.githubusercontent.com/124175118/221961436-1c1dd47b-6d85-4eb7-8860-a34774550502.png)

-	XAMPP : It is a set of software allowing to set up a local Web server, an FTP server and an e-mail server. It is a free software distribution offering a good flexibility of use, known for its simple and fast installation.
 
![image](https://user-images.githubusercontent.com/124175118/221961553-03ae8259-eb2d-4295-883a-89c93e89b95e.png)

### 3. Graphical User Interface: The final result 
![image](https://user-images.githubusercontent.com/124175118/221961944-42bbc0b6-2dfd-4fb8-85d4-9c3a7a6db573.png)

***- ADD a new production Order***
![image](https://user-images.githubusercontent.com/124175118/221964260-fe44b0bc-67c3-46d8-8fb7-3b434fe52115.png)

Data is saved in the Excel File:
![image](https://user-images.githubusercontent.com/124175118/221964409-596526d1-dce8-4cae-9223-fa5c5ecfb762.png)

***-Edit an excisting data***

![image](https://user-images.githubusercontent.com/124175118/221964766-85dd6718-5132-45c9-9fef-850d48887fc1.png)

For example, we change the number of pieces to 200.
![image](https://user-images.githubusercontent.com/124175118/221964862-4d179c40-4407-4d80-a172-0e453f3faffa.png)

***-Delete an excisting data***

![image](https://user-images.githubusercontent.com/124175118/221965060-e076a0fb-2912-47a1-b5b8-7b76b2d5f435.png)



