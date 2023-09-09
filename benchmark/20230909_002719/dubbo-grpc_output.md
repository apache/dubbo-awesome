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
# Warmup Iteration   1: 3.616 ops/ms
# Warmup Iteration   2: 8.539 ops/ms
# Warmup Iteration   3: 9.961 ops/ms
Iteration   1: 10.089 ops/ms
Iteration   2: 10.298 ops/ms
Iteration   3: 10.125 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.171 ±(99.9%) 2.035 ops/ms [Average]
  (min, avg, max) = (10.089, 10.171, 10.298), stdev = 0.112
  CI (99.9%): [8.136, 12.206] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.337 ops/ms
# Warmup Iteration   2: 9.852 ops/ms
# Warmup Iteration   3: 10.628 ops/ms
Iteration   1: 10.802 ops/ms
Iteration   2: 10.649 ops/ms
Iteration   3: 10.821 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.757 ±(99.9%) 1.720 ops/ms [Average]
  (min, avg, max) = (10.649, 10.757, 10.821), stdev = 0.094
  CI (99.9%): [9.037, 12.478] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.162 ops/ms
# Warmup Iteration   2: 9.687 ops/ms
# Warmup Iteration   3: 9.792 ops/ms
Iteration   1: 10.296 ops/ms
Iteration   2: 10.179 ops/ms
Iteration   3: 10.471 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.315 ±(99.9%) 2.672 ops/ms [Average]
  (min, avg, max) = (10.179, 10.315, 10.471), stdev = 0.146
  CI (99.9%): [7.644, 12.987] (assumes normal distribution)


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
# Warmup Iteration   1: 5.143 ops/ms
# Warmup Iteration   2: 7.349 ops/ms
# Warmup Iteration   3: 7.477 ops/ms
Iteration   1: 7.529 ops/ms
Iteration   2: 7.731 ops/ms
Iteration   3: 7.691 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.650 ±(99.9%) 1.952 ops/ms [Average]
  (min, avg, max) = (7.529, 7.650, 7.731), stdev = 0.107
  CI (99.9%): [5.698, 9.602] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 5.009 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.302 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 3.247 ±(99.9%) 0.003 ms/op
Iteration   1: 3.212 ±(99.9%) 0.007 ms/op
Iteration   2: 3.200 ±(99.9%) 0.003 ms/op
Iteration   3: 3.234 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.215 ±(99.9%) 0.315 ms/op [Average]
  (min, avg, max) = (3.200, 3.215, 3.234), stdev = 0.017
  CI (99.9%): [2.901, 3.530] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.189 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.135 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.002 ms/op
Iteration   1: 3.056 ±(99.9%) 0.002 ms/op
Iteration   2: 3.055 ±(99.9%) 0.002 ms/op
Iteration   3: 2.918 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.010 ±(99.9%) 1.443 ms/op [Average]
  (min, avg, max) = (2.918, 3.010, 3.056), stdev = 0.079
  CI (99.9%): [1.566, 4.453] (assumes normal distribution)


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
# Warmup Iteration   1: 4.685 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.290 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.225 ±(99.9%) 0.004 ms/op
Iteration   1: 3.164 ±(99.9%) 0.003 ms/op
Iteration   2: 3.115 ±(99.9%) 0.003 ms/op
Iteration   3: 3.105 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.128 ±(99.9%) 0.573 ms/op [Average]
  (min, avg, max) = (3.105, 3.128, 3.164), stdev = 0.031
  CI (99.9%): [2.555, 3.701] (assumes normal distribution)


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
# Warmup Iteration   1: 6.240 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.388 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.239 ±(99.9%) 0.011 ms/op
Iteration   1: 4.272 ±(99.9%) 0.015 ms/op
Iteration   2: 4.308 ±(99.9%) 0.021 ms/op
Iteration   3: 4.290 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.290 ±(99.9%) 0.325 ms/op [Average]
  (min, avg, max) = (4.272, 4.290, 4.308), stdev = 0.018
  CI (99.9%): [3.965, 4.615] (assumes normal distribution)


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
# Warmup Iteration   1: 4.581 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.160 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.117 ±(99.9%) 0.007 ms/op
Iteration   1: 3.114 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.814 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   5.210 ms/op
                 createUser·p0.999:  11.242 ms/op
                 createUser·p0.9999: 13.393 ms/op
                 createUser·p1.00:   13.910 ms/op

Iteration   2: 3.151 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.801 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   5.014 ms/op
                 createUser·p0.999:  9.259 ms/op
                 createUser·p0.9999: 16.997 ms/op
                 createUser·p1.00:   17.596 ms/op

Iteration   3: 3.192 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.707 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   4.121 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  9.920 ms/op
                 createUser·p0.9999: 17.924 ms/op
                 createUser·p1.00:   19.431 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 304853
  mean =      3.152 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 917 
    [ 1.250,  2.500) = 17777 
    [ 2.500,  3.750) = 256441 
    [ 3.750,  5.000) = 25933 
    [ 5.000,  6.250) = 2063 
    [ 6.250,  7.500) = 933 
    [ 7.500,  8.750) = 271 
    [ 8.750, 10.000) = 197 
    [10.000, 11.250) = 42 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 57 
    [16.250, 17.500) = 46 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.707 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      4.047 ms/op
     p(99.0000) =      5.202 ms/op
     p(99.9000) =     10.668 ms/op
     p(99.9900) =     17.187 ms/op
     p(99.9990) =     19.222 ms/op
     p(99.9999) =     19.431 ms/op
    p(100.0000) =     19.431 ms/op


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
# Warmup Iteration   1: 4.253 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.194 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.969 ±(99.9%) 0.007 ms/op
Iteration   1: 3.017 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.588 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  6.783 ms/op
                 existUser·p0.9999: 16.754 ms/op
                 existUser·p1.00:   18.416 ms/op

Iteration   2: 3.048 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.731 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   4.850 ms/op
                 existUser·p0.999:  11.095 ms/op
                 existUser·p0.9999: 18.874 ms/op
                 existUser·p1.00:   19.497 ms/op

Iteration   3: 2.999 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.681 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   4.751 ms/op
                 existUser·p0.999:  9.790 ms/op
                 existUser·p0.9999: 20.840 ms/op
                 existUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 317580
  mean =      3.021 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27564 
    [ 2.500,  5.000) = 287843 
    [ 5.000,  7.500) = 1602 
    [ 7.500, 10.000) = 291 
    [10.000, 12.500) = 151 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.588 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.661 ms/op
     p(99.9000) =      8.908 ms/op
     p(99.9900) =     19.447 ms/op
     p(99.9990) =     20.939 ms/op
     p(99.9999) =     20.972 ms/op
    p(100.0000) =     20.972 ms/op


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
# Warmup Iteration   1: 4.211 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.215 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.129 ±(99.9%) 0.007 ms/op
Iteration   1: 3.163 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.830 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   5.399 ms/op
                 getUser·p0.999:  9.960 ms/op
                 getUser·p0.9999: 22.115 ms/op
                 getUser·p1.00:   22.446 ms/op

Iteration   2: 3.161 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.851 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   4.071 ms/op
                 getUser·p0.99:   5.014 ms/op
                 getUser·p0.999:  7.826 ms/op
                 getUser·p0.9999: 17.686 ms/op
                 getUser·p1.00:   17.924 ms/op

Iteration   3: 3.132 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.882 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  8.959 ms/op
                 getUser·p0.9999: 26.765 ms/op
                 getUser·p1.00:   27.132 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 304502
  mean =      3.152 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18596 
    [ 2.500,  5.000) = 282595 
    [ 5.000,  7.500) = 2630 
    [ 7.500, 10.000) = 480 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.830 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.091 ms/op
     p(99.0000) =      5.071 ms/op
     p(99.9000) =      9.028 ms/op
     p(99.9900) =     25.330 ms/op
     p(99.9990) =     27.093 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


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
# Warmup Iteration   1: 5.464 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.359 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.213 ±(99.9%) 0.012 ms/op
Iteration   1: 4.279 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.343 ms/op
                 listUser·p0.50:   4.030 ms/op
                 listUser·p0.90:   5.464 ms/op
                 listUser·p0.95:   6.234 ms/op
                 listUser·p0.99:   8.110 ms/op
                 listUser·p0.999:  16.195 ms/op
                 listUser·p0.9999: 24.268 ms/op
                 listUser·p1.00:   25.788 ms/op

Iteration   2: 4.270 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.741 ms/op
                 listUser·p0.50:   4.026 ms/op
                 listUser·p0.90:   5.579 ms/op
                 listUser·p0.95:   6.373 ms/op
                 listUser·p0.99:   7.848 ms/op
                 listUser·p0.999:  19.173 ms/op
                 listUser·p0.9999: 21.545 ms/op
                 listUser·p1.00:   22.020 ms/op

Iteration   3: 4.293 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.946 ms/op
                 listUser·p0.50:   4.055 ms/op
                 listUser·p0.90:   5.562 ms/op
                 listUser·p0.95:   6.267 ms/op
                 listUser·p0.99:   7.979 ms/op
                 listUser·p0.999:  18.580 ms/op
                 listUser·p0.9999: 22.439 ms/op
                 listUser·p1.00:   23.560 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 224255
  mean =      4.281 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1524 
    [ 2.500,  5.000) = 188030 
    [ 5.000,  7.500) = 31442 
    [ 7.500, 10.000) = 2446 
    [10.000, 12.500) = 225 
    [12.500, 15.000) = 172 
    [15.000, 17.500) = 166 
    [17.500, 20.000) = 161 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.741 ms/op
     p(50.0000) =      4.039 ms/op
     p(90.0000) =      5.538 ms/op
     p(95.0000) =      6.291 ms/op
     p(99.0000) =      7.974 ms/op
     p(99.9000) =     17.916 ms/op
     p(99.9900) =     21.992 ms/op
     p(99.9990) =     25.414 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.171 ± 2.035  ops/ms
ClientGrpc.existUser                       thrpt       3  10.757 ± 1.720  ops/ms
ClientGrpc.getUser                         thrpt       3  10.315 ± 2.672  ops/ms
ClientGrpc.listUser                        thrpt       3   7.650 ± 1.952  ops/ms
ClientGrpc.createUser                       avgt       3   3.215 ± 0.315   ms/op
ClientGrpc.existUser                        avgt       3   3.010 ± 1.443   ms/op
ClientGrpc.getUser                          avgt       3   3.128 ± 0.573   ms/op
ClientGrpc.listUser                         avgt       3   4.290 ± 0.325   ms/op
ClientGrpc.createUser                     sample  304853   3.152 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.707           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.105           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.740           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.047           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.202           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.668           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.187           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.431           ms/op
ClientGrpc.existUser                      sample  317580   3.021 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.588           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.978           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.564           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.797           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.661           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.908           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.447           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.972           ms/op
ClientGrpc.getUser                        sample  304502   3.152 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.830           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.097           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.777           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.091           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.071           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.028           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.330           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.132           ms/op
ClientGrpc.listUser                       sample  224255   4.281 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.741           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.039           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.538           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.291           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.974           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.916           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.992           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.788           ms/op
