# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.897 ops/ms
# Warmup Iteration   2: 8.811 ops/ms
# Warmup Iteration   3: 10.101 ops/ms
Iteration   1: 10.216 ops/ms
Iteration   2: 10.404 ops/ms
Iteration   3: 10.487 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.369 ±(99.9%) 2.531 ops/ms [Average]
  (min, avg, max) = (10.216, 10.369, 10.487), stdev = 0.139
  CI (99.9%): [7.838, 12.900] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.489 ops/ms
# Warmup Iteration   2: 10.502 ops/ms
# Warmup Iteration   3: 11.161 ops/ms
Iteration   1: 11.135 ops/ms
Iteration   2: 11.338 ops/ms
Iteration   3: 10.998 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.157 ±(99.9%) 3.126 ops/ms [Average]
  (min, avg, max) = (10.998, 11.157, 11.338), stdev = 0.171
  CI (99.9%): [8.031, 14.283] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.676 ops/ms
# Warmup Iteration   2: 10.091 ops/ms
# Warmup Iteration   3: 10.677 ops/ms
Iteration   1: 10.672 ops/ms
Iteration   2: 10.456 ops/ms
Iteration   3: 10.556 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.561 ±(99.9%) 1.965 ops/ms [Average]
  (min, avg, max) = (10.456, 10.561, 10.672), stdev = 0.108
  CI (99.9%): [8.596, 12.527] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.189 ops/ms
# Warmup Iteration   2: 7.709 ops/ms
# Warmup Iteration   3: 8.049 ops/ms
Iteration   1: 8.037 ops/ms
Iteration   2: 8.071 ops/ms
Iteration   3: 8.123 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.077 ±(99.9%) 0.789 ops/ms [Average]
  (min, avg, max) = (8.037, 8.077, 8.123), stdev = 0.043
  CI (99.9%): [7.288, 8.865] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.247 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.188 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.101 ±(99.9%) 0.010 ms/op
Iteration   1: 3.079 ±(99.9%) 0.003 ms/op
Iteration   2: 3.034 ±(99.9%) 0.002 ms/op
Iteration   3: 3.023 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.045 ±(99.9%) 0.542 ms/op [Average]
  (min, avg, max) = (3.023, 3.045, 3.079), stdev = 0.030
  CI (99.9%): [2.503, 3.587] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.042 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.010 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 2.941 ±(99.9%) 0.003 ms/op
Iteration   1: 2.865 ±(99.9%) 0.002 ms/op
Iteration   2: 2.893 ±(99.9%) 0.002 ms/op
Iteration   3: 2.805 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.854 ±(99.9%) 0.816 ms/op [Average]
  (min, avg, max) = (2.805, 2.854, 2.893), stdev = 0.045
  CI (99.9%): [2.038, 3.671] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.145 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.203 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.002 ms/op
Iteration   1: 3.059 ±(99.9%) 0.003 ms/op
Iteration   2: 3.030 ±(99.9%) 0.002 ms/op
Iteration   3: 3.034 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.041 ±(99.9%) 0.283 ms/op [Average]
  (min, avg, max) = (3.030, 3.041, 3.059), stdev = 0.016
  CI (99.9%): [2.758, 3.324] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.194 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.194 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.000 ±(99.9%) 0.011 ms/op
Iteration   1: 4.044 ±(99.9%) 0.038 ms/op
Iteration   2: 4.032 ±(99.9%) 0.008 ms/op
Iteration   3: 3.998 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.024 ±(99.9%) 0.436 ms/op [Average]
  (min, avg, max) = (3.998, 4.024, 4.044), stdev = 0.024
  CI (99.9%): [3.588, 4.461] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.338 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.217 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.007 ms/op
Iteration   1: 3.002 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.706 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.453 ms/op
                 createUser·p0.95:   3.641 ms/op
                 createUser·p0.99:   4.202 ms/op
                 createUser·p0.999:  8.520 ms/op
                 createUser·p0.9999: 16.974 ms/op
                 createUser·p1.00:   17.367 ms/op

Iteration   2: 2.999 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.782 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.633 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  7.143 ms/op
                 createUser·p0.9999: 19.377 ms/op
                 createUser·p1.00:   19.464 ms/op

Iteration   3: 3.013 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.844 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.363 ms/op
                 createUser·p0.999:  7.380 ms/op
                 createUser·p0.9999: 20.460 ms/op
                 createUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319465
  mean =      3.005 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25785 
    [ 2.500,  5.000) = 292344 
    [ 5.000,  7.500) = 1000 
    [ 7.500, 10.000) = 132 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.706 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      7.590 ms/op
     p(99.9900) =     19.728 ms/op
     p(99.9990) =     20.828 ms/op
     p(99.9999) =     20.972 ms/op
    p(100.0000) =     20.972 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.159 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.009 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.915 ±(99.9%) 0.005 ms/op
Iteration   1: 2.913 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.768 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.564 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  6.128 ms/op
                 existUser·p0.9999: 13.271 ms/op
                 existUser·p1.00:   13.369 ms/op

Iteration   2: 2.905 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.759 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   4.030 ms/op
                 existUser·p0.999:  5.693 ms/op
                 existUser·p0.9999: 14.401 ms/op
                 existUser·p1.00:   14.664 ms/op

Iteration   3: 2.937 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.726 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.023 ms/op
                 existUser·p0.999:  11.505 ms/op
                 existUser·p0.9999: 18.055 ms/op
                 existUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328926
  mean =      2.918 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 969 
    [ 1.250,  2.500) = 33511 
    [ 2.500,  3.750) = 286027 
    [ 3.750,  5.000) = 7594 
    [ 5.000,  6.250) = 362 
    [ 6.250,  7.500) = 140 
    [ 7.500,  8.750) = 67 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 39 
    [17.500, 18.750) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.726 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.363 ms/op
     p(95.0000) =      3.564 ms/op
     p(99.0000) =      4.104 ms/op
     p(99.9000) =      7.432 ms/op
     p(99.9900) =     17.239 ms/op
     p(99.9990) =     18.153 ms/op
     p(99.9999) =     18.186 ms/op
    p(100.0000) =     18.186 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.408 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.149 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.108 ±(99.9%) 0.008 ms/op
Iteration   1: 3.076 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.916 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  7.176 ms/op
                 getUser·p0.9999: 12.868 ms/op
                 getUser·p1.00:   13.337 ms/op

Iteration   2: 3.083 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.874 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  7.826 ms/op
                 getUser·p0.9999: 20.902 ms/op
                 getUser·p1.00:   22.643 ms/op

Iteration   3: 3.072 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.954 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  6.838 ms/op
                 getUser·p0.9999: 17.274 ms/op
                 getUser·p1.00:   17.793 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311837
  mean =      3.077 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15078 
    [ 2.500,  5.000) = 295697 
    [ 5.000,  7.500) = 804 
    [ 7.500, 10.000) = 97 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.874 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      7.184 ms/op
     p(99.9900) =     20.408 ms/op
     p(99.9990) =     21.931 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.552 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.215 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.975 ±(99.9%) 0.011 ms/op
Iteration   1: 4.046 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.235 ms/op
                 listUser·p0.50:   3.873 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   7.168 ms/op
                 listUser·p0.999:  14.205 ms/op
                 listUser·p0.9999: 22.783 ms/op
                 listUser·p1.00:   23.953 ms/op

Iteration   2: 3.982 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.241 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  15.225 ms/op
                 listUser·p0.9999: 23.592 ms/op
                 listUser·p1.00:   24.248 ms/op

Iteration   3: 4.034 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.980 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.956 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  17.695 ms/op
                 listUser·p0.9999: 19.202 ms/op
                 listUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238687
  mean =      4.021 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2457 
    [ 2.500,  5.000) = 212480 
    [ 5.000,  7.500) = 22304 
    [ 7.500, 10.000) = 1026 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 135 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.980 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.997 ms/op
     p(95.0000) =      5.767 ms/op
     p(99.0000) =      7.029 ms/op
     p(99.9000) =     16.476 ms/op
     p(99.9900) =     22.549 ms/op
     p(99.9990) =     24.139 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.369 ± 2.531  ops/ms
ClientGrpc.existUser                       thrpt       3  11.157 ± 3.126  ops/ms
ClientGrpc.getUser                         thrpt       3  10.561 ± 1.965  ops/ms
ClientGrpc.listUser                        thrpt       3   8.077 ± 0.789  ops/ms
ClientGrpc.createUser                       avgt       3   3.045 ± 0.542   ms/op
ClientGrpc.existUser                        avgt       3   2.854 ± 0.816   ms/op
ClientGrpc.getUser                          avgt       3   3.041 ± 0.283   ms/op
ClientGrpc.listUser                         avgt       3   4.024 ± 0.436   ms/op
ClientGrpc.createUser                     sample  319465   3.005 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.706           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.974           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.473           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.670           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.590           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.728           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.972           ms/op
ClientGrpc.existUser                      sample  328926   2.918 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.726           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.892           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.363           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.564           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.104           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.432           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.239           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.186           ms/op
ClientGrpc.getUser                        sample  311837   3.077 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.874           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.039           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.600           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.830           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.184           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.408           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.643           ms/op
ClientGrpc.listUser                       sample  238687   4.021 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.980           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.863           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.997           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.767           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.029           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.476           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.549           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.248           ms/op
