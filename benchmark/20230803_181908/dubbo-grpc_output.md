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
# Warmup Iteration   1: 2.847 ops/ms
# Warmup Iteration   2: 6.080 ops/ms
# Warmup Iteration   3: 7.689 ops/ms
Iteration   1: 8.046 ops/ms
Iteration   2: 8.026 ops/ms
Iteration   3: 8.144 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.072 ±(99.9%) 1.155 ops/ms [Average]
  (min, avg, max) = (8.026, 8.072, 8.144), stdev = 0.063
  CI (99.9%): [6.917, 9.227] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.350 ops/ms
# Warmup Iteration   2: 8.056 ops/ms
# Warmup Iteration   3: 8.491 ops/ms
Iteration   1: 8.962 ops/ms
Iteration   2: 8.774 ops/ms
Iteration   3: 8.977 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.904 ±(99.9%) 2.066 ops/ms [Average]
  (min, avg, max) = (8.774, 8.904, 8.977), stdev = 0.113
  CI (99.9%): [6.839, 10.970] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.333 ops/ms
# Warmup Iteration   2: 7.922 ops/ms
# Warmup Iteration   3: 8.328 ops/ms
Iteration   1: 8.394 ops/ms
Iteration   2: 8.299 ops/ms
Iteration   3: 8.124 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.272 ±(99.9%) 2.504 ops/ms [Average]
  (min, avg, max) = (8.124, 8.272, 8.394), stdev = 0.137
  CI (99.9%): [5.769, 10.776] (assumes normal distribution)


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
# Warmup Iteration   1: 4.206 ops/ms
# Warmup Iteration   2: 5.931 ops/ms
# Warmup Iteration   3: 6.356 ops/ms
Iteration   1: 6.351 ops/ms
Iteration   2: 6.431 ops/ms
Iteration   3: 6.444 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.409 ±(99.9%) 0.921 ops/ms [Average]
  (min, avg, max) = (6.351, 6.409, 6.444), stdev = 0.050
  CI (99.9%): [5.488, 7.330] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.708 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.088 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.039 ±(99.9%) 0.010 ms/op
Iteration   1: 3.938 ±(99.9%) 0.008 ms/op
Iteration   2: 3.884 ±(99.9%) 0.003 ms/op
Iteration   3: 3.832 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.885 ±(99.9%) 0.966 ms/op [Average]
  (min, avg, max) = (3.832, 3.885, 3.938), stdev = 0.053
  CI (99.9%): [2.918, 4.851] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.713 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.852 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.781 ±(99.9%) 0.003 ms/op
Iteration   1: 3.682 ±(99.9%) 0.003 ms/op
Iteration   2: 3.617 ±(99.9%) 0.004 ms/op
Iteration   3: 3.686 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.661 ±(99.9%) 0.704 ms/op [Average]
  (min, avg, max) = (3.617, 3.661, 3.686), stdev = 0.039
  CI (99.9%): [2.957, 4.366] (assumes normal distribution)


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
# Warmup Iteration   1: 5.740 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.970 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.948 ±(99.9%) 0.006 ms/op
Iteration   1: 4.162 ±(99.9%) 0.009 ms/op
Iteration   2: 4.005 ±(99.9%) 0.003 ms/op
Iteration   3: 3.932 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.033 ±(99.9%) 2.148 ms/op [Average]
  (min, avg, max) = (3.932, 4.033, 4.162), stdev = 0.118
  CI (99.9%): [1.884, 6.181] (assumes normal distribution)


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
# Warmup Iteration   1: 7.019 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 5.616 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.110 ±(99.9%) 0.008 ms/op
Iteration   1: 4.810 ±(99.9%) 0.010 ms/op
Iteration   2: 5.032 ±(99.9%) 0.017 ms/op
Iteration   3: 4.987 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.943 ±(99.9%) 2.143 ms/op [Average]
  (min, avg, max) = (4.810, 4.943, 5.032), stdev = 0.117
  CI (99.9%): [2.800, 7.086] (assumes normal distribution)


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
# Warmup Iteration   1: 6.019 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.246 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.198 ±(99.9%) 0.013 ms/op
Iteration   1: 4.056 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.029 ms/op
                 createUser·p0.50:   3.973 ms/op
                 createUser·p0.90:   4.956 ms/op
                 createUser·p0.95:   5.341 ms/op
                 createUser·p0.99:   7.094 ms/op
                 createUser·p0.999:  13.096 ms/op
                 createUser·p0.9999: 20.193 ms/op
                 createUser·p1.00:   20.709 ms/op

Iteration   2: 3.962 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.038 ms/op
                 createUser·p0.50:   3.854 ms/op
                 createUser·p0.90:   4.776 ms/op
                 createUser·p0.95:   5.202 ms/op
                 createUser·p0.99:   6.660 ms/op
                 createUser·p0.999:  11.891 ms/op
                 createUser·p0.9999: 22.315 ms/op
                 createUser·p1.00:   22.807 ms/op

Iteration   3: 4.010 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.083 ms/op
                 createUser·p0.50:   3.903 ms/op
                 createUser·p0.90:   4.899 ms/op
                 createUser·p0.95:   5.251 ms/op
                 createUser·p0.99:   6.454 ms/op
                 createUser·p0.999:  12.985 ms/op
                 createUser·p0.9999: 28.149 ms/op
                 createUser·p1.00:   28.574 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 239374
  mean =      4.009 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5483 
    [ 2.500,  5.000) = 214525 
    [ 5.000,  7.500) = 17928 
    [ 7.500, 10.000) = 1020 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      1.029 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      4.882 ms/op
     p(95.0000) =      5.267 ms/op
     p(99.0000) =      6.734 ms/op
     p(99.9000) =     12.337 ms/op
     p(99.9900) =     27.558 ms/op
     p(99.9990) =     28.561 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


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
# Warmup Iteration   1: 5.407 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.028 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.856 ±(99.9%) 0.009 ms/op
Iteration   1: 3.775 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.770 ms/op
                 existUser·p0.50:   3.703 ms/op
                 existUser·p0.90:   4.588 ms/op
                 existUser·p0.95:   4.940 ms/op
                 existUser·p0.99:   6.840 ms/op
                 existUser·p0.999:  9.716 ms/op
                 existUser·p0.9999: 28.767 ms/op
                 existUser·p1.00:   29.622 ms/op

Iteration   2: 3.768 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.406 ms/op
                 existUser·p0.50:   3.674 ms/op
                 existUser·p0.90:   4.620 ms/op
                 existUser·p0.95:   5.087 ms/op
                 existUser·p0.99:   6.824 ms/op
                 existUser·p0.999:  9.486 ms/op
                 existUser·p0.9999: 32.080 ms/op
                 existUser·p1.00:   33.489 ms/op

Iteration   3: 3.778 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.983 ms/op
                 existUser·p0.50:   3.711 ms/op
                 existUser·p0.90:   4.522 ms/op
                 existUser·p0.95:   4.801 ms/op
                 existUser·p0.99:   6.308 ms/op
                 existUser·p0.999:  10.705 ms/op
                 existUser·p0.9999: 25.874 ms/op
                 existUser·p1.00:   26.280 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 254326
  mean =      3.774 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11366 
    [ 2.500,  5.000) = 231398 
    [ 5.000,  7.500) = 10081 
    [ 7.500, 10.000) = 1232 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.406 ms/op
     p(50.0000) =      3.695 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      4.948 ms/op
     p(99.0000) =      6.676 ms/op
     p(99.9000) =      9.972 ms/op
     p(99.9900) =     30.020 ms/op
     p(99.9990) =     33.456 ms/op
     p(99.9999) =     33.489 ms/op
    p(100.0000) =     33.489 ms/op


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
# Warmup Iteration   1: 5.895 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.160 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.076 ±(99.9%) 0.011 ms/op
Iteration   1: 4.003 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.104 ms/op
                 getUser·p0.50:   3.903 ms/op
                 getUser·p0.90:   4.899 ms/op
                 getUser·p0.95:   5.308 ms/op
                 getUser·p0.99:   6.776 ms/op
                 getUser·p0.999:  13.322 ms/op
                 getUser·p0.9999: 16.352 ms/op
                 getUser·p1.00:   16.548 ms/op

Iteration   2: 3.894 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.163 ms/op
                 getUser·p0.50:   3.826 ms/op
                 getUser·p0.90:   4.547 ms/op
                 getUser·p0.95:   4.932 ms/op
                 getUser·p0.99:   6.046 ms/op
                 getUser·p0.999:  8.552 ms/op
                 getUser·p0.9999: 17.367 ms/op
                 getUser·p1.00:   17.662 ms/op

Iteration   3: 3.935 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.692 ms/op
                 getUser·p0.50:   3.838 ms/op
                 getUser·p0.90:   4.948 ms/op
                 getUser·p0.95:   5.366 ms/op
                 getUser·p0.99:   7.004 ms/op
                 getUser·p0.999:  12.956 ms/op
                 getUser·p0.9999: 22.245 ms/op
                 getUser·p1.00:   22.643 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 243296
  mean =      3.944 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6861 
    [ 2.500,  5.000) = 218784 
    [ 5.000,  7.500) = 16274 
    [ 7.500, 10.000) = 1067 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.692 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      4.817 ms/op
     p(95.0000) =      5.218 ms/op
     p(99.0000) =      6.644 ms/op
     p(99.9000) =     11.846 ms/op
     p(99.9900) =     21.714 ms/op
     p(99.9990) =     22.502 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


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
# Warmup Iteration   1: 7.615 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 5.690 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.126 ±(99.9%) 0.015 ms/op
Iteration   1: 4.992 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.704 ms/op
                 listUser·p0.50:   4.817 ms/op
                 listUser·p0.90:   5.923 ms/op
                 listUser·p0.95:   7.111 ms/op
                 listUser·p0.99:   9.195 ms/op
                 listUser·p0.999:  15.087 ms/op
                 listUser·p0.9999: 20.289 ms/op
                 listUser·p1.00:   20.677 ms/op

Iteration   2: 5.071 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.343 ms/op
                 listUser·p0.50:   4.801 ms/op
                 listUser·p0.90:   6.676 ms/op
                 listUser·p0.95:   7.610 ms/op
                 listUser·p0.99:   9.585 ms/op
                 listUser·p0.999:  16.350 ms/op
                 listUser·p0.9999: 17.979 ms/op
                 listUser·p1.00:   21.496 ms/op

Iteration   3: 4.952 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.409 ms/op
                 listUser·p0.50:   4.776 ms/op
                 listUser·p0.90:   5.874 ms/op
                 listUser·p0.95:   6.930 ms/op
                 listUser·p0.99:   8.765 ms/op
                 listUser·p0.999:  20.677 ms/op
                 listUser·p0.9999: 24.284 ms/op
                 listUser·p1.00:   25.133 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 191692
  mean =      5.005 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 176 
    [ 2.500,  5.000) = 121769 
    [ 5.000,  7.500) = 61716 
    [ 7.500, 10.000) = 6907 
    [10.000, 12.500) = 710 
    [12.500, 15.000) = 145 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.343 ms/op
     p(50.0000) =      4.801 ms/op
     p(90.0000) =      6.185 ms/op
     p(95.0000) =      7.266 ms/op
     p(99.0000) =      9.224 ms/op
     p(99.9000) =     16.415 ms/op
     p(99.9900) =     22.637 ms/op
     p(99.9990) =     24.923 ms/op
     p(99.9999) =     25.133 ms/op
    p(100.0000) =     25.133 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.072 ± 1.155  ops/ms
ClientGrpc.existUser                       thrpt       3   8.904 ± 2.066  ops/ms
ClientGrpc.getUser                         thrpt       3   8.272 ± 2.504  ops/ms
ClientGrpc.listUser                        thrpt       3   6.409 ± 0.921  ops/ms
ClientGrpc.createUser                       avgt       3   3.885 ± 0.966   ms/op
ClientGrpc.existUser                        avgt       3   3.661 ± 0.704   ms/op
ClientGrpc.getUser                          avgt       3   4.033 ± 2.148   ms/op
ClientGrpc.listUser                         avgt       3   4.943 ± 2.143   ms/op
ClientGrpc.createUser                     sample  239374   4.009 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.029           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.903           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.882           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.267           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.734           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.337           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.558           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.574           ms/op
ClientGrpc.existUser                      sample  254326   3.774 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.406           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.695           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.563           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.948           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.676           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.972           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          30.020           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          33.489           ms/op
ClientGrpc.getUser                        sample  243296   3.944 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.692           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.854           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.817           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.218           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.644           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.846           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.714           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.643           ms/op
ClientGrpc.listUser                       sample  191692   5.005 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.343           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.801           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.185           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.266           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.224           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.415           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.637           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.133           ms/op
