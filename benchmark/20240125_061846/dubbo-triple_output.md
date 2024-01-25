# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.359 ops/ms
# Warmup Iteration   2: 12.023 ops/ms
# Warmup Iteration   3: 12.450 ops/ms
Iteration   1: 12.683 ops/ms
Iteration   2: 12.660 ops/ms
Iteration   3: 12.690 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.678 ±(99.9%) 0.292 ops/ms [Average]
  (min, avg, max) = (12.660, 12.678, 12.690), stdev = 0.016
  CI (99.9%): [12.385, 12.970] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.415 ops/ms
# Warmup Iteration   2: 13.323 ops/ms
# Warmup Iteration   3: 13.213 ops/ms
Iteration   1: 13.167 ops/ms
Iteration   2: 13.277 ops/ms
Iteration   3: 13.300 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.248 ±(99.9%) 1.294 ops/ms [Average]
  (min, avg, max) = (13.167, 13.248, 13.300), stdev = 0.071
  CI (99.9%): [11.954, 14.542] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.420 ops/ms
# Warmup Iteration   2: 12.949 ops/ms
# Warmup Iteration   3: 12.911 ops/ms
Iteration   1: 13.083 ops/ms
Iteration   2: 12.984 ops/ms
Iteration   3: 12.995 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.021 ±(99.9%) 0.988 ops/ms [Average]
  (min, avg, max) = (12.984, 13.021, 13.083), stdev = 0.054
  CI (99.9%): [12.033, 14.009] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.633 ops/ms
# Warmup Iteration   2: 10.380 ops/ms
# Warmup Iteration   3: 10.556 ops/ms
Iteration   1: 10.693 ops/ms
Iteration   2: 10.565 ops/ms
Iteration   3: 10.685 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.648 ±(99.9%) 1.318 ops/ms [Average]
  (min, avg, max) = (10.565, 10.648, 10.693), stdev = 0.072
  CI (99.9%): [9.330, 11.966] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.037 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.541 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.488 ±(99.9%) 0.004 ms/op
Iteration   1: 2.528 ±(99.9%) 0.004 ms/op
Iteration   2: 2.469 ±(99.9%) 0.004 ms/op
Iteration   3: 2.485 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.494 ±(99.9%) 0.558 ms/op [Average]
  (min, avg, max) = (2.469, 2.494, 2.528), stdev = 0.031
  CI (99.9%): [1.937, 3.052] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.631 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.438 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.446 ±(99.9%) 0.003 ms/op
Iteration   1: 2.418 ±(99.9%) 0.003 ms/op
Iteration   2: 2.451 ±(99.9%) 0.004 ms/op
Iteration   3: 2.439 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.436 ±(99.9%) 0.309 ms/op [Average]
  (min, avg, max) = (2.418, 2.436, 2.451), stdev = 0.017
  CI (99.9%): [2.127, 2.745] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.822 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.517 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.465 ±(99.9%) 0.003 ms/op
Iteration   1: 2.468 ±(99.9%) 0.005 ms/op
Iteration   2: 2.438 ±(99.9%) 0.003 ms/op
Iteration   3: 2.461 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.456 ±(99.9%) 0.285 ms/op [Average]
  (min, avg, max) = (2.438, 2.456, 2.468), stdev = 0.016
  CI (99.9%): [2.171, 2.741] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.686 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.077 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.004 ms/op
Iteration   1: 3.016 ±(99.9%) 0.006 ms/op
Iteration   2: 3.026 ±(99.9%) 0.007 ms/op
Iteration   3: 3.036 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.026 ±(99.9%) 0.187 ms/op [Average]
  (min, avg, max) = (3.016, 3.026, 3.036), stdev = 0.010
  CI (99.9%): [2.839, 3.213] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.329 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.599 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.512 ±(99.9%) 0.005 ms/op
Iteration   1: 2.498 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.950 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.670 ms/op
                 createUser·p0.999:  11.239 ms/op
                 createUser·p0.9999: 13.891 ms/op
                 createUser·p1.00:   14.139 ms/op

Iteration   2: 2.506 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.893 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.580 ms/op
                 createUser·p0.999:  8.817 ms/op
                 createUser·p0.9999: 12.354 ms/op
                 createUser·p1.00:   13.418 ms/op

Iteration   3: 2.520 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.004 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.977 ms/op
                 createUser·p0.999:  8.331 ms/op
                 createUser·p0.9999: 11.474 ms/op
                 createUser·p1.00:   13.451 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382368
  mean =      2.508 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 186680 
    [ 2.500,  3.750) = 191922 
    [ 3.750,  5.000) = 2867 
    [ 5.000,  6.250) = 395 
    [ 6.250,  7.500) = 51 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 115 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 84 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.893 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.736 ms/op
     p(99.9000) =      8.331 ms/op
     p(99.9900) =     13.353 ms/op
     p(99.9990) =     14.028 ms/op
     p(99.9999) =     14.139 ms/op
    p(100.0000) =     14.139 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.779 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.476 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.451 ±(99.9%) 0.005 ms/op
Iteration   1: 2.432 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.069 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.387 ms/op
                 existUser·p0.999:  5.464 ms/op
                 existUser·p0.9999: 13.722 ms/op
                 existUser·p1.00:   14.352 ms/op

Iteration   2: 2.451 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.863 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.695 ms/op
                 existUser·p0.999:  7.648 ms/op
                 existUser·p0.9999: 12.828 ms/op
                 existUser·p1.00:   13.517 ms/op

Iteration   3: 2.451 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.879 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.905 ms/op
                 existUser·p0.999:  6.152 ms/op
                 existUser·p0.9999: 11.353 ms/op
                 existUser·p1.00:   12.681 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392449
  mean =      2.445 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 198443 
    [ 2.500,  3.750) = 190540 
    [ 3.750,  5.000) = 2588 
    [ 5.000,  6.250) = 410 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 84 
    [12.500, 13.750) = 116 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      2.478 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.092 ms/op
     p(99.0000) =      3.658 ms/op
     p(99.9000) =      6.709 ms/op
     p(99.9900) =     13.369 ms/op
     p(99.9990) =     14.209 ms/op
     p(99.9999) =     14.352 ms/op
    p(100.0000) =     14.352 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.873 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.564 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.006 ms/op
Iteration   1: 2.481 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.818 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.674 ms/op
                 getUser·p0.999:  7.108 ms/op
                 getUser·p0.9999: 15.731 ms/op
                 getUser·p1.00:   16.351 ms/op

Iteration   2: 2.510 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.997 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   4.088 ms/op
                 getUser·p0.999:  8.578 ms/op
                 getUser·p0.9999: 12.751 ms/op
                 getUser·p1.00:   13.681 ms/op

Iteration   3: 2.501 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.868 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.641 ms/op
                 getUser·p0.999:  8.520 ms/op
                 getUser·p0.9999: 11.407 ms/op
                 getUser·p1.00:   12.321 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384136
  mean =      2.497 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 73 
    [ 1.250,  2.500) = 190583 
    [ 2.500,  3.750) = 189280 
    [ 3.750,  5.000) = 3422 
    [ 5.000,  6.250) = 381 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 91 
    [10.000, 11.250) = 67 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 94 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.801 ms/op
     p(99.9000) =      8.466 ms/op
     p(99.9900) =     14.450 ms/op
     p(99.9990) =     16.097 ms/op
     p(99.9999) =     16.351 ms/op
    p(100.0000) =     16.351 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.790 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.009 ms/op
Iteration   1: 3.025 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.860 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  9.814 ms/op
                 listUser·p0.9999: 12.361 ms/op
                 listUser·p1.00:   12.599 ms/op

Iteration   2: 3.005 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.614 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.398 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.601 ms/op
                 listUser·p0.9999: 11.929 ms/op
                 listUser·p1.00:   12.812 ms/op

Iteration   3: 3.010 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.780 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  9.339 ms/op
                 listUser·p0.9999: 10.937 ms/op
                 listUser·p1.00:   11.289 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318247
  mean =      3.013 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 140 
    [ 1.250,  2.500) = 93125 
    [ 2.500,  3.750) = 186024 
    [ 3.750,  5.000) = 31503 
    [ 5.000,  6.250) = 6057 
    [ 6.250,  7.500) = 711 
    [ 7.500,  8.750) = 189 
    [ 8.750, 10.000) = 285 
    [10.000, 11.250) = 133 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.614 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =      9.564 ms/op
     p(99.9900) =     11.977 ms/op
     p(99.9990) =     12.741 ms/op
     p(99.9999) =     12.812 ms/op
    p(100.0000) =     12.812 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.678 ± 0.292  ops/ms
ClientPb.existUser                       thrpt       3  13.248 ± 1.294  ops/ms
ClientPb.getUser                         thrpt       3  13.021 ± 0.988  ops/ms
ClientPb.listUser                        thrpt       3  10.648 ± 1.318  ops/ms
ClientPb.createUser                       avgt       3   2.494 ± 0.558   ms/op
ClientPb.existUser                        avgt       3   2.436 ± 0.309   ms/op
ClientPb.getUser                          avgt       3   2.456 ± 0.285   ms/op
ClientPb.listUser                         avgt       3   3.026 ± 0.187   ms/op
ClientPb.createUser                     sample  382368   2.508 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.893           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.552           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.056           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.736           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.331           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.353           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.139           ms/op
ClientPb.existUser                      sample  392449   2.445 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.863           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.478           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.982           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.658           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.709           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.369           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.352           ms/op
ClientPb.getUser                        sample  384136   2.497 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.818           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.519           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.801           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.466           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.450           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.351           ms/op
ClientPb.listUser                       sample  318247   3.013 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.614           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.887           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.587           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.564           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.977           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.812           ms/op
