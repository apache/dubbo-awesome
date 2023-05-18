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
# Warmup Iteration   1: 2.324 ops/ms
# Warmup Iteration   2: 5.940 ops/ms
# Warmup Iteration   3: 7.531 ops/ms
Iteration   1: 7.798 ops/ms
Iteration   2: 8.310 ops/ms
Iteration   3: 8.030 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.046 ±(99.9%) 4.677 ops/ms [Average]
  (min, avg, max) = (7.798, 8.046, 8.310), stdev = 0.256
  CI (99.9%): [3.369, 12.723] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.008 ops/ms
# Warmup Iteration   2: 8.228 ops/ms
# Warmup Iteration   3: 8.535 ops/ms
Iteration   1: 8.892 ops/ms
Iteration   2: 8.776 ops/ms
Iteration   3: 8.570 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.746 ±(99.9%) 2.981 ops/ms [Average]
  (min, avg, max) = (8.570, 8.746, 8.892), stdev = 0.163
  CI (99.9%): [5.765, 11.727] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.895 ops/ms
# Warmup Iteration   2: 7.369 ops/ms
# Warmup Iteration   3: 7.973 ops/ms
Iteration   1: 8.277 ops/ms
Iteration   2: 7.947 ops/ms
Iteration   3: 8.053 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.092 ±(99.9%) 3.068 ops/ms [Average]
  (min, avg, max) = (7.947, 8.092, 8.277), stdev = 0.168
  CI (99.9%): [5.024, 11.161] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.584 ops/ms
# Warmup Iteration   2: 5.867 ops/ms
# Warmup Iteration   3: 6.070 ops/ms
Iteration   1: 6.157 ops/ms
Iteration   2: 6.414 ops/ms
Iteration   3: 6.266 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.279 ±(99.9%) 2.356 ops/ms [Average]
  (min, avg, max) = (6.157, 6.279, 6.414), stdev = 0.129
  CI (99.9%): [3.923, 8.635] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.007 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.347 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.092 ±(99.9%) 0.006 ms/op
Iteration   1: 4.100 ±(99.9%) 0.003 ms/op
Iteration   2: 3.958 ±(99.9%) 0.004 ms/op
Iteration   3: 3.898 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.985 ±(99.9%) 1.891 ms/op [Average]
  (min, avg, max) = (3.898, 3.985, 4.100), stdev = 0.104
  CI (99.9%): [2.094, 5.877] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.591 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.013 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.862 ±(99.9%) 0.003 ms/op
Iteration   1: 3.767 ±(99.9%) 0.002 ms/op
Iteration   2: 3.592 ±(99.9%) 0.003 ms/op
Iteration   3: 3.707 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.689 ±(99.9%) 1.622 ms/op [Average]
  (min, avg, max) = (3.592, 3.689, 3.767), stdev = 0.089
  CI (99.9%): [2.066, 5.311] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.165 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.364 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.038 ±(99.9%) 0.004 ms/op
Iteration   1: 3.907 ±(99.9%) 0.003 ms/op
Iteration   2: 4.007 ±(99.9%) 0.008 ms/op
Iteration   3: 3.939 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.951 ±(99.9%) 0.938 ms/op [Average]
  (min, avg, max) = (3.907, 3.951, 4.007), stdev = 0.051
  CI (99.9%): [3.013, 4.889] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.759 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 5.583 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.172 ±(99.9%) 0.018 ms/op
Iteration   1: 4.986 ±(99.9%) 0.014 ms/op
Iteration   2: 5.117 ±(99.9%) 0.019 ms/op
Iteration   3: 5.096 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.066 ±(99.9%) 1.281 ms/op [Average]
  (min, avg, max) = (4.986, 5.066, 5.117), stdev = 0.070
  CI (99.9%): [3.785, 6.348] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.954 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.321 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.111 ±(99.9%) 0.013 ms/op
Iteration   1: 4.010 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.163 ms/op
                 createUser·p0.50:   3.875 ms/op
                 createUser·p0.90:   4.989 ms/op
                 createUser·p0.95:   5.407 ms/op
                 createUser·p0.99:   7.029 ms/op
                 createUser·p0.999:  12.263 ms/op
                 createUser·p0.9999: 19.629 ms/op
                 createUser·p1.00:   19.956 ms/op

Iteration   2: 4.076 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.022 ms/op
                 createUser·p0.50:   3.949 ms/op
                 createUser·p0.90:   5.120 ms/op
                 createUser·p0.95:   5.652 ms/op
                 createUser·p0.99:   8.036 ms/op
                 createUser·p0.999:  12.907 ms/op
                 createUser·p0.9999: 23.996 ms/op
                 createUser·p1.00:   24.576 ms/op

Iteration   3: 3.924 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.069 ms/op
                 createUser·p0.50:   3.850 ms/op
                 createUser·p0.90:   4.784 ms/op
                 createUser·p0.95:   5.153 ms/op
                 createUser·p0.99:   6.644 ms/op
                 createUser·p0.999:  13.820 ms/op
                 createUser·p0.9999: 27.750 ms/op
                 createUser·p1.00:   28.443 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 239697
  mean =      4.002 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6198 
    [ 2.500,  5.000) = 210922 
    [ 5.000,  7.500) = 20412 
    [ 7.500, 10.000) = 1622 
    [10.000, 12.500) = 281 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.022 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.964 ms/op
     p(95.0000) =      5.407 ms/op
     p(99.0000) =      7.315 ms/op
     p(99.9000) =     12.861 ms/op
     p(99.9900) =     26.542 ms/op
     p(99.9990) =     28.141 ms/op
     p(99.9999) =     28.443 ms/op
    p(100.0000) =     28.443 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.647 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 3.965 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.777 ±(99.9%) 0.010 ms/op
Iteration   1: 3.614 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.733 ms/op
                 existUser·p0.50:   3.564 ms/op
                 existUser·p0.90:   4.489 ms/op
                 existUser·p0.95:   4.940 ms/op
                 existUser·p0.99:   6.652 ms/op
                 existUser·p0.999:  10.043 ms/op
                 existUser·p0.9999: 14.147 ms/op
                 existUser·p1.00:   14.746 ms/op

Iteration   2: 3.669 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.850 ms/op
                 existUser·p0.50:   3.617 ms/op
                 existUser·p0.90:   4.497 ms/op
                 existUser·p0.95:   4.923 ms/op
                 existUser·p0.99:   6.799 ms/op
                 existUser·p0.999:  11.172 ms/op
                 existUser·p0.9999: 18.678 ms/op
                 existUser·p1.00:   19.235 ms/op

Iteration   3: 3.664 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.565 ms/op
                 existUser·p0.50:   3.617 ms/op
                 existUser·p0.90:   4.579 ms/op
                 existUser·p0.95:   5.132 ms/op
                 existUser·p0.99:   7.299 ms/op
                 existUser·p0.999:  17.518 ms/op
                 existUser·p0.9999: 24.396 ms/op
                 existUser·p1.00:   24.969 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 263014
  mean =      3.649 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19640 
    [ 2.500,  5.000) = 230205 
    [ 5.000,  7.500) = 11344 
    [ 7.500, 10.000) = 1306 
    [10.000, 12.500) = 254 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.565 ms/op
     p(50.0000) =      3.600 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      5.005 ms/op
     p(99.0000) =      6.889 ms/op
     p(99.9000) =     12.517 ms/op
     p(99.9900) =     22.983 ms/op
     p(99.9990) =     24.842 ms/op
     p(99.9999) =     24.969 ms/op
    p(100.0000) =     24.969 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.365 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.353 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.015 ±(99.9%) 0.014 ms/op
Iteration   1: 3.894 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.820 ms/op
                 getUser·p0.50:   3.830 ms/op
                 getUser·p0.90:   4.882 ms/op
                 getUser·p0.95:   5.366 ms/op
                 getUser·p0.99:   7.627 ms/op
                 getUser·p0.999:  12.091 ms/op
                 getUser·p0.9999: 25.428 ms/op
                 getUser·p1.00:   25.657 ms/op

Iteration   2: 3.951 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.069 ms/op
                 getUser·p0.50:   3.871 ms/op
                 getUser·p0.90:   4.923 ms/op
                 getUser·p0.95:   5.464 ms/op
                 getUser·p0.99:   7.700 ms/op
                 getUser·p0.999:  12.994 ms/op
                 getUser·p0.9999: 18.672 ms/op
                 getUser·p1.00:   19.137 ms/op

Iteration   3: 3.858 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.891 ms/op
                 getUser·p0.50:   3.789 ms/op
                 getUser·p0.90:   4.727 ms/op
                 getUser·p0.95:   5.333 ms/op
                 getUser·p0.99:   7.217 ms/op
                 getUser·p0.999:  11.800 ms/op
                 getUser·p0.9999: 23.672 ms/op
                 getUser·p1.00:   24.347 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 245961
  mean =      3.901 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14809 
    [ 2.500,  5.000) = 211030 
    [ 5.000,  7.500) = 17662 
    [ 7.500, 10.000) = 1791 
    [10.000, 12.500) = 429 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.820 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      4.858 ms/op
     p(95.0000) =      5.390 ms/op
     p(99.0000) =      7.504 ms/op
     p(99.9000) =     12.420 ms/op
     p(99.9900) =     24.505 ms/op
     p(99.9990) =     25.592 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


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
# Warmup Iteration   1: 7.770 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 5.737 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.511 ±(99.9%) 0.026 ms/op
Iteration   1: 5.320 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.335 ms/op
                 listUser·p0.50:   4.940 ms/op
                 listUser·p0.90:   7.504 ms/op
                 listUser·p0.95:   8.315 ms/op
                 listUser·p0.99:   10.600 ms/op
                 listUser·p0.999:  16.208 ms/op
                 listUser·p0.9999: 19.922 ms/op
                 listUser·p1.00:   22.512 ms/op

Iteration   2: 5.336 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.313 ms/op
                 listUser·p0.50:   4.940 ms/op
                 listUser·p0.90:   7.561 ms/op
                 listUser·p0.95:   8.389 ms/op
                 listUser·p0.99:   11.108 ms/op
                 listUser·p0.999:  20.842 ms/op
                 listUser·p0.9999: 28.181 ms/op
                 listUser·p1.00:   32.801 ms/op

Iteration   3: 5.315 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.397 ms/op
                 listUser·p0.50:   4.940 ms/op
                 listUser·p0.90:   7.381 ms/op
                 listUser·p0.95:   8.225 ms/op
                 listUser·p0.99:   10.650 ms/op
                 listUser·p0.999:  23.131 ms/op
                 listUser·p0.9999: 37.879 ms/op
                 listUser·p1.00:   38.339 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 180201
  mean =      5.324 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 959 
    [ 2.500,  5.000) = 93497 
    [ 5.000,  7.500) = 67908 
    [ 7.500, 10.000) = 15147 
    [10.000, 12.500) = 1724 
    [12.500, 15.000) = 541 
    [15.000, 17.500) = 167 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.313 ms/op
     p(50.0000) =      4.940 ms/op
     p(90.0000) =      7.487 ms/op
     p(95.0000) =      8.307 ms/op
     p(99.0000) =     10.781 ms/op
     p(99.9000) =     19.589 ms/op
     p(99.9900) =     37.289 ms/op
     p(99.9990) =     38.233 ms/op
     p(99.9999) =     38.339 ms/op
    p(100.0000) =     38.339 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.046 ± 4.677  ops/ms
ClientGrpc.existUser                       thrpt       3   8.746 ± 2.981  ops/ms
ClientGrpc.getUser                         thrpt       3   8.092 ± 3.068  ops/ms
ClientGrpc.listUser                        thrpt       3   6.279 ± 2.356  ops/ms
ClientGrpc.createUser                       avgt       3   3.985 ± 1.891   ms/op
ClientGrpc.existUser                        avgt       3   3.689 ± 1.622   ms/op
ClientGrpc.getUser                          avgt       3   3.951 ± 0.938   ms/op
ClientGrpc.listUser                         avgt       3   5.066 ± 1.281   ms/op
ClientGrpc.createUser                     sample  239697   4.002 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.022           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.887           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.964           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.407           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.315           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.861           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.542           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.443           ms/op
ClientGrpc.existUser                      sample  263014   3.649 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.565           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.600           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.522           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.005           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.889           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.517           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.983           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.969           ms/op
ClientGrpc.getUser                        sample  245961   3.901 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.820           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.826           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.858           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.390           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.504           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.420           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.505           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.657           ms/op
ClientGrpc.listUser                       sample  180201   5.324 ± 0.014   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.313           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.940           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.487           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.307           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.781           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.589           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          37.289           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          38.339           ms/op
