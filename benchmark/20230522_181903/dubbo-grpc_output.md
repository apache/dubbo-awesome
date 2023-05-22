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
# Warmup Iteration   1: 4.044 ops/ms
# Warmup Iteration   2: 8.953 ops/ms
# Warmup Iteration   3: 10.049 ops/ms
Iteration   1: 10.439 ops/ms
Iteration   2: 10.496 ops/ms
Iteration   3: 10.666 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.534 ±(99.9%) 2.150 ops/ms [Average]
  (min, avg, max) = (10.439, 10.534, 10.666), stdev = 0.118
  CI (99.9%): [8.384, 12.683] (assumes normal distribution)


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
# Warmup Iteration   1: 7.414 ops/ms
# Warmup Iteration   2: 10.647 ops/ms
# Warmup Iteration   3: 11.040 ops/ms
Iteration   1: 11.153 ops/ms
Iteration   2: 11.236 ops/ms
Iteration   3: 10.853 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.081 ±(99.9%) 3.676 ops/ms [Average]
  (min, avg, max) = (10.853, 11.081, 11.236), stdev = 0.201
  CI (99.9%): [7.405, 14.757] (assumes normal distribution)


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
# Warmup Iteration   1: 6.913 ops/ms
# Warmup Iteration   2: 10.177 ops/ms
# Warmup Iteration   3: 10.542 ops/ms
Iteration   1: 10.698 ops/ms
Iteration   2: 10.723 ops/ms
Iteration   3: 10.454 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.625 ±(99.9%) 2.715 ops/ms [Average]
  (min, avg, max) = (10.454, 10.625, 10.723), stdev = 0.149
  CI (99.9%): [7.910, 13.340] (assumes normal distribution)


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
# Warmup Iteration   1: 5.051 ops/ms
# Warmup Iteration   2: 7.998 ops/ms
# Warmup Iteration   3: 8.031 ops/ms
Iteration   1: 8.320 ops/ms
Iteration   2: 8.294 ops/ms
Iteration   3: 8.136 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.250 ±(99.9%) 1.818 ops/ms [Average]
  (min, avg, max) = (8.136, 8.250, 8.320), stdev = 0.100
  CI (99.9%): [6.432, 10.068] (assumes normal distribution)


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
# Warmup Iteration   1: 4.491 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.202 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.093 ±(99.9%) 0.001 ms/op
Iteration   1: 3.038 ±(99.9%) 0.003 ms/op
Iteration   2: 2.996 ±(99.9%) 0.002 ms/op
Iteration   3: 3.046 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.027 ±(99.9%) 0.485 ms/op [Average]
  (min, avg, max) = (2.996, 3.027, 3.046), stdev = 0.027
  CI (99.9%): [2.541, 3.512] (assumes normal distribution)


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
# Warmup Iteration   1: 4.057 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.007 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.949 ±(99.9%) 0.003 ms/op
Iteration   1: 2.817 ±(99.9%) 0.002 ms/op
Iteration   2: 2.859 ±(99.9%) 0.002 ms/op
Iteration   3: 2.908 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.861 ±(99.9%) 0.825 ms/op [Average]
  (min, avg, max) = (2.817, 2.861, 2.908), stdev = 0.045
  CI (99.9%): [2.036, 3.687] (assumes normal distribution)


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
# Warmup Iteration   1: 4.294 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.100 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.006 ms/op
Iteration   1: 3.032 ±(99.9%) 0.003 ms/op
Iteration   2: 3.004 ±(99.9%) 0.003 ms/op
Iteration   3: 3.051 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.029 ±(99.9%) 0.432 ms/op [Average]
  (min, avg, max) = (3.004, 3.029, 3.051), stdev = 0.024
  CI (99.9%): [2.597, 3.462] (assumes normal distribution)


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
# Warmup Iteration   1: 5.711 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.171 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.973 ±(99.9%) 0.008 ms/op
Iteration   1: 3.983 ±(99.9%) 0.017 ms/op
Iteration   2: 3.967 ±(99.9%) 0.022 ms/op
Iteration   3: 3.932 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.961 ±(99.9%) 0.480 ms/op [Average]
  (min, avg, max) = (3.932, 3.961, 3.983), stdev = 0.026
  CI (99.9%): [3.481, 4.441] (assumes normal distribution)


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
# Warmup Iteration   1: 4.386 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.169 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.006 ms/op
Iteration   1: 3.063 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.029 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  7.978 ms/op
                 createUser·p0.9999: 18.860 ms/op
                 createUser·p1.00:   19.137 ms/op

Iteration   2: 3.004 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.770 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.396 ms/op
                 createUser·p0.95:   3.568 ms/op
                 createUser·p0.99:   4.084 ms/op
                 createUser·p0.999:  6.779 ms/op
                 createUser·p0.9999: 18.252 ms/op
                 createUser·p1.00:   18.612 ms/op

Iteration   3: 3.065 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.740 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   4.421 ms/op
                 createUser·p0.999:  13.806 ms/op
                 createUser·p0.9999: 23.284 ms/op
                 createUser·p1.00:   24.281 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315221
  mean =      3.044 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17921 
    [ 2.500,  5.000) = 295750 
    [ 5.000,  7.500) = 1112 
    [ 7.500, 10.000) = 150 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.740 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      8.909 ms/op
     p(99.9900) =     22.720 ms/op
     p(99.9990) =     23.681 ms/op
     p(99.9999) =     24.281 ms/op
    p(100.0000) =     24.281 ms/op


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
# Warmup Iteration   1: 4.059 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.007 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.958 ±(99.9%) 0.005 ms/op
Iteration   1: 2.938 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.891 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   3.994 ms/op
                 existUser·p0.999:  7.734 ms/op
                 existUser·p0.9999: 13.214 ms/op
                 existUser·p1.00:   13.664 ms/op

Iteration   2: 2.927 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.763 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.551 ms/op
                 existUser·p0.99:   4.137 ms/op
                 existUser·p0.999:  7.029 ms/op
                 existUser·p0.9999: 13.292 ms/op
                 existUser·p1.00:   15.286 ms/op

Iteration   3: 2.919 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.724 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  8.326 ms/op
                 existUser·p0.9999: 24.052 ms/op
                 existUser·p1.00:   25.199 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327948
  mean =      2.928 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35816 
    [ 2.500,  5.000) = 291190 
    [ 5.000,  7.500) = 585 
    [ 7.500, 10.000) = 133 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.724 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.551 ms/op
     p(99.0000) =      4.110 ms/op
     p(99.9000) =      7.766 ms/op
     p(99.9900) =     18.858 ms/op
     p(99.9990) =     24.337 ms/op
     p(99.9999) =     25.199 ms/op
    p(100.0000) =     25.199 ms/op


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
# Warmup Iteration   1: 4.265 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.135 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.006 ms/op
Iteration   1: 3.040 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.896 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  9.361 ms/op
                 getUser·p0.9999: 15.761 ms/op
                 getUser·p1.00:   16.204 ms/op

Iteration   2: 2.995 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.563 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.669 ms/op
                 getUser·p0.999:  6.851 ms/op
                 getUser·p0.9999: 23.768 ms/op
                 getUser·p1.00:   24.052 ms/op

Iteration   3: 3.009 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.800 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.412 ms/op
                 getUser·p0.95:   3.604 ms/op
                 getUser·p0.99:   4.125 ms/op
                 getUser·p0.999:  7.709 ms/op
                 getUser·p0.9999: 22.634 ms/op
                 getUser·p1.00:   24.019 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318197
  mean =      3.015 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19234 
    [ 2.500,  5.000) = 297322 
    [ 5.000,  7.500) = 1245 
    [ 7.500, 10.000) = 197 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.563 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.674 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      7.881 ms/op
     p(99.9900) =     23.337 ms/op
     p(99.9990) =     23.980 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


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
# Warmup Iteration   1: 5.298 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.190 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.951 ±(99.9%) 0.012 ms/op
Iteration   1: 3.976 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.071 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  13.189 ms/op
                 listUser·p0.9999: 14.548 ms/op
                 listUser·p1.00:   16.613 ms/op

Iteration   2: 3.879 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.760 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.374 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  16.876 ms/op
                 listUser·p0.9999: 22.184 ms/op
                 listUser·p1.00:   24.740 ms/op

Iteration   3: 3.937 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.046 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.817 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   6.820 ms/op
                 listUser·p0.999:  15.905 ms/op
                 listUser·p0.9999: 24.244 ms/op
                 listUser·p1.00:   25.264 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244371
  mean =      3.931 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2647 
    [ 2.500,  5.000) = 220566 
    [ 5.000,  7.500) = 19964 
    [ 7.500, 10.000) = 740 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 145 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.760 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.866 ms/op
     p(95.0000) =      5.644 ms/op
     p(99.0000) =      6.849 ms/op
     p(99.9000) =     14.451 ms/op
     p(99.9900) =     23.841 ms/op
     p(99.9990) =     24.977 ms/op
     p(99.9999) =     25.264 ms/op
    p(100.0000) =     25.264 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.534 ± 2.150  ops/ms
ClientGrpc.existUser                       thrpt       3  11.081 ± 3.676  ops/ms
ClientGrpc.getUser                         thrpt       3  10.625 ± 2.715  ops/ms
ClientGrpc.listUser                        thrpt       3   8.250 ± 1.818  ops/ms
ClientGrpc.createUser                       avgt       3   3.027 ± 0.485   ms/op
ClientGrpc.existUser                        avgt       3   2.861 ± 0.825   ms/op
ClientGrpc.getUser                          avgt       3   3.029 ± 0.432   ms/op
ClientGrpc.listUser                         avgt       3   3.961 ± 0.480   ms/op
ClientGrpc.createUser                     sample  315221   3.044 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.740           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.998           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.523           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.711           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.301           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.909           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.720           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.281           ms/op
ClientGrpc.existUser                      sample  327948   2.928 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.724           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.908           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.391           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.551           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.110           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.766           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.858           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.199           ms/op
ClientGrpc.getUser                        sample  318197   3.015 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.563           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.986           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.453           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.674           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.407           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.881           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.337           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.052           ms/op
ClientGrpc.listUser                       sample  244371   3.931 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.760           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.772           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.866           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.644           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.849           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.451           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.841           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.264           ms/op
