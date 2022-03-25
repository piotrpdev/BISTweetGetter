# BISTweetGetter

Gets *all* of your tweets at puts them into a word document.

## How do I use it?

* Install [Python 3](https://www.python.org/downloads/)
* Go into `main.py` and change `user_id` to your own twitter id
* [Create a twitter developer account and make an app](https://developer.twitter.com/en/apply-for-access)
* Use `export 'BEARER_TOKEN'='<your_bearer_token>'` in bash (you can use git bash) and use your own bearer token from the app
* Install requests (`pip install requests`)
* Run the script (`py main.py`) and a word document should be generated in the directory

## Questions

> Why not just get the tweets that at @ComputingAtWIT(/SETU)?

A lot of people didn't catch on in the beginning (including me) that you need to do that and didn't bother. If you want that functionality though, it should be pretty easy to just filter out the JSON objects that don't have that in the text field.
