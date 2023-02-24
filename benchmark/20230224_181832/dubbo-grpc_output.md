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
# Warmup Iteration   1: 4.792 ops/ms
# Warmup Iteration   2: 9.592 ops/ms
# Warmup Iteration   3: 10.492 ops/ms
Iteration   1: 10.616 ops/ms
Iteration   2: 10.685 ops/ms
Iteration   3: 10.377 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.559 ±(99.9%) 2.953 ops/ms [Average]
  (min, avg, max) = (10.377, 10.559, 10.685), stdev = 0.162
  CI (99.9%): [7.607, 13.512] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 8.165 ops/ms
# Warmup Iteration   2: 10.877 ops/ms
# Warmup Iteration   3: 10.723 ops/ms
Iteration   1: 11.289 ops/ms
Iteration   2: 11.247 ops/ms
Iteration   3: 10.748 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.095 ±(99.9%) 5.495 ops/ms [Average]
  (min, avg, max) = (10.748, 11.095, 11.289), stdev = 0.301
  CI (99.9%): [5.600, 16.589] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.132 ops/ms
# Warmup Iteration   2: 10.147 ops/ms
# Warmup Iteration   3: 10.655 ops/ms
Iteration   1: 10.203 ops/ms
Iteration   2: 10.274 ops/ms
Iteration   3: 10.417 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.298 ±(99.9%) 1.987 ops/ms [Average]
  (min, avg, max) = (10.203, 10.298, 10.417), stdev = 0.109
  CI (99.9%): [8.311, 12.286] (assumes normal distribution)


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
# Warmup Iteration   1: 5.980 ops/ms
# Warmup Iteration   2: 7.707 ops/ms
# Warmup Iteration   3: 7.898 ops/ms
Iteration   1: 8.179 ops/ms
Iteration   2: 7.746 ops/ms
Iteration   3: 7.993 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.972 ±(99.9%) 3.966 ops/ms [Average]
  (min, avg, max) = (7.746, 7.972, 8.179), stdev = 0.217
  CI (99.9%): [4.006, 11.939] (assumes normal distribution)


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
# Warmup Iteration   1: 4.008 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.108 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.003 ms/op
Iteration   1: 3.055 ±(99.9%) 0.002 ms/op
Iteration   2: 3.100 ±(99.9%) 0.002 ms/op
Iteration   3: 3.124 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.093 ±(99.9%) 0.643 ms/op [Average]
  (min, avg, max) = (3.055, 3.093, 3.124), stdev = 0.035
  CI (99.9%): [2.450, 3.736] (assumes normal distribution)


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
# Warmup Iteration   1: 3.860 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.063 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.879 ±(99.9%) 0.003 ms/op
Iteration   1: 2.954 ±(99.9%) 0.003 ms/op
Iteration   2: 3.003 ±(99.9%) 0.002 ms/op
Iteration   3: 2.959 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.972 ±(99.9%) 0.489 ms/op [Average]
  (min, avg, max) = (2.954, 2.972, 3.003), stdev = 0.027
  CI (99.9%): [2.483, 3.461] (assumes normal distribution)


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
# Warmup Iteration   1: 3.836 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.095 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.977 ±(99.9%) 0.003 ms/op
Iteration   1: 3.087 ±(99.9%) 0.003 ms/op
Iteration   2: 3.028 ±(99.9%) 0.003 ms/op
Iteration   3: 3.036 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.050 ±(99.9%) 0.582 ms/op [Average]
  (min, avg, max) = (3.028, 3.050, 3.087), stdev = 0.032
  CI (99.9%): [2.468, 3.632] (assumes normal distribution)


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
# Warmup Iteration   1: 4.415 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.138 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.969 ±(99.9%) 0.031 ms/op
Iteration   1: 4.025 ±(99.9%) 0.007 ms/op
Iteration   2: 3.901 ±(99.9%) 0.006 ms/op
Iteration   3: 4.032 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.986 ±(99.9%) 1.345 ms/op [Average]
  (min, avg, max) = (3.901, 3.986, 4.032), stdev = 0.074
  CI (99.9%): [2.641, 5.331] (assumes normal distribution)


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
# Warmup Iteration   1: 4.050 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.161 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.085 ±(99.9%) 0.007 ms/op
Iteration   1: 3.143 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.738 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   3.944 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  6.287 ms/op
                 createUser·p0.9999: 16.168 ms/op
                 createUser·p1.00:   16.712 ms/op

Iteration   2: 3.196 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.666 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.903 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  14.598 ms/op
                 createUser·p0.9999: 17.531 ms/op
                 createUser·p1.00:   17.629 ms/op

Iteration   3: 3.074 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.230 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.092 ms/op
                 createUser·p0.999:  9.519 ms/op
                 createUser·p0.9999: 21.660 ms/op
                 createUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 306157
  mean =      3.136 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22225 
    [ 2.500,  5.000) = 282953 
    [ 5.000,  7.500) = 506 
    [ 7.500, 10.000) = 153 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 124 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.230 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =     10.467 ms/op
     p(99.9900) =     20.984 ms/op
     p(99.9990) =     21.758 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


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
# Warmup Iteration   1: 3.835 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.091 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.942 ±(99.9%) 0.007 ms/op
Iteration   1: 2.944 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.701 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  6.983 ms/op
                 existUser·p0.9999: 12.159 ms/op
                 existUser·p1.00:   12.599 ms/op

Iteration   2: 3.026 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.743 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   3.863 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  7.032 ms/op
                 existUser·p0.9999: 15.363 ms/op
                 existUser·p1.00:   16.761 ms/op

Iteration   3: 3.040 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.722 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   3.895 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  6.529 ms/op
                 existUser·p0.9999: 14.844 ms/op
                 existUser·p1.00:   15.270 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 319548
  mean =      3.003 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2146 
    [ 1.250,  2.500) = 42849 
    [ 2.500,  3.750) = 250104 
    [ 3.750,  5.000) = 23708 
    [ 5.000,  6.250) = 300 
    [ 6.250,  7.500) = 194 
    [ 7.500,  8.750) = 45 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 48 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.701 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      6.836 ms/op
     p(99.9900) =     14.927 ms/op
     p(99.9990) =     16.505 ms/op
     p(99.9999) =     16.761 ms/op
    p(100.0000) =     16.761 ms/op


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
# Warmup Iteration   1: 3.790 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.118 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.006 ms/op
Iteration   1: 3.075 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.754 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  6.775 ms/op
                 getUser·p0.9999: 11.957 ms/op
                 getUser·p1.00:   12.255 ms/op

Iteration   2: 3.125 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.870 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  7.176 ms/op
                 getUser·p0.9999: 13.697 ms/op
                 getUser·p1.00:   13.943 ms/op

Iteration   3: 3.108 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.614 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   3.953 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  6.112 ms/op
                 getUser·p0.9999: 14.557 ms/op
                 getUser·p1.00:   15.401 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309320
  mean =      3.102 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 857 
    [ 1.250,  2.500) = 21779 
    [ 2.500,  3.750) = 256960 
    [ 3.750,  5.000) = 28933 
    [ 5.000,  6.250) = 401 
    [ 6.250,  7.500) = 151 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.614 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      6.674 ms/op
     p(99.9900) =     13.585 ms/op
     p(99.9990) =     15.279 ms/op
     p(99.9999) =     15.401 ms/op
    p(100.0000) =     15.401 ms/op


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
# Warmup Iteration   1: 4.931 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.125 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.077 ±(99.9%) 0.012 ms/op
Iteration   1: 3.940 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.651 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  15.647 ms/op
                 listUser·p0.9999: 20.476 ms/op
                 listUser·p1.00:   22.151 ms/op

Iteration   2: 3.955 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.023 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   5.001 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  16.616 ms/op
                 listUser·p0.9999: 25.482 ms/op
                 listUser·p1.00:   26.051 ms/op

Iteration   3: 3.949 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.843 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  14.640 ms/op
                 listUser·p0.9999: 21.230 ms/op
                 listUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243320
  mean =      3.948 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3495 
    [ 2.500,  5.000) = 216998 
    [ 5.000,  7.500) = 21663 
    [ 7.500, 10.000) = 758 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 159 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.651 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.948 ms/op
     p(95.0000) =      5.562 ms/op
     p(99.0000) =      6.758 ms/op
     p(99.9000) =     15.854 ms/op
     p(99.9900) =     23.801 ms/op
     p(99.9990) =     25.924 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.559 ± 2.953  ops/ms
ClientGrpc.existUser                       thrpt       3  11.095 ± 5.495  ops/ms
ClientGrpc.getUser                         thrpt       3  10.298 ± 1.987  ops/ms
ClientGrpc.listUser                        thrpt       3   7.972 ± 3.966  ops/ms
ClientGrpc.createUser                       avgt       3   3.093 ± 0.643   ms/op
ClientGrpc.existUser                        avgt       3   2.972 ± 0.489   ms/op
ClientGrpc.getUser                          avgt       3   3.050 ± 0.582   ms/op
ClientGrpc.listUser                         avgt       3   3.986 ± 1.345   ms/op
ClientGrpc.createUser                     sample  306157   3.136 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.230           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.101           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.777           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.953           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.293           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.467           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.984           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.217           ms/op
ClientGrpc.existUser                      sample  319548   3.003 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.701           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.986           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.678           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.858           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.235           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.836           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.927           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.761           ms/op
ClientGrpc.getUser                        sample  309320   3.102 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.614           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.084           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.736           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.932           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.268           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.674           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          13.585           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          15.401           ms/op
ClientGrpc.listUser                       sample  243320   3.948 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.651           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.797           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.948           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.562           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.758           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.854           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.801           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.051           ms/op
