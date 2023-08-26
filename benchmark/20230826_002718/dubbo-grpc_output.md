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
# Warmup Iteration   1: 4.295 ops/ms
# Warmup Iteration   2: 8.736 ops/ms
# Warmup Iteration   3: 9.774 ops/ms
Iteration   1: 10.259 ops/ms
Iteration   2: 10.485 ops/ms
Iteration   3: 10.503 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.416 ±(99.9%) 2.479 ops/ms [Average]
  (min, avg, max) = (10.259, 10.416, 10.503), stdev = 0.136
  CI (99.9%): [7.936, 12.895] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.364 ops/ms
# Warmup Iteration   2: 10.486 ops/ms
# Warmup Iteration   3: 10.779 ops/ms
Iteration   1: 11.188 ops/ms
Iteration   2: 10.974 ops/ms
Iteration   3: 10.863 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.008 ±(99.9%) 3.011 ops/ms [Average]
  (min, avg, max) = (10.863, 11.008, 11.188), stdev = 0.165
  CI (99.9%): [7.997, 14.019] (assumes normal distribution)


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
# Warmup Iteration   1: 6.744 ops/ms
# Warmup Iteration   2: 9.955 ops/ms
# Warmup Iteration   3: 10.241 ops/ms
Iteration   1: 10.536 ops/ms
Iteration   2: 10.415 ops/ms
Iteration   3: 10.285 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.412 ±(99.9%) 2.290 ops/ms [Average]
  (min, avg, max) = (10.285, 10.412, 10.536), stdev = 0.126
  CI (99.9%): [8.122, 12.702] (assumes normal distribution)


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
# Warmup Iteration   1: 5.353 ops/ms
# Warmup Iteration   2: 7.657 ops/ms
# Warmup Iteration   3: 7.941 ops/ms
Iteration   1: 8.060 ops/ms
Iteration   2: 8.053 ops/ms
Iteration   3: 7.932 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.015 ±(99.9%) 1.313 ops/ms [Average]
  (min, avg, max) = (7.932, 8.015, 8.060), stdev = 0.072
  CI (99.9%): [6.702, 9.328] (assumes normal distribution)


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
# Warmup Iteration   1: 4.183 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.260 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.131 ±(99.9%) 0.009 ms/op
Iteration   1: 3.148 ±(99.9%) 0.003 ms/op
Iteration   2: 3.087 ±(99.9%) 0.003 ms/op
Iteration   3: 3.160 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.132 ±(99.9%) 0.721 ms/op [Average]
  (min, avg, max) = (3.087, 3.132, 3.160), stdev = 0.040
  CI (99.9%): [2.411, 3.852] (assumes normal distribution)


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
# Warmup Iteration   1: 4.141 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.068 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.906 ±(99.9%) 0.004 ms/op
Iteration   1: 2.897 ±(99.9%) 0.002 ms/op
Iteration   2: 2.909 ±(99.9%) 0.003 ms/op
Iteration   3: 2.826 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.877 ±(99.9%) 0.821 ms/op [Average]
  (min, avg, max) = (2.826, 2.877, 2.909), stdev = 0.045
  CI (99.9%): [2.056, 3.698] (assumes normal distribution)


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
# Warmup Iteration   1: 4.196 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.166 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.004 ms/op
Iteration   1: 3.041 ±(99.9%) 0.003 ms/op
Iteration   2: 3.102 ±(99.9%) 0.002 ms/op
Iteration   3: 3.032 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.058 ±(99.9%) 0.697 ms/op [Average]
  (min, avg, max) = (3.032, 3.058, 3.102), stdev = 0.038
  CI (99.9%): [2.362, 3.755] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.543 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.230 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.986 ±(99.9%) 0.018 ms/op
Iteration   1: 4.041 ±(99.9%) 0.021 ms/op
Iteration   2: 4.010 ±(99.9%) 0.026 ms/op
Iteration   3: 4.019 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.024 ±(99.9%) 0.289 ms/op [Average]
  (min, avg, max) = (4.010, 4.024, 4.041), stdev = 0.016
  CI (99.9%): [3.734, 4.313] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.228 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.246 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.090 ±(99.9%) 0.006 ms/op
Iteration   1: 3.054 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.692 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   4.710 ms/op
                 createUser·p0.999:  8.809 ms/op
                 createUser·p0.9999: 16.081 ms/op
                 createUser·p1.00:   16.499 ms/op

Iteration   2: 3.072 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.633 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  8.496 ms/op
                 createUser·p0.9999: 14.182 ms/op
                 createUser·p1.00:   14.516 ms/op

Iteration   3: 3.073 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.945 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.792 ms/op
                 createUser·p0.999:  13.008 ms/op
                 createUser·p0.9999: 28.134 ms/op
                 createUser·p1.00:   28.738 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313118
  mean =      3.066 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20134 
    [ 2.500,  5.000) = 290880 
    [ 5.000,  7.500) = 1568 
    [ 7.500, 10.000) = 208 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 165 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.633 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.645 ms/op
     p(99.9000) =     11.832 ms/op
     p(99.9900) =     27.197 ms/op
     p(99.9990) =     28.635 ms/op
     p(99.9999) =     28.738 ms/op
    p(100.0000) =     28.738 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.020 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.078 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.966 ±(99.9%) 0.005 ms/op
Iteration   1: 2.909 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.513 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.457 ms/op
                 existUser·p0.99:   4.125 ms/op
                 existUser·p0.999:  7.192 ms/op
                 existUser·p0.9999: 12.599 ms/op
                 existUser·p1.00:   12.730 ms/op

Iteration   2: 2.954 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.782 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  7.805 ms/op
                 existUser·p0.9999: 13.943 ms/op
                 existUser·p1.00:   14.287 ms/op

Iteration   3: 2.885 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.618 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.490 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  6.669 ms/op
                 existUser·p0.9999: 26.608 ms/op
                 existUser·p1.00:   26.903 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329247
  mean =      2.916 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33124 
    [ 2.500,  5.000) = 294726 
    [ 5.000,  7.500) = 1120 
    [ 7.500, 10.000) = 117 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.513 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.330 ms/op
     p(95.0000) =      3.535 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      7.283 ms/op
     p(99.9900) =     15.135 ms/op
     p(99.9990) =     26.827 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


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
# Warmup Iteration   1: 3.813 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.232 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.104 ±(99.9%) 0.007 ms/op
Iteration   1: 3.078 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.694 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.903 ms/op
                 getUser·p0.99:   4.973 ms/op
                 getUser·p0.999:  9.487 ms/op
                 getUser·p0.9999: 17.138 ms/op
                 getUser·p1.00:   18.383 ms/op

Iteration   2: 3.059 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.808 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   4.737 ms/op
                 getUser·p0.999:  10.289 ms/op
                 getUser·p0.9999: 25.937 ms/op
                 getUser·p1.00:   26.214 ms/op

Iteration   3: 3.032 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.575 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.725 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  7.987 ms/op
                 getUser·p0.9999: 17.433 ms/op
                 getUser·p1.00:   18.612 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314162
  mean =      3.056 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20869 
    [ 2.500,  5.000) = 291103 
    [ 5.000,  7.500) = 1572 
    [ 7.500, 10.000) = 344 
    [10.000, 12.500) = 113 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.575 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      4.776 ms/op
     p(99.9000) =      8.959 ms/op
     p(99.9900) =     24.732 ms/op
     p(99.9990) =     26.144 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


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
# Warmup Iteration   1: 5.550 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.153 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.992 ±(99.9%) 0.010 ms/op
Iteration   1: 4.032 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.565 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   7.209 ms/op
                 listUser·p0.999:  15.238 ms/op
                 listUser·p0.9999: 21.538 ms/op
                 listUser·p1.00:   21.856 ms/op

Iteration   2: 4.007 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.456 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  15.190 ms/op
                 listUser·p0.9999: 26.543 ms/op
                 listUser·p1.00:   27.361 ms/op

Iteration   3: 4.000 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.963 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   7.348 ms/op
                 listUser·p0.999:  16.515 ms/op
                 listUser·p0.9999: 19.726 ms/op
                 listUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239160
  mean =      4.013 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1933 
    [ 2.500,  5.000) = 214857 
    [ 5.000,  7.500) = 20634 
    [ 7.500, 10.000) = 1187 
    [10.000, 12.500) = 149 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 192 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.565 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.923 ms/op
     p(95.0000) =      5.767 ms/op
     p(99.0000) =      7.176 ms/op
     p(99.9000) =     15.510 ms/op
     p(99.9900) =     25.788 ms/op
     p(99.9990) =     27.237 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.416 ± 2.479  ops/ms
ClientGrpc.existUser                       thrpt       3  11.008 ± 3.011  ops/ms
ClientGrpc.getUser                         thrpt       3  10.412 ± 2.290  ops/ms
ClientGrpc.listUser                        thrpt       3   8.015 ± 1.313  ops/ms
ClientGrpc.createUser                       avgt       3   3.132 ± 0.721   ms/op
ClientGrpc.existUser                        avgt       3   2.877 ± 0.821   ms/op
ClientGrpc.getUser                          avgt       3   3.058 ± 0.697   ms/op
ClientGrpc.listUser                         avgt       3   4.024 ± 0.289   ms/op
ClientGrpc.createUser                     sample  313118   3.066 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.633           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.031           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.559           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.772           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.645           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.832           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.197           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.738           ms/op
ClientGrpc.existUser                      sample  329247   2.916 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.513           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.896           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.330           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.535           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.366           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.283           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.135           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.903           ms/op
ClientGrpc.getUser                        sample  314162   3.056 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.575           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.023           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.572           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.830           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.776           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.959           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.732           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.214           ms/op
ClientGrpc.listUser                       sample  239160   4.013 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.565           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.850           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.923           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.767           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.176           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.510           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.788           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.361           ms/op
