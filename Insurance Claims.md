# Insurance Claims Case Study
Here I'll explain a case study I created with Tableau Desktop using the Real World, Fake Data Project created by Mark Bradbourne. You can find the file [here](https://sonsofhierarchies.com/real-world-fake-data/). 

## Introduction

Using said file, I prepared a story in Tableau mimicking a job's presentation about a simulated database of a client.

The objective is to showcase the possible categorical variables related to the number of claims reported, claim frequency and intensity in Tableau. As a closure, I'll post some findings.

## Project's Description

We got a document from the client's insurance claim database. Here we can see the 10 first records (out of 37k)

![Sample tbl](https://github.com/user-attachments/assets/7820d94d-98e4-49b8-9212-693e147e43f9)

From that table we could extract the amount of claims per every possible category. For example, we can see that drivers with no kids onboard have a much higher number of claims than those who have.

![Dashboard - Abs Data](https://github.com/user-attachments/assets/1485a239-34c7-4439-8e35-5f86a126aa90)

Another example: I know it is not legal to segment by sex in every country, But we could offer a discount to married females who regularly take their kids to school.

![Dashboard - Abs Data Example](https://github.com/user-attachments/assets/3a96b753-80d3-497d-9fdb-882b25898d60)

The issue here is we are using absolute values, so it may make sense that the oldest cars are the ones with the least claims reported as there may be fewer on the portfolio as a whole.

Now, instead, we see each category's bin claim frequency. As you can see in the "Car's Age" chart, the claim frequency of the older cars is higher than the newer ones.

![Dashboard - Rel Data](https://github.com/user-attachments/assets/dddc3f74-8703-4ff1-82dc-e5fd79258c3e)

If we try to replicate the filters of the third slide, the difference in frequency between male and female drivers is not so significant.

![Dashboard - Rel Data Example](https://github.com/user-attachments/assets/f2c0de48-64c5-426c-9c48-9c1932db9105)

Lastly on the claims analysis, we are able to see how important is each category relative to its proportion to the portfolio.

![Dashboard - Rel to Portfolio Prop Data](https://github.com/user-attachments/assets/16bce255-642a-4ed6-9be7-5cb4b75efd4b)


If you want to interact with this Tableau Story, you can find it [here](https://public.tableau.com/views/InsurancePoliciesProjectRealWorldFakeData/InsurancePolicies-ClaimsReported?:language=es-ES&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link).


