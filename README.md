# twitter-history
Tracking significant changes to the Twitter API or platform as a whole. Attempting to be accurate to the day for dates, and as exhaustive as possible. Main purpose was to have a reference for when to use certain filters in APIs, and originally created for keeping track of dates when writing about features. Edits / additions welcome.

This is a rabbit hole. Historically, things have appeared and disappeared over time, only to re-appear again, like [tweet link previews](https://twitter.com/IgorBrigadir/status/514767293562507264) for example, spotted in the wild, removed, then came back as Quote Tweets. Before it was a very good subtweet tactic.

Custom Timelines are now "Collections" in TweetDeck, but morphed / merged with "Moments" for Web / Mobile. But Collections on TweetDeck still exist.

### Why? 

Archiving mostly, but also as a reference for analysis, for when things can be attributed to platform changes rather than some other changes you may be interested in measuring. For example: Did you measure a shift in user behaviour? or was it a UI tweak? Is this a bot? or just someone using a new Thread feature to post tweets?  etc.

### What is a significant change?:

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

* GNIP Tweet Timeline http://support.gnip.com/articles/tweet-timeline.html http://archive.ph/X87dl
* GNIP PowerTrack http://support.gnip.com/articles/hpt-timeline.html http://archive.ph/k3l4u
* GNIP Full Archive http://support.gnip.com/articles/fas-timeline.html http://archive.is/LCxgy

* Tweet Timeline https://developer.twitter.com/en/docs/tweets/data-dictionary/guides/tweet-timeline
* PowerTrack Timeline https://developer.twitter.com/en/docs/tweets/batch-historical/guides/hpt-timeline.html
* Full Archive Search Timeline https://developer.twitter.com/en/docs/tweets/search/guides/fas-timeline

* Premium Docs https://developer.twitter.com/en/docs/tweets/search/overview/premium

* Investor Reports https://investor.twitterinc.com/results.cfm
* Developer Forums https://twittercommunity.com/c/announcements
