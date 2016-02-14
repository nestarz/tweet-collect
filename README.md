# tweet-collect

A shitty script I wrote to collect the content I've posted, retweeted, and faved on twitter.

## requirements

* bash, coreutils
* jq - https://github.com/stedolan/jq
* twurl - https://github.com/twitter/twurl
* wget

## install

Put it in crontab to run every hour or whatever.

# TODO

Get rid of all the lame double quote stripping, `jq -r` can handle most of these.

Download more links and shit, lest they disappear from the internet forever.
