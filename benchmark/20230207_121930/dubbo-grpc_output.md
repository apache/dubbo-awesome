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
# Warmup Iteration   1: 4.234 ops/ms
# Warmup Iteration   2: 9.187 ops/ms
# Warmup Iteration   3: 9.949 ops/ms
Iteration   1: 9.893 ops/ms
Iteration   2: 10.110 ops/ms
Iteration   3: 10.061 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.022 ±(99.9%) 2.078 ops/ms [Average]
  (min, avg, max) = (9.893, 10.022, 10.110), stdev = 0.114
  CI (99.9%): [7.944, 12.099] (assumes normal distribution)


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
# Warmup Iteration   1: 7.783 ops/ms
# Warmup Iteration   2: 10.270 ops/ms
# Warmup Iteration   3: 10.653 ops/ms
Iteration   1: 10.590 ops/ms
Iteration   2: 10.535 ops/ms
Iteration   3: 10.538 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.555 ±(99.9%) 0.563 ops/ms [Average]
  (min, avg, max) = (10.535, 10.555, 10.590), stdev = 0.031
  CI (99.9%): [9.992, 11.117] (assumes normal distribution)


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
# Warmup Iteration   1: 6.937 ops/ms
# Warmup Iteration   2: 10.251 ops/ms
# Warmup Iteration   3: 10.158 ops/ms
Iteration   1: 10.070 ops/ms
Iteration   2: 10.171 ops/ms
Iteration   3: 10.107 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.116 ±(99.9%) 0.930 ops/ms [Average]
  (min, avg, max) = (10.070, 10.116, 10.171), stdev = 0.051
  CI (99.9%): [9.186, 11.046] (assumes normal distribution)


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
# Warmup Iteration   1: 5.626 ops/ms
# Warmup Iteration   2: 7.472 ops/ms
# Warmup Iteration   3: 7.671 ops/ms
Iteration   1: 7.829 ops/ms
Iteration   2: 7.928 ops/ms
Iteration   3: 7.858 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.872 ±(99.9%) 0.927 ops/ms [Average]
  (min, avg, max) = (7.829, 7.872, 7.928), stdev = 0.051
  CI (99.9%): [6.945, 8.798] (assumes normal distribution)


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
# Warmup Iteration   1: 4.285 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.177 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.159 ±(99.9%) 0.003 ms/op
Iteration   1: 3.028 ±(99.9%) 0.002 ms/op
Iteration   2: 3.112 ±(99.9%) 0.003 ms/op
Iteration   3: 3.180 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.107 ±(99.9%) 1.385 ms/op [Average]
  (min, avg, max) = (3.028, 3.107, 3.180), stdev = 0.076
  CI (99.9%): [1.722, 4.492] (assumes normal distribution)


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
# Warmup Iteration   1: 4.034 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.249 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.003 ms/op
Iteration   1: 3.105 ±(99.9%) 0.001 ms/op
Iteration   2: 3.049 ±(99.9%) 0.002 ms/op
Iteration   3: 3.009 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.054 ±(99.9%) 0.878 ms/op [Average]
  (min, avg, max) = (3.009, 3.054, 3.105), stdev = 0.048
  CI (99.9%): [2.177, 3.932] (assumes normal distribution)


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
# Warmup Iteration   1: 4.188 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.266 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.175 ±(99.9%) 0.002 ms/op
Iteration   1: 3.153 ±(99.9%) 0.002 ms/op
Iteration   2: 3.180 ±(99.9%) 0.002 ms/op
Iteration   3: 3.182 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.172 ±(99.9%) 0.299 ms/op [Average]
  (min, avg, max) = (3.153, 3.172, 3.182), stdev = 0.016
  CI (99.9%): [2.873, 3.471] (assumes normal distribution)


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
# Warmup Iteration   1: 5.180 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.191 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.092 ±(99.9%) 0.009 ms/op
Iteration   1: 4.123 ±(99.9%) 0.015 ms/op
Iteration   2: 4.088 ±(99.9%) 0.008 ms/op
Iteration   3: 4.127 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.113 ±(99.9%) 0.390 ms/op [Average]
  (min, avg, max) = (4.088, 4.113, 4.127), stdev = 0.021
  CI (99.9%): [3.722, 4.503] (assumes normal distribution)


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
# Warmup Iteration   1: 4.161 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.274 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.141 ±(99.9%) 0.008 ms/op
Iteration   1: 3.179 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.935 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.850 ms/op
                 createUser·p0.95:   4.063 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  7.135 ms/op
                 createUser·p0.9999: 14.988 ms/op
                 createUser·p1.00:   15.745 ms/op

Iteration   2: 3.208 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.658 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.883 ms/op
                 createUser·p0.95:   4.043 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  10.043 ms/op
                 createUser·p0.9999: 17.859 ms/op
                 createUser·p1.00:   18.055 ms/op

Iteration   3: 3.185 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.752 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.830 ms/op
                 createUser·p0.95:   4.071 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  12.162 ms/op
                 createUser·p0.9999: 20.378 ms/op
                 createUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 300957
  mean =      3.190 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18029 
    [ 2.500,  5.000) = 281582 
    [ 5.000,  7.500) = 918 
    [ 7.500, 10.000) = 113 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.658 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =     10.437 ms/op
     p(99.9900) =     19.199 ms/op
     p(99.9990) =     20.709 ms/op
     p(99.9999) =     20.840 ms/op
    p(100.0000) =     20.840 ms/op


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
# Warmup Iteration   1: 4.017 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.087 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.006 ms/op
Iteration   1: 3.057 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.775 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.772 ms/op
                 existUser·p0.95:   3.949 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  8.713 ms/op
                 existUser·p0.9999: 15.131 ms/op
                 existUser·p1.00:   15.335 ms/op

Iteration   2: 3.101 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.897 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.785 ms/op
                 existUser·p0.95:   3.936 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  6.477 ms/op
                 existUser·p0.9999: 15.740 ms/op
                 existUser·p1.00:   16.335 ms/op

Iteration   3: 3.034 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.695 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   4.092 ms/op
                 existUser·p0.999:  6.599 ms/op
                 existUser·p0.9999: 15.802 ms/op
                 existUser·p1.00:   16.630 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 313416
  mean =      3.064 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 993 
    [ 1.250,  2.500) = 37282 
    [ 2.500,  3.750) = 244572 
    [ 3.750,  5.000) = 29732 
    [ 5.000,  6.250) = 355 
    [ 6.250,  7.500) = 212 
    [ 7.500,  8.750) = 71 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 41 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.695 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      7.201 ms/op
     p(99.9900) =     15.379 ms/op
     p(99.9990) =     16.492 ms/op
     p(99.9999) =     16.630 ms/op
    p(100.0000) =     16.630 ms/op


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
# Warmup Iteration   1: 4.102 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.133 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.232 ±(99.9%) 0.007 ms/op
Iteration   1: 3.183 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.892 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.867 ms/op
                 getUser·p0.95:   4.043 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  9.168 ms/op
                 getUser·p0.9999: 14.530 ms/op
                 getUser·p1.00:   14.778 ms/op

Iteration   2: 3.131 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.977 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   4.014 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  6.365 ms/op
                 getUser·p0.9999: 14.371 ms/op
                 getUser·p1.00:   14.680 ms/op

Iteration   3: 3.130 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.642 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   3.953 ms/op
                 getUser·p0.99:   4.404 ms/op
                 getUser·p0.999:  8.748 ms/op
                 getUser·p0.9999: 22.348 ms/op
                 getUser·p1.00:   22.970 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 304817
  mean =      3.148 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24759 
    [ 2.500,  5.000) = 278968 
    [ 5.000,  7.500) = 769 
    [ 7.500, 10.000) = 111 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.642 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.010 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      7.703 ms/op
     p(99.9900) =     21.989 ms/op
     p(99.9990) =     22.803 ms/op
     p(99.9999) =     22.970 ms/op
    p(100.0000) =     22.970 ms/op


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
# Warmup Iteration   1: 5.094 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.182 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.056 ±(99.9%) 0.011 ms/op
Iteration   1: 4.080 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.374 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  13.454 ms/op
                 listUser·p0.9999: 14.783 ms/op
                 listUser·p1.00:   15.188 ms/op

Iteration   2: 4.083 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.046 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.906 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  15.035 ms/op
                 listUser·p0.9999: 16.990 ms/op
                 listUser·p1.00:   18.842 ms/op

Iteration   3: 4.066 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.083 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   5.072 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   6.891 ms/op
                 listUser·p0.999:  21.965 ms/op
                 listUser·p0.9999: 26.092 ms/op
                 listUser·p1.00:   26.870 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235435
  mean =      4.076 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1881 
    [ 2.500,  5.000) = 207295 
    [ 5.000,  7.500) = 25039 
    [ 7.500, 10.000) = 820 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 152 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.046 ms/op
     p(50.0000) =      3.916 ms/op
     p(90.0000) =      5.112 ms/op
     p(95.0000) =      5.792 ms/op
     p(99.0000) =      6.936 ms/op
     p(99.9000) =     14.575 ms/op
     p(99.9900) =     25.625 ms/op
     p(99.9990) =     26.421 ms/op
     p(99.9999) =     26.870 ms/op
    p(100.0000) =     26.870 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.022 ± 2.078  ops/ms
ClientGrpc.existUser                       thrpt       3  10.555 ± 0.563  ops/ms
ClientGrpc.getUser                         thrpt       3  10.116 ± 0.930  ops/ms
ClientGrpc.listUser                        thrpt       3   7.872 ± 0.927  ops/ms
ClientGrpc.createUser                       avgt       3   3.107 ± 1.385   ms/op
ClientGrpc.existUser                        avgt       3   3.054 ± 0.878   ms/op
ClientGrpc.getUser                          avgt       3   3.172 ± 0.299   ms/op
ClientGrpc.listUser                         avgt       3   4.113 ± 0.390   ms/op
ClientGrpc.createUser                     sample  300957   3.190 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.658           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.146           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.858           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.055           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.437           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.199           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.840           ms/op
ClientGrpc.existUser                      sample  313416   3.064 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.695           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.035           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.744           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.908           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.201           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.379           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.630           ms/op
ClientGrpc.getUser                        sample  304817   3.148 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.642           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.125           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.813           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.010           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.383           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.703           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.989           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.970           ms/op
ClientGrpc.listUser                       sample  235435   4.076 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.046           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.916           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.112           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.792           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.936           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.575           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.625           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.870           ms/op
