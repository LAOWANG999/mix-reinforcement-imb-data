# mix-reinforcement-imb-data
Mixture reinforcement training technique for imbalanced data

I am recently involved in a fraud detection project for a big express delivery company from China. Each year, they deliver about 2.6 billion packages and receives about 1.2million claims that their service did not meet the standard they promise. The reasons for claim includes "broken", "partly broken", "delayed delivery", "lost", "partly lost". And the total claim has reached 5,000 million RMB in the previous year. 

The company provided 1 year of full "waybill" and claim data. There are two major difficulties: firstly, the data is extremely imbalanced. Secondly, because the express delivery service is anonymous, the information provided is very limited. We found it almost impossible to evaluate our algorithm with the traditional precision-recall measure. Then we turned to focus on precision first. 

The technique in this package helped us improve our precision from 1% to about 10%, though with a significant decrease in recall. We then applied the same method in other imbalanced datasets. 

I created this repo to put our idea into a code that can be applied to any dataset. Hope that this may help someone someday.

Guangju Wang
