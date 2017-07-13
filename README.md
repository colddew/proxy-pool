profile
=======
highly available ip proxy pool built on java, just for better tuning

tech stack
=======
springboot, mongodb, redis, okhttp3, swagger, jsoup

requirement
=======
- [x] 1
- [x] 2
- [x] 3
- [x] 4
- [x] 5
- [x] 6
- [x] 7
- [x] 8
- [x] 9
- [x] 10

build
=======

endpoint
=======
GET `http://{host}:{port}/proxypool/api/v1/proxies/random`  
GET `http://{host}:{port}/proxypool/api/v1/proxies?pageNo={pageNo}&pageSize={pageSize}`  
DELETE `http://{host}:{port}/proxypool/api/v1/proxies/{proxy}`  
GET `http://{host}:{port}/proxypool/api/v1/proxies/refresh`  
GET `http://{host}:{port}/proxypool/api/v1/proxies/{proxy}/check`  
POST `http://{host}:{port}/proxypool/api/v1/proxies`  
POST `http://{host}:{port}/proxypool/api/v1/proxies`  
