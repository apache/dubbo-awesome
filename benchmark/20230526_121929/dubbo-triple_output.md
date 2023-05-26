# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.649 ops/ms
# Warmup Iteration   2: 3.634 ops/ms
# Warmup Iteration   3: 7.260 ops/ms
Iteration   1: 7.615 ops/ms
Iteration   2: 8.406 ops/ms
Iteration   3: 8.289 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.103 ±(99.9%) 7.785 ops/ms [Average]
  (min, avg, max) = (7.615, 8.103, 8.406), stdev = 0.427
  CI (99.9%): [0.318, 15.888] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.318 ops/ms
# Warmup Iteration   2: 7.343 ops/ms
# Warmup Iteration   3: 8.502 ops/ms
Iteration   1: 8.888 ops/ms
Iteration   2: 8.674 ops/ms
Iteration   3: 8.625 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.729 ±(99.9%) 2.548 ops/ms [Average]
  (min, avg, max) = (8.625, 8.729, 8.888), stdev = 0.140
  CI (99.9%): [6.181, 11.277] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.179 ops/ms
# Warmup Iteration   2: 6.265 ops/ms
# Warmup Iteration   3: 8.189 ops/ms
Iteration   1: 7.902 ops/ms
Iteration   2: 8.015 ops/ms
Iteration   3: 8.166 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.028 ±(99.9%) 2.418 ops/ms [Average]
  (min, avg, max) = (7.902, 8.028, 8.166), stdev = 0.133
  CI (99.9%): [5.609, 10.446] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.196 ops/ms
# Warmup Iteration   2: 5.776 ops/ms
# Warmup Iteration   3: 6.678 ops/ms
Iteration   1: 6.785 ops/ms
Iteration   2: 6.827 ops/ms
Iteration   3: 6.890 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.834 ±(99.9%) 0.962 ops/ms [Average]
  (min, avg, max) = (6.785, 6.834, 6.890), stdev = 0.053
  CI (99.9%): [5.873, 7.796] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 13.581 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.655 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.258 ±(99.9%) 0.007 ms/op
Iteration   1: 4.038 ±(99.9%) 0.003 ms/op
Iteration   2: 3.960 ±(99.9%) 0.006 ms/op
Iteration   3: 3.928 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.975 ±(99.9%) 1.036 ms/op [Average]
  (min, avg, max) = (3.928, 3.975, 4.038), stdev = 0.057
  CI (99.9%): [2.939, 5.012] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 13.099 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.420 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.757 ±(99.9%) 0.005 ms/op
Iteration   1: 3.685 ±(99.9%) 0.007 ms/op
Iteration   2: 3.649 ±(99.9%) 0.004 ms/op
Iteration   3: 3.651 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.662 ±(99.9%) 0.375 ms/op [Average]
  (min, avg, max) = (3.649, 3.662, 3.685), stdev = 0.021
  CI (99.9%): [3.287, 4.036] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 11.474 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.765 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.921 ±(99.9%) 0.006 ms/op
Iteration   1: 3.942 ±(99.9%) 0.011 ms/op
Iteration   2: 4.007 ±(99.9%) 0.009 ms/op
Iteration   3: 3.731 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.894 ±(99.9%) 2.632 ms/op [Average]
  (min, avg, max) = (3.731, 3.894, 4.007), stdev = 0.144
  CI (99.9%): [1.261, 6.526] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 14.989 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 5.738 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.749 ±(99.9%) 0.008 ms/op
Iteration   1: 4.448 ±(99.9%) 0.011 ms/op
Iteration   2: 4.465 ±(99.9%) 0.012 ms/op
Iteration   3: 4.624 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.512 ±(99.9%) 1.766 ms/op [Average]
  (min, avg, max) = (4.448, 4.512, 4.624), stdev = 0.097
  CI (99.9%): [2.746, 6.278] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 13.843 ±(99.9%) 0.192 ms/op
# Warmup Iteration   2: 4.753 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.109 ±(99.9%) 0.017 ms/op
Iteration   1: 3.829 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.802 ms/op
                 createUser·p0.50:   3.674 ms/op
                 createUser·p0.90:   4.309 ms/op
                 createUser·p0.95:   4.735 ms/op
                 createUser·p0.99:   6.955 ms/op
                 createUser·p0.999:  23.429 ms/op
                 createUser·p0.9999: 26.345 ms/op
                 createUser·p1.00:   27.886 ms/op

Iteration   2: 4.014 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.448 ms/op
                 createUser·p0.50:   3.842 ms/op
                 createUser·p0.90:   4.637 ms/op
                 createUser·p0.95:   5.254 ms/op
                 createUser·p0.99:   8.086 ms/op
                 createUser·p0.999:  24.760 ms/op
                 createUser·p0.9999: 32.933 ms/op
                 createUser·p1.00:   33.096 ms/op

Iteration   3: 3.980 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.696 ms/op
                 createUser·p0.50:   3.809 ms/op
                 createUser·p0.90:   4.547 ms/op
                 createUser·p0.95:   5.145 ms/op
                 createUser·p0.99:   7.356 ms/op
                 createUser·p0.999:  19.694 ms/op
                 createUser·p0.9999: 33.094 ms/op
                 createUser·p1.00:   35.979 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 243453
  mean =      3.939 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 404 
    [ 2.500,  5.000) = 230454 
    [ 5.000,  7.500) = 10145 
    [ 7.500, 10.000) = 1740 
    [10.000, 12.500) = 283 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 103 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 46 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.448 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      5.030 ms/op
     p(99.0000) =      7.516 ms/op
     p(99.9000) =     23.429 ms/op
     p(99.9900) =     32.834 ms/op
     p(99.9990) =     34.486 ms/op
     p(99.9999) =     35.979 ms/op
    p(100.0000) =     35.979 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.546 ±(99.9%) 0.177 ms/op
# Warmup Iteration   2: 4.754 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 3.942 ±(99.9%) 0.012 ms/op
Iteration   1: 3.930 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.374 ms/op
                 existUser·p0.50:   3.719 ms/op
                 existUser·p0.90:   4.555 ms/op
                 existUser·p0.95:   5.489 ms/op
                 existUser·p0.99:   7.389 ms/op
                 existUser·p0.999:  24.183 ms/op
                 existUser·p0.9999: 27.263 ms/op
                 existUser·p1.00:   27.623 ms/op

Iteration   2: 3.942 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.718 ms/op
                 existUser·p0.50:   3.764 ms/op
                 existUser·p0.90:   4.596 ms/op
                 existUser·p0.95:   5.095 ms/op
                 existUser·p0.99:   6.748 ms/op
                 existUser·p0.999:  12.009 ms/op
                 existUser·p0.9999: 27.296 ms/op
                 existUser·p1.00:   27.918 ms/op

Iteration   3: 3.663 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.470 ms/op
                 existUser·p0.50:   3.564 ms/op
                 existUser·p0.90:   3.944 ms/op
                 existUser·p0.95:   4.153 ms/op
                 existUser·p0.99:   6.078 ms/op
                 existUser·p0.999:  26.992 ms/op
                 existUser·p0.9999: 31.171 ms/op
                 existUser·p1.00:   33.194 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 249845
  mean =      3.840 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 457 
    [ 2.500,  5.000) = 237518 
    [ 5.000,  7.500) = 10180 
    [ 7.500, 10.000) = 1167 
    [10.000, 12.500) = 235 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 133 
    [27.500, 30.000) = 59 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.374 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.932 ms/op
     p(99.0000) =      6.889 ms/op
     p(99.9000) =     23.200 ms/op
     p(99.9900) =     29.919 ms/op
     p(99.9990) =     32.015 ms/op
     p(99.9999) =     33.194 ms/op
    p(100.0000) =     33.194 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.001 ±(99.9%) 0.198 ms/op
# Warmup Iteration   2: 4.431 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.062 ±(99.9%) 0.014 ms/op
Iteration   1: 4.025 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.228 ms/op
                 getUser·p0.50:   3.883 ms/op
                 getUser·p0.90:   4.538 ms/op
                 getUser·p0.95:   5.145 ms/op
                 getUser·p0.99:   7.102 ms/op
                 getUser·p0.999:  19.300 ms/op
                 getUser·p0.9999: 28.157 ms/op
                 getUser·p1.00:   29.131 ms/op

Iteration   2: 4.106 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.335 ms/op
                 getUser·p0.50:   3.936 ms/op
                 getUser·p0.90:   4.841 ms/op
                 getUser·p0.95:   5.521 ms/op
                 getUser·p0.99:   7.532 ms/op
                 getUser·p0.999:  12.946 ms/op
                 getUser·p0.9999: 28.005 ms/op
                 getUser·p1.00:   30.474 ms/op

Iteration   3: 3.971 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   2.138 ms/op
                 getUser·p0.50:   3.797 ms/op
                 getUser·p0.90:   4.645 ms/op
                 getUser·p0.95:   5.128 ms/op
                 getUser·p0.99:   7.168 ms/op
                 getUser·p0.999:  27.066 ms/op
                 getUser·p0.9999: 32.532 ms/op
                 getUser·p1.00:   33.620 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 237869
  mean =      4.033 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 115 
    [ 2.500,  5.000) = 222119 
    [ 5.000,  7.500) = 13610 
    [ 7.500, 10.000) = 1282 
    [10.000, 12.500) = 287 
    [12.500, 15.000) = 165 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 99 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 42 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.138 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.678 ms/op
     p(95.0000) =      5.267 ms/op
     p(99.0000) =      7.258 ms/op
     p(99.9000) =     20.054 ms/op
     p(99.9900) =     31.263 ms/op
     p(99.9990) =     33.595 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.391 ±(99.9%) 0.238 ms/op
# Warmup Iteration   2: 5.608 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.903 ±(99.9%) 0.017 ms/op
Iteration   1: 4.674 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.503 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   8.798 ms/op
                 listUser·p0.999:  26.642 ms/op
                 listUser·p0.9999: 30.878 ms/op
                 listUser·p1.00:   31.916 ms/op

Iteration   2: 4.620 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.605 ms/op
                 listUser·p0.50:   4.407 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.643 ms/op
                 listUser·p0.99:   9.110 ms/op
                 listUser·p0.999:  18.461 ms/op
                 listUser·p0.9999: 20.316 ms/op
                 listUser·p1.00:   20.644 ms/op

Iteration   3: 4.505 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   4.309 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.276 ms/op
                 listUser·p0.99:   8.004 ms/op
                 listUser·p0.999:  17.171 ms/op
                 listUser·p0.9999: 20.127 ms/op
                 listUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 208690
  mean =      4.599 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 183186 
    [ 5.000,  7.500) = 21033 
    [ 7.500, 10.000) = 3454 
    [10.000, 12.500) = 503 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 123 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.318 ms/op
     p(50.0000) =      4.375 ms/op
     p(90.0000) =      5.087 ms/op
     p(95.0000) =      5.554 ms/op
     p(99.0000) =      8.733 ms/op
     p(99.9000) =     19.704 ms/op
     p(99.9900) =     28.869 ms/op
     p(99.9990) =     31.880 ms/op
     p(99.9999) =     31.916 ms/op
    p(100.0000) =     31.916 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.103 ± 7.785  ops/ms
ClientPb.existUser                       thrpt       3   8.729 ± 2.548  ops/ms
ClientPb.getUser                         thrpt       3   8.028 ± 2.418  ops/ms
ClientPb.listUser                        thrpt       3   6.834 ± 0.962  ops/ms
ClientPb.createUser                       avgt       3   3.975 ± 1.036   ms/op
ClientPb.existUser                        avgt       3   3.662 ± 0.375   ms/op
ClientPb.getUser                          avgt       3   3.894 ± 2.632   ms/op
ClientPb.listUser                         avgt       3   4.512 ± 1.766   ms/op
ClientPb.createUser                     sample  243453   3.939 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.448           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.777           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.497           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.030           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.516           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.429           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.834           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.979           ms/op
ClientPb.existUser                      sample  249845   3.840 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.374           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.674           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.383           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.932           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.889           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.200           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.919           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.194           ms/op
ClientPb.getUser                        sample  237869   4.033 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.138           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.867           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.678           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.267           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.258           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.054           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.263           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.620           ms/op
ClientPb.listUser                       sample  208690   4.599 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.318           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.087           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.554           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.733           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.704           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.869           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.916           ms/op
