Customer Service Portal
Customer Service Portal is an application built using React Functionalities.
 Login – The customer can log in by entering the credentials.
 Purchased Items – Displays the various products bought by the customer. 
 Feedback – The customer can provide feedback on the products they purchased.

Following are the steps for the deployment of case study in local machine:
1. Install node.js from Node.js official site or from Software House

2. Click on the Customer Service Portal to download the case study.

3. Install the required packages:

Note: Installing the npm modules is prevented if your machine is connected to the Infosys network. 
To overcome this, set specified proxy by entering the following code in the node.js command prompt.

4. Open node.js command prompt and navigate to the folder where the case study is downloaded. And execute the below command

--  npm install  --

The above command installs all the required packages

After step 4, install the json-server manually by running the command 

-- npm install json-server -g  --

5. Open the 2nd node.js command prompt and navigate to the same folder.
6. And start the JSON server by running the below command

-- json-server --watch db.json --port 4000 --

The json-server will run in 4000 port

6. Once the installation is done, execute the below command to start the application

-- npm start --

7. The application will run in the 3000 port.
