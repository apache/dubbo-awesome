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
# Warmup Iteration   1: 3.879 ops/ms
# Warmup Iteration   2: 9.044 ops/ms
# Warmup Iteration   3: 10.001 ops/ms
Iteration   1: 10.470 ops/ms
Iteration   2: 10.493 ops/ms
Iteration   3: 10.694 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.552 ±(99.9%) 2.247 ops/ms [Average]
  (min, avg, max) = (10.470, 10.552, 10.694), stdev = 0.123
  CI (99.9%): [8.305, 12.799] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 6.877 ops/ms
# Warmup Iteration   2: 10.633 ops/ms
# Warmup Iteration   3: 10.876 ops/ms
Iteration   1: 11.021 ops/ms
Iteration   2: 11.110 ops/ms
Iteration   3: 11.100 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.077 ±(99.9%) 0.887 ops/ms [Average]
  (min, avg, max) = (11.021, 11.077, 11.110), stdev = 0.049
  CI (99.9%): [10.190, 11.964] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.533 ops/ms
# Warmup Iteration   2: 10.013 ops/ms
# Warmup Iteration   3: 10.373 ops/ms
Iteration   1: 10.600 ops/ms
Iteration   2: 10.613 ops/ms
Iteration   3: 10.560 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.591 ±(99.9%) 0.501 ops/ms [Average]
  (min, avg, max) = (10.560, 10.591, 10.613), stdev = 0.027
  CI (99.9%): [10.090, 11.092] (assumes normal distribution)


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
# Warmup Iteration   1: 5.233 ops/ms
# Warmup Iteration   2: 7.734 ops/ms
# Warmup Iteration   3: 8.116 ops/ms
Iteration   1: 8.214 ops/ms
Iteration   2: 8.211 ops/ms
Iteration   3: 8.291 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.239 ±(99.9%) 0.829 ops/ms [Average]
  (min, avg, max) = (8.211, 8.239, 8.291), stdev = 0.045
  CI (99.9%): [7.410, 9.068] (assumes normal distribution)


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
# Warmup Iteration   1: 4.170 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.141 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.002 ms/op
Iteration   1: 2.999 ±(99.9%) 0.002 ms/op
Iteration   2: 2.996 ±(99.9%) 0.001 ms/op
Iteration   3: 3.000 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.998 ±(99.9%) 0.039 ms/op [Average]
  (min, avg, max) = (2.996, 2.998, 3.000), stdev = 0.002
  CI (99.9%): [2.959, 3.037] (assumes normal distribution)


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
# Warmup Iteration   1: 3.344 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.118 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.914 ±(99.9%) 0.002 ms/op
Iteration   1: 2.855 ±(99.9%) 0.002 ms/op
Iteration   2: 2.862 ±(99.9%) 0.003 ms/op
Iteration   3: 2.869 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.862 ±(99.9%) 0.130 ms/op [Average]
  (min, avg, max) = (2.855, 2.862, 2.869), stdev = 0.007
  CI (99.9%): [2.732, 2.992] (assumes normal distribution)


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
# Warmup Iteration   1: 4.451 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.077 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.995 ±(99.9%) 0.003 ms/op
Iteration   1: 2.966 ±(99.9%) 0.003 ms/op
Iteration   2: 2.875 ±(99.9%) 0.003 ms/op
Iteration   3: 3.000 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.947 ±(99.9%) 1.180 ms/op [Average]
  (min, avg, max) = (2.875, 2.947, 3.000), stdev = 0.065
  CI (99.9%): [1.767, 4.127] (assumes normal distribution)


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
# Warmup Iteration   1: 5.139 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.017 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.864 ±(99.9%) 0.028 ms/op
Iteration   1: 3.897 ±(99.9%) 0.007 ms/op
Iteration   2: 3.824 ±(99.9%) 0.010 ms/op
Iteration   3: 3.964 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.895 ±(99.9%) 1.278 ms/op [Average]
  (min, avg, max) = (3.824, 3.895, 3.964), stdev = 0.070
  CI (99.9%): [2.617, 5.173] (assumes normal distribution)


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
# Warmup Iteration   1: 4.232 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.086 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.037 ±(99.9%) 0.006 ms/op
Iteration   1: 2.959 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.857 ms/op
                 createUser·p0.50:   2.929 ms/op
                 createUser·p0.90:   3.363 ms/op
                 createUser·p0.95:   3.551 ms/op
                 createUser·p0.99:   4.237 ms/op
                 createUser·p0.999:  8.101 ms/op
                 createUser·p0.9999: 12.773 ms/op
                 createUser·p1.00:   13.025 ms/op

Iteration   2: 2.957 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.843 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  6.618 ms/op
                 createUser·p0.9999: 14.044 ms/op
                 createUser·p1.00:   14.156 ms/op

Iteration   3: 3.036 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.805 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  11.922 ms/op
                 createUser·p0.9999: 17.695 ms/op
                 createUser·p1.00:   19.071 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321559
  mean =      2.983 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 649 
    [ 1.250,  2.500) = 31239 
    [ 2.500,  3.750) = 275862 
    [ 3.750,  5.000) = 12744 
    [ 5.000,  6.250) = 544 
    [ 6.250,  7.500) = 162 
    [ 7.500,  8.750) = 66 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 50 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.805 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      8.240 ms/op
     p(99.9900) =     17.465 ms/op
     p(99.9990) =     17.976 ms/op
     p(99.9999) =     19.071 ms/op
    p(100.0000) =     19.071 ms/op


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
# Warmup Iteration   1: 3.985 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.936 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.885 ±(99.9%) 0.006 ms/op
Iteration   1: 2.865 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.077 ms/op
                 existUser·p0.50:   2.839 ms/op
                 existUser·p0.90:   3.199 ms/op
                 existUser·p0.95:   3.338 ms/op
                 existUser·p0.99:   3.801 ms/op
                 existUser·p0.999:  6.514 ms/op
                 existUser·p0.9999: 17.727 ms/op
                 existUser·p1.00:   17.990 ms/op

Iteration   2: 2.904 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.782 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  7.641 ms/op
                 existUser·p0.9999: 17.266 ms/op
                 existUser·p1.00:   17.793 ms/op

Iteration   3: 2.898 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.620 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   4.137 ms/op
                 existUser·p0.999:  6.529 ms/op
                 existUser·p0.9999: 19.692 ms/op
                 existUser·p1.00:   21.365 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332236
  mean =      2.889 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41899 
    [ 2.500,  5.000) = 289372 
    [ 5.000,  7.500) = 701 
    [ 7.500, 10.000) = 42 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.620 ms/op
     p(50.0000) =      2.859 ms/op
     p(90.0000) =      3.305 ms/op
     p(95.0000) =      3.486 ms/op
     p(99.0000) =      4.084 ms/op
     p(99.9000) =      7.092 ms/op
     p(99.9900) =     19.129 ms/op
     p(99.9990) =     20.081 ms/op
     p(99.9999) =     21.365 ms/op
    p(100.0000) =     21.365 ms/op


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
# Warmup Iteration   1: 4.351 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.106 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.007 ms/op
Iteration   1: 2.975 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.558 ms/op
                 getUser·p0.50:   2.945 ms/op
                 getUser·p0.90:   3.363 ms/op
                 getUser·p0.95:   3.547 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  7.713 ms/op
                 getUser·p0.9999: 18.964 ms/op
                 getUser·p1.00:   19.202 ms/op

Iteration   2: 3.065 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.535 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  7.785 ms/op
                 getUser·p0.9999: 22.643 ms/op
                 getUser·p1.00:   22.708 ms/op

Iteration   3: 3.033 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.555 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.637 ms/op
                 getUser·p0.99:   4.096 ms/op
                 getUser·p0.999:  7.487 ms/op
                 getUser·p0.9999: 22.249 ms/op
                 getUser·p1.00:   22.643 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317388
  mean =      3.024 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17352 
    [ 2.500,  5.000) = 298590 
    [ 5.000,  7.500) = 1094 
    [ 7.500, 10.000) = 148 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.535 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      7.684 ms/op
     p(99.9900) =     22.225 ms/op
     p(99.9990) =     22.675 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


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
# Warmup Iteration   1: 5.255 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.127 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.913 ±(99.9%) 0.010 ms/op
Iteration   1: 3.920 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.544 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  12.835 ms/op
                 listUser·p0.9999: 21.223 ms/op
                 listUser·p1.00:   21.594 ms/op

Iteration   2: 3.907 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.319 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  14.828 ms/op
                 listUser·p0.9999: 16.712 ms/op
                 listUser·p1.00:   17.072 ms/op

Iteration   3: 3.938 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.219 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.464 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  16.068 ms/op
                 listUser·p0.9999: 25.612 ms/op
                 listUser·p1.00:   25.952 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244762
  mean =      3.921 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2679 
    [ 2.500,  5.000) = 222933 
    [ 5.000,  7.500) = 17766 
    [ 7.500, 10.000) = 821 
    [10.000, 12.500) = 136 
    [12.500, 15.000) = 175 
    [15.000, 17.500) = 156 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.219 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      5.521 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     15.061 ms/op
     p(99.9900) =     24.921 ms/op
     p(99.9990) =     25.887 ms/op
     p(99.9999) =     25.952 ms/op
    p(100.0000) =     25.952 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.552 ± 2.247  ops/ms
ClientGrpc.existUser                       thrpt       3  11.077 ± 0.887  ops/ms
ClientGrpc.getUser                         thrpt       3  10.591 ± 0.501  ops/ms
ClientGrpc.listUser                        thrpt       3   8.239 ± 0.829  ops/ms
ClientGrpc.createUser                       avgt       3   2.998 ± 0.039   ms/op
ClientGrpc.existUser                        avgt       3   2.862 ± 0.130   ms/op
ClientGrpc.getUser                          avgt       3   2.947 ± 1.180   ms/op
ClientGrpc.listUser                         avgt       3   3.895 ± 1.278   ms/op
ClientGrpc.createUser                     sample  321559   2.983 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.805           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.961           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.478           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.699           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.317           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.240           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.465           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.071           ms/op
ClientGrpc.existUser                      sample  332236   2.889 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.620           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.859           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.305           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.486           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.084           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.092           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.129           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.365           ms/op
ClientGrpc.getUser                        sample  317388   3.024 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.535           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.982           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.486           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.678           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.268           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.684           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.225           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.708           ms/op
ClientGrpc.listUser                       sample  244762   3.921 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.219           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.764           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.792           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.521           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.865           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.061           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.921           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.952           ms/op
