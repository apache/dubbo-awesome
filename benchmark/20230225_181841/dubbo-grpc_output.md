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
# Warmup Iteration   1: 4.244 ops/ms
# Warmup Iteration   2: 9.122 ops/ms
# Warmup Iteration   3: 10.054 ops/ms
Iteration   1: 9.852 ops/ms
Iteration   2: 10.359 ops/ms
Iteration   3: 9.893 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.035 ±(99.9%) 5.136 ops/ms [Average]
  (min, avg, max) = (9.852, 10.035, 10.359), stdev = 0.282
  CI (99.9%): [4.899, 15.170] (assumes normal distribution)


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
# Warmup Iteration   1: 7.446 ops/ms
# Warmup Iteration   2: 10.123 ops/ms
# Warmup Iteration   3: 10.544 ops/ms
Iteration   1: 10.810 ops/ms
Iteration   2: 10.632 ops/ms
Iteration   3: 10.726 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.723 ±(99.9%) 1.618 ops/ms [Average]
  (min, avg, max) = (10.632, 10.723, 10.810), stdev = 0.089
  CI (99.9%): [9.104, 12.341] (assumes normal distribution)


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
# Warmup Iteration   1: 7.446 ops/ms
# Warmup Iteration   2: 10.119 ops/ms
# Warmup Iteration   3: 10.063 ops/ms
Iteration   1: 10.108 ops/ms
Iteration   2: 10.370 ops/ms
Iteration   3: 10.056 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.178 ±(99.9%) 3.071 ops/ms [Average]
  (min, avg, max) = (10.056, 10.178, 10.370), stdev = 0.168
  CI (99.9%): [7.107, 13.250] (assumes normal distribution)


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
# Warmup Iteration   1: 5.864 ops/ms
# Warmup Iteration   2: 7.760 ops/ms
# Warmup Iteration   3: 7.774 ops/ms
Iteration   1: 7.931 ops/ms
Iteration   2: 8.117 ops/ms
Iteration   3: 8.040 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.029 ±(99.9%) 1.705 ops/ms [Average]
  (min, avg, max) = (7.931, 8.029, 8.117), stdev = 0.093
  CI (99.9%): [6.324, 9.734] (assumes normal distribution)


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
# Warmup Iteration   1: 3.901 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.212 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.110 ±(99.9%) 0.003 ms/op
Iteration   1: 3.133 ±(99.9%) 0.008 ms/op
Iteration   2: 3.127 ±(99.9%) 0.003 ms/op
Iteration   3: 3.162 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.141 ±(99.9%) 0.342 ms/op [Average]
  (min, avg, max) = (3.127, 3.141, 3.162), stdev = 0.019
  CI (99.9%): [2.798, 3.483] (assumes normal distribution)


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
# Warmup Iteration   1: 4.041 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.066 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.969 ±(99.9%) 0.003 ms/op
Iteration   1: 3.046 ±(99.9%) 0.002 ms/op
Iteration   2: 3.015 ±(99.9%) 0.002 ms/op
Iteration   3: 2.935 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.999 ±(99.9%) 1.047 ms/op [Average]
  (min, avg, max) = (2.935, 2.999, 3.046), stdev = 0.057
  CI (99.9%): [1.952, 4.046] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.274 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.312 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.079 ±(99.9%) 0.003 ms/op
Iteration   1: 3.136 ±(99.9%) 0.002 ms/op
Iteration   2: 3.095 ±(99.9%) 0.002 ms/op
Iteration   3: 3.115 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.116 ±(99.9%) 0.370 ms/op [Average]
  (min, avg, max) = (3.095, 3.116, 3.136), stdev = 0.020
  CI (99.9%): [2.746, 3.485] (assumes normal distribution)


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
# Warmup Iteration   1: 5.563 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.074 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.986 ±(99.9%) 0.024 ms/op
Iteration   1: 3.922 ±(99.9%) 0.009 ms/op
Iteration   2: 3.986 ±(99.9%) 0.013 ms/op
Iteration   3: 4.101 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.003 ±(99.9%) 1.659 ms/op [Average]
  (min, avg, max) = (3.922, 4.003, 4.101), stdev = 0.091
  CI (99.9%): [2.344, 5.661] (assumes normal distribution)


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
# Warmup Iteration   1: 3.993 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.202 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.179 ±(99.9%) 0.007 ms/op
Iteration   1: 3.625 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   0.686 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   4.145 ms/op
                 createUser·p0.95:   8.208 ms/op
                 createUser·p0.99:   12.632 ms/op
                 createUser·p0.999:  15.298 ms/op
                 createUser·p0.9999: 17.078 ms/op
                 createUser·p1.00:   18.350 ms/op

Iteration   2: 3.172 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.645 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.875 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   4.472 ms/op
                 createUser·p0.999:  8.210 ms/op
                 createUser·p0.9999: 17.037 ms/op
                 createUser·p1.00:   17.465 ms/op

Iteration   3: 3.168 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.894 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  10.076 ms/op
                 createUser·p0.9999: 25.428 ms/op
                 createUser·p1.00:   26.083 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 290189
  mean =      3.308 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22185 
    [ 2.500,  5.000) = 260825 
    [ 5.000,  7.500) = 1840 
    [ 7.500, 10.000) = 2242 
    [10.000, 12.500) = 1990 
    [12.500, 15.000) = 865 
    [15.000, 17.500) = 209 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.645 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =     10.174 ms/op
     p(99.9000) =     14.808 ms/op
     p(99.9900) =     17.823 ms/op
     p(99.9990) =     25.486 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


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
# Warmup Iteration   1: 3.928 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.145 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.007 ms/op
Iteration   1: 2.958 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.718 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  7.017 ms/op
                 existUser·p0.9999: 12.737 ms/op
                 existUser·p1.00:   13.107 ms/op

Iteration   2: 2.902 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.777 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   4.190 ms/op
                 existUser·p0.999:  6.798 ms/op
                 existUser·p0.9999: 14.171 ms/op
                 existUser·p1.00:   14.418 ms/op

Iteration   3: 3.042 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.837 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  7.078 ms/op
                 existUser·p0.9999: 17.564 ms/op
                 existUser·p1.00:   19.694 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323451
  mean =      2.966 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1873 
    [ 1.250,  2.500) = 48312 
    [ 2.500,  3.750) = 252646 
    [ 3.750,  5.000) = 19573 
    [ 5.000,  6.250) = 482 
    [ 6.250,  7.500) = 314 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.718 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      7.021 ms/op
     p(99.9900) =     17.192 ms/op
     p(99.9990) =     18.980 ms/op
     p(99.9999) =     19.694 ms/op
    p(100.0000) =     19.694 ms/op


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
# Warmup Iteration   1: 4.123 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.226 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.113 ±(99.9%) 0.006 ms/op
Iteration   1: 3.115 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.585 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   3.994 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  7.291 ms/op
                 getUser·p0.9999: 14.451 ms/op
                 getUser·p1.00:   14.844 ms/op

Iteration   2: 3.086 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.811 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  7.184 ms/op
                 getUser·p0.9999: 14.813 ms/op
                 getUser·p1.00:   15.204 ms/op

Iteration   3: 3.173 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.767 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.022 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  5.409 ms/op
                 getUser·p0.9999: 16.613 ms/op
                 getUser·p1.00:   17.269 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 307397
  mean =      3.124 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 485 
    [ 1.250,  2.500) = 23539 
    [ 2.500,  3.750) = 249041 
    [ 3.750,  5.000) = 33353 
    [ 5.000,  6.250) = 540 
    [ 6.250,  7.500) = 236 
    [ 7.500,  8.750) = 43 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 69 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.585 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      6.791 ms/op
     p(99.9900) =     14.815 ms/op
     p(99.9990) =     17.133 ms/op
     p(99.9999) =     17.269 ms/op
    p(100.0000) =     17.269 ms/op


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
# Warmup Iteration   1: 5.573 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.026 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.902 ±(99.9%) 0.010 ms/op
Iteration   1: 4.022 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.978 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   5.333 ms/op
                 listUser·p0.95:   5.923 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  13.263 ms/op
                 listUser·p0.9999: 20.092 ms/op
                 listUser·p1.00:   21.398 ms/op

Iteration   2: 3.896 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.427 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  20.473 ms/op
                 listUser·p0.9999: 24.038 ms/op
                 listUser·p1.00:   24.740 ms/op

Iteration   3: 3.912 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.876 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   6.611 ms/op
                 listUser·p0.999:  21.080 ms/op
                 listUser·p0.9999: 25.166 ms/op
                 listUser·p1.00:   25.625 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243423
  mean =      3.942 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3444 
    [ 2.500,  5.000) = 213540 
    [ 5.000,  7.500) = 25253 
    [ 7.500, 10.000) = 690 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.876 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      5.079 ms/op
     p(95.0000) =      5.726 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     17.564 ms/op
     p(99.9900) =     24.619 ms/op
     p(99.9990) =     25.497 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.035 ± 5.136  ops/ms
ClientGrpc.existUser                       thrpt       3  10.723 ± 1.618  ops/ms
ClientGrpc.getUser                         thrpt       3  10.178 ± 3.071  ops/ms
ClientGrpc.listUser                        thrpt       3   8.029 ± 1.705  ops/ms
ClientGrpc.createUser                       avgt       3   3.141 ± 0.342   ms/op
ClientGrpc.existUser                        avgt       3   2.999 ± 1.047   ms/op
ClientGrpc.getUser                          avgt       3   3.116 ± 0.370   ms/op
ClientGrpc.listUser                         avgt       3   4.003 ± 1.659   ms/op
ClientGrpc.createUser                     sample  290189   3.308 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.645           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.146           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.903           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.166           ms/op
ClientGrpc.createUser:createUser·p0.99    sample          10.174           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.808           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.823           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.083           ms/op
ClientGrpc.existUser                      sample  323451   2.966 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.718           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.961           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.613           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.813           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.021           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.192           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.694           ms/op
ClientGrpc.getUser                        sample  307397   3.124 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.585           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.101           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.785           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.973           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.317           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.791           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.815           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.269           ms/op
ClientGrpc.listUser                       sample  243423   3.942 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.876           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.756           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.079           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.726           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.808           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.564           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.619           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.625           ms/op
