# CustomerReward
Customer Reward Testing 


# To run
- git clone 
- mvn clean compile
- mvn spring-boot:run

# Health Check for application
http://localhost:8080/actuator
http://localhost:8080/actuator/health

After server getting up : Response check by health API : {"status":"UP"}



# Urls:
1. To get rewards for All customers  ->http://localhost:8080/customer/rewards
2. To get Rewards for Customer by their Id -> http://localhost:8080/customer/rewards/{customerId}
3. TO insert Customer and transaction amount in DB -> use post link like below :
      http://localhost:8080/customer/rewards/insertTransaction
 Requestbody :   {

    "customerName" : "PQRR",
    "transactionAmount" : 1,
    "transactionDate" : "2023-07-12"
}


# Database 

To log into the H2 database to check the data in tables use following link:

http://localhost:8080/h2/login.jsp
jdbc url : jdbc:h2:mem:test
username : admin
password: admin



