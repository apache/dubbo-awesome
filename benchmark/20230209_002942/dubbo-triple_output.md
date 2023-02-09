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
# Warmup Iteration   1: 1.248 ops/ms
# Warmup Iteration   2: 3.158 ops/ms
# Warmup Iteration   3: 6.337 ops/ms
Iteration   1: 6.453 ops/ms
Iteration   2: 6.810 ops/ms
Iteration   3: 6.712 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.658 ±(99.9%) 3.366 ops/ms [Average]
  (min, avg, max) = (6.453, 6.658, 6.810), stdev = 0.184
  CI (99.9%): [3.293, 10.024] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.053 ops/ms
# Warmup Iteration   2: 5.934 ops/ms
# Warmup Iteration   3: 6.970 ops/ms
Iteration   1: 7.092 ops/ms
Iteration   2: 7.247 ops/ms
Iteration   3: 6.912 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.083 ±(99.9%) 3.059 ops/ms [Average]
  (min, avg, max) = (6.912, 7.083, 7.247), stdev = 0.168
  CI (99.9%): [4.024, 10.142] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.359 ops/ms
# Warmup Iteration   2: 6.053 ops/ms
# Warmup Iteration   3: 6.898 ops/ms
Iteration   1: 6.782 ops/ms
Iteration   2: 7.015 ops/ms
Iteration   3: 6.771 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.856 ±(99.9%) 2.513 ops/ms [Average]
  (min, avg, max) = (6.771, 6.856, 7.015), stdev = 0.138
  CI (99.9%): [4.343, 9.370] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 1.739 ops/ms
# Warmup Iteration   2: 5.353 ops/ms
# Warmup Iteration   3: 5.812 ops/ms
Iteration   1: 5.804 ops/ms
Iteration   2: 5.901 ops/ms
Iteration   3: 5.895 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.867 ±(99.9%) 0.986 ops/ms [Average]
  (min, avg, max) = (5.804, 5.867, 5.901), stdev = 0.054
  CI (99.9%): [4.881, 6.852] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 14.605 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 5.662 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.051 ±(99.9%) 0.010 ms/op
Iteration   1: 4.879 ±(99.9%) 0.011 ms/op
Iteration   2: 4.881 ±(99.9%) 0.016 ms/op
Iteration   3: 4.927 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.896 ±(99.9%) 0.494 ms/op [Average]
  (min, avg, max) = (4.879, 4.896, 4.927), stdev = 0.027
  CI (99.9%): [4.402, 5.389] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 13.738 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 4.961 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.677 ±(99.9%) 0.015 ms/op
Iteration   1: 4.637 ±(99.9%) 0.007 ms/op
Iteration   2: 4.948 ±(99.9%) 0.010 ms/op
Iteration   3: 4.678 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.754 ±(99.9%) 3.087 ms/op [Average]
  (min, avg, max) = (4.637, 4.754, 4.948), stdev = 0.169
  CI (99.9%): [1.667, 7.842] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 15.283 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 6.374 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.378 ±(99.9%) 0.009 ms/op
Iteration   1: 5.077 ±(99.9%) 0.010 ms/op
Iteration   2: 4.951 ±(99.9%) 0.012 ms/op
Iteration   3: 4.911 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.979 ±(99.9%) 1.582 ms/op [Average]
  (min, avg, max) = (4.911, 4.979, 5.077), stdev = 0.087
  CI (99.9%): [3.398, 6.561] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 15.968 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 6.355 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.630 ±(99.9%) 0.009 ms/op
Iteration   1: 5.629 ±(99.9%) 0.011 ms/op
Iteration   2: 5.232 ±(99.9%) 0.008 ms/op
Iteration   3: 5.423 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.428 ±(99.9%) 3.629 ms/op [Average]
  (min, avg, max) = (5.232, 5.428, 5.629), stdev = 0.199
  CI (99.9%): [1.799, 9.056] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 15.004 ±(99.9%) 0.209 ms/op
# Warmup Iteration   2: 6.491 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.100 ±(99.9%) 0.019 ms/op
Iteration   1: 4.731 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   2.167 ms/op
                 createUser·p0.50:   4.465 ms/op
                 createUser·p0.90:   5.784 ms/op
                 createUser·p0.95:   6.570 ms/op
                 createUser·p0.99:   8.471 ms/op
                 createUser·p0.999:  14.932 ms/op
                 createUser·p0.9999: 26.175 ms/op
                 createUser·p1.00:   27.427 ms/op

Iteration   2: 5.127 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   2.126 ms/op
                 createUser·p0.50:   4.899 ms/op
                 createUser·p0.90:   6.308 ms/op
                 createUser·p0.95:   6.914 ms/op
                 createUser·p0.99:   9.421 ms/op
                 createUser·p0.999:  20.173 ms/op
                 createUser·p0.9999: 25.489 ms/op
                 createUser·p1.00:   26.116 ms/op

Iteration   3: 4.843 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   2.101 ms/op
                 createUser·p0.50:   4.686 ms/op
                 createUser·p0.90:   5.784 ms/op
                 createUser·p0.95:   6.234 ms/op
                 createUser·p0.99:   8.274 ms/op
                 createUser·p0.999:  17.957 ms/op
                 createUser·p0.9999: 30.461 ms/op
                 createUser·p1.00:   32.539 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 195966
  mean =      4.895 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 162 
    [ 2.500,  5.000) = 128380 
    [ 5.000,  7.500) = 62747 
    [ 7.500, 10.000) = 3802 
    [10.000, 12.500) = 507 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 44 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.101 ms/op
     p(50.0000) =      4.669 ms/op
     p(90.0000) =      5.988 ms/op
     p(95.0000) =      6.611 ms/op
     p(99.0000) =      8.700 ms/op
     p(99.9000) =     19.633 ms/op
     p(99.9900) =     28.313 ms/op
     p(99.9990) =     32.256 ms/op
     p(99.9999) =     32.539 ms/op
    p(100.0000) =     32.539 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 13.306 ±(99.9%) 0.174 ms/op
# Warmup Iteration   2: 5.590 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.999 ±(99.9%) 0.016 ms/op
Iteration   1: 4.813 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.118 ms/op
                 existUser·p0.50:   4.547 ms/op
                 existUser·p0.90:   5.841 ms/op
                 existUser·p0.95:   6.889 ms/op
                 existUser·p0.99:   9.421 ms/op
                 existUser·p0.999:  15.547 ms/op
                 existUser·p0.9999: 26.491 ms/op
                 existUser·p1.00:   27.066 ms/op

Iteration   2: 4.800 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   2.093 ms/op
                 existUser·p0.50:   4.596 ms/op
                 existUser·p0.90:   5.849 ms/op
                 existUser·p0.95:   6.373 ms/op
                 existUser·p0.99:   8.052 ms/op
                 existUser·p0.999:  14.942 ms/op
                 existUser·p0.9999: 28.106 ms/op
                 existUser·p1.00:   28.705 ms/op

Iteration   3: 4.691 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.105 ms/op
                 existUser·p0.50:   4.424 ms/op
                 existUser·p0.90:   5.661 ms/op
                 existUser·p0.95:   6.275 ms/op
                 existUser·p0.99:   8.749 ms/op
                 existUser·p0.999:  19.256 ms/op
                 existUser·p0.9999: 39.148 ms/op
                 existUser·p1.00:   40.436 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 201181
  mean =      4.767 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 151772 
    [ 5.000, 10.000) = 48246 
    [10.000, 15.000) = 889 
    [15.000, 20.000) = 82 
    [20.000, 25.000) = 47 
    [25.000, 30.000) = 113 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 27 
    [40.000, 45.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      2.093 ms/op
     p(50.0000) =      4.522 ms/op
     p(90.0000) =      5.775 ms/op
     p(95.0000) =      6.455 ms/op
     p(99.0000) =      8.733 ms/op
     p(99.9000) =     18.573 ms/op
     p(99.9900) =     37.421 ms/op
     p(99.9990) =     40.368 ms/op
     p(99.9999) =     40.436 ms/op
    p(100.0000) =     40.436 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 14.768 ±(99.9%) 0.214 ms/op
# Warmup Iteration   2: 5.597 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.316 ±(99.9%) 0.019 ms/op
Iteration   1: 5.162 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.576 ms/op
                 getUser·p0.50:   4.784 ms/op
                 getUser·p0.90:   6.504 ms/op
                 getUser·p0.95:   7.832 ms/op
                 getUser·p0.99:   10.240 ms/op
                 getUser·p0.999:  16.581 ms/op
                 getUser·p0.9999: 22.433 ms/op
                 getUser·p1.00:   23.036 ms/op

Iteration   2: 5.650 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.466 ms/op
                 getUser·p0.50:   5.177 ms/op
                 getUser·p0.90:   8.102 ms/op
                 getUser·p0.95:   8.815 ms/op
                 getUser·p0.99:   11.502 ms/op
                 getUser·p0.999:  22.290 ms/op
                 getUser·p0.9999: 26.522 ms/op
                 getUser·p1.00:   28.082 ms/op

Iteration   3: 5.047 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.392 ms/op
                 getUser·p0.50:   4.751 ms/op
                 getUser·p0.90:   6.070 ms/op
                 getUser·p0.95:   6.889 ms/op
                 getUser·p0.99:   9.877 ms/op
                 getUser·p0.999:  22.436 ms/op
                 getUser·p0.9999: 27.219 ms/op
                 getUser·p1.00:   28.901 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 181907
  mean =      5.274 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 97920 
    [ 5.000,  7.500) = 70533 
    [ 7.500, 10.000) = 11032 
    [10.000, 12.500) = 1620 
    [12.500, 15.000) = 457 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 45 

  Percentiles, ms/op:
      p(0.0000) =      2.392 ms/op
     p(50.0000) =      4.923 ms/op
     p(90.0000) =      6.676 ms/op
     p(95.0000) =      8.233 ms/op
     p(99.0000) =     10.502 ms/op
     p(99.9000) =     20.775 ms/op
     p(99.9900) =     26.628 ms/op
     p(99.9990) =     28.391 ms/op
     p(99.9999) =     28.901 ms/op
    p(100.0000) =     28.901 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 17.253 ±(99.9%) 0.299 ms/op
# Warmup Iteration   2: 6.484 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 6.145 ±(99.9%) 0.020 ms/op
Iteration   1: 5.724 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.183 ms/op
                 listUser·p0.50:   5.497 ms/op
                 listUser·p0.90:   6.562 ms/op
                 listUser·p0.95:   7.397 ms/op
                 listUser·p0.99:   10.510 ms/op
                 listUser·p0.999:  23.038 ms/op
                 listUser·p0.9999: 26.477 ms/op
                 listUser·p1.00:   27.066 ms/op

Iteration   2: 5.974 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.294 ms/op
                 listUser·p0.50:   5.702 ms/op
                 listUser·p0.90:   7.045 ms/op
                 listUser·p0.95:   8.118 ms/op
                 listUser·p0.99:   11.125 ms/op
                 listUser·p0.999:  27.865 ms/op
                 listUser·p0.9999: 32.537 ms/op
                 listUser·p1.00:   32.997 ms/op

Iteration   3: 5.837 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.976 ms/op
                 listUser·p0.50:   5.661 ms/op
                 listUser·p0.90:   6.808 ms/op
                 listUser·p0.95:   7.601 ms/op
                 listUser·p0.99:   9.630 ms/op
                 listUser·p0.999:  18.192 ms/op
                 listUser·p0.9999: 20.764 ms/op
                 listUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 164296
  mean =      5.843 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 22787 
    [ 5.000,  7.500) = 132170 
    [ 7.500, 10.000) = 7222 
    [10.000, 12.500) = 1343 
    [12.500, 15.000) = 369 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 43 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.976 ms/op
     p(50.0000) =      5.620 ms/op
     p(90.0000) =      6.816 ms/op
     p(95.0000) =      7.700 ms/op
     p(99.0000) =     10.469 ms/op
     p(99.9000) =     22.633 ms/op
     p(99.9900) =     30.778 ms/op
     p(99.9990) =     32.850 ms/op
     p(99.9999) =     32.997 ms/op
    p(100.0000) =     32.997 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.658 ± 3.366  ops/ms
ClientPb.existUser                       thrpt       3   7.083 ± 3.059  ops/ms
ClientPb.getUser                         thrpt       3   6.856 ± 2.513  ops/ms
ClientPb.listUser                        thrpt       3   5.867 ± 0.986  ops/ms
ClientPb.createUser                       avgt       3   4.896 ± 0.494   ms/op
ClientPb.existUser                        avgt       3   4.754 ± 3.087   ms/op
ClientPb.getUser                          avgt       3   4.979 ± 1.582   ms/op
ClientPb.listUser                         avgt       3   5.428 ± 3.629   ms/op
ClientPb.createUser                     sample  195966   4.895 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.101           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.669           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.988           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.611           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.700           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.633           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.313           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.539           ms/op
ClientPb.existUser                      sample  201181   4.767 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.093           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.522           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.775           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.455           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.733           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.573           ms/op
ClientPb.existUser:existUser·p0.9999    sample          37.421           ms/op
ClientPb.existUser:existUser·p1.00      sample          40.436           ms/op
ClientPb.getUser                        sample  181907   5.274 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.392           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.923           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.676           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.233           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.502           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.775           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.628           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.901           ms/op
ClientPb.listUser                       sample  164296   5.843 ± 0.011   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.976           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.620           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.816           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.700           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.469           ms/op
ClientPb.listUser:listUser·p0.999       sample          22.633           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.778           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.997           ms/op
