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
# Warmup Iteration   1: 3.857 ops/ms
# Warmup Iteration   2: 8.490 ops/ms
# Warmup Iteration   3: 9.841 ops/ms
Iteration   1: 10.110 ops/ms
Iteration   2: 10.118 ops/ms
Iteration   3: 10.345 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.191 ±(99.9%) 2.432 ops/ms [Average]
  (min, avg, max) = (10.110, 10.191, 10.345), stdev = 0.133
  CI (99.9%): [7.759, 12.623] (assumes normal distribution)


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
# Warmup Iteration   1: 7.060 ops/ms
# Warmup Iteration   2: 10.437 ops/ms
# Warmup Iteration   3: 10.599 ops/ms
Iteration   1: 10.970 ops/ms
Iteration   2: 10.777 ops/ms
Iteration   3: 10.875 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.874 ±(99.9%) 1.763 ops/ms [Average]
  (min, avg, max) = (10.777, 10.874, 10.970), stdev = 0.097
  CI (99.9%): [9.111, 12.636] (assumes normal distribution)


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
# Warmup Iteration   1: 6.250 ops/ms
# Warmup Iteration   2: 10.127 ops/ms
# Warmup Iteration   3: 10.379 ops/ms
Iteration   1: 10.656 ops/ms
Iteration   2: 10.360 ops/ms
Iteration   3: 10.496 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.504 ±(99.9%) 2.704 ops/ms [Average]
  (min, avg, max) = (10.360, 10.504, 10.656), stdev = 0.148
  CI (99.9%): [7.800, 13.209] (assumes normal distribution)


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
# Warmup Iteration   1: 5.302 ops/ms
# Warmup Iteration   2: 7.554 ops/ms
# Warmup Iteration   3: 8.005 ops/ms
Iteration   1: 7.734 ops/ms
Iteration   2: 7.873 ops/ms
Iteration   3: 7.916 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.841 ±(99.9%) 1.728 ops/ms [Average]
  (min, avg, max) = (7.734, 7.841, 7.916), stdev = 0.095
  CI (99.9%): [6.113, 9.569] (assumes normal distribution)


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
# Warmup Iteration   1: 4.457 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.254 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.152 ±(99.9%) 0.002 ms/op
Iteration   1: 3.129 ±(99.9%) 0.002 ms/op
Iteration   2: 3.062 ±(99.9%) 0.003 ms/op
Iteration   3: 3.137 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.109 ±(99.9%) 0.759 ms/op [Average]
  (min, avg, max) = (3.062, 3.109, 3.137), stdev = 0.042
  CI (99.9%): [2.350, 3.869] (assumes normal distribution)


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
# Warmup Iteration   1: 4.072 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.132 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.003 ms/op
Iteration   1: 2.919 ±(99.9%) 0.004 ms/op
Iteration   2: 2.911 ±(99.9%) 0.002 ms/op
Iteration   3: 2.963 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.931 ±(99.9%) 0.508 ms/op [Average]
  (min, avg, max) = (2.911, 2.931, 2.963), stdev = 0.028
  CI (99.9%): [2.423, 3.439] (assumes normal distribution)


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
# Warmup Iteration   1: 4.267 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.143 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.093 ±(99.9%) 0.003 ms/op
Iteration   1: 3.060 ±(99.9%) 0.005 ms/op
Iteration   2: 3.098 ±(99.9%) 0.005 ms/op
Iteration   3: 3.047 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.068 ±(99.9%) 0.485 ms/op [Average]
  (min, avg, max) = (3.047, 3.068, 3.098), stdev = 0.027
  CI (99.9%): [2.583, 3.554] (assumes normal distribution)


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
# Warmup Iteration   1: 5.712 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.130 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.982 ±(99.9%) 0.009 ms/op
Iteration   1: 4.018 ±(99.9%) 0.015 ms/op
Iteration   2: 4.109 ±(99.9%) 0.016 ms/op
Iteration   3: 4.097 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.075 ±(99.9%) 0.901 ms/op [Average]
  (min, avg, max) = (4.018, 4.075, 4.109), stdev = 0.049
  CI (99.9%): [3.174, 4.975] (assumes normal distribution)


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
# Warmup Iteration   1: 4.383 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.268 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.177 ±(99.9%) 0.007 ms/op
Iteration   1: 3.104 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.927 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   4.981 ms/op
                 createUser·p0.999:  11.124 ms/op
                 createUser·p0.9999: 22.787 ms/op
                 createUser·p1.00:   23.003 ms/op

Iteration   2: 3.105 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.610 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.928 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  9.847 ms/op
                 createUser·p0.9999: 15.937 ms/op
                 createUser·p1.00:   16.843 ms/op

Iteration   3: 3.130 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.792 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   4.915 ms/op
                 createUser·p0.999:  13.156 ms/op
                 createUser·p0.9999: 18.695 ms/op
                 createUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308362
  mean =      3.113 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17694 
    [ 2.500,  5.000) = 288093 
    [ 5.000,  7.500) = 1705 
    [ 7.500, 10.000) = 540 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.610 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      4.792 ms/op
     p(99.9000) =     10.676 ms/op
     p(99.9900) =     21.993 ms/op
     p(99.9990) =     22.968 ms/op
     p(99.9999) =     23.003 ms/op
    p(100.0000) =     23.003 ms/op


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
# Warmup Iteration   1: 4.161 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.038 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.006 ms/op
Iteration   1: 2.980 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.696 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.768 ms/op
                 existUser·p0.99:   4.735 ms/op
                 existUser·p0.999:  7.969 ms/op
                 existUser·p0.9999: 14.136 ms/op
                 existUser·p1.00:   14.549 ms/op

Iteration   2: 2.980 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.819 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  7.325 ms/op
                 existUser·p0.9999: 15.630 ms/op
                 existUser·p1.00:   15.843 ms/op

Iteration   3: 2.976 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.764 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   4.653 ms/op
                 existUser·p0.999:  10.733 ms/op
                 existUser·p0.9999: 18.498 ms/op
                 existUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322111
  mean =      2.979 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 877 
    [ 1.250,  2.500) = 24874 
    [ 2.500,  3.750) = 283159 
    [ 3.750,  5.000) = 11255 
    [ 5.000,  6.250) = 967 
    [ 6.250,  7.500) = 481 
    [ 7.500,  8.750) = 219 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 62 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 37 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =      8.305 ms/op
     p(99.9900) =     17.622 ms/op
     p(99.9990) =     18.743 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.455 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.278 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.133 ±(99.9%) 0.007 ms/op
Iteration   1: 3.149 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.897 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   5.169 ms/op
                 getUser·p0.999:  11.106 ms/op
                 getUser·p0.9999: 14.514 ms/op
                 getUser·p1.00:   15.024 ms/op

Iteration   2: 3.113 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.830 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.912 ms/op
                 getUser·p0.99:   4.661 ms/op
                 getUser·p0.999:  9.379 ms/op
                 getUser·p0.9999: 15.469 ms/op
                 getUser·p1.00:   15.925 ms/op

Iteration   3: 3.138 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.824 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   3.990 ms/op
                 getUser·p0.99:   4.710 ms/op
                 getUser·p0.999:  8.063 ms/op
                 getUser·p0.9999: 18.141 ms/op
                 getUser·p1.00:   18.416 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306327
  mean =      3.133 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 520 
    [ 1.250,  2.500) = 13459 
    [ 2.500,  3.750) = 264624 
    [ 3.750,  5.000) = 25047 
    [ 5.000,  6.250) = 1407 
    [ 6.250,  7.500) = 534 
    [ 7.500,  8.750) = 339 
    [ 8.750, 10.000) = 109 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 75 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      3.965 ms/op
     p(99.0000) =      4.866 ms/op
     p(99.9000) =      9.748 ms/op
     p(99.9900) =     17.424 ms/op
     p(99.9990) =     18.315 ms/op
     p(99.9999) =     18.416 ms/op
    p(100.0000) =     18.416 ms/op


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
# Warmup Iteration   1: 5.746 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.137 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.043 ±(99.9%) 0.011 ms/op
Iteration   1: 4.091 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.264 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.997 ms/op
                 listUser·p0.99:   7.299 ms/op
                 listUser·p0.999:  14.087 ms/op
                 listUser·p0.9999: 17.271 ms/op
                 listUser·p1.00:   18.874 ms/op

Iteration   2: 3.948 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.159 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.980 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  15.843 ms/op
                 listUser·p0.9999: 24.242 ms/op
                 listUser·p1.00:   28.705 ms/op

Iteration   3: 4.105 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.809 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.757 ms/op
                 listUser·p0.99:   7.283 ms/op
                 listUser·p0.999:  17.334 ms/op
                 listUser·p0.9999: 21.660 ms/op
                 listUser·p1.00:   22.086 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237242
  mean =      4.047 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3338 
    [ 2.500,  5.000) = 206675 
    [ 5.000,  7.500) = 25371 
    [ 7.500, 10.000) = 1326 
    [10.000, 12.500) = 171 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.809 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      5.145 ms/op
     p(95.0000) =      5.923 ms/op
     p(99.0000) =      7.242 ms/op
     p(99.9000) =     14.959 ms/op
     p(99.9900) =     23.635 ms/op
     p(99.9990) =     27.048 ms/op
     p(99.9999) =     28.705 ms/op
    p(100.0000) =     28.705 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.191 ± 2.432  ops/ms
ClientGrpc.existUser                       thrpt       3  10.874 ± 1.763  ops/ms
ClientGrpc.getUser                         thrpt       3  10.504 ± 2.704  ops/ms
ClientGrpc.listUser                        thrpt       3   7.841 ± 1.728  ops/ms
ClientGrpc.createUser                       avgt       3   3.109 ± 0.759   ms/op
ClientGrpc.existUser                        avgt       3   2.931 ± 0.508   ms/op
ClientGrpc.getUser                          avgt       3   3.068 ± 0.485   ms/op
ClientGrpc.listUser                         avgt       3   4.075 ± 0.901   ms/op
ClientGrpc.createUser                     sample  308362   3.113 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.610           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.068           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.637           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.903           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.792           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.676           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.993           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.003           ms/op
ClientGrpc.existUser                      sample  322111   2.979 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.696           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.945           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.441           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.686           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.571           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.305           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.622           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.809           ms/op
ClientGrpc.getUser                        sample  306327   3.133 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.824           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.080           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.707           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.965           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.866           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.748           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.424           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.416           ms/op
ClientGrpc.listUser                       sample  237242   4.047 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.809           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.883           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.145           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.923           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.242           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.959           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.635           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.705           ms/op
