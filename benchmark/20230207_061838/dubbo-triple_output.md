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
# Warmup Iteration   1: 2.274 ops/ms
# Warmup Iteration   2: 6.218 ops/ms
# Warmup Iteration   3: 8.598 ops/ms
Iteration   1: 9.121 ops/ms
Iteration   2: 9.585 ops/ms
Iteration   3: 9.141 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.282 ±(99.9%) 4.792 ops/ms [Average]
  (min, avg, max) = (9.121, 9.282, 9.585), stdev = 0.263
  CI (99.9%): [4.491, 14.074] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.297 ops/ms
# Warmup Iteration   2: 9.229 ops/ms
# Warmup Iteration   3: 9.628 ops/ms
Iteration   1: 8.871 ops/ms
Iteration   2: 9.023 ops/ms
Iteration   3: 9.785 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.226 ±(99.9%) 8.940 ops/ms [Average]
  (min, avg, max) = (8.871, 9.226, 9.785), stdev = 0.490
  CI (99.9%): [0.286, 18.167] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.296 ops/ms
# Warmup Iteration   2: 8.723 ops/ms
# Warmup Iteration   3: 8.940 ops/ms
Iteration   1: 9.529 ops/ms
Iteration   2: 9.179 ops/ms
Iteration   3: 9.374 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.361 ±(99.9%) 3.198 ops/ms [Average]
  (min, avg, max) = (9.179, 9.361, 9.529), stdev = 0.175
  CI (99.9%): [6.163, 12.559] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.846 ops/ms
# Warmup Iteration   2: 7.292 ops/ms
# Warmup Iteration   3: 7.936 ops/ms
Iteration   1: 8.330 ops/ms
Iteration   2: 8.102 ops/ms
Iteration   3: 8.468 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.300 ±(99.9%) 3.377 ops/ms [Average]
  (min, avg, max) = (8.102, 8.300, 8.468), stdev = 0.185
  CI (99.9%): [4.923, 11.677] (assumes normal distribution)


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
# Warmup Iteration   1: 10.376 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.789 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.542 ±(99.9%) 0.008 ms/op
Iteration   1: 3.468 ±(99.9%) 0.009 ms/op
Iteration   2: 3.590 ±(99.9%) 0.007 ms/op
Iteration   3: 3.577 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.545 ±(99.9%) 1.221 ms/op [Average]
  (min, avg, max) = (3.468, 3.545, 3.590), stdev = 0.067
  CI (99.9%): [2.324, 4.766] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.279 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.648 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.302 ±(99.9%) 0.007 ms/op
Iteration   1: 3.284 ±(99.9%) 0.002 ms/op
Iteration   2: 3.249 ±(99.9%) 0.007 ms/op
Iteration   3: 3.257 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.263 ±(99.9%) 0.328 ms/op [Average]
  (min, avg, max) = (3.249, 3.263, 3.284), stdev = 0.018
  CI (99.9%): [2.936, 3.591] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.175 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.645 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.424 ±(99.9%) 0.007 ms/op
Iteration   1: 3.442 ±(99.9%) 0.006 ms/op
Iteration   2: 3.388 ±(99.9%) 0.006 ms/op
Iteration   3: 3.423 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.418 ±(99.9%) 0.496 ms/op [Average]
  (min, avg, max) = (3.388, 3.418, 3.442), stdev = 0.027
  CI (99.9%): [2.922, 3.913] (assumes normal distribution)


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
# Warmup Iteration   1: 10.508 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.215 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.160 ±(99.9%) 0.010 ms/op
Iteration   1: 3.891 ±(99.9%) 0.011 ms/op
Iteration   2: 3.889 ±(99.9%) 0.013 ms/op
Iteration   3: 3.942 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.907 ±(99.9%) 0.554 ms/op [Average]
  (min, avg, max) = (3.889, 3.907, 3.942), stdev = 0.030
  CI (99.9%): [3.354, 4.461] (assumes normal distribution)


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
# Warmup Iteration   1: 9.136 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.831 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.462 ±(99.9%) 0.011 ms/op
Iteration   1: 3.732 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.716 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   4.743 ms/op
                 createUser·p0.95:   6.111 ms/op
                 createUser·p0.99:   7.487 ms/op
                 createUser·p0.999:  19.431 ms/op
                 createUser·p0.9999: 36.897 ms/op
                 createUser·p1.00:   39.911 ms/op

Iteration   2: 3.451 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.618 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   3.990 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   5.702 ms/op
                 createUser·p0.999:  22.544 ms/op
                 createUser·p0.9999: 25.900 ms/op
                 createUser·p1.00:   26.214 ms/op

Iteration   3: 3.413 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.260 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.899 ms/op
                 createUser·p0.95:   4.178 ms/op
                 createUser·p0.99:   5.652 ms/op
                 createUser·p0.999:  21.836 ms/op
                 createUser·p0.9999: 27.083 ms/op
                 createUser·p1.00:   29.622 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 272123
  mean =      3.527 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5986 
    [ 2.500,  5.000) = 254063 
    [ 5.000,  7.500) = 10639 
    [ 7.500, 10.000) = 935 
    [10.000, 12.500) = 182 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 106 
    [25.000, 27.500) = 98 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.260 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      4.096 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     19.964 ms/op
     p(99.9900) =     36.096 ms/op
     p(99.9990) =     39.610 ms/op
     p(99.9999) =     39.911 ms/op
    p(100.0000) =     39.911 ms/op


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
# Warmup Iteration   1: 8.304 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.549 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.367 ±(99.9%) 0.010 ms/op
Iteration   1: 3.327 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.413 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   4.190 ms/op
                 existUser·p0.99:   5.513 ms/op
                 existUser·p0.999:  8.389 ms/op
                 existUser·p0.9999: 22.812 ms/op
                 existUser·p1.00:   23.331 ms/op

Iteration   2: 3.279 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.364 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   5.562 ms/op
                 existUser·p0.999:  14.683 ms/op
                 existUser·p0.9999: 24.387 ms/op
                 existUser·p1.00:   24.871 ms/op

Iteration   3: 3.286 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.739 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.932 ms/op
                 existUser·p0.99:   6.101 ms/op
                 existUser·p0.999:  18.448 ms/op
                 existUser·p0.9999: 26.706 ms/op
                 existUser·p1.00:   27.361 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290819
  mean =      3.297 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15369 
    [ 2.500,  5.000) = 269496 
    [ 5.000,  7.500) = 5088 
    [ 7.500, 10.000) = 425 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 57 

  Percentiles, ms/op:
      p(0.0000) =      1.364 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.981 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =     16.237 ms/op
     p(99.9900) =     25.753 ms/op
     p(99.9990) =     26.876 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


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
# Warmup Iteration   1: 9.753 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.729 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.478 ±(99.9%) 0.010 ms/op
Iteration   1: 3.432 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.296 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   3.928 ms/op
                 getUser·p0.95:   4.293 ms/op
                 getUser·p0.99:   5.915 ms/op
                 getUser·p0.999:  18.527 ms/op
                 getUser·p0.9999: 21.967 ms/op
                 getUser·p1.00:   23.233 ms/op

Iteration   2: 3.331 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.704 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   5.685 ms/op
                 getUser·p0.999:  19.919 ms/op
                 getUser·p0.9999: 27.827 ms/op
                 getUser·p1.00:   28.672 ms/op

Iteration   3: 3.365 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.352 ms/op
                 getUser·p0.50:   3.244 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   6.029 ms/op
                 getUser·p0.999:  19.694 ms/op
                 getUser·p0.9999: 24.312 ms/op
                 getUser·p1.00:   25.657 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 284502
  mean =      3.375 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4105 
    [ 2.500,  5.000) = 273837 
    [ 5.000,  7.500) = 5660 
    [ 7.500, 10.000) = 443 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 149 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.296 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      5.898 ms/op
     p(99.9000) =     18.629 ms/op
     p(99.9900) =     25.759 ms/op
     p(99.9990) =     28.579 ms/op
     p(99.9999) =     28.672 ms/op
    p(100.0000) =     28.672 ms/op


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
# Warmup Iteration   1: 9.304 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 4.446 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.032 ±(99.9%) 0.013 ms/op
Iteration   1: 4.093 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.610 ms/op
                 listUser·p0.50:   3.965 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.858 ms/op
                 listUser·p0.99:   7.405 ms/op
                 listUser·p0.999:  20.426 ms/op
                 listUser·p0.9999: 24.746 ms/op
                 listUser·p1.00:   25.297 ms/op

Iteration   2: 3.912 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.370 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   7.430 ms/op
                 listUser·p0.999:  14.369 ms/op
                 listUser·p0.9999: 16.531 ms/op
                 listUser·p1.00:   17.695 ms/op

Iteration   3: 4.097 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.085 ms/op
                 listUser·p0.50:   3.965 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   7.488 ms/op
                 listUser·p0.999:  15.778 ms/op
                 listUser·p0.9999: 19.497 ms/op
                 listUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238033
  mean =      4.032 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 63 
    [ 2.500,  5.000) = 228015 
    [ 5.000,  7.500) = 7656 
    [ 7.500, 10.000) = 1394 
    [10.000, 12.500) = 299 
    [12.500, 15.000) = 306 
    [15.000, 17.500) = 142 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.370 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      7.447 ms/op
     p(99.9000) =     15.696 ms/op
     p(99.9900) =     23.658 ms/op
     p(99.9990) =     24.965 ms/op
     p(99.9999) =     25.297 ms/op
    p(100.0000) =     25.297 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.282 ± 4.792  ops/ms
ClientPb.existUser                       thrpt       3   9.226 ± 8.940  ops/ms
ClientPb.getUser                         thrpt       3   9.361 ± 3.198  ops/ms
ClientPb.listUser                        thrpt       3   8.300 ± 3.377  ops/ms
ClientPb.createUser                       avgt       3   3.545 ± 1.221   ms/op
ClientPb.existUser                        avgt       3   3.263 ± 0.328   ms/op
ClientPb.getUser                          avgt       3   3.418 ± 0.496   ms/op
ClientPb.listUser                         avgt       3   3.907 ± 0.554   ms/op
ClientPb.createUser                     sample  272123   3.527 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.260           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.330           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.096           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.710           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.053           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.964           ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.096           ms/op
ClientPb.createUser:createUser·p1.00    sample          39.911           ms/op
ClientPb.existUser                      sample  290819   3.297 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.364           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.244           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.572           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.981           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.677           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.237           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.753           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.361           ms/op
ClientPb.getUser                        sample  284502   3.375 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.296           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.248           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.736           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.014           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.898           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.629           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.759           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.672           ms/op
ClientPb.listUser                       sample  238033   4.032 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.370           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.817           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.447           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.696           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.658           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.297           ms/op
