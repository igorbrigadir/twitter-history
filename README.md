# twitter-history
Tracking significant changes to the Twitter API or platform as a whole.

Attempting to be accurate to the day for dates, and as exhaustive as possible. The main purpose was to have a reference for when to use certain filters in APIs, and originally created for keeping track of dates when writing about features. Edits / additions welcome.

### Why? 

Archiving mostly, but also as a reference for analysis, for when things can be attributed to platform changes rather than some other changes you may be interested in measuring.

### What is a significant change?:

Roughly, any change that is platform-wide is included, eg: Major changes to UI like Retweet button. Policy tweaks to TOS, Developer agreement aren't in here, but maybe should be. Suggestions on classifying this better are welcome, I've been arbitrarily deciding what's significant and what's not.

### Data:

* `date`: YYYY-MM-DD

* `change`: Short label

* `type`: Rough classification of the type of change
	- `UX` is any change where users would be impacted somehow
	- `ORG` is any major organisational change
	- `API` any change that developers may care about
	- `EVT` a pivotal event of some sort

* `description`: A Longer description of the change or impact.

* `link`: Source URL for this change announcement or documentation.

### Todo, Maybe:

* Add column of affected fields and or endpoints, so CSV can be used automatically to check queries for issues (eg: warning that GEO data is unavailable for some date range, etc)
* Bibtex entries for official source and a representative paper.
* Extra column for source of change (docs, blog, other)
* Move Org / Evt "changes" to a separate list, leave only changes with data impact.

### Main Sources:

* Twitter Blog https://blog.twitter.com
* Tweet Timeline https://developer.twitter.com/en/docs/tweets/data-dictionary/guides/tweet-timeline
* PowerTrack Timeline https://developer.twitter.com/en/docs/tweets/batch-historical/guides/hpt-timeline.html
* Full Archive Search Timeline https://developer.twitter.com/en/docs/tweets/search/guides/fas-timeline
* Premium Docs https://developer.twitter.com/en/docs/tweets/search/overview/premium
* Investor Reports https://investor.twitterinc.com/results.cfm
* Developer Forums https://twittercommunity.com/c/announcements
* Indieweb Wiki https://indieweb.org/Twitter