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
# Warmup Iteration   1: 2.473 ops/ms
# Warmup Iteration   2: 5.936 ops/ms
# Warmup Iteration   3: 7.173 ops/ms
Iteration   1: 7.449 ops/ms
Iteration   2: 7.638 ops/ms
Iteration   3: 7.838 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.642 ±(99.9%) 3.553 ops/ms [Average]
  (min, avg, max) = (7.449, 7.642, 7.838), stdev = 0.195
  CI (99.9%): [4.089, 11.195] (assumes normal distribution)


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
# Warmup Iteration   1: 4.998 ops/ms
# Warmup Iteration   2: 7.482 ops/ms
# Warmup Iteration   3: 7.905 ops/ms
Iteration   1: 8.196 ops/ms
Iteration   2: 8.310 ops/ms
Iteration   3: 7.924 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.143 ±(99.9%) 3.613 ops/ms [Average]
  (min, avg, max) = (7.924, 8.143, 8.310), stdev = 0.198
  CI (99.9%): [4.530, 11.756] (assumes normal distribution)


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
# Warmup Iteration   1: 4.451 ops/ms
# Warmup Iteration   2: 6.801 ops/ms
# Warmup Iteration   3: 7.043 ops/ms
Iteration   1: 7.407 ops/ms
Iteration   2: 7.495 ops/ms
Iteration   3: 7.331 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.411 ±(99.9%) 1.490 ops/ms [Average]
  (min, avg, max) = (7.331, 7.411, 7.495), stdev = 0.082
  CI (99.9%): [5.921, 8.901] (assumes normal distribution)


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
# Warmup Iteration   1: 3.645 ops/ms
# Warmup Iteration   2: 5.490 ops/ms
# Warmup Iteration   3: 5.599 ops/ms
Iteration   1: 5.757 ops/ms
Iteration   2: 5.757 ops/ms
Iteration   3: 5.838 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.784 ±(99.9%) 0.853 ops/ms [Average]
  (min, avg, max) = (5.757, 5.784, 5.838), stdev = 0.047
  CI (99.9%): [4.931, 6.637] (assumes normal distribution)


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
# Warmup Iteration   1: 6.727 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.704 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.461 ±(99.9%) 0.019 ms/op
Iteration   1: 4.417 ±(99.9%) 0.004 ms/op
Iteration   2: 4.246 ±(99.9%) 0.004 ms/op
Iteration   3: 4.439 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.368 ±(99.9%) 1.933 ms/op [Average]
  (min, avg, max) = (4.246, 4.368, 4.439), stdev = 0.106
  CI (99.9%): [2.435, 6.301] (assumes normal distribution)


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
# Warmup Iteration   1: 6.363 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.409 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.177 ±(99.9%) 0.004 ms/op
Iteration   1: 3.989 ±(99.9%) 0.004 ms/op
Iteration   2: 4.036 ±(99.9%) 0.003 ms/op
Iteration   3: 4.271 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.099 ±(99.9%) 2.750 ms/op [Average]
  (min, avg, max) = (3.989, 4.099, 4.271), stdev = 0.151
  CI (99.9%): [1.349, 6.848] (assumes normal distribution)


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
# Warmup Iteration   1: 7.077 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 5.019 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.429 ±(99.9%) 0.016 ms/op
Iteration   1: 4.334 ±(99.9%) 0.003 ms/op
Iteration   2: 4.568 ±(99.9%) 0.003 ms/op
Iteration   3: 4.485 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.462 ±(99.9%) 2.166 ms/op [Average]
  (min, avg, max) = (4.334, 4.462, 4.568), stdev = 0.119
  CI (99.9%): [2.296, 6.628] (assumes normal distribution)


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
# Warmup Iteration   1: 8.062 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 6.182 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.997 ±(99.9%) 0.017 ms/op
Iteration   1: 5.725 ±(99.9%) 0.016 ms/op
Iteration   2: 5.593 ±(99.9%) 0.020 ms/op
Iteration   3: 5.599 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.639 ±(99.9%) 1.357 ms/op [Average]
  (min, avg, max) = (5.593, 5.639, 5.725), stdev = 0.074
  CI (99.9%): [4.282, 6.996] (assumes normal distribution)


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
# Warmup Iteration   1: 6.816 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 4.657 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.318 ±(99.9%) 0.014 ms/op
Iteration   1: 4.154 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.847 ms/op
                 createUser·p0.50:   4.071 ms/op
                 createUser·p0.90:   5.325 ms/op
                 createUser·p0.95:   5.874 ms/op
                 createUser·p0.99:   7.823 ms/op
                 createUser·p0.999:  12.485 ms/op
                 createUser·p0.9999: 24.193 ms/op
                 createUser·p1.00:   25.297 ms/op

Iteration   2: 4.380 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.085 ms/op
                 createUser·p0.50:   4.202 ms/op
                 createUser·p0.90:   5.513 ms/op
                 createUser·p0.95:   6.046 ms/op
                 createUser·p0.99:   8.274 ms/op
                 createUser·p0.999:  13.467 ms/op
                 createUser·p0.9999: 25.660 ms/op
                 createUser·p1.00:   26.313 ms/op

Iteration   3: 4.249 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.198 ms/op
                 createUser·p0.50:   4.116 ms/op
                 createUser·p0.90:   5.333 ms/op
                 createUser·p0.95:   5.833 ms/op
                 createUser·p0.99:   7.668 ms/op
                 createUser·p0.999:  11.495 ms/op
                 createUser·p0.9999: 29.174 ms/op
                 createUser·p1.00:   30.147 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 225367
  mean =      4.259 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7753 
    [ 2.500,  5.000) = 180073 
    [ 5.000,  7.500) = 34549 
    [ 7.500, 10.000) = 2286 
    [10.000, 12.500) = 491 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.847 ms/op
     p(50.0000) =      4.129 ms/op
     p(90.0000) =      5.399 ms/op
     p(95.0000) =      5.923 ms/op
     p(99.0000) =      7.965 ms/op
     p(99.9000) =     12.380 ms/op
     p(99.9900) =     27.722 ms/op
     p(99.9990) =     29.908 ms/op
     p(99.9999) =     30.147 ms/op
    p(100.0000) =     30.147 ms/op


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
# Warmup Iteration   1: 6.003 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.746 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.353 ±(99.9%) 0.015 ms/op
Iteration   1: 4.185 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.949 ms/op
                 existUser·p0.50:   4.055 ms/op
                 existUser·p0.90:   5.210 ms/op
                 existUser·p0.95:   5.685 ms/op
                 existUser·p0.99:   7.840 ms/op
                 existUser·p0.999:  12.845 ms/op
                 existUser·p0.9999: 15.627 ms/op
                 existUser·p1.00:   17.859 ms/op

Iteration   2: 4.018 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.994 ms/op
                 existUser·p0.50:   3.871 ms/op
                 existUser·p0.90:   5.054 ms/op
                 existUser·p0.95:   5.571 ms/op
                 existUser·p0.99:   7.553 ms/op
                 existUser·p0.999:  12.207 ms/op
                 existUser·p0.9999: 26.347 ms/op
                 existUser·p1.00:   28.148 ms/op

Iteration   3: 3.992 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.981 ms/op
                 existUser·p0.50:   3.842 ms/op
                 existUser·p0.90:   4.948 ms/op
                 existUser·p0.95:   5.448 ms/op
                 existUser·p0.99:   7.414 ms/op
                 existUser·p0.999:  10.893 ms/op
                 existUser·p0.9999: 17.596 ms/op
                 existUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 236118
  mean =      4.063 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6112 
    [ 2.500,  5.000) = 203376 
    [ 5.000,  7.500) = 24075 
    [ 7.500, 10.000) = 1949 
    [10.000, 12.500) = 404 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.949 ms/op
     p(50.0000) =      3.920 ms/op
     p(90.0000) =      5.079 ms/op
     p(95.0000) =      5.571 ms/op
     p(99.0000) =      7.610 ms/op
     p(99.9000) =     12.188 ms/op
     p(99.9900) =     25.625 ms/op
     p(99.9990) =     27.588 ms/op
     p(99.9999) =     28.148 ms/op
    p(100.0000) =     28.148 ms/op


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
# Warmup Iteration   1: 6.371 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.614 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.426 ±(99.9%) 0.014 ms/op
Iteration   1: 4.317 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.018 ms/op
                 getUser·p0.50:   4.182 ms/op
                 getUser·p0.90:   5.423 ms/op
                 getUser·p0.95:   5.931 ms/op
                 getUser·p0.99:   8.077 ms/op
                 getUser·p0.999:  13.460 ms/op
                 getUser·p0.9999: 29.273 ms/op
                 getUser·p1.00:   30.605 ms/op

Iteration   2: 4.409 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.856 ms/op
                 getUser·p0.50:   4.334 ms/op
                 getUser·p0.90:   5.579 ms/op
                 getUser·p0.95:   6.087 ms/op
                 getUser·p0.99:   8.431 ms/op
                 getUser·p0.999:  12.255 ms/op
                 getUser·p0.9999: 30.278 ms/op
                 getUser·p1.00:   30.310 ms/op

Iteration   3: 4.416 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.016 ms/op
                 getUser·p0.50:   4.276 ms/op
                 getUser·p0.90:   5.530 ms/op
                 getUser·p0.95:   6.005 ms/op
                 getUser·p0.99:   7.545 ms/op
                 getUser·p0.999:  12.210 ms/op
                 getUser·p0.9999: 33.851 ms/op
                 getUser·p1.00:   34.865 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 219095
  mean =      4.380 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6962 
    [ 2.500,  5.000) = 167362 
    [ 5.000,  7.500) = 41835 
    [ 7.500, 10.000) = 2268 
    [10.000, 12.500) = 445 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.856 ms/op
     p(50.0000) =      4.260 ms/op
     p(90.0000) =      5.513 ms/op
     p(95.0000) =      6.005 ms/op
     p(99.0000) =      8.020 ms/op
     p(99.9000) =     12.565 ms/op
     p(99.9900) =     32.869 ms/op
     p(99.9990) =     34.406 ms/op
     p(99.9999) =     34.865 ms/op
    p(100.0000) =     34.865 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 7.867 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 6.223 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.772 ±(99.9%) 0.022 ms/op
Iteration   1: 5.759 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.561 ms/op
                 listUser·p0.50:   5.407 ms/op
                 listUser·p0.90:   7.553 ms/op
                 listUser·p0.95:   8.684 ms/op
                 listUser·p0.99:   11.305 ms/op
                 listUser·p0.999:  19.478 ms/op
                 listUser·p0.9999: 27.491 ms/op
                 listUser·p1.00:   28.344 ms/op

Iteration   2: 5.637 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.686 ms/op
                 listUser·p0.50:   5.317 ms/op
                 listUser·p0.90:   7.381 ms/op
                 listUser·p0.95:   8.438 ms/op
                 listUser·p0.99:   11.321 ms/op
                 listUser·p0.999:  24.590 ms/op
                 listUser·p0.9999: 33.378 ms/op
                 listUser·p1.00:   33.882 ms/op

Iteration   3: 5.562 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.311 ms/op
                 listUser·p0.50:   5.292 ms/op
                 listUser·p0.90:   6.914 ms/op
                 listUser·p0.95:   8.086 ms/op
                 listUser·p0.99:   11.158 ms/op
                 listUser·p0.999:  25.373 ms/op
                 listUser·p0.9999: 30.128 ms/op
                 listUser·p1.00:   32.145 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 169927
  mean =      5.652 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 117 
    [ 2.500,  5.000) = 56649 
    [ 5.000,  7.500) = 98145 
    [ 7.500, 10.000) = 11554 
    [10.000, 12.500) = 2540 
    [12.500, 15.000) = 453 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.311 ms/op
     p(50.0000) =      5.333 ms/op
     p(90.0000) =      7.299 ms/op
     p(95.0000) =      8.405 ms/op
     p(99.0000) =     11.272 ms/op
     p(99.9000) =     21.561 ms/op
     p(99.9900) =     32.604 ms/op
     p(99.9990) =     33.790 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.642 ± 3.553  ops/ms
ClientGrpc.existUser                       thrpt       3   8.143 ± 3.613  ops/ms
ClientGrpc.getUser                         thrpt       3   7.411 ± 1.490  ops/ms
ClientGrpc.listUser                        thrpt       3   5.784 ± 0.853  ops/ms
ClientGrpc.createUser                       avgt       3   4.368 ± 1.933   ms/op
ClientGrpc.existUser                        avgt       3   4.099 ± 2.750   ms/op
ClientGrpc.getUser                          avgt       3   4.462 ± 2.166   ms/op
ClientGrpc.listUser                         avgt       3   5.639 ± 1.357   ms/op
ClientGrpc.createUser                     sample  225367   4.259 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.847           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.129           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.399           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.923           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.965           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.380           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.722           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.147           ms/op
ClientGrpc.existUser                      sample  236118   4.063 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.949           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.079           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.571           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.610           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.188           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.625           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.148           ms/op
ClientGrpc.getUser                        sample  219095   4.380 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.856           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.260           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.513           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.005           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.020           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.565           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          32.869           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          34.865           ms/op
ClientGrpc.listUser                       sample  169927   5.652 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.311           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.333           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.299           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.405           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.272           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          21.561           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.604           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.882           ms/op
