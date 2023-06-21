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
# Warmup Iteration   1: 4.682 ops/ms
# Warmup Iteration   2: 9.176 ops/ms
# Warmup Iteration   3: 10.546 ops/ms
Iteration   1: 10.698 ops/ms
Iteration   2: 10.670 ops/ms
Iteration   3: 10.331 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.567 ±(99.9%) 3.725 ops/ms [Average]
  (min, avg, max) = (10.331, 10.567, 10.698), stdev = 0.204
  CI (99.9%): [6.841, 14.292] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.852 ops/ms
# Warmup Iteration   2: 10.289 ops/ms
# Warmup Iteration   3: 10.897 ops/ms
Iteration   1: 10.967 ops/ms
Iteration   2: 11.059 ops/ms
Iteration   3: 11.062 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.029 ±(99.9%) 0.986 ops/ms [Average]
  (min, avg, max) = (10.967, 11.029, 11.062), stdev = 0.054
  CI (99.9%): [10.043, 12.015] (assumes normal distribution)


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
# Warmup Iteration   1: 7.163 ops/ms
# Warmup Iteration   2: 10.203 ops/ms
# Warmup Iteration   3: 10.480 ops/ms
Iteration   1: 10.542 ops/ms
Iteration   2: 10.544 ops/ms
Iteration   3: 10.518 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.535 ±(99.9%) 0.258 ops/ms [Average]
  (min, avg, max) = (10.518, 10.535, 10.544), stdev = 0.014
  CI (99.9%): [10.276, 10.793] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.896 ops/ms
# Warmup Iteration   2: 7.780 ops/ms
# Warmup Iteration   3: 8.285 ops/ms
Iteration   1: 8.203 ops/ms
Iteration   2: 8.443 ops/ms
Iteration   3: 8.349 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.331 ±(99.9%) 2.211 ops/ms [Average]
  (min, avg, max) = (8.203, 8.331, 8.443), stdev = 0.121
  CI (99.9%): [6.120, 10.543] (assumes normal distribution)


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
# Warmup Iteration   1: 4.180 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.163 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.003 ms/op
Iteration   1: 3.040 ±(99.9%) 0.003 ms/op
Iteration   2: 2.986 ±(99.9%) 0.002 ms/op
Iteration   3: 3.068 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.032 ±(99.9%) 0.763 ms/op [Average]
  (min, avg, max) = (2.986, 3.032, 3.068), stdev = 0.042
  CI (99.9%): [2.269, 3.795] (assumes normal distribution)


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
# Warmup Iteration   1: 3.618 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.938 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.882 ±(99.9%) 0.003 ms/op
Iteration   1: 2.856 ±(99.9%) 0.004 ms/op
Iteration   2: 2.843 ±(99.9%) 0.003 ms/op
Iteration   3: 2.899 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.866 ±(99.9%) 0.535 ms/op [Average]
  (min, avg, max) = (2.843, 2.866, 2.899), stdev = 0.029
  CI (99.9%): [2.331, 3.401] (assumes normal distribution)


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
# Warmup Iteration   1: 3.976 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.079 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.003 ms/op
Iteration   1: 3.007 ±(99.9%) 0.003 ms/op
Iteration   2: 3.025 ±(99.9%) 0.003 ms/op
Iteration   3: 3.050 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.027 ±(99.9%) 0.401 ms/op [Average]
  (min, avg, max) = (3.007, 3.027, 3.050), stdev = 0.022
  CI (99.9%): [2.627, 3.428] (assumes normal distribution)


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
# Warmup Iteration   1: 4.708 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.893 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.853 ±(99.9%) 0.013 ms/op
Iteration   1: 3.870 ±(99.9%) 0.017 ms/op
Iteration   2: 3.832 ±(99.9%) 0.020 ms/op
Iteration   3: 3.826 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.842 ±(99.9%) 0.431 ms/op [Average]
  (min, avg, max) = (3.826, 3.842, 3.870), stdev = 0.024
  CI (99.9%): [3.411, 4.274] (assumes normal distribution)


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
# Warmup Iteration   1: 4.152 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.238 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.111 ±(99.9%) 0.006 ms/op
Iteration   1: 3.170 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.951 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   3.940 ms/op
                 createUser·p0.99:   4.547 ms/op
                 createUser·p0.999:  8.753 ms/op
                 createUser·p0.9999: 19.589 ms/op
                 createUser·p1.00:   20.054 ms/op

Iteration   2: 3.105 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.680 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  7.766 ms/op
                 createUser·p0.9999: 14.255 ms/op
                 createUser·p1.00:   14.746 ms/op

Iteration   3: 3.090 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.897 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  6.982 ms/op
                 createUser·p0.9999: 15.054 ms/op
                 createUser·p1.00:   15.925 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307606
  mean =      3.121 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14551 
    [ 2.500,  5.000) = 291619 
    [ 5.000,  7.500) = 1062 
    [ 7.500, 10.000) = 164 
    [10.000, 12.500) = 17 
    [12.500, 15.000) = 137 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.680 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      7.948 ms/op
     p(99.9900) =     18.193 ms/op
     p(99.9990) =     19.923 ms/op
     p(99.9999) =     20.054 ms/op
    p(100.0000) =     20.054 ms/op


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
# Warmup Iteration   1: 4.212 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.097 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.006 ms/op
Iteration   1: 2.910 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.593 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.444 ms/op
                 existUser·p0.999:  6.013 ms/op
                 existUser·p0.9999: 11.878 ms/op
                 existUser·p1.00:   12.255 ms/op

Iteration   2: 2.964 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.766 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.547 ms/op
                 existUser·p0.999:  6.849 ms/op
                 existUser·p0.9999: 14.690 ms/op
                 existUser·p1.00:   15.204 ms/op

Iteration   3: 3.004 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.549 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   3.850 ms/op
                 existUser·p0.99:   4.465 ms/op
                 existUser·p0.999:  7.422 ms/op
                 existUser·p0.9999: 17.334 ms/op
                 existUser·p1.00:   17.367 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324240
  mean =      2.959 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2171 
    [ 1.250,  2.500) = 33503 
    [ 2.500,  3.750) = 272967 
    [ 3.750,  5.000) = 14315 
    [ 5.000,  6.250) = 806 
    [ 6.250,  7.500) = 246 
    [ 7.500,  8.750) = 72 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.549 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      6.920 ms/op
     p(99.9900) =     15.822 ms/op
     p(99.9990) =     17.367 ms/op
     p(99.9999) =     17.367 ms/op
    p(100.0000) =     17.367 ms/op


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
# Warmup Iteration   1: 4.415 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.145 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.070 ±(99.9%) 0.005 ms/op
Iteration   1: 3.085 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.785 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   4.653 ms/op
                 getUser·p0.999:  7.507 ms/op
                 getUser·p0.9999: 12.190 ms/op
                 getUser·p1.00:   12.517 ms/op

Iteration   2: 3.020 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.248 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.383 ms/op
                 getUser·p0.95:   3.572 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  6.766 ms/op
                 getUser·p0.9999: 14.457 ms/op
                 getUser·p1.00:   14.680 ms/op

Iteration   3: 3.075 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.523 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  7.332 ms/op
                 getUser·p0.9999: 27.008 ms/op
                 getUser·p1.00:   27.263 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313607
  mean =      3.060 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15648 
    [ 2.500,  5.000) = 296580 
    [ 5.000,  7.500) = 1106 
    [ 7.500, 10.000) = 80 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.248 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      7.286 ms/op
     p(99.9900) =     25.056 ms/op
     p(99.9990) =     27.189 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


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
# Warmup Iteration   1: 5.035 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.049 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.921 ±(99.9%) 0.011 ms/op
Iteration   1: 3.965 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.364 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  12.833 ms/op
                 listUser·p0.9999: 18.806 ms/op
                 listUser·p1.00:   19.169 ms/op

Iteration   2: 3.888 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.964 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  13.812 ms/op
                 listUser·p0.9999: 16.054 ms/op
                 listUser·p1.00:   18.579 ms/op

Iteration   3: 3.885 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.029 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  16.139 ms/op
                 listUser·p0.9999: 23.790 ms/op
                 listUser·p1.00:   24.445 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245436
  mean =      3.912 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3566 
    [ 2.500,  5.000) = 221357 
    [ 5.000,  7.500) = 19235 
    [ 7.500, 10.000) = 796 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 185 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.964 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.809 ms/op
     p(95.0000) =      5.628 ms/op
     p(99.0000) =      6.873 ms/op
     p(99.9000) =     13.821 ms/op
     p(99.9900) =     23.066 ms/op
     p(99.9990) =     24.269 ms/op
     p(99.9999) =     24.445 ms/op
    p(100.0000) =     24.445 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.567 ± 3.725  ops/ms
ClientGrpc.existUser                       thrpt       3  11.029 ± 0.986  ops/ms
ClientGrpc.getUser                         thrpt       3  10.535 ± 0.258  ops/ms
ClientGrpc.listUser                        thrpt       3   8.331 ± 2.211  ops/ms
ClientGrpc.createUser                       avgt       3   3.032 ± 0.763   ms/op
ClientGrpc.existUser                        avgt       3   2.866 ± 0.535   ms/op
ClientGrpc.getUser                          avgt       3   3.027 ± 0.401   ms/op
ClientGrpc.listUser                         avgt       3   3.842 ± 0.431   ms/op
ClientGrpc.createUser                     sample  307606   3.121 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.680           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.088           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.674           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.903           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.497           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.948           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.193           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.054           ms/op
ClientGrpc.existUser                      sample  324240   2.959 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.549           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.949           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.494           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.736           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.481           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.920           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.822           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.367           ms/op
ClientGrpc.getUser                        sample  313607   3.060 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.248           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.039           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.514           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.752           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.415           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.286           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.056           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.263           ms/op
ClientGrpc.listUser                       sample  245436   3.912 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.964           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.764           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.809           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.628           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.873           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.821           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.066           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.445           ms/op
