# CustomerReward
Customer Reward Testing 


# To run
- git clone https://github.com/Nupur321/Customer_Rewards
- mvn clean compile
- mvn spring-boot:run

# Health API
http://localhost:8080/actuator/
http://localhost:8080/actuator/health

Sample Response
```{"status":"UP"}```

# Urls:
1. To get rewards for All customers  -> /rewards
2. To get Rewards for Customer by their Id -> /rewards/{customerId} 

After the program is run, user can enter either of the following link in the URL:


# Database 

To log into the H2 database to check the data in tables use following link:

JDBC URL =jdbc:h2:mem:testdb



