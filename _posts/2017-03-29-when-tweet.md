---
layout: post
title: When does Trump Tweet?
---

What time of day does Trump tweet? The answer is surprising: A huge fraction of Trump's tweets are sent out between 6am and 9am Eastern Time. Take a look at this chart and the following data:


![image](http://i.imgur.com/IiBw6HY.png){: .center-image}


| Hour   | Count (All Time) | Mass (All Time) | Count (L3W) | Mass (L3W) |
|-------:|-----------------:|----------------:|------------:|-----------:|
| 0      | 2                | 0.6%            | 1           | 1.2%       |
| 1      | -                | 0.0%            | -           | 0.0%       |
| 2      | -                | 0.0%            | -           | 0.0%       |
| 3      | -                | 0.0%            | -           | 0.0%       |
| 4      | -                | 0.0%            | -           | 0.0%       |
| 5      | 2                | 0.6%            | 1           | 1.2%       |
| 6      | 37               | 11.9%           | 4           | 4.7%       |
| 7      | 33               | 10.6%           | 5           | 5.9%       |
| 8      | 56               | 18.0%           | 18          | 21.2%      |
| 9      | 16               | 5.1%            | 8           | 9.4%       |
| 10     | 13               | 4.2%            | 4           | 4.7%       |
| 11     | 12               | 3.9%            | 5           | 5.9%       |
| 12     | 9                | 2.9%            | 3           | 3.5%       |
| 13     | 10               | 3.2%            | 6           | 7.1%       |
| 14     | 6                | 1.9%            | 1           | 1.2%       |
| 15     | 8                | 2.6%            | -           | 0.0%       |
| 16     | 20               | 6.4%            | 5           | 5.9%       |
| 17     | 13               | 4.2%            | 4           | 4.7%       |
| 18     | 26               | 8.4%            | 8           | 9.4%       |
| 19     | 12               | 3.9%            | 2           | 2.4%       |
| 20     | 6                | 1.9%            | 1           | 1.2%       |
| 21     | 18               | 5.8%            | 7           | 8.2%       |
| 22     | 12               | 3.9%            | 2           | 2.4%       |
| 23     | -                | 0.0%            | -           | 0.0%       |
| Totals | 311              | 100.0%          | 85          | 100.0%     |

The "All Time" columns show data for all tweets from Jan. 25 to Mar. 29 2017. Look at rows 6, 7, and 8 -- an amazing 40.5% of tweets occurred during those hours! The "L3W" columns show data for the last three weeks only (March 8 to March 29). The pattern isn't as strong here, but it's still there: 31.8% of tweets occurred between 6 and 9am again.

The implication for prediction markets is clear: If Trump hasn't tweeted by 9am, you should worry that his tweet count for the day will be *much lower* than average. We can put a finer point on this by looking at a regression plot of total daily tweets against tweets before 9am:

![image](http://i.imgur.com/ODM2PcM.png){: .center-image}

What this chart tells us is that Trump doesn't "make up for lost tweets" if he fails to tweet before 9am. If he doesn't tweet before 9, his total daily count will be lower. Of the 15 times Trump hasn't tweeted by 9am, on average he only tweets 2.9 times that day:

| # Tweets Before 9am | Avg. Daily Total | Times this Happened |
|---------------------|------------------|---------------------|
| 0                   | 2.9              | 15                  |
| 1                   | 3.1              | 10                  |
| 2                   | 5                | 15                  |
| 3                   | 6.5              | 6                   |
| 4                   | 6                | 4                   |
| 5                   | 9.2              | 5                   |
| 6                   | 10.5             | 4                   |
| 7                   | 11               | 1                   |

