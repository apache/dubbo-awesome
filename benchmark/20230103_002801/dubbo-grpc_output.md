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
# Warmup Iteration   1: 4.756 ops/ms
# Warmup Iteration   2: 9.628 ops/ms
# Warmup Iteration   3: 10.336 ops/ms
Iteration   1: 10.296 ops/ms
Iteration   2: 10.679 ops/ms
Iteration   3: 10.409 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.461 ±(99.9%) 3.587 ops/ms [Average]
  (min, avg, max) = (10.296, 10.461, 10.679), stdev = 0.197
  CI (99.9%): [6.874, 14.049] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.802 ops/ms
# Warmup Iteration   2: 10.865 ops/ms
# Warmup Iteration   3: 10.855 ops/ms
Iteration   1: 10.976 ops/ms
Iteration   2: 10.990 ops/ms
Iteration   3: 11.033 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.999 ±(99.9%) 0.539 ops/ms [Average]
  (min, avg, max) = (10.976, 10.999, 11.033), stdev = 0.030
  CI (99.9%): [10.461, 11.538] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.395 ops/ms
# Warmup Iteration   2: 10.311 ops/ms
# Warmup Iteration   3: 10.647 ops/ms
Iteration   1: 10.568 ops/ms
Iteration   2: 10.775 ops/ms
Iteration   3: 10.252 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.532 ±(99.9%) 4.809 ops/ms [Average]
  (min, avg, max) = (10.252, 10.532, 10.775), stdev = 0.264
  CI (99.9%): [5.723, 15.340] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.139 ops/ms
# Warmup Iteration   2: 7.689 ops/ms
# Warmup Iteration   3: 8.202 ops/ms
Iteration   1: 8.122 ops/ms
Iteration   2: 8.103 ops/ms
Iteration   3: 7.984 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.070 ±(99.9%) 1.361 ops/ms [Average]
  (min, avg, max) = (7.984, 8.070, 8.122), stdev = 0.075
  CI (99.9%): [6.709, 9.430] (assumes normal distribution)


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
# Warmup Iteration   1: 3.685 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.212 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.064 ±(99.9%) 0.002 ms/op
Iteration   1: 2.973 ±(99.9%) 0.003 ms/op
Iteration   2: 3.128 ±(99.9%) 0.002 ms/op
Iteration   3: 3.181 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.094 ±(99.9%) 1.974 ms/op [Average]
  (min, avg, max) = (2.973, 3.094, 3.181), stdev = 0.108
  CI (99.9%): [1.120, 5.068] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.662 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.968 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.923 ±(99.9%) 0.002 ms/op
Iteration   1: 3.018 ±(99.9%) 0.002 ms/op
Iteration   2: 2.846 ±(99.9%) 0.003 ms/op
Iteration   3: 2.871 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.911 ±(99.9%) 1.702 ms/op [Average]
  (min, avg, max) = (2.846, 2.911, 3.018), stdev = 0.093
  CI (99.9%): [1.209, 4.614] (assumes normal distribution)


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
# Warmup Iteration   1: 3.913 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.058 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.003 ms/op
Iteration   1: 3.146 ±(99.9%) 0.003 ms/op
Iteration   2: 3.052 ±(99.9%) 0.003 ms/op
Iteration   3: 3.046 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.081 ±(99.9%) 1.024 ms/op [Average]
  (min, avg, max) = (3.046, 3.081, 3.146), stdev = 0.056
  CI (99.9%): [2.057, 4.105] (assumes normal distribution)


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
# Warmup Iteration   1: 4.189 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.242 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 3.939 ±(99.9%) 0.044 ms/op
Iteration   1: 3.893 ±(99.9%) 0.008 ms/op
Iteration   2: 3.984 ±(99.9%) 0.025 ms/op
Iteration   3: 3.722 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.866 ±(99.9%) 2.428 ms/op [Average]
  (min, avg, max) = (3.722, 3.866, 3.984), stdev = 0.133
  CI (99.9%): [1.438, 6.295] (assumes normal distribution)


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
# Warmup Iteration   1: 4.055 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.213 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.007 ms/op
Iteration   1: 2.991 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.740 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  7.002 ms/op
                 createUser·p0.9999: 24.028 ms/op
                 createUser·p1.00:   24.281 ms/op

Iteration   2: 3.137 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.476 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  11.502 ms/op
                 createUser·p0.9999: 18.147 ms/op
                 createUser·p1.00:   18.514 ms/op

Iteration   3: 3.180 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.584 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.006 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  11.145 ms/op
                 createUser·p0.9999: 18.608 ms/op
                 createUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309643
  mean =      3.100 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29772 
    [ 2.500,  5.000) = 278696 
    [ 5.000,  7.500) = 701 
    [ 7.500, 10.000) = 161 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.476 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =     10.389 ms/op
     p(99.9900) =     23.563 ms/op
     p(99.9990) =     24.245 ms/op
     p(99.9999) =     24.281 ms/op
    p(100.0000) =     24.281 ms/op


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
# Warmup Iteration   1: 3.805 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.032 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.907 ±(99.9%) 0.006 ms/op
Iteration   1: 2.956 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.644 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  6.390 ms/op
                 existUser·p0.9999: 11.884 ms/op
                 existUser·p1.00:   12.255 ms/op

Iteration   2: 2.933 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.655 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.108 ms/op
                 existUser·p0.999:  5.889 ms/op
                 existUser·p0.9999: 11.832 ms/op
                 existUser·p1.00:   12.255 ms/op

Iteration   3: 2.965 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.722 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.580 ms/op
                 existUser·p0.95:   3.793 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  10.373 ms/op
                 existUser·p0.9999: 16.103 ms/op
                 existUser·p1.00:   16.581 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325212
  mean =      2.951 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2622 
    [ 1.250,  2.500) = 42011 
    [ 2.500,  3.750) = 265088 
    [ 3.750,  5.000) = 14483 
    [ 5.000,  6.250) = 603 
    [ 6.250,  7.500) = 111 
    [ 7.500,  8.750) = 69 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 53 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.644 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      7.076 ms/op
     p(99.9900) =     14.925 ms/op
     p(99.9990) =     16.470 ms/op
     p(99.9999) =     16.581 ms/op
    p(100.0000) =     16.581 ms/op


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
# Warmup Iteration   1: 3.928 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.121 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.007 ms/op
Iteration   1: 3.007 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.640 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  8.875 ms/op
                 getUser·p0.9999: 17.883 ms/op
                 getUser·p1.00:   18.088 ms/op

Iteration   2: 2.933 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.336 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.412 ms/op
                 getUser·p0.95:   3.682 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  7.307 ms/op
                 getUser·p0.9999: 19.759 ms/op
                 getUser·p1.00:   20.513 ms/op

Iteration   3: 3.046 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.298 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.153 ms/op
                 getUser·p0.999:  7.102 ms/op
                 getUser·p0.9999: 20.955 ms/op
                 getUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320270
  mean =      2.995 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31908 
    [ 2.500,  5.000) = 287108 
    [ 5.000,  7.500) = 920 
    [ 7.500, 10.000) = 124 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.298 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      7.584 ms/op
     p(99.9900) =     20.513 ms/op
     p(99.9990) =     21.594 ms/op
     p(99.9999) =     21.692 ms/op
    p(100.0000) =     21.692 ms/op


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
# Warmup Iteration   1: 5.313 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.987 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.973 ±(99.9%) 0.011 ms/op
Iteration   1: 4.028 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.309 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   5.292 ms/op
                 listUser·p0.95:   5.886 ms/op
                 listUser·p0.99:   7.094 ms/op
                 listUser·p0.999:  11.751 ms/op
                 listUser·p0.9999: 22.710 ms/op
                 listUser·p1.00:   22.905 ms/op

Iteration   2: 3.993 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.722 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  15.723 ms/op
                 listUser·p0.9999: 23.200 ms/op
                 listUser·p1.00:   26.542 ms/op

Iteration   3: 4.053 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.289 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  14.729 ms/op
                 listUser·p0.9999: 21.398 ms/op
                 listUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238465
  mean =      4.024 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3610 
    [ 2.500,  5.000) = 201454 
    [ 5.000,  7.500) = 32135 
    [ 7.500, 10.000) = 877 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.289 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      5.226 ms/op
     p(95.0000) =      5.693 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     14.565 ms/op
     p(99.9900) =     22.849 ms/op
     p(99.9990) =     24.473 ms/op
     p(99.9999) =     26.542 ms/op
    p(100.0000) =     26.542 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.461 ± 3.587  ops/ms
ClientGrpc.existUser                       thrpt       3  10.999 ± 0.539  ops/ms
ClientGrpc.getUser                         thrpt       3  10.532 ± 4.809  ops/ms
ClientGrpc.listUser                        thrpt       3   8.070 ± 1.361  ops/ms
ClientGrpc.createUser                       avgt       3   3.094 ± 1.974   ms/op
ClientGrpc.existUser                        avgt       3   2.911 ± 1.702   ms/op
ClientGrpc.getUser                          avgt       3   3.081 ± 1.024   ms/op
ClientGrpc.listUser                         avgt       3   3.866 ± 2.428   ms/op
ClientGrpc.createUser                     sample  309643   3.100 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.476           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.068           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.752           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.953           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.342           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.389           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.563           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.281           ms/op
ClientGrpc.existUser                      sample  325212   2.951 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.644           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.945           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.547           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.736           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.202           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.076           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.925           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.581           ms/op
ClientGrpc.getUser                        sample  320270   2.995 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.298           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.998           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.535           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.785           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.584           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.513           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.692           ms/op
ClientGrpc.listUser                       sample  238465   4.024 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.289           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.809           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.226           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.693           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.930           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.565           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.849           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.542           ms/op
