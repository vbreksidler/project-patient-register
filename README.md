<div>
  This is a challenge project, and the goal is a web application (CRUD) to manage patient registers (Patient's name, birth date, email and address) using a cloud database.

 </div>

 <br>

 ------------------------------
 
● Tech:

 ------------------------------
	 ◕ frontend: 
		  ◑ Javascript;
		  ◑ React;  
	 ◕ backend:
		  ◑ express;
		  ◑ NodeJs;
          	  ◑ AWS Lambda serveless computing;
          	  ◑ AWS DynamoDB;
         	  ◑ AWS API Gateway;
		  ◑ AWS Amplify;
-------------------------------

● Require: 

-------------------------------
	◕ You need to develop both the front-end and the back-end. ✔️
	◕ In the front-end you MUST use React. ✔️
	◕ In the back-end you MUST use Node.js and AWS free-tier. ✔️
	◕ The patient data should not be static or local. ✔️
	◕ Field validation (date, required fields, etc). ✔️
	◕ AWS RDS MySQL, PostgreSQL or DynamoDB as database. ✔️
	◕ AWS Lambda for serveless computing. ✔️
	◕ AWS API Gateway for managing your REST API. ✔️
	Extra:
	 ◕ Cache the data in-browser.
	 ◕ Pagination.
	 ◕ Use Material UI - https://material-ui.com.
	 ◕ A cool design. ✔️
-------------------------------

● To run the project: 

-------------------------------
	◕ https://github.com/vbreksidler/development-challenge-two/tree/victor-reksidler-branch
	◕ git clone git@github.com:vbreksidler/development-challenge-two.git
		 or ◑ download the project:
			◦ https://github.com/vbreksidler/development-challenge-two/archive/refs/heads/victor-reksidler-branch.zip
			◦ extract the folder
	◕ run terminal
	◕ cd development-challenge-two-victor-reksidler-branch/patient-register
	◕ apt install npm
	◕ npm install
	◕ npm i aws
	◕ aws configure 
		(if aws configure dont run, install -> apt install awscli)
		◑ Use the follow access to configure your AWS:
			◦ AWS Acesss Key ID: AKIAVYG2NKJE2P2ADPPU
			◦ AWS Secret Acees Key: TYbcqZmGGVonE6xE4OiBX1so3mdJaCm0bJxCCJlN
			◦ default region name: sa-east-1
			◦ default output format: json	
	◕ npm start

-------------------------------

● Future improvements:

-------------------------------
	◕ Front:
		◑ add a filter
		◑ change to state context.
		◑ cancel button is only functional.
		◑ when click edit button replace the add form
	◕ Back:
		◑ improve the validation through AWS API Gateway.
		◑ implement especific methods in AWS API Gateway.
		◑ need getting to know more of AWS authentication(IAM and Cognito).
-------------------------------

  ![GIF do projeto mostrando a funcionalidades](https://raw.githubusercontent.com/vbreksidler/project-patient-register/master/patient-register/public/a5cfa8a2ce9c8ed6694f2ca6d853493d2ce71e06.gif)
  ![GIF do projeto mostrando a funcionalidades2](https://raw.githubusercontent.com/vbreksidler/project-patient-register/master/patient-register/public/c014a1377e3cf34617288a55b5d2ccdf01686863.gif)
  ![GIF do projeto mostrando a funcionalidades3](https://raw.githubusercontent.com/vbreksidler/project-patient-register/master/patient-register/public/6090.gif)
    ![GIF do projeto mostrando a funcionalidades4](https://raw.githubusercontent.com/vbreksidler/project-patient-register/master/patient-register/public/60120.gif)
![GIF do projeto mostrando o serviço AWS](https://raw.githubusercontent.com/vbreksidler/project-patient-register/master/patient-register/public/Painel%20_%20Amazon%20DynamoDB%20Management%20Console%20-%2022%20December%202022.gif)

-------------------------------

