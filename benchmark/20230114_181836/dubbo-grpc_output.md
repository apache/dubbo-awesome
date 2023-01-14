# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.532 ops/ms
# Warmup Iteration   2: 6.207 ops/ms
# Warmup Iteration   3: 7.397 ops/ms
Iteration   1: 7.905 ops/ms
Iteration   2: 8.210 ops/ms
Iteration   3: 7.974 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.030 ±(99.9%) 2.923 ops/ms [Average]
  (min, avg, max) = (7.905, 8.030, 8.210), stdev = 0.160
  CI (99.9%): [5.106, 10.953] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.472 ops/ms
# Warmup Iteration   2: 7.810 ops/ms
# Warmup Iteration   3: 8.490 ops/ms
Iteration   1: 8.616 ops/ms
Iteration   2: 8.250 ops/ms
Iteration   3: 8.409 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.425 ±(99.9%) 3.350 ops/ms [Average]
  (min, avg, max) = (8.250, 8.425, 8.616), stdev = 0.184
  CI (99.9%): [5.075, 11.775] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.212 ops/ms
# Warmup Iteration   2: 7.677 ops/ms
# Warmup Iteration   3: 8.064 ops/ms
Iteration   1: 7.933 ops/ms
Iteration   2: 7.746 ops/ms
Iteration   3: 8.103 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.927 ±(99.9%) 3.256 ops/ms [Average]
  (min, avg, max) = (7.746, 7.927, 8.103), stdev = 0.178
  CI (99.9%): [4.672, 11.183] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.198 ops/ms
# Warmup Iteration   2: 5.784 ops/ms
# Warmup Iteration   3: 6.343 ops/ms
Iteration   1: 6.163 ops/ms
Iteration   2: 6.516 ops/ms
Iteration   3: 6.452 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.377 ±(99.9%) 3.436 ops/ms [Average]
  (min, avg, max) = (6.163, 6.377, 6.516), stdev = 0.188
  CI (99.9%): [2.941, 9.813] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.871 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.194 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.088 ±(99.9%) 0.004 ms/op
Iteration   1: 4.161 ±(99.9%) 0.002 ms/op
Iteration   2: 4.016 ±(99.9%) 0.003 ms/op
Iteration   3: 3.904 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.027 ±(99.9%) 2.358 ms/op [Average]
  (min, avg, max) = (3.904, 4.027, 4.161), stdev = 0.129
  CI (99.9%): [1.669, 6.385] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.268 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.989 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.957 ±(99.9%) 0.002 ms/op
Iteration   1: 3.764 ±(99.9%) 0.003 ms/op
Iteration   2: 3.807 ±(99.9%) 0.003 ms/op
Iteration   3: 3.925 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.832 ±(99.9%) 1.529 ms/op [Average]
  (min, avg, max) = (3.764, 3.832, 3.925), stdev = 0.084
  CI (99.9%): [2.303, 5.361] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.749 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.376 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.250 ±(99.9%) 0.004 ms/op
Iteration   1: 4.086 ±(99.9%) 0.003 ms/op
Iteration   2: 4.218 ±(99.9%) 0.005 ms/op
Iteration   3: 4.120 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.141 ±(99.9%) 1.251 ms/op [Average]
  (min, avg, max) = (4.086, 4.141, 4.218), stdev = 0.069
  CI (99.9%): [2.891, 5.392] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.130 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 5.562 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.364 ±(99.9%) 0.030 ms/op
Iteration   1: 5.256 ±(99.9%) 0.028 ms/op
Iteration   2: 5.399 ±(99.9%) 0.047 ms/op
Iteration   3: 5.341 ±(99.9%) 0.040 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.332 ±(99.9%) 1.311 ms/op [Average]
  (min, avg, max) = (5.256, 5.332, 5.399), stdev = 0.072
  CI (99.9%): [4.020, 6.643] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.956 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.372 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.005 ±(99.9%) 0.011 ms/op
Iteration   1: 4.137 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.763 ms/op
                 createUser·p0.50:   4.006 ms/op
                 createUser·p0.90:   5.317 ms/op
                 createUser·p0.95:   5.710 ms/op
                 createUser·p0.99:   7.594 ms/op
                 createUser·p0.999:  14.386 ms/op
                 createUser·p0.9999: 16.908 ms/op
                 createUser·p1.00:   17.203 ms/op

Iteration   2: 4.029 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.065 ms/op
                 createUser·p0.50:   3.928 ms/op
                 createUser·p0.90:   5.251 ms/op
                 createUser·p0.95:   5.644 ms/op
                 createUser·p0.99:   7.053 ms/op
                 createUser·p0.999:  11.534 ms/op
                 createUser·p0.9999: 29.069 ms/op
                 createUser·p1.00:   29.426 ms/op

Iteration   3: 4.056 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.979 ms/op
                 createUser·p0.50:   3.953 ms/op
                 createUser·p0.90:   5.095 ms/op
                 createUser·p0.95:   5.448 ms/op
                 createUser·p0.99:   7.034 ms/op
                 createUser·p0.999:  18.086 ms/op
                 createUser·p0.9999: 25.690 ms/op
                 createUser·p1.00:   26.018 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 235823
  mean =      4.073 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5895 
    [ 2.500,  5.000) = 196034 
    [ 5.000,  7.500) = 31807 
    [ 7.500, 10.000) = 1567 
    [10.000, 12.500) = 268 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.763 ms/op
     p(50.0000) =      3.961 ms/op
     p(90.0000) =      5.218 ms/op
     p(95.0000) =      5.603 ms/op
     p(99.0000) =      7.291 ms/op
     p(99.9000) =     13.637 ms/op
     p(99.9900) =     28.306 ms/op
     p(99.9990) =     29.369 ms/op
     p(99.9999) =     29.426 ms/op
    p(100.0000) =     29.426 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.751 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.145 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.885 ±(99.9%) 0.011 ms/op
Iteration   1: 4.168 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.178 ms/op
                 existUser·p0.50:   4.002 ms/op
                 existUser·p0.90:   5.358 ms/op
                 existUser·p0.95:   5.816 ms/op
                 existUser·p0.99:   7.578 ms/op
                 existUser·p0.999:  11.876 ms/op
                 existUser·p0.9999: 18.350 ms/op
                 existUser·p1.00:   19.890 ms/op

Iteration   2: 4.163 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.126 ms/op
                 existUser·p0.50:   4.096 ms/op
                 existUser·p0.90:   5.259 ms/op
                 existUser·p0.95:   5.587 ms/op
                 existUser·p0.99:   6.939 ms/op
                 existUser·p0.999:  10.587 ms/op
                 existUser·p0.9999: 17.803 ms/op
                 existUser·p1.00:   19.169 ms/op

Iteration   3: 4.158 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.126 ms/op
                 existUser·p0.50:   4.067 ms/op
                 existUser·p0.90:   5.259 ms/op
                 existUser·p0.95:   5.595 ms/op
                 existUser·p0.99:   6.636 ms/op
                 existUser·p0.999:  11.275 ms/op
                 existUser·p0.9999: 22.348 ms/op
                 existUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 230562
  mean =      4.163 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4409 
    [ 2.500,  5.000) = 189949 
    [ 5.000,  7.500) = 34549 
    [ 7.500, 10.000) = 1237 
    [10.000, 12.500) = 283 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.126 ms/op
     p(50.0000) =      4.051 ms/op
     p(90.0000) =      5.284 ms/op
     p(95.0000) =      5.661 ms/op
     p(99.0000) =      7.029 ms/op
     p(99.9000) =     11.148 ms/op
     p(99.9900) =     20.249 ms/op
     p(99.9990) =     22.645 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.221 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.440 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.210 ±(99.9%) 0.011 ms/op
Iteration   1: 4.153 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.935 ms/op
                 getUser·p0.50:   4.043 ms/op
                 getUser·p0.90:   5.095 ms/op
                 getUser·p0.95:   5.595 ms/op
                 getUser·p0.99:   7.202 ms/op
                 getUser·p0.999:  13.698 ms/op
                 getUser·p0.9999: 15.303 ms/op
                 getUser·p1.00:   15.565 ms/op

Iteration   2: 4.127 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.486 ms/op
                 getUser·p0.50:   4.067 ms/op
                 getUser·p0.90:   5.120 ms/op
                 getUser·p0.95:   5.480 ms/op
                 getUser·p0.99:   6.504 ms/op
                 getUser·p0.999:  10.469 ms/op
                 getUser·p0.9999: 15.340 ms/op
                 getUser·p1.00:   17.007 ms/op

Iteration   3: 4.200 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.038 ms/op
                 getUser·p0.50:   4.108 ms/op
                 getUser·p0.90:   5.251 ms/op
                 getUser·p0.95:   5.562 ms/op
                 getUser·p0.99:   6.791 ms/op
                 getUser·p0.999:  14.451 ms/op
                 getUser·p0.9999: 19.137 ms/op
                 getUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 230611
  mean =      4.160 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 36 
    [ 1.250,  2.500) = 4546 
    [ 2.500,  3.750) = 69587 
    [ 3.750,  5.000) = 125797 
    [ 5.000,  6.250) = 26833 
    [ 6.250,  7.500) = 2338 
    [ 7.500,  8.750) = 671 
    [ 8.750, 10.000) = 312 
    [10.000, 11.250) = 177 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 91 
    [15.000, 16.250) = 56 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.486 ms/op
     p(50.0000) =      4.071 ms/op
     p(90.0000) =      5.169 ms/op
     p(95.0000) =      5.538 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     13.337 ms/op
     p(99.9900) =     17.648 ms/op
     p(99.9990) =     19.258 ms/op
     p(99.9999) =     19.497 ms/op
    p(100.0000) =     19.497 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 7.873 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 5.539 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.441 ±(99.9%) 0.021 ms/op
Iteration   1: 5.257 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.370 ms/op
                 listUser·p0.50:   5.046 ms/op
                 listUser·p0.90:   6.668 ms/op
                 listUser·p0.95:   7.447 ms/op
                 listUser·p0.99:   9.470 ms/op
                 listUser·p0.999:  22.741 ms/op
                 listUser·p0.9999: 24.702 ms/op
                 listUser·p1.00:   25.133 ms/op

Iteration   2: 5.209 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.442 ms/op
                 listUser·p0.50:   5.005 ms/op
                 listUser·p0.90:   6.636 ms/op
                 listUser·p0.95:   7.602 ms/op
                 listUser·p0.99:   9.273 ms/op
                 listUser·p0.999:  24.234 ms/op
                 listUser·p0.9999: 26.968 ms/op
                 listUser·p1.00:   27.361 ms/op

Iteration   3: 5.172 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.298 ms/op
                 listUser·p0.50:   4.997 ms/op
                 listUser·p0.90:   6.652 ms/op
                 listUser·p0.95:   7.561 ms/op
                 listUser·p0.99:   9.235 ms/op
                 listUser·p0.999:  23.784 ms/op
                 listUser·p0.9999: 28.308 ms/op
                 listUser·p1.00:   29.655 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 184127
  mean =      5.213 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 300 
    [ 2.500,  5.000) = 90308 
    [ 5.000,  7.500) = 83979 
    [ 7.500, 10.000) = 8449 
    [10.000, 12.500) = 694 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 149 
    [25.000, 27.500) = 72 

  Percentiles, ms/op:
      p(0.0000) =      1.298 ms/op
     p(50.0000) =      5.022 ms/op
     p(90.0000) =      6.652 ms/op
     p(95.0000) =      7.537 ms/op
     p(99.0000) =      9.322 ms/op
     p(99.9000) =     23.134 ms/op
     p(99.9900) =     27.007 ms/op
     p(99.9990) =     29.517 ms/op
     p(99.9999) =     29.655 ms/op
    p(100.0000) =     29.655 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.030 ± 2.923  ops/ms
ClientGrpc.existUser                       thrpt       3   8.425 ± 3.350  ops/ms
ClientGrpc.getUser                         thrpt       3   7.927 ± 3.256  ops/ms
ClientGrpc.listUser                        thrpt       3   6.377 ± 3.436  ops/ms
ClientGrpc.createUser                       avgt       3   4.027 ± 2.358   ms/op
ClientGrpc.existUser                        avgt       3   3.832 ± 1.529   ms/op
ClientGrpc.getUser                          avgt       3   4.141 ± 1.251   ms/op
ClientGrpc.listUser                         avgt       3   5.332 ± 1.311   ms/op
ClientGrpc.createUser                     sample  235823   4.073 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.763           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.961           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.218           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.603           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.291           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.637           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.306           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.426           ms/op
ClientGrpc.existUser                      sample  230562   4.163 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.126           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.051           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.284           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.661           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.029           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.148           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.249           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.741           ms/op
ClientGrpc.getUser                        sample  230611   4.160 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.486           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.071           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.169           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.538           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.799           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.337           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.648           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.497           ms/op
ClientGrpc.listUser                       sample  184127   5.213 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.298           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.022           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.652           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.537           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.322           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          23.134           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.007           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.655           ms/op
