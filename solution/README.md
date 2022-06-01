Part 1
1) docker run -d infracloudio/csvserver:latest
2) docker logs <contianer ID>
3) Created shell script gencsv.sh
4) docker run -d -i -v /root/test/inputFile:/csvserver/inputdata/ infracloudio/csvserver:latest
5) Application listening in 9300 port
6) docker run -e CSVSERVER_BORDER=Orange -it -v /root/test/inputFile:/csvserver/inputdata/ infracloudio/csvserver:latest bash
7)  
