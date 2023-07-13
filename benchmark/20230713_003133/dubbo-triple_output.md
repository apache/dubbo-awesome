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
# Warmup Iteration   1: 1.324 ops/ms
# Warmup Iteration   2: 2.961 ops/ms
# Warmup Iteration   3: 5.653 ops/ms
Iteration   1: 5.706 ops/ms
Iteration   2: 6.117 ops/ms
Iteration   3: 6.298 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.040 ±(99.9%) 5.538 ops/ms [Average]
  (min, avg, max) = (5.706, 6.040, 6.298), stdev = 0.304
  CI (99.9%): [0.502, 11.578] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 1.824 ops/ms
# Warmup Iteration   2: 5.274 ops/ms
# Warmup Iteration   3: 6.288 ops/ms
Iteration   1: 6.281 ops/ms
Iteration   2: 6.241 ops/ms
Iteration   3: 6.491 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.338 ±(99.9%) 2.454 ops/ms [Average]
  (min, avg, max) = (6.241, 6.338, 6.491), stdev = 0.134
  CI (99.9%): [3.884, 8.792] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.674 ops/ms
# Warmup Iteration   2: 5.059 ops/ms
# Warmup Iteration   3: 5.648 ops/ms
Iteration   1: 5.415 ops/ms
Iteration   2: 5.973 ops/ms
Iteration   3: 5.705 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.698 ±(99.9%) 5.096 ops/ms [Average]
  (min, avg, max) = (5.415, 5.698, 5.973), stdev = 0.279
  CI (99.9%): [0.601, 10.794] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.728 ops/ms
# Warmup Iteration   2: 4.593 ops/ms
# Warmup Iteration   3: 5.212 ops/ms
Iteration   1: 5.177 ops/ms
Iteration   2: 5.371 ops/ms
Iteration   3: 5.176 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.241 ±(99.9%) 2.047 ops/ms [Average]
  (min, avg, max) = (5.176, 5.241, 5.371), stdev = 0.112
  CI (99.9%): [3.195, 7.288] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 16.195 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 6.280 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.622 ±(99.9%) 0.016 ms/op
Iteration   1: 5.627 ±(99.9%) 0.008 ms/op
Iteration   2: 5.322 ±(99.9%) 0.014 ms/op
Iteration   3: 5.651 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.533 ±(99.9%) 3.344 ms/op [Average]
  (min, avg, max) = (5.322, 5.533, 5.651), stdev = 0.183
  CI (99.9%): [2.189, 8.877] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 16.563 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 6.091 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.166 ±(99.9%) 0.005 ms/op
Iteration   1: 5.320 ±(99.9%) 0.009 ms/op
Iteration   2: 4.989 ±(99.9%) 0.012 ms/op
Iteration   3: 5.232 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.181 ±(99.9%) 3.127 ms/op [Average]
  (min, avg, max) = (4.989, 5.181, 5.320), stdev = 0.171
  CI (99.9%): [2.054, 8.307] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 16.158 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 6.120 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.529 ±(99.9%) 0.011 ms/op
Iteration   1: 5.502 ±(99.9%) 0.010 ms/op
Iteration   2: 5.477 ±(99.9%) 0.015 ms/op
Iteration   3: 5.428 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.469 ±(99.9%) 0.692 ms/op [Average]
  (min, avg, max) = (5.428, 5.469, 5.502), stdev = 0.038
  CI (99.9%): [4.777, 6.161] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 18.315 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 7.680 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 6.055 ±(99.9%) 0.010 ms/op
Iteration   1: 6.133 ±(99.9%) 0.015 ms/op
Iteration   2: 6.074 ±(99.9%) 0.016 ms/op
Iteration   3: 6.290 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.166 ±(99.9%) 2.038 ms/op [Average]
  (min, avg, max) = (6.074, 6.166, 6.290), stdev = 0.112
  CI (99.9%): [4.127, 8.204] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 15.717 ±(99.9%) 0.241 ms/op
# Warmup Iteration   2: 6.304 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.864 ±(99.9%) 0.024 ms/op
Iteration   1: 5.469 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.404 ms/op
                 createUser·p0.50:   5.128 ms/op
                 createUser·p0.90:   6.775 ms/op
                 createUser·p0.95:   7.594 ms/op
                 createUser·p0.99:   9.788 ms/op
                 createUser·p0.999:  23.181 ms/op
                 createUser·p0.9999: 26.749 ms/op
                 createUser·p1.00:   27.984 ms/op

Iteration   2: 5.521 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.388 ms/op
                 createUser·p0.50:   5.210 ms/op
                 createUser·p0.90:   7.021 ms/op
                 createUser·p0.95:   7.676 ms/op
                 createUser·p0.99:   9.600 ms/op
                 createUser·p0.999:  26.054 ms/op
                 createUser·p0.9999: 29.577 ms/op
                 createUser·p1.00:   30.212 ms/op

Iteration   3: 5.323 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.849 ms/op
                 createUser·p0.50:   5.087 ms/op
                 createUser·p0.90:   6.439 ms/op
                 createUser·p0.95:   7.160 ms/op
                 createUser·p0.99:   9.372 ms/op
                 createUser·p0.999:  28.899 ms/op
                 createUser·p0.9999: 33.292 ms/op
                 createUser·p1.00:   34.800 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 176530
  mean =      5.436 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28 
    [ 2.500,  5.000) = 78807 
    [ 5.000,  7.500) = 88603 
    [ 7.500, 10.000) = 7721 
    [10.000, 12.500) = 948 
    [12.500, 15.000) = 176 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 49 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.849 ms/op
     p(50.0000) =      5.136 ms/op
     p(90.0000) =      6.783 ms/op
     p(95.0000) =      7.537 ms/op
     p(99.0000) =      9.601 ms/op
     p(99.9000) =     23.477 ms/op
     p(99.9900) =     30.813 ms/op
     p(99.9990) =     33.997 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 14.509 ±(99.9%) 0.251 ms/op
# Warmup Iteration   2: 5.549 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.117 ±(99.9%) 0.018 ms/op
Iteration   1: 5.064 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.523 ms/op
                 existUser·p0.50:   4.678 ms/op
                 existUser·p0.90:   6.545 ms/op
                 existUser·p0.95:   7.209 ms/op
                 existUser·p0.99:   9.552 ms/op
                 existUser·p0.999:  22.989 ms/op
                 existUser·p0.9999: 41.992 ms/op
                 existUser·p1.00:   42.729 ms/op

Iteration   2: 5.224 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.109 ms/op
                 existUser·p0.50:   5.022 ms/op
                 existUser·p0.90:   6.504 ms/op
                 existUser·p0.95:   7.438 ms/op
                 existUser·p0.99:   9.585 ms/op
                 existUser·p0.999:  14.483 ms/op
                 existUser·p0.9999: 29.742 ms/op
                 existUser·p1.00:   31.752 ms/op

Iteration   3: 5.056 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.661 ms/op
                 existUser·p0.50:   4.784 ms/op
                 existUser·p0.90:   6.308 ms/op
                 existUser·p0.95:   6.996 ms/op
                 existUser·p0.99:   9.193 ms/op
                 existUser·p0.999:  25.749 ms/op
                 existUser·p0.9999: 28.410 ms/op
                 existUser·p1.00:   30.605 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 187607
  mean =      5.113 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 107546 
    [ 5.000, 10.000) = 78890 
    [10.000, 15.000) = 957 
    [15.000, 20.000) = 52 
    [20.000, 25.000) = 34 
    [25.000, 30.000) = 88 
    [30.000, 35.000) = 8 
    [35.000, 40.000) = 17 
    [40.000, 45.000) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.661 ms/op
     p(50.0000) =      4.825 ms/op
     p(90.0000) =      6.447 ms/op
     p(95.0000) =      7.217 ms/op
     p(99.0000) =      9.404 ms/op
     p(99.9000) =     17.373 ms/op
     p(99.9900) =     39.977 ms/op
     p(99.9990) =     42.672 ms/op
     p(99.9999) =     42.729 ms/op
    p(100.0000) =     42.729 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 14.989 ±(99.9%) 0.206 ms/op
# Warmup Iteration   2: 6.053 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.536 ±(99.9%) 0.020 ms/op
Iteration   1: 5.876 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   1.274 ms/op
                 getUser·p0.50:   5.439 ms/op
                 getUser·p0.90:   7.414 ms/op
                 getUser·p0.95:   8.602 ms/op
                 getUser·p0.99:   13.402 ms/op
                 getUser·p0.999:  23.972 ms/op
                 getUser·p0.9999: 32.466 ms/op
                 getUser·p1.00:   34.537 ms/op

Iteration   2: 5.476 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.450 ms/op
                 getUser·p0.50:   5.226 ms/op
                 getUser·p0.90:   6.758 ms/op
                 getUser·p0.95:   7.627 ms/op
                 getUser·p0.99:   9.667 ms/op
                 getUser·p0.999:  22.863 ms/op
                 getUser·p0.9999: 26.131 ms/op
                 getUser·p1.00:   27.197 ms/op

Iteration   3: 5.530 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.535 ms/op
                 getUser·p0.50:   5.284 ms/op
                 getUser·p0.90:   6.898 ms/op
                 getUser·p0.95:   7.668 ms/op
                 getUser·p0.99:   9.604 ms/op
                 getUser·p0.999:  13.209 ms/op
                 getUser·p0.9999: 28.253 ms/op
                 getUser·p1.00:   30.310 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 170595
  mean =      5.622 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 57300 
    [ 5.000,  7.500) = 101659 
    [ 7.500, 10.000) = 9093 
    [10.000, 12.500) = 1488 
    [12.500, 15.000) = 582 
    [15.000, 17.500) = 142 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.274 ms/op
     p(50.0000) =      5.317 ms/op
     p(90.0000) =      7.021 ms/op
     p(95.0000) =      7.938 ms/op
     p(99.0000) =     10.961 ms/op
     p(99.9000) =     22.970 ms/op
     p(99.9900) =     30.649 ms/op
     p(99.9990) =     33.982 ms/op
     p(99.9999) =     34.537 ms/op
    p(100.0000) =     34.537 ms/op


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
# Warmup Iteration   1: 18.190 ±(99.9%) 0.283 ms/op
# Warmup Iteration   2: 6.958 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 6.538 ±(99.9%) 0.030 ms/op
Iteration   1: 6.211 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.007 ms/op
                 listUser·p0.50:   5.874 ms/op
                 listUser·p0.90:   7.388 ms/op
                 listUser·p0.95:   8.454 ms/op
                 listUser·p0.99:   11.469 ms/op
                 listUser·p0.999:  25.567 ms/op
                 listUser·p0.9999: 31.256 ms/op
                 listUser·p1.00:   31.425 ms/op

Iteration   2: 6.210 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.976 ms/op
                 listUser·p0.50:   5.988 ms/op
                 listUser·p0.90:   7.381 ms/op
                 listUser·p0.95:   8.503 ms/op
                 listUser·p0.99:   11.747 ms/op
                 listUser·p0.999:  27.075 ms/op
                 listUser·p0.9999: 30.950 ms/op
                 listUser·p1.00:   31.556 ms/op

Iteration   3: 6.103 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.331 ms/op
                 listUser·p0.50:   5.693 ms/op
                 listUser·p0.90:   7.406 ms/op
                 listUser·p0.95:   8.454 ms/op
                 listUser·p0.99:   11.026 ms/op
                 listUser·p0.999:  22.643 ms/op
                 listUser·p0.9999: 26.452 ms/op
                 listUser·p1.00:   28.377 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 155617
  mean =      6.174 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 12852 
    [ 5.000,  7.500) = 128605 
    [ 7.500, 10.000) = 11254 
    [10.000, 12.500) = 1995 
    [12.500, 15.000) = 378 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 106 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.976 ms/op
     p(50.0000) =      5.857 ms/op
     p(90.0000) =      7.389 ms/op
     p(95.0000) =      8.454 ms/op
     p(99.0000) =     11.368 ms/op
     p(99.9000) =     25.244 ms/op
     p(99.9900) =     30.831 ms/op
     p(99.9990) =     31.483 ms/op
     p(99.9999) =     31.556 ms/op
    p(100.0000) =     31.556 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.040 ± 5.538  ops/ms
ClientPb.existUser                       thrpt       3   6.338 ± 2.454  ops/ms
ClientPb.getUser                         thrpt       3   5.698 ± 5.096  ops/ms
ClientPb.listUser                        thrpt       3   5.241 ± 2.047  ops/ms
ClientPb.createUser                       avgt       3   5.533 ± 3.344   ms/op
ClientPb.existUser                        avgt       3   5.181 ± 3.127   ms/op
ClientPb.getUser                          avgt       3   5.469 ± 0.692   ms/op
ClientPb.listUser                         avgt       3   6.166 ± 2.038   ms/op
ClientPb.createUser                     sample  176530   5.436 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.849           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.136           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.783           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.537           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.601           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.477           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.813           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.800           ms/op
ClientPb.existUser                      sample  187607   5.113 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.661           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.825           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.447           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.217           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.404           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.373           ms/op
ClientPb.existUser:existUser·p0.9999    sample          39.977           ms/op
ClientPb.existUser:existUser·p1.00      sample          42.729           ms/op
ClientPb.getUser                        sample  170595   5.622 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.274           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.317           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.021           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.938           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.961           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.970           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.649           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.537           ms/op
ClientPb.listUser                       sample  155617   6.174 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.976           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.857           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.389           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.454           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.368           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.244           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.831           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.556           ms/op
