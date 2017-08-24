### OBS Configuration
Url: rtmp://localhost:3000/live

Stream Key: test

### Run
docker run -p 3000:1935 -p 3001:3001 -d -v ${PWD}/nginx.conf:/etc/nginx/nginx.conf -v ${PWD}/media:/tmp/media -v ${PWD}/videos:/tmp/videos -v ${PWD}/html:/usr/local/nginx/html thanhson1085/videolivestream
