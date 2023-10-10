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
# Warmup Iteration   1: 4.003 ops/ms
# Warmup Iteration   2: 8.560 ops/ms
# Warmup Iteration   3: 9.529 ops/ms
Iteration   1: 9.779 ops/ms
Iteration   2: 10.090 ops/ms
Iteration   3: 10.126 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.998 ±(99.9%) 3.487 ops/ms [Average]
  (min, avg, max) = (9.779, 9.998, 10.126), stdev = 0.191
  CI (99.9%): [6.512, 13.485] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 6.833 ops/ms
# Warmup Iteration   2: 9.957 ops/ms
# Warmup Iteration   3: 10.313 ops/ms
Iteration   1: 10.425 ops/ms
Iteration   2: 10.636 ops/ms
Iteration   3: 10.533 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.531 ±(99.9%) 1.927 ops/ms [Average]
  (min, avg, max) = (10.425, 10.531, 10.636), stdev = 0.106
  CI (99.9%): [8.604, 12.459] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.203 ops/ms
# Warmup Iteration   2: 9.696 ops/ms
# Warmup Iteration   3: 9.925 ops/ms
Iteration   1: 10.040 ops/ms
Iteration   2: 9.976 ops/ms
Iteration   3: 10.140 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.052 ±(99.9%) 1.508 ops/ms [Average]
  (min, avg, max) = (9.976, 10.052, 10.140), stdev = 0.083
  CI (99.9%): [8.544, 11.560] (assumes normal distribution)


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
# Warmup Iteration   1: 5.446 ops/ms
# Warmup Iteration   2: 7.658 ops/ms
# Warmup Iteration   3: 7.886 ops/ms
Iteration   1: 7.893 ops/ms
Iteration   2: 7.992 ops/ms
Iteration   3: 8.157 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.014 ±(99.9%) 2.432 ops/ms [Average]
  (min, avg, max) = (7.893, 8.014, 8.157), stdev = 0.133
  CI (99.9%): [5.582, 10.446] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.577 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.350 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.219 ±(99.9%) 0.006 ms/op
Iteration   1: 3.194 ±(99.9%) 0.005 ms/op
Iteration   2: 3.176 ±(99.9%) 0.004 ms/op
Iteration   3: 3.176 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.182 ±(99.9%) 0.184 ms/op [Average]
  (min, avg, max) = (3.176, 3.182, 3.194), stdev = 0.010
  CI (99.9%): [2.998, 3.366] (assumes normal distribution)


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
# Warmup Iteration   1: 4.327 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.228 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.079 ±(99.9%) 0.003 ms/op
Iteration   1: 3.082 ±(99.9%) 0.005 ms/op
Iteration   2: 3.153 ±(99.9%) 0.004 ms/op
Iteration   3: 3.076 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.104 ±(99.9%) 0.787 ms/op [Average]
  (min, avg, max) = (3.076, 3.104, 3.153), stdev = 0.043
  CI (99.9%): [2.316, 3.891] (assumes normal distribution)


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
# Warmup Iteration   1: 4.494 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.335 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.257 ±(99.9%) 0.002 ms/op
Iteration   1: 3.188 ±(99.9%) 0.004 ms/op
Iteration   2: 3.142 ±(99.9%) 0.005 ms/op
Iteration   3: 3.158 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.163 ±(99.9%) 0.425 ms/op [Average]
  (min, avg, max) = (3.142, 3.163, 3.188), stdev = 0.023
  CI (99.9%): [2.738, 3.587] (assumes normal distribution)


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
# Warmup Iteration   1: 5.569 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.089 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.024 ±(99.9%) 0.040 ms/op
Iteration   1: 4.017 ±(99.9%) 0.018 ms/op
Iteration   2: 3.859 ±(99.9%) 0.023 ms/op
Iteration   3: 3.966 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.947 ±(99.9%) 1.464 ms/op [Average]
  (min, avg, max) = (3.859, 3.947, 4.017), stdev = 0.080
  CI (99.9%): [2.484, 5.411] (assumes normal distribution)


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
# Warmup Iteration   1: 4.622 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.348 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.176 ±(99.9%) 0.006 ms/op
Iteration   1: 3.173 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.911 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   4.014 ms/op
                 createUser·p0.99:   4.981 ms/op
                 createUser·p0.999:  9.015 ms/op
                 createUser·p0.9999: 13.696 ms/op
                 createUser·p1.00:   15.270 ms/op

Iteration   2: 3.168 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.987 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   3.908 ms/op
                 createUser·p0.99:   4.620 ms/op
                 createUser·p0.999:  9.321 ms/op
                 createUser·p0.9999: 17.138 ms/op
                 createUser·p1.00:   18.088 ms/op

Iteration   3: 3.150 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.313 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.944 ms/op
                 createUser·p0.99:   4.645 ms/op
                 createUser·p0.999:  11.813 ms/op
                 createUser·p0.9999: 29.518 ms/op
                 createUser·p1.00:   42.533 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 303655
  mean =      3.164 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 301228 
    [ 5.000, 10.000) = 2072 
    [10.000, 15.000) = 198 
    [15.000, 20.000) = 125 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 28 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.313 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      3.957 ms/op
     p(99.0000) =      4.780 ms/op
     p(99.9000) =     10.950 ms/op
     p(99.9900) =     27.591 ms/op
     p(99.9990) =     42.266 ms/op
     p(99.9999) =     42.533 ms/op
    p(100.0000) =     42.533 ms/op


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
# Warmup Iteration   1: 4.267 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.193 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.006 ms/op
Iteration   1: 3.023 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.794 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.448 ms/op
                 existUser·p0.999:  8.151 ms/op
                 existUser·p0.9999: 13.441 ms/op
                 existUser·p1.00:   17.433 ms/op

Iteration   2: 2.979 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.770 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  6.947 ms/op
                 existUser·p0.9999: 23.327 ms/op
                 existUser·p1.00:   24.871 ms/op

Iteration   3: 3.024 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.656 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   4.891 ms/op
                 existUser·p0.999:  10.938 ms/op
                 existUser·p0.9999: 18.345 ms/op
                 existUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 319242
  mean =      3.008 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24839 
    [ 2.500,  5.000) = 292410 
    [ 5.000,  7.500) = 1470 
    [ 7.500, 10.000) = 207 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.656 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.695 ms/op
     p(99.0000) =      4.637 ms/op
     p(99.9000) =      9.974 ms/op
     p(99.9900) =     18.088 ms/op
     p(99.9990) =     24.674 ms/op
     p(99.9999) =     24.871 ms/op
    p(100.0000) =     24.871 ms/op


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
# Warmup Iteration   1: 4.838 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.297 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.207 ±(99.9%) 0.006 ms/op
Iteration   1: 3.236 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.564 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.039 ms/op
                 getUser·p0.99:   4.710 ms/op
                 getUser·p0.999:  8.460 ms/op
                 getUser·p0.9999: 14.190 ms/op
                 getUser·p1.00:   14.500 ms/op

Iteration   2: 3.157 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.602 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   4.801 ms/op
                 getUser·p0.999:  8.004 ms/op
                 getUser·p0.9999: 20.668 ms/op
                 getUser·p1.00:   21.103 ms/op

Iteration   3: 3.208 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.420 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  8.262 ms/op
                 getUser·p0.9999: 17.993 ms/op
                 getUser·p1.00:   18.416 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 299872
  mean =      3.200 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9825 
    [ 2.500,  5.000) = 288127 
    [ 5.000,  7.500) = 1514 
    [ 7.500, 10.000) = 188 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.420 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      4.655 ms/op
     p(99.9000) =      8.225 ms/op
     p(99.9900) =     18.350 ms/op
     p(99.9990) =     21.004 ms/op
     p(99.9999) =     21.103 ms/op
    p(100.0000) =     21.103 ms/op


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
# Warmup Iteration   1: 5.592 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.292 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.045 ±(99.9%) 0.011 ms/op
Iteration   1: 3.992 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.386 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   6.781 ms/op
                 listUser·p0.999:  14.252 ms/op
                 listUser·p0.9999: 17.727 ms/op
                 listUser·p1.00:   18.285 ms/op

Iteration   2: 4.005 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.702 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  14.731 ms/op
                 listUser·p0.9999: 16.597 ms/op
                 listUser·p1.00:   17.433 ms/op

Iteration   3: 3.958 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.057 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   5.112 ms/op
                 listUser·p0.99:   7.094 ms/op
                 listUser·p0.999:  16.824 ms/op
                 listUser·p0.9999: 36.688 ms/op
                 listUser·p1.00:   37.356 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240910
  mean =      3.985 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2271 
    [ 2.500,  5.000) = 221933 
    [ 5.000,  7.500) = 15148 
    [ 7.500, 10.000) = 941 
    [10.000, 12.500) = 162 
    [12.500, 15.000) = 245 
    [15.000, 17.500) = 142 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.702 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      5.571 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     14.729 ms/op
     p(99.9900) =     31.749 ms/op
     p(99.9990) =     37.183 ms/op
     p(99.9999) =     37.356 ms/op
    p(100.0000) =     37.356 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.998 ± 3.487  ops/ms
ClientGrpc.existUser                       thrpt       3  10.531 ± 1.927  ops/ms
ClientGrpc.getUser                         thrpt       3  10.052 ± 1.508  ops/ms
ClientGrpc.listUser                        thrpt       3   8.014 ± 2.432  ops/ms
ClientGrpc.createUser                       avgt       3   3.182 ± 0.184   ms/op
ClientGrpc.existUser                        avgt       3   3.104 ± 0.787   ms/op
ClientGrpc.getUser                          avgt       3   3.163 ± 0.425   ms/op
ClientGrpc.listUser                         avgt       3   3.947 ± 1.464   ms/op
ClientGrpc.createUser                     sample  303655   3.164 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.313           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.109           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.707           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.957           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.780           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.950           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.591           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          42.533           ms/op
ClientGrpc.existUser                      sample  319242   3.008 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.656           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.978           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.498           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.695           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.637           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.974           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.088           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.871           ms/op
ClientGrpc.getUser                        sample  299872   3.200 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.420           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.158           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.805           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.994           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.655           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.225           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.350           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.103           ms/op
ClientGrpc.listUser                       sample  240910   3.985 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.702           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.871           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.530           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.571           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.980           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.729           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.749           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          37.356           ms/op
