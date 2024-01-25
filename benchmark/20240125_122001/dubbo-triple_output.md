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
# Warmup Iteration   1: 4.720 ops/ms
# Warmup Iteration   2: 12.125 ops/ms
# Warmup Iteration   3: 12.241 ops/ms
Iteration   1: 12.604 ops/ms
Iteration   2: 12.643 ops/ms
Iteration   3: 12.711 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.652 ±(99.9%) 0.986 ops/ms [Average]
  (min, avg, max) = (12.604, 12.652, 12.711), stdev = 0.054
  CI (99.9%): [11.666, 13.639] (assumes normal distribution)


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
# Warmup Iteration   1: 8.247 ops/ms
# Warmup Iteration   2: 12.957 ops/ms
# Warmup Iteration   3: 12.983 ops/ms
Iteration   1: 12.990 ops/ms
Iteration   2: 12.837 ops/ms
Iteration   3: 13.027 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.951 ±(99.9%) 1.833 ops/ms [Average]
  (min, avg, max) = (12.837, 12.951, 13.027), stdev = 0.100
  CI (99.9%): [11.118, 14.785] (assumes normal distribution)


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
# Warmup Iteration   1: 7.592 ops/ms
# Warmup Iteration   2: 12.296 ops/ms
# Warmup Iteration   3: 12.904 ops/ms
Iteration   1: 12.600 ops/ms
Iteration   2: 12.894 ops/ms
Iteration   3: 12.757 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.750 ±(99.9%) 2.689 ops/ms [Average]
  (min, avg, max) = (12.600, 12.750, 12.894), stdev = 0.147
  CI (99.9%): [10.062, 15.439] (assumes normal distribution)


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
# Warmup Iteration   1: 6.629 ops/ms
# Warmup Iteration   2: 10.348 ops/ms
# Warmup Iteration   3: 10.594 ops/ms
Iteration   1: 10.578 ops/ms
Iteration   2: 10.625 ops/ms
Iteration   3: 10.590 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.597 ±(99.9%) 0.445 ops/ms [Average]
  (min, avg, max) = (10.578, 10.597, 10.625), stdev = 0.024
  CI (99.9%): [10.152, 11.043] (assumes normal distribution)


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
# Warmup Iteration   1: 4.058 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.602 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.544 ±(99.9%) 0.004 ms/op
Iteration   1: 2.580 ±(99.9%) 0.004 ms/op
Iteration   2: 2.583 ±(99.9%) 0.004 ms/op
Iteration   3: 2.548 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.570 ±(99.9%) 0.351 ms/op [Average]
  (min, avg, max) = (2.548, 2.570, 2.583), stdev = 0.019
  CI (99.9%): [2.219, 2.922] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.849 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.435 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.457 ±(99.9%) 0.003 ms/op
Iteration   1: 2.440 ±(99.9%) 0.004 ms/op
Iteration   2: 2.436 ±(99.9%) 0.003 ms/op
Iteration   3: 2.486 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.454 ±(99.9%) 0.507 ms/op [Average]
  (min, avg, max) = (2.436, 2.454, 2.486), stdev = 0.028
  CI (99.9%): [1.947, 2.961] (assumes normal distribution)


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
# Warmup Iteration   1: 3.855 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.545 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.506 ±(99.9%) 0.005 ms/op
Iteration   1: 2.471 ±(99.9%) 0.004 ms/op
Iteration   2: 2.442 ±(99.9%) 0.004 ms/op
Iteration   3: 2.471 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.461 ±(99.9%) 0.306 ms/op [Average]
  (min, avg, max) = (2.442, 2.461, 2.471), stdev = 0.017
  CI (99.9%): [2.155, 2.767] (assumes normal distribution)


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
# Warmup Iteration   1: 4.530 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.973 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.958 ±(99.9%) 0.005 ms/op
Iteration   1: 2.944 ±(99.9%) 0.006 ms/op
Iteration   2: 2.959 ±(99.9%) 0.005 ms/op
Iteration   3: 2.945 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.949 ±(99.9%) 0.149 ms/op [Average]
  (min, avg, max) = (2.944, 2.949, 2.959), stdev = 0.008
  CI (99.9%): [2.800, 3.098] (assumes normal distribution)


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
# Warmup Iteration   1: 4.112 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.628 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.006 ms/op
Iteration   1: 2.487 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.022 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.625 ms/op
                 createUser·p0.999:  8.537 ms/op
                 createUser·p0.9999: 13.639 ms/op
                 createUser·p1.00:   14.746 ms/op

Iteration   2: 2.519 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.909 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.920 ms/op
                 createUser·p0.999:  9.431 ms/op
                 createUser·p0.9999: 12.468 ms/op
                 createUser·p1.00:   12.927 ms/op

Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.937 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.768 ms/op
                 createUser·p0.999:  7.969 ms/op
                 createUser·p0.9999: 11.033 ms/op
                 createUser·p1.00:   11.387 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383557
  mean =      2.501 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 187462 
    [ 2.500,  3.750) = 191991 
    [ 3.750,  5.000) = 3084 
    [ 5.000,  6.250) = 528 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 117 
    [11.250, 12.500) = 99 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.909 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.785 ms/op
     p(99.9000) =      7.978 ms/op
     p(99.9900) =     12.796 ms/op
     p(99.9990) =     14.126 ms/op
     p(99.9999) =     14.746 ms/op
    p(100.0000) =     14.746 ms/op


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
# Warmup Iteration   1: 3.536 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.401 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.390 ±(99.9%) 0.005 ms/op
Iteration   1: 2.384 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.801 ms/op
                 existUser·p0.50:   2.429 ms/op
                 existUser·p0.90:   2.912 ms/op
                 existUser·p0.95:   3.019 ms/op
                 existUser·p0.99:   3.490 ms/op
                 existUser·p0.999:  5.210 ms/op
                 existUser·p0.9999: 13.136 ms/op
                 existUser·p1.00:   14.025 ms/op

Iteration   2: 2.392 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.895 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.900 ms/op
                 existUser·p0.95:   3.015 ms/op
                 existUser·p0.99:   3.637 ms/op
                 existUser·p0.999:  6.536 ms/op
                 existUser·p0.9999: 14.504 ms/op
                 existUser·p1.00:   14.991 ms/op

Iteration   3: 2.402 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.748 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   2.929 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.588 ms/op
                 existUser·p0.999:  6.077 ms/op
                 existUser·p0.9999: 11.338 ms/op
                 existUser·p1.00:   12.534 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 400798
  mean =      2.393 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 90 
    [ 1.250,  2.500) = 206410 
    [ 2.500,  3.750) = 191444 
    [ 3.750,  5.000) = 2290 
    [ 5.000,  6.250) = 200 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 83 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      2.454 ms/op
     p(90.0000) =      2.912 ms/op
     p(95.0000) =      3.027 ms/op
     p(99.0000) =      3.568 ms/op
     p(99.9000) =      5.687 ms/op
     p(99.9900) =     13.427 ms/op
     p(99.9990) =     14.794 ms/op
     p(99.9999) =     14.991 ms/op
    p(100.0000) =     14.991 ms/op


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
# Warmup Iteration   1: 3.961 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.549 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.472 ±(99.9%) 0.005 ms/op
Iteration   1: 2.490 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.764 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.756 ms/op
                 getUser·p0.999:  8.853 ms/op
                 getUser·p0.9999: 13.626 ms/op
                 getUser·p1.00:   14.041 ms/op

Iteration   2: 2.464 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.901 ms/op
                 getUser·p0.50:   2.466 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.117 ms/op
                 getUser·p0.99:   3.662 ms/op
                 getUser·p0.999:  5.948 ms/op
                 getUser·p0.9999: 12.043 ms/op
                 getUser·p1.00:   12.911 ms/op

Iteration   3: 2.479 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.961 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   3.985 ms/op
                 getUser·p0.999:  6.833 ms/op
                 getUser·p0.9999: 11.159 ms/op
                 getUser·p1.00:   12.059 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387163
  mean =      2.478 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 194042 
    [ 2.500,  3.750) = 188927 
    [ 3.750,  5.000) = 3368 
    [ 5.000,  6.250) = 330 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 89 
    [10.000, 11.250) = 109 
    [11.250, 12.500) = 84 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.764 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.793 ms/op
     p(99.9000) =      6.750 ms/op
     p(99.9900) =     12.840 ms/op
     p(99.9990) =     13.978 ms/op
     p(99.9999) =     14.041 ms/op
    p(100.0000) =     14.041 ms/op


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
# Warmup Iteration   1: 4.563 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.041 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.965 ±(99.9%) 0.008 ms/op
Iteration   1: 2.966 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.816 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.093 ms/op
                 listUser·p0.9999: 10.524 ms/op
                 listUser·p1.00:   11.321 ms/op

Iteration   2: 2.968 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.828 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.419 ms/op
                 listUser·p0.999:  9.339 ms/op
                 listUser·p0.9999: 10.817 ms/op
                 listUser·p1.00:   11.174 ms/op

Iteration   3: 2.948 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.900 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.789 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   5.407 ms/op
                 listUser·p0.999:  9.020 ms/op
                 listUser·p0.9999: 11.289 ms/op
                 listUser·p1.00:   12.075 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323989
  mean =      2.960 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 167 
    [ 1.250,  2.500) = 100102 
    [ 2.500,  3.750) = 187466 
    [ 3.750,  5.000) = 29445 
    [ 5.000,  6.250) = 5487 
    [ 6.250,  7.500) = 635 
    [ 7.500,  8.750) = 306 
    [ 8.750, 10.000) = 243 
    [10.000, 11.250) = 126 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.816 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =      9.126 ms/op
     p(99.9900) =     10.807 ms/op
     p(99.9990) =     11.940 ms/op
     p(99.9999) =     12.075 ms/op
    p(100.0000) =     12.075 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.652 ± 0.986  ops/ms
ClientPb.existUser                       thrpt       3  12.951 ± 1.833  ops/ms
ClientPb.getUser                         thrpt       3  12.750 ± 2.689  ops/ms
ClientPb.listUser                        thrpt       3  10.597 ± 0.445  ops/ms
ClientPb.createUser                       avgt       3   2.570 ± 0.351   ms/op
ClientPb.existUser                        avgt       3   2.454 ± 0.507   ms/op
ClientPb.getUser                          avgt       3   2.461 ± 0.306   ms/op
ClientPb.listUser                         avgt       3   2.949 ± 0.149   ms/op
ClientPb.createUser                     sample  383557   2.501 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.909           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.552           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.039           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.785           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.978           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.796           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.746           ms/op
ClientPb.existUser                      sample  400798   2.393 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.748           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.454           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.912           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.027           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.568           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.687           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.427           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.991           ms/op
ClientPb.getUser                        sample  387163   2.478 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.764           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.494           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.019           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.133           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.793           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.750           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.840           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.041           ms/op
ClientPb.listUser                       sample  323989   2.960 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.816           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.896           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.830           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.489           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.126           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.807           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.075           ms/op
