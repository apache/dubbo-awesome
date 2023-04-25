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
# Warmup Iteration   1: 3.979 ops/ms
# Warmup Iteration   2: 9.281 ops/ms
# Warmup Iteration   3: 10.120 ops/ms
Iteration   1: 10.463 ops/ms
Iteration   2: 10.989 ops/ms
Iteration   3: 10.463 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.638 ±(99.9%) 5.548 ops/ms [Average]
  (min, avg, max) = (10.463, 10.638, 10.989), stdev = 0.304
  CI (99.9%): [5.091, 16.186] (assumes normal distribution)


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
# Warmup Iteration   1: 7.385 ops/ms
# Warmup Iteration   2: 10.454 ops/ms
# Warmup Iteration   3: 11.028 ops/ms
Iteration   1: 11.217 ops/ms
Iteration   2: 11.122 ops/ms
Iteration   3: 11.100 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.146 ±(99.9%) 1.139 ops/ms [Average]
  (min, avg, max) = (11.100, 11.146, 11.217), stdev = 0.062
  CI (99.9%): [10.008, 12.285] (assumes normal distribution)


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
# Warmup Iteration   1: 6.964 ops/ms
# Warmup Iteration   2: 10.233 ops/ms
# Warmup Iteration   3: 10.468 ops/ms
Iteration   1: 10.545 ops/ms
Iteration   2: 10.484 ops/ms
Iteration   3: 10.585 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.538 ±(99.9%) 0.922 ops/ms [Average]
  (min, avg, max) = (10.484, 10.538, 10.585), stdev = 0.051
  CI (99.9%): [9.616, 11.460] (assumes normal distribution)


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
# Warmup Iteration   1: 5.178 ops/ms
# Warmup Iteration   2: 7.784 ops/ms
# Warmup Iteration   3: 7.913 ops/ms
Iteration   1: 8.073 ops/ms
Iteration   2: 8.087 ops/ms
Iteration   3: 8.076 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.079 ±(99.9%) 0.138 ops/ms [Average]
  (min, avg, max) = (8.073, 8.079, 8.087), stdev = 0.008
  CI (99.9%): [7.941, 8.217] (assumes normal distribution)


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
# Warmup Iteration   1: 4.335 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.233 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.069 ±(99.9%) 0.003 ms/op
Iteration   1: 3.087 ±(99.9%) 0.002 ms/op
Iteration   2: 3.010 ±(99.9%) 0.003 ms/op
Iteration   3: 3.051 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.050 ±(99.9%) 0.707 ms/op [Average]
  (min, avg, max) = (3.010, 3.050, 3.087), stdev = 0.039
  CI (99.9%): [2.342, 3.757] (assumes normal distribution)


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
# Warmup Iteration   1: 4.178 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.053 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 2.949 ±(99.9%) 0.002 ms/op
Iteration   1: 2.942 ±(99.9%) 0.003 ms/op
Iteration   2: 2.869 ±(99.9%) 0.003 ms/op
Iteration   3: 2.767 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.859 ±(99.9%) 1.602 ms/op [Average]
  (min, avg, max) = (2.767, 2.859, 2.942), stdev = 0.088
  CI (99.9%): [1.257, 4.462] (assumes normal distribution)


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
# Warmup Iteration   1: 4.097 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.123 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.004 ms/op
Iteration   1: 3.064 ±(99.9%) 0.003 ms/op
Iteration   2: 3.000 ±(99.9%) 0.003 ms/op
Iteration   3: 3.089 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.051 ±(99.9%) 0.841 ms/op [Average]
  (min, avg, max) = (3.000, 3.051, 3.089), stdev = 0.046
  CI (99.9%): [2.210, 3.892] (assumes normal distribution)


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
# Warmup Iteration   1: 6.067 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.151 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 3.996 ±(99.9%) 0.020 ms/op
Iteration   1: 4.001 ±(99.9%) 0.027 ms/op
Iteration   2: 3.966 ±(99.9%) 0.035 ms/op
Iteration   3: 3.977 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.981 ±(99.9%) 0.333 ms/op [Average]
  (min, avg, max) = (3.966, 3.981, 4.001), stdev = 0.018
  CI (99.9%): [3.648, 4.314] (assumes normal distribution)


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
# Warmup Iteration   1: 3.936 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.275 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.100 ±(99.9%) 0.008 ms/op
Iteration   1: 3.055 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.787 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   4.669 ms/op
                 createUser·p0.999:  9.454 ms/op
                 createUser·p0.9999: 16.847 ms/op
                 createUser·p1.00:   17.269 ms/op

Iteration   2: 3.047 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.877 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.412 ms/op
                 createUser·p0.95:   3.564 ms/op
                 createUser·p0.99:   4.108 ms/op
                 createUser·p0.999:  7.379 ms/op
                 createUser·p0.9999: 17.908 ms/op
                 createUser·p1.00:   18.186 ms/op

Iteration   3: 3.075 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.561 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.547 ms/op
                 createUser·p0.999:  8.567 ms/op
                 createUser·p0.9999: 19.595 ms/op
                 createUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313770
  mean =      3.059 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12720 
    [ 2.500,  5.000) = 299366 
    [ 5.000,  7.500) = 1315 
    [ 7.500, 10.000) = 100 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.561 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      9.142 ms/op
     p(99.9900) =     18.862 ms/op
     p(99.9990) =     20.008 ms/op
     p(99.9999) =     20.644 ms/op
    p(100.0000) =     20.644 ms/op


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
# Warmup Iteration   1: 4.124 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.044 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.921 ±(99.9%) 0.005 ms/op
Iteration   1: 2.922 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.771 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.453 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  7.167 ms/op
                 existUser·p0.9999: 16.583 ms/op
                 existUser·p1.00:   16.908 ms/op

Iteration   2: 2.929 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.719 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  9.169 ms/op
                 existUser·p0.9999: 13.386 ms/op
                 existUser·p1.00:   13.713 ms/op

Iteration   3: 2.960 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.811 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  6.808 ms/op
                 existUser·p0.9999: 14.976 ms/op
                 existUser·p1.00:   16.302 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326834
  mean =      2.937 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 594 
    [ 1.250,  2.500) = 29274 
    [ 2.500,  3.750) = 286968 
    [ 3.750,  5.000) = 8743 
    [ 5.000,  6.250) = 680 
    [ 6.250,  7.500) = 246 
    [ 7.500,  8.750) = 78 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 82 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.719 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.371 ms/op
     p(95.0000) =      3.580 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      7.522 ms/op
     p(99.9900) =     14.543 ms/op
     p(99.9990) =     16.834 ms/op
     p(99.9999) =     16.908 ms/op
    p(100.0000) =     16.908 ms/op


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
# Warmup Iteration   1: 4.095 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.216 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.006 ms/op
Iteration   1: 3.017 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.618 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.690 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  8.947 ms/op
                 getUser·p0.9999: 13.733 ms/op
                 getUser·p1.00:   13.976 ms/op

Iteration   2: 3.036 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.765 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.596 ms/op
                 getUser·p0.999:  6.673 ms/op
                 getUser·p0.9999: 13.279 ms/op
                 getUser·p1.00:   13.828 ms/op

Iteration   3: 3.099 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.757 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.763 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  8.323 ms/op
                 getUser·p0.9999: 16.744 ms/op
                 getUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314555
  mean =      3.050 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 641 
    [ 1.250,  2.500) = 19193 
    [ 2.500,  3.750) = 279025 
    [ 3.750,  5.000) = 14177 
    [ 5.000,  6.250) = 976 
    [ 6.250,  7.500) = 137 
    [ 7.500,  8.750) = 96 
    [ 8.750, 10.000) = 49 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 110 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.618 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      8.633 ms/op
     p(99.9900) =     14.968 ms/op
     p(99.9990) =     16.904 ms/op
     p(99.9999) =     17.007 ms/op
    p(100.0000) =     17.007 ms/op


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
# Warmup Iteration   1: 5.232 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.093 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.968 ±(99.9%) 0.011 ms/op
Iteration   1: 3.967 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.249 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  14.598 ms/op
                 listUser·p0.9999: 19.724 ms/op
                 listUser·p1.00:   22.741 ms/op

Iteration   2: 3.985 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.614 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   7.050 ms/op
                 listUser·p0.999:  15.053 ms/op
                 listUser·p0.9999: 23.985 ms/op
                 listUser·p1.00:   24.314 ms/op

Iteration   3: 3.974 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.667 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.906 ms/op
                 listUser·p0.99:   6.972 ms/op
                 listUser·p0.999:  15.729 ms/op
                 listUser·p0.9999: 18.541 ms/op
                 listUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241450
  mean =      3.976 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3309 
    [ 2.500,  5.000) = 214077 
    [ 5.000,  7.500) = 22592 
    [ 7.500, 10.000) = 931 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 190 
    [15.000, 17.500) = 128 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.667 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      4.997 ms/op
     p(95.0000) =      5.792 ms/op
     p(99.0000) =      7.004 ms/op
     p(99.9000) =     15.106 ms/op
     p(99.9900) =     23.003 ms/op
     p(99.9990) =     24.136 ms/op
     p(99.9999) =     24.314 ms/op
    p(100.0000) =     24.314 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.638 ± 5.548  ops/ms
ClientGrpc.existUser                       thrpt       3  11.146 ± 1.139  ops/ms
ClientGrpc.getUser                         thrpt       3  10.538 ± 0.922  ops/ms
ClientGrpc.listUser                        thrpt       3   8.079 ± 0.138  ops/ms
ClientGrpc.createUser                       avgt       3   3.050 ± 0.707   ms/op
ClientGrpc.existUser                        avgt       3   2.859 ± 1.602   ms/op
ClientGrpc.getUser                          avgt       3   3.051 ± 0.841   ms/op
ClientGrpc.listUser                         avgt       3   3.981 ± 0.333   ms/op
ClientGrpc.createUser                     sample  313770   3.059 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.561           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.031           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.486           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.670           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.142           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.862           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.644           ms/op
ClientGrpc.existUser                      sample  326834   2.937 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.719           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.904           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.371           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.580           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.334           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.522           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.543           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.908           ms/op
ClientGrpc.getUser                        sample  314555   3.050 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.618           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.023           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.584           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.748           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.506           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.633           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.968           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.007           ms/op
ClientGrpc.listUser                       sample  241450   3.976 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.667           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.801           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.997           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.792           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.004           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.106           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.003           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.314           ms/op
