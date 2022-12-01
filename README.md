# Amazon_Vine_Analysis
## Overview
Our goal today was to go over data provided to us and compare reviews written from paid sponsorships vs. free reviews from general customers. I chose to review a dataset of mobile electronics. After this data was analyzed and broken down into various data frames, I then pushed it to a SQL database using AWS.

<img width="265" alt="customers_table" src="https://user-images.githubusercontent.com/111014191/204978192-c2a06b23-245f-406b-827e-fda0fcb43f9c.png">
<img width="233" alt="products_table" src="https://user-images.githubusercontent.com/111014191/204978226-acc95245-f739-4d21-97a4-a870ca78709e.png">
<img width="525" alt="review_id_table" src="https://user-images.githubusercontent.com/111014191/204978248-acca4bba-45f1-4687-9a94-183c87f54931.png">
<img width="650" alt="vine_table" src="https://user-images.githubusercontent.com/111014191/204978260-bc4ec2f4-7822-422e-a4f2-c0702cd771c8.png">

## Results
As seen in the chart below, there were:
- 4 paid reviews vs. 1060 free reviews
- 1 paid five star review vs. 527 free five star reviews
- 25% of the being reviews were five star reviews vs. 49.5% of the free reviews being five star reviews
<img width="617" alt="vine" src="https://user-images.githubusercontent.com/111014191/204978141-aede6294-3018-4d47-8b8c-002446be977b.png">

## Summary
In my dataset, there is not a positivity bias for paid reviews vs. the free ones. Obviously, the sample size was much smaller but it seems that the free reviews were much more positive than the paid ones. There were nearly two free five star reviews for every one paid five star review. In my opinion, this comes from the product that is being discussed. While mobile electronics is a broad subject group, I am assuming that this is describing important purchases such as a cell phone. The free reviews are coming from people who went and purchased that device vs. the competition so they most likely knew that they were going to like the product before even purchasing it. Due to this, Amazon would be better off putting their advertisement dollars in other categories since the free reviews are producing better results than the paid ones.
