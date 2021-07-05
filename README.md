# postman
Here added some simple tests for http://users.bugred.ru system with Postman.
You can import this collection - "UsersBugred.postman_collection.json" and environment "UsersBugred Environment.postman_environment.json".
Find the documentation here: https://testbase.atlassian.net/wiki/spaces/USERS/pages/592511089/SOAP+REST

"UsersBugred.postman_collection.json" collection includes 9 simple tests:
1. Requests: DoRegister Positive Tests With .CSV/JSON and DoRegister Negative Tests With .CSV/JSON can be run with .csv and .json test data.
You can find attached files in this repository. 
2. All other request can be run without additional test data.

Files:
doreg.csv, doreg.json - need to run "DoRegister Positive Tests With .CSV/JSON" request
doReg_neg.csv - need to run "DoRegister Negative Tests With .CSV/JSON" request
image.jpg - need to run "AddAvatar" request


NOTICE: to run the collection you need to use both: collection and enviroment. 
