# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.870 ops/ms
# Warmup Iteration   2: 8.750 ops/ms
# Warmup Iteration   3: 9.922 ops/ms
Iteration   1: 10.420 ops/ms
Iteration   2: 10.354 ops/ms
Iteration   3: 9.693 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.156 ±(99.9%) 7.330 ops/ms [Average]
  (min, avg, max) = (9.693, 10.156, 10.420), stdev = 0.402
  CI (99.9%): [2.826, 17.486] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.325 ops/ms
# Warmup Iteration   2: 10.487 ops/ms
# Warmup Iteration   3: 10.413 ops/ms
Iteration   1: 10.658 ops/ms
Iteration   2: 10.839 ops/ms
Iteration   3: 10.721 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.739 ±(99.9%) 1.672 ops/ms [Average]
  (min, avg, max) = (10.658, 10.739, 10.839), stdev = 0.092
  CI (99.9%): [9.067, 12.411] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.184 ops/ms
# Warmup Iteration   2: 10.602 ops/ms
# Warmup Iteration   3: 10.355 ops/ms
Iteration   1: 10.114 ops/ms
Iteration   2: 10.332 ops/ms
Iteration   3: 10.745 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.397 ±(99.9%) 5.843 ops/ms [Average]
  (min, avg, max) = (10.114, 10.397, 10.745), stdev = 0.320
  CI (99.9%): [4.554, 16.241] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.489 ops/ms
# Warmup Iteration   2: 7.897 ops/ms
# Warmup Iteration   3: 7.877 ops/ms
Iteration   1: 7.697 ops/ms
Iteration   2: 7.980 ops/ms
Iteration   3: 8.057 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.911 ±(99.9%) 3.462 ops/ms [Average]
  (min, avg, max) = (7.697, 7.911, 8.057), stdev = 0.190
  CI (99.9%): [4.449, 11.373] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.607 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.270 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.182 ±(99.9%) 0.003 ms/op
Iteration   1: 3.147 ±(99.9%) 0.002 ms/op
Iteration   2: 3.115 ±(99.9%) 0.002 ms/op
Iteration   3: 3.014 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.092 ±(99.9%) 1.268 ms/op [Average]
  (min, avg, max) = (3.014, 3.092, 3.147), stdev = 0.069
  CI (99.9%): [1.824, 4.360] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.727 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.933 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.958 ±(99.9%) 0.002 ms/op
Iteration   1: 3.077 ±(99.9%) 0.002 ms/op
Iteration   2: 2.939 ±(99.9%) 0.002 ms/op
Iteration   3: 3.006 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.007 ±(99.9%) 1.255 ms/op [Average]
  (min, avg, max) = (2.939, 3.007, 3.077), stdev = 0.069
  CI (99.9%): [1.752, 4.263] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.260 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.191 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.134 ±(99.9%) 0.002 ms/op
Iteration   1: 3.138 ±(99.9%) 0.003 ms/op
Iteration   2: 3.208 ±(99.9%) 0.001 ms/op
Iteration   3: 3.100 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.149 ±(99.9%) 1.002 ms/op [Average]
  (min, avg, max) = (3.100, 3.149, 3.208), stdev = 0.055
  CI (99.9%): [2.147, 4.150] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.657 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.135 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.064 ±(99.9%) 0.006 ms/op
Iteration   1: 4.074 ±(99.9%) 0.011 ms/op
Iteration   2: 3.988 ±(99.9%) 0.014 ms/op
Iteration   3: 3.987 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.016 ±(99.9%) 0.913 ms/op [Average]
  (min, avg, max) = (3.987, 4.016, 4.074), stdev = 0.050
  CI (99.9%): [3.103, 4.929] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.536 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.264 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.260 ±(99.9%) 0.008 ms/op
Iteration   1: 3.172 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.824 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.899 ms/op
                 createUser·p0.95:   4.121 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  10.735 ms/op
                 createUser·p0.9999: 14.892 ms/op
                 createUser·p1.00:   15.057 ms/op

Iteration   2: 3.203 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.299 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.928 ms/op
                 createUser·p0.95:   4.112 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  8.962 ms/op
                 createUser·p0.9999: 14.860 ms/op
                 createUser·p1.00:   16.515 ms/op

Iteration   3: 3.137 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.957 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   3.908 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  8.929 ms/op
                 createUser·p0.9999: 31.247 ms/op
                 createUser·p1.00:   31.850 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 303025
  mean =      3.170 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24536 
    [ 2.500,  5.000) = 277396 
    [ 5.000,  7.500) = 684 
    [ 7.500, 10.000) = 133 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.299 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.063 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      9.485 ms/op
     p(99.9900) =     30.399 ms/op
     p(99.9990) =     31.717 ms/op
     p(99.9999) =     31.850 ms/op
    p(100.0000) =     31.850 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.179 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.008 ms/op
Iteration   1: 3.011 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.859 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.760 ms/op
                 existUser·p0.95:   3.920 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  6.611 ms/op
                 existUser·p0.9999: 13.699 ms/op
                 existUser·p1.00:   14.041 ms/op

Iteration   2: 2.979 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.683 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.629 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   4.162 ms/op
                 existUser·p0.999:  7.126 ms/op
                 existUser·p0.9999: 17.408 ms/op
                 existUser·p1.00:   17.891 ms/op

Iteration   3: 3.042 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.562 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.731 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  5.612 ms/op
                 existUser·p0.9999: 17.464 ms/op
                 existUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 318759
  mean =      3.010 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2381 
    [ 1.250,  2.500) = 46382 
    [ 2.500,  3.750) = 242241 
    [ 3.750,  5.000) = 26842 
    [ 5.000,  6.250) = 509 
    [ 6.250,  7.500) = 240 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 50 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.562 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      6.578 ms/op
     p(99.9900) =     17.203 ms/op
     p(99.9990) =     17.885 ms/op
     p(99.9999) =     17.957 ms/op
    p(100.0000) =     17.957 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.289 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.246 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.133 ±(99.9%) 0.007 ms/op
Iteration   1: 3.093 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.846 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  7.366 ms/op
                 getUser·p0.9999: 12.747 ms/op
                 getUser·p1.00:   15.630 ms/op

Iteration   2: 3.148 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.936 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.809 ms/op
                 getUser·p0.95:   3.949 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  6.808 ms/op
                 getUser·p0.9999: 14.956 ms/op
                 getUser·p1.00:   15.335 ms/op

Iteration   3: 3.217 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.645 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.908 ms/op
                 getUser·p0.95:   4.076 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  7.337 ms/op
                 getUser·p0.9999: 18.547 ms/op
                 getUser·p1.00:   19.071 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 304349
  mean =      3.152 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 258 
    [ 1.250,  2.500) = 23016 
    [ 2.500,  3.750) = 244201 
    [ 3.750,  5.000) = 35818 
    [ 5.000,  6.250) = 581 
    [ 6.250,  7.500) = 246 
    [ 7.500,  8.750) = 65 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 38 

  Percentiles, ms/op:
      p(0.0000) =      0.645 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      3.981 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      7.075 ms/op
     p(99.9900) =     18.012 ms/op
     p(99.9990) =     18.739 ms/op
     p(99.9999) =     19.071 ms/op
    p(100.0000) =     19.071 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.696 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.156 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.159 ±(99.9%) 0.012 ms/op
Iteration   1: 4.117 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.438 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   5.980 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  14.554 ms/op
                 listUser·p0.9999: 23.921 ms/op
                 listUser·p1.00:   24.216 ms/op

Iteration   2: 4.017 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.137 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  16.766 ms/op
                 listUser·p0.9999: 23.698 ms/op
                 listUser·p1.00:   24.478 ms/op

Iteration   3: 4.175 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.055 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   5.358 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   7.102 ms/op
                 listUser·p0.999:  18.462 ms/op
                 listUser·p0.9999: 22.883 ms/op
                 listUser·p1.00:   24.510 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 233954
  mean =      4.102 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2094 
    [ 2.500,  5.000) = 202079 
    [ 5.000,  7.500) = 28350 
    [ 7.500, 10.000) = 922 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.055 ms/op
     p(50.0000) =      3.916 ms/op
     p(90.0000) =      5.243 ms/op
     p(95.0000) =      5.890 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     16.355 ms/op
     p(99.9900) =     23.855 ms/op
     p(99.9990) =     24.455 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.156 ± 7.330  ops/ms
ClientGrpc.existUser                       thrpt       3  10.739 ± 1.672  ops/ms
ClientGrpc.getUser                         thrpt       3  10.397 ± 5.843  ops/ms
ClientGrpc.listUser                        thrpt       3   7.911 ± 3.462  ops/ms
ClientGrpc.createUser                       avgt       3   3.092 ± 1.268   ms/op
ClientGrpc.existUser                        avgt       3   3.007 ± 1.255   ms/op
ClientGrpc.getUser                          avgt       3   3.149 ± 1.002   ms/op
ClientGrpc.listUser                         avgt       3   4.016 ± 0.913   ms/op
ClientGrpc.createUser                     sample  303025   3.170 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.299           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.138           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.850           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.063           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.465           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.485           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          30.399           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.850           ms/op
ClientGrpc.existUser                      sample  318759   3.010 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.562           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.031           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.715           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.883           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.202           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.578           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.203           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.957           ms/op
ClientGrpc.getUser                        sample  304349   3.152 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.645           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.121           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.809           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.981           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.075           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.012           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.071           ms/op
ClientGrpc.listUser                       sample  233954   4.102 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.055           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.916           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.243           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.890           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.053           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.355           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.855           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.510           ms/op
