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
# Warmup Iteration   1: 2.639 ops/ms
# Warmup Iteration   2: 6.269 ops/ms
# Warmup Iteration   3: 7.472 ops/ms
Iteration   1: 7.246 ops/ms
Iteration   2: 7.429 ops/ms
Iteration   3: 7.812 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.496 ±(99.9%) 5.273 ops/ms [Average]
  (min, avg, max) = (7.246, 7.496, 7.812), stdev = 0.289
  CI (99.9%): [2.222, 12.769] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.206 ops/ms
# Warmup Iteration   2: 7.909 ops/ms
# Warmup Iteration   3: 8.332 ops/ms
Iteration   1: 8.718 ops/ms
Iteration   2: 8.553 ops/ms
Iteration   3: 8.216 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.496 ±(99.9%) 4.672 ops/ms [Average]
  (min, avg, max) = (8.216, 8.496, 8.718), stdev = 0.256
  CI (99.9%): [3.824, 13.168] (assumes normal distribution)


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
# Warmup Iteration   1: 4.738 ops/ms
# Warmup Iteration   2: 6.717 ops/ms
# Warmup Iteration   3: 6.721 ops/ms
Iteration   1: 8.013 ops/ms
Iteration   2: 7.905 ops/ms
Iteration   3: 7.986 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.968 ±(99.9%) 1.030 ops/ms [Average]
  (min, avg, max) = (7.905, 7.968, 8.013), stdev = 0.056
  CI (99.9%): [6.938, 8.998] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.941 ops/ms
# Warmup Iteration   2: 5.481 ops/ms
# Warmup Iteration   3: 5.885 ops/ms
Iteration   1: 5.943 ops/ms
Iteration   2: 5.565 ops/ms
Iteration   3: 5.812 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.773 ±(99.9%) 3.503 ops/ms [Average]
  (min, avg, max) = (5.565, 5.773, 5.943), stdev = 0.192
  CI (99.9%): [2.270, 9.277] (assumes normal distribution)


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
# Warmup Iteration   1: 6.452 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.376 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.241 ±(99.9%) 0.023 ms/op
Iteration   1: 4.033 ±(99.9%) 0.003 ms/op
Iteration   2: 3.966 ±(99.9%) 0.003 ms/op
Iteration   3: 4.192 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.064 ±(99.9%) 2.121 ms/op [Average]
  (min, avg, max) = (3.966, 4.064, 4.192), stdev = 0.116
  CI (99.9%): [1.942, 6.185] (assumes normal distribution)


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
# Warmup Iteration   1: 5.698 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.321 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.780 ±(99.9%) 0.004 ms/op
Iteration   1: 3.762 ±(99.9%) 0.003 ms/op
Iteration   2: 3.657 ±(99.9%) 0.003 ms/op
Iteration   3: 3.791 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.737 ±(99.9%) 1.285 ms/op [Average]
  (min, avg, max) = (3.657, 3.737, 3.791), stdev = 0.070
  CI (99.9%): [2.452, 5.021] (assumes normal distribution)


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
# Warmup Iteration   1: 6.044 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.504 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.155 ±(99.9%) 0.007 ms/op
Iteration   1: 4.043 ±(99.9%) 0.003 ms/op
Iteration   2: 3.892 ±(99.9%) 0.003 ms/op
Iteration   3: 4.007 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.981 ±(99.9%) 1.442 ms/op [Average]
  (min, avg, max) = (3.892, 3.981, 4.043), stdev = 0.079
  CI (99.9%): [2.539, 5.423] (assumes normal distribution)


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
# Warmup Iteration   1: 7.570 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 5.672 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.203 ±(99.9%) 0.014 ms/op
Iteration   1: 5.369 ±(99.9%) 0.018 ms/op
Iteration   2: 5.432 ±(99.9%) 0.011 ms/op
Iteration   3: 5.202 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.334 ±(99.9%) 2.171 ms/op [Average]
  (min, avg, max) = (5.202, 5.334, 5.432), stdev = 0.119
  CI (99.9%): [3.164, 7.505] (assumes normal distribution)


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
# Warmup Iteration   1: 5.779 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.160 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.015 ±(99.9%) 0.011 ms/op
Iteration   1: 3.908 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.944 ms/op
                 createUser·p0.50:   3.838 ms/op
                 createUser·p0.90:   4.923 ms/op
                 createUser·p0.95:   5.349 ms/op
                 createUser·p0.99:   6.750 ms/op
                 createUser·p0.999:  9.290 ms/op
                 createUser·p0.9999: 14.705 ms/op
                 createUser·p1.00:   16.941 ms/op

Iteration   2: 4.025 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.967 ms/op
                 createUser·p0.50:   3.891 ms/op
                 createUser·p0.90:   5.054 ms/op
                 createUser·p0.95:   5.489 ms/op
                 createUser·p0.99:   7.160 ms/op
                 createUser·p0.999:  15.881 ms/op
                 createUser·p0.9999: 23.103 ms/op
                 createUser·p1.00:   26.640 ms/op

Iteration   3: 3.910 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.643 ms/op
                 createUser·p0.50:   3.858 ms/op
                 createUser·p0.90:   4.956 ms/op
                 createUser·p0.95:   5.333 ms/op
                 createUser·p0.99:   6.341 ms/op
                 createUser·p0.999:  9.752 ms/op
                 createUser·p0.9999: 17.820 ms/op
                 createUser·p1.00:   18.776 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 243070
  mean =      3.947 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9206 
    [ 2.500,  5.000) = 210552 
    [ 5.000,  7.500) = 21899 
    [ 7.500, 10.000) = 1116 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.643 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.973 ms/op
     p(95.0000) =      5.390 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     10.435 ms/op
     p(99.9900) =     22.403 ms/op
     p(99.9990) =     25.913 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


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
# Warmup Iteration   1: 5.751 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.151 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.872 ±(99.9%) 0.010 ms/op
Iteration   1: 3.807 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.983 ms/op
                 existUser·p0.50:   3.736 ms/op
                 existUser·p0.90:   4.760 ms/op
                 existUser·p0.95:   5.177 ms/op
                 existUser·p0.99:   6.379 ms/op
                 existUser·p0.999:  9.895 ms/op
                 existUser·p0.9999: 17.596 ms/op
                 existUser·p1.00:   17.891 ms/op

Iteration   2: 3.764 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.817 ms/op
                 existUser·p0.50:   3.715 ms/op
                 existUser·p0.90:   4.653 ms/op
                 existUser·p0.95:   5.079 ms/op
                 existUser·p0.99:   6.399 ms/op
                 existUser·p0.999:  12.026 ms/op
                 existUser·p0.9999: 18.170 ms/op
                 existUser·p1.00:   21.332 ms/op

Iteration   3: 3.910 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.987 ms/op
                 existUser·p0.50:   3.809 ms/op
                 existUser·p0.90:   4.801 ms/op
                 existUser·p0.95:   5.177 ms/op
                 existUser·p0.99:   6.883 ms/op
                 existUser·p0.999:  11.190 ms/op
                 existUser·p0.9999: 20.677 ms/op
                 existUser·p1.00:   20.873 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 250803
  mean =      3.826 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9879 
    [ 2.500,  5.000) = 224807 
    [ 5.000,  7.500) = 14673 
    [ 7.500, 10.000) = 1036 
    [10.000, 12.500) = 252 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.817 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.743 ms/op
     p(95.0000) =      5.145 ms/op
     p(99.0000) =      6.554 ms/op
     p(99.9000) =     11.239 ms/op
     p(99.9900) =     20.182 ms/op
     p(99.9990) =     20.873 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


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
# Warmup Iteration   1: 5.839 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.230 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.062 ±(99.9%) 0.011 ms/op
Iteration   1: 3.906 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.966 ms/op
                 getUser·p0.50:   3.809 ms/op
                 getUser·p0.90:   4.891 ms/op
                 getUser·p0.95:   5.349 ms/op
                 getUser·p0.99:   6.785 ms/op
                 getUser·p0.999:  14.648 ms/op
                 getUser·p0.9999: 15.627 ms/op
                 getUser·p1.00:   15.860 ms/op

Iteration   2: 3.889 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.079 ms/op
                 getUser·p0.50:   3.813 ms/op
                 getUser·p0.90:   4.784 ms/op
                 getUser·p0.95:   5.186 ms/op
                 getUser·p0.99:   6.454 ms/op
                 getUser·p0.999:  10.652 ms/op
                 getUser·p0.9999: 19.352 ms/op
                 getUser·p1.00:   19.890 ms/op

Iteration   3: 4.036 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.964 ms/op
                 getUser·p0.50:   3.912 ms/op
                 getUser·p0.90:   5.030 ms/op
                 getUser·p0.95:   5.431 ms/op
                 getUser·p0.99:   7.012 ms/op
                 getUser·p0.999:  11.332 ms/op
                 getUser·p0.9999: 35.198 ms/op
                 getUser·p1.00:   35.586 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 243365
  mean =      3.943 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7199 
    [ 2.500,  5.000) = 215286 
    [ 5.000,  7.500) = 19333 
    [ 7.500, 10.000) = 1017 
    [10.000, 12.500) = 327 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.964 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.907 ms/op
     p(95.0000) =      5.333 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     11.643 ms/op
     p(99.9900) =     34.144 ms/op
     p(99.9990) =     35.529 ms/op
     p(99.9999) =     35.586 ms/op
    p(100.0000) =     35.586 ms/op


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
# Warmup Iteration   1: 8.225 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 5.053 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.518 ±(99.9%) 0.015 ms/op
Iteration   1: 4.427 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.871 ms/op
                 listUser·p0.50:   4.211 ms/op
                 listUser·p0.90:   5.734 ms/op
                 listUser·p0.95:   6.595 ms/op
                 listUser·p0.99:   8.348 ms/op
                 listUser·p0.999:  16.747 ms/op
                 listUser·p0.9999: 19.787 ms/op
                 listUser·p1.00:   21.168 ms/op

Iteration   2: 4.458 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.909 ms/op
                 listUser·p0.50:   4.252 ms/op
                 listUser·p0.90:   5.693 ms/op
                 listUser·p0.95:   6.545 ms/op
                 listUser·p0.99:   8.471 ms/op
                 listUser·p0.999:  16.007 ms/op
                 listUser·p0.9999: 18.594 ms/op
                 listUser·p1.00:   19.497 ms/op

Iteration   3: 4.536 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.019 ms/op
                 listUser·p0.50:   4.317 ms/op
                 listUser·p0.90:   5.882 ms/op
                 listUser·p0.95:   6.693 ms/op
                 listUser·p0.99:   8.798 ms/op
                 listUser·p0.999:  17.302 ms/op
                 listUser·p0.9999: 25.392 ms/op
                 listUser·p1.00:   25.821 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 214637
  mean =      4.473 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1376 
    [ 2.500,  5.000) = 171024 
    [ 5.000,  7.500) = 37370 
    [ 7.500, 10.000) = 3958 
    [10.000, 12.500) = 440 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 211 
    [17.500, 20.000) = 128 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      4.260 ms/op
     p(90.0000) =      5.767 ms/op
     p(95.0000) =      6.611 ms/op
     p(99.0000) =      8.536 ms/op
     p(99.9000) =     16.810 ms/op
     p(99.9900) =     20.024 ms/op
     p(99.9990) =     25.713 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.496 ± 5.273  ops/ms
ClientGrpc.existUser                       thrpt       3   8.496 ± 4.672  ops/ms
ClientGrpc.getUser                         thrpt       3   7.968 ± 1.030  ops/ms
ClientGrpc.listUser                        thrpt       3   5.773 ± 3.503  ops/ms
ClientGrpc.createUser                       avgt       3   4.064 ± 2.121   ms/op
ClientGrpc.existUser                        avgt       3   3.737 ± 1.285   ms/op
ClientGrpc.getUser                          avgt       3   3.981 ± 1.442   ms/op
ClientGrpc.listUser                         avgt       3   5.334 ± 2.171   ms/op
ClientGrpc.createUser                     sample  243070   3.947 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.643           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.863           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.973           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.390           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.717           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.435           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.403           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.640           ms/op
ClientGrpc.existUser                      sample  250803   3.826 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.817           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.752           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.743           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.145           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.554           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.239           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.182           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.332           ms/op
ClientGrpc.getUser                        sample  243365   3.943 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.964           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.842           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.907           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.333           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.726           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.643           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          34.144           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          35.586           ms/op
ClientGrpc.listUser                       sample  214637   4.473 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.871           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.260           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.767           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.611           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.536           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.810           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.024           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.821           ms/op
