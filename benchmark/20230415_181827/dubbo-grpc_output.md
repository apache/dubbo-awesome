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
# Warmup Iteration   1: 4.354 ops/ms
# Warmup Iteration   2: 9.080 ops/ms
# Warmup Iteration   3: 10.161 ops/ms
Iteration   1: 10.523 ops/ms
Iteration   2: 10.491 ops/ms
Iteration   3: 10.574 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.530 ±(99.9%) 0.764 ops/ms [Average]
  (min, avg, max) = (10.491, 10.530, 10.574), stdev = 0.042
  CI (99.9%): [9.766, 11.294] (assumes normal distribution)


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
# Warmup Iteration   1: 7.797 ops/ms
# Warmup Iteration   2: 10.936 ops/ms
# Warmup Iteration   3: 11.164 ops/ms
Iteration   1: 11.299 ops/ms
Iteration   2: 11.412 ops/ms
Iteration   3: 11.070 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.260 ±(99.9%) 3.178 ops/ms [Average]
  (min, avg, max) = (11.070, 11.260, 11.412), stdev = 0.174
  CI (99.9%): [8.082, 14.439] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.946 ops/ms
# Warmup Iteration   2: 10.126 ops/ms
# Warmup Iteration   3: 10.429 ops/ms
Iteration   1: 10.503 ops/ms
Iteration   2: 10.726 ops/ms
Iteration   3: 10.663 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.631 ±(99.9%) 2.098 ops/ms [Average]
  (min, avg, max) = (10.503, 10.631, 10.726), stdev = 0.115
  CI (99.9%): [8.533, 12.728] (assumes normal distribution)


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
# Warmup Iteration   1: 5.867 ops/ms
# Warmup Iteration   2: 7.972 ops/ms
# Warmup Iteration   3: 8.218 ops/ms
Iteration   1: 8.204 ops/ms
Iteration   2: 8.185 ops/ms
Iteration   3: 8.453 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.281 ±(99.9%) 2.728 ops/ms [Average]
  (min, avg, max) = (8.185, 8.281, 8.453), stdev = 0.150
  CI (99.9%): [5.552, 11.009] (assumes normal distribution)


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
# Warmup Iteration   1: 4.342 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.131 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.002 ms/op
Iteration   1: 3.058 ±(99.9%) 0.003 ms/op
Iteration   2: 3.052 ±(99.9%) 0.004 ms/op
Iteration   3: 2.999 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.036 ±(99.9%) 0.594 ms/op [Average]
  (min, avg, max) = (2.999, 3.036, 3.058), stdev = 0.033
  CI (99.9%): [2.442, 3.631] (assumes normal distribution)


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
# Warmup Iteration   1: 3.997 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.011 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.881 ±(99.9%) 0.003 ms/op
Iteration   1: 2.870 ±(99.9%) 0.003 ms/op
Iteration   2: 2.896 ±(99.9%) 0.002 ms/op
Iteration   3: 2.874 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.880 ±(99.9%) 0.258 ms/op [Average]
  (min, avg, max) = (2.870, 2.880, 2.896), stdev = 0.014
  CI (99.9%): [2.622, 3.138] (assumes normal distribution)


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
# Warmup Iteration   1: 4.196 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.995 ±(99.9%) 0.002 ms/op
Iteration   1: 3.020 ±(99.9%) 0.003 ms/op
Iteration   2: 3.024 ±(99.9%) 0.003 ms/op
Iteration   3: 2.954 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.999 ±(99.9%) 0.720 ms/op [Average]
  (min, avg, max) = (2.954, 2.999, 3.024), stdev = 0.039
  CI (99.9%): [2.279, 3.719] (assumes normal distribution)


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
# Warmup Iteration   1: 5.314 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.001 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 3.926 ±(99.9%) 0.020 ms/op
Iteration   1: 3.891 ±(99.9%) 0.015 ms/op
Iteration   2: 3.917 ±(99.9%) 0.024 ms/op
Iteration   3: 3.849 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.885 ±(99.9%) 0.628 ms/op [Average]
  (min, avg, max) = (3.849, 3.885, 3.917), stdev = 0.034
  CI (99.9%): [3.258, 4.513] (assumes normal distribution)


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
# Warmup Iteration   1: 4.242 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.144 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.006 ms/op
Iteration   1: 3.019 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.640 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.547 ms/op
                 createUser·p0.999:  9.539 ms/op
                 createUser·p0.9999: 20.034 ms/op
                 createUser·p1.00:   20.152 ms/op

Iteration   2: 3.059 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.703 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  6.836 ms/op
                 createUser·p0.9999: 25.069 ms/op
                 createUser·p1.00:   25.494 ms/op

Iteration   3: 3.055 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.586 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  7.563 ms/op
                 createUser·p0.9999: 17.203 ms/op
                 createUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315590
  mean =      3.044 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25782 
    [ 2.500,  5.000) = 288350 
    [ 5.000,  7.500) = 1107 
    [ 7.500, 10.000) = 121 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.586 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =      7.784 ms/op
     p(99.9900) =     24.193 ms/op
     p(99.9990) =     25.385 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


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
# Warmup Iteration   1: 4.076 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.027 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.867 ±(99.9%) 0.006 ms/op
Iteration   1: 2.917 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.796 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  6.687 ms/op
                 existUser·p0.9999: 12.127 ms/op
                 existUser·p1.00:   12.583 ms/op

Iteration   2: 2.888 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.920 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.240 ms/op
                 existUser·p0.95:   3.432 ms/op
                 existUser·p0.99:   3.879 ms/op
                 existUser·p0.999:  6.374 ms/op
                 existUser·p0.9999: 22.836 ms/op
                 existUser·p1.00:   23.265 ms/op

Iteration   3: 2.873 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.741 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  9.454 ms/op
                 existUser·p0.9999: 16.092 ms/op
                 existUser·p1.00:   16.581 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331856
  mean =      2.892 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41042 
    [ 2.500,  5.000) = 289734 
    [ 5.000,  7.500) = 814 
    [ 7.500, 10.000) = 57 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.741 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      3.334 ms/op
     p(95.0000) =      3.568 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      6.963 ms/op
     p(99.9900) =     16.568 ms/op
     p(99.9990) =     23.146 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


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
# Warmup Iteration   1: 4.348 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.141 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.005 ms/op
Iteration   1: 3.018 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.826 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.407 ms/op
                 getUser·p0.999:  8.200 ms/op
                 getUser·p0.9999: 18.409 ms/op
                 getUser·p1.00:   19.169 ms/op

Iteration   2: 3.020 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.811 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  6.423 ms/op
                 getUser·p0.9999: 15.152 ms/op
                 getUser·p1.00:   15.417 ms/op

Iteration   3: 2.937 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.854 ms/op
                 getUser·p0.50:   2.925 ms/op
                 getUser·p0.90:   3.285 ms/op
                 getUser·p0.95:   3.400 ms/op
                 getUser·p0.99:   4.116 ms/op
                 getUser·p0.999:  6.730 ms/op
                 getUser·p0.9999: 16.519 ms/op
                 getUser·p1.00:   17.072 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320709
  mean =      2.991 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 638 
    [ 1.250,  2.500) = 21393 
    [ 2.500,  3.750) = 284278 
    [ 3.750,  5.000) = 13282 
    [ 5.000,  6.250) = 623 
    [ 6.250,  7.500) = 187 
    [ 7.500,  8.750) = 99 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 43 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.811 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      7.224 ms/op
     p(99.9900) =     17.559 ms/op
     p(99.9990) =     18.762 ms/op
     p(99.9999) =     19.169 ms/op
    p(100.0000) =     19.169 ms/op


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
# Warmup Iteration   1: 5.387 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.008 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.891 ±(99.9%) 0.010 ms/op
Iteration   1: 3.912 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.999 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  13.476 ms/op
                 listUser·p0.9999: 20.500 ms/op
                 listUser·p1.00:   20.972 ms/op

Iteration   2: 3.847 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.059 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   6.570 ms/op
                 listUser·p0.999:  14.685 ms/op
                 listUser·p0.9999: 16.007 ms/op
                 listUser·p1.00:   17.039 ms/op

Iteration   3: 3.799 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.339 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   5.358 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  15.275 ms/op
                 listUser·p0.9999: 17.537 ms/op
                 listUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249196
  mean =      3.852 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3044 
    [ 2.500,  5.000) = 228087 
    [ 5.000,  7.500) = 17116 
    [ 7.500, 10.000) = 559 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 148 
    [15.000, 17.500) = 163 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.999 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      5.530 ms/op
     p(99.0000) =      6.685 ms/op
     p(99.9000) =     14.467 ms/op
     p(99.9900) =     19.926 ms/op
     p(99.9990) =     20.858 ms/op
     p(99.9999) =     20.972 ms/op
    p(100.0000) =     20.972 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.530 ± 0.764  ops/ms
ClientGrpc.existUser                       thrpt       3  11.260 ± 3.178  ops/ms
ClientGrpc.getUser                         thrpt       3  10.631 ± 2.098  ops/ms
ClientGrpc.listUser                        thrpt       3   8.281 ± 2.728  ops/ms
ClientGrpc.createUser                       avgt       3   3.036 ± 0.594   ms/op
ClientGrpc.existUser                        avgt       3   2.880 ± 0.258   ms/op
ClientGrpc.getUser                          avgt       3   2.999 ± 0.720   ms/op
ClientGrpc.listUser                         avgt       3   3.885 ± 0.628   ms/op
ClientGrpc.createUser                     sample  315590   3.044 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.586           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.011           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.600           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.809           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.522           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.784           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.193           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.494           ms/op
ClientGrpc.existUser                      sample  331856   2.892 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.741           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.875           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.334           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.568           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.963           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.568           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.265           ms/op
ClientGrpc.getUser                        sample  320709   2.991 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.811           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.966           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.441           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.711           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.317           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.224           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.559           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.169           ms/op
ClientGrpc.listUser                       sample  249196   3.852 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.999           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.723           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.653           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.530           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.685           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.467           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.926           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.972           ms/op
