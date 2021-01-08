Static build homepage: https://johnvansickle.com/ffmpeg/

Manual: 
 - update volumes path in `docker-compose.yml`
 - `docker-compose up -d`
 - `docker-compose exec centos /bin/bash`
 - `/ffmpeg/ffmpeg -ss 1 -i ./sample.mp4 -frames:v 1 output.png`
 - `docker-compose stop`