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
# Warmup Iteration   1: 2.146 ops/ms
# Warmup Iteration   2: 5.537 ops/ms
# Warmup Iteration   3: 7.173 ops/ms
Iteration   1: 7.207 ops/ms
Iteration   2: 6.949 ops/ms
Iteration   3: 6.722 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.959 ±(99.9%) 4.423 ops/ms [Average]
  (min, avg, max) = (6.722, 6.959, 7.207), stdev = 0.242
  CI (99.9%): [2.537, 11.382] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.027 ops/ms
# Warmup Iteration   2: 7.170 ops/ms
# Warmup Iteration   3: 7.821 ops/ms
Iteration   1: 7.611 ops/ms
Iteration   2: 8.384 ops/ms
Iteration   3: 7.998 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.998 ±(99.9%) 7.057 ops/ms [Average]
  (min, avg, max) = (7.611, 7.998, 8.384), stdev = 0.387
  CI (99.9%): [0.940, 15.055] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.427 ops/ms
# Warmup Iteration   2: 6.856 ops/ms
# Warmup Iteration   3: 7.215 ops/ms
Iteration   1: 7.616 ops/ms
Iteration   2: 7.795 ops/ms
Iteration   3: 7.531 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.647 ±(99.9%) 2.462 ops/ms [Average]
  (min, avg, max) = (7.531, 7.647, 7.795), stdev = 0.135
  CI (99.9%): [5.185, 10.109] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.713 ops/ms
# Warmup Iteration   2: 5.003 ops/ms
# Warmup Iteration   3: 5.461 ops/ms
Iteration   1: 5.810 ops/ms
Iteration   2: 5.805 ops/ms
Iteration   3: 5.834 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.816 ±(99.9%) 0.281 ops/ms [Average]
  (min, avg, max) = (5.805, 5.816, 5.834), stdev = 0.015
  CI (99.9%): [5.535, 6.097] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.826 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.531 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.260 ±(99.9%) 0.005 ms/op
Iteration   1: 4.117 ±(99.9%) 0.003 ms/op
Iteration   2: 4.188 ±(99.9%) 0.004 ms/op
Iteration   3: 4.218 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.175 ±(99.9%) 0.945 ms/op [Average]
  (min, avg, max) = (4.117, 4.175, 4.218), stdev = 0.052
  CI (99.9%): [3.230, 5.119] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.210 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.258 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.344 ±(99.9%) 0.004 ms/op
Iteration   1: 4.187 ±(99.9%) 0.004 ms/op
Iteration   2: 3.938 ±(99.9%) 0.002 ms/op
Iteration   3: 3.907 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.010 ±(99.9%) 2.798 ms/op [Average]
  (min, avg, max) = (3.907, 4.010, 4.187), stdev = 0.153
  CI (99.9%): [1.212, 6.809] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.553 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.641 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.623 ±(99.9%) 0.006 ms/op
Iteration   1: 4.465 ±(99.9%) 0.004 ms/op
Iteration   2: 4.366 ±(99.9%) 0.003 ms/op
Iteration   3: 4.220 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.350 ±(99.9%) 2.246 ms/op [Average]
  (min, avg, max) = (4.220, 4.350, 4.465), stdev = 0.123
  CI (99.9%): [2.104, 6.596] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.516 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 5.826 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 5.650 ±(99.9%) 0.024 ms/op
Iteration   1: 5.474 ±(99.9%) 0.012 ms/op
Iteration   2: 5.494 ±(99.9%) 0.022 ms/op
Iteration   3: 5.375 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.448 ±(99.9%) 1.169 ms/op [Average]
  (min, avg, max) = (5.375, 5.448, 5.494), stdev = 0.064
  CI (99.9%): [4.279, 6.616] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.564 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.550 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.240 ±(99.9%) 0.012 ms/op
Iteration   1: 4.221 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.174 ms/op
                 createUser·p0.50:   4.112 ms/op
                 createUser·p0.90:   5.267 ms/op
                 createUser·p0.95:   5.644 ms/op
                 createUser·p0.99:   7.242 ms/op
                 createUser·p0.999:  10.125 ms/op
                 createUser·p0.9999: 15.703 ms/op
                 createUser·p1.00:   15.958 ms/op

Iteration   2: 4.114 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.188 ms/op
                 createUser·p0.50:   4.055 ms/op
                 createUser·p0.90:   4.981 ms/op
                 createUser·p0.95:   5.300 ms/op
                 createUser·p0.99:   6.338 ms/op
                 createUser·p0.999:  10.490 ms/op
                 createUser·p0.9999: 16.920 ms/op
                 createUser·p1.00:   19.530 ms/op

Iteration   3: 4.206 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.736 ms/op
                 createUser·p0.50:   4.080 ms/op
                 createUser·p0.90:   5.128 ms/op
                 createUser·p0.95:   5.530 ms/op
                 createUser·p0.99:   7.340 ms/op
                 createUser·p0.999:  19.202 ms/op
                 createUser·p0.9999: 22.020 ms/op
                 createUser·p1.00:   22.512 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 229556
  mean =      4.180 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2627 
    [ 2.500,  5.000) = 198272 
    [ 5.000,  7.500) = 26939 
    [ 7.500, 10.000) = 1272 
    [10.000, 12.500) = 221 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.736 ms/op
     p(50.0000) =      4.084 ms/op
     p(90.0000) =      5.128 ms/op
     p(95.0000) =      5.497 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =     12.312 ms/op
     p(99.9900) =     20.580 ms/op
     p(99.9990) =     22.384 ms/op
     p(99.9999) =     22.512 ms/op
    p(100.0000) =     22.512 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.812 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.269 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.918 ±(99.9%) 0.012 ms/op
Iteration   1: 3.778 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.650 ms/op
                 existUser·p0.50:   3.674 ms/op
                 existUser·p0.90:   4.604 ms/op
                 existUser·p0.95:   5.005 ms/op
                 existUser·p0.99:   6.613 ms/op
                 existUser·p0.999:  9.961 ms/op
                 existUser·p0.9999: 20.808 ms/op
                 existUser·p1.00:   22.381 ms/op

Iteration   2: 3.759 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.719 ms/op
                 existUser·p0.50:   3.654 ms/op
                 existUser·p0.90:   4.456 ms/op
                 existUser·p0.95:   4.891 ms/op
                 existUser·p0.99:   6.758 ms/op
                 existUser·p0.999:  12.698 ms/op
                 existUser·p0.9999: 38.436 ms/op
                 existUser·p1.00:   39.780 ms/op

Iteration   3: 3.770 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.780 ms/op
                 existUser·p0.50:   3.731 ms/op
                 existUser·p0.90:   4.661 ms/op
                 existUser·p0.95:   5.022 ms/op
                 existUser·p0.99:   6.341 ms/op
                 existUser·p0.999:  10.702 ms/op
                 existUser·p0.9999: 24.558 ms/op
                 existUser·p1.00:   26.313 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 254680
  mean =      3.769 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8507 
    [ 2.500,  5.000) = 234027 
    [ 5.000,  7.500) = 10515 
    [ 7.500, 10.000) = 1226 
    [10.000, 12.500) = 247 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.650 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      4.973 ms/op
     p(99.0000) =      6.529 ms/op
     p(99.9000) =     10.753 ms/op
     p(99.9900) =     36.962 ms/op
     p(99.9990) =     39.208 ms/op
     p(99.9999) =     39.780 ms/op
    p(100.0000) =     39.780 ms/op


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
# Warmup Iteration   1: 6.581 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 4.401 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.144 ±(99.9%) 0.013 ms/op
Iteration   1: 4.118 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.169 ms/op
                 getUser·p0.50:   4.010 ms/op
                 getUser·p0.90:   5.063 ms/op
                 getUser·p0.95:   5.530 ms/op
                 getUser·p0.99:   7.332 ms/op
                 getUser·p0.999:  11.743 ms/op
                 getUser·p0.9999: 17.760 ms/op
                 getUser·p1.00:   21.627 ms/op

Iteration   2: 4.140 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.366 ms/op
                 getUser·p0.50:   4.030 ms/op
                 getUser·p0.90:   5.104 ms/op
                 getUser·p0.95:   5.448 ms/op
                 getUser·p0.99:   6.922 ms/op
                 getUser·p0.999:  10.744 ms/op
                 getUser·p0.9999: 26.640 ms/op
                 getUser·p1.00:   26.706 ms/op

Iteration   3: 4.347 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.147 ms/op
                 getUser·p0.50:   4.202 ms/op
                 getUser·p0.90:   5.423 ms/op
                 getUser·p0.95:   5.923 ms/op
                 getUser·p0.99:   7.715 ms/op
                 getUser·p0.999:  12.337 ms/op
                 getUser·p0.9999: 25.601 ms/op
                 getUser·p1.00:   28.279 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 228518
  mean =      4.199 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3724 
    [ 2.500,  5.000) = 193225 
    [ 5.000,  7.500) = 29441 
    [ 7.500, 10.000) = 1621 
    [10.000, 12.500) = 339 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 46 

  Percentiles, ms/op:
      p(0.0000) =      1.147 ms/op
     p(50.0000) =      4.076 ms/op
     p(90.0000) =      5.202 ms/op
     p(95.0000) =      5.644 ms/op
     p(99.0000) =      7.389 ms/op
     p(99.9000) =     11.346 ms/op
     p(99.9900) =     25.737 ms/op
     p(99.9990) =     26.851 ms/op
     p(99.9999) =     28.279 ms/op
    p(100.0000) =     28.279 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.150 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 5.987 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.669 ±(99.9%) 0.020 ms/op
Iteration   1: 5.306 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.679 ms/op
                 listUser·p0.50:   5.071 ms/op
                 listUser·p0.90:   6.693 ms/op
                 listUser·p0.95:   7.758 ms/op
                 listUser·p0.99:   9.732 ms/op
                 listUser·p0.999:  18.121 ms/op
                 listUser·p0.9999: 22.249 ms/op
                 listUser·p1.00:   27.197 ms/op

Iteration   2: 5.282 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.731 ms/op
                 listUser·p0.50:   5.095 ms/op
                 listUser·p0.90:   6.578 ms/op
                 listUser·p0.95:   7.504 ms/op
                 listUser·p0.99:   9.978 ms/op
                 listUser·p0.999:  17.069 ms/op
                 listUser·p0.9999: 20.677 ms/op
                 listUser·p1.00:   21.201 ms/op

Iteration   3: 5.328 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.329 ms/op
                 listUser·p0.50:   5.104 ms/op
                 listUser·p0.90:   6.668 ms/op
                 listUser·p0.95:   7.815 ms/op
                 listUser·p0.99:   10.230 ms/op
                 listUser·p0.999:  18.905 ms/op
                 listUser·p0.9999: 23.429 ms/op
                 listUser·p1.00:   24.183 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 180871
  mean =      5.305 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 128 
    [ 2.500,  5.000) = 81798 
    [ 5.000,  7.500) = 88475 
    [ 7.500, 10.000) = 8654 
    [10.000, 12.500) = 1259 
    [12.500, 15.000) = 254 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 121 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.329 ms/op
     p(50.0000) =      5.087 ms/op
     p(90.0000) =      6.644 ms/op
     p(95.0000) =      7.700 ms/op
     p(99.0000) =     10.011 ms/op
     p(99.9000) =     18.088 ms/op
     p(99.9900) =     22.617 ms/op
     p(99.9990) =     26.906 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.959 ± 4.423  ops/ms
ClientGrpc.existUser                       thrpt       3   7.998 ± 7.057  ops/ms
ClientGrpc.getUser                         thrpt       3   7.647 ± 2.462  ops/ms
ClientGrpc.listUser                        thrpt       3   5.816 ± 0.281  ops/ms
ClientGrpc.createUser                       avgt       3   4.175 ± 0.945   ms/op
ClientGrpc.existUser                        avgt       3   4.010 ± 2.798   ms/op
ClientGrpc.getUser                          avgt       3   4.350 ± 2.246   ms/op
ClientGrpc.listUser                         avgt       3   5.448 ± 1.169   ms/op
ClientGrpc.createUser                     sample  229556   4.180 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.736           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.084           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.128           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.497           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.963           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.312           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.580           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.512           ms/op
ClientGrpc.existUser                      sample  254680   3.769 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.650           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.686           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.579           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.973           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.529           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.753           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          36.962           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          39.780           ms/op
ClientGrpc.getUser                        sample  228518   4.199 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.147           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.076           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.202           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.644           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.389           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.346           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.737           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.279           ms/op
ClientGrpc.listUser                       sample  180871   5.305 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.329           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.087           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.644           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.700           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.011           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.088           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.617           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.197           ms/op
