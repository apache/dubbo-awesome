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
# Warmup Iteration   1: 4.580 ops/ms
# Warmup Iteration   2: 9.106 ops/ms
# Warmup Iteration   3: 10.241 ops/ms
Iteration   1: 10.369 ops/ms
Iteration   2: 10.862 ops/ms
Iteration   3: 10.442 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.558 ±(99.9%) 4.859 ops/ms [Average]
  (min, avg, max) = (10.369, 10.558, 10.862), stdev = 0.266
  CI (99.9%): [5.699, 15.416] (assumes normal distribution)


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
# Warmup Iteration   1: 7.904 ops/ms
# Warmup Iteration   2: 11.018 ops/ms
# Warmup Iteration   3: 10.881 ops/ms
Iteration   1: 11.113 ops/ms
Iteration   2: 11.135 ops/ms
Iteration   3: 10.959 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.069 ±(99.9%) 1.749 ops/ms [Average]
  (min, avg, max) = (10.959, 11.069, 11.135), stdev = 0.096
  CI (99.9%): [9.321, 12.818] (assumes normal distribution)


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
# Warmup Iteration   1: 7.275 ops/ms
# Warmup Iteration   2: 10.119 ops/ms
# Warmup Iteration   3: 10.307 ops/ms
Iteration   1: 10.421 ops/ms
Iteration   2: 10.518 ops/ms
Iteration   3: 10.470 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.470 ±(99.9%) 0.884 ops/ms [Average]
  (min, avg, max) = (10.421, 10.470, 10.518), stdev = 0.048
  CI (99.9%): [9.586, 11.353] (assumes normal distribution)


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
# Warmup Iteration   1: 6.393 ops/ms
# Warmup Iteration   2: 7.451 ops/ms
# Warmup Iteration   3: 7.943 ops/ms
Iteration   1: 8.072 ops/ms
Iteration   2: 8.110 ops/ms
Iteration   3: 7.957 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.046 ±(99.9%) 1.448 ops/ms [Average]
  (min, avg, max) = (7.957, 8.046, 8.110), stdev = 0.079
  CI (99.9%): [6.598, 9.494] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.249 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.169 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.004 ms/op
Iteration   1: 3.126 ±(99.9%) 0.002 ms/op
Iteration   2: 3.022 ±(99.9%) 0.004 ms/op
Iteration   3: 3.062 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.070 ±(99.9%) 0.959 ms/op [Average]
  (min, avg, max) = (3.022, 3.070, 3.126), stdev = 0.053
  CI (99.9%): [2.111, 4.029] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.467 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.138 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.154 ±(99.9%) 0.002 ms/op
Iteration   1: 3.014 ±(99.9%) 0.003 ms/op
Iteration   2: 2.974 ±(99.9%) 0.003 ms/op
Iteration   3: 3.052 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.013 ±(99.9%) 0.714 ms/op [Average]
  (min, avg, max) = (2.974, 3.013, 3.052), stdev = 0.039
  CI (99.9%): [2.299, 3.728] (assumes normal distribution)


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
# Warmup Iteration   1: 4.155 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.274 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.196 ±(99.9%) 0.002 ms/op
Iteration   1: 3.029 ±(99.9%) 0.003 ms/op
Iteration   2: 2.949 ±(99.9%) 0.003 ms/op
Iteration   3: 3.000 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.993 ±(99.9%) 0.735 ms/op [Average]
  (min, avg, max) = (2.949, 2.993, 3.029), stdev = 0.040
  CI (99.9%): [2.257, 3.728] (assumes normal distribution)


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
# Warmup Iteration   1: 5.257 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.062 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.033 ±(99.9%) 0.026 ms/op
Iteration   1: 3.969 ±(99.9%) 0.024 ms/op
Iteration   2: 3.949 ±(99.9%) 0.011 ms/op
Iteration   3: 3.979 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.965 ±(99.9%) 0.275 ms/op [Average]
  (min, avg, max) = (3.949, 3.965, 3.979), stdev = 0.015
  CI (99.9%): [3.691, 4.240] (assumes normal distribution)


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
# Warmup Iteration   1: 4.311 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.145 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.007 ms/op
Iteration   1: 3.004 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.881 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   4.669 ms/op
                 createUser·p0.999:  7.340 ms/op
                 createUser·p0.9999: 16.286 ms/op
                 createUser·p1.00:   16.466 ms/op

Iteration   2: 3.010 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.748 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  6.468 ms/op
                 createUser·p0.9999: 18.395 ms/op
                 createUser·p1.00:   18.743 ms/op

Iteration   3: 3.026 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.787 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.170 ms/op
                 createUser·p0.999:  10.572 ms/op
                 createUser·p0.9999: 16.634 ms/op
                 createUser·p1.00:   17.105 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318455
  mean =      3.014 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 712 
    [ 1.250,  2.500) = 28247 
    [ 2.500,  3.750) = 272765 
    [ 3.750,  5.000) = 15333 
    [ 5.000,  6.250) = 771 
    [ 6.250,  7.500) = 247 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 47 
    [16.250, 17.500) = 52 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      9.316 ms/op
     p(99.9900) =     16.908 ms/op
     p(99.9990) =     18.672 ms/op
     p(99.9999) =     18.743 ms/op
    p(100.0000) =     18.743 ms/op


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
# Warmup Iteration   1: 3.760 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.990 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.904 ±(99.9%) 0.005 ms/op
Iteration   1: 2.920 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.433 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.502 ms/op
                 existUser·p0.99:   3.985 ms/op
                 existUser·p0.999:  6.737 ms/op
                 existUser·p0.9999: 16.155 ms/op
                 existUser·p1.00:   16.400 ms/op

Iteration   2: 2.832 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.806 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.158 ms/op
                 existUser·p0.95:   3.273 ms/op
                 existUser·p0.99:   4.006 ms/op
                 existUser·p0.999:  6.725 ms/op
                 existUser·p0.9999: 18.486 ms/op
                 existUser·p1.00:   19.104 ms/op

Iteration   3: 2.879 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.649 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.207 ms/op
                 existUser·p0.95:   3.330 ms/op
                 existUser·p0.99:   3.969 ms/op
                 existUser·p0.999:  8.667 ms/op
                 existUser·p0.9999: 26.852 ms/op
                 existUser·p1.00:   27.296 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333780
  mean =      2.876 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36596 
    [ 2.500,  5.000) = 296320 
    [ 5.000,  7.500) = 568 
    [ 7.500, 10.000) = 86 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.433 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.269 ms/op
     p(95.0000) =      3.420 ms/op
     p(99.0000) =      3.990 ms/op
     p(99.9000) =      7.145 ms/op
     p(99.9900) =     19.104 ms/op
     p(99.9990) =     27.208 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


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
# Warmup Iteration   1: 4.155 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.180 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.006 ms/op
Iteration   1: 3.010 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.563 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.432 ms/op
                 getUser·p0.95:   3.658 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  7.491 ms/op
                 getUser·p0.9999: 16.292 ms/op
                 getUser·p1.00:   16.613 ms/op

Iteration   2: 3.072 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.680 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  7.717 ms/op
                 getUser·p0.9999: 17.779 ms/op
                 getUser·p1.00:   18.252 ms/op

Iteration   3: 3.009 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.910 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.674 ms/op
                 getUser·p0.99:   4.202 ms/op
                 getUser·p0.999:  5.923 ms/op
                 getUser·p0.9999: 19.333 ms/op
                 getUser·p1.00:   19.366 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316867
  mean =      3.030 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 482 
    [ 1.250,  2.500) = 14536 
    [ 2.500,  3.750) = 287915 
    [ 3.750,  5.000) = 12756 
    [ 5.000,  6.250) = 663 
    [ 6.250,  7.500) = 259 
    [ 7.500,  8.750) = 84 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 51 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.563 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      6.948 ms/op
     p(99.9900) =     18.207 ms/op
     p(99.9990) =     19.360 ms/op
     p(99.9999) =     19.366 ms/op
    p(100.0000) =     19.366 ms/op


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
# Warmup Iteration   1: 4.816 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.253 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.067 ±(99.9%) 0.012 ms/op
Iteration   1: 4.017 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.916 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  16.048 ms/op
                 listUser·p0.9999: 19.072 ms/op
                 listUser·p1.00:   19.399 ms/op

Iteration   2: 4.002 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.241 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.849 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  15.663 ms/op
                 listUser·p0.9999: 18.088 ms/op
                 listUser·p1.00:   19.792 ms/op

Iteration   3: 3.959 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.155 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  15.421 ms/op
                 listUser·p0.9999: 37.875 ms/op
                 listUser·p1.00:   38.339 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240554
  mean =      3.993 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3262 
    [ 2.500,  5.000) = 212126 
    [ 5.000,  7.500) = 23747 
    [ 7.500, 10.000) = 933 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 188 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.916 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      5.046 ms/op
     p(95.0000) =      5.759 ms/op
     p(99.0000) =      7.029 ms/op
     p(99.9000) =     15.499 ms/op
     p(99.9900) =     32.315 ms/op
     p(99.9990) =     38.220 ms/op
     p(99.9999) =     38.339 ms/op
    p(100.0000) =     38.339 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.558 ± 4.859  ops/ms
ClientGrpc.existUser                       thrpt       3  11.069 ± 1.749  ops/ms
ClientGrpc.getUser                         thrpt       3  10.470 ± 0.884  ops/ms
ClientGrpc.listUser                        thrpt       3   8.046 ± 1.448  ops/ms
ClientGrpc.createUser                       avgt       3   3.070 ± 0.959   ms/op
ClientGrpc.existUser                        avgt       3   3.013 ± 0.714   ms/op
ClientGrpc.getUser                          avgt       3   2.993 ± 0.735   ms/op
ClientGrpc.listUser                         avgt       3   3.965 ± 0.275   ms/op
ClientGrpc.createUser                     sample  318455   3.014 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.748           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.986           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.535           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.768           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.506           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.316           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.908           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.743           ms/op
ClientGrpc.existUser                      sample  333780   2.876 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.433           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.269           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.420           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           3.990           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.145           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.104           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.296           ms/op
ClientGrpc.getUser                        sample  316867   3.030 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.563           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.998           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.478           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.707           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.260           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.948           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.207           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.366           ms/op
ClientGrpc.listUser                       sample  240554   3.993 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.916           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.817           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.046           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.759           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.029           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.499           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.315           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          38.339           ms/op
