![213916221-ec2281dd-00b6-4491-b0ad-614fd2463028](https://user-images.githubusercontent.com/124068895/215821260-027bff4f-f273-404f-97dd-e8a5f6161e80.png)
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

![213916221-ec2281dd-00b6-4491-b0ad-614fd2463028](https://user-images.githubusercontent.com/124068895/215821358-a9dcde5d-91ff-40a6-8ae3-38059df7ec8b.png)

![213916274-1358fdb7-2f31-4f88-b923-902ebbaeee1d](https://user-images.githubusercontent.com/124068895/215821406-d2a1e64d-f9d9-4b98-9589-d654bc31d925.png)

![213916273-329402c0-9f22-422e-b1a7-a3f3e78d7d91](https://user-images.githubusercontent.com/124068895/215821492-e60469d0-3fcd-4658-9133-6bcc18dc42f9.png)

![213916282-d09c4734-88fd-4f1c-9727-ac2a2b343c8f](https://user-images.githubusercontent.com/124068895/215821553-52983ef9-a109-4f55-b1e3-9c18d10d5983.png)

DEMO VIDEO:-

https://www.loom.com/share/23d794661afc4e7eb1393b63d66f40ba

LIVE LINK:-

https://voting-mli2.onrender.com/
