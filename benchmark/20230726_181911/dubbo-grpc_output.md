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
# Warmup Iteration   1: 4.006 ops/ms
# Warmup Iteration   2: 8.450 ops/ms
# Warmup Iteration   3: 9.867 ops/ms
Iteration   1: 10.544 ops/ms
Iteration   2: 10.447 ops/ms
Iteration   3: 10.220 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.403 ±(99.9%) 3.031 ops/ms [Average]
  (min, avg, max) = (10.220, 10.403, 10.544), stdev = 0.166
  CI (99.9%): [7.372, 13.435] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.185 ops/ms
# Warmup Iteration   2: 10.401 ops/ms
# Warmup Iteration   3: 11.012 ops/ms
Iteration   1: 10.991 ops/ms
Iteration   2: 10.980 ops/ms
Iteration   3: 11.000 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.990 ±(99.9%) 0.184 ops/ms [Average]
  (min, avg, max) = (10.980, 10.990, 11.000), stdev = 0.010
  CI (99.9%): [10.806, 11.175] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.655 ops/ms
# Warmup Iteration   2: 9.988 ops/ms
# Warmup Iteration   3: 10.224 ops/ms
Iteration   1: 10.453 ops/ms
Iteration   2: 10.302 ops/ms
Iteration   3: 10.573 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.443 ±(99.9%) 2.483 ops/ms [Average]
  (min, avg, max) = (10.302, 10.443, 10.573), stdev = 0.136
  CI (99.9%): [7.960, 12.925] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.180 ops/ms
# Warmup Iteration   2: 7.406 ops/ms
# Warmup Iteration   3: 7.767 ops/ms
Iteration   1: 7.869 ops/ms
Iteration   2: 7.799 ops/ms
Iteration   3: 7.745 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.804 ±(99.9%) 1.128 ops/ms [Average]
  (min, avg, max) = (7.745, 7.804, 7.869), stdev = 0.062
  CI (99.9%): [6.676, 8.933] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.598 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.281 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.004 ms/op
Iteration   1: 3.062 ±(99.9%) 0.003 ms/op
Iteration   2: 3.049 ±(99.9%) 0.002 ms/op
Iteration   3: 3.045 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.052 ±(99.9%) 0.168 ms/op [Average]
  (min, avg, max) = (3.045, 3.052, 3.062), stdev = 0.009
  CI (99.9%): [2.884, 3.220] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.184 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.030 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.983 ±(99.9%) 0.002 ms/op
Iteration   1: 2.942 ±(99.9%) 0.004 ms/op
Iteration   2: 3.009 ±(99.9%) 0.003 ms/op
Iteration   3: 2.917 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.956 ±(99.9%) 0.871 ms/op [Average]
  (min, avg, max) = (2.917, 2.956, 3.009), stdev = 0.048
  CI (99.9%): [2.085, 3.827] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.134 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.252 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.134 ±(99.9%) 0.004 ms/op
Iteration   1: 3.115 ±(99.9%) 0.003 ms/op
Iteration   2: 3.086 ±(99.9%) 0.003 ms/op
Iteration   3: 3.063 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.088 ±(99.9%) 0.472 ms/op [Average]
  (min, avg, max) = (3.063, 3.088, 3.115), stdev = 0.026
  CI (99.9%): [2.616, 3.560] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.972 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.279 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.079 ±(99.9%) 0.013 ms/op
Iteration   1: 4.048 ±(99.9%) 0.036 ms/op
Iteration   2: 4.058 ±(99.9%) 0.011 ms/op
Iteration   3: 4.107 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.071 ±(99.9%) 0.574 ms/op [Average]
  (min, avg, max) = (4.048, 4.071, 4.107), stdev = 0.031
  CI (99.9%): [3.497, 4.645] (assumes normal distribution)


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
# Warmup Iteration   1: 4.484 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.296 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.006 ms/op
Iteration   1: 3.106 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.700 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   4.956 ms/op
                 createUser·p0.999:  9.044 ms/op
                 createUser·p0.9999: 17.990 ms/op
                 createUser·p1.00:   18.088 ms/op

Iteration   2: 3.053 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.725 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  9.634 ms/op
                 createUser·p0.9999: 19.678 ms/op
                 createUser·p1.00:   20.185 ms/op

Iteration   3: 3.063 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.773 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   4.751 ms/op
                 createUser·p0.999:  10.964 ms/op
                 createUser·p0.9999: 21.430 ms/op
                 createUser·p1.00:   22.086 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312148
  mean =      3.074 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19470 
    [ 2.500,  5.000) = 290378 
    [ 5.000,  7.500) = 1650 
    [ 7.500, 10.000) = 353 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.700 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      4.743 ms/op
     p(99.9000) =      9.648 ms/op
     p(99.9900) =     21.023 ms/op
     p(99.9990) =     21.943 ms/op
     p(99.9999) =     22.086 ms/op
    p(100.0000) =     22.086 ms/op


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
# Warmup Iteration   1: 4.336 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.071 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.001 ±(99.9%) 0.006 ms/op
Iteration   1: 2.999 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.809 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   3.768 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  7.643 ms/op
                 existUser·p0.9999: 12.845 ms/op
                 existUser·p1.00:   13.173 ms/op

Iteration   2: 2.995 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.962 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   4.451 ms/op
                 existUser·p0.999:  8.753 ms/op
                 existUser·p0.9999: 14.980 ms/op
                 existUser·p1.00:   15.221 ms/op

Iteration   3: 2.991 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.673 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   4.495 ms/op
                 existUser·p0.999:  9.590 ms/op
                 existUser·p0.9999: 21.713 ms/op
                 existUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 320213
  mean =      2.995 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28438 
    [ 2.500,  5.000) = 290064 
    [ 5.000,  7.500) = 1115 
    [ 7.500, 10.000) = 405 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.673 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      8.467 ms/op
     p(99.9900) =     19.178 ms/op
     p(99.9990) =     22.040 ms/op
     p(99.9999) =     22.151 ms/op
    p(100.0000) =     22.151 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.477 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.191 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.182 ±(99.9%) 0.008 ms/op
Iteration   1: 3.138 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.905 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.826 ms/op
                 getUser·p0.95:   4.092 ms/op
                 getUser·p0.99:   4.866 ms/op
                 getUser·p0.999:  8.943 ms/op
                 getUser·p0.9999: 28.272 ms/op
                 getUser·p1.00:   28.475 ms/op

Iteration   2: 3.108 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.788 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   4.891 ms/op
                 getUser·p0.999:  8.997 ms/op
                 getUser·p0.9999: 25.091 ms/op
                 getUser·p1.00:   25.559 ms/op

Iteration   3: 3.111 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.861 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   4.841 ms/op
                 getUser·p0.999:  7.184 ms/op
                 getUser·p0.9999: 22.264 ms/op
                 getUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 307798
  mean =      3.119 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20946 
    [ 2.500,  5.000) = 284408 
    [ 5.000,  7.500) = 1994 
    [ 7.500, 10.000) = 245 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.788 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      4.866 ms/op
     p(99.9000) =      8.210 ms/op
     p(99.9900) =     27.361 ms/op
     p(99.9990) =     28.410 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


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
# Warmup Iteration   1: 5.720 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.212 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.050 ±(99.9%) 0.011 ms/op
Iteration   1: 4.111 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.399 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   6.054 ms/op
                 listUser·p0.99:   7.537 ms/op
                 listUser·p0.999:  14.257 ms/op
                 listUser·p0.9999: 16.087 ms/op
                 listUser·p1.00:   18.743 ms/op

Iteration   2: 3.982 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.008 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.923 ms/op
                 listUser·p0.99:   7.406 ms/op
                 listUser·p0.999:  15.972 ms/op
                 listUser·p0.9999: 23.525 ms/op
                 listUser·p1.00:   25.788 ms/op

Iteration   3: 4.004 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.423 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   7.242 ms/op
                 listUser·p0.999:  18.121 ms/op
                 listUser·p0.9999: 30.278 ms/op
                 listUser·p1.00:   30.900 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237999
  mean =      4.032 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1954 
    [ 2.500,  5.000) = 211583 
    [ 5.000,  7.500) = 22257 
    [ 7.500, 10.000) = 1584 
    [10.000, 12.500) = 221 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 147 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.008 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      5.038 ms/op
     p(95.0000) =      5.931 ms/op
     p(99.0000) =      7.406 ms/op
     p(99.9000) =     15.745 ms/op
     p(99.9900) =     29.209 ms/op
     p(99.9990) =     30.702 ms/op
     p(99.9999) =     30.900 ms/op
    p(100.0000) =     30.900 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.403 ± 3.031  ops/ms
ClientGrpc.existUser                       thrpt       3  10.990 ± 0.184  ops/ms
ClientGrpc.getUser                         thrpt       3  10.443 ± 2.483  ops/ms
ClientGrpc.listUser                        thrpt       3   7.804 ± 1.128  ops/ms
ClientGrpc.createUser                       avgt       3   3.052 ± 0.168   ms/op
ClientGrpc.existUser                        avgt       3   2.956 ± 0.871   ms/op
ClientGrpc.getUser                          avgt       3   3.088 ± 0.472   ms/op
ClientGrpc.listUser                         avgt       3   4.071 ± 0.574   ms/op
ClientGrpc.createUser                     sample  312148   3.074 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.700           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.035           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.572           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.830           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.743           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.648           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.023           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.086           ms/op
ClientGrpc.existUser                      sample  320213   2.995 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.673           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.957           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.523           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.731           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.432           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.467           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.178           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.151           ms/op
ClientGrpc.getUser                        sample  307798   3.119 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.788           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.072           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.723           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.994           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.866           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.210           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.361           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.475           ms/op
ClientGrpc.listUser                       sample  237999   4.032 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.008           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.871           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.038           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.931           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.406           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.745           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.209           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.900           ms/op
