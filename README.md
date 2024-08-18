>>npm install json-server

>>npm install -g concurrently
>>npm install concurrently --save-dev

add a json file with sample customer data 

>>customer.json

add  "start": "concurrently \"json-server --watch customer.json\" \"ng serve\"", in package.json file

to run both project >> npm start

ng add @angular/material

