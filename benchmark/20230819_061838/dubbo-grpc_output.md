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
# Warmup Iteration   1: 2.440 ops/ms
# Warmup Iteration   2: 5.945 ops/ms
# Warmup Iteration   3: 6.599 ops/ms
Iteration   1: 7.236 ops/ms
Iteration   2: 7.965 ops/ms
Iteration   3: 8.159 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.787 ±(99.9%) 8.881 ops/ms [Average]
  (min, avg, max) = (7.236, 7.787, 8.159), stdev = 0.487
  CI (99.9%): [≈ 0, 16.668] (assumes normal distribution)


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
# Warmup Iteration   1: 5.432 ops/ms
# Warmup Iteration   2: 7.460 ops/ms
# Warmup Iteration   3: 7.818 ops/ms
Iteration   1: 8.242 ops/ms
Iteration   2: 8.364 ops/ms
Iteration   3: 8.467 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.358 ±(99.9%) 2.060 ops/ms [Average]
  (min, avg, max) = (8.242, 8.358, 8.467), stdev = 0.113
  CI (99.9%): [6.297, 10.418] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.397 ops/ms
# Warmup Iteration   2: 7.480 ops/ms
# Warmup Iteration   3: 8.155 ops/ms
Iteration   1: 8.023 ops/ms
Iteration   2: 8.120 ops/ms
Iteration   3: 7.849 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.997 ±(99.9%) 2.506 ops/ms [Average]
  (min, avg, max) = (7.849, 7.997, 8.120), stdev = 0.137
  CI (99.9%): [5.491, 10.503] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.592 ops/ms
# Warmup Iteration   2: 5.086 ops/ms
# Warmup Iteration   3: 5.728 ops/ms
Iteration   1: 5.968 ops/ms
Iteration   2: 5.995 ops/ms
Iteration   3: 6.292 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.085 ±(99.9%) 3.281 ops/ms [Average]
  (min, avg, max) = (5.968, 6.085, 6.292), stdev = 0.180
  CI (99.9%): [2.804, 9.366] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.652 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.926 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.770 ±(99.9%) 0.004 ms/op
Iteration   1: 3.813 ±(99.9%) 0.002 ms/op
Iteration   2: 3.894 ±(99.9%) 0.003 ms/op
Iteration   3: 4.030 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.912 ±(99.9%) 2.002 ms/op [Average]
  (min, avg, max) = (3.813, 3.912, 4.030), stdev = 0.110
  CI (99.9%): [1.910, 5.915] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.234 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.264 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.020 ±(99.9%) 0.003 ms/op
Iteration   1: 4.040 ±(99.9%) 0.003 ms/op
Iteration   2: 3.607 ±(99.9%) 0.003 ms/op
Iteration   3: 3.712 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.787 ±(99.9%) 4.122 ms/op [Average]
  (min, avg, max) = (3.607, 3.787, 4.040), stdev = 0.226
  CI (99.9%): [≈ 0, 7.909] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.929 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.234 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.245 ±(99.9%) 0.017 ms/op
Iteration   1: 4.198 ±(99.9%) 0.004 ms/op
Iteration   2: 4.444 ±(99.9%) 0.004 ms/op
Iteration   3: 4.089 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.244 ±(99.9%) 3.324 ms/op [Average]
  (min, avg, max) = (4.089, 4.244, 4.444), stdev = 0.182
  CI (99.9%): [0.920, 7.567] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.922 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 5.645 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.454 ±(99.9%) 0.022 ms/op
Iteration   1: 5.452 ±(99.9%) 0.012 ms/op
Iteration   2: 5.521 ±(99.9%) 0.016 ms/op
Iteration   3: 5.469 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.481 ±(99.9%) 0.658 ms/op [Average]
  (min, avg, max) = (5.452, 5.481, 5.521), stdev = 0.036
  CI (99.9%): [4.823, 6.139] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.954 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.379 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.962 ±(99.9%) 0.012 ms/op
Iteration   1: 4.255 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.935 ms/op
                 createUser·p0.50:   4.092 ms/op
                 createUser·p0.90:   5.448 ms/op
                 createUser·p0.95:   6.078 ms/op
                 createUser·p0.99:   8.716 ms/op
                 createUser·p0.999:  14.178 ms/op
                 createUser·p0.9999: 16.408 ms/op
                 createUser·p1.00:   16.695 ms/op

Iteration   2: 4.026 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.886 ms/op
                 createUser·p0.50:   3.899 ms/op
                 createUser·p0.90:   5.087 ms/op
                 createUser·p0.95:   5.587 ms/op
                 createUser·p0.99:   7.422 ms/op
                 createUser·p0.999:  10.914 ms/op
                 createUser·p0.9999: 20.939 ms/op
                 createUser·p1.00:   21.496 ms/op

Iteration   3: 3.910 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.457 ms/op
                 createUser·p0.50:   3.842 ms/op
                 createUser·p0.90:   4.973 ms/op
                 createUser·p0.95:   5.423 ms/op
                 createUser·p0.99:   6.955 ms/op
                 createUser·p0.999:  10.983 ms/op
                 createUser·p0.9999: 18.731 ms/op
                 createUser·p1.00:   19.169 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 236464
  mean =      4.059 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7997 
    [ 2.500,  5.000) = 198197 
    [ 5.000,  7.500) = 27607 
    [ 7.500, 10.000) = 2024 
    [10.000, 12.500) = 379 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.457 ms/op
     p(50.0000) =      3.936 ms/op
     p(90.0000) =      5.177 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      7.692 ms/op
     p(99.9000) =     12.821 ms/op
     p(99.9900) =     20.721 ms/op
     p(99.9990) =     21.257 ms/op
     p(99.9999) =     21.496 ms/op
    p(100.0000) =     21.496 ms/op


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
# Warmup Iteration   1: 5.583 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.978 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.808 ±(99.9%) 0.010 ms/op
Iteration   1: 3.818 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.848 ms/op
                 existUser·p0.50:   3.723 ms/op
                 existUser·p0.90:   4.784 ms/op
                 existUser·p0.95:   5.341 ms/op
                 existUser·p0.99:   6.898 ms/op
                 existUser·p0.999:  10.469 ms/op
                 existUser·p0.9999: 15.827 ms/op
                 existUser·p1.00:   16.155 ms/op

Iteration   2: 3.836 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.987 ms/op
                 existUser·p0.50:   3.756 ms/op
                 existUser·p0.90:   4.678 ms/op
                 existUser·p0.95:   5.030 ms/op
                 existUser·p0.99:   6.284 ms/op
                 existUser·p0.999:  12.412 ms/op
                 existUser·p0.9999: 18.896 ms/op
                 existUser·p1.00:   19.333 ms/op

Iteration   3: 3.795 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.767 ms/op
                 existUser·p0.50:   3.686 ms/op
                 existUser·p0.90:   4.719 ms/op
                 existUser·p0.95:   5.152 ms/op
                 existUser·p0.99:   6.586 ms/op
                 existUser·p0.999:  10.678 ms/op
                 existUser·p0.9999: 18.978 ms/op
                 existUser·p1.00:   20.906 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 251456
  mean =      3.816 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7547 
    [ 2.500,  5.000) = 227813 
    [ 5.000,  7.500) = 14665 
    [ 7.500, 10.000) = 1012 
    [10.000, 12.500) = 251 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.767 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.719 ms/op
     p(95.0000) =      5.169 ms/op
     p(99.0000) =      6.636 ms/op
     p(99.9000) =     11.035 ms/op
     p(99.9900) =     18.547 ms/op
     p(99.9990) =     19.821 ms/op
     p(99.9999) =     20.906 ms/op
    p(100.0000) =     20.906 ms/op


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
# Warmup Iteration   1: 6.210 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.275 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.131 ±(99.9%) 0.011 ms/op
Iteration   1: 4.166 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.149 ms/op
                 getUser·p0.50:   4.014 ms/op
                 getUser·p0.90:   5.210 ms/op
                 getUser·p0.95:   5.767 ms/op
                 getUser·p0.99:   8.118 ms/op
                 getUser·p0.999:  13.798 ms/op
                 getUser·p0.9999: 17.421 ms/op
                 getUser·p1.00:   17.924 ms/op

Iteration   2: 4.038 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.106 ms/op
                 getUser·p0.50:   3.936 ms/op
                 getUser·p0.90:   4.997 ms/op
                 getUser·p0.95:   5.439 ms/op
                 getUser·p0.99:   6.832 ms/op
                 getUser·p0.999:  9.991 ms/op
                 getUser·p0.9999: 19.139 ms/op
                 getUser·p1.00:   19.562 ms/op

Iteration   3: 3.962 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.977 ms/op
                 getUser·p0.50:   3.879 ms/op
                 getUser·p0.90:   4.899 ms/op
                 getUser·p0.95:   5.292 ms/op
                 getUser·p0.99:   6.586 ms/op
                 getUser·p0.999:  9.430 ms/op
                 getUser·p0.9999: 17.816 ms/op
                 getUser·p1.00:   19.431 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 236746
  mean =      4.053 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 5127 
    [ 2.500,  3.750) = 85994 
    [ 3.750,  5.000) = 120559 
    [ 5.000,  6.250) = 20097 
    [ 6.250,  7.500) = 2912 
    [ 7.500,  8.750) = 1193 
    [ 8.750, 10.000) = 518 
    [10.000, 11.250) = 92 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 33 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.977 ms/op
     p(50.0000) =      3.940 ms/op
     p(90.0000) =      5.038 ms/op
     p(95.0000) =      5.489 ms/op
     p(99.0000) =      7.234 ms/op
     p(99.9000) =     10.588 ms/op
     p(99.9900) =     18.285 ms/op
     p(99.9990) =     19.494 ms/op
     p(99.9999) =     19.562 ms/op
    p(100.0000) =     19.562 ms/op


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
# Warmup Iteration   1: 7.995 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 5.841 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.409 ±(99.9%) 0.019 ms/op
Iteration   1: 5.131 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.380 ms/op
                 listUser·p0.50:   4.874 ms/op
                 listUser·p0.90:   6.652 ms/op
                 listUser·p0.95:   7.569 ms/op
                 listUser·p0.99:   10.338 ms/op
                 listUser·p0.999:  18.568 ms/op
                 listUser·p0.9999: 22.259 ms/op
                 listUser·p1.00:   24.904 ms/op

Iteration   2: 5.229 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.389 ms/op
                 listUser·p0.50:   4.964 ms/op
                 listUser·p0.90:   6.865 ms/op
                 listUser·p0.95:   7.840 ms/op
                 listUser·p0.99:   9.994 ms/op
                 listUser·p0.999:  18.607 ms/op
                 listUser·p0.9999: 25.932 ms/op
                 listUser·p1.00:   27.722 ms/op

Iteration   3: 5.136 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.559 ms/op
                 listUser·p0.50:   4.874 ms/op
                 listUser·p0.90:   6.808 ms/op
                 listUser·p0.95:   7.881 ms/op
                 listUser·p0.99:   10.322 ms/op
                 listUser·p0.999:  20.316 ms/op
                 listUser·p0.9999: 24.651 ms/op
                 listUser·p1.00:   25.068 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 185836
  mean =      5.165 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 339 
    [ 2.500,  5.000) = 100605 
    [ 5.000,  7.500) = 73585 
    [ 7.500, 10.000) = 9206 
    [10.000, 12.500) = 1466 
    [12.500, 15.000) = 253 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 124 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.380 ms/op
     p(50.0000) =      4.907 ms/op
     p(90.0000) =      6.775 ms/op
     p(95.0000) =      7.774 ms/op
     p(99.0000) =     10.224 ms/op
     p(99.9000) =     19.633 ms/op
     p(99.9900) =     24.355 ms/op
     p(99.9990) =     27.637 ms/op
     p(99.9999) =     27.722 ms/op
    p(100.0000) =     27.722 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.787 ± 8.881  ops/ms
ClientGrpc.existUser                       thrpt       3   8.358 ± 2.060  ops/ms
ClientGrpc.getUser                         thrpt       3   7.997 ± 2.506  ops/ms
ClientGrpc.listUser                        thrpt       3   6.085 ± 3.281  ops/ms
ClientGrpc.createUser                       avgt       3   3.912 ± 2.002   ms/op
ClientGrpc.existUser                        avgt       3   3.787 ± 4.122   ms/op
ClientGrpc.getUser                          avgt       3   4.244 ± 3.324   ms/op
ClientGrpc.listUser                         avgt       3   5.481 ± 0.658   ms/op
ClientGrpc.createUser                     sample  236464   4.059 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.457           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.936           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.177           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.702           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.692           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.821           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.721           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.496           ms/op
ClientGrpc.existUser                      sample  251456   3.816 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.767           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.723           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.719           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.169           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.636           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.035           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.547           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.906           ms/op
ClientGrpc.getUser                        sample  236746   4.053 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.977           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.940           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.038           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.489           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.234           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.588           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.285           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.562           ms/op
ClientGrpc.listUser                       sample  185836   5.165 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.380           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.907           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.775           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.774           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.224           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.633           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.355           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.722           ms/op
