# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.112 ops/ms
# Warmup Iteration   2: 8.950 ops/ms
# Warmup Iteration   3: 10.030 ops/ms
Iteration   1: 10.196 ops/ms
Iteration   2: 10.075 ops/ms
Iteration   3: 10.009 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.093 ±(99.9%) 1.728 ops/ms [Average]
  (min, avg, max) = (10.009, 10.093, 10.196), stdev = 0.095
  CI (99.9%): [8.365, 11.822] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.019 ops/ms
# Warmup Iteration   2: 9.988 ops/ms
# Warmup Iteration   3: 10.463 ops/ms
Iteration   1: 10.556 ops/ms
Iteration   2: 10.320 ops/ms
Iteration   3: 10.641 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.506 ±(99.9%) 3.040 ops/ms [Average]
  (min, avg, max) = (10.320, 10.506, 10.641), stdev = 0.167
  CI (99.9%): [7.465, 13.546] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.911 ops/ms
# Warmup Iteration   2: 9.857 ops/ms
# Warmup Iteration   3: 9.918 ops/ms
Iteration   1: 10.030 ops/ms
Iteration   2: 9.917 ops/ms
Iteration   3: 10.013 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.987 ±(99.9%) 1.118 ops/ms [Average]
  (min, avg, max) = (9.917, 9.987, 10.030), stdev = 0.061
  CI (99.9%): [8.868, 11.105] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.173 ops/ms
# Warmup Iteration   2: 7.432 ops/ms
# Warmup Iteration   3: 7.918 ops/ms
Iteration   1: 7.766 ops/ms
Iteration   2: 7.888 ops/ms
Iteration   3: 7.911 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.855 ±(99.9%) 1.421 ops/ms [Average]
  (min, avg, max) = (7.766, 7.855, 7.911), stdev = 0.078
  CI (99.9%): [6.434, 9.276] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.417 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.255 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.203 ±(99.9%) 0.002 ms/op
Iteration   1: 3.156 ±(99.9%) 0.008 ms/op
Iteration   2: 3.092 ±(99.9%) 0.003 ms/op
Iteration   3: 3.232 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.160 ±(99.9%) 1.278 ms/op [Average]
  (min, avg, max) = (3.092, 3.160, 3.232), stdev = 0.070
  CI (99.9%): [1.882, 4.438] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.243 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.181 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.104 ±(99.9%) 0.002 ms/op
Iteration   1: 3.080 ±(99.9%) 0.001 ms/op
Iteration   2: 3.075 ±(99.9%) 0.002 ms/op
Iteration   3: 3.043 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.066 ±(99.9%) 0.365 ms/op [Average]
  (min, avg, max) = (3.043, 3.066, 3.080), stdev = 0.020
  CI (99.9%): [2.701, 3.431] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.447 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.294 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.275 ±(99.9%) 0.002 ms/op
Iteration   1: 3.145 ±(99.9%) 0.002 ms/op
Iteration   2: 3.153 ±(99.9%) 0.002 ms/op
Iteration   3: 3.176 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.158 ±(99.9%) 0.294 ms/op [Average]
  (min, avg, max) = (3.145, 3.158, 3.176), stdev = 0.016
  CI (99.9%): [2.864, 3.452] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.613 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.256 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.214 ±(99.9%) 0.012 ms/op
Iteration   1: 4.029 ±(99.9%) 0.011 ms/op
Iteration   2: 4.062 ±(99.9%) 0.022 ms/op
Iteration   3: 4.113 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.068 ±(99.9%) 0.775 ms/op [Average]
  (min, avg, max) = (4.029, 4.068, 4.113), stdev = 0.042
  CI (99.9%): [3.293, 4.843] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.505 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.351 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.326 ±(99.9%) 0.007 ms/op
Iteration   1: 3.300 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.027 ms/op
                 createUser·p0.50:   3.273 ms/op
                 createUser·p0.90:   4.022 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   4.620 ms/op
                 createUser·p0.999:  8.062 ms/op
                 createUser·p0.9999: 13.800 ms/op
                 createUser·p1.00:   14.025 ms/op

Iteration   2: 3.289 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.930 ms/op
                 createUser·p0.50:   3.273 ms/op
                 createUser·p0.90:   4.022 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   4.585 ms/op
                 createUser·p0.999:  6.894 ms/op
                 createUser·p0.9999: 15.562 ms/op
                 createUser·p1.00:   16.105 ms/op

Iteration   3: 3.246 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.955 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.104 ms/op
                 createUser·p0.99:   4.653 ms/op
                 createUser·p0.999:  8.596 ms/op
                 createUser·p0.9999: 18.814 ms/op
                 createUser·p1.00:   19.202 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 292646
  mean =      3.278 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 232 
    [ 1.250,  2.500) = 15678 
    [ 2.500,  3.750) = 220534 
    [ 3.750,  5.000) = 54842 
    [ 5.000,  6.250) = 667 
    [ 6.250,  7.500) = 335 
    [ 7.500,  8.750) = 130 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 57 
    [15.000, 16.250) = 38 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.930 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.182 ms/op
     p(99.0000) =      4.612 ms/op
     p(99.9000) =      7.873 ms/op
     p(99.9900) =     18.050 ms/op
     p(99.9990) =     19.045 ms/op
     p(99.9999) =     19.202 ms/op
    p(100.0000) =     19.202 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.046 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.165 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.069 ±(99.9%) 0.006 ms/op
Iteration   1: 3.114 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.830 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.797 ms/op
                 existUser·p0.95:   3.969 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  7.866 ms/op
                 existUser·p0.9999: 12.873 ms/op
                 existUser·p1.00:   13.206 ms/op

Iteration   2: 2.999 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.746 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.629 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   4.186 ms/op
                 existUser·p0.999:  8.703 ms/op
                 existUser·p0.9999: 22.358 ms/op
                 existUser·p1.00:   22.807 ms/op

Iteration   3: 3.025 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.840 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   4.153 ms/op
                 existUser·p0.999:  6.856 ms/op
                 existUser·p0.9999: 16.590 ms/op
                 existUser·p1.00:   16.908 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 315175
  mean =      3.045 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35866 
    [ 2.500,  5.000) = 278228 
    [ 5.000,  7.500) = 749 
    [ 7.500, 10.000) = 185 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.746 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      7.668 ms/op
     p(99.9900) =     20.758 ms/op
     p(99.9990) =     22.703 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.434 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.290 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.203 ±(99.9%) 0.007 ms/op
Iteration   1: 3.228 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.583 ms/op
                 getUser·p0.50:   3.211 ms/op
                 getUser·p0.90:   3.932 ms/op
                 getUser·p0.95:   4.116 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  7.338 ms/op
                 getUser·p0.9999: 12.012 ms/op
                 getUser·p1.00:   12.976 ms/op

Iteration   2: 3.198 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.870 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.908 ms/op
                 getUser·p0.95:   4.100 ms/op
                 getUser·p0.99:   4.563 ms/op
                 getUser·p0.999:  7.566 ms/op
                 getUser·p0.9999: 15.974 ms/op
                 getUser·p1.00:   16.400 ms/op

Iteration   3: 3.176 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.723 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  6.957 ms/op
                 getUser·p0.9999: 17.362 ms/op
                 getUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 299961
  mean =      3.201 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 427 
    [ 1.250,  2.500) = 19532 
    [ 2.500,  3.750) = 234560 
    [ 3.750,  5.000) = 44296 
    [ 5.000,  6.250) = 575 
    [ 6.250,  7.500) = 324 
    [ 7.500,  8.750) = 61 
    [ 8.750, 10.000) = 20 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 56 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.583 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      7.234 ms/op
     p(99.9900) =     16.532 ms/op
     p(99.9990) =     18.416 ms/op
     p(99.9999) =     18.547 ms/op
    p(100.0000) =     18.547 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.844 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.126 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.179 ±(99.9%) 0.013 ms/op
Iteration   1: 4.168 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.343 ms/op
                 listUser·p0.50:   3.983 ms/op
                 listUser·p0.90:   5.448 ms/op
                 listUser·p0.95:   6.128 ms/op
                 listUser·p0.99:   7.253 ms/op
                 listUser·p0.999:  13.818 ms/op
                 listUser·p0.9999: 17.400 ms/op
                 listUser·p1.00:   18.481 ms/op

Iteration   2: 4.094 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.102 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   5.317 ms/op
                 listUser·p0.95:   5.988 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  14.482 ms/op
                 listUser·p0.9999: 20.366 ms/op
                 listUser·p1.00:   21.135 ms/op

Iteration   3: 4.066 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.929 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  18.427 ms/op
                 listUser·p0.9999: 25.068 ms/op
                 listUser·p1.00:   26.706 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 233628
  mean =      4.109 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2151 
    [ 2.500,  5.000) = 202136 
    [ 5.000,  7.500) = 27754 
    [ 7.500, 10.000) = 1179 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 135 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.929 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      5.284 ms/op
     p(95.0000) =      6.021 ms/op
     p(99.0000) =      7.152 ms/op
     p(99.9000) =     14.610 ms/op
     p(99.9900) =     24.707 ms/op
     p(99.9990) =     26.531 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.093 ± 1.728  ops/ms
ClientGrpc.existUser                       thrpt       3  10.506 ± 3.040  ops/ms
ClientGrpc.getUser                         thrpt       3   9.987 ± 1.118  ops/ms
ClientGrpc.listUser                        thrpt       3   7.855 ± 1.421  ops/ms
ClientGrpc.createUser                       avgt       3   3.160 ± 1.278   ms/op
ClientGrpc.existUser                        avgt       3   3.066 ± 0.365   ms/op
ClientGrpc.getUser                          avgt       3   3.158 ± 0.294   ms/op
ClientGrpc.listUser                         avgt       3   4.068 ± 0.775   ms/op
ClientGrpc.createUser                     sample  292646   3.278 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.930           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.252           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.985           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.182           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.612           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.873           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.050           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.202           ms/op
ClientGrpc.existUser                      sample  315175   3.045 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.746           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.031           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.707           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.887           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.668           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.758           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.807           ms/op
ClientGrpc.getUser                        sample  299961   3.201 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.583           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.178           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.887           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.080           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.506           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.234           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.532           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.547           ms/op
ClientGrpc.listUser                       sample  233628   4.109 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.929           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.928           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.284           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.021           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.152           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.610           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.707           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.706           ms/op
