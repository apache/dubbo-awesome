# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.310 ops/ms
# Warmup Iteration   2: 5.621 ops/ms
# Warmup Iteration   3: 7.250 ops/ms
Iteration   1: 7.488 ops/ms
Iteration   2: 7.544 ops/ms
Iteration   3: 7.513 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.515 ±(99.9%) 0.514 ops/ms [Average]
  (min, avg, max) = (7.488, 7.515, 7.544), stdev = 0.028
  CI (99.9%): [7.001, 8.029] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.985 ops/ms
# Warmup Iteration   2: 7.446 ops/ms
# Warmup Iteration   3: 7.857 ops/ms
Iteration   1: 8.387 ops/ms
Iteration   2: 8.047 ops/ms
Iteration   3: 8.101 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.179 ±(99.9%) 3.334 ops/ms [Average]
  (min, avg, max) = (8.047, 8.179, 8.387), stdev = 0.183
  CI (99.9%): [4.845, 11.512] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.367 ops/ms
# Warmup Iteration   2: 6.958 ops/ms
# Warmup Iteration   3: 7.534 ops/ms
Iteration   1: 7.719 ops/ms
Iteration   2: 7.877 ops/ms
Iteration   3: 7.912 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.836 ±(99.9%) 1.872 ops/ms [Average]
  (min, avg, max) = (7.719, 7.836, 7.912), stdev = 0.103
  CI (99.9%): [5.964, 9.708] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.569 ops/ms
# Warmup Iteration   2: 5.409 ops/ms
# Warmup Iteration   3: 5.681 ops/ms
Iteration   1: 5.958 ops/ms
Iteration   2: 5.895 ops/ms
Iteration   3: 5.799 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.884 ±(99.9%) 1.459 ops/ms [Average]
  (min, avg, max) = (5.799, 5.884, 5.958), stdev = 0.080
  CI (99.9%): [4.426, 7.343] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.392 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.391 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.151 ±(99.9%) 0.003 ms/op
Iteration   1: 4.096 ±(99.9%) 0.002 ms/op
Iteration   2: 4.355 ±(99.9%) 0.003 ms/op
Iteration   3: 4.285 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.245 ±(99.9%) 2.448 ms/op [Average]
  (min, avg, max) = (4.096, 4.245, 4.355), stdev = 0.134
  CI (99.9%): [1.798, 6.693] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.620 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.293 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.079 ±(99.9%) 0.002 ms/op
Iteration   1: 3.885 ±(99.9%) 0.002 ms/op
Iteration   2: 3.876 ±(99.9%) 0.003 ms/op
Iteration   3: 3.944 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.902 ±(99.9%) 0.674 ms/op [Average]
  (min, avg, max) = (3.876, 3.902, 3.944), stdev = 0.037
  CI (99.9%): [3.228, 4.575] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.303 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.484 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.296 ±(99.9%) 0.008 ms/op
Iteration   1: 4.340 ±(99.9%) 0.004 ms/op
Iteration   2: 4.193 ±(99.9%) 0.003 ms/op
Iteration   3: 4.236 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.257 ±(99.9%) 1.380 ms/op [Average]
  (min, avg, max) = (4.193, 4.257, 4.340), stdev = 0.076
  CI (99.9%): [2.877, 5.637] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.817 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 5.679 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.340 ±(99.9%) 0.025 ms/op
Iteration   1: 5.464 ±(99.9%) 0.021 ms/op
Iteration   2: 5.404 ±(99.9%) 0.015 ms/op
Iteration   3: 5.314 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.394 ±(99.9%) 1.380 ms/op [Average]
  (min, avg, max) = (5.314, 5.394, 5.464), stdev = 0.076
  CI (99.9%): [4.014, 6.774] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.096 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 4.570 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.378 ±(99.9%) 0.012 ms/op
Iteration   1: 4.225 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.887 ms/op
                 createUser·p0.50:   4.133 ms/op
                 createUser·p0.90:   5.112 ms/op
                 createUser·p0.95:   5.538 ms/op
                 createUser·p0.99:   6.865 ms/op
                 createUser·p0.999:  11.783 ms/op
                 createUser·p0.9999: 15.546 ms/op
                 createUser·p1.00:   15.827 ms/op

Iteration   2: 4.304 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.384 ms/op
                 createUser·p0.50:   4.202 ms/op
                 createUser·p0.90:   5.325 ms/op
                 createUser·p0.95:   5.677 ms/op
                 createUser·p0.99:   7.045 ms/op
                 createUser·p0.999:  15.298 ms/op
                 createUser·p0.9999: 18.781 ms/op
                 createUser·p1.00:   19.562 ms/op

Iteration   3: 4.186 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.143 ms/op
                 createUser·p0.50:   4.104 ms/op
                 createUser·p0.90:   5.145 ms/op
                 createUser·p0.95:   5.505 ms/op
                 createUser·p0.99:   6.693 ms/op
                 createUser·p0.999:  12.304 ms/op
                 createUser·p0.9999: 19.988 ms/op
                 createUser·p1.00:   21.037 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 226708
  mean =      4.238 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3074 
    [ 2.500,  5.000) = 191704 
    [ 5.000,  7.500) = 30314 
    [ 7.500, 10.000) = 1131 
    [10.000, 12.500) = 274 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.887 ms/op
     p(50.0000) =      4.145 ms/op
     p(90.0000) =      5.202 ms/op
     p(95.0000) =      5.587 ms/op
     p(99.0000) =      6.831 ms/op
     p(99.9000) =     12.276 ms/op
     p(99.9900) =     19.125 ms/op
     p(99.9990) =     20.397 ms/op
     p(99.9999) =     21.037 ms/op
    p(100.0000) =     21.037 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.850 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.239 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.024 ±(99.9%) 0.011 ms/op
Iteration   1: 3.957 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.861 ms/op
                 existUser·p0.50:   3.879 ms/op
                 existUser·p0.90:   4.940 ms/op
                 existUser·p0.95:   5.374 ms/op
                 existUser·p0.99:   6.709 ms/op
                 existUser·p0.999:  10.727 ms/op
                 existUser·p0.9999: 20.546 ms/op
                 existUser·p1.00:   20.840 ms/op

Iteration   2: 3.877 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.918 ms/op
                 existUser·p0.50:   3.846 ms/op
                 existUser·p0.90:   4.710 ms/op
                 existUser·p0.95:   5.046 ms/op
                 existUser·p0.99:   6.013 ms/op
                 existUser·p0.999:  9.767 ms/op
                 existUser·p0.9999: 18.648 ms/op
                 existUser·p1.00:   21.496 ms/op

Iteration   3: 3.982 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.898 ms/op
                 existUser·p0.50:   3.908 ms/op
                 existUser·p0.90:   4.809 ms/op
                 existUser·p0.95:   5.210 ms/op
                 existUser·p0.99:   6.324 ms/op
                 existUser·p0.999:  11.979 ms/op
                 existUser·p0.9999: 20.479 ms/op
                 existUser·p1.00:   22.413 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 243563
  mean =      3.938 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8255 
    [ 2.500,  5.000) = 217739 
    [ 5.000,  7.500) = 16442 
    [ 7.500, 10.000) = 764 
    [10.000, 12.500) = 187 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.861 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.817 ms/op
     p(95.0000) =      5.210 ms/op
     p(99.0000) =      6.349 ms/op
     p(99.9000) =     10.715 ms/op
     p(99.9900) =     20.468 ms/op
     p(99.9990) =     21.889 ms/op
     p(99.9999) =     22.413 ms/op
    p(100.0000) =     22.413 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.691 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.523 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.256 ±(99.9%) 0.011 ms/op
Iteration   1: 4.081 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.198 ms/op
                 getUser·p0.50:   4.006 ms/op
                 getUser·p0.90:   5.014 ms/op
                 getUser·p0.95:   5.423 ms/op
                 getUser·p0.99:   6.447 ms/op
                 getUser·p0.999:  10.928 ms/op
                 getUser·p0.9999: 15.245 ms/op
                 getUser·p1.00:   15.712 ms/op

Iteration   2: 4.185 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.773 ms/op
                 getUser·p0.50:   4.092 ms/op
                 getUser·p0.90:   5.153 ms/op
                 getUser·p0.95:   5.513 ms/op
                 getUser·p0.99:   6.472 ms/op
                 getUser·p0.999:  14.160 ms/op
                 getUser·p0.9999: 27.462 ms/op
                 getUser·p1.00:   27.886 ms/op

Iteration   3: 4.100 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.776 ms/op
                 getUser·p0.50:   4.026 ms/op
                 getUser·p0.90:   4.981 ms/op
                 getUser·p0.95:   5.341 ms/op
                 getUser·p0.99:   6.300 ms/op
                 getUser·p0.999:  9.765 ms/op
                 getUser·p0.9999: 20.840 ms/op
                 getUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 232887
  mean =      4.121 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3989 
    [ 2.500,  5.000) = 203384 
    [ 5.000,  7.500) = 24583 
    [ 7.500, 10.000) = 581 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.773 ms/op
     p(50.0000) =      4.043 ms/op
     p(90.0000) =      5.054 ms/op
     p(95.0000) =      5.431 ms/op
     p(99.0000) =      6.406 ms/op
     p(99.9000) =     11.667 ms/op
     p(99.9900) =     25.793 ms/op
     p(99.9990) =     27.820 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 7.570 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 5.922 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.505 ±(99.9%) 0.019 ms/op
Iteration   1: 5.377 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.896 ms/op
                 listUser·p0.50:   5.161 ms/op
                 listUser·p0.90:   6.775 ms/op
                 listUser·p0.95:   7.815 ms/op
                 listUser·p0.99:   9.748 ms/op
                 listUser·p0.999:  16.925 ms/op
                 listUser·p0.9999: 24.909 ms/op
                 listUser·p1.00:   25.297 ms/op

Iteration   2: 5.312 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.720 ms/op
                 listUser·p0.50:   5.112 ms/op
                 listUser·p0.90:   6.808 ms/op
                 listUser·p0.95:   7.692 ms/op
                 listUser·p0.99:   9.470 ms/op
                 listUser·p0.999:  17.031 ms/op
                 listUser·p0.9999: 23.427 ms/op
                 listUser·p1.00:   24.019 ms/op

Iteration   3: 5.494 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.550 ms/op
                 listUser·p0.50:   5.276 ms/op
                 listUser·p0.90:   6.939 ms/op
                 listUser·p0.95:   7.799 ms/op
                 listUser·p0.99:   10.076 ms/op
                 listUser·p0.999:  22.610 ms/op
                 listUser·p0.9999: 28.457 ms/op
                 listUser·p1.00:   28.836 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 177930
  mean =      5.393 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 99 
    [ 2.500,  5.000) = 74350 
    [ 5.000,  7.500) = 92560 
    [ 7.500, 10.000) = 9401 
    [10.000, 12.500) = 1046 
    [12.500, 15.000) = 172 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.550 ms/op
     p(50.0000) =      5.177 ms/op
     p(90.0000) =      6.849 ms/op
     p(95.0000) =      7.766 ms/op
     p(99.0000) =      9.781 ms/op
     p(99.9000) =     19.368 ms/op
     p(99.9900) =     26.523 ms/op
     p(99.9990) =     28.836 ms/op
     p(99.9999) =     28.836 ms/op
    p(100.0000) =     28.836 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.515 ± 0.514  ops/ms
ClientGrpc.existUser                       thrpt       3   8.179 ± 3.334  ops/ms
ClientGrpc.getUser                         thrpt       3   7.836 ± 1.872  ops/ms
ClientGrpc.listUser                        thrpt       3   5.884 ± 1.459  ops/ms
ClientGrpc.createUser                       avgt       3   4.245 ± 2.448   ms/op
ClientGrpc.existUser                        avgt       3   3.902 ± 0.674   ms/op
ClientGrpc.getUser                          avgt       3   4.257 ± 1.380   ms/op
ClientGrpc.listUser                         avgt       3   5.394 ± 1.380   ms/op
ClientGrpc.createUser                     sample  226708   4.238 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.887           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.145           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.202           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.587           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.831           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.276           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.125           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.037           ms/op
ClientGrpc.existUser                      sample  243563   3.938 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.861           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.879           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.817           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.210           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.349           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.715           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.468           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.413           ms/op
ClientGrpc.getUser                        sample  232887   4.121 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.773           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.043           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.054           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.431           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.406           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.667           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.793           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.886           ms/op
ClientGrpc.listUser                       sample  177930   5.393 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.550           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.177           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.849           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.766           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.781           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.368           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.523           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.836           ms/op
