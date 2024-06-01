# Project Titile: Automate demo fintech API by using Postman and Newman
## Project Summary: In this project, I have created a postman collection for a demo fintech web application called "dmoney" to cover the following scenarios in the given flow:
- Admin creates an agent and random 2 customers. 
- Deposit some money from SYSTEM account to the agent. System account: SYSTEM (range 10 tk to 10000 tk)
- Agent deposit to any of 1 customer
- Check agent balance-
- Then withdraw any amount by the customer from the agent (range 10 tk to 10000 tk)
- Then the customer checks balance-
- Then send money to the other customer
- Then from the another customer payment to any merchant (create a merchant account)
- Then the second customer will check both balance and statement
- Then the merchant will check his own balance




## Pre-requisites:
- Node JS (LTS)
- Newman
- Newman-reporter-htmlextra



## How to run?
### Execute the following commands in the given order
- ```git clone <repo url>```
- ```npm i```
- add the .env file (have to directly request the author for this file)
- ```node report.js``` or ```npm test```




## Newman report (Screenshot) 
![image](https://github.com/sofiaa89/Integration-Testing-with-Postman-dmoney-users-collection-/assets/150695266/f114243d-fc4f-4021-b9b1-e1c32e24a881)
![image](https://github.com/sofiaa89/Integration-Testing-with-Postman-dmoney-users-collection-/assets/150695266/b1262d82-7d8f-4192-8be9-d5e4cfadf4dd)
![image](https://github.com/sofiaa89/Integration-Testing-with-Postman-dmoney-users-collection-/assets/150695266/50200ea9-5ced-4d81-aadd-a2eb07b28d27)


## Postman Documentation link: 
https://documenter.getpostman.com/view/35118611/2sA3QwbUnj








