# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.268 ops/ms
# Warmup Iteration   2: 9.121 ops/ms
# Warmup Iteration   3: 10.186 ops/ms
Iteration   1: 10.491 ops/ms
Iteration   2: 10.423 ops/ms
Iteration   3: 10.700 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.538 ±(99.9%) 2.632 ops/ms [Average]
  (min, avg, max) = (10.423, 10.538, 10.700), stdev = 0.144
  CI (99.9%): [7.905, 13.170] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.714 ops/ms
# Warmup Iteration   2: 10.732 ops/ms
# Warmup Iteration   3: 11.190 ops/ms
Iteration   1: 10.932 ops/ms
Iteration   2: 11.095 ops/ms
Iteration   3: 11.165 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.064 ±(99.9%) 2.182 ops/ms [Average]
  (min, avg, max) = (10.932, 11.064, 11.165), stdev = 0.120
  CI (99.9%): [8.882, 13.245] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.239 ops/ms
# Warmup Iteration   2: 10.363 ops/ms
# Warmup Iteration   3: 10.534 ops/ms
Iteration   1: 10.688 ops/ms
Iteration   2: 10.607 ops/ms
Iteration   3: 10.587 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.627 ±(99.9%) 0.974 ops/ms [Average]
  (min, avg, max) = (10.587, 10.627, 10.688), stdev = 0.053
  CI (99.9%): [9.653, 11.601] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.731 ops/ms
# Warmup Iteration   2: 7.862 ops/ms
# Warmup Iteration   3: 8.139 ops/ms
Iteration   1: 8.299 ops/ms
Iteration   2: 8.259 ops/ms
Iteration   3: 8.216 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.258 ±(99.9%) 0.756 ops/ms [Average]
  (min, avg, max) = (8.216, 8.258, 8.299), stdev = 0.041
  CI (99.9%): [7.503, 9.014] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.019 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.133 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.003 ms/op
Iteration   1: 2.971 ±(99.9%) 0.002 ms/op
Iteration   2: 2.932 ±(99.9%) 0.002 ms/op
Iteration   3: 2.975 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.959 ±(99.9%) 0.433 ms/op [Average]
  (min, avg, max) = (2.932, 2.959, 2.975), stdev = 0.024
  CI (99.9%): [2.526, 3.392] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.743 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.028 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.897 ±(99.9%) 0.004 ms/op
Iteration   1: 2.838 ±(99.9%) 0.004 ms/op
Iteration   2: 2.949 ±(99.9%) 0.002 ms/op
Iteration   3: 2.906 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.898 ±(99.9%) 1.021 ms/op [Average]
  (min, avg, max) = (2.838, 2.898, 2.949), stdev = 0.056
  CI (99.9%): [1.877, 3.918] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.096 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.099 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.934 ±(99.9%) 0.003 ms/op
Iteration   1: 2.991 ±(99.9%) 0.003 ms/op
Iteration   2: 2.958 ±(99.9%) 0.004 ms/op
Iteration   3: 2.951 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.967 ±(99.9%) 0.394 ms/op [Average]
  (min, avg, max) = (2.951, 2.967, 2.991), stdev = 0.022
  CI (99.9%): [2.572, 3.361] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.932 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.965 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.897 ±(99.9%) 0.023 ms/op
Iteration   1: 3.965 ±(99.9%) 0.015 ms/op
Iteration   2: 3.911 ±(99.9%) 0.011 ms/op
Iteration   3: 3.918 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.931 ±(99.9%) 0.543 ms/op [Average]
  (min, avg, max) = (3.911, 3.931, 3.965), stdev = 0.030
  CI (99.9%): [3.389, 4.474] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.103 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.181 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.006 ms/op
Iteration   1: 2.953 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.633 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.461 ms/op
                 createUser·p0.95:   3.690 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  6.545 ms/op
                 createUser·p0.9999: 18.159 ms/op
                 createUser·p1.00:   18.481 ms/op

Iteration   2: 3.015 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.748 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  10.571 ms/op
                 createUser·p0.9999: 13.566 ms/op
                 createUser·p1.00:   13.894 ms/op

Iteration   3: 3.003 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.700 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.404 ms/op
                 createUser·p0.95:   3.588 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  7.821 ms/op
                 createUser·p0.9999: 28.923 ms/op
                 createUser·p1.00:   29.491 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321111
  mean =      2.990 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26265 
    [ 2.500,  5.000) = 293589 
    [ 5.000,  7.500) = 936 
    [ 7.500, 10.000) = 83 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.633 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      7.524 ms/op
     p(99.9900) =     27.747 ms/op
     p(99.9990) =     29.403 ms/op
     p(99.9999) =     29.491 ms/op
    p(100.0000) =     29.491 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.759 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.972 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.888 ±(99.9%) 0.007 ms/op
Iteration   1: 2.893 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.590 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  6.685 ms/op
                 existUser·p0.9999: 12.353 ms/op
                 existUser·p1.00:   12.812 ms/op

Iteration   2: 2.888 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.660 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.596 ms/op
                 existUser·p0.999:  6.662 ms/op
                 existUser·p0.9999: 22.577 ms/op
                 existUser·p1.00:   22.872 ms/op

Iteration   3: 2.922 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.486 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  7.447 ms/op
                 existUser·p0.9999: 15.928 ms/op
                 existUser·p1.00:   16.400 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330724
  mean =      2.901 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46296 
    [ 2.500,  5.000) = 283128 
    [ 5.000,  7.500) = 1039 
    [ 7.500, 10.000) = 89 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.486 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.658 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      7.218 ms/op
     p(99.9900) =     16.396 ms/op
     p(99.9990) =     22.796 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.161 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.136 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.982 ±(99.9%) 0.006 ms/op
Iteration   1: 2.970 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.616 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.367 ms/op
                 getUser·p0.95:   3.564 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  7.618 ms/op
                 getUser·p0.9999: 13.131 ms/op
                 getUser·p1.00:   13.517 ms/op

Iteration   2: 3.011 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.664 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  6.349 ms/op
                 getUser·p0.9999: 13.333 ms/op
                 getUser·p1.00:   13.779 ms/op

Iteration   3: 3.020 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.636 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   4.202 ms/op
                 getUser·p0.999:  6.457 ms/op
                 getUser·p0.9999: 25.973 ms/op
                 getUser·p1.00:   26.608 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319730
  mean =      3.000 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20605 
    [ 2.500,  5.000) = 297968 
    [ 5.000,  7.500) = 908 
    [ 7.500, 10.000) = 56 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.616 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      6.784 ms/op
     p(99.9900) =     24.248 ms/op
     p(99.9990) =     26.313 ms/op
     p(99.9999) =     26.608 ms/op
    p(100.0000) =     26.608 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.544 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.097 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.915 ±(99.9%) 0.010 ms/op
Iteration   1: 3.868 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.352 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.817 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  12.888 ms/op
                 listUser·p0.9999: 15.134 ms/op
                 listUser·p1.00:   15.466 ms/op

Iteration   2: 3.913 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.090 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  13.173 ms/op
                 listUser·p0.9999: 15.985 ms/op
                 listUser·p1.00:   16.302 ms/op

Iteration   3: 3.901 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.030 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.817 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   6.752 ms/op
                 listUser·p0.999:  14.091 ms/op
                 listUser·p0.9999: 19.020 ms/op
                 listUser·p1.00:   19.988 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246430
  mean =      3.894 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 5604 
    [ 2.500,  3.750) = 118938 
    [ 3.750,  5.000) = 99483 
    [ 5.000,  6.250) = 16808 
    [ 6.250,  7.500) = 4260 
    [ 7.500,  8.750) = 587 
    [ 8.750, 10.000) = 236 
    [10.000, 11.250) = 97 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 163 
    [13.750, 15.000) = 86 
    [15.000, 16.250) = 43 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.030 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.891 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     13.271 ms/op
     p(99.9900) =     17.772 ms/op
     p(99.9990) =     19.908 ms/op
     p(99.9999) =     19.988 ms/op
    p(100.0000) =     19.988 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.538 ± 2.632  ops/ms
ClientGrpc.existUser                       thrpt       3  11.064 ± 2.182  ops/ms
ClientGrpc.getUser                         thrpt       3  10.627 ± 0.974  ops/ms
ClientGrpc.listUser                        thrpt       3   8.258 ± 0.756  ops/ms
ClientGrpc.createUser                       avgt       3   2.959 ± 0.433   ms/op
ClientGrpc.existUser                        avgt       3   2.898 ± 1.021   ms/op
ClientGrpc.getUser                          avgt       3   2.967 ± 0.394   ms/op
ClientGrpc.listUser                         avgt       3   3.931 ± 0.543   ms/op
ClientGrpc.createUser                     sample  321111   2.990 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.633           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.982           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.482           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.719           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.366           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.524           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.747           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.491           ms/op
ClientGrpc.existUser                      sample  330724   2.901 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.486           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.875           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.457           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.658           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.481           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.218           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.396           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.872           ms/op
ClientGrpc.getUser                        sample  319730   3.000 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.616           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.998           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.465           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.678           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.227           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.784           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.248           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.608           ms/op
ClientGrpc.listUser                       sample  246430   3.894 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.030           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.744           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.891           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.743           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.824           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.271           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.772           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.988           ms/op
