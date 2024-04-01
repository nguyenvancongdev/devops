1 số lệnh hay dùng:
- liệt kê các image đang có:
- liệt kê các container đang có:
docker ps
- stop tất cả các container:
docker stop $(docker ps -aq)
- delete tất cả các container:
docker rm $(docker ps -aq)
