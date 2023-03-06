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
# Warmup Iteration   1: 4.636 ops/ms
# Warmup Iteration   2: 8.881 ops/ms
# Warmup Iteration   3: 10.147 ops/ms
Iteration   1: 10.975 ops/ms
Iteration   2: 10.280 ops/ms
Iteration   3: 10.223 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.492 ±(99.9%) 7.643 ops/ms [Average]
  (min, avg, max) = (10.223, 10.492, 10.975), stdev = 0.419
  CI (99.9%): [2.849, 18.136] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.318 ops/ms
# Warmup Iteration   2: 10.472 ops/ms
# Warmup Iteration   3: 11.131 ops/ms
Iteration   1: 10.871 ops/ms
Iteration   2: 10.739 ops/ms
Iteration   3: 11.038 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.882 ±(99.9%) 2.734 ops/ms [Average]
  (min, avg, max) = (10.739, 10.882, 11.038), stdev = 0.150
  CI (99.9%): [8.149, 13.616] (assumes normal distribution)


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
# Warmup Iteration   1: 7.394 ops/ms
# Warmup Iteration   2: 10.237 ops/ms
# Warmup Iteration   3: 10.512 ops/ms
Iteration   1: 10.123 ops/ms
Iteration   2: 10.962 ops/ms
Iteration   3: 10.210 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.432 ±(99.9%) 8.413 ops/ms [Average]
  (min, avg, max) = (10.123, 10.432, 10.962), stdev = 0.461
  CI (99.9%): [2.019, 18.844] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.484 ops/ms
# Warmup Iteration   2: 7.456 ops/ms
# Warmup Iteration   3: 7.779 ops/ms
Iteration   1: 7.805 ops/ms
Iteration   2: 7.860 ops/ms
Iteration   3: 7.606 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.757 ±(99.9%) 2.436 ops/ms [Average]
  (min, avg, max) = (7.606, 7.757, 7.860), stdev = 0.134
  CI (99.9%): [5.321, 10.193] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.030 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.071 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.035 ±(99.9%) 0.002 ms/op
Iteration   1: 3.073 ±(99.9%) 0.009 ms/op
Iteration   2: 2.973 ±(99.9%) 0.002 ms/op
Iteration   3: 3.043 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.030 ±(99.9%) 0.933 ms/op [Average]
  (min, avg, max) = (2.973, 3.030, 3.073), stdev = 0.051
  CI (99.9%): [2.097, 3.962] (assumes normal distribution)


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
# Warmup Iteration   1: 3.964 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.949 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.881 ±(99.9%) 0.004 ms/op
Iteration   1: 2.974 ±(99.9%) 0.002 ms/op
Iteration   2: 2.869 ±(99.9%) 0.003 ms/op
Iteration   3: 2.918 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.920 ±(99.9%) 0.959 ms/op [Average]
  (min, avg, max) = (2.869, 2.920, 2.974), stdev = 0.053
  CI (99.9%): [1.961, 3.879] (assumes normal distribution)


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
# Warmup Iteration   1: 3.805 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.022 ±(99.9%) 0.002 ms/op
Iteration   1: 3.080 ±(99.9%) 0.003 ms/op
Iteration   2: 3.101 ±(99.9%) 0.002 ms/op
Iteration   3: 3.096 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.092 ±(99.9%) 0.201 ms/op [Average]
  (min, avg, max) = (3.080, 3.092, 3.101), stdev = 0.011
  CI (99.9%): [2.891, 3.294] (assumes normal distribution)


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
# Warmup Iteration   1: 5.085 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.156 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.950 ±(99.9%) 0.024 ms/op
Iteration   1: 4.000 ±(99.9%) 0.031 ms/op
Iteration   2: 4.097 ±(99.9%) 0.023 ms/op
Iteration   3: 3.984 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.027 ±(99.9%) 1.114 ms/op [Average]
  (min, avg, max) = (3.984, 4.027, 4.097), stdev = 0.061
  CI (99.9%): [2.912, 5.141] (assumes normal distribution)


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
# Warmup Iteration   1: 4.157 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.138 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.031 ±(99.9%) 0.006 ms/op
Iteration   1: 3.011 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.522 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.420 ms/op
                 createUser·p0.95:   3.641 ms/op
                 createUser·p0.99:   4.918 ms/op
                 createUser·p0.999:  11.858 ms/op
                 createUser·p0.9999: 24.052 ms/op
                 createUser·p1.00:   25.068 ms/op

Iteration   2: 3.166 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.229 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   4.051 ms/op
                 createUser·p0.95:   4.538 ms/op
                 createUser·p0.99:   5.898 ms/op
                 createUser·p0.999:  12.995 ms/op
                 createUser·p0.9999: 24.737 ms/op
                 createUser·p1.00:   25.494 ms/op

Iteration   3: 3.129 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.800 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.830 ms/op
                 createUser·p0.95:   4.014 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  6.526 ms/op
                 createUser·p0.9999: 20.742 ms/op
                 createUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309649
  mean =      3.101 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27058 
    [ 2.500,  5.000) = 278704 
    [ 5.000,  7.500) = 3358 
    [ 7.500, 10.000) = 210 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.229 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =      5.202 ms/op
     p(99.9000) =     10.792 ms/op
     p(99.9900) =     24.216 ms/op
     p(99.9990) =     25.127 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


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
# Warmup Iteration   1: 3.746 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.063 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.950 ±(99.9%) 0.006 ms/op
Iteration   1: 2.997 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.693 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   3.871 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  7.677 ms/op
                 existUser·p0.9999: 13.374 ms/op
                 existUser·p1.00:   14.533 ms/op

Iteration   2: 2.933 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.691 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  6.217 ms/op
                 existUser·p0.9999: 16.156 ms/op
                 existUser·p1.00:   16.515 ms/op

Iteration   3: 3.026 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.752 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   3.858 ms/op
                 existUser·p0.99:   4.125 ms/op
                 existUser·p0.999:  5.420 ms/op
                 existUser·p0.9999: 16.342 ms/op
                 existUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321575
  mean =      2.985 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1660 
    [ 1.250,  2.500) = 45379 
    [ 2.500,  3.750) = 250793 
    [ 3.750,  5.000) = 23051 
    [ 5.000,  6.250) = 372 
    [ 6.250,  7.500) = 82 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 41 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.691 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      4.178 ms/op
     p(99.9000) =      6.213 ms/op
     p(99.9900) =     16.122 ms/op
     p(99.9990) =     18.540 ms/op
     p(99.9999) =     18.645 ms/op
    p(100.0000) =     18.645 ms/op


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
# Warmup Iteration   1: 3.901 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.152 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.006 ms/op
Iteration   1: 3.024 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.727 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   4.407 ms/op
                 getUser·p0.999:  9.490 ms/op
                 getUser·p0.9999: 11.751 ms/op
                 getUser·p1.00:   12.108 ms/op

Iteration   2: 3.029 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.860 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  7.310 ms/op
                 getUser·p0.9999: 13.196 ms/op
                 getUser·p1.00:   13.599 ms/op

Iteration   3: 2.963 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.316 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.457 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  5.670 ms/op
                 getUser·p0.9999: 13.631 ms/op
                 getUser·p1.00:   14.582 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319479
  mean =      3.005 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2096 
    [ 1.250,  2.500) = 27346 
    [ 2.500,  3.750) = 272813 
    [ 3.750,  5.000) = 16274 
    [ 5.000,  6.250) = 503 
    [ 6.250,  7.500) = 177 
    [ 7.500,  8.750) = 60 
    [ 8.750, 10.000) = 17 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.316 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      7.139 ms/op
     p(99.9900) =     13.239 ms/op
     p(99.9990) =     14.376 ms/op
     p(99.9999) =     14.582 ms/op
    p(100.0000) =     14.582 ms/op


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
# Warmup Iteration   1: 5.149 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.141 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.987 ±(99.9%) 0.010 ms/op
Iteration   1: 3.979 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.993 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  12.094 ms/op
                 listUser·p0.9999: 14.563 ms/op
                 listUser·p1.00:   15.778 ms/op

Iteration   2: 3.959 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.919 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  13.154 ms/op
                 listUser·p0.9999: 16.905 ms/op
                 listUser·p1.00:   17.924 ms/op

Iteration   3: 4.128 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.912 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   7.413 ms/op
                 listUser·p0.999:  15.147 ms/op
                 listUser·p0.9999: 22.938 ms/op
                 listUser·p1.00:   23.724 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238771
  mean =      4.021 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4680 
    [ 2.500,  5.000) = 199041 
    [ 5.000,  7.500) = 33611 
    [ 7.500, 10.000) = 1027 
    [10.000, 12.500) = 97 
    [12.500, 15.000) = 176 
    [15.000, 17.500) = 107 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.912 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      5.202 ms/op
     p(95.0000) =      5.571 ms/op
     p(99.0000) =      6.996 ms/op
     p(99.9000) =     13.422 ms/op
     p(99.9900) =     17.928 ms/op
     p(99.9990) =     23.557 ms/op
     p(99.9999) =     23.724 ms/op
    p(100.0000) =     23.724 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.492 ± 7.643  ops/ms
ClientGrpc.existUser                       thrpt       3  10.882 ± 2.734  ops/ms
ClientGrpc.getUser                         thrpt       3  10.432 ± 8.413  ops/ms
ClientGrpc.listUser                        thrpt       3   7.757 ± 2.436  ops/ms
ClientGrpc.createUser                       avgt       3   3.030 ± 0.933   ms/op
ClientGrpc.existUser                        avgt       3   2.920 ± 0.959   ms/op
ClientGrpc.getUser                          avgt       3   3.092 ± 0.201   ms/op
ClientGrpc.listUser                         avgt       3   4.027 ± 1.114   ms/op
ClientGrpc.createUser                     sample  309649   3.101 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.229           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.064           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.789           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.108           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.202           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.792           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.216           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.494           ms/op
ClientGrpc.existUser                      sample  321575   2.985 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.691           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.957           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.662           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.846           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.178           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.213           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.122           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.645           ms/op
ClientGrpc.getUser                        sample  319479   3.005 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.316           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.011           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.543           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.772           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.293           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.139           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          13.239           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          14.582           ms/op
ClientGrpc.listUser                       sample  238771   4.021 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.912           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.830           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.202           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.571           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.996           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.422           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.928           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.724           ms/op
