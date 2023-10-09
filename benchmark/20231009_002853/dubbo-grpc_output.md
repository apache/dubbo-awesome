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
# Warmup Iteration   1: 4.493 ops/ms
# Warmup Iteration   2: 9.092 ops/ms
# Warmup Iteration   3: 10.120 ops/ms
Iteration   1: 10.478 ops/ms
Iteration   2: 10.423 ops/ms
Iteration   3: 10.418 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.439 ±(99.9%) 0.607 ops/ms [Average]
  (min, avg, max) = (10.418, 10.439, 10.478), stdev = 0.033
  CI (99.9%): [9.833, 11.046] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.607 ops/ms
# Warmup Iteration   2: 10.985 ops/ms
# Warmup Iteration   3: 10.733 ops/ms
Iteration   1: 10.793 ops/ms
Iteration   2: 11.019 ops/ms
Iteration   3: 10.821 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.878 ±(99.9%) 2.250 ops/ms [Average]
  (min, avg, max) = (10.793, 10.878, 11.019), stdev = 0.123
  CI (99.9%): [8.628, 13.128] (assumes normal distribution)


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
# Warmup Iteration   1: 7.359 ops/ms
# Warmup Iteration   2: 10.270 ops/ms
# Warmup Iteration   3: 10.256 ops/ms
Iteration   1: 10.469 ops/ms
Iteration   2: 10.258 ops/ms
Iteration   3: 10.386 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.371 ±(99.9%) 1.943 ops/ms [Average]
  (min, avg, max) = (10.258, 10.371, 10.469), stdev = 0.107
  CI (99.9%): [8.428, 12.314] (assumes normal distribution)


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
# Warmup Iteration   1: 5.790 ops/ms
# Warmup Iteration   2: 8.071 ops/ms
# Warmup Iteration   3: 8.225 ops/ms
Iteration   1: 8.420 ops/ms
Iteration   2: 8.666 ops/ms
Iteration   3: 8.386 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.491 ±(99.9%) 2.785 ops/ms [Average]
  (min, avg, max) = (8.386, 8.491, 8.666), stdev = 0.153
  CI (99.9%): [5.706, 11.276] (assumes normal distribution)


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
# Warmup Iteration   1: 4.121 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.108 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.115 ±(99.9%) 0.003 ms/op
Iteration   1: 3.122 ±(99.9%) 0.004 ms/op
Iteration   2: 2.999 ±(99.9%) 0.002 ms/op
Iteration   3: 3.081 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.067 ±(99.9%) 1.135 ms/op [Average]
  (min, avg, max) = (2.999, 3.067, 3.122), stdev = 0.062
  CI (99.9%): [1.932, 4.202] (assumes normal distribution)


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
# Warmup Iteration   1: 3.474 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.976 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.945 ±(99.9%) 0.006 ms/op
Iteration   1: 2.975 ±(99.9%) 0.002 ms/op
Iteration   2: 2.867 ±(99.9%) 0.004 ms/op
Iteration   3: 2.933 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.925 ±(99.9%) 0.993 ms/op [Average]
  (min, avg, max) = (2.867, 2.925, 2.975), stdev = 0.054
  CI (99.9%): [1.932, 3.919] (assumes normal distribution)


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
# Warmup Iteration   1: 4.244 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.171 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.107 ±(99.9%) 0.003 ms/op
Iteration   1: 3.062 ±(99.9%) 0.003 ms/op
Iteration   2: 3.082 ±(99.9%) 0.003 ms/op
Iteration   3: 3.084 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.076 ±(99.9%) 0.219 ms/op [Average]
  (min, avg, max) = (3.062, 3.076, 3.084), stdev = 0.012
  CI (99.9%): [2.857, 3.295] (assumes normal distribution)


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
# Warmup Iteration   1: 5.149 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.918 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.897 ±(99.9%) 0.072 ms/op
Iteration   1: 3.814 ±(99.9%) 0.023 ms/op
Iteration   2: 3.798 ±(99.9%) 0.011 ms/op
Iteration   3: 3.887 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.833 ±(99.9%) 0.863 ms/op [Average]
  (min, avg, max) = (3.798, 3.833, 3.887), stdev = 0.047
  CI (99.9%): [2.970, 4.696] (assumes normal distribution)


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
# Warmup Iteration   1: 4.034 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.210 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.005 ms/op
Iteration   1: 3.050 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.531 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   4.751 ms/op
                 createUser·p0.999:  9.950 ms/op
                 createUser·p0.9999: 12.149 ms/op
                 createUser·p1.00:   12.403 ms/op

Iteration   2: 3.102 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.841 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.731 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  9.044 ms/op
                 createUser·p0.9999: 13.430 ms/op
                 createUser·p1.00:   13.746 ms/op

Iteration   3: 3.061 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.632 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   3.869 ms/op
                 createUser·p0.99:   4.686 ms/op
                 createUser·p0.999:  8.029 ms/op
                 createUser·p0.9999: 16.442 ms/op
                 createUser·p1.00:   16.810 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312463
  mean =      3.071 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1174 
    [ 1.250,  2.500) = 20867 
    [ 2.500,  3.750) = 269222 
    [ 3.750,  5.000) = 19221 
    [ 5.000,  6.250) = 1025 
    [ 6.250,  7.500) = 371 
    [ 7.500,  8.750) = 214 
    [ 8.750, 10.000) = 118 
    [10.000, 11.250) = 41 
    [11.250, 12.500) = 106 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.531 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      4.637 ms/op
     p(99.9000) =      9.266 ms/op
     p(99.9900) =     15.176 ms/op
     p(99.9990) =     16.706 ms/op
     p(99.9999) =     16.810 ms/op
    p(100.0000) =     16.810 ms/op


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
# Warmup Iteration   1: 3.937 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.059 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.958 ±(99.9%) 0.006 ms/op
Iteration   1: 2.985 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.645 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  6.685 ms/op
                 existUser·p0.9999: 14.509 ms/op
                 existUser·p1.00:   15.598 ms/op

Iteration   2: 2.977 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.886 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  7.632 ms/op
                 existUser·p0.9999: 14.635 ms/op
                 existUser·p1.00:   15.221 ms/op

Iteration   3: 2.948 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.544 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.604 ms/op
                 existUser·p0.999:  11.201 ms/op
                 existUser·p0.9999: 21.013 ms/op
                 existUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323310
  mean =      2.970 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29687 
    [ 2.500,  5.000) = 292010 
    [ 5.000,  7.500) = 1176 
    [ 7.500, 10.000) = 127 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.544 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      9.535 ms/op
     p(99.9900) =     17.848 ms/op
     p(99.9990) =     21.284 ms/op
     p(99.9999) =     21.398 ms/op
    p(100.0000) =     21.398 ms/op


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
# Warmup Iteration   1: 3.899 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.180 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.097 ±(99.9%) 0.007 ms/op
Iteration   1: 3.101 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.755 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  9.526 ms/op
                 getUser·p0.9999: 15.893 ms/op
                 getUser·p1.00:   16.843 ms/op

Iteration   2: 3.107 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.657 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  7.840 ms/op
                 getUser·p0.9999: 16.330 ms/op
                 getUser·p1.00:   16.646 ms/op

Iteration   3: 3.032 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.756 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  8.674 ms/op
                 getUser·p0.9999: 20.036 ms/op
                 getUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311662
  mean =      3.080 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18905 
    [ 2.500,  5.000) = 290986 
    [ 5.000,  7.500) = 1318 
    [ 7.500, 10.000) = 219 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.657 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      8.667 ms/op
     p(99.9900) =     19.322 ms/op
     p(99.9990) =     21.430 ms/op
     p(99.9999) =     21.660 ms/op
    p(100.0000) =     21.660 ms/op


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
# Warmup Iteration   1: 5.173 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.944 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.823 ±(99.9%) 0.009 ms/op
Iteration   1: 3.864 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.856 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   5.243 ms/op
                 listUser·p0.99:   6.529 ms/op
                 listUser·p0.999:  12.485 ms/op
                 listUser·p0.9999: 20.944 ms/op
                 listUser·p1.00:   21.529 ms/op

Iteration   2: 3.818 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.941 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   5.014 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  14.239 ms/op
                 listUser·p0.9999: 20.467 ms/op
                 listUser·p1.00:   21.692 ms/op

Iteration   3: 3.852 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.124 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.923 ms/op
                 listUser·p0.99:   6.545 ms/op
                 listUser·p0.999:  13.435 ms/op
                 listUser·p0.9999: 17.632 ms/op
                 listUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249783
  mean =      3.844 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3949 
    [ 2.500,  5.000) = 232690 
    [ 5.000,  7.500) = 11960 
    [ 7.500, 10.000) = 475 
    [10.000, 12.500) = 334 
    [12.500, 15.000) = 239 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.856 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      5.087 ms/op
     p(99.0000) =      6.586 ms/op
     p(99.9000) =     13.229 ms/op
     p(99.9900) =     20.480 ms/op
     p(99.9990) =     21.496 ms/op
     p(99.9999) =     21.692 ms/op
    p(100.0000) =     21.692 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.439 ± 0.607  ops/ms
ClientGrpc.existUser                       thrpt       3  10.878 ± 2.250  ops/ms
ClientGrpc.getUser                         thrpt       3  10.371 ± 1.943  ops/ms
ClientGrpc.listUser                        thrpt       3   8.491 ± 2.785  ops/ms
ClientGrpc.createUser                       avgt       3   3.067 ± 1.135   ms/op
ClientGrpc.existUser                        avgt       3   2.925 ± 0.993   ms/op
ClientGrpc.getUser                          avgt       3   3.076 ± 0.219   ms/op
ClientGrpc.listUser                         avgt       3   3.833 ± 0.863   ms/op
ClientGrpc.createUser                     sample  312463   3.071 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.531           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.039           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.641           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.838           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.637           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.266           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.176           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.810           ms/op
ClientGrpc.existUser                      sample  323310   2.970 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.544           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.941           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.482           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.678           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.424           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.535           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.848           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.398           ms/op
ClientGrpc.getUser                        sample  311662   3.080 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.657           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.052           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.678           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.879           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.448           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.667           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.322           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.660           ms/op
ClientGrpc.listUser                       sample  249783   3.844 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.856           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.756           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.260           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.087           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.586           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.229           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.480           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.692           ms/op
