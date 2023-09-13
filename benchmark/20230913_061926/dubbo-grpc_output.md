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
# Warmup Iteration   1: 3.240 ops/ms
# Warmup Iteration   2: 6.444 ops/ms
# Warmup Iteration   3: 7.791 ops/ms
Iteration   1: 8.327 ops/ms
Iteration   2: 8.383 ops/ms
Iteration   3: 8.306 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.339 ±(99.9%) 0.729 ops/ms [Average]
  (min, avg, max) = (8.306, 8.339, 8.383), stdev = 0.040
  CI (99.9%): [7.609, 9.068] (assumes normal distribution)


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
# Warmup Iteration   1: 5.630 ops/ms
# Warmup Iteration   2: 7.920 ops/ms
# Warmup Iteration   3: 8.445 ops/ms
Iteration   1: 8.766 ops/ms
Iteration   2: 8.643 ops/ms
Iteration   3: 8.877 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.762 ±(99.9%) 2.137 ops/ms [Average]
  (min, avg, max) = (8.643, 8.762, 8.877), stdev = 0.117
  CI (99.9%): [6.625, 10.899] (assumes normal distribution)


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
# Warmup Iteration   1: 5.315 ops/ms
# Warmup Iteration   2: 7.838 ops/ms
# Warmup Iteration   3: 8.194 ops/ms
Iteration   1: 8.437 ops/ms
Iteration   2: 8.213 ops/ms
Iteration   3: 8.335 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.328 ±(99.9%) 2.052 ops/ms [Average]
  (min, avg, max) = (8.213, 8.328, 8.437), stdev = 0.112
  CI (99.9%): [6.276, 10.381] (assumes normal distribution)


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
# Warmup Iteration   1: 4.079 ops/ms
# Warmup Iteration   2: 6.062 ops/ms
# Warmup Iteration   3: 6.288 ops/ms
Iteration   1: 6.507 ops/ms
Iteration   2: 6.503 ops/ms
Iteration   3: 6.538 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.516 ±(99.9%) 0.353 ops/ms [Average]
  (min, avg, max) = (6.503, 6.516, 6.538), stdev = 0.019
  CI (99.9%): [6.163, 6.869] (assumes normal distribution)


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
# Warmup Iteration   1: 5.348 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.044 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.889 ±(99.9%) 0.030 ms/op
Iteration   1: 3.741 ±(99.9%) 0.004 ms/op
Iteration   2: 3.830 ±(99.9%) 0.003 ms/op
Iteration   3: 3.821 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.797 ±(99.9%) 0.898 ms/op [Average]
  (min, avg, max) = (3.741, 3.797, 3.830), stdev = 0.049
  CI (99.9%): [2.900, 4.695] (assumes normal distribution)


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
# Warmup Iteration   1: 4.847 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.809 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.649 ±(99.9%) 0.003 ms/op
Iteration   1: 3.592 ±(99.9%) 0.005 ms/op
Iteration   2: 3.755 ±(99.9%) 0.003 ms/op
Iteration   3: 3.666 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.671 ±(99.9%) 1.484 ms/op [Average]
  (min, avg, max) = (3.592, 3.671, 3.755), stdev = 0.081
  CI (99.9%): [2.187, 5.155] (assumes normal distribution)


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
# Warmup Iteration   1: 5.495 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.042 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.878 ±(99.9%) 0.007 ms/op
Iteration   1: 3.886 ±(99.9%) 0.004 ms/op
Iteration   2: 3.824 ±(99.9%) 0.003 ms/op
Iteration   3: 3.825 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.845 ±(99.9%) 0.649 ms/op [Average]
  (min, avg, max) = (3.824, 3.845, 3.886), stdev = 0.036
  CI (99.9%): [3.196, 4.494] (assumes normal distribution)


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
# Warmup Iteration   1: 6.819 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 5.176 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.877 ±(99.9%) 0.012 ms/op
Iteration   1: 4.935 ±(99.9%) 0.011 ms/op
Iteration   2: 4.893 ±(99.9%) 0.017 ms/op
Iteration   3: 4.902 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.910 ±(99.9%) 0.407 ms/op [Average]
  (min, avg, max) = (4.893, 4.910, 4.935), stdev = 0.022
  CI (99.9%): [4.503, 5.317] (assumes normal distribution)


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
# Warmup Iteration   1: 5.563 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.186 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.986 ±(99.9%) 0.010 ms/op
Iteration   1: 3.928 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.915 ms/op
                 createUser·p0.50:   3.805 ms/op
                 createUser·p0.90:   4.669 ms/op
                 createUser·p0.95:   5.108 ms/op
                 createUser·p0.99:   7.373 ms/op
                 createUser·p0.999:  14.279 ms/op
                 createUser·p0.9999: 17.226 ms/op
                 createUser·p1.00:   17.727 ms/op

Iteration   2: 3.958 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.935 ms/op
                 createUser·p0.50:   3.863 ms/op
                 createUser·p0.90:   4.727 ms/op
                 createUser·p0.95:   5.095 ms/op
                 createUser·p0.99:   7.096 ms/op
                 createUser·p0.999:  12.468 ms/op
                 createUser·p0.9999: 23.162 ms/op
                 createUser·p1.00:   23.527 ms/op

Iteration   3: 3.869 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.990 ms/op
                 createUser·p0.50:   3.781 ms/op
                 createUser·p0.90:   4.645 ms/op
                 createUser·p0.95:   5.054 ms/op
                 createUser·p0.99:   6.521 ms/op
                 createUser·p0.999:  12.222 ms/op
                 createUser·p0.9999: 23.027 ms/op
                 createUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 244898
  mean =      3.918 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4961 
    [ 2.500,  5.000) = 225946 
    [ 5.000,  7.500) = 12099 
    [ 7.500, 10.000) = 1296 
    [10.000, 12.500) = 294 
    [12.500, 15.000) = 157 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.915 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.686 ms/op
     p(95.0000) =      5.087 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =     13.389 ms/op
     p(99.9900) =     22.970 ms/op
     p(99.9990) =     23.400 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


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
# Warmup Iteration   1: 5.216 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.908 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.597 ±(99.9%) 0.009 ms/op
Iteration   1: 3.639 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.736 ms/op
                 existUser·p0.50:   3.609 ms/op
                 existUser·p0.90:   4.309 ms/op
                 existUser·p0.95:   4.768 ms/op
                 existUser·p0.99:   6.726 ms/op
                 existUser·p0.999:  11.020 ms/op
                 existUser·p0.9999: 22.938 ms/op
                 existUser·p1.00:   23.396 ms/op

Iteration   2: 3.586 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.492 ms/op
                 existUser·p0.50:   3.580 ms/op
                 existUser·p0.90:   4.211 ms/op
                 existUser·p0.95:   4.588 ms/op
                 existUser·p0.99:   6.062 ms/op
                 existUser·p0.999:  10.349 ms/op
                 existUser·p0.9999: 16.107 ms/op
                 existUser·p1.00:   16.515 ms/op

Iteration   3: 3.459 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.915 ms/op
                 existUser·p0.50:   3.539 ms/op
                 existUser·p0.90:   4.149 ms/op
                 existUser·p0.95:   4.522 ms/op
                 existUser·p0.99:   5.833 ms/op
                 existUser·p0.999:  10.484 ms/op
                 existUser·p0.9999: 21.077 ms/op
                 existUser·p1.00:   22.512 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 269815
  mean =      3.560 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21795 
    [ 2.500,  5.000) = 239869 
    [ 5.000,  7.500) = 6942 
    [ 7.500, 10.000) = 872 
    [10.000, 12.500) = 203 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.492 ms/op
     p(50.0000) =      3.572 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      6.167 ms/op
     p(99.9000) =     10.568 ms/op
     p(99.9900) =     22.120 ms/op
     p(99.9990) =     23.318 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


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
# Warmup Iteration   1: 5.354 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.041 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.895 ±(99.9%) 0.009 ms/op
Iteration   1: 3.793 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.874 ms/op
                 getUser·p0.50:   3.760 ms/op
                 getUser·p0.90:   4.686 ms/op
                 getUser·p0.95:   5.120 ms/op
                 getUser·p0.99:   6.480 ms/op
                 getUser·p0.999:  10.471 ms/op
                 getUser·p0.9999: 15.216 ms/op
                 getUser·p1.00:   15.532 ms/op

Iteration   2: 3.815 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.863 ms/op
                 getUser·p0.50:   3.736 ms/op
                 getUser·p0.90:   4.538 ms/op
                 getUser·p0.95:   4.915 ms/op
                 getUser·p0.99:   6.685 ms/op
                 getUser·p0.999:  9.899 ms/op
                 getUser·p0.9999: 29.970 ms/op
                 getUser·p1.00:   30.179 ms/op

Iteration   3: 3.812 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.118 ms/op
                 getUser·p0.50:   3.715 ms/op
                 getUser·p0.90:   4.596 ms/op
                 getUser·p0.95:   4.964 ms/op
                 getUser·p0.99:   6.169 ms/op
                 getUser·p0.999:  10.471 ms/op
                 getUser·p0.9999: 20.225 ms/op
                 getUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 251999
  mean =      3.807 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9718 
    [ 2.500,  5.000) = 229610 
    [ 5.000,  7.500) = 11423 
    [ 7.500, 10.000) = 921 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.604 ms/op
     p(95.0000) =      5.005 ms/op
     p(99.0000) =      6.423 ms/op
     p(99.9000) =     10.371 ms/op
     p(99.9900) =     29.393 ms/op
     p(99.9990) =     30.130 ms/op
     p(99.9999) =     30.179 ms/op
    p(100.0000) =     30.179 ms/op


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
# Warmup Iteration   1: 6.579 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 5.310 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.969 ±(99.9%) 0.017 ms/op
Iteration   1: 4.916 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.522 ms/op
                 listUser·p0.50:   4.678 ms/op
                 listUser·p0.90:   6.291 ms/op
                 listUser·p0.95:   7.119 ms/op
                 listUser·p0.99:   9.093 ms/op
                 listUser·p0.999:  15.630 ms/op
                 listUser·p0.9999: 18.235 ms/op
                 listUser·p1.00:   20.382 ms/op

Iteration   2: 5.062 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.505 ms/op
                 listUser·p0.50:   4.801 ms/op
                 listUser·p0.90:   6.324 ms/op
                 listUser·p0.95:   7.225 ms/op
                 listUser·p0.99:   9.273 ms/op
                 listUser·p0.999:  20.965 ms/op
                 listUser·p0.9999: 25.079 ms/op
                 listUser·p1.00:   25.362 ms/op

Iteration   3: 4.807 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.491 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   5.882 ms/op
                 listUser·p0.95:   6.734 ms/op
                 listUser·p0.99:   8.838 ms/op
                 listUser·p0.999:  21.885 ms/op
                 listUser·p0.9999: 27.867 ms/op
                 listUser·p1.00:   29.983 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 194842
  mean =      4.926 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 174 
    [ 2.500,  5.000) = 132038 
    [ 5.000,  7.500) = 55915 
    [ 7.500, 10.000) = 5614 
    [10.000, 12.500) = 698 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.491 ms/op
     p(50.0000) =      4.702 ms/op
     p(90.0000) =      6.177 ms/op
     p(95.0000) =      7.045 ms/op
     p(99.0000) =      9.077 ms/op
     p(99.9000) =     18.088 ms/op
     p(99.9900) =     26.640 ms/op
     p(99.9990) =     28.926 ms/op
     p(99.9999) =     29.983 ms/op
    p(100.0000) =     29.983 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.339 ± 0.729  ops/ms
ClientGrpc.existUser                       thrpt       3   8.762 ± 2.137  ops/ms
ClientGrpc.getUser                         thrpt       3   8.328 ± 2.052  ops/ms
ClientGrpc.listUser                        thrpt       3   6.516 ± 0.353  ops/ms
ClientGrpc.createUser                       avgt       3   3.797 ± 0.898   ms/op
ClientGrpc.existUser                        avgt       3   3.671 ± 1.484   ms/op
ClientGrpc.getUser                          avgt       3   3.845 ± 0.649   ms/op
ClientGrpc.listUser                         avgt       3   4.910 ± 0.407   ms/op
ClientGrpc.createUser                     sample  244898   3.918 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.915           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.817           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.686           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.087           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.037           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.389           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.970           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.527           ms/op
ClientGrpc.existUser                      sample  269815   3.560 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.492           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.572           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.628           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.167           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.568           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.120           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.396           ms/op
ClientGrpc.getUser                        sample  251999   3.807 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.863           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.736           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.604           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.005           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.423           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.371           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          29.393           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.179           ms/op
ClientGrpc.listUser                       sample  194842   4.926 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.491           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.702           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.177           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.045           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.077           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.088           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.640           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.983           ms/op
