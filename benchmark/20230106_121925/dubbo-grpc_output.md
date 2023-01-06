# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.829 ops/ms
# Warmup Iteration   2: 9.240 ops/ms
# Warmup Iteration   3: 10.598 ops/ms
Iteration   1: 10.873 ops/ms
Iteration   2: 10.516 ops/ms
Iteration   3: 10.581 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.656 ±(99.9%) 3.475 ops/ms [Average]
  (min, avg, max) = (10.516, 10.656, 10.873), stdev = 0.190
  CI (99.9%): [7.182, 14.131] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.183 ops/ms
# Warmup Iteration   2: 11.020 ops/ms
# Warmup Iteration   3: 11.105 ops/ms
Iteration   1: 11.234 ops/ms
Iteration   2: 10.998 ops/ms
Iteration   3: 11.080 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.104 ±(99.9%) 2.189 ops/ms [Average]
  (min, avg, max) = (10.998, 11.104, 11.234), stdev = 0.120
  CI (99.9%): [8.915, 13.293] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.421 ops/ms
# Warmup Iteration   2: 10.224 ops/ms
# Warmup Iteration   3: 10.607 ops/ms
Iteration   1: 10.877 ops/ms
Iteration   2: 10.669 ops/ms
Iteration   3: 10.600 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.715 ±(99.9%) 2.639 ops/ms [Average]
  (min, avg, max) = (10.600, 10.715, 10.877), stdev = 0.145
  CI (99.9%): [8.076, 13.354] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.626 ops/ms
# Warmup Iteration   2: 8.113 ops/ms
# Warmup Iteration   3: 8.398 ops/ms
Iteration   1: 7.747 ops/ms
Iteration   2: 7.660 ops/ms
Iteration   3: 8.282 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.896 ±(99.9%) 6.142 ops/ms [Average]
  (min, avg, max) = (7.660, 7.896, 8.282), stdev = 0.337
  CI (99.9%): [1.754, 14.038] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.007 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.039 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.975 ±(99.9%) 0.004 ms/op
Iteration   1: 3.107 ±(99.9%) 0.001 ms/op
Iteration   2: 3.150 ±(99.9%) 0.013 ms/op
Iteration   3: 3.134 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.130 ±(99.9%) 0.400 ms/op [Average]
  (min, avg, max) = (3.107, 3.130, 3.150), stdev = 0.022
  CI (99.9%): [2.730, 3.531] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.683 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.915 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.959 ±(99.9%) 0.002 ms/op
Iteration   1: 2.866 ±(99.9%) 0.004 ms/op
Iteration   2: 2.933 ±(99.9%) 0.003 ms/op
Iteration   3: 2.915 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.905 ±(99.9%) 0.630 ms/op [Average]
  (min, avg, max) = (2.866, 2.905, 2.933), stdev = 0.035
  CI (99.9%): [2.275, 3.535] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.974 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.054 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.003 ms/op
Iteration   1: 3.112 ±(99.9%) 0.006 ms/op
Iteration   2: 3.042 ±(99.9%) 0.002 ms/op
Iteration   3: 3.080 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.078 ±(99.9%) 0.639 ms/op [Average]
  (min, avg, max) = (3.042, 3.078, 3.112), stdev = 0.035
  CI (99.9%): [2.440, 3.717] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.327 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.113 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.959 ±(99.9%) 0.017 ms/op
Iteration   1: 3.977 ±(99.9%) 0.021 ms/op
Iteration   2: 3.996 ±(99.9%) 0.028 ms/op
Iteration   3: 3.822 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.932 ±(99.9%) 1.742 ms/op [Average]
  (min, avg, max) = (3.822, 3.932, 3.996), stdev = 0.095
  CI (99.9%): [2.190, 5.673] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.032 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.078 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.006 ms/op
Iteration   1: 3.084 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.604 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  7.497 ms/op
                 createUser·p0.9999: 23.294 ms/op
                 createUser·p1.00:   23.626 ms/op

Iteration   2: 2.940 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.428 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.391 ms/op
                 createUser·p0.95:   3.588 ms/op
                 createUser·p0.99:   4.182 ms/op
                 createUser·p0.999:  7.360 ms/op
                 createUser·p0.9999: 23.040 ms/op
                 createUser·p1.00:   23.429 ms/op

Iteration   3: 2.929 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.457 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.355 ms/op
                 createUser·p0.95:   3.510 ms/op
                 createUser·p0.99:   4.080 ms/op
                 createUser·p0.999:  8.634 ms/op
                 createUser·p0.9999: 17.465 ms/op
                 createUser·p1.00:   17.859 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321867
  mean =      2.982 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32178 
    [ 2.500,  5.000) = 288795 
    [ 5.000,  7.500) = 571 
    [ 7.500, 10.000) = 99 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.428 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      7.522 ms/op
     p(99.9900) =     22.899 ms/op
     p(99.9990) =     23.546 ms/op
     p(99.9999) =     23.626 ms/op
    p(100.0000) =     23.626 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.753 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 2.985 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.876 ±(99.9%) 0.006 ms/op
Iteration   1: 2.870 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.752 ms/op
                 existUser·p0.50:   2.830 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   3.875 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  6.655 ms/op
                 existUser·p0.9999: 9.451 ms/op
                 existUser·p1.00:   9.912 ms/op

Iteration   2: 2.964 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.615 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   4.087 ms/op
                 existUser·p0.999:  5.808 ms/op
                 existUser·p0.9999: 17.498 ms/op
                 existUser·p1.00:   17.859 ms/op

Iteration   3: 2.921 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.702 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   4.157 ms/op
                 existUser·p0.999:  10.952 ms/op
                 existUser·p0.9999: 16.122 ms/op
                 existUser·p1.00:   16.368 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329057
  mean =      2.917 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2474 
    [ 1.250,  2.500) = 58436 
    [ 2.500,  3.750) = 248996 
    [ 3.750,  5.000) = 18180 
    [ 5.000,  6.250) = 521 
    [ 6.250,  7.500) = 128 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 44 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.615 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      7.257 ms/op
     p(99.9900) =     16.392 ms/op
     p(99.9990) =     17.727 ms/op
     p(99.9999) =     17.859 ms/op
    p(100.0000) =     17.859 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.884 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.006 ms/op
Iteration   1: 3.003 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.665 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  7.377 ms/op
                 getUser·p0.9999: 11.311 ms/op
                 getUser·p1.00:   12.714 ms/op

Iteration   2: 3.061 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.813 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  7.307 ms/op
                 getUser·p0.9999: 21.430 ms/op
                 getUser·p1.00:   22.479 ms/op

Iteration   3: 3.045 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.808 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  7.430 ms/op
                 getUser·p0.9999: 20.496 ms/op
                 getUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316042
  mean =      3.036 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30948 
    [ 2.500,  5.000) = 284259 
    [ 5.000,  7.500) = 536 
    [ 7.500, 10.000) = 75 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.665 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      7.381 ms/op
     p(99.9900) =     20.873 ms/op
     p(99.9990) =     21.551 ms/op
     p(99.9999) =     22.479 ms/op
    p(100.0000) =     22.479 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.743 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.144 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.095 ±(99.9%) 0.012 ms/op
Iteration   1: 3.931 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.227 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.423 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  15.940 ms/op
                 listUser·p0.9999: 18.149 ms/op
                 listUser·p1.00:   19.333 ms/op

Iteration   2: 4.011 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.292 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  15.073 ms/op
                 listUser·p0.9999: 22.349 ms/op
                 listUser·p1.00:   22.872 ms/op

Iteration   3: 4.010 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.442 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  13.697 ms/op
                 listUser·p0.9999: 24.710 ms/op
                 listUser·p1.00:   25.362 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240783
  mean =      3.984 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3413 
    [ 2.500,  5.000) = 209646 
    [ 5.000,  7.500) = 26675 
    [ 7.500, 10.000) = 629 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 124 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.442 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      5.095 ms/op
     p(95.0000) =      5.562 ms/op
     p(99.0000) =      6.767 ms/op
     p(99.9000) =     15.172 ms/op
     p(99.9900) =     23.263 ms/op
     p(99.9990) =     25.126 ms/op
     p(99.9999) =     25.362 ms/op
    p(100.0000) =     25.362 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.656 ± 3.475  ops/ms
ClientGrpc.existUser                       thrpt       3  11.104 ± 2.189  ops/ms
ClientGrpc.getUser                         thrpt       3  10.715 ± 2.639  ops/ms
ClientGrpc.listUser                        thrpt       3   7.896 ± 6.142  ops/ms
ClientGrpc.createUser                       avgt       3   3.130 ± 0.400   ms/op
ClientGrpc.existUser                        avgt       3   2.905 ± 0.630   ms/op
ClientGrpc.getUser                          avgt       3   3.078 ± 0.639   ms/op
ClientGrpc.listUser                         avgt       3   3.932 ± 1.742   ms/op
ClientGrpc.createUser                     sample  321867   2.982 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.428           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.994           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.514           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.756           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.194           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.522           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.899           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.626           ms/op
ClientGrpc.existUser                      sample  329057   2.917 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.615           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.900           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.584           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.793           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.257           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.392           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.859           ms/op
ClientGrpc.getUser                        sample  316042   3.036 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.665           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.027           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.629           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.813           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.202           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.381           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.873           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.479           ms/op
ClientGrpc.listUser                       sample  240783   3.984 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.442           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.793           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.095           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.562           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.767           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.172           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.263           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.362           ms/op
