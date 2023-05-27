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
# Warmup Iteration   1: 4.604 ops/ms
# Warmup Iteration   2: 9.321 ops/ms
# Warmup Iteration   3: 10.434 ops/ms
Iteration   1: 10.547 ops/ms
Iteration   2: 10.733 ops/ms
Iteration   3: 10.714 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.665 ±(99.9%) 1.865 ops/ms [Average]
  (min, avg, max) = (10.547, 10.665, 10.733), stdev = 0.102
  CI (99.9%): [8.800, 12.529] (assumes normal distribution)


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
# Warmup Iteration   1: 7.907 ops/ms
# Warmup Iteration   2: 10.627 ops/ms
# Warmup Iteration   3: 11.079 ops/ms
Iteration   1: 11.078 ops/ms
Iteration   2: 11.022 ops/ms
Iteration   3: 10.932 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.011 ±(99.9%) 1.336 ops/ms [Average]
  (min, avg, max) = (10.932, 11.011, 11.078), stdev = 0.073
  CI (99.9%): [9.675, 12.347] (assumes normal distribution)


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
# Warmup Iteration   1: 8.229 ops/ms
# Warmup Iteration   2: 10.196 ops/ms
# Warmup Iteration   3: 10.882 ops/ms
Iteration   1: 10.611 ops/ms
Iteration   2: 10.874 ops/ms
Iteration   3: 10.880 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.788 ±(99.9%) 2.804 ops/ms [Average]
  (min, avg, max) = (10.611, 10.788, 10.880), stdev = 0.154
  CI (99.9%): [7.984, 13.593] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.791 ops/ms
# Warmup Iteration   2: 7.928 ops/ms
# Warmup Iteration   3: 8.244 ops/ms
Iteration   1: 8.296 ops/ms
Iteration   2: 8.183 ops/ms
Iteration   3: 8.339 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.273 ±(99.9%) 1.469 ops/ms [Average]
  (min, avg, max) = (8.183, 8.273, 8.339), stdev = 0.081
  CI (99.9%): [6.803, 9.742] (assumes normal distribution)


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
# Warmup Iteration   1: 3.905 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.134 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.009 ±(99.9%) 0.003 ms/op
Iteration   1: 2.972 ±(99.9%) 0.003 ms/op
Iteration   2: 2.971 ±(99.9%) 0.002 ms/op
Iteration   3: 2.981 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.975 ±(99.9%) 0.101 ms/op [Average]
  (min, avg, max) = (2.971, 2.975, 2.981), stdev = 0.006
  CI (99.9%): [2.874, 3.076] (assumes normal distribution)


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
# Warmup Iteration   1: 3.698 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.976 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.889 ±(99.9%) 0.008 ms/op
Iteration   1: 2.848 ±(99.9%) 0.004 ms/op
Iteration   2: 2.929 ±(99.9%) 0.003 ms/op
Iteration   3: 2.822 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.866 ±(99.9%) 1.017 ms/op [Average]
  (min, avg, max) = (2.822, 2.866, 2.929), stdev = 0.056
  CI (99.9%): [1.849, 3.883] (assumes normal distribution)


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
# Warmup Iteration   1: 4.179 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.081 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.006 ms/op
Iteration   1: 2.959 ±(99.9%) 0.002 ms/op
Iteration   2: 2.981 ±(99.9%) 0.003 ms/op
Iteration   3: 2.977 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.972 ±(99.9%) 0.210 ms/op [Average]
  (min, avg, max) = (2.959, 2.972, 2.981), stdev = 0.012
  CI (99.9%): [2.762, 3.183] (assumes normal distribution)


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
# Warmup Iteration   1: 4.481 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.142 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.858 ±(99.9%) 0.016 ms/op
Iteration   1: 3.795 ±(99.9%) 0.022 ms/op
Iteration   2: 3.955 ±(99.9%) 0.028 ms/op
Iteration   3: 3.850 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.866 ±(99.9%) 1.486 ms/op [Average]
  (min, avg, max) = (3.795, 3.866, 3.955), stdev = 0.081
  CI (99.9%): [2.381, 5.352] (assumes normal distribution)


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
# Warmup Iteration   1: 3.884 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.152 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.009 ±(99.9%) 0.006 ms/op
Iteration   1: 3.035 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.797 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.232 ms/op
                 createUser·p0.999:  7.205 ms/op
                 createUser·p0.9999: 15.081 ms/op
                 createUser·p1.00:   15.450 ms/op

Iteration   2: 2.976 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.734 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  7.307 ms/op
                 createUser·p0.9999: 17.113 ms/op
                 createUser·p1.00:   18.285 ms/op

Iteration   3: 2.980 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.693 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.461 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   4.202 ms/op
                 createUser·p0.999:  7.379 ms/op
                 createUser·p0.9999: 23.839 ms/op
                 createUser·p1.00:   24.347 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320331
  mean =      2.996 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26372 
    [ 2.500,  5.000) = 292924 
    [ 5.000,  7.500) = 755 
    [ 7.500, 10.000) = 72 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      7.299 ms/op
     p(99.9900) =     20.992 ms/op
     p(99.9990) =     24.111 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


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
# Warmup Iteration   1: 3.899 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.973 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.900 ±(99.9%) 0.006 ms/op
Iteration   1: 2.900 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.787 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   4.620 ms/op
                 existUser·p0.999:  8.229 ms/op
                 existUser·p0.9999: 11.763 ms/op
                 existUser·p1.00:   12.026 ms/op

Iteration   2: 2.878 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.515 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.252 ms/op
                 existUser·p0.95:   3.432 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  10.022 ms/op
                 existUser·p0.9999: 12.202 ms/op
                 existUser·p1.00:   14.434 ms/op

Iteration   3: 2.846 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.631 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.252 ms/op
                 existUser·p0.95:   3.420 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  6.324 ms/op
                 existUser·p0.9999: 24.183 ms/op
                 existUser·p1.00:   25.494 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 334056
  mean =      2.874 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45468 
    [ 2.500,  5.000) = 287283 
    [ 5.000,  7.500) = 935 
    [ 7.500, 10.000) = 123 
    [10.000, 12.500) = 177 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.515 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.334 ms/op
     p(95.0000) =      3.613 ms/op
     p(99.0000) =      4.476 ms/op
     p(99.9000) =      7.839 ms/op
     p(99.9900) =     15.424 ms/op
     p(99.9990) =     25.231 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


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
# Warmup Iteration   1: 3.985 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.079 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.051 ±(99.9%) 0.007 ms/op
Iteration   1: 3.019 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.680 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.629 ms/op
                 getUser·p0.99:   4.129 ms/op
                 getUser·p0.999:  8.159 ms/op
                 getUser·p0.9999: 13.333 ms/op
                 getUser·p1.00:   13.681 ms/op

Iteration   2: 2.987 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.583 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  7.274 ms/op
                 getUser·p0.9999: 12.571 ms/op
                 getUser·p1.00:   12.730 ms/op

Iteration   3: 2.964 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.745 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.408 ms/op
                 getUser·p0.95:   3.600 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  6.833 ms/op
                 getUser·p0.9999: 15.073 ms/op
                 getUser·p1.00:   15.401 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320889
  mean =      2.990 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1603 
    [ 1.250,  2.500) = 22832 
    [ 2.500,  3.750) = 284955 
    [ 3.750,  5.000) = 10428 
    [ 5.000,  6.250) = 531 
    [ 6.250,  7.500) = 264 
    [ 7.500,  8.750) = 72 
    [ 8.750, 10.000) = 21 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 90 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.583 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.650 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      7.201 ms/op
     p(99.9900) =     14.457 ms/op
     p(99.9990) =     15.259 ms/op
     p(99.9999) =     15.401 ms/op
    p(100.0000) =     15.401 ms/op


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
# Warmup Iteration   1: 5.293 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.994 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.011 ±(99.9%) 0.011 ms/op
Iteration   1: 3.930 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.914 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.488 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  13.369 ms/op
                 listUser·p0.9999: 21.186 ms/op
                 listUser·p1.00:   21.398 ms/op

Iteration   2: 3.889 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.805 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   6.513 ms/op
                 listUser·p0.999:  17.039 ms/op
                 listUser·p0.9999: 25.774 ms/op
                 listUser·p1.00:   26.051 ms/op

Iteration   3: 3.937 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.015 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  13.766 ms/op
                 listUser·p0.9999: 21.454 ms/op
                 listUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245155
  mean =      3.919 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4047 
    [ 2.500,  5.000) = 220625 
    [ 5.000,  7.500) = 19249 
    [ 7.500, 10.000) = 789 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 134 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.805 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.833 ms/op
     p(95.0000) =      5.513 ms/op
     p(99.0000) =      6.770 ms/op
     p(99.9000) =     14.514 ms/op
     p(99.9900) =     23.247 ms/op
     p(99.9990) =     25.937 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.665 ± 1.865  ops/ms
ClientGrpc.existUser                       thrpt       3  11.011 ± 1.336  ops/ms
ClientGrpc.getUser                         thrpt       3  10.788 ± 2.804  ops/ms
ClientGrpc.listUser                        thrpt       3   8.273 ± 1.469  ops/ms
ClientGrpc.createUser                       avgt       3   2.975 ± 0.101   ms/op
ClientGrpc.existUser                        avgt       3   2.866 ± 1.017   ms/op
ClientGrpc.getUser                          avgt       3   2.972 ± 0.210   ms/op
ClientGrpc.listUser                         avgt       3   3.866 ± 1.486   ms/op
ClientGrpc.createUser                     sample  320331   2.996 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.693           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.982           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.531           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.760           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.293           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.299           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.992           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.347           ms/op
ClientGrpc.existUser                      sample  334056   2.874 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.515           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.334           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.613           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.476           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.839           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.424           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.494           ms/op
ClientGrpc.getUser                        sample  320889   2.990 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.583           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.994           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.469           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.650           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.268           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.201           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.457           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          15.401           ms/op
ClientGrpc.listUser                       sample  245155   3.919 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.805           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.777           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.833           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.513           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.770           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.514           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.247           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.051           ms/op
