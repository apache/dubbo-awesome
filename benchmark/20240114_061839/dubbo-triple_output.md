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
# Warmup Iteration   1: 4.541 ops/ms
# Warmup Iteration   2: 11.759 ops/ms
# Warmup Iteration   3: 12.206 ops/ms
Iteration   1: 12.329 ops/ms
Iteration   2: 12.575 ops/ms
Iteration   3: 12.594 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.499 ±(99.9%) 2.701 ops/ms [Average]
  (min, avg, max) = (12.329, 12.499, 12.594), stdev = 0.148
  CI (99.9%): [9.798, 15.201] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.150 ops/ms
# Warmup Iteration   2: 12.853 ops/ms
# Warmup Iteration   3: 12.737 ops/ms
Iteration   1: 12.913 ops/ms
Iteration   2: 12.936 ops/ms
Iteration   3: 12.947 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.932 ±(99.9%) 0.320 ops/ms [Average]
  (min, avg, max) = (12.913, 12.932, 12.947), stdev = 0.018
  CI (99.9%): [12.612, 13.252] (assumes normal distribution)


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
# Warmup Iteration   1: 7.637 ops/ms
# Warmup Iteration   2: 12.202 ops/ms
# Warmup Iteration   3: 12.707 ops/ms
Iteration   1: 12.542 ops/ms
Iteration   2: 12.526 ops/ms
Iteration   3: 12.829 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.632 ±(99.9%) 3.114 ops/ms [Average]
  (min, avg, max) = (12.526, 12.632, 12.829), stdev = 0.171
  CI (99.9%): [9.518, 15.747] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.774 ops/ms
# Warmup Iteration   2: 10.342 ops/ms
# Warmup Iteration   3: 10.409 ops/ms
Iteration   1: 10.415 ops/ms
Iteration   2: 10.418 ops/ms
Iteration   3: 10.378 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.404 ±(99.9%) 0.408 ops/ms [Average]
  (min, avg, max) = (10.378, 10.404, 10.418), stdev = 0.022
  CI (99.9%): [9.996, 10.811] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.193 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.649 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.585 ±(99.9%) 0.004 ms/op
Iteration   1: 2.631 ±(99.9%) 0.004 ms/op
Iteration   2: 2.595 ±(99.9%) 0.005 ms/op
Iteration   3: 2.590 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.605 ±(99.9%) 0.406 ms/op [Average]
  (min, avg, max) = (2.590, 2.605, 2.631), stdev = 0.022
  CI (99.9%): [2.199, 3.012] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.887 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.519 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.491 ±(99.9%) 0.003 ms/op
Iteration   1: 2.508 ±(99.9%) 0.005 ms/op
Iteration   2: 2.481 ±(99.9%) 0.004 ms/op
Iteration   3: 2.506 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.498 ±(99.9%) 0.276 ms/op [Average]
  (min, avg, max) = (2.481, 2.498, 2.508), stdev = 0.015
  CI (99.9%): [2.222, 2.774] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.026 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.580 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.528 ±(99.9%) 0.004 ms/op
Iteration   1: 2.526 ±(99.9%) 0.004 ms/op
Iteration   2: 2.524 ±(99.9%) 0.004 ms/op
Iteration   3: 2.536 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.529 ±(99.9%) 0.121 ms/op [Average]
  (min, avg, max) = (2.524, 2.529, 2.536), stdev = 0.007
  CI (99.9%): [2.407, 2.650] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.999 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.098 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.102 ±(99.9%) 0.005 ms/op
Iteration   1: 3.056 ±(99.9%) 0.005 ms/op
Iteration   2: 3.067 ±(99.9%) 0.005 ms/op
Iteration   3: 3.058 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.061 ±(99.9%) 0.108 ms/op [Average]
  (min, avg, max) = (3.056, 3.061, 3.067), stdev = 0.006
  CI (99.9%): [2.953, 3.169] (assumes normal distribution)


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
# Warmup Iteration   1: 4.263 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.646 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.580 ±(99.9%) 0.006 ms/op
Iteration   1: 2.580 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.767 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.142 ms/op
                 createUser·p0.95:   3.261 ms/op
                 createUser·p0.99:   3.752 ms/op
                 createUser·p0.999:  11.355 ms/op
                 createUser·p0.9999: 14.054 ms/op
                 createUser·p1.00:   14.516 ms/op

Iteration   2: 2.582 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.873 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.129 ms/op
                 createUser·p0.95:   3.252 ms/op
                 createUser·p0.99:   3.858 ms/op
                 createUser·p0.999:  9.374 ms/op
                 createUser·p0.9999: 14.422 ms/op
                 createUser·p1.00:   15.434 ms/op

Iteration   3: 2.597 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.843 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.150 ms/op
                 createUser·p0.95:   3.314 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  8.815 ms/op
                 createUser·p0.9999: 12.021 ms/op
                 createUser·p1.00:   13.812 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 370900
  mean =      2.586 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 173876 
    [ 2.500,  3.750) = 191623 
    [ 3.750,  5.000) = 4223 
    [ 5.000,  6.250) = 563 
    [ 6.250,  7.500) = 121 
    [ 7.500,  8.750) = 64 
    [ 8.750, 10.000) = 95 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 114 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.767 ms/op
     p(50.0000) =      2.642 ms/op
     p(90.0000) =      3.142 ms/op
     p(95.0000) =      3.273 ms/op
     p(99.0000) =      3.965 ms/op
     p(99.9000) =      8.880 ms/op
     p(99.9900) =     14.025 ms/op
     p(99.9990) =     14.721 ms/op
     p(99.9999) =     15.434 ms/op
    p(100.0000) =     15.434 ms/op


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
# Warmup Iteration   1: 3.847 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.574 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.534 ±(99.9%) 0.005 ms/op
Iteration   1: 2.515 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.986 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   3.060 ms/op
                 existUser·p0.95:   3.154 ms/op
                 existUser·p0.99:   3.494 ms/op
                 existUser·p0.999:  11.305 ms/op
                 existUser·p0.9999: 14.427 ms/op
                 existUser·p1.00:   15.188 ms/op

Iteration   2: 2.541 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.728 ms/op
                 existUser·p0.50:   2.650 ms/op
                 existUser·p0.90:   3.072 ms/op
                 existUser·p0.95:   3.174 ms/op
                 existUser·p0.99:   3.760 ms/op
                 existUser·p0.999:  8.431 ms/op
                 existUser·p0.9999: 12.763 ms/op
                 existUser·p1.00:   12.878 ms/op

Iteration   3: 2.538 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.049 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   3.101 ms/op
                 existUser·p0.95:   3.207 ms/op
                 existUser·p0.99:   3.666 ms/op
                 existUser·p0.999:  6.776 ms/op
                 existUser·p0.9999: 11.705 ms/op
                 existUser·p1.00:   13.091 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 378825
  mean =      2.531 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 185041 
    [ 2.500,  3.750) = 190629 
    [ 3.750,  5.000) = 2522 
    [ 5.000,  6.250) = 207 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 92 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.728 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.650 ms/op
     p(99.9000) =      6.899 ms/op
     p(99.9900) =     13.107 ms/op
     p(99.9990) =     15.113 ms/op
     p(99.9999) =     15.188 ms/op
    p(100.0000) =     15.188 ms/op


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
# Warmup Iteration   1: 3.975 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.667 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.552 ±(99.9%) 0.006 ms/op
Iteration   1: 2.571 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.012 ms/op
                 getUser·p0.50:   2.601 ms/op
                 getUser·p0.90:   3.129 ms/op
                 getUser·p0.95:   3.277 ms/op
                 getUser·p0.99:   3.949 ms/op
                 getUser·p0.999:  11.620 ms/op
                 getUser·p0.9999: 13.748 ms/op
                 getUser·p1.00:   14.238 ms/op

Iteration   2: 2.603 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.898 ms/op
                 getUser·p0.50:   2.626 ms/op
                 getUser·p0.90:   3.158 ms/op
                 getUser·p0.95:   3.293 ms/op
                 getUser·p0.99:   4.153 ms/op
                 getUser·p0.999:  9.028 ms/op
                 getUser·p0.9999: 13.981 ms/op
                 getUser·p1.00:   15.778 ms/op

Iteration   3: 2.583 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.864 ms/op
                 getUser·p0.50:   2.593 ms/op
                 getUser·p0.90:   3.150 ms/op
                 getUser·p0.95:   3.260 ms/op
                 getUser·p0.99:   3.744 ms/op
                 getUser·p0.999:  7.832 ms/op
                 getUser·p0.9999: 12.190 ms/op
                 getUser·p1.00:   12.796 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 370937
  mean =      2.586 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 178884 
    [ 2.500,  3.750) = 186883 
    [ 3.750,  5.000) = 3868 
    [ 5.000,  6.250) = 714 
    [ 6.250,  7.500) = 130 
    [ 7.500,  8.750) = 49 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 66 
    [11.250, 12.500) = 119 
    [12.500, 13.750) = 87 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.864 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.150 ms/op
     p(95.0000) =      3.277 ms/op
     p(99.0000) =      3.940 ms/op
     p(99.9000) =      8.651 ms/op
     p(99.9900) =     13.319 ms/op
     p(99.9990) =     15.460 ms/op
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

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.922 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.123 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.076 ±(99.9%) 0.009 ms/op
Iteration   1: 3.066 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.931 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.734 ms/op
                 listUser·p0.999:  9.826 ms/op
                 listUser·p0.9999: 10.945 ms/op
                 listUser·p1.00:   12.206 ms/op

Iteration   2: 3.042 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.929 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.626 ms/op
                 listUser·p0.999:  9.697 ms/op
                 listUser·p0.9999: 11.288 ms/op
                 listUser·p1.00:   13.238 ms/op

Iteration   3: 3.054 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.055 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.754 ms/op
                 listUser·p0.9999: 11.162 ms/op
                 listUser·p1.00:   12.911 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314093
  mean =      3.054 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 91 
    [ 1.250,  2.500) = 82758 
    [ 2.500,  3.750) = 189411 
    [ 3.750,  5.000) = 34139 
    [ 5.000,  6.250) = 6238 
    [ 6.250,  7.500) = 780 
    [ 7.500,  8.750) = 133 
    [ 8.750, 10.000) = 336 
    [10.000, 11.250) = 185 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.929 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =      9.748 ms/op
     p(99.9900) =     11.029 ms/op
     p(99.9990) =     12.852 ms/op
     p(99.9999) =     13.238 ms/op
    p(100.0000) =     13.238 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.499 ± 2.701  ops/ms
ClientPb.existUser                       thrpt       3  12.932 ± 0.320  ops/ms
ClientPb.getUser                         thrpt       3  12.632 ± 3.114  ops/ms
ClientPb.listUser                        thrpt       3  10.404 ± 0.408  ops/ms
ClientPb.createUser                       avgt       3   2.605 ± 0.406   ms/op
ClientPb.existUser                        avgt       3   2.498 ± 0.276   ms/op
ClientPb.getUser                          avgt       3   2.529 ± 0.121   ms/op
ClientPb.listUser                         avgt       3   3.061 ± 0.108   ms/op
ClientPb.createUser                     sample  370900   2.586 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.767           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.642           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.273           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.965           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.880           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.025           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.434           ms/op
ClientPb.existUser                      sample  378825   2.531 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.728           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.572           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.178           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.650           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.899           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.107           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.188           ms/op
ClientPb.getUser                        sample  370937   2.586 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.864           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.605           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.277           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.940           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.651           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.319           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.778           ms/op
ClientPb.listUser                       sample  314093   3.054 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.929           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.990           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.944           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.644           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.748           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.029           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.238           ms/op
