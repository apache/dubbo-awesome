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
# Warmup Iteration   1: 4.463 ops/ms
# Warmup Iteration   2: 9.457 ops/ms
# Warmup Iteration   3: 10.018 ops/ms
Iteration   1: 10.246 ops/ms
Iteration   2: 10.789 ops/ms
Iteration   3: 10.298 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.444 ±(99.9%) 5.469 ops/ms [Average]
  (min, avg, max) = (10.246, 10.444, 10.789), stdev = 0.300
  CI (99.9%): [4.975, 15.913] (assumes normal distribution)


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
# Warmup Iteration   1: 8.424 ops/ms
# Warmup Iteration   2: 10.709 ops/ms
# Warmup Iteration   3: 10.910 ops/ms
Iteration   1: 11.246 ops/ms
Iteration   2: 10.847 ops/ms
Iteration   3: 10.753 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.949 ±(99.9%) 4.775 ops/ms [Average]
  (min, avg, max) = (10.753, 10.949, 11.246), stdev = 0.262
  CI (99.9%): [6.174, 15.724] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.155 ops/ms
# Warmup Iteration   2: 10.146 ops/ms
# Warmup Iteration   3: 10.543 ops/ms
Iteration   1: 10.396 ops/ms
Iteration   2: 10.265 ops/ms
Iteration   3: 10.281 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.314 ±(99.9%) 1.306 ops/ms [Average]
  (min, avg, max) = (10.265, 10.314, 10.396), stdev = 0.072
  CI (99.9%): [9.008, 11.620] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.927 ops/ms
# Warmup Iteration   2: 7.680 ops/ms
# Warmup Iteration   3: 7.766 ops/ms
Iteration   1: 7.995 ops/ms
Iteration   2: 8.086 ops/ms
Iteration   3: 7.823 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.968 ±(99.9%) 2.434 ops/ms [Average]
  (min, avg, max) = (7.823, 7.968, 8.086), stdev = 0.133
  CI (99.9%): [5.534, 10.401] (assumes normal distribution)


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
# Warmup Iteration   1: 4.106 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.224 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.081 ±(99.9%) 0.003 ms/op
Iteration   1: 3.057 ±(99.9%) 0.010 ms/op
Iteration   2: 3.009 ±(99.9%) 0.005 ms/op
Iteration   3: 3.059 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.042 ±(99.9%) 0.511 ms/op [Average]
  (min, avg, max) = (3.009, 3.042, 3.059), stdev = 0.028
  CI (99.9%): [2.531, 3.553] (assumes normal distribution)


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
# Warmup Iteration   1: 3.819 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.017 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.968 ±(99.9%) 0.002 ms/op
Iteration   1: 2.959 ±(99.9%) 0.002 ms/op
Iteration   2: 2.925 ±(99.9%) 0.002 ms/op
Iteration   3: 3.006 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.963 ±(99.9%) 0.739 ms/op [Average]
  (min, avg, max) = (2.925, 2.963, 3.006), stdev = 0.041
  CI (99.9%): [2.224, 3.702] (assumes normal distribution)


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
# Warmup Iteration   1: 4.117 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.120 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.009 ±(99.9%) 0.003 ms/op
Iteration   1: 3.045 ±(99.9%) 0.002 ms/op
Iteration   2: 3.163 ±(99.9%) 0.006 ms/op
Iteration   3: 3.100 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.103 ±(99.9%) 1.078 ms/op [Average]
  (min, avg, max) = (3.045, 3.103, 3.163), stdev = 0.059
  CI (99.9%): [2.025, 4.180] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.814 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.054 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 4.074 ±(99.9%) 0.010 ms/op
Iteration   1: 4.049 ±(99.9%) 0.016 ms/op
Iteration   2: 3.921 ±(99.9%) 0.034 ms/op
Iteration   3: 4.025 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.998 ±(99.9%) 1.249 ms/op [Average]
  (min, avg, max) = (3.921, 3.998, 4.049), stdev = 0.068
  CI (99.9%): [2.750, 5.247] (assumes normal distribution)


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
# Warmup Iteration   1: 3.981 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.165 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.085 ±(99.9%) 0.007 ms/op
Iteration   1: 3.130 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.798 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   4.002 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  9.562 ms/op
                 createUser·p0.9999: 17.484 ms/op
                 createUser·p1.00:   17.891 ms/op

Iteration   2: 3.032 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.678 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  9.028 ms/op
                 createUser·p0.9999: 16.628 ms/op
                 createUser·p1.00:   17.138 ms/op

Iteration   3: 3.113 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.459 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  11.473 ms/op
                 createUser·p0.9999: 17.850 ms/op
                 createUser·p1.00:   18.252 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310436
  mean =      3.091 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1246 
    [ 1.250,  2.500) = 19944 
    [ 2.500,  3.750) = 265376 
    [ 3.750,  5.000) = 22439 
    [ 5.000,  6.250) = 667 
    [ 6.250,  7.500) = 204 
    [ 7.500,  8.750) = 119 
    [ 8.750, 10.000) = 128 
    [10.000, 11.250) = 66 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 77 
    [15.000, 16.250) = 47 
    [16.250, 17.500) = 60 
    [17.500, 18.750) = 36 

  Percentiles, ms/op:
      p(0.0000) =      0.459 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =     10.153 ms/op
     p(99.9900) =     17.628 ms/op
     p(99.9990) =     18.147 ms/op
     p(99.9999) =     18.252 ms/op
    p(100.0000) =     18.252 ms/op


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
# Warmup Iteration   1: 3.874 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.020 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.006 ms/op
Iteration   1: 3.018 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.688 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.690 ms/op
                 existUser·p0.95:   3.879 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  6.349 ms/op
                 existUser·p0.9999: 14.605 ms/op
                 existUser·p1.00:   15.073 ms/op

Iteration   2: 3.038 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.743 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.662 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   4.162 ms/op
                 existUser·p0.999:  5.835 ms/op
                 existUser·p0.9999: 15.761 ms/op
                 existUser·p1.00:   16.581 ms/op

Iteration   3: 2.928 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.657 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  6.244 ms/op
                 existUser·p0.9999: 17.469 ms/op
                 existUser·p1.00:   18.121 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 320592
  mean =      2.994 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2218 
    [ 1.250,  2.500) = 39231 
    [ 2.500,  3.750) = 259044 
    [ 3.750,  5.000) = 19352 
    [ 5.000,  6.250) = 431 
    [ 6.250,  7.500) = 89 
    [ 7.500,  8.750) = 45 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 85 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.657 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      6.229 ms/op
     p(99.9900) =     16.231 ms/op
     p(99.9990) =     17.943 ms/op
     p(99.9999) =     18.121 ms/op
    p(100.0000) =     18.121 ms/op


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
# Warmup Iteration   1: 3.916 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.156 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.125 ±(99.9%) 0.007 ms/op
Iteration   1: 3.128 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.630 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.838 ms/op
                 getUser·p0.95:   4.047 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  8.074 ms/op
                 getUser·p0.9999: 21.791 ms/op
                 getUser·p1.00:   23.855 ms/op

Iteration   2: 3.043 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.587 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  7.201 ms/op
                 getUser·p0.9999: 32.850 ms/op
                 getUser·p1.00:   34.079 ms/op

Iteration   3: 3.067 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.547 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.895 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  6.741 ms/op
                 getUser·p0.9999: 22.905 ms/op
                 getUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311776
  mean =      3.079 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31609 
    [ 2.500,  5.000) = 278860 
    [ 5.000,  7.500) = 1023 
    [ 7.500, 10.000) = 124 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.547 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      7.244 ms/op
     p(99.9900) =     31.821 ms/op
     p(99.9990) =     33.508 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


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
# Warmup Iteration   1: 4.015 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.338 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.136 ±(99.9%) 0.013 ms/op
Iteration   1: 4.015 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.012 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   7.260 ms/op
                 listUser·p0.999:  13.122 ms/op
                 listUser·p0.9999: 18.483 ms/op
                 listUser·p1.00:   19.038 ms/op

Iteration   2: 4.016 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.866 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  14.818 ms/op
                 listUser·p0.9999: 24.707 ms/op
                 listUser·p1.00:   25.035 ms/op

Iteration   3: 4.006 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.828 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  16.368 ms/op
                 listUser·p0.9999: 22.479 ms/op
                 listUser·p1.00:   22.807 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239305
  mean =      4.012 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4055 
    [ 2.500,  5.000) = 207556 
    [ 5.000,  7.500) = 26221 
    [ 7.500, 10.000) = 844 
    [10.000, 12.500) = 222 
    [12.500, 15.000) = 137 
    [15.000, 17.500) = 125 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.828 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      5.136 ms/op
     p(95.0000) =      5.767 ms/op
     p(99.0000) =      7.004 ms/op
     p(99.9000) =     15.527 ms/op
     p(99.9900) =     23.434 ms/op
     p(99.9990) =     24.970 ms/op
     p(99.9999) =     25.035 ms/op
    p(100.0000) =     25.035 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.444 ± 5.469  ops/ms
ClientGrpc.existUser                       thrpt       3  10.949 ± 4.775  ops/ms
ClientGrpc.getUser                         thrpt       3  10.314 ± 1.306  ops/ms
ClientGrpc.listUser                        thrpt       3   7.968 ± 2.434  ops/ms
ClientGrpc.createUser                       avgt       3   3.042 ± 0.511   ms/op
ClientGrpc.existUser                        avgt       3   2.963 ± 0.739   ms/op
ClientGrpc.getUser                          avgt       3   3.103 ± 1.078   ms/op
ClientGrpc.listUser                         avgt       3   3.998 ± 1.249   ms/op
ClientGrpc.createUser                     sample  310436   3.091 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.459           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.064           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.654           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.891           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.415           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.153           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.628           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.252           ms/op
ClientGrpc.existUser                      sample  320592   2.994 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.657           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.978           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.617           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.809           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.284           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.229           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.231           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.121           ms/op
ClientGrpc.getUser                        sample  311776   3.079 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.547           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.064           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.731           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.932           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.424           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.244           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          31.821           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          34.079           ms/op
ClientGrpc.listUser                       sample  239305   4.012 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.828           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.830           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.136           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.767           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.004           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.527           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.434           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.035           ms/op
