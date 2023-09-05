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
# Warmup Iteration   1: 4.521 ops/ms
# Warmup Iteration   2: 9.569 ops/ms
# Warmup Iteration   3: 10.336 ops/ms
Iteration   1: 10.563 ops/ms
Iteration   2: 10.583 ops/ms
Iteration   3: 10.847 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.664 ±(99.9%) 2.892 ops/ms [Average]
  (min, avg, max) = (10.563, 10.664, 10.847), stdev = 0.159
  CI (99.9%): [7.772, 13.556] (assumes normal distribution)


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
# Warmup Iteration   1: 7.787 ops/ms
# Warmup Iteration   2: 10.700 ops/ms
# Warmup Iteration   3: 10.891 ops/ms
Iteration   1: 11.199 ops/ms
Iteration   2: 11.469 ops/ms
Iteration   3: 11.297 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.322 ±(99.9%) 2.485 ops/ms [Average]
  (min, avg, max) = (11.199, 11.322, 11.469), stdev = 0.136
  CI (99.9%): [8.836, 13.807] (assumes normal distribution)


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
# Warmup Iteration   1: 8.219 ops/ms
# Warmup Iteration   2: 10.165 ops/ms
# Warmup Iteration   3: 10.601 ops/ms
Iteration   1: 10.694 ops/ms
Iteration   2: 10.632 ops/ms
Iteration   3: 10.746 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.691 ±(99.9%) 1.047 ops/ms [Average]
  (min, avg, max) = (10.632, 10.691, 10.746), stdev = 0.057
  CI (99.9%): [9.644, 11.737] (assumes normal distribution)


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
# Warmup Iteration   1: 5.882 ops/ms
# Warmup Iteration   2: 8.020 ops/ms
# Warmup Iteration   3: 8.044 ops/ms
Iteration   1: 8.131 ops/ms
Iteration   2: 8.119 ops/ms
Iteration   3: 8.421 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.224 ±(99.9%) 3.124 ops/ms [Average]
  (min, avg, max) = (8.119, 8.224, 8.421), stdev = 0.171
  CI (99.9%): [5.100, 11.348] (assumes normal distribution)


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
# Warmup Iteration   1: 3.960 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.150 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.003 ms/op
Iteration   1: 3.013 ±(99.9%) 0.003 ms/op
Iteration   2: 2.981 ±(99.9%) 0.003 ms/op
Iteration   3: 2.992 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.995 ±(99.9%) 0.298 ms/op [Average]
  (min, avg, max) = (2.981, 2.995, 3.013), stdev = 0.016
  CI (99.9%): [2.697, 3.294] (assumes normal distribution)


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
# Warmup Iteration   1: 3.761 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.979 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 2.864 ±(99.9%) 0.003 ms/op
Iteration   1: 2.868 ±(99.9%) 0.004 ms/op
Iteration   2: 2.843 ±(99.9%) 0.003 ms/op
Iteration   3: 2.840 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.850 ±(99.9%) 0.278 ms/op [Average]
  (min, avg, max) = (2.840, 2.850, 2.868), stdev = 0.015
  CI (99.9%): [2.572, 3.128] (assumes normal distribution)


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
# Warmup Iteration   1: 3.855 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.085 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.004 ms/op
Iteration   1: 2.958 ±(99.9%) 0.003 ms/op
Iteration   2: 2.982 ±(99.9%) 0.003 ms/op
Iteration   3: 2.959 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.966 ±(99.9%) 0.246 ms/op [Average]
  (min, avg, max) = (2.958, 2.966, 2.982), stdev = 0.013
  CI (99.9%): [2.720, 3.212] (assumes normal distribution)


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
# Warmup Iteration   1: 5.465 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.991 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.966 ±(99.9%) 0.047 ms/op
Iteration   1: 3.893 ±(99.9%) 0.031 ms/op
Iteration   2: 3.899 ±(99.9%) 0.014 ms/op
Iteration   3: 3.924 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.905 ±(99.9%) 0.297 ms/op [Average]
  (min, avg, max) = (3.893, 3.905, 3.924), stdev = 0.016
  CI (99.9%): [3.609, 4.202] (assumes normal distribution)


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
# Warmup Iteration   1: 3.909 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.099 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.007 ms/op
Iteration   1: 2.986 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.705 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.596 ms/op
                 createUser·p0.999:  9.992 ms/op
                 createUser·p0.9999: 23.406 ms/op
                 createUser·p1.00:   23.560 ms/op

Iteration   2: 3.008 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.746 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  7.754 ms/op
                 createUser·p0.9999: 17.039 ms/op
                 createUser·p1.00:   17.695 ms/op

Iteration   3: 3.011 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.537 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  7.972 ms/op
                 createUser·p0.9999: 29.045 ms/op
                 createUser·p1.00:   29.557 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319830
  mean =      3.002 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31889 
    [ 2.500,  5.000) = 286085 
    [ 5.000,  7.500) = 1351 
    [ 7.500, 10.000) = 239 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.537 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      8.128 ms/op
     p(99.9900) =     27.493 ms/op
     p(99.9990) =     29.354 ms/op
     p(99.9999) =     29.557 ms/op
    p(100.0000) =     29.557 ms/op


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
# Warmup Iteration   1: 3.847 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.909 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.892 ±(99.9%) 0.006 ms/op
Iteration   1: 2.887 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.464 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   4.547 ms/op
                 existUser·p0.999:  7.868 ms/op
                 existUser·p0.9999: 11.828 ms/op
                 existUser·p1.00:   12.091 ms/op

Iteration   2: 2.866 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.510 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  7.524 ms/op
                 existUser·p0.9999: 16.858 ms/op
                 existUser·p1.00:   18.022 ms/op

Iteration   3: 2.878 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.546 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.559 ms/op
                 existUser·p0.99:   4.596 ms/op
                 existUser·p0.999:  8.909 ms/op
                 existUser·p0.9999: 19.984 ms/op
                 existUser·p1.00:   21.037 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333789
  mean =      2.877 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47884 
    [ 2.500,  5.000) = 284002 
    [ 5.000,  7.500) = 1484 
    [ 7.500, 10.000) = 227 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.464 ms/op
     p(50.0000) =      2.863 ms/op
     p(90.0000) =      3.375 ms/op
     p(95.0000) =      3.629 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      8.148 ms/op
     p(99.9900) =     18.022 ms/op
     p(99.9990) =     20.141 ms/op
     p(99.9999) =     21.037 ms/op
    p(100.0000) =     21.037 ms/op


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
# Warmup Iteration   1: 4.016 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.058 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.999 ±(99.9%) 0.006 ms/op
Iteration   1: 3.002 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.782 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  7.725 ms/op
                 getUser·p0.9999: 12.801 ms/op
                 getUser·p1.00:   13.140 ms/op

Iteration   2: 2.986 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.764 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.428 ms/op
                 getUser·p0.95:   3.678 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  7.638 ms/op
                 getUser·p0.9999: 13.018 ms/op
                 getUser·p1.00:   13.173 ms/op

Iteration   3: 2.962 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.623 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  9.121 ms/op
                 getUser·p0.9999: 25.440 ms/op
                 getUser·p1.00:   25.887 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 322027
  mean =      2.983 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29181 
    [ 2.500,  5.000) = 291143 
    [ 5.000,  7.500) = 1263 
    [ 7.500, 10.000) = 266 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.623 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      7.946 ms/op
     p(99.9900) =     22.879 ms/op
     p(99.9990) =     25.748 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


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
# Warmup Iteration   1: 5.054 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.011 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.970 ±(99.9%) 0.011 ms/op
Iteration   1: 3.919 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.953 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.553 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  12.131 ms/op
                 listUser·p0.9999: 19.978 ms/op
                 listUser·p1.00:   20.316 ms/op

Iteration   2: 3.933 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.141 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  15.943 ms/op
                 listUser·p0.9999: 23.846 ms/op
                 listUser·p1.00:   24.117 ms/op

Iteration   3: 3.895 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.803 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  16.315 ms/op
                 listUser·p0.9999: 25.919 ms/op
                 listUser·p1.00:   26.640 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245255
  mean =      3.916 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5643 
    [ 2.500,  5.000) = 218368 
    [ 5.000,  7.500) = 19783 
    [ 7.500, 10.000) = 930 
    [10.000, 12.500) = 212 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.803 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.882 ms/op
     p(95.0000) =      5.595 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     14.926 ms/op
     p(99.9900) =     23.953 ms/op
     p(99.9990) =     26.509 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.664 ± 2.892  ops/ms
ClientGrpc.existUser                       thrpt       3  11.322 ± 2.485  ops/ms
ClientGrpc.getUser                         thrpt       3  10.691 ± 1.047  ops/ms
ClientGrpc.listUser                        thrpt       3   8.224 ± 3.124  ops/ms
ClientGrpc.createUser                       avgt       3   2.995 ± 0.298   ms/op
ClientGrpc.existUser                        avgt       3   2.850 ± 0.278   ms/op
ClientGrpc.getUser                          avgt       3   2.966 ± 0.246   ms/op
ClientGrpc.listUser                         avgt       3   3.905 ± 0.297   ms/op
ClientGrpc.createUser                     sample  319830   3.002 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.537           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.978           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.531           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.764           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.497           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.128           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.493           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.557           ms/op
ClientGrpc.existUser                      sample  333789   2.877 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.464           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.863           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.375           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.629           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.514           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.148           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.022           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.037           ms/op
ClientGrpc.getUser                        sample  322027   2.983 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.623           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.978           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.486           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.744           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.424           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.946           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.879           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.887           ms/op
ClientGrpc.listUser                       sample  245255   3.916 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.803           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.768           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.882           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.595           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.930           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.926           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.953           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.640           ms/op
