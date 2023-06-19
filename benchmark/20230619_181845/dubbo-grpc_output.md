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
# Warmup Iteration   1: 4.572 ops/ms
# Warmup Iteration   2: 9.379 ops/ms
# Warmup Iteration   3: 10.121 ops/ms
Iteration   1: 10.499 ops/ms
Iteration   2: 10.556 ops/ms
Iteration   3: 10.616 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.557 ±(99.9%) 1.068 ops/ms [Average]
  (min, avg, max) = (10.499, 10.557, 10.616), stdev = 0.059
  CI (99.9%): [9.489, 11.625] (assumes normal distribution)


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
# Warmup Iteration   1: 7.760 ops/ms
# Warmup Iteration   2: 11.136 ops/ms
# Warmup Iteration   3: 11.093 ops/ms
Iteration   1: 11.289 ops/ms
Iteration   2: 11.482 ops/ms
Iteration   3: 11.686 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.485 ±(99.9%) 3.626 ops/ms [Average]
  (min, avg, max) = (11.289, 11.485, 11.686), stdev = 0.199
  CI (99.9%): [7.859, 15.112] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.266 ops/ms
# Warmup Iteration   2: 10.309 ops/ms
# Warmup Iteration   3: 10.668 ops/ms
Iteration   1: 10.727 ops/ms
Iteration   2: 10.889 ops/ms
Iteration   3: 10.575 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.730 ±(99.9%) 2.863 ops/ms [Average]
  (min, avg, max) = (10.575, 10.730, 10.889), stdev = 0.157
  CI (99.9%): [7.867, 13.594] (assumes normal distribution)


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
# Warmup Iteration   1: 6.938 ops/ms
# Warmup Iteration   2: 8.574 ops/ms
# Warmup Iteration   3: 8.417 ops/ms
Iteration   1: 8.384 ops/ms
Iteration   2: 8.396 ops/ms
Iteration   3: 8.600 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.460 ±(99.9%) 2.209 ops/ms [Average]
  (min, avg, max) = (8.384, 8.460, 8.600), stdev = 0.121
  CI (99.9%): [6.251, 10.669] (assumes normal distribution)


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
# Warmup Iteration   1: 4.038 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.120 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 2.985 ±(99.9%) 0.003 ms/op
Iteration   1: 3.027 ±(99.9%) 0.003 ms/op
Iteration   2: 2.992 ±(99.9%) 0.002 ms/op
Iteration   3: 2.968 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.996 ±(99.9%) 0.536 ms/op [Average]
  (min, avg, max) = (2.968, 2.996, 3.027), stdev = 0.029
  CI (99.9%): [2.459, 3.532] (assumes normal distribution)


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
# Warmup Iteration   1: 3.262 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.960 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.865 ±(99.9%) 0.003 ms/op
Iteration   1: 2.766 ±(99.9%) 0.003 ms/op
Iteration   2: 2.897 ±(99.9%) 0.005 ms/op
Iteration   3: 2.858 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.841 ±(99.9%) 1.233 ms/op [Average]
  (min, avg, max) = (2.766, 2.841, 2.897), stdev = 0.068
  CI (99.9%): [1.608, 4.073] (assumes normal distribution)


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
# Warmup Iteration   1: 4.105 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.084 ±(99.9%) 0.003 ms/op
Iteration   1: 2.983 ±(99.9%) 0.002 ms/op
Iteration   2: 2.950 ±(99.9%) 0.003 ms/op
Iteration   3: 2.960 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.964 ±(99.9%) 0.309 ms/op [Average]
  (min, avg, max) = (2.950, 2.964, 2.983), stdev = 0.017
  CI (99.9%): [2.655, 3.274] (assumes normal distribution)


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
# Warmup Iteration   1: 4.390 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.832 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.853 ±(99.9%) 0.024 ms/op
Iteration   1: 3.836 ±(99.9%) 0.030 ms/op
Iteration   2: 3.791 ±(99.9%) 0.018 ms/op
Iteration   3: 3.755 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.794 ±(99.9%) 0.738 ms/op [Average]
  (min, avg, max) = (3.755, 3.794, 3.836), stdev = 0.040
  CI (99.9%): [3.056, 4.532] (assumes normal distribution)


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
# Warmup Iteration   1: 4.044 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.166 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.979 ±(99.9%) 0.009 ms/op
Iteration   1: 3.027 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.640 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.859 ms/op
                 createUser·p0.99:   4.714 ms/op
                 createUser·p0.999:  8.782 ms/op
                 createUser·p0.9999: 26.687 ms/op
                 createUser·p1.00:   27.165 ms/op

Iteration   2: 3.012 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.749 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.441 ms/op
                 createUser·p0.95:   3.707 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  7.579 ms/op
                 createUser·p0.9999: 20.611 ms/op
                 createUser·p1.00:   21.004 ms/op

Iteration   3: 2.965 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.659 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.674 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  7.414 ms/op
                 createUser·p0.9999: 21.627 ms/op
                 createUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319795
  mean =      3.001 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25835 
    [ 2.500,  5.000) = 292283 
    [ 5.000,  7.500) = 1312 
    [ 7.500, 10.000) = 156 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.640 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =      7.807 ms/op
     p(99.9900) =     25.921 ms/op
     p(99.9990) =     27.021 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


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
# Warmup Iteration   1: 3.537 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.998 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.885 ±(99.9%) 0.006 ms/op
Iteration   1: 2.903 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.522 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.604 ms/op
                 existUser·p0.999:  7.904 ms/op
                 existUser·p0.9999: 20.021 ms/op
                 existUser·p1.00:   20.480 ms/op

Iteration   2: 2.888 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.676 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  8.487 ms/op
                 existUser·p0.9999: 13.892 ms/op
                 existUser·p1.00:   14.926 ms/op

Iteration   3: 2.917 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.683 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  7.347 ms/op
                 existUser·p0.9999: 14.534 ms/op
                 existUser·p1.00:   16.220 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330595
  mean =      2.903 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46728 
    [ 2.500,  5.000) = 282461 
    [ 5.000,  7.500) = 1014 
    [ 7.500, 10.000) = 218 
    [10.000, 12.500) = 14 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.522 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.658 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      7.830 ms/op
     p(99.9900) =     16.204 ms/op
     p(99.9990) =     20.404 ms/op
     p(99.9999) =     20.480 ms/op
    p(100.0000) =     20.480 ms/op


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
# Warmup Iteration   1: 3.785 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.213 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.033 ±(99.9%) 0.006 ms/op
Iteration   1: 3.089 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.798 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  8.129 ms/op
                 getUser·p0.9999: 13.248 ms/op
                 getUser·p1.00:   13.861 ms/op

Iteration   2: 2.996 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.699 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.416 ms/op
                 getUser·p0.95:   3.572 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  7.907 ms/op
                 getUser·p0.9999: 12.883 ms/op
                 getUser·p1.00:   13.074 ms/op

Iteration   3: 3.079 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.717 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  7.201 ms/op
                 getUser·p0.9999: 15.673 ms/op
                 getUser·p1.00:   16.089 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314312
  mean =      3.054 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 683 
    [ 1.250,  2.500) = 18229 
    [ 2.500,  3.750) = 279533 
    [ 3.750,  5.000) = 14443 
    [ 5.000,  6.250) = 764 
    [ 6.250,  7.500) = 323 
    [ 7.500,  8.750) = 76 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.699 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      7.635 ms/op
     p(99.9900) =     15.076 ms/op
     p(99.9990) =     15.951 ms/op
     p(99.9999) =     16.089 ms/op
    p(100.0000) =     16.089 ms/op


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
# Warmup Iteration   1: 4.754 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.971 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.914 ±(99.9%) 0.010 ms/op
Iteration   1: 3.910 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.057 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  12.173 ms/op
                 listUser·p0.9999: 20.972 ms/op
                 listUser·p1.00:   21.496 ms/op

Iteration   2: 3.763 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.638 ms/op
                 listUser·p0.50:   3.609 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  14.615 ms/op
                 listUser·p0.9999: 28.082 ms/op
                 listUser·p1.00:   28.803 ms/op

Iteration   3: 3.824 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.112 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.480 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  14.537 ms/op
                 listUser·p0.9999: 16.851 ms/op
                 listUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 250534
  mean =      3.831 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5489 
    [ 2.500,  5.000) = 223567 
    [ 5.000,  7.500) = 20147 
    [ 7.500, 10.000) = 834 
    [10.000, 12.500) = 152 
    [12.500, 15.000) = 136 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.638 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.841 ms/op
     p(95.0000) =      5.579 ms/op
     p(99.0000) =      6.775 ms/op
     p(99.9000) =     14.172 ms/op
     p(99.9900) =     26.737 ms/op
     p(99.9990) =     28.359 ms/op
     p(99.9999) =     28.803 ms/op
    p(100.0000) =     28.803 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.557 ± 1.068  ops/ms
ClientGrpc.existUser                       thrpt       3  11.485 ± 3.626  ops/ms
ClientGrpc.getUser                         thrpt       3  10.730 ± 2.863  ops/ms
ClientGrpc.listUser                        thrpt       3   8.460 ± 2.209  ops/ms
ClientGrpc.createUser                       avgt       3   2.996 ± 0.536   ms/op
ClientGrpc.existUser                        avgt       3   2.841 ± 1.233   ms/op
ClientGrpc.getUser                          avgt       3   2.964 ± 0.309   ms/op
ClientGrpc.listUser                         avgt       3   3.794 ± 0.738   ms/op
ClientGrpc.createUser                     sample  319795   3.001 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.640           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.986           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.494           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.756           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.522           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.807           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.921           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.165           ms/op
ClientGrpc.existUser                      sample  330595   2.903 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.522           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.888           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.457           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.658           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.489           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.830           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.204           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.480           ms/op
ClientGrpc.getUser                        sample  314312   3.054 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.699           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.035           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.555           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.752           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.407           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.635           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.076           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.089           ms/op
ClientGrpc.listUser                       sample  250534   3.831 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.638           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.686           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.841           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.579           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.775           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.172           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.737           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.803           ms/op
