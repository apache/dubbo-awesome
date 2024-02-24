# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.909 ops/ms
# Warmup Iteration   2: 11.777 ops/ms
# Warmup Iteration   3: 12.172 ops/ms
Iteration   1: 12.256 ops/ms
Iteration   2: 12.404 ops/ms
Iteration   3: 12.462 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.374 ±(99.9%) 1.938 ops/ms [Average]
  (min, avg, max) = (12.256, 12.374, 12.462), stdev = 0.106
  CI (99.9%): [10.435, 14.312] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.811 ops/ms
# Warmup Iteration   2: 12.972 ops/ms
# Warmup Iteration   3: 13.136 ops/ms
Iteration   1: 13.115 ops/ms
Iteration   2: 13.144 ops/ms
Iteration   3: 13.113 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.124 ±(99.9%) 0.320 ops/ms [Average]
  (min, avg, max) = (13.113, 13.124, 13.144), stdev = 0.018
  CI (99.9%): [12.804, 13.444] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.453 ops/ms
# Warmup Iteration   2: 12.705 ops/ms
# Warmup Iteration   3: 12.943 ops/ms
Iteration   1: 12.913 ops/ms
Iteration   2: 12.968 ops/ms
Iteration   3: 12.849 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.910 ±(99.9%) 1.083 ops/ms [Average]
  (min, avg, max) = (12.849, 12.910, 12.968), stdev = 0.059
  CI (99.9%): [11.827, 13.994] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.394 ops/ms
# Warmup Iteration   2: 10.449 ops/ms
# Warmup Iteration   3: 10.578 ops/ms
Iteration   1: 10.640 ops/ms
Iteration   2: 10.767 ops/ms
Iteration   3: 10.727 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.711 ±(99.9%) 1.184 ops/ms [Average]
  (min, avg, max) = (10.640, 10.711, 10.767), stdev = 0.065
  CI (99.9%): [9.528, 11.895] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 3.968 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.600 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.508 ±(99.9%) 0.005 ms/op
Iteration   1: 2.550 ±(99.9%) 0.004 ms/op
Iteration   2: 2.532 ±(99.9%) 0.004 ms/op
Iteration   3: 2.499 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.527 ±(99.9%) 0.474 ms/op [Average]
  (min, avg, max) = (2.499, 2.527, 2.550), stdev = 0.026
  CI (99.9%): [2.053, 3.001] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.793 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.454 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.004 ms/op
Iteration   1: 2.462 ±(99.9%) 0.004 ms/op
Iteration   2: 2.499 ±(99.9%) 0.004 ms/op
Iteration   3: 2.472 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.478 ±(99.9%) 0.356 ms/op [Average]
  (min, avg, max) = (2.462, 2.478, 2.499), stdev = 0.020
  CI (99.9%): [2.122, 2.834] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 4.046 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.538 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.443 ±(99.9%) 0.004 ms/op
Iteration   1: 2.462 ±(99.9%) 0.004 ms/op
Iteration   2: 2.460 ±(99.9%) 0.004 ms/op
Iteration   3: 2.455 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.459 ±(99.9%) 0.066 ms/op [Average]
  (min, avg, max) = (2.455, 2.459, 2.462), stdev = 0.004
  CI (99.9%): [2.393, 2.525] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.872 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.047 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.006 ms/op
Iteration   1: 2.980 ±(99.9%) 0.005 ms/op
Iteration   2: 2.993 ±(99.9%) 0.006 ms/op
Iteration   3: 2.997 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.990 ±(99.9%) 0.168 ms/op [Average]
  (min, avg, max) = (2.980, 2.990, 2.997), stdev = 0.009
  CI (99.9%): [2.821, 3.158] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.375 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.671 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.545 ±(99.9%) 0.006 ms/op
Iteration   1: 2.542 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.870 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   3.822 ms/op
                 createUser·p0.999:  11.496 ms/op
                 createUser·p0.9999: 14.481 ms/op
                 createUser·p1.00:   15.254 ms/op

Iteration   2: 2.522 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.735 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.658 ms/op
                 createUser·p0.999:  9.428 ms/op
                 createUser·p0.9999: 13.331 ms/op
                 createUser·p1.00:   14.483 ms/op

Iteration   3: 2.540 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.953 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.785 ms/op
                 createUser·p0.999:  8.703 ms/op
                 createUser·p0.9999: 11.689 ms/op
                 createUser·p1.00:   11.977 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378460
  mean =      2.534 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 181352 
    [ 2.500,  3.750) = 193208 
    [ 3.750,  5.000) = 3094 
    [ 5.000,  6.250) = 335 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 96 
    [10.000, 11.250) = 61 
    [11.250, 12.500) = 112 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.735 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      3.762 ms/op
     p(99.9000) =      8.749 ms/op
     p(99.9900) =     13.779 ms/op
     p(99.9990) =     15.175 ms/op
     p(99.9999) =     15.254 ms/op
    p(100.0000) =     15.254 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.915 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.487 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.470 ±(99.9%) 0.005 ms/op
Iteration   1: 2.483 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.922 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.609 ms/op
                 existUser·p0.999:  8.338 ms/op
                 existUser·p0.9999: 14.778 ms/op
                 existUser·p1.00:   16.384 ms/op

Iteration   2: 2.483 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.085 ms/op
                 existUser·p0.50:   2.585 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.518 ms/op
                 existUser·p0.999:  8.091 ms/op
                 existUser·p0.9999: 13.079 ms/op
                 existUser·p1.00:   13.484 ms/op

Iteration   3: 2.516 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.932 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   3.060 ms/op
                 existUser·p0.95:   3.162 ms/op
                 existUser·p0.99:   3.748 ms/op
                 existUser·p0.999:  8.352 ms/op
                 existUser·p0.9999: 11.452 ms/op
                 existUser·p1.00:   11.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 384583
  mean =      2.494 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 188187 
    [ 2.500,  3.750) = 193089 
    [ 3.750,  5.000) = 2567 
    [ 5.000,  6.250) = 242 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 103 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.922 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.637 ms/op
     p(99.9000) =      8.305 ms/op
     p(99.9900) =     13.853 ms/op
     p(99.9990) =     15.256 ms/op
     p(99.9999) =     16.384 ms/op
    p(100.0000) =     16.384 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.963 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.574 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.534 ±(99.9%) 0.006 ms/op
Iteration   1: 2.491 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.067 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.707 ms/op
                 getUser·p0.999:  10.096 ms/op
                 getUser·p0.9999: 13.386 ms/op
                 getUser·p1.00:   14.107 ms/op

Iteration   2: 2.514 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.968 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.936 ms/op
                 getUser·p0.999:  9.398 ms/op
                 getUser·p0.9999: 13.156 ms/op
                 getUser·p1.00:   13.746 ms/op

Iteration   3: 2.521 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.001 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   3.985 ms/op
                 getUser·p0.999:  8.847 ms/op
                 getUser·p0.9999: 11.140 ms/op
                 getUser·p1.00:   11.600 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382292
  mean =      2.509 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 189017 
    [ 2.500,  3.750) = 188428 
    [ 3.750,  5.000) = 3789 
    [ 5.000,  6.250) = 510 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 115 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.968 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.883 ms/op
     p(99.9000) =      8.859 ms/op
     p(99.9900) =     13.173 ms/op
     p(99.9990) =     13.706 ms/op
     p(99.9999) =     14.107 ms/op
    p(100.0000) =     14.107 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.855 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.082 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.009 ms/op
Iteration   1: 3.010 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.859 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.066 ms/op
                 listUser·p0.9999: 11.059 ms/op
                 listUser·p1.00:   11.583 ms/op

Iteration   2: 3.041 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.943 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.420 ms/op
                 listUser·p0.99:   5.632 ms/op
                 listUser·p0.999:  9.957 ms/op
                 listUser·p0.9999: 13.148 ms/op
                 listUser·p1.00:   14.123 ms/op

Iteration   3: 3.054 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.824 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.470 ms/op
                 listUser·p0.9999: 10.872 ms/op
                 listUser·p1.00:   11.698 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316045
  mean =      3.035 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 114 
    [ 1.250,  2.500) = 87667 
    [ 2.500,  3.750) = 187643 
    [ 3.750,  5.000) = 33291 
    [ 5.000,  6.250) = 5869 
    [ 6.250,  7.500) = 741 
    [ 7.500,  8.750) = 228 
    [ 8.750, 10.000) = 294 
    [10.000, 11.250) = 149 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =      9.585 ms/op
     p(99.9900) =     11.616 ms/op
     p(99.9990) =     13.702 ms/op
     p(99.9999) =     14.123 ms/op
    p(100.0000) =     14.123 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.374 ± 1.938  ops/ms
ClientPb.existUser                       thrpt       3  13.124 ± 0.320  ops/ms
ClientPb.getUser                         thrpt       3  12.910 ± 1.083  ops/ms
ClientPb.listUser                        thrpt       3  10.711 ± 1.184  ops/ms
ClientPb.createUser                       avgt       3   2.527 ± 0.474   ms/op
ClientPb.existUser                        avgt       3   2.478 ± 0.356   ms/op
ClientPb.getUser                          avgt       3   2.459 ± 0.066   ms/op
ClientPb.listUser                         avgt       3   2.990 ± 0.168   ms/op
ClientPb.createUser                     sample  378460   2.534 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.735           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.601           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.080           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.762           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.749           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.779           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.254           ms/op
ClientPb.existUser                      sample  384583   2.494 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.922           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.564           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.031           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.133           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.637           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.305           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.853           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.384           ms/op
ClientPb.getUser                        sample  382292   2.509 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.968           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.527           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.056           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.183           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.883           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.859           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.173           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.107           ms/op
ClientPb.listUser                       sample  316045   3.035 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.824           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.970           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.620           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.585           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.616           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.123           ms/op
