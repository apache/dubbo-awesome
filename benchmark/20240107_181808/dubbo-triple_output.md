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
# Warmup Iteration   1: 5.013 ops/ms
# Warmup Iteration   2: 12.232 ops/ms
# Warmup Iteration   3: 12.528 ops/ms
Iteration   1: 12.670 ops/ms
Iteration   2: 12.610 ops/ms
Iteration   3: 12.749 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.676 ±(99.9%) 1.268 ops/ms [Average]
  (min, avg, max) = (12.610, 12.676, 12.749), stdev = 0.069
  CI (99.9%): [11.409, 13.944] (assumes normal distribution)


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
# Warmup Iteration   1: 7.725 ops/ms
# Warmup Iteration   2: 12.995 ops/ms
# Warmup Iteration   3: 12.986 ops/ms
Iteration   1: 13.030 ops/ms
Iteration   2: 12.935 ops/ms
Iteration   3: 13.016 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.994 ±(99.9%) 0.936 ops/ms [Average]
  (min, avg, max) = (12.935, 12.994, 13.030), stdev = 0.051
  CI (99.9%): [12.058, 13.930] (assumes normal distribution)


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
# Warmup Iteration   1: 7.496 ops/ms
# Warmup Iteration   2: 12.296 ops/ms
# Warmup Iteration   3: 12.690 ops/ms
Iteration   1: 12.798 ops/ms
Iteration   2: 12.930 ops/ms
Iteration   3: 12.757 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.828 ±(99.9%) 1.651 ops/ms [Average]
  (min, avg, max) = (12.757, 12.828, 12.930), stdev = 0.091
  CI (99.9%): [11.177, 14.480] (assumes normal distribution)


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
# Warmup Iteration   1: 6.124 ops/ms
# Warmup Iteration   2: 10.426 ops/ms
# Warmup Iteration   3: 10.463 ops/ms
Iteration   1: 10.661 ops/ms
Iteration   2: 10.695 ops/ms
Iteration   3: 10.554 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.637 ±(99.9%) 1.342 ops/ms [Average]
  (min, avg, max) = (10.554, 10.637, 10.695), stdev = 0.074
  CI (99.9%): [9.294, 11.979] (assumes normal distribution)


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
# Warmup Iteration   1: 4.233 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.605 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.525 ±(99.9%) 0.004 ms/op
Iteration   1: 2.563 ±(99.9%) 0.005 ms/op
Iteration   2: 2.546 ±(99.9%) 0.004 ms/op
Iteration   3: 2.551 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.553 ±(99.9%) 0.163 ms/op [Average]
  (min, avg, max) = (2.546, 2.553, 2.563), stdev = 0.009
  CI (99.9%): [2.390, 2.716] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.870 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.505 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.004 ms/op
Iteration   1: 2.453 ±(99.9%) 0.003 ms/op
Iteration   2: 2.477 ±(99.9%) 0.004 ms/op
Iteration   3: 2.464 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.465 ±(99.9%) 0.215 ms/op [Average]
  (min, avg, max) = (2.453, 2.465, 2.477), stdev = 0.012
  CI (99.9%): [2.249, 2.680] (assumes normal distribution)


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
# Warmup Iteration   1: 4.335 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.607 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.555 ±(99.9%) 0.003 ms/op
Iteration   1: 2.572 ±(99.9%) 0.004 ms/op
Iteration   2: 2.556 ±(99.9%) 0.005 ms/op
Iteration   3: 2.552 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.560 ±(99.9%) 0.191 ms/op [Average]
  (min, avg, max) = (2.552, 2.560, 2.572), stdev = 0.010
  CI (99.9%): [2.369, 2.751] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.726 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.083 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.062 ±(99.9%) 0.007 ms/op
Iteration   1: 3.061 ±(99.9%) 0.005 ms/op
Iteration   2: 3.056 ±(99.9%) 0.007 ms/op
Iteration   3: 3.042 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.053 ±(99.9%) 0.173 ms/op [Average]
  (min, avg, max) = (3.042, 3.053, 3.061), stdev = 0.009
  CI (99.9%): [2.880, 3.226] (assumes normal distribution)


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
# Warmup Iteration   1: 4.441 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.681 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.549 ±(99.9%) 0.006 ms/op
Iteration   1: 2.533 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.025 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.756 ms/op
                 createUser·p0.999:  11.731 ms/op
                 createUser·p0.9999: 13.959 ms/op
                 createUser·p1.00:   15.073 ms/op

Iteration   2: 2.487 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.038 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   3.559 ms/op
                 createUser·p0.999:  7.881 ms/op
                 createUser·p0.9999: 14.867 ms/op
                 createUser·p1.00:   16.417 ms/op

Iteration   3: 2.491 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.852 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.895 ms/op
                 createUser·p0.999:  8.782 ms/op
                 createUser·p0.9999: 10.554 ms/op
                 createUser·p1.00:   11.272 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383123
  mean =      2.503 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 39 
    [ 1.250,  2.500) = 183911 
    [ 2.500,  3.750) = 195441 
    [ 3.750,  5.000) = 2834 
    [ 5.000,  6.250) = 440 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 113 
    [10.000, 11.250) = 108 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 88 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.852 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.736 ms/op
     p(99.9000) =      8.782 ms/op
     p(99.9900) =     14.008 ms/op
     p(99.9990) =     15.721 ms/op
     p(99.9999) =     16.417 ms/op
    p(100.0000) =     16.417 ms/op


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
# Warmup Iteration   1: 3.501 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.398 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.416 ±(99.9%) 0.005 ms/op
Iteration   1: 2.397 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.797 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.031 ms/op
                 existUser·p0.99:   3.482 ms/op
                 existUser·p0.999:  4.915 ms/op
                 existUser·p0.9999: 13.637 ms/op
                 existUser·p1.00:   14.991 ms/op

Iteration   2: 2.427 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.972 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.518 ms/op
                 existUser·p0.999:  8.184 ms/op
                 existUser·p0.9999: 13.184 ms/op
                 existUser·p1.00:   14.189 ms/op

Iteration   3: 2.457 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.887 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.928 ms/op
                 existUser·p0.999:  8.487 ms/op
                 existUser·p0.9999: 11.550 ms/op
                 existUser·p1.00:   12.698 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 395143
  mean =      2.427 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 198687 
    [ 2.500,  3.750) = 193054 
    [ 3.750,  5.000) = 2653 
    [ 5.000,  6.250) = 243 
    [ 6.250,  7.500) = 65 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 114 
    [10.000, 11.250) = 56 
    [11.250, 12.500) = 111 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.797 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      3.645 ms/op
     p(99.9000) =      7.321 ms/op
     p(99.9900) =     13.213 ms/op
     p(99.9990) =     14.355 ms/op
     p(99.9999) =     14.991 ms/op
    p(100.0000) =     14.991 ms/op


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
# Warmup Iteration   1: 3.968 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.575 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.535 ±(99.9%) 0.006 ms/op
Iteration   1: 2.497 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.059 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.682 ms/op
                 getUser·p0.999:  11.190 ms/op
                 getUser·p0.9999: 14.086 ms/op
                 getUser·p1.00:   14.254 ms/op

Iteration   2: 2.555 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.833 ms/op
                 getUser·p0.50:   2.589 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   4.760 ms/op
                 getUser·p0.999:  9.157 ms/op
                 getUser·p0.9999: 14.131 ms/op
                 getUser·p1.00:   14.795 ms/op

Iteration   3: 2.510 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.000 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.662 ms/op
                 getUser·p0.999:  8.845 ms/op
                 getUser·p0.9999: 11.239 ms/op
                 getUser·p1.00:   11.370 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380548
  mean =      2.520 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 187807 
    [ 2.500,  3.750) = 187978 
    [ 3.750,  5.000) = 3227 
    [ 5.000,  6.250) = 991 
    [ 6.250,  7.500) = 96 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 91 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 102 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.833 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.908 ms/op
     p(99.9000) =      9.044 ms/op
     p(99.9900) =     13.826 ms/op
     p(99.9990) =     14.700 ms/op
     p(99.9999) =     14.795 ms/op
    p(100.0000) =     14.795 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.619 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.069 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.001 ±(99.9%) 0.008 ms/op
Iteration   1: 3.018 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.803 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.661 ms/op
                 listUser·p0.999:  9.618 ms/op
                 listUser·p0.9999: 11.885 ms/op
                 listUser·p1.00:   12.337 ms/op

Iteration   2: 2.980 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.720 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.465 ms/op
                 listUser·p0.9999: 10.523 ms/op
                 listUser·p1.00:   11.534 ms/op

Iteration   3: 2.969 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.919 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  8.716 ms/op
                 listUser·p0.9999: 10.313 ms/op
                 listUser·p1.00:   10.650 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320887
  mean =      2.989 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 161 
    [ 1.250,  2.500) = 96702 
    [ 2.500,  3.750) = 185378 
    [ 3.750,  5.000) = 31485 
    [ 5.000,  6.250) = 5713 
    [ 6.250,  7.500) = 764 
    [ 7.500,  8.750) = 238 
    [ 8.750, 10.000) = 293 
    [10.000, 11.250) = 126 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.720 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =      9.306 ms/op
     p(99.9900) =     11.076 ms/op
     p(99.9990) =     12.003 ms/op
     p(99.9999) =     12.337 ms/op
    p(100.0000) =     12.337 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.676 ± 1.268  ops/ms
ClientPb.existUser                       thrpt       3  12.994 ± 0.936  ops/ms
ClientPb.getUser                         thrpt       3  12.828 ± 1.651  ops/ms
ClientPb.listUser                        thrpt       3  10.637 ± 1.342  ops/ms
ClientPb.createUser                       avgt       3   2.553 ± 0.163   ms/op
ClientPb.existUser                        avgt       3   2.465 ± 0.215   ms/op
ClientPb.getUser                          avgt       3   2.560 ± 0.191   ms/op
ClientPb.listUser                         avgt       3   3.053 ± 0.173   ms/op
ClientPb.createUser                     sample  383123   2.503 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.852           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.597           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.039           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.158           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.736           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.782           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.008           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.417           ms/op
ClientPb.existUser                      sample  395143   2.427 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.797           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.490           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.953           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.645           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.321           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.213           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.991           ms/op
ClientPb.getUser                        sample  380548   2.520 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.833           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.060           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.908           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.044           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.826           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.795           ms/op
ClientPb.listUser                       sample  320887   2.989 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.720           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.925           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.875           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.587           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.306           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.076           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.337           ms/op
