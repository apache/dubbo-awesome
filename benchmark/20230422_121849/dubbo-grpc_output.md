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
# Warmup Iteration   1: 4.109 ops/ms
# Warmup Iteration   2: 9.044 ops/ms
# Warmup Iteration   3: 10.169 ops/ms
Iteration   1: 10.648 ops/ms
Iteration   2: 10.632 ops/ms
Iteration   3: 10.706 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.662 ±(99.9%) 0.718 ops/ms [Average]
  (min, avg, max) = (10.632, 10.662, 10.706), stdev = 0.039
  CI (99.9%): [9.943, 11.380] (assumes normal distribution)


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
# Warmup Iteration   1: 8.003 ops/ms
# Warmup Iteration   2: 10.862 ops/ms
# Warmup Iteration   3: 11.229 ops/ms
Iteration   1: 11.659 ops/ms
Iteration   2: 11.368 ops/ms
Iteration   3: 11.271 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.433 ±(99.9%) 3.681 ops/ms [Average]
  (min, avg, max) = (11.271, 11.433, 11.659), stdev = 0.202
  CI (99.9%): [7.752, 15.114] (assumes normal distribution)


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
# Warmup Iteration   1: 6.962 ops/ms
# Warmup Iteration   2: 10.743 ops/ms
# Warmup Iteration   3: 10.659 ops/ms
Iteration   1: 10.845 ops/ms
Iteration   2: 10.677 ops/ms
Iteration   3: 10.647 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.723 ±(99.9%) 1.952 ops/ms [Average]
  (min, avg, max) = (10.647, 10.723, 10.845), stdev = 0.107
  CI (99.9%): [8.771, 12.675] (assumes normal distribution)


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
# Warmup Iteration   1: 5.918 ops/ms
# Warmup Iteration   2: 7.886 ops/ms
# Warmup Iteration   3: 8.280 ops/ms
Iteration   1: 8.013 ops/ms
Iteration   2: 8.313 ops/ms
Iteration   3: 8.286 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.204 ±(99.9%) 3.021 ops/ms [Average]
  (min, avg, max) = (8.013, 8.204, 8.313), stdev = 0.166
  CI (99.9%): [5.183, 11.225] (assumes normal distribution)


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
# Warmup Iteration   1: 4.339 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.138 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.003 ms/op
Iteration   1: 2.977 ±(99.9%) 0.004 ms/op
Iteration   2: 2.918 ±(99.9%) 0.002 ms/op
Iteration   3: 2.985 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.960 ±(99.9%) 0.668 ms/op [Average]
  (min, avg, max) = (2.918, 2.960, 2.985), stdev = 0.037
  CI (99.9%): [2.292, 3.628] (assumes normal distribution)


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
# Warmup Iteration   1: 4.247 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.018 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.849 ±(99.9%) 0.004 ms/op
Iteration   1: 2.847 ±(99.9%) 0.002 ms/op
Iteration   2: 2.750 ±(99.9%) 0.004 ms/op
Iteration   3: 2.868 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.821 ±(99.9%) 1.147 ms/op [Average]
  (min, avg, max) = (2.750, 2.821, 2.868), stdev = 0.063
  CI (99.9%): [1.674, 3.969] (assumes normal distribution)


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
# Warmup Iteration   1: 4.134 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.132 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.033 ±(99.9%) 0.002 ms/op
Iteration   1: 3.004 ±(99.9%) 0.003 ms/op
Iteration   2: 3.018 ±(99.9%) 0.003 ms/op
Iteration   3: 3.050 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.024 ±(99.9%) 0.434 ms/op [Average]
  (min, avg, max) = (3.004, 3.024, 3.050), stdev = 0.024
  CI (99.9%): [2.591, 3.458] (assumes normal distribution)


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
# Warmup Iteration   1: 5.212 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.042 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.930 ±(99.9%) 0.020 ms/op
Iteration   1: 3.921 ±(99.9%) 0.015 ms/op
Iteration   2: 3.933 ±(99.9%) 0.010 ms/op
Iteration   3: 3.909 ±(99.9%) 0.031 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.921 ±(99.9%) 0.218 ms/op [Average]
  (min, avg, max) = (3.909, 3.921, 3.933), stdev = 0.012
  CI (99.9%): [3.703, 4.139] (assumes normal distribution)


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
# Warmup Iteration   1: 4.562 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.144 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.005 ms/op
Iteration   1: 2.965 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.900 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.682 ms/op
                 createUser·p0.99:   4.653 ms/op
                 createUser·p0.999:  6.522 ms/op
                 createUser·p0.9999: 12.806 ms/op
                 createUser·p1.00:   13.173 ms/op

Iteration   2: 2.995 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.539 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.645 ms/op
                 createUser·p0.999:  9.083 ms/op
                 createUser·p0.9999: 14.002 ms/op
                 createUser·p1.00:   14.615 ms/op

Iteration   3: 2.997 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.707 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.731 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  7.662 ms/op
                 createUser·p0.9999: 16.908 ms/op
                 createUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321509
  mean =      2.986 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1380 
    [ 1.250,  2.500) = 33780 
    [ 2.500,  3.750) = 271321 
    [ 3.750,  5.000) = 13567 
    [ 5.000,  6.250) = 878 
    [ 6.250,  7.500) = 240 
    [ 7.500,  8.750) = 58 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.539 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =      7.750 ms/op
     p(99.9900) =     16.482 ms/op
     p(99.9990) =     17.557 ms/op
     p(99.9999) =     17.662 ms/op
    p(100.0000) =     17.662 ms/op


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
# Warmup Iteration   1: 4.030 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.928 ±(99.9%) 0.005 ms/op
Iteration   1: 2.817 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.665 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.551 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  6.821 ms/op
                 existUser·p0.9999: 12.501 ms/op
                 existUser·p1.00:   12.730 ms/op

Iteration   2: 2.929 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.896 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   3.951 ms/op
                 existUser·p0.999:  5.172 ms/op
                 existUser·p0.9999: 14.191 ms/op
                 existUser·p1.00:   14.729 ms/op

Iteration   3: 2.888 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.682 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.047 ms/op
                 existUser·p0.999:  10.469 ms/op
                 existUser·p0.9999: 18.642 ms/op
                 existUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333936
  mean =      2.877 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3002 
    [ 1.250,  2.500) = 46101 
    [ 2.500,  3.750) = 276909 
    [ 3.750,  5.000) = 7047 
    [ 5.000,  6.250) = 427 
    [ 6.250,  7.500) = 222 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 56 

  Percentiles, ms/op:
      p(0.0000) =      0.665 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      3.371 ms/op
     p(95.0000) =      3.559 ms/op
     p(99.0000) =      4.129 ms/op
     p(99.9000) =      6.644 ms/op
     p(99.9900) =     18.350 ms/op
     p(99.9990) =     18.962 ms/op
     p(99.9999) =     19.038 ms/op
    p(100.0000) =     19.038 ms/op


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
# Warmup Iteration   1: 4.343 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.133 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.022 ±(99.9%) 0.006 ms/op
Iteration   1: 3.098 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.632 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.735 ms/op
                 getUser·p0.999:  10.036 ms/op
                 getUser·p0.9999: 13.768 ms/op
                 getUser·p1.00:   16.138 ms/op

Iteration   2: 2.997 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.314 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  8.170 ms/op
                 getUser·p0.9999: 16.225 ms/op
                 getUser·p1.00:   16.843 ms/op

Iteration   3: 3.001 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.712 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  7.305 ms/op
                 getUser·p0.9999: 17.598 ms/op
                 getUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316622
  mean =      3.031 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 656 
    [ 1.250,  2.500) = 25242 
    [ 2.500,  3.750) = 272533 
    [ 3.750,  5.000) = 16349 
    [ 5.000,  6.250) = 1006 
    [ 6.250,  7.500) = 339 
    [ 7.500,  8.750) = 125 
    [ 8.750, 10.000) = 107 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 38 
    [16.250, 17.500) = 41 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.314 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.620 ms/op
     p(99.9000) =      9.339 ms/op
     p(99.9900) =     16.843 ms/op
     p(99.9990) =     18.055 ms/op
     p(99.9999) =     18.383 ms/op
    p(100.0000) =     18.383 ms/op


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
# Warmup Iteration   1: 5.370 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.153 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.992 ±(99.9%) 0.010 ms/op
Iteration   1: 3.996 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.204 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  13.042 ms/op
                 listUser·p0.9999: 14.565 ms/op
                 listUser·p1.00:   15.172 ms/op

Iteration   2: 4.005 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.993 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  14.605 ms/op
                 listUser·p0.9999: 19.302 ms/op
                 listUser·p1.00:   19.759 ms/op

Iteration   3: 3.955 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.073 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   6.827 ms/op
                 listUser·p0.999:  16.385 ms/op
                 listUser·p0.9999: 23.194 ms/op
                 listUser·p1.00:   23.593 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240766
  mean =      3.985 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2448 
    [ 2.500,  5.000) = 217229 
    [ 5.000,  7.500) = 19716 
    [ 7.500, 10.000) = 870 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 203 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.993 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.866 ms/op
     p(95.0000) =      5.734 ms/op
     p(99.0000) =      7.012 ms/op
     p(99.9000) =     14.238 ms/op
     p(99.9900) =     21.526 ms/op
     p(99.9990) =     23.593 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.662 ± 0.718  ops/ms
ClientGrpc.existUser                       thrpt       3  11.433 ± 3.681  ops/ms
ClientGrpc.getUser                         thrpt       3  10.723 ± 1.952  ops/ms
ClientGrpc.listUser                        thrpt       3   8.204 ± 3.021  ops/ms
ClientGrpc.createUser                       avgt       3   2.960 ± 0.668   ms/op
ClientGrpc.existUser                        avgt       3   2.821 ± 1.147   ms/op
ClientGrpc.getUser                          avgt       3   3.024 ± 0.434   ms/op
ClientGrpc.listUser                         avgt       3   3.921 ± 0.218   ms/op
ClientGrpc.createUser                     sample  321509   2.986 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.539           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.966           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.523           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.727           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.571           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.750           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.482           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.662           ms/op
ClientGrpc.existUser                      sample  333936   2.877 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.665           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.875           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.371           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.559           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.129           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.644           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.350           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.038           ms/op
ClientGrpc.getUser                        sample  316622   3.031 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.314           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.998           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.580           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.793           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.620           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.339           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.843           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.383           ms/op
ClientGrpc.listUser                       sample  240766   3.985 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.993           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.834           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.866           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.734           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.012           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.238           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.526           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.593           ms/op
