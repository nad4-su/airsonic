# airsonic docker-compose.yml

This is a docker compose file for the airsonic jukebox player.

- Using `sound.properties`
```
javax.sound.sampled.Clip=#PCH [plughw:1,0]
javax.sound.sampled.Port=#Port PCH [hw:1]
javax.sound.sampled.SourceDataLine=#PCH [plughw:1,0]
javax.sound.sampled.TargetDataLine=#PCH [plughw:1,0]
```

## How to use
1. git clone
```
git clone https://github.com/nad4-su/airsonic.git
```
2. docker compose up
```
docker compose up -d ##or docker-compose up {-d}
```
3. insert music path : The music folder path is './airsonic/music/'


## [Reference]
- [Airsonic git Link](https://github.com/airsonic/airsonic)
- [Airsonic Docker Image](https://hub.docker.com/r/airsonic/airsonic/)
- [Airsonic Documentation Docker Jukebox](https://airsonic.github.io/docs/jukebox/)



