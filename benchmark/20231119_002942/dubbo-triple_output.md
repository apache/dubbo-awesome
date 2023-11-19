# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.000 ops/ms
# Warmup Iteration   2: 12.075 ops/ms
# Warmup Iteration   3: 12.301 ops/ms
Iteration   1: 12.482 ops/ms
Iteration   2: 12.603 ops/ms
Iteration   3: 12.659 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.582 ±(99.9%) 1.651 ops/ms [Average]
  (min, avg, max) = (12.482, 12.582, 12.659), stdev = 0.091
  CI (99.9%): [10.931, 14.233] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.081 ops/ms
# Warmup Iteration   2: 13.096 ops/ms
# Warmup Iteration   3: 13.190 ops/ms
Iteration   1: 13.227 ops/ms
Iteration   2: 13.120 ops/ms
Iteration   3: 13.193 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.180 ±(99.9%) 0.999 ops/ms [Average]
  (min, avg, max) = (13.120, 13.180, 13.227), stdev = 0.055
  CI (99.9%): [12.181, 14.179] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.499 ops/ms
# Warmup Iteration   2: 12.897 ops/ms
# Warmup Iteration   3: 12.851 ops/ms
Iteration   1: 12.846 ops/ms
Iteration   2: 12.862 ops/ms
Iteration   3: 12.793 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.834 ±(99.9%) 0.663 ops/ms [Average]
  (min, avg, max) = (12.793, 12.834, 12.862), stdev = 0.036
  CI (99.9%): [12.171, 13.496] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.847 ops/ms
# Warmup Iteration   2: 10.422 ops/ms
# Warmup Iteration   3: 10.664 ops/ms
Iteration   1: 10.522 ops/ms
Iteration   2: 10.597 ops/ms
Iteration   3: 10.695 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.605 ±(99.9%) 1.585 ops/ms [Average]
  (min, avg, max) = (10.522, 10.605, 10.695), stdev = 0.087
  CI (99.9%): [9.020, 12.189] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 3.974 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.600 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.475 ±(99.9%) 0.004 ms/op
Iteration   1: 2.485 ±(99.9%) 0.005 ms/op
Iteration   2: 2.517 ±(99.9%) 0.004 ms/op
Iteration   3: 2.452 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.485 ±(99.9%) 0.595 ms/op [Average]
  (min, avg, max) = (2.452, 2.485, 2.517), stdev = 0.033
  CI (99.9%): [1.890, 3.080] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.704 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.481 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.450 ±(99.9%) 0.004 ms/op
Iteration   1: 2.424 ±(99.9%) 0.004 ms/op
Iteration   2: 2.447 ±(99.9%) 0.004 ms/op
Iteration   3: 2.438 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.436 ±(99.9%) 0.207 ms/op [Average]
  (min, avg, max) = (2.424, 2.436, 2.447), stdev = 0.011
  CI (99.9%): [2.229, 2.643] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.906 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.539 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.526 ±(99.9%) 0.004 ms/op
Iteration   1: 2.497 ±(99.9%) 0.004 ms/op
Iteration   2: 2.485 ±(99.9%) 0.004 ms/op
Iteration   3: 2.474 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.485 ±(99.9%) 0.215 ms/op [Average]
  (min, avg, max) = (2.474, 2.485, 2.497), stdev = 0.012
  CI (99.9%): [2.271, 2.700] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.716 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.094 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.005 ms/op
Iteration   1: 3.034 ±(99.9%) 0.006 ms/op
Iteration   2: 3.056 ±(99.9%) 0.006 ms/op
Iteration   3: 3.052 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.047 ±(99.9%) 0.213 ms/op [Average]
  (min, avg, max) = (3.034, 3.047, 3.056), stdev = 0.012
  CI (99.9%): [2.834, 3.261] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.231 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 2.604 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.006 ms/op
Iteration   1: 2.479 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.887 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   2.994 ms/op
                 createUser·p0.95:   3.109 ms/op
                 createUser·p0.99:   3.768 ms/op
                 createUser·p0.999:  7.031 ms/op
                 createUser·p0.9999: 15.009 ms/op
                 createUser·p1.00:   15.909 ms/op

Iteration   2: 2.453 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.992 ms/op
                 createUser·p0.50:   2.511 ms/op
                 createUser·p0.90:   2.982 ms/op
                 createUser·p0.95:   3.092 ms/op
                 createUser·p0.99:   3.531 ms/op
                 createUser·p0.999:  6.842 ms/op
                 createUser·p0.9999: 12.319 ms/op
                 createUser·p1.00:   12.567 ms/op

Iteration   3: 2.497 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.853 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   4.036 ms/op
                 createUser·p0.999:  8.379 ms/op
                 createUser·p0.9999: 10.525 ms/op
                 createUser·p1.00:   11.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 387297
  mean =      2.476 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 187959 
    [ 2.500,  3.750) = 195358 
    [ 3.750,  5.000) = 2922 
    [ 5.000,  6.250) = 558 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 130 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.853 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.760 ms/op
     p(99.9000) =      8.295 ms/op
     p(99.9900) =     13.783 ms/op
     p(99.9990) =     15.288 ms/op
     p(99.9999) =     15.909 ms/op
    p(100.0000) =     15.909 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.841 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.491 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.006 ms/op
Iteration   1: 2.455 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.869 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.559 ms/op
                 existUser·p0.999:  7.402 ms/op
                 existUser·p0.9999: 16.613 ms/op
                 existUser·p1.00:   17.727 ms/op

Iteration   2: 2.469 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.022 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.588 ms/op
                 existUser·p0.999:  8.036 ms/op
                 existUser·p0.9999: 11.946 ms/op
                 existUser·p1.00:   12.812 ms/op

Iteration   3: 2.464 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.868 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.559 ms/op
                 existUser·p0.999:  5.325 ms/op
                 existUser·p0.9999: 11.846 ms/op
                 existUser·p1.00:   12.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389495
  mean =      2.462 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 25 
    [ 1.250,  2.500) = 191254 
    [ 2.500,  3.750) = 195295 
    [ 3.750,  5.000) = 2224 
    [ 5.000,  6.250) = 302 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.088 ms/op
     p(99.0000) =      3.568 ms/op
     p(99.9000) =      6.480 ms/op
     p(99.9900) =     13.862 ms/op
     p(99.9990) =     17.538 ms/op
     p(99.9999) =     17.727 ms/op
    p(100.0000) =     17.727 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.955 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.600 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.523 ±(99.9%) 0.006 ms/op
Iteration   1: 2.464 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.978 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.088 ms/op
                 getUser·p0.99:   3.629 ms/op
                 getUser·p0.999:  7.187 ms/op
                 getUser·p0.9999: 14.729 ms/op
                 getUser·p1.00:   15.696 ms/op

Iteration   2: 2.498 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.936 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.899 ms/op
                 getUser·p0.999:  9.189 ms/op
                 getUser·p0.9999: 14.303 ms/op
                 getUser·p1.00:   14.615 ms/op

Iteration   3: 2.499 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.013 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  8.424 ms/op
                 getUser·p0.9999: 11.308 ms/op
                 getUser·p1.00:   12.157 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385665
  mean =      2.487 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 72 
    [ 1.250,  2.500) = 191086 
    [ 2.500,  3.750) = 189757 
    [ 3.750,  5.000) = 3561 
    [ 5.000,  6.250) = 760 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 132 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 94 
    [13.750, 15.000) = 54 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.936 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.887 ms/op
     p(99.9000) =      7.187 ms/op
     p(99.9900) =     14.116 ms/op
     p(99.9990) =     15.569 ms/op
     p(99.9999) =     15.696 ms/op
    p(100.0000) =     15.696 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.667 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.067 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.009 ms/op
Iteration   1: 3.035 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.813 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.757 ms/op
                 listUser·p0.999:  8.995 ms/op
                 listUser·p0.9999: 10.469 ms/op
                 listUser·p1.00:   10.863 ms/op

Iteration   2: 3.008 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.910 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.219 ms/op
                 listUser·p0.9999: 11.366 ms/op
                 listUser·p1.00:   11.747 ms/op

Iteration   3: 3.012 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.821 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  9.077 ms/op
                 listUser·p0.9999: 10.869 ms/op
                 listUser·p1.00:   11.551 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317768
  mean =      3.018 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 131 
    [ 1.250,  2.500) = 93048 
    [ 2.500,  3.750) = 183756 
    [ 3.750,  5.000) = 32915 
    [ 5.000,  6.250) = 6454 
    [ 6.250,  7.500) = 753 
    [ 7.500,  8.750) = 288 
    [ 8.750, 10.000) = 273 
    [10.000, 11.250) = 124 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.813 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.436 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =      9.097 ms/op
     p(99.9900) =     11.059 ms/op
     p(99.9990) =     11.682 ms/op
     p(99.9999) =     11.747 ms/op
    p(100.0000) =     11.747 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.582 ± 1.651  ops/ms
ClientPb.existUser                       thrpt       3  13.180 ± 0.999  ops/ms
ClientPb.getUser                         thrpt       3  12.834 ± 0.663  ops/ms
ClientPb.listUser                        thrpt       3  10.605 ± 1.585  ops/ms
ClientPb.createUser                       avgt       3   2.485 ± 0.595   ms/op
ClientPb.existUser                        avgt       3   2.436 ± 0.207   ms/op
ClientPb.getUser                          avgt       3   2.485 ± 0.215   ms/op
ClientPb.listUser                         avgt       3   3.047 ± 0.213   ms/op
ClientPb.createUser                     sample  387297   2.476 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.853           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.560           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.998           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.117           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.760           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.295           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.783           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.909           ms/op
ClientPb.existUser                      sample  389495   2.462 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.868           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.548           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.088           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.568           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.480           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.862           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.727           ms/op
ClientPb.getUser                        sample  385665   2.487 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.936           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.019           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.146           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.887           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.187           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.116           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.696           ms/op
ClientPb.listUser                       sample  317768   3.018 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.813           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.928           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.436           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.685           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.097           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.059           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.747           ms/op
