# KPI & Metrics

*What is measured get managed*

## Growth and activation Metrics

1) Total new users per month.

   - Send query to our DB to know the number of our users in the start of the month and then compare it with the number of users at the end of the month.

2) New user by source (Seo, Social media, blogs, etc ...)

   - Google analytics might be helpful here, where we can check the source of the new user, if he/she coming from social media, Organically , from a back-link in a blog etc ...

3) Active users.

   - Google analytics is a useful tool to check this metric.



## Retention Metrics

1) Retained users.
   -   let's say that 100 users visited out website last month and got activated. Then we see this month that 60 of them are actually here again using the website, we would say that our user retention rate is at 60%.

2) Resurrected users.

   -  Then for the resurrected users, let's say that those 40 were now considering gone like we've sort of lost them because they're not here this month. But next month, we send them an email or a push notification. And let's say all 40 of those people come back into our website, we would say that our resurrected user rate was 100%.

## Engagement


1) Average order value of all customers per (day or week or month)

2) Average number of orders the user make per (day or week or month).

Details on how we calculate those metrics are mentioned in the table below.

 It's basically a survey that goes out 

## User Happiness
1) NPS Scores. (Net promoter score)

   - Send ac Survey to users to track how likely they are to recommend our product to other people.

2) Social Media Feedbacks (from comments, rating, ets ...)

## Revenue Metrics

1) Life Time Value (LTV)

   -  pick a period of time let's say one year which will represent the customer lifetime. then we say over one year on average, how much revenue does each customer generate us? So let's say within that space of one year, we're getting,300 JOD from each user on average, that would be our LTV.

2) Cost Of Acquisition of Customer (CAC)

   - It's basically how much money do we have to spend in marketing or advertising, or even salaries for salespeople to on average acquire a customer.

3) Monthly recurring revenue (MRR) or Annually recurring revenue (ARR)

This is basically how much revenue are we making per month or per year and this is of all of our customers combined. let's say we have every month 20 clients spend an average of 150 JOD, then our monthly recurring revenue is going to be 3000 JOD. 

## More Metrics 

X | Goals| Signals | Metrics
------------ | ------------- | --------------|--------------
Adoption | Maximize # of users who ordered at least one time from our website | Number of people who ordered at least one time from our website (send a query to the DB to know the number) and total number of people who visited our website  and viewed our product(use google analytics and find sessions)| What percentage of people visited the website (Sessions) and placed an order (conversion rate or adoption rate)
Task Success| Minimize # of abandoned carts (people who don't complete the order). And Maximize the # of users that successfully complete an order within 5 minutes| Number of people who didn't complete an order.(By Tracking the people that have added something to their cart and they never went and clicked to finalized purchase button) and  Amount of time spent completing an order.| Average time it takes all users to complete their order. and Ratio of incomplete Orders
Engagement| Maximize # of orders and total value of the orders|Number of Orders per customer in a specific period|Average order value of all customers per (day or week or month) and Average number of orders the user make per (day or week or month).
Retention |  Maximize % of users that return and place an order|  Who has ordered the product and When did they ordered the product ?|Retention rate
Happiness | Maximize our client satisfaction with our brand | Track Scores from NPS survey| What percentage of total users gave us a perfect score.




Note: DB has a timestamp that help us to know when a particular thing happened in the DB. this will help us to get the data needed to know the user retention 

