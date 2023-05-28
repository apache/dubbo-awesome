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
# Warmup Iteration   1: 4.423 ops/ms
# Warmup Iteration   2: 9.196 ops/ms
# Warmup Iteration   3: 10.045 ops/ms
Iteration   1: 10.937 ops/ms
Iteration   2: 10.603 ops/ms
Iteration   3: 10.713 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.751 ±(99.9%) 3.102 ops/ms [Average]
  (min, avg, max) = (10.603, 10.751, 10.937), stdev = 0.170
  CI (99.9%): [7.648, 13.853] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.561 ops/ms
# Warmup Iteration   2: 10.869 ops/ms
# Warmup Iteration   3: 11.126 ops/ms
Iteration   1: 11.289 ops/ms
Iteration   2: 11.535 ops/ms
Iteration   3: 11.347 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.390 ±(99.9%) 2.342 ops/ms [Average]
  (min, avg, max) = (11.289, 11.390, 11.535), stdev = 0.128
  CI (99.9%): [9.049, 13.732] (assumes normal distribution)


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
# Warmup Iteration   1: 7.789 ops/ms
# Warmup Iteration   2: 10.495 ops/ms
# Warmup Iteration   3: 10.750 ops/ms
Iteration   1: 10.644 ops/ms
Iteration   2: 10.797 ops/ms
Iteration   3: 10.549 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.663 ±(99.9%) 2.288 ops/ms [Average]
  (min, avg, max) = (10.549, 10.663, 10.797), stdev = 0.125
  CI (99.9%): [8.376, 12.951] (assumes normal distribution)


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
# Warmup Iteration   1: 5.572 ops/ms
# Warmup Iteration   2: 7.904 ops/ms
# Warmup Iteration   3: 8.039 ops/ms
Iteration   1: 8.191 ops/ms
Iteration   2: 8.319 ops/ms
Iteration   3: 8.263 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.258 ±(99.9%) 1.167 ops/ms [Average]
  (min, avg, max) = (8.191, 8.258, 8.319), stdev = 0.064
  CI (99.9%): [7.091, 9.424] (assumes normal distribution)


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
# Warmup Iteration   1: 4.083 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.128 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 3.022 ±(99.9%) 0.005 ms/op
Iteration   1: 2.972 ±(99.9%) 0.003 ms/op
Iteration   2: 2.951 ±(99.9%) 0.003 ms/op
Iteration   3: 2.972 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.965 ±(99.9%) 0.226 ms/op [Average]
  (min, avg, max) = (2.951, 2.965, 2.972), stdev = 0.012
  CI (99.9%): [2.739, 3.191] (assumes normal distribution)


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
# Warmup Iteration   1: 3.864 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 2.974 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.913 ±(99.9%) 0.004 ms/op
Iteration   1: 2.911 ±(99.9%) 0.002 ms/op
Iteration   2: 2.913 ±(99.9%) 0.003 ms/op
Iteration   3: 2.895 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.906 ±(99.9%) 0.174 ms/op [Average]
  (min, avg, max) = (2.895, 2.906, 2.913), stdev = 0.010
  CI (99.9%): [2.733, 3.080] (assumes normal distribution)


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
# Warmup Iteration   1: 3.975 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.038 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.962 ±(99.9%) 0.003 ms/op
Iteration   1: 2.952 ±(99.9%) 0.003 ms/op
Iteration   2: 3.005 ±(99.9%) 0.005 ms/op
Iteration   3: 2.960 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.972 ±(99.9%) 0.520 ms/op [Average]
  (min, avg, max) = (2.952, 2.972, 3.005), stdev = 0.028
  CI (99.9%): [2.452, 3.492] (assumes normal distribution)


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
# Warmup Iteration   1: 3.825 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.101 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.859 ±(99.9%) 0.024 ms/op
Iteration   1: 3.910 ±(99.9%) 0.011 ms/op
Iteration   2: 3.810 ±(99.9%) 0.006 ms/op
Iteration   3: 3.842 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.854 ±(99.9%) 0.931 ms/op [Average]
  (min, avg, max) = (3.810, 3.854, 3.910), stdev = 0.051
  CI (99.9%): [2.923, 4.785] (assumes normal distribution)


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
# Warmup Iteration   1: 4.098 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.115 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.006 ms/op
Iteration   1: 3.031 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.871 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.441 ms/op
                 createUser·p0.95:   3.641 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  8.135 ms/op
                 createUser·p0.9999: 16.908 ms/op
                 createUser·p1.00:   17.203 ms/op

Iteration   2: 3.003 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.737 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   4.671 ms/op
                 createUser·p0.999:  7.963 ms/op
                 createUser·p0.9999: 12.943 ms/op
                 createUser·p1.00:   13.418 ms/op

Iteration   3: 2.993 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.768 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   4.604 ms/op
                 createUser·p0.999:  9.395 ms/op
                 createUser·p0.9999: 16.656 ms/op
                 createUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318839
  mean =      3.009 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1120 
    [ 1.250,  2.500) = 24525 
    [ 2.500,  3.750) = 278641 
    [ 3.750,  5.000) = 12885 
    [ 5.000,  6.250) = 985 
    [ 6.250,  7.500) = 243 
    [ 7.500,  8.750) = 140 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 47 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =      8.249 ms/op
     p(99.9900) =     16.648 ms/op
     p(99.9990) =     18.639 ms/op
     p(99.9999) =     18.645 ms/op
    p(100.0000) =     18.645 ms/op


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
# Warmup Iteration   1: 3.862 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.983 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.909 ±(99.9%) 0.006 ms/op
Iteration   1: 2.889 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.816 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  9.365 ms/op
                 existUser·p0.9999: 12.156 ms/op
                 existUser·p1.00:   12.763 ms/op

Iteration   2: 2.978 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.649 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  6.832 ms/op
                 existUser·p0.9999: 13.132 ms/op
                 existUser·p1.00:   13.550 ms/op

Iteration   3: 2.964 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.511 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   4.506 ms/op
                 existUser·p0.999:  8.324 ms/op
                 existUser·p0.9999: 17.898 ms/op
                 existUser·p1.00:   18.121 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325921
  mean =      2.943 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2187 
    [ 1.250,  2.500) = 36033 
    [ 2.500,  3.750) = 277269 
    [ 3.750,  5.000) = 9346 
    [ 5.000,  6.250) = 549 
    [ 6.250,  7.500) = 216 
    [ 7.500,  8.750) = 79 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.511 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.645 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      7.423 ms/op
     p(99.9900) =     15.258 ms/op
     p(99.9990) =     18.079 ms/op
     p(99.9999) =     18.121 ms/op
    p(100.0000) =     18.121 ms/op


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
# Warmup Iteration   1: 3.977 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.141 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.007 ms/op
Iteration   1: 3.074 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.790 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   4.686 ms/op
                 getUser·p0.999:  7.069 ms/op
                 getUser·p0.9999: 13.844 ms/op
                 getUser·p1.00:   14.189 ms/op

Iteration   2: 3.000 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.792 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.480 ms/op
                 getUser·p0.999:  6.647 ms/op
                 getUser·p0.9999: 23.833 ms/op
                 getUser·p1.00:   24.052 ms/op

Iteration   3: 3.003 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.734 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  7.185 ms/op
                 getUser·p0.9999: 15.734 ms/op
                 getUser·p1.00:   17.793 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317139
  mean =      3.025 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26080 
    [ 2.500,  5.000) = 289673 
    [ 5.000,  7.500) = 1127 
    [ 7.500, 10.000) = 24 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.734 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =      7.029 ms/op
     p(99.9900) =     21.295 ms/op
     p(99.9990) =     23.915 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


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
# Warmup Iteration   1: 4.327 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.188 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.974 ±(99.9%) 0.010 ms/op
Iteration   1: 3.903 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.305 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   5.267 ms/op
                 listUser·p0.99:   6.636 ms/op
                 listUser·p0.999:  12.387 ms/op
                 listUser·p0.9999: 21.135 ms/op
                 listUser·p1.00:   21.660 ms/op

Iteration   2: 3.845 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.559 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   5.374 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  14.920 ms/op
                 listUser·p0.9999: 19.466 ms/op
                 listUser·p1.00:   20.021 ms/op

Iteration   3: 3.883 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.961 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  13.630 ms/op
                 listUser·p0.9999: 24.379 ms/op
                 listUser·p1.00:   25.985 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247475
  mean =      3.877 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3067 
    [ 2.500,  5.000) = 226550 
    [ 5.000,  7.500) = 16858 
    [ 7.500, 10.000) = 509 
    [10.000, 12.500) = 171 
    [12.500, 15.000) = 146 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.961 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      5.390 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =     13.247 ms/op
     p(99.9900) =     24.183 ms/op
     p(99.9990) =     25.790 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.751 ± 3.102  ops/ms
ClientGrpc.existUser                       thrpt       3  11.390 ± 2.342  ops/ms
ClientGrpc.getUser                         thrpt       3  10.663 ± 2.288  ops/ms
ClientGrpc.listUser                        thrpt       3   8.258 ± 1.167  ops/ms
ClientGrpc.createUser                       avgt       3   2.965 ± 0.226   ms/op
ClientGrpc.existUser                        avgt       3   2.906 ± 0.174   ms/op
ClientGrpc.getUser                          avgt       3   2.972 ± 0.520   ms/op
ClientGrpc.listUser                         avgt       3   3.854 ± 0.931   ms/op
ClientGrpc.createUser                     sample  318839   3.009 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.737           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.990           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.486           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.715           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.547           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.249           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.648           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.645           ms/op
ClientGrpc.existUser                      sample  325921   2.943 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.511           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.916           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.490           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.645           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.391           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.423           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.258           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.121           ms/op
ClientGrpc.getUser                        sample  317139   3.025 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.734           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.006           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.555           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.813           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.547           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.029           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.295           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.052           ms/op
ClientGrpc.listUser                       sample  247475   3.877 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.961           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.744           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.620           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.390           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.701           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.247           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.183           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.985           ms/op
