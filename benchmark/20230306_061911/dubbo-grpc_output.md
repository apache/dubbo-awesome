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
# Warmup Iteration   1: 4.055 ops/ms
# Warmup Iteration   2: 8.738 ops/ms
# Warmup Iteration   3: 9.890 ops/ms
Iteration   1: 9.912 ops/ms
Iteration   2: 9.725 ops/ms
Iteration   3: 9.913 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.850 ±(99.9%) 1.979 ops/ms [Average]
  (min, avg, max) = (9.725, 9.850, 9.913), stdev = 0.108
  CI (99.9%): [7.871, 11.829] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.557 ops/ms
# Warmup Iteration   2: 10.493 ops/ms
# Warmup Iteration   3: 10.363 ops/ms
Iteration   1: 10.530 ops/ms
Iteration   2: 10.622 ops/ms
Iteration   3: 10.442 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.531 ±(99.9%) 1.644 ops/ms [Average]
  (min, avg, max) = (10.442, 10.531, 10.622), stdev = 0.090
  CI (99.9%): [8.888, 12.175] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.837 ops/ms
# Warmup Iteration   2: 9.893 ops/ms
# Warmup Iteration   3: 10.150 ops/ms
Iteration   1: 10.111 ops/ms
Iteration   2: 10.180 ops/ms
Iteration   3: 10.303 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.198 ±(99.9%) 1.780 ops/ms [Average]
  (min, avg, max) = (10.111, 10.198, 10.303), stdev = 0.098
  CI (99.9%): [8.418, 11.978] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.490 ops/ms
# Warmup Iteration   2: 7.539 ops/ms
# Warmup Iteration   3: 7.583 ops/ms
Iteration   1: 7.799 ops/ms
Iteration   2: 8.237 ops/ms
Iteration   3: 7.852 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.962 ±(99.9%) 4.360 ops/ms [Average]
  (min, avg, max) = (7.799, 7.962, 8.237), stdev = 0.239
  CI (99.9%): [3.602, 12.323] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.154 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.228 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.131 ±(99.9%) 0.010 ms/op
Iteration   1: 3.201 ±(99.9%) 0.003 ms/op
Iteration   2: 3.092 ±(99.9%) 0.003 ms/op
Iteration   3: 3.055 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.116 ±(99.9%) 1.380 ms/op [Average]
  (min, avg, max) = (3.055, 3.116, 3.201), stdev = 0.076
  CI (99.9%): [1.736, 4.496] (assumes normal distribution)


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
# Warmup Iteration   1: 4.034 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.193 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.002 ms/op
Iteration   1: 2.991 ±(99.9%) 0.003 ms/op
Iteration   2: 2.947 ±(99.9%) 0.002 ms/op
Iteration   3: 3.076 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.005 ±(99.9%) 1.198 ms/op [Average]
  (min, avg, max) = (2.947, 3.005, 3.076), stdev = 0.066
  CI (99.9%): [1.807, 4.203] (assumes normal distribution)


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
# Warmup Iteration   1: 4.450 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.235 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.146 ±(99.9%) 0.003 ms/op
Iteration   1: 3.173 ±(99.9%) 0.002 ms/op
Iteration   2: 3.132 ±(99.9%) 0.004 ms/op
Iteration   3: 3.144 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.149 ±(99.9%) 0.380 ms/op [Average]
  (min, avg, max) = (3.132, 3.149, 3.173), stdev = 0.021
  CI (99.9%): [2.770, 3.529] (assumes normal distribution)


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
# Warmup Iteration   1: 5.730 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.248 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.104 ±(99.9%) 0.010 ms/op
Iteration   1: 4.109 ±(99.9%) 0.011 ms/op
Iteration   2: 4.068 ±(99.9%) 0.007 ms/op
Iteration   3: 4.014 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.064 ±(99.9%) 0.869 ms/op [Average]
  (min, avg, max) = (4.014, 4.064, 4.109), stdev = 0.048
  CI (99.9%): [3.195, 4.932] (assumes normal distribution)


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
# Warmup Iteration   1: 4.406 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.234 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.138 ±(99.9%) 0.007 ms/op
Iteration   1: 3.207 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.909 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.903 ms/op
                 createUser·p0.95:   4.104 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  7.086 ms/op
                 createUser·p0.9999: 19.268 ms/op
                 createUser·p1.00:   19.857 ms/op

Iteration   2: 3.096 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.837 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  7.898 ms/op
                 createUser·p0.9999: 14.904 ms/op
                 createUser·p1.00:   15.663 ms/op

Iteration   3: 3.206 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.763 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.071 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  9.067 ms/op
                 createUser·p0.9999: 18.875 ms/op
                 createUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 303158
  mean =      3.169 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 453 
    [ 1.250,  2.500) = 23497 
    [ 2.500,  3.750) = 239944 
    [ 3.750,  5.000) = 38192 
    [ 5.000,  6.250) = 463 
    [ 6.250,  7.500) = 264 
    [ 7.500,  8.750) = 113 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 55 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.763 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.030 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      7.855 ms/op
     p(99.9900) =     18.897 ms/op
     p(99.9990) =     19.756 ms/op
     p(99.9999) =     19.923 ms/op
    p(100.0000) =     19.923 ms/op


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
# Warmup Iteration   1: 4.285 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.167 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.108 ±(99.9%) 0.007 ms/op
Iteration   1: 2.977 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.693 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  5.444 ms/op
                 existUser·p0.9999: 13.509 ms/op
                 existUser·p1.00:   13.746 ms/op

Iteration   2: 3.050 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.855 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  6.908 ms/op
                 existUser·p0.9999: 15.213 ms/op
                 existUser·p1.00:   15.679 ms/op

Iteration   3: 3.080 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.706 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.736 ms/op
                 existUser·p0.95:   3.916 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  10.951 ms/op
                 existUser·p0.9999: 18.534 ms/op
                 existUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 316077
  mean =      3.035 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37413 
    [ 2.500,  5.000) = 277882 
    [ 5.000,  7.500) = 540 
    [ 7.500, 10.000) = 18 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      6.774 ms/op
     p(99.9900) =     17.805 ms/op
     p(99.9990) =     20.502 ms/op
     p(99.9999) =     20.644 ms/op
    p(100.0000) =     20.644 ms/op


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
# Warmup Iteration   1: 4.392 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.250 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.233 ±(99.9%) 0.007 ms/op
Iteration   1: 3.183 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.840 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.051 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  9.256 ms/op
                 getUser·p0.9999: 16.644 ms/op
                 getUser·p1.00:   17.072 ms/op

Iteration   2: 3.205 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.697 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.084 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  9.027 ms/op
                 getUser·p0.9999: 15.647 ms/op
                 getUser·p1.00:   16.155 ms/op

Iteration   3: 3.189 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.927 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.030 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  6.540 ms/op
                 getUser·p0.9999: 17.462 ms/op
                 getUser·p1.00:   18.153 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 300880
  mean =      3.192 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 436 
    [ 1.250,  2.500) = 19832 
    [ 2.500,  3.750) = 237308 
    [ 3.750,  5.000) = 42135 
    [ 5.000,  6.250) = 523 
    [ 6.250,  7.500) = 269 
    [ 7.500,  8.750) = 117 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 56 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 62 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.697 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      8.086 ms/op
     p(99.9900) =     16.482 ms/op
     p(99.9990) =     18.088 ms/op
     p(99.9999) =     18.153 ms/op
    p(100.0000) =     18.153 ms/op


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
# Warmup Iteration   1: 5.614 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.372 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.146 ±(99.9%) 0.012 ms/op
Iteration   1: 4.067 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.329 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   5.349 ms/op
                 listUser·p0.95:   6.128 ms/op
                 listUser·p0.99:   7.051 ms/op
                 listUser·p0.999:  13.797 ms/op
                 listUser·p0.9999: 16.100 ms/op
                 listUser·p1.00:   18.547 ms/op

Iteration   2: 4.173 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.296 ms/op
                 listUser·p0.50:   3.985 ms/op
                 listUser·p0.90:   5.317 ms/op
                 listUser·p0.95:   6.038 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  16.230 ms/op
                 listUser·p0.9999: 19.661 ms/op
                 listUser·p1.00:   19.988 ms/op

Iteration   3: 4.135 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.239 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   5.399 ms/op
                 listUser·p0.95:   5.956 ms/op
                 listUser·p0.99:   7.258 ms/op
                 listUser·p0.999:  16.247 ms/op
                 listUser·p0.9999: 28.156 ms/op
                 listUser·p1.00:   28.738 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 232720
  mean =      4.124 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2636 
    [ 2.500,  5.000) = 198211 
    [ 5.000,  7.500) = 30295 
    [ 7.500, 10.000) = 1100 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 162 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.239 ms/op
     p(50.0000) =      3.940 ms/op
     p(90.0000) =      5.366 ms/op
     p(95.0000) =      6.046 ms/op
     p(99.0000) =      7.127 ms/op
     p(99.9000) =     15.537 ms/op
     p(99.9900) =     26.271 ms/op
     p(99.9990) =     28.618 ms/op
     p(99.9999) =     28.738 ms/op
    p(100.0000) =     28.738 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.850 ± 1.979  ops/ms
ClientGrpc.existUser                       thrpt       3  10.531 ± 1.644  ops/ms
ClientGrpc.getUser                         thrpt       3  10.198 ± 1.780  ops/ms
ClientGrpc.listUser                        thrpt       3   7.962 ± 4.360  ops/ms
ClientGrpc.createUser                       avgt       3   3.116 ± 1.380   ms/op
ClientGrpc.existUser                        avgt       3   3.005 ± 1.198   ms/op
ClientGrpc.getUser                          avgt       3   3.149 ± 0.380   ms/op
ClientGrpc.listUser                         avgt       3   4.064 ± 0.869   ms/op
ClientGrpc.createUser                     sample  303158   3.169 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.763           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.138           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.838           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.030           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.855           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.897           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.923           ms/op
ClientGrpc.existUser                      sample  316077   3.035 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.693           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.011           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.654           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.842           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.252           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.774           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.805           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.644           ms/op
ClientGrpc.getUser                        sample  300880   3.192 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.697           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.170           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.867           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.055           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.489           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.086           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.482           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.153           ms/op
ClientGrpc.listUser                       sample  232720   4.124 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.239           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.940           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.366           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.046           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.127           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.537           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.271           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.738           ms/op
