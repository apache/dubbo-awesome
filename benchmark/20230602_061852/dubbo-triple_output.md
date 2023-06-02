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
# Warmup Iteration   1: 1.992 ops/ms
# Warmup Iteration   2: 5.341 ops/ms
# Warmup Iteration   3: 8.632 ops/ms
Iteration   1: 9.308 ops/ms
Iteration   2: 9.122 ops/ms
Iteration   3: 9.549 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.326 ±(99.9%) 3.908 ops/ms [Average]
  (min, avg, max) = (9.122, 9.326, 9.549), stdev = 0.214
  CI (99.9%): [5.419, 13.234] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.364 ops/ms
# Warmup Iteration   2: 8.733 ops/ms
# Warmup Iteration   3: 9.198 ops/ms
Iteration   1: 9.892 ops/ms
Iteration   2: 9.331 ops/ms
Iteration   3: 9.840 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.688 ±(99.9%) 5.655 ops/ms [Average]
  (min, avg, max) = (9.331, 9.688, 9.892), stdev = 0.310
  CI (99.9%): [4.032, 15.343] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.552 ops/ms
# Warmup Iteration   2: 8.173 ops/ms
# Warmup Iteration   3: 8.980 ops/ms
Iteration   1: 9.132 ops/ms
Iteration   2: 9.336 ops/ms
Iteration   3: 9.459 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.309 ±(99.9%) 3.015 ops/ms [Average]
  (min, avg, max) = (9.132, 9.309, 9.459), stdev = 0.165
  CI (99.9%): [6.294, 12.323] (assumes normal distribution)


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
# Warmup Iteration   1: 2.727 ops/ms
# Warmup Iteration   2: 7.271 ops/ms
# Warmup Iteration   3: 7.806 ops/ms
Iteration   1: 7.933 ops/ms
Iteration   2: 7.775 ops/ms
Iteration   3: 8.238 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.982 ±(99.9%) 4.296 ops/ms [Average]
  (min, avg, max) = (7.775, 7.982, 8.238), stdev = 0.235
  CI (99.9%): [3.686, 12.278] (assumes normal distribution)


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
# Warmup Iteration   1: 10.885 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.139 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.520 ±(99.9%) 0.009 ms/op
Iteration   1: 3.517 ±(99.9%) 0.007 ms/op
Iteration   2: 3.352 ±(99.9%) 0.011 ms/op
Iteration   3: 3.348 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.405 ±(99.9%) 1.759 ms/op [Average]
  (min, avg, max) = (3.348, 3.405, 3.517), stdev = 0.096
  CI (99.9%): [1.646, 5.164] (assumes normal distribution)


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
# Warmup Iteration   1: 7.837 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.646 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.252 ±(99.9%) 0.005 ms/op
Iteration   1: 3.234 ±(99.9%) 0.011 ms/op
Iteration   2: 3.325 ±(99.9%) 0.012 ms/op
Iteration   3: 3.322 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.294 ±(99.9%) 0.944 ms/op [Average]
  (min, avg, max) = (3.234, 3.294, 3.325), stdev = 0.052
  CI (99.9%): [2.350, 4.238] (assumes normal distribution)


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
# Warmup Iteration   1: 8.511 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.556 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.455 ±(99.9%) 0.011 ms/op
Iteration   1: 3.394 ±(99.9%) 0.004 ms/op
Iteration   2: 3.313 ±(99.9%) 0.010 ms/op
Iteration   3: 3.482 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.396 ±(99.9%) 1.546 ms/op [Average]
  (min, avg, max) = (3.313, 3.396, 3.482), stdev = 0.085
  CI (99.9%): [1.851, 4.942] (assumes normal distribution)


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
# Warmup Iteration   1: 10.485 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.173 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.134 ±(99.9%) 0.007 ms/op
Iteration   1: 4.136 ±(99.9%) 0.007 ms/op
Iteration   2: 4.026 ±(99.9%) 0.009 ms/op
Iteration   3: 3.981 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.047 ±(99.9%) 1.454 ms/op [Average]
  (min, avg, max) = (3.981, 4.047, 4.136), stdev = 0.080
  CI (99.9%): [2.594, 5.501] (assumes normal distribution)


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
# Warmup Iteration   1: 8.995 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.960 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.430 ±(99.9%) 0.010 ms/op
Iteration   1: 3.492 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.632 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   4.022 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   5.800 ms/op
                 createUser·p0.999:  21.541 ms/op
                 createUser·p0.9999: 23.986 ms/op
                 createUser·p1.00:   27.689 ms/op

Iteration   2: 3.314 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.765 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   5.114 ms/op
                 createUser·p0.999:  17.558 ms/op
                 createUser·p0.9999: 26.542 ms/op
                 createUser·p1.00:   28.803 ms/op

Iteration   3: 3.458 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.550 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   4.067 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   5.505 ms/op
                 createUser·p0.999:  20.513 ms/op
                 createUser·p0.9999: 25.911 ms/op
                 createUser·p1.00:   26.477 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280643
  mean =      3.420 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8182 
    [ 2.500,  5.000) = 266911 
    [ 5.000,  7.500) = 4693 
    [ 7.500, 10.000) = 313 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 116 
    [25.000, 27.500) = 95 

  Percentiles, ms/op:
      p(0.0000) =      1.550 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =     20.627 ms/op
     p(99.9900) =     26.313 ms/op
     p(99.9990) =     27.780 ms/op
     p(99.9999) =     28.803 ms/op
    p(100.0000) =     28.803 ms/op


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
# Warmup Iteration   1: 7.765 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.490 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.317 ±(99.9%) 0.008 ms/op
Iteration   1: 3.294 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.575 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.699 ms/op
                 existUser·p0.95:   3.994 ms/op
                 existUser·p0.99:   5.317 ms/op
                 existUser·p0.999:  9.781 ms/op
                 existUser·p0.9999: 24.398 ms/op
                 existUser·p1.00:   25.264 ms/op

Iteration   2: 3.469 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.456 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   4.678 ms/op
                 existUser·p0.95:   4.866 ms/op
                 existUser·p0.99:   6.308 ms/op
                 existUser·p0.999:  21.290 ms/op
                 existUser·p0.9999: 25.849 ms/op
                 existUser·p1.00:   26.870 ms/op

Iteration   3: 3.440 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.729 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   4.100 ms/op
                 existUser·p0.95:   4.489 ms/op
                 existUser·p0.99:   6.791 ms/op
                 existUser·p0.999:  9.814 ms/op
                 existUser·p0.9999: 37.121 ms/op
                 existUser·p1.00:   38.076 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282289
  mean =      3.399 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14850 
    [ 2.500,  5.000) = 259938 
    [ 5.000,  7.500) = 6599 
    [ 7.500, 10.000) = 622 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 95 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.456 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      3.994 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      6.144 ms/op
     p(99.9000) =      9.989 ms/op
     p(99.9900) =     36.554 ms/op
     p(99.9990) =     37.564 ms/op
     p(99.9999) =     38.076 ms/op
    p(100.0000) =     38.076 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.942 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.754 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.508 ±(99.9%) 0.010 ms/op
Iteration   1: 3.474 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.182 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   4.067 ms/op
                 getUser·p0.99:   6.136 ms/op
                 getUser·p0.999:  11.684 ms/op
                 getUser·p0.9999: 26.503 ms/op
                 getUser·p1.00:   26.771 ms/op

Iteration   2: 3.425 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.636 ms/op
                 getUser·p0.50:   3.281 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   4.178 ms/op
                 getUser·p0.99:   5.939 ms/op
                 getUser·p0.999:  23.444 ms/op
                 getUser·p0.9999: 26.804 ms/op
                 getUser·p1.00:   28.279 ms/op

Iteration   3: 3.554 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.329 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   4.358 ms/op
                 getUser·p0.95:   4.945 ms/op
                 getUser·p0.99:   6.521 ms/op
                 getUser·p0.999:  21.264 ms/op
                 getUser·p0.9999: 27.656 ms/op
                 getUser·p1.00:   29.458 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275563
  mean =      3.484 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6548 
    [ 2.500,  5.000) = 259104 
    [ 5.000,  7.500) = 8825 
    [ 7.500, 10.000) = 683 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 94 

  Percentiles, ms/op:
      p(0.0000) =      1.182 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      6.193 ms/op
     p(99.9000) =     15.785 ms/op
     p(99.9900) =     26.837 ms/op
     p(99.9990) =     28.997 ms/op
     p(99.9999) =     29.458 ms/op
    p(100.0000) =     29.458 ms/op


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
# Warmup Iteration   1: 12.701 ±(99.9%) 0.169 ms/op
# Warmup Iteration   2: 4.546 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.225 ±(99.9%) 0.014 ms/op
Iteration   1: 4.150 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.769 ms/op
                 listUser·p0.50:   3.961 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   4.948 ms/op
                 listUser·p0.99:   8.053 ms/op
                 listUser·p0.999:  21.223 ms/op
                 listUser·p0.9999: 26.307 ms/op
                 listUser·p1.00:   28.246 ms/op

Iteration   2: 3.952 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.408 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  16.073 ms/op
                 listUser·p0.9999: 18.842 ms/op
                 listUser·p1.00:   18.907 ms/op

Iteration   3: 4.051 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.281 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   5.112 ms/op
                 listUser·p0.99:   7.922 ms/op
                 listUser·p0.999:  15.991 ms/op
                 listUser·p0.9999: 23.079 ms/op
                 listUser·p1.00:   23.953 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237027
  mean =      4.049 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 62 
    [ 2.500,  5.000) = 226573 
    [ 5.000,  7.500) = 7671 
    [ 7.500, 10.000) = 1779 
    [10.000, 12.500) = 413 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 130 
    [17.500, 20.000) = 135 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.769 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      7.774 ms/op
     p(99.9000) =     17.826 ms/op
     p(99.9900) =     24.041 ms/op
     p(99.9990) =     26.956 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.326 ± 3.908  ops/ms
ClientPb.existUser                       thrpt       3   9.688 ± 5.655  ops/ms
ClientPb.getUser                         thrpt       3   9.309 ± 3.015  ops/ms
ClientPb.listUser                        thrpt       3   7.982 ± 4.296  ops/ms
ClientPb.createUser                       avgt       3   3.405 ± 1.759   ms/op
ClientPb.existUser                        avgt       3   3.294 ± 0.944   ms/op
ClientPb.getUser                          avgt       3   3.396 ± 1.546   ms/op
ClientPb.listUser                         avgt       3   4.047 ± 1.454   ms/op
ClientPb.createUser                     sample  280643   3.420 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.550           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.293           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.908           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.268           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.521           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.627           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.313           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.803           ms/op
ClientPb.existUser                      sample  282289   3.399 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.456           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.252           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.994           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.678           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.144           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.989           ms/op
ClientPb.existUser:existUser·p0.9999    sample          36.554           ms/op
ClientPb.existUser:existUser·p1.00      sample          38.076           ms/op
ClientPb.getUser                        sample  275563   3.484 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.182           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.342           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.899           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.653           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.193           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.785           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.837           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.458           ms/op
ClientPb.listUser                       sample  237027   4.049 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.769           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.858           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.774           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.826           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.041           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.246           ms/op
