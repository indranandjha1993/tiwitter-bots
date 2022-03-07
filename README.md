# tiwitter-bots
**Build the image using this command:**

`docker build . -t fav-retweet-bot`

**Run command to test the image, passing it the environment variables holding the authentication credentials:**

`docker run -it -e CONSUMER_KEY="uDRNy31oWfoiKV9AvPoNavy0I" \
 -e CONSUMER_SECRET="lnAL5VAgZLWNspQVpd3X6tEo47PRCmsPEwuxpvLCLSR08DMa4O" \
 -e ACCESS_TOKEN="622518593-j7gWSqzQO31ju7Bf7idB47NlZeSENsuADGU9B69I" \
 -e ACCESS_TOKEN_SECRET="iutFsxvP5IglRckJ1I1why6017xMNkzxqBID48Azw0GvT" \
 fav-retweet-bot`