# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.714 ops/ms
# Warmup Iteration   2: 8.983 ops/ms
# Warmup Iteration   3: 10.329 ops/ms
Iteration   1: 10.495 ops/ms
Iteration   2: 10.689 ops/ms
Iteration   3: 10.632 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.605 ±(99.9%) 1.823 ops/ms [Average]
  (min, avg, max) = (10.495, 10.605, 10.689), stdev = 0.100
  CI (99.9%): [8.782, 12.428] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.087 ops/ms
# Warmup Iteration   2: 10.894 ops/ms
# Warmup Iteration   3: 11.290 ops/ms
Iteration   1: 11.173 ops/ms
Iteration   2: 11.195 ops/ms
Iteration   3: 11.238 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.202 ±(99.9%) 0.604 ops/ms [Average]
  (min, avg, max) = (11.173, 11.202, 11.238), stdev = 0.033
  CI (99.9%): [10.597, 11.806] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.618 ops/ms
# Warmup Iteration   2: 10.491 ops/ms
# Warmup Iteration   3: 10.642 ops/ms
Iteration   1: 10.963 ops/ms
Iteration   2: 10.761 ops/ms
Iteration   3: 10.662 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.795 ±(99.9%) 2.805 ops/ms [Average]
  (min, avg, max) = (10.662, 10.795, 10.963), stdev = 0.154
  CI (99.9%): [7.990, 13.600] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.620 ops/ms
# Warmup Iteration   2: 8.085 ops/ms
# Warmup Iteration   3: 8.185 ops/ms
Iteration   1: 8.287 ops/ms
Iteration   2: 8.319 ops/ms
Iteration   3: 8.277 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.294 ±(99.9%) 0.405 ops/ms [Average]
  (min, avg, max) = (8.277, 8.294, 8.319), stdev = 0.022
  CI (99.9%): [7.889, 8.699] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.984 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.110 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.001 ±(99.9%) 0.004 ms/op
Iteration   1: 2.952 ±(99.9%) 0.003 ms/op
Iteration   2: 3.014 ±(99.9%) 0.002 ms/op
Iteration   3: 2.945 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.970 ±(99.9%) 0.690 ms/op [Average]
  (min, avg, max) = (2.945, 2.970, 3.014), stdev = 0.038
  CI (99.9%): [2.280, 3.660] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.865 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.001 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.864 ±(99.9%) 0.003 ms/op
Iteration   1: 2.774 ±(99.9%) 0.003 ms/op
Iteration   2: 2.840 ±(99.9%) 0.002 ms/op
Iteration   3: 2.877 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.831 ±(99.9%) 0.949 ms/op [Average]
  (min, avg, max) = (2.774, 2.831, 2.877), stdev = 0.052
  CI (99.9%): [1.882, 3.779] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.986 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.058 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.995 ±(99.9%) 0.003 ms/op
Iteration   1: 2.961 ±(99.9%) 0.002 ms/op
Iteration   2: 2.916 ±(99.9%) 0.003 ms/op
Iteration   3: 2.918 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.932 ±(99.9%) 0.463 ms/op [Average]
  (min, avg, max) = (2.916, 2.932, 2.961), stdev = 0.025
  CI (99.9%): [2.469, 3.395] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.633 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.005 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.854 ±(99.9%) 0.024 ms/op
Iteration   1: 3.883 ±(99.9%) 0.019 ms/op
Iteration   2: 3.811 ±(99.9%) 0.007 ms/op
Iteration   3: 3.853 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.849 ±(99.9%) 0.663 ms/op [Average]
  (min, avg, max) = (3.811, 3.849, 3.883), stdev = 0.036
  CI (99.9%): [3.186, 4.512] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.003 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.102 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.952 ±(99.9%) 0.007 ms/op
Iteration   1: 2.976 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.476 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.641 ms/op
                 createUser·p0.99:   4.194 ms/op
                 createUser·p0.999:  11.511 ms/op
                 createUser·p0.9999: 16.229 ms/op
                 createUser·p1.00:   19.169 ms/op

Iteration   2: 2.989 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.813 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.707 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  7.306 ms/op
                 createUser·p0.9999: 13.159 ms/op
                 createUser·p1.00:   13.779 ms/op

Iteration   3: 3.046 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.554 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   5.071 ms/op
                 createUser·p0.999:  10.437 ms/op
                 createUser·p0.9999: 22.086 ms/op
                 createUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319481
  mean =      3.003 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25011 
    [ 2.500,  5.000) = 292327 
    [ 5.000,  7.500) = 1580 
    [ 7.500, 10.000) = 232 
    [10.000, 12.500) = 152 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.476 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.563 ms/op
     p(99.9000) =     10.298 ms/op
     p(99.9900) =     21.629 ms/op
     p(99.9990) =     22.184 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.357 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.990 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.850 ±(99.9%) 0.006 ms/op
Iteration   1: 2.823 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.506 ms/op
                 existUser·p0.50:   2.822 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  6.631 ms/op
                 existUser·p0.9999: 12.048 ms/op
                 existUser·p1.00:   12.976 ms/op

Iteration   2: 2.844 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.651 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.490 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  7.697 ms/op
                 existUser·p0.9999: 24.062 ms/op
                 existUser·p1.00:   24.609 ms/op

Iteration   3: 2.819 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.552 ms/op
                 existUser·p0.50:   2.830 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.539 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  8.041 ms/op
                 existUser·p0.9999: 15.247 ms/op
                 existUser·p1.00:   15.925 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 339170
  mean =      2.829 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 59035 
    [ 2.500,  5.000) = 277727 
    [ 5.000,  7.500) = 1962 
    [ 7.500, 10.000) = 257 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.506 ms/op
     p(50.0000) =      2.834 ms/op
     p(90.0000) =      3.318 ms/op
     p(95.0000) =      3.518 ms/op
     p(99.0000) =      4.620 ms/op
     p(99.9000) =      7.879 ms/op
     p(99.9900) =     15.760 ms/op
     p(99.9990) =     24.412 ms/op
     p(99.9999) =     24.609 ms/op
    p(100.0000) =     24.609 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.927 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.950 ±(99.9%) 0.006 ms/op
Iteration   1: 2.910 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.633 ms/op
                 getUser·p0.50:   2.904 ms/op
                 getUser·p0.90:   3.408 ms/op
                 getUser·p0.95:   3.588 ms/op
                 getUser·p0.99:   4.202 ms/op
                 getUser·p0.999:  6.627 ms/op
                 getUser·p0.9999: 11.764 ms/op
                 getUser·p1.00:   12.141 ms/op

Iteration   2: 2.980 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.631 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   4.669 ms/op
                 getUser·p0.999:  7.659 ms/op
                 getUser·p0.9999: 13.587 ms/op
                 getUser·p1.00:   13.844 ms/op

Iteration   3: 2.957 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.764 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.457 ms/op
                 getUser·p0.95:   3.699 ms/op
                 getUser·p0.99:   4.661 ms/op
                 getUser·p0.999:  8.049 ms/op
                 getUser·p0.9999: 24.778 ms/op
                 getUser·p1.00:   25.133 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 325468
  mean =      2.949 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35746 
    [ 2.500,  5.000) = 287651 
    [ 5.000,  7.500) = 1606 
    [ 7.500, 10.000) = 272 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.674 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      7.860 ms/op
     p(99.9900) =     18.819 ms/op
     p(99.9990) =     25.035 ms/op
     p(99.9999) =     25.133 ms/op
    p(100.0000) =     25.133 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.325 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.003 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.900 ±(99.9%) 0.012 ms/op
Iteration   1: 3.833 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.116 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.480 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  13.217 ms/op
                 listUser·p0.9999: 23.341 ms/op
                 listUser·p1.00:   23.658 ms/op

Iteration   2: 3.920 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.913 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.761 ms/op
                 listUser·p0.99:   7.283 ms/op
                 listUser·p0.999:  15.679 ms/op
                 listUser·p0.9999: 19.530 ms/op
                 listUser·p1.00:   20.513 ms/op

Iteration   3: 3.893 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.422 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   7.290 ms/op
                 listUser·p0.999:  16.898 ms/op
                 listUser·p0.9999: 23.749 ms/op
                 listUser·p1.00:   23.822 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247341
  mean =      3.882 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5272 
    [ 2.500,  5.000) = 219561 
    [ 5.000,  7.500) = 20515 
    [ 7.500, 10.000) = 1488 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 145 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.422 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.915 ms/op
     p(95.0000) =      5.603 ms/op
     p(99.0000) =      7.217 ms/op
     p(99.9000) =     15.548 ms/op
     p(99.9900) =     23.396 ms/op
     p(99.9990) =     23.822 ms/op
     p(99.9999) =     23.822 ms/op
    p(100.0000) =     23.822 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.605 ± 1.823  ops/ms
ClientGrpc.existUser                       thrpt       3  11.202 ± 0.604  ops/ms
ClientGrpc.getUser                         thrpt       3  10.795 ± 2.805  ops/ms
ClientGrpc.listUser                        thrpt       3   8.294 ± 0.405  ops/ms
ClientGrpc.createUser                       avgt       3   2.970 ± 0.690   ms/op
ClientGrpc.existUser                        avgt       3   2.831 ± 0.949   ms/op
ClientGrpc.getUser                          avgt       3   2.932 ± 0.463   ms/op
ClientGrpc.listUser                         avgt       3   3.849 ± 0.663   ms/op
ClientGrpc.createUser                     sample  319481   3.003 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.476           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.974           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.510           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.703           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.563           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.298           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.629           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.217           ms/op
ClientGrpc.existUser                      sample  339170   2.829 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.506           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.834           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.318           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.518           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.620           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.879           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.760           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.609           ms/op
ClientGrpc.getUser                        sample  325468   2.949 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.631           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.941           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.457           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.674           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.448           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.860           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.819           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.133           ms/op
ClientGrpc.listUser                       sample  247341   3.882 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.422           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.715           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.915           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.603           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.217           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.548           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.396           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.822           ms/op
