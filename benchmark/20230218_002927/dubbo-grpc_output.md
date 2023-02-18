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
# Warmup Iteration   1: 4.105 ops/ms
# Warmup Iteration   2: 8.816 ops/ms
# Warmup Iteration   3: 9.852 ops/ms
Iteration   1: 10.173 ops/ms
Iteration   2: 10.052 ops/ms
Iteration   3: 10.363 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.196 ±(99.9%) 2.860 ops/ms [Average]
  (min, avg, max) = (10.052, 10.196, 10.363), stdev = 0.157
  CI (99.9%): [7.337, 13.056] (assumes normal distribution)


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
# Warmup Iteration   1: 7.550 ops/ms
# Warmup Iteration   2: 10.158 ops/ms
# Warmup Iteration   3: 10.840 ops/ms
Iteration   1: 10.604 ops/ms
Iteration   2: 10.659 ops/ms
Iteration   3: 10.560 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.608 ±(99.9%) 0.907 ops/ms [Average]
  (min, avg, max) = (10.560, 10.608, 10.659), stdev = 0.050
  CI (99.9%): [9.701, 11.514] (assumes normal distribution)


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
# Warmup Iteration   1: 6.575 ops/ms
# Warmup Iteration   2: 10.059 ops/ms
# Warmup Iteration   3: 10.048 ops/ms
Iteration   1: 9.996 ops/ms
Iteration   2: 9.998 ops/ms
Iteration   3: 10.093 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.029 ±(99.9%) 1.013 ops/ms [Average]
  (min, avg, max) = (9.996, 10.029, 10.093), stdev = 0.056
  CI (99.9%): [9.016, 11.042] (assumes normal distribution)


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
# Warmup Iteration   1: 6.087 ops/ms
# Warmup Iteration   2: 7.892 ops/ms
# Warmup Iteration   3: 7.858 ops/ms
Iteration   1: 7.896 ops/ms
Iteration   2: 8.046 ops/ms
Iteration   3: 7.926 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.956 ±(99.9%) 1.453 ops/ms [Average]
  (min, avg, max) = (7.896, 7.956, 8.046), stdev = 0.080
  CI (99.9%): [6.503, 9.409] (assumes normal distribution)


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
# Warmup Iteration   1: 4.498 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.240 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.195 ±(99.9%) 0.003 ms/op
Iteration   1: 3.222 ±(99.9%) 0.009 ms/op
Iteration   2: 3.199 ±(99.9%) 0.002 ms/op
Iteration   3: 3.231 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.217 ±(99.9%) 0.304 ms/op [Average]
  (min, avg, max) = (3.199, 3.217, 3.231), stdev = 0.017
  CI (99.9%): [2.913, 3.521] (assumes normal distribution)


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
# Warmup Iteration   1: 4.097 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.123 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.003 ms/op
Iteration   1: 2.947 ±(99.9%) 0.002 ms/op
Iteration   2: 3.013 ±(99.9%) 0.002 ms/op
Iteration   3: 3.062 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.007 ±(99.9%) 1.051 ms/op [Average]
  (min, avg, max) = (2.947, 3.007, 3.062), stdev = 0.058
  CI (99.9%): [1.956, 4.058] (assumes normal distribution)


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
# Warmup Iteration   1: 4.145 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.178 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.164 ±(99.9%) 0.002 ms/op
Iteration   1: 3.187 ±(99.9%) 0.002 ms/op
Iteration   2: 3.173 ±(99.9%) 0.002 ms/op
Iteration   3: 3.148 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.169 ±(99.9%) 0.355 ms/op [Average]
  (min, avg, max) = (3.148, 3.169, 3.187), stdev = 0.019
  CI (99.9%): [2.815, 3.524] (assumes normal distribution)


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
# Warmup Iteration   1: 5.651 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.162 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.056 ±(99.9%) 0.012 ms/op
Iteration   1: 4.053 ±(99.9%) 0.010 ms/op
Iteration   2: 3.970 ±(99.9%) 0.008 ms/op
Iteration   3: 4.019 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.014 ±(99.9%) 0.757 ms/op [Average]
  (min, avg, max) = (3.970, 4.014, 4.053), stdev = 0.041
  CI (99.9%): [3.258, 4.771] (assumes normal distribution)


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
# Warmup Iteration   1: 4.305 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.265 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.110 ±(99.9%) 0.005 ms/op
Iteration   1: 3.146 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.666 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  8.290 ms/op
                 createUser·p0.9999: 13.036 ms/op
                 createUser·p1.00:   13.287 ms/op

Iteration   2: 3.179 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.043 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.047 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  6.451 ms/op
                 createUser·p0.9999: 14.023 ms/op
                 createUser·p1.00:   14.434 ms/op

Iteration   3: 3.193 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.652 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.928 ms/op
                 createUser·p0.95:   4.112 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  14.541 ms/op
                 createUser·p0.9999: 17.105 ms/op
                 createUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 302411
  mean =      3.172 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 422 
    [ 1.250,  2.500) = 24556 
    [ 2.500,  3.750) = 234580 
    [ 3.750,  5.000) = 41888 
    [ 5.000,  6.250) = 452 
    [ 6.250,  7.500) = 173 
    [ 7.500,  8.750) = 80 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 47 
    [16.250, 17.500) = 37 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.652 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.043 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      8.071 ms/op
     p(99.9900) =     16.528 ms/op
     p(99.9990) =     17.431 ms/op
     p(99.9999) =     17.531 ms/op
    p(100.0000) =     17.531 ms/op


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
# Warmup Iteration   1: 4.068 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.146 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.007 ms/op
Iteration   1: 2.991 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.611 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   3.879 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  6.904 ms/op
                 existUser·p0.9999: 13.035 ms/op
                 existUser·p1.00:   13.353 ms/op

Iteration   2: 2.990 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.622 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.711 ms/op
                 existUser·p0.95:   3.899 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  5.865 ms/op
                 existUser·p0.9999: 17.564 ms/op
                 existUser·p1.00:   17.695 ms/op

Iteration   3: 3.144 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.645 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.850 ms/op
                 existUser·p0.95:   3.981 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  7.557 ms/op
                 existUser·p0.9999: 16.897 ms/op
                 existUser·p1.00:   17.269 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 315877
  mean =      3.040 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2023 
    [ 1.250,  2.500) = 42767 
    [ 2.500,  3.750) = 238455 
    [ 3.750,  5.000) = 31797 
    [ 5.000,  6.250) = 461 
    [ 6.250,  7.500) = 149 
    [ 7.500,  8.750) = 72 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 53 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.611 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      6.744 ms/op
     p(99.9900) =     17.086 ms/op
     p(99.9990) =     17.596 ms/op
     p(99.9999) =     17.695 ms/op
    p(100.0000) =     17.695 ms/op


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
# Warmup Iteration   1: 4.230 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.228 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.160 ±(99.9%) 0.006 ms/op
Iteration   1: 3.209 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.959 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.916 ms/op
                 getUser·p0.95:   4.092 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  6.303 ms/op
                 getUser·p0.9999: 12.978 ms/op
                 getUser·p1.00:   13.500 ms/op

Iteration   2: 3.244 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.850 ms/op
                 getUser·p0.50:   3.232 ms/op
                 getUser·p0.90:   3.965 ms/op
                 getUser·p0.95:   4.137 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  6.744 ms/op
                 getUser·p0.9999: 14.289 ms/op
                 getUser·p1.00:   14.533 ms/op

Iteration   3: 3.111 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.780 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  8.078 ms/op
                 getUser·p0.9999: 27.253 ms/op
                 getUser·p1.00:   27.689 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 301319
  mean =      3.187 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19678 
    [ 2.500,  5.000) = 280512 
    [ 5.000,  7.500) = 884 
    [ 7.500, 10.000) = 62 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.780 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      7.002 ms/op
     p(99.9900) =     25.706 ms/op
     p(99.9990) =     27.622 ms/op
     p(99.9999) =     27.689 ms/op
    p(100.0000) =     27.689 ms/op


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
# Warmup Iteration   1: 5.168 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.430 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.168 ±(99.9%) 0.013 ms/op
Iteration   1: 4.119 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.165 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   5.325 ms/op
                 listUser·p0.95:   6.078 ms/op
                 listUser·p0.99:   7.143 ms/op
                 listUser·p0.999:  14.210 ms/op
                 listUser·p0.9999: 21.355 ms/op
                 listUser·p1.00:   21.823 ms/op

Iteration   2: 4.062 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.182 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   5.988 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  16.323 ms/op
                 listUser·p0.9999: 21.365 ms/op
                 listUser·p1.00:   22.807 ms/op

Iteration   3: 4.067 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.192 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  16.767 ms/op
                 listUser·p0.9999: 19.235 ms/op
                 listUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235153
  mean =      4.082 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1784 
    [ 2.500,  5.000) = 204854 
    [ 5.000,  7.500) = 27124 
    [ 7.500, 10.000) = 934 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.165 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      5.210 ms/op
     p(95.0000) =      5.906 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     16.040 ms/op
     p(99.9900) =     21.184 ms/op
     p(99.9990) =     22.683 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.196 ± 2.860  ops/ms
ClientGrpc.existUser                       thrpt       3  10.608 ± 0.907  ops/ms
ClientGrpc.getUser                         thrpt       3  10.029 ± 1.013  ops/ms
ClientGrpc.listUser                        thrpt       3   7.956 ± 1.453  ops/ms
ClientGrpc.createUser                       avgt       3   3.217 ± 0.304   ms/op
ClientGrpc.existUser                        avgt       3   3.007 ± 1.051   ms/op
ClientGrpc.getUser                          avgt       3   3.169 ± 0.355   ms/op
ClientGrpc.listUser                         avgt       3   4.014 ± 0.757   ms/op
ClientGrpc.createUser                     sample  302411   3.172 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.652           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.142           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.863           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.043           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.399           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.071           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.528           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.531           ms/op
ClientGrpc.existUser                      sample  315877   3.040 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.611           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.031           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.760           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.932           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.284           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.744           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.086           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.695           ms/op
ClientGrpc.getUser                        sample  301319   3.187 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.780           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.154           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.891           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.080           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.473           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.002           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.706           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.689           ms/op
ClientGrpc.listUser                       sample  235153   4.082 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.165           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.899           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.210           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.906           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.021           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.040           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.184           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.807           ms/op
