#online voting


Online Voting Application built by using Node.js,Express JS(EJS). 

It consists of two user roles...

1)admin 2)Voter 

admin : admin can create multiple elections, each election consist of multiple questions. admin adds the voters by giving voter ID and password. After creating 

questions and voters, admin can launch the election and it provides publicURL where voters can vote through using publicURL. Finally admin ends the election and checks the results. 

Voter: Voter should visit the publicURL given by the admin. Login by using default credentials by admin. After login voter can be able to vote for the question and submit the result.


#procedure


Voter visits the publicURL given by the admin.

Login by using default credentials provided by admin.

After login voter can be able to vote for the questions and submits the result.

To Run Locally

Install postgresql and update your username and password in config.json

To start the postgresql server

sudo service postgresql start

Install dependencies

npm install

Create database

npx sequlize-cli db:create

Migrate database

npx sequlize-cli db:migrate

Run locally at port 3000

npm start

Run test cases

npm test
