# User Tasks in Web Archives

## How Journalists Use Web Archives

There are a variety of ways journalists use web archives when investigating stories. This data set includes 106 articles from May 11, 2022 to July 6, 2022 that use web archives as evidence. Each article was analyzed to determine its topic and the user task that web archives supported. The mementos from the articles were also extracted when they were present, and articles without links to mementos were anaylized to determine why a link was absent. The memento_date can be used as a start date and the article_date can be used as an end date to determine a time span of interest for each memento URI for versioning purposes.

[webarchives_journalists_user_tasks_clean.csv](webarchives_journalists_user_tasks_clean.csv)
* topic - the topic of the news article (Sports, Politics, ...)
* task - why the journalist use web archives
* article_date - the date of the news article
* article_url  - the url of the news article
* memento_url - the url of the memento referenced directly or indirectly in the news article
* memento_url_prob - if the memento was not referenced directly, what the problem was
* memento_date - the date of the memento extracted from the memento_url

The blog entry [Web Archiving in Popular Media II: User Tasks of Journalists](https://ws-dl.blogspot.com/2022/08/2022-08-10-web-archiving-in-popular.html) talks more about this data set.
