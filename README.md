This repository contains all contains Rowland Savage's solution to Practical Assigment 5.

All code is contained in the Jupyter Notebook: [Practical_5_RMS]<https://github.com/rsavage2201/Berkeley-AI-Course/blob/main/Practical_5_RMS.ipynb>
All data can be found in the file: [coupons.csv]<https://github.com/rsavage2201/Berkeley-AI-Course/blob/main/coupons.csv>


SUMMARY OF FINDINGS
Overall the bar coupons appear to be very successful - 41% of all bar coupons were accepted in this dataset.
That seems to be a great outcome as doing a quick google search, indicates that at an industry level, apparently, 
a 7% redemption rate on digital vouchers is considered good.

Within this population provided however, we could see;
 - Drivers without kids in the car were more likely to use the coupon (43% vs 21%)
 - Drivers who were less than 30 were more likely to use the coupon (48-50% vs 30-43%)
 - Drivers who go to bars regularly were more likely to use the coupon(69% vs 30%)
 - Drivers with certain careers were more likely to use the coupon than others, e.g.
    Architecture and Engineering, Production occupations and healthcare support (all over 65%)

So, younger drivers with no kids in the car, who visit bars regularly and are in certain professions are much more likely to accept the coupon than the general population.

It follows, that we could then combine these attributues to target specific drivers to and see an increased redemption rate. 
In fact, if we target drivers who are younger, without kids in the car, less than 30 and in the 3 most likely occupations, the success rate rises significantly - in fact in this particular cohort the success rate is 100%.

However, only 13 drivers match all these criteria, which is too small a group.

So it seems when doing this type of analysis a balance needs to be struck between the accuracy of the targeting criteria and overall size of the resulting group affected.
i.e. the goal in this case is likely to maximize the number of coupons redeemed, not maximize the accuracy of the targetting.

ADDITIONAL
Additional insights include
1. Drivers who were going in the same direction were significantly LESS likely to accept the coupon (77% vs 23%).
   This is a surprising, non intuitive result, so I'm concious of the possibility of error, and I would definitely want to recheck this data
2. More coupons were accepted when it was sunny, and when the temp was at 49.5%
   However, I'm very concious of not confusing causation with correlation (i.e. sunny warm weather may have simply been the most common during this trial)
3. The other different types of coupon were impacted to different degrees by the weather, though warm summer weather seemed to have the most positive effect.
4. The data provided had been "Grouped" so it didn't seem appropriate to try to use other graphs like scatterplots to visualize the data (which I feel would have been more effective if more continous values were provided).

