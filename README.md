# Progjar-C-Tugas-ETS
<p>Raul Ilma Rajasa - 5025201076</p>
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