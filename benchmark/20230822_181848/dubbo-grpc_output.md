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
# Warmup Iteration   1: 4.726 ops/ms
# Warmup Iteration   2: 9.781 ops/ms
# Warmup Iteration   3: 10.222 ops/ms
Iteration   1: 10.624 ops/ms
Iteration   2: 10.503 ops/ms
Iteration   3: 10.579 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.569 ±(99.9%) 1.121 ops/ms [Average]
  (min, avg, max) = (10.503, 10.569, 10.624), stdev = 0.061
  CI (99.9%): [9.448, 11.690] (assumes normal distribution)


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
# Warmup Iteration   1: 8.756 ops/ms
# Warmup Iteration   2: 11.031 ops/ms
# Warmup Iteration   3: 11.123 ops/ms
Iteration   1: 11.149 ops/ms
Iteration   2: 11.289 ops/ms
Iteration   3: 11.486 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.308 ±(99.9%) 3.089 ops/ms [Average]
  (min, avg, max) = (11.149, 11.308, 11.486), stdev = 0.169
  CI (99.9%): [8.219, 14.397] (assumes normal distribution)


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
# Warmup Iteration   1: 7.623 ops/ms
# Warmup Iteration   2: 10.258 ops/ms
# Warmup Iteration   3: 10.634 ops/ms
Iteration   1: 10.591 ops/ms
Iteration   2: 10.659 ops/ms
Iteration   3: 10.581 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.610 ±(99.9%) 0.774 ops/ms [Average]
  (min, avg, max) = (10.581, 10.610, 10.659), stdev = 0.042
  CI (99.9%): [9.836, 11.384] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.897 ops/ms
# Warmup Iteration   2: 7.814 ops/ms
# Warmup Iteration   3: 8.097 ops/ms
Iteration   1: 8.083 ops/ms
Iteration   2: 8.062 ops/ms
Iteration   3: 8.034 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.060 ±(99.9%) 0.454 ops/ms [Average]
  (min, avg, max) = (8.034, 8.060, 8.083), stdev = 0.025
  CI (99.9%): [7.606, 8.513] (assumes normal distribution)


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
# Warmup Iteration   1: 4.089 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.157 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.003 ms/op
Iteration   1: 3.038 ±(99.9%) 0.003 ms/op
Iteration   2: 2.990 ±(99.9%) 0.004 ms/op
Iteration   3: 3.081 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.037 ±(99.9%) 0.831 ms/op [Average]
  (min, avg, max) = (2.990, 3.037, 3.081), stdev = 0.046
  CI (99.9%): [2.205, 3.868] (assumes normal distribution)


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
# Warmup Iteration   1: 3.911 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.945 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.883 ±(99.9%) 0.005 ms/op
Iteration   1: 2.898 ±(99.9%) 0.004 ms/op
Iteration   2: 2.782 ±(99.9%) 0.003 ms/op
Iteration   3: 2.882 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.854 ±(99.9%) 1.140 ms/op [Average]
  (min, avg, max) = (2.782, 2.854, 2.898), stdev = 0.062
  CI (99.9%): [1.714, 3.994] (assumes normal distribution)


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
# Warmup Iteration   1: 4.049 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.144 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.003 ms/op
Iteration   1: 3.013 ±(99.9%) 0.003 ms/op
Iteration   2: 3.016 ±(99.9%) 0.002 ms/op
Iteration   3: 3.010 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.013 ±(99.9%) 0.055 ms/op [Average]
  (min, avg, max) = (3.010, 3.013, 3.016), stdev = 0.003
  CI (99.9%): [2.958, 3.068] (assumes normal distribution)


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
# Warmup Iteration   1: 4.615 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.203 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.941 ±(99.9%) 0.026 ms/op
Iteration   1: 3.991 ±(99.9%) 0.018 ms/op
Iteration   2: 3.938 ±(99.9%) 0.028 ms/op
Iteration   3: 3.924 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.951 ±(99.9%) 0.646 ms/op [Average]
  (min, avg, max) = (3.924, 3.951, 3.991), stdev = 0.035
  CI (99.9%): [3.306, 4.597] (assumes normal distribution)


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
# Warmup Iteration   1: 3.868 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.121 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.007 ms/op
Iteration   1: 2.977 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.539 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.416 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.678 ms/op
                 createUser·p0.999:  10.732 ms/op
                 createUser·p0.9999: 18.653 ms/op
                 createUser·p1.00:   19.005 ms/op

Iteration   2: 2.968 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.742 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.588 ms/op
                 createUser·p0.999:  7.389 ms/op
                 createUser·p0.9999: 16.134 ms/op
                 createUser·p1.00:   16.433 ms/op

Iteration   3: 2.994 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.752 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.876 ms/op
                 createUser·p0.99:   4.776 ms/op
                 createUser·p0.999:  11.865 ms/op
                 createUser·p0.9999: 18.219 ms/op
                 createUser·p1.00:   18.481 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321937
  mean =      2.980 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3127 
    [ 1.250,  2.500) = 29001 
    [ 2.500,  3.750) = 272138 
    [ 3.750,  5.000) = 15659 
    [ 5.000,  6.250) = 999 
    [ 6.250,  7.500) = 396 
    [ 7.500,  8.750) = 271 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 63 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 49 

  Percentiles, ms/op:
      p(0.0000) =      0.539 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.686 ms/op
     p(99.9000) =     10.307 ms/op
     p(99.9900) =     18.376 ms/op
     p(99.9990) =     18.867 ms/op
     p(99.9999) =     19.005 ms/op
    p(100.0000) =     19.005 ms/op


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
# Warmup Iteration   1: 3.873 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.977 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.910 ±(99.9%) 0.007 ms/op
Iteration   1: 2.937 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.796 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   4.637 ms/op
                 existUser·p0.999:  7.332 ms/op
                 existUser·p0.9999: 17.606 ms/op
                 existUser·p1.00:   18.579 ms/op

Iteration   2: 2.901 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.489 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   4.686 ms/op
                 existUser·p0.999:  7.339 ms/op
                 existUser·p0.9999: 18.251 ms/op
                 existUser·p1.00:   18.809 ms/op

Iteration   3: 2.910 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.551 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.710 ms/op
                 existUser·p0.999:  8.539 ms/op
                 existUser·p0.9999: 26.936 ms/op
                 existUser·p1.00:   27.230 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329311
  mean =      2.916 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43375 
    [ 2.500,  5.000) = 283840 
    [ 5.000,  7.500) = 1661 
    [ 7.500, 10.000) = 243 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.489 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      4.678 ms/op
     p(99.9000) =      7.922 ms/op
     p(99.9900) =     19.230 ms/op
     p(99.9990) =     27.197 ms/op
     p(99.9999) =     27.230 ms/op
    p(100.0000) =     27.230 ms/op


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
# Warmup Iteration   1: 3.942 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.146 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.008 ms/op
Iteration   1: 3.027 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.760 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.858 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  8.471 ms/op
                 getUser·p0.9999: 20.349 ms/op
                 getUser·p1.00:   20.382 ms/op

Iteration   2: 3.038 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.622 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  7.676 ms/op
                 getUser·p0.9999: 19.825 ms/op
                 getUser·p1.00:   20.120 ms/op

Iteration   3: 3.054 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.370 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.407 ms/op
                 getUser·p0.999:  7.302 ms/op
                 getUser·p0.9999: 20.726 ms/op
                 getUser·p1.00:   21.201 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315782
  mean =      3.039 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26567 
    [ 2.500,  5.000) = 287462 
    [ 5.000,  7.500) = 1371 
    [ 7.500, 10.000) = 158 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.370 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      7.954 ms/op
     p(99.9900) =     20.349 ms/op
     p(99.9990) =     21.065 ms/op
     p(99.9999) =     21.201 ms/op
    p(100.0000) =     21.201 ms/op


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
# Warmup Iteration   1: 5.250 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.121 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.978 ±(99.9%) 0.012 ms/op
Iteration   1: 3.958 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.953 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  12.785 ms/op
                 listUser·p0.9999: 14.623 ms/op
                 listUser·p1.00:   15.057 ms/op

Iteration   2: 3.936 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.202 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  15.505 ms/op
                 listUser·p0.9999: 23.781 ms/op
                 listUser·p1.00:   24.216 ms/op

Iteration   3: 4.007 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.044 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   7.201 ms/op
                 listUser·p0.999:  17.971 ms/op
                 listUser·p0.9999: 20.710 ms/op
                 listUser·p1.00:   20.939 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241914
  mean =      3.967 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4377 
    [ 2.500,  5.000) = 217082 
    [ 5.000,  7.500) = 18783 
    [ 7.500, 10.000) = 1063 
    [10.000, 12.500) = 245 
    [12.500, 15.000) = 129 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.953 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      4.841 ms/op
     p(95.0000) =      5.661 ms/op
     p(99.0000) =      6.988 ms/op
     p(99.9000) =     14.844 ms/op
     p(99.9900) =     23.062 ms/op
     p(99.9990) =     24.109 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.569 ± 1.121  ops/ms
ClientGrpc.existUser                       thrpt       3  11.308 ± 3.089  ops/ms
ClientGrpc.getUser                         thrpt       3  10.610 ± 0.774  ops/ms
ClientGrpc.listUser                        thrpt       3   8.060 ± 0.454  ops/ms
ClientGrpc.createUser                       avgt       3   3.037 ± 0.831   ms/op
ClientGrpc.existUser                        avgt       3   2.854 ± 1.140   ms/op
ClientGrpc.getUser                          avgt       3   3.013 ± 0.055   ms/op
ClientGrpc.listUser                         avgt       3   3.951 ± 0.646   ms/op
ClientGrpc.createUser                     sample  321937   2.980 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.539           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.974           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.469           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.797           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.686           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.307           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.376           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.005           ms/op
ClientGrpc.existUser                      sample  329311   2.916 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.489           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.445           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.690           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.678           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.922           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.230           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.230           ms/op
ClientGrpc.getUser                        sample  315782   3.039 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.370           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.035           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.559           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.813           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.530           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.954           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.349           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.201           ms/op
ClientGrpc.listUser                       sample  241914   3.967 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.953           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.826           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.841           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.661           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.988           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.844           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.062           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.216           ms/op
