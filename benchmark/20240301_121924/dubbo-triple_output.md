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
# Warmup Iteration   1: 5.396 ops/ms
# Warmup Iteration   2: 12.356 ops/ms
# Warmup Iteration   3: 12.474 ops/ms
Iteration   1: 12.911 ops/ms
Iteration   2: 13.035 ops/ms
Iteration   3: 13.285 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  13.077 ±(99.9%) 3.479 ops/ms [Average]
  (min, avg, max) = (12.911, 13.077, 13.285), stdev = 0.191
  CI (99.9%): [9.598, 16.556] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.712 ops/ms
# Warmup Iteration   2: 13.227 ops/ms
# Warmup Iteration   3: 13.328 ops/ms
Iteration   1: 13.461 ops/ms
Iteration   2: 13.491 ops/ms
Iteration   3: 13.172 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.375 ±(99.9%) 3.212 ops/ms [Average]
  (min, avg, max) = (13.172, 13.375, 13.491), stdev = 0.176
  CI (99.9%): [10.163, 16.587] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.796 ops/ms
# Warmup Iteration   2: 12.677 ops/ms
# Warmup Iteration   3: 12.668 ops/ms
Iteration   1: 12.917 ops/ms
Iteration   2: 12.861 ops/ms
Iteration   3: 12.772 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.850 ±(99.9%) 1.338 ops/ms [Average]
  (min, avg, max) = (12.772, 12.850, 12.917), stdev = 0.073
  CI (99.9%): [11.512, 14.188] (assumes normal distribution)


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
# Warmup Iteration   1: 6.388 ops/ms
# Warmup Iteration   2: 10.494 ops/ms
# Warmup Iteration   3: 10.691 ops/ms
Iteration   1: 10.779 ops/ms
Iteration   2: 10.646 ops/ms
Iteration   3: 10.646 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.690 ±(99.9%) 1.402 ops/ms [Average]
  (min, avg, max) = (10.646, 10.690, 10.779), stdev = 0.077
  CI (99.9%): [9.288, 12.092] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.206 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.594 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.509 ±(99.9%) 0.004 ms/op
Iteration   1: 2.498 ±(99.9%) 0.004 ms/op
Iteration   2: 2.483 ±(99.9%) 0.004 ms/op
Iteration   3: 2.445 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.476 ±(99.9%) 0.505 ms/op [Average]
  (min, avg, max) = (2.445, 2.476, 2.498), stdev = 0.028
  CI (99.9%): [1.971, 2.980] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.624 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.427 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.422 ±(99.9%) 0.004 ms/op
Iteration   1: 2.403 ±(99.9%) 0.003 ms/op
Iteration   2: 2.378 ±(99.9%) 0.004 ms/op
Iteration   3: 2.408 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.396 ±(99.9%) 0.293 ms/op [Average]
  (min, avg, max) = (2.378, 2.396, 2.408), stdev = 0.016
  CI (99.9%): [2.103, 2.689] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.898 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.472 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.418 ±(99.9%) 0.004 ms/op
Iteration   1: 2.416 ±(99.9%) 0.004 ms/op
Iteration   2: 2.436 ±(99.9%) 0.004 ms/op
Iteration   3: 2.459 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.437 ±(99.9%) 0.388 ms/op [Average]
  (min, avg, max) = (2.416, 2.437, 2.459), stdev = 0.021
  CI (99.9%): [2.049, 2.825] (assumes normal distribution)


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
# Warmup Iteration   1: 4.644 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.997 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.946 ±(99.9%) 0.006 ms/op
Iteration   1: 2.946 ±(99.9%) 0.005 ms/op
Iteration   2: 2.967 ±(99.9%) 0.005 ms/op
Iteration   3: 2.930 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.948 ±(99.9%) 0.335 ms/op [Average]
  (min, avg, max) = (2.930, 2.948, 2.967), stdev = 0.018
  CI (99.9%): [2.612, 3.283] (assumes normal distribution)


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
# Warmup Iteration   1: 4.184 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.694 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.542 ±(99.9%) 0.006 ms/op
Iteration   1: 2.513 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.919 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.682 ms/op
                 createUser·p0.999:  11.483 ms/op
                 createUser·p0.9999: 13.849 ms/op
                 createUser·p1.00:   14.467 ms/op

Iteration   2: 2.545 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.977 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   4.043 ms/op
                 createUser·p0.999:  9.755 ms/op
                 createUser·p0.9999: 12.869 ms/op
                 createUser·p1.00:   13.173 ms/op

Iteration   3: 2.501 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.800 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.621 ms/op
                 createUser·p0.999:  8.102 ms/op
                 createUser·p0.9999: 11.505 ms/op
                 createUser·p1.00:   17.236 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380519
  mean =      2.520 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 72 
    [ 1.250,  2.500) = 183569 
    [ 2.500,  3.750) = 192949 
    [ 3.750,  5.000) = 3109 
    [ 5.000,  6.250) = 400 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 103 
    [12.500, 13.750) = 94 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.768 ms/op
     p(99.9000) =      8.139 ms/op
     p(99.9900) =     13.401 ms/op
     p(99.9990) =     14.467 ms/op
     p(99.9999) =     17.236 ms/op
    p(100.0000) =     17.236 ms/op


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
# Warmup Iteration   1: 3.596 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.419 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.397 ±(99.9%) 0.005 ms/op
Iteration   1: 2.388 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.971 ms/op
                 existUser·p0.50:   2.437 ms/op
                 existUser·p0.90:   2.896 ms/op
                 existUser·p0.95:   2.994 ms/op
                 existUser·p0.99:   3.584 ms/op
                 existUser·p0.999:  5.940 ms/op
                 existUser·p0.9999: 13.648 ms/op
                 existUser·p1.00:   14.270 ms/op

Iteration   2: 2.394 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.803 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.904 ms/op
                 existUser·p0.95:   3.006 ms/op
                 existUser·p0.99:   3.568 ms/op
                 existUser·p0.999:  6.741 ms/op
                 existUser·p0.9999: 13.091 ms/op
                 existUser·p1.00:   13.795 ms/op

Iteration   3: 2.393 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.027 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.900 ms/op
                 existUser·p0.95:   3.011 ms/op
                 existUser·p0.99:   3.662 ms/op
                 existUser·p0.999:  5.778 ms/op
                 existUser·p0.9999: 11.674 ms/op
                 existUser·p1.00:   12.026 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 401124
  mean =      2.392 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 204274 
    [ 2.500,  3.750) = 193564 
    [ 3.750,  5.000) = 2551 
    [ 5.000,  6.250) = 280 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 129 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.803 ms/op
     p(50.0000) =      2.470 ms/op
     p(90.0000) =      2.900 ms/op
     p(95.0000) =      3.002 ms/op
     p(99.0000) =      3.604 ms/op
     p(99.9000) =      6.399 ms/op
     p(99.9900) =     13.171 ms/op
     p(99.9990) =     14.025 ms/op
     p(99.9999) =     14.270 ms/op
    p(100.0000) =     14.270 ms/op


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
# Warmup Iteration   1: 3.756 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.516 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.488 ±(99.9%) 0.006 ms/op
Iteration   1: 2.464 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.644 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   3.831 ms/op
                 getUser·p0.999:  6.469 ms/op
                 getUser·p0.9999: 13.518 ms/op
                 getUser·p1.00:   14.172 ms/op

Iteration   2: 2.476 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.794 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.953 ms/op
                 getUser·p0.999:  7.636 ms/op
                 getUser·p0.9999: 12.505 ms/op
                 getUser·p1.00:   13.320 ms/op

Iteration   3: 2.467 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.008 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   3.744 ms/op
                 getUser·p0.999:  5.849 ms/op
                 getUser·p0.9999: 10.453 ms/op
                 getUser·p1.00:   10.879 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 388484
  mean =      2.469 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 77 
    [ 1.250,  2.500) = 193710 
    [ 2.500,  3.750) = 190243 
    [ 3.750,  5.000) = 3583 
    [ 5.000,  6.250) = 449 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 91 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 100 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.644 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.838 ms/op
     p(99.9000) =      7.297 ms/op
     p(99.9900) =     13.047 ms/op
     p(99.9990) =     13.848 ms/op
     p(99.9999) =     14.172 ms/op
    p(100.0000) =     14.172 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.787 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 2.992 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.968 ±(99.9%) 0.008 ms/op
Iteration   1: 2.965 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.786 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  9.126 ms/op
                 listUser·p0.9999: 10.837 ms/op
                 listUser·p1.00:   12.681 ms/op

Iteration   2: 2.962 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.911 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.426 ms/op
                 listUser·p0.9999: 11.095 ms/op
                 listUser·p1.00:   11.878 ms/op

Iteration   3: 2.956 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.840 ms/op
                 listUser·p0.50:   2.888 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.238 ms/op
                 listUser·p0.9999: 12.415 ms/op
                 listUser·p1.00:   13.533 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323908
  mean =      2.961 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 169 
    [ 1.250,  2.500) = 101420 
    [ 2.500,  3.750) = 185616 
    [ 3.750,  5.000) = 29767 
    [ 5.000,  6.250) = 5738 
    [ 6.250,  7.500) = 518 
    [ 7.500,  8.750) = 214 
    [ 8.750, 10.000) = 284 
    [10.000, 11.250) = 138 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.786 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =      9.291 ms/op
     p(99.9900) =     11.705 ms/op
     p(99.9990) =     12.735 ms/op
     p(99.9999) =     13.533 ms/op
    p(100.0000) =     13.533 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  13.077 ± 3.479  ops/ms
ClientPb.existUser                       thrpt       3  13.375 ± 3.212  ops/ms
ClientPb.getUser                         thrpt       3  12.850 ± 1.338  ops/ms
ClientPb.listUser                        thrpt       3  10.690 ± 1.402  ops/ms
ClientPb.createUser                       avgt       3   2.476 ± 0.505   ms/op
ClientPb.existUser                        avgt       3   2.396 ± 0.293   ms/op
ClientPb.getUser                          avgt       3   2.437 ± 0.388   ms/op
ClientPb.listUser                         avgt       3   2.948 ± 0.335   ms/op
ClientPb.createUser                     sample  380519   2.520 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.800           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.576           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.768           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.139           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.401           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.236           ms/op
ClientPb.existUser                      sample  401124   2.392 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.803           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.470           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.900           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.604           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.399           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.171           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.270           ms/op
ClientPb.getUser                        sample  388484   2.469 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.644           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.507           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.006           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.133           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.838           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.297           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.047           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.172           ms/op
ClientPb.listUser                       sample  323908   2.961 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.786           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.892           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.830           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.521           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.291           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.705           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.533           ms/op
