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
# Warmup Iteration   1: 4.176 ops/ms
# Warmup Iteration   2: 8.486 ops/ms
# Warmup Iteration   3: 9.827 ops/ms
Iteration   1: 10.370 ops/ms
Iteration   2: 10.204 ops/ms
Iteration   3: 10.480 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.351 ±(99.9%) 2.532 ops/ms [Average]
  (min, avg, max) = (10.204, 10.351, 10.480), stdev = 0.139
  CI (99.9%): [7.819, 12.884] (assumes normal distribution)


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
# Warmup Iteration   1: 7.376 ops/ms
# Warmup Iteration   2: 10.490 ops/ms
# Warmup Iteration   3: 10.783 ops/ms
Iteration   1: 11.013 ops/ms
Iteration   2: 10.855 ops/ms
Iteration   3: 10.975 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.948 ±(99.9%) 1.503 ops/ms [Average]
  (min, avg, max) = (10.855, 10.948, 11.013), stdev = 0.082
  CI (99.9%): [9.445, 12.451] (assumes normal distribution)


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
# Warmup Iteration   1: 6.877 ops/ms
# Warmup Iteration   2: 9.961 ops/ms
# Warmup Iteration   3: 10.490 ops/ms
Iteration   1: 10.316 ops/ms
Iteration   2: 10.552 ops/ms
Iteration   3: 10.461 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.443 ±(99.9%) 2.171 ops/ms [Average]
  (min, avg, max) = (10.316, 10.443, 10.552), stdev = 0.119
  CI (99.9%): [8.272, 12.613] (assumes normal distribution)


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
# Warmup Iteration   1: 6.217 ops/ms
# Warmup Iteration   2: 7.665 ops/ms
# Warmup Iteration   3: 7.954 ops/ms
Iteration   1: 7.942 ops/ms
Iteration   2: 8.059 ops/ms
Iteration   3: 8.124 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.042 ±(99.9%) 1.687 ops/ms [Average]
  (min, avg, max) = (7.942, 8.042, 8.124), stdev = 0.092
  CI (99.9%): [6.354, 9.729] (assumes normal distribution)


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
# Warmup Iteration   1: 4.238 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.231 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.167 ±(99.9%) 0.003 ms/op
Iteration   1: 3.149 ±(99.9%) 0.003 ms/op
Iteration   2: 3.199 ±(99.9%) 0.002 ms/op
Iteration   3: 3.158 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.169 ±(99.9%) 0.489 ms/op [Average]
  (min, avg, max) = (3.149, 3.169, 3.199), stdev = 0.027
  CI (99.9%): [2.680, 3.658] (assumes normal distribution)


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
# Warmup Iteration   1: 3.757 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.111 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.002 ms/op
Iteration   1: 2.932 ±(99.9%) 0.002 ms/op
Iteration   2: 2.979 ±(99.9%) 0.002 ms/op
Iteration   3: 2.933 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.948 ±(99.9%) 0.490 ms/op [Average]
  (min, avg, max) = (2.932, 2.948, 2.979), stdev = 0.027
  CI (99.9%): [2.458, 3.438] (assumes normal distribution)


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
# Warmup Iteration   1: 4.280 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.184 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.105 ±(99.9%) 0.002 ms/op
Iteration   1: 3.052 ±(99.9%) 0.004 ms/op
Iteration   2: 3.031 ±(99.9%) 0.003 ms/op
Iteration   3: 3.090 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.058 ±(99.9%) 0.542 ms/op [Average]
  (min, avg, max) = (3.031, 3.058, 3.090), stdev = 0.030
  CI (99.9%): [2.516, 3.599] (assumes normal distribution)


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
# Warmup Iteration   1: 4.985 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.095 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.071 ±(99.9%) 0.010 ms/op
Iteration   1: 3.986 ±(99.9%) 0.012 ms/op
Iteration   2: 4.014 ±(99.9%) 0.015 ms/op
Iteration   3: 3.921 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.974 ±(99.9%) 0.874 ms/op [Average]
  (min, avg, max) = (3.921, 3.974, 4.014), stdev = 0.048
  CI (99.9%): [3.100, 4.848] (assumes normal distribution)


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
# Warmup Iteration   1: 4.480 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.245 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.136 ±(99.9%) 0.007 ms/op
Iteration   1: 3.108 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.596 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   3.973 ms/op
                 createUser·p0.99:   4.841 ms/op
                 createUser·p0.999:  8.283 ms/op
                 createUser·p0.9999: 13.889 ms/op
                 createUser·p1.00:   14.107 ms/op

Iteration   2: 3.069 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.586 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   4.833 ms/op
                 createUser·p0.999:  8.345 ms/op
                 createUser·p0.9999: 14.631 ms/op
                 createUser·p1.00:   14.877 ms/op

Iteration   3: 3.087 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.837 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   5.054 ms/op
                 createUser·p0.999:  9.667 ms/op
                 createUser·p0.9999: 18.186 ms/op
                 createUser·p1.00:   19.071 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310973
  mean =      3.088 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 821 
    [ 1.250,  2.500) = 21234 
    [ 2.500,  3.750) = 264150 
    [ 3.750,  5.000) = 21989 
    [ 5.000,  6.250) = 1799 
    [ 6.250,  7.500) = 390 
    [ 7.500,  8.750) = 187 
    [ 8.750, 10.000) = 163 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 79 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.586 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      4.923 ms/op
     p(99.9000) =      9.404 ms/op
     p(99.9900) =     16.300 ms/op
     p(99.9990) =     19.002 ms/op
     p(99.9999) =     19.071 ms/op
    p(100.0000) =     19.071 ms/op


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
# Warmup Iteration   1: 3.911 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.181 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.006 ms/op
Iteration   1: 2.937 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.768 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.841 ms/op
                 existUser·p0.999:  7.168 ms/op
                 existUser·p0.9999: 14.570 ms/op
                 existUser·p1.00:   17.367 ms/op

Iteration   2: 3.035 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.825 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   4.653 ms/op
                 existUser·p0.999:  8.248 ms/op
                 existUser·p0.9999: 14.835 ms/op
                 existUser·p1.00:   15.630 ms/op

Iteration   3: 2.985 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.615 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   4.547 ms/op
                 existUser·p0.999:  8.749 ms/op
                 existUser·p0.9999: 16.876 ms/op
                 existUser·p1.00:   17.334 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321578
  mean =      2.985 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1813 
    [ 1.250,  2.500) = 26720 
    [ 2.500,  3.750) = 276202 
    [ 3.750,  5.000) = 14611 
    [ 5.000,  6.250) = 1226 
    [ 6.250,  7.500) = 543 
    [ 7.500,  8.750) = 204 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 43 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 57 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 68 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.615 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      4.678 ms/op
     p(99.9000) =      8.266 ms/op
     p(99.9900) =     16.777 ms/op
     p(99.9990) =     17.262 ms/op
     p(99.9999) =     17.367 ms/op
    p(100.0000) =     17.367 ms/op


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
# Warmup Iteration   1: 4.248 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.186 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.101 ±(99.9%) 0.007 ms/op
Iteration   1: 3.071 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.694 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  7.216 ms/op
                 getUser·p0.9999: 13.091 ms/op
                 getUser·p1.00:   13.287 ms/op

Iteration   2: 3.095 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.897 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   4.792 ms/op
                 getUser·p0.999:  9.912 ms/op
                 getUser·p0.9999: 24.510 ms/op
                 getUser·p1.00:   24.936 ms/op

Iteration   3: 3.099 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.821 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.801 ms/op
                 getUser·p0.999:  10.544 ms/op
                 getUser·p0.9999: 18.285 ms/op
                 getUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310746
  mean =      3.088 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14474 
    [ 2.500,  5.000) = 293930 
    [ 5.000,  7.500) = 1887 
    [ 7.500, 10.000) = 167 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.694 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.710 ms/op
     p(99.9000) =      9.654 ms/op
     p(99.9900) =     22.315 ms/op
     p(99.9990) =     24.871 ms/op
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
# Warmup Iteration   1: 5.620 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.116 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.031 ±(99.9%) 0.011 ms/op
Iteration   1: 3.958 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.155 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  14.354 ms/op
                 listUser·p0.9999: 18.019 ms/op
                 listUser·p1.00:   19.104 ms/op

Iteration   2: 4.081 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.029 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   5.415 ms/op
                 listUser·p0.95:   6.062 ms/op
                 listUser·p0.99:   7.504 ms/op
                 listUser·p0.999:  16.777 ms/op
                 listUser·p0.9999: 21.566 ms/op
                 listUser·p1.00:   22.184 ms/op

Iteration   3: 3.990 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.176 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  17.203 ms/op
                 listUser·p0.9999: 18.676 ms/op
                 listUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239687
  mean =      4.009 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3649 
    [ 2.500,  5.000) = 206751 
    [ 5.000,  7.500) = 27513 
    [ 7.500, 10.000) = 1234 
    [10.000, 12.500) = 133 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 171 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.029 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      5.177 ms/op
     p(95.0000) =      5.800 ms/op
     p(99.0000) =      7.176 ms/op
     p(99.9000) =     16.024 ms/op
     p(99.9900) =     20.023 ms/op
     p(99.9990) =     22.283 ms/op
     p(99.9999) =     22.348 ms/op
    p(100.0000) =     22.348 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.351 ± 2.532  ops/ms
ClientGrpc.existUser                       thrpt       3  10.948 ± 1.503  ops/ms
ClientGrpc.getUser                         thrpt       3  10.443 ± 2.171  ops/ms
ClientGrpc.listUser                        thrpt       3   8.042 ± 1.687  ops/ms
ClientGrpc.createUser                       avgt       3   3.169 ± 0.489   ms/op
ClientGrpc.existUser                        avgt       3   2.948 ± 0.490   ms/op
ClientGrpc.getUser                          avgt       3   3.058 ± 0.542   ms/op
ClientGrpc.listUser                         avgt       3   3.974 ± 0.874   ms/op
ClientGrpc.createUser                     sample  310973   3.088 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.586           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.047           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.666           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.928           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.923           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.404           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.300           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.071           ms/op
ClientGrpc.existUser                      sample  321578   2.985 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.615           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.945           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.518           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.764           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.678           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.266           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.777           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.367           ms/op
ClientGrpc.getUser                        sample  310746   3.088 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.694           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.576           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.809           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.710           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.654           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.315           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.936           ms/op
ClientGrpc.listUser                       sample  239687   4.009 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.029           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.801           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.177           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.800           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.176           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.024           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.023           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.348           ms/op
