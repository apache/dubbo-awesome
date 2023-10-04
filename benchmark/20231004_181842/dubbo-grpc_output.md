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
# Warmup Iteration   1: 3.238 ops/ms
# Warmup Iteration   2: 8.191 ops/ms
# Warmup Iteration   3: 9.344 ops/ms
Iteration   1: 9.784 ops/ms
Iteration   2: 9.919 ops/ms
Iteration   3: 9.837 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.847 ±(99.9%) 1.236 ops/ms [Average]
  (min, avg, max) = (9.784, 9.847, 9.919), stdev = 0.068
  CI (99.9%): [8.611, 11.083] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.561 ops/ms
# Warmup Iteration   2: 9.709 ops/ms
# Warmup Iteration   3: 10.288 ops/ms
Iteration   1: 10.366 ops/ms
Iteration   2: 10.617 ops/ms
Iteration   3: 10.562 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.515 ±(99.9%) 2.416 ops/ms [Average]
  (min, avg, max) = (10.366, 10.515, 10.617), stdev = 0.132
  CI (99.9%): [8.099, 12.931] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.613 ops/ms
# Warmup Iteration   2: 9.506 ops/ms
# Warmup Iteration   3: 9.806 ops/ms
Iteration   1: 9.737 ops/ms
Iteration   2: 9.794 ops/ms
Iteration   3: 10.132 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.888 ±(99.9%) 3.896 ops/ms [Average]
  (min, avg, max) = (9.737, 9.888, 10.132), stdev = 0.214
  CI (99.9%): [5.992, 13.784] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.709 ops/ms
# Warmup Iteration   2: 7.215 ops/ms
# Warmup Iteration   3: 7.833 ops/ms
Iteration   1: 7.719 ops/ms
Iteration   2: 7.957 ops/ms
Iteration   3: 7.791 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.822 ±(99.9%) 2.233 ops/ms [Average]
  (min, avg, max) = (7.719, 7.822, 7.957), stdev = 0.122
  CI (99.9%): [5.589, 10.055] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.663 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.365 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.246 ±(99.9%) 0.008 ms/op
Iteration   1: 3.319 ±(99.9%) 0.002 ms/op
Iteration   2: 3.191 ±(99.9%) 0.003 ms/op
Iteration   3: 3.224 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.245 ±(99.9%) 1.220 ms/op [Average]
  (min, avg, max) = (3.191, 3.245, 3.319), stdev = 0.067
  CI (99.9%): [2.024, 4.465] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.424 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.185 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.004 ms/op
Iteration   1: 3.075 ±(99.9%) 0.004 ms/op
Iteration   2: 3.080 ±(99.9%) 0.002 ms/op
Iteration   3: 3.062 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.072 ±(99.9%) 0.173 ms/op [Average]
  (min, avg, max) = (3.062, 3.072, 3.080), stdev = 0.009
  CI (99.9%): [2.899, 3.245] (assumes normal distribution)


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
# Warmup Iteration   1: 4.511 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.539 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.263 ±(99.9%) 0.004 ms/op
Iteration   1: 3.193 ±(99.9%) 0.003 ms/op
Iteration   2: 3.166 ±(99.9%) 0.005 ms/op
Iteration   3: 3.155 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.171 ±(99.9%) 0.359 ms/op [Average]
  (min, avg, max) = (3.155, 3.171, 3.193), stdev = 0.020
  CI (99.9%): [2.812, 3.530] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.171 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.262 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.083 ±(99.9%) 0.009 ms/op
Iteration   1: 4.107 ±(99.9%) 0.013 ms/op
Iteration   2: 4.188 ±(99.9%) 0.021 ms/op
Iteration   3: 4.100 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.131 ±(99.9%) 0.888 ms/op [Average]
  (min, avg, max) = (4.100, 4.131, 4.188), stdev = 0.049
  CI (99.9%): [3.243, 5.020] (assumes normal distribution)


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
# Warmup Iteration   1: 4.904 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.383 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.247 ±(99.9%) 0.009 ms/op
Iteration   1: 3.197 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.728 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   3.994 ms/op
                 createUser·p0.99:   4.866 ms/op
                 createUser·p0.999:  11.715 ms/op
                 createUser·p0.9999: 18.251 ms/op
                 createUser·p1.00:   18.776 ms/op

Iteration   2: 3.189 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.709 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   3.981 ms/op
                 createUser·p0.99:   5.325 ms/op
                 createUser·p0.999:  12.747 ms/op
                 createUser·p0.9999: 22.577 ms/op
                 createUser·p1.00:   22.905 ms/op

Iteration   3: 3.215 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.895 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.104 ms/op
                 createUser·p0.99:   5.235 ms/op
                 createUser·p0.999:  20.120 ms/op
                 createUser·p0.9999: 23.398 ms/op
                 createUser·p1.00:   23.757 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 299922
  mean =      3.200 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12850 
    [ 2.500,  5.000) = 283518 
    [ 5.000,  7.500) = 2796 
    [ 7.500, 10.000) = 390 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.709 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      4.026 ms/op
     p(99.0000) =      5.177 ms/op
     p(99.9000) =     12.781 ms/op
     p(99.9900) =     23.069 ms/op
     p(99.9990) =     23.659 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


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
# Warmup Iteration   1: 4.504 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.309 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.124 ±(99.9%) 0.007 ms/op
Iteration   1: 3.117 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.705 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.699 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   4.866 ms/op
                 existUser·p0.999:  13.427 ms/op
                 existUser·p0.9999: 22.093 ms/op
                 existUser·p1.00:   25.723 ms/op

Iteration   2: 3.129 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.801 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.641 ms/op
                 existUser·p0.95:   3.803 ms/op
                 existUser·p0.99:   4.833 ms/op
                 existUser·p0.999:  12.190 ms/op
                 existUser·p0.9999: 23.643 ms/op
                 existUser·p1.00:   24.216 ms/op

Iteration   3: 3.028 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.817 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   4.563 ms/op
                 existUser·p0.999:  9.333 ms/op
                 existUser·p0.9999: 16.316 ms/op
                 existUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 310688
  mean =      3.091 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18731 
    [ 2.500,  5.000) = 289523 
    [ 5.000,  7.500) = 1718 
    [ 7.500, 10.000) = 342 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.705 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      4.792 ms/op
     p(99.9000) =     10.971 ms/op
     p(99.9900) =     22.016 ms/op
     p(99.9990) =     24.143 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.922 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.436 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.300 ±(99.9%) 0.009 ms/op
Iteration   1: 3.255 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.767 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.936 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   5.530 ms/op
                 getUser·p0.999:  11.764 ms/op
                 getUser·p0.9999: 24.910 ms/op
                 getUser·p1.00:   24.969 ms/op

Iteration   2: 3.245 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.783 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.875 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   5.685 ms/op
                 getUser·p0.999:  10.023 ms/op
                 getUser·p0.9999: 16.482 ms/op
                 getUser·p1.00:   17.433 ms/op

Iteration   3: 3.165 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.766 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.067 ms/op
                 getUser·p0.99:   4.886 ms/op
                 getUser·p0.999:  11.596 ms/op
                 getUser·p0.9999: 20.440 ms/op
                 getUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 297896
  mean =      3.221 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16288 
    [ 2.500,  5.000) = 277356 
    [ 5.000,  7.500) = 3267 
    [ 7.500, 10.000) = 576 
    [10.000, 12.500) = 186 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.766 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.178 ms/op
     p(99.0000) =      5.390 ms/op
     p(99.9000) =     11.081 ms/op
     p(99.9900) =     20.225 ms/op
     p(99.9990) =     24.969 ms/op
     p(99.9999) =     24.969 ms/op
    p(100.0000) =     24.969 ms/op


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
# Warmup Iteration   1: 5.630 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.346 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.247 ±(99.9%) 0.015 ms/op
Iteration   1: 4.233 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.565 ms/op
                 listUser·p0.50:   3.990 ms/op
                 listUser·p0.90:   5.423 ms/op
                 listUser·p0.95:   6.160 ms/op
                 listUser·p0.99:   7.922 ms/op
                 listUser·p0.999:  15.679 ms/op
                 listUser·p0.9999: 18.157 ms/op
                 listUser·p1.00:   19.104 ms/op

Iteration   2: 4.349 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   0.943 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   5.407 ms/op
                 listUser·p0.95:   6.627 ms/op
                 listUser·p0.99:   13.779 ms/op
                 listUser·p0.999:  18.579 ms/op
                 listUser·p0.9999: 21.058 ms/op
                 listUser·p1.00:   22.839 ms/op

Iteration   3: 4.122 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.169 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   6.062 ms/op
                 listUser·p0.99:   7.848 ms/op
                 listUser·p0.999:  19.393 ms/op
                 listUser·p0.9999: 22.634 ms/op
                 listUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 226710
  mean =      4.233 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1799 
    [ 2.500,  5.000) = 194980 
    [ 5.000,  7.500) = 25539 
    [ 7.500, 10.000) = 2061 
    [10.000, 12.500) = 847 
    [12.500, 15.000) = 758 
    [15.000, 17.500) = 459 
    [17.500, 20.000) = 170 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.943 ms/op
     p(50.0000) =      3.973 ms/op
     p(90.0000) =      5.349 ms/op
     p(95.0000) =      6.279 ms/op
     p(99.0000) =     10.174 ms/op
     p(99.9000) =     17.760 ms/op
     p(99.9900) =     22.271 ms/op
     p(99.9990) =     23.346 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.847 ± 1.236  ops/ms
ClientGrpc.existUser                       thrpt       3  10.515 ± 2.416  ops/ms
ClientGrpc.getUser                         thrpt       3   9.888 ± 3.896  ops/ms
ClientGrpc.listUser                        thrpt       3   7.822 ± 2.233  ops/ms
ClientGrpc.createUser                       avgt       3   3.245 ± 1.220   ms/op
ClientGrpc.existUser                        avgt       3   3.072 ± 0.173   ms/op
ClientGrpc.getUser                          avgt       3   3.171 ± 0.359   ms/op
ClientGrpc.listUser                         avgt       3   4.131 ± 0.888   ms/op
ClientGrpc.createUser                     sample  299922   3.200 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.709           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.146           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.772           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.026           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.177           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.781           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.069           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.757           ms/op
ClientGrpc.existUser                      sample  310688   3.091 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.705           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.052           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.625           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.830           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.792           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.971           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.016           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.723           ms/op
ClientGrpc.getUser                        sample  297896   3.221 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.766           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.158           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.867           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.178           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.390           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.081           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.225           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.969           ms/op
ClientGrpc.listUser                       sample  226710   4.233 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.943           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.973           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.349           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.279           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.174           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.760           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.271           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.527           ms/op
