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
# Warmup Iteration   1: 4.975 ops/ms
# Warmup Iteration   2: 9.669 ops/ms
# Warmup Iteration   3: 10.397 ops/ms
Iteration   1: 10.014 ops/ms
Iteration   2: 9.905 ops/ms
Iteration   3: 9.958 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.959 ±(99.9%) 0.996 ops/ms [Average]
  (min, avg, max) = (9.905, 9.959, 10.014), stdev = 0.055
  CI (99.9%): [8.962, 10.955] (assumes normal distribution)


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
# Warmup Iteration   1: 8.020 ops/ms
# Warmup Iteration   2: 10.384 ops/ms
# Warmup Iteration   3: 10.799 ops/ms
Iteration   1: 10.562 ops/ms
Iteration   2: 10.832 ops/ms
Iteration   3: 10.452 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.615 ±(99.9%) 3.566 ops/ms [Average]
  (min, avg, max) = (10.452, 10.615, 10.832), stdev = 0.195
  CI (99.9%): [7.049, 14.181] (assumes normal distribution)


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
# Warmup Iteration   1: 7.447 ops/ms
# Warmup Iteration   2: 9.857 ops/ms
# Warmup Iteration   3: 10.161 ops/ms
Iteration   1: 10.206 ops/ms
Iteration   2: 9.896 ops/ms
Iteration   3: 9.872 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.991 ±(99.9%) 3.402 ops/ms [Average]
  (min, avg, max) = (9.872, 9.991, 10.206), stdev = 0.186
  CI (99.9%): [6.589, 13.393] (assumes normal distribution)


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
# Warmup Iteration   1: 6.431 ops/ms
# Warmup Iteration   2: 7.305 ops/ms
# Warmup Iteration   3: 7.759 ops/ms
Iteration   1: 7.742 ops/ms
Iteration   2: 7.843 ops/ms
Iteration   3: 7.834 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.807 ±(99.9%) 1.022 ops/ms [Average]
  (min, avg, max) = (7.742, 7.807, 7.843), stdev = 0.056
  CI (99.9%): [6.785, 8.828] (assumes normal distribution)


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
# Warmup Iteration   1: 3.752 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.306 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.181 ±(99.9%) 0.003 ms/op
Iteration   1: 3.260 ±(99.9%) 0.002 ms/op
Iteration   2: 3.095 ±(99.9%) 0.002 ms/op
Iteration   3: 3.265 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.207 ±(99.9%) 1.764 ms/op [Average]
  (min, avg, max) = (3.095, 3.207, 3.265), stdev = 0.097
  CI (99.9%): [1.442, 4.971] (assumes normal distribution)


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
# Warmup Iteration   1: 3.576 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.043 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.002 ms/op
Iteration   1: 2.990 ±(99.9%) 0.003 ms/op
Iteration   2: 3.024 ±(99.9%) 0.002 ms/op
Iteration   3: 2.964 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.993 ±(99.9%) 0.545 ms/op [Average]
  (min, avg, max) = (2.964, 2.993, 3.024), stdev = 0.030
  CI (99.9%): [2.448, 3.537] (assumes normal distribution)


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
# Warmup Iteration   1: 4.091 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.093 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.171 ±(99.9%) 0.002 ms/op
Iteration   1: 3.040 ±(99.9%) 0.002 ms/op
Iteration   2: 3.047 ±(99.9%) 0.003 ms/op
Iteration   3: 3.121 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.070 ±(99.9%) 0.815 ms/op [Average]
  (min, avg, max) = (3.040, 3.070, 3.121), stdev = 0.045
  CI (99.9%): [2.255, 3.884] (assumes normal distribution)


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
# Warmup Iteration   1: 5.348 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.107 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.115 ±(99.9%) 0.011 ms/op
Iteration   1: 3.944 ±(99.9%) 0.008 ms/op
Iteration   2: 4.122 ±(99.9%) 0.012 ms/op
Iteration   3: 3.882 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.982 ±(99.9%) 2.271 ms/op [Average]
  (min, avg, max) = (3.882, 3.982, 4.122), stdev = 0.125
  CI (99.9%): [1.711, 6.254] (assumes normal distribution)


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
# Warmup Iteration   1: 3.867 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.147 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.118 ±(99.9%) 0.006 ms/op
Iteration   1: 3.151 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.744 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   4.035 ms/op
                 createUser·p0.99:   4.612 ms/op
                 createUser·p0.999:  11.649 ms/op
                 createUser·p0.9999: 15.843 ms/op
                 createUser·p1.00:   15.991 ms/op

Iteration   2: 3.067 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.574 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  6.463 ms/op
                 createUser·p0.9999: 18.547 ms/op
                 createUser·p1.00:   19.431 ms/op

Iteration   3: 3.158 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.874 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.018 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  12.428 ms/op
                 createUser·p0.9999: 20.148 ms/op
                 createUser·p1.00:   20.447 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307429
  mean =      3.125 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24283 
    [ 2.500,  5.000) = 281817 
    [ 5.000,  7.500) = 884 
    [ 7.500, 10.000) = 79 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.574 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      3.981 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =     11.576 ms/op
     p(99.9900) =     19.571 ms/op
     p(99.9990) =     20.377 ms/op
     p(99.9999) =     20.447 ms/op
    p(100.0000) =     20.447 ms/op


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
# Warmup Iteration   1: 3.926 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.973 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.006 ms/op
Iteration   1: 2.990 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.737 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  5.325 ms/op
                 existUser·p0.9999: 13.023 ms/op
                 existUser·p1.00:   13.287 ms/op

Iteration   2: 2.979 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.712 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  7.267 ms/op
                 existUser·p0.9999: 12.743 ms/op
                 existUser·p1.00:   13.025 ms/op

Iteration   3: 2.976 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.685 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  5.619 ms/op
                 existUser·p0.9999: 14.864 ms/op
                 existUser·p1.00:   15.073 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321993
  mean =      2.982 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2266 
    [ 1.250,  2.500) = 36868 
    [ 2.500,  3.750) = 264050 
    [ 3.750,  5.000) = 17997 
    [ 5.000,  6.250) = 524 
    [ 6.250,  7.500) = 89 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 48 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.685 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      6.111 ms/op
     p(99.9900) =     14.320 ms/op
     p(99.9990) =     15.017 ms/op
     p(99.9999) =     15.073 ms/op
    p(100.0000) =     15.073 ms/op


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
# Warmup Iteration   1: 4.099 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.151 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.007 ms/op
Iteration   1: 3.107 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.552 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   3.994 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  7.089 ms/op
                 getUser·p0.9999: 18.448 ms/op
                 getUser·p1.00:   18.547 ms/op

Iteration   2: 3.169 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.494 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   3.994 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  10.215 ms/op
                 getUser·p0.9999: 34.597 ms/op
                 getUser·p1.00:   34.996 ms/op

Iteration   3: 3.138 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.691 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   3.977 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  6.359 ms/op
                 getUser·p0.9999: 32.723 ms/op
                 getUser·p1.00:   33.096 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 305775
  mean =      3.138 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21151 
    [ 2.500,  5.000) = 283633 
    [ 5.000,  7.500) = 688 
    [ 7.500, 10.000) = 70 
    [10.000, 12.500) = 9 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 44 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.494 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      3.990 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      7.447 ms/op
     p(99.9900) =     33.882 ms/op
     p(99.9990) =     34.865 ms/op
     p(99.9999) =     34.996 ms/op
    p(100.0000) =     34.996 ms/op


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
# Warmup Iteration   1: 4.767 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.224 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.017 ±(99.9%) 0.011 ms/op
Iteration   1: 3.949 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.548 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.678 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  13.606 ms/op
                 listUser·p0.9999: 15.754 ms/op
                 listUser·p1.00:   16.417 ms/op

Iteration   2: 4.070 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.802 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  12.999 ms/op
                 listUser·p0.9999: 21.482 ms/op
                 listUser·p1.00:   22.118 ms/op

Iteration   3: 4.211 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.903 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   5.456 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   7.240 ms/op
                 listUser·p0.999:  14.592 ms/op
                 listUser·p0.9999: 22.805 ms/op
                 listUser·p1.00:   23.233 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235798
  mean =      4.074 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3370 
    [ 2.500,  5.000) = 193453 
    [ 5.000,  7.500) = 37495 
    [ 7.500, 10.000) = 1038 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 179 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.802 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      5.300 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =     13.369 ms/op
     p(99.9900) =     21.996 ms/op
     p(99.9990) =     23.188 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.959 ± 0.996  ops/ms
ClientGrpc.existUser                       thrpt       3  10.615 ± 3.566  ops/ms
ClientGrpc.getUser                         thrpt       3   9.991 ± 3.402  ops/ms
ClientGrpc.listUser                        thrpt       3   7.807 ± 1.022  ops/ms
ClientGrpc.createUser                       avgt       3   3.207 ± 1.764   ms/op
ClientGrpc.existUser                        avgt       3   2.993 ± 0.545   ms/op
ClientGrpc.getUser                          avgt       3   3.070 ± 0.815   ms/op
ClientGrpc.listUser                         avgt       3   3.982 ± 2.271   ms/op
ClientGrpc.createUser                     sample  307429   3.125 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.574           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.088           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.781           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.981           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.576           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.571           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.447           ms/op
ClientGrpc.existUser                      sample  321993   2.982 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.685           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.982           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.588           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.789           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.111           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.320           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.073           ms/op
ClientGrpc.getUser                        sample  305775   3.138 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.494           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.117           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.793           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.990           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.366           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.447           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          33.882           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          34.996           ms/op
ClientGrpc.listUser                       sample  235798   4.074 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.802           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.854           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.300           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.669           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.963           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.369           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.996           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.233           ms/op
