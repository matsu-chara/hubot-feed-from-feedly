# hubot-feed-from-feedly

* get feed from feedly at 2 minute interval (cron)
* get feed by telling `hubot feed`

## installation

* `npm install --save hubot-feed-from-feedly`

* save feedly access token in `<hubot project root>/feedly_access_token.txt` (you need read & write permissions)

* save below environmental variables

```sh
# feedly
export FEEDLY_REFRESH_TOKEN=""
export FEEDLY_CLIENT_ID=""
export FEEDLY_CLIENT_SECRET=""

## adapter-options
# hubot-shell
# export HUBOT_NAME="hubot"
# export HUBOT_ROOM_NAME="Shell"

# hubot-twitter-userstream
# export HUBOT_NAME="hubot"
# export HUBOT_ROOM_NAME="Twitter"
# export BITLY_ACCESS_TOKEN=""
# export HUBOT_TWITTER_KEY="" # 140 charcter mode if define
# export HUBOT_TWITTER_SECRET=""
# export HUBOT_TWITTER_TOKEN=""
# export HUBOT_TWITTER_TOKEN_SECRET=""

# slack
# export HUBOT_NAME="hubot"
# export HUBOT_ROOM_NAME="#general"
# expoert HUBOT_SLACK_TOKEN=""
# expoert HUBOT_SLACK_TEAM=""
# expoert HUBOT_SLACK_BOTNAME="$HUBOT_NAME"
```

* add "hubot-feed-from-feedly" into external-scripts.json
