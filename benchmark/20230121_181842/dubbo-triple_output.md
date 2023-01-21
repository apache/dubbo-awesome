# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.406 ops/ms
# Warmup Iteration   2: 5.681 ops/ms
# Warmup Iteration   3: 9.240 ops/ms
Iteration   1: 9.422 ops/ms
Iteration   2: 9.548 ops/ms
Iteration   3: 9.732 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.567 ±(99.9%) 2.850 ops/ms [Average]
  (min, avg, max) = (9.422, 9.567, 9.732), stdev = 0.156
  CI (99.9%): [6.718, 12.417] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.583 ops/ms
# Warmup Iteration   2: 9.401 ops/ms
# Warmup Iteration   3: 10.051 ops/ms
Iteration   1: 10.277 ops/ms
Iteration   2: 10.516 ops/ms
Iteration   3: 10.071 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.288 ±(99.9%) 4.060 ops/ms [Average]
  (min, avg, max) = (10.071, 10.288, 10.516), stdev = 0.223
  CI (99.9%): [6.228, 14.348] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.413 ops/ms
# Warmup Iteration   2: 8.552 ops/ms
# Warmup Iteration   3: 9.177 ops/ms
Iteration   1: 9.496 ops/ms
Iteration   2: 9.527 ops/ms
Iteration   3: 9.418 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.480 ±(99.9%) 1.030 ops/ms [Average]
  (min, avg, max) = (9.418, 9.480, 9.527), stdev = 0.056
  CI (99.9%): [8.450, 10.510] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.295 ops/ms
# Warmup Iteration   2: 7.866 ops/ms
# Warmup Iteration   3: 8.240 ops/ms
Iteration   1: 8.626 ops/ms
Iteration   2: 8.436 ops/ms
Iteration   3: 8.422 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.495 ±(99.9%) 2.079 ops/ms [Average]
  (min, avg, max) = (8.422, 8.495, 8.626), stdev = 0.114
  CI (99.9%): [6.416, 10.574] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.354 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.453 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.382 ±(99.9%) 0.003 ms/op
Iteration   1: 3.249 ±(99.9%) 0.006 ms/op
Iteration   2: 3.214 ±(99.9%) 0.009 ms/op
Iteration   3: 3.220 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.228 ±(99.9%) 0.336 ms/op [Average]
  (min, avg, max) = (3.214, 3.228, 3.249), stdev = 0.018
  CI (99.9%): [2.892, 3.563] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.076 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.286 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.195 ±(99.9%) 0.004 ms/op
Iteration   1: 3.185 ±(99.9%) 0.005 ms/op
Iteration   2: 2.988 ±(99.9%) 0.004 ms/op
Iteration   3: 2.993 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.056 ±(99.9%) 2.049 ms/op [Average]
  (min, avg, max) = (2.988, 3.056, 3.185), stdev = 0.112
  CI (99.9%): [1.006, 5.105] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.465 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.514 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.312 ±(99.9%) 0.004 ms/op
Iteration   1: 3.264 ±(99.9%) 0.003 ms/op
Iteration   2: 3.104 ±(99.9%) 0.005 ms/op
Iteration   3: 3.171 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.180 ±(99.9%) 1.463 ms/op [Average]
  (min, avg, max) = (3.104, 3.180, 3.264), stdev = 0.080
  CI (99.9%): [1.716, 4.643] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.876 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.522 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.843 ±(99.9%) 0.006 ms/op
Iteration   1: 3.733 ±(99.9%) 0.006 ms/op
Iteration   2: 3.734 ±(99.9%) 0.006 ms/op
Iteration   3: 3.650 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.706 ±(99.9%) 0.885 ms/op [Average]
  (min, avg, max) = (3.650, 3.706, 3.734), stdev = 0.048
  CI (99.9%): [2.821, 4.590] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.771 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.819 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.316 ±(99.9%) 0.009 ms/op
Iteration   1: 3.288 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.501 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   4.190 ms/op
                 createUser·p0.99:   6.070 ms/op
                 createUser·p0.999:  11.009 ms/op
                 createUser·p0.9999: 23.413 ms/op
                 createUser·p1.00:   24.347 ms/op

Iteration   2: 3.180 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.667 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.338 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   5.390 ms/op
                 createUser·p0.999:  16.014 ms/op
                 createUser·p0.9999: 27.523 ms/op
                 createUser·p1.00:   28.180 ms/op

Iteration   3: 3.203 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.606 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  15.036 ms/op
                 createUser·p0.9999: 21.136 ms/op
                 createUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297670
  mean =      3.223 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22902 
    [ 2.500,  5.000) = 269351 
    [ 5.000,  7.500) = 4532 
    [ 7.500, 10.000) = 398 
    [10.000, 12.500) = 113 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.501 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =     15.248 ms/op
     p(99.9900) =     26.557 ms/op
     p(99.9990) =     27.886 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.416 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.470 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.186 ±(99.9%) 0.007 ms/op
Iteration   1: 3.187 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.319 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   4.088 ms/op
                 existUser·p0.99:   5.333 ms/op
                 existUser·p0.999:  9.732 ms/op
                 existUser·p0.9999: 22.148 ms/op
                 existUser·p1.00:   23.790 ms/op

Iteration   2: 3.187 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.321 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   5.161 ms/op
                 existUser·p0.999:  9.486 ms/op
                 existUser·p0.9999: 23.231 ms/op
                 existUser·p1.00:   24.150 ms/op

Iteration   3: 3.287 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.602 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.756 ms/op
                 existUser·p0.95:   4.067 ms/op
                 existUser·p0.99:   5.906 ms/op
                 existUser·p0.999:  12.005 ms/op
                 existUser·p0.9999: 21.284 ms/op
                 existUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 297898
  mean =      3.219 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22015 
    [ 2.500,  5.000) = 270951 
    [ 5.000,  7.500) = 4177 
    [ 7.500, 10.000) = 407 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 131 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.319 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      4.137 ms/op
     p(99.0000) =      5.374 ms/op
     p(99.9000) =     11.521 ms/op
     p(99.9900) =     22.500 ms/op
     p(99.9990) =     23.693 ms/op
     p(99.9999) =     24.150 ms/op
    p(100.0000) =     24.150 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.655 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.481 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.352 ±(99.9%) 0.011 ms/op
Iteration   1: 3.252 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.130 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   4.121 ms/op
                 getUser·p0.99:   6.210 ms/op
                 getUser·p0.999:  18.031 ms/op
                 getUser·p0.9999: 21.677 ms/op
                 getUser·p1.00:   23.462 ms/op

Iteration   2: 3.263 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.151 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   4.104 ms/op
                 getUser·p0.99:   5.874 ms/op
                 getUser·p0.999:  18.153 ms/op
                 getUser·p0.9999: 27.702 ms/op
                 getUser·p1.00:   28.344 ms/op

Iteration   3: 3.269 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.495 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   4.039 ms/op
                 getUser·p0.99:   5.743 ms/op
                 getUser·p0.999:  10.348 ms/op
                 getUser·p0.9999: 21.594 ms/op
                 getUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294153
  mean =      3.262 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19078 
    [ 2.500,  5.000) = 267040 
    [ 5.000,  7.500) = 6755 
    [ 7.500, 10.000) = 732 
    [10.000, 12.500) = 201 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      4.088 ms/op
     p(99.0000) =      5.939 ms/op
     p(99.9000) =     15.328 ms/op
     p(99.9900) =     27.039 ms/op
     p(99.9990) =     28.057 ms/op
     p(99.9999) =     28.344 ms/op
    p(100.0000) =     28.344 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.871 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 4.127 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.861 ±(99.9%) 0.012 ms/op
Iteration   1: 3.802 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.068 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  14.860 ms/op
                 listUser·p0.9999: 19.038 ms/op
                 listUser·p1.00:   19.137 ms/op

Iteration   2: 3.876 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.929 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  14.270 ms/op
                 listUser·p0.9999: 16.368 ms/op
                 listUser·p1.00:   16.400 ms/op

Iteration   3: 3.885 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.273 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.801 ms/op
                 listUser·p0.99:   7.569 ms/op
                 listUser·p0.999:  13.844 ms/op
                 listUser·p0.9999: 19.063 ms/op
                 listUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 248908
  mean =      3.854 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 58 
    [ 2.500,  3.750) = 95769 
    [ 3.750,  5.000) = 144151 
    [ 5.000,  6.250) = 3908 
    [ 6.250,  7.500) = 3259 
    [ 7.500,  8.750) = 729 
    [ 8.750, 10.000) = 316 
    [10.000, 11.250) = 163 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 141 
    [13.750, 15.000) = 188 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 34 
    [17.500, 18.750) = 37 

  Percentiles, ms/op:
      p(0.0000) =      1.929 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.157 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     14.598 ms/op
     p(99.9900) =     19.038 ms/op
     p(99.9990) =     19.488 ms/op
     p(99.9999) =     19.857 ms/op
    p(100.0000) =     19.857 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.567 ± 2.850  ops/ms
ClientPb.existUser                       thrpt       3  10.288 ± 4.060  ops/ms
ClientPb.getUser                         thrpt       3   9.480 ± 1.030  ops/ms
ClientPb.listUser                        thrpt       3   8.495 ± 2.079  ops/ms
ClientPb.createUser                       avgt       3   3.228 ± 0.336   ms/op
ClientPb.existUser                        avgt       3   3.056 ± 2.049   ms/op
ClientPb.getUser                          avgt       3   3.180 ± 1.463   ms/op
ClientPb.listUser                         avgt       3   3.706 ± 0.885   ms/op
ClientPb.createUser                     sample  297670   3.223 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.501           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.191           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.473           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.838           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.595           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.248           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.557           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.180           ms/op
ClientPb.existUser                      sample  297898   3.219 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.319           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.174           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.645           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.137           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.374           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.521           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.500           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.150           ms/op
ClientPb.getUser                        sample  294153   3.262 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.130           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.723           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.088           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.939           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.328           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.039           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.344           ms/op
ClientPb.listUser                       sample  248908   3.854 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.929           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.777           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.157           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.579           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.021           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.598           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.038           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.857           ms/op
