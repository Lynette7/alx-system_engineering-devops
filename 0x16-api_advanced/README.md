Questions involving APIs are common for interviews. Sometimes they’re as simple as ‘write a Python script that queries a given endpoint’, sometimes they require you to use recursive functions and format/sort the results.

A great API to use for some practice is the Reddit API. There’s a lot of endpoints available, many that don’t require any form of authentication, and there’s tons of information to be parsed out and presented. Getting comfortable with API calls now can save you some face during technical interviews and even outside of the job market, you might find personal use cases to make your life a little bit easier.

Table of Contents
- 0-subs.py: Python function that queries the Reddit API and returns the number of subscribers (not active users, total subscribers) for a given subreddit
- 1-top_ten.py: Python function that queries the Reddit API and prints the titles of the first 10 hot posts listed for a given subreddit
- 2-recurse.py: a Python recursive function that queries the Reddit API and returns a list containing the titles of all hot articles for a given subreddit
- 100-count.py: a Python recursive function that queries the Reddit API, parses the title of all hot articles, and prints a sorted count of given keywords (case-insensitive, delimited by spaces. Javascript should count as javascript, but java should not)