## Document - where you would find the data sources -

https://docs.google.com/spreadsheets/d/1VIfunqcshcNug7cJEzzg4cGyhN7FC9TUEcpyfpFTRMc/edit#gid=1218415869

## Problem Set I - Regex

- Write a query to extract the keywords from the **url** column. This query should be run on a Google Sheet. **This should be done only via SQL (Query Function) and Regex and not via any formulas.** Also, please note that keywords - with multiple words - should be separated by space.

```python
https://docs.google.com/spreadsheets/d/1VIfunqcshcNug7cJEzzg4cGyhN7FC9TUEcpyfpFTRMc/edit?usp=sharing
```

Resource - How to run Queries on Google Sheets - [Link](https://support.google.com/docs/answer/3093343?hl=en)

## **Problem Set 2 -  SQL**

Suppose there’s a log of security related incidences for about 60 days along with instance_id. Now, there are cases when the incident is reported but the incident_id is not. This should be done only via SQL (Query Function) in Google sheets and not any other tool. 

- Your goal is to find out - how many incidents have **incident_id** on a given day. How many percentage of incidents have a non-null id?
- The time is in UTC, so convert that into IST.
- What time of the day does the incident_id percentage is lower?

**Bonus Points** - Use Google Looker Studio - to help visualize the same. Also, Incorporate as many operations as possible in a single formula.  

## **Problem Set 3 - Working with BigQuery**

Suppose you get a raw data of your website visitors and you are asked: 

1. Identify how many users came via a certain referrer url. 
2. Also, convert the ***visitStartTime*** property to IST.

💡 **Hint 1:** Group the number of rows grouped by hit→ referral property. (If the hit →referral is not present, please consider that as a null and group this too). 
💡 **PS:** The link to the data set for this problem is provided in the problem sheet

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/1d9e0f1e-032d-4413-abe3-f12e214b3859/Untitled.png)

## **Problem 4 - Modified VLOOKUP**

1. User inputs two comma separated lists - list A and list B.
2. We take an element from the list A - and match it with the entire range.
3. Whichever cell from list B has the highest match, will be return against the values of List A. 
