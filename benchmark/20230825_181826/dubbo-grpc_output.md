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
# Warmup Iteration   1: 4.348 ops/ms
# Warmup Iteration   2: 9.131 ops/ms
# Warmup Iteration   3: 9.979 ops/ms
Iteration   1: 10.709 ops/ms
Iteration   2: 10.846 ops/ms
Iteration   3: 10.651 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.735 ±(99.9%) 1.829 ops/ms [Average]
  (min, avg, max) = (10.651, 10.735, 10.846), stdev = 0.100
  CI (99.9%): [8.906, 12.564] (assumes normal distribution)


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
# Warmup Iteration   1: 8.119 ops/ms
# Warmup Iteration   2: 10.702 ops/ms
# Warmup Iteration   3: 10.966 ops/ms
Iteration   1: 11.249 ops/ms
Iteration   2: 11.224 ops/ms
Iteration   3: 10.965 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.146 ±(99.9%) 2.868 ops/ms [Average]
  (min, avg, max) = (10.965, 11.146, 11.249), stdev = 0.157
  CI (99.9%): [8.278, 14.014] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.064 ops/ms
# Warmup Iteration   2: 10.153 ops/ms
# Warmup Iteration   3: 10.437 ops/ms
Iteration   1: 10.453 ops/ms
Iteration   2: 10.626 ops/ms
Iteration   3: 10.554 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.544 ±(99.9%) 1.583 ops/ms [Average]
  (min, avg, max) = (10.453, 10.544, 10.626), stdev = 0.087
  CI (99.9%): [8.961, 12.127] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.077 ops/ms
# Warmup Iteration   2: 7.529 ops/ms
# Warmup Iteration   3: 8.092 ops/ms
Iteration   1: 8.074 ops/ms
Iteration   2: 8.124 ops/ms
Iteration   3: 8.010 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.070 ±(99.9%) 1.046 ops/ms [Average]
  (min, avg, max) = (8.010, 8.070, 8.124), stdev = 0.057
  CI (99.9%): [7.024, 9.115] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.218 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.187 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.003 ms/op
Iteration   1: 2.984 ±(99.9%) 0.003 ms/op
Iteration   2: 3.051 ±(99.9%) 0.003 ms/op
Iteration   3: 3.016 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.017 ±(99.9%) 0.609 ms/op [Average]
  (min, avg, max) = (2.984, 3.017, 3.051), stdev = 0.033
  CI (99.9%): [2.408, 3.626] (assumes normal distribution)


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
# Warmup Iteration   1: 3.978 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.012 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.885 ±(99.9%) 0.005 ms/op
Iteration   1: 2.913 ±(99.9%) 0.008 ms/op
Iteration   2: 2.952 ±(99.9%) 0.003 ms/op
Iteration   3: 2.888 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.918 ±(99.9%) 0.586 ms/op [Average]
  (min, avg, max) = (2.888, 2.918, 2.952), stdev = 0.032
  CI (99.9%): [2.332, 3.503] (assumes normal distribution)


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
# Warmup Iteration   1: 3.997 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.061 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.003 ms/op
Iteration   1: 3.035 ±(99.9%) 0.002 ms/op
Iteration   2: 2.987 ±(99.9%) 0.002 ms/op
Iteration   3: 3.048 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.023 ±(99.9%) 0.595 ms/op [Average]
  (min, avg, max) = (2.987, 3.023, 3.048), stdev = 0.033
  CI (99.9%): [2.428, 3.619] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.348 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.041 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.961 ±(99.9%) 0.009 ms/op
Iteration   1: 3.877 ±(99.9%) 0.019 ms/op
Iteration   2: 3.817 ±(99.9%) 0.025 ms/op
Iteration   3: 3.940 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.878 ±(99.9%) 1.128 ms/op [Average]
  (min, avg, max) = (3.817, 3.878, 3.940), stdev = 0.062
  CI (99.9%): [2.750, 5.006] (assumes normal distribution)


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
# Warmup Iteration   1: 3.970 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.131 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.007 ms/op
Iteration   1: 3.003 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.559 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  8.369 ms/op
                 createUser·p0.9999: 21.911 ms/op
                 createUser·p1.00:   22.184 ms/op

Iteration   2: 2.967 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.560 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  8.520 ms/op
                 createUser·p0.9999: 16.613 ms/op
                 createUser·p1.00:   17.170 ms/op

Iteration   3: 2.947 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.520 ms/op
                 createUser·p0.50:   2.920 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  10.748 ms/op
                 createUser·p0.9999: 30.900 ms/op
                 createUser·p1.00:   31.064 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 323343
  mean =      2.972 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31807 
    [ 2.500,  5.000) = 289707 
    [ 5.000,  7.500) = 1245 
    [ 7.500, 10.000) = 275 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.520 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      9.759 ms/op
     p(99.9900) =     27.593 ms/op
     p(99.9990) =     31.056 ms/op
     p(99.9999) =     31.064 ms/op
    p(100.0000) =     31.064 ms/op


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
# Warmup Iteration   1: 3.686 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.936 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.921 ±(99.9%) 0.006 ms/op
Iteration   1: 2.909 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.734 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  7.807 ms/op
                 existUser·p0.9999: 13.419 ms/op
                 existUser·p1.00:   14.303 ms/op

Iteration   2: 2.897 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.617 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.523 ms/op
                 existUser·p0.99:   4.547 ms/op
                 existUser·p0.999:  12.354 ms/op
                 existUser·p0.9999: 20.380 ms/op
                 existUser·p1.00:   22.708 ms/op

Iteration   3: 2.867 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.528 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.645 ms/op
                 existUser·p0.999:  8.681 ms/op
                 existUser·p0.9999: 25.723 ms/op
                 existUser·p1.00:   27.591 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331937
  mean =      2.891 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46726 
    [ 2.500,  5.000) = 283343 
    [ 5.000,  7.500) = 1292 
    [ 7.500, 10.000) = 304 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.528 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.379 ms/op
     p(95.0000) =      3.625 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      8.766 ms/op
     p(99.9900) =     23.587 ms/op
     p(99.9990) =     26.977 ms/op
     p(99.9999) =     27.591 ms/op
    p(100.0000) =     27.591 ms/op


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
# Warmup Iteration   1: 3.977 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.079 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.006 ms/op
Iteration   1: 3.056 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.841 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  7.889 ms/op
                 getUser·p0.9999: 11.731 ms/op
                 getUser·p1.00:   12.370 ms/op

Iteration   2: 2.993 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.617 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.424 ms/op
                 getUser·p0.95:   3.654 ms/op
                 getUser·p0.99:   4.653 ms/op
                 getUser·p0.999:  11.076 ms/op
                 getUser·p0.9999: 18.547 ms/op
                 getUser·p1.00:   18.809 ms/op

Iteration   3: 2.986 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.554 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.420 ms/op
                 getUser·p0.95:   3.650 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  8.019 ms/op
                 getUser·p0.9999: 15.813 ms/op
                 getUser·p1.00:   16.679 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318522
  mean =      3.011 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1325 
    [ 1.250,  2.500) = 22443 
    [ 2.500,  3.750) = 280261 
    [ 3.750,  5.000) = 12760 
    [ 5.000,  6.250) = 756 
    [ 6.250,  7.500) = 488 
    [ 7.500,  8.750) = 187 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 50 
    [11.250, 12.500) = 89 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 40 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.554 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      8.355 ms/op
     p(99.9900) =     18.158 ms/op
     p(99.9990) =     18.731 ms/op
     p(99.9999) =     18.809 ms/op
    p(100.0000) =     18.809 ms/op


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
# Warmup Iteration   1: 5.010 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.127 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.969 ±(99.9%) 0.010 ms/op
Iteration   1: 3.967 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.194 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  12.851 ms/op
                 listUser·p0.9999: 19.366 ms/op
                 listUser·p1.00:   20.906 ms/op

Iteration   2: 3.977 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.118 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   7.227 ms/op
                 listUser·p0.999:  16.941 ms/op
                 listUser·p0.9999: 24.441 ms/op
                 listUser·p1.00:   25.297 ms/op

Iteration   3: 4.006 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.692 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  16.353 ms/op
                 listUser·p0.9999: 21.103 ms/op
                 listUser·p1.00:   21.365 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240958
  mean =      3.984 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3134 
    [ 2.500,  5.000) = 215957 
    [ 5.000,  7.500) = 20358 
    [ 7.500, 10.000) = 936 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 185 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.692 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      4.899 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =      6.996 ms/op
     p(99.9000) =     15.156 ms/op
     p(99.9900) =     22.249 ms/op
     p(99.9990) =     25.184 ms/op
     p(99.9999) =     25.297 ms/op
    p(100.0000) =     25.297 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.735 ± 1.829  ops/ms
ClientGrpc.existUser                       thrpt       3  11.146 ± 2.868  ops/ms
ClientGrpc.getUser                         thrpt       3  10.544 ± 1.583  ops/ms
ClientGrpc.listUser                        thrpt       3   8.070 ± 1.046  ops/ms
ClientGrpc.createUser                       avgt       3   3.017 ± 0.609   ms/op
ClientGrpc.existUser                        avgt       3   2.918 ± 0.586   ms/op
ClientGrpc.getUser                          avgt       3   3.023 ± 0.595   ms/op
ClientGrpc.listUser                         avgt       3   3.878 ± 1.128   ms/op
ClientGrpc.createUser                     sample  323343   2.972 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.520           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.953           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.494           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.772           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.489           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.759           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.593           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.064           ms/op
ClientGrpc.existUser                      sample  331937   2.891 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.528           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.379           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.625           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.530           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.766           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.587           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.591           ms/op
ClientGrpc.getUser                        sample  318522   3.011 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.554           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.998           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.506           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.719           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.424           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.355           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.158           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.809           ms/op
ClientGrpc.listUser                       sample  240958   3.984 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.692           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.826           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.899           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.743           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.996           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.156           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.249           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.297           ms/op
