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
# Warmup Iteration   1: 4.394 ops/ms
# Warmup Iteration   2: 9.253 ops/ms
# Warmup Iteration   3: 10.083 ops/ms
Iteration   1: 10.196 ops/ms
Iteration   2: 10.337 ops/ms
Iteration   3: 10.119 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.218 ±(99.9%) 2.012 ops/ms [Average]
  (min, avg, max) = (10.119, 10.218, 10.337), stdev = 0.110
  CI (99.9%): [8.206, 12.229] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.840 ops/ms
# Warmup Iteration   2: 10.944 ops/ms
# Warmup Iteration   3: 11.096 ops/ms
Iteration   1: 10.745 ops/ms
Iteration   2: 10.917 ops/ms
Iteration   3: 11.237 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.966 ±(99.9%) 4.547 ops/ms [Average]
  (min, avg, max) = (10.745, 10.966, 11.237), stdev = 0.249
  CI (99.9%): [6.419, 15.513] (assumes normal distribution)


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
# Warmup Iteration   1: 7.622 ops/ms
# Warmup Iteration   2: 10.189 ops/ms
# Warmup Iteration   3: 10.286 ops/ms
Iteration   1: 10.448 ops/ms
Iteration   2: 10.500 ops/ms
Iteration   3: 10.631 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.526 ±(99.9%) 1.724 ops/ms [Average]
  (min, avg, max) = (10.448, 10.526, 10.631), stdev = 0.094
  CI (99.9%): [8.803, 12.250] (assumes normal distribution)


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
# Warmup Iteration   1: 6.356 ops/ms
# Warmup Iteration   2: 7.565 ops/ms
# Warmup Iteration   3: 8.082 ops/ms
Iteration   1: 8.264 ops/ms
Iteration   2: 8.024 ops/ms
Iteration   3: 8.143 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.143 ±(99.9%) 2.191 ops/ms [Average]
  (min, avg, max) = (8.024, 8.143, 8.264), stdev = 0.120
  CI (99.9%): [5.953, 10.334] (assumes normal distribution)


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
# Warmup Iteration   1: 4.083 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.118 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.002 ms/op
Iteration   1: 3.121 ±(99.9%) 0.004 ms/op
Iteration   2: 2.951 ±(99.9%) 0.003 ms/op
Iteration   3: 3.096 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.056 ±(99.9%) 1.678 ms/op [Average]
  (min, avg, max) = (2.951, 3.056, 3.121), stdev = 0.092
  CI (99.9%): [1.378, 4.734] (assumes normal distribution)


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
# Warmup Iteration   1: 3.932 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.955 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.979 ±(99.9%) 0.003 ms/op
Iteration   1: 2.971 ±(99.9%) 0.003 ms/op
Iteration   2: 3.027 ±(99.9%) 0.002 ms/op
Iteration   3: 2.950 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.983 ±(99.9%) 0.726 ms/op [Average]
  (min, avg, max) = (2.950, 2.983, 3.027), stdev = 0.040
  CI (99.9%): [2.257, 3.708] (assumes normal distribution)


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
# Warmup Iteration   1: 4.020 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.136 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.003 ms/op
Iteration   1: 3.105 ±(99.9%) 0.002 ms/op
Iteration   2: 2.993 ±(99.9%) 0.001 ms/op
Iteration   3: 3.070 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.056 ±(99.9%) 1.051 ms/op [Average]
  (min, avg, max) = (2.993, 3.056, 3.105), stdev = 0.058
  CI (99.9%): [2.005, 4.107] (assumes normal distribution)


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
# Warmup Iteration   1: 4.142 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.154 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.013 ±(99.9%) 0.009 ms/op
Iteration   1: 3.945 ±(99.9%) 0.023 ms/op
Iteration   2: 3.866 ±(99.9%) 0.032 ms/op
Iteration   3: 4.096 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.969 ±(99.9%) 2.133 ms/op [Average]
  (min, avg, max) = (3.866, 3.969, 4.096), stdev = 0.117
  CI (99.9%): [1.837, 6.102] (assumes normal distribution)


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
# Warmup Iteration   1: 3.915 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.961 ±(99.9%) 0.007 ms/op
Iteration   1: 3.127 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.663 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.817 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  6.431 ms/op
                 createUser·p0.9999: 16.511 ms/op
                 createUser·p1.00:   17.302 ms/op

Iteration   2: 3.067 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.474 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.116 ms/op
                 createUser·p0.999:  9.765 ms/op
                 createUser·p0.9999: 23.907 ms/op
                 createUser·p1.00:   24.347 ms/op

Iteration   3: 3.089 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.649 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   4.166 ms/op
                 createUser·p0.999:  10.699 ms/op
                 createUser·p0.9999: 20.096 ms/op
                 createUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310065
  mean =      3.094 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25825 
    [ 2.500,  5.000) = 283084 
    [ 5.000,  7.500) = 667 
    [ 7.500, 10.000) = 177 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.474 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =     10.189 ms/op
     p(99.9900) =     22.801 ms/op
     p(99.9990) =     24.245 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


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
# Warmup Iteration   1: 3.839 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.133 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.998 ±(99.9%) 0.006 ms/op
Iteration   1: 3.016 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.727 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.699 ms/op
                 existUser·p0.95:   3.863 ms/op
                 existUser·p0.99:   4.153 ms/op
                 existUser·p0.999:  5.554 ms/op
                 existUser·p0.9999: 12.072 ms/op
                 existUser·p1.00:   12.370 ms/op

Iteration   2: 2.989 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.831 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.633 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.104 ms/op
                 existUser·p0.999:  7.250 ms/op
                 existUser·p0.9999: 17.639 ms/op
                 existUser·p1.00:   17.924 ms/op

Iteration   3: 2.997 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.762 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  8.161 ms/op
                 existUser·p0.9999: 14.385 ms/op
                 existUser·p1.00:   14.860 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 319785
  mean =      3.001 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2074 
    [ 1.250,  2.500) = 40133 
    [ 2.500,  3.750) = 255599 
    [ 3.750,  5.000) = 21110 
    [ 5.000,  6.250) = 457 
    [ 6.250,  7.500) = 159 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 72 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.727 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      4.157 ms/op
     p(99.9000) =      7.071 ms/op
     p(99.9900) =     16.876 ms/op
     p(99.9990) =     17.787 ms/op
     p(99.9999) =     17.924 ms/op
    p(100.0000) =     17.924 ms/op


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
# Warmup Iteration   1: 3.699 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.089 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.977 ±(99.9%) 0.006 ms/op
Iteration   1: 3.081 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.461 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  6.809 ms/op
                 getUser·p0.9999: 21.090 ms/op
                 getUser·p1.00:   21.529 ms/op

Iteration   2: 3.047 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.638 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  8.847 ms/op
                 getUser·p0.9999: 18.792 ms/op
                 getUser·p1.00:   19.333 ms/op

Iteration   3: 3.054 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.700 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.858 ms/op
                 getUser·p0.99:   4.202 ms/op
                 getUser·p0.999:  6.528 ms/op
                 getUser·p0.9999: 18.680 ms/op
                 getUser·p1.00:   19.137 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313743
  mean =      3.061 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24734 
    [ 2.500,  5.000) = 287909 
    [ 5.000,  7.500) = 768 
    [ 7.500, 10.000) = 187 
    [10.000, 12.500) = 13 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.461 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      7.670 ms/op
     p(99.9900) =     20.271 ms/op
     p(99.9990) =     21.393 ms/op
     p(99.9999) =     21.529 ms/op
    p(100.0000) =     21.529 ms/op


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
# Warmup Iteration   1: 4.329 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.345 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.055 ±(99.9%) 0.011 ms/op
Iteration   1: 4.040 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.210 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  12.124 ms/op
                 listUser·p0.9999: 16.025 ms/op
                 listUser·p1.00:   16.433 ms/op

Iteration   2: 4.034 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.122 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  14.615 ms/op
                 listUser·p0.9999: 17.243 ms/op
                 listUser·p1.00:   17.793 ms/op

Iteration   3: 3.954 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.014 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  15.024 ms/op
                 listUser·p0.9999: 17.262 ms/op
                 listUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239423
  mean =      4.009 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 26 
    [ 1.250,  2.500) = 3236 
    [ 2.500,  3.750) = 94964 
    [ 3.750,  5.000) = 116686 
    [ 5.000,  6.250) = 18160 
    [ 6.250,  7.500) = 4911 
    [ 7.500,  8.750) = 724 
    [ 8.750, 10.000) = 217 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 133 
    [15.000, 16.250) = 109 
    [16.250, 17.500) = 57 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.014 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      5.030 ms/op
     p(95.0000) =      5.759 ms/op
     p(99.0000) =      6.988 ms/op
     p(99.9000) =     14.533 ms/op
     p(99.9900) =     16.978 ms/op
     p(99.9990) =     18.791 ms/op
     p(99.9999) =     19.464 ms/op
    p(100.0000) =     19.464 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.218 ± 2.012  ops/ms
ClientGrpc.existUser                       thrpt       3  10.966 ± 4.547  ops/ms
ClientGrpc.getUser                         thrpt       3  10.526 ± 1.724  ops/ms
ClientGrpc.listUser                        thrpt       3   8.143 ± 2.191  ops/ms
ClientGrpc.createUser                       avgt       3   3.056 ± 1.678   ms/op
ClientGrpc.existUser                        avgt       3   2.983 ± 0.726   ms/op
ClientGrpc.getUser                          avgt       3   3.056 ± 1.051   ms/op
ClientGrpc.listUser                         avgt       3   3.969 ± 2.133   ms/op
ClientGrpc.createUser                     sample  310065   3.094 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.474           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.068           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.707           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.879           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.227           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.189           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.801           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.347           ms/op
ClientGrpc.existUser                      sample  319785   3.001 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.727           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.986           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.654           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.822           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.157           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.071           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.876           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.924           ms/op
ClientGrpc.getUser                        sample  313743   3.061 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.461           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.658           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.867           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.252           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.670           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.271           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.529           ms/op
ClientGrpc.listUser                       sample  239423   4.009 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.014           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.850           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.030           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.759           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.988           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.533           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          16.978           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.464           ms/op
