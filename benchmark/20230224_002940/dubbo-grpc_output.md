# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.771 ops/ms
# Warmup Iteration   2: 9.244 ops/ms
# Warmup Iteration   3: 10.188 ops/ms
Iteration   1: 9.804 ops/ms
Iteration   2: 10.183 ops/ms
Iteration   3: 10.396 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.128 ±(99.9%) 5.474 ops/ms [Average]
  (min, avg, max) = (9.804, 10.128, 10.396), stdev = 0.300
  CI (99.9%): [4.654, 15.601] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.872 ops/ms
# Warmup Iteration   2: 10.597 ops/ms
# Warmup Iteration   3: 10.786 ops/ms
Iteration   1: 11.049 ops/ms
Iteration   2: 10.780 ops/ms
Iteration   3: 10.736 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.855 ±(99.9%) 3.084 ops/ms [Average]
  (min, avg, max) = (10.736, 10.855, 11.049), stdev = 0.169
  CI (99.9%): [7.771, 13.940] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.520 ops/ms
# Warmup Iteration   2: 10.242 ops/ms
# Warmup Iteration   3: 10.550 ops/ms
Iteration   1: 10.634 ops/ms
Iteration   2: 10.493 ops/ms
Iteration   3: 10.362 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.497 ±(99.9%) 2.486 ops/ms [Average]
  (min, avg, max) = (10.362, 10.497, 10.634), stdev = 0.136
  CI (99.9%): [8.011, 12.982] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.333 ops/ms
# Warmup Iteration   2: 7.944 ops/ms
# Warmup Iteration   3: 8.161 ops/ms
Iteration   1: 7.939 ops/ms
Iteration   2: 8.169 ops/ms
Iteration   3: 8.134 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.081 ±(99.9%) 2.262 ops/ms [Average]
  (min, avg, max) = (7.939, 8.081, 8.169), stdev = 0.124
  CI (99.9%): [5.819, 10.343] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.954 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.162 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.134 ±(99.9%) 0.002 ms/op
Iteration   1: 3.103 ±(99.9%) 0.006 ms/op
Iteration   2: 3.140 ±(99.9%) 0.002 ms/op
Iteration   3: 3.154 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.132 ±(99.9%) 0.476 ms/op [Average]
  (min, avg, max) = (3.103, 3.132, 3.154), stdev = 0.026
  CI (99.9%): [2.656, 3.609] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.904 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.098 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 2.950 ±(99.9%) 0.002 ms/op
Iteration   1: 2.910 ±(99.9%) 0.002 ms/op
Iteration   2: 2.977 ±(99.9%) 0.002 ms/op
Iteration   3: 3.066 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.984 ±(99.9%) 1.433 ms/op [Average]
  (min, avg, max) = (2.910, 2.984, 3.066), stdev = 0.079
  CI (99.9%): [1.551, 4.418] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.811 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.108 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.127 ±(99.9%) 0.003 ms/op
Iteration   1: 3.032 ±(99.9%) 0.002 ms/op
Iteration   2: 3.047 ±(99.9%) 0.003 ms/op
Iteration   3: 3.127 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.068 ±(99.9%) 0.929 ms/op [Average]
  (min, avg, max) = (3.032, 3.068, 3.127), stdev = 0.051
  CI (99.9%): [2.140, 3.997] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.784 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.100 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.956 ±(99.9%) 0.016 ms/op
Iteration   1: 3.943 ±(99.9%) 0.049 ms/op
Iteration   2: 3.921 ±(99.9%) 0.009 ms/op
Iteration   3: 4.034 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.966 ±(99.9%) 1.090 ms/op [Average]
  (min, avg, max) = (3.921, 3.966, 4.034), stdev = 0.060
  CI (99.9%): [2.876, 5.056] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.822 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.168 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.076 ±(99.9%) 0.007 ms/op
Iteration   1: 3.164 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.772 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.002 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  6.544 ms/op
                 createUser·p0.9999: 12.266 ms/op
                 createUser·p1.00:   12.599 ms/op

Iteration   2: 3.170 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.608 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.850 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  9.454 ms/op
                 createUser·p0.9999: 13.792 ms/op
                 createUser·p1.00:   14.172 ms/op

Iteration   3: 3.212 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.878 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.932 ms/op
                 createUser·p0.95:   4.080 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  8.190 ms/op
                 createUser·p0.9999: 24.808 ms/op
                 createUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 301660
  mean =      3.182 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19905 
    [ 2.500,  5.000) = 280819 
    [ 5.000,  7.500) = 565 
    [ 7.500, 10.000) = 140 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.608 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.043 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      8.787 ms/op
     p(99.9900) =     23.975 ms/op
     p(99.9990) =     25.651 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.845 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.006 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.899 ±(99.9%) 0.007 ms/op
Iteration   1: 2.952 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.652 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  6.411 ms/op
                 existUser·p0.9999: 13.183 ms/op
                 existUser·p1.00:   13.713 ms/op

Iteration   2: 2.969 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.737 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   4.186 ms/op
                 existUser·p0.999:  6.733 ms/op
                 existUser·p0.9999: 21.569 ms/op
                 existUser·p1.00:   21.987 ms/op

Iteration   3: 2.970 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.607 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.629 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.171 ms/op
                 existUser·p0.999:  9.093 ms/op
                 existUser·p0.9999: 21.823 ms/op
                 existUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323737
  mean =      2.964 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47486 
    [ 2.500,  5.000) = 275413 
    [ 5.000,  7.500) = 579 
    [ 7.500, 10.000) = 76 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.607 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      4.186 ms/op
     p(99.9000) =      6.834 ms/op
     p(99.9900) =     21.516 ms/op
     p(99.9990) =     22.362 ms/op
     p(99.9999) =     22.938 ms/op
    p(100.0000) =     22.938 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.909 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.006 ms/op
Iteration   1: 3.128 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.736 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   4.445 ms/op
                 getUser·p0.999:  8.303 ms/op
                 getUser·p0.9999: 11.613 ms/op
                 getUser·p1.00:   11.796 ms/op

Iteration   2: 3.066 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.560 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   4.157 ms/op
                 getUser·p0.999:  6.101 ms/op
                 getUser·p0.9999: 12.775 ms/op
                 getUser·p1.00:   13.025 ms/op

Iteration   3: 3.058 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.238 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  6.892 ms/op
                 getUser·p0.9999: 15.368 ms/op
                 getUser·p1.00:   15.827 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311232
  mean =      3.084 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1292 
    [ 1.250,  2.500) = 21486 
    [ 2.500,  3.750) = 262835 
    [ 3.750,  5.000) = 24587 
    [ 5.000,  6.250) = 537 
    [ 6.250,  7.500) = 225 
    [ 7.500,  8.750) = 93 
    [ 8.750, 10.000) = 17 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.238 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      7.094 ms/op
     p(99.9900) =     14.694 ms/op
     p(99.9990) =     15.705 ms/op
     p(99.9999) =     15.827 ms/op
    p(100.0000) =     15.827 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.972 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.980 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.992 ±(99.9%) 0.011 ms/op
Iteration   1: 3.909 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.955 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   6.480 ms/op
                 listUser·p0.999:  12.226 ms/op
                 listUser·p0.9999: 13.331 ms/op
                 listUser·p1.00:   14.156 ms/op

Iteration   2: 3.801 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.200 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   5.439 ms/op
                 listUser·p0.99:   6.480 ms/op
                 listUser·p0.999:  13.579 ms/op
                 listUser·p0.9999: 16.225 ms/op
                 listUser·p1.00:   16.499 ms/op

Iteration   3: 3.952 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.770 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  16.717 ms/op
                 listUser·p0.9999: 23.521 ms/op
                 listUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246916
  mean =      3.886 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4780 
    [ 2.500,  5.000) = 218967 
    [ 5.000,  7.500) = 22163 
    [ 7.500, 10.000) = 524 
    [10.000, 12.500) = 133 
    [12.500, 15.000) = 208 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.770 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.948 ms/op
     p(95.0000) =      5.497 ms/op
     p(99.0000) =      6.611 ms/op
     p(99.9000) =     13.535 ms/op
     p(99.9900) =     18.491 ms/op
     p(99.9990) =     23.792 ms/op
     p(99.9999) =     23.921 ms/op
    p(100.0000) =     23.921 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.128 ± 5.474  ops/ms
ClientGrpc.existUser                       thrpt       3  10.855 ± 3.084  ops/ms
ClientGrpc.getUser                         thrpt       3  10.497 ± 2.486  ops/ms
ClientGrpc.listUser                        thrpt       3   8.081 ± 2.262  ops/ms
ClientGrpc.createUser                       avgt       3   3.132 ± 0.476   ms/op
ClientGrpc.existUser                        avgt       3   2.984 ± 1.433   ms/op
ClientGrpc.getUser                          avgt       3   3.068 ± 0.929   ms/op
ClientGrpc.listUser                         avgt       3   3.966 ± 1.090   ms/op
ClientGrpc.createUser                     sample  301660   3.182 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.608           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.154           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.871           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.043           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.334           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.787           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.975           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.919           ms/op
ClientGrpc.existUser                      sample  323737   2.964 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.607           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.957           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.621           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.805           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.186           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.834           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.516           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.938           ms/op
ClientGrpc.getUser                        sample  311232   3.084 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.238           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.072           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.695           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.883           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.268           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.094           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.694           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          15.827           ms/op
ClientGrpc.listUser                       sample  246916   3.886 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.770           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.744           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.948           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.497           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.611           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.535           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.491           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.921           ms/op
