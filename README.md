# Web_Api
implemented Spring boot architecture
Created a Data Set 

index of files: 

RewardsCalculator.java
RewardsCalculatorController.java -- Controller Class
DataException.java -- Exception Class
Transactions.java  -- Model Class
RewardsCalculatorService.java  -- Service Class
Application.properties
RewardsApplicationTests.java
RewardsServiceTestConfiguration.java



Formula for calculating the reward points for the customers per transaction

-- expenses -- per transaction

-- rewardPts -- rewardpoints per transaction

if(expenses > 50 && expenses < 100)
{
    rewardPts = (expenses -50);
} else if(expenses >100)
{
    rewardPts = 50 + (expenses - 100)*2;
}

