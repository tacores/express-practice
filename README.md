# express-practice

## memo
npm init -y
npm install express
npm install jsonwebtoken
npm install express-session

変更のたびに再起動する必要が無いように nodemon
npm install -g nodemon


node index.js
 or
nodemon index.js

curl --request POST 'localhost:5000/user?firstName=Jon&lastName=Lovato&email=jonlovato@theworld.com&DOB=10/10/1995'
curl --request PUT 'localhost:5000/user/johnsmith@gamil.com?DOB=1/1/1971'
curl --request DELETE 'localhost:5000/user/johnsmith@gamil.com'
