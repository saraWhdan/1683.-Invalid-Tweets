# 1683.-Invalid-Tweets
Problem Link: https://leetcode.com/problems/invalid-tweets/description/?envType=study-plan-v2&envId=top-sql-50
## Solution

```sql
select tweet_id 
from tweets
where LEN(content)> 15
