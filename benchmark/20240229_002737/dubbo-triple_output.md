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
# Warmup Iteration   1: 4.966 ops/ms
# Warmup Iteration   2: 12.151 ops/ms
# Warmup Iteration   3: 12.424 ops/ms
Iteration   1: 12.608 ops/ms
Iteration   2: 12.692 ops/ms
Iteration   3: 12.734 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.678 ±(99.9%) 1.172 ops/ms [Average]
  (min, avg, max) = (12.608, 12.678, 12.734), stdev = 0.064
  CI (99.9%): [11.506, 13.850] (assumes normal distribution)


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
# Warmup Iteration   1: 8.448 ops/ms
# Warmup Iteration   2: 13.157 ops/ms
# Warmup Iteration   3: 13.046 ops/ms
Iteration   1: 13.053 ops/ms
Iteration   2: 13.291 ops/ms
Iteration   3: 13.248 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.197 ±(99.9%) 2.308 ops/ms [Average]
  (min, avg, max) = (13.053, 13.197, 13.291), stdev = 0.126
  CI (99.9%): [10.890, 15.505] (assumes normal distribution)


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
# Warmup Iteration   1: 7.609 ops/ms
# Warmup Iteration   2: 12.748 ops/ms
# Warmup Iteration   3: 13.010 ops/ms
Iteration   1: 12.936 ops/ms
Iteration   2: 12.991 ops/ms
Iteration   3: 13.010 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.979 ±(99.9%) 0.702 ops/ms [Average]
  (min, avg, max) = (12.936, 12.979, 13.010), stdev = 0.038
  CI (99.9%): [12.277, 13.681] (assumes normal distribution)


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
# Warmup Iteration   1: 6.845 ops/ms
# Warmup Iteration   2: 10.536 ops/ms
# Warmup Iteration   3: 10.594 ops/ms
Iteration   1: 10.714 ops/ms
Iteration   2: 10.610 ops/ms
Iteration   3: 10.616 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.647 ±(99.9%) 1.067 ops/ms [Average]
  (min, avg, max) = (10.610, 10.647, 10.714), stdev = 0.058
  CI (99.9%): [9.580, 11.714] (assumes normal distribution)


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
# Warmup Iteration   1: 3.893 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.541 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.472 ±(99.9%) 0.004 ms/op
Iteration   1: 2.494 ±(99.9%) 0.005 ms/op
Iteration   2: 2.501 ±(99.9%) 0.004 ms/op
Iteration   3: 2.481 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.492 ±(99.9%) 0.191 ms/op [Average]
  (min, avg, max) = (2.481, 2.492, 2.501), stdev = 0.010
  CI (99.9%): [2.301, 2.683] (assumes normal distribution)


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
# Warmup Iteration   1: 3.632 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.376 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.402 ±(99.9%) 0.004 ms/op
Iteration   1: 2.405 ±(99.9%) 0.003 ms/op
Iteration   2: 2.418 ±(99.9%) 0.003 ms/op
Iteration   3: 2.424 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.416 ±(99.9%) 0.185 ms/op [Average]
  (min, avg, max) = (2.405, 2.416, 2.424), stdev = 0.010
  CI (99.9%): [2.231, 2.600] (assumes normal distribution)


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
# Warmup Iteration   1: 3.801 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.487 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.441 ±(99.9%) 0.004 ms/op
Iteration   1: 2.453 ±(99.9%) 0.004 ms/op
Iteration   2: 2.470 ±(99.9%) 0.003 ms/op
Iteration   3: 2.459 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.461 ±(99.9%) 0.151 ms/op [Average]
  (min, avg, max) = (2.453, 2.461, 2.470), stdev = 0.008
  CI (99.9%): [2.310, 2.611] (assumes normal distribution)


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
# Warmup Iteration   1: 4.768 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.017 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.005 ms/op
Iteration   1: 2.986 ±(99.9%) 0.006 ms/op
Iteration   2: 3.007 ±(99.9%) 0.006 ms/op
Iteration   3: 2.993 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.995 ±(99.9%) 0.194 ms/op [Average]
  (min, avg, max) = (2.986, 2.995, 3.007), stdev = 0.011
  CI (99.9%): [2.802, 3.189] (assumes normal distribution)


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
# Warmup Iteration   1: 4.020 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.630 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.486 ±(99.9%) 0.005 ms/op
Iteration   1: 2.515 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.988 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.895 ms/op
                 createUser·p0.999:  11.154 ms/op
                 createUser·p0.9999: 13.063 ms/op
                 createUser·p1.00:   13.369 ms/op

Iteration   2: 2.516 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.861 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.449 ms/op
                 createUser·p0.999:  11.158 ms/op
                 createUser·p0.9999: 17.990 ms/op
                 createUser·p1.00:   18.186 ms/op

Iteration   3: 2.541 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.999 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   4.219 ms/op
                 createUser·p0.999:  8.540 ms/op
                 createUser·p0.9999: 10.928 ms/op
                 createUser·p1.00:   13.566 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379927
  mean =      2.524 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 183202 
    [ 2.500,  3.750) = 192289 
    [ 3.750,  5.000) = 3259 
    [ 5.000,  6.250) = 529 
    [ 6.250,  7.500) = 117 
    [ 7.500,  8.750) = 93 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 129 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.861 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.846 ms/op
     p(99.9000) =      8.978 ms/op
     p(99.9900) =     13.173 ms/op
     p(99.9990) =     18.153 ms/op
     p(99.9999) =     18.186 ms/op
    p(100.0000) =     18.186 ms/op


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
# Warmup Iteration   1: 3.617 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.423 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.414 ±(99.9%) 0.005 ms/op
Iteration   1: 2.384 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.893 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   2.892 ms/op
                 existUser·p0.95:   2.990 ms/op
                 existUser·p0.99:   3.412 ms/op
                 existUser·p0.999:  5.570 ms/op
                 existUser·p0.9999: 13.254 ms/op
                 existUser·p1.00:   14.287 ms/op

Iteration   2: 2.408 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.911 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.920 ms/op
                 existUser·p0.95:   3.015 ms/op
                 existUser·p0.99:   3.391 ms/op
                 existUser·p0.999:  7.491 ms/op
                 existUser·p0.9999: 13.332 ms/op
                 existUser·p1.00:   13.631 ms/op

Iteration   3: 2.408 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.664 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.789 ms/op
                 existUser·p0.999:  8.194 ms/op
                 existUser·p0.9999: 11.432 ms/op
                 existUser·p1.00:   12.009 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 399588
  mean =      2.400 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 82 
    [ 1.250,  2.500) = 202555 
    [ 2.500,  3.750) = 194082 
    [ 3.750,  5.000) = 2203 
    [ 5.000,  6.250) = 225 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 91 
    [11.250, 12.500) = 104 
    [12.500, 13.750) = 105 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.664 ms/op
     p(50.0000) =      2.474 ms/op
     p(90.0000) =      2.912 ms/op
     p(95.0000) =      3.015 ms/op
     p(99.0000) =      3.535 ms/op
     p(99.9000) =      7.437 ms/op
     p(99.9900) =     13.141 ms/op
     p(99.9990) =     13.796 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.790 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.502 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.432 ±(99.9%) 0.006 ms/op
Iteration   1: 2.451 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.931 ms/op
                 getUser·p0.50:   2.454 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.797 ms/op
                 getUser·p0.999:  7.248 ms/op
                 getUser·p0.9999: 14.007 ms/op
                 getUser·p1.00:   14.402 ms/op

Iteration   2: 2.457 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.924 ms/op
                 getUser·p0.50:   2.466 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  9.187 ms/op
                 getUser·p0.9999: 12.877 ms/op
                 getUser·p1.00:   13.599 ms/op

Iteration   3: 2.424 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.794 ms/op
                 getUser·p0.50:   2.433 ms/op
                 getUser·p0.90:   2.957 ms/op
                 getUser·p0.95:   3.088 ms/op
                 getUser·p0.99:   3.797 ms/op
                 getUser·p0.999:  6.246 ms/op
                 getUser·p0.9999: 10.600 ms/op
                 getUser·p1.00:   10.994 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 392429
  mean =      2.444 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 128 
    [ 1.250,  2.500) = 201170 
    [ 2.500,  3.750) = 185989 
    [ 3.750,  5.000) = 4015 
    [ 5.000,  6.250) = 675 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 96 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 93 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.794 ms/op
     p(50.0000) =      2.454 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.977 ms/op
     p(99.9000) =      7.582 ms/op
     p(99.9900) =     13.402 ms/op
     p(99.9990) =     14.173 ms/op
     p(99.9999) =     14.402 ms/op
    p(100.0000) =     14.402 ms/op


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
# Warmup Iteration   1: 4.855 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.035 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.998 ±(99.9%) 0.009 ms/op
Iteration   1: 2.973 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.829 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  9.411 ms/op
                 listUser·p0.9999: 18.218 ms/op
                 listUser·p1.00:   19.661 ms/op

Iteration   2: 2.977 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.878 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  9.228 ms/op
                 listUser·p0.9999: 10.764 ms/op
                 listUser·p1.00:   11.796 ms/op

Iteration   3: 2.971 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.980 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.415 ms/op
                 listUser·p0.999:  9.657 ms/op
                 listUser·p0.9999: 11.717 ms/op
                 listUser·p1.00:   12.173 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322589
  mean =      2.974 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 189 
    [ 1.250,  2.500) = 99127 
    [ 2.500,  3.750) = 184731 
    [ 3.750,  5.000) = 31389 
    [ 5.000,  6.250) = 5997 
    [ 6.250,  7.500) = 479 
    [ 7.500,  8.750) = 215 
    [ 8.750, 10.000) = 233 
    [10.000, 11.250) = 158 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.829 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =      9.421 ms/op
     p(99.9900) =     15.561 ms/op
     p(99.9990) =     18.860 ms/op
     p(99.9999) =     19.661 ms/op
    p(100.0000) =     19.661 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.678 ± 1.172  ops/ms
ClientPb.existUser                       thrpt       3  13.197 ± 2.308  ops/ms
ClientPb.getUser                         thrpt       3  12.979 ± 0.702  ops/ms
ClientPb.listUser                        thrpt       3  10.647 ± 1.067  ops/ms
ClientPb.createUser                       avgt       3   2.492 ± 0.191   ms/op
ClientPb.existUser                        avgt       3   2.416 ± 0.185   ms/op
ClientPb.getUser                          avgt       3   2.461 ± 0.151   ms/op
ClientPb.listUser                         avgt       3   2.995 ± 0.194   ms/op
ClientPb.createUser                     sample  379927   2.524 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.861           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.605           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.056           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.846           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.978           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.173           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.186           ms/op
ClientPb.existUser                      sample  399588   2.400 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.664           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.474           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.912           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.015           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.535           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.437           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.141           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.287           ms/op
ClientPb.getUser                        sample  392429   2.444 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.794           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.454           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.986           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.125           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.977           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.582           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.402           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.402           ms/op
ClientPb.listUser                       sample  322589   2.974 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.829           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.900           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.497           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.421           ms/op
ClientPb.listUser:listUser·p0.9999      sample          15.561           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.661           ms/op
