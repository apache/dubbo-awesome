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
# Warmup Iteration   1: 3.715 ops/ms
# Warmup Iteration   2: 8.605 ops/ms
# Warmup Iteration   3: 9.547 ops/ms
Iteration   1: 9.834 ops/ms
Iteration   2: 10.051 ops/ms
Iteration   3: 9.924 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.936 ±(99.9%) 1.984 ops/ms [Average]
  (min, avg, max) = (9.834, 9.936, 10.051), stdev = 0.109
  CI (99.9%): [7.952, 11.920] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 6.983 ops/ms
# Warmup Iteration   2: 10.082 ops/ms
# Warmup Iteration   3: 10.798 ops/ms
Iteration   1: 10.841 ops/ms
Iteration   2: 10.963 ops/ms
Iteration   3: 10.914 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.906 ±(99.9%) 1.125 ops/ms [Average]
  (min, avg, max) = (10.841, 10.906, 10.963), stdev = 0.062
  CI (99.9%): [9.781, 12.031] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.718 ops/ms
# Warmup Iteration   2: 9.731 ops/ms
# Warmup Iteration   3: 10.243 ops/ms
Iteration   1: 10.231 ops/ms
Iteration   2: 10.422 ops/ms
Iteration   3: 10.367 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.340 ±(99.9%) 1.792 ops/ms [Average]
  (min, avg, max) = (10.231, 10.340, 10.422), stdev = 0.098
  CI (99.9%): [8.548, 12.132] (assumes normal distribution)


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
# Warmup Iteration   1: 5.156 ops/ms
# Warmup Iteration   2: 7.662 ops/ms
# Warmup Iteration   3: 7.539 ops/ms
Iteration   1: 7.686 ops/ms
Iteration   2: 7.568 ops/ms
Iteration   3: 7.805 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.686 ±(99.9%) 2.165 ops/ms [Average]
  (min, avg, max) = (7.568, 7.686, 7.805), stdev = 0.119
  CI (99.9%): [5.522, 9.851] (assumes normal distribution)


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
# Warmup Iteration   1: 4.594 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.321 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.172 ±(99.9%) 0.003 ms/op
Iteration   1: 3.174 ±(99.9%) 0.002 ms/op
Iteration   2: 3.138 ±(99.9%) 0.002 ms/op
Iteration   3: 3.123 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.145 ±(99.9%) 0.481 ms/op [Average]
  (min, avg, max) = (3.123, 3.145, 3.174), stdev = 0.026
  CI (99.9%): [2.664, 3.626] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.868 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.213 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.001 ms/op
Iteration   1: 2.998 ±(99.9%) 0.001 ms/op
Iteration   2: 2.847 ±(99.9%) 0.003 ms/op
Iteration   3: 2.936 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.927 ±(99.9%) 1.383 ms/op [Average]
  (min, avg, max) = (2.847, 2.927, 2.998), stdev = 0.076
  CI (99.9%): [1.545, 4.310] (assumes normal distribution)


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
# Warmup Iteration   1: 4.590 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.270 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.108 ±(99.9%) 0.004 ms/op
Iteration   1: 3.086 ±(99.9%) 0.002 ms/op
Iteration   2: 3.084 ±(99.9%) 0.003 ms/op
Iteration   3: 3.056 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.076 ±(99.9%) 0.305 ms/op [Average]
  (min, avg, max) = (3.056, 3.076, 3.086), stdev = 0.017
  CI (99.9%): [2.770, 3.381] (assumes normal distribution)


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
# Warmup Iteration   1: 5.454 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.307 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.035 ±(99.9%) 0.008 ms/op
Iteration   1: 4.015 ±(99.9%) 0.014 ms/op
Iteration   2: 4.099 ±(99.9%) 0.020 ms/op
Iteration   3: 4.139 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.084 ±(99.9%) 1.153 ms/op [Average]
  (min, avg, max) = (4.015, 4.084, 4.139), stdev = 0.063
  CI (99.9%): [2.932, 5.237] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.727 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.370 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.132 ±(99.9%) 0.006 ms/op
Iteration   1: 3.144 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.662 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   4.084 ms/op
                 createUser·p0.99:   5.112 ms/op
                 createUser·p0.999:  9.011 ms/op
                 createUser·p0.9999: 13.842 ms/op
                 createUser·p1.00:   14.320 ms/op

Iteration   2: 3.124 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.541 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   4.940 ms/op
                 createUser·p0.999:  9.676 ms/op
                 createUser·p0.9999: 17.803 ms/op
                 createUser·p1.00:   18.153 ms/op

Iteration   3: 3.166 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.746 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   4.047 ms/op
                 createUser·p0.99:   4.743 ms/op
                 createUser·p0.999:  9.421 ms/op
                 createUser·p0.9999: 21.293 ms/op
                 createUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305115
  mean =      3.145 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19212 
    [ 2.500,  5.000) = 283089 
    [ 5.000,  7.500) = 2115 
    [ 7.500, 10.000) = 445 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.541 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      4.039 ms/op
     p(99.0000) =      4.907 ms/op
     p(99.9000) =      9.290 ms/op
     p(99.9900) =     19.235 ms/op
     p(99.9990) =     21.429 ms/op
     p(99.9999) =     21.463 ms/op
    p(100.0000) =     21.463 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.109 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.054 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.943 ±(99.9%) 0.007 ms/op
Iteration   1: 2.940 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.831 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.620 ms/op
                 existUser·p0.999:  8.094 ms/op
                 existUser·p0.9999: 19.108 ms/op
                 existUser·p1.00:   19.661 ms/op

Iteration   2: 2.833 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.650 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  7.373 ms/op
                 existUser·p0.9999: 23.452 ms/op
                 existUser·p1.00:   23.855 ms/op

Iteration   3: 2.971 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.715 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  11.436 ms/op
                 existUser·p0.9999: 18.489 ms/op
                 existUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329445
  mean =      2.913 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38272 
    [ 2.500,  5.000) = 288982 
    [ 5.000,  7.500) = 1644 
    [ 7.500, 10.000) = 303 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.650 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.408 ms/op
     p(95.0000) =      3.629 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      8.866 ms/op
     p(99.9900) =     19.890 ms/op
     p(99.9990) =     23.747 ms/op
     p(99.9999) =     23.855 ms/op
    p(100.0000) =     23.855 ms/op


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
# Warmup Iteration   1: 4.460 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.186 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.101 ±(99.9%) 0.007 ms/op
Iteration   1: 3.049 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.827 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.628 ms/op
                 getUser·p0.999:  8.962 ms/op
                 getUser·p0.9999: 28.033 ms/op
                 getUser·p1.00:   28.443 ms/op

Iteration   2: 3.071 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.751 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.953 ms/op
                 getUser·p0.99:   4.932 ms/op
                 getUser·p0.999:  8.762 ms/op
                 getUser·p0.9999: 33.285 ms/op
                 getUser·p1.00:   33.817 ms/op

Iteration   3: 3.033 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.625 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.809 ms/op
                 getUser·p0.999:  7.911 ms/op
                 getUser·p0.9999: 22.786 ms/op
                 getUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314496
  mean =      3.051 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23541 
    [ 2.500,  5.000) = 288488 
    [ 5.000,  7.500) = 1898 
    [ 7.500, 10.000) = 332 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.625 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.809 ms/op
     p(99.9000) =      8.774 ms/op
     p(99.9900) =     32.753 ms/op
     p(99.9990) =     33.742 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


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
# Warmup Iteration   1: 5.593 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.219 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.039 ±(99.9%) 0.011 ms/op
Iteration   1: 4.052 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.280 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   5.259 ms/op
                 listUser·p0.95:   6.021 ms/op
                 listUser·p0.99:   7.299 ms/op
                 listUser·p0.999:  12.793 ms/op
                 listUser·p0.9999: 23.206 ms/op
                 listUser·p1.00:   23.691 ms/op

Iteration   2: 3.993 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.339 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   5.988 ms/op
                 listUser·p0.99:   7.234 ms/op
                 listUser·p0.999:  16.151 ms/op
                 listUser·p0.9999: 21.889 ms/op
                 listUser·p1.00:   21.955 ms/op

Iteration   3: 4.070 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.888 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   7.563 ms/op
                 listUser·p0.999:  18.711 ms/op
                 listUser·p0.9999: 20.981 ms/op
                 listUser·p1.00:   24.314 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237886
  mean =      4.038 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2822 
    [ 2.500,  5.000) = 206423 
    [ 5.000,  7.500) = 26538 
    [ 7.500, 10.000) = 1606 
    [10.000, 12.500) = 117 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 154 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.888 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      5.194 ms/op
     p(95.0000) =      5.972 ms/op
     p(99.0000) =      7.365 ms/op
     p(99.9000) =     16.255 ms/op
     p(99.9900) =     22.715 ms/op
     p(99.9990) =     23.666 ms/op
     p(99.9999) =     24.314 ms/op
    p(100.0000) =     24.314 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.936 ± 1.984  ops/ms
ClientGrpc.existUser                       thrpt       3  10.906 ± 1.125  ops/ms
ClientGrpc.getUser                         thrpt       3  10.340 ± 1.792  ops/ms
ClientGrpc.listUser                        thrpt       3   7.686 ± 2.165  ops/ms
ClientGrpc.createUser                       avgt       3   3.145 ± 0.481   ms/op
ClientGrpc.existUser                        avgt       3   2.927 ± 1.383   ms/op
ClientGrpc.getUser                          avgt       3   3.076 ± 0.305   ms/op
ClientGrpc.listUser                         avgt       3   4.084 ± 1.153   ms/op
ClientGrpc.createUser                     sample  305115   3.145 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.541           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.109           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.740           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.039           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.907           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.290           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.235           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.463           ms/op
ClientGrpc.existUser                      sample  329445   2.913 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.650           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.408           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.629           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.481           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.866           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.890           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.855           ms/op
ClientGrpc.getUser                        sample  314496   3.051 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.625           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.019           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.572           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.826           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.809           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.774           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          32.753           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          33.817           ms/op
ClientGrpc.listUser                       sample  237886   4.038 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.888           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.834           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.194           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.972           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.365           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.255           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.715           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.314           ms/op
