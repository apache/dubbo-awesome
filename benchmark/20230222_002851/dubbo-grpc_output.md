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
# Warmup Iteration   1: 4.086 ops/ms
# Warmup Iteration   2: 8.838 ops/ms
# Warmup Iteration   3: 9.668 ops/ms
Iteration   1: 9.738 ops/ms
Iteration   2: 9.965 ops/ms
Iteration   3: 9.625 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.776 ±(99.9%) 3.160 ops/ms [Average]
  (min, avg, max) = (9.625, 9.776, 9.965), stdev = 0.173
  CI (99.9%): [6.615, 12.936] (assumes normal distribution)


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
# Warmup Iteration   1: 7.816 ops/ms
# Warmup Iteration   2: 10.164 ops/ms
# Warmup Iteration   3: 10.566 ops/ms
Iteration   1: 10.744 ops/ms
Iteration   2: 10.506 ops/ms
Iteration   3: 10.725 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.658 ±(99.9%) 2.407 ops/ms [Average]
  (min, avg, max) = (10.506, 10.658, 10.744), stdev = 0.132
  CI (99.9%): [8.251, 13.065] (assumes normal distribution)


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
# Warmup Iteration   1: 6.557 ops/ms
# Warmup Iteration   2: 9.841 ops/ms
# Warmup Iteration   3: 9.883 ops/ms
Iteration   1: 10.329 ops/ms
Iteration   2: 9.963 ops/ms
Iteration   3: 10.208 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.166 ±(99.9%) 3.400 ops/ms [Average]
  (min, avg, max) = (9.963, 10.166, 10.329), stdev = 0.186
  CI (99.9%): [6.766, 13.567] (assumes normal distribution)


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
# Warmup Iteration   1: 5.013 ops/ms
# Warmup Iteration   2: 7.476 ops/ms
# Warmup Iteration   3: 7.773 ops/ms
Iteration   1: 7.761 ops/ms
Iteration   2: 7.925 ops/ms
Iteration   3: 8.073 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.919 ±(99.9%) 2.849 ops/ms [Average]
  (min, avg, max) = (7.761, 7.919, 8.073), stdev = 0.156
  CI (99.9%): [5.070, 10.769] (assumes normal distribution)


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
# Warmup Iteration   1: 4.559 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.206 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.219 ±(99.9%) 0.001 ms/op
Iteration   1: 3.179 ±(99.9%) 0.002 ms/op
Iteration   2: 3.193 ±(99.9%) 0.002 ms/op
Iteration   3: 3.202 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.192 ±(99.9%) 0.216 ms/op [Average]
  (min, avg, max) = (3.179, 3.192, 3.202), stdev = 0.012
  CI (99.9%): [2.976, 3.407] (assumes normal distribution)


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
# Warmup Iteration   1: 4.201 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.139 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.959 ±(99.9%) 0.003 ms/op
Iteration   1: 3.104 ±(99.9%) 0.002 ms/op
Iteration   2: 3.064 ±(99.9%) 0.002 ms/op
Iteration   3: 3.002 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.057 ±(99.9%) 0.931 ms/op [Average]
  (min, avg, max) = (3.002, 3.057, 3.104), stdev = 0.051
  CI (99.9%): [2.126, 3.987] (assumes normal distribution)


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
# Warmup Iteration   1: 4.195 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.161 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.163 ±(99.9%) 0.003 ms/op
Iteration   1: 3.197 ±(99.9%) 0.002 ms/op
Iteration   2: 3.143 ±(99.9%) 0.003 ms/op
Iteration   3: 3.153 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.164 ±(99.9%) 0.522 ms/op [Average]
  (min, avg, max) = (3.143, 3.164, 3.197), stdev = 0.029
  CI (99.9%): [2.642, 3.686] (assumes normal distribution)


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
# Warmup Iteration   1: 5.623 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.156 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.157 ±(99.9%) 0.073 ms/op
Iteration   1: 4.068 ±(99.9%) 0.021 ms/op
Iteration   2: 4.035 ±(99.9%) 0.009 ms/op
Iteration   3: 4.036 ±(99.9%) 0.041 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.046 ±(99.9%) 0.348 ms/op [Average]
  (min, avg, max) = (4.035, 4.046, 4.068), stdev = 0.019
  CI (99.9%): [3.698, 4.395] (assumes normal distribution)


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
# Warmup Iteration   1: 4.025 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.321 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.126 ±(99.9%) 0.006 ms/op
Iteration   1: 3.165 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.890 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  7.264 ms/op
                 createUser·p0.9999: 14.959 ms/op
                 createUser·p1.00:   15.286 ms/op

Iteration   2: 3.213 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.712 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.903 ms/op
                 createUser·p0.95:   4.108 ms/op
                 createUser·p0.99:   4.645 ms/op
                 createUser·p0.999:  8.602 ms/op
                 createUser·p0.9999: 17.270 ms/op
                 createUser·p1.00:   17.727 ms/op

Iteration   3: 3.236 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.684 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.924 ms/op
                 createUser·p0.95:   4.112 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  9.290 ms/op
                 createUser·p0.9999: 18.291 ms/op
                 createUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 299648
  mean =      3.205 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 377 
    [ 1.250,  2.500) = 21271 
    [ 2.500,  3.750) = 234205 
    [ 3.750,  5.000) = 42440 
    [ 5.000,  6.250) = 650 
    [ 6.250,  7.500) = 309 
    [ 7.500,  8.750) = 119 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 65 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 41 
    [17.500, 18.750) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.684 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.067 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      8.552 ms/op
     p(99.9900) =     17.565 ms/op
     p(99.9990) =     18.645 ms/op
     p(99.9999) =     18.743 ms/op
    p(100.0000) =     18.743 ms/op


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
# Warmup Iteration   1: 4.153 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.195 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.083 ±(99.9%) 0.006 ms/op
Iteration   1: 3.029 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.857 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   3.920 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  6.857 ms/op
                 existUser·p0.9999: 12.679 ms/op
                 existUser·p1.00:   13.074 ms/op

Iteration   2: 3.067 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.828 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.760 ms/op
                 existUser·p0.95:   3.981 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  6.354 ms/op
                 existUser·p0.9999: 13.954 ms/op
                 existUser·p1.00:   14.320 ms/op

Iteration   3: 2.933 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.514 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.588 ms/op
                 existUser·p0.999:  10.009 ms/op
                 existUser·p0.9999: 18.547 ms/op
                 existUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 319079
  mean =      3.009 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1235 
    [ 1.250,  2.500) = 41500 
    [ 2.500,  3.750) = 251749 
    [ 3.750,  5.000) = 23490 
    [ 5.000,  6.250) = 595 
    [ 6.250,  7.500) = 274 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 42 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.514 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      6.881 ms/op
     p(99.9900) =     17.808 ms/op
     p(99.9990) =     18.743 ms/op
     p(99.9999) =     19.530 ms/op
    p(100.0000) =     19.530 ms/op


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
# Warmup Iteration   1: 4.410 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.257 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.141 ±(99.9%) 0.006 ms/op
Iteration   1: 3.164 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.904 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.838 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  8.436 ms/op
                 getUser·p0.9999: 14.789 ms/op
                 getUser·p1.00:   15.696 ms/op

Iteration   2: 3.143 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.864 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  7.504 ms/op
                 getUser·p0.9999: 14.524 ms/op
                 getUser·p1.00:   14.959 ms/op

Iteration   3: 3.138 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.771 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.834 ms/op
                 getUser·p0.95:   4.006 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  6.267 ms/op
                 getUser·p0.9999: 14.811 ms/op
                 getUser·p1.00:   16.482 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 304755
  mean =      3.148 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 608 
    [ 1.250,  2.500) = 22475 
    [ 2.500,  3.750) = 245844 
    [ 3.750,  5.000) = 34544 
    [ 5.000,  6.250) = 722 
    [ 6.250,  7.500) = 257 
    [ 7.500,  8.750) = 94 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 77 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.771 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      7.504 ms/op
     p(99.9900) =     14.754 ms/op
     p(99.9990) =     15.630 ms/op
     p(99.9999) =     16.482 ms/op
    p(100.0000) =     16.482 ms/op


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
# Warmup Iteration   1: 4.536 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.505 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.065 ±(99.9%) 0.011 ms/op
Iteration   1: 4.105 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.440 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   5.333 ms/op
                 listUser·p0.95:   6.038 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  13.581 ms/op
                 listUser·p0.9999: 15.037 ms/op
                 listUser·p1.00:   15.991 ms/op

Iteration   2: 4.109 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.360 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   7.225 ms/op
                 listUser·p0.999:  16.117 ms/op
                 listUser·p0.9999: 18.823 ms/op
                 listUser·p1.00:   19.562 ms/op

Iteration   3: 4.172 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.133 ms/op
                 listUser·p0.50:   3.965 ms/op
                 listUser·p0.90:   5.292 ms/op
                 listUser·p0.95:   5.857 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  16.564 ms/op
                 listUser·p0.9999: 20.599 ms/op
                 listUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 232701
  mean =      4.128 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1391 
    [ 2.500,  5.000) = 200738 
    [ 5.000,  7.500) = 29076 
    [ 7.500, 10.000) = 1040 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 162 
    [15.000, 17.500) = 144 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.133 ms/op
     p(50.0000) =      3.932 ms/op
     p(90.0000) =      5.276 ms/op
     p(95.0000) =      5.915 ms/op
     p(99.0000) =      7.143 ms/op
     p(99.9000) =     14.782 ms/op
     p(99.9900) =     19.075 ms/op
     p(99.9990) =     21.038 ms/op
     p(99.9999) =     21.168 ms/op
    p(100.0000) =     21.168 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.776 ± 3.160  ops/ms
ClientGrpc.existUser                       thrpt       3  10.658 ± 2.407  ops/ms
ClientGrpc.getUser                         thrpt       3  10.166 ± 3.400  ops/ms
ClientGrpc.listUser                        thrpt       3   7.919 ± 2.849  ops/ms
ClientGrpc.createUser                       avgt       3   3.192 ± 0.216   ms/op
ClientGrpc.existUser                        avgt       3   3.057 ± 0.931   ms/op
ClientGrpc.getUser                          avgt       3   3.164 ± 0.522   ms/op
ClientGrpc.listUser                         avgt       3   4.046 ± 0.348   ms/op
ClientGrpc.createUser                     sample  299648   3.205 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.684           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.178           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.875           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.067           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.465           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.552           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.565           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.743           ms/op
ClientGrpc.existUser                      sample  319079   3.009 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.514           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.986           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.662           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.887           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.366           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.881           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.808           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.530           ms/op
ClientGrpc.getUser                        sample  304755   3.148 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.771           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.129           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.797           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.977           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.456           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.504           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.754           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.482           ms/op
ClientGrpc.listUser                       sample  232701   4.128 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.133           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.932           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.276           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.915           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.143           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.782           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.075           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.168           ms/op
