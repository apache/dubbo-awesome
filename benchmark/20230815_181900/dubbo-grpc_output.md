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
# Warmup Iteration   1: 3.511 ops/ms
# Warmup Iteration   2: 7.652 ops/ms
# Warmup Iteration   3: 8.945 ops/ms
Iteration   1: 8.966 ops/ms
Iteration   2: 8.968 ops/ms
Iteration   3: 9.223 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.052 ±(99.9%) 2.697 ops/ms [Average]
  (min, avg, max) = (8.966, 9.052, 9.223), stdev = 0.148
  CI (99.9%): [6.355, 11.749] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 6.694 ops/ms
# Warmup Iteration   2: 9.343 ops/ms
# Warmup Iteration   3: 9.607 ops/ms
Iteration   1: 9.902 ops/ms
Iteration   2: 9.549 ops/ms
Iteration   3: 9.570 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.674 ±(99.9%) 3.611 ops/ms [Average]
  (min, avg, max) = (9.549, 9.674, 9.902), stdev = 0.198
  CI (99.9%): [6.062, 13.285] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.691 ops/ms
# Warmup Iteration   2: 8.868 ops/ms
# Warmup Iteration   3: 9.020 ops/ms
Iteration   1: 9.046 ops/ms
Iteration   2: 9.121 ops/ms
Iteration   3: 9.026 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.064 ±(99.9%) 0.919 ops/ms [Average]
  (min, avg, max) = (9.026, 9.064, 9.121), stdev = 0.050
  CI (99.9%): [8.145, 9.984] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.750 ops/ms
# Warmup Iteration   2: 6.459 ops/ms
# Warmup Iteration   3: 6.770 ops/ms
Iteration   1: 6.877 ops/ms
Iteration   2: 6.748 ops/ms
Iteration   3: 6.838 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.821 ±(99.9%) 1.214 ops/ms [Average]
  (min, avg, max) = (6.748, 6.821, 6.877), stdev = 0.067
  CI (99.9%): [5.607, 8.035] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.052 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.744 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.570 ±(99.9%) 0.011 ms/op
Iteration   1: 3.549 ±(99.9%) 0.005 ms/op
Iteration   2: 3.560 ±(99.9%) 0.003 ms/op
Iteration   3: 3.471 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.527 ±(99.9%) 0.878 ms/op [Average]
  (min, avg, max) = (3.471, 3.527, 3.560), stdev = 0.048
  CI (99.9%): [2.649, 4.404] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.805 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.536 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.270 ±(99.9%) 0.004 ms/op
Iteration   1: 3.317 ±(99.9%) 0.003 ms/op
Iteration   2: 3.386 ±(99.9%) 0.004 ms/op
Iteration   3: 3.342 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.348 ±(99.9%) 0.634 ms/op [Average]
  (min, avg, max) = (3.317, 3.348, 3.386), stdev = 0.035
  CI (99.9%): [2.714, 3.983] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.160 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.716 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.578 ±(99.9%) 0.004 ms/op
Iteration   1: 3.555 ±(99.9%) 0.006 ms/op
Iteration   2: 3.522 ±(99.9%) 0.005 ms/op
Iteration   3: 3.500 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.526 ±(99.9%) 0.506 ms/op [Average]
  (min, avg, max) = (3.500, 3.526, 3.555), stdev = 0.028
  CI (99.9%): [3.020, 4.032] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.166 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 5.085 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.775 ±(99.9%) 0.020 ms/op
Iteration   1: 4.743 ±(99.9%) 0.015 ms/op
Iteration   2: 4.658 ±(99.9%) 0.011 ms/op
Iteration   3: 4.726 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.709 ±(99.9%) 0.823 ms/op [Average]
  (min, avg, max) = (4.658, 4.709, 4.743), stdev = 0.045
  CI (99.9%): [3.886, 5.532] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.464 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.794 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.574 ±(99.9%) 0.009 ms/op
Iteration   1: 3.494 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.017 ms/op
                 createUser·p0.50:   3.473 ms/op
                 createUser·p0.90:   4.116 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   5.702 ms/op
                 createUser·p0.999:  9.126 ms/op
                 createUser·p0.9999: 23.915 ms/op
                 createUser·p1.00:   24.117 ms/op

Iteration   2: 3.517 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.941 ms/op
                 createUser·p0.50:   3.473 ms/op
                 createUser·p0.90:   4.116 ms/op
                 createUser·p0.95:   4.415 ms/op
                 createUser·p0.99:   5.194 ms/op
                 createUser·p0.999:  11.617 ms/op
                 createUser·p0.9999: 18.707 ms/op
                 createUser·p1.00:   20.152 ms/op

Iteration   3: 3.566 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.840 ms/op
                 createUser·p0.50:   3.514 ms/op
                 createUser·p0.90:   4.018 ms/op
                 createUser·p0.95:   4.399 ms/op
                 createUser·p0.99:   5.169 ms/op
                 createUser·p0.999:  10.994 ms/op
                 createUser·p0.9999: 19.333 ms/op
                 createUser·p1.00:   20.185 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 272272
  mean =      3.526 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7879 
    [ 2.500,  5.000) = 260277 
    [ 5.000,  7.500) = 3423 
    [ 7.500, 10.000) = 443 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.840 ms/op
     p(50.0000) =      3.486 ms/op
     p(90.0000) =      4.088 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.415 ms/op
     p(99.9000) =      9.658 ms/op
     p(99.9900) =     23.578 ms/op
     p(99.9990) =     24.061 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


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
# Warmup Iteration   1: 4.786 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.641 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.341 ±(99.9%) 0.008 ms/op
Iteration   1: 3.363 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.826 ms/op
                 existUser·p0.50:   3.363 ms/op
                 existUser·p0.90:   3.863 ms/op
                 existUser·p0.95:   4.141 ms/op
                 existUser·p0.99:   5.341 ms/op
                 existUser·p0.999:  9.978 ms/op
                 existUser·p0.9999: 15.441 ms/op
                 existUser·p1.00:   15.712 ms/op

Iteration   2: 3.379 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.788 ms/op
                 existUser·p0.50:   3.355 ms/op
                 existUser·p0.90:   3.817 ms/op
                 existUser·p0.95:   4.039 ms/op
                 existUser·p0.99:   5.172 ms/op
                 existUser·p0.999:  8.798 ms/op
                 existUser·p0.9999: 14.731 ms/op
                 existUser·p1.00:   15.712 ms/op

Iteration   3: 3.328 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.815 ms/op
                 existUser·p0.50:   3.330 ms/op
                 existUser·p0.90:   3.895 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   5.022 ms/op
                 existUser·p0.999:  10.273 ms/op
                 existUser·p0.9999: 21.955 ms/op
                 existUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 286005
  mean =      3.356 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13351 
    [ 2.500,  5.000) = 269371 
    [ 5.000,  7.500) = 2642 
    [ 7.500, 10.000) = 409 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.788 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.137 ms/op
     p(99.0000) =      5.202 ms/op
     p(99.9000) =      9.421 ms/op
     p(99.9900) =     20.952 ms/op
     p(99.9990) =     22.123 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.924 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.555 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.414 ±(99.9%) 0.007 ms/op
Iteration   1: 3.495 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.838 ms/op
                 getUser·p0.50:   3.453 ms/op
                 getUser·p0.90:   4.153 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   5.464 ms/op
                 getUser·p0.999:  10.133 ms/op
                 getUser·p0.9999: 22.249 ms/op
                 getUser·p1.00:   22.446 ms/op

Iteration   2: 3.491 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.927 ms/op
                 getUser·p0.50:   3.486 ms/op
                 getUser·p0.90:   4.026 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   5.505 ms/op
                 getUser·p0.999:  9.994 ms/op
                 getUser·p0.9999: 16.310 ms/op
                 getUser·p1.00:   16.712 ms/op

Iteration   3: 3.555 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.698 ms/op
                 getUser·p0.50:   3.494 ms/op
                 getUser·p0.90:   4.194 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   5.390 ms/op
                 getUser·p0.999:  9.126 ms/op
                 getUser·p0.9999: 20.677 ms/op
                 getUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 273189
  mean =      3.513 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8890 
    [ 2.500,  5.000) = 259960 
    [ 5.000,  7.500) = 3609 
    [ 7.500, 10.000) = 481 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.698 ms/op
     p(50.0000) =      3.478 ms/op
     p(90.0000) =      4.125 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =      9.781 ms/op
     p(99.9900) =     21.889 ms/op
     p(99.9990) =     22.357 ms/op
     p(99.9999) =     22.446 ms/op
    p(100.0000) =     22.446 ms/op


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
# Warmup Iteration   1: 6.256 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.772 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.680 ±(99.9%) 0.014 ms/op
Iteration   1: 4.643 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.884 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   5.448 ms/op
                 listUser·p0.95:   6.314 ms/op
                 listUser·p0.99:   8.211 ms/op
                 listUser·p0.999:  15.487 ms/op
                 listUser·p0.9999: 19.082 ms/op
                 listUser·p1.00:   19.726 ms/op

Iteration   2: 4.598 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.556 ms/op
                 listUser·p0.50:   4.424 ms/op
                 listUser·p0.90:   5.464 ms/op
                 listUser·p0.95:   6.431 ms/op
                 listUser·p0.99:   8.135 ms/op
                 listUser·p0.999:  16.843 ms/op
                 listUser·p0.9999: 22.188 ms/op
                 listUser·p1.00:   22.610 ms/op

Iteration   3: 4.643 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.768 ms/op
                 listUser·p0.50:   4.432 ms/op
                 listUser·p0.90:   5.800 ms/op
                 listUser·p0.95:   6.554 ms/op
                 listUser·p0.99:   8.258 ms/op
                 listUser·p0.999:  18.219 ms/op
                 listUser·p0.9999: 20.431 ms/op
                 listUser·p1.00:   22.544 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 207403
  mean =      4.628 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 274 
    [ 2.500,  5.000) = 170741 
    [ 5.000,  7.500) = 32507 
    [ 7.500, 10.000) = 3252 
    [10.000, 12.500) = 295 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 165 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      4.456 ms/op
     p(90.0000) =      5.595 ms/op
     p(95.0000) =      6.439 ms/op
     p(99.0000) =      8.200 ms/op
     p(99.9000) =     16.476 ms/op
     p(99.9900) =     20.587 ms/op
     p(99.9990) =     22.542 ms/op
     p(99.9999) =     22.610 ms/op
    p(100.0000) =     22.610 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.052 ± 2.697  ops/ms
ClientGrpc.existUser                       thrpt       3   9.674 ± 3.611  ops/ms
ClientGrpc.getUser                         thrpt       3   9.064 ± 0.919  ops/ms
ClientGrpc.listUser                        thrpt       3   6.821 ± 1.214  ops/ms
ClientGrpc.createUser                       avgt       3   3.527 ± 0.878   ms/op
ClientGrpc.existUser                        avgt       3   3.348 ± 0.634   ms/op
ClientGrpc.getUser                          avgt       3   3.526 ± 0.506   ms/op
ClientGrpc.listUser                         avgt       3   4.709 ± 0.823   ms/op
ClientGrpc.createUser                     sample  272272   3.526 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.840           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.486           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.088           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.415           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.415           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.658           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.578           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.117           ms/op
ClientGrpc.existUser                      sample  286005   3.356 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.788           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.351           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.854           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.137           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.202           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.421           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.952           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.217           ms/op
ClientGrpc.getUser                        sample  273189   3.513 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.698           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.478           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.125           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.415           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.456           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.781           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.889           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.446           ms/op
ClientGrpc.listUser                       sample  207403   4.628 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.768           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.456           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.595           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.439           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.200           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.476           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.587           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.610           ms/op
