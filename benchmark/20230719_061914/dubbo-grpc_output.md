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
# Warmup Iteration   1: 3.807 ops/ms
# Warmup Iteration   2: 8.544 ops/ms
# Warmup Iteration   3: 9.636 ops/ms
Iteration   1: 10.300 ops/ms
Iteration   2: 10.083 ops/ms
Iteration   3: 10.273 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.219 ±(99.9%) 2.157 ops/ms [Average]
  (min, avg, max) = (10.083, 10.219, 10.300), stdev = 0.118
  CI (99.9%): [8.062, 12.376] (assumes normal distribution)


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
# Warmup Iteration   1: 6.777 ops/ms
# Warmup Iteration   2: 9.926 ops/ms
# Warmup Iteration   3: 11.011 ops/ms
Iteration   1: 10.663 ops/ms
Iteration   2: 10.642 ops/ms
Iteration   3: 10.695 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.667 ±(99.9%) 0.492 ops/ms [Average]
  (min, avg, max) = (10.642, 10.667, 10.695), stdev = 0.027
  CI (99.9%): [10.175, 11.159] (assumes normal distribution)


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
# Warmup Iteration   1: 6.150 ops/ms
# Warmup Iteration   2: 9.637 ops/ms
# Warmup Iteration   3: 10.091 ops/ms
Iteration   1: 10.006 ops/ms
Iteration   2: 10.072 ops/ms
Iteration   3: 10.356 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.145 ±(99.9%) 3.387 ops/ms [Average]
  (min, avg, max) = (10.006, 10.145, 10.356), stdev = 0.186
  CI (99.9%): [6.757, 13.532] (assumes normal distribution)


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
# Warmup Iteration   1: 4.963 ops/ms
# Warmup Iteration   2: 7.402 ops/ms
# Warmup Iteration   3: 7.795 ops/ms
Iteration   1: 7.991 ops/ms
Iteration   2: 7.767 ops/ms
Iteration   3: 7.858 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.872 ±(99.9%) 2.056 ops/ms [Average]
  (min, avg, max) = (7.767, 7.872, 7.991), stdev = 0.113
  CI (99.9%): [5.815, 9.928] (assumes normal distribution)


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
# Warmup Iteration   1: 4.634 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.386 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.153 ±(99.9%) 0.004 ms/op
Iteration   1: 3.141 ±(99.9%) 0.003 ms/op
Iteration   2: 3.142 ±(99.9%) 0.002 ms/op
Iteration   3: 3.104 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.129 ±(99.9%) 0.398 ms/op [Average]
  (min, avg, max) = (3.104, 3.129, 3.142), stdev = 0.022
  CI (99.9%): [2.731, 3.527] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.133 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.184 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.003 ms/op
Iteration   1: 3.030 ±(99.9%) 0.003 ms/op
Iteration   2: 3.001 ±(99.9%) 0.002 ms/op
Iteration   3: 2.989 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.006 ±(99.9%) 0.383 ms/op [Average]
  (min, avg, max) = (2.989, 3.006, 3.030), stdev = 0.021
  CI (99.9%): [2.623, 3.389] (assumes normal distribution)


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
# Warmup Iteration   1: 4.589 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.232 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.189 ±(99.9%) 0.002 ms/op
Iteration   1: 3.117 ±(99.9%) 0.003 ms/op
Iteration   2: 3.096 ±(99.9%) 0.003 ms/op
Iteration   3: 3.048 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.087 ±(99.9%) 0.643 ms/op [Average]
  (min, avg, max) = (3.048, 3.087, 3.117), stdev = 0.035
  CI (99.9%): [2.443, 3.730] (assumes normal distribution)


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
# Warmup Iteration   1: 5.552 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.458 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.073 ±(99.9%) 0.016 ms/op
Iteration   1: 4.044 ±(99.9%) 0.013 ms/op
Iteration   2: 4.109 ±(99.9%) 0.029 ms/op
Iteration   3: 4.087 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.080 ±(99.9%) 0.606 ms/op [Average]
  (min, avg, max) = (4.044, 4.080, 4.109), stdev = 0.033
  CI (99.9%): [3.474, 4.686] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.043 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.351 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.133 ±(99.9%) 0.007 ms/op
Iteration   1: 3.186 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.982 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   3.908 ms/op
                 createUser·p0.99:   4.612 ms/op
                 createUser·p0.999:  9.863 ms/op
                 createUser·p0.9999: 13.646 ms/op
                 createUser·p1.00:   13.992 ms/op

Iteration   2: 3.155 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.897 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   4.055 ms/op
                 createUser·p0.99:   5.120 ms/op
                 createUser·p0.999:  9.273 ms/op
                 createUser·p0.9999: 15.991 ms/op
                 createUser·p1.00:   16.351 ms/op

Iteration   3: 3.084 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.927 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.604 ms/op
                 createUser·p0.999:  9.182 ms/op
                 createUser·p0.9999: 24.072 ms/op
                 createUser·p1.00:   24.412 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305532
  mean =      3.141 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15992 
    [ 2.500,  5.000) = 287115 
    [ 5.000,  7.500) = 1793 
    [ 7.500, 10.000) = 373 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.897 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      4.817 ms/op
     p(99.9000) =      9.421 ms/op
     p(99.9900) =     23.524 ms/op
     p(99.9990) =     24.210 ms/op
     p(99.9999) =     24.412 ms/op
    p(100.0000) =     24.412 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.182 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.116 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.005 ms/op
Iteration   1: 3.006 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.752 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.381 ms/op
                 existUser·p0.999:  6.778 ms/op
                 existUser·p0.9999: 16.964 ms/op
                 existUser·p1.00:   17.367 ms/op

Iteration   2: 2.950 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.550 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   4.473 ms/op
                 existUser·p0.999:  8.922 ms/op
                 existUser·p0.9999: 14.584 ms/op
                 existUser·p1.00:   15.008 ms/op

Iteration   3: 2.956 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.740 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.514 ms/op
                 existUser·p0.99:   4.006 ms/op
                 existUser·p0.999:  5.972 ms/op
                 existUser·p0.9999: 15.824 ms/op
                 existUser·p1.00:   17.465 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323315
  mean =      2.970 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 950 
    [ 1.250,  2.500) = 27177 
    [ 2.500,  3.750) = 282875 
    [ 3.750,  5.000) = 11106 
    [ 5.000,  6.250) = 748 
    [ 6.250,  7.500) = 210 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 86 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 37 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.550 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.674 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      6.832 ms/op
     p(99.9900) =     16.335 ms/op
     p(99.9990) =     17.433 ms/op
     p(99.9999) =     17.465 ms/op
    p(100.0000) =     17.465 ms/op


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
# Warmup Iteration   1: 4.130 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.253 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.092 ±(99.9%) 0.006 ms/op
Iteration   1: 3.137 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.597 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   4.043 ms/op
                 getUser·p0.99:   5.087 ms/op
                 getUser·p0.999:  10.945 ms/op
                 getUser·p0.9999: 22.643 ms/op
                 getUser·p1.00:   23.233 ms/op

Iteration   2: 3.167 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.656 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   4.145 ms/op
                 getUser·p0.99:   5.366 ms/op
                 getUser·p0.999:  9.912 ms/op
                 getUser·p0.9999: 17.626 ms/op
                 getUser·p1.00:   17.957 ms/op

Iteration   3: 3.115 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.490 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   4.006 ms/op
                 getUser·p0.99:   4.899 ms/op
                 getUser·p0.999:  9.203 ms/op
                 getUser·p0.9999: 31.907 ms/op
                 getUser·p1.00:   32.244 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 305812
  mean =      3.140 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21434 
    [ 2.500,  5.000) = 280755 
    [ 5.000,  7.500) = 3099 
    [ 7.500, 10.000) = 221 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.490 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      4.067 ms/op
     p(99.0000) =      5.145 ms/op
     p(99.9000) =      9.965 ms/op
     p(99.9900) =     31.204 ms/op
     p(99.9990) =     32.113 ms/op
     p(99.9999) =     32.244 ms/op
    p(100.0000) =     32.244 ms/op


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
# Warmup Iteration   1: 6.065 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.460 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.304 ±(99.9%) 0.014 ms/op
Iteration   1: 4.057 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.929 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   6.021 ms/op
                 listUser·p0.99:   7.406 ms/op
                 listUser·p0.999:  16.772 ms/op
                 listUser·p0.9999: 21.729 ms/op
                 listUser·p1.00:   22.217 ms/op

Iteration   2: 4.153 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.016 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   5.300 ms/op
                 listUser·p0.95:   6.111 ms/op
                 listUser·p0.99:   7.726 ms/op
                 listUser·p0.999:  17.295 ms/op
                 listUser·p0.9999: 28.344 ms/op
                 listUser·p1.00:   31.031 ms/op

Iteration   3: 4.126 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.385 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   5.956 ms/op
                 listUser·p0.99:   7.496 ms/op
                 listUser·p0.999:  15.739 ms/op
                 listUser·p0.9999: 20.931 ms/op
                 listUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 233551
  mean =      4.112 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1550 
    [ 2.500,  5.000) = 203660 
    [ 5.000,  7.500) = 25924 
    [ 7.500, 10.000) = 1837 
    [10.000, 12.500) = 156 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.385 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      5.210 ms/op
     p(95.0000) =      6.021 ms/op
     p(99.0000) =      7.545 ms/op
     p(99.9000) =     16.857 ms/op
     p(99.9900) =     28.103 ms/op
     p(99.9990) =     30.649 ms/op
     p(99.9999) =     31.031 ms/op
    p(100.0000) =     31.031 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.219 ± 2.157  ops/ms
ClientGrpc.existUser                       thrpt       3  10.667 ± 0.492  ops/ms
ClientGrpc.getUser                         thrpt       3  10.145 ± 3.387  ops/ms
ClientGrpc.listUser                        thrpt       3   7.872 ± 2.056  ops/ms
ClientGrpc.createUser                       avgt       3   3.129 ± 0.398   ms/op
ClientGrpc.existUser                        avgt       3   3.006 ± 0.383   ms/op
ClientGrpc.getUser                          avgt       3   3.087 ± 0.643   ms/op
ClientGrpc.listUser                         avgt       3   4.080 ± 0.606   ms/op
ClientGrpc.createUser                     sample  305532   3.141 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.897           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.097           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.703           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.916           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.817           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.421           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.524           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.412           ms/op
ClientGrpc.existUser                      sample  323315   2.970 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.550           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.949           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.461           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.674           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.276           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.832           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.335           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.465           ms/op
ClientGrpc.getUser                        sample  305812   3.140 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.490           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.101           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.740           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.067           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.145           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.965           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          31.204           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          32.244           ms/op
ClientGrpc.listUser                       sample  233551   4.112 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.385           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.903           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.210           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.021           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.545           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.857           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.103           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.031           ms/op
