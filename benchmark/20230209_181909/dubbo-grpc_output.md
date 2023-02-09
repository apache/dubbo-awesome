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
# Warmup Iteration   1: 4.891 ops/ms
# Warmup Iteration   2: 9.328 ops/ms
# Warmup Iteration   3: 10.190 ops/ms
Iteration   1: 10.573 ops/ms
Iteration   2: 10.198 ops/ms
Iteration   3: 10.270 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.347 ±(99.9%) 3.630 ops/ms [Average]
  (min, avg, max) = (10.198, 10.347, 10.573), stdev = 0.199
  CI (99.9%): [6.717, 13.977] (assumes normal distribution)


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
# Warmup Iteration   1: 8.072 ops/ms
# Warmup Iteration   2: 10.681 ops/ms
# Warmup Iteration   3: 11.102 ops/ms
Iteration   1: 10.949 ops/ms
Iteration   2: 10.746 ops/ms
Iteration   3: 10.773 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.823 ±(99.9%) 2.016 ops/ms [Average]
  (min, avg, max) = (10.746, 10.823, 10.949), stdev = 0.110
  CI (99.9%): [8.807, 12.838] (assumes normal distribution)


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
# Warmup Iteration   1: 7.623 ops/ms
# Warmup Iteration   2: 10.517 ops/ms
# Warmup Iteration   3: 10.750 ops/ms
Iteration   1: 10.324 ops/ms
Iteration   2: 10.307 ops/ms
Iteration   3: 10.781 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.470 ±(99.9%) 4.905 ops/ms [Average]
  (min, avg, max) = (10.307, 10.470, 10.781), stdev = 0.269
  CI (99.9%): [5.566, 15.375] (assumes normal distribution)


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
# Warmup Iteration   1: 6.731 ops/ms
# Warmup Iteration   2: 7.869 ops/ms
# Warmup Iteration   3: 8.002 ops/ms
Iteration   1: 8.180 ops/ms
Iteration   2: 8.236 ops/ms
Iteration   3: 8.214 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.210 ±(99.9%) 0.512 ops/ms [Average]
  (min, avg, max) = (8.180, 8.210, 8.236), stdev = 0.028
  CI (99.9%): [7.698, 8.722] (assumes normal distribution)


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
# Warmup Iteration   1: 4.068 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.108 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.002 ms/op
Iteration   1: 3.025 ±(99.9%) 0.002 ms/op
Iteration   2: 3.138 ±(99.9%) 0.002 ms/op
Iteration   3: 3.126 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.096 ±(99.9%) 1.135 ms/op [Average]
  (min, avg, max) = (3.025, 3.096, 3.138), stdev = 0.062
  CI (99.9%): [1.961, 4.231] (assumes normal distribution)


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
# Warmup Iteration   1: 3.791 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.020 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.939 ±(99.9%) 0.003 ms/op
Iteration   1: 2.984 ±(99.9%) 0.002 ms/op
Iteration   2: 2.999 ±(99.9%) 0.002 ms/op
Iteration   3: 2.871 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.952 ±(99.9%) 1.276 ms/op [Average]
  (min, avg, max) = (2.871, 2.952, 2.999), stdev = 0.070
  CI (99.9%): [1.676, 4.227] (assumes normal distribution)


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
# Warmup Iteration   1: 3.992 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.159 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.003 ms/op
Iteration   1: 3.086 ±(99.9%) 0.002 ms/op
Iteration   2: 3.022 ±(99.9%) 0.003 ms/op
Iteration   3: 3.002 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.037 ±(99.9%) 0.804 ms/op [Average]
  (min, avg, max) = (3.002, 3.037, 3.086), stdev = 0.044
  CI (99.9%): [2.232, 3.841] (assumes normal distribution)


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
# Warmup Iteration   1: 5.036 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.070 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.991 ±(99.9%) 0.037 ms/op
Iteration   1: 3.947 ±(99.9%) 0.024 ms/op
Iteration   2: 3.943 ±(99.9%) 0.043 ms/op
Iteration   3: 3.907 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.932 ±(99.9%) 0.399 ms/op [Average]
  (min, avg, max) = (3.907, 3.932, 3.947), stdev = 0.022
  CI (99.9%): [3.533, 4.331] (assumes normal distribution)


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
# Warmup Iteration   1: 3.843 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.125 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.099 ±(99.9%) 0.006 ms/op
Iteration   1: 3.127 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.765 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.026 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  8.085 ms/op
                 createUser·p0.9999: 11.518 ms/op
                 createUser·p1.00:   11.747 ms/op

Iteration   2: 3.101 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.766 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.817 ms/op
                 createUser·p0.95:   4.006 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  6.832 ms/op
                 createUser·p0.9999: 20.447 ms/op
                 createUser·p1.00:   20.873 ms/op

Iteration   3: 3.127 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.583 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  15.169 ms/op
                 createUser·p0.9999: 22.774 ms/op
                 createUser·p1.00:   22.905 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307922
  mean =      3.118 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27462 
    [ 2.500,  5.000) = 279505 
    [ 5.000,  7.500) = 572 
    [ 7.500, 10.000) = 126 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.583 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      9.339 ms/op
     p(99.9900) =     22.512 ms/op
     p(99.9990) =     22.872 ms/op
     p(99.9999) =     22.905 ms/op
    p(100.0000) =     22.905 ms/op


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
# Warmup Iteration   1: 3.775 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.055 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.984 ±(99.9%) 0.006 ms/op
Iteration   1: 2.950 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.534 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   4.063 ms/op
                 existUser·p0.999:  5.710 ms/op
                 existUser·p0.9999: 11.750 ms/op
                 existUser·p1.00:   12.009 ms/op

Iteration   2: 3.042 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.767 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   4.084 ms/op
                 existUser·p0.999:  5.069 ms/op
                 existUser·p0.9999: 12.811 ms/op
                 existUser·p1.00:   13.304 ms/op

Iteration   3: 3.031 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.651 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.662 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   4.100 ms/op
                 existUser·p0.999:  7.505 ms/op
                 existUser·p0.9999: 22.294 ms/op
                 existUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 319100
  mean =      3.007 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33918 
    [ 2.500,  5.000) = 284591 
    [ 5.000,  7.500) = 386 
    [ 7.500, 10.000) = 33 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.534 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.084 ms/op
     p(99.9000) =      5.962 ms/op
     p(99.9900) =     20.251 ms/op
     p(99.9990) =     22.708 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


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
# Warmup Iteration   1: 4.037 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.223 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.112 ±(99.9%) 0.007 ms/op
Iteration   1: 3.013 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.594 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  6.857 ms/op
                 getUser·p0.9999: 18.153 ms/op
                 getUser·p1.00:   20.906 ms/op

Iteration   2: 3.099 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.874 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  6.425 ms/op
                 getUser·p0.9999: 13.233 ms/op
                 getUser·p1.00:   13.468 ms/op

Iteration   3: 3.164 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.726 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.895 ms/op
                 getUser·p0.95:   4.063 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  7.749 ms/op
                 getUser·p0.9999: 21.430 ms/op
                 getUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310457
  mean =      3.091 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28852 
    [ 2.500,  5.000) = 280729 
    [ 5.000,  7.500) = 635 
    [ 7.500, 10.000) = 47 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.594 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      6.775 ms/op
     p(99.9900) =     20.742 ms/op
     p(99.9990) =     21.820 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


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
# Warmup Iteration   1: 4.446 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.076 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.066 ±(99.9%) 0.012 ms/op
Iteration   1: 4.045 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.915 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   5.284 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  13.483 ms/op
                 listUser·p0.9999: 18.461 ms/op
                 listUser·p1.00:   18.907 ms/op

Iteration   2: 4.035 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.145 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   5.431 ms/op
                 listUser·p0.95:   5.980 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  14.816 ms/op
                 listUser·p0.9999: 18.743 ms/op
                 listUser·p1.00:   19.464 ms/op

Iteration   3: 3.925 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.149 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  14.565 ms/op
                 listUser·p0.9999: 17.997 ms/op
                 listUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239832
  mean =      4.001 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 12 
    [ 1.250,  2.500) = 5708 
    [ 2.500,  3.750) = 107448 
    [ 3.750,  5.000) = 91642 
    [ 5.000,  6.250) = 29265 
    [ 6.250,  7.500) = 4655 
    [ 7.500,  8.750) = 543 
    [ 8.750, 10.000) = 112 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 48 
    [12.500, 13.750) = 94 
    [13.750, 15.000) = 130 
    [15.000, 16.250) = 39 
    [16.250, 17.500) = 69 
    [17.500, 18.750) = 45 

  Percentiles, ms/op:
      p(0.0000) =      0.915 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      5.325 ms/op
     p(95.0000) =      5.857 ms/op
     p(99.0000) =      6.750 ms/op
     p(99.9000) =     14.254 ms/op
     p(99.9900) =     18.285 ms/op
     p(99.9990) =     19.045 ms/op
     p(99.9999) =     19.464 ms/op
    p(100.0000) =     19.464 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.347 ± 3.630  ops/ms
ClientGrpc.existUser                       thrpt       3  10.823 ± 2.016  ops/ms
ClientGrpc.getUser                         thrpt       3  10.470 ± 4.905  ops/ms
ClientGrpc.listUser                        thrpt       3   8.210 ± 0.512  ops/ms
ClientGrpc.createUser                       avgt       3   3.096 ± 1.135   ms/op
ClientGrpc.existUser                        avgt       3   2.952 ± 1.276   ms/op
ClientGrpc.getUser                          avgt       3   3.037 ± 0.804   ms/op
ClientGrpc.listUser                         avgt       3   3.932 ± 0.399   ms/op
ClientGrpc.createUser                     sample  307922   3.118 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.583           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.097           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.817           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.998           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.317           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.339           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.512           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.905           ms/op
ClientGrpc.existUser                      sample  319100   3.007 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.534           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.990           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.629           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.801           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.084           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           5.962           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.251           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.298           ms/op
ClientGrpc.getUser                        sample  310457   3.091 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.594           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.080           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.789           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.998           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.366           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.775           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.742           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.889           ms/op
ClientGrpc.listUser                       sample  239832   4.001 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.915           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.789           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.325           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.857           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.750           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.254           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.285           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.464           ms/op
