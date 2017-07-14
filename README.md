profile
=======
highly available proxy pool built on java, for better tuning

tech stack
=======
springboot, mongodb, redis, okhttp3, swagger, jsoup

requirement
=======
- [ ] availability, speed, stable
- [ ] structured data model (easy to query and hanle)
- [ ] convenient data visualization
- [ ] scalable proxy source (free & paid)
- [ ] scalable persistent storage
- [ ] convenient restful api
- [ ] multithreading, asynchronous and schedule task for high performance
- [ ] distributed architecture

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
PUT `http://{host}:{port}/proxypool/api/v1/proxies`  
