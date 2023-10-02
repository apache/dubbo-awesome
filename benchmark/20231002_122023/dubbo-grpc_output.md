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
# Warmup Iteration   1: 4.345 ops/ms
# Warmup Iteration   2: 9.154 ops/ms
# Warmup Iteration   3: 9.945 ops/ms
Iteration   1: 10.118 ops/ms
Iteration   2: 10.198 ops/ms
Iteration   3: 10.198 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.171 ±(99.9%) 0.843 ops/ms [Average]
  (min, avg, max) = (10.118, 10.171, 10.198), stdev = 0.046
  CI (99.9%): [9.328, 11.015] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.830 ops/ms
# Warmup Iteration   2: 10.340 ops/ms
# Warmup Iteration   3: 10.394 ops/ms
Iteration   1: 10.853 ops/ms
Iteration   2: 10.620 ops/ms
Iteration   3: 10.776 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.750 ±(99.9%) 2.160 ops/ms [Average]
  (min, avg, max) = (10.620, 10.750, 10.853), stdev = 0.118
  CI (99.9%): [8.590, 12.909] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.855 ops/ms
# Warmup Iteration   2: 9.915 ops/ms
# Warmup Iteration   3: 10.131 ops/ms
Iteration   1: 10.151 ops/ms
Iteration   2: 10.425 ops/ms
Iteration   3: 10.259 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.278 ±(99.9%) 2.514 ops/ms [Average]
  (min, avg, max) = (10.151, 10.278, 10.425), stdev = 0.138
  CI (99.9%): [7.764, 12.792] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.120 ops/ms
# Warmup Iteration   2: 8.193 ops/ms
# Warmup Iteration   3: 8.511 ops/ms
Iteration   1: 8.365 ops/ms
Iteration   2: 8.434 ops/ms
Iteration   3: 8.461 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.420 ±(99.9%) 0.901 ops/ms [Average]
  (min, avg, max) = (8.365, 8.420, 8.461), stdev = 0.049
  CI (99.9%): [7.519, 9.321] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.157 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.218 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.128 ±(99.9%) 0.003 ms/op
Iteration   1: 3.163 ±(99.9%) 0.009 ms/op
Iteration   2: 3.069 ±(99.9%) 0.002 ms/op
Iteration   3: 3.149 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.127 ±(99.9%) 0.925 ms/op [Average]
  (min, avg, max) = (3.069, 3.127, 3.163), stdev = 0.051
  CI (99.9%): [2.202, 4.053] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.926 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.100 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.003 ms/op
Iteration   1: 2.924 ±(99.9%) 0.003 ms/op
Iteration   2: 2.993 ±(99.9%) 0.004 ms/op
Iteration   3: 3.037 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.985 ±(99.9%) 1.042 ms/op [Average]
  (min, avg, max) = (2.924, 2.985, 3.037), stdev = 0.057
  CI (99.9%): [1.943, 4.027] (assumes normal distribution)


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
# Warmup Iteration   1: 4.040 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.237 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.199 ±(99.9%) 0.002 ms/op
Iteration   1: 3.195 ±(99.9%) 0.001 ms/op
Iteration   2: 3.097 ±(99.9%) 0.002 ms/op
Iteration   3: 3.174 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.155 ±(99.9%) 0.939 ms/op [Average]
  (min, avg, max) = (3.097, 3.155, 3.195), stdev = 0.051
  CI (99.9%): [2.216, 4.095] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.372 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.929 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.888 ±(99.9%) 0.014 ms/op
Iteration   1: 3.849 ±(99.9%) 0.017 ms/op
Iteration   2: 3.833 ±(99.9%) 0.030 ms/op
Iteration   3: 3.832 ±(99.9%) 0.048 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.838 ±(99.9%) 0.176 ms/op [Average]
  (min, avg, max) = (3.832, 3.838, 3.849), stdev = 0.010
  CI (99.9%): [3.661, 4.014] (assumes normal distribution)


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
# Warmup Iteration   1: 3.900 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.202 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.107 ±(99.9%) 0.006 ms/op
Iteration   1: 3.129 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.307 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   4.801 ms/op
                 createUser·p0.999:  9.434 ms/op
                 createUser·p0.9999: 12.765 ms/op
                 createUser·p1.00:   14.926 ms/op

Iteration   2: 3.101 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.593 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.604 ms/op
                 createUser·p0.999:  11.068 ms/op
                 createUser·p0.9999: 15.576 ms/op
                 createUser·p1.00:   19.202 ms/op

Iteration   3: 3.085 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.835 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  6.696 ms/op
                 createUser·p0.9999: 14.591 ms/op
                 createUser·p1.00:   15.024 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309041
  mean =      3.105 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 554 
    [ 1.250,  2.500) = 8744 
    [ 2.500,  3.750) = 281771 
    [ 3.750,  5.000) = 15910 
    [ 5.000,  6.250) = 1177 
    [ 6.250,  7.500) = 409 
    [ 7.500,  8.750) = 105 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 117 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.307 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.637 ms/op
     p(99.9000) =     10.271 ms/op
     p(99.9900) =     14.505 ms/op
     p(99.9990) =     19.065 ms/op
     p(99.9999) =     19.202 ms/op
    p(100.0000) =     19.202 ms/op


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
# Warmup Iteration   1: 3.524 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.006 ms/op
Iteration   1: 3.066 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.739 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.506 ms/op
                 existUser·p0.999:  7.528 ms/op
                 existUser·p0.9999: 16.059 ms/op
                 existUser·p1.00:   16.318 ms/op

Iteration   2: 3.026 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.883 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  6.660 ms/op
                 existUser·p0.9999: 15.122 ms/op
                 existUser·p1.00:   15.532 ms/op

Iteration   3: 3.074 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.773 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  7.187 ms/op
                 existUser·p0.9999: 27.263 ms/op
                 existUser·p1.00:   27.492 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 314316
  mean =      3.055 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16010 
    [ 2.500,  5.000) = 296978 
    [ 5.000,  7.500) = 1075 
    [ 7.500, 10.000) = 67 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.739 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      7.094 ms/op
     p(99.9900) =     16.173 ms/op
     p(99.9990) =     27.422 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


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
# Warmup Iteration   1: 4.196 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.241 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.239 ±(99.9%) 0.006 ms/op
Iteration   1: 3.159 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.858 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   3.928 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  10.568 ms/op
                 getUser·p0.9999: 12.190 ms/op
                 getUser·p1.00:   12.583 ms/op

Iteration   2: 3.164 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.705 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   4.617 ms/op
                 getUser·p0.999:  9.518 ms/op
                 getUser·p0.9999: 12.419 ms/op
                 getUser·p1.00:   12.632 ms/op

Iteration   3: 3.081 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.677 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  6.379 ms/op
                 getUser·p0.9999: 15.722 ms/op
                 getUser·p1.00:   16.515 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306242
  mean =      3.134 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 743 
    [ 1.250,  2.500) = 10914 
    [ 2.500,  3.750) = 268429 
    [ 3.750,  5.000) = 24585 
    [ 5.000,  6.250) = 741 
    [ 6.250,  7.500) = 349 
    [ 7.500,  8.750) = 150 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 112 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.677 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      9.286 ms/op
     p(99.9900) =     15.026 ms/op
     p(99.9990) =     16.398 ms/op
     p(99.9999) =     16.515 ms/op
    p(100.0000) =     16.515 ms/op


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
# Warmup Iteration   1: 5.114 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.151 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.914 ±(99.9%) 0.011 ms/op
Iteration   1: 3.896 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.262 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.973 ms/op
                 listUser·p0.99:   6.439 ms/op
                 listUser·p0.999:  13.155 ms/op
                 listUser·p0.9999: 14.988 ms/op
                 listUser·p1.00:   15.303 ms/op

Iteration   2: 3.852 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.341 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   5.022 ms/op
                 listUser·p0.99:   6.641 ms/op
                 listUser·p0.999:  12.959 ms/op
                 listUser·p0.9999: 15.227 ms/op
                 listUser·p1.00:   15.778 ms/op

Iteration   3: 3.861 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.972 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   5.079 ms/op
                 listUser·p0.99:   6.521 ms/op
                 listUser·p0.999:  13.861 ms/op
                 listUser·p0.9999: 19.477 ms/op
                 listUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248107
  mean =      3.870 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 10 
    [ 1.250,  2.500) = 3208 
    [ 2.500,  3.750) = 108924 
    [ 3.750,  5.000) = 123469 
    [ 5.000,  6.250) = 8368 
    [ 6.250,  7.500) = 3212 
    [ 7.500,  8.750) = 319 
    [ 8.750, 10.000) = 115 
    [10.000, 11.250) = 52 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 161 
    [13.750, 15.000) = 134 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.972 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      5.014 ms/op
     p(99.0000) =      6.529 ms/op
     p(99.9000) =     13.318 ms/op
     p(99.9900) =     18.153 ms/op
     p(99.9990) =     19.777 ms/op
     p(99.9999) =     19.825 ms/op
    p(100.0000) =     19.825 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.171 ± 0.843  ops/ms
ClientGrpc.existUser                       thrpt       3  10.750 ± 2.160  ops/ms
ClientGrpc.getUser                         thrpt       3  10.278 ± 2.514  ops/ms
ClientGrpc.listUser                        thrpt       3   8.420 ± 0.901  ops/ms
ClientGrpc.createUser                       avgt       3   3.127 ± 0.925   ms/op
ClientGrpc.existUser                        avgt       3   2.985 ± 1.042   ms/op
ClientGrpc.getUser                          avgt       3   3.155 ± 0.939   ms/op
ClientGrpc.listUser                         avgt       3   3.838 ± 0.176   ms/op
ClientGrpc.createUser                     sample  309041   3.105 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.307           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.060           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.600           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.797           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.637           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.271           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          14.505           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.202           ms/op
ClientGrpc.existUser                      sample  314316   3.055 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.739           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.011           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.576           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.703           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.358           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.094           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.173           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.492           ms/op
ClientGrpc.getUser                        sample  306242   3.134 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.677           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.097           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.699           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.891           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.440           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.286           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.026           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.515           ms/op
ClientGrpc.listUser                       sample  248107   3.870 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.972           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.793           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.301           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.014           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.529           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.318           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.153           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.825           ms/op
