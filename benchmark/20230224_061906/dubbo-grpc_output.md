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
# Warmup Iteration   1: 4.147 ops/ms
# Warmup Iteration   2: 8.835 ops/ms
# Warmup Iteration   3: 9.818 ops/ms
Iteration   1: 10.100 ops/ms
Iteration   2: 9.813 ops/ms
Iteration   3: 10.024 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.979 ±(99.9%) 2.720 ops/ms [Average]
  (min, avg, max) = (9.813, 9.979, 10.100), stdev = 0.149
  CI (99.9%): [7.259, 12.699] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.588 ops/ms
# Warmup Iteration   2: 10.099 ops/ms
# Warmup Iteration   3: 10.386 ops/ms
Iteration   1: 10.657 ops/ms
Iteration   2: 10.423 ops/ms
Iteration   3: 10.718 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.599 ±(99.9%) 2.842 ops/ms [Average]
  (min, avg, max) = (10.423, 10.599, 10.718), stdev = 0.156
  CI (99.9%): [7.757, 13.441] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.335 ops/ms
# Warmup Iteration   2: 9.544 ops/ms
# Warmup Iteration   3: 9.958 ops/ms
Iteration   1: 9.789 ops/ms
Iteration   2: 9.885 ops/ms
Iteration   3: 9.940 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.871 ±(99.9%) 1.391 ops/ms [Average]
  (min, avg, max) = (9.789, 9.871, 9.940), stdev = 0.076
  CI (99.9%): [8.480, 11.263] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.539 ops/ms
# Warmup Iteration   2: 7.481 ops/ms
# Warmup Iteration   3: 7.668 ops/ms
Iteration   1: 7.981 ops/ms
Iteration   2: 7.714 ops/ms
Iteration   3: 7.743 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.813 ±(99.9%) 2.677 ops/ms [Average]
  (min, avg, max) = (7.714, 7.813, 7.981), stdev = 0.147
  CI (99.9%): [5.136, 10.489] (assumes normal distribution)


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
# Warmup Iteration   1: 4.264 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.269 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.293 ±(99.9%) 0.002 ms/op
Iteration   1: 3.257 ±(99.9%) 0.001 ms/op
Iteration   2: 3.199 ±(99.9%) 0.002 ms/op
Iteration   3: 3.242 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.233 ±(99.9%) 0.544 ms/op [Average]
  (min, avg, max) = (3.199, 3.233, 3.257), stdev = 0.030
  CI (99.9%): [2.689, 3.776] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.046 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.177 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.132 ±(99.9%) 0.002 ms/op
Iteration   1: 3.001 ±(99.9%) 0.004 ms/op
Iteration   2: 3.073 ±(99.9%) 0.001 ms/op
Iteration   3: 3.075 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.050 ±(99.9%) 0.761 ms/op [Average]
  (min, avg, max) = (3.001, 3.050, 3.075), stdev = 0.042
  CI (99.9%): [2.288, 3.811] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.255 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.182 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.172 ±(99.9%) 0.003 ms/op
Iteration   1: 3.188 ±(99.9%) 0.002 ms/op
Iteration   2: 3.165 ±(99.9%) 0.002 ms/op
Iteration   3: 3.122 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.158 ±(99.9%) 0.614 ms/op [Average]
  (min, avg, max) = (3.122, 3.158, 3.188), stdev = 0.034
  CI (99.9%): [2.544, 3.772] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.738 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.250 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.036 ±(99.9%) 0.029 ms/op
Iteration   1: 3.941 ±(99.9%) 0.015 ms/op
Iteration   2: 3.976 ±(99.9%) 0.004 ms/op
Iteration   3: 3.972 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.963 ±(99.9%) 0.349 ms/op [Average]
  (min, avg, max) = (3.941, 3.963, 3.976), stdev = 0.019
  CI (99.9%): [3.614, 4.313] (assumes normal distribution)


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
# Warmup Iteration   1: 4.306 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.306 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.214 ±(99.9%) 0.007 ms/op
Iteration   1: 3.128 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.786 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.817 ms/op
                 createUser·p0.95:   4.043 ms/op
                 createUser·p0.99:   4.809 ms/op
                 createUser·p0.999:  8.660 ms/op
                 createUser·p0.9999: 12.867 ms/op
                 createUser·p1.00:   13.287 ms/op

Iteration   2: 3.116 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.812 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  6.916 ms/op
                 createUser·p0.9999: 14.212 ms/op
                 createUser·p1.00:   14.418 ms/op

Iteration   3: 3.209 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.682 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.920 ms/op
                 createUser·p0.95:   4.084 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  9.377 ms/op
                 createUser·p0.9999: 28.542 ms/op
                 createUser·p1.00:   28.836 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 304708
  mean =      3.150 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26790 
    [ 2.500,  5.000) = 276346 
    [ 5.000,  7.500) = 1249 
    [ 7.500, 10.000) = 106 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.682 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.018 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =      7.791 ms/op
     p(99.9900) =     27.429 ms/op
     p(99.9990) =     28.770 ms/op
     p(99.9999) =     28.836 ms/op
    p(100.0000) =     28.836 ms/op


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
# Warmup Iteration   1: 4.009 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.196 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.006 ms/op
Iteration   1: 3.010 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.607 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   4.174 ms/op
                 existUser·p0.999:  5.726 ms/op
                 existUser·p0.9999: 12.501 ms/op
                 existUser·p1.00:   12.681 ms/op

Iteration   2: 3.010 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.851 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.826 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  7.296 ms/op
                 existUser·p0.9999: 15.254 ms/op
                 existUser·p1.00:   17.891 ms/op

Iteration   3: 3.052 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.881 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.703 ms/op
                 existUser·p0.95:   3.858 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  6.275 ms/op
                 existUser·p0.9999: 18.022 ms/op
                 existUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 317562
  mean =      3.024 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1144 
    [ 1.250,  2.500) = 39139 
    [ 2.500,  3.750) = 253747 
    [ 3.750,  5.000) = 22736 
    [ 5.000,  6.250) = 425 
    [ 6.250,  7.500) = 184 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.607 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      6.523 ms/op
     p(99.9900) =     16.326 ms/op
     p(99.9990) =     18.121 ms/op
     p(99.9999) =     18.579 ms/op
    p(100.0000) =     18.579 ms/op


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
# Warmup Iteration   1: 4.250 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.231 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.167 ±(99.9%) 0.006 ms/op
Iteration   1: 3.158 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.644 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.809 ms/op
                 getUser·p0.95:   4.014 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  6.680 ms/op
                 getUser·p0.9999: 14.839 ms/op
                 getUser·p1.00:   15.647 ms/op

Iteration   2: 3.062 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.725 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  7.168 ms/op
                 getUser·p0.9999: 13.369 ms/op
                 getUser·p1.00:   16.056 ms/op

Iteration   3: 3.244 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.939 ms/op
                 getUser·p0.50:   3.211 ms/op
                 getUser·p0.90:   3.908 ms/op
                 getUser·p0.95:   4.059 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  8.326 ms/op
                 getUser·p0.9999: 28.054 ms/op
                 getUser·p1.00:   28.443 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 304332
  mean =      3.153 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20892 
    [ 2.500,  5.000) = 282256 
    [ 5.000,  7.500) = 871 
    [ 7.500, 10.000) = 121 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 130 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.644 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.002 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      7.528 ms/op
     p(99.9900) =     27.122 ms/op
     p(99.9990) =     28.277 ms/op
     p(99.9999) =     28.443 ms/op
    p(100.0000) =     28.443 ms/op


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
# Warmup Iteration   1: 5.450 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.141 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.982 ±(99.9%) 0.010 ms/op
Iteration   1: 4.001 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.167 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  12.944 ms/op
                 listUser·p0.9999: 13.877 ms/op
                 listUser·p1.00:   15.188 ms/op

Iteration   2: 3.909 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.120 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.480 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  14.553 ms/op
                 listUser·p0.9999: 16.044 ms/op
                 listUser·p1.00:   17.793 ms/op

Iteration   3: 4.014 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.018 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   6.741 ms/op
                 listUser·p0.999:  17.695 ms/op
                 listUser·p0.9999: 27.592 ms/op
                 listUser·p1.00:   28.508 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241568
  mean =      3.974 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2221 
    [ 2.500,  5.000) = 215692 
    [ 5.000,  7.500) = 22613 
    [ 7.500, 10.000) = 626 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 190 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.018 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.981 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     14.228 ms/op
     p(99.9900) =     26.232 ms/op
     p(99.9990) =     27.850 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.979 ± 2.720  ops/ms
ClientGrpc.existUser                       thrpt       3  10.599 ± 2.842  ops/ms
ClientGrpc.getUser                         thrpt       3   9.871 ± 1.391  ops/ms
ClientGrpc.listUser                        thrpt       3   7.813 ± 2.677  ops/ms
ClientGrpc.createUser                       avgt       3   3.233 ± 0.544   ms/op
ClientGrpc.existUser                        avgt       3   3.050 ± 0.761   ms/op
ClientGrpc.getUser                          avgt       3   3.158 ± 0.614   ms/op
ClientGrpc.listUser                         avgt       3   3.963 ± 0.349   ms/op
ClientGrpc.createUser                     sample  304708   3.150 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.682           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.125           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.826           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.018           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.547           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.791           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.429           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.836           ms/op
ClientGrpc.existUser                      sample  317562   3.024 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.607           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.011           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.666           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.842           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.211           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.523           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.326           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.579           ms/op
ClientGrpc.getUser                        sample  304332   3.153 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.644           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.117           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.813           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.002           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.407           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.528           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.122           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.443           ms/op
ClientGrpc.listUser                       sample  241568   3.974 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.018           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.822           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.981           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.612           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.799           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.228           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.232           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.508           ms/op
