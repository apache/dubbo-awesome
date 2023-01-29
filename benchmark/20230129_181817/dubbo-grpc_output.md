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
# Warmup Iteration   1: 4.374 ops/ms
# Warmup Iteration   2: 9.263 ops/ms
# Warmup Iteration   3: 10.244 ops/ms
Iteration   1: 10.601 ops/ms
Iteration   2: 10.414 ops/ms
Iteration   3: 10.305 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.440 ±(99.9%) 2.734 ops/ms [Average]
  (min, avg, max) = (10.305, 10.440, 10.601), stdev = 0.150
  CI (99.9%): [7.706, 13.175] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.273 ops/ms
# Warmup Iteration   2: 10.494 ops/ms
# Warmup Iteration   3: 11.006 ops/ms
Iteration   1: 11.042 ops/ms
Iteration   2: 10.932 ops/ms
Iteration   3: 10.934 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.969 ±(99.9%) 1.150 ops/ms [Average]
  (min, avg, max) = (10.932, 10.969, 11.042), stdev = 0.063
  CI (99.9%): [9.819, 12.119] (assumes normal distribution)


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
# Warmup Iteration   1: 7.650 ops/ms
# Warmup Iteration   2: 10.379 ops/ms
# Warmup Iteration   3: 10.781 ops/ms
Iteration   1: 10.715 ops/ms
Iteration   2: 10.469 ops/ms
Iteration   3: 10.272 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.485 ±(99.9%) 4.041 ops/ms [Average]
  (min, avg, max) = (10.272, 10.485, 10.715), stdev = 0.222
  CI (99.9%): [6.444, 14.527] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.529 ops/ms
# Warmup Iteration   2: 7.752 ops/ms
# Warmup Iteration   3: 7.851 ops/ms
Iteration   1: 8.025 ops/ms
Iteration   2: 8.013 ops/ms
Iteration   3: 7.964 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.000 ±(99.9%) 0.587 ops/ms [Average]
  (min, avg, max) = (7.964, 8.000, 8.025), stdev = 0.032
  CI (99.9%): [7.414, 8.587] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.764 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.064 ±(99.9%) 0.003 ms/op
Iteration   1: 3.166 ±(99.9%) 0.002 ms/op
Iteration   2: 3.139 ±(99.9%) 0.001 ms/op
Iteration   3: 3.123 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.142 ±(99.9%) 0.396 ms/op [Average]
  (min, avg, max) = (3.123, 3.142, 3.166), stdev = 0.022
  CI (99.9%): [2.746, 3.538] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.624 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 2.906 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.939 ±(99.9%) 0.003 ms/op
Iteration   1: 2.957 ±(99.9%) 0.006 ms/op
Iteration   2: 2.809 ±(99.9%) 0.003 ms/op
Iteration   3: 2.905 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.890 ±(99.9%) 1.375 ms/op [Average]
  (min, avg, max) = (2.809, 2.890, 2.957), stdev = 0.075
  CI (99.9%): [1.515, 4.266] (assumes normal distribution)


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
# Warmup Iteration   1: 3.576 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.128 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.012 ms/op
Iteration   1: 3.034 ±(99.9%) 0.001 ms/op
Iteration   2: 2.990 ±(99.9%) 0.002 ms/op
Iteration   3: 3.013 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.012 ±(99.9%) 0.400 ms/op [Average]
  (min, avg, max) = (2.990, 3.012, 3.034), stdev = 0.022
  CI (99.9%): [2.612, 3.413] (assumes normal distribution)


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
# Warmup Iteration   1: 4.008 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.128 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.124 ±(99.9%) 0.009 ms/op
Iteration   1: 4.013 ±(99.9%) 0.016 ms/op
Iteration   2: 4.067 ±(99.9%) 0.020 ms/op
Iteration   3: 3.900 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.993 ±(99.9%) 1.551 ms/op [Average]
  (min, avg, max) = (3.900, 3.993, 4.067), stdev = 0.085
  CI (99.9%): [2.443, 5.544] (assumes normal distribution)


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
# Warmup Iteration   1: 3.613 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.124 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.068 ±(99.9%) 0.007 ms/op
Iteration   1: 3.048 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.621 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   4.162 ms/op
                 createUser·p0.999:  5.965 ms/op
                 createUser·p0.9999: 12.001 ms/op
                 createUser·p1.00:   12.255 ms/op

Iteration   2: 3.154 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.813 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.850 ms/op
                 createUser·p0.95:   4.022 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  7.539 ms/op
                 createUser·p0.9999: 13.023 ms/op
                 createUser·p1.00:   13.222 ms/op

Iteration   3: 3.150 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.748 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.895 ms/op
                 createUser·p0.95:   4.059 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  9.493 ms/op
                 createUser·p0.9999: 16.040 ms/op
                 createUser·p1.00:   18.153 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308152
  mean =      3.117 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1253 
    [ 1.250,  2.500) = 26413 
    [ 2.500,  3.750) = 242896 
    [ 3.750,  5.000) = 36693 
    [ 5.000,  6.250) = 384 
    [ 6.250,  7.500) = 175 
    [ 7.500,  8.750) = 68 
    [ 8.750, 10.000) = 43 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 56 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.621 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      3.990 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      8.019 ms/op
     p(99.9900) =     16.007 ms/op
     p(99.9990) =     18.017 ms/op
     p(99.9999) =     18.153 ms/op
    p(100.0000) =     18.153 ms/op


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
# Warmup Iteration   1: 3.739 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.909 ±(99.9%) 0.006 ms/op
Iteration   1: 2.888 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.638 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.076 ms/op
                 existUser·p0.999:  6.998 ms/op
                 existUser·p0.9999: 12.878 ms/op
                 existUser·p1.00:   13.058 ms/op

Iteration   2: 2.937 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.759 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.580 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   4.100 ms/op
                 existUser·p0.999:  6.551 ms/op
                 existUser·p0.9999: 12.503 ms/op
                 existUser·p1.00:   12.812 ms/op

Iteration   3: 2.896 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.484 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.125 ms/op
                 existUser·p0.999:  10.142 ms/op
                 existUser·p0.9999: 14.499 ms/op
                 existUser·p1.00:   14.860 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330554
  mean =      2.907 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4020 
    [ 1.250,  2.500) = 48224 
    [ 2.500,  3.750) = 265545 
    [ 3.750,  5.000) = 12020 
    [ 5.000,  6.250) = 198 
    [ 6.250,  7.500) = 229 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 46 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.484 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      4.100 ms/op
     p(99.9000) =      7.360 ms/op
     p(99.9900) =     13.349 ms/op
     p(99.9990) =     14.785 ms/op
     p(99.9999) =     14.860 ms/op
    p(100.0000) =     14.860 ms/op


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
# Warmup Iteration   1: 3.856 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.062 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.007 ms/op
Iteration   1: 3.161 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.586 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.883 ms/op
                 getUser·p0.95:   4.051 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  7.550 ms/op
                 getUser·p0.9999: 15.645 ms/op
                 getUser·p1.00:   16.056 ms/op

Iteration   2: 3.116 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.692 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  9.154 ms/op
                 getUser·p0.9999: 16.457 ms/op
                 getUser·p1.00:   16.646 ms/op

Iteration   3: 3.061 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.604 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  6.869 ms/op
                 getUser·p0.9999: 20.349 ms/op
                 getUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 308342
  mean =      3.113 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28594 
    [ 2.500,  5.000) = 278933 
    [ 5.000,  7.500) = 404 
    [ 7.500, 10.000) = 208 
    [10.000, 12.500) = 11 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.586 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      8.255 ms/op
     p(99.9900) =     17.809 ms/op
     p(99.9990) =     20.477 ms/op
     p(99.9999) =     20.611 ms/op
    p(100.0000) =     20.611 ms/op


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
# Warmup Iteration   1: 4.677 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.149 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.983 ±(99.9%) 0.011 ms/op
Iteration   1: 3.938 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.280 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.423 ms/op
                 listUser·p0.99:   6.537 ms/op
                 listUser·p0.999:  13.284 ms/op
                 listUser·p0.9999: 18.739 ms/op
                 listUser·p1.00:   19.137 ms/op

Iteration   2: 4.001 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.717 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  15.615 ms/op
                 listUser·p0.9999: 19.595 ms/op
                 listUser·p1.00:   20.087 ms/op

Iteration   3: 3.898 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.292 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  13.762 ms/op
                 listUser·p0.9999: 16.803 ms/op
                 listUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243176
  mean =      3.946 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4577 
    [ 2.500,  5.000) = 212251 
    [ 5.000,  7.500) = 25276 
    [ 7.500, 10.000) = 519 
    [10.000, 12.500) = 200 
    [12.500, 15.000) = 158 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.717 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      5.054 ms/op
     p(95.0000) =      5.472 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     14.153 ms/op
     p(99.9900) =     18.711 ms/op
     p(99.9990) =     19.979 ms/op
     p(99.9999) =     20.087 ms/op
    p(100.0000) =     20.087 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.440 ± 2.734  ops/ms
ClientGrpc.existUser                       thrpt       3  10.969 ± 1.150  ops/ms
ClientGrpc.getUser                         thrpt       3  10.485 ± 4.041  ops/ms
ClientGrpc.listUser                        thrpt       3   8.000 ± 0.587  ops/ms
ClientGrpc.createUser                       avgt       3   3.142 ± 0.396   ms/op
ClientGrpc.existUser                        avgt       3   2.890 ± 1.375   ms/op
ClientGrpc.getUser                          avgt       3   3.012 ± 0.400   ms/op
ClientGrpc.listUser                         avgt       3   3.993 ± 1.551   ms/op
ClientGrpc.createUser                     sample  308152   3.117 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.621           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.092           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.813           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.990           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.268           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.019           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.007           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.153           ms/op
ClientGrpc.existUser                      sample  330554   2.907 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.484           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.916           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.494           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.686           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.100           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.360           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.349           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          14.860           ms/op
ClientGrpc.getUser                        sample  308342   3.113 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.586           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.092           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.809           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.977           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.301           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.255           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.809           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.611           ms/op
ClientGrpc.listUser                       sample  243176   3.946 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.717           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.785           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.054           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.472           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.717           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.153           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.711           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.087           ms/op
