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
# Warmup Iteration   1: 4.902 ops/ms
# Warmup Iteration   2: 12.025 ops/ms
# Warmup Iteration   3: 12.268 ops/ms
Iteration   1: 12.297 ops/ms
Iteration   2: 12.673 ops/ms
Iteration   3: 12.663 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.544 ±(99.9%) 3.905 ops/ms [Average]
  (min, avg, max) = (12.297, 12.544, 12.673), stdev = 0.214
  CI (99.9%): [8.639, 16.449] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.933 ops/ms
# Warmup Iteration   2: 12.881 ops/ms
# Warmup Iteration   3: 12.953 ops/ms
Iteration   1: 13.170 ops/ms
Iteration   2: 13.142 ops/ms
Iteration   3: 12.979 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.097 ±(99.9%) 1.878 ops/ms [Average]
  (min, avg, max) = (12.979, 13.097, 13.170), stdev = 0.103
  CI (99.9%): [11.220, 14.975] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.638 ops/ms
# Warmup Iteration   2: 12.803 ops/ms
# Warmup Iteration   3: 12.961 ops/ms
Iteration   1: 13.145 ops/ms
Iteration   2: 13.013 ops/ms
Iteration   3: 12.972 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.043 ±(99.9%) 1.650 ops/ms [Average]
  (min, avg, max) = (12.972, 13.043, 13.145), stdev = 0.090
  CI (99.9%): [11.393, 14.694] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.704 ops/ms
# Warmup Iteration   2: 10.537 ops/ms
# Warmup Iteration   3: 10.652 ops/ms
Iteration   1: 10.606 ops/ms
Iteration   2: 10.591 ops/ms
Iteration   3: 10.718 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.638 ±(99.9%) 1.269 ops/ms [Average]
  (min, avg, max) = (10.591, 10.638, 10.718), stdev = 0.070
  CI (99.9%): [9.369, 11.908] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.051 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.593 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.509 ±(99.9%) 0.004 ms/op
Iteration   1: 2.609 ±(99.9%) 0.003 ms/op
Iteration   2: 2.520 ±(99.9%) 0.004 ms/op
Iteration   3: 2.498 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.542 ±(99.9%) 1.080 ms/op [Average]
  (min, avg, max) = (2.498, 2.542, 2.609), stdev = 0.059
  CI (99.9%): [1.463, 3.622] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.721 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.467 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.442 ±(99.9%) 0.004 ms/op
Iteration   1: 2.466 ±(99.9%) 0.003 ms/op
Iteration   2: 2.441 ±(99.9%) 0.004 ms/op
Iteration   3: 2.437 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.448 ±(99.9%) 0.284 ms/op [Average]
  (min, avg, max) = (2.437, 2.448, 2.466), stdev = 0.016
  CI (99.9%): [2.163, 2.732] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.871 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.537 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.488 ±(99.9%) 0.004 ms/op
Iteration   1: 2.500 ±(99.9%) 0.003 ms/op
Iteration   2: 2.488 ±(99.9%) 0.003 ms/op
Iteration   3: 2.479 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.489 ±(99.9%) 0.187 ms/op [Average]
  (min, avg, max) = (2.479, 2.489, 2.500), stdev = 0.010
  CI (99.9%): [2.302, 2.676] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.617 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.081 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.006 ms/op
Iteration   1: 3.028 ±(99.9%) 0.005 ms/op
Iteration   2: 3.022 ±(99.9%) 0.005 ms/op
Iteration   3: 3.035 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.028 ±(99.9%) 0.119 ms/op [Average]
  (min, avg, max) = (3.022, 3.028, 3.035), stdev = 0.007
  CI (99.9%): [2.910, 3.147] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.058 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.630 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.494 ±(99.9%) 0.006 ms/op
Iteration   1: 2.483 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.853 ms/op
                 createUser·p0.50:   2.531 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.793 ms/op
                 createUser·p0.999:  7.706 ms/op
                 createUser·p0.9999: 13.189 ms/op
                 createUser·p1.00:   14.287 ms/op

Iteration   2: 2.474 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.035 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.629 ms/op
                 createUser·p0.999:  6.114 ms/op
                 createUser·p0.9999: 12.585 ms/op
                 createUser·p1.00:   12.845 ms/op

Iteration   3: 2.492 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.986 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.871 ms/op
                 createUser·p0.999:  8.364 ms/op
                 createUser·p0.9999: 11.600 ms/op
                 createUser·p1.00:   12.124 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 386347
  mean =      2.483 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 188481 
    [ 2.500,  3.750) = 193917 
    [ 3.750,  5.000) = 3132 
    [ 5.000,  6.250) = 264 
    [ 6.250,  7.500) = 85 
    [ 7.500,  8.750) = 72 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 82 
    [11.250, 12.500) = 112 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.853 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.756 ms/op
     p(99.9000) =      8.348 ms/op
     p(99.9900) =     12.861 ms/op
     p(99.9990) =     14.025 ms/op
     p(99.9999) =     14.287 ms/op
    p(100.0000) =     14.287 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.759 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.457 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.450 ±(99.9%) 0.005 ms/op
Iteration   1: 2.431 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.880 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.592 ms/op
                 existUser·p0.999:  5.554 ms/op
                 existUser·p0.9999: 13.350 ms/op
                 existUser·p1.00:   14.090 ms/op

Iteration   2: 2.416 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.915 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.920 ms/op
                 existUser·p0.95:   3.002 ms/op
                 existUser·p0.99:   3.453 ms/op
                 existUser·p0.999:  6.054 ms/op
                 existUser·p0.9999: 13.697 ms/op
                 existUser·p1.00:   14.565 ms/op

Iteration   3: 2.437 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.002 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.645 ms/op
                 existUser·p0.999:  7.180 ms/op
                 existUser·p0.9999: 14.352 ms/op
                 existUser·p1.00:   14.615 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 395035
  mean =      2.428 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 197846 
    [ 2.500,  3.750) = 194217 
    [ 3.750,  5.000) = 2284 
    [ 5.000,  6.250) = 226 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 91 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.880 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      2.945 ms/op
     p(95.0000) =      3.047 ms/op
     p(99.0000) =      3.572 ms/op
     p(99.9000) =      6.586 ms/op
     p(99.9900) =     13.615 ms/op
     p(99.9990) =     14.503 ms/op
     p(99.9999) =     14.615 ms/op
    p(100.0000) =     14.615 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.886 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.544 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.006 ms/op
Iteration   1: 2.477 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.908 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.764 ms/op
                 getUser·p0.999:  6.482 ms/op
                 getUser·p0.9999: 13.780 ms/op
                 getUser·p1.00:   14.139 ms/op

Iteration   2: 2.528 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.047 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   4.202 ms/op
                 getUser·p0.999:  8.766 ms/op
                 getUser·p0.9999: 13.304 ms/op
                 getUser·p1.00:   13.697 ms/op

Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.941 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.756 ms/op
                 getUser·p0.999:  8.532 ms/op
                 getUser·p0.9999: 13.881 ms/op
                 getUser·p1.00:   14.582 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383640
  mean =      2.500 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 78 
    [ 1.250,  2.500) = 190449 
    [ 2.500,  3.750) = 188149 
    [ 3.750,  5.000) = 3948 
    [ 5.000,  6.250) = 566 
    [ 6.250,  7.500) = 66 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 80 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 116 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.908 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.920 ms/op
     p(99.9000) =      8.722 ms/op
     p(99.9900) =     13.626 ms/op
     p(99.9990) =     14.483 ms/op
     p(99.9999) =     14.582 ms/op
    p(100.0000) =     14.582 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.805 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.098 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.008 ms/op
Iteration   1: 3.031 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.590 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  8.774 ms/op
                 listUser·p0.9999: 10.355 ms/op
                 listUser·p1.00:   10.748 ms/op

Iteration   2: 3.017 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.743 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.519 ms/op
                 listUser·p0.9999: 11.476 ms/op
                 listUser·p1.00:   12.173 ms/op

Iteration   3: 3.013 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.997 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  8.700 ms/op
                 listUser·p0.9999: 10.387 ms/op
                 listUser·p1.00:   10.715 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317538
  mean =      3.020 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 124 
    [ 1.250,  2.500) = 90787 
    [ 2.500,  3.750) = 186047 
    [ 3.750,  5.000) = 33320 
    [ 5.000,  6.250) = 5966 
    [ 6.250,  7.500) = 691 
    [ 7.500,  8.750) = 231 
    [ 8.750, 10.000) = 241 
    [10.000, 11.250) = 113 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.590 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =      9.028 ms/op
     p(99.9900) =     11.026 ms/op
     p(99.9990) =     12.107 ms/op
     p(99.9999) =     12.173 ms/op
    p(100.0000) =     12.173 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.544 ± 3.905  ops/ms
ClientPb.existUser                       thrpt       3  13.097 ± 1.878  ops/ms
ClientPb.getUser                         thrpt       3  13.043 ± 1.650  ops/ms
ClientPb.listUser                        thrpt       3  10.638 ± 1.269  ops/ms
ClientPb.createUser                       avgt       3   2.542 ± 1.080   ms/op
ClientPb.existUser                        avgt       3   2.448 ± 0.284   ms/op
ClientPb.getUser                          avgt       3   2.489 ± 0.187   ms/op
ClientPb.listUser                         avgt       3   3.028 ± 0.119   ms/op
ClientPb.createUser                     sample  386347   2.483 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.853           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.548           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.019           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.146           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.756           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.348           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.861           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.287           ms/op
ClientPb.existUser                      sample  395035   2.428 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.880           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.494           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.945           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.572           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.586           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.615           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.615           ms/op
ClientPb.getUser                        sample  383640   2.500 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.908           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.515           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.052           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.187           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.920           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.722           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.626           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.582           ms/op
ClientPb.listUser                       sample  317538   3.020 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.590           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.920           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.554           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.028           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.026           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.173           ms/op
