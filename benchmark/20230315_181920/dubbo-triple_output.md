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
# Warmup Iteration   1: 2.647 ops/ms
# Warmup Iteration   2: 6.458 ops/ms
# Warmup Iteration   3: 9.210 ops/ms
Iteration   1: 9.691 ops/ms
Iteration   2: 10.168 ops/ms
Iteration   3: 10.324 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.061 ±(99.9%) 6.022 ops/ms [Average]
  (min, avg, max) = (9.691, 10.061, 10.324), stdev = 0.330
  CI (99.9%): [4.039, 16.084] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.925 ops/ms
# Warmup Iteration   2: 9.442 ops/ms
# Warmup Iteration   3: 10.199 ops/ms
Iteration   1: 10.610 ops/ms
Iteration   2: 10.395 ops/ms
Iteration   3: 10.720 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.575 ±(99.9%) 3.021 ops/ms [Average]
  (min, avg, max) = (10.395, 10.575, 10.720), stdev = 0.166
  CI (99.9%): [7.554, 13.596] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.801 ops/ms
# Warmup Iteration   2: 9.147 ops/ms
# Warmup Iteration   3: 9.620 ops/ms
Iteration   1: 10.316 ops/ms
Iteration   2: 10.159 ops/ms
Iteration   3: 10.265 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.247 ±(99.9%) 1.463 ops/ms [Average]
  (min, avg, max) = (10.159, 10.247, 10.316), stdev = 0.080
  CI (99.9%): [8.784, 11.710] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.350 ops/ms
# Warmup Iteration   2: 7.560 ops/ms
# Warmup Iteration   3: 8.380 ops/ms
Iteration   1: 8.489 ops/ms
Iteration   2: 8.620 ops/ms
Iteration   3: 8.683 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.597 ±(99.9%) 1.801 ops/ms [Average]
  (min, avg, max) = (8.489, 8.597, 8.683), stdev = 0.099
  CI (99.9%): [6.796, 10.398] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.536 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.645 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.353 ±(99.9%) 0.003 ms/op
Iteration   1: 3.176 ±(99.9%) 0.004 ms/op
Iteration   2: 3.206 ±(99.9%) 0.005 ms/op
Iteration   3: 3.159 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.180 ±(99.9%) 0.433 ms/op [Average]
  (min, avg, max) = (3.159, 3.180, 3.206), stdev = 0.024
  CI (99.9%): [2.747, 3.613] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.113 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.220 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.150 ±(99.9%) 0.003 ms/op
Iteration   1: 3.092 ±(99.9%) 0.003 ms/op
Iteration   2: 3.046 ±(99.9%) 0.003 ms/op
Iteration   3: 3.067 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.068 ±(99.9%) 0.424 ms/op [Average]
  (min, avg, max) = (3.046, 3.068, 3.092), stdev = 0.023
  CI (99.9%): [2.644, 3.492] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.061 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.403 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.385 ±(99.9%) 0.007 ms/op
Iteration   1: 3.255 ±(99.9%) 0.004 ms/op
Iteration   2: 3.089 ±(99.9%) 0.005 ms/op
Iteration   3: 3.075 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.140 ±(99.9%) 1.828 ms/op [Average]
  (min, avg, max) = (3.075, 3.140, 3.255), stdev = 0.100
  CI (99.9%): [1.312, 4.968] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.881 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.031 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.904 ±(99.9%) 0.005 ms/op
Iteration   1: 3.721 ±(99.9%) 0.005 ms/op
Iteration   2: 3.711 ±(99.9%) 0.007 ms/op
Iteration   3: 3.609 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.680 ±(99.9%) 1.126 ms/op [Average]
  (min, avg, max) = (3.609, 3.680, 3.721), stdev = 0.062
  CI (99.9%): [2.555, 4.806] (assumes normal distribution)


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
# Warmup Iteration   1: 8.354 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.645 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.245 ±(99.9%) 0.008 ms/op
Iteration   1: 3.156 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.973 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   5.972 ms/op
                 createUser·p0.999:  12.124 ms/op
                 createUser·p0.9999: 21.507 ms/op
                 createUser·p1.00:   23.036 ms/op

Iteration   2: 3.193 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.309 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   5.388 ms/op
                 createUser·p0.999:  17.785 ms/op
                 createUser·p0.9999: 24.997 ms/op
                 createUser·p1.00:   25.919 ms/op

Iteration   3: 3.103 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.370 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.342 ms/op
                 createUser·p0.95:   3.629 ms/op
                 createUser·p0.99:   5.300 ms/op
                 createUser·p0.999:  15.645 ms/op
                 createUser·p0.9999: 19.426 ms/op
                 createUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 304550
  mean =      3.150 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16107 
    [ 2.500,  5.000) = 283183 
    [ 5.000,  7.500) = 4401 
    [ 7.500, 10.000) = 321 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.973 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =     16.015 ms/op
     p(99.9900) =     23.089 ms/op
     p(99.9990) =     25.525 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


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
# Warmup Iteration   1: 7.390 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.406 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.006 ms/op
Iteration   1: 3.042 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.137 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.219 ms/op
                 existUser·p0.95:   3.428 ms/op
                 existUser·p0.99:   5.792 ms/op
                 existUser·p0.999:  12.370 ms/op
                 existUser·p0.9999: 20.037 ms/op
                 existUser·p1.00:   21.004 ms/op

Iteration   2: 3.203 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.384 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.633 ms/op
                 existUser·p0.95:   3.961 ms/op
                 existUser·p0.99:   5.841 ms/op
                 existUser·p0.999:  13.028 ms/op
                 existUser·p0.9999: 28.607 ms/op
                 existUser·p1.00:   30.605 ms/op

Iteration   3: 3.221 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.462 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   3.973 ms/op
                 existUser·p0.99:   5.480 ms/op
                 existUser·p0.999:  8.280 ms/op
                 existUser·p0.9999: 22.446 ms/op
                 existUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304342
  mean =      3.153 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23927 
    [ 2.500,  5.000) = 274084 
    [ 5.000,  7.500) = 5499 
    [ 7.500, 10.000) = 370 
    [10.000, 12.500) = 201 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 112 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.137 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      5.682 ms/op
     p(99.9000) =     11.774 ms/op
     p(99.9900) =     27.380 ms/op
     p(99.9990) =     30.548 ms/op
     p(99.9999) =     30.605 ms/op
    p(100.0000) =     30.605 ms/op


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
# Warmup Iteration   1: 7.236 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.469 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.367 ±(99.9%) 0.011 ms/op
Iteration   1: 3.286 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.155 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   4.415 ms/op
                 getUser·p0.99:   6.676 ms/op
                 getUser·p0.999:  18.993 ms/op
                 getUser·p0.9999: 24.847 ms/op
                 getUser·p1.00:   25.133 ms/op

Iteration   2: 3.207 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.401 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   5.603 ms/op
                 getUser·p0.999:  10.626 ms/op
                 getUser·p0.9999: 23.496 ms/op
                 getUser·p1.00:   25.854 ms/op

Iteration   3: 3.129 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.118 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.391 ms/op
                 getUser·p0.95:   3.633 ms/op
                 getUser·p0.99:   4.817 ms/op
                 getUser·p0.999:  15.840 ms/op
                 getUser·p0.9999: 22.301 ms/op
                 getUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299157
  mean =      3.206 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23704 
    [ 2.500,  5.000) = 269788 
    [ 5.000,  7.500) = 4678 
    [ 7.500, 10.000) = 590 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 135 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.118 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.940 ms/op
     p(99.0000) =      5.874 ms/op
     p(99.9000) =     17.957 ms/op
     p(99.9900) =     24.153 ms/op
     p(99.9990) =     25.139 ms/op
     p(99.9999) =     25.854 ms/op
    p(100.0000) =     25.854 ms/op


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
# Warmup Iteration   1: 9.315 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.973 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.818 ±(99.9%) 0.013 ms/op
Iteration   1: 3.841 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.112 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   7.594 ms/op
                 listUser·p0.999:  13.697 ms/op
                 listUser·p0.9999: 18.952 ms/op
                 listUser·p1.00:   19.235 ms/op

Iteration   2: 3.662 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.042 ms/op
                 listUser·p0.50:   3.564 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.141 ms/op
                 listUser·p0.99:   6.545 ms/op
                 listUser·p0.999:  12.266 ms/op
                 listUser·p0.9999: 13.341 ms/op
                 listUser·p1.00:   15.548 ms/op

Iteration   3: 3.808 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.367 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   7.782 ms/op
                 listUser·p0.999:  12.795 ms/op
                 listUser·p0.9999: 20.925 ms/op
                 listUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254578
  mean =      3.769 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 76 
    [ 2.500,  5.000) = 245438 
    [ 5.000,  7.500) = 6693 
    [ 7.500, 10.000) = 1618 
    [10.000, 12.500) = 407 
    [12.500, 15.000) = 235 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.112 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.051 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      7.381 ms/op
     p(99.9000) =     12.911 ms/op
     p(99.9900) =     18.633 ms/op
     p(99.9990) =     20.954 ms/op
     p(99.9999) =     20.972 ms/op
    p(100.0000) =     20.972 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.061 ± 6.022  ops/ms
ClientPb.existUser                       thrpt       3  10.575 ± 3.021  ops/ms
ClientPb.getUser                         thrpt       3  10.247 ± 1.463  ops/ms
ClientPb.listUser                        thrpt       3   8.597 ± 1.801  ops/ms
ClientPb.createUser                       avgt       3   3.180 ± 0.433   ms/op
ClientPb.existUser                        avgt       3   3.068 ± 0.424   ms/op
ClientPb.getUser                          avgt       3   3.140 ± 1.828   ms/op
ClientPb.listUser                         avgt       3   3.680 ± 1.126   ms/op
ClientPb.createUser                     sample  304550   3.150 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.973           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.064           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.510           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.793           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.489           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.015           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.089           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.919           ms/op
ClientPb.existUser                      sample  304342   3.153 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.137           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.580           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.903           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.682           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.774           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.380           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.605           ms/op
ClientPb.getUser                        sample  299157   3.206 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.118           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.154           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.568           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.940           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.874           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.957           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.153           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.854           ms/op
ClientPb.listUser                       sample  254578   3.769 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.112           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.662           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.051           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.381           ms/op
ClientPb.listUser:listUser·p0.999       sample          12.911           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.633           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.972           ms/op
