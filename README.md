# Dmoney API Testing Project
DMoney is a demonstration project related to financial transactions, allowing the transfer of virtual funds. 
In this project, I carried out integration and automated API testing for the DMoney API collection.\

# Technology used
- postman
- newman
- nodejs

# Testcase scenarios

1. Admin creates an Agent, 2 random Customers, and a Merchant.
2. Deposit some money from the SYSTEM account to the Agent. (range 10 TK to 10,000 TK)
3. Agent deposits money to one of the Customers.
4. Check the Agent's balance.
5. Then, send money from one Customer to another Customer.
6. Withdraw any amount from a Customer to the Agent (range 10 TK to 10,000 TK).
7. Check the Customer's balance and transaction statement by trnxId.
8. Make a payment from the second Customer to the Merchant.
9. The second Customer checks both balance and transaction statement.
10. The Merchant checks their balance.

# How to run?
- Clone this project.
- Give following Commands:
- ```npm i```
- ```npm test```

# Documantation for the API Collection -
https://documenter.getpostman.com/view/37977154/2sAYHzFNUX

# Test Case
https://docs.google.com/spreadsheets/d/1j_1NnZm-j40svgoj_WDhBKWaop9HKK2WQIn4jO7JBlo/edit?usp=sharing

# Bug Report
 https://docs.google.com/spreadsheets/d/1Aof8tmCGsj90zC3wnR6crmM1Kaaar9fJ4oSQqU2o2kg/edit?usp=sharing

# Report
![image](https://github.com/user-attachments/assets/654847ac-8fcd-412f-a089-295c91dc6943)




  
