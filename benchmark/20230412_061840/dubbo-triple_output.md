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
# Warmup Iteration   1: 2.072 ops/ms
# Warmup Iteration   2: 5.136 ops/ms
# Warmup Iteration   3: 8.626 ops/ms
Iteration   1: 9.510 ops/ms
Iteration   2: 9.388 ops/ms
Iteration   3: 9.358 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.419 ±(99.9%) 1.465 ops/ms [Average]
  (min, avg, max) = (9.358, 9.419, 9.510), stdev = 0.080
  CI (99.9%): [7.954, 10.884] (assumes normal distribution)


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
# Warmup Iteration   1: 3.193 ops/ms
# Warmup Iteration   2: 8.976 ops/ms
# Warmup Iteration   3: 9.836 ops/ms
Iteration   1: 9.862 ops/ms
Iteration   2: 10.034 ops/ms
Iteration   3: 9.805 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.900 ±(99.9%) 2.173 ops/ms [Average]
  (min, avg, max) = (9.805, 9.900, 10.034), stdev = 0.119
  CI (99.9%): [7.727, 12.073] (assumes normal distribution)


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
# Warmup Iteration   1: 3.286 ops/ms
# Warmup Iteration   2: 8.393 ops/ms
# Warmup Iteration   3: 9.610 ops/ms
Iteration   1: 9.299 ops/ms
Iteration   2: 9.555 ops/ms
Iteration   3: 9.506 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.453 ±(99.9%) 2.485 ops/ms [Average]
  (min, avg, max) = (9.299, 9.453, 9.555), stdev = 0.136
  CI (99.9%): [6.968, 11.938] (assumes normal distribution)


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
# Warmup Iteration   1: 2.716 ops/ms
# Warmup Iteration   2: 7.427 ops/ms
# Warmup Iteration   3: 8.015 ops/ms
Iteration   1: 7.873 ops/ms
Iteration   2: 7.729 ops/ms
Iteration   3: 8.163 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.921 ±(99.9%) 4.037 ops/ms [Average]
  (min, avg, max) = (7.729, 7.921, 8.163), stdev = 0.221
  CI (99.9%): [3.884, 11.959] (assumes normal distribution)


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
# Warmup Iteration   1: 8.443 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.913 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.575 ±(99.9%) 0.010 ms/op
Iteration   1: 3.562 ±(99.9%) 0.006 ms/op
Iteration   2: 3.446 ±(99.9%) 0.004 ms/op
Iteration   3: 3.463 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.490 ±(99.9%) 1.144 ms/op [Average]
  (min, avg, max) = (3.446, 3.490, 3.562), stdev = 0.063
  CI (99.9%): [2.346, 4.635] (assumes normal distribution)


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
# Warmup Iteration   1: 9.165 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.553 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.830 ±(99.9%) 0.006 ms/op
Iteration   1: 3.271 ±(99.9%) 0.003 ms/op
Iteration   2: 3.284 ±(99.9%) 0.005 ms/op
Iteration   3: 3.225 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.260 ±(99.9%) 0.569 ms/op [Average]
  (min, avg, max) = (3.225, 3.260, 3.284), stdev = 0.031
  CI (99.9%): [2.691, 3.829] (assumes normal distribution)


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
# Warmup Iteration   1: 9.970 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.656 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.656 ±(99.9%) 0.005 ms/op
Iteration   1: 3.537 ±(99.9%) 0.004 ms/op
Iteration   2: 3.402 ±(99.9%) 0.008 ms/op
Iteration   3: 3.351 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.430 ±(99.9%) 1.755 ms/op [Average]
  (min, avg, max) = (3.351, 3.430, 3.537), stdev = 0.096
  CI (99.9%): [1.675, 5.185] (assumes normal distribution)


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
# Warmup Iteration   1: 10.519 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.418 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.076 ±(99.9%) 0.008 ms/op
Iteration   1: 3.986 ±(99.9%) 0.012 ms/op
Iteration   2: 3.925 ±(99.9%) 0.012 ms/op
Iteration   3: 3.826 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.912 ±(99.9%) 1.478 ms/op [Average]
  (min, avg, max) = (3.826, 3.912, 3.986), stdev = 0.081
  CI (99.9%): [2.434, 5.391] (assumes normal distribution)


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
# Warmup Iteration   1: 10.235 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 3.976 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.547 ±(99.9%) 0.011 ms/op
Iteration   1: 3.569 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.757 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   4.407 ms/op
                 createUser·p0.95:   6.078 ms/op
                 createUser·p0.99:   7.037 ms/op
                 createUser·p0.999:  9.601 ms/op
                 createUser·p0.9999: 22.249 ms/op
                 createUser·p1.00:   22.872 ms/op

Iteration   2: 3.522 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.671 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   4.153 ms/op
                 createUser·p0.95:   4.596 ms/op
                 createUser·p0.99:   6.504 ms/op
                 createUser·p0.999:  23.790 ms/op
                 createUser·p0.9999: 28.440 ms/op
                 createUser·p1.00:   29.426 ms/op

Iteration   3: 3.344 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.087 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   4.956 ms/op
                 createUser·p0.999:  20.702 ms/op
                 createUser·p0.9999: 26.819 ms/op
                 createUser·p1.00:   27.754 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275989
  mean =      3.476 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8265 
    [ 2.500,  5.000) = 255812 
    [ 5.000,  7.500) = 10492 
    [ 7.500, 10.000) = 1058 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 78 

  Percentiles, ms/op:
      p(0.0000) =      1.087 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      6.627 ms/op
     p(99.9000) =     19.301 ms/op
     p(99.9900) =     27.197 ms/op
     p(99.9990) =     29.040 ms/op
     p(99.9999) =     29.426 ms/op
    p(100.0000) =     29.426 ms/op


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
# Warmup Iteration   1: 8.220 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.638 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.336 ±(99.9%) 0.010 ms/op
Iteration   1: 3.211 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.667 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.620 ms/op
                 existUser·p0.999:  8.225 ms/op
                 existUser·p0.9999: 22.774 ms/op
                 existUser·p1.00:   23.069 ms/op

Iteration   2: 3.382 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.239 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.908 ms/op
                 existUser·p0.95:   4.334 ms/op
                 existUser·p0.99:   5.841 ms/op
                 existUser·p0.999:  9.486 ms/op
                 existUser·p0.9999: 28.296 ms/op
                 existUser·p1.00:   28.574 ms/op

Iteration   3: 3.394 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.548 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.887 ms/op
                 existUser·p0.95:   4.334 ms/op
                 existUser·p0.99:   6.152 ms/op
                 existUser·p0.999:  21.063 ms/op
                 existUser·p0.9999: 26.547 ms/op
                 existUser·p1.00:   27.066 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288624
  mean =      3.327 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13027 
    [ 2.500,  5.000) = 269893 
    [ 5.000,  7.500) = 4930 
    [ 7.500, 10.000) = 488 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      1.239 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      4.137 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =      9.994 ms/op
     p(99.9900) =     27.661 ms/op
     p(99.9990) =     28.545 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


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
# Warmup Iteration   1: 9.033 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.923 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.538 ±(99.9%) 0.011 ms/op
Iteration   1: 3.517 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.272 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.875 ms/op
                 getUser·p0.95:   5.284 ms/op
                 getUser·p0.99:   7.176 ms/op
                 getUser·p0.999:  15.124 ms/op
                 getUser·p0.9999: 28.508 ms/op
                 getUser·p1.00:   31.162 ms/op

Iteration   2: 3.392 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.761 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   3.998 ms/op
                 getUser·p0.99:   5.571 ms/op
                 getUser·p0.999:  22.067 ms/op
                 getUser·p0.9999: 24.955 ms/op
                 getUser·p1.00:   25.199 ms/op

Iteration   3: 3.454 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.534 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   5.912 ms/op
                 getUser·p0.999:  19.757 ms/op
                 getUser·p0.9999: 26.443 ms/op
                 getUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277737
  mean =      3.453 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2696 
    [ 2.500,  5.000) = 266857 
    [ 5.000,  7.500) = 6980 
    [ 7.500, 10.000) = 831 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 125 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.272 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      6.439 ms/op
     p(99.9000) =     15.653 ms/op
     p(99.9900) =     27.394 ms/op
     p(99.9990) =     31.046 ms/op
     p(99.9999) =     31.162 ms/op
    p(100.0000) =     31.162 ms/op


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
# Warmup Iteration   1: 12.370 ±(99.9%) 0.158 ms/op
# Warmup Iteration   2: 4.826 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.033 ±(99.9%) 0.013 ms/op
Iteration   1: 3.964 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.878 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  19.311 ms/op
                 listUser·p0.9999: 21.559 ms/op
                 listUser·p1.00:   22.970 ms/op

Iteration   2: 3.980 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.220 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   7.332 ms/op
                 listUser·p0.999:  16.829 ms/op
                 listUser·p0.9999: 20.775 ms/op
                 listUser·p1.00:   21.135 ms/op

Iteration   3: 4.036 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.667 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   7.582 ms/op
                 listUser·p0.999:  14.025 ms/op
                 listUser·p0.9999: 15.368 ms/op
                 listUser·p1.00:   15.434 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240377
  mean =      3.993 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50 
    [ 2.500,  5.000) = 231447 
    [ 5.000,  7.500) = 6644 
    [ 7.500, 10.000) = 1401 
    [10.000, 12.500) = 277 
    [12.500, 15.000) = 248 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.667 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      7.340 ms/op
     p(99.9000) =     16.138 ms/op
     p(99.9900) =     20.998 ms/op
     p(99.9990) =     22.529 ms/op
     p(99.9999) =     22.970 ms/op
    p(100.0000) =     22.970 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.419 ± 1.465  ops/ms
ClientPb.existUser                       thrpt       3   9.900 ± 2.173  ops/ms
ClientPb.getUser                         thrpt       3   9.453 ± 2.485  ops/ms
ClientPb.listUser                        thrpt       3   7.921 ± 4.037  ops/ms
ClientPb.createUser                       avgt       3   3.490 ± 1.144   ms/op
ClientPb.existUser                        avgt       3   3.260 ± 0.569   ms/op
ClientPb.getUser                          avgt       3   3.430 ± 1.755   ms/op
ClientPb.listUser                         avgt       3   3.912 ± 1.478   ms/op
ClientPb.createUser                     sample  275989   3.476 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.087           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.293           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.981           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.653           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.627           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.301           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.197           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.426           ms/op
ClientPb.existUser                      sample  288624   3.327 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.239           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.252           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.740           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.137           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.669           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.994           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.661           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.574           ms/op
ClientPb.getUser                        sample  277737   3.453 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.272           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.310           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.793           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.080           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.439           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.653           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.394           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.162           ms/op
ClientPb.listUser                       sample  240377   3.993 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.667           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.846           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.702           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.340           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.138           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.998           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.970           ms/op
