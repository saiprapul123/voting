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


SCREEN SHOOTS:-


![213916282-d09c4734-88fd-4f1c-9727-ac2a2b343c8f](https://user-images.githubusercontent.com/124068895/215817792-a983fe9b-79d6-4c43-bf32-b1a22416c3e8.png)
![213916273-329402c0-9f22-422e-b1a7-a3f3e78d7d91](https://user-images.githubusercontent.com/124068895/215817799-ac625508-12ac-4cd6-bda9-44c75e3df0f4.png)
![213916274-1358fdb7-2f31-4f88-b923-902ebbaeee1d](https://user-images.githubusercontent.com/124068895/215817802-d504ee0a-3264-4ee2-89a7-9b996a706ec1.png)
![213916221-ec2281dd-00b6-4491-b0ad-614fd2463028](https://user-images.githubusercontent.com/124068895/215817806-c49ec8c3-7b5e-4ac3-8dae-f3d2f567d4a6.png)
