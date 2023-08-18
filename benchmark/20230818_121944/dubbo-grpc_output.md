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
# Warmup Iteration   1: 2.469 ops/ms
# Warmup Iteration   2: 6.629 ops/ms
# Warmup Iteration   3: 8.048 ops/ms
Iteration   1: 8.151 ops/ms
Iteration   2: 8.800 ops/ms
Iteration   3: 8.612 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.521 ±(99.9%) 6.095 ops/ms [Average]
  (min, avg, max) = (8.151, 8.521, 8.800), stdev = 0.334
  CI (99.9%): [2.426, 14.616] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.564 ops/ms
# Warmup Iteration   2: 8.514 ops/ms
# Warmup Iteration   3: 8.845 ops/ms
Iteration   1: 9.064 ops/ms
Iteration   2: 9.457 ops/ms
Iteration   3: 9.173 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.232 ±(99.9%) 3.701 ops/ms [Average]
  (min, avg, max) = (9.064, 9.232, 9.457), stdev = 0.203
  CI (99.9%): [5.531, 12.932] (assumes normal distribution)


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
# Warmup Iteration   1: 5.130 ops/ms
# Warmup Iteration   2: 7.957 ops/ms
# Warmup Iteration   3: 8.226 ops/ms
Iteration   1: 8.741 ops/ms
Iteration   2: 8.587 ops/ms
Iteration   3: 8.178 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.502 ±(99.9%) 5.302 ops/ms [Average]
  (min, avg, max) = (8.178, 8.502, 8.741), stdev = 0.291
  CI (99.9%): [3.200, 13.804] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.518 ops/ms
# Warmup Iteration   2: 5.726 ops/ms
# Warmup Iteration   3: 6.198 ops/ms
Iteration   1: 6.189 ops/ms
Iteration   2: 6.094 ops/ms
Iteration   3: 6.300 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.194 ±(99.9%) 1.873 ops/ms [Average]
  (min, avg, max) = (6.094, 6.194, 6.300), stdev = 0.103
  CI (99.9%): [4.321, 8.068] (assumes normal distribution)


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
# Warmup Iteration   1: 5.335 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.200 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.991 ±(99.9%) 0.003 ms/op
Iteration   1: 3.848 ±(99.9%) 0.004 ms/op
Iteration   2: 3.859 ±(99.9%) 0.003 ms/op
Iteration   3: 3.764 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.824 ±(99.9%) 0.943 ms/op [Average]
  (min, avg, max) = (3.764, 3.824, 3.859), stdev = 0.052
  CI (99.9%): [2.881, 4.767] (assumes normal distribution)


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
# Warmup Iteration   1: 5.382 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.668 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.598 ±(99.9%) 0.006 ms/op
Iteration   1: 3.616 ±(99.9%) 0.002 ms/op
Iteration   2: 3.537 ±(99.9%) 0.001 ms/op
Iteration   3: 3.466 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.539 ±(99.9%) 1.366 ms/op [Average]
  (min, avg, max) = (3.466, 3.539, 3.616), stdev = 0.075
  CI (99.9%): [2.173, 4.905] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.478 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.973 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.789 ±(99.9%) 0.007 ms/op
Iteration   1: 3.872 ±(99.9%) 0.004 ms/op
Iteration   2: 3.837 ±(99.9%) 0.002 ms/op
Iteration   3: 3.745 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.818 ±(99.9%) 1.201 ms/op [Average]
  (min, avg, max) = (3.745, 3.818, 3.872), stdev = 0.066
  CI (99.9%): [2.617, 5.019] (assumes normal distribution)


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
# Warmup Iteration   1: 6.356 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 5.375 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.079 ±(99.9%) 0.020 ms/op
Iteration   1: 5.076 ±(99.9%) 0.018 ms/op
Iteration   2: 5.038 ±(99.9%) 0.022 ms/op
Iteration   3: 5.167 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.094 ±(99.9%) 1.214 ms/op [Average]
  (min, avg, max) = (5.038, 5.094, 5.167), stdev = 0.067
  CI (99.9%): [3.880, 6.308] (assumes normal distribution)


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
# Warmup Iteration   1: 5.701 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.118 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.940 ±(99.9%) 0.012 ms/op
Iteration   1: 3.827 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.951 ms/op
                 createUser·p0.50:   3.678 ms/op
                 createUser·p0.90:   4.801 ms/op
                 createUser·p0.95:   5.218 ms/op
                 createUser·p0.99:   6.816 ms/op
                 createUser·p0.999:  11.169 ms/op
                 createUser·p0.9999: 27.186 ms/op
                 createUser·p1.00:   27.558 ms/op

Iteration   2: 3.823 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.795 ms/op
                 createUser·p0.50:   3.719 ms/op
                 createUser·p0.90:   4.784 ms/op
                 createUser·p0.95:   5.243 ms/op
                 createUser·p0.99:   6.636 ms/op
                 createUser·p0.999:  14.845 ms/op
                 createUser·p0.9999: 20.042 ms/op
                 createUser·p1.00:   20.546 ms/op

Iteration   3: 3.735 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.149 ms/op
                 createUser·p0.50:   3.621 ms/op
                 createUser·p0.90:   4.710 ms/op
                 createUser·p0.95:   5.145 ms/op
                 createUser·p0.99:   6.234 ms/op
                 createUser·p0.999:  9.508 ms/op
                 createUser·p0.9999: 21.987 ms/op
                 createUser·p1.00:   24.347 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 252873
  mean =      3.795 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5379 
    [ 2.500,  5.000) = 230221 
    [ 5.000,  7.500) = 15883 
    [ 7.500, 10.000) = 1002 
    [10.000, 12.500) = 174 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.795 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.768 ms/op
     p(95.0000) =      5.202 ms/op
     p(99.0000) =      6.578 ms/op
     p(99.9000) =     11.457 ms/op
     p(99.9900) =     26.598 ms/op
     p(99.9990) =     27.425 ms/op
     p(99.9999) =     27.558 ms/op
    p(100.0000) =     27.558 ms/op


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
# Warmup Iteration   1: 4.937 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.085 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.632 ±(99.9%) 0.011 ms/op
Iteration   1: 3.511 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.584 ms/op
                 existUser·p0.50:   3.416 ms/op
                 existUser·p0.90:   4.456 ms/op
                 existUser·p0.95:   4.882 ms/op
                 existUser·p0.99:   6.169 ms/op
                 existUser·p0.999:  10.008 ms/op
                 existUser·p0.9999: 15.100 ms/op
                 existUser·p1.00:   15.679 ms/op

Iteration   2: 3.829 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.915 ms/op
                 existUser·p0.50:   3.690 ms/op
                 existUser·p0.90:   4.768 ms/op
                 existUser·p0.95:   5.226 ms/op
                 existUser·p0.99:   7.365 ms/op
                 existUser·p0.999:  15.070 ms/op
                 existUser·p0.9999: 31.577 ms/op
                 existUser·p1.00:   32.539 ms/op

Iteration   3: 3.504 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.820 ms/op
                 existUser·p0.50:   3.404 ms/op
                 existUser·p0.90:   4.399 ms/op
                 existUser·p0.95:   4.801 ms/op
                 existUser·p0.99:   5.784 ms/op
                 existUser·p0.999:  8.195 ms/op
                 existUser·p0.9999: 21.979 ms/op
                 existUser·p1.00:   23.167 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 266051
  mean =      3.609 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11107 
    [ 2.500,  5.000) = 242341 
    [ 5.000,  7.500) = 11292 
    [ 7.500, 10.000) = 998 
    [10.000, 12.500) = 137 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.584 ms/op
     p(50.0000) =      3.498 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      4.964 ms/op
     p(99.0000) =      6.439 ms/op
     p(99.9000) =     10.369 ms/op
     p(99.9900) =     30.769 ms/op
     p(99.9990) =     32.408 ms/op
     p(99.9999) =     32.539 ms/op
    p(100.0000) =     32.539 ms/op


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
# Warmup Iteration   1: 5.591 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.181 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.954 ±(99.9%) 0.013 ms/op
Iteration   1: 3.896 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.943 ms/op
                 getUser·p0.50:   3.785 ms/op
                 getUser·p0.90:   4.932 ms/op
                 getUser·p0.95:   5.431 ms/op
                 getUser·p0.99:   7.021 ms/op
                 getUser·p0.999:  9.535 ms/op
                 getUser·p0.9999: 14.886 ms/op
                 getUser·p1.00:   15.139 ms/op

Iteration   2: 3.819 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.057 ms/op
                 getUser·p0.50:   3.703 ms/op
                 getUser·p0.90:   4.891 ms/op
                 getUser·p0.95:   5.358 ms/op
                 getUser·p0.99:   6.611 ms/op
                 getUser·p0.999:  11.030 ms/op
                 getUser·p0.9999: 23.240 ms/op
                 getUser·p1.00:   25.100 ms/op

Iteration   3: 3.822 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.934 ms/op
                 getUser·p0.50:   3.715 ms/op
                 getUser·p0.90:   4.801 ms/op
                 getUser·p0.95:   5.169 ms/op
                 getUser·p0.99:   6.226 ms/op
                 getUser·p0.999:  11.928 ms/op
                 getUser·p0.9999: 19.137 ms/op
                 getUser·p1.00:   20.480 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 249679
  mean =      3.845 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7030 
    [ 2.500,  5.000) = 222282 
    [ 5.000,  7.500) = 19041 
    [ 7.500, 10.000) = 1046 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.934 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.874 ms/op
     p(95.0000) =      5.317 ms/op
     p(99.0000) =      6.644 ms/op
     p(99.9000) =     10.469 ms/op
     p(99.9900) =     22.349 ms/op
     p(99.9990) =     24.953 ms/op
     p(99.9999) =     25.100 ms/op
    p(100.0000) =     25.100 ms/op


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
# Warmup Iteration   1: 7.517 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 5.289 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.980 ±(99.9%) 0.018 ms/op
Iteration   1: 5.011 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.769 ms/op
                 listUser·p0.50:   4.768 ms/op
                 listUser·p0.90:   6.545 ms/op
                 listUser·p0.95:   7.471 ms/op
                 listUser·p0.99:   9.765 ms/op
                 listUser·p0.999:  13.542 ms/op
                 listUser·p0.9999: 18.958 ms/op
                 listUser·p1.00:   19.956 ms/op

Iteration   2: 4.967 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   0.941 ms/op
                 listUser·p0.50:   4.743 ms/op
                 listUser·p0.90:   6.365 ms/op
                 listUser·p0.95:   7.307 ms/op
                 listUser·p0.99:   9.142 ms/op
                 listUser·p0.999:  23.627 ms/op
                 listUser·p0.9999: 26.174 ms/op
                 listUser·p1.00:   26.771 ms/op

Iteration   3: 4.949 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.048 ms/op
                 listUser·p0.50:   4.669 ms/op
                 listUser·p0.90:   6.652 ms/op
                 listUser·p0.95:   7.496 ms/op
                 listUser·p0.99:   9.667 ms/op
                 listUser·p0.999:  18.186 ms/op
                 listUser·p0.9999: 24.891 ms/op
                 listUser·p1.00:   25.395 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 192912
  mean =      4.976 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 309 
    [ 2.500,  5.000) = 118087 
    [ 5.000,  7.500) = 65398 
    [ 7.500, 10.000) = 7727 
    [10.000, 12.500) = 895 
    [12.500, 15.000) = 220 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 106 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.941 ms/op
     p(50.0000) =      4.727 ms/op
     p(90.0000) =      6.529 ms/op
     p(95.0000) =      7.430 ms/op
     p(99.0000) =      9.517 ms/op
     p(99.9000) =     17.605 ms/op
     p(99.9900) =     24.927 ms/op
     p(99.9990) =     26.558 ms/op
     p(99.9999) =     26.771 ms/op
    p(100.0000) =     26.771 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.521 ± 6.095  ops/ms
ClientGrpc.existUser                       thrpt       3   9.232 ± 3.701  ops/ms
ClientGrpc.getUser                         thrpt       3   8.502 ± 5.302  ops/ms
ClientGrpc.listUser                        thrpt       3   6.194 ± 1.873  ops/ms
ClientGrpc.createUser                       avgt       3   3.824 ± 0.943   ms/op
ClientGrpc.existUser                        avgt       3   3.539 ± 1.366   ms/op
ClientGrpc.getUser                          avgt       3   3.818 ± 1.201   ms/op
ClientGrpc.listUser                         avgt       3   5.094 ± 1.214   ms/op
ClientGrpc.createUser                     sample  252873   3.795 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.795           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.674           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.768           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.202           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.578           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.457           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.598           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.558           ms/op
ClientGrpc.existUser                      sample  266051   3.609 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.584           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.498           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.555           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.964           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.439           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.369           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          30.769           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          32.539           ms/op
ClientGrpc.getUser                        sample  249679   3.845 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.934           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.736           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.874           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.317           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.644           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.469           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.349           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.100           ms/op
ClientGrpc.listUser                       sample  192912   4.976 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.941           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.727           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.529           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.430           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.517           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.605           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.927           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.771           ms/op
