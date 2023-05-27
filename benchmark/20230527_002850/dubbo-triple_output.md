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
# Warmup Iteration   1: 2.001 ops/ms
# Warmup Iteration   2: 5.141 ops/ms
# Warmup Iteration   3: 8.418 ops/ms
Iteration   1: 9.223 ops/ms
Iteration   2: 9.063 ops/ms
Iteration   3: 9.142 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.143 ±(99.9%) 1.464 ops/ms [Average]
  (min, avg, max) = (9.063, 9.143, 9.223), stdev = 0.080
  CI (99.9%): [7.679, 10.606] (assumes normal distribution)


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
# Warmup Iteration   1: 3.266 ops/ms
# Warmup Iteration   2: 8.863 ops/ms
# Warmup Iteration   3: 9.353 ops/ms
Iteration   1: 9.856 ops/ms
Iteration   2: 9.577 ops/ms
Iteration   3: 9.571 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.668 ±(99.9%) 2.966 ops/ms [Average]
  (min, avg, max) = (9.571, 9.668, 9.856), stdev = 0.163
  CI (99.9%): [6.702, 12.634] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.373 ops/ms
# Warmup Iteration   2: 8.672 ops/ms
# Warmup Iteration   3: 9.146 ops/ms
Iteration   1: 9.555 ops/ms
Iteration   2: 9.266 ops/ms
Iteration   3: 9.519 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.447 ±(99.9%) 2.867 ops/ms [Average]
  (min, avg, max) = (9.266, 9.447, 9.555), stdev = 0.157
  CI (99.9%): [6.580, 12.313] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.014 ops/ms
# Warmup Iteration   2: 7.405 ops/ms
# Warmup Iteration   3: 8.111 ops/ms
Iteration   1: 8.160 ops/ms
Iteration   2: 8.295 ops/ms
Iteration   3: 8.253 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.236 ±(99.9%) 1.263 ops/ms [Average]
  (min, avg, max) = (8.160, 8.236, 8.295), stdev = 0.069
  CI (99.9%): [6.973, 9.499] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.362 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.732 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.490 ±(99.9%) 0.004 ms/op
Iteration   1: 3.293 ±(99.9%) 0.008 ms/op
Iteration   2: 3.269 ±(99.9%) 0.009 ms/op
Iteration   3: 3.327 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.296 ±(99.9%) 0.532 ms/op [Average]
  (min, avg, max) = (3.269, 3.296, 3.327), stdev = 0.029
  CI (99.9%): [2.765, 3.828] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 9.283 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.515 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.243 ±(99.9%) 0.008 ms/op
Iteration   1: 3.290 ±(99.9%) 0.010 ms/op
Iteration   2: 3.203 ±(99.9%) 0.005 ms/op
Iteration   3: 3.255 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.249 ±(99.9%) 0.799 ms/op [Average]
  (min, avg, max) = (3.203, 3.249, 3.290), stdev = 0.044
  CI (99.9%): [2.450, 4.049] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.899 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.813 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.494 ±(99.9%) 0.005 ms/op
Iteration   1: 3.460 ±(99.9%) 0.004 ms/op
Iteration   2: 3.427 ±(99.9%) 0.003 ms/op
Iteration   3: 3.360 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.416 ±(99.9%) 0.928 ms/op [Average]
  (min, avg, max) = (3.360, 3.416, 3.460), stdev = 0.051
  CI (99.9%): [2.488, 4.344] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.350 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.339 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.074 ±(99.9%) 0.009 ms/op
Iteration   1: 3.893 ±(99.9%) 0.010 ms/op
Iteration   2: 4.010 ±(99.9%) 0.008 ms/op
Iteration   3: 4.082 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.995 ±(99.9%) 1.746 ms/op [Average]
  (min, avg, max) = (3.893, 3.995, 4.082), stdev = 0.096
  CI (99.9%): [2.249, 5.741] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.712 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 4.264 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.497 ±(99.9%) 0.011 ms/op
Iteration   1: 3.374 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.630 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   4.051 ms/op
                 createUser·p0.99:   6.139 ms/op
                 createUser·p0.999:  18.358 ms/op
                 createUser·p0.9999: 23.857 ms/op
                 createUser·p1.00:   24.674 ms/op

Iteration   2: 3.507 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.555 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   4.129 ms/op
                 createUser·p0.95:   5.079 ms/op
                 createUser·p0.99:   6.087 ms/op
                 createUser·p0.999:  19.482 ms/op
                 createUser·p0.9999: 23.720 ms/op
                 createUser·p1.00:   24.576 ms/op

Iteration   3: 3.552 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.534 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   4.252 ms/op
                 createUser·p0.95:   4.678 ms/op
                 createUser·p0.99:   6.431 ms/op
                 createUser·p0.999:  16.482 ms/op
                 createUser·p0.9999: 29.753 ms/op
                 createUser·p1.00:   30.114 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276070
  mean =      3.476 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9638 
    [ 2.500,  5.000) = 255736 
    [ 5.000,  7.500) = 9379 
    [ 7.500, 10.000) = 790 
    [10.000, 12.500) = 181 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 133 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      4.051 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      6.204 ms/op
     p(99.9000) =     16.843 ms/op
     p(99.9900) =     28.993 ms/op
     p(99.9990) =     29.958 ms/op
     p(99.9999) =     30.114 ms/op
    p(100.0000) =     30.114 ms/op


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
# Warmup Iteration   1: 8.510 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.700 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.431 ±(99.9%) 0.009 ms/op
Iteration   1: 3.379 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.466 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   3.875 ms/op
                 existUser·p0.95:   4.301 ms/op
                 existUser·p0.99:   5.431 ms/op
                 existUser·p0.999:  13.840 ms/op
                 existUser·p0.9999: 20.762 ms/op
                 existUser·p1.00:   22.544 ms/op

Iteration   2: 3.288 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.321 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   5.546 ms/op
                 existUser·p0.999:  17.718 ms/op
                 existUser·p0.9999: 27.248 ms/op
                 existUser·p1.00:   27.787 ms/op

Iteration   3: 3.323 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.591 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   5.562 ms/op
                 existUser·p0.999:  14.960 ms/op
                 existUser·p0.9999: 26.729 ms/op
                 existUser·p1.00:   28.148 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288313
  mean =      3.330 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17492 
    [ 2.500,  5.000) = 266299 
    [ 5.000,  7.500) = 3569 
    [ 7.500, 10.000) = 486 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 50 

  Percentiles, ms/op:
      p(0.0000) =      1.321 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      4.063 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =     13.921 ms/op
     p(99.9900) =     26.422 ms/op
     p(99.9990) =     27.758 ms/op
     p(99.9999) =     28.148 ms/op
    p(100.0000) =     28.148 ms/op


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
# Warmup Iteration   1: 10.271 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 3.967 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.427 ±(99.9%) 0.010 ms/op
Iteration   1: 3.452 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.110 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.883 ms/op
                 getUser·p0.95:   5.145 ms/op
                 getUser·p0.99:   6.562 ms/op
                 getUser·p0.999:  19.211 ms/op
                 getUser·p0.9999: 22.565 ms/op
                 getUser·p1.00:   24.150 ms/op

Iteration   2: 3.404 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.444 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   5.715 ms/op
                 getUser·p0.999:  21.006 ms/op
                 getUser·p0.9999: 24.301 ms/op
                 getUser·p1.00:   24.969 ms/op

Iteration   3: 3.371 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.853 ms/op
                 getUser·p0.50:   3.260 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   5.857 ms/op
                 getUser·p0.999:  16.181 ms/op
                 getUser·p0.9999: 26.608 ms/op
                 getUser·p1.00:   27.689 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 281500
  mean =      3.409 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2089 
    [ 2.500,  5.000) = 271174 
    [ 5.000,  7.500) = 7172 
    [ 7.500, 10.000) = 610 
    [10.000, 12.500) = 133 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 101 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.110 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      4.047 ms/op
     p(99.0000) =      6.201 ms/op
     p(99.9000) =     16.613 ms/op
     p(99.9900) =     25.461 ms/op
     p(99.9990) =     27.359 ms/op
     p(99.9999) =     27.689 ms/op
    p(100.0000) =     27.689 ms/op


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
# Warmup Iteration   1: 9.952 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.231 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.075 ±(99.9%) 0.011 ms/op
Iteration   1: 4.049 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.425 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.676 ms/op
                 listUser·p0.99:   7.979 ms/op
                 listUser·p0.999:  17.104 ms/op
                 listUser·p0.9999: 25.375 ms/op
                 listUser·p1.00:   26.018 ms/op

Iteration   2: 3.905 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.241 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   6.613 ms/op
                 listUser·p0.999:  14.844 ms/op
                 listUser·p0.9999: 23.471 ms/op
                 listUser·p1.00:   24.019 ms/op

Iteration   3: 4.037 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.281 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   7.129 ms/op
                 listUser·p0.999:  14.272 ms/op
                 listUser·p0.9999: 17.009 ms/op
                 listUser·p1.00:   17.203 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240073
  mean =      3.996 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47 
    [ 2.500,  5.000) = 232852 
    [ 5.000,  7.500) = 4965 
    [ 7.500, 10.000) = 1413 
    [10.000, 12.500) = 229 
    [12.500, 15.000) = 351 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.425 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      7.356 ms/op
     p(99.9000) =     14.825 ms/op
     p(99.9900) =     24.671 ms/op
     p(99.9990) =     25.788 ms/op
     p(99.9999) =     26.018 ms/op
    p(100.0000) =     26.018 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.143 ± 1.464  ops/ms
ClientPb.existUser                       thrpt       3   9.668 ± 2.966  ops/ms
ClientPb.getUser                         thrpt       3   9.447 ± 2.867  ops/ms
ClientPb.listUser                        thrpt       3   8.236 ± 1.263  ops/ms
ClientPb.createUser                       avgt       3   3.296 ± 0.532   ms/op
ClientPb.existUser                        avgt       3   3.249 ± 0.799   ms/op
ClientPb.getUser                          avgt       3   3.416 ± 0.928   ms/op
ClientPb.listUser                         avgt       3   3.995 ± 1.746   ms/op
ClientPb.createUser                     sample  276070   3.476 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.555           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.351           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.051           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.604           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.204           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.843           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.993           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.114           ms/op
ClientPb.existUser                      sample  288313   3.330 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.321           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.269           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.703           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.063           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.530           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.921           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.422           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.148           ms/op
ClientPb.getUser                        sample  281500   3.409 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.110           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.269           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.744           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.047           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.201           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.613           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.461           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.689           ms/op
ClientPb.listUser                       sample  240073   3.996 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.425           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.895           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.547           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.356           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.825           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.671           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.018           ms/op
