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
# Warmup Iteration   1: 4.972 ops/ms
# Warmup Iteration   2: 9.159 ops/ms
# Warmup Iteration   3: 10.379 ops/ms
Iteration   1: 10.673 ops/ms
Iteration   2: 10.599 ops/ms
Iteration   3: 10.670 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.648 ±(99.9%) 0.765 ops/ms [Average]
  (min, avg, max) = (10.599, 10.648, 10.673), stdev = 0.042
  CI (99.9%): [9.883, 11.412] (assumes normal distribution)


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
# Warmup Iteration   1: 7.887 ops/ms
# Warmup Iteration   2: 10.682 ops/ms
# Warmup Iteration   3: 11.421 ops/ms
Iteration   1: 11.407 ops/ms
Iteration   2: 11.461 ops/ms
Iteration   3: 11.217 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.362 ±(99.9%) 2.338 ops/ms [Average]
  (min, avg, max) = (11.217, 11.362, 11.461), stdev = 0.128
  CI (99.9%): [9.024, 13.699] (assumes normal distribution)


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
# Warmup Iteration   1: 7.985 ops/ms
# Warmup Iteration   2: 10.407 ops/ms
# Warmup Iteration   3: 10.750 ops/ms
Iteration   1: 10.742 ops/ms
Iteration   2: 10.681 ops/ms
Iteration   3: 10.780 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.734 ±(99.9%) 0.905 ops/ms [Average]
  (min, avg, max) = (10.681, 10.734, 10.780), stdev = 0.050
  CI (99.9%): [9.829, 11.639] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.945 ops/ms
# Warmup Iteration   2: 8.019 ops/ms
# Warmup Iteration   3: 8.197 ops/ms
Iteration   1: 8.201 ops/ms
Iteration   2: 8.134 ops/ms
Iteration   3: 8.385 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.240 ±(99.9%) 2.369 ops/ms [Average]
  (min, avg, max) = (8.134, 8.240, 8.385), stdev = 0.130
  CI (99.9%): [5.872, 10.609] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.190 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.003 ms/op
Iteration   1: 2.990 ±(99.9%) 0.003 ms/op
Iteration   2: 2.951 ±(99.9%) 0.001 ms/op
Iteration   3: 3.012 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.984 ±(99.9%) 0.564 ms/op [Average]
  (min, avg, max) = (2.951, 2.984, 3.012), stdev = 0.031
  CI (99.9%): [2.420, 3.549] (assumes normal distribution)


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
# Warmup Iteration   1: 3.865 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.883 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.838 ±(99.9%) 0.003 ms/op
Iteration   1: 2.836 ±(99.9%) 0.003 ms/op
Iteration   2: 2.829 ±(99.9%) 0.003 ms/op
Iteration   3: 2.842 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.836 ±(99.9%) 0.123 ms/op [Average]
  (min, avg, max) = (2.829, 2.836, 2.842), stdev = 0.007
  CI (99.9%): [2.713, 2.958] (assumes normal distribution)


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
# Warmup Iteration   1: 3.794 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.981 ±(99.9%) 0.002 ms/op
Iteration   1: 2.951 ±(99.9%) 0.002 ms/op
Iteration   2: 2.981 ±(99.9%) 0.003 ms/op
Iteration   3: 2.962 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.965 ±(99.9%) 0.276 ms/op [Average]
  (min, avg, max) = (2.951, 2.965, 2.981), stdev = 0.015
  CI (99.9%): [2.689, 3.240] (assumes normal distribution)


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
# Warmup Iteration   1: 5.142 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.000 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 3.794 ±(99.9%) 0.015 ms/op
Iteration   1: 3.759 ±(99.9%) 0.013 ms/op
Iteration   2: 3.852 ±(99.9%) 0.026 ms/op
Iteration   3: 3.900 ±(99.9%) 0.032 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.837 ±(99.9%) 1.306 ms/op [Average]
  (min, avg, max) = (3.759, 3.837, 3.900), stdev = 0.072
  CI (99.9%): [2.531, 5.143] (assumes normal distribution)


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
# Warmup Iteration   1: 4.014 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.113 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.006 ms/op
Iteration   1: 2.911 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.730 ms/op
                 createUser·p0.50:   2.920 ms/op
                 createUser·p0.90:   3.326 ms/op
                 createUser·p0.95:   3.527 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  7.178 ms/op
                 createUser·p0.9999: 16.368 ms/op
                 createUser·p1.00:   16.843 ms/op

Iteration   2: 2.913 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.807 ms/op
                 createUser·p0.50:   2.900 ms/op
                 createUser·p0.90:   3.256 ms/op
                 createUser·p0.95:   3.342 ms/op
                 createUser·p0.99:   4.088 ms/op
                 createUser·p0.999:  7.924 ms/op
                 createUser·p0.9999: 15.746 ms/op
                 createUser·p1.00:   16.220 ms/op

Iteration   3: 2.957 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.670 ms/op
                 createUser·p0.50:   2.937 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.670 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  15.008 ms/op
                 createUser·p0.9999: 17.498 ms/op
                 createUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 327971
  mean =      2.927 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1519 
    [ 1.250,  2.500) = 30439 
    [ 2.500,  3.750) = 286660 
    [ 3.750,  5.000) = 8240 
    [ 5.000,  6.250) = 515 
    [ 6.250,  7.500) = 243 
    [ 7.500,  8.750) = 66 
    [ 8.750, 10.000) = 20 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 97 
    [16.250, 17.500) = 105 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.670 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.342 ms/op
     p(95.0000) =      3.539 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      7.865 ms/op
     p(99.9900) =     17.236 ms/op
     p(99.9990) =     17.644 ms/op
     p(99.9999) =     17.727 ms/op
    p(100.0000) =     17.727 ms/op


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
# Warmup Iteration   1: 3.958 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.960 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.835 ±(99.9%) 0.006 ms/op
Iteration   1: 2.857 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.671 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.273 ms/op
                 existUser·p0.95:   3.400 ms/op
                 existUser·p0.99:   4.059 ms/op
                 existUser·p0.999:  5.864 ms/op
                 existUser·p0.9999: 19.261 ms/op
                 existUser·p1.00:   19.628 ms/op

Iteration   2: 2.870 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.647 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  6.384 ms/op
                 existUser·p0.9999: 19.454 ms/op
                 existUser·p1.00:   19.857 ms/op

Iteration   3: 2.842 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.697 ms/op
                 existUser·p0.50:   2.830 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.506 ms/op
                 existUser·p0.999:  7.081 ms/op
                 existUser·p0.9999: 24.183 ms/op
                 existUser·p1.00:   25.133 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 336263
  mean =      2.856 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 57566 
    [ 2.500,  5.000) = 277454 
    [ 5.000,  7.500) = 1019 
    [ 7.500, 10.000) = 60 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.647 ms/op
     p(50.0000) =      2.851 ms/op
     p(90.0000) =      3.365 ms/op
     p(95.0000) =      3.572 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      6.486 ms/op
     p(99.9900) =     19.816 ms/op
     p(99.9990) =     24.880 ms/op
     p(99.9999) =     25.133 ms/op
    p(100.0000) =     25.133 ms/op


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
# Warmup Iteration   1: 3.961 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.030 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.988 ±(99.9%) 0.006 ms/op
Iteration   1: 2.991 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.808 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  7.226 ms/op
                 getUser·p0.9999: 12.888 ms/op
                 getUser·p1.00:   14.107 ms/op

Iteration   2: 2.914 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.791 ms/op
                 getUser·p0.50:   2.941 ms/op
                 getUser·p0.90:   3.367 ms/op
                 getUser·p0.95:   3.633 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  6.163 ms/op
                 getUser·p0.9999: 15.500 ms/op
                 getUser·p1.00:   16.040 ms/op

Iteration   3: 3.001 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.554 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.666 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  7.029 ms/op
                 getUser·p0.9999: 22.096 ms/op
                 getUser·p1.00:   22.970 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 323376
  mean =      2.968 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31007 
    [ 2.500,  5.000) = 291095 
    [ 5.000,  7.500) = 1056 
    [ 7.500, 10.000) = 58 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.554 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.695 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      6.949 ms/op
     p(99.9900) =     18.677 ms/op
     p(99.9990) =     22.275 ms/op
     p(99.9999) =     22.970 ms/op
    p(100.0000) =     22.970 ms/op


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
# Warmup Iteration   1: 4.800 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.016 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.920 ±(99.9%) 0.009 ms/op
Iteration   1: 3.864 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.864 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   6.636 ms/op
                 listUser·p0.999:  12.682 ms/op
                 listUser·p0.9999: 17.433 ms/op
                 listUser·p1.00:   20.120 ms/op

Iteration   2: 3.929 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.241 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  13.500 ms/op
                 listUser·p0.9999: 16.218 ms/op
                 listUser·p1.00:   16.499 ms/op

Iteration   3: 3.872 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.879 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  18.438 ms/op
                 listUser·p0.9999: 21.815 ms/op
                 listUser·p1.00:   22.774 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247098
  mean =      3.888 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5201 
    [ 2.500,  5.000) = 220618 
    [ 5.000,  7.500) = 20277 
    [ 7.500, 10.000) = 571 
    [10.000, 12.500) = 113 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.864 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.858 ms/op
     p(95.0000) =      5.603 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =     13.679 ms/op
     p(99.9900) =     21.482 ms/op
     p(99.9990) =     22.037 ms/op
     p(99.9999) =     22.774 ms/op
    p(100.0000) =     22.774 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.648 ± 0.765  ops/ms
ClientGrpc.existUser                       thrpt       3  11.362 ± 2.338  ops/ms
ClientGrpc.getUser                         thrpt       3  10.734 ± 0.905  ops/ms
ClientGrpc.listUser                        thrpt       3   8.240 ± 2.369  ops/ms
ClientGrpc.createUser                       avgt       3   2.984 ± 0.564   ms/op
ClientGrpc.existUser                        avgt       3   2.836 ± 0.123   ms/op
ClientGrpc.getUser                          avgt       3   2.965 ± 0.276   ms/op
ClientGrpc.listUser                         avgt       3   3.837 ± 1.306   ms/op
ClientGrpc.createUser                     sample  327971   2.927 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.670           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.916           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.342           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.539           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.350           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.865           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.236           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.727           ms/op
ClientGrpc.existUser                      sample  336263   2.856 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.647           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.851           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.365           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.572           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.375           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.486           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.816           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.133           ms/op
ClientGrpc.getUser                        sample  323376   2.968 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.554           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.966           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.494           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.695           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.375           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.949           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.677           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.970           ms/op
ClientGrpc.listUser                       sample  247098   3.888 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.864           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.752           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.858           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.603           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.701           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.679           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.482           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.774           ms/op
