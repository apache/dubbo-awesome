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
# Warmup Iteration   1: 2.232 ops/ms
# Warmup Iteration   2: 5.276 ops/ms
# Warmup Iteration   3: 6.931 ops/ms
Iteration   1: 7.174 ops/ms
Iteration   2: 7.173 ops/ms
Iteration   3: 7.217 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.188 ±(99.9%) 0.462 ops/ms [Average]
  (min, avg, max) = (7.173, 7.188, 7.217), stdev = 0.025
  CI (99.9%): [6.726, 7.650] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.659 ops/ms
# Warmup Iteration   2: 7.010 ops/ms
# Warmup Iteration   3: 7.417 ops/ms
Iteration   1: 7.791 ops/ms
Iteration   2: 7.984 ops/ms
Iteration   3: 7.993 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.923 ±(99.9%) 2.083 ops/ms [Average]
  (min, avg, max) = (7.791, 7.923, 7.993), stdev = 0.114
  CI (99.9%): [5.840, 10.006] (assumes normal distribution)


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
# Warmup Iteration   1: 4.331 ops/ms
# Warmup Iteration   2: 6.710 ops/ms
# Warmup Iteration   3: 7.063 ops/ms
Iteration   1: 7.014 ops/ms
Iteration   2: 7.008 ops/ms
Iteration   3: 7.167 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.063 ±(99.9%) 1.639 ops/ms [Average]
  (min, avg, max) = (7.008, 7.063, 7.167), stdev = 0.090
  CI (99.9%): [5.424, 8.701] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.654 ops/ms
# Warmup Iteration   2: 5.279 ops/ms
# Warmup Iteration   3: 5.463 ops/ms
Iteration   1: 5.697 ops/ms
Iteration   2: 5.549 ops/ms
Iteration   3: 5.770 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.672 ±(99.9%) 2.055 ops/ms [Average]
  (min, avg, max) = (5.549, 5.672, 5.770), stdev = 0.113
  CI (99.9%): [3.616, 7.727] (assumes normal distribution)


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
# Warmup Iteration   1: 7.127 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.812 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.492 ±(99.9%) 0.006 ms/op
Iteration   1: 4.284 ±(99.9%) 0.004 ms/op
Iteration   2: 4.230 ±(99.9%) 0.004 ms/op
Iteration   3: 4.309 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.274 ±(99.9%) 0.739 ms/op [Average]
  (min, avg, max) = (4.230, 4.274, 4.309), stdev = 0.040
  CI (99.9%): [3.536, 5.013] (assumes normal distribution)


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
# Warmup Iteration   1: 6.849 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.444 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.236 ±(99.9%) 0.002 ms/op
Iteration   1: 4.037 ±(99.9%) 0.002 ms/op
Iteration   2: 4.028 ±(99.9%) 0.003 ms/op
Iteration   3: 4.212 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.093 ±(99.9%) 1.892 ms/op [Average]
  (min, avg, max) = (4.028, 4.093, 4.212), stdev = 0.104
  CI (99.9%): [2.201, 5.984] (assumes normal distribution)


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
# Warmup Iteration   1: 7.213 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.600 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.376 ±(99.9%) 0.004 ms/op
Iteration   1: 4.302 ±(99.9%) 0.004 ms/op
Iteration   2: 4.336 ±(99.9%) 0.005 ms/op
Iteration   3: 4.262 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.300 ±(99.9%) 0.672 ms/op [Average]
  (min, avg, max) = (4.262, 4.300, 4.336), stdev = 0.037
  CI (99.9%): [3.628, 4.972] (assumes normal distribution)


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
# Warmup Iteration   1: 8.709 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 6.002 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.765 ±(99.9%) 0.021 ms/op
Iteration   1: 5.775 ±(99.9%) 0.015 ms/op
Iteration   2: 5.777 ±(99.9%) 0.019 ms/op
Iteration   3: 5.650 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.734 ±(99.9%) 1.329 ms/op [Average]
  (min, avg, max) = (5.650, 5.734, 5.777), stdev = 0.073
  CI (99.9%): [4.405, 7.063] (assumes normal distribution)


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
# Warmup Iteration   1: 6.969 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.862 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.574 ±(99.9%) 0.015 ms/op
Iteration   1: 4.408 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.200 ms/op
                 createUser·p0.50:   4.243 ms/op
                 createUser·p0.90:   5.743 ms/op
                 createUser·p0.95:   6.291 ms/op
                 createUser·p0.99:   7.987 ms/op
                 createUser·p0.999:  10.764 ms/op
                 createUser·p0.9999: 16.973 ms/op
                 createUser·p1.00:   18.285 ms/op

Iteration   2: 4.506 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.204 ms/op
                 createUser·p0.50:   4.317 ms/op
                 createUser·p0.90:   5.825 ms/op
                 createUser·p0.95:   6.472 ms/op
                 createUser·p0.99:   8.428 ms/op
                 createUser·p0.999:  12.255 ms/op
                 createUser·p0.9999: 20.644 ms/op
                 createUser·p1.00:   21.594 ms/op

Iteration   3: 4.373 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.777 ms/op
                 createUser·p0.50:   4.211 ms/op
                 createUser·p0.90:   5.661 ms/op
                 createUser·p0.95:   6.349 ms/op
                 createUser·p0.99:   8.585 ms/op
                 createUser·p0.999:  15.661 ms/op
                 createUser·p0.9999: 26.906 ms/op
                 createUser·p1.00:   28.115 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 216703
  mean =      4.429 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4580 
    [ 2.500,  5.000) = 161655 
    [ 5.000,  7.500) = 46453 
    [ 7.500, 10.000) = 3342 
    [10.000, 12.500) = 462 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.777 ms/op
     p(50.0000) =      4.260 ms/op
     p(90.0000) =      5.743 ms/op
     p(95.0000) =      6.373 ms/op
     p(99.0000) =      8.339 ms/op
     p(99.9000) =     12.391 ms/op
     p(99.9900) =     24.543 ms/op
     p(99.9990) =     27.733 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


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
# Warmup Iteration   1: 6.301 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.495 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.209 ±(99.9%) 0.014 ms/op
Iteration   1: 4.201 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.996 ms/op
                 existUser·p0.50:   4.006 ms/op
                 existUser·p0.90:   5.349 ms/op
                 existUser·p0.95:   6.070 ms/op
                 existUser·p0.99:   8.225 ms/op
                 existUser·p0.999:  14.760 ms/op
                 existUser·p0.9999: 21.927 ms/op
                 existUser·p1.00:   22.184 ms/op

Iteration   2: 4.074 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.907 ms/op
                 existUser·p0.50:   3.895 ms/op
                 existUser·p0.90:   5.169 ms/op
                 existUser·p0.95:   5.808 ms/op
                 existUser·p0.99:   8.946 ms/op
                 existUser·p0.999:  13.009 ms/op
                 existUser·p0.9999: 20.391 ms/op
                 existUser·p1.00:   20.677 ms/op

Iteration   3: 4.144 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.907 ms/op
                 existUser·p0.50:   3.981 ms/op
                 existUser·p0.90:   5.308 ms/op
                 existUser·p0.95:   5.865 ms/op
                 existUser·p0.99:   7.758 ms/op
                 existUser·p0.999:  12.988 ms/op
                 existUser·p0.9999: 20.882 ms/op
                 existUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 231871
  mean =      4.139 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6964 
    [ 2.500,  5.000) = 192126 
    [ 5.000,  7.500) = 29127 
    [ 7.500, 10.000) = 2631 
    [10.000, 12.500) = 689 
    [12.500, 15.000) = 166 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.907 ms/op
     p(50.0000) =      3.957 ms/op
     p(90.0000) =      5.276 ms/op
     p(95.0000) =      5.906 ms/op
     p(99.0000) =      8.315 ms/op
     p(99.9000) =     13.290 ms/op
     p(99.9900) =     21.201 ms/op
     p(99.9990) =     22.173 ms/op
     p(99.9999) =     22.610 ms/op
    p(100.0000) =     22.610 ms/op


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
# Warmup Iteration   1: 6.590 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.674 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.534 ±(99.9%) 0.014 ms/op
Iteration   1: 4.502 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.167 ms/op
                 getUser·p0.50:   4.301 ms/op
                 getUser·p0.90:   5.825 ms/op
                 getUser·p0.95:   6.529 ms/op
                 getUser·p0.99:   8.503 ms/op
                 getUser·p0.999:  13.844 ms/op
                 getUser·p0.9999: 17.334 ms/op
                 getUser·p1.00:   17.760 ms/op

Iteration   2: 4.533 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.231 ms/op
                 getUser·p0.50:   4.325 ms/op
                 getUser·p0.90:   5.915 ms/op
                 getUser·p0.95:   6.636 ms/op
                 getUser·p0.99:   9.110 ms/op
                 getUser·p0.999:  15.364 ms/op
                 getUser·p0.9999: 22.671 ms/op
                 getUser·p1.00:   24.019 ms/op

Iteration   3: 4.276 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.854 ms/op
                 getUser·p0.50:   4.133 ms/op
                 getUser·p0.90:   5.571 ms/op
                 getUser·p0.95:   6.234 ms/op
                 getUser·p0.99:   8.143 ms/op
                 getUser·p0.999:  14.045 ms/op
                 getUser·p0.9999: 21.349 ms/op
                 getUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 216423
  mean =      4.434 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6038 
    [ 2.500,  5.000) = 160329 
    [ 5.000,  7.500) = 45535 
    [ 7.500, 10.000) = 3565 
    [10.000, 12.500) = 640 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.854 ms/op
     p(50.0000) =      4.243 ms/op
     p(90.0000) =      5.775 ms/op
     p(95.0000) =      6.472 ms/op
     p(99.0000) =      8.602 ms/op
     p(99.9000) =     14.224 ms/op
     p(99.9900) =     22.065 ms/op
     p(99.9990) =     23.757 ms/op
     p(99.9999) =     24.019 ms/op
    p(100.0000) =     24.019 ms/op


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
# Warmup Iteration   1: 8.076 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 6.091 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.551 ±(99.9%) 0.022 ms/op
Iteration   1: 5.717 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.997 ms/op
                 listUser·p0.50:   5.308 ms/op
                 listUser·p0.90:   7.815 ms/op
                 listUser·p0.95:   8.847 ms/op
                 listUser·p0.99:   11.911 ms/op
                 listUser·p0.999:  17.859 ms/op
                 listUser·p0.9999: 21.218 ms/op
                 listUser·p1.00:   22.086 ms/op

Iteration   2: 5.693 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.677 ms/op
                 listUser·p0.50:   5.341 ms/op
                 listUser·p0.90:   7.635 ms/op
                 listUser·p0.95:   8.700 ms/op
                 listUser·p0.99:   11.239 ms/op
                 listUser·p0.999:  18.907 ms/op
                 listUser·p0.9999: 27.177 ms/op
                 listUser·p1.00:   28.803 ms/op

Iteration   3: 5.565 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.075 ms/op
                 listUser·p0.50:   5.161 ms/op
                 listUser·p0.90:   7.553 ms/op
                 listUser·p0.95:   8.749 ms/op
                 listUser·p0.99:   11.985 ms/op
                 listUser·p0.999:  22.101 ms/op
                 listUser·p0.9999: 31.475 ms/op
                 listUser·p1.00:   33.128 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 169771
  mean =      5.658 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 169 
    [ 2.500,  5.000) = 66189 
    [ 5.000,  7.500) = 84605 
    [ 7.500, 10.000) = 14506 
    [10.000, 12.500) = 3108 
    [12.500, 15.000) = 622 
    [15.000, 17.500) = 259 
    [17.500, 20.000) = 186 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.075 ms/op
     p(50.0000) =      5.276 ms/op
     p(90.0000) =      7.668 ms/op
     p(95.0000) =      8.765 ms/op
     p(99.0000) =     11.715 ms/op
     p(99.9000) =     19.177 ms/op
     p(99.9900) =     30.803 ms/op
     p(99.9990) =     32.237 ms/op
     p(99.9999) =     33.128 ms/op
    p(100.0000) =     33.128 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.188 ± 0.462  ops/ms
ClientGrpc.existUser                       thrpt       3   7.923 ± 2.083  ops/ms
ClientGrpc.getUser                         thrpt       3   7.063 ± 1.639  ops/ms
ClientGrpc.listUser                        thrpt       3   5.672 ± 2.055  ops/ms
ClientGrpc.createUser                       avgt       3   4.274 ± 0.739   ms/op
ClientGrpc.existUser                        avgt       3   4.093 ± 1.892   ms/op
ClientGrpc.getUser                          avgt       3   4.300 ± 0.672   ms/op
ClientGrpc.listUser                         avgt       3   5.734 ± 1.329   ms/op
ClientGrpc.createUser                     sample  216703   4.429 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.777           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.260           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.743           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.373           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.339           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.391           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.543           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.115           ms/op
ClientGrpc.existUser                      sample  231871   4.139 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.907           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.957           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.276           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.906           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.315           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.290           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.201           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.610           ms/op
ClientGrpc.getUser                        sample  216423   4.434 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.854           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.243           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.775           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.472           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.602           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.224           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.065           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.019           ms/op
ClientGrpc.listUser                       sample  169771   5.658 ± 0.014   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.075           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.276           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.668           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.765           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.715           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.177           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.803           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.128           ms/op
