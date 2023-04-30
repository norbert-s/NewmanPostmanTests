# NewmanPostmanTests

This reporitory is the host for different newman tests


IN GENERAL

Running different postman collections

This repository can be called from other repos to use it in a multipipeline test layout

It is running tests through calling the postman api -using api key for postman ,and calling the collection in postman and particular enviroment is postman by calling the hash of that particular collection

Finally it reports back the results

--------------------------

THE DEMO TESTS

The first demo tests run some tests, creates orders, then queries them, updates them and then deletes them -using different env variables in postman and also running pre-and after test scripts to store and use the results of previous tests
