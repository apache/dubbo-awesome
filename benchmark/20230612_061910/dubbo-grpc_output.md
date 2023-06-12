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
# Warmup Iteration   1: 3.907 ops/ms
# Warmup Iteration   2: 9.120 ops/ms
# Warmup Iteration   3: 9.958 ops/ms
Iteration   1: 10.331 ops/ms
Iteration   2: 10.495 ops/ms
Iteration   3: 10.328 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.385 ±(99.9%) 1.742 ops/ms [Average]
  (min, avg, max) = (10.328, 10.385, 10.495), stdev = 0.095
  CI (99.9%): [8.643, 12.127] (assumes normal distribution)


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
# Warmup Iteration   1: 7.096 ops/ms
# Warmup Iteration   2: 10.233 ops/ms
# Warmup Iteration   3: 10.717 ops/ms
Iteration   1: 10.789 ops/ms
Iteration   2: 10.878 ops/ms
Iteration   3: 10.789 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.819 ±(99.9%) 0.931 ops/ms [Average]
  (min, avg, max) = (10.789, 10.819, 10.878), stdev = 0.051
  CI (99.9%): [9.887, 11.750] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.616 ops/ms
# Warmup Iteration   2: 9.818 ops/ms
# Warmup Iteration   3: 10.363 ops/ms
Iteration   1: 10.256 ops/ms
Iteration   2: 10.305 ops/ms
Iteration   3: 10.502 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.355 ±(99.9%) 2.371 ops/ms [Average]
  (min, avg, max) = (10.256, 10.355, 10.502), stdev = 0.130
  CI (99.9%): [7.984, 12.725] (assumes normal distribution)


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
# Warmup Iteration   1: 5.723 ops/ms
# Warmup Iteration   2: 7.504 ops/ms
# Warmup Iteration   3: 7.754 ops/ms
Iteration   1: 7.699 ops/ms
Iteration   2: 7.940 ops/ms
Iteration   3: 7.915 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.851 ±(99.9%) 2.417 ops/ms [Average]
  (min, avg, max) = (7.699, 7.851, 7.940), stdev = 0.132
  CI (99.9%): [5.434, 10.268] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.312 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.238 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.104 ±(99.9%) 0.003 ms/op
Iteration   1: 3.118 ±(99.9%) 0.002 ms/op
Iteration   2: 3.057 ±(99.9%) 0.002 ms/op
Iteration   3: 3.108 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.094 ±(99.9%) 0.605 ms/op [Average]
  (min, avg, max) = (3.057, 3.094, 3.118), stdev = 0.033
  CI (99.9%): [2.489, 3.700] (assumes normal distribution)


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
# Warmup Iteration   1: 4.066 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.971 ±(99.9%) 0.002 ms/op
Iteration   1: 2.831 ±(99.9%) 0.002 ms/op
Iteration   2: 2.952 ±(99.9%) 0.003 ms/op
Iteration   3: 2.922 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.902 ±(99.9%) 1.147 ms/op [Average]
  (min, avg, max) = (2.831, 2.902, 2.952), stdev = 0.063
  CI (99.9%): [1.755, 4.049] (assumes normal distribution)


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
# Warmup Iteration   1: 4.190 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.150 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.062 ±(99.9%) 0.002 ms/op
Iteration   1: 3.089 ±(99.9%) 0.003 ms/op
Iteration   2: 3.127 ±(99.9%) 0.003 ms/op
Iteration   3: 3.088 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.101 ±(99.9%) 0.399 ms/op [Average]
  (min, avg, max) = (3.088, 3.101, 3.127), stdev = 0.022
  CI (99.9%): [2.703, 3.500] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.917 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.214 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.034 ±(99.9%) 0.010 ms/op
Iteration   1: 4.098 ±(99.9%) 0.014 ms/op
Iteration   2: 4.036 ±(99.9%) 0.014 ms/op
Iteration   3: 3.994 ±(99.9%) 0.036 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.042 ±(99.9%) 0.952 ms/op [Average]
  (min, avg, max) = (3.994, 4.042, 4.098), stdev = 0.052
  CI (99.9%): [3.091, 4.994] (assumes normal distribution)


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
# Warmup Iteration   1: 4.531 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.264 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.129 ±(99.9%) 0.007 ms/op
Iteration   1: 3.111 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.829 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  7.301 ms/op
                 createUser·p0.9999: 16.543 ms/op
                 createUser·p1.00:   16.908 ms/op

Iteration   2: 3.100 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.637 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  7.054 ms/op
                 createUser·p0.9999: 18.536 ms/op
                 createUser·p1.00:   18.842 ms/op

Iteration   3: 3.137 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.806 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  11.450 ms/op
                 createUser·p0.9999: 32.440 ms/op
                 createUser·p1.00:   35.652 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308087
  mean =      3.116 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12664 
    [ 2.500,  5.000) = 293879 
    [ 5.000,  7.500) = 1222 
    [ 7.500, 10.000) = 56 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.637 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      4.425 ms/op
     p(99.9000) =      7.634 ms/op
     p(99.9900) =     31.634 ms/op
     p(99.9990) =     33.156 ms/op
     p(99.9999) =     35.652 ms/op
    p(100.0000) =     35.652 ms/op


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
# Warmup Iteration   1: 4.146 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.940 ±(99.9%) 0.006 ms/op
Iteration   1: 2.970 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.713 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  6.809 ms/op
                 existUser·p0.9999: 15.638 ms/op
                 existUser·p1.00:   15.958 ms/op

Iteration   2: 2.933 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.948 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.330 ms/op
                 existUser·p0.99:   3.752 ms/op
                 existUser·p0.999:  10.435 ms/op
                 existUser·p0.9999: 15.122 ms/op
                 existUser·p1.00:   17.203 ms/op

Iteration   3: 2.854 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.426 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  10.977 ms/op
                 existUser·p0.9999: 22.242 ms/op
                 existUser·p1.00:   22.807 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329120
  mean =      2.918 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32989 
    [ 2.500,  5.000) = 295069 
    [ 5.000,  7.500) = 608 
    [ 7.500, 10.000) = 129 
    [10.000, 12.500) = 165 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.426 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.355 ms/op
     p(95.0000) =      3.580 ms/op
     p(99.0000) =      4.145 ms/op
     p(99.9000) =      9.845 ms/op
     p(99.9900) =     19.773 ms/op
     p(99.9990) =     22.666 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


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
# Warmup Iteration   1: 4.529 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.265 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.197 ±(99.9%) 0.007 ms/op
Iteration   1: 3.152 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.814 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   4.579 ms/op
                 getUser·p0.999:  7.383 ms/op
                 getUser·p0.9999: 13.785 ms/op
                 getUser·p1.00:   14.139 ms/op

Iteration   2: 3.096 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.840 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  6.914 ms/op
                 getUser·p0.9999: 14.554 ms/op
                 getUser·p1.00:   14.713 ms/op

Iteration   3: 3.139 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.691 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  7.145 ms/op
                 getUser·p0.9999: 19.151 ms/op
                 getUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306738
  mean =      3.129 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9333 
    [ 2.500,  5.000) = 295942 
    [ 5.000,  7.500) = 1221 
    [ 7.500, 10.000) = 82 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.691 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      7.178 ms/op
     p(99.9900) =     16.831 ms/op
     p(99.9990) =     22.247 ms/op
     p(99.9999) =     22.348 ms/op
    p(100.0000) =     22.348 ms/op


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
# Warmup Iteration   1: 5.603 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.132 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.111 ±(99.9%) 0.012 ms/op
Iteration   1: 4.110 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.315 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.964 ms/op
                 listUser·p0.99:   7.444 ms/op
                 listUser·p0.999:  14.511 ms/op
                 listUser·p0.9999: 21.470 ms/op
                 listUser·p1.00:   21.955 ms/op

Iteration   2: 4.045 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.085 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  15.598 ms/op
                 listUser·p0.9999: 21.499 ms/op
                 listUser·p1.00:   21.758 ms/op

Iteration   3: 4.057 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.204 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   5.972 ms/op
                 listUser·p0.99:   7.258 ms/op
                 listUser·p0.999:  18.541 ms/op
                 listUser·p0.9999: 24.436 ms/op
                 listUser·p1.00:   25.100 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235625
  mean =      4.071 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2509 
    [ 2.500,  5.000) = 206087 
    [ 5.000,  7.500) = 25168 
    [ 7.500, 10.000) = 1314 
    [10.000, 12.500) = 120 
    [12.500, 15.000) = 133 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.085 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      5.145 ms/op
     p(95.0000) =      5.906 ms/op
     p(99.0000) =      7.266 ms/op
     p(99.9000) =     16.105 ms/op
     p(99.9900) =     23.097 ms/op
     p(99.9990) =     24.955 ms/op
     p(99.9999) =     25.100 ms/op
    p(100.0000) =     25.100 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.385 ± 1.742  ops/ms
ClientGrpc.existUser                       thrpt       3  10.819 ± 0.931  ops/ms
ClientGrpc.getUser                         thrpt       3  10.355 ± 2.371  ops/ms
ClientGrpc.listUser                        thrpt       3   7.851 ± 2.417  ops/ms
ClientGrpc.createUser                       avgt       3   3.094 ± 0.605   ms/op
ClientGrpc.existUser                        avgt       3   2.902 ± 1.147   ms/op
ClientGrpc.getUser                          avgt       3   3.101 ± 0.399   ms/op
ClientGrpc.listUser                         avgt       3   4.042 ± 0.952   ms/op
ClientGrpc.createUser                     sample  308087   3.116 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.637           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.076           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.625           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.838           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.425           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.634           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          31.634           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          35.652           ms/op
ClientGrpc.existUser                      sample  329120   2.918 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.426           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.937           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.355           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.580           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.145           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.845           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.773           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.807           ms/op
ClientGrpc.getUser                        sample  306738   3.129 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.691           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.105           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.613           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.842           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.407           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.178           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.831           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.348           ms/op
ClientGrpc.listUser                       sample  235625   4.071 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.085           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.891           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.145           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.906           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.266           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.105           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.097           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.100           ms/op
