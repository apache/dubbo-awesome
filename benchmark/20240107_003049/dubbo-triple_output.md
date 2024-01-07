# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.262 ops/ms
# Warmup Iteration   2: 12.301 ops/ms
# Warmup Iteration   3: 12.628 ops/ms
Iteration   1: 12.763 ops/ms
Iteration   2: 12.816 ops/ms
Iteration   3: 12.883 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.821 ±(99.9%) 1.091 ops/ms [Average]
  (min, avg, max) = (12.763, 12.821, 12.883), stdev = 0.060
  CI (99.9%): [11.729, 13.912] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.223 ops/ms
# Warmup Iteration   2: 12.728 ops/ms
# Warmup Iteration   3: 12.778 ops/ms
Iteration   1: 12.881 ops/ms
Iteration   2: 12.897 ops/ms
Iteration   3: 12.780 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.852 ±(99.9%) 1.150 ops/ms [Average]
  (min, avg, max) = (12.780, 12.852, 12.897), stdev = 0.063
  CI (99.9%): [11.702, 14.002] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.561 ops/ms
# Warmup Iteration   2: 12.450 ops/ms
# Warmup Iteration   3: 12.666 ops/ms
Iteration   1: 12.747 ops/ms
Iteration   2: 12.663 ops/ms
Iteration   3: 12.646 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.685 ±(99.9%) 0.984 ops/ms [Average]
  (min, avg, max) = (12.646, 12.685, 12.747), stdev = 0.054
  CI (99.9%): [11.701, 13.669] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.720 ops/ms
# Warmup Iteration   2: 10.371 ops/ms
# Warmup Iteration   3: 10.613 ops/ms
Iteration   1: 10.727 ops/ms
Iteration   2: 10.603 ops/ms
Iteration   3: 10.726 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.685 ±(99.9%) 1.304 ops/ms [Average]
  (min, avg, max) = (10.603, 10.685, 10.727), stdev = 0.071
  CI (99.9%): [9.381, 11.989] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.010 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 2.588 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.531 ±(99.9%) 0.004 ms/op
Iteration   1: 2.562 ±(99.9%) 0.005 ms/op
Iteration   2: 2.590 ±(99.9%) 0.005 ms/op
Iteration   3: 2.511 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.554 ±(99.9%) 0.728 ms/op [Average]
  (min, avg, max) = (2.511, 2.554, 2.590), stdev = 0.040
  CI (99.9%): [1.826, 3.282] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.654 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.474 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.452 ±(99.9%) 0.004 ms/op
Iteration   1: 2.446 ±(99.9%) 0.004 ms/op
Iteration   2: 2.429 ±(99.9%) 0.003 ms/op
Iteration   3: 2.434 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.436 ±(99.9%) 0.158 ms/op [Average]
  (min, avg, max) = (2.429, 2.436, 2.446), stdev = 0.009
  CI (99.9%): [2.279, 2.594] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.858 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.522 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.506 ±(99.9%) 0.004 ms/op
Iteration   1: 2.511 ±(99.9%) 0.004 ms/op
Iteration   2: 2.476 ±(99.9%) 0.005 ms/op
Iteration   3: 2.475 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.487 ±(99.9%) 0.374 ms/op [Average]
  (min, avg, max) = (2.475, 2.487, 2.511), stdev = 0.021
  CI (99.9%): [2.113, 2.861] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.498 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.051 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.005 ms/op
Iteration   1: 2.992 ±(99.9%) 0.005 ms/op
Iteration   2: 2.974 ±(99.9%) 0.005 ms/op
Iteration   3: 2.972 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.979 ±(99.9%) 0.196 ms/op [Average]
  (min, avg, max) = (2.972, 2.979, 2.992), stdev = 0.011
  CI (99.9%): [2.784, 3.175] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 3.957 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.666 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.536 ±(99.9%) 0.005 ms/op
Iteration   1: 2.530 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.090 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.715 ms/op
                 createUser·p0.999:  11.431 ms/op
                 createUser·p0.9999: 13.572 ms/op
                 createUser·p1.00:   14.074 ms/op

Iteration   2: 2.507 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.958 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.588 ms/op
                 createUser·p0.999:  8.999 ms/op
                 createUser·p0.9999: 12.951 ms/op
                 createUser·p1.00:   13.107 ms/op

Iteration   3: 2.519 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.033 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.735 ms/op
                 createUser·p0.999:  8.259 ms/op
                 createUser·p0.9999: 10.606 ms/op
                 createUser·p1.00:   15.204 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380692
  mean =      2.518 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 182236 
    [ 2.500,  3.750) = 195086 
    [ 3.750,  5.000) = 2745 
    [ 5.000,  6.250) = 181 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 111 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 114 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.958 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.686 ms/op
     p(99.9000) =      8.276 ms/op
     p(99.9900) =     13.106 ms/op
     p(99.9990) =     13.792 ms/op
     p(99.9999) =     15.204 ms/op
    p(100.0000) =     15.204 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.793 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.487 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.439 ±(99.9%) 0.005 ms/op
Iteration   1: 2.445 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.664 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.707 ms/op
                 existUser·p0.999:  7.458 ms/op
                 existUser·p0.9999: 13.722 ms/op
                 existUser·p1.00:   14.320 ms/op

Iteration   2: 2.446 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.987 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.514 ms/op
                 existUser·p0.999:  6.439 ms/op
                 existUser·p0.9999: 13.369 ms/op
                 existUser·p1.00:   13.681 ms/op

Iteration   3: 2.449 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.767 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.690 ms/op
                 existUser·p0.999:  8.389 ms/op
                 existUser·p0.9999: 11.894 ms/op
                 existUser·p1.00:   12.583 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391972
  mean =      2.447 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 195164 
    [ 2.500,  3.750) = 193495 
    [ 3.750,  5.000) = 2643 
    [ 5.000,  6.250) = 172 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 58 
    [ 8.750, 10.000) = 66 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 106 
    [12.500, 13.750) = 88 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.664 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      3.650 ms/op
     p(99.9000) =      8.380 ms/op
     p(99.9900) =     13.369 ms/op
     p(99.9990) =     14.057 ms/op
     p(99.9999) =     14.320 ms/op
    p(100.0000) =     14.320 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.794 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.566 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.006 ms/op
Iteration   1: 2.472 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.895 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   3.650 ms/op
                 getUser·p0.999:  5.912 ms/op
                 getUser·p0.9999: 14.195 ms/op
                 getUser·p1.00:   15.778 ms/op

Iteration   2: 2.497 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.930 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.686 ms/op
                 getUser·p0.999:  9.825 ms/op
                 getUser·p0.9999: 13.926 ms/op
                 getUser·p1.00:   14.533 ms/op

Iteration   3: 2.510 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.843 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.232 ms/op
                 getUser·p0.99:   3.934 ms/op
                 getUser·p0.999:  7.508 ms/op
                 getUser·p0.9999: 11.358 ms/op
                 getUser·p1.00:   11.649 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384718
  mean =      2.493 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 191631 
    [ 2.500,  3.750) = 189113 
    [ 3.750,  5.000) = 3312 
    [ 5.000,  6.250) = 226 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 97 
    [11.250, 12.500) = 109 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.843 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.760 ms/op
     p(99.9000) =      6.745 ms/op
     p(99.9900) =     13.886 ms/op
     p(99.9990) =     14.605 ms/op
     p(99.9999) =     15.778 ms/op
    p(100.0000) =     15.778 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.865 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.078 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.009 ms/op
Iteration   1: 3.019 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.944 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.759 ms/op
                 listUser·p0.999:  9.259 ms/op
                 listUser·p0.9999: 11.260 ms/op
                 listUser·p1.00:   11.911 ms/op

Iteration   2: 3.020 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.831 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.781 ms/op
                 listUser·p0.9999: 11.946 ms/op
                 listUser·p1.00:   13.107 ms/op

Iteration   3: 3.023 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.979 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.736 ms/op
                 listUser·p0.9999: 11.178 ms/op
                 listUser·p1.00:   11.616 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317484
  mean =      3.021 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 120 
    [ 1.250,  2.500) = 91765 
    [ 2.500,  3.750) = 186888 
    [ 3.750,  5.000) = 31216 
    [ 5.000,  6.250) = 6008 
    [ 6.250,  7.500) = 797 
    [ 7.500,  8.750) = 163 
    [ 8.750, 10.000) = 317 
    [10.000, 11.250) = 162 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.831 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =      9.585 ms/op
     p(99.9900) =     11.747 ms/op
     p(99.9990) =     12.613 ms/op
     p(99.9999) =     13.107 ms/op
    p(100.0000) =     13.107 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.821 ± 1.091  ops/ms
ClientPb.existUser                       thrpt       3  12.852 ± 1.150  ops/ms
ClientPb.getUser                         thrpt       3  12.685 ± 0.984  ops/ms
ClientPb.listUser                        thrpt       3  10.685 ± 1.304  ops/ms
ClientPb.createUser                       avgt       3   2.554 ± 0.728   ms/op
ClientPb.existUser                        avgt       3   2.436 ± 0.158   ms/op
ClientPb.getUser                          avgt       3   2.487 ± 0.374   ms/op
ClientPb.listUser                         avgt       3   2.979 ± 0.196   ms/op
ClientPb.createUser                     sample  380692   2.518 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.958           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.597           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.056           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.686           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.276           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.106           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.204           ms/op
ClientPb.existUser                      sample  391972   2.447 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.664           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.982           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.650           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.380           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.369           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.320           ms/op
ClientPb.getUser                        sample  384718   2.493 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.843           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.507           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.039           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.170           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.760           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.745           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.886           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.778           ms/op
ClientPb.listUser                       sample  317484   3.021 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.831           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.966           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.644           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.585           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.747           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.107           ms/op
