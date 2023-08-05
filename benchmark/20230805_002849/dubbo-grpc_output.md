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
# Warmup Iteration   1: 4.648 ops/ms
# Warmup Iteration   2: 9.744 ops/ms
# Warmup Iteration   3: 10.119 ops/ms
Iteration   1: 10.666 ops/ms
Iteration   2: 10.540 ops/ms
Iteration   3: 10.638 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.615 ±(99.9%) 1.200 ops/ms [Average]
  (min, avg, max) = (10.540, 10.615, 10.666), stdev = 0.066
  CI (99.9%): [9.414, 11.815] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.921 ops/ms
# Warmup Iteration   2: 11.015 ops/ms
# Warmup Iteration   3: 11.225 ops/ms
Iteration   1: 11.007 ops/ms
Iteration   2: 11.223 ops/ms
Iteration   3: 11.210 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.147 ±(99.9%) 2.209 ops/ms [Average]
  (min, avg, max) = (11.007, 11.147, 11.223), stdev = 0.121
  CI (99.9%): [8.938, 13.355] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.582 ops/ms
# Warmup Iteration   2: 10.134 ops/ms
# Warmup Iteration   3: 10.656 ops/ms
Iteration   1: 10.711 ops/ms
Iteration   2: 10.704 ops/ms
Iteration   3: 10.594 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.670 ±(99.9%) 1.190 ops/ms [Average]
  (min, avg, max) = (10.594, 10.670, 10.711), stdev = 0.065
  CI (99.9%): [9.480, 11.860] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.425 ops/ms
# Warmup Iteration   2: 8.019 ops/ms
# Warmup Iteration   3: 8.011 ops/ms
Iteration   1: 8.164 ops/ms
Iteration   2: 8.154 ops/ms
Iteration   3: 8.149 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.156 ±(99.9%) 0.135 ops/ms [Average]
  (min, avg, max) = (8.149, 8.156, 8.164), stdev = 0.007
  CI (99.9%): [8.021, 8.291] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.156 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.203 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.003 ms/op
Iteration   1: 3.044 ±(99.9%) 0.009 ms/op
Iteration   2: 3.030 ±(99.9%) 0.002 ms/op
Iteration   3: 2.975 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.016 ±(99.9%) 0.659 ms/op [Average]
  (min, avg, max) = (2.975, 3.016, 3.044), stdev = 0.036
  CI (99.9%): [2.358, 3.675] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.673 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 2.996 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.946 ±(99.9%) 0.004 ms/op
Iteration   1: 2.877 ±(99.9%) 0.004 ms/op
Iteration   2: 2.880 ±(99.9%) 0.004 ms/op
Iteration   3: 2.849 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.868 ±(99.9%) 0.315 ms/op [Average]
  (min, avg, max) = (2.849, 2.868, 2.880), stdev = 0.017
  CI (99.9%): [2.553, 3.183] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.983 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.043 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.003 ms/op
Iteration   1: 2.936 ±(99.9%) 0.004 ms/op
Iteration   2: 2.992 ±(99.9%) 0.003 ms/op
Iteration   3: 2.990 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.972 ±(99.9%) 0.581 ms/op [Average]
  (min, avg, max) = (2.936, 2.972, 2.992), stdev = 0.032
  CI (99.9%): [2.391, 3.553] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.406 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 4.072 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.893 ±(99.9%) 0.013 ms/op
Iteration   1: 3.816 ±(99.9%) 0.007 ms/op
Iteration   2: 3.948 ±(99.9%) 0.010 ms/op
Iteration   3: 3.896 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.887 ±(99.9%) 1.210 ms/op [Average]
  (min, avg, max) = (3.816, 3.887, 3.948), stdev = 0.066
  CI (99.9%): [2.677, 5.096] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.190 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.129 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.007 ms/op
Iteration   1: 2.969 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.773 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.379 ms/op
                 createUser·p0.95:   3.654 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  6.604 ms/op
                 createUser·p0.9999: 12.259 ms/op
                 createUser·p1.00:   12.550 ms/op

Iteration   2: 3.046 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.835 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  8.069 ms/op
                 createUser·p0.9999: 19.677 ms/op
                 createUser·p1.00:   19.890 ms/op

Iteration   3: 3.041 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.860 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  10.121 ms/op
                 createUser·p0.9999: 14.647 ms/op
                 createUser·p1.00:   14.860 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317879
  mean =      3.018 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1551 
    [ 1.250,  2.500) = 22963 
    [ 2.500,  3.750) = 273014 
    [ 3.750,  5.000) = 18572 
    [ 5.000,  6.250) = 1021 
    [ 6.250,  7.500) = 386 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 82 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 70 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.773 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      9.044 ms/op
     p(99.9900) =     18.888 ms/op
     p(99.9990) =     19.825 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.826 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.973 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.937 ±(99.9%) 0.006 ms/op
Iteration   1: 2.891 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.784 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  9.784 ms/op
                 existUser·p0.9999: 12.549 ms/op
                 existUser·p1.00:   12.845 ms/op

Iteration   2: 2.890 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.693 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.620 ms/op
                 existUser·p0.999:  8.522 ms/op
                 existUser·p0.9999: 21.392 ms/op
                 existUser·p1.00:   22.282 ms/op

Iteration   3: 2.893 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.603 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.645 ms/op
                 existUser·p0.999:  8.166 ms/op
                 existUser·p0.9999: 15.581 ms/op
                 existUser·p1.00:   16.089 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332256
  mean =      2.891 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 52674 
    [ 2.500,  5.000) = 277536 
    [ 5.000,  7.500) = 1541 
    [ 7.500, 10.000) = 280 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.603 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.695 ms/op
     p(99.0000) =      4.596 ms/op
     p(99.9000) =      8.630 ms/op
     p(99.9900) =     16.085 ms/op
     p(99.9990) =     21.496 ms/op
     p(99.9999) =     22.282 ms/op
    p(100.0000) =     22.282 ms/op


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
# Warmup Iteration   1: 3.857 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.100 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.975 ±(99.9%) 0.006 ms/op
Iteration   1: 3.000 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.785 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  7.594 ms/op
                 getUser·p0.9999: 20.458 ms/op
                 getUser·p1.00:   20.840 ms/op

Iteration   2: 2.997 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.599 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  6.335 ms/op
                 getUser·p0.9999: 13.243 ms/op
                 getUser·p1.00:   17.859 ms/op

Iteration   3: 2.953 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.629 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.379 ms/op
                 getUser·p0.95:   3.682 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  7.684 ms/op
                 getUser·p0.9999: 27.536 ms/op
                 getUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 321820
  mean =      2.983 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23886 
    [ 2.500,  5.000) = 296428 
    [ 5.000,  7.500) = 1179 
    [ 7.500, 10.000) = 164 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.599 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.449 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      7.537 ms/op
     p(99.9900) =     24.838 ms/op
     p(99.9990) =     27.747 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


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
# Warmup Iteration   1: 5.141 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.164 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.963 ±(99.9%) 0.011 ms/op
Iteration   1: 4.025 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.620 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   7.291 ms/op
                 listUser·p0.999:  15.106 ms/op
                 listUser·p0.9999: 18.241 ms/op
                 listUser·p1.00:   22.282 ms/op

Iteration   2: 3.920 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.227 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  15.962 ms/op
                 listUser·p0.9999: 23.978 ms/op
                 listUser·p1.00:   24.510 ms/op

Iteration   3: 3.933 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.896 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   7.315 ms/op
                 listUser·p0.999:  14.404 ms/op
                 listUser·p0.9999: 17.105 ms/op
                 listUser·p1.00:   17.596 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242594
  mean =      3.959 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6804 
    [ 2.500,  5.000) = 206154 
    [ 5.000,  7.500) = 27811 
    [ 7.500, 10.000) = 1241 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 183 
    [15.000, 17.500) = 191 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.620 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.816 ms/op
     p(99.0000) =      7.176 ms/op
     p(99.9000) =     15.106 ms/op
     p(99.9900) =     23.027 ms/op
     p(99.9990) =     24.403 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.615 ± 1.200  ops/ms
ClientGrpc.existUser                       thrpt       3  11.147 ± 2.209  ops/ms
ClientGrpc.getUser                         thrpt       3  10.670 ± 1.190  ops/ms
ClientGrpc.listUser                        thrpt       3   8.156 ± 0.135  ops/ms
ClientGrpc.createUser                       avgt       3   3.016 ± 0.659   ms/op
ClientGrpc.existUser                        avgt       3   2.868 ± 0.315   ms/op
ClientGrpc.getUser                          avgt       3   2.972 ± 0.581   ms/op
ClientGrpc.listUser                         avgt       3   3.887 ± 1.210   ms/op
ClientGrpc.createUser                     sample  317879   3.018 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.773           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.990           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.584           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.822           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.448           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.044           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.888           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.890           ms/op
ClientGrpc.existUser                      sample  332256   2.891 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.603           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.453           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.695           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.596           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.630           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.085           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.282           ms/op
ClientGrpc.getUser                        sample  321820   2.983 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.599           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.974           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.449           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.699           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.309           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.537           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.838           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.886           ms/op
ClientGrpc.listUser                       sample  242594   3.959 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.620           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.781           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.161           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.816           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.176           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.106           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.027           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.510           ms/op
