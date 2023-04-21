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
# Warmup Iteration   1: 4.054 ops/ms
# Warmup Iteration   2: 8.829 ops/ms
# Warmup Iteration   3: 10.172 ops/ms
Iteration   1: 10.271 ops/ms
Iteration   2: 10.442 ops/ms
Iteration   3: 10.593 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.435 ±(99.9%) 2.943 ops/ms [Average]
  (min, avg, max) = (10.271, 10.435, 10.593), stdev = 0.161
  CI (99.9%): [7.493, 13.378] (assumes normal distribution)


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
# Warmup Iteration   1: 7.140 ops/ms
# Warmup Iteration   2: 10.128 ops/ms
# Warmup Iteration   3: 10.872 ops/ms
Iteration   1: 10.967 ops/ms
Iteration   2: 11.013 ops/ms
Iteration   3: 10.874 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.952 ±(99.9%) 1.292 ops/ms [Average]
  (min, avg, max) = (10.874, 10.952, 11.013), stdev = 0.071
  CI (99.9%): [9.660, 12.243] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.976 ops/ms
# Warmup Iteration   2: 9.989 ops/ms
# Warmup Iteration   3: 10.396 ops/ms
Iteration   1: 10.423 ops/ms
Iteration   2: 10.376 ops/ms
Iteration   3: 10.477 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.425 ±(99.9%) 0.923 ops/ms [Average]
  (min, avg, max) = (10.376, 10.425, 10.477), stdev = 0.051
  CI (99.9%): [9.502, 11.349] (assumes normal distribution)


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
# Warmup Iteration   1: 5.456 ops/ms
# Warmup Iteration   2: 7.237 ops/ms
# Warmup Iteration   3: 7.859 ops/ms
Iteration   1: 7.890 ops/ms
Iteration   2: 7.959 ops/ms
Iteration   3: 7.895 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.914 ±(99.9%) 0.708 ops/ms [Average]
  (min, avg, max) = (7.890, 7.914, 7.959), stdev = 0.039
  CI (99.9%): [7.207, 8.622] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.555 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.174 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.003 ms/op
Iteration   1: 2.978 ±(99.9%) 0.001 ms/op
Iteration   2: 3.052 ±(99.9%) 0.002 ms/op
Iteration   3: 3.043 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.024 ±(99.9%) 0.738 ms/op [Average]
  (min, avg, max) = (2.978, 3.024, 3.052), stdev = 0.040
  CI (99.9%): [2.286, 3.763] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.146 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.040 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.946 ±(99.9%) 0.003 ms/op
Iteration   1: 2.947 ±(99.9%) 0.003 ms/op
Iteration   2: 2.859 ±(99.9%) 0.002 ms/op
Iteration   3: 2.876 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.894 ±(99.9%) 0.846 ms/op [Average]
  (min, avg, max) = (2.859, 2.894, 2.947), stdev = 0.046
  CI (99.9%): [2.048, 3.740] (assumes normal distribution)


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
# Warmup Iteration   1: 4.248 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.129 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.004 ms/op
Iteration   1: 2.992 ±(99.9%) 0.003 ms/op
Iteration   2: 3.056 ±(99.9%) 0.002 ms/op
Iteration   3: 3.002 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.017 ±(99.9%) 0.632 ms/op [Average]
  (min, avg, max) = (2.992, 3.017, 3.056), stdev = 0.035
  CI (99.9%): [2.385, 3.648] (assumes normal distribution)


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
# Warmup Iteration   1: 5.888 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.093 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.029 ±(99.9%) 0.006 ms/op
Iteration   1: 3.962 ±(99.9%) 0.023 ms/op
Iteration   2: 3.829 ±(99.9%) 0.006 ms/op
Iteration   3: 3.961 ±(99.9%) 0.042 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.917 ±(99.9%) 1.398 ms/op [Average]
  (min, avg, max) = (3.829, 3.917, 3.962), stdev = 0.077
  CI (99.9%): [2.519, 5.315] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.522 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.156 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.121 ±(99.9%) 0.007 ms/op
Iteration   1: 3.107 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.835 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  10.270 ms/op
                 createUser·p0.9999: 16.489 ms/op
                 createUser·p1.00:   16.908 ms/op

Iteration   2: 3.117 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.859 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  7.768 ms/op
                 createUser·p0.9999: 19.439 ms/op
                 createUser·p1.00:   20.349 ms/op

Iteration   3: 3.028 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.708 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  9.011 ms/op
                 createUser·p0.9999: 23.527 ms/op
                 createUser·p1.00:   23.560 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311436
  mean =      3.083 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21272 
    [ 2.500,  5.000) = 288506 
    [ 5.000,  7.500) = 1210 
    [ 7.500, 10.000) = 140 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.708 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.863 ms/op
     p(99.0000) =      4.470 ms/op
     p(99.9000) =      9.938 ms/op
     p(99.9900) =     21.716 ms/op
     p(99.9990) =     23.560 ms/op
     p(99.9999) =     23.560 ms/op
    p(100.0000) =     23.560 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.388 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.037 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.966 ±(99.9%) 0.006 ms/op
Iteration   1: 2.920 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.561 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   4.157 ms/op
                 existUser·p0.999:  7.827 ms/op
                 existUser·p0.9999: 13.026 ms/op
                 existUser·p1.00:   13.451 ms/op

Iteration   2: 2.888 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.309 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.473 ms/op
                 existUser·p0.99:   4.006 ms/op
                 existUser·p0.999:  6.087 ms/op
                 existUser·p0.9999: 15.104 ms/op
                 existUser·p1.00:   15.385 ms/op

Iteration   3: 2.898 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.854 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.514 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  7.018 ms/op
                 existUser·p0.9999: 15.645 ms/op
                 existUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330567
  mean =      2.902 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1068 
    [ 1.250,  2.500) = 32213 
    [ 2.500,  3.750) = 288564 
    [ 3.750,  5.000) = 7832 
    [ 5.000,  6.250) = 396 
    [ 6.250,  7.500) = 264 
    [ 7.500,  8.750) = 68 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 38 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.309 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.322 ms/op
     p(95.0000) =      3.523 ms/op
     p(99.0000) =      4.145 ms/op
     p(99.9000) =      7.062 ms/op
     p(99.9900) =     15.106 ms/op
     p(99.9990) =     17.160 ms/op
     p(99.9999) =     17.400 ms/op
    p(100.0000) =     17.400 ms/op


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
# Warmup Iteration   1: 4.517 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.201 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.076 ±(99.9%) 0.008 ms/op
Iteration   1: 3.062 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.412 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  7.225 ms/op
                 getUser·p0.9999: 30.281 ms/op
                 getUser·p1.00:   31.687 ms/op

Iteration   2: 3.050 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.659 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  7.127 ms/op
                 getUser·p0.9999: 22.594 ms/op
                 getUser·p1.00:   22.970 ms/op

Iteration   3: 3.017 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.777 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.437 ms/op
                 getUser·p0.95:   3.645 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  7.856 ms/op
                 getUser·p0.9999: 24.223 ms/op
                 getUser·p1.00:   24.805 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315219
  mean =      3.043 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19832 
    [ 2.500,  5.000) = 293916 
    [ 5.000,  7.500) = 1165 
    [ 7.500, 10.000) = 114 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 96 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.412 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      7.412 ms/op
     p(99.9900) =     27.660 ms/op
     p(99.9990) =     30.704 ms/op
     p(99.9999) =     31.687 ms/op
    p(100.0000) =     31.687 ms/op


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
# Warmup Iteration   1: 5.587 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.168 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.050 ±(99.9%) 0.013 ms/op
Iteration   1: 3.999 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.528 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  21.824 ms/op
                 listUser·p0.9999: 30.048 ms/op
                 listUser·p1.00:   30.474 ms/op

Iteration   2: 4.001 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.973 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   7.315 ms/op
                 listUser·p0.999:  17.205 ms/op
                 listUser·p0.9999: 19.988 ms/op
                 listUser·p1.00:   20.218 ms/op

Iteration   3: 3.856 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.048 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.743 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  17.829 ms/op
                 listUser·p0.9999: 30.170 ms/op
                 listUser·p1.00:   30.933 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242885
  mean =      3.951 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3321 
    [ 2.500,  5.000) = 215730 
    [ 5.000,  7.500) = 22221 
    [ 7.500, 10.000) = 1009 
    [10.000, 12.500) = 207 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 19 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.528 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.981 ms/op
     p(95.0000) =      5.784 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =     18.161 ms/op
     p(99.9900) =     29.767 ms/op
     p(99.9990) =     30.900 ms/op
     p(99.9999) =     30.933 ms/op
    p(100.0000) =     30.933 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.435 ± 2.943  ops/ms
ClientGrpc.existUser                       thrpt       3  10.952 ± 1.292  ops/ms
ClientGrpc.getUser                         thrpt       3  10.425 ± 0.923  ops/ms
ClientGrpc.listUser                        thrpt       3   7.914 ± 0.708  ops/ms
ClientGrpc.createUser                       avgt       3   3.024 ± 0.738   ms/op
ClientGrpc.existUser                        avgt       3   2.894 ± 0.846   ms/op
ClientGrpc.getUser                          avgt       3   3.017 ± 0.632   ms/op
ClientGrpc.listUser                         avgt       3   3.917 ± 1.398   ms/op
ClientGrpc.createUser                     sample  311436   3.083 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.708           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.039           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.658           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.863           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.470           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.938           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.716           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.560           ms/op
ClientGrpc.existUser                      sample  330567   2.902 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.309           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.884           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.322           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.523           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.145           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.062           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.106           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.400           ms/op
ClientGrpc.getUser                        sample  315219   3.043 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.412           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.002           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.543           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.760           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.412           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.660           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          31.687           ms/op
ClientGrpc.listUser                       sample  242885   3.951 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.528           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.772           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.981           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.784           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.037           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.161           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.767           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.933           ms/op
