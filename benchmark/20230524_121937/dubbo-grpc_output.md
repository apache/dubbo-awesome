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
# Warmup Iteration   1: 3.584 ops/ms
# Warmup Iteration   2: 8.306 ops/ms
# Warmup Iteration   3: 9.744 ops/ms
Iteration   1: 10.193 ops/ms
Iteration   2: 10.375 ops/ms
Iteration   3: 10.244 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.271 ±(99.9%) 1.715 ops/ms [Average]
  (min, avg, max) = (10.193, 10.271, 10.375), stdev = 0.094
  CI (99.9%): [8.556, 11.985] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.194 ops/ms
# Warmup Iteration   2: 10.712 ops/ms
# Warmup Iteration   3: 10.845 ops/ms
Iteration   1: 11.114 ops/ms
Iteration   2: 10.986 ops/ms
Iteration   3: 10.963 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.021 ±(99.9%) 1.480 ops/ms [Average]
  (min, avg, max) = (10.963, 11.021, 11.114), stdev = 0.081
  CI (99.9%): [9.541, 12.501] (assumes normal distribution)


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
# Warmup Iteration   1: 6.361 ops/ms
# Warmup Iteration   2: 9.780 ops/ms
# Warmup Iteration   3: 10.375 ops/ms
Iteration   1: 10.449 ops/ms
Iteration   2: 10.451 ops/ms
Iteration   3: 10.407 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.435 ±(99.9%) 0.455 ops/ms [Average]
  (min, avg, max) = (10.407, 10.435, 10.451), stdev = 0.025
  CI (99.9%): [9.980, 10.891] (assumes normal distribution)


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
# Warmup Iteration   1: 5.394 ops/ms
# Warmup Iteration   2: 7.496 ops/ms
# Warmup Iteration   3: 7.606 ops/ms
Iteration   1: 7.849 ops/ms
Iteration   2: 7.888 ops/ms
Iteration   3: 7.808 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.848 ±(99.9%) 0.730 ops/ms [Average]
  (min, avg, max) = (7.808, 7.848, 7.888), stdev = 0.040
  CI (99.9%): [7.118, 8.578] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.657 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.222 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.108 ±(99.9%) 0.002 ms/op
Iteration   1: 3.093 ±(99.9%) 0.002 ms/op
Iteration   2: 3.022 ±(99.9%) 0.003 ms/op
Iteration   3: 3.145 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.086 ±(99.9%) 1.126 ms/op [Average]
  (min, avg, max) = (3.022, 3.086, 3.145), stdev = 0.062
  CI (99.9%): [1.960, 4.213] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.886 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.206 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.002 ms/op
Iteration   1: 2.990 ±(99.9%) 0.003 ms/op
Iteration   2: 2.944 ±(99.9%) 0.002 ms/op
Iteration   3: 2.993 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.976 ±(99.9%) 0.493 ms/op [Average]
  (min, avg, max) = (2.944, 2.976, 2.993), stdev = 0.027
  CI (99.9%): [2.483, 3.469] (assumes normal distribution)


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
# Warmup Iteration   1: 4.497 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.240 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.135 ±(99.9%) 0.003 ms/op
Iteration   1: 3.076 ±(99.9%) 0.002 ms/op
Iteration   2: 3.055 ±(99.9%) 0.003 ms/op
Iteration   3: 3.141 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.091 ±(99.9%) 0.820 ms/op [Average]
  (min, avg, max) = (3.055, 3.091, 3.141), stdev = 0.045
  CI (99.9%): [2.270, 3.911] (assumes normal distribution)


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
# Warmup Iteration   1: 5.807 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.231 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.030 ±(99.9%) 0.009 ms/op
Iteration   1: 3.956 ±(99.9%) 0.005 ms/op
Iteration   2: 4.033 ±(99.9%) 0.015 ms/op
Iteration   3: 4.021 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.003 ±(99.9%) 0.761 ms/op [Average]
  (min, avg, max) = (3.956, 4.003, 4.033), stdev = 0.042
  CI (99.9%): [3.243, 4.764] (assumes normal distribution)


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
# Warmup Iteration   1: 4.483 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.205 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.142 ±(99.9%) 0.007 ms/op
Iteration   1: 3.115 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.950 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   3.981 ms/op
                 createUser·p0.99:   5.140 ms/op
                 createUser·p0.999:  12.337 ms/op
                 createUser·p0.9999: 20.134 ms/op
                 createUser·p1.00:   20.414 ms/op

Iteration   2: 3.157 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.675 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   4.039 ms/op
                 createUser·p0.99:   5.480 ms/op
                 createUser·p0.999:  10.695 ms/op
                 createUser·p0.9999: 20.152 ms/op
                 createUser·p1.00:   20.152 ms/op

Iteration   3: 3.128 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.871 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   5.161 ms/op
                 createUser·p0.999:  9.621 ms/op
                 createUser·p0.9999: 19.974 ms/op
                 createUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 306273
  mean =      3.133 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16290 
    [ 2.500,  5.000) = 286289 
    [ 5.000,  7.500) = 2792 
    [ 7.500, 10.000) = 555 
    [10.000, 12.500) = 111 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.675 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      5.259 ms/op
     p(99.9000) =     10.486 ms/op
     p(99.9900) =     20.152 ms/op
     p(99.9990) =     20.836 ms/op
     p(99.9999) =     20.972 ms/op
    p(100.0000) =     20.972 ms/op


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
# Warmup Iteration   1: 4.219 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.128 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.006 ms/op
Iteration   1: 2.973 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.720 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  10.256 ms/op
                 existUser·p0.9999: 19.546 ms/op
                 existUser·p1.00:   20.021 ms/op

Iteration   2: 2.897 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.888 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.473 ms/op
                 existUser·p0.999:  7.463 ms/op
                 existUser·p0.9999: 22.512 ms/op
                 existUser·p1.00:   23.134 ms/op

Iteration   3: 2.917 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.729 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  10.208 ms/op
                 existUser·p0.9999: 17.368 ms/op
                 existUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327513
  mean =      2.928 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36722 
    [ 2.500,  5.000) = 289000 
    [ 5.000,  7.500) = 1274 
    [ 7.500, 10.000) = 213 
    [10.000, 12.500) = 136 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.720 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.613 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      9.748 ms/op
     p(99.9900) =     20.404 ms/op
     p(99.9990) =     23.051 ms/op
     p(99.9999) =     23.134 ms/op
    p(100.0000) =     23.134 ms/op


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
# Warmup Iteration   1: 4.638 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.225 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.109 ±(99.9%) 0.007 ms/op
Iteration   1: 3.178 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.841 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   4.121 ms/op
                 getUser·p0.99:   5.710 ms/op
                 getUser·p0.999:  10.093 ms/op
                 getUser·p0.9999: 13.105 ms/op
                 getUser·p1.00:   13.566 ms/op

Iteration   2: 3.126 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.725 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   3.998 ms/op
                 getUser·p0.99:   5.439 ms/op
                 getUser·p0.999:  9.847 ms/op
                 getUser·p0.9999: 15.554 ms/op
                 getUser·p1.00:   15.974 ms/op

Iteration   3: 3.065 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.839 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   4.907 ms/op
                 getUser·p0.999:  7.501 ms/op
                 getUser·p0.9999: 17.859 ms/op
                 getUser·p1.00:   18.153 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 307293
  mean =      3.122 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 616 
    [ 1.250,  2.500) = 17451 
    [ 2.500,  3.750) = 261982 
    [ 3.750,  5.000) = 22974 
    [ 5.000,  6.250) = 2591 
    [ 6.250,  7.500) = 878 
    [ 7.500,  8.750) = 376 
    [ 8.750, 10.000) = 185 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.725 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      5.325 ms/op
     p(99.9000) =      9.503 ms/op
     p(99.9900) =     16.381 ms/op
     p(99.9990) =     18.013 ms/op
     p(99.9999) =     18.153 ms/op
    p(100.0000) =     18.153 ms/op


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
# Warmup Iteration   1: 6.034 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.135 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.107 ±(99.9%) 0.012 ms/op
Iteration   1: 4.199 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.462 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   5.571 ms/op
                 listUser·p0.95:   6.332 ms/op
                 listUser·p0.99:   8.126 ms/op
                 listUser·p0.999:  14.233 ms/op
                 listUser·p0.9999: 17.924 ms/op
                 listUser·p1.00:   18.481 ms/op

Iteration   2: 4.138 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.225 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   7.406 ms/op
                 listUser·p0.999:  14.385 ms/op
                 listUser·p0.9999: 17.360 ms/op
                 listUser·p1.00:   17.990 ms/op

Iteration   3: 3.957 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.264 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   7.168 ms/op
                 listUser·p0.999:  15.139 ms/op
                 listUser·p0.9999: 19.726 ms/op
                 listUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234306
  mean =      4.095 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2101 
    [ 2.500,  5.000) = 203027 
    [ 5.000,  7.500) = 26660 
    [ 7.500, 10.000) = 2034 
    [10.000, 12.500) = 136 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 144 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.225 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      5.235 ms/op
     p(95.0000) =      5.988 ms/op
     p(99.0000) =      7.578 ms/op
     p(99.9000) =     14.512 ms/op
     p(99.9900) =     18.991 ms/op
     p(99.9990) =     20.086 ms/op
     p(99.9999) =     20.218 ms/op
    p(100.0000) =     20.218 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.271 ± 1.715  ops/ms
ClientGrpc.existUser                       thrpt       3  11.021 ± 1.480  ops/ms
ClientGrpc.getUser                         thrpt       3  10.435 ± 0.455  ops/ms
ClientGrpc.listUser                        thrpt       3   7.848 ± 0.730  ops/ms
ClientGrpc.createUser                       avgt       3   3.086 ± 1.126   ms/op
ClientGrpc.existUser                        avgt       3   2.976 ± 0.493   ms/op
ClientGrpc.getUser                          avgt       3   3.091 ± 0.820   ms/op
ClientGrpc.listUser                         avgt       3   4.003 ± 0.761   ms/op
ClientGrpc.createUser                     sample  306273   3.133 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.675           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.068           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.666           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.953           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.259           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.486           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.152           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.972           ms/op
ClientGrpc.existUser                      sample  327513   2.928 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.720           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.908           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.391           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.613           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.489           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.748           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.404           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.134           ms/op
ClientGrpc.getUser                        sample  307293   3.122 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.725           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.060           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.703           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.994           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.325           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.503           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.381           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.153           ms/op
ClientGrpc.listUser                       sample  234306   4.095 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.225           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.887           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.235           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.988           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.578           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.512           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.991           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.218           ms/op
