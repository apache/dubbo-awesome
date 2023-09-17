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
# Warmup Iteration   1: 4.077 ops/ms
# Warmup Iteration   2: 8.357 ops/ms
# Warmup Iteration   3: 9.634 ops/ms
Iteration   1: 9.907 ops/ms
Iteration   2: 10.223 ops/ms
Iteration   3: 9.710 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.946 ±(99.9%) 4.720 ops/ms [Average]
  (min, avg, max) = (9.710, 9.946, 10.223), stdev = 0.259
  CI (99.9%): [5.227, 14.666] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 8.275 ops/ms
# Warmup Iteration   2: 10.432 ops/ms
# Warmup Iteration   3: 10.830 ops/ms
Iteration   1: 10.897 ops/ms
Iteration   2: 10.615 ops/ms
Iteration   3: 10.950 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.820 ±(99.9%) 3.286 ops/ms [Average]
  (min, avg, max) = (10.615, 10.820, 10.950), stdev = 0.180
  CI (99.9%): [7.535, 14.106] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 7.347 ops/ms
# Warmup Iteration   2: 9.682 ops/ms
# Warmup Iteration   3: 10.277 ops/ms
Iteration   1: 9.885 ops/ms
Iteration   2: 9.974 ops/ms
Iteration   3: 10.007 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.955 ±(99.9%) 1.149 ops/ms [Average]
  (min, avg, max) = (9.885, 9.955, 10.007), stdev = 0.063
  CI (99.9%): [8.806, 11.104] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.077 ops/ms
# Warmup Iteration   2: 7.714 ops/ms
# Warmup Iteration   3: 8.076 ops/ms
Iteration   1: 8.073 ops/ms
Iteration   2: 8.045 ops/ms
Iteration   3: 8.118 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.079 ±(99.9%) 0.666 ops/ms [Average]
  (min, avg, max) = (8.045, 8.079, 8.118), stdev = 0.036
  CI (99.9%): [7.413, 8.744] (assumes normal distribution)


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
# Warmup Iteration   1: 4.297 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.184 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.219 ±(99.9%) 0.003 ms/op
Iteration   1: 3.085 ±(99.9%) 0.002 ms/op
Iteration   2: 3.069 ±(99.9%) 0.002 ms/op
Iteration   3: 3.088 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.081 ±(99.9%) 0.191 ms/op [Average]
  (min, avg, max) = (3.069, 3.081, 3.088), stdev = 0.010
  CI (99.9%): [2.890, 3.271] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.013 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.142 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.004 ms/op
Iteration   1: 2.921 ±(99.9%) 0.003 ms/op
Iteration   2: 2.941 ±(99.9%) 0.005 ms/op
Iteration   3: 3.053 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.972 ±(99.9%) 1.301 ms/op [Average]
  (min, avg, max) = (2.921, 2.972, 3.053), stdev = 0.071
  CI (99.9%): [1.671, 4.272] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.035 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.201 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.122 ±(99.9%) 0.002 ms/op
Iteration   1: 3.099 ±(99.9%) 0.002 ms/op
Iteration   2: 3.087 ±(99.9%) 0.003 ms/op
Iteration   3: 3.220 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.135 ±(99.9%) 1.335 ms/op [Average]
  (min, avg, max) = (3.087, 3.135, 3.220), stdev = 0.073
  CI (99.9%): [1.800, 4.470] (assumes normal distribution)


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
# Warmup Iteration   1: 5.391 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.108 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.013 ±(99.9%) 0.036 ms/op
Iteration   1: 3.953 ±(99.9%) 0.024 ms/op
Iteration   2: 3.976 ±(99.9%) 0.012 ms/op
Iteration   3: 3.949 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.960 ±(99.9%) 0.267 ms/op [Average]
  (min, avg, max) = (3.949, 3.960, 3.976), stdev = 0.015
  CI (99.9%): [3.693, 4.226] (assumes normal distribution)


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
# Warmup Iteration   1: 4.023 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.220 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.140 ±(99.9%) 0.007 ms/op
Iteration   1: 3.070 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.664 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.694 ms/op
                 createUser·p0.999:  9.738 ms/op
                 createUser·p0.9999: 17.877 ms/op
                 createUser·p1.00:   18.973 ms/op

Iteration   2: 3.113 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.652 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.735 ms/op
                 createUser·p0.999:  8.071 ms/op
                 createUser·p0.9999: 19.946 ms/op
                 createUser·p1.00:   20.185 ms/op

Iteration   3: 3.080 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.681 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  9.191 ms/op
                 createUser·p0.9999: 20.251 ms/op
                 createUser·p1.00:   20.677 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310935
  mean =      3.088 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14960 
    [ 2.500,  5.000) = 293794 
    [ 5.000,  7.500) = 1662 
    [ 7.500, 10.000) = 257 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 116 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.652 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.678 ms/op
     p(99.9000) =      8.800 ms/op
     p(99.9900) =     19.988 ms/op
     p(99.9990) =     20.378 ms/op
     p(99.9999) =     20.677 ms/op
    p(100.0000) =     20.677 ms/op


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
# Warmup Iteration   1: 3.921 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.123 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.007 ms/op
Iteration   1: 2.957 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.808 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   4.694 ms/op
                 existUser·p0.999:  6.421 ms/op
                 existUser·p0.9999: 17.537 ms/op
                 existUser·p1.00:   18.055 ms/op

Iteration   2: 3.008 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.621 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.801 ms/op
                 existUser·p0.999:  10.000 ms/op
                 existUser·p0.9999: 20.775 ms/op
                 existUser·p1.00:   21.594 ms/op

Iteration   3: 3.042 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.658 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   4.620 ms/op
                 existUser·p0.999:  7.979 ms/op
                 existUser·p0.9999: 20.872 ms/op
                 existUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 319759
  mean =      3.002 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24061 
    [ 2.500,  5.000) = 293604 
    [ 5.000,  7.500) = 1738 
    [ 7.500, 10.000) = 154 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.621 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.694 ms/op
     p(99.9000) =      7.727 ms/op
     p(99.9900) =     20.709 ms/op
     p(99.9990) =     21.325 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


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
# Warmup Iteration   1: 4.051 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.242 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.206 ±(99.9%) 0.006 ms/op
Iteration   1: 3.090 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.835 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   4.678 ms/op
                 getUser·p0.999:  7.553 ms/op
                 getUser·p0.9999: 11.824 ms/op
                 getUser·p1.00:   12.157 ms/op

Iteration   2: 3.100 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.923 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.735 ms/op
                 getUser·p0.999:  7.889 ms/op
                 getUser·p0.9999: 13.272 ms/op
                 getUser·p1.00:   13.681 ms/op

Iteration   3: 3.105 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.765 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  6.840 ms/op
                 getUser·p0.9999: 16.030 ms/op
                 getUser·p1.00:   16.515 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309721
  mean =      3.098 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 759 
    [ 1.250,  2.500) = 8901 
    [ 2.500,  3.750) = 280494 
    [ 3.750,  5.000) = 17565 
    [ 5.000,  6.250) = 1195 
    [ 6.250,  7.500) = 479 
    [ 7.500,  8.750) = 167 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 48 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.765 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      7.553 ms/op
     p(99.9900) =     15.451 ms/op
     p(99.9990) =     16.363 ms/op
     p(99.9999) =     16.515 ms/op
    p(100.0000) =     16.515 ms/op


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
# Warmup Iteration   1: 4.847 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.171 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.979 ±(99.9%) 0.009 ms/op
Iteration   1: 3.948 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.844 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   5.251 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  11.878 ms/op
                 listUser·p0.9999: 15.924 ms/op
                 listUser·p1.00:   17.859 ms/op

Iteration   2: 4.030 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.925 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   5.374 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  13.086 ms/op
                 listUser·p0.9999: 14.387 ms/op
                 listUser·p1.00:   15.385 ms/op

Iteration   3: 3.974 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.079 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  15.492 ms/op
                 listUser·p0.9999: 20.806 ms/op
                 listUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240822
  mean =      3.984 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1704 
    [ 2.500,  5.000) = 225651 
    [ 5.000,  7.500) = 12368 
    [ 7.500, 10.000) = 638 
    [10.000, 12.500) = 155 
    [12.500, 15.000) = 196 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.844 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      5.136 ms/op
     p(99.0000) =      6.767 ms/op
     p(99.9000) =     13.058 ms/op
     p(99.9900) =     19.235 ms/op
     p(99.9990) =     21.450 ms/op
     p(99.9999) =     21.463 ms/op
    p(100.0000) =     21.463 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.946 ± 4.720  ops/ms
ClientGrpc.existUser                       thrpt       3  10.820 ± 3.286  ops/ms
ClientGrpc.getUser                         thrpt       3   9.955 ± 1.149  ops/ms
ClientGrpc.listUser                        thrpt       3   8.079 ± 0.666  ops/ms
ClientGrpc.createUser                       avgt       3   3.081 ± 0.191   ms/op
ClientGrpc.existUser                        avgt       3   2.972 ± 1.301   ms/op
ClientGrpc.getUser                          avgt       3   3.135 ± 1.335   ms/op
ClientGrpc.listUser                         avgt       3   3.960 ± 0.267   ms/op
ClientGrpc.createUser                     sample  310935   3.088 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.652           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.056           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.572           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.801           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.678           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.800           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.988           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.677           ms/op
ClientGrpc.existUser                      sample  319759   3.002 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.621           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.966           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.494           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.727           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.694           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.727           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.709           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.594           ms/op
ClientGrpc.getUser                        sample  309721   3.098 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.765           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.060           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.600           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.822           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.514           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.553           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.451           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.515           ms/op
ClientGrpc.listUser                       sample  240822   3.984 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.844           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.908           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.440           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.136           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.767           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.058           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.235           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.463           ms/op
