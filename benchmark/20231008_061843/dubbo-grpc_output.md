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
# Warmup Iteration   1: 3.244 ops/ms
# Warmup Iteration   2: 7.312 ops/ms
# Warmup Iteration   3: 8.938 ops/ms
Iteration   1: 9.560 ops/ms
Iteration   2: 9.752 ops/ms
Iteration   3: 9.836 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.716 ±(99.9%) 2.577 ops/ms [Average]
  (min, avg, max) = (9.560, 9.716, 9.836), stdev = 0.141
  CI (99.9%): [7.140, 12.293] (assumes normal distribution)


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
# Warmup Iteration   1: 6.847 ops/ms
# Warmup Iteration   2: 10.109 ops/ms
# Warmup Iteration   3: 10.444 ops/ms
Iteration   1: 10.260 ops/ms
Iteration   2: 10.212 ops/ms
Iteration   3: 10.415 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.295 ±(99.9%) 1.937 ops/ms [Average]
  (min, avg, max) = (10.212, 10.295, 10.415), stdev = 0.106
  CI (99.9%): [8.359, 12.232] (assumes normal distribution)


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
# Warmup Iteration   1: 5.275 ops/ms
# Warmup Iteration   2: 9.365 ops/ms
# Warmup Iteration   3: 9.755 ops/ms
Iteration   1: 9.807 ops/ms
Iteration   2: 10.033 ops/ms
Iteration   3: 10.120 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.986 ±(99.9%) 2.946 ops/ms [Average]
  (min, avg, max) = (9.807, 9.986, 10.120), stdev = 0.161
  CI (99.9%): [7.041, 12.932] (assumes normal distribution)


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
# Warmup Iteration   1: 5.402 ops/ms
# Warmup Iteration   2: 7.579 ops/ms
# Warmup Iteration   3: 7.909 ops/ms
Iteration   1: 7.981 ops/ms
Iteration   2: 8.281 ops/ms
Iteration   3: 7.987 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.083 ±(99.9%) 3.128 ops/ms [Average]
  (min, avg, max) = (7.981, 8.083, 8.281), stdev = 0.171
  CI (99.9%): [4.955, 11.211] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 4.376 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.341 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.181 ±(99.9%) 0.003 ms/op
Iteration   1: 3.220 ±(99.9%) 0.004 ms/op
Iteration   2: 3.124 ±(99.9%) 0.004 ms/op
Iteration   3: 3.133 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.159 ±(99.9%) 0.972 ms/op [Average]
  (min, avg, max) = (3.124, 3.159, 3.220), stdev = 0.053
  CI (99.9%): [2.187, 4.131] (assumes normal distribution)


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
# Warmup Iteration   1: 3.951 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.004 ms/op
Iteration   1: 3.051 ±(99.9%) 0.006 ms/op
Iteration   2: 2.990 ±(99.9%) 0.003 ms/op
Iteration   3: 3.043 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.028 ±(99.9%) 0.604 ms/op [Average]
  (min, avg, max) = (2.990, 3.028, 3.051), stdev = 0.033
  CI (99.9%): [2.424, 3.632] (assumes normal distribution)


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
# Warmup Iteration   1: 4.494 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.251 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.165 ±(99.9%) 0.003 ms/op
Iteration   1: 3.155 ±(99.9%) 0.002 ms/op
Iteration   2: 3.217 ±(99.9%) 0.005 ms/op
Iteration   3: 3.103 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.158 ±(99.9%) 1.039 ms/op [Average]
  (min, avg, max) = (3.103, 3.158, 3.217), stdev = 0.057
  CI (99.9%): [2.119, 4.197] (assumes normal distribution)


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
# Warmup Iteration   1: 5.407 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.120 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.997 ±(99.9%) 0.019 ms/op
Iteration   1: 3.905 ±(99.9%) 0.019 ms/op
Iteration   2: 3.907 ±(99.9%) 0.022 ms/op
Iteration   3: 3.965 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.926 ±(99.9%) 0.621 ms/op [Average]
  (min, avg, max) = (3.905, 3.926, 3.965), stdev = 0.034
  CI (99.9%): [3.305, 4.546] (assumes normal distribution)


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
# Warmup Iteration   1: 4.192 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.332 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.195 ±(99.9%) 0.006 ms/op
Iteration   1: 3.150 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.820 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.604 ms/op
                 createUser·p0.999:  7.556 ms/op
                 createUser·p0.9999: 12.594 ms/op
                 createUser·p1.00:   13.533 ms/op

Iteration   2: 3.099 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.798 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.678 ms/op
                 createUser·p0.999:  8.989 ms/op
                 createUser·p0.9999: 19.290 ms/op
                 createUser·p1.00:   20.611 ms/op

Iteration   3: 3.198 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.743 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  10.241 ms/op
                 createUser·p0.9999: 16.663 ms/op
                 createUser·p1.00:   17.138 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 304735
  mean =      3.149 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12305 
    [ 2.500,  5.000) = 290551 
    [ 5.000,  7.500) = 1368 
    [ 7.500, 10.000) = 276 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 147 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.743 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      8.639 ms/op
     p(99.9900) =     16.622 ms/op
     p(99.9990) =     20.610 ms/op
     p(99.9999) =     20.611 ms/op
    p(100.0000) =     20.611 ms/op


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
# Warmup Iteration   1: 4.203 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.150 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.006 ms/op
Iteration   1: 3.022 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.716 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.768 ms/op
                 existUser·p0.99:   4.628 ms/op
                 existUser·p0.999:  6.824 ms/op
                 existUser·p0.9999: 13.458 ms/op
                 existUser·p1.00:   14.107 ms/op

Iteration   2: 3.005 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.713 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  12.255 ms/op
                 existUser·p0.9999: 16.095 ms/op
                 existUser·p1.00:   16.384 ms/op

Iteration   3: 3.079 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.638 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  7.743 ms/op
                 existUser·p0.9999: 17.924 ms/op
                 existUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 316272
  mean =      3.035 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 698 
    [ 1.250,  2.500) = 22063 
    [ 2.500,  3.750) = 278826 
    [ 3.750,  5.000) = 12846 
    [ 5.000,  6.250) = 1111 
    [ 6.250,  7.500) = 291 
    [ 7.500,  8.750) = 64 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 48 
    [11.250, 12.500) = 92 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 68 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.638 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =     10.797 ms/op
     p(99.9900) =     16.206 ms/op
     p(99.9990) =     18.285 ms/op
     p(99.9999) =     18.383 ms/op
    p(100.0000) =     18.383 ms/op


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
# Warmup Iteration   1: 4.555 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.271 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.234 ±(99.9%) 0.007 ms/op
Iteration   1: 3.159 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.800 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.907 ms/op
                 getUser·p0.999:  8.333 ms/op
                 getUser·p0.9999: 17.105 ms/op
                 getUser·p1.00:   17.334 ms/op

Iteration   2: 3.190 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.988 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.928 ms/op
                 getUser·p0.99:   5.276 ms/op
                 getUser·p0.999:  10.133 ms/op
                 getUser·p0.9999: 25.919 ms/op
                 getUser·p1.00:   26.739 ms/op

Iteration   3: 3.131 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.805 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.768 ms/op
                 getUser·p0.999:  15.303 ms/op
                 getUser·p0.9999: 33.999 ms/op
                 getUser·p1.00:   35.521 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 303641
  mean =      3.160 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9174 
    [ 2.500,  5.000) = 291593 
    [ 5.000,  7.500) = 2230 
    [ 7.500, 10.000) = 304 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      4.956 ms/op
     p(99.9000) =     10.754 ms/op
     p(99.9900) =     32.515 ms/op
     p(99.9990) =     35.389 ms/op
     p(99.9999) =     35.521 ms/op
    p(100.0000) =     35.521 ms/op


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
# Warmup Iteration   1: 6.002 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.201 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.922 ±(99.9%) 0.012 ms/op
Iteration   1: 3.991 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.048 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  13.890 ms/op
                 listUser·p0.9999: 26.802 ms/op
                 listUser·p1.00:   27.427 ms/op

Iteration   2: 4.021 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.782 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  15.539 ms/op
                 listUser·p0.9999: 19.007 ms/op
                 listUser·p1.00:   19.431 ms/op

Iteration   3: 3.987 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.787 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  15.952 ms/op
                 listUser·p0.9999: 19.716 ms/op
                 listUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240065
  mean =      4.000 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3073 
    [ 2.500,  5.000) = 218425 
    [ 5.000,  7.500) = 17118 
    [ 7.500, 10.000) = 832 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 252 
    [15.000, 17.500) = 157 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.782 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      5.693 ms/op
     p(99.0000) =      6.873 ms/op
     p(99.9000) =     14.958 ms/op
     p(99.9900) =     19.922 ms/op
     p(99.9990) =     27.197 ms/op
     p(99.9999) =     27.427 ms/op
    p(100.0000) =     27.427 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.716 ± 2.577  ops/ms
ClientGrpc.existUser                       thrpt       3  10.295 ± 1.937  ops/ms
ClientGrpc.getUser                         thrpt       3   9.986 ± 2.946  ops/ms
ClientGrpc.listUser                        thrpt       3   8.083 ± 3.128  ops/ms
ClientGrpc.createUser                       avgt       3   3.159 ± 0.972   ms/op
ClientGrpc.existUser                        avgt       3   3.028 ± 0.604   ms/op
ClientGrpc.getUser                          avgt       3   3.158 ± 1.039   ms/op
ClientGrpc.listUser                         avgt       3   3.926 ± 0.621   ms/op
ClientGrpc.createUser                     sample  304735   3.149 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.743           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.105           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.711           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.895           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.530           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.639           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.622           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.611           ms/op
ClientGrpc.existUser                      sample  316272   3.035 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.638           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.994           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.543           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.731           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.448           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.797           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.206           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.383           ms/op
ClientGrpc.getUser                        sample  303641   3.160 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.800           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.109           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.678           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.867           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.956           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.754           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          32.515           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          35.521           ms/op
ClientGrpc.listUser                       sample  240065   4.000 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.782           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.883           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.620           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.693           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.873           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.958           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.922           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.427           ms/op
