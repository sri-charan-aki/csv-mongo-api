# csv-mongo-api
Contains two api's, one for uploading csv to mongoDB and another for making CRUD operations on those collections in mongoDB.

hosted links:
for csv upload: https://frozen-brook-94540.herokuapp.com/
(you need to provide the name of the file(which is stored as the name of the collection) and the csv file. No authorization required. POST to route /csvUpload)
for crud collection: https://floating-sands-68898.herokuapp.com/
(You need to register or login first
/register: to register, provide email, password and confirmPassword
/login: to login, provide email and password and collect access token which has to be sent to perform other functionalities.
Now you can perform crud operations on the collection you like by providing its name in the route (ex. /youtube))

