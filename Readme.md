Retail Rewards Program Application

Rewards-Service :
GetRewards (customer ID)  : http://localhost:8080/rewards/1

All Transactions : http://localhost:8080/transactions/

GetAllRewards : http://localhost:8080/rewards/


DB Section :

SQL Commands:
CREATE DATABASE `retail_rewards` /*!40100 DEFAULT CHARACTER SET utf8mb4 COLLATE utf8mb4_0900_ai_ci */;

CREATE TABLE `transactions` (
`id` int(11) NOT NULL,
`customer_name` varchar(45) DEFAULT NULL,
`amount` decimal(10,0) DEFAULT NULL,
`date` datetime DEFAULT CURRENT_TIMESTAMP,
`cust_id` int(11) NOT NULL,
PRIMARY KEY (`id`)
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_0900_ai_ci;


InsertCommansds in SQL :

insert into  retail_rewards.transactions (id, customer_name, amount,cust_id) values(14,"Sachin",280.0,2)


