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
# Warmup Iteration   1: 3.884 ops/ms
# Warmup Iteration   2: 10.993 ops/ms
# Warmup Iteration   3: 11.244 ops/ms
Iteration   1: 11.540 ops/ms
Iteration   2: 11.605 ops/ms
Iteration   3: 11.714 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  11.620 ±(99.9%) 1.600 ops/ms [Average]
  (min, avg, max) = (11.540, 11.620, 11.714), stdev = 0.088
  CI (99.9%): [10.020, 13.219] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:55
# Fork: 1 of 1
# Warmup Iteration   1: 6.915 ops/ms
# Warmup Iteration   2: 11.803 ops/ms
# Warmup Iteration   3: 11.777 ops/ms
Iteration   1: 11.924 ops/ms
Iteration   2: 11.876 ops/ms
Iteration   3: 12.062 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  11.954 ±(99.9%) 1.763 ops/ms [Average]
  (min, avg, max) = (11.876, 11.954, 12.062), stdev = 0.097
  CI (99.9%): [10.191, 13.717] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 7.135 ops/ms
# Warmup Iteration   2: 11.470 ops/ms
# Warmup Iteration   3: 11.496 ops/ms
Iteration   1: 11.691 ops/ms
Iteration   2: 11.663 ops/ms
Iteration   3: 11.662 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  11.672 ±(99.9%) 0.300 ops/ms [Average]
  (min, avg, max) = (11.662, 11.672, 11.691), stdev = 0.016
  CI (99.9%): [11.372, 11.971] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.761 ops/ms
# Warmup Iteration   2: 9.558 ops/ms
# Warmup Iteration   3: 9.499 ops/ms
Iteration   1: 9.653 ops/ms
Iteration   2: 9.562 ops/ms
Iteration   3: 9.629 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  9.615 ±(99.9%) 0.863 ops/ms [Average]
  (min, avg, max) = (9.562, 9.615, 9.653), stdev = 0.047
  CI (99.9%): [8.752, 10.478] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.609 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.880 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.762 ±(99.9%) 0.004 ms/op
Iteration   1: 2.815 ±(99.9%) 0.004 ms/op
Iteration   2: 2.776 ±(99.9%) 0.005 ms/op
Iteration   3: 2.749 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.780 ±(99.9%) 0.603 ms/op [Average]
  (min, avg, max) = (2.749, 2.780, 2.815), stdev = 0.033
  CI (99.9%): [2.177, 3.383] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.294 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.728 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.741 ±(99.9%) 0.004 ms/op
Iteration   1: 2.747 ±(99.9%) 0.004 ms/op
Iteration   2: 2.730 ±(99.9%) 0.005 ms/op
Iteration   3: 2.710 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.729 ±(99.9%) 0.340 ms/op [Average]
  (min, avg, max) = (2.710, 2.729, 2.747), stdev = 0.019
  CI (99.9%): [2.389, 3.070] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.456 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.759 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.723 ±(99.9%) 0.004 ms/op
Iteration   1: 2.750 ±(99.9%) 0.004 ms/op
Iteration   2: 2.715 ±(99.9%) 0.005 ms/op
Iteration   3: 2.733 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.733 ±(99.9%) 0.323 ms/op [Average]
  (min, avg, max) = (2.715, 2.733, 2.750), stdev = 0.018
  CI (99.9%): [2.409, 3.056] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.382 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.391 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.229 ±(99.9%) 0.005 ms/op
Iteration   1: 3.319 ±(99.9%) 0.006 ms/op
Iteration   2: 3.345 ±(99.9%) 0.005 ms/op
Iteration   3: 3.350 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.338 ±(99.9%) 0.300 ms/op [Average]
  (min, avg, max) = (3.319, 3.338, 3.350), stdev = 0.016
  CI (99.9%): [3.038, 3.638] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.165 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 2.907 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.795 ±(99.9%) 0.007 ms/op
Iteration   1: 2.795 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.102 ms/op
                 createUser·p0.50:   2.818 ms/op
                 createUser·p0.90:   3.404 ms/op
                 createUser·p0.95:   3.592 ms/op
                 createUser·p0.99:   4.649 ms/op
                 createUser·p0.999:  15.789 ms/op
                 createUser·p0.9999: 18.303 ms/op
                 createUser·p1.00:   18.612 ms/op

Iteration   2: 2.794 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.864 ms/op
                 createUser·p0.50:   2.839 ms/op
                 createUser·p0.90:   3.404 ms/op
                 createUser·p0.95:   3.592 ms/op
                 createUser·p0.99:   4.530 ms/op
                 createUser·p0.999:  13.634 ms/op
                 createUser·p0.9999: 18.219 ms/op
                 createUser·p1.00:   19.333 ms/op

Iteration   3: 2.797 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.014 ms/op
                 createUser·p0.50:   2.863 ms/op
                 createUser·p0.90:   3.404 ms/op
                 createUser·p0.95:   3.555 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  7.330 ms/op
                 createUser·p0.9999: 14.788 ms/op
                 createUser·p1.00:   15.188 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 343128
  mean =      2.795 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 29 
    [ 1.250,  2.500) = 145244 
    [ 2.500,  3.750) = 187181 
    [ 3.750,  5.000) = 8759 
    [ 5.000,  6.250) = 1419 
    [ 6.250,  7.500) = 130 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 117 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 63 
    [17.500, 18.750) = 72 

  Percentiles, ms/op:
      p(0.0000) =      0.864 ms/op
     p(50.0000) =      2.839 ms/op
     p(90.0000) =      3.404 ms/op
     p(95.0000) =      3.580 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =     10.975 ms/op
     p(99.9900) =     18.133 ms/op
     p(99.9990) =     18.668 ms/op
     p(99.9999) =     19.333 ms/op
    p(100.0000) =     19.333 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.245 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.756 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.667 ±(99.9%) 0.006 ms/op
Iteration   1: 2.685 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.005 ms/op
                 existUser·p0.50:   2.744 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.404 ms/op
                 existUser·p0.99:   4.104 ms/op
                 existUser·p0.999:  15.221 ms/op
                 existUser·p0.9999: 16.911 ms/op
                 existUser·p1.00:   17.400 ms/op

Iteration   2: 2.692 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.038 ms/op
                 existUser·p0.50:   2.761 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.416 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  7.905 ms/op
                 existUser·p0.9999: 18.715 ms/op
                 existUser·p1.00:   20.021 ms/op

Iteration   3: 2.699 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.085 ms/op
                 existUser·p0.50:   2.703 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.457 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  12.026 ms/op
                 existUser·p0.9999: 14.830 ms/op
                 existUser·p1.00:   15.041 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 356422
  mean =      2.692 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 160644 
    [ 2.500,  5.000) = 194207 
    [ 5.000,  7.500) = 1145 
    [ 7.500, 10.000) = 74 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 198 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.005 ms/op
     p(50.0000) =      2.736 ms/op
     p(90.0000) =      3.277 ms/op
     p(95.0000) =      3.424 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      9.571 ms/op
     p(99.9900) =     17.117 ms/op
     p(99.9990) =     19.915 ms/op
     p(99.9999) =     20.021 ms/op
    p(100.0000) =     20.021 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.630 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 2.875 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.758 ±(99.9%) 0.007 ms/op
Iteration   1: 2.741 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.948 ms/op
                 getUser·p0.50:   2.736 ms/op
                 getUser·p0.90:   3.342 ms/op
                 getUser·p0.95:   3.502 ms/op
                 getUser·p0.99:   4.463 ms/op
                 getUser·p0.999:  16.024 ms/op
                 getUser·p0.9999: 18.143 ms/op
                 getUser·p1.00:   18.907 ms/op

Iteration   2: 2.773 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.013 ms/op
                 getUser·p0.50:   2.789 ms/op
                 getUser·p0.90:   3.379 ms/op
                 getUser·p0.95:   3.617 ms/op
                 getUser·p0.99:   5.161 ms/op
                 getUser·p0.999:  7.496 ms/op
                 getUser·p0.9999: 19.019 ms/op
                 getUser·p1.00:   19.726 ms/op

Iteration   3: 2.711 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.071 ms/op
                 getUser·p0.50:   2.728 ms/op
                 getUser·p0.90:   3.305 ms/op
                 getUser·p0.95:   3.457 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  13.223 ms/op
                 getUser·p0.9999: 16.067 ms/op
                 getUser·p1.00:   16.564 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 349831
  mean =      2.742 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 157433 
    [ 2.500,  3.750) = 182221 
    [ 3.750,  5.000) = 7724 
    [ 5.000,  6.250) = 1815 
    [ 6.250,  7.500) = 224 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 94 
    [16.250, 17.500) = 104 
    [17.500, 18.750) = 66 

  Percentiles, ms/op:
      p(0.0000) =      0.948 ms/op
     p(50.0000) =      2.753 ms/op
     p(90.0000) =      3.342 ms/op
     p(95.0000) =      3.518 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =     13.074 ms/op
     p(99.9900) =     18.350 ms/op
     p(99.9990) =     19.661 ms/op
     p(99.9999) =     19.726 ms/op
    p(100.0000) =     19.726 ms/op


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
# Warmup Iteration   1: 5.654 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 3.413 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.338 ±(99.9%) 0.011 ms/op
Iteration   1: 3.336 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.038 ms/op
                 listUser·p0.50:   3.244 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.915 ms/op
                 listUser·p0.99:   6.336 ms/op
                 listUser·p0.999:  11.993 ms/op
                 listUser·p0.9999: 14.696 ms/op
                 listUser·p1.00:   15.057 ms/op

Iteration   2: 3.333 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.104 ms/op
                 listUser·p0.50:   3.248 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   6.193 ms/op
                 listUser·p0.999:  13.009 ms/op
                 listUser·p0.9999: 16.302 ms/op
                 listUser·p1.00:   16.630 ms/op

Iteration   3: 3.368 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.777 ms/op
                 listUser·p0.50:   3.260 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   5.022 ms/op
                 listUser·p0.99:   6.537 ms/op
                 listUser·p0.999:  12.076 ms/op
                 listUser·p0.9999: 14.353 ms/op
                 listUser·p1.00:   15.172 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 286653
  mean =      3.346 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 41118 
    [ 2.500,  3.750) = 176722 
    [ 3.750,  5.000) = 55612 
    [ 5.000,  6.250) = 9902 
    [ 6.250,  7.500) = 2216 
    [ 7.500,  8.750) = 329 
    [ 8.750, 10.000) = 103 
    [10.000, 11.250) = 183 
    [11.250, 12.500) = 162 
    [12.500, 13.750) = 169 
    [13.750, 15.000) = 71 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.777 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      6.349 ms/op
     p(99.9000) =     12.419 ms/op
     p(99.9900) =     15.335 ms/op
     p(99.9990) =     16.522 ms/op
     p(99.9999) =     16.630 ms/op
    p(100.0000) =     16.630 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  11.620 ± 1.600  ops/ms
ClientPb.existUser                       thrpt       3  11.954 ± 1.763  ops/ms
ClientPb.getUser                         thrpt       3  11.672 ± 0.300  ops/ms
ClientPb.listUser                        thrpt       3   9.615 ± 0.863  ops/ms
ClientPb.createUser                       avgt       3   2.780 ± 0.603   ms/op
ClientPb.existUser                        avgt       3   2.729 ± 0.340   ms/op
ClientPb.getUser                          avgt       3   2.733 ± 0.323   ms/op
ClientPb.listUser                         avgt       3   3.338 ± 0.300   ms/op
ClientPb.createUser                     sample  343128   2.795 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.864           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.839           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.404           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.580           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.506           ms/op
ClientPb.createUser:createUser·p0.999   sample          10.975           ms/op
ClientPb.createUser:createUser·p0.9999  sample          18.133           ms/op
ClientPb.createUser:createUser·p1.00    sample          19.333           ms/op
ClientPb.existUser                      sample  356422   2.692 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.005           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.736           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.277           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.424           ms/op
ClientPb.existUser:existUser·p0.99      sample           4.276           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.571           ms/op
ClientPb.existUser:existUser·p0.9999    sample          17.117           ms/op
ClientPb.existUser:existUser·p1.00      sample          20.021           ms/op
ClientPb.getUser                        sample  349831   2.742 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.948           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.753           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.342           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.518           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.604           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.074           ms/op
ClientPb.getUser:getUser·p0.9999        sample          18.350           ms/op
ClientPb.getUser:getUser·p1.00          sample          19.726           ms/op
ClientPb.listUser                       sample  286653   3.346 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.777           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.252           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.923           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.349           ms/op
ClientPb.listUser:listUser·p0.999       sample          12.419           ms/op
ClientPb.listUser:listUser·p0.9999      sample          15.335           ms/op
ClientPb.listUser:listUser·p1.00        sample          16.630           ms/op
