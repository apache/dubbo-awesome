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
# Warmup Iteration   1: 3.611 ops/ms
# Warmup Iteration   2: 8.347 ops/ms
# Warmup Iteration   3: 9.606 ops/ms
Iteration   1: 10.061 ops/ms
Iteration   2: 9.928 ops/ms
Iteration   3: 10.009 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.999 ±(99.9%) 1.227 ops/ms [Average]
  (min, avg, max) = (9.928, 9.999, 10.061), stdev = 0.067
  CI (99.9%): [8.772, 11.226] (assumes normal distribution)


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
# Warmup Iteration   1: 6.991 ops/ms
# Warmup Iteration   2: 10.088 ops/ms
# Warmup Iteration   3: 10.500 ops/ms
Iteration   1: 10.377 ops/ms
Iteration   2: 10.625 ops/ms
Iteration   3: 10.669 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.557 ±(99.9%) 2.866 ops/ms [Average]
  (min, avg, max) = (10.377, 10.557, 10.669), stdev = 0.157
  CI (99.9%): [7.691, 13.423] (assumes normal distribution)


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
# Warmup Iteration   1: 6.441 ops/ms
# Warmup Iteration   2: 9.835 ops/ms
# Warmup Iteration   3: 10.248 ops/ms
Iteration   1: 10.081 ops/ms
Iteration   2: 10.062 ops/ms
Iteration   3: 10.118 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.087 ±(99.9%) 0.523 ops/ms [Average]
  (min, avg, max) = (10.062, 10.087, 10.118), stdev = 0.029
  CI (99.9%): [9.564, 10.610] (assumes normal distribution)


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
# Warmup Iteration   1: 5.378 ops/ms
# Warmup Iteration   2: 7.375 ops/ms
# Warmup Iteration   3: 7.695 ops/ms
Iteration   1: 7.862 ops/ms
Iteration   2: 7.757 ops/ms
Iteration   3: 7.978 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.866 ±(99.9%) 2.018 ops/ms [Average]
  (min, avg, max) = (7.757, 7.866, 7.978), stdev = 0.111
  CI (99.9%): [5.847, 9.884] (assumes normal distribution)


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
# Warmup Iteration   1: 4.838 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.307 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.272 ±(99.9%) 0.002 ms/op
Iteration   1: 3.266 ±(99.9%) 0.006 ms/op
Iteration   2: 3.171 ±(99.9%) 0.002 ms/op
Iteration   3: 3.166 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.201 ±(99.9%) 1.031 ms/op [Average]
  (min, avg, max) = (3.166, 3.201, 3.266), stdev = 0.056
  CI (99.9%): [2.170, 4.231] (assumes normal distribution)


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
# Warmup Iteration   1: 4.160 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.091 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.005 ms/op
Iteration   1: 3.029 ±(99.9%) 0.003 ms/op
Iteration   2: 2.975 ±(99.9%) 0.003 ms/op
Iteration   3: 3.045 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.017 ±(99.9%) 0.673 ms/op [Average]
  (min, avg, max) = (2.975, 3.017, 3.045), stdev = 0.037
  CI (99.9%): [2.344, 3.689] (assumes normal distribution)


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
# Warmup Iteration   1: 4.349 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.260 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.168 ±(99.9%) 0.003 ms/op
Iteration   1: 3.179 ±(99.9%) 0.005 ms/op
Iteration   2: 3.192 ±(99.9%) 0.004 ms/op
Iteration   3: 3.148 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.173 ±(99.9%) 0.407 ms/op [Average]
  (min, avg, max) = (3.148, 3.173, 3.192), stdev = 0.022
  CI (99.9%): [2.766, 3.580] (assumes normal distribution)


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
# Warmup Iteration   1: 6.195 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.381 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.060 ±(99.9%) 0.036 ms/op
Iteration   1: 4.012 ±(99.9%) 0.022 ms/op
Iteration   2: 4.035 ±(99.9%) 0.018 ms/op
Iteration   3: 4.003 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.017 ±(99.9%) 0.301 ms/op [Average]
  (min, avg, max) = (4.003, 4.017, 4.035), stdev = 0.016
  CI (99.9%): [3.716, 4.318] (assumes normal distribution)


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
# Warmup Iteration   1: 4.453 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.395 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.150 ±(99.9%) 0.008 ms/op
Iteration   1: 3.191 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.682 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  11.753 ms/op
                 createUser·p0.9999: 28.735 ms/op
                 createUser·p1.00:   29.753 ms/op

Iteration   2: 3.137 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.817 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   4.702 ms/op
                 createUser·p0.999:  9.840 ms/op
                 createUser·p0.9999: 18.769 ms/op
                 createUser·p1.00:   20.218 ms/op

Iteration   3: 3.118 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.733 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  13.411 ms/op
                 createUser·p0.9999: 25.050 ms/op
                 createUser·p1.00:   26.083 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305147
  mean =      3.148 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10605 
    [ 2.500,  5.000) = 292377 
    [ 5.000,  7.500) = 1559 
    [ 7.500, 10.000) = 258 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.682 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =     10.598 ms/op
     p(99.9900) =     25.034 ms/op
     p(99.9990) =     29.586 ms/op
     p(99.9999) =     29.753 ms/op
    p(100.0000) =     29.753 ms/op


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
# Warmup Iteration   1: 4.026 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.156 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.006 ms/op
Iteration   1: 3.030 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.721 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.682 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  11.581 ms/op
                 existUser·p0.9999: 19.839 ms/op
                 existUser·p1.00:   20.283 ms/op

Iteration   2: 3.057 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.760 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   4.465 ms/op
                 existUser·p0.999:  6.259 ms/op
                 existUser·p0.9999: 14.894 ms/op
                 existUser·p1.00:   15.319 ms/op

Iteration   3: 3.070 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.791 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.822 ms/op
                 existUser·p0.99:   4.702 ms/op
                 existUser·p0.999:  15.214 ms/op
                 existUser·p0.9999: 27.760 ms/op
                 existUser·p1.00:   28.279 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 314441
  mean =      3.052 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21795 
    [ 2.500,  5.000) = 290908 
    [ 5.000,  7.500) = 1362 
    [ 7.500, 10.000) = 123 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.721 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      7.849 ms/op
     p(99.9900) =     27.492 ms/op
     p(99.9990) =     28.180 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.472 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.346 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.256 ±(99.9%) 0.007 ms/op
Iteration   1: 3.196 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.919 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   3.985 ms/op
                 getUser·p0.99:   4.653 ms/op
                 getUser·p0.999:  9.616 ms/op
                 getUser·p0.9999: 14.680 ms/op
                 getUser·p1.00:   15.385 ms/op

Iteration   2: 3.166 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.822 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   4.907 ms/op
                 getUser·p0.999:  10.883 ms/op
                 getUser·p0.9999: 20.146 ms/op
                 getUser·p1.00:   20.677 ms/op

Iteration   3: 3.151 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.626 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.407 ms/op
                 getUser·p0.999:  8.779 ms/op
                 getUser·p0.9999: 22.409 ms/op
                 getUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 302496
  mean =      3.171 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9201 
    [ 2.500,  5.000) = 291218 
    [ 5.000,  7.500) = 1566 
    [ 7.500, 10.000) = 231 
    [10.000, 12.500) = 23 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.626 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      4.653 ms/op
     p(99.9000) =      9.593 ms/op
     p(99.9900) =     20.038 ms/op
     p(99.9990) =     22.512 ms/op
     p(99.9999) =     22.577 ms/op
    p(100.0000) =     22.577 ms/op


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
# Warmup Iteration   1: 5.264 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.214 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.050 ±(99.9%) 0.011 ms/op
Iteration   1: 4.013 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.128 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  15.029 ms/op
                 listUser·p0.9999: 22.521 ms/op
                 listUser·p1.00:   27.820 ms/op

Iteration   2: 4.058 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.063 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   7.201 ms/op
                 listUser·p0.999:  15.270 ms/op
                 listUser·p0.9999: 16.763 ms/op
                 listUser·p1.00:   18.252 ms/op

Iteration   3: 3.880 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.128 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  16.043 ms/op
                 listUser·p0.9999: 18.818 ms/op
                 listUser·p1.00:   19.300 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240889
  mean =      3.982 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2500 
    [ 2.500,  5.000) = 219832 
    [ 5.000,  7.500) = 17017 
    [ 7.500, 10.000) = 867 
    [10.000, 12.500) = 198 
    [12.500, 15.000) = 191 
    [15.000, 17.500) = 214 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.063 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      5.644 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     15.272 ms/op
     p(99.9900) =     20.382 ms/op
     p(99.9990) =     27.635 ms/op
     p(99.9999) =     27.820 ms/op
    p(100.0000) =     27.820 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.999 ± 1.227  ops/ms
ClientGrpc.existUser                       thrpt       3  10.557 ± 2.866  ops/ms
ClientGrpc.getUser                         thrpt       3  10.087 ± 0.523  ops/ms
ClientGrpc.listUser                        thrpt       3   7.866 ± 2.018  ops/ms
ClientGrpc.createUser                       avgt       3   3.201 ± 1.031   ms/op
ClientGrpc.existUser                        avgt       3   3.017 ± 0.673   ms/op
ClientGrpc.getUser                          avgt       3   3.173 ± 0.407   ms/op
ClientGrpc.listUser                         avgt       3   4.017 ± 0.301   ms/op
ClientGrpc.createUser                     sample  305147   3.148 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.682           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.097           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.695           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.858           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.588           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.598           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.034           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.753           ms/op
ClientGrpc.existUser                      sample  314441   3.052 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.721           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.011           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.604           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.797           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.489           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.849           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          27.492           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.279           ms/op
ClientGrpc.getUser                        sample  302496   3.171 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.626           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.125           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.731           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.916           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.653           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.593           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.038           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.577           ms/op
ClientGrpc.listUser                       sample  240889   3.982 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.063           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.867           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.669           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.644           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.980           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.272           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.382           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.820           ms/op
