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
# Warmup Iteration   1: 2.042 ops/ms
# Warmup Iteration   2: 5.987 ops/ms
# Warmup Iteration   3: 8.833 ops/ms
Iteration   1: 9.329 ops/ms
Iteration   2: 9.568 ops/ms
Iteration   3: 9.375 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.424 ±(99.9%) 2.313 ops/ms [Average]
  (min, avg, max) = (9.329, 9.424, 9.568), stdev = 0.127
  CI (99.9%): [7.111, 11.737] (assumes normal distribution)


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
# Warmup Iteration   1: 2.924 ops/ms
# Warmup Iteration   2: 8.954 ops/ms
# Warmup Iteration   3: 9.713 ops/ms
Iteration   1: 9.833 ops/ms
Iteration   2: 9.787 ops/ms
Iteration   3: 9.807 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.809 ±(99.9%) 0.426 ops/ms [Average]
  (min, avg, max) = (9.787, 9.809, 9.833), stdev = 0.023
  CI (99.9%): [9.383, 10.235] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.911 ops/ms
# Warmup Iteration   2: 8.356 ops/ms
# Warmup Iteration   3: 9.157 ops/ms
Iteration   1: 9.610 ops/ms
Iteration   2: 9.452 ops/ms
Iteration   3: 9.146 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.402 ±(99.9%) 4.302 ops/ms [Average]
  (min, avg, max) = (9.146, 9.402, 9.610), stdev = 0.236
  CI (99.9%): [5.100, 13.705] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.778 ops/ms
# Warmup Iteration   2: 6.988 ops/ms
# Warmup Iteration   3: 7.850 ops/ms
Iteration   1: 7.928 ops/ms
Iteration   2: 7.826 ops/ms
Iteration   3: 7.937 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.897 ±(99.9%) 1.122 ops/ms [Average]
  (min, avg, max) = (7.826, 7.897, 7.937), stdev = 0.061
  CI (99.9%): [6.775, 9.018] (assumes normal distribution)


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
# Warmup Iteration   1: 9.947 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.720 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.493 ±(99.9%) 0.007 ms/op
Iteration   1: 3.551 ±(99.9%) 0.003 ms/op
Iteration   2: 3.400 ±(99.9%) 0.009 ms/op
Iteration   3: 3.370 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.440 ±(99.9%) 1.768 ms/op [Average]
  (min, avg, max) = (3.370, 3.440, 3.551), stdev = 0.097
  CI (99.9%): [1.672, 5.209] (assumes normal distribution)


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
# Warmup Iteration   1: 8.980 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.568 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.324 ±(99.9%) 0.010 ms/op
Iteration   1: 3.357 ±(99.9%) 0.005 ms/op
Iteration   2: 3.275 ±(99.9%) 0.012 ms/op
Iteration   3: 3.275 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.302 ±(99.9%) 0.862 ms/op [Average]
  (min, avg, max) = (3.275, 3.302, 3.357), stdev = 0.047
  CI (99.9%): [2.440, 4.164] (assumes normal distribution)


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
# Warmup Iteration   1: 10.399 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.751 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.629 ±(99.9%) 0.004 ms/op
Iteration   1: 3.590 ±(99.9%) 0.005 ms/op
Iteration   2: 3.489 ±(99.9%) 0.006 ms/op
Iteration   3: 3.438 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.505 ±(99.9%) 1.420 ms/op [Average]
  (min, avg, max) = (3.438, 3.505, 3.590), stdev = 0.078
  CI (99.9%): [2.086, 4.925] (assumes normal distribution)


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
# Warmup Iteration   1: 11.396 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.403 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.135 ±(99.9%) 0.006 ms/op
Iteration   1: 4.003 ±(99.9%) 0.012 ms/op
Iteration   2: 3.941 ±(99.9%) 0.011 ms/op
Iteration   3: 3.985 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.976 ±(99.9%) 0.590 ms/op [Average]
  (min, avg, max) = (3.941, 3.976, 4.003), stdev = 0.032
  CI (99.9%): [3.386, 4.567] (assumes normal distribution)


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
# Warmup Iteration   1: 9.474 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.944 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.459 ±(99.9%) 0.010 ms/op
Iteration   1: 3.425 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.094 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.883 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   5.603 ms/op
                 createUser·p0.999:  21.173 ms/op
                 createUser·p0.9999: 29.195 ms/op
                 createUser·p1.00:   30.999 ms/op

Iteration   2: 3.504 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.550 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   4.039 ms/op
                 createUser·p0.95:   4.440 ms/op
                 createUser·p0.99:   6.496 ms/op
                 createUser·p0.999:  22.970 ms/op
                 createUser·p0.9999: 28.158 ms/op
                 createUser·p1.00:   28.508 ms/op

Iteration   3: 3.634 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.335 ms/op
                 createUser·p0.50:   3.432 ms/op
                 createUser·p0.90:   4.461 ms/op
                 createUser·p0.95:   4.899 ms/op
                 createUser·p0.99:   6.119 ms/op
                 createUser·p0.999:  19.005 ms/op
                 createUser·p0.9999: 27.139 ms/op
                 createUser·p1.00:   28.836 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 272767
  mean =      3.519 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6344 
    [ 2.500,  5.000) = 257350 
    [ 5.000,  7.500) = 7915 
    [ 7.500, 10.000) = 651 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 139 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.094 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      4.141 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      6.103 ms/op
     p(99.9000) =     19.595 ms/op
     p(99.9900) =     28.008 ms/op
     p(99.9990) =     30.769 ms/op
     p(99.9999) =     30.999 ms/op
    p(100.0000) =     30.999 ms/op


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
# Warmup Iteration   1: 8.429 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.694 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.556 ±(99.9%) 0.010 ms/op
Iteration   1: 3.505 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.460 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   4.121 ms/op
                 existUser·p0.95:   4.596 ms/op
                 existUser·p0.99:   6.498 ms/op
                 existUser·p0.999:  11.764 ms/op
                 existUser·p0.9999: 22.704 ms/op
                 existUser·p1.00:   23.396 ms/op

Iteration   2: 3.294 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.645 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   5.431 ms/op
                 existUser·p0.999:  15.719 ms/op
                 existUser·p0.9999: 24.881 ms/op
                 existUser·p1.00:   25.362 ms/op

Iteration   3: 3.339 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.499 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   4.051 ms/op
                 existUser·p0.99:   5.784 ms/op
                 existUser·p0.999:  22.832 ms/op
                 existUser·p0.9999: 27.646 ms/op
                 existUser·p1.00:   28.148 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283942
  mean =      3.377 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6942 
    [ 2.500,  5.000) = 270218 
    [ 5.000,  7.500) = 5380 
    [ 7.500, 10.000) = 862 
    [10.000, 12.500) = 216 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 105 
    [25.000, 27.500) = 59 

  Percentiles, ms/op:
      p(0.0000) =      1.460 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      5.874 ms/op
     p(99.9000) =     15.204 ms/op
     p(99.9900) =     25.952 ms/op
     p(99.9990) =     28.087 ms/op
     p(99.9999) =     28.148 ms/op
    p(100.0000) =     28.148 ms/op


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
# Warmup Iteration   1: 8.971 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.814 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.636 ±(99.9%) 0.011 ms/op
Iteration   1: 3.473 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.247 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.153 ms/op
                 getUser·p0.99:   6.324 ms/op
                 getUser·p0.999:  19.592 ms/op
                 getUser·p0.9999: 21.758 ms/op
                 getUser·p1.00:   22.839 ms/op

Iteration   2: 3.616 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.526 ms/op
                 getUser·p0.50:   3.461 ms/op
                 getUser·p0.90:   4.301 ms/op
                 getUser·p0.95:   4.686 ms/op
                 getUser·p0.99:   6.455 ms/op
                 getUser·p0.999:  11.364 ms/op
                 getUser·p0.9999: 24.357 ms/op
                 getUser·p1.00:   26.345 ms/op

Iteration   3: 3.501 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.425 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   3.887 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   6.570 ms/op
                 getUser·p0.999:  24.131 ms/op
                 getUser·p0.9999: 29.777 ms/op
                 getUser·p1.00:   31.490 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271836
  mean =      3.529 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3228 
    [ 2.500,  5.000) = 260435 
    [ 5.000,  7.500) = 6922 
    [ 7.500, 10.000) = 777 
    [10.000, 12.500) = 190 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.247 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      4.018 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      6.373 ms/op
     p(99.9000) =     13.726 ms/op
     p(99.9900) =     27.966 ms/op
     p(99.9990) =     30.408 ms/op
     p(99.9999) =     31.490 ms/op
    p(100.0000) =     31.490 ms/op


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
# Warmup Iteration   1: 11.431 ±(99.9%) 0.160 ms/op
# Warmup Iteration   2: 4.721 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.194 ±(99.9%) 0.015 ms/op
Iteration   1: 4.202 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.064 ms/op
                 listUser·p0.50:   4.043 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   5.161 ms/op
                 listUser·p0.99:   7.986 ms/op
                 listUser·p0.999:  22.267 ms/op
                 listUser·p0.9999: 26.979 ms/op
                 listUser·p1.00:   28.377 ms/op

Iteration   2: 4.010 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.413 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.825 ms/op
                 listUser·p0.99:   7.365 ms/op
                 listUser·p0.999:  16.487 ms/op
                 listUser·p0.9999: 21.433 ms/op
                 listUser·p1.00:   22.151 ms/op

Iteration   3: 4.103 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.841 ms/op
                 listUser·p0.50:   3.969 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.899 ms/op
                 listUser·p0.99:   7.954 ms/op
                 listUser·p0.999:  16.744 ms/op
                 listUser·p0.9999: 20.126 ms/op
                 listUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 233897
  mean =      4.103 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28 
    [ 2.500,  5.000) = 223119 
    [ 5.000,  7.500) = 7896 
    [ 7.500, 10.000) = 1927 
    [10.000, 12.500) = 339 
    [12.500, 15.000) = 157 
    [15.000, 17.500) = 190 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      1.841 ms/op
     p(50.0000) =      3.949 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      7.832 ms/op
     p(99.9000) =     17.564 ms/op
     p(99.9900) =     26.136 ms/op
     p(99.9990) =     28.158 ms/op
     p(99.9999) =     28.377 ms/op
    p(100.0000) =     28.377 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.424 ± 2.313  ops/ms
ClientPb.existUser                       thrpt       3   9.809 ± 0.426  ops/ms
ClientPb.getUser                         thrpt       3   9.402 ± 4.302  ops/ms
ClientPb.listUser                        thrpt       3   7.897 ± 1.122  ops/ms
ClientPb.createUser                       avgt       3   3.440 ± 1.768   ms/op
ClientPb.existUser                        avgt       3   3.302 ± 0.862   ms/op
ClientPb.getUser                          avgt       3   3.505 ± 1.420   ms/op
ClientPb.listUser                         avgt       3   3.976 ± 0.590   ms/op
ClientPb.createUser                     sample  272767   3.519 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.094           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.363           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.141           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.604           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.103           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.595           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.008           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.999           ms/op
ClientPb.existUser                      sample  283942   3.377 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.460           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.248           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.838           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.211           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.874           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.204           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.952           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.148           ms/op
ClientPb.getUser                        sample  271836   3.529 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.247           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.400           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.018           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.465           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.373           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.726           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.966           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.490           ms/op
ClientPb.listUser                       sample  233897   4.103 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.841           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.923           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.832           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.564           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.136           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.377           ms/op
