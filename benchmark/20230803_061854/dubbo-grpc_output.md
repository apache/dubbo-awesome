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
# Warmup Iteration   1: 4.235 ops/ms
# Warmup Iteration   2: 9.033 ops/ms
# Warmup Iteration   3: 10.284 ops/ms
Iteration   1: 10.427 ops/ms
Iteration   2: 10.194 ops/ms
Iteration   3: 10.767 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.463 ±(99.9%) 5.254 ops/ms [Average]
  (min, avg, max) = (10.194, 10.463, 10.767), stdev = 0.288
  CI (99.9%): [5.209, 15.716] (assumes normal distribution)


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
# Warmup Iteration   1: 7.420 ops/ms
# Warmup Iteration   2: 10.544 ops/ms
# Warmup Iteration   3: 10.862 ops/ms
Iteration   1: 11.068 ops/ms
Iteration   2: 11.008 ops/ms
Iteration   3: 11.049 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.042 ±(99.9%) 0.562 ops/ms [Average]
  (min, avg, max) = (11.008, 11.042, 11.068), stdev = 0.031
  CI (99.9%): [10.479, 11.604] (assumes normal distribution)


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
# Warmup Iteration   1: 7.299 ops/ms
# Warmup Iteration   2: 10.156 ops/ms
# Warmup Iteration   3: 10.432 ops/ms
Iteration   1: 10.644 ops/ms
Iteration   2: 10.596 ops/ms
Iteration   3: 10.598 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.613 ±(99.9%) 0.491 ops/ms [Average]
  (min, avg, max) = (10.596, 10.613, 10.644), stdev = 0.027
  CI (99.9%): [10.121, 11.104] (assumes normal distribution)


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
# Warmup Iteration   1: 5.629 ops/ms
# Warmup Iteration   2: 7.915 ops/ms
# Warmup Iteration   3: 8.003 ops/ms
Iteration   1: 7.966 ops/ms
Iteration   2: 8.139 ops/ms
Iteration   3: 8.113 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.073 ±(99.9%) 1.702 ops/ms [Average]
  (min, avg, max) = (7.966, 8.073, 8.139), stdev = 0.093
  CI (99.9%): [6.371, 9.775] (assumes normal distribution)


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
# Warmup Iteration   1: 4.270 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.189 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.107 ±(99.9%) 0.003 ms/op
Iteration   1: 3.041 ±(99.9%) 0.002 ms/op
Iteration   2: 3.051 ±(99.9%) 0.002 ms/op
Iteration   3: 3.011 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.034 ±(99.9%) 0.379 ms/op [Average]
  (min, avg, max) = (3.011, 3.034, 3.051), stdev = 0.021
  CI (99.9%): [2.655, 3.414] (assumes normal distribution)


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
# Warmup Iteration   1: 3.910 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.960 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.928 ±(99.9%) 0.003 ms/op
Iteration   1: 2.987 ±(99.9%) 0.003 ms/op
Iteration   2: 2.958 ±(99.9%) 0.002 ms/op
Iteration   3: 2.987 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.978 ±(99.9%) 0.305 ms/op [Average]
  (min, avg, max) = (2.958, 2.978, 2.987), stdev = 0.017
  CI (99.9%): [2.673, 3.282] (assumes normal distribution)


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
# Warmup Iteration   1: 4.239 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.141 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.005 ms/op
Iteration   1: 3.013 ±(99.9%) 0.004 ms/op
Iteration   2: 3.025 ±(99.9%) 0.005 ms/op
Iteration   3: 3.015 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.017 ±(99.9%) 0.116 ms/op [Average]
  (min, avg, max) = (3.013, 3.017, 3.025), stdev = 0.006
  CI (99.9%): [2.902, 3.133] (assumes normal distribution)


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
# Warmup Iteration   1: 5.412 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.023 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.983 ±(99.9%) 0.006 ms/op
Iteration   1: 3.888 ±(99.9%) 0.021 ms/op
Iteration   2: 3.949 ±(99.9%) 0.023 ms/op
Iteration   3: 3.938 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.925 ±(99.9%) 0.588 ms/op [Average]
  (min, avg, max) = (3.888, 3.925, 3.949), stdev = 0.032
  CI (99.9%): [3.337, 4.513] (assumes normal distribution)


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
# Warmup Iteration   1: 4.319 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.290 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.144 ±(99.9%) 0.006 ms/op
Iteration   1: 3.060 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.818 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   4.923 ms/op
                 createUser·p0.999:  10.124 ms/op
                 createUser·p0.9999: 13.684 ms/op
                 createUser·p1.00:   14.287 ms/op

Iteration   2: 3.022 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.603 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.478 ms/op
                 createUser·p0.95:   3.662 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  8.348 ms/op
                 createUser·p0.9999: 14.399 ms/op
                 createUser·p1.00:   14.828 ms/op

Iteration   3: 3.086 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.799 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   3.908 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  10.085 ms/op
                 createUser·p0.9999: 22.522 ms/op
                 createUser·p1.00:   23.396 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313889
  mean =      3.056 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22089 
    [ 2.500,  5.000) = 289713 
    [ 5.000,  7.500) = 1565 
    [ 7.500, 10.000) = 246 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 151 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.603 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      4.719 ms/op
     p(99.9000) =      8.913 ms/op
     p(99.9900) =     21.536 ms/op
     p(99.9990) =     23.219 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.008 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.086 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.959 ±(99.9%) 0.006 ms/op
Iteration   1: 2.837 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.608 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.502 ms/op
                 existUser·p0.99:   4.298 ms/op
                 existUser·p0.999:  7.832 ms/op
                 existUser·p0.9999: 13.152 ms/op
                 existUser·p1.00:   13.287 ms/op

Iteration   2: 2.916 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.797 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  6.909 ms/op
                 existUser·p0.9999: 26.543 ms/op
                 existUser·p1.00:   26.804 ms/op

Iteration   3: 2.954 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.735 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.628 ms/op
                 existUser·p0.999:  10.895 ms/op
                 existUser·p0.9999: 27.989 ms/op
                 existUser·p1.00:   28.410 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330851
  mean =      2.901 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35463 
    [ 2.500,  5.000) = 293637 
    [ 5.000,  7.500) = 1292 
    [ 7.500, 10.000) = 157 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      0.608 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.326 ms/op
     p(95.0000) =      3.547 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      9.508 ms/op
     p(99.9900) =     26.801 ms/op
     p(99.9990) =     28.291 ms/op
     p(99.9999) =     28.410 ms/op
    p(100.0000) =     28.410 ms/op


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
# Warmup Iteration   1: 4.194 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.264 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.129 ±(99.9%) 0.006 ms/op
Iteration   1: 3.098 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.833 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   4.710 ms/op
                 getUser·p0.999:  7.386 ms/op
                 getUser·p0.9999: 13.249 ms/op
                 getUser·p1.00:   13.468 ms/op

Iteration   2: 3.083 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.315 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  8.038 ms/op
                 getUser·p0.9999: 14.533 ms/op
                 getUser·p1.00:   14.778 ms/op

Iteration   3: 3.013 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.817 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   4.702 ms/op
                 getUser·p0.999:  8.239 ms/op
                 getUser·p0.9999: 17.674 ms/op
                 getUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313382
  mean =      3.064 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1290 
    [ 1.250,  2.500) = 22468 
    [ 2.500,  3.750) = 266399 
    [ 3.750,  5.000) = 21216 
    [ 5.000,  6.250) = 1083 
    [ 6.250,  7.500) = 535 
    [ 7.500,  8.750) = 177 
    [ 8.750, 10.000) = 17 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 68 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 33 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.315 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      4.653 ms/op
     p(99.9000) =      7.946 ms/op
     p(99.9900) =     16.941 ms/op
     p(99.9990) =     17.756 ms/op
     p(99.9999) =     17.924 ms/op
    p(100.0000) =     17.924 ms/op


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
# Warmup Iteration   1: 5.016 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.139 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.043 ±(99.9%) 0.011 ms/op
Iteration   1: 3.987 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.968 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  13.390 ms/op
                 listUser·p0.9999: 18.349 ms/op
                 listUser·p1.00:   19.137 ms/op

Iteration   2: 3.975 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.591 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.921 ms/op
                 listUser·p0.99:   7.143 ms/op
                 listUser·p0.999:  15.434 ms/op
                 listUser·p0.9999: 19.297 ms/op
                 listUser·p1.00:   19.661 ms/op

Iteration   3: 4.006 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.988 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.828 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  21.627 ms/op
                 listUser·p0.9999: 30.049 ms/op
                 listUser·p1.00:   30.573 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240864
  mean =      3.989 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3362 
    [ 2.500,  5.000) = 213919 
    [ 5.000,  7.500) = 21871 
    [ 7.500, 10.000) = 1139 
    [10.000, 12.500) = 166 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 139 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.968 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.973 ms/op
     p(95.0000) =      5.825 ms/op
     p(99.0000) =      7.094 ms/op
     p(99.9000) =     15.405 ms/op
     p(99.9900) =     28.961 ms/op
     p(99.9990) =     30.494 ms/op
     p(99.9999) =     30.573 ms/op
    p(100.0000) =     30.573 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.463 ± 5.254  ops/ms
ClientGrpc.existUser                       thrpt       3  11.042 ± 0.562  ops/ms
ClientGrpc.getUser                         thrpt       3  10.613 ± 0.491  ops/ms
ClientGrpc.listUser                        thrpt       3   8.073 ± 1.702  ops/ms
ClientGrpc.createUser                       avgt       3   3.034 ± 0.379   ms/op
ClientGrpc.existUser                        avgt       3   2.978 ± 0.305   ms/op
ClientGrpc.getUser                          avgt       3   3.017 ± 0.116   ms/op
ClientGrpc.listUser                         avgt       3   3.925 ± 0.588   ms/op
ClientGrpc.createUser                     sample  313889   3.056 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.603           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.011           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.576           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.838           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.719           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.913           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.536           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.396           ms/op
ClientGrpc.existUser                      sample  330851   2.901 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.608           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.896           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.326           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.547           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.407           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.508           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.801           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.410           ms/op
ClientGrpc.getUser                        sample  313382   3.064 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.315           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.637           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.891           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.653           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.946           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.941           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.924           ms/op
ClientGrpc.listUser                       sample  240864   3.989 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.968           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.822           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.973           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.825           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.094           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.405           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.961           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.573           ms/op
