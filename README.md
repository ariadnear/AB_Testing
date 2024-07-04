# Evaluating Facebook Ad Bidding Strategies: A/B Testing Analysis"

### Objective
To evaluate and compare the effectiveness of Facebook's new "average bidding" system (test group) against the existing "maximum bidding" system (control group) over a 40-day period. The goal is to determine which bidding strategy yields higher impressions, clicks, purchases, and earnings, thereby identifying the most advantageous approach for maximizing our brand's advertising performance on Facebook.

### Data Details
Facebook recently introduced a new bidding system called "average bidding" (test group) alongside the existing "maximum bidding" (control group) system. These bidding systems determine which ads get displayed to users based on how much advertisers are willing to pay.

With "maximum bidding," advertisers specify the maximum amount they are willing to pay for each impression. For example, an advertiser might say, "I'm willing to pay a maximum of $10 for each impression."

With "average bidding," advertisers specify an average amount they are willing to pay for impressions. For instance, they might say, "On average, I'm willing to pay $6 for each impression."

### Features
- Impression: Number of impressions per ad.
- Click: Numbers of clicks per ad.
- Purchase: The number of products purchased after the click.
- Earnings: Earning after purchase.

### Test Statistics
•	Hypothesis: 
- H0: there is no statistically significant difference between the two bidding options?
- Ha: there is a statistically significant difference between the two bidding options?

<img width="369" alt="Screenshot 2024-07-03 at 5 49 48 PM" src="https://github.com/ariadnear/AB_Testing/assets/146493977/53660856-9777-4abb-977d-bda459394420">

Summary Interpretation:
For purchases, there is no statistically significant difference observed.
For clicks, impressions, and earnings, there are statistically significant differences observed between the two bidding options.

### Results

* Purchase vs Impressions
![1](https://github.com/ariadnear/AB_Testing/assets/146493977/516e52da-e422-4751-b5c5-525861301693)

* Earnings vs Impressions
 ![2](https://github.com/ariadnear/AB_Testing/assets/146493977/d050a65e-6531-4cf9-a717-57b47390c18f)

* Purchase vs Earnings
 ![3](https://github.com/ariadnear/AB_Testing/assets/146493977/78b196be-7935-443b-8418-79b8cd67ac8b)

* Purchase vs Number of clicks
![4](https://github.com/ariadnear/AB_Testing/assets/146493977/ab73703c-2258-4437-990c-ea9860795550)

* Earnings vs Clicks
![5](https://github.com/ariadnear/AB_Testing/assets/146493977/6cf8f8f8-b2ae-4223-96a4-b62aa5c938e4)

* Total Impressions by Campaign
![6](https://github.com/ariadnear/AB_Testing/assets/146493977/e8b3da67-81b2-4db2-8a88-4aabd30f5ca4)

* Total Clicks
 ![7](https://github.com/ariadnear/AB_Testing/assets/146493977/18ebbfad-1d97-464e-a446-1460599be084)

* Total Purchases
 ![8](https://github.com/ariadnear/AB_Testing/assets/146493977/0b8be201-a6fa-42bc-981b-a6af5a4cbbba)

* Total Earnings
![9](https://github.com/ariadnear/AB_Testing/assets/146493977/524ad783-40d0-4bf2-9d5e-1f8ad362c0b5)

Test statistics were performed on variables including Clicks, Purchases, Impressions, and Earnings. The analysis indicated no significant difference between the control and test campaigns in any of these variables. The maximum bidding strategy (control campaign) generated significantly more clicks per ad. However, the number of products purchased after clicks was slightly higher for the average bidding strategy (test campaign). Additionally, the average bidding strategy resulted in significantly higher earnings and impressions. Based on these results, the average bidding strategy demonstrated slightly higher overall success compared to the maximum bidding strategy, although the differences were not statistically significant.

### Recommendations

a. Based on the A/B testing results comparing two Facebook advertising systems, we should consider adopting the average bidding system, as it led to more impressions, purchases, and earnings. Although the maximum bidding strategy produced more clicks, it might not be the most effective for maximizing purchases.

b. Further modifications and A/B testing can be conducted on both maximum and average bidding campaigns, or new ad bidding strategies can be proposed.

c. Facebook could offer multiple ad bidding options, allowing customers to choose the option that best fits their needs and budget.

### References

Data source: https://www.kaggle.com/datasets/furth3r/facebook-ab-test-of-bidding-feature








