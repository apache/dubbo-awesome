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
# Warmup Iteration   1: 4.954 ops/ms
# Warmup Iteration   2: 12.043 ops/ms
# Warmup Iteration   3: 12.355 ops/ms
Iteration   1: 12.227 ops/ms
Iteration   2: 12.652 ops/ms
Iteration   3: 12.812 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.564 ±(99.9%) 5.516 ops/ms [Average]
  (min, avg, max) = (12.227, 12.564, 12.812), stdev = 0.302
  CI (99.9%): [7.048, 18.080] (assumes normal distribution)


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
# Warmup Iteration   1: 8.283 ops/ms
# Warmup Iteration   2: 12.933 ops/ms
# Warmup Iteration   3: 13.164 ops/ms
Iteration   1: 13.213 ops/ms
Iteration   2: 12.958 ops/ms
Iteration   3: 12.846 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.006 ±(99.9%) 3.432 ops/ms [Average]
  (min, avg, max) = (12.846, 13.006, 13.213), stdev = 0.188
  CI (99.9%): [9.574, 16.438] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.482 ops/ms
# Warmup Iteration   2: 12.623 ops/ms
# Warmup Iteration   3: 12.846 ops/ms
Iteration   1: 12.766 ops/ms
Iteration   2: 12.725 ops/ms
Iteration   3: 12.700 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.730 ±(99.9%) 0.611 ops/ms [Average]
  (min, avg, max) = (12.700, 12.730, 12.766), stdev = 0.033
  CI (99.9%): [12.120, 13.341] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.675 ops/ms
# Warmup Iteration   2: 10.571 ops/ms
# Warmup Iteration   3: 10.782 ops/ms
Iteration   1: 10.834 ops/ms
Iteration   2: 10.888 ops/ms
Iteration   3: 10.793 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.839 ±(99.9%) 0.866 ops/ms [Average]
  (min, avg, max) = (10.793, 10.839, 10.888), stdev = 0.047
  CI (99.9%): [9.973, 11.705] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.033 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.602 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.003 ms/op
Iteration   1: 2.503 ±(99.9%) 0.004 ms/op
Iteration   2: 2.542 ±(99.9%) 0.003 ms/op
Iteration   3: 2.525 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.523 ±(99.9%) 0.358 ms/op [Average]
  (min, avg, max) = (2.503, 2.523, 2.542), stdev = 0.020
  CI (99.9%): [2.165, 2.882] (assumes normal distribution)


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
# Warmup Iteration   1: 3.677 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.484 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.478 ±(99.9%) 0.004 ms/op
Iteration   1: 2.471 ±(99.9%) 0.004 ms/op
Iteration   2: 2.519 ±(99.9%) 0.003 ms/op
Iteration   3: 2.499 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.496 ±(99.9%) 0.439 ms/op [Average]
  (min, avg, max) = (2.471, 2.496, 2.519), stdev = 0.024
  CI (99.9%): [2.057, 2.935] (assumes normal distribution)


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
# Warmup Iteration   1: 3.851 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.500 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.476 ±(99.9%) 0.004 ms/op
Iteration   1: 2.489 ±(99.9%) 0.004 ms/op
Iteration   2: 2.480 ±(99.9%) 0.004 ms/op
Iteration   3: 2.509 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.493 ±(99.9%) 0.271 ms/op [Average]
  (min, avg, max) = (2.480, 2.493, 2.509), stdev = 0.015
  CI (99.9%): [2.221, 2.764] (assumes normal distribution)


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
# Warmup Iteration   1: 4.527 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.977 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.966 ±(99.9%) 0.005 ms/op
Iteration   1: 2.978 ±(99.9%) 0.005 ms/op
Iteration   2: 2.957 ±(99.9%) 0.006 ms/op
Iteration   3: 2.971 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.969 ±(99.9%) 0.196 ms/op [Average]
  (min, avg, max) = (2.957, 2.969, 2.978), stdev = 0.011
  CI (99.9%): [2.773, 3.165] (assumes normal distribution)


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
# Warmup Iteration   1: 3.922 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.592 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.467 ±(99.9%) 0.005 ms/op
Iteration   1: 2.474 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.991 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   2.994 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   3.813 ms/op
                 createUser·p0.999:  7.542 ms/op
                 createUser·p0.9999: 13.372 ms/op
                 createUser·p1.00:   13.926 ms/op

Iteration   2: 2.472 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.652 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   2.998 ms/op
                 createUser·p0.95:   3.117 ms/op
                 createUser·p0.99:   3.686 ms/op
                 createUser·p0.999:  6.793 ms/op
                 createUser·p0.9999: 12.289 ms/op
                 createUser·p1.00:   13.156 ms/op

Iteration   3: 2.469 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.968 ms/op
                 createUser·p0.50:   2.523 ms/op
                 createUser·p0.90:   2.998 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.781 ms/op
                 createUser·p0.999:  8.755 ms/op
                 createUser·p0.9999: 11.305 ms/op
                 createUser·p1.00:   11.977 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 388173
  mean =      2.471 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 190421 
    [ 2.500,  3.750) = 193803 
    [ 3.750,  5.000) = 3060 
    [ 5.000,  6.250) = 385 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 103 
    [10.000, 11.250) = 97 
    [11.250, 12.500) = 110 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.652 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.752 ms/op
     p(99.9000) =      8.609 ms/op
     p(99.9900) =     13.042 ms/op
     p(99.9990) =     13.717 ms/op
     p(99.9999) =     13.926 ms/op
    p(100.0000) =     13.926 ms/op


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
# Warmup Iteration   1: 3.640 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.450 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.441 ±(99.9%) 0.005 ms/op
Iteration   1: 2.416 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.823 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.408 ms/op
                 existUser·p0.999:  5.169 ms/op
                 existUser·p0.9999: 14.369 ms/op
                 existUser·p1.00:   14.664 ms/op

Iteration   2: 2.463 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.053 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.760 ms/op
                 existUser·p0.999:  7.483 ms/op
                 existUser·p0.9999: 12.027 ms/op
                 existUser·p1.00:   12.747 ms/op

Iteration   3: 2.447 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.918 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.670 ms/op
                 existUser·p0.999:  6.486 ms/op
                 existUser·p0.9999: 11.664 ms/op
                 existUser·p1.00:   12.026 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392688
  mean =      2.442 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 196049 
    [ 2.500,  3.750) = 193483 
    [ 3.750,  5.000) = 2453 
    [ 5.000,  6.250) = 258 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 45 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 103 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.823 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.088 ms/op
     p(99.0000) =      3.600 ms/op
     p(99.9000) =      6.299 ms/op
     p(99.9900) =     13.517 ms/op
     p(99.9990) =     14.550 ms/op
     p(99.9999) =     14.664 ms/op
    p(100.0000) =     14.664 ms/op


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
# Warmup Iteration   1: 3.813 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.510 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.006 ms/op
Iteration   1: 2.468 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.876 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.895 ms/op
                 getUser·p0.999:  6.240 ms/op
                 getUser·p0.9999: 13.682 ms/op
                 getUser·p1.00:   14.598 ms/op

Iteration   2: 2.459 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.956 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   2.982 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  6.580 ms/op
                 getUser·p0.9999: 12.452 ms/op
                 getUser·p1.00:   12.993 ms/op

Iteration   3: 2.449 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.700 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   2.986 ms/op
                 getUser·p0.95:   3.092 ms/op
                 getUser·p0.99:   3.611 ms/op
                 getUser·p0.999:  6.246 ms/op
                 getUser·p0.9999: 10.551 ms/op
                 getUser·p1.00:   11.059 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 390055
  mean =      2.459 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 72 
    [ 1.250,  2.500) = 195345 
    [ 2.500,  3.750) = 189897 
    [ 3.750,  5.000) = 3416 
    [ 5.000,  6.250) = 932 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 153 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 92 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.700 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.889 ms/op
     p(99.9000) =      6.365 ms/op
     p(99.9900) =     13.337 ms/op
     p(99.9990) =     14.041 ms/op
     p(99.9999) =     14.598 ms/op
    p(100.0000) =     14.598 ms/op


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
# Warmup Iteration   1: 4.649 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.066 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.009 ms/op
Iteration   1: 3.012 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.596 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  9.075 ms/op
                 listUser·p0.9999: 11.492 ms/op
                 listUser·p1.00:   12.042 ms/op

Iteration   2: 2.937 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   0.962 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.736 ms/op
                 listUser·p0.95:   4.166 ms/op
                 listUser·p0.99:   5.300 ms/op
                 listUser·p0.999:  9.996 ms/op
                 listUser·p0.9999: 11.684 ms/op
                 listUser·p1.00:   13.058 ms/op

Iteration   3: 2.970 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.707 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.813 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  9.406 ms/op
                 listUser·p0.9999: 10.725 ms/op
                 listUser·p1.00:   11.649 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322634
  mean =      2.973 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 138 
    [ 1.250,  2.500) = 97914 
    [ 2.500,  3.750) = 188657 
    [ 3.750,  5.000) = 29560 
    [ 5.000,  6.250) = 5131 
    [ 6.250,  7.500) = 555 
    [ 7.500,  8.750) = 239 
    [ 8.750, 10.000) = 224 
    [10.000, 11.250) = 169 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.596 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =      9.273 ms/op
     p(99.9900) =     11.448 ms/op
     p(99.9990) =     12.031 ms/op
     p(99.9999) =     13.058 ms/op
    p(100.0000) =     13.058 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.564 ± 5.516  ops/ms
ClientPb.existUser                       thrpt       3  13.006 ± 3.432  ops/ms
ClientPb.getUser                         thrpt       3  12.730 ± 0.611  ops/ms
ClientPb.listUser                        thrpt       3  10.839 ± 0.866  ops/ms
ClientPb.createUser                       avgt       3   2.523 ± 0.358   ms/op
ClientPb.existUser                        avgt       3   2.496 ± 0.439   ms/op
ClientPb.getUser                          avgt       3   2.493 ± 0.271   ms/op
ClientPb.listUser                         avgt       3   2.969 ± 0.196   ms/op
ClientPb.createUser                     sample  388173   2.471 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.652           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.535           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.998           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.117           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.752           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.609           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.042           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.926           ms/op
ClientPb.existUser                      sample  392688   2.442 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.823           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.503           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.088           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.600           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.299           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.517           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.664           ms/op
ClientPb.getUser                        sample  390055   2.459 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.700           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.494           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.990           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.117           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.889           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.365           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.337           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.598           ms/op
ClientPb.listUser                       sample  322634   2.973 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.596           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.916           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.822           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.464           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.273           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.448           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.058           ms/op
