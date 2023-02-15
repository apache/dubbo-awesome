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
# Warmup Iteration   2: 9.104 ops/ms
# Warmup Iteration   3: 9.971 ops/ms
Iteration   1: 9.850 ops/ms
Iteration   2: 9.877 ops/ms
Iteration   3: 9.994 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.907 ±(99.9%) 1.402 ops/ms [Average]
  (min, avg, max) = (9.850, 9.907, 9.994), stdev = 0.077
  CI (99.9%): [8.505, 11.309] (assumes normal distribution)


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
# Warmup Iteration   1: 8.115 ops/ms
# Warmup Iteration   2: 10.291 ops/ms
# Warmup Iteration   3: 10.653 ops/ms
Iteration   1: 10.165 ops/ms
Iteration   2: 10.386 ops/ms
Iteration   3: 10.679 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.410 ±(99.9%) 4.709 ops/ms [Average]
  (min, avg, max) = (10.165, 10.410, 10.679), stdev = 0.258
  CI (99.9%): [5.701, 15.119] (assumes normal distribution)


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
# Warmup Iteration   1: 6.257 ops/ms
# Warmup Iteration   2: 10.067 ops/ms
# Warmup Iteration   3: 9.974 ops/ms
Iteration   1: 9.728 ops/ms
Iteration   2: 10.154 ops/ms
Iteration   3: 10.210 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.031 ±(99.9%) 4.809 ops/ms [Average]
  (min, avg, max) = (9.728, 10.031, 10.210), stdev = 0.264
  CI (99.9%): [5.222, 14.839] (assumes normal distribution)


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
# Warmup Iteration   1: 5.228 ops/ms
# Warmup Iteration   2: 7.433 ops/ms
# Warmup Iteration   3: 7.680 ops/ms
Iteration   1: 7.799 ops/ms
Iteration   2: 7.908 ops/ms
Iteration   3: 8.042 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.916 ±(99.9%) 2.215 ops/ms [Average]
  (min, avg, max) = (7.799, 7.916, 8.042), stdev = 0.121
  CI (99.9%): [5.702, 10.131] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.240 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.159 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.159 ±(99.9%) 0.002 ms/op
Iteration   1: 3.127 ±(99.9%) 0.006 ms/op
Iteration   2: 3.112 ±(99.9%) 0.002 ms/op
Iteration   3: 3.194 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.144 ±(99.9%) 0.795 ms/op [Average]
  (min, avg, max) = (3.112, 3.144, 3.194), stdev = 0.044
  CI (99.9%): [2.349, 3.939] (assumes normal distribution)


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
# Warmup Iteration   1: 4.009 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.048 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.984 ±(99.9%) 0.007 ms/op
Iteration   1: 2.972 ±(99.9%) 0.002 ms/op
Iteration   2: 2.951 ±(99.9%) 0.002 ms/op
Iteration   3: 2.957 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.960 ±(99.9%) 0.189 ms/op [Average]
  (min, avg, max) = (2.951, 2.960, 2.972), stdev = 0.010
  CI (99.9%): [2.771, 3.149] (assumes normal distribution)


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
# Warmup Iteration   1: 4.372 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.124 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.142 ±(99.9%) 0.002 ms/op
Iteration   1: 3.121 ±(99.9%) 0.002 ms/op
Iteration   2: 3.131 ±(99.9%) 0.002 ms/op
Iteration   3: 3.161 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.138 ±(99.9%) 0.377 ms/op [Average]
  (min, avg, max) = (3.121, 3.138, 3.161), stdev = 0.021
  CI (99.9%): [2.760, 3.515] (assumes normal distribution)


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
# Warmup Iteration   1: 5.559 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.109 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.107 ±(99.9%) 0.013 ms/op
Iteration   1: 4.064 ±(99.9%) 0.006 ms/op
Iteration   2: 3.944 ±(99.9%) 0.013 ms/op
Iteration   3: 3.977 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.995 ±(99.9%) 1.126 ms/op [Average]
  (min, avg, max) = (3.944, 3.995, 4.064), stdev = 0.062
  CI (99.9%): [2.869, 5.121] (assumes normal distribution)


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
# Warmup Iteration   1: 4.145 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.178 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.138 ±(99.9%) 0.008 ms/op
Iteration   1: 3.139 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.678 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   4.035 ms/op
                 createUser·p0.99:   4.596 ms/op
                 createUser·p0.999:  7.999 ms/op
                 createUser·p0.9999: 14.327 ms/op
                 createUser·p1.00:   14.582 ms/op

Iteration   2: 3.199 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.810 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.096 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  9.622 ms/op
                 createUser·p0.9999: 16.761 ms/op
                 createUser·p1.00:   18.186 ms/op

Iteration   3: 3.224 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.679 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.973 ms/op
                 createUser·p0.95:   4.137 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  8.809 ms/op
                 createUser·p0.9999: 30.870 ms/op
                 createUser·p1.00:   31.228 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 301009
  mean =      3.187 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25909 
    [ 2.500,  5.000) = 273912 
    [ 5.000,  7.500) = 784 
    [ 7.500, 10.000) = 148 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.678 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.096 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      8.880 ms/op
     p(99.9900) =     29.809 ms/op
     p(99.9990) =     31.129 ms/op
     p(99.9999) =     31.228 ms/op
    p(100.0000) =     31.228 ms/op


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
# Warmup Iteration   1: 3.789 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.171 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.007 ms/op
Iteration   1: 2.971 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.854 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   4.182 ms/op
                 existUser·p0.999:  6.816 ms/op
                 existUser·p0.9999: 13.697 ms/op
                 existUser·p1.00:   14.107 ms/op

Iteration   2: 3.027 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.644 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.633 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  6.747 ms/op
                 existUser·p0.9999: 16.358 ms/op
                 existUser·p1.00:   16.744 ms/op

Iteration   3: 3.036 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.631 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.789 ms/op
                 existUser·p0.95:   3.990 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  9.420 ms/op
                 existUser·p0.9999: 16.383 ms/op
                 existUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 318557
  mean =      3.011 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1263 
    [ 1.250,  2.500) = 47110 
    [ 2.500,  3.750) = 244616 
    [ 3.750,  5.000) = 24751 
    [ 5.000,  6.250) = 333 
    [ 6.250,  7.500) = 222 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 40 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 52 
    [16.250, 17.500) = 38 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      7.062 ms/op
     p(99.9900) =     16.304 ms/op
     p(99.9990) =     17.846 ms/op
     p(99.9999) =     17.990 ms/op
    p(100.0000) =     17.990 ms/op


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
# Warmup Iteration   1: 4.221 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.160 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.144 ±(99.9%) 0.007 ms/op
Iteration   1: 3.236 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.745 ms/op
                 getUser·p0.50:   3.228 ms/op
                 getUser·p0.90:   4.014 ms/op
                 getUser·p0.95:   4.149 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  7.579 ms/op
                 getUser·p0.9999: 13.912 ms/op
                 getUser·p1.00:   14.123 ms/op

Iteration   2: 3.102 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.823 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  6.929 ms/op
                 getUser·p0.9999: 15.330 ms/op
                 getUser·p1.00:   15.679 ms/op

Iteration   3: 3.148 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.711 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.834 ms/op
                 getUser·p0.95:   4.002 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  6.965 ms/op
                 getUser·p0.9999: 16.269 ms/op
                 getUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 303551
  mean =      3.161 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 717 
    [ 1.250,  2.500) = 25314 
    [ 2.500,  3.750) = 233044 
    [ 3.750,  5.000) = 43445 
    [ 5.000,  6.250) = 494 
    [ 6.250,  7.500) = 290 
    [ 7.500,  8.750) = 55 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.711 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      7.106 ms/op
     p(99.9900) =     15.656 ms/op
     p(99.9990) =     16.752 ms/op
     p(99.9999) =     18.022 ms/op
    p(100.0000) =     18.022 ms/op


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
# Warmup Iteration   1: 5.351 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.178 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.094 ±(99.9%) 0.012 ms/op
Iteration   1: 4.076 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.245 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   5.374 ms/op
                 listUser·p0.95:   6.078 ms/op
                 listUser·p0.99:   7.094 ms/op
                 listUser·p0.999:  14.128 ms/op
                 listUser·p0.9999: 15.436 ms/op
                 listUser·p1.00:   15.778 ms/op

Iteration   2: 4.005 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.386 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.835 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  16.060 ms/op
                 listUser·p0.9999: 25.494 ms/op
                 listUser·p1.00:   25.690 ms/op

Iteration   3: 4.079 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.217 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  19.767 ms/op
                 listUser·p0.9999: 27.525 ms/op
                 listUser·p1.00:   28.574 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236883
  mean =      4.053 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2576 
    [ 2.500,  5.000) = 207481 
    [ 5.000,  7.500) = 25347 
    [ 7.500, 10.000) = 992 
    [10.000, 12.500) = 153 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 50 

  Percentiles, ms/op:
      p(0.0000) =      1.217 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.939 ms/op
     p(99.0000) =      7.029 ms/op
     p(99.9000) =     14.666 ms/op
     p(99.9900) =     27.066 ms/op
     p(99.9990) =     28.439 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.907 ± 1.402  ops/ms
ClientGrpc.existUser                       thrpt       3  10.410 ± 4.709  ops/ms
ClientGrpc.getUser                         thrpt       3  10.031 ± 4.809  ops/ms
ClientGrpc.listUser                        thrpt       3   7.916 ± 2.215  ops/ms
ClientGrpc.createUser                       avgt       3   3.144 ± 0.795   ms/op
ClientGrpc.existUser                        avgt       3   2.960 ± 0.189   ms/op
ClientGrpc.getUser                          avgt       3   3.138 ± 0.377   ms/op
ClientGrpc.listUser                         avgt       3   3.995 ± 1.126   ms/op
ClientGrpc.createUser                     sample  301009   3.187 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.678           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.150           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.903           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.096           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.497           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.880           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.809           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.228           ms/op
ClientGrpc.existUser                      sample  318557   3.011 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.631           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.002           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.682           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.883           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.243           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.062           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.304           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.990           ms/op
ClientGrpc.getUser                        sample  303551   3.161 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.711           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.133           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.883           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.055           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.407           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.106           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.656           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.022           ms/op
ClientGrpc.listUser                       sample  236883   4.053 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.217           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.875           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.161           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.939           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.029           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.666           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.066           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.574           ms/op
