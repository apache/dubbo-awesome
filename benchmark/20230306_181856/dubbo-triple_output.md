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
# Warmup Iteration   1: 1.737 ops/ms
# Warmup Iteration   2: 4.536 ops/ms
# Warmup Iteration   3: 7.639 ops/ms
Iteration   1: 8.525 ops/ms
Iteration   2: 8.870 ops/ms
Iteration   3: 8.979 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.791 ±(99.9%) 4.327 ops/ms [Average]
  (min, avg, max) = (8.525, 8.791, 8.979), stdev = 0.237
  CI (99.9%): [4.464, 13.118] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.639 ops/ms
# Warmup Iteration   2: 7.062 ops/ms
# Warmup Iteration   3: 8.774 ops/ms
Iteration   1: 9.312 ops/ms
Iteration   2: 9.724 ops/ms
Iteration   3: 9.114 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.383 ±(99.9%) 5.681 ops/ms [Average]
  (min, avg, max) = (9.114, 9.383, 9.724), stdev = 0.311
  CI (99.9%): [3.702, 15.064] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.343 ops/ms
# Warmup Iteration   2: 7.230 ops/ms
# Warmup Iteration   3: 8.914 ops/ms
Iteration   1: 8.874 ops/ms
Iteration   2: 8.880 ops/ms
Iteration   3: 9.317 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.024 ±(99.9%) 4.632 ops/ms [Average]
  (min, avg, max) = (8.874, 9.024, 9.317), stdev = 0.254
  CI (99.9%): [4.391, 13.656] (assumes normal distribution)


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
# Warmup Iteration   1: 2.278 ops/ms
# Warmup Iteration   2: 6.819 ops/ms
# Warmup Iteration   3: 7.489 ops/ms
Iteration   1: 7.488 ops/ms
Iteration   2: 7.662 ops/ms
Iteration   3: 7.856 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.669 ±(99.9%) 3.359 ops/ms [Average]
  (min, avg, max) = (7.488, 7.669, 7.856), stdev = 0.184
  CI (99.9%): [4.309, 11.028] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 12.456 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.129 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.783 ±(99.9%) 0.008 ms/op
Iteration   1: 3.634 ±(99.9%) 0.006 ms/op
Iteration   2: 3.521 ±(99.9%) 0.009 ms/op
Iteration   3: 3.518 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.558 ±(99.9%) 1.202 ms/op [Average]
  (min, avg, max) = (3.518, 3.558, 3.634), stdev = 0.066
  CI (99.9%): [2.356, 4.760] (assumes normal distribution)


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
# Warmup Iteration   1: 11.546 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.884 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.618 ±(99.9%) 0.003 ms/op
Iteration   1: 3.430 ±(99.9%) 0.007 ms/op
Iteration   2: 3.461 ±(99.9%) 0.003 ms/op
Iteration   3: 3.491 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.461 ±(99.9%) 0.553 ms/op [Average]
  (min, avg, max) = (3.430, 3.461, 3.491), stdev = 0.030
  CI (99.9%): [2.907, 4.014] (assumes normal distribution)


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
# Warmup Iteration   1: 13.210 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.317 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.708 ±(99.9%) 0.009 ms/op
Iteration   1: 3.721 ±(99.9%) 0.004 ms/op
Iteration   2: 3.619 ±(99.9%) 0.009 ms/op
Iteration   3: 3.611 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.650 ±(99.9%) 1.122 ms/op [Average]
  (min, avg, max) = (3.611, 3.650, 3.721), stdev = 0.062
  CI (99.9%): [2.528, 4.773] (assumes normal distribution)


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
# Warmup Iteration   1: 14.672 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.984 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.443 ±(99.9%) 0.007 ms/op
Iteration   1: 4.221 ±(99.9%) 0.014 ms/op
Iteration   2: 4.292 ±(99.9%) 0.012 ms/op
Iteration   3: 4.065 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.193 ±(99.9%) 2.115 ms/op [Average]
  (min, avg, max) = (4.065, 4.193, 4.292), stdev = 0.116
  CI (99.9%): [2.078, 6.308] (assumes normal distribution)


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
# Warmup Iteration   1: 10.205 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 4.253 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.681 ±(99.9%) 0.013 ms/op
Iteration   1: 3.991 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.425 ms/op
                 createUser·p0.50:   3.617 ms/op
                 createUser·p0.90:   5.210 ms/op
                 createUser·p0.95:   6.832 ms/op
                 createUser·p0.99:   8.421 ms/op
                 createUser·p0.999:  25.649 ms/op
                 createUser·p0.9999: 28.540 ms/op
                 createUser·p1.00:   29.065 ms/op

Iteration   2: 3.459 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.804 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   4.080 ms/op
                 createUser·p0.99:   5.833 ms/op
                 createUser·p0.999:  27.708 ms/op
                 createUser·p0.9999: 35.800 ms/op
                 createUser·p1.00:   37.880 ms/op

Iteration   3: 3.618 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.315 ms/op
                 createUser·p0.50:   3.424 ms/op
                 createUser·p0.90:   4.071 ms/op
                 createUser·p0.95:   4.432 ms/op
                 createUser·p0.99:   7.085 ms/op
                 createUser·p0.999:  24.071 ms/op
                 createUser·p0.9999: 37.290 ms/op
                 createUser·p1.00:   41.419 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 260962
  mean =      3.676 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 248463 
    [ 5.000, 10.000) = 11643 
    [10.000, 15.000) = 440 
    [15.000, 20.000) = 102 
    [20.000, 25.000) = 51 
    [25.000, 30.000) = 193 
    [30.000, 35.000) = 18 
    [35.000, 40.000) = 45 
    [40.000, 45.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.315 ms/op
     p(50.0000) =      3.437 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      7.520 ms/op
     p(99.9000) =     25.068 ms/op
     p(99.9900) =     35.907 ms/op
     p(99.9990) =     41.379 ms/op
     p(99.9999) =     41.419 ms/op
    p(100.0000) =     41.419 ms/op


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
# Warmup Iteration   1: 11.472 ±(99.9%) 0.194 ms/op
# Warmup Iteration   2: 3.991 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.566 ±(99.9%) 0.012 ms/op
Iteration   1: 3.421 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.487 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.777 ms/op
                 existUser·p0.95:   4.432 ms/op
                 existUser·p0.99:   6.070 ms/op
                 existUser·p0.999:  23.053 ms/op
                 existUser·p0.9999: 30.594 ms/op
                 existUser·p1.00:   31.064 ms/op

Iteration   2: 3.387 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.665 ms/op
                 existUser·p0.50:   3.342 ms/op
                 existUser·p0.90:   3.641 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   5.693 ms/op
                 existUser·p0.999:  11.174 ms/op
                 existUser·p0.9999: 32.604 ms/op
                 existUser·p1.00:   33.620 ms/op

Iteration   3: 3.505 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.655 ms/op
                 existUser·p0.50:   3.363 ms/op
                 existUser·p0.90:   3.936 ms/op
                 existUser·p0.95:   4.522 ms/op
                 existUser·p0.99:   6.819 ms/op
                 existUser·p0.999:  28.983 ms/op
                 existUser·p0.9999: 37.356 ms/op
                 existUser·p1.00:   38.404 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 279165
  mean =      3.437 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6280 
    [ 2.500,  5.000) = 265595 
    [ 5.000,  7.500) = 5833 
    [ 7.500, 10.000) = 980 
    [10.000, 12.500) = 216 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 91 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.487 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      6.169 ms/op
     p(99.9000) =     11.944 ms/op
     p(99.9900) =     35.084 ms/op
     p(99.9990) =     38.027 ms/op
     p(99.9999) =     38.404 ms/op
    p(100.0000) =     38.404 ms/op


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
# Warmup Iteration   1: 13.619 ±(99.9%) 0.167 ms/op
# Warmup Iteration   2: 4.411 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.918 ±(99.9%) 0.015 ms/op
Iteration   1: 3.954 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.839 ms/op
                 getUser·p0.50:   3.650 ms/op
                 getUser·p0.90:   5.128 ms/op
                 getUser·p0.95:   6.078 ms/op
                 getUser·p0.99:   8.372 ms/op
                 getUser·p0.999:  17.924 ms/op
                 getUser·p0.9999: 26.932 ms/op
                 getUser·p1.00:   28.541 ms/op

Iteration   2: 3.479 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.511 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.010 ms/op
                 getUser·p0.99:   5.931 ms/op
                 getUser·p0.999:  26.603 ms/op
                 getUser·p0.9999: 29.452 ms/op
                 getUser·p1.00:   29.819 ms/op

Iteration   3: 3.518 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.081 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   3.973 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   6.177 ms/op
                 getUser·p0.999:  26.959 ms/op
                 getUser·p0.9999: 32.763 ms/op
                 getUser·p1.00:   33.358 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 263832
  mean =      3.638 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2237 
    [ 2.500,  5.000) = 248527 
    [ 5.000,  7.500) = 10613 
    [ 7.500, 10.000) = 1825 
    [10.000, 12.500) = 281 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 74 
    [27.500, 30.000) = 103 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.081 ms/op
     p(50.0000) =      3.449 ms/op
     p(90.0000) =      4.112 ms/op
     p(95.0000) =      4.989 ms/op
     p(99.0000) =      7.430 ms/op
     p(99.9000) =     18.683 ms/op
     p(99.9900) =     31.019 ms/op
     p(99.9990) =     33.239 ms/op
     p(99.9999) =     33.358 ms/op
    p(100.0000) =     33.358 ms/op


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
# Warmup Iteration   1: 12.394 ±(99.9%) 0.183 ms/op
# Warmup Iteration   2: 5.135 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.467 ±(99.9%) 0.017 ms/op
Iteration   1: 4.361 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.400 ms/op
                 listUser·p0.50:   4.174 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   5.235 ms/op
                 listUser·p0.99:   8.927 ms/op
                 listUser·p0.999:  25.944 ms/op
                 listUser·p0.9999: 30.463 ms/op
                 listUser·p1.00:   33.391 ms/op

Iteration   2: 4.371 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.985 ms/op
                 listUser·p0.50:   4.211 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.038 ms/op
                 listUser·p0.99:   8.864 ms/op
                 listUser·p0.999:  19.985 ms/op
                 listUser·p0.9999: 25.330 ms/op
                 listUser·p1.00:   26.149 ms/op

Iteration   3: 4.274 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.367 ms/op
                 listUser·p0.50:   4.178 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   7.660 ms/op
                 listUser·p0.999:  16.335 ms/op
                 listUser·p0.9999: 20.613 ms/op
                 listUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 221206
  mean =      4.335 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29 
    [ 2.500,  5.000) = 210214 
    [ 5.000,  7.500) = 7395 
    [ 7.500, 10.000) = 2376 
    [10.000, 12.500) = 502 
    [12.500, 15.000) = 135 
    [15.000, 17.500) = 173 
    [17.500, 20.000) = 159 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.985 ms/op
     p(50.0000) =      4.186 ms/op
     p(90.0000) =      4.661 ms/op
     p(95.0000) =      4.997 ms/op
     p(99.0000) =      8.520 ms/op
     p(99.9000) =     20.080 ms/op
     p(99.9900) =     29.377 ms/op
     p(99.9990) =     32.820 ms/op
     p(99.9999) =     33.391 ms/op
    p(100.0000) =     33.391 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.791 ± 4.327  ops/ms
ClientPb.existUser                       thrpt       3   9.383 ± 5.681  ops/ms
ClientPb.getUser                         thrpt       3   9.024 ± 4.632  ops/ms
ClientPb.listUser                        thrpt       3   7.669 ± 3.359  ops/ms
ClientPb.createUser                       avgt       3   3.558 ± 1.202   ms/op
ClientPb.existUser                        avgt       3   3.461 ± 0.553   ms/op
ClientPb.getUser                          avgt       3   3.650 ± 1.122   ms/op
ClientPb.listUser                         avgt       3   4.193 ± 2.115   ms/op
ClientPb.createUser                     sample  260962   3.676 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.315           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.437           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.190           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.891           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.520           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.068           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.907           ms/op
ClientPb.createUser:createUser·p1.00    sample          41.419           ms/op
ClientPb.existUser                      sample  279165   3.437 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.487           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.326           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.764           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.219           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.169           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.944           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.084           ms/op
ClientPb.existUser:existUser·p1.00      sample          38.404           ms/op
ClientPb.getUser                        sample  263832   3.638 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.081           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.449           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.112           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.989           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.430           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.683           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.019           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.358           ms/op
ClientPb.listUser                       sample  221206   4.335 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.985           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.186           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.661           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.997           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.520           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.080           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.377           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.391           ms/op
