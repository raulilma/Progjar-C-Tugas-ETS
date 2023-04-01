# Progjar-C-Tugas-ETS
Raul Ilma Rajasa - 5025201076
## Multithreading
### 1. Non-Secure
#### a. ```ab -n 1000 -c 10 -s 86400 http://192.168.2.19:20001/```
<details>
  <summary>
      Thread Non-Secure (n = 1000 - c = 10)
  </summary>
This is ApacheBench, Version 2.3 <$Revision: 1879490 $>
Copyright 1996 Adam Twiss, Zeus Technology Ltd, http://www.zeustech.net/
Licensed to The Apache Software Foundation, http://www.apache.org/

Benchmarking 192.168.2.19 (be patient)
Completed 100 requests
Completed 200 requests
Completed 300 requests
Completed 400 requests
Completed 500 requests
Completed 600 requests
Completed 700 requests
Completed 800 requests
Completed 900 requests
Completed 1000 requests
Finished 1000 requests


Server Software:        myserver/1.0
Server Hostname:        192.168.2.19
Server Port:            20001

Document Path:          /
Document Length:        35 bytes

Concurrency Level:      10
Time taken for tests:   234.082 seconds
Complete requests:      1000
Failed requests:        0
Total transferred:      147000 bytes
HTML transferred:       35000 bytes
Requests per second:    4.27 [#/sec] (mean)
Time per request:       2340.821 [ms] (mean)
Time per request:       234.082 [ms] (mean, across all concurrent requests)
Transfer rate:          0.61 [Kbytes/sec] received

Connection Times (ms)
              min  mean[+/-sd] median   max
Connect:        0    1   0.4      1       1
Processing:     9 2210 3462.3   1574   35608
Waiting:        3 2179 3453.5   1556   35578
Total:         10 2211 3462.3   1575   35608

Percentage of the requests served within a certain time (ms)
  50%   1575
  66%   2232
  75%   2674
  80%   2977
  90%   3963
  95%   5130
  98%   9658
  99%  17420
 100%  35608 (longest request)
</details>

#### b. ```ab -n 1000 -c 50 -s 86400 http://192.168.2.19:20001/```
<details>
  <summary>
      Thread Non-Secure (n = 1000 - c = 50)
  </summary>
This is ApacheBench, Version 2.3 <$Revision: 1879490 $>
Copyright 1996 Adam Twiss, Zeus Technology Ltd, http://www.zeustech.net/
Licensed to The Apache Software Foundation, http://www.apache.org/

Benchmarking 192.168.2.19 (be patient)
Completed 100 requests
Completed 200 requests
Completed 300 requests
Completed 400 requests
Completed 500 requests
Completed 600 requests
Completed 700 requests
Completed 800 requests
Completed 900 requests
Completed 1000 requests
Finished 1000 requests


Server Software:        myserver/1.0
Server Hostname:        192.168.2.19
Server Port:            20001

Document Path:          /
Document Length:        35 bytes

Concurrency Level:      50
Time taken for tests:   555.743 seconds
Complete requests:      1000
Failed requests:        89
   (Connect: 0, Receive: 0, Length: 89, Exceptions: 0)
Total transferred:      133917 bytes
HTML transferred:       31885 bytes
Requests per second:    1.80 [#/sec] (mean)
Time per request:       27787.132 [ms] (mean)
Time per request:       555.743 [ms] (mean, across all concurrent requests)
Transfer rate:          0.24 [Kbytes/sec] received

Connection Times (ms)
              min  mean[+/-sd] median   max
Connect:        0    1   0.4      1       1
Processing:  1346 25146 47433.9   6163  257282
Waiting:        0 11001 16290.7   5201   96017
Total:       1347 25147 47433.9   6163  257283

Percentage of the requests served within a certain time (ms)
  50%   6163
  66%   9921
  75%  18424
  80%  21940
  90%  69797
  95%  131707
  98%  257256
  99%  257268
 100%  257283 (longest request)
</details>

#### c. ```ab -n 1000 -c 100 -s 86400 http://192.168.2.19:20001/```
<details>
  <summary>
      Thread Non-Secure (n = 1000 - c = 100)
  </summary>
This is ApacheBench, Version 2.3 <$Revision: 1879490 $>
Copyright 1996 Adam Twiss, Zeus Technology Ltd, http://www.zeustech.net/
Licensed to The Apache Software Foundation, http://www.apache.org/

Benchmarking 192.168.2.19 (be patient)
Completed 100 requests
Completed 200 requests
Completed 300 requests
Completed 400 requests
Completed 500 requests
Completed 600 requests
Completed 700 requests
Completed 800 requests
Completed 900 requests
Completed 1000 requests
Finished 1000 requests


Server Software:        myserver/1.0
Server Hostname:        192.168.2.19
Server Port:            20001

Document Path:          /
Document Length:        35 bytes

Concurrency Level:      100
Time taken for tests:   618.782 seconds
Complete requests:      1000
Failed requests:        312
   (Connect: 0, Receive: 0, Length: 312, Exceptions: 0)
Total transferred:      101136 bytes
HTML transferred:       24080 bytes
Requests per second:    1.62 [#/sec] (mean)
Time per request:       61878.232 [ms] (mean)
Time per request:       618.782 [ms] (mean, across all concurrent requests)
Transfer rate:          0.16 [Kbytes/sec] received

Connection Times (ms)
              min  mean[+/-sd] median   max
Connect:        0    1   0.5      1       2
Processing:  1309 55453 58130.2  21785  240656
Waiting:        0 13485 20205.9   6578  183301
Total:       1310 55454 58130.2  21785  240656

Percentage of the requests served within a certain time (ms)
  50%  21785
  66%  72260
  75%  115786
  80%  131011
  90%  133111
  95%  133126
  98%  179201
  99%  240639
 100%  240656 (longest request)
</details>

#### d. ```ab -n 1000 -c 150 -s 86400 http://192.168.2.19:20001/```
<details>
  <summary>
      Thread Non-Secure (n = 1000 - c = 150)
  </summary>
This is ApacheBench, Version 2.3 <$Revision: 1879490 $>
Copyright 1996 Adam Twiss, Zeus Technology Ltd, http://www.zeustech.net/
Licensed to The Apache Software Foundation, http://www.apache.org/

Benchmarking 192.168.2.19 (be patient)
Completed 100 requests
Completed 200 requests
Completed 300 requests
Completed 400 requests
Completed 500 requests
Completed 600 requests
Completed 700 requests
Completed 800 requests
Completed 900 requests
Completed 1000 requests
Finished 1000 requests


Server Software:        myserver/1.0
Server Hostname:        192.168.2.19
Server Port:            20001

Document Path:          /
Document Length:        35 bytes

Concurrency Level:      150
Time taken for tests:   601.931 seconds
Complete requests:      1000
Failed requests:        485
   (Connect: 0, Receive: 0, Length: 485, Exceptions: 0)
Total transferred:      75705 bytes
HTML transferred:       18025 bytes
Requests per second:    1.66 [#/sec] (mean)
Time per request:       90289.580 [ms] (mean)
Time per request:       601.931 [ms] (mean, across all concurrent requests)
Transfer rate:          0.12 [Kbytes/sec] received

Connection Times (ms)
              min  mean[+/-sd] median   max
Connect:        0    0   0.5      1       2
Processing:  2381 76410 58348.1  78987  228967
Waiting:        0 12304 22143.2   4486  125220
Total:       2381 76410 58348.0  78987  228967
ERROR: The median and mean for the initial connection time are more than twice the standard
       deviation apart. These results are NOT reliable.

Percentage of the requests served within a certain time (ms)
  50%  78987
  66%  130091
  75%  132590
  80%  133098
  90%  133125
  95%  143314
  98%  143368
  99%  179201
 100%  228967 (longest request)
</details>

#### e. ```ab -n 1000 -c 200 -s 86400 http://192.168.2.19:20001/```
<details>
  <summary>
      Thread Non-Secure (n = 1000 - c = 200)
  </summary>
This is ApacheBench, Version 2.3 <$Revision: 1879490 $>
Copyright 1996 Adam Twiss, Zeus Technology Ltd, http://www.zeustech.net/
Licensed to The Apache Software Foundation, http://www.apache.org/

Benchmarking 192.168.2.19 (be patient)
Completed 100 requests
Completed 200 requests
Completed 300 requests
Completed 400 requests
Completed 500 requests
Completed 600 requests
Completed 700 requests
Completed 800 requests
Completed 900 requests
Completed 1000 requests
Finished 1000 requests


Server Software:        myserver/1.0
Server Hostname:        192.168.2.19
Server Port:            20001

Document Path:          /
Document Length:        35 bytes

Concurrency Level:      200
Time taken for tests:   382.448 seconds
Complete requests:      1000
Failed requests:        342
   (Connect: 0, Receive: 0, Length: 342, Exceptions: 0)
Total transferred:      96726 bytes
HTML transferred:       23030 bytes
Requests per second:    2.61 [#/sec] (mean)
Time per request:       76489.550 [ms] (mean)
Time per request:       382.448 [ms] (mean, across all concurrent requests)
Transfer rate:          0.25 [Kbytes/sec] received

Connection Times (ms)
              min  mean[+/-sd] median   max
Connect:        0    0   0.4      1       1
Processing:  1218 55720 56369.5  20281  179168
Waiting:        0 11587 20044.8   3609  122976
Total:       1219 55720 56369.4  20282  179169
ERROR: The median and mean for the initial connection time are more than twice the standard
       deviation apart. These results are NOT reliable.

Percentage of the requests served within a certain time (ms)
  50%  20282
  66%  112644
  75%  120127
  80%  130441
  90%  131332
  95%  133084
  98%  145766
  99%  179149
 100%  179169 (longest request)
 </details>

### 2. Secured
#### a. ```abs -n 1000 -c 10 -s 86400 https://192.168.2.19:20001/```
<details>
  <summary>
      Thread Secure (n = 1000 - c = 10)
  </summary>
This is ApacheBench, Version 2.3 <$Revision: 1879490 $>
Copyright 1996 Adam Twiss, Zeus Technology Ltd, http://www.zeustech.net/
Licensed to The Apache Software Foundation, http://www.apache.org/

Benchmarking 192.168.2.19 (be patient)
Completed 100 requests
Completed 200 requests
Completed 300 requests
Completed 400 requests
Completed 500 requests
SSL handshake failed (5).
Completed 600 requests
Completed 700 requests
Completed 800 requests
SSL handshake failed (5).
Completed 900 requests
Completed 1000 requests
Finished 1000 requests


Server Software:        myserver/1.0
Server Hostname:        192.168.2.19
Server Port:            20001
SSL/TLS Protocol:       TLSv1.2,ECDHE-RSA-AES256-GCM-SHA384,2048,256
Server Temp Key:        X25519 253 bits

Document Path:          /
Document Length:        35 bytes

Concurrency Level:      10
Time taken for tests:   404.864 seconds
Complete requests:      1000
Failed requests:        2
   (Connect: 0, Receive: 0, Length: 2, Exceptions: 0)
Total transferred:      146706 bytes
HTML transferred:       34930 bytes
Requests per second:    2.47 [#/sec] (mean)
Time per request:       4048.636 [ms] (mean)
Time per request:       404.864 [ms] (mean, across all concurrent requests)
Transfer rate:          0.35 [Kbytes/sec] received

Connection Times (ms)
              min  mean[+/-sd] median   max
Connect:        0 2460 6119.3   1181   66398
Processing:     6 1398 5942.4   1037  133521
Waiting:        2 1093 724.8    994    3408
Total:         15 3858 8556.4   2445  133521

Percentage of the requests served within a certain time (ms)
  50%   2445
  66%   3347
  75%   3835
  80%   4280
  90%   5983
  95%   9541
  98%  18543
  99%  35491
 100%  133521 (longest request)
 </details>

#### b. ```abs -n 1000 -c 50 -s 86400 https://192.168.2.19:20001/```
<details>
  <summary>
      Thread Secure (n = 1000 - c = 50)
  </summary>
This is ApacheBench, Version 2.3 <$Revision: 1879490 $>
Copyright 1996 Adam Twiss, Zeus Technology Ltd, http://www.zeustech.net/
Licensed to The Apache Software Foundation, http://www.apache.org/

Benchmarking 192.168.2.19 (be patient)
Completed 100 requests
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
Completed 200 requests
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
Completed 300 requests
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
Completed 400 requests
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
Completed 500 requests
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
Completed 600 requests
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
Completed 700 requests
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
Completed 800 requests
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
Completed 900 requests
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
Completed 1000 requests
Finished 1000 requests


Server Software:        myserver/1.0
Server Hostname:        192.168.2.19
Server Port:            20001
SSL/TLS Protocol:       TLSv1.2,ECDHE-RSA-AES256-GCM-SHA384,2048,256
Server Temp Key:        X25519 253 bits

Document Path:          /
Document Length:        35 bytes

Concurrency Level:      50
Time taken for tests:   817.440 seconds
Complete requests:      1000
Failed requests:        181
   (Connect: 0, Receive: 0, Length: 181, Exceptions: 0)
Total transferred:      120393 bytes
HTML transferred:       28665 bytes
Requests per second:    1.22 [#/sec] (mean)
Time per request:       40871.975 [ms] (mean)
Time per request:       817.440 [ms] (mean, across all concurrent requests)
Transfer rate:          0.14 [Kbytes/sec] received

Connection Times (ms)
              min  mean[+/-sd] median   max
Connect:        0 10473 17239.4   3529  121546
Processing:   516 28024 55688.3   2691  221079
Waiting:        0 2350 968.3   2328    5571
Total:       1431 38497 53494.9   9459  221079

Percentage of the requests served within a certain time (ms)
  50%   9459
  66%  21288
  75%  38679
  80%  71141
  90%  133105
  95%  133889
  98%  215785
  99%  220977
 100%  221079 (longest request)
</details>

#### c. ```abs -n 1000 -c 100 -s 86400 https://192.168.2.19:20001/```
<details>
  <summary>
      Thread Secure (n = 1000 - c = 100)
  </summary>
This is ApacheBench, Version 2.3 <$Revision: 1879490 $>
Copyright 1996 Adam Twiss, Zeus Technology Ltd, http://www.zeustech.net/
Licensed to The Apache Software Foundation, http://www.apache.org/

Benchmarking 192.168.2.19 (be patient)
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
Completed 100 requests
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
Completed 200 requests
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
Completed 300 requests
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
Completed 400 requests
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
Completed 500 requests
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
Completed 600 requests
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
Completed 700 requests
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
Completed 800 requests
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
Completed 900 requests
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
Completed 1000 requests
Finished 1000 requests


Server Software:        myserver/1.0
Server Hostname:        192.168.2.19
Server Port:            20001
SSL/TLS Protocol:       TLSv1.2,ECDHE-RSA-AES256-GCM-SHA384,2048,256
Server Temp Key:        X25519 253 bits

Document Path:          /
Document Length:        35 bytes

Concurrency Level:      100
Time taken for tests:   779.642 seconds
Complete requests:      1000
Failed requests:        455
   (Connect: 0, Receive: 0, Length: 455, Exceptions: 0)
Total transferred:      80115 bytes
HTML transferred:       19075 bytes
Requests per second:    1.28 [#/sec] (mean)
Time per request:       77964.221 [ms] (mean)
Time per request:       779.642 [ms] (mean, across all concurrent requests)
Transfer rate:          0.10 [Kbytes/sec] received

Connection Times (ms)
              min  mean[+/-sd] median   max
Connect:        0 8832 16501.7   2868  112768
Processing:   824 62673 65765.7   5223  279317
Waiting:        0 2543 1789.0   2950    7110
Total:       1719 71505 59612.8  56693  279317

Percentage of the requests served within a certain time (ms)
  50%  56693
  66%  131677
  75%  132936
  80%  133103
  90%  133124
  95%  133620
  98%  174035
  99%  174075
 100%  279317 (longest request)
</details>

#### d. ```abs -n 1000 -c 150 -s 86400 https://192.168.2.19:20001/```
<details>
  <summary>
      Thread Secure (n = 1000 - c = 150)
  </summary>
This is ApacheBench, Version 2.3 <$Revision: 1879490 $>
Copyright 1996 Adam Twiss, Zeus Technology Ltd, http://www.zeustech.net/
Licensed to The Apache Software Foundation, http://www.apache.org/

Benchmarking 192.168.2.19 (be patient)
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
Completed 100 requests
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
Completed 200 requests
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
Completed 300 requests
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
Completed 400 requests
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
Completed 500 requests
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
Completed 600 requests
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
Completed 700 requests
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
Completed 800 requests
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
Completed 900 requests
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
Completed 1000 requests
SSL handshake failed (5).
SSL handshake failed (5).
Finished 1000 requests


Server Software:        myserver/1.0
Server Hostname:        192.168.2.19
Server Port:            20001
SSL/TLS Protocol:       TLSv1.2,ECDHE-RSA-AES256-GCM-SHA384,2048,256
Server Temp Key:        X25519 253 bits

Document Path:          /
Document Length:        35 bytes

Concurrency Level:      150
Time taken for tests:   670.578 seconds
Complete requests:      1000
Failed requests:        630
   (Connect: 0, Receive: 0, Length: 630, Exceptions: 0)
Total transferred:      54684 bytes
HTML transferred:       13020 bytes
Requests per second:    1.49 [#/sec] (mean)
Time per request:       100586.665 [ms] (mean)
Time per request:       670.578 [ms] (mean, across all concurrent requests)
Transfer rate:          0.08 [Kbytes/sec] received

Connection Times (ms)
              min  mean[+/-sd] median   max
Connect:        0 6572 16653.4      0  120391
Processing:  1463 85685 63392.6 132520  220162
Waiting:        0 1992 2294.1      0    8210
Total:       3289 92257 56792.1 132520  220162

Percentage of the requests served within a certain time (ms)
  50%  132520
  66%  133111
  75%  133129
  80%  133159
  90%  134285
  95%  134344
  98%  174026
  99%  174078
 100%  220162 (longest request)
</details>

#### e. ```abs -n 1000 -c 200 -s 86400 https://192.168.2.19:20001/```
<details>
  <summary>
      Thread Secure (n = 1000 - c = 200)
  </summary>
This is ApacheBench, Version 2.3 <$Revision: 1879490 $>
Copyright 1996 Adam Twiss, Zeus Technology Ltd, http://www.zeustech.net/
Licensed to The Apache Software Foundation, http://www.apache.org/

Benchmarking 192.168.2.19 (be patient)
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
Completed 100 requests
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
Completed 200 requests
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
Completed 300 requests
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
Completed 400 requests
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
Completed 500 requests
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
Completed 600 requests
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
Completed 700 requests
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
Completed 800 requests
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
Completed 900 requests
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
SSL handshake failed (5).
Completed 1000 requests
Finished 1000 requests


Server Software:        myserver/1.0
Server Hostname:        192.168.2.19
Server Port:            20001
SSL/TLS Protocol:       TLSv1.2,ECDHE-RSA-AES256-GCM-SHA384,2048,256
Server Temp Key:        X25519 253 bits

Document Path:          /
Document Length:        35 bytes

Concurrency Level:      200
Time taken for tests:   560.836 seconds
Complete requests:      1000
Failed requests:        722
   (Connect: 0, Receive: 0, Length: 722, Exceptions: 0)
Total transferred:      40866 bytes
HTML transferred:       9730 bytes
Requests per second:    1.78 [#/sec] (mean)
Time per request:       112167.148 [ms] (mean)
Time per request:       560.836 [ms] (mean, across all concurrent requests)
Transfer rate:          0.07 [Kbytes/sec] received

Connection Times (ms)
              min  mean[+/-sd] median   max
Connect:        0 4931 13651.5      0  114084
Processing:  1410 97377 58647.0 129557  245500
Waiting:        0 1739 2552.7      0   11169
Total:       4121 102307 52104.5 129557  245500

Percentage of the requests served within a certain time (ms)
  50%  129557
  66%  133085
  75%  133113
  80%  133123
  90%  133198
  95%  138218
  98%  138276
  99%  216391
 100%  245500 (longest request)
</details>

# Multiprocess
## 1. Non-Secure
#### a. ```ab -n 1000 -c 10 -s 86400 http://192.168.2.19:20001/```
<details>
  <summary>
      Process Non-Secure (n = 1000 - c = 10)
  </summary>
C:\xampp\apache\bin>ab -n 1000 -c 10 -s 86400 http://192.168.2.19:20001/
This is ApacheBench, Version 2.3 <$Revision: 1879490 $>
Copyright 1996 Adam Twiss, Zeus Technology Ltd, http://www.zeustech.net/
Licensed to The Apache Software Foundation, http://www.apache.org/

Benchmarking 192.168.2.19 (be patient)
Completed 100 requests
Completed 200 requests
Completed 300 requests
Completed 400 requests
Completed 500 requests
Completed 600 requests
Completed 700 requests
Completed 800 requests
Completed 900 requests
Completed 1000 requests
Finished 1000 requests


Server Software:        myserver/1.0
Server Hostname:        192.168.2.19
Server Port:            20001

Document Path:          /
Document Length:        35 bytes

Concurrency Level:      10
Time taken for tests:   743.436 seconds
Complete requests:      1000
Failed requests:        20
   (Connect: 0, Receive: 0, Length: 20, Exceptions: 0)
Total transferred:      144060 bytes
HTML transferred:       34300 bytes
Requests per second:    1.35 [#/sec] (mean)
Time per request:       7434.364 [ms] (mean)
Time per request:       743.436 [ms] (mean, across all concurrent requests)
Transfer rate:          0.19 [Kbytes/sec] received

Connection Times (ms)
              min  mean[+/-sd] median   max
Connect:        0    1   0.7      1       8
Processing:     7 7121 20365.1   1900  133729
Waiting:        0 4473 9944.5   1774   73619
Total:          7 7122 20365.1   1901  133729

Percentage of the requests served within a certain time (ms)
  50%   1901
  66%   3672
  75%   5100
  80%   6366
  90%   9559
  95%  23418
  98%  129176
  99%  132101
 100%  133729 (longest request)
</details>

#### b. ```ab -n 1000 -c 50 -s 86400 http://192.168.2.19:20001/```

<details>
  <summary>
      Process Non-Secure (n = 1000 - c = 50)
  </summary>
This is ApacheBench, Version 2.3 <$Revision: 1879490 $>
Copyright 1996 Adam Twiss, Zeus Technology Ltd, http://www.zeustech.net/
Licensed to The Apache Software Foundation, http://www.apache.org/

Benchmarking 192.168.2.19 (be patient)
Completed 100 requests
Completed 200 requests
Completed 300 requests
Completed 400 requests
Completed 500 requests
Completed 600 requests
Completed 700 requests
Completed 800 requests
Completed 900 requests
Completed 1000 requests
Finished 1000 requests


Server Software:        myserver/1.0
Server Hostname:        192.168.2.19
Server Port:            20001

Document Path:          /
Document Length:        35 bytes

Concurrency Level:      50
Time taken for tests:   559.465 seconds
Complete requests:      1000
Failed requests:        149
   (Connect: 0, Receive: 0, Length: 149, Exceptions: 0)
Total transferred:      125097 bytes
HTML transferred:       29785 bytes
Requests per second:    1.79 [#/sec] (mean)
Time per request:       27973.245 [ms] (mean)
Time per request:       559.465 [ms] (mean, across all concurrent requests)
Transfer rate:          0.22 [Kbytes/sec] received

Connection Times (ms)
              min  mean[+/-sd] median   max
Connect:        0    1   0.7      1      11
Processing:    12 25780 46514.2   2938  179182
Waiting:        0 6297 15329.9   1243  155462
Total:         13 25781 46514.3   2939  179182

Percentage of the requests served within a certain time (ms)
  50%   2939
  66%   5697
  75%  15843
  80%  34326
  90%  130921
  95%  133111
  98%  133131
  99%  133604
 100%  179182 (longest request)
</details>

#### c. ```ab -n 1000 -c 100 -s 86400 http://192.168.2.19:20001/```
<details>
  <summary>
      Process Non-Secure (n = 1000 - c = 100)
  </summary>
C:\xampp\apache\bin>ab -n 1000 -c 100 -s 86400 http://192.168.2.19:20001/
This is ApacheBench, Version 2.3 <$Revision: 1879490 $>
Copyright 1996 Adam Twiss, Zeus Technology Ltd, http://www.zeustech.net/
Licensed to The Apache Software Foundation, http://www.apache.org/

Benchmarking 192.168.2.19 (be patient)
Completed 100 requests
Completed 200 requests
Completed 300 requests
Completed 400 requests
Completed 500 requests
Completed 600 requests
Completed 700 requests
Completed 800 requests
Completed 900 requests
Completed 1000 requests
Finished 1000 requests


Server Software:        myserver/1.0
Server Hostname:        192.168.2.19
Server Port:            20001

Document Path:          /
Document Length:        35 bytes

Concurrency Level:      100
Time taken for tests:   402.394 seconds
Complete requests:      1000
Failed requests:        182
   (Connect: 0, Receive: 0, Length: 182, Exceptions: 0)
Total transferred:      120246 bytes
HTML transferred:       28630 bytes
Requests per second:    2.49 [#/sec] (mean)
Time per request:       40239.396 [ms] (mean)
Time per request:       402.394 [ms] (mean, across all concurrent requests)
Transfer rate:          0.29 [Kbytes/sec] received

Connection Times (ms)
              min  mean[+/-sd] median   max
Connect:        0    1   0.6      1       8
Processing:    10 35407 65561.4   3439  228345
Waiting:        0 5381 12422.4   1260  122889
Total:         11 35408 65561.3   3440  228346

Percentage of the requests served within a certain time (ms)
  50%   3440
  66%   7538
  75%  18585
  80%  66531
  90%  133104
  95%  228283
  98%  228310
  99%  228321
 100%  228346 (longest request)
</details>

#### d. ```ab -n 1000 -c 150 -s 86400 http://192.168.2.19:20001/```
<details>
  <summary>
      Process Non-Secure (n = 1000 - c = 150)
  </summary>
This is ApacheBench, Version 2.3 <$Revision: 1879490 $>
Copyright 1996 Adam Twiss, Zeus Technology Ltd, http://www.zeustech.net/
Licensed to The Apache Software Foundation, http://www.apache.org/

Benchmarking 192.168.2.19 (be patient)
Completed 100 requests
Completed 200 requests
Completed 300 requests
Completed 400 requests
Completed 500 requests
Completed 600 requests
Completed 700 requests
Completed 800 requests
Completed 900 requests
Completed 1000 requests
Finished 1000 requests


Server Software:        myserver/1.0
Server Hostname:        192.168.2.19
Server Port:            20001

Document Path:          /
Document Length:        35 bytes

Concurrency Level:      150
Time taken for tests:   306.281 seconds
Complete requests:      1000
Failed requests:        260
   (Connect: 0, Receive: 0, Length: 260, Exceptions: 0)
Total transferred:      108780 bytes
HTML transferred:       25900 bytes
Requests per second:    3.26 [#/sec] (mean)
Time per request:       45942.147 [ms] (mean)
Time per request:       306.281 [ms] (mean, across all concurrent requests)
Transfer rate:          0.35 [Kbytes/sec] received

Connection Times (ms)
              min  mean[+/-sd] median   max
Connect:        0    1   0.8      1       8
Processing:    23 37377 54009.3   3804  289853
Waiting:        0 4873 12101.0   1044  132553
Total:         24 37378 54009.2   3804  289854

Percentage of the requests served within a certain time (ms)
  50%   3804
  66%  16743
  75%  111609
  80%  112635
  90%  131830
  95%  133109
  98%  134280
  99%  138208
 100%  289854 (longest request)
</details>

#### e. ```ab -n 1000 -c 200 -s 86400 http://192.168.2.19:20001/```
<details>
  <summary>
      Process Non-Secure (n = 1000 - c = 200)
  </summary>
This is ApacheBench, Version 2.3 <$Revision: 1879490 $>
Copyright 1996 Adam Twiss, Zeus Technology Ltd, http://www.zeustech.net/
Licensed to The Apache Software Foundation, http://www.apache.org/

Benchmarking 192.168.2.19 (be patient)
Completed 100 requests
Completed 200 requests
Completed 300 requests
Completed 400 requests
Completed 500 requests
Completed 600 requests
Completed 700 requests
Completed 800 requests
Completed 900 requests
Completed 1000 requests
Finished 1000 requests


Server Software:        myserver/1.0
Server Hostname:        192.168.2.19
Server Port:            20001

Document Path:          /
Document Length:        35 bytes

Concurrency Level:      200
Time taken for tests:   304.643 seconds
Complete requests:      1000
Failed requests:        316
   (Connect: 0, Receive: 0, Length: 316, Exceptions: 0)
Total transferred:      100548 bytes
HTML transferred:       23940 bytes
Requests per second:    3.28 [#/sec] (mean)
Time per request:       60928.511 [ms] (mean)
Time per request:       304.643 [ms] (mean, across all concurrent requests)
Transfer rate:          0.32 [Kbytes/sec] received

Connection Times (ms)
              min  mean[+/-sd] median   max
Connect:        0    1   1.3      1      12
Processing:    31 49320 61500.6   5852  174071
Waiting:        0 6576 16576.2    516  121759
Total:         32 49320 61500.6   5853  174072

Percentage of the requests served within a certain time (ms)
  50%   5853
  66%  67184
  75%  117773
  80%  130286
  90%  133068
  95%  173996
  98%  174036
  99%  174049
 100%  174072 (longest request)
</details>