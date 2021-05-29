# Farsi-word-cloud-generator
This notebook can generate Farsi (Persian) word clouds from twitter data.  
  
Data gathering phase is not included in this code, I used snscrape for this purpose. Check this link out for more details:  
https://betterprogramming.pub/how-to-scrape-tweets-with-snscrape-90124ed006af  
  
The command I used in below example is this:
```
snscrape --jsonl --since 2021-05-01 twitter-hashtag "انتخابات until:2021-05-27" > election.json
```
  
And the result looks like this:  
  
![انتخابات](/election.png?raw=true)  
  
**Dont forget to set the hyperparameters in the first cell!**
