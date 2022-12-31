# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.560 ops/ms
# Warmup Iteration   2: 9.455 ops/ms
# Warmup Iteration   3: 10.436 ops/ms
Iteration   1: 10.078 ops/ms
Iteration   2: 10.368 ops/ms
Iteration   3: 10.293 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.246 ±(99.9%) 2.751 ops/ms [Average]
  (min, avg, max) = (10.078, 10.246, 10.368), stdev = 0.151
  CI (99.9%): [7.495, 12.997] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.127 ops/ms
# Warmup Iteration   2: 10.621 ops/ms
# Warmup Iteration   3: 11.170 ops/ms
Iteration   1: 10.746 ops/ms
Iteration   2: 11.188 ops/ms
Iteration   3: 10.953 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.962 ±(99.9%) 4.036 ops/ms [Average]
  (min, avg, max) = (10.746, 10.962, 11.188), stdev = 0.221
  CI (99.9%): [6.926, 14.998] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:50
# Fork: 1 of 1
# Warmup Iteration   1: 7.497 ops/ms
# Warmup Iteration   2: 10.584 ops/ms
# Warmup Iteration   3: 10.693 ops/ms
Iteration   1: 10.730 ops/ms
Iteration   2: 10.633 ops/ms
Iteration   3: 10.618 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.660 ±(99.9%) 1.116 ops/ms [Average]
  (min, avg, max) = (10.618, 10.660, 10.730), stdev = 0.061
  CI (99.9%): [9.544, 11.776] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.985 ops/ms
# Warmup Iteration   2: 7.893 ops/ms
# Warmup Iteration   3: 7.896 ops/ms
Iteration   1: 8.110 ops/ms
Iteration   2: 8.170 ops/ms
Iteration   3: 8.117 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.132 ±(99.9%) 0.599 ops/ms [Average]
  (min, avg, max) = (8.110, 8.132, 8.170), stdev = 0.033
  CI (99.9%): [7.533, 8.732] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.879 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.118 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.004 ms/op
Iteration   1: 3.130 ±(99.9%) 0.002 ms/op
Iteration   2: 3.141 ±(99.9%) 0.002 ms/op
Iteration   3: 3.202 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.158 ±(99.9%) 0.713 ms/op [Average]
  (min, avg, max) = (3.130, 3.158, 3.202), stdev = 0.039
  CI (99.9%): [2.445, 3.870] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.714 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.973 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.924 ±(99.9%) 0.002 ms/op
Iteration   1: 3.007 ±(99.9%) 0.001 ms/op
Iteration   2: 2.890 ±(99.9%) 0.004 ms/op
Iteration   3: 2.835 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.911 ±(99.9%) 1.603 ms/op [Average]
  (min, avg, max) = (2.835, 2.911, 3.007), stdev = 0.088
  CI (99.9%): [1.308, 4.514] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.964 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.046 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.003 ms/op
Iteration   1: 3.066 ±(99.9%) 0.002 ms/op
Iteration   2: 3.037 ±(99.9%) 0.002 ms/op
Iteration   3: 3.042 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.049 ±(99.9%) 0.284 ms/op [Average]
  (min, avg, max) = (3.037, 3.049, 3.066), stdev = 0.016
  CI (99.9%): [2.765, 3.332] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.361 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 4.108 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 3.916 ±(99.9%) 0.034 ms/op
Iteration   1: 4.026 ±(99.9%) 0.016 ms/op
Iteration   2: 3.870 ±(99.9%) 0.019 ms/op
Iteration   3: 3.852 ±(99.9%) 0.078 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.916 ±(99.9%) 1.740 ms/op [Average]
  (min, avg, max) = (3.852, 3.916, 4.026), stdev = 0.095
  CI (99.9%): [2.176, 5.656] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.653 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.994 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.981 ±(99.9%) 0.006 ms/op
Iteration   1: 3.006 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.210 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  7.684 ms/op
                 createUser·p0.9999: 26.739 ms/op
                 createUser·p1.00:   26.903 ms/op

Iteration   2: 3.090 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.628 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.744 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  11.969 ms/op
                 createUser·p0.9999: 19.366 ms/op
                 createUser·p1.00:   21.594 ms/op

Iteration   3: 3.106 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.567 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   4.202 ms/op
                 createUser·p0.999:  7.561 ms/op
                 createUser·p0.9999: 20.470 ms/op
                 createUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313045
  mean =      3.067 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29375 
    [ 2.500,  5.000) = 282555 
    [ 5.000,  7.500) = 717 
    [ 7.500, 10.000) = 105 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.210 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      8.976 ms/op
     p(99.9900) =     25.231 ms/op
     p(99.9990) =     26.771 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.549 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.938 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.952 ±(99.9%) 0.006 ms/op
Iteration   1: 2.940 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.681 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   4.022 ms/op
                 existUser·p0.999:  5.830 ms/op
                 existUser·p0.9999: 21.008 ms/op
                 existUser·p1.00:   21.463 ms/op

Iteration   2: 2.953 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.884 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   4.145 ms/op
                 existUser·p0.999:  6.193 ms/op
                 existUser·p0.9999: 12.943 ms/op
                 existUser·p1.00:   14.008 ms/op

Iteration   3: 2.922 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.605 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   4.145 ms/op
                 existUser·p0.999:  5.698 ms/op
                 existUser·p0.9999: 17.108 ms/op
                 existUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326660
  mean =      2.938 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51078 
    [ 2.500,  5.000) = 274909 
    [ 5.000,  7.500) = 495 
    [ 7.500, 10.000) = 18 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.605 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      4.096 ms/op
     p(99.9000) =      5.931 ms/op
     p(99.9900) =     18.494 ms/op
     p(99.9990) =     21.323 ms/op
     p(99.9999) =     21.463 ms/op
    p(100.0000) =     21.463 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.977 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.062 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.976 ±(99.9%) 0.006 ms/op
Iteration   1: 2.981 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.655 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  6.524 ms/op
                 getUser·p0.9999: 11.981 ms/op
                 getUser·p1.00:   12.206 ms/op

Iteration   2: 3.043 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.697 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  6.889 ms/op
                 getUser·p0.9999: 13.475 ms/op
                 getUser·p1.00:   13.992 ms/op

Iteration   3: 3.186 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.216 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   4.391 ms/op
                 getUser·p0.99:   5.677 ms/op
                 getUser·p0.999:  12.035 ms/op
                 getUser·p0.9999: 24.116 ms/op
                 getUser·p1.00:   25.231 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312805
  mean =      3.068 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30407 
    [ 2.500,  5.000) = 279613 
    [ 5.000,  7.500) = 2385 
    [ 7.500, 10.000) = 152 
    [10.000, 12.500) = 117 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.216 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      4.899 ms/op
     p(99.9000) =      8.667 ms/op
     p(99.9900) =     22.924 ms/op
     p(99.9990) =     25.133 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.315 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.904 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.988 ±(99.9%) 0.011 ms/op
Iteration   1: 3.930 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.781 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  16.662 ms/op
                 listUser·p0.9999: 20.301 ms/op
                 listUser·p1.00:   20.742 ms/op

Iteration   2: 3.928 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.384 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.578 ms/op
                 listUser·p0.999:  13.615 ms/op
                 listUser·p0.9999: 23.747 ms/op
                 listUser·p1.00:   26.575 ms/op

Iteration   3: 4.036 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.729 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  17.269 ms/op
                 listUser·p0.9999: 20.781 ms/op
                 listUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242322
  mean =      3.964 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4013 
    [ 2.500,  5.000) = 211734 
    [ 5.000,  7.500) = 25335 
    [ 7.500, 10.000) = 691 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 187 
    [15.000, 17.500) = 125 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.729 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      5.079 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      6.847 ms/op
     p(99.9000) =     15.761 ms/op
     p(99.9900) =     23.233 ms/op
     p(99.9990) =     26.487 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.246 ± 2.751  ops/ms
ClientGrpc.existUser                       thrpt       3  10.962 ± 4.036  ops/ms
ClientGrpc.getUser                         thrpt       3  10.660 ± 1.116  ops/ms
ClientGrpc.listUser                        thrpt       3   8.132 ± 0.599  ops/ms
ClientGrpc.createUser                       avgt       3   3.158 ± 0.713   ms/op
ClientGrpc.existUser                        avgt       3   2.911 ± 1.603   ms/op
ClientGrpc.getUser                          avgt       3   3.049 ± 0.284   ms/op
ClientGrpc.listUser                         avgt       3   3.916 ± 1.740   ms/op
ClientGrpc.createUser                     sample  313045   3.067 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.210           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.039           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.699           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.887           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.260           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.976           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.231           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.903           ms/op
ClientGrpc.existUser                      sample  326660   2.938 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.605           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.925           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.539           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.723           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.096           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           5.931           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.494           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.463           ms/op
ClientGrpc.getUser                        sample  312805   3.068 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.216           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.035           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.699           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.969           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.899           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.667           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.924           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.231           ms/op
ClientGrpc.listUser                       sample  242322   3.964 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.729           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.785           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.079           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.612           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.847           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.761           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.233           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.575           ms/op
