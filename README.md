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

SCREEN SHOOTS:-![213916221-ec2281dd-00b6-4491-b0ad-614fd2463028](https://user-images.githubusercontent.com/124068895/215817479-594b5c62-3264-475c-8da7-8c79e3c28277.png)
![213916274-1358fdb7-2f31-4f88-b923-902ebbaeee1d](https://user-images.githubusercontent.com/124068895/215817543-f6cdf18e-2e43-4f59-ae9b-9c0cf9039149.png)
![213916282-d09c4734-88fd-4f1c-9727-ac2a2b343c8f](https://user-images.githubusercontent.com/124068895/215817579-d802fc23-ed50-468e-bf30-0f5f9460b33d.png)
![213916273-329402c0-9f22-422e-b1a7-a3f3e78d7d91](https://user-images.githubusercontent.com/124068895/215817588-8735eb33-7e63-4658-8f66-b4be3c310d29.png)
![213916274-1358fdb7-2f31-4f88-b923-902ebbaeee1d](https://user-images.githubusercontent.com/124068895/215817592-88805344-97be-4946-ac69-c593270408a0.png)
![213916221-ec2281dd-00b6-4491-b0ad-614fd2463028](https://user-images.githubusercontent.com/124068895/215817595-9d4999f7-e12f-46ca-ad6a-be79df799095.png)
