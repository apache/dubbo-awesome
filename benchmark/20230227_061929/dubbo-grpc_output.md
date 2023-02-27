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
# Warmup Iteration   1: 4.520 ops/ms
# Warmup Iteration   2: 9.359 ops/ms
# Warmup Iteration   3: 10.147 ops/ms
Iteration   1: 10.191 ops/ms
Iteration   2: 10.272 ops/ms
Iteration   3: 10.029 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.164 ±(99.9%) 2.266 ops/ms [Average]
  (min, avg, max) = (10.029, 10.164, 10.272), stdev = 0.124
  CI (99.9%): [7.898, 12.430] (assumes normal distribution)


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
# Warmup Iteration   1: 7.492 ops/ms
# Warmup Iteration   2: 10.441 ops/ms
# Warmup Iteration   3: 10.436 ops/ms
Iteration   1: 10.430 ops/ms
Iteration   2: 10.795 ops/ms
Iteration   3: 10.707 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.644 ±(99.9%) 3.476 ops/ms [Average]
  (min, avg, max) = (10.430, 10.644, 10.795), stdev = 0.191
  CI (99.9%): [7.167, 14.120] (assumes normal distribution)


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
# Warmup Iteration   1: 7.121 ops/ms
# Warmup Iteration   2: 9.888 ops/ms
# Warmup Iteration   3: 10.349 ops/ms
Iteration   1: 10.255 ops/ms
Iteration   2: 10.296 ops/ms
Iteration   3: 10.234 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.262 ±(99.9%) 0.572 ops/ms [Average]
  (min, avg, max) = (10.234, 10.262, 10.296), stdev = 0.031
  CI (99.9%): [9.689, 10.834] (assumes normal distribution)


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
# Warmup Iteration   1: 5.435 ops/ms
# Warmup Iteration   2: 7.603 ops/ms
# Warmup Iteration   3: 7.956 ops/ms
Iteration   1: 7.940 ops/ms
Iteration   2: 7.947 ops/ms
Iteration   3: 8.039 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.975 ±(99.9%) 1.006 ops/ms [Average]
  (min, avg, max) = (7.940, 7.975, 8.039), stdev = 0.055
  CI (99.9%): [6.969, 8.981] (assumes normal distribution)


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
# Warmup Iteration   1: 4.175 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.171 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.116 ±(99.9%) 0.012 ms/op
Iteration   1: 3.177 ±(99.9%) 0.002 ms/op
Iteration   2: 3.180 ±(99.9%) 0.003 ms/op
Iteration   3: 3.179 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.179 ±(99.9%) 0.026 ms/op [Average]
  (min, avg, max) = (3.177, 3.179, 3.180), stdev = 0.001
  CI (99.9%): [3.153, 3.205] (assumes normal distribution)


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
# Warmup Iteration   1: 3.727 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.086 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.102 ±(99.9%) 0.002 ms/op
Iteration   1: 2.997 ±(99.9%) 0.002 ms/op
Iteration   2: 2.982 ±(99.9%) 0.002 ms/op
Iteration   3: 3.033 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.004 ±(99.9%) 0.477 ms/op [Average]
  (min, avg, max) = (2.982, 3.004, 3.033), stdev = 0.026
  CI (99.9%): [2.527, 3.482] (assumes normal distribution)


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
# Warmup Iteration   1: 4.207 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.250 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.215 ±(99.9%) 0.003 ms/op
Iteration   1: 3.131 ±(99.9%) 0.002 ms/op
Iteration   2: 3.103 ±(99.9%) 0.002 ms/op
Iteration   3: 3.107 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.114 ±(99.9%) 0.281 ms/op [Average]
  (min, avg, max) = (3.103, 3.114, 3.131), stdev = 0.015
  CI (99.9%): [2.833, 3.394] (assumes normal distribution)


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
# Warmup Iteration   1: 5.844 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.085 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.036 ±(99.9%) 0.018 ms/op
Iteration   1: 4.004 ±(99.9%) 0.009 ms/op
Iteration   2: 3.925 ±(99.9%) 0.014 ms/op
Iteration   3: 3.978 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.969 ±(99.9%) 0.736 ms/op [Average]
  (min, avg, max) = (3.925, 3.969, 4.004), stdev = 0.040
  CI (99.9%): [3.233, 4.705] (assumes normal distribution)


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
# Warmup Iteration   1: 4.329 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.260 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.208 ±(99.9%) 0.007 ms/op
Iteration   1: 3.192 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.736 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.071 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  7.976 ms/op
                 createUser·p0.9999: 16.760 ms/op
                 createUser·p1.00:   17.138 ms/op

Iteration   2: 3.137 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.287 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.006 ms/op
                 createUser·p0.99:   4.402 ms/op
                 createUser·p0.999:  6.570 ms/op
                 createUser·p0.9999: 19.156 ms/op
                 createUser·p1.00:   19.628 ms/op

Iteration   3: 3.233 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.833 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.932 ms/op
                 createUser·p0.95:   4.108 ms/op
                 createUser·p0.99:   4.547 ms/op
                 createUser·p0.999:  9.978 ms/op
                 createUser·p0.9999: 19.405 ms/op
                 createUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 301365
  mean =      3.187 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 636 
    [ 1.250,  2.500) = 23184 
    [ 2.500,  3.750) = 232500 
    [ 3.750,  5.000) = 43734 
    [ 5.000,  6.250) = 592 
    [ 6.250,  7.500) = 355 
    [ 7.500,  8.750) = 139 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 42 
    [16.250, 17.500) = 57 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.287 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.067 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      7.971 ms/op
     p(99.9900) =     19.071 ms/op
     p(99.9990) =     19.693 ms/op
     p(99.9999) =     19.825 ms/op
    p(100.0000) =     19.825 ms/op


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
# Warmup Iteration   1: 3.968 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.178 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.006 ms/op
Iteration   1: 2.925 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.821 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   4.174 ms/op
                 existUser·p0.999:  6.226 ms/op
                 existUser·p0.9999: 11.683 ms/op
                 existUser·p1.00:   12.108 ms/op

Iteration   2: 2.970 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.838 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   4.153 ms/op
                 existUser·p0.999:  11.534 ms/op
                 existUser·p0.9999: 14.704 ms/op
                 existUser·p1.00:   15.237 ms/op

Iteration   3: 2.991 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.681 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   4.100 ms/op
                 existUser·p0.999:  6.078 ms/op
                 existUser·p0.9999: 15.613 ms/op
                 existUser·p1.00:   17.793 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324051
  mean =      2.962 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2090 
    [ 1.250,  2.500) = 52216 
    [ 2.500,  3.750) = 250256 
    [ 3.750,  5.000) = 18521 
    [ 5.000,  6.250) = 500 
    [ 6.250,  7.500) = 147 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 49 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 111 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 50 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.681 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.145 ms/op
     p(99.9000) =      7.224 ms/op
     p(99.9900) =     15.257 ms/op
     p(99.9990) =     16.028 ms/op
     p(99.9999) =     17.793 ms/op
    p(100.0000) =     17.793 ms/op


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
# Warmup Iteration   1: 4.152 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.174 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.179 ±(99.9%) 0.007 ms/op
Iteration   1: 3.087 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.740 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   4.407 ms/op
                 getUser·p0.999:  6.939 ms/op
                 getUser·p0.9999: 13.194 ms/op
                 getUser·p1.00:   13.369 ms/op

Iteration   2: 3.178 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.867 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.899 ms/op
                 getUser·p0.95:   4.088 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  7.171 ms/op
                 getUser·p0.9999: 27.754 ms/op
                 getUser·p1.00:   28.082 ms/op

Iteration   3: 3.181 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.739 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.035 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  7.381 ms/op
                 getUser·p0.9999: 28.703 ms/op
                 getUser·p1.00:   29.098 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 304681
  mean =      3.148 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26137 
    [ 2.500,  5.000) = 277419 
    [ 5.000,  7.500) = 881 
    [ 7.500, 10.000) = 83 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.739 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      7.187 ms/op
     p(99.9900) =     28.117 ms/op
     p(99.9990) =     28.997 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


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
# Warmup Iteration   1: 5.487 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.183 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.045 ±(99.9%) 0.010 ms/op
Iteration   1: 4.041 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.460 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.988 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  13.372 ms/op
                 listUser·p0.9999: 17.111 ms/op
                 listUser·p1.00:   17.465 ms/op

Iteration   2: 4.057 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.262 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  16.516 ms/op
                 listUser·p0.9999: 22.492 ms/op
                 listUser·p1.00:   24.052 ms/op

Iteration   3: 3.991 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.932 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  16.597 ms/op
                 listUser·p0.9999: 25.919 ms/op
                 listUser·p1.00:   26.411 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238300
  mean =      4.030 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2256 
    [ 2.500,  5.000) = 210487 
    [ 5.000,  7.500) = 24136 
    [ 7.500, 10.000) = 867 
    [10.000, 12.500) = 193 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.932 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      5.079 ms/op
     p(95.0000) =      5.718 ms/op
     p(99.0000) =      6.947 ms/op
     p(99.9000) =     14.975 ms/op
     p(99.9900) =     25.084 ms/op
     p(99.9990) =     26.288 ms/op
     p(99.9999) =     26.411 ms/op
    p(100.0000) =     26.411 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.164 ± 2.266  ops/ms
ClientGrpc.existUser                       thrpt       3  10.644 ± 3.476  ops/ms
ClientGrpc.getUser                         thrpt       3  10.262 ± 0.572  ops/ms
ClientGrpc.listUser                        thrpt       3   7.975 ± 1.006  ops/ms
ClientGrpc.createUser                       avgt       3   3.179 ± 0.026   ms/op
ClientGrpc.existUser                        avgt       3   3.004 ± 0.477   ms/op
ClientGrpc.getUser                          avgt       3   3.114 ± 0.281   ms/op
ClientGrpc.listUser                         avgt       3   3.969 ± 0.736   ms/op
ClientGrpc.createUser                     sample  301365   3.187 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.287           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.154           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.887           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.067           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.465           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.971           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.071           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.825           ms/op
ClientGrpc.existUser                      sample  324051   2.962 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.681           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.953           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.613           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.797           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.145           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.224           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.257           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.793           ms/op
ClientGrpc.getUser                        sample  304681   3.148 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.739           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.117           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.846           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.051           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.432           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.187           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.117           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.098           ms/op
ClientGrpc.listUser                       sample  238300   4.030 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.932           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.867           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.079           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.718           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.947           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.975           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.084           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.411           ms/op
