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
# Warmup Iteration   1: 2.290 ops/ms
# Warmup Iteration   2: 6.049 ops/ms
# Warmup Iteration   3: 9.178 ops/ms
Iteration   1: 9.314 ops/ms
Iteration   2: 9.969 ops/ms
Iteration   3: 9.782 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.688 ±(99.9%) 6.151 ops/ms [Average]
  (min, avg, max) = (9.314, 9.688, 9.969), stdev = 0.337
  CI (99.9%): [3.537, 15.840] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.615 ops/ms
# Warmup Iteration   2: 9.823 ops/ms
# Warmup Iteration   3: 10.387 ops/ms
Iteration   1: 10.280 ops/ms
Iteration   2: 9.978 ops/ms
Iteration   3: 9.774 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.011 ±(99.9%) 4.649 ops/ms [Average]
  (min, avg, max) = (9.774, 10.011, 10.280), stdev = 0.255
  CI (99.9%): [5.362, 14.659] (assumes normal distribution)


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
# Warmup Iteration   1: 3.116 ops/ms
# Warmup Iteration   2: 8.531 ops/ms
# Warmup Iteration   3: 9.481 ops/ms
Iteration   1: 10.030 ops/ms
Iteration   2: 10.132 ops/ms
Iteration   3: 9.893 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.018 ±(99.9%) 2.193 ops/ms [Average]
  (min, avg, max) = (9.893, 10.018, 10.132), stdev = 0.120
  CI (99.9%): [7.825, 12.211] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.086 ops/ms
# Warmup Iteration   2: 7.435 ops/ms
# Warmup Iteration   3: 8.403 ops/ms
Iteration   1: 8.313 ops/ms
Iteration   2: 8.310 ops/ms
Iteration   3: 8.467 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.363 ±(99.9%) 1.642 ops/ms [Average]
  (min, avg, max) = (8.310, 8.363, 8.467), stdev = 0.090
  CI (99.9%): [6.722, 10.005] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.947 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.607 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.446 ±(99.9%) 0.004 ms/op
Iteration   1: 3.183 ±(99.9%) 0.004 ms/op
Iteration   2: 3.252 ±(99.9%) 0.006 ms/op
Iteration   3: 3.350 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.261 ±(99.9%) 1.532 ms/op [Average]
  (min, avg, max) = (3.183, 3.261, 3.350), stdev = 0.084
  CI (99.9%): [1.729, 4.794] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.145 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.389 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.113 ±(99.9%) 0.004 ms/op
Iteration   1: 3.041 ±(99.9%) 0.005 ms/op
Iteration   2: 3.140 ±(99.9%) 0.003 ms/op
Iteration   3: 3.100 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.094 ±(99.9%) 0.909 ms/op [Average]
  (min, avg, max) = (3.041, 3.094, 3.140), stdev = 0.050
  CI (99.9%): [2.185, 4.003] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.697 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.542 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.401 ±(99.9%) 0.002 ms/op
Iteration   1: 3.278 ±(99.9%) 0.003 ms/op
Iteration   2: 3.160 ±(99.9%) 0.007 ms/op
Iteration   3: 3.209 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.216 ±(99.9%) 1.079 ms/op [Average]
  (min, avg, max) = (3.160, 3.216, 3.278), stdev = 0.059
  CI (99.9%): [2.137, 4.294] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.092 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.259 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.841 ±(99.9%) 0.008 ms/op
Iteration   1: 3.741 ±(99.9%) 0.006 ms/op
Iteration   2: 3.713 ±(99.9%) 0.007 ms/op
Iteration   3: 3.742 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.732 ±(99.9%) 0.295 ms/op [Average]
  (min, avg, max) = (3.713, 3.732, 3.742), stdev = 0.016
  CI (99.9%): [3.437, 4.027] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.444 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.539 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.221 ±(99.9%) 0.009 ms/op
Iteration   1: 3.129 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.382 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.731 ms/op
                 createUser·p0.99:   5.276 ms/op
                 createUser·p0.999:  14.451 ms/op
                 createUser·p0.9999: 19.129 ms/op
                 createUser·p1.00:   21.201 ms/op

Iteration   2: 3.113 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.237 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.416 ms/op
                 createUser·p0.95:   3.645 ms/op
                 createUser·p0.99:   4.801 ms/op
                 createUser·p0.999:  19.674 ms/op
                 createUser·p0.9999: 24.043 ms/op
                 createUser·p1.00:   24.773 ms/op

Iteration   3: 3.072 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.839 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.363 ms/op
                 createUser·p0.95:   3.588 ms/op
                 createUser·p0.99:   4.604 ms/op
                 createUser·p0.999:  14.547 ms/op
                 createUser·p0.9999: 18.121 ms/op
                 createUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 308969
  mean =      3.105 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11157 
    [ 2.500,  5.000) = 294742 
    [ 5.000,  7.500) = 2181 
    [ 7.500, 10.000) = 374 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 124 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.839 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.449 ms/op
     p(95.0000) =      3.662 ms/op
     p(99.0000) =      4.983 ms/op
     p(99.9000) =     15.746 ms/op
     p(99.9900) =     23.053 ms/op
     p(99.9990) =     24.508 ms/op
     p(99.9999) =     24.773 ms/op
    p(100.0000) =     24.773 ms/op


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
# Warmup Iteration   1: 7.525 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.396 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.112 ±(99.9%) 0.007 ms/op
Iteration   1: 3.128 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.106 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   4.092 ms/op
                 existUser·p0.99:   5.325 ms/op
                 existUser·p0.999:  9.699 ms/op
                 existUser·p0.9999: 21.259 ms/op
                 existUser·p1.00:   21.922 ms/op

Iteration   2: 3.067 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.962 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.465 ms/op
                 existUser·p0.99:   4.563 ms/op
                 existUser·p0.999:  10.842 ms/op
                 existUser·p0.9999: 21.796 ms/op
                 existUser·p1.00:   22.741 ms/op

Iteration   3: 3.037 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.096 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.252 ms/op
                 existUser·p0.95:   3.420 ms/op
                 existUser·p0.99:   5.136 ms/op
                 existUser·p0.999:  11.665 ms/op
                 existUser·p0.9999: 22.494 ms/op
                 existUser·p1.00:   23.724 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 311860
  mean =      3.077 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13232 
    [ 2.500,  5.000) = 295138 
    [ 5.000,  7.500) = 2705 
    [ 7.500, 10.000) = 369 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 133 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.962 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.314 ms/op
     p(95.0000) =      3.559 ms/op
     p(99.0000) =      5.202 ms/op
     p(99.9000) =     11.190 ms/op
     p(99.9900) =     21.692 ms/op
     p(99.9990) =     23.417 ms/op
     p(99.9999) =     23.724 ms/op
    p(100.0000) =     23.724 ms/op


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
# Warmup Iteration   1: 7.968 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.610 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.161 ±(99.9%) 0.008 ms/op
Iteration   1: 3.284 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.204 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   6.627 ms/op
                 getUser·p0.999:  17.367 ms/op
                 getUser·p0.9999: 21.203 ms/op
                 getUser·p1.00:   22.479 ms/op

Iteration   2: 3.169 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.564 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   5.308 ms/op
                 getUser·p0.999:  19.038 ms/op
                 getUser·p0.9999: 22.086 ms/op
                 getUser·p1.00:   23.462 ms/op

Iteration   3: 3.149 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.182 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.404 ms/op
                 getUser·p0.95:   3.592 ms/op
                 getUser·p0.99:   5.415 ms/op
                 getUser·p0.999:  13.638 ms/op
                 getUser·p0.9999: 18.312 ms/op
                 getUser·p1.00:   18.612 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299893
  mean =      3.200 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12670 
    [ 2.500,  5.000) = 281635 
    [ 5.000,  7.500) = 4460 
    [ 7.500, 10.000) = 563 
    [10.000, 12.500) = 162 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 137 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.564 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =     16.908 ms/op
     p(99.9900) =     21.463 ms/op
     p(99.9990) =     22.643 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


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
# Warmup Iteration   1: 8.144 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.104 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.806 ±(99.9%) 0.012 ms/op
Iteration   1: 3.777 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.772 ms/op
                 listUser·p0.50:   3.609 ms/op
                 listUser·p0.90:   4.100 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   7.430 ms/op
                 listUser·p0.999:  15.397 ms/op
                 listUser·p0.9999: 21.387 ms/op
                 listUser·p1.00:   23.134 ms/op

Iteration   2: 3.734 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.585 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  14.008 ms/op
                 listUser·p0.9999: 15.811 ms/op
                 listUser·p1.00:   15.925 ms/op

Iteration   3: 3.838 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.622 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.170 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   7.633 ms/op
                 listUser·p0.999:  15.254 ms/op
                 listUser·p0.9999: 18.547 ms/op
                 listUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253656
  mean =      3.782 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 114 
    [ 2.500,  5.000) = 244820 
    [ 5.000,  7.500) = 6282 
    [ 7.500, 10.000) = 1606 
    [10.000, 12.500) = 315 
    [12.500, 15.000) = 296 
    [15.000, 17.500) = 154 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.585 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.425 ms/op
     p(99.0000) =      7.455 ms/op
     p(99.9000) =     14.795 ms/op
     p(99.9900) =     19.445 ms/op
     p(99.9990) =     22.699 ms/op
     p(99.9999) =     23.134 ms/op
    p(100.0000) =     23.134 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.688 ± 6.151  ops/ms
ClientPb.existUser                       thrpt       3  10.011 ± 4.649  ops/ms
ClientPb.getUser                         thrpt       3  10.018 ± 2.193  ops/ms
ClientPb.listUser                        thrpt       3   8.363 ± 1.642  ops/ms
ClientPb.createUser                       avgt       3   3.261 ± 1.532   ms/op
ClientPb.existUser                        avgt       3   3.094 ± 0.909   ms/op
ClientPb.getUser                          avgt       3   3.216 ± 1.079   ms/op
ClientPb.listUser                         avgt       3   3.732 ± 0.295   ms/op
ClientPb.createUser                     sample  308969   3.105 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.839           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.002           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.449           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.662           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.983           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.746           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.053           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.773           ms/op
ClientPb.existUser                      sample  311860   3.077 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.962           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.006           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.314           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.559           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.202           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.190           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.692           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.724           ms/op
ClientPb.getUser                        sample  299893   3.200 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.564           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.105           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.527           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.789           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.628           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.908           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.463           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.462           ms/op
ClientPb.listUser                       sample  253656   3.782 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.585           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.633           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.100           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.425           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.455           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.795           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.445           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.134           ms/op
