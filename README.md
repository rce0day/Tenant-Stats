# **Microsoft Tenant Stats**

### Acquired using a previously uploaded script - https://github.com/rce0day/Tenant-osint ###
This dataset and statistical analysis was initially made to see interesting statistical data but outputted an interesting insight into SSO SaaS companies' market share.

### What is so interesting about this data? ###
This data provides an interesting insight into the SSO (Single Sign On) systems the top 25,000 companies use. 

### Why did you scrape this data? ###
I like statistics.

### Microsoft Usage Statistics: (inner values are correct) ###
![Microsft Usage Statistics](https://i.imgur.com/ZKnz9QL.png)
```
> 7.5% of companies have a configured Microsoft tenant but handle SSO by an external entity.
> 23.3% of companies utilize Microsoft's SSO system without external entities.
> 69.3% of companies do not have a Microsoft tenant configured under their domain.
```

### External Redirect Statistics: (sorted by root domain) ###
![External Redirect Statistics](https://i.imgur.com/fMOd8bi.png)
Out of the 1,791 identified companies that use external redirects:
```
> 33.5% use okta. - (1.2% is okta-emea.com so 34.7%)
> 3.4% use godaddy.
> 2.6% use onelogin.
```

### What can we assume from this data? ###
Out of the identified companies, okta has a significant market share for external SSO entities, feel free to fork this repo or take the dataset, it is formatted in jsonl format for easy iteration.
