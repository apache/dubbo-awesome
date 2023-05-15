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
# Warmup Iteration   1: 4.629 ops/ms
# Warmup Iteration   2: 9.384 ops/ms
# Warmup Iteration   3: 10.194 ops/ms
Iteration   1: 10.581 ops/ms
Iteration   2: 10.522 ops/ms
Iteration   3: 10.772 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.625 ±(99.9%) 2.384 ops/ms [Average]
  (min, avg, max) = (10.522, 10.625, 10.772), stdev = 0.131
  CI (99.9%): [8.241, 13.010] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.400 ops/ms
# Warmup Iteration   2: 10.480 ops/ms
# Warmup Iteration   3: 10.839 ops/ms
Iteration   1: 10.936 ops/ms
Iteration   2: 11.311 ops/ms
Iteration   3: 11.255 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.167 ±(99.9%) 3.689 ops/ms [Average]
  (min, avg, max) = (10.936, 11.167, 11.311), stdev = 0.202
  CI (99.9%): [7.478, 14.856] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.389 ops/ms
# Warmup Iteration   2: 10.380 ops/ms
# Warmup Iteration   3: 10.830 ops/ms
Iteration   1: 10.839 ops/ms
Iteration   2: 10.674 ops/ms
Iteration   3: 10.778 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.764 ±(99.9%) 1.516 ops/ms [Average]
  (min, avg, max) = (10.674, 10.764, 10.839), stdev = 0.083
  CI (99.9%): [9.248, 12.279] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.660 ops/ms
# Warmup Iteration   2: 7.922 ops/ms
# Warmup Iteration   3: 8.252 ops/ms
Iteration   1: 8.113 ops/ms
Iteration   2: 8.414 ops/ms
Iteration   3: 8.206 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.244 ±(99.9%) 2.819 ops/ms [Average]
  (min, avg, max) = (8.113, 8.244, 8.414), stdev = 0.154
  CI (99.9%): [5.426, 11.063] (assumes normal distribution)


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
# Warmup Iteration   1: 4.155 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.138 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.003 ms/op
Iteration   1: 2.970 ±(99.9%) 0.004 ms/op
Iteration   2: 3.006 ±(99.9%) 0.002 ms/op
Iteration   3: 2.951 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.975 ±(99.9%) 0.514 ms/op [Average]
  (min, avg, max) = (2.951, 2.975, 3.006), stdev = 0.028
  CI (99.9%): [2.462, 3.489] (assumes normal distribution)


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
# Warmup Iteration   1: 3.508 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.936 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.884 ±(99.9%) 0.002 ms/op
Iteration   1: 2.719 ±(99.9%) 0.003 ms/op
Iteration   2: 2.840 ±(99.9%) 0.002 ms/op
Iteration   3: 2.861 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.806 ±(99.9%) 1.397 ms/op [Average]
  (min, avg, max) = (2.719, 2.806, 2.861), stdev = 0.077
  CI (99.9%): [1.409, 4.204] (assumes normal distribution)


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
# Warmup Iteration   1: 4.138 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.058 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.957 ±(99.9%) 0.003 ms/op
Iteration   1: 2.977 ±(99.9%) 0.002 ms/op
Iteration   2: 2.953 ±(99.9%) 0.004 ms/op
Iteration   3: 2.928 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.953 ±(99.9%) 0.454 ms/op [Average]
  (min, avg, max) = (2.928, 2.953, 2.977), stdev = 0.025
  CI (99.9%): [2.499, 3.406] (assumes normal distribution)


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
# Warmup Iteration   1: 5.011 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.982 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.862 ±(99.9%) 0.023 ms/op
Iteration   1: 3.933 ±(99.9%) 0.014 ms/op
Iteration   2: 3.829 ±(99.9%) 0.041 ms/op
Iteration   3: 3.875 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.879 ±(99.9%) 0.945 ms/op [Average]
  (min, avg, max) = (3.829, 3.879, 3.933), stdev = 0.052
  CI (99.9%): [2.934, 4.824] (assumes normal distribution)


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
# Warmup Iteration   1: 4.209 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.138 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.975 ±(99.9%) 0.006 ms/op
Iteration   1: 3.011 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.817 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.707 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  7.680 ms/op
                 createUser·p0.9999: 13.244 ms/op
                 createUser·p1.00:   13.418 ms/op

Iteration   2: 2.998 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.754 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  6.338 ms/op
                 createUser·p0.9999: 13.702 ms/op
                 createUser·p1.00:   14.369 ms/op

Iteration   3: 3.066 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.608 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  10.418 ms/op
                 createUser·p0.9999: 16.688 ms/op
                 createUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317207
  mean =      3.025 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 559 
    [ 1.250,  2.500) = 27982 
    [ 2.500,  3.750) = 271475 
    [ 3.750,  5.000) = 15770 
    [ 5.000,  6.250) = 765 
    [ 6.250,  7.500) = 290 
    [ 7.500,  8.750) = 83 
    [ 8.750, 10.000) = 45 
    [10.000, 11.250) = 35 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.608 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      7.969 ms/op
     p(99.9900) =     15.315 ms/op
     p(99.9990) =     16.968 ms/op
     p(99.9999) =     17.039 ms/op
    p(100.0000) =     17.039 ms/op


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
# Warmup Iteration   1: 3.896 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.956 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.848 ±(99.9%) 0.006 ms/op
Iteration   1: 2.869 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.535 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.228 ms/op
                 existUser·p0.95:   3.408 ms/op
                 existUser·p0.99:   3.838 ms/op
                 existUser·p0.999:  5.874 ms/op
                 existUser·p0.9999: 17.128 ms/op
                 existUser·p1.00:   18.612 ms/op

Iteration   2: 2.856 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.886 ms/op
                 existUser·p0.50:   2.830 ms/op
                 existUser·p0.90:   3.240 ms/op
                 existUser·p0.95:   3.437 ms/op
                 existUser·p0.99:   4.035 ms/op
                 existUser·p0.999:  8.184 ms/op
                 existUser·p0.9999: 13.952 ms/op
                 existUser·p1.00:   14.270 ms/op

Iteration   3: 2.861 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.790 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.224 ms/op
                 existUser·p0.95:   3.341 ms/op
                 existUser·p0.99:   3.809 ms/op
                 existUser·p0.999:  10.076 ms/op
                 existUser·p0.9999: 27.722 ms/op
                 existUser·p1.00:   27.951 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 335499
  mean =      2.862 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40955 
    [ 2.500,  5.000) = 293792 
    [ 5.000,  7.500) = 385 
    [ 7.500, 10.000) = 152 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.535 ms/op
     p(50.0000) =      2.843 ms/op
     p(90.0000) =      3.228 ms/op
     p(95.0000) =      3.391 ms/op
     p(99.0000) =      3.891 ms/op
     p(99.9000) =      8.262 ms/op
     p(99.9900) =     18.594 ms/op
     p(99.9990) =     27.874 ms/op
     p(99.9999) =     27.951 ms/op
    p(100.0000) =     27.951 ms/op


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
# Warmup Iteration   1: 4.242 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.079 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.975 ±(99.9%) 0.007 ms/op
Iteration   1: 2.991 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.760 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.682 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  10.505 ms/op
                 getUser·p0.9999: 14.025 ms/op
                 getUser·p1.00:   14.254 ms/op

Iteration   2: 2.940 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.740 ms/op
                 getUser·p0.50:   2.929 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.604 ms/op
                 getUser·p0.999:  6.872 ms/op
                 getUser·p0.9999: 13.765 ms/op
                 getUser·p1.00:   14.025 ms/op

Iteration   3: 2.923 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.758 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  6.447 ms/op
                 getUser·p0.9999: 16.978 ms/op
                 getUser·p1.00:   17.498 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 325105
  mean =      2.951 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1833 
    [ 1.250,  2.500) = 39877 
    [ 2.500,  3.750) = 267658 
    [ 3.750,  5.000) = 14361 
    [ 5.000,  6.250) = 814 
    [ 6.250,  7.500) = 226 
    [ 7.500,  8.750) = 74 
    [ 8.750, 10.000) = 44 
    [10.000, 11.250) = 46 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 34 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.740 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      7.626 ms/op
     p(99.9900) =     16.358 ms/op
     p(99.9990) =     17.383 ms/op
     p(99.9999) =     17.498 ms/op
    p(100.0000) =     17.498 ms/op


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
# Warmup Iteration   1: 5.365 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.023 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.978 ±(99.9%) 0.011 ms/op
Iteration   1: 3.873 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.264 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  13.311 ms/op
                 listUser·p0.9999: 20.185 ms/op
                 listUser·p1.00:   20.513 ms/op

Iteration   2: 3.851 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.885 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   6.923 ms/op
                 listUser·p0.999:  14.058 ms/op
                 listUser·p0.9999: 15.712 ms/op
                 listUser·p1.00:   16.056 ms/op

Iteration   3: 3.848 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.059 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   5.161 ms/op
                 listUser·p0.99:   6.644 ms/op
                 listUser·p0.999:  15.121 ms/op
                 listUser·p0.9999: 26.892 ms/op
                 listUser·p1.00:   27.197 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248654
  mean =      3.857 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3583 
    [ 2.500,  5.000) = 226185 
    [ 5.000,  7.500) = 17819 
    [ 7.500, 10.000) = 655 
    [10.000, 12.500) = 23 
    [12.500, 15.000) = 228 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.885 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.743 ms/op
     p(95.0000) =      5.497 ms/op
     p(99.0000) =      6.775 ms/op
     p(99.9000) =     14.112 ms/op
     p(99.9900) =     25.264 ms/op
     p(99.9990) =     27.083 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.625 ± 2.384  ops/ms
ClientGrpc.existUser                       thrpt       3  11.167 ± 3.689  ops/ms
ClientGrpc.getUser                         thrpt       3  10.764 ± 1.516  ops/ms
ClientGrpc.listUser                        thrpt       3   8.244 ± 2.819  ops/ms
ClientGrpc.createUser                       avgt       3   2.975 ± 0.514   ms/op
ClientGrpc.existUser                        avgt       3   2.806 ± 1.397   ms/op
ClientGrpc.getUser                          avgt       3   2.953 ± 0.454   ms/op
ClientGrpc.listUser                         avgt       3   3.879 ± 0.945   ms/op
ClientGrpc.createUser                     sample  317207   3.025 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.608           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.990           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.572           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.772           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.415           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.969           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.315           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.039           ms/op
ClientGrpc.existUser                      sample  335499   2.862 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.535           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.843           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.228           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.391           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           3.891           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.262           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.594           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.951           ms/op
ClientGrpc.getUser                        sample  325105   2.951 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.740           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.945           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.531           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.740           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.440           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.626           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.358           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.498           ms/op
ClientGrpc.listUser                       sample  248654   3.857 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.885           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.715           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.743           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.497           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.775           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.112           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.264           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.197           ms/op
