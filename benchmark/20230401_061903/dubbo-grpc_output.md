# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.465 ops/ms
# Warmup Iteration   2: 9.261 ops/ms
# Warmup Iteration   3: 10.329 ops/ms
Iteration   1: 10.482 ops/ms
Iteration   2: 10.613 ops/ms
Iteration   3: 10.669 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.588 ±(99.9%) 1.751 ops/ms [Average]
  (min, avg, max) = (10.482, 10.588, 10.669), stdev = 0.096
  CI (99.9%): [8.837, 12.339] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.876 ops/ms
# Warmup Iteration   2: 10.788 ops/ms
# Warmup Iteration   3: 11.164 ops/ms
Iteration   1: 10.973 ops/ms
Iteration   2: 11.017 ops/ms
Iteration   3: 11.086 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.025 ±(99.9%) 1.031 ops/ms [Average]
  (min, avg, max) = (10.973, 11.025, 11.086), stdev = 0.057
  CI (99.9%): [9.994, 12.057] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.437 ops/ms
# Warmup Iteration   2: 10.402 ops/ms
# Warmup Iteration   3: 10.665 ops/ms
Iteration   1: 10.725 ops/ms
Iteration   2: 10.548 ops/ms
Iteration   3: 10.459 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.577 ±(99.9%) 2.470 ops/ms [Average]
  (min, avg, max) = (10.459, 10.577, 10.725), stdev = 0.135
  CI (99.9%): [8.107, 13.048] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.677 ops/ms
# Warmup Iteration   2: 8.158 ops/ms
# Warmup Iteration   3: 8.239 ops/ms
Iteration   1: 8.239 ops/ms
Iteration   2: 8.255 ops/ms
Iteration   3: 8.220 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.238 ±(99.9%) 0.318 ops/ms [Average]
  (min, avg, max) = (8.220, 8.238, 8.255), stdev = 0.017
  CI (99.9%): [7.920, 8.556] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.133 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.155 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.003 ms/op
Iteration   1: 3.020 ±(99.9%) 0.011 ms/op
Iteration   2: 3.041 ±(99.9%) 0.002 ms/op
Iteration   3: 3.024 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.028 ±(99.9%) 0.199 ms/op [Average]
  (min, avg, max) = (3.020, 3.028, 3.041), stdev = 0.011
  CI (99.9%): [2.829, 3.227] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.631 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.984 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.703 ±(99.9%) 0.008 ms/op
Iteration   1: 2.871 ±(99.9%) 0.003 ms/op
Iteration   2: 2.882 ±(99.9%) 0.003 ms/op
Iteration   3: 2.849 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.867 ±(99.9%) 0.311 ms/op [Average]
  (min, avg, max) = (2.849, 2.867, 2.882), stdev = 0.017
  CI (99.9%): [2.556, 3.179] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.932 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.139 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.002 ms/op
Iteration   1: 3.017 ±(99.9%) 0.003 ms/op
Iteration   2: 3.026 ±(99.9%) 0.006 ms/op
Iteration   3: 3.016 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.020 ±(99.9%) 0.101 ms/op [Average]
  (min, avg, max) = (3.016, 3.020, 3.026), stdev = 0.006
  CI (99.9%): [2.918, 3.121] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.817 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.929 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.866 ±(99.9%) 0.013 ms/op
Iteration   1: 3.880 ±(99.9%) 0.009 ms/op
Iteration   2: 3.902 ±(99.9%) 0.009 ms/op
Iteration   3: 3.921 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.901 ±(99.9%) 0.371 ms/op [Average]
  (min, avg, max) = (3.880, 3.901, 3.921), stdev = 0.020
  CI (99.9%): [3.530, 4.271] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.078 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.128 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.008 ms/op
Iteration   1: 3.021 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.691 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  7.136 ms/op
                 createUser·p0.9999: 21.168 ms/op
                 createUser·p1.00:   21.529 ms/op

Iteration   2: 3.006 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.627 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  7.364 ms/op
                 createUser·p0.9999: 24.326 ms/op
                 createUser·p1.00:   24.773 ms/op

Iteration   3: 3.010 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.219 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.620 ms/op
                 createUser·p0.999:  9.626 ms/op
                 createUser·p0.9999: 19.717 ms/op
                 createUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318809
  mean =      3.013 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25138 
    [ 2.500,  5.000) = 292077 
    [ 5.000,  7.500) = 1244 
    [ 7.500, 10.000) = 93 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.219 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =      7.984 ms/op
     p(99.9900) =     22.941 ms/op
     p(99.9990) =     24.629 ms/op
     p(99.9999) =     24.773 ms/op
    p(100.0000) =     24.773 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.735 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.968 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.905 ±(99.9%) 0.005 ms/op
Iteration   1: 2.910 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.578 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.502 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  5.900 ms/op
                 existUser·p0.9999: 21.299 ms/op
                 existUser·p1.00:   21.529 ms/op

Iteration   2: 2.898 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.672 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.506 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  9.819 ms/op
                 existUser·p0.9999: 13.795 ms/op
                 existUser·p1.00:   14.205 ms/op

Iteration   3: 2.876 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.542 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.219 ms/op
                 existUser·p0.95:   3.342 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  5.720 ms/op
                 existUser·p0.9999: 14.825 ms/op
                 existUser·p1.00:   15.286 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331662
  mean =      2.895 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29578 
    [ 2.500,  5.000) = 301354 
    [ 5.000,  7.500) = 455 
    [ 7.500, 10.000) = 47 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 128 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.542 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.273 ms/op
     p(95.0000) =      3.465 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      6.150 ms/op
     p(99.9900) =     15.286 ms/op
     p(99.9990) =     21.453 ms/op
     p(99.9999) =     21.529 ms/op
    p(100.0000) =     21.529 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.031 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.107 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.006 ms/op
Iteration   1: 2.987 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.234 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.396 ms/op
                 getUser·p0.95:   3.600 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  8.165 ms/op
                 getUser·p0.9999: 12.101 ms/op
                 getUser·p1.00:   13.517 ms/op

Iteration   2: 3.053 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.262 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.654 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  7.684 ms/op
                 getUser·p0.9999: 13.017 ms/op
                 getUser·p1.00:   13.533 ms/op

Iteration   3: 3.038 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.738 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  6.085 ms/op
                 getUser·p0.9999: 17.186 ms/op
                 getUser·p1.00:   17.564 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317277
  mean =      3.026 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1555 
    [ 1.250,  2.500) = 20021 
    [ 2.500,  3.750) = 282005 
    [ 3.750,  5.000) = 12523 
    [ 5.000,  6.250) = 599 
    [ 6.250,  7.500) = 265 
    [ 7.500,  8.750) = 98 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.234 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      7.471 ms/op
     p(99.9900) =     15.021 ms/op
     p(99.9990) =     17.334 ms/op
     p(99.9999) =     17.564 ms/op
    p(100.0000) =     17.564 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.050 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.995 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.902 ±(99.9%) 0.010 ms/op
Iteration   1: 3.906 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.883 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   6.611 ms/op
                 listUser·p0.999:  12.435 ms/op
                 listUser·p0.9999: 15.706 ms/op
                 listUser·p1.00:   16.302 ms/op

Iteration   2: 3.924 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.192 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  13.983 ms/op
                 listUser·p0.9999: 20.639 ms/op
                 listUser·p1.00:   20.840 ms/op

Iteration   3: 3.929 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.300 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   6.728 ms/op
                 listUser·p0.999:  16.634 ms/op
                 listUser·p0.9999: 21.098 ms/op
                 listUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244767
  mean =      3.920 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6225 
    [ 2.500,  5.000) = 215184 
    [ 5.000,  7.500) = 22345 
    [ 7.500, 10.000) = 623 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 129 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.300 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.956 ms/op
     p(95.0000) =      5.718 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     13.861 ms/op
     p(99.9900) =     20.564 ms/op
     p(99.9990) =     21.622 ms/op
     p(99.9999) =     21.758 ms/op
    p(100.0000) =     21.758 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.588 ± 1.751  ops/ms
ClientGrpc.existUser                       thrpt       3  11.025 ± 1.031  ops/ms
ClientGrpc.getUser                         thrpt       3  10.577 ± 2.470  ops/ms
ClientGrpc.listUser                        thrpt       3   8.238 ± 0.318  ops/ms
ClientGrpc.createUser                       avgt       3   3.028 ± 0.199   ms/op
ClientGrpc.existUser                        avgt       3   2.867 ± 0.311   ms/op
ClientGrpc.getUser                          avgt       3   3.020 ± 0.101   ms/op
ClientGrpc.listUser                         avgt       3   3.901 ± 0.371   ms/op
ClientGrpc.createUser                     sample  318809   3.013 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.219           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.006           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.518           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.764           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.555           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.984           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.941           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.773           ms/op
ClientGrpc.existUser                      sample  331662   2.895 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.542           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.904           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.273           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.465           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.350           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.150           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.286           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.529           ms/op
ClientGrpc.getUser                        sample  317277   3.026 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.234           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.027           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.502           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.703           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.383           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.471           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.021           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.564           ms/op
ClientGrpc.listUser                       sample  244767   3.920 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.300           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.772           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.956           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.718           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.668           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.861           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.564           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.758           ms/op
