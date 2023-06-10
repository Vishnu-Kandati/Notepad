### Python Django web application for a notepad using SQL


Notepad is a generic text editor app where the user can create documents, add content and save documents for future use. 

Our app provides features like Google authentication where the use can login into the app using his/her gmail.

### Technologies Used

Python(Django Framework)

Sqlite(Database)

heroku

### Instructions

Install necessary packages for the application from requirements.txt using command pip install -r requirements.txt

### HTTP Methods

Get -  The GET HTTP method is used to retrieve the documents from the database by passing the docid as params. 
       If no params passed all the docs can be retreived created by that user. 
       
Post - The POST HTTP method is used to create a document by passing the content entered by the user. A new document will be created in the database with a 
       newid(identification for document).

Put -  The PUT HTTP method is used to edit the content of the document of the user which was edited before.

Delete - The DELETE HTTP method is used to delete the document. The params will be the docid which specifies the document to be deleted.
