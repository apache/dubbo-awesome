# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.996 ops/ms
# Warmup Iteration   2: 8.854 ops/ms
# Warmup Iteration   3: 10.021 ops/ms
Iteration   1: 10.480 ops/ms
Iteration   2: 10.510 ops/ms
Iteration   3: 10.531 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.507 ±(99.9%) 0.465 ops/ms [Average]
  (min, avg, max) = (10.480, 10.507, 10.531), stdev = 0.025
  CI (99.9%): [10.042, 10.972] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.294 ops/ms
# Warmup Iteration   2: 10.496 ops/ms
# Warmup Iteration   3: 10.648 ops/ms
Iteration   1: 10.999 ops/ms
Iteration   2: 10.786 ops/ms
Iteration   3: 10.986 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.924 ±(99.9%) 2.183 ops/ms [Average]
  (min, avg, max) = (10.786, 10.924, 10.999), stdev = 0.120
  CI (99.9%): [8.741, 13.106] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.792 ops/ms
# Warmup Iteration   2: 10.169 ops/ms
# Warmup Iteration   3: 10.477 ops/ms
Iteration   1: 10.647 ops/ms
Iteration   2: 10.429 ops/ms
Iteration   3: 10.593 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.556 ±(99.9%) 2.065 ops/ms [Average]
  (min, avg, max) = (10.429, 10.556, 10.647), stdev = 0.113
  CI (99.9%): [8.491, 12.622] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.678 ops/ms
# Warmup Iteration   2: 7.642 ops/ms
# Warmup Iteration   3: 7.732 ops/ms
Iteration   1: 8.015 ops/ms
Iteration   2: 7.852 ops/ms
Iteration   3: 8.065 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.977 ±(99.9%) 2.026 ops/ms [Average]
  (min, avg, max) = (7.852, 7.977, 8.065), stdev = 0.111
  CI (99.9%): [5.951, 10.003] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.420 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.187 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.124 ±(99.9%) 0.003 ms/op
Iteration   1: 3.086 ±(99.9%) 0.002 ms/op
Iteration   2: 3.034 ±(99.9%) 0.004 ms/op
Iteration   3: 3.047 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.056 ±(99.9%) 0.501 ms/op [Average]
  (min, avg, max) = (3.034, 3.056, 3.086), stdev = 0.027
  CI (99.9%): [2.555, 3.556] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.060 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.092 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 2.973 ±(99.9%) 0.001 ms/op
Iteration   1: 2.880 ±(99.9%) 0.002 ms/op
Iteration   2: 2.885 ±(99.9%) 0.002 ms/op
Iteration   3: 2.918 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.894 ±(99.9%) 0.371 ms/op [Average]
  (min, avg, max) = (2.880, 2.894, 2.918), stdev = 0.020
  CI (99.9%): [2.523, 3.266] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.383 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.203 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.022 ±(99.9%) 0.004 ms/op
Iteration   1: 3.082 ±(99.9%) 0.003 ms/op
Iteration   2: 3.100 ±(99.9%) 0.003 ms/op
Iteration   3: 3.021 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.068 ±(99.9%) 0.756 ms/op [Average]
  (min, avg, max) = (3.021, 3.068, 3.100), stdev = 0.041
  CI (99.9%): [2.312, 3.824] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.369 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.160 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.047 ±(99.9%) 0.022 ms/op
Iteration   1: 4.027 ±(99.9%) 0.017 ms/op
Iteration   2: 4.003 ±(99.9%) 0.011 ms/op
Iteration   3: 4.011 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.014 ±(99.9%) 0.218 ms/op [Average]
  (min, avg, max) = (4.003, 4.014, 4.027), stdev = 0.012
  CI (99.9%): [3.795, 4.232] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.463 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.214 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.072 ±(99.9%) 0.007 ms/op
Iteration   1: 3.105 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.681 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  7.913 ms/op
                 createUser·p0.9999: 13.119 ms/op
                 createUser·p1.00:   13.582 ms/op

Iteration   2: 3.036 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.979 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.776 ms/op
                 createUser·p0.999:  8.045 ms/op
                 createUser·p0.9999: 19.610 ms/op
                 createUser·p1.00:   19.825 ms/op

Iteration   3: 3.015 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.618 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   4.833 ms/op
                 createUser·p0.999:  9.634 ms/op
                 createUser·p0.9999: 17.400 ms/op
                 createUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314586
  mean =      3.052 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 383 
    [ 1.250,  2.500) = 20870 
    [ 2.500,  3.750) = 274335 
    [ 3.750,  5.000) = 16849 
    [ 5.000,  6.250) = 1195 
    [ 6.250,  7.500) = 485 
    [ 7.500,  8.750) = 208 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 36 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.618 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.710 ms/op
     p(99.9000) =      8.154 ms/op
     p(99.9900) =     19.205 ms/op
     p(99.9990) =     19.754 ms/op
     p(99.9999) =     19.825 ms/op
    p(100.0000) =     19.825 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.201 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.053 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.948 ±(99.9%) 0.006 ms/op
Iteration   1: 2.966 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.555 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.178 ms/op
                 existUser·p0.999:  7.366 ms/op
                 existUser·p0.9999: 12.766 ms/op
                 existUser·p1.00:   13.140 ms/op

Iteration   2: 2.906 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.776 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  8.077 ms/op
                 existUser·p0.9999: 16.433 ms/op
                 existUser·p1.00:   16.597 ms/op

Iteration   3: 2.923 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.831 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.539 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  8.660 ms/op
                 existUser·p0.9999: 16.777 ms/op
                 existUser·p1.00:   17.072 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327374
  mean =      2.932 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1365 
    [ 1.250,  2.500) = 31786 
    [ 2.500,  3.750) = 284523 
    [ 3.750,  5.000) = 8300 
    [ 5.000,  6.250) = 597 
    [ 6.250,  7.500) = 352 
    [ 7.500,  8.750) = 215 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 63 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.383 ms/op
     p(95.0000) =      3.584 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      7.938 ms/op
     p(99.9900) =     16.475 ms/op
     p(99.9990) =     16.974 ms/op
     p(99.9999) =     17.072 ms/op
    p(100.0000) =     17.072 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.450 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.283 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.133 ±(99.9%) 0.007 ms/op
Iteration   1: 3.080 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.734 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   4.628 ms/op
                 getUser·p0.999:  7.817 ms/op
                 getUser·p0.9999: 20.435 ms/op
                 getUser·p1.00:   20.611 ms/op

Iteration   2: 3.078 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.908 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   5.112 ms/op
                 getUser·p0.999:  11.449 ms/op
                 getUser·p0.9999: 14.729 ms/op
                 getUser·p1.00:   14.877 ms/op

Iteration   3: 3.067 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.698 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.494 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  8.808 ms/op
                 getUser·p0.9999: 17.302 ms/op
                 getUser·p1.00:   17.596 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312335
  mean =      3.075 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14998 
    [ 2.500,  5.000) = 294800 
    [ 5.000,  7.500) = 1813 
    [ 7.500, 10.000) = 443 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.698 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.760 ms/op
     p(99.9000) =      9.339 ms/op
     p(99.9900) =     19.940 ms/op
     p(99.9990) =     20.546 ms/op
     p(99.9999) =     20.611 ms/op
    p(100.0000) =     20.611 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.795 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.137 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.030 ±(99.9%) 0.011 ms/op
Iteration   1: 4.073 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.167 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   7.548 ms/op
                 listUser·p0.999:  12.878 ms/op
                 listUser·p0.9999: 17.334 ms/op
                 listUser·p1.00:   17.629 ms/op

Iteration   2: 4.002 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.491 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  15.413 ms/op
                 listUser·p0.9999: 27.361 ms/op
                 listUser·p1.00:   30.278 ms/op

Iteration   3: 4.007 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.315 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   5.284 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  15.788 ms/op
                 listUser·p0.9999: 25.560 ms/op
                 listUser·p1.00:   26.739 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238267
  mean =      4.027 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2474 
    [ 2.500,  5.000) = 207510 
    [ 5.000,  7.500) = 26396 
    [ 7.500, 10.000) = 1383 
    [10.000, 12.500) = 152 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 145 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      5.169 ms/op
     p(95.0000) =      5.849 ms/op
     p(99.0000) =      7.234 ms/op
     p(99.9000) =     14.929 ms/op
     p(99.9900) =     25.451 ms/op
     p(99.9990) =     30.089 ms/op
     p(99.9999) =     30.278 ms/op
    p(100.0000) =     30.278 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.507 ± 0.465  ops/ms
ClientGrpc.existUser                       thrpt       3  10.924 ± 2.183  ops/ms
ClientGrpc.getUser                         thrpt       3  10.556 ± 2.065  ops/ms
ClientGrpc.listUser                        thrpt       3   7.977 ± 2.026  ops/ms
ClientGrpc.createUser                       avgt       3   3.056 ± 0.501   ms/op
ClientGrpc.existUser                        avgt       3   2.894 ± 0.371   ms/op
ClientGrpc.getUser                          avgt       3   3.068 ± 0.756   ms/op
ClientGrpc.listUser                         avgt       3   4.014 ± 0.218   ms/op
ClientGrpc.createUser                     sample  314586   3.052 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.618           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.006           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.576           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.809           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.710           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.154           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.205           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.825           ms/op
ClientGrpc.existUser                      sample  327374   2.932 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.555           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.908           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.383           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.584           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.317           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.938           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.475           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.072           ms/op
ClientGrpc.getUser                        sample  312335   3.075 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.698           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.035           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.535           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.797           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.760           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.339           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.940           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.611           ms/op
ClientGrpc.listUser                       sample  238267   4.027 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.167           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.842           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.169           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.849           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.234           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.929           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.451           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.278           ms/op
