HMS
# Project Objective
This project is developed with the aim to store patient healthcare records over blockchain. The DApp build provides a patient centric system in which a patient has
control over his data i.e. patients themselves decide who can view their profiles/data. The system classifies the users into three categories: ADMIN, DOCTOR, PATIENT.
Patients can grant or revoke data access permission to/from any doctor. Patients can also add files to their profile/data like reports, X Rays etc. which will be stored over
IPFS. These files can help the doctors (who have been granted access) to review and treat patients accordingly. Also patients can view the past consultation records.
Doctors are provided with a facility to view the patient records to which they have access granted. Doctors can view their patients' files and previous consultations too
and can accordingly provide consultation or treatment.
# To run this project kindly install following prerequisites
Truffle v5.11.0 (core: 5.11.0)
Ganache v7.9.0
Solidity v0.5.16 (solc-js)
Node v16.14.1
Web3.js v1.10.0
Install Metamask as a Browser extension.
Install Ganache for deployment of Contracts.
# Steps to run project
Add truffle-config.js file in Ganache.
Create new network in metamask with port number same as in truffle-config.js
Configure Ganache with the same port number.
Goto Project Directory and run "truffle migrate" on command prompt.
Goto 'Client' directory using prompt and use "npm install" or "yarn install
run "npm start" to start the react server.
Project will be open in your browser.
Import Ganache account(s) in metamask and use it for user login/register purposes.
Execution will start from App.js file in the client directory.
