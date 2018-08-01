
# docker-matterircd

Docker container for [42wims' excellent matterircd](https://github.com/42wim/matterircd). Run like this:
```
docker run -ti -e MM_SERVER="https://your.server" -e MM_TEAM="the-a-team" - -p 6667:6667 dramaturg/matterircd
```
