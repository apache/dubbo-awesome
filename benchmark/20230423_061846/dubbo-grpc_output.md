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
# Warmup Iteration   1: 4.655 ops/ms
# Warmup Iteration   2: 9.421 ops/ms
# Warmup Iteration   3: 10.412 ops/ms
Iteration   1: 10.719 ops/ms
Iteration   2: 10.772 ops/ms
Iteration   3: 10.783 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.758 ±(99.9%) 0.623 ops/ms [Average]
  (min, avg, max) = (10.719, 10.758, 10.783), stdev = 0.034
  CI (99.9%): [10.135, 11.381] (assumes normal distribution)


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
# Warmup Iteration   1: 7.495 ops/ms
# Warmup Iteration   2: 10.994 ops/ms
# Warmup Iteration   3: 11.156 ops/ms
Iteration   1: 11.388 ops/ms
Iteration   2: 11.309 ops/ms
Iteration   3: 11.414 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.370 ±(99.9%) 1.001 ops/ms [Average]
  (min, avg, max) = (11.309, 11.370, 11.414), stdev = 0.055
  CI (99.9%): [10.370, 12.371] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.936 ops/ms
# Warmup Iteration   2: 10.439 ops/ms
# Warmup Iteration   3: 10.799 ops/ms
Iteration   1: 10.881 ops/ms
Iteration   2: 10.879 ops/ms
Iteration   3: 10.878 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.879 ±(99.9%) 0.030 ops/ms [Average]
  (min, avg, max) = (10.878, 10.879, 10.881), stdev = 0.002
  CI (99.9%): [10.849, 10.909] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.650 ops/ms
# Warmup Iteration   2: 8.000 ops/ms
# Warmup Iteration   3: 8.218 ops/ms
Iteration   1: 8.335 ops/ms
Iteration   2: 8.230 ops/ms
Iteration   3: 8.442 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.335 ±(99.9%) 1.931 ops/ms [Average]
  (min, avg, max) = (8.230, 8.335, 8.442), stdev = 0.106
  CI (99.9%): [6.404, 10.267] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.252 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.180 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.959 ±(99.9%) 0.003 ms/op
Iteration   1: 2.974 ±(99.9%) 0.004 ms/op
Iteration   2: 2.975 ±(99.9%) 0.003 ms/op
Iteration   3: 2.969 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.973 ±(99.9%) 0.059 ms/op [Average]
  (min, avg, max) = (2.969, 2.973, 2.975), stdev = 0.003
  CI (99.9%): [2.914, 3.031] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.625 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.975 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.875 ±(99.9%) 0.005 ms/op
Iteration   1: 2.851 ±(99.9%) 0.003 ms/op
Iteration   2: 2.878 ±(99.9%) 0.003 ms/op
Iteration   3: 2.832 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.854 ±(99.9%) 0.419 ms/op [Average]
  (min, avg, max) = (2.832, 2.854, 2.878), stdev = 0.023
  CI (99.9%): [2.435, 3.272] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.799 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.088 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.002 ms/op
Iteration   1: 3.017 ±(99.9%) 0.002 ms/op
Iteration   2: 2.959 ±(99.9%) 0.002 ms/op
Iteration   3: 3.010 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.996 ±(99.9%) 0.580 ms/op [Average]
  (min, avg, max) = (2.959, 2.996, 3.017), stdev = 0.032
  CI (99.9%): [2.416, 3.575] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 3.800 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.047 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.834 ±(99.9%) 0.023 ms/op
Iteration   1: 3.835 ±(99.9%) 0.036 ms/op
Iteration   2: 3.799 ±(99.9%) 0.036 ms/op
Iteration   3: 3.847 ±(99.9%) 0.045 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.827 ±(99.9%) 0.457 ms/op [Average]
  (min, avg, max) = (3.799, 3.827, 3.847), stdev = 0.025
  CI (99.9%): [3.370, 4.284] (assumes normal distribution)


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
# Warmup Iteration   1: 4.017 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.995 ±(99.9%) 0.007 ms/op
Iteration   1: 3.021 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.780 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  8.208 ms/op
                 createUser·p0.9999: 11.088 ms/op
                 createUser·p1.00:   13.337 ms/op

Iteration   2: 2.958 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.370 ms/op
                 createUser·p0.50:   2.937 ms/op
                 createUser·p0.90:   3.322 ms/op
                 createUser·p0.95:   3.506 ms/op
                 createUser·p0.99:   4.112 ms/op
                 createUser·p0.999:  6.978 ms/op
                 createUser·p0.9999: 21.463 ms/op
                 createUser·p1.00:   21.692 ms/op

Iteration   3: 2.960 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.430 ms/op
                 createUser·p0.50:   2.941 ms/op
                 createUser·p0.90:   3.391 ms/op
                 createUser·p0.95:   3.617 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  9.257 ms/op
                 createUser·p0.9999: 14.696 ms/op
                 createUser·p1.00:   14.893 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 322395
  mean =      2.979 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22588 
    [ 2.500,  5.000) = 298591 
    [ 5.000,  7.500) = 861 
    [ 7.500, 10.000) = 129 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.370 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.437 ms/op
     p(95.0000) =      3.674 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      7.984 ms/op
     p(99.9900) =     20.212 ms/op
     p(99.9990) =     21.652 ms/op
     p(99.9999) =     21.692 ms/op
    p(100.0000) =     21.692 ms/op


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
# Warmup Iteration   1: 3.071 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 2.929 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.869 ±(99.9%) 0.006 ms/op
Iteration   1: 2.791 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.752 ms/op
                 existUser·p0.50:   2.834 ms/op
                 existUser·p0.90:   3.215 ms/op
                 existUser·p0.95:   3.387 ms/op
                 existUser·p0.99:   4.100 ms/op
                 existUser·p0.999:  5.210 ms/op
                 existUser·p0.9999: 11.534 ms/op
                 existUser·p1.00:   11.747 ms/op

Iteration   2: 2.931 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.717 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   3.916 ms/op
                 existUser·p0.999:  7.646 ms/op
                 existUser·p0.9999: 21.862 ms/op
                 existUser·p1.00:   22.184 ms/op

Iteration   3: 2.873 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.515 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.482 ms/op
                 existUser·p0.99:   4.039 ms/op
                 existUser·p0.999:  10.355 ms/op
                 existUser·p0.9999: 16.375 ms/op
                 existUser·p1.00:   16.564 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 335101
  mean =      2.864 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43681 
    [ 2.500,  5.000) = 290652 
    [ 5.000,  7.500) = 357 
    [ 7.500, 10.000) = 138 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.515 ms/op
     p(50.0000) =      2.859 ms/op
     p(90.0000) =      3.305 ms/op
     p(95.0000) =      3.473 ms/op
     p(99.0000) =      4.010 ms/op
     p(99.9000) =      7.799 ms/op
     p(99.9900) =     21.692 ms/op
     p(99.9990) =     22.140 ms/op
     p(99.9999) =     22.184 ms/op
    p(100.0000) =     22.184 ms/op


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
# Warmup Iteration   1: 4.052 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.065 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.937 ±(99.9%) 0.006 ms/op
Iteration   1: 2.989 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.802 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.375 ms/op
                 getUser·p0.95:   3.613 ms/op
                 getUser·p0.99:   4.112 ms/op
                 getUser·p0.999:  6.865 ms/op
                 getUser·p0.9999: 17.105 ms/op
                 getUser·p1.00:   17.334 ms/op

Iteration   2: 2.980 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.755 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  8.471 ms/op
                 getUser·p0.9999: 16.127 ms/op
                 getUser·p1.00:   16.843 ms/op

Iteration   3: 2.993 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.698 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  6.373 ms/op
                 getUser·p0.9999: 19.475 ms/op
                 getUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 321058
  mean =      2.987 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23944 
    [ 2.500,  5.000) = 295994 
    [ 5.000,  7.500) = 804 
    [ 7.500, 10.000) = 91 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.698 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      7.381 ms/op
     p(99.9900) =     17.593 ms/op
     p(99.9990) =     20.209 ms/op
     p(99.9999) =     20.316 ms/op
    p(100.0000) =     20.316 ms/op


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
# Warmup Iteration   1: 4.759 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.999 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.888 ±(99.9%) 0.010 ms/op
Iteration   1: 3.846 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.176 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.743 ms/op
                 listUser·p0.95:   5.349 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  11.646 ms/op
                 listUser·p0.9999: 13.654 ms/op
                 listUser·p1.00:   14.107 ms/op

Iteration   2: 3.832 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.739 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   5.153 ms/op
                 listUser·p0.99:   6.586 ms/op
                 listUser·p0.999:  15.601 ms/op
                 listUser·p0.9999: 22.031 ms/op
                 listUser·p1.00:   22.217 ms/op

Iteration   3: 3.831 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.991 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   6.554 ms/op
                 listUser·p0.999:  14.130 ms/op
                 listUser·p0.9999: 23.974 ms/op
                 listUser·p1.00:   27.492 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 250197
  mean =      3.836 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4548 
    [ 2.500,  5.000) = 228542 
    [ 5.000,  7.500) = 16187 
    [ 7.500, 10.000) = 491 
    [10.000, 12.500) = 143 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.739 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      5.366 ms/op
     p(99.0000) =      6.595 ms/op
     p(99.9000) =     13.117 ms/op
     p(99.9900) =     23.461 ms/op
     p(99.9990) =     27.377 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.758 ± 0.623  ops/ms
ClientGrpc.existUser                       thrpt       3  11.370 ± 1.001  ops/ms
ClientGrpc.getUser                         thrpt       3  10.879 ± 0.030  ops/ms
ClientGrpc.listUser                        thrpt       3   8.335 ± 1.931  ops/ms
ClientGrpc.createUser                       avgt       3   2.973 ± 0.059   ms/op
ClientGrpc.existUser                        avgt       3   2.854 ± 0.419   ms/op
ClientGrpc.getUser                          avgt       3   2.996 ± 0.580   ms/op
ClientGrpc.listUser                         avgt       3   3.827 ± 0.457   ms/op
ClientGrpc.createUser                     sample  322395   2.979 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.370           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.961           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.437           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.674           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.260           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.984           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.212           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.692           ms/op
ClientGrpc.existUser                      sample  335101   2.864 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.515           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.859           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.305           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.473           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.010           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.799           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.692           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.184           ms/op
ClientGrpc.getUser                        sample  321058   2.987 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.698           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.974           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.486           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.719           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.252           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.381           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.593           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.316           ms/op
ClientGrpc.listUser                       sample  250197   3.836 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.739           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.711           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.620           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.366           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.595           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.117           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.461           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.492           ms/op
