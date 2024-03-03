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
# Warmup Iteration   1: 5.060 ops/ms
# Warmup Iteration   2: 12.087 ops/ms
# Warmup Iteration   3: 12.566 ops/ms
Iteration   1: 12.730 ops/ms
Iteration   2: 12.861 ops/ms
Iteration   3: 12.794 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.795 ±(99.9%) 1.194 ops/ms [Average]
  (min, avg, max) = (12.730, 12.795, 12.861), stdev = 0.065
  CI (99.9%): [11.601, 13.989] (assumes normal distribution)


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
# Warmup Iteration   1: 8.124 ops/ms
# Warmup Iteration   2: 13.346 ops/ms
# Warmup Iteration   3: 13.318 ops/ms
Iteration   1: 13.196 ops/ms
Iteration   2: 13.410 ops/ms
Iteration   3: 13.244 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.283 ±(99.9%) 2.045 ops/ms [Average]
  (min, avg, max) = (13.196, 13.283, 13.410), stdev = 0.112
  CI (99.9%): [11.239, 15.328] (assumes normal distribution)


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
# Warmup Iteration   1: 7.927 ops/ms
# Warmup Iteration   2: 12.998 ops/ms
# Warmup Iteration   3: 13.084 ops/ms
Iteration   1: 13.179 ops/ms
Iteration   2: 13.007 ops/ms
Iteration   3: 13.063 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.083 ±(99.9%) 1.606 ops/ms [Average]
  (min, avg, max) = (13.007, 13.083, 13.179), stdev = 0.088
  CI (99.9%): [11.477, 14.689] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.473 ops/ms
# Warmup Iteration   2: 10.410 ops/ms
# Warmup Iteration   3: 10.535 ops/ms
Iteration   1: 10.652 ops/ms
Iteration   2: 10.612 ops/ms
Iteration   3: 10.615 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.626 ±(99.9%) 0.399 ops/ms [Average]
  (min, avg, max) = (10.612, 10.626, 10.652), stdev = 0.022
  CI (99.9%): [10.227, 11.026] (assumes normal distribution)


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
# Warmup Iteration   1: 3.998 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.514 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.501 ±(99.9%) 0.004 ms/op
Iteration   1: 2.482 ±(99.9%) 0.004 ms/op
Iteration   2: 2.471 ±(99.9%) 0.004 ms/op
Iteration   3: 2.482 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.479 ±(99.9%) 0.113 ms/op [Average]
  (min, avg, max) = (2.471, 2.479, 2.482), stdev = 0.006
  CI (99.9%): [2.366, 2.591] (assumes normal distribution)


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
# Warmup Iteration   1: 3.686 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.431 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.399 ±(99.9%) 0.004 ms/op
Iteration   1: 2.396 ±(99.9%) 0.004 ms/op
Iteration   2: 2.416 ±(99.9%) 0.005 ms/op
Iteration   3: 2.411 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.408 ±(99.9%) 0.185 ms/op [Average]
  (min, avg, max) = (2.396, 2.408, 2.416), stdev = 0.010
  CI (99.9%): [2.222, 2.593] (assumes normal distribution)


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
# Warmup Iteration   1: 3.662 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.495 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.473 ±(99.9%) 0.004 ms/op
Iteration   1: 2.445 ±(99.9%) 0.005 ms/op
Iteration   2: 2.472 ±(99.9%) 0.005 ms/op
Iteration   3: 2.444 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.454 ±(99.9%) 0.285 ms/op [Average]
  (min, avg, max) = (2.444, 2.454, 2.472), stdev = 0.016
  CI (99.9%): [2.169, 2.738] (assumes normal distribution)


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
# Warmup Iteration   1: 4.736 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.030 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.004 ms/op
Iteration   1: 3.009 ±(99.9%) 0.005 ms/op
Iteration   2: 3.006 ±(99.9%) 0.004 ms/op
Iteration   3: 3.031 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.015 ±(99.9%) 0.249 ms/op [Average]
  (min, avg, max) = (3.006, 3.015, 3.031), stdev = 0.014
  CI (99.9%): [2.767, 3.264] (assumes normal distribution)


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
# Warmup Iteration   1: 4.091 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.598 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.472 ±(99.9%) 0.005 ms/op
Iteration   1: 2.499 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.094 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.863 ms/op
                 createUser·p0.999:  11.601 ms/op
                 createUser·p0.9999: 13.487 ms/op
                 createUser·p1.00:   14.057 ms/op

Iteration   2: 2.481 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.079 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.588 ms/op
                 createUser·p0.999:  6.786 ms/op
                 createUser·p0.9999: 12.208 ms/op
                 createUser·p1.00:   13.140 ms/op

Iteration   3: 2.474 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.884 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.617 ms/op
                 createUser·p0.999:  8.369 ms/op
                 createUser·p0.9999: 9.782 ms/op
                 createUser·p1.00:   9.961 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 386042
  mean =      2.485 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 188284 
    [ 2.500,  3.750) = 194326 
    [ 3.750,  5.000) = 2590 
    [ 5.000,  6.250) = 347 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 111 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 90 
    [12.500, 13.750) = 98 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.884 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.678 ms/op
     p(99.9000) =      8.765 ms/op
     p(99.9900) =     13.189 ms/op
     p(99.9990) =     13.654 ms/op
     p(99.9999) =     14.057 ms/op
    p(100.0000) =     14.057 ms/op


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
# Warmup Iteration   1: 3.555 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.402 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.389 ±(99.9%) 0.005 ms/op
Iteration   1: 2.383 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.024 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.884 ms/op
                 existUser·p0.95:   2.998 ms/op
                 existUser·p0.99:   3.650 ms/op
                 existUser·p0.999:  5.366 ms/op
                 existUser·p0.9999: 14.591 ms/op
                 existUser·p1.00:   15.139 ms/op

Iteration   2: 2.370 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.895 ms/op
                 existUser·p0.50:   2.433 ms/op
                 existUser·p0.90:   2.879 ms/op
                 existUser·p0.95:   2.986 ms/op
                 existUser·p0.99:   3.527 ms/op
                 existUser·p0.999:  6.899 ms/op
                 existUser·p0.9999: 13.296 ms/op
                 existUser·p1.00:   14.696 ms/op

Iteration   3: 2.416 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.788 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.756 ms/op
                 existUser·p0.999:  8.339 ms/op
                 existUser·p0.9999: 11.219 ms/op
                 existUser·p1.00:   12.009 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 401258
  mean =      2.390 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 205164 
    [ 2.500,  3.750) = 192665 
    [ 3.750,  5.000) = 2580 
    [ 5.000,  6.250) = 393 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 55 
    [ 8.750, 10.000) = 109 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.788 ms/op
     p(50.0000) =      2.466 ms/op
     p(90.0000) =      2.904 ms/op
     p(95.0000) =      3.019 ms/op
     p(99.0000) =      3.641 ms/op
     p(99.9000) =      6.850 ms/op
     p(99.9900) =     13.785 ms/op
     p(99.9990) =     15.040 ms/op
     p(99.9999) =     15.139 ms/op
    p(100.0000) =     15.139 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.911 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.527 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.497 ±(99.9%) 0.006 ms/op
Iteration   1: 2.520 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.853 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   4.563 ms/op
                 getUser·p0.999:  11.227 ms/op
                 getUser·p0.9999: 13.473 ms/op
                 getUser·p1.00:   14.500 ms/op

Iteration   2: 2.488 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.941 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.957 ms/op
                 getUser·p0.999:  6.595 ms/op
                 getUser·p0.9999: 12.894 ms/op
                 getUser·p1.00:   13.107 ms/op

Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.961 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.723 ms/op
                 getUser·p0.999:  6.606 ms/op
                 getUser·p0.9999: 11.505 ms/op
                 getUser·p1.00:   12.206 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384182
  mean =      2.496 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 189302 
    [ 2.500,  3.750) = 188712 
    [ 3.750,  5.000) = 4838 
    [ 5.000,  6.250) = 828 
    [ 6.250,  7.500) = 81 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 43 
    [10.000, 11.250) = 115 
    [11.250, 12.500) = 118 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.853 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      4.084 ms/op
     p(99.9000) =      6.803 ms/op
     p(99.9900) =     12.976 ms/op
     p(99.9990) =     13.975 ms/op
     p(99.9999) =     14.500 ms/op
    p(100.0000) =     14.500 ms/op


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
# Warmup Iteration   1: 4.822 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.062 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.043 ±(99.9%) 0.009 ms/op
Iteration   1: 3.031 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.918 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.702 ms/op
                 listUser·p0.999:  9.224 ms/op
                 listUser·p0.9999: 10.732 ms/op
                 listUser·p1.00:   11.649 ms/op

Iteration   2: 3.006 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.782 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  8.325 ms/op
                 listUser·p0.9999: 10.017 ms/op
                 listUser·p1.00:   11.682 ms/op

Iteration   3: 3.009 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.012 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  9.843 ms/op
                 listUser·p0.9999: 12.311 ms/op
                 listUser·p1.00:   13.828 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318079
  mean =      3.015 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 113 
    [ 1.250,  2.500) = 89666 
    [ 2.500,  3.750) = 189603 
    [ 3.750,  5.000) = 31931 
    [ 5.000,  6.250) = 5496 
    [ 6.250,  7.500) = 635 
    [ 7.500,  8.750) = 244 
    [ 8.750, 10.000) = 256 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.782 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =      9.157 ms/op
     p(99.9900) =     11.600 ms/op
     p(99.9990) =     12.853 ms/op
     p(99.9999) =     13.828 ms/op
    p(100.0000) =     13.828 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.795 ± 1.194  ops/ms
ClientPb.existUser                       thrpt       3  13.283 ± 2.045  ops/ms
ClientPb.getUser                         thrpt       3  13.083 ± 1.606  ops/ms
ClientPb.listUser                        thrpt       3  10.626 ± 0.399  ops/ms
ClientPb.createUser                       avgt       3   2.479 ± 0.113   ms/op
ClientPb.existUser                        avgt       3   2.408 ± 0.185   ms/op
ClientPb.getUser                          avgt       3   2.454 ± 0.285   ms/op
ClientPb.listUser                         avgt       3   3.015 ± 0.249   ms/op
ClientPb.createUser                     sample  386042   2.485 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.884           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.556           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.019           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.678           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.765           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.189           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.057           ms/op
ClientPb.existUser                      sample  401258   2.390 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.788           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.466           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.904           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.641           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.850           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.785           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.139           ms/op
ClientPb.getUser                        sample  384182   2.496 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.853           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.531           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.183           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.084           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.803           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.976           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.500           ms/op
ClientPb.listUser                       sample  318079   3.015 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.782           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.875           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.554           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.157           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.600           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.828           ms/op
