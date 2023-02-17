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
# Warmup Iteration   1: 4.849 ops/ms
# Warmup Iteration   2: 9.716 ops/ms
# Warmup Iteration   3: 10.770 ops/ms
Iteration   1: 10.611 ops/ms
Iteration   2: 10.434 ops/ms
Iteration   3: 10.376 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.474 ±(99.9%) 2.232 ops/ms [Average]
  (min, avg, max) = (10.376, 10.474, 10.611), stdev = 0.122
  CI (99.9%): [8.242, 12.706] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.627 ops/ms
# Warmup Iteration   2: 10.782 ops/ms
# Warmup Iteration   3: 10.893 ops/ms
Iteration   1: 10.868 ops/ms
Iteration   2: 10.806 ops/ms
Iteration   3: 10.745 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.806 ±(99.9%) 1.120 ops/ms [Average]
  (min, avg, max) = (10.745, 10.806, 10.868), stdev = 0.061
  CI (99.9%): [9.687, 11.926] (assumes normal distribution)


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
# Warmup Iteration   1: 7.605 ops/ms
# Warmup Iteration   2: 10.277 ops/ms
# Warmup Iteration   3: 10.772 ops/ms
Iteration   1: 10.293 ops/ms
Iteration   2: 10.195 ops/ms
Iteration   3: 10.526 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.338 ±(99.9%) 3.097 ops/ms [Average]
  (min, avg, max) = (10.195, 10.338, 10.526), stdev = 0.170
  CI (99.9%): [7.241, 13.436] (assumes normal distribution)


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
# Warmup Iteration   1: 6.157 ops/ms
# Warmup Iteration   2: 7.759 ops/ms
# Warmup Iteration   3: 8.101 ops/ms
Iteration   1: 7.896 ops/ms
Iteration   2: 8.124 ops/ms
Iteration   3: 8.255 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.092 ±(99.9%) 3.314 ops/ms [Average]
  (min, avg, max) = (7.896, 8.092, 8.255), stdev = 0.182
  CI (99.9%): [4.777, 11.406] (assumes normal distribution)


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
# Warmup Iteration   1: 3.877 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.058 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.981 ±(99.9%) 0.003 ms/op
Iteration   1: 3.136 ±(99.9%) 0.002 ms/op
Iteration   2: 3.133 ±(99.9%) 0.002 ms/op
Iteration   3: 3.104 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.124 ±(99.9%) 0.323 ms/op [Average]
  (min, avg, max) = (3.104, 3.124, 3.136), stdev = 0.018
  CI (99.9%): [2.801, 3.447] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.639 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.923 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.968 ±(99.9%) 0.008 ms/op
Iteration   1: 2.991 ±(99.9%) 0.002 ms/op
Iteration   2: 2.938 ±(99.9%) 0.002 ms/op
Iteration   3: 2.925 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.952 ±(99.9%) 0.632 ms/op [Average]
  (min, avg, max) = (2.925, 2.952, 2.991), stdev = 0.035
  CI (99.9%): [2.319, 3.584] (assumes normal distribution)


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
# Warmup Iteration   1: 3.862 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.039 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.070 ±(99.9%) 0.002 ms/op
Iteration   1: 3.090 ±(99.9%) 0.002 ms/op
Iteration   2: 3.016 ±(99.9%) 0.004 ms/op
Iteration   3: 3.013 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.040 ±(99.9%) 0.792 ms/op [Average]
  (min, avg, max) = (3.013, 3.040, 3.090), stdev = 0.043
  CI (99.9%): [2.247, 3.832] (assumes normal distribution)


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
# Warmup Iteration   1: 4.448 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.105 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.070 ±(99.9%) 0.011 ms/op
Iteration   1: 3.997 ±(99.9%) 0.031 ms/op
Iteration   2: 3.916 ±(99.9%) 0.034 ms/op
Iteration   3: 3.928 ±(99.9%) 0.052 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.947 ±(99.9%) 0.796 ms/op [Average]
  (min, avg, max) = (3.916, 3.947, 3.997), stdev = 0.044
  CI (99.9%): [3.151, 4.743] (assumes normal distribution)


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
# Warmup Iteration   1: 3.937 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.213 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.118 ±(99.9%) 0.007 ms/op
Iteration   1: 3.135 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.831 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.785 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  9.387 ms/op
                 createUser·p0.9999: 16.446 ms/op
                 createUser·p1.00:   16.876 ms/op

Iteration   2: 3.010 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.452 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  9.286 ms/op
                 createUser·p0.9999: 15.348 ms/op
                 createUser·p1.00:   16.007 ms/op

Iteration   3: 3.047 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.551 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.876 ms/op
                 createUser·p0.99:   4.227 ms/op
                 createUser·p0.999:  7.332 ms/op
                 createUser·p0.9999: 19.857 ms/op
                 createUser·p1.00:   20.054 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313211
  mean =      3.063 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30073 
    [ 2.500,  5.000) = 281849 
    [ 5.000,  7.500) = 920 
    [ 7.500, 10.000) = 102 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.452 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      3.899 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      8.582 ms/op
     p(99.9900) =     17.215 ms/op
     p(99.9990) =     19.890 ms/op
     p(99.9999) =     20.054 ms/op
    p(100.0000) =     20.054 ms/op


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
# Warmup Iteration   1: 3.857 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.074 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.007 ms/op
Iteration   1: 2.918 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.692 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  7.152 ms/op
                 existUser·p0.9999: 11.699 ms/op
                 existUser·p1.00:   12.141 ms/op

Iteration   2: 2.897 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.598 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   4.048 ms/op
                 existUser·p0.999:  6.504 ms/op
                 existUser·p0.9999: 12.533 ms/op
                 existUser·p1.00:   12.796 ms/op

Iteration   3: 2.984 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.578 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  6.159 ms/op
                 existUser·p0.9999: 20.677 ms/op
                 existUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327168
  mean =      2.933 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 56049 
    [ 2.500,  5.000) = 270315 
    [ 5.000,  7.500) = 538 
    [ 7.500, 10.000) = 74 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.578 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      6.798 ms/op
     p(99.9900) =     15.755 ms/op
     p(99.9990) =     20.742 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


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
# Warmup Iteration   1: 3.976 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.093 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.006 ms/op
Iteration   1: 3.043 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.659 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   4.149 ms/op
                 getUser·p0.999:  6.724 ms/op
                 getUser·p0.9999: 23.806 ms/op
                 getUser·p1.00:   24.150 ms/op

Iteration   2: 2.982 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.315 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.396 ms/op
                 getUser·p0.95:   3.592 ms/op
                 getUser·p0.99:   4.121 ms/op
                 getUser·p0.999:  6.096 ms/op
                 getUser·p0.9999: 17.933 ms/op
                 getUser·p1.00:   18.153 ms/op

Iteration   3: 3.080 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.680 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.903 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  7.194 ms/op
                 getUser·p0.9999: 16.027 ms/op
                 getUser·p1.00:   17.236 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316342
  mean =      3.035 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23689 
    [ 2.500,  5.000) = 291838 
    [ 5.000,  7.500) = 592 
    [ 7.500, 10.000) = 59 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.315 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      6.633 ms/op
     p(99.9900) =     23.328 ms/op
     p(99.9990) =     24.068 ms/op
     p(99.9999) =     24.150 ms/op
    p(100.0000) =     24.150 ms/op


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
# Warmup Iteration   1: 4.680 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.083 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.067 ±(99.9%) 0.012 ms/op
Iteration   1: 4.067 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.835 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   5.472 ms/op
                 listUser·p0.95:   6.038 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  17.859 ms/op
                 listUser·p0.9999: 22.053 ms/op
                 listUser·p1.00:   22.348 ms/op

Iteration   2: 3.930 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.763 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  16.509 ms/op
                 listUser·p0.9999: 22.007 ms/op
                 listUser·p1.00:   23.069 ms/op

Iteration   3: 4.076 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.614 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  14.696 ms/op
                 listUser·p0.9999: 21.603 ms/op
                 listUser·p1.00:   22.807 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238568
  mean =      4.023 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5116 
    [ 2.500,  5.000) = 201934 
    [ 5.000,  7.500) = 30228 
    [ 7.500, 10.000) = 845 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.614 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      5.226 ms/op
     p(95.0000) =      5.800 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     16.646 ms/op
     p(99.9900) =     21.856 ms/op
     p(99.9990) =     22.968 ms/op
     p(99.9999) =     23.069 ms/op
    p(100.0000) =     23.069 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.474 ± 2.232  ops/ms
ClientGrpc.existUser                       thrpt       3  10.806 ± 1.120  ops/ms
ClientGrpc.getUser                         thrpt       3  10.338 ± 3.097  ops/ms
ClientGrpc.listUser                        thrpt       3   8.092 ± 3.314  ops/ms
ClientGrpc.createUser                       avgt       3   3.124 ± 0.323   ms/op
ClientGrpc.existUser                        avgt       3   2.952 ± 0.632   ms/op
ClientGrpc.getUser                          avgt       3   3.040 ± 0.792   ms/op
ClientGrpc.listUser                         avgt       3   3.947 ± 0.796   ms/op
ClientGrpc.createUser                     sample  313211   3.063 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.452           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.047           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.699           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.899           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.268           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.582           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.215           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.054           ms/op
ClientGrpc.existUser                      sample  327168   2.933 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.578           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.916           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.572           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.768           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.798           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.755           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.775           ms/op
ClientGrpc.getUser                        sample  316342   3.035 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.315           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.031           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.576           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.801           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.202           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.633           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.328           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.150           ms/op
ClientGrpc.listUser                       sample  238568   4.023 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.614           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.834           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.226           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.800           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.930           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.646           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.856           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.069           ms/op
