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
# Warmup Iteration   1: 4.847 ops/ms
# Warmup Iteration   2: 9.148 ops/ms
# Warmup Iteration   3: 9.840 ops/ms
Iteration   1: 9.931 ops/ms
Iteration   2: 10.237 ops/ms
Iteration   3: 10.289 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.153 ±(99.9%) 3.526 ops/ms [Average]
  (min, avg, max) = (9.931, 10.153, 10.289), stdev = 0.193
  CI (99.9%): [6.627, 13.678] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.803 ops/ms
# Warmup Iteration   2: 10.224 ops/ms
# Warmup Iteration   3: 10.500 ops/ms
Iteration   1: 10.679 ops/ms
Iteration   2: 10.656 ops/ms
Iteration   3: 10.535 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.624 ±(99.9%) 1.409 ops/ms [Average]
  (min, avg, max) = (10.535, 10.624, 10.679), stdev = 0.077
  CI (99.9%): [9.215, 12.032] (assumes normal distribution)


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
# Warmup Iteration   1: 6.878 ops/ms
# Warmup Iteration   2: 10.033 ops/ms
# Warmup Iteration   3: 10.119 ops/ms
Iteration   1: 10.191 ops/ms
Iteration   2: 10.259 ops/ms
Iteration   3: 10.329 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.260 ±(99.9%) 1.262 ops/ms [Average]
  (min, avg, max) = (10.191, 10.260, 10.329), stdev = 0.069
  CI (99.9%): [8.998, 11.522] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.053 ops/ms
# Warmup Iteration   2: 8.252 ops/ms
# Warmup Iteration   3: 8.263 ops/ms
Iteration   1: 8.268 ops/ms
Iteration   2: 8.386 ops/ms
Iteration   3: 8.288 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.314 ±(99.9%) 1.155 ops/ms [Average]
  (min, avg, max) = (8.268, 8.314, 8.386), stdev = 0.063
  CI (99.9%): [7.159, 9.469] (assumes normal distribution)


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
# Warmup Iteration   1: 3.956 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.247 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.151 ±(99.9%) 0.006 ms/op
Iteration   1: 3.113 ±(99.9%) 0.002 ms/op
Iteration   2: 3.139 ±(99.9%) 0.002 ms/op
Iteration   3: 3.135 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.129 ±(99.9%) 0.254 ms/op [Average]
  (min, avg, max) = (3.113, 3.129, 3.139), stdev = 0.014
  CI (99.9%): [2.875, 3.382] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.914 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.106 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.002 ms/op
Iteration   1: 2.986 ±(99.9%) 0.002 ms/op
Iteration   2: 2.995 ±(99.9%) 0.002 ms/op
Iteration   3: 2.971 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.984 ±(99.9%) 0.219 ms/op [Average]
  (min, avg, max) = (2.971, 2.984, 2.995), stdev = 0.012
  CI (99.9%): [2.765, 3.203] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.122 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.227 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.116 ±(99.9%) 0.003 ms/op
Iteration   1: 3.097 ±(99.9%) 0.002 ms/op
Iteration   2: 3.200 ±(99.9%) 0.003 ms/op
Iteration   3: 3.102 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.133 ±(99.9%) 1.056 ms/op [Average]
  (min, avg, max) = (3.097, 3.133, 3.200), stdev = 0.058
  CI (99.9%): [2.077, 4.189] (assumes normal distribution)


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
# Warmup Iteration   1: 5.210 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.991 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 3.899 ±(99.9%) 0.022 ms/op
Iteration   1: 3.861 ±(99.9%) 0.018 ms/op
Iteration   2: 3.850 ±(99.9%) 0.038 ms/op
Iteration   3: 3.859 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.857 ±(99.9%) 0.112 ms/op [Average]
  (min, avg, max) = (3.850, 3.857, 3.861), stdev = 0.006
  CI (99.9%): [3.744, 3.969] (assumes normal distribution)


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
# Warmup Iteration   1: 3.856 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.336 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.193 ±(99.9%) 0.006 ms/op
Iteration   1: 3.163 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.932 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  6.570 ms/op
                 createUser·p0.9999: 12.658 ms/op
                 createUser·p1.00:   13.107 ms/op

Iteration   2: 3.168 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.799 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  8.339 ms/op
                 createUser·p0.9999: 13.235 ms/op
                 createUser·p1.00:   13.566 ms/op

Iteration   3: 3.173 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.743 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   3.944 ms/op
                 createUser·p0.99:   4.612 ms/op
                 createUser·p0.999:  11.216 ms/op
                 createUser·p0.9999: 14.549 ms/op
                 createUser·p1.00:   16.204 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 302966
  mean =      3.168 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 358 
    [ 1.250,  2.500) = 6086 
    [ 2.500,  3.750) = 270549 
    [ 3.750,  5.000) = 24291 
    [ 5.000,  6.250) = 837 
    [ 6.250,  7.500) = 355 
    [ 7.500,  8.750) = 133 
    [ 8.750, 10.000) = 82 
    [10.000, 11.250) = 61 
    [11.250, 12.500) = 93 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.743 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      4.402 ms/op
     p(99.9000) =      9.585 ms/op
     p(99.9900) =     14.359 ms/op
     p(99.9990) =     14.907 ms/op
     p(99.9999) =     16.204 ms/op
    p(100.0000) =     16.204 ms/op


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
# Warmup Iteration   1: 3.856 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.062 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.005 ms/op
Iteration   1: 3.052 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.810 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.768 ms/op
                 existUser·p0.99:   4.137 ms/op
                 existUser·p0.999:  6.826 ms/op
                 existUser·p0.9999: 11.395 ms/op
                 existUser·p1.00:   11.682 ms/op

Iteration   2: 3.051 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.465 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  12.288 ms/op
                 existUser·p0.9999: 17.924 ms/op
                 existUser·p1.00:   19.694 ms/op

Iteration   3: 2.987 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.575 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   4.751 ms/op
                 existUser·p0.999:  8.864 ms/op
                 existUser·p0.9999: 14.476 ms/op
                 existUser·p1.00:   14.844 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 316876
  mean =      3.030 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1130 
    [ 1.250,  2.500) = 15809 
    [ 2.500,  3.750) = 286548 
    [ 3.750,  5.000) = 11572 
    [ 5.000,  6.250) = 886 
    [ 6.250,  7.500) = 325 
    [ 7.500,  8.750) = 160 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 111 
    [11.250, 12.500) = 102 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 66 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.465 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =     10.863 ms/op
     p(99.9900) =     17.508 ms/op
     p(99.9990) =     18.241 ms/op
     p(99.9999) =     19.694 ms/op
    p(100.0000) =     19.694 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.078 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.211 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.164 ±(99.9%) 0.006 ms/op
Iteration   1: 3.232 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.545 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.809 ms/op
                 getUser·p0.95:   3.965 ms/op
                 getUser·p0.99:   4.628 ms/op
                 getUser·p0.999:  10.169 ms/op
                 getUser·p0.9999: 11.962 ms/op
                 getUser·p1.00:   12.435 ms/op

Iteration   2: 3.174 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.699 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  8.867 ms/op
                 getUser·p0.9999: 14.826 ms/op
                 getUser·p1.00:   14.942 ms/op

Iteration   3: 3.133 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.515 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  6.769 ms/op
                 getUser·p0.9999: 16.433 ms/op
                 getUser·p1.00:   16.728 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 301955
  mean =      3.179 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 499 
    [ 1.250,  2.500) = 6581 
    [ 2.500,  3.750) = 266935 
    [ 3.750,  5.000) = 26212 
    [ 5.000,  6.250) = 770 
    [ 6.250,  7.500) = 451 
    [ 7.500,  8.750) = 190 
    [ 8.750, 10.000) = 71 
    [10.000, 11.250) = 103 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 59 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.515 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      8.915 ms/op
     p(99.9900) =     16.129 ms/op
     p(99.9990) =     16.661 ms/op
     p(99.9999) =     16.728 ms/op
    p(100.0000) =     16.728 ms/op


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
# Warmup Iteration   1: 4.892 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.976 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.862 ±(99.9%) 0.009 ms/op
Iteration   1: 3.862 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.335 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   5.358 ms/op
                 listUser·p0.99:   6.463 ms/op
                 listUser·p0.999:  12.587 ms/op
                 listUser·p0.9999: 14.486 ms/op
                 listUser·p1.00:   17.596 ms/op

Iteration   2: 3.857 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.380 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   6.414 ms/op
                 listUser·p0.999:  12.195 ms/op
                 listUser·p0.9999: 17.381 ms/op
                 listUser·p1.00:   17.826 ms/op

Iteration   3: 3.898 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.378 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   5.177 ms/op
                 listUser·p0.99:   6.513 ms/op
                 listUser·p0.999:  11.502 ms/op
                 listUser·p0.9999: 15.152 ms/op
                 listUser·p1.00:   16.810 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247772
  mean =      3.872 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 3139 
    [ 2.500,  3.750) = 108545 
    [ 3.750,  5.000) = 123378 
    [ 5.000,  6.250) = 8878 
    [ 6.250,  7.500) = 3007 
    [ 7.500,  8.750) = 288 
    [ 8.750, 10.000) = 91 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 140 
    [12.500, 13.750) = 111 
    [13.750, 15.000) = 66 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 35 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.335 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      5.038 ms/op
     p(99.0000) =      6.472 ms/op
     p(99.9000) =     12.222 ms/op
     p(99.9900) =     16.633 ms/op
     p(99.9990) =     17.681 ms/op
     p(99.9999) =     17.826 ms/op
    p(100.0000) =     17.826 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.153 ± 3.526  ops/ms
ClientGrpc.existUser                       thrpt       3  10.624 ± 1.409  ops/ms
ClientGrpc.getUser                         thrpt       3  10.260 ± 1.262  ops/ms
ClientGrpc.listUser                        thrpt       3   8.314 ± 1.155  ops/ms
ClientGrpc.createUser                       avgt       3   3.129 ± 0.254   ms/op
ClientGrpc.existUser                        avgt       3   2.984 ± 0.219   ms/op
ClientGrpc.getUser                          avgt       3   3.133 ± 1.056   ms/op
ClientGrpc.listUser                         avgt       3   3.857 ± 0.112   ms/op
ClientGrpc.createUser                     sample  302966   3.168 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.743           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.121           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.703           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.916           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.402           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.585           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          14.359           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.204           ms/op
ClientGrpc.existUser                      sample  316876   3.030 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.465           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.990           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.531           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.707           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.415           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.863           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.508           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.694           ms/op
ClientGrpc.getUser                        sample  301955   3.179 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.515           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.129           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.727           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.916           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.481           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.915           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.129           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.728           ms/op
ClientGrpc.listUser                       sample  247772   3.872 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.335           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.793           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.309           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.038           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.472           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.222           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          16.633           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          17.826           ms/op
