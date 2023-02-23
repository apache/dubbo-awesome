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
# Warmup Iteration   1: 4.787 ops/ms
# Warmup Iteration   2: 9.946 ops/ms
# Warmup Iteration   3: 10.501 ops/ms
Iteration   1: 10.529 ops/ms
Iteration   2: 10.283 ops/ms
Iteration   3: 10.325 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.379 ±(99.9%) 2.403 ops/ms [Average]
  (min, avg, max) = (10.283, 10.379, 10.529), stdev = 0.132
  CI (99.9%): [7.977, 12.782] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.813 ops/ms
# Warmup Iteration   2: 10.530 ops/ms
# Warmup Iteration   3: 10.797 ops/ms
Iteration   1: 10.729 ops/ms
Iteration   2: 10.667 ops/ms
Iteration   3: 10.941 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.779 ±(99.9%) 2.623 ops/ms [Average]
  (min, avg, max) = (10.667, 10.779, 10.941), stdev = 0.144
  CI (99.9%): [8.156, 13.402] (assumes normal distribution)


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
# Warmup Iteration   1: 7.951 ops/ms
# Warmup Iteration   2: 10.238 ops/ms
# Warmup Iteration   3: 10.280 ops/ms
Iteration   1: 10.647 ops/ms
Iteration   2: 10.413 ops/ms
Iteration   3: 10.505 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.522 ±(99.9%) 2.146 ops/ms [Average]
  (min, avg, max) = (10.413, 10.522, 10.647), stdev = 0.118
  CI (99.9%): [8.376, 12.668] (assumes normal distribution)


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
# Warmup Iteration   1: 5.882 ops/ms
# Warmup Iteration   2: 7.728 ops/ms
# Warmup Iteration   3: 7.739 ops/ms
Iteration   1: 7.843 ops/ms
Iteration   2: 8.085 ops/ms
Iteration   3: 8.053 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.993 ±(99.9%) 2.393 ops/ms [Average]
  (min, avg, max) = (7.843, 7.993, 8.085), stdev = 0.131
  CI (99.9%): [5.601, 10.386] (assumes normal distribution)


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
# Warmup Iteration   1: 4.066 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.178 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.003 ms/op
Iteration   1: 3.109 ±(99.9%) 0.003 ms/op
Iteration   2: 3.222 ±(99.9%) 0.002 ms/op
Iteration   3: 3.122 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.151 ±(99.9%) 1.127 ms/op [Average]
  (min, avg, max) = (3.109, 3.151, 3.222), stdev = 0.062
  CI (99.9%): [2.024, 4.278] (assumes normal distribution)


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
# Warmup Iteration   1: 3.771 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.082 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.003 ms/op
Iteration   1: 2.962 ±(99.9%) 0.003 ms/op
Iteration   2: 3.037 ±(99.9%) 0.003 ms/op
Iteration   3: 2.943 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.981 ±(99.9%) 0.911 ms/op [Average]
  (min, avg, max) = (2.943, 2.981, 3.037), stdev = 0.050
  CI (99.9%): [2.070, 3.891] (assumes normal distribution)


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
# Warmup Iteration   1: 4.103 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.135 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.127 ±(99.9%) 0.003 ms/op
Iteration   1: 3.066 ±(99.9%) 0.003 ms/op
Iteration   2: 3.094 ±(99.9%) 0.002 ms/op
Iteration   3: 3.080 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.080 ±(99.9%) 0.255 ms/op [Average]
  (min, avg, max) = (3.066, 3.080, 3.094), stdev = 0.014
  CI (99.9%): [2.825, 3.335] (assumes normal distribution)


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
# Warmup Iteration   1: 4.260 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 4.101 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.048 ±(99.9%) 0.019 ms/op
Iteration   1: 3.958 ±(99.9%) 0.028 ms/op
Iteration   2: 3.959 ±(99.9%) 0.006 ms/op
Iteration   3: 3.932 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.950 ±(99.9%) 0.275 ms/op [Average]
  (min, avg, max) = (3.932, 3.950, 3.959), stdev = 0.015
  CI (99.9%): [3.675, 4.225] (assumes normal distribution)


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
# Warmup Iteration   1: 3.836 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.178 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.006 ms/op
Iteration   1: 3.096 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.719 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  8.093 ms/op
                 createUser·p0.9999: 16.984 ms/op
                 createUser·p1.00:   17.302 ms/op

Iteration   2: 3.035 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.633 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.731 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  8.145 ms/op
                 createUser·p0.9999: 18.002 ms/op
                 createUser·p1.00:   19.104 ms/op

Iteration   3: 3.028 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.652 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.637 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  10.990 ms/op
                 createUser·p0.9999: 21.740 ms/op
                 createUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314454
  mean =      3.052 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21806 
    [ 2.500,  5.000) = 291550 
    [ 5.000,  7.500) = 654 
    [ 7.500, 10.000) = 126 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.633 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =     10.069 ms/op
     p(99.9900) =     21.190 ms/op
     p(99.9990) =     22.048 ms/op
     p(99.9999) =     22.184 ms/op
    p(100.0000) =     22.184 ms/op


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
# Warmup Iteration   1: 3.929 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.014 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.007 ms/op
Iteration   1: 2.943 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.359 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.850 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  7.810 ms/op
                 existUser·p0.9999: 17.236 ms/op
                 existUser·p1.00:   17.760 ms/op

Iteration   2: 2.996 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.674 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   4.186 ms/op
                 existUser·p0.999:  10.732 ms/op
                 existUser·p0.9999: 13.921 ms/op
                 existUser·p1.00:   14.221 ms/op

Iteration   3: 3.003 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.756 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   3.899 ms/op
                 existUser·p0.99:   4.186 ms/op
                 existUser·p0.999:  5.243 ms/op
                 existUser·p0.9999: 14.611 ms/op
                 existUser·p1.00:   15.188 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321748
  mean =      2.980 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1729 
    [ 1.250,  2.500) = 45745 
    [ 2.500,  3.750) = 251531 
    [ 3.750,  5.000) = 21968 
    [ 5.000,  6.250) = 310 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 106 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 131 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.359 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      8.676 ms/op
     p(99.9900) =     16.215 ms/op
     p(99.9990) =     17.400 ms/op
     p(99.9999) =     17.760 ms/op
    p(100.0000) =     17.760 ms/op


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
# Warmup Iteration   1: 4.243 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.190 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.006 ms/op
Iteration   1: 3.015 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.595 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   3.650 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  7.379 ms/op
                 getUser·p0.9999: 11.665 ms/op
                 getUser·p1.00:   12.108 ms/op

Iteration   2: 3.066 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.461 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   4.407 ms/op
                 getUser·p0.999:  8.049 ms/op
                 getUser·p0.9999: 24.252 ms/op
                 getUser·p1.00:   25.756 ms/op

Iteration   3: 3.007 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.377 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.629 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  5.423 ms/op
                 getUser·p0.9999: 15.560 ms/op
                 getUser·p1.00:   16.941 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317083
  mean =      3.029 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23933 
    [ 2.500,  5.000) = 292260 
    [ 5.000,  7.500) = 640 
    [ 7.500, 10.000) = 96 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.377 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      6.980 ms/op
     p(99.9900) =     23.331 ms/op
     p(99.9990) =     25.625 ms/op
     p(99.9999) =     25.756 ms/op
    p(100.0000) =     25.756 ms/op


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
# Warmup Iteration   1: 5.126 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.137 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.077 ±(99.9%) 0.011 ms/op
Iteration   1: 4.237 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.200 ms/op
                 listUser·p0.50:   4.014 ms/op
                 listUser·p0.90:   5.415 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   7.291 ms/op
                 listUser·p0.999:  11.541 ms/op
                 listUser·p0.9999: 17.790 ms/op
                 listUser·p1.00:   18.186 ms/op

Iteration   2: 4.081 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.260 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  13.189 ms/op
                 listUser·p0.9999: 18.388 ms/op
                 listUser·p1.00:   18.645 ms/op

Iteration   3: 4.038 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.691 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   6.029 ms/op
                 listUser·p0.99:   7.176 ms/op
                 listUser·p0.999:  16.012 ms/op
                 listUser·p0.9999: 23.737 ms/op
                 listUser·p1.00:   24.379 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 233187
  mean =      4.117 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3538 
    [ 2.500,  5.000) = 191499 
    [ 5.000,  7.500) = 36511 
    [ 7.500, 10.000) = 1176 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 192 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.691 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      5.333 ms/op
     p(95.0000) =      5.775 ms/op
     p(99.0000) =      7.135 ms/op
     p(99.9000) =     13.759 ms/op
     p(99.9900) =     22.905 ms/op
     p(99.9990) =     24.347 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.379 ± 2.403  ops/ms
ClientGrpc.existUser                       thrpt       3  10.779 ± 2.623  ops/ms
ClientGrpc.getUser                         thrpt       3  10.522 ± 2.146  ops/ms
ClientGrpc.listUser                        thrpt       3   7.993 ± 2.393  ops/ms
ClientGrpc.createUser                       avgt       3   3.151 ± 1.127   ms/op
ClientGrpc.existUser                        avgt       3   2.981 ± 0.911   ms/op
ClientGrpc.getUser                          avgt       3   3.080 ± 0.255   ms/op
ClientGrpc.listUser                         avgt       3   3.950 ± 0.275   ms/op
ClientGrpc.createUser                     sample  314454   3.052 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.633           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.052           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.551           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.789           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.317           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.069           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.190           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.184           ms/op
ClientGrpc.existUser                      sample  321748   2.980 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.359           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.961           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.645           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.838           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.211           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.676           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.215           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.760           ms/op
ClientGrpc.getUser                        sample  317083   3.029 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.377           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.514           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.727           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.293           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.980           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.331           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.756           ms/op
ClientGrpc.listUser                       sample  233187   4.117 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.691           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.895           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.333           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.775           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.135           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.759           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.905           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.379           ms/op
