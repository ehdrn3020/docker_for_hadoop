docker build -t ehdrn3020/hadoop3:1.0 .
docker run -d --name hadoop3 -it ehdrn3020/hadoop3:1.0
docker exec -it hadoop3 /bin/bash
