This is a simple web app that shows the top stories from [Hacker News](https://news.ycombinator.com/news) via [its API](http://blog.ycombinator.com/hacker-news-api).

Unfortunately it has a bunch of performance issues, such as:

* Layout Thrashing
* Expensive painting
* Unnecessary layouts
* Long-running and badly-timed JavaScript
* Bad touch handling

