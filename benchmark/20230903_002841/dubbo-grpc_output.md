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
# Warmup Iteration   1: 2.466 ops/ms
# Warmup Iteration   2: 5.648 ops/ms
# Warmup Iteration   3: 6.913 ops/ms
Iteration   1: 7.243 ops/ms
Iteration   2: 7.345 ops/ms
Iteration   3: 7.180 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.256 ±(99.9%) 1.517 ops/ms [Average]
  (min, avg, max) = (7.180, 7.256, 7.345), stdev = 0.083
  CI (99.9%): [5.739, 8.772] (assumes normal distribution)


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
# Warmup Iteration   1: 4.773 ops/ms
# Warmup Iteration   2: 7.247 ops/ms
# Warmup Iteration   3: 7.596 ops/ms
Iteration   1: 7.608 ops/ms
Iteration   2: 7.698 ops/ms
Iteration   3: 7.988 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.765 ±(99.9%) 3.627 ops/ms [Average]
  (min, avg, max) = (7.608, 7.765, 7.988), stdev = 0.199
  CI (99.9%): [4.138, 11.392] (assumes normal distribution)


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
# Warmup Iteration   1: 4.449 ops/ms
# Warmup Iteration   2: 7.017 ops/ms
# Warmup Iteration   3: 7.653 ops/ms
Iteration   1: 7.521 ops/ms
Iteration   2: 7.540 ops/ms
Iteration   3: 7.571 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.544 ±(99.9%) 0.461 ops/ms [Average]
  (min, avg, max) = (7.521, 7.544, 7.571), stdev = 0.025
  CI (99.9%): [7.083, 8.005] (assumes normal distribution)


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
# Warmup Iteration   1: 3.495 ops/ms
# Warmup Iteration   2: 5.451 ops/ms
# Warmup Iteration   3: 5.793 ops/ms
Iteration   1: 5.909 ops/ms
Iteration   2: 5.865 ops/ms
Iteration   3: 5.838 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.871 ±(99.9%) 0.655 ops/ms [Average]
  (min, avg, max) = (5.838, 5.871, 5.909), stdev = 0.036
  CI (99.9%): [5.215, 6.526] (assumes normal distribution)


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
# Warmup Iteration   1: 6.248 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.382 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.353 ±(99.9%) 0.016 ms/op
Iteration   1: 4.228 ±(99.9%) 0.003 ms/op
Iteration   2: 4.318 ±(99.9%) 0.003 ms/op
Iteration   3: 4.238 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.262 ±(99.9%) 0.901 ms/op [Average]
  (min, avg, max) = (4.228, 4.262, 4.318), stdev = 0.049
  CI (99.9%): [3.360, 5.163] (assumes normal distribution)


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
# Warmup Iteration   1: 5.597 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.278 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.820 ±(99.9%) 0.006 ms/op
Iteration   1: 3.682 ±(99.9%) 0.003 ms/op
Iteration   2: 3.714 ±(99.9%) 0.003 ms/op
Iteration   3: 3.705 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.700 ±(99.9%) 0.303 ms/op [Average]
  (min, avg, max) = (3.682, 3.700, 3.714), stdev = 0.017
  CI (99.9%): [3.398, 4.003] (assumes normal distribution)


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
# Warmup Iteration   1: 5.866 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.633 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.114 ±(99.9%) 0.003 ms/op
Iteration   1: 4.030 ±(99.9%) 0.035 ms/op
Iteration   2: 3.965 ±(99.9%) 0.003 ms/op
Iteration   3: 3.964 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.986 ±(99.9%) 0.689 ms/op [Average]
  (min, avg, max) = (3.964, 3.986, 4.030), stdev = 0.038
  CI (99.9%): [3.297, 4.675] (assumes normal distribution)


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
# Warmup Iteration   1: 7.902 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 6.040 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.514 ±(99.9%) 0.013 ms/op
Iteration   1: 5.476 ±(99.9%) 0.027 ms/op
Iteration   2: 5.373 ±(99.9%) 0.016 ms/op
Iteration   3: 5.430 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.427 ±(99.9%) 0.941 ms/op [Average]
  (min, avg, max) = (5.373, 5.427, 5.476), stdev = 0.052
  CI (99.9%): [4.486, 6.367] (assumes normal distribution)


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
# Warmup Iteration   1: 6.074 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.278 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.190 ±(99.9%) 0.012 ms/op
Iteration   1: 4.089 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.102 ms/op
                 createUser·p0.50:   3.969 ms/op
                 createUser·p0.90:   5.120 ms/op
                 createUser·p0.95:   5.612 ms/op
                 createUser·p0.99:   7.214 ms/op
                 createUser·p0.999:  11.119 ms/op
                 createUser·p0.9999: 22.288 ms/op
                 createUser·p1.00:   24.117 ms/op

Iteration   2: 4.273 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.206 ms/op
                 createUser·p0.50:   4.141 ms/op
                 createUser·p0.90:   5.349 ms/op
                 createUser·p0.95:   5.800 ms/op
                 createUser·p0.99:   7.602 ms/op
                 createUser·p0.999:  12.435 ms/op
                 createUser·p0.9999: 20.300 ms/op
                 createUser·p1.00:   20.742 ms/op

Iteration   3: 4.292 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.126 ms/op
                 createUser·p0.50:   4.145 ms/op
                 createUser·p0.90:   5.366 ms/op
                 createUser·p0.95:   5.800 ms/op
                 createUser·p0.99:   8.020 ms/op
                 createUser·p0.999:  12.622 ms/op
                 createUser·p0.9999: 28.725 ms/op
                 createUser·p1.00:   29.032 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 227795
  mean =      4.216 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2328 
    [ 2.500,  5.000) = 190767 
    [ 5.000,  7.500) = 32318 
    [ 7.500, 10.000) = 1686 
    [10.000, 12.500) = 484 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.102 ms/op
     p(50.0000) =      4.080 ms/op
     p(90.0000) =      5.292 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =      7.586 ms/op
     p(99.9000) =     12.370 ms/op
     p(99.9900) =     26.680 ms/op
     p(99.9990) =     28.991 ms/op
     p(99.9999) =     29.032 ms/op
    p(100.0000) =     29.032 ms/op


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
# Warmup Iteration   1: 5.851 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.200 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.967 ±(99.9%) 0.011 ms/op
Iteration   1: 3.936 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.044 ms/op
                 existUser·p0.50:   3.838 ms/op
                 existUser·p0.90:   5.005 ms/op
                 existUser·p0.95:   5.456 ms/op
                 existUser·p0.99:   6.447 ms/op
                 existUser·p0.999:  8.962 ms/op
                 existUser·p0.9999: 16.087 ms/op
                 existUser·p1.00:   16.597 ms/op

Iteration   2: 3.891 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.858 ms/op
                 existUser·p0.50:   3.768 ms/op
                 existUser·p0.90:   4.858 ms/op
                 existUser·p0.95:   5.292 ms/op
                 existUser·p0.99:   6.316 ms/op
                 existUser·p0.999:  11.878 ms/op
                 existUser·p0.9999: 17.451 ms/op
                 existUser·p1.00:   17.957 ms/op

Iteration   3: 3.901 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.883 ms/op
                 existUser·p0.50:   3.768 ms/op
                 existUser·p0.90:   4.784 ms/op
                 existUser·p0.95:   5.210 ms/op
                 existUser·p0.99:   7.266 ms/op
                 existUser·p0.999:  13.976 ms/op
                 existUser·p0.9999: 34.013 ms/op
                 existUser·p1.00:   34.669 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 245615
  mean =      3.909 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4953 
    [ 2.500,  5.000) = 220198 
    [ 5.000,  7.500) = 19045 
    [ 7.500, 10.000) = 929 
    [10.000, 12.500) = 295 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.858 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.882 ms/op
     p(95.0000) =      5.333 ms/op
     p(99.0000) =      6.554 ms/op
     p(99.9000) =     11.862 ms/op
     p(99.9900) =     31.846 ms/op
     p(99.9990) =     34.478 ms/op
     p(99.9999) =     34.669 ms/op
    p(100.0000) =     34.669 ms/op


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
# Warmup Iteration   1: 5.905 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.298 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.066 ±(99.9%) 0.012 ms/op
Iteration   1: 4.014 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.212 ms/op
                 getUser·p0.50:   3.875 ms/op
                 getUser·p0.90:   5.126 ms/op
                 getUser·p0.95:   5.562 ms/op
                 getUser·p0.99:   7.004 ms/op
                 getUser·p0.999:  11.137 ms/op
                 getUser·p0.9999: 23.003 ms/op
                 getUser·p1.00:   23.331 ms/op

Iteration   2: 4.182 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.023 ms/op
                 getUser·p0.50:   4.010 ms/op
                 getUser·p0.90:   5.317 ms/op
                 getUser·p0.95:   5.759 ms/op
                 getUser·p0.99:   7.569 ms/op
                 getUser·p0.999:  11.593 ms/op
                 getUser·p0.9999: 21.179 ms/op
                 getUser·p1.00:   21.234 ms/op

Iteration   3: 4.260 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.389 ms/op
                 getUser·p0.50:   4.166 ms/op
                 getUser·p0.90:   5.226 ms/op
                 getUser·p0.95:   5.587 ms/op
                 getUser·p0.99:   7.062 ms/op
                 getUser·p0.999:  12.812 ms/op
                 getUser·p0.9999: 19.120 ms/op
                 getUser·p1.00:   20.677 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 231351
  mean =      4.150 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3657 
    [ 2.500,  5.000) = 194531 
    [ 5.000,  7.500) = 31195 
    [ 7.500, 10.000) = 1547 
    [10.000, 12.500) = 233 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.023 ms/op
     p(50.0000) =      4.014 ms/op
     p(90.0000) =      5.226 ms/op
     p(95.0000) =      5.644 ms/op
     p(99.0000) =      7.217 ms/op
     p(99.9000) =     11.807 ms/op
     p(99.9900) =     22.339 ms/op
     p(99.9990) =     23.245 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


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
# Warmup Iteration   1: 7.691 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 5.264 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 5.093 ±(99.9%) 0.018 ms/op
Iteration   1: 5.034 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.636 ms/op
                 listUser·p0.50:   4.801 ms/op
                 listUser·p0.90:   6.431 ms/op
                 listUser·p0.95:   7.348 ms/op
                 listUser·p0.99:   9.404 ms/op
                 listUser·p0.999:  16.121 ms/op
                 listUser·p0.9999: 21.658 ms/op
                 listUser·p1.00:   22.348 ms/op

Iteration   2: 5.202 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.540 ms/op
                 listUser·p0.50:   4.932 ms/op
                 listUser·p0.90:   6.750 ms/op
                 listUser·p0.95:   7.840 ms/op
                 listUser·p0.99:   9.880 ms/op
                 listUser·p0.999:  15.789 ms/op
                 listUser·p0.9999: 19.347 ms/op
                 listUser·p1.00:   22.086 ms/op

Iteration   3: 5.122 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.538 ms/op
                 listUser·p0.50:   4.858 ms/op
                 listUser·p0.90:   6.808 ms/op
                 listUser·p0.95:   7.676 ms/op
                 listUser·p0.99:   10.109 ms/op
                 listUser·p0.999:  18.285 ms/op
                 listUser·p0.9999: 24.298 ms/op
                 listUser·p1.00:   25.100 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 187487
  mean =      5.118 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 219 
    [ 2.500,  5.000) = 105320 
    [ 5.000,  7.500) = 71731 
    [ 7.500, 10.000) = 8573 
    [10.000, 12.500) = 1135 
    [12.500, 15.000) = 225 
    [15.000, 17.500) = 123 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.538 ms/op
     p(50.0000) =      4.858 ms/op
     p(90.0000) =      6.668 ms/op
     p(95.0000) =      7.619 ms/op
     p(99.0000) =      9.814 ms/op
     p(99.9000) =     16.573 ms/op
     p(99.9900) =     23.274 ms/op
     p(99.9990) =     24.670 ms/op
     p(99.9999) =     25.100 ms/op
    p(100.0000) =     25.100 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.256 ± 1.517  ops/ms
ClientGrpc.existUser                       thrpt       3   7.765 ± 3.627  ops/ms
ClientGrpc.getUser                         thrpt       3   7.544 ± 0.461  ops/ms
ClientGrpc.listUser                        thrpt       3   5.871 ± 0.655  ops/ms
ClientGrpc.createUser                       avgt       3   4.262 ± 0.901   ms/op
ClientGrpc.existUser                        avgt       3   3.700 ± 0.303   ms/op
ClientGrpc.getUser                          avgt       3   3.986 ± 0.689   ms/op
ClientGrpc.listUser                         avgt       3   5.427 ± 0.941   ms/op
ClientGrpc.createUser                     sample  227795   4.216 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.102           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.080           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.292           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.743           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.586           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.370           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.680           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.032           ms/op
ClientGrpc.existUser                      sample  245615   3.909 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.858           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.789           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.882           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.333           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.554           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.862           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          31.846           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          34.669           ms/op
ClientGrpc.getUser                        sample  231351   4.150 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.023           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.014           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.226           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.644           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.217           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.807           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.339           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.331           ms/op
ClientGrpc.listUser                       sample  187487   5.118 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.538           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.858           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.668           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.619           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.814           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.573           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.274           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.100           ms/op
