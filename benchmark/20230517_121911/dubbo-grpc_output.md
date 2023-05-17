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
# Warmup Iteration   1: 4.040 ops/ms
# Warmup Iteration   2: 8.802 ops/ms
# Warmup Iteration   3: 9.970 ops/ms
Iteration   1: 10.176 ops/ms
Iteration   2: 10.599 ops/ms
Iteration   3: 10.656 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.477 ±(99.9%) 4.784 ops/ms [Average]
  (min, avg, max) = (10.176, 10.477, 10.656), stdev = 0.262
  CI (99.9%): [5.693, 15.262] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.710 ops/ms
# Warmup Iteration   2: 10.742 ops/ms
# Warmup Iteration   3: 10.935 ops/ms
Iteration   1: 11.203 ops/ms
Iteration   2: 11.096 ops/ms
Iteration   3: 11.119 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.139 ±(99.9%) 1.035 ops/ms [Average]
  (min, avg, max) = (11.096, 11.139, 11.203), stdev = 0.057
  CI (99.9%): [10.104, 12.174] (assumes normal distribution)


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
# Warmup Iteration   1: 6.712 ops/ms
# Warmup Iteration   2: 10.047 ops/ms
# Warmup Iteration   3: 10.598 ops/ms
Iteration   1: 10.747 ops/ms
Iteration   2: 10.734 ops/ms
Iteration   3: 10.928 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.803 ±(99.9%) 1.980 ops/ms [Average]
  (min, avg, max) = (10.734, 10.803, 10.928), stdev = 0.109
  CI (99.9%): [8.823, 12.783] (assumes normal distribution)


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
# Warmup Iteration   1: 5.299 ops/ms
# Warmup Iteration   2: 8.044 ops/ms
# Warmup Iteration   3: 8.126 ops/ms
Iteration   1: 8.196 ops/ms
Iteration   2: 8.374 ops/ms
Iteration   3: 8.302 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.290 ±(99.9%) 1.632 ops/ms [Average]
  (min, avg, max) = (8.196, 8.290, 8.374), stdev = 0.089
  CI (99.9%): [6.658, 9.923] (assumes normal distribution)


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
# Warmup Iteration   1: 4.241 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.151 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.005 ms/op
Iteration   1: 3.011 ±(99.9%) 0.003 ms/op
Iteration   2: 2.979 ±(99.9%) 0.002 ms/op
Iteration   3: 3.018 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.003 ±(99.9%) 0.377 ms/op [Average]
  (min, avg, max) = (2.979, 3.003, 3.018), stdev = 0.021
  CI (99.9%): [2.626, 3.379] (assumes normal distribution)


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
# Warmup Iteration   1: 3.975 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.955 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.866 ±(99.9%) 0.004 ms/op
Iteration   1: 2.866 ±(99.9%) 0.003 ms/op
Iteration   2: 2.847 ±(99.9%) 0.004 ms/op
Iteration   3: 2.841 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.851 ±(99.9%) 0.237 ms/op [Average]
  (min, avg, max) = (2.841, 2.851, 2.866), stdev = 0.013
  CI (99.9%): [2.614, 3.088] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.008 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.003 ms/op
Iteration   1: 2.971 ±(99.9%) 0.003 ms/op
Iteration   2: 2.981 ±(99.9%) 0.004 ms/op
Iteration   3: 2.990 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.980 ±(99.9%) 0.174 ms/op [Average]
  (min, avg, max) = (2.971, 2.980, 2.990), stdev = 0.010
  CI (99.9%): [2.806, 3.155] (assumes normal distribution)


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
# Warmup Iteration   1: 4.642 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 4.129 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.983 ±(99.9%) 0.014 ms/op
Iteration   1: 3.875 ±(99.9%) 0.008 ms/op
Iteration   2: 3.790 ±(99.9%) 0.010 ms/op
Iteration   3: 3.886 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.850 ±(99.9%) 0.952 ms/op [Average]
  (min, avg, max) = (3.790, 3.850, 3.886), stdev = 0.052
  CI (99.9%): [2.898, 4.803] (assumes normal distribution)


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
# Warmup Iteration   1: 4.318 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.202 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.005 ms/op
Iteration   1: 2.989 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.776 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.453 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  7.700 ms/op
                 createUser·p0.9999: 13.156 ms/op
                 createUser·p1.00:   13.631 ms/op

Iteration   2: 2.987 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.772 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.695 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  7.005 ms/op
                 createUser·p0.9999: 15.313 ms/op
                 createUser·p1.00:   15.565 ms/op

Iteration   3: 3.033 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.775 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  10.912 ms/op
                 createUser·p0.9999: 15.571 ms/op
                 createUser·p1.00:   16.368 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319524
  mean =      3.003 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 739 
    [ 1.250,  2.500) = 26901 
    [ 2.500,  3.750) = 278238 
    [ 3.750,  5.000) = 12147 
    [ 5.000,  6.250) = 813 
    [ 6.250,  7.500) = 275 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 91 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 112 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 50 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.772 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      9.634 ms/op
     p(99.9900) =     15.369 ms/op
     p(99.9990) =     16.319 ms/op
     p(99.9999) =     16.368 ms/op
    p(100.0000) =     16.368 ms/op


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
# Warmup Iteration   1: 4.060 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.970 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.886 ±(99.9%) 0.005 ms/op
Iteration   1: 2.850 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.605 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  6.294 ms/op
                 existUser·p0.9999: 12.667 ms/op
                 existUser·p1.00:   13.156 ms/op

Iteration   2: 2.927 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.558 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  5.882 ms/op
                 existUser·p0.9999: 22.184 ms/op
                 existUser·p1.00:   22.446 ms/op

Iteration   3: 2.874 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.685 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.543 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  11.793 ms/op
                 existUser·p0.9999: 16.136 ms/op
                 existUser·p1.00:   17.334 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332862
  mean =      2.883 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50978 
    [ 2.500,  5.000) = 280680 
    [ 5.000,  7.500) = 834 
    [ 7.500, 10.000) = 100 
    [10.000, 12.500) = 160 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      2.855 ms/op
     p(90.0000) =      3.387 ms/op
     p(95.0000) =      3.588 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      7.883 ms/op
     p(99.9900) =     17.334 ms/op
     p(99.9990) =     22.370 ms/op
     p(99.9999) =     22.446 ms/op
    p(100.0000) =     22.446 ms/op


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
# Warmup Iteration   1: 4.237 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.244 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.006 ms/op
Iteration   1: 3.007 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.780 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.686 ms/op
                 getUser·p0.999:  6.645 ms/op
                 getUser·p0.9999: 14.839 ms/op
                 getUser·p1.00:   15.139 ms/op

Iteration   2: 2.995 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.702 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.457 ms/op
                 getUser·p0.95:   3.670 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  6.922 ms/op
                 getUser·p0.9999: 15.220 ms/op
                 getUser·p1.00:   15.483 ms/op

Iteration   3: 3.001 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.866 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.618 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  7.975 ms/op
                 getUser·p0.9999: 23.473 ms/op
                 getUser·p1.00:   24.936 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319873
  mean =      3.001 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23802 
    [ 2.500,  5.000) = 294654 
    [ 5.000,  7.500) = 1132 
    [ 7.500, 10.000) = 91 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.702 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      7.202 ms/op
     p(99.9900) =     22.580 ms/op
     p(99.9990) =     24.689 ms/op
     p(99.9999) =     24.936 ms/op
    p(100.0000) =     24.936 ms/op


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
# Warmup Iteration   1: 5.401 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.100 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.903 ±(99.9%) 0.011 ms/op
Iteration   1: 3.920 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.409 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  13.088 ms/op
                 listUser·p0.9999: 18.410 ms/op
                 listUser·p1.00:   22.446 ms/op

Iteration   2: 3.910 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.468 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  14.678 ms/op
                 listUser·p0.9999: 16.384 ms/op
                 listUser·p1.00:   18.776 ms/op

Iteration   3: 3.890 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.157 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  15.401 ms/op
                 listUser·p0.9999: 25.143 ms/op
                 listUser·p1.00:   26.051 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245644
  mean =      3.907 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3136 
    [ 2.500,  5.000) = 221120 
    [ 5.000,  7.500) = 20314 
    [ 7.500, 10.000) = 609 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 175 
    [15.000, 17.500) = 128 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.157 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.866 ms/op
     p(95.0000) =      5.628 ms/op
     p(99.0000) =      6.767 ms/op
     p(99.9000) =     14.632 ms/op
     p(99.9900) =     24.347 ms/op
     p(99.9990) =     25.794 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.477 ± 4.784  ops/ms
ClientGrpc.existUser                       thrpt       3  11.139 ± 1.035  ops/ms
ClientGrpc.getUser                         thrpt       3  10.803 ± 1.980  ops/ms
ClientGrpc.listUser                        thrpt       3   8.290 ± 1.632  ops/ms
ClientGrpc.createUser                       avgt       3   3.003 ± 0.377   ms/op
ClientGrpc.existUser                        avgt       3   2.851 ± 0.237   ms/op
ClientGrpc.getUser                          avgt       3   2.980 ± 0.174   ms/op
ClientGrpc.listUser                         avgt       3   3.850 ± 0.952   ms/op
ClientGrpc.createUser                     sample  319524   3.003 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.772           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.978           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.518           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.707           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.350           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.634           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.369           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.368           ms/op
ClientGrpc.existUser                      sample  332862   2.883 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.558           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.855           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.387           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.588           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.260           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.883           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.334           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.446           ms/op
ClientGrpc.getUser                        sample  319873   3.001 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.702           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.970           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.482           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.707           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.440           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.202           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.580           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.936           ms/op
ClientGrpc.listUser                       sample  245644   3.907 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.157           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.744           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.866           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.628           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.767           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.632           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.347           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.051           ms/op
