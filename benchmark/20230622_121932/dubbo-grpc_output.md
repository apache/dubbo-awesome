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
# Warmup Iteration   1: 4.559 ops/ms
# Warmup Iteration   2: 9.320 ops/ms
# Warmup Iteration   3: 10.208 ops/ms
Iteration   1: 10.716 ops/ms
Iteration   2: 10.952 ops/ms
Iteration   3: 10.859 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.842 ±(99.9%) 2.170 ops/ms [Average]
  (min, avg, max) = (10.716, 10.842, 10.952), stdev = 0.119
  CI (99.9%): [8.673, 13.012] (assumes normal distribution)


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
# Warmup Iteration   1: 8.105 ops/ms
# Warmup Iteration   2: 10.783 ops/ms
# Warmup Iteration   3: 11.285 ops/ms
Iteration   1: 11.193 ops/ms
Iteration   2: 11.217 ops/ms
Iteration   3: 11.282 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.231 ±(99.9%) 0.842 ops/ms [Average]
  (min, avg, max) = (11.193, 11.231, 11.282), stdev = 0.046
  CI (99.9%): [10.389, 12.073] (assumes normal distribution)


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
# Warmup Iteration   1: 7.777 ops/ms
# Warmup Iteration   2: 10.547 ops/ms
# Warmup Iteration   3: 10.856 ops/ms
Iteration   1: 10.943 ops/ms
Iteration   2: 10.741 ops/ms
Iteration   3: 10.844 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.843 ±(99.9%) 1.848 ops/ms [Average]
  (min, avg, max) = (10.741, 10.843, 10.943), stdev = 0.101
  CI (99.9%): [8.995, 12.690] (assumes normal distribution)


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
# Warmup Iteration   1: 5.663 ops/ms
# Warmup Iteration   2: 8.157 ops/ms
# Warmup Iteration   3: 8.192 ops/ms
Iteration   1: 8.219 ops/ms
Iteration   2: 8.340 ops/ms
Iteration   3: 8.189 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.249 ±(99.9%) 1.463 ops/ms [Average]
  (min, avg, max) = (8.189, 8.249, 8.340), stdev = 0.080
  CI (99.9%): [6.786, 9.712] (assumes normal distribution)


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
# Warmup Iteration   1: 3.945 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.071 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.005 ms/op
Iteration   1: 3.043 ±(99.9%) 0.011 ms/op
Iteration   2: 2.963 ±(99.9%) 0.002 ms/op
Iteration   3: 2.957 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.988 ±(99.9%) 0.875 ms/op [Average]
  (min, avg, max) = (2.957, 2.988, 3.043), stdev = 0.048
  CI (99.9%): [2.113, 3.863] (assumes normal distribution)


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
# Warmup Iteration   1: 3.737 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 2.896 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.845 ±(99.9%) 0.004 ms/op
Iteration   1: 2.851 ±(99.9%) 0.003 ms/op
Iteration   2: 2.855 ±(99.9%) 0.003 ms/op
Iteration   3: 2.859 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.855 ±(99.9%) 0.074 ms/op [Average]
  (min, avg, max) = (2.851, 2.855, 2.859), stdev = 0.004
  CI (99.9%): [2.781, 2.929] (assumes normal distribution)


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
# Warmup Iteration   1: 4.008 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.026 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.956 ±(99.9%) 0.003 ms/op
Iteration   1: 3.000 ±(99.9%) 0.003 ms/op
Iteration   2: 2.992 ±(99.9%) 0.003 ms/op
Iteration   3: 2.932 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.975 ±(99.9%) 0.677 ms/op [Average]
  (min, avg, max) = (2.932, 2.975, 3.000), stdev = 0.037
  CI (99.9%): [2.298, 3.651] (assumes normal distribution)


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
# Warmup Iteration   1: 5.082 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.962 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.937 ±(99.9%) 0.018 ms/op
Iteration   1: 3.820 ±(99.9%) 0.023 ms/op
Iteration   2: 3.747 ±(99.9%) 0.035 ms/op
Iteration   3: 3.749 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.772 ±(99.9%) 0.753 ms/op [Average]
  (min, avg, max) = (3.747, 3.772, 3.820), stdev = 0.041
  CI (99.9%): [3.019, 4.525] (assumes normal distribution)


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
# Warmup Iteration   1: 3.988 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.186 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.951 ±(99.9%) 0.006 ms/op
Iteration   1: 2.966 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.603 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  8.536 ms/op
                 createUser·p0.9999: 19.366 ms/op
                 createUser·p1.00:   19.792 ms/op

Iteration   2: 2.969 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.493 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  8.639 ms/op
                 createUser·p0.9999: 12.718 ms/op
                 createUser·p1.00:   14.451 ms/op

Iteration   3: 3.033 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.681 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.441 ms/op
                 createUser·p0.95:   3.662 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  14.723 ms/op
                 createUser·p0.9999: 20.724 ms/op
                 createUser·p1.00:   20.873 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321312
  mean =      2.989 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33343 
    [ 2.500,  5.000) = 286524 
    [ 5.000,  7.500) = 837 
    [ 7.500, 10.000) = 252 
    [10.000, 12.500) = 131 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.493 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =     10.623 ms/op
     p(99.9900) =     18.973 ms/op
     p(99.9990) =     20.826 ms/op
     p(99.9999) =     20.873 ms/op
    p(100.0000) =     20.873 ms/op


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
# Warmup Iteration   1: 3.853 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.942 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.874 ±(99.9%) 0.006 ms/op
Iteration   1: 2.797 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.692 ms/op
                 existUser·p0.50:   2.834 ms/op
                 existUser·p0.90:   3.187 ms/op
                 existUser·p0.95:   3.322 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  7.723 ms/op
                 existUser·p0.9999: 11.176 ms/op
                 existUser·p1.00:   12.878 ms/op

Iteration   2: 2.838 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.702 ms/op
                 existUser·p0.50:   2.839 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.502 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  6.144 ms/op
                 existUser·p0.9999: 14.274 ms/op
                 existUser·p1.00:   14.500 ms/op

Iteration   3: 2.876 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.742 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  6.029 ms/op
                 existUser·p0.9999: 15.169 ms/op
                 existUser·p1.00:   15.450 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 338359
  mean =      2.837 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4645 
    [ 1.250,  2.500) = 46170 
    [ 2.500,  3.750) = 279447 
    [ 3.750,  5.000) = 7044 
    [ 5.000,  6.250) = 670 
    [ 6.250,  7.500) = 103 
    [ 7.500,  8.750) = 88 
    [ 8.750, 10.000) = 20 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 72 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.692 ms/op
     p(50.0000) =      2.847 ms/op
     p(90.0000) =      3.297 ms/op
     p(95.0000) =      3.535 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      6.824 ms/op
     p(99.9900) =     14.647 ms/op
     p(99.9990) =     15.280 ms/op
     p(99.9999) =     15.450 ms/op
    p(100.0000) =     15.450 ms/op


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
# Warmup Iteration   1: 3.870 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.107 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.006 ms/op
Iteration   1: 2.991 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.712 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.494 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   4.547 ms/op
                 getUser·p0.999:  8.152 ms/op
                 getUser·p0.9999: 15.493 ms/op
                 getUser·p1.00:   15.942 ms/op

Iteration   2: 2.950 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.715 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.342 ms/op
                 getUser·p0.95:   3.494 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  6.154 ms/op
                 getUser·p0.9999: 23.462 ms/op
                 getUser·p1.00:   24.412 ms/op

Iteration   3: 2.923 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.702 ms/op
                 getUser·p0.50:   2.937 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.654 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  6.705 ms/op
                 getUser·p0.9999: 20.581 ms/op
                 getUser·p1.00:   21.070 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 324914
  mean =      2.955 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29362 
    [ 2.500,  5.000) = 294582 
    [ 5.000,  7.500) = 697 
    [ 7.500, 10.000) = 49 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.702 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.437 ms/op
     p(95.0000) =      3.637 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      6.679 ms/op
     p(99.9900) =     20.677 ms/op
     p(99.9990) =     23.724 ms/op
     p(99.9999) =     24.412 ms/op
    p(100.0000) =     24.412 ms/op


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
# Warmup Iteration   1: 4.459 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.935 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.886 ±(99.9%) 0.010 ms/op
Iteration   1: 3.910 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.825 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.390 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  13.393 ms/op
                 listUser·p0.9999: 17.086 ms/op
                 listUser·p1.00:   18.350 ms/op

Iteration   2: 3.855 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.645 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  14.273 ms/op
                 listUser·p0.9999: 23.793 ms/op
                 listUser·p1.00:   25.526 ms/op

Iteration   3: 3.731 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.898 ms/op
                 listUser·p0.50:   3.596 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  14.243 ms/op
                 listUser·p0.9999: 19.956 ms/op
                 listUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 250534
  mean =      3.831 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7656 
    [ 2.500,  5.000) = 220231 
    [ 5.000,  7.500) = 21461 
    [ 7.500, 10.000) = 724 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 140 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.645 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.915 ms/op
     p(95.0000) =      5.538 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     13.852 ms/op
     p(99.9900) =     22.312 ms/op
     p(99.9990) =     25.428 ms/op
     p(99.9999) =     25.526 ms/op
    p(100.0000) =     25.526 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.842 ± 2.170  ops/ms
ClientGrpc.existUser                       thrpt       3  11.231 ± 0.842  ops/ms
ClientGrpc.getUser                         thrpt       3  10.843 ± 1.848  ops/ms
ClientGrpc.listUser                        thrpt       3   8.249 ± 1.463  ops/ms
ClientGrpc.createUser                       avgt       3   2.988 ± 0.875   ms/op
ClientGrpc.existUser                        avgt       3   2.855 ± 0.074   ms/op
ClientGrpc.getUser                          avgt       3   2.975 ± 0.677   ms/op
ClientGrpc.listUser                         avgt       3   3.772 ± 0.753   ms/op
ClientGrpc.createUser                     sample  321312   2.989 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.493           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.978           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.510           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.740           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.623           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.973           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.873           ms/op
ClientGrpc.existUser                      sample  338359   2.837 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.692           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.847           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.297           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.535           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.293           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.824           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.647           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.450           ms/op
ClientGrpc.getUser                        sample  324914   2.955 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.702           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.949           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.437           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.637           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.350           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.679           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.677           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.412           ms/op
ClientGrpc.listUser                       sample  250534   3.831 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.645           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.690           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.915           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.538           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.799           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.852           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.312           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.526           ms/op
