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
# Warmup Iteration   1: 4.692 ops/ms
# Warmup Iteration   2: 8.903 ops/ms
# Warmup Iteration   3: 9.991 ops/ms
Iteration   1: 10.631 ops/ms
Iteration   2: 10.632 ops/ms
Iteration   3: 10.762 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.675 ±(99.9%) 1.376 ops/ms [Average]
  (min, avg, max) = (10.631, 10.675, 10.762), stdev = 0.075
  CI (99.9%): [9.300, 12.051] (assumes normal distribution)


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
# Warmup Iteration   1: 7.579 ops/ms
# Warmup Iteration   2: 10.986 ops/ms
# Warmup Iteration   3: 11.367 ops/ms
Iteration   1: 11.096 ops/ms
Iteration   2: 11.167 ops/ms
Iteration   3: 11.056 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.106 ±(99.9%) 1.026 ops/ms [Average]
  (min, avg, max) = (11.056, 11.106, 11.167), stdev = 0.056
  CI (99.9%): [10.081, 12.132] (assumes normal distribution)


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
# Warmup Iteration   1: 6.970 ops/ms
# Warmup Iteration   2: 9.945 ops/ms
# Warmup Iteration   3: 10.610 ops/ms
Iteration   1: 10.789 ops/ms
Iteration   2: 10.808 ops/ms
Iteration   3: 10.769 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.789 ±(99.9%) 0.355 ops/ms [Average]
  (min, avg, max) = (10.769, 10.789, 10.808), stdev = 0.019
  CI (99.9%): [10.434, 11.144] (assumes normal distribution)


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
# Warmup Iteration   1: 5.355 ops/ms
# Warmup Iteration   2: 8.085 ops/ms
# Warmup Iteration   3: 8.092 ops/ms
Iteration   1: 8.152 ops/ms
Iteration   2: 8.386 ops/ms
Iteration   3: 8.222 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.253 ±(99.9%) 2.188 ops/ms [Average]
  (min, avg, max) = (8.152, 8.253, 8.386), stdev = 0.120
  CI (99.9%): [6.066, 10.441] (assumes normal distribution)


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
# Warmup Iteration   1: 4.129 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.091 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.020 ±(99.9%) 0.003 ms/op
Iteration   1: 3.012 ±(99.9%) 0.002 ms/op
Iteration   2: 3.008 ±(99.9%) 0.002 ms/op
Iteration   3: 3.009 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.010 ±(99.9%) 0.033 ms/op [Average]
  (min, avg, max) = (3.008, 3.010, 3.012), stdev = 0.002
  CI (99.9%): [2.977, 3.043] (assumes normal distribution)


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
# Warmup Iteration   1: 3.933 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.986 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.821 ±(99.9%) 0.003 ms/op
Iteration   1: 2.759 ±(99.9%) 0.004 ms/op
Iteration   2: 2.871 ±(99.9%) 0.003 ms/op
Iteration   3: 2.977 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.869 ±(99.9%) 1.983 ms/op [Average]
  (min, avg, max) = (2.759, 2.869, 2.977), stdev = 0.109
  CI (99.9%): [0.886, 4.852] (assumes normal distribution)


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
# Warmup Iteration   1: 3.734 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.002 ms/op
Iteration   1: 3.001 ±(99.9%) 0.002 ms/op
Iteration   2: 3.017 ±(99.9%) 0.002 ms/op
Iteration   3: 2.975 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.998 ±(99.9%) 0.385 ms/op [Average]
  (min, avg, max) = (2.975, 2.998, 3.017), stdev = 0.021
  CI (99.9%): [2.612, 3.383] (assumes normal distribution)


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
# Warmup Iteration   1: 4.365 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.093 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.910 ±(99.9%) 0.040 ms/op
Iteration   1: 3.932 ±(99.9%) 0.008 ms/op
Iteration   2: 3.914 ±(99.9%) 0.017 ms/op
Iteration   3: 3.884 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.910 ±(99.9%) 0.440 ms/op [Average]
  (min, avg, max) = (3.884, 3.910, 3.932), stdev = 0.024
  CI (99.9%): [3.470, 4.350] (assumes normal distribution)


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
# Warmup Iteration   1: 4.125 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.181 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.006 ms/op
Iteration   1: 3.028 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.568 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.445 ms/op
                 createUser·p0.95:   3.666 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  7.122 ms/op
                 createUser·p0.9999: 16.326 ms/op
                 createUser·p1.00:   16.613 ms/op

Iteration   2: 3.035 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.722 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  8.585 ms/op
                 createUser·p0.9999: 14.103 ms/op
                 createUser·p1.00:   14.369 ms/op

Iteration   3: 3.050 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.536 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.883 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  11.288 ms/op
                 createUser·p0.9999: 15.065 ms/op
                 createUser·p1.00:   16.482 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316171
  mean =      3.038 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1432 
    [ 1.250,  2.500) = 21674 
    [ 2.500,  3.750) = 275449 
    [ 3.750,  5.000) = 16023 
    [ 5.000,  6.250) = 933 
    [ 6.250,  7.500) = 246 
    [ 7.500,  8.750) = 49 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 74 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.536 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      9.829 ms/op
     p(99.9900) =     15.948 ms/op
     p(99.9990) =     16.556 ms/op
     p(99.9999) =     16.613 ms/op
    p(100.0000) =     16.613 ms/op


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
# Warmup Iteration   1: 3.859 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.962 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.899 ±(99.9%) 0.007 ms/op
Iteration   1: 2.926 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.712 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.174 ms/op
                 existUser·p0.999:  6.062 ms/op
                 existUser·p0.9999: 11.732 ms/op
                 existUser·p1.00:   11.977 ms/op

Iteration   2: 2.909 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.633 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.312 ms/op
                 existUser·p0.999:  6.178 ms/op
                 existUser·p0.9999: 12.927 ms/op
                 existUser·p1.00:   13.156 ms/op

Iteration   3: 2.918 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.369 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.571 ms/op
                 existUser·p0.999:  9.806 ms/op
                 existUser·p0.9999: 15.534 ms/op
                 existUser·p1.00:   16.155 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328621
  mean =      2.918 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3085 
    [ 1.250,  2.500) = 33455 
    [ 2.500,  3.750) = 281677 
    [ 3.750,  5.000) = 9105 
    [ 5.000,  6.250) = 844 
    [ 6.250,  7.500) = 158 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 46 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 56 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.369 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.420 ms/op
     p(95.0000) =      3.629 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      7.189 ms/op
     p(99.9900) =     14.500 ms/op
     p(99.9990) =     16.047 ms/op
     p(99.9999) =     16.155 ms/op
    p(100.0000) =     16.155 ms/op


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
# Warmup Iteration   1: 4.034 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.134 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.006 ms/op
Iteration   1: 3.000 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.639 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.393 ms/op
                 getUser·p0.999:  7.834 ms/op
                 getUser·p0.9999: 16.013 ms/op
                 getUser·p1.00:   16.417 ms/op

Iteration   2: 3.026 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.736 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  8.296 ms/op
                 getUser·p0.9999: 15.260 ms/op
                 getUser·p1.00:   15.598 ms/op

Iteration   3: 2.978 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.583 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  6.883 ms/op
                 getUser·p0.9999: 15.667 ms/op
                 getUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319837
  mean =      3.001 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2263 
    [ 1.250,  2.500) = 23788 
    [ 2.500,  3.750) = 276406 
    [ 3.750,  5.000) = 16066 
    [ 5.000,  6.250) = 798 
    [ 6.250,  7.500) = 166 
    [ 7.500,  8.750) = 100 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 46 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 63 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.583 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      7.860 ms/op
     p(99.9900) =     15.663 ms/op
     p(99.9990) =     17.066 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.173 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.120 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.006 ±(99.9%) 0.011 ms/op
Iteration   1: 3.852 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.805 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  12.132 ms/op
                 listUser·p0.9999: 13.648 ms/op
                 listUser·p1.00:   15.139 ms/op

Iteration   2: 3.921 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.862 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  13.521 ms/op
                 listUser·p0.9999: 17.296 ms/op
                 listUser·p1.00:   17.695 ms/op

Iteration   3: 3.977 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.652 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   7.091 ms/op
                 listUser·p0.999:  18.809 ms/op
                 listUser·p0.9999: 21.592 ms/op
                 listUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245295
  mean =      3.916 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5109 
    [ 2.500,  5.000) = 217884 
    [ 5.000,  7.500) = 21020 
    [ 7.500, 10.000) = 781 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 168 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.652 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.915 ms/op
     p(95.0000) =      5.595 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     13.386 ms/op
     p(99.9900) =     21.052 ms/op
     p(99.9990) =     22.139 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.675 ± 1.376  ops/ms
ClientGrpc.existUser                       thrpt       3  11.106 ± 1.026  ops/ms
ClientGrpc.getUser                         thrpt       3  10.789 ± 0.355  ops/ms
ClientGrpc.listUser                        thrpt       3   8.253 ± 2.188  ops/ms
ClientGrpc.createUser                       avgt       3   3.010 ± 0.033   ms/op
ClientGrpc.existUser                        avgt       3   2.869 ± 1.983   ms/op
ClientGrpc.getUser                          avgt       3   2.998 ± 0.385   ms/op
ClientGrpc.listUser                         avgt       3   3.910 ± 0.440   ms/op
ClientGrpc.createUser                     sample  316171   3.038 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.536           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.023           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.572           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.781           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.415           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.829           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.948           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.613           ms/op
ClientGrpc.existUser                      sample  328621   2.918 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.369           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.420           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.629           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.350           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.189           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.500           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.155           ms/op
ClientGrpc.getUser                        sample  319837   3.001 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.583           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.006           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.523           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.781           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.375           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.860           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.663           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.924           ms/op
ClientGrpc.listUser                       sample  245295   3.916 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.652           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.772           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.915           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.595           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.906           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.386           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.052           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.217           ms/op
