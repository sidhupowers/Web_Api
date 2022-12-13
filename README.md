# Web_Api
implemented Spring boot architecture
Created a Data Set 


Sudo code 


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
