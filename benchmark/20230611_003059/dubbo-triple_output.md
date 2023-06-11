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
# Warmup Iteration   1: 2.154 ops/ms
# Warmup Iteration   2: 5.377 ops/ms
# Warmup Iteration   3: 8.408 ops/ms
Iteration   1: 8.959 ops/ms
Iteration   2: 9.279 ops/ms
Iteration   3: 9.197 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.145 ±(99.9%) 3.036 ops/ms [Average]
  (min, avg, max) = (8.959, 9.145, 9.279), stdev = 0.166
  CI (99.9%): [6.109, 12.181] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.856 ops/ms
# Warmup Iteration   2: 8.761 ops/ms
# Warmup Iteration   3: 9.256 ops/ms
Iteration   1: 9.758 ops/ms
Iteration   2: 10.005 ops/ms
Iteration   3: 9.872 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.879 ±(99.9%) 2.250 ops/ms [Average]
  (min, avg, max) = (9.758, 9.879, 10.005), stdev = 0.123
  CI (99.9%): [7.629, 12.128] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.949 ops/ms
# Warmup Iteration   2: 8.487 ops/ms
# Warmup Iteration   3: 9.446 ops/ms
Iteration   1: 9.090 ops/ms
Iteration   2: 9.749 ops/ms
Iteration   3: 9.606 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.482 ±(99.9%) 6.325 ops/ms [Average]
  (min, avg, max) = (9.090, 9.482, 9.749), stdev = 0.347
  CI (99.9%): [3.156, 15.807] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.892 ops/ms
# Warmup Iteration   2: 7.318 ops/ms
# Warmup Iteration   3: 7.760 ops/ms
Iteration   1: 8.077 ops/ms
Iteration   2: 8.304 ops/ms
Iteration   3: 8.354 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.245 ±(99.9%) 2.694 ops/ms [Average]
  (min, avg, max) = (8.077, 8.245, 8.354), stdev = 0.148
  CI (99.9%): [5.551, 10.938] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.614 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.987 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.486 ±(99.9%) 0.012 ms/op
Iteration   1: 3.420 ±(99.9%) 0.003 ms/op
Iteration   2: 3.401 ±(99.9%) 0.006 ms/op
Iteration   3: 3.348 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.390 ±(99.9%) 0.681 ms/op [Average]
  (min, avg, max) = (3.348, 3.390, 3.420), stdev = 0.037
  CI (99.9%): [2.709, 4.070] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.376 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.752 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.428 ±(99.9%) 0.004 ms/op
Iteration   1: 3.327 ±(99.9%) 0.010 ms/op
Iteration   2: 3.227 ±(99.9%) 0.011 ms/op
Iteration   3: 3.224 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.260 ±(99.9%) 1.067 ms/op [Average]
  (min, avg, max) = (3.224, 3.260, 3.327), stdev = 0.058
  CI (99.9%): [2.193, 4.327] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 10.792 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.835 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.539 ±(99.9%) 0.008 ms/op
Iteration   1: 3.368 ±(99.9%) 0.011 ms/op
Iteration   2: 3.528 ±(99.9%) 0.007 ms/op
Iteration   3: 3.309 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.402 ±(99.9%) 2.070 ms/op [Average]
  (min, avg, max) = (3.309, 3.402, 3.528), stdev = 0.113
  CI (99.9%): [1.332, 5.472] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.545 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.350 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.965 ±(99.9%) 0.008 ms/op
Iteration   1: 3.903 ±(99.9%) 0.013 ms/op
Iteration   2: 3.911 ±(99.9%) 0.010 ms/op
Iteration   3: 3.870 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.895 ±(99.9%) 0.403 ms/op [Average]
  (min, avg, max) = (3.870, 3.895, 3.911), stdev = 0.022
  CI (99.9%): [3.491, 4.298] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.930 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 3.856 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.545 ±(99.9%) 0.010 ms/op
Iteration   1: 3.447 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.370 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.949 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   5.997 ms/op
                 createUser·p0.999:  19.272 ms/op
                 createUser·p0.9999: 24.042 ms/op
                 createUser·p1.00:   24.543 ms/op

Iteration   2: 3.401 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.348 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.850 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   5.693 ms/op
                 createUser·p0.999:  20.900 ms/op
                 createUser·p0.9999: 29.366 ms/op
                 createUser·p1.00:   30.015 ms/op

Iteration   3: 3.463 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.579 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   3.998 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   6.054 ms/op
                 createUser·p0.999:  16.297 ms/op
                 createUser·p0.9999: 24.102 ms/op
                 createUser·p1.00:   25.297 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279262
  mean =      3.437 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5342 
    [ 2.500,  5.000) = 267398 
    [ 5.000,  7.500) = 5538 
    [ 7.500, 10.000) = 558 
    [10.000, 12.500) = 120 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 116 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.348 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      5.898 ms/op
     p(99.9000) =     17.326 ms/op
     p(99.9900) =     26.774 ms/op
     p(99.9990) =     29.662 ms/op
     p(99.9999) =     30.015 ms/op
    p(100.0000) =     30.015 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.506 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.440 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.373 ±(99.9%) 0.009 ms/op
Iteration   1: 3.321 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.473 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   5.923 ms/op
                 existUser·p0.999:  14.646 ms/op
                 existUser·p0.9999: 24.197 ms/op
                 existUser·p1.00:   24.740 ms/op

Iteration   2: 3.315 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.286 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   4.112 ms/op
                 existUser·p0.99:   5.784 ms/op
                 existUser·p0.999:  18.853 ms/op
                 existUser·p0.9999: 30.871 ms/op
                 existUser·p1.00:   32.211 ms/op

Iteration   3: 3.344 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.237 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.699 ms/op
                 existUser·p0.95:   4.182 ms/op
                 existUser·p0.99:   5.692 ms/op
                 existUser·p0.999:  19.105 ms/op
                 existUser·p0.9999: 28.850 ms/op
                 existUser·p1.00:   29.098 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288494
  mean =      3.327 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14595 
    [ 2.500,  5.000) = 266864 
    [ 5.000,  7.500) = 5908 
    [ 7.500, 10.000) = 603 
    [10.000, 12.500) = 201 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.237 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     17.695 ms/op
     p(99.9900) =     30.255 ms/op
     p(99.9990) =     32.062 ms/op
     p(99.9999) =     32.211 ms/op
    p(100.0000) =     32.211 ms/op


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
# Warmup Iteration   1: 8.269 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.694 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.511 ±(99.9%) 0.010 ms/op
Iteration   1: 3.507 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.284 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   4.112 ms/op
                 getUser·p0.95:   4.792 ms/op
                 getUser·p0.99:   6.029 ms/op
                 getUser·p0.999:  19.673 ms/op
                 getUser·p0.9999: 21.942 ms/op
                 getUser·p1.00:   22.282 ms/op

Iteration   2: 3.337 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.405 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   5.677 ms/op
                 getUser·p0.999:  20.868 ms/op
                 getUser·p0.9999: 26.031 ms/op
                 getUser·p1.00:   26.673 ms/op

Iteration   3: 3.381 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.323 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   5.926 ms/op
                 getUser·p0.999:  18.263 ms/op
                 getUser·p0.9999: 27.117 ms/op
                 getUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 281796
  mean =      3.407 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7099 
    [ 2.500,  5.000) = 267156 
    [ 5.000,  7.500) = 6430 
    [ 7.500, 10.000) = 643 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 131 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 56 

  Percentiles, ms/op:
      p(0.0000) =      1.284 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =      5.849 ms/op
     p(99.9000) =     19.091 ms/op
     p(99.9900) =     26.307 ms/op
     p(99.9990) =     27.466 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.918 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 4.446 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.022 ±(99.9%) 0.013 ms/op
Iteration   1: 3.995 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.356 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   7.700 ms/op
                 listUser·p0.999:  17.302 ms/op
                 listUser·p0.9999: 24.773 ms/op
                 listUser·p1.00:   25.068 ms/op

Iteration   2: 4.039 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.261 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   8.102 ms/op
                 listUser·p0.999:  15.106 ms/op
                 listUser·p0.9999: 16.947 ms/op
                 listUser·p1.00:   19.956 ms/op

Iteration   3: 3.895 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.261 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   7.412 ms/op
                 listUser·p0.999:  13.255 ms/op
                 listUser·p0.9999: 15.656 ms/op
                 listUser·p1.00:   15.811 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241047
  mean =      3.975 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43 
    [ 2.500,  5.000) = 233639 
    [ 5.000,  7.500) = 4579 
    [ 7.500, 10.000) = 1787 
    [10.000, 12.500) = 538 
    [12.500, 15.000) = 175 
    [15.000, 17.500) = 208 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.356 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      7.733 ms/op
     p(99.9000) =     15.172 ms/op
     p(99.9900) =     22.996 ms/op
     p(99.9990) =     25.041 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.145 ± 3.036  ops/ms
ClientPb.existUser                       thrpt       3   9.879 ± 2.250  ops/ms
ClientPb.getUser                         thrpt       3   9.482 ± 6.325  ops/ms
ClientPb.listUser                        thrpt       3   8.245 ± 2.694  ops/ms
ClientPb.createUser                       avgt       3   3.390 ± 0.681   ms/op
ClientPb.existUser                        avgt       3   3.260 ± 1.067   ms/op
ClientPb.getUser                          avgt       3   3.402 ± 2.070   ms/op
ClientPb.listUser                         avgt       3   3.895 ± 0.403   ms/op
ClientPb.createUser                     sample  279262   3.437 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.348           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.310           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.936           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.301           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.898           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.326           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.774           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.015           ms/op
ClientPb.existUser                      sample  288494   3.327 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.237           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.232           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.703           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.166           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.792           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.695           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.255           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.211           ms/op
ClientPb.getUser                        sample  281796   3.407 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.284           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.289           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.830           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.166           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.849           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.091           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.307           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.525           ms/op
ClientPb.listUser                       sample  241047   3.975 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.356           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.826           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.555           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.733           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.172           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.996           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.068           ms/op
