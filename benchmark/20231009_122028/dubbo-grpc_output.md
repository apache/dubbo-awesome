# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.135 ops/ms
# Warmup Iteration   2: 8.337 ops/ms
# Warmup Iteration   3: 9.408 ops/ms
Iteration   1: 9.869 ops/ms
Iteration   2: 9.960 ops/ms
Iteration   3: 10.039 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.956 ±(99.9%) 1.555 ops/ms [Average]
  (min, avg, max) = (9.869, 9.956, 10.039), stdev = 0.085
  CI (99.9%): [8.401, 11.511] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 6.875 ops/ms
# Warmup Iteration   2: 9.909 ops/ms
# Warmup Iteration   3: 10.379 ops/ms
Iteration   1: 10.285 ops/ms
Iteration   2: 10.184 ops/ms
Iteration   3: 10.427 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.299 ±(99.9%) 2.219 ops/ms [Average]
  (min, avg, max) = (10.184, 10.299, 10.427), stdev = 0.122
  CI (99.9%): [8.080, 12.518] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.147 ops/ms
# Warmup Iteration   2: 9.246 ops/ms
# Warmup Iteration   3: 9.780 ops/ms
Iteration   1: 9.842 ops/ms
Iteration   2: 9.921 ops/ms
Iteration   3: 9.841 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.868 ±(99.9%) 0.840 ops/ms [Average]
  (min, avg, max) = (9.841, 9.868, 9.921), stdev = 0.046
  CI (99.9%): [9.028, 10.708] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 4.912 ops/ms
# Warmup Iteration   2: 7.482 ops/ms
# Warmup Iteration   3: 7.584 ops/ms
Iteration   1: 7.635 ops/ms
Iteration   2: 7.805 ops/ms
Iteration   3: 8.014 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.818 ±(99.9%) 3.464 ops/ms [Average]
  (min, avg, max) = (7.635, 7.818, 8.014), stdev = 0.190
  CI (99.9%): [4.354, 11.283] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.680 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.315 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.158 ±(99.9%) 0.003 ms/op
Iteration   1: 3.169 ±(99.9%) 0.004 ms/op
Iteration   2: 3.230 ±(99.9%) 0.007 ms/op
Iteration   3: 3.148 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.182 ±(99.9%) 0.770 ms/op [Average]
  (min, avg, max) = (3.148, 3.182, 3.230), stdev = 0.042
  CI (99.9%): [2.412, 3.953] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.089 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.106 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.002 ms/op
Iteration   1: 3.089 ±(99.9%) 0.005 ms/op
Iteration   2: 3.023 ±(99.9%) 0.003 ms/op
Iteration   3: 3.054 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.055 ±(99.9%) 0.602 ms/op [Average]
  (min, avg, max) = (3.023, 3.055, 3.089), stdev = 0.033
  CI (99.9%): [2.453, 3.657] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.522 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.228 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.177 ±(99.9%) 0.004 ms/op
Iteration   1: 3.204 ±(99.9%) 0.003 ms/op
Iteration   2: 3.179 ±(99.9%) 0.003 ms/op
Iteration   3: 3.127 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.170 ±(99.9%) 0.716 ms/op [Average]
  (min, avg, max) = (3.127, 3.170, 3.204), stdev = 0.039
  CI (99.9%): [2.454, 3.887] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.324 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.259 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.004 ±(99.9%) 0.012 ms/op
Iteration   1: 4.032 ±(99.9%) 0.014 ms/op
Iteration   2: 3.992 ±(99.9%) 0.011 ms/op
Iteration   3: 3.982 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.002 ±(99.9%) 0.484 ms/op [Average]
  (min, avg, max) = (3.982, 4.002, 4.032), stdev = 0.027
  CI (99.9%): [3.518, 4.487] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.610 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.377 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.186 ±(99.9%) 0.007 ms/op
Iteration   1: 3.200 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.995 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   4.596 ms/op
                 createUser·p0.999:  8.632 ms/op
                 createUser·p0.9999: 15.843 ms/op
                 createUser·p1.00:   16.515 ms/op

Iteration   2: 3.151 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.761 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.932 ms/op
                 createUser·p0.999:  9.765 ms/op
                 createUser·p0.9999: 17.001 ms/op
                 createUser·p1.00:   18.383 ms/op

Iteration   3: 3.155 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.680 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   4.964 ms/op
                 createUser·p0.999:  13.451 ms/op
                 createUser·p0.9999: 28.302 ms/op
                 createUser·p1.00:   28.901 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 303180
  mean =      3.168 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11739 
    [ 2.500,  5.000) = 288864 
    [ 5.000,  7.500) = 2111 
    [ 7.500, 10.000) = 176 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.680 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      4.866 ms/op
     p(99.9000) =      9.798 ms/op
     p(99.9900) =     20.906 ms/op
     p(99.9990) =     28.735 ms/op
     p(99.9999) =     28.901 ms/op
    p(100.0000) =     28.901 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.445 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.194 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.108 ±(99.9%) 0.006 ms/op
Iteration   1: 3.057 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.887 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   4.251 ms/op
                 existUser·p0.999:  8.324 ms/op
                 existUser·p0.9999: 11.878 ms/op
                 existUser·p1.00:   15.073 ms/op

Iteration   2: 3.098 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.578 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   3.928 ms/op
                 existUser·p0.99:   4.760 ms/op
                 existUser·p0.999:  9.011 ms/op
                 existUser·p0.9999: 17.717 ms/op
                 existUser·p1.00:   19.726 ms/op

Iteration   3: 3.035 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.575 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  10.404 ms/op
                 existUser·p0.9999: 17.644 ms/op
                 existUser·p1.00:   17.793 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 313324
  mean =      3.063 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 902 
    [ 1.250,  2.500) = 17381 
    [ 2.500,  3.750) = 276550 
    [ 3.750,  5.000) = 16650 
    [ 5.000,  6.250) = 860 
    [ 6.250,  7.500) = 434 
    [ 7.500,  8.750) = 236 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 90 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.575 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      8.744 ms/op
     p(99.9900) =     17.028 ms/op
     p(99.9990) =     18.018 ms/op
     p(99.9999) =     19.726 ms/op
    p(100.0000) =     19.726 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.336 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.327 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.231 ±(99.9%) 0.006 ms/op
Iteration   1: 3.235 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.881 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   3.994 ms/op
                 getUser·p0.99:   5.030 ms/op
                 getUser·p0.999:  11.994 ms/op
                 getUser·p0.9999: 19.005 ms/op
                 getUser·p1.00:   19.169 ms/op

Iteration   2: 3.217 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.895 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.076 ms/op
                 getUser·p0.99:   4.768 ms/op
                 getUser·p0.999:  10.070 ms/op
                 getUser·p0.9999: 19.015 ms/op
                 getUser·p1.00:   19.366 ms/op

Iteration   3: 3.188 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.772 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   4.858 ms/op
                 getUser·p0.999:  10.496 ms/op
                 getUser·p0.9999: 25.133 ms/op
                 getUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 298751
  mean =      3.213 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8859 
    [ 2.500,  5.000) = 287260 
    [ 5.000,  7.500) = 1845 
    [ 7.500, 10.000) = 427 
    [10.000, 12.500) = 138 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.772 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      4.866 ms/op
     p(99.9000) =     10.506 ms/op
     p(99.9900) =     19.169 ms/op
     p(99.9990) =     25.756 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.697 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.231 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.062 ±(99.9%) 0.013 ms/op
Iteration   1: 4.086 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.683 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   6.078 ms/op
                 listUser·p0.99:   7.476 ms/op
                 listUser·p0.999:  15.213 ms/op
                 listUser·p0.9999: 20.551 ms/op
                 listUser·p1.00:   26.837 ms/op

Iteration   2: 4.019 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.894 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   5.218 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  15.553 ms/op
                 listUser·p0.9999: 27.871 ms/op
                 listUser·p1.00:   29.327 ms/op

Iteration   3: 4.034 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.282 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   7.283 ms/op
                 listUser·p0.999:  15.506 ms/op
                 listUser·p0.9999: 18.876 ms/op
                 listUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237254
  mean =      4.046 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2756 
    [ 2.500,  5.000) = 215296 
    [ 5.000,  7.500) = 17486 
    [ 7.500, 10.000) = 1033 
    [10.000, 12.500) = 196 
    [12.500, 15.000) = 199 
    [15.000, 17.500) = 199 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.894 ms/op
     p(50.0000) =      3.924 ms/op
     p(90.0000) =      4.735 ms/op
     p(95.0000) =      5.751 ms/op
     p(99.0000) =      7.143 ms/op
     p(99.9000) =     15.397 ms/op
     p(99.9900) =     25.643 ms/op
     p(99.9990) =     29.295 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.956 ± 1.555  ops/ms
ClientGrpc.existUser                       thrpt       3  10.299 ± 2.219  ops/ms
ClientGrpc.getUser                         thrpt       3   9.868 ± 0.840  ops/ms
ClientGrpc.listUser                        thrpt       3   7.818 ± 3.464  ops/ms
ClientGrpc.createUser                       avgt       3   3.182 ± 0.770   ms/op
ClientGrpc.existUser                        avgt       3   3.055 ± 0.602   ms/op
ClientGrpc.getUser                          avgt       3   3.170 ± 0.716   ms/op
ClientGrpc.listUser                         avgt       3   4.002 ± 0.484   ms/op
ClientGrpc.createUser                     sample  303180   3.168 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.680           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.125           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.715           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.936           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.866           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.798           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.906           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.901           ms/op
ClientGrpc.existUser                      sample  313324   3.063 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.575           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.023           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.600           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.793           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.440           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.744           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.028           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.726           ms/op
ClientGrpc.getUser                        sample  298751   3.213 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.772           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.150           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.801           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.014           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.866           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.506           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.169           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.919           ms/op
ClientGrpc.listUser                       sample  237254   4.046 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.894           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.924           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.735           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.751           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.143           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.397           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.643           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.327           ms/op
