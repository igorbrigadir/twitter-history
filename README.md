# twitter-history
Tracking significant changes to the Twitter API or platform as a whole. Attempting to be accurate to the day for dates, and as exhaustive as possible. Main purpose was to have a reference for when to use certain filters in APIs, and originally created for keeping track of dates when writing about features. Edits / additions welcome.

### Significance:

Roughly, any change that is platform-wide is included, eg: Major changes to UI like Retweet button are included, but incremental changes to Apps may not be. Policy tweaks to TOS, Developer agreement aren't in here, but maybe should be. Probably shouldn't include events about individuals or groups (eg: some celebrity deleted / suspended etc). 

### Data:

* `date`: YYYY-MM-DD

* `change`: Short label

* `type`: Rough classification of the type of change
	- `UX` is any change where users would be impacted somehow
	- `ORG` is any major organisational change
	- `API` any change that only developers may care about

* `description`: A Longer description of the change or impact.

* `link`: Source URL for this change announcement or documentation.

### Sources:

* Twitter Blog https://blog.twitter.com
* GNIP Blog http://support.gnip.com/articles/tweet-timeline.html http://archive.ph/X87dl
* GNIP Docs http://support.gnip.com/articles/hpt-timeline.html http://archive.ph/k3l4u
* Premium Docs https://developer.twitter.com/en/docs/tweets/search/overview/premium
* Premium Docs https://developer.twitter.com/en/docs/tweets/data-dictionary/guides/tweet-timeline
* Investor Reports https://investor.twitterinc.com/results.cfm
* Developer Forums https://twittercommunity.com/c/announcements
