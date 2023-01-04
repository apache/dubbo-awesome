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
# Warmup Iteration   1: 3.439 ops/ms
# Warmup Iteration   2: 7.028 ops/ms
# Warmup Iteration   3: 8.443 ops/ms
Iteration   1: 8.454 ops/ms
Iteration   2: 8.417 ops/ms
Iteration   3: 8.462 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.445 ±(99.9%) 0.440 ops/ms [Average]
  (min, avg, max) = (8.417, 8.445, 8.462), stdev = 0.024
  CI (99.9%): [8.005, 8.884] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.323 ops/ms
# Warmup Iteration   2: 8.576 ops/ms
# Warmup Iteration   3: 8.838 ops/ms
Iteration   1: 8.798 ops/ms
Iteration   2: 8.655 ops/ms
Iteration   3: 8.746 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.733 ±(99.9%) 1.317 ops/ms [Average]
  (min, avg, max) = (8.655, 8.733, 8.798), stdev = 0.072
  CI (99.9%): [7.416, 10.050] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.623 ops/ms
# Warmup Iteration   2: 8.034 ops/ms
# Warmup Iteration   3: 8.567 ops/ms
Iteration   1: 8.256 ops/ms
Iteration   2: 8.515 ops/ms
Iteration   3: 8.488 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.420 ±(99.9%) 2.604 ops/ms [Average]
  (min, avg, max) = (8.256, 8.420, 8.515), stdev = 0.143
  CI (99.9%): [5.815, 11.024] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.418 ops/ms
# Warmup Iteration   2: 6.217 ops/ms
# Warmup Iteration   3: 6.599 ops/ms
Iteration   1: 6.723 ops/ms
Iteration   2: 6.704 ops/ms
Iteration   3: 6.894 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.773 ±(99.9%) 1.910 ops/ms [Average]
  (min, avg, max) = (6.704, 6.773, 6.894), stdev = 0.105
  CI (99.9%): [4.863, 8.684] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.235 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.020 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.869 ±(99.9%) 0.015 ms/op
Iteration   1: 3.917 ±(99.9%) 0.004 ms/op
Iteration   2: 3.864 ±(99.9%) 0.002 ms/op
Iteration   3: 3.843 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.874 ±(99.9%) 0.695 ms/op [Average]
  (min, avg, max) = (3.843, 3.874, 3.917), stdev = 0.038
  CI (99.9%): [3.179, 4.570] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.967 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.813 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.777 ±(99.9%) 0.013 ms/op
Iteration   1: 3.625 ±(99.9%) 0.004 ms/op
Iteration   2: 3.669 ±(99.9%) 0.003 ms/op
Iteration   3: 3.597 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.631 ±(99.9%) 0.660 ms/op [Average]
  (min, avg, max) = (3.597, 3.631, 3.669), stdev = 0.036
  CI (99.9%): [2.971, 4.290] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 4.676 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 4.064 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.905 ±(99.9%) 0.004 ms/op
Iteration   1: 3.787 ±(99.9%) 0.003 ms/op
Iteration   2: 3.868 ±(99.9%) 0.003 ms/op
Iteration   3: 3.798 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.818 ±(99.9%) 0.800 ms/op [Average]
  (min, avg, max) = (3.787, 3.818, 3.868), stdev = 0.044
  CI (99.9%): [3.018, 4.617] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 7.004 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.971 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.807 ±(99.9%) 0.012 ms/op
Iteration   1: 4.768 ±(99.9%) 0.007 ms/op
Iteration   2: 4.720 ±(99.9%) 0.020 ms/op
Iteration   3: 4.726 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.738 ±(99.9%) 0.472 ms/op [Average]
  (min, avg, max) = (4.720, 4.738, 4.768), stdev = 0.026
  CI (99.9%): [4.266, 5.210] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.487 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.860 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.872 ±(99.9%) 0.010 ms/op
Iteration   1: 3.818 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.698 ms/op
                 createUser·p0.50:   3.744 ms/op
                 createUser·p0.90:   4.719 ms/op
                 createUser·p0.95:   5.079 ms/op
                 createUser·p0.99:   6.521 ms/op
                 createUser·p0.999:  11.316 ms/op
                 createUser·p0.9999: 16.355 ms/op
                 createUser·p1.00:   16.712 ms/op

Iteration   2: 3.908 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.139 ms/op
                 createUser·p0.50:   3.826 ms/op
                 createUser·p0.90:   4.809 ms/op
                 createUser·p0.95:   5.120 ms/op
                 createUser·p0.99:   6.365 ms/op
                 createUser·p0.999:  10.784 ms/op
                 createUser·p0.9999: 18.228 ms/op
                 createUser·p1.00:   19.366 ms/op

Iteration   3: 3.808 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.650 ms/op
                 createUser·p0.50:   3.727 ms/op
                 createUser·p0.90:   4.538 ms/op
                 createUser·p0.95:   4.833 ms/op
                 createUser·p0.99:   6.308 ms/op
                 createUser·p0.999:  13.564 ms/op
                 createUser·p0.9999: 29.478 ms/op
                 createUser·p1.00:   30.048 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 249668
  mean =      3.845 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5695 
    [ 2.500,  5.000) = 230976 
    [ 5.000,  7.500) = 11698 
    [ 7.500, 10.000) = 835 
    [10.000, 12.500) = 262 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 44 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.650 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.702 ms/op
     p(95.0000) =      5.022 ms/op
     p(99.0000) =      6.414 ms/op
     p(99.9000) =     11.354 ms/op
     p(99.9900) =     27.460 ms/op
     p(99.9990) =     29.950 ms/op
     p(99.9999) =     30.048 ms/op
    p(100.0000) =     30.048 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 4.835 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.895 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.701 ±(99.9%) 0.010 ms/op
Iteration   1: 3.641 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.949 ms/op
                 existUser·p0.50:   3.625 ms/op
                 existUser·p0.90:   4.497 ms/op
                 existUser·p0.95:   4.727 ms/op
                 existUser·p0.99:   5.415 ms/op
                 existUser·p0.999:  8.607 ms/op
                 existUser·p0.9999: 19.904 ms/op
                 existUser·p1.00:   23.757 ms/op

Iteration   2: 3.598 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.886 ms/op
                 existUser·p0.50:   3.584 ms/op
                 existUser·p0.90:   4.481 ms/op
                 existUser·p0.95:   4.727 ms/op
                 existUser·p0.99:   5.497 ms/op
                 existUser·p0.999:  8.013 ms/op
                 existUser·p0.9999: 19.075 ms/op
                 existUser·p1.00:   19.628 ms/op

Iteration   3: 3.743 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.073 ms/op
                 existUser·p0.50:   3.654 ms/op
                 existUser·p0.90:   4.596 ms/op
                 existUser·p0.95:   4.891 ms/op
                 existUser·p0.99:   6.455 ms/op
                 existUser·p0.999:  9.961 ms/op
                 existUser·p0.9999: 25.766 ms/op
                 existUser·p1.00:   26.116 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 262308
  mean =      3.660 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12203 
    [ 2.500,  5.000) = 242640 
    [ 5.000,  7.500) = 6620 
    [ 7.500, 10.000) = 653 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.886 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =      8.995 ms/op
     p(99.9900) =     25.060 ms/op
     p(99.9990) =     26.063 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.393 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.933 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.886 ±(99.9%) 0.010 ms/op
Iteration   1: 3.942 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.180 ms/op
                 getUser·p0.50:   3.863 ms/op
                 getUser·p0.90:   4.841 ms/op
                 getUser·p0.95:   5.153 ms/op
                 getUser·p0.99:   6.578 ms/op
                 getUser·p0.999:  11.387 ms/op
                 getUser·p0.9999: 15.936 ms/op
                 getUser·p1.00:   16.286 ms/op

Iteration   2: 3.871 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.928 ms/op
                 getUser·p0.50:   3.809 ms/op
                 getUser·p0.90:   4.751 ms/op
                 getUser·p0.95:   5.022 ms/op
                 getUser·p0.99:   6.423 ms/op
                 getUser·p0.999:  11.272 ms/op
                 getUser·p0.9999: 16.368 ms/op
                 getUser·p1.00:   16.777 ms/op

Iteration   3: 3.777 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.964 ms/op
                 getUser·p0.50:   3.707 ms/op
                 getUser·p0.90:   4.620 ms/op
                 getUser·p0.95:   4.956 ms/op
                 getUser·p0.99:   5.961 ms/op
                 getUser·p0.999:  8.798 ms/op
                 getUser·p0.9999: 26.232 ms/op
                 getUser·p1.00:   29.327 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 248493
  mean =      3.862 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6028 
    [ 2.500,  5.000) = 228618 
    [ 5.000,  7.500) = 12806 
    [ 7.500, 10.000) = 700 
    [10.000, 12.500) = 180 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.928 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.743 ms/op
     p(95.0000) =      5.046 ms/op
     p(99.0000) =      6.308 ms/op
     p(99.9000) =     11.190 ms/op
     p(99.9900) =     25.738 ms/op
     p(99.9990) =     28.989 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


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
# Warmup Iteration   1: 6.570 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 5.053 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.777 ±(99.9%) 0.014 ms/op
Iteration   1: 4.834 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.534 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   6.185 ms/op
                 listUser·p0.95:   6.816 ms/op
                 listUser·p0.99:   8.454 ms/op
                 listUser·p0.999:  15.732 ms/op
                 listUser·p0.9999: 23.826 ms/op
                 listUser·p1.00:   24.281 ms/op

Iteration   2: 4.776 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.100 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   6.054 ms/op
                 listUser·p0.95:   6.775 ms/op
                 listUser·p0.99:   8.832 ms/op
                 listUser·p0.999:  16.120 ms/op
                 listUser·p0.9999: 22.989 ms/op
                 listUser·p1.00:   23.364 ms/op

Iteration   3: 4.770 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.444 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   6.185 ms/op
                 listUser·p0.95:   7.004 ms/op
                 listUser·p0.99:   8.815 ms/op
                 listUser·p0.999:  21.036 ms/op
                 listUser·p0.9999: 26.558 ms/op
                 listUser·p1.00:   26.968 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 200374
  mean =      4.793 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 445 
    [ 2.500,  5.000) = 143769 
    [ 5.000,  7.500) = 50751 
    [ 7.500, 10.000) = 4554 
    [10.000, 12.500) = 444 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 123 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      4.571 ms/op
     p(90.0000) =      6.144 ms/op
     p(95.0000) =      6.865 ms/op
     p(99.0000) =      8.716 ms/op
     p(99.9000) =     16.591 ms/op
     p(99.9900) =     25.652 ms/op
     p(99.9990) =     26.870 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.445 ± 0.440  ops/ms
ClientGrpc.existUser                       thrpt       3   8.733 ± 1.317  ops/ms
ClientGrpc.getUser                         thrpt       3   8.420 ± 2.604  ops/ms
ClientGrpc.listUser                        thrpt       3   6.773 ± 1.910  ops/ms
ClientGrpc.createUser                       avgt       3   3.874 ± 0.695   ms/op
ClientGrpc.existUser                        avgt       3   3.631 ± 0.660   ms/op
ClientGrpc.getUser                          avgt       3   3.818 ± 0.800   ms/op
ClientGrpc.listUser                         avgt       3   4.738 ± 0.472   ms/op
ClientGrpc.createUser                     sample  249668   3.845 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.650           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.760           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.702           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.022           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.414           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.354           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.460           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.048           ms/op
ClientGrpc.existUser                      sample  262308   3.660 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.886           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.621           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.522           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.776           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.710           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.995           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.060           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.116           ms/op
ClientGrpc.getUser                        sample  248493   3.862 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.928           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.785           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.743           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.046           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.308           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.190           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.738           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.327           ms/op
ClientGrpc.listUser                       sample  200374   4.793 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.100           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.571           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.144           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.865           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.716           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.591           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.652           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.968           ms/op
