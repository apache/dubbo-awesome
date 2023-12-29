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
# Warmup Iteration   1: 4.803 ops/ms
# Warmup Iteration   2: 12.131 ops/ms
# Warmup Iteration   3: 12.385 ops/ms
Iteration   1: 12.522 ops/ms
Iteration   2: 12.590 ops/ms
Iteration   3: 12.498 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.537 ±(99.9%) 0.873 ops/ms [Average]
  (min, avg, max) = (12.498, 12.537, 12.590), stdev = 0.048
  CI (99.9%): [11.664, 13.410] (assumes normal distribution)


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
# Warmup Iteration   1: 7.937 ops/ms
# Warmup Iteration   2: 12.673 ops/ms
# Warmup Iteration   3: 12.793 ops/ms
Iteration   1: 12.893 ops/ms
Iteration   2: 12.808 ops/ms
Iteration   3: 12.942 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.881 ±(99.9%) 1.234 ops/ms [Average]
  (min, avg, max) = (12.808, 12.881, 12.942), stdev = 0.068
  CI (99.9%): [11.647, 14.115] (assumes normal distribution)


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
# Warmup Iteration   1: 7.934 ops/ms
# Warmup Iteration   2: 12.590 ops/ms
# Warmup Iteration   3: 12.813 ops/ms
Iteration   1: 12.629 ops/ms
Iteration   2: 12.818 ops/ms
Iteration   3: 12.856 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.768 ±(99.9%) 2.218 ops/ms [Average]
  (min, avg, max) = (12.629, 12.768, 12.856), stdev = 0.122
  CI (99.9%): [10.549, 14.986] (assumes normal distribution)


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
# Warmup Iteration   1: 6.936 ops/ms
# Warmup Iteration   2: 10.608 ops/ms
# Warmup Iteration   3: 10.584 ops/ms
Iteration   1: 10.613 ops/ms
Iteration   2: 10.731 ops/ms
Iteration   3: 10.688 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.677 ±(99.9%) 1.097 ops/ms [Average]
  (min, avg, max) = (10.613, 10.677, 10.731), stdev = 0.060
  CI (99.9%): [9.581, 11.774] (assumes normal distribution)


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
# Warmup Iteration   1: 3.995 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.573 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.517 ±(99.9%) 0.005 ms/op
Iteration   1: 2.542 ±(99.9%) 0.003 ms/op
Iteration   2: 2.535 ±(99.9%) 0.003 ms/op
Iteration   3: 2.507 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.528 ±(99.9%) 0.341 ms/op [Average]
  (min, avg, max) = (2.507, 2.528, 2.542), stdev = 0.019
  CI (99.9%): [2.186, 2.869] (assumes normal distribution)


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
# Warmup Iteration   1: 3.746 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.480 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.004 ms/op
Iteration   1: 2.460 ±(99.9%) 0.004 ms/op
Iteration   2: 2.460 ±(99.9%) 0.004 ms/op
Iteration   3: 2.429 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.450 ±(99.9%) 0.321 ms/op [Average]
  (min, avg, max) = (2.429, 2.450, 2.460), stdev = 0.018
  CI (99.9%): [2.128, 2.771] (assumes normal distribution)


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
# Warmup Iteration   1: 3.909 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.581 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.512 ±(99.9%) 0.004 ms/op
Iteration   1: 2.509 ±(99.9%) 0.004 ms/op
Iteration   2: 2.505 ±(99.9%) 0.004 ms/op
Iteration   3: 2.495 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.503 ±(99.9%) 0.135 ms/op [Average]
  (min, avg, max) = (2.495, 2.503, 2.509), stdev = 0.007
  CI (99.9%): [2.368, 2.638] (assumes normal distribution)


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
# Warmup Iteration   1: 4.656 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.071 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.006 ms/op
Iteration   1: 3.001 ±(99.9%) 0.006 ms/op
Iteration   2: 3.027 ±(99.9%) 0.006 ms/op
Iteration   3: 3.017 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.015 ±(99.9%) 0.236 ms/op [Average]
  (min, avg, max) = (3.001, 3.015, 3.027), stdev = 0.013
  CI (99.9%): [2.779, 3.251] (assumes normal distribution)


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
# Warmup Iteration   1: 4.303 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.681 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.563 ±(99.9%) 0.006 ms/op
Iteration   1: 2.573 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.862 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.125 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   3.805 ms/op
                 createUser·p0.999:  12.190 ms/op
                 createUser·p0.9999: 16.531 ms/op
                 createUser·p1.00:   17.433 ms/op

Iteration   2: 2.569 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.913 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   3.674 ms/op
                 createUser·p0.999:  10.921 ms/op
                 createUser·p0.9999: 13.428 ms/op
                 createUser·p1.00:   14.647 ms/op

Iteration   3: 2.555 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.810 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.793 ms/op
                 createUser·p0.999:  8.944 ms/op
                 createUser·p0.9999: 10.805 ms/op
                 createUser·p1.00:   11.764 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 373815
  mean =      2.566 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 178757 
    [ 2.500,  3.750) = 191181 
    [ 3.750,  5.000) = 3186 
    [ 5.000,  6.250) = 230 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.810 ms/op
     p(50.0000) =      2.617 ms/op
     p(90.0000) =      3.117 ms/op
     p(95.0000) =      3.232 ms/op
     p(99.0000) =      3.764 ms/op
     p(99.9000) =      9.174 ms/op
     p(99.9900) =     15.065 ms/op
     p(99.9990) =     16.889 ms/op
     p(99.9999) =     17.433 ms/op
    p(100.0000) =     17.433 ms/op


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
# Warmup Iteration   1: 3.789 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.466 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.472 ±(99.9%) 0.006 ms/op
Iteration   1: 2.449 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.079 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.584 ms/op
                 existUser·p0.999:  5.452 ms/op
                 existUser·p0.9999: 14.188 ms/op
                 existUser·p1.00:   15.106 ms/op

Iteration   2: 2.484 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.859 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.617 ms/op
                 existUser·p0.999:  7.442 ms/op
                 existUser·p0.9999: 13.664 ms/op
                 existUser·p1.00:   14.336 ms/op

Iteration   3: 2.491 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.921 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.154 ms/op
                 existUser·p0.99:   3.830 ms/op
                 existUser·p0.999:  8.372 ms/op
                 existUser·p0.9999: 12.408 ms/op
                 existUser·p1.00:   12.796 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387543
  mean =      2.475 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 192271 
    [ 2.500,  3.750) = 191810 
    [ 3.750,  5.000) = 2694 
    [ 5.000,  6.250) = 335 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 84 
    [10.000, 11.250) = 62 
    [11.250, 12.500) = 89 
    [12.500, 13.750) = 104 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.859 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.674 ms/op
     p(99.9000) =      7.260 ms/op
     p(99.9900) =     13.767 ms/op
     p(99.9990) =     14.817 ms/op
     p(99.9999) =     15.106 ms/op
    p(100.0000) =     15.106 ms/op


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
# Warmup Iteration   1: 3.955 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.604 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.553 ±(99.9%) 0.006 ms/op
Iteration   1: 2.530 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.726 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.846 ms/op
                 getUser·p0.999:  11.338 ms/op
                 getUser·p0.9999: 14.698 ms/op
                 getUser·p1.00:   15.401 ms/op

Iteration   2: 2.543 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.034 ms/op
                 getUser·p0.50:   2.597 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   4.653 ms/op
                 getUser·p0.999:  9.362 ms/op
                 getUser·p0.9999: 12.931 ms/op
                 getUser·p1.00:   13.140 ms/op

Iteration   3: 2.561 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.862 ms/op
                 getUser·p0.50:   2.593 ms/op
                 getUser·p0.90:   3.125 ms/op
                 getUser·p0.95:   3.285 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  8.915 ms/op
                 getUser·p0.9999: 11.600 ms/op
                 getUser·p1.00:   12.272 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377023
  mean =      2.544 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 88 
    [ 1.250,  2.500) = 183874 
    [ 2.500,  3.750) = 186647 
    [ 3.750,  5.000) = 4748 
    [ 5.000,  6.250) = 1170 
    [ 6.250,  7.500) = 85 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 142 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.726 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.232 ms/op
     p(99.0000) =      4.170 ms/op
     p(99.9000) =      8.946 ms/op
     p(99.9900) =     13.828 ms/op
     p(99.9990) =     15.289 ms/op
     p(99.9999) =     15.401 ms/op
    p(100.0000) =     15.401 ms/op


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
# Warmup Iteration   1: 5.014 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.125 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.009 ms/op
Iteration   1: 3.015 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.823 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  9.551 ms/op
                 listUser·p0.9999: 11.580 ms/op
                 listUser·p1.00:   12.370 ms/op

Iteration   2: 2.998 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.984 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  9.535 ms/op
                 listUser·p0.9999: 10.803 ms/op
                 listUser·p1.00:   11.633 ms/op

Iteration   3: 3.032 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.819 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.587 ms/op
                 listUser·p0.9999: 11.156 ms/op
                 listUser·p1.00:   12.550 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318111
  mean =      3.015 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 141 
    [ 1.250,  2.500) = 89607 
    [ 2.500,  3.750) = 189615 
    [ 3.750,  5.000) = 31458 
    [ 5.000,  6.250) = 5845 
    [ 6.250,  7.500) = 745 
    [ 7.500,  8.750) = 157 
    [ 8.750, 10.000) = 351 
    [10.000, 11.250) = 158 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.819 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =      9.552 ms/op
     p(99.9900) =     11.295 ms/op
     p(99.9990) =     12.254 ms/op
     p(99.9999) =     12.550 ms/op
    p(100.0000) =     12.550 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.537 ± 0.873  ops/ms
ClientPb.existUser                       thrpt       3  12.881 ± 1.234  ops/ms
ClientPb.getUser                         thrpt       3  12.768 ± 2.218  ops/ms
ClientPb.listUser                        thrpt       3  10.677 ± 1.097  ops/ms
ClientPb.createUser                       avgt       3   2.528 ± 0.341   ms/op
ClientPb.existUser                        avgt       3   2.450 ± 0.321   ms/op
ClientPb.getUser                          avgt       3   2.503 ± 0.135   ms/op
ClientPb.listUser                         avgt       3   3.015 ± 0.236   ms/op
ClientPb.createUser                     sample  373815   2.566 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.810           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.617           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.117           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.232           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.764           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.174           ms/op
ClientPb.createUser:createUser·p0.9999  sample          15.065           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.433           ms/op
ClientPb.existUser                      sample  387543   2.475 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.859           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.519           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.015           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.125           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.674           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.260           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.767           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.106           ms/op
ClientPb.getUser                        sample  377023   2.544 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.726           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.572           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.092           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.232           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.170           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.946           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.828           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.401           ms/op
ClientPb.listUser                       sample  318111   3.015 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.819           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.587           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.552           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.295           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.550           ms/op
