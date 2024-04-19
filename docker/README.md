1 số lệnh hay dùng:
- liệt kê các image đang có: sudo docker images
- liệt kê các container đang có:
docker ps
- stop tất cả các container:
docker stop $(docker ps -aq) / sudo docker stop $(sudo docker ps -aq)
- delete tất cả các container:
docker rm $(docker ps -aq)
- lệnh chạy docker: sudo docker-compose -f 1docker-compose.yaml up

- xoa: docker system pruneVNINDEX