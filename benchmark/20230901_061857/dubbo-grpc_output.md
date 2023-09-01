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
# Warmup Iteration   1: 4.991 ops/ms
# Warmup Iteration   2: 9.240 ops/ms
# Warmup Iteration   3: 10.113 ops/ms
Iteration   1: 10.760 ops/ms
Iteration   2: 10.795 ops/ms
Iteration   3: 10.634 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.729 ±(99.9%) 1.546 ops/ms [Average]
  (min, avg, max) = (10.634, 10.729, 10.795), stdev = 0.085
  CI (99.9%): [9.183, 12.276] (assumes normal distribution)


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
# Warmup Iteration   1: 8.164 ops/ms
# Warmup Iteration   2: 10.632 ops/ms
# Warmup Iteration   3: 10.961 ops/ms
Iteration   1: 11.400 ops/ms
Iteration   2: 11.241 ops/ms
Iteration   3: 11.463 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.368 ±(99.9%) 2.083 ops/ms [Average]
  (min, avg, max) = (11.241, 11.368, 11.463), stdev = 0.114
  CI (99.9%): [9.286, 13.451] (assumes normal distribution)


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
# Warmup Iteration   1: 7.660 ops/ms
# Warmup Iteration   2: 10.280 ops/ms
# Warmup Iteration   3: 10.600 ops/ms
Iteration   1: 10.720 ops/ms
Iteration   2: 10.772 ops/ms
Iteration   3: 10.502 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.665 ±(99.9%) 2.617 ops/ms [Average]
  (min, avg, max) = (10.502, 10.665, 10.772), stdev = 0.143
  CI (99.9%): [8.047, 13.282] (assumes normal distribution)


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
# Warmup Iteration   1: 5.759 ops/ms
# Warmup Iteration   2: 8.054 ops/ms
# Warmup Iteration   3: 8.259 ops/ms
Iteration   1: 8.156 ops/ms
Iteration   2: 8.355 ops/ms
Iteration   3: 8.308 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.273 ±(99.9%) 1.899 ops/ms [Average]
  (min, avg, max) = (8.156, 8.273, 8.355), stdev = 0.104
  CI (99.9%): [6.374, 10.172] (assumes normal distribution)


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
# Warmup Iteration   1: 4.124 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.151 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.003 ms/op
Iteration   1: 2.960 ±(99.9%) 0.003 ms/op
Iteration   2: 3.022 ±(99.9%) 0.002 ms/op
Iteration   3: 2.992 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.992 ±(99.9%) 0.569 ms/op [Average]
  (min, avg, max) = (2.960, 2.992, 3.022), stdev = 0.031
  CI (99.9%): [2.422, 3.561] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.761 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.905 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.871 ±(99.9%) 0.005 ms/op
Iteration   1: 2.697 ±(99.9%) 0.006 ms/op
Iteration   2: 2.826 ±(99.9%) 0.003 ms/op
Iteration   3: 2.833 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.785 ±(99.9%) 1.391 ms/op [Average]
  (min, avg, max) = (2.697, 2.785, 2.833), stdev = 0.076
  CI (99.9%): [1.395, 4.176] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.984 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.004 ms/op
Iteration   1: 2.963 ±(99.9%) 0.002 ms/op
Iteration   2: 2.992 ±(99.9%) 0.002 ms/op
Iteration   3: 2.948 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.968 ±(99.9%) 0.404 ms/op [Average]
  (min, avg, max) = (2.948, 2.968, 2.992), stdev = 0.022
  CI (99.9%): [2.564, 3.372] (assumes normal distribution)


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
# Warmup Iteration   1: 4.763 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.961 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.853 ±(99.9%) 0.021 ms/op
Iteration   1: 3.884 ±(99.9%) 0.050 ms/op
Iteration   2: 3.800 ±(99.9%) 0.016 ms/op
Iteration   3: 3.819 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.835 ±(99.9%) 0.796 ms/op [Average]
  (min, avg, max) = (3.800, 3.835, 3.884), stdev = 0.044
  CI (99.9%): [3.038, 4.631] (assumes normal distribution)


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
# Warmup Iteration   1: 4.129 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.007 ms/op
Iteration   1: 2.953 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.623 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.387 ms/op
                 createUser·p0.95:   3.654 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  8.135 ms/op
                 createUser·p0.9999: 17.470 ms/op
                 createUser·p1.00:   17.891 ms/op

Iteration   2: 3.011 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.677 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.443 ms/op
                 createUser·p0.95:   3.637 ms/op
                 createUser·p0.99:   4.194 ms/op
                 createUser·p0.999:  7.056 ms/op
                 createUser·p0.9999: 17.543 ms/op
                 createUser·p1.00:   18.219 ms/op

Iteration   3: 3.006 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.596 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  8.098 ms/op
                 createUser·p0.9999: 20.251 ms/op
                 createUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321199
  mean =      2.990 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24977 
    [ 2.500,  5.000) = 294551 
    [ 5.000,  7.500) = 1217 
    [ 7.500, 10.000) = 210 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 122 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.596 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.437 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      7.971 ms/op
     p(99.9900) =     19.395 ms/op
     p(99.9990) =     20.473 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.984 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.929 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.871 ±(99.9%) 0.006 ms/op
Iteration   1: 2.805 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.672 ms/op
                 existUser·p0.50:   2.834 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.473 ms/op
                 existUser·p0.999:  7.242 ms/op
                 existUser·p0.9999: 11.842 ms/op
                 existUser·p1.00:   14.139 ms/op

Iteration   2: 2.845 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.720 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  7.462 ms/op
                 existUser·p0.9999: 20.243 ms/op
                 existUser·p1.00:   21.070 ms/op

Iteration   3: 2.887 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.685 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   4.724 ms/op
                 existUser·p0.999:  10.095 ms/op
                 existUser·p0.9999: 15.233 ms/op
                 existUser·p1.00:   15.712 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 337213
  mean =      2.845 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55251 
    [ 2.500,  5.000) = 280145 
    [ 5.000,  7.500) = 1406 
    [ 7.500, 10.000) = 193 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.672 ms/op
     p(50.0000) =      2.855 ms/op
     p(90.0000) =      3.367 ms/op
     p(95.0000) =      3.645 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =      8.100 ms/op
     p(99.9900) =     15.677 ms/op
     p(99.9990) =     20.619 ms/op
     p(99.9999) =     21.070 ms/op
    p(100.0000) =     21.070 ms/op


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
# Warmup Iteration   1: 4.110 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.097 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.041 ±(99.9%) 0.006 ms/op
Iteration   1: 2.995 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.483 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  7.866 ms/op
                 getUser·p0.9999: 17.312 ms/op
                 getUser·p1.00:   17.531 ms/op

Iteration   2: 2.982 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.742 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.699 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  7.694 ms/op
                 getUser·p0.9999: 13.765 ms/op
                 getUser·p1.00:   14.139 ms/op

Iteration   3: 3.089 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.775 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.547 ms/op
                 getUser·p0.999:  8.282 ms/op
                 getUser·p0.9999: 18.252 ms/op
                 getUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317665
  mean =      3.021 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1523 
    [ 1.250,  2.500) = 19536 
    [ 2.500,  3.750) = 280078 
    [ 3.750,  5.000) = 14742 
    [ 5.000,  6.250) = 971 
    [ 6.250,  7.500) = 341 
    [ 7.500,  8.750) = 227 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 35 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 83 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 35 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.483 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      8.072 ms/op
     p(99.9900) =     17.407 ms/op
     p(99.9990) =     18.568 ms/op
     p(99.9999) =     18.678 ms/op
    p(100.0000) =     18.678 ms/op


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
# Warmup Iteration   1: 4.625 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.038 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.908 ±(99.9%) 0.011 ms/op
Iteration   1: 3.877 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.865 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.965 ms/op
                 listUser·p0.999:  15.099 ms/op
                 listUser·p0.9999: 19.038 ms/op
                 listUser·p1.00:   19.333 ms/op

Iteration   2: 3.958 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.963 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  15.517 ms/op
                 listUser·p0.9999: 25.723 ms/op
                 listUser·p1.00:   26.149 ms/op

Iteration   3: 3.881 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.826 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  16.450 ms/op
                 listUser·p0.9999: 21.758 ms/op
                 listUser·p1.00:   22.446 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245904
  mean =      3.905 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6462 
    [ 2.500,  5.000) = 216310 
    [ 5.000,  7.500) = 21601 
    [ 7.500, 10.000) = 957 
    [10.000, 12.500) = 131 
    [12.500, 15.000) = 155 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.826 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.956 ms/op
     p(95.0000) =      5.579 ms/op
     p(99.0000) =      6.988 ms/op
     p(99.9000) =     15.663 ms/op
     p(99.9900) =     24.753 ms/op
     p(99.9990) =     26.071 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.729 ± 1.546  ops/ms
ClientGrpc.existUser                       thrpt       3  11.368 ± 2.083  ops/ms
ClientGrpc.getUser                         thrpt       3  10.665 ± 2.617  ops/ms
ClientGrpc.listUser                        thrpt       3   8.273 ± 1.899  ops/ms
ClientGrpc.createUser                       avgt       3   2.992 ± 0.569   ms/op
ClientGrpc.existUser                        avgt       3   2.785 ± 1.391   ms/op
ClientGrpc.getUser                          avgt       3   2.968 ± 0.404   ms/op
ClientGrpc.listUser                         avgt       3   3.835 ± 0.796   ms/op
ClientGrpc.createUser                     sample  321199   2.990 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.596           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.974           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.437           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.686           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.971           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.395           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.611           ms/op
ClientGrpc.existUser                      sample  337213   2.845 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.672           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.855           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.367           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.645           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.571           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.100           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.677           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.070           ms/op
ClientGrpc.getUser                        sample  317665   3.021 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.483           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.998           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.527           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.764           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.506           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.072           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.407           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.678           ms/op
ClientGrpc.listUser                       sample  245904   3.905 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.826           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.744           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.956           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.579           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.988           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.663           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.753           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.149           ms/op
