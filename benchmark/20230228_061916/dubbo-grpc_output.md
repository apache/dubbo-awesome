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
# Warmup Iteration   1: 4.938 ops/ms
# Warmup Iteration   2: 9.184 ops/ms
# Warmup Iteration   3: 10.223 ops/ms
Iteration   1: 10.559 ops/ms
Iteration   2: 10.089 ops/ms
Iteration   3: 10.395 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.348 ±(99.9%) 4.353 ops/ms [Average]
  (min, avg, max) = (10.089, 10.348, 10.559), stdev = 0.239
  CI (99.9%): [5.995, 14.701] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:55
# Fork: 1 of 1
# Warmup Iteration   1: 9.305 ops/ms
# Warmup Iteration   2: 10.903 ops/ms
# Warmup Iteration   3: 11.050 ops/ms
Iteration   1: 11.254 ops/ms
Iteration   2: 11.236 ops/ms
Iteration   3: 11.046 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.178 ±(99.9%) 2.105 ops/ms [Average]
  (min, avg, max) = (11.046, 11.178, 11.254), stdev = 0.115
  CI (99.9%): [9.073, 13.283] (assumes normal distribution)


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
# Warmup Iteration   1: 7.319 ops/ms
# Warmup Iteration   2: 10.327 ops/ms
# Warmup Iteration   3: 10.437 ops/ms
Iteration   1: 10.446 ops/ms
Iteration   2: 10.983 ops/ms
Iteration   3: 10.483 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.637 ±(99.9%) 5.471 ops/ms [Average]
  (min, avg, max) = (10.446, 10.637, 10.983), stdev = 0.300
  CI (99.9%): [5.166, 16.108] (assumes normal distribution)


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
# Warmup Iteration   1: 5.886 ops/ms
# Warmup Iteration   2: 8.096 ops/ms
# Warmup Iteration   3: 8.303 ops/ms
Iteration   1: 8.012 ops/ms
Iteration   2: 8.244 ops/ms
Iteration   3: 7.970 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.075 ±(99.9%) 2.690 ops/ms [Average]
  (min, avg, max) = (7.970, 8.075, 8.244), stdev = 0.147
  CI (99.9%): [5.385, 10.765] (assumes normal distribution)


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
# Warmup Iteration   1: 3.939 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.097 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.965 ±(99.9%) 0.003 ms/op
Iteration   1: 3.126 ±(99.9%) 0.002 ms/op
Iteration   2: 3.108 ±(99.9%) 0.001 ms/op
Iteration   3: 3.139 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.125 ±(99.9%) 0.284 ms/op [Average]
  (min, avg, max) = (3.108, 3.125, 3.139), stdev = 0.016
  CI (99.9%): [2.840, 3.409] (assumes normal distribution)


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
# Warmup Iteration   1: 3.795 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.031 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.876 ±(99.9%) 0.004 ms/op
Iteration   1: 2.872 ±(99.9%) 0.003 ms/op
Iteration   2: 2.851 ±(99.9%) 0.003 ms/op
Iteration   3: 2.895 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.873 ±(99.9%) 0.406 ms/op [Average]
  (min, avg, max) = (2.851, 2.873, 2.895), stdev = 0.022
  CI (99.9%): [2.467, 3.279] (assumes normal distribution)


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
# Warmup Iteration   1: 3.836 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.056 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.002 ms/op
Iteration   1: 3.022 ±(99.9%) 0.002 ms/op
Iteration   2: 2.957 ±(99.9%) 0.002 ms/op
Iteration   3: 3.043 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.007 ±(99.9%) 0.814 ms/op [Average]
  (min, avg, max) = (2.957, 3.007, 3.043), stdev = 0.045
  CI (99.9%): [2.193, 3.821] (assumes normal distribution)


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
# Warmup Iteration   1: 4.613 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.031 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.948 ±(99.9%) 0.016 ms/op
Iteration   1: 3.933 ±(99.9%) 0.015 ms/op
Iteration   2: 3.853 ±(99.9%) 0.005 ms/op
Iteration   3: 3.982 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.923 ±(99.9%) 1.188 ms/op [Average]
  (min, avg, max) = (3.853, 3.923, 3.982), stdev = 0.065
  CI (99.9%): [2.734, 5.111] (assumes normal distribution)


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
# Warmup Iteration   1: 3.996 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.103 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.006 ms/op
Iteration   1: 3.019 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.741 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.682 ms/op
                 createUser·p0.99:   4.202 ms/op
                 createUser·p0.999:  7.733 ms/op
                 createUser·p0.9999: 15.676 ms/op
                 createUser·p1.00:   15.974 ms/op

Iteration   2: 2.969 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.406 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.408 ms/op
                 createUser·p0.95:   3.617 ms/op
                 createUser·p0.99:   4.227 ms/op
                 createUser·p0.999:  7.039 ms/op
                 createUser·p0.9999: 16.171 ms/op
                 createUser·p1.00:   18.350 ms/op

Iteration   3: 3.060 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.613 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   4.162 ms/op
                 createUser·p0.999:  11.223 ms/op
                 createUser·p0.9999: 33.066 ms/op
                 createUser·p1.00:   33.522 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318334
  mean =      3.015 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27905 
    [ 2.500,  5.000) = 289270 
    [ 5.000,  7.500) = 789 
    [ 7.500, 10.000) = 117 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 6 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.406 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      7.903 ms/op
     p(99.9900) =     32.189 ms/op
     p(99.9990) =     33.385 ms/op
     p(99.9999) =     33.522 ms/op
    p(100.0000) =     33.522 ms/op


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
# Warmup Iteration   1: 3.800 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.185 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.870 ±(99.9%) 0.006 ms/op
Iteration   1: 2.862 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.515 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  5.647 ms/op
                 existUser·p0.9999: 16.712 ms/op
                 existUser·p1.00:   17.269 ms/op

Iteration   2: 2.892 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.623 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.465 ms/op
                 existUser·p0.999:  7.628 ms/op
                 existUser·p0.9999: 14.202 ms/op
                 existUser·p1.00:   15.122 ms/op

Iteration   3: 2.886 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.353 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   4.207 ms/op
                 existUser·p0.999:  11.715 ms/op
                 existUser·p0.9999: 14.629 ms/op
                 existUser·p1.00:   15.024 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333227
  mean =      2.880 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2933 
    [ 1.250,  2.500) = 55197 
    [ 2.500,  3.750) = 263550 
    [ 3.750,  5.000) = 10414 
    [ 5.000,  6.250) = 610 
    [ 6.250,  7.500) = 169 
    [ 7.500,  8.750) = 77 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 66 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.353 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      3.396 ms/op
     p(95.0000) =      3.621 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      7.610 ms/op
     p(99.9900) =     14.768 ms/op
     p(99.9990) =     16.832 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.016 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.103 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.007 ms/op
Iteration   1: 2.926 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.265 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  7.938 ms/op
                 getUser·p0.9999: 13.959 ms/op
                 getUser·p1.00:   14.254 ms/op

Iteration   2: 2.954 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.552 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.383 ms/op
                 getUser·p0.95:   3.604 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  5.887 ms/op
                 getUser·p0.9999: 20.484 ms/op
                 getUser·p1.00:   21.365 ms/op

Iteration   3: 2.980 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.648 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   4.174 ms/op
                 getUser·p0.999:  6.724 ms/op
                 getUser·p0.9999: 26.256 ms/op
                 getUser·p1.00:   26.804 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 324988
  mean =      2.953 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38797 
    [ 2.500,  5.000) = 285219 
    [ 5.000,  7.500) = 730 
    [ 7.500, 10.000) = 54 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.265 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      6.865 ms/op
     p(99.9900) =     23.204 ms/op
     p(99.9990) =     26.640 ms/op
     p(99.9999) =     26.804 ms/op
    p(100.0000) =     26.804 ms/op


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
# Warmup Iteration   1: 4.842 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.946 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.834 ±(99.9%) 0.010 ms/op
Iteration   1: 3.865 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.251 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   6.554 ms/op
                 listUser·p0.999:  13.189 ms/op
                 listUser·p0.9999: 20.152 ms/op
                 listUser·p1.00:   20.644 ms/op

Iteration   2: 3.846 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.887 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.382 ms/op
                 listUser·p0.99:   6.529 ms/op
                 listUser·p0.999:  13.971 ms/op
                 listUser·p0.9999: 15.958 ms/op
                 listUser·p1.00:   16.351 ms/op

Iteration   3: 3.943 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.705 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  15.660 ms/op
                 listUser·p0.9999: 21.263 ms/op
                 listUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247300
  mean =      3.884 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4748 
    [ 2.500,  5.000) = 218792 
    [ 5.000,  7.500) = 22836 
    [ 7.500, 10.000) = 495 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 142 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.705 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.973 ms/op
     p(95.0000) =      5.505 ms/op
     p(99.0000) =      6.570 ms/op
     p(99.9000) =     14.446 ms/op
     p(99.9900) =     20.522 ms/op
     p(99.9990) =     21.498 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.348 ± 4.353  ops/ms
ClientGrpc.existUser                       thrpt       3  11.178 ± 2.105  ops/ms
ClientGrpc.getUser                         thrpt       3  10.637 ± 5.471  ops/ms
ClientGrpc.listUser                        thrpt       3   8.075 ± 2.690  ops/ms
ClientGrpc.createUser                       avgt       3   3.125 ± 0.284   ms/op
ClientGrpc.existUser                        avgt       3   2.873 ± 0.406   ms/op
ClientGrpc.getUser                          avgt       3   3.007 ± 0.814   ms/op
ClientGrpc.listUser                         avgt       3   3.923 ± 1.188   ms/op
ClientGrpc.createUser                     sample  318334   3.015 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.406           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.019           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.539           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.736           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.194           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.903           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          32.189           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.522           ms/op
ClientGrpc.existUser                      sample  333227   2.880 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.353           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.875           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.396           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.621           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.317           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.610           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.768           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.269           ms/op
ClientGrpc.getUser                        sample  324988   2.953 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.265           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.982           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.473           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.699           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.260           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.865           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.204           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.804           ms/op
ClientGrpc.listUser                       sample  247300   3.884 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.705           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.719           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.973           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.505           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.570           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.446           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.522           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.594           ms/op
