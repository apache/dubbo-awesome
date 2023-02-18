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
# Warmup Iteration   1: 2.303 ops/ms
# Warmup Iteration   2: 5.868 ops/ms
# Warmup Iteration   3: 8.804 ops/ms
Iteration   1: 8.899 ops/ms
Iteration   2: 9.221 ops/ms
Iteration   3: 9.511 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.210 ±(99.9%) 5.580 ops/ms [Average]
  (min, avg, max) = (8.899, 9.210, 9.511), stdev = 0.306
  CI (99.9%): [3.630, 14.790] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 2.944 ops/ms
# Warmup Iteration   2: 8.975 ops/ms
# Warmup Iteration   3: 9.335 ops/ms
Iteration   1: 9.583 ops/ms
Iteration   2: 9.942 ops/ms
Iteration   3: 9.712 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.746 ±(99.9%) 3.317 ops/ms [Average]
  (min, avg, max) = (9.583, 9.746, 9.942), stdev = 0.182
  CI (99.9%): [6.429, 13.062] (assumes normal distribution)


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
# Warmup Iteration   1: 3.540 ops/ms
# Warmup Iteration   2: 8.818 ops/ms
# Warmup Iteration   3: 8.797 ops/ms
Iteration   1: 9.521 ops/ms
Iteration   2: 9.296 ops/ms
Iteration   3: 9.352 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.389 ±(99.9%) 2.136 ops/ms [Average]
  (min, avg, max) = (9.296, 9.389, 9.521), stdev = 0.117
  CI (99.9%): [7.254, 11.525] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.971 ops/ms
# Warmup Iteration   2: 7.424 ops/ms
# Warmup Iteration   3: 7.795 ops/ms
Iteration   1: 8.041 ops/ms
Iteration   2: 8.048 ops/ms
Iteration   3: 7.877 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.988 ±(99.9%) 1.767 ops/ms [Average]
  (min, avg, max) = (7.877, 7.988, 8.048), stdev = 0.097
  CI (99.9%): [6.221, 9.755] (assumes normal distribution)


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
# Warmup Iteration   1: 8.872 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.728 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.637 ±(99.9%) 0.004 ms/op
Iteration   1: 3.338 ±(99.9%) 0.010 ms/op
Iteration   2: 3.360 ±(99.9%) 0.005 ms/op
Iteration   3: 3.245 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.315 ±(99.9%) 1.117 ms/op [Average]
  (min, avg, max) = (3.245, 3.315, 3.360), stdev = 0.061
  CI (99.9%): [2.197, 4.432] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.230 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.509 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.314 ±(99.9%) 0.005 ms/op
Iteration   1: 3.191 ±(99.9%) 0.002 ms/op
Iteration   2: 3.287 ±(99.9%) 0.004 ms/op
Iteration   3: 3.210 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.229 ±(99.9%) 0.926 ms/op [Average]
  (min, avg, max) = (3.191, 3.229, 3.287), stdev = 0.051
  CI (99.9%): [2.304, 4.155] (assumes normal distribution)


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
# Warmup Iteration   1: 9.751 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.670 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.628 ±(99.9%) 0.005 ms/op
Iteration   1: 3.466 ±(99.9%) 0.007 ms/op
Iteration   2: 3.465 ±(99.9%) 0.006 ms/op
Iteration   3: 3.329 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.420 ±(99.9%) 1.442 ms/op [Average]
  (min, avg, max) = (3.329, 3.420, 3.466), stdev = 0.079
  CI (99.9%): [1.979, 4.862] (assumes normal distribution)


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
# Warmup Iteration   1: 11.066 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.253 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.033 ±(99.9%) 0.009 ms/op
Iteration   1: 3.901 ±(99.9%) 0.009 ms/op
Iteration   2: 3.886 ±(99.9%) 0.009 ms/op
Iteration   3: 3.869 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.885 ±(99.9%) 0.297 ms/op [Average]
  (min, avg, max) = (3.869, 3.885, 3.901), stdev = 0.016
  CI (99.9%): [3.589, 4.182] (assumes normal distribution)


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
# Warmup Iteration   1: 8.902 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.901 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.431 ±(99.9%) 0.010 ms/op
Iteration   1: 3.379 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.315 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   5.923 ms/op
                 createUser·p0.999:  20.068 ms/op
                 createUser·p0.9999: 25.533 ms/op
                 createUser·p1.00:   26.608 ms/op

Iteration   2: 3.330 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.354 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   5.603 ms/op
                 createUser·p0.999:  22.023 ms/op
                 createUser·p0.9999: 24.379 ms/op
                 createUser·p1.00:   24.740 ms/op

Iteration   3: 3.436 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.579 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.875 ms/op
                 createUser·p0.95:   4.129 ms/op
                 createUser·p0.99:   6.210 ms/op
                 createUser·p0.999:  16.101 ms/op
                 createUser·p0.9999: 25.821 ms/op
                 createUser·p1.00:   26.477 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 283736
  mean =      3.381 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12039 
    [ 2.500,  5.000) = 265998 
    [ 5.000,  7.500) = 4683 
    [ 7.500, 10.000) = 517 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 135 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.315 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      3.768 ms/op
     p(95.0000) =      4.100 ms/op
     p(99.0000) =      5.887 ms/op
     p(99.9000) =     17.376 ms/op
     p(99.9900) =     25.317 ms/op
     p(99.9990) =     26.482 ms/op
     p(99.9999) =     26.608 ms/op
    p(100.0000) =     26.608 ms/op


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
# Warmup Iteration   1: 7.469 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.558 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.488 ±(99.9%) 0.010 ms/op
Iteration   1: 3.222 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.391 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   5.415 ms/op
                 existUser·p0.999:  11.321 ms/op
                 existUser·p0.9999: 23.658 ms/op
                 existUser·p1.00:   24.805 ms/op

Iteration   2: 3.272 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.546 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.883 ms/op
                 existUser·p0.99:   5.030 ms/op
                 existUser·p0.999:  10.437 ms/op
                 existUser·p0.9999: 26.509 ms/op
                 existUser·p1.00:   27.230 ms/op

Iteration   3: 3.226 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.534 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   5.542 ms/op
                 existUser·p0.999:  15.284 ms/op
                 existUser·p0.9999: 26.119 ms/op
                 existUser·p1.00:   27.001 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 296256
  mean =      3.240 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9230 
    [ 2.500,  5.000) = 282915 
    [ 5.000,  7.500) = 3378 
    [ 7.500, 10.000) = 397 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 107 
    [25.000, 27.500) = 69 

  Percentiles, ms/op:
      p(0.0000) =      1.391 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      5.366 ms/op
     p(99.9000) =     11.747 ms/op
     p(99.9900) =     26.051 ms/op
     p(99.9990) =     27.166 ms/op
     p(99.9999) =     27.230 ms/op
    p(100.0000) =     27.230 ms/op


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
# Warmup Iteration   1: 9.646 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.729 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.477 ±(99.9%) 0.009 ms/op
Iteration   1: 3.471 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.139 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   4.407 ms/op
                 getUser·p0.99:   6.824 ms/op
                 getUser·p0.999:  20.053 ms/op
                 getUser·p0.9999: 25.126 ms/op
                 getUser·p1.00:   25.264 ms/op

Iteration   2: 3.463 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.767 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   4.002 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   5.939 ms/op
                 getUser·p0.999:  21.791 ms/op
                 getUser·p0.9999: 27.659 ms/op
                 getUser·p1.00:   29.524 ms/op

Iteration   3: 3.421 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.305 ms/op
                 getUser·p0.50:   3.281 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   4.067 ms/op
                 getUser·p0.99:   6.463 ms/op
                 getUser·p0.999:  20.298 ms/op
                 getUser·p0.9999: 25.238 ms/op
                 getUser·p1.00:   26.706 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277756
  mean =      3.452 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9522 
    [ 2.500,  5.000) = 259970 
    [ 5.000,  7.500) = 7028 
    [ 7.500, 10.000) = 744 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 131 
    [25.000, 27.500) = 46 

  Percentiles, ms/op:
      p(0.0000) =      1.139 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      6.414 ms/op
     p(99.9000) =     20.209 ms/op
     p(99.9900) =     26.095 ms/op
     p(99.9990) =     28.173 ms/op
     p(99.9999) =     29.524 ms/op
    p(100.0000) =     29.524 ms/op


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
# Warmup Iteration   1: 10.022 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 4.363 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.956 ±(99.9%) 0.012 ms/op
Iteration   1: 4.027 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.862 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.784 ms/op
                 listUser·p0.99:   7.700 ms/op
                 listUser·p0.999:  17.061 ms/op
                 listUser·p0.9999: 22.839 ms/op
                 listUser·p1.00:   23.888 ms/op

Iteration   2: 4.032 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.882 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.792 ms/op
                 listUser·p0.99:   7.520 ms/op
                 listUser·p0.999:  14.572 ms/op
                 listUser·p0.9999: 18.909 ms/op
                 listUser·p1.00:   19.104 ms/op

Iteration   3: 3.930 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.269 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   8.069 ms/op
                 listUser·p0.999:  15.778 ms/op
                 listUser·p0.9999: 20.967 ms/op
                 listUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240094
  mean =      3.996 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51 
    [ 2.500,  5.000) = 230247 
    [ 5.000,  7.500) = 7009 
    [ 7.500, 10.000) = 2065 
    [10.000, 12.500) = 233 
    [12.500, 15.000) = 229 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.862 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      7.741 ms/op
     p(99.9000) =     15.508 ms/op
     p(99.9900) =     21.987 ms/op
     p(99.9990) =     23.698 ms/op
     p(99.9999) =     23.888 ms/op
    p(100.0000) =     23.888 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.210 ± 5.580  ops/ms
ClientPb.existUser                       thrpt       3   9.746 ± 3.317  ops/ms
ClientPb.getUser                         thrpt       3   9.389 ± 2.136  ops/ms
ClientPb.listUser                        thrpt       3   7.988 ± 1.767  ops/ms
ClientPb.createUser                       avgt       3   3.315 ± 1.117   ms/op
ClientPb.existUser                        avgt       3   3.229 ± 0.926   ms/op
ClientPb.getUser                          avgt       3   3.420 ± 1.442   ms/op
ClientPb.listUser                         avgt       3   3.885 ± 0.297   ms/op
ClientPb.createUser                     sample  283736   3.381 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.315           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.305           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.768           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.100           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.887           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.376           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.317           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.608           ms/op
ClientPb.existUser                      sample  296256   3.240 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.391           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.158           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.539           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.756           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.366           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.747           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.051           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.230           ms/op
ClientPb.getUser                        sample  277756   3.452 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.139           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.318           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.903           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.276           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.414           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.209           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.095           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.524           ms/op
ClientPb.listUser                       sample  240094   3.996 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.862           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.809           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.719           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.741           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.508           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.987           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.888           ms/op
