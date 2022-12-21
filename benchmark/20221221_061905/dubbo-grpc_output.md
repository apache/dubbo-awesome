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
# Warmup Iteration   1: 4.053 ops/ms
# Warmup Iteration   2: 9.056 ops/ms
# Warmup Iteration   3: 10.116 ops/ms
Iteration   1: 10.526 ops/ms
Iteration   2: 10.300 ops/ms
Iteration   3: 10.255 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.361 ±(99.9%) 2.651 ops/ms [Average]
  (min, avg, max) = (10.255, 10.361, 10.526), stdev = 0.145
  CI (99.9%): [7.710, 13.012] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 8.377 ops/ms
# Warmup Iteration   2: 10.179 ops/ms
# Warmup Iteration   3: 10.640 ops/ms
Iteration   1: 10.678 ops/ms
Iteration   2: 11.237 ops/ms
Iteration   3: 10.697 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.871 ±(99.9%) 5.792 ops/ms [Average]
  (min, avg, max) = (10.678, 10.871, 11.237), stdev = 0.317
  CI (99.9%): [5.079, 16.663] (assumes normal distribution)


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
# Warmup Iteration   1: 6.761 ops/ms
# Warmup Iteration   2: 10.043 ops/ms
# Warmup Iteration   3: 10.180 ops/ms
Iteration   1: 10.157 ops/ms
Iteration   2: 10.151 ops/ms
Iteration   3: 10.209 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.173 ±(99.9%) 0.584 ops/ms [Average]
  (min, avg, max) = (10.151, 10.173, 10.209), stdev = 0.032
  CI (99.9%): [9.589, 10.756] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.211 ops/ms
# Warmup Iteration   2: 7.585 ops/ms
# Warmup Iteration   3: 8.009 ops/ms
Iteration   1: 7.836 ops/ms
Iteration   2: 7.843 ops/ms
Iteration   3: 8.110 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.929 ±(99.9%) 2.849 ops/ms [Average]
  (min, avg, max) = (7.836, 7.929, 8.110), stdev = 0.156
  CI (99.9%): [5.080, 10.778] (assumes normal distribution)


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
# Warmup Iteration   1: 4.068 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.145 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.107 ±(99.9%) 0.007 ms/op
Iteration   1: 3.136 ±(99.9%) 0.003 ms/op
Iteration   2: 3.112 ±(99.9%) 0.003 ms/op
Iteration   3: 3.168 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.139 ±(99.9%) 0.508 ms/op [Average]
  (min, avg, max) = (3.112, 3.139, 3.168), stdev = 0.028
  CI (99.9%): [2.630, 3.647] (assumes normal distribution)


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
# Warmup Iteration   1: 3.973 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.105 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.003 ms/op
Iteration   1: 3.009 ±(99.9%) 0.003 ms/op
Iteration   2: 2.924 ±(99.9%) 0.002 ms/op
Iteration   3: 2.977 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.970 ±(99.9%) 0.778 ms/op [Average]
  (min, avg, max) = (2.924, 2.970, 3.009), stdev = 0.043
  CI (99.9%): [2.192, 3.748] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.065 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.214 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.064 ±(99.9%) 0.001 ms/op
Iteration   1: 3.122 ±(99.9%) 0.002 ms/op
Iteration   2: 3.135 ±(99.9%) 0.003 ms/op
Iteration   3: 3.109 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.122 ±(99.9%) 0.239 ms/op [Average]
  (min, avg, max) = (3.109, 3.122, 3.135), stdev = 0.013
  CI (99.9%): [2.883, 3.361] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.111 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.157 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.990 ±(99.9%) 0.013 ms/op
Iteration   1: 4.069 ±(99.9%) 0.018 ms/op
Iteration   2: 3.966 ±(99.9%) 0.017 ms/op
Iteration   3: 3.979 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.005 ±(99.9%) 1.025 ms/op [Average]
  (min, avg, max) = (3.966, 4.005, 4.069), stdev = 0.056
  CI (99.9%): [2.980, 5.030] (assumes normal distribution)


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
# Warmup Iteration   1: 4.200 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.105 ±(99.9%) 0.007 ms/op
Iteration   1: 3.173 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.016 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.883 ms/op
                 createUser·p0.95:   4.047 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  6.098 ms/op
                 createUser·p0.9999: 12.708 ms/op
                 createUser·p1.00:   13.091 ms/op

Iteration   2: 3.022 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.767 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  7.029 ms/op
                 createUser·p0.9999: 13.540 ms/op
                 createUser·p1.00:   13.779 ms/op

Iteration   3: 3.010 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.450 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  7.102 ms/op
                 createUser·p0.9999: 15.934 ms/op
                 createUser·p1.00:   16.712 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313011
  mean =      3.067 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 578 
    [ 1.250,  2.500) = 29530 
    [ 2.500,  3.750) = 258799 
    [ 3.750,  5.000) = 23040 
    [ 5.000,  6.250) = 659 
    [ 6.250,  7.500) = 177 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 42 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.450 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      6.799 ms/op
     p(99.9900) =     15.417 ms/op
     p(99.9990) =     16.596 ms/op
     p(99.9999) =     16.712 ms/op
    p(100.0000) =     16.712 ms/op


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
# Warmup Iteration   1: 3.776 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.105 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.006 ms/op
Iteration   1: 2.964 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.730 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   3.871 ms/op
                 existUser·p0.99:   4.149 ms/op
                 existUser·p0.999:  6.438 ms/op
                 existUser·p0.9999: 12.550 ms/op
                 existUser·p1.00:   12.911 ms/op

Iteration   2: 2.957 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.628 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.711 ms/op
                 existUser·p0.95:   3.895 ms/op
                 existUser·p0.99:   4.174 ms/op
                 existUser·p0.999:  7.143 ms/op
                 existUser·p0.9999: 18.585 ms/op
                 existUser·p1.00:   19.759 ms/op

Iteration   3: 3.037 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.820 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.711 ms/op
                 existUser·p0.95:   3.875 ms/op
                 existUser·p0.99:   4.182 ms/op
                 existUser·p0.999:  8.247 ms/op
                 existUser·p0.9999: 17.315 ms/op
                 existUser·p1.00:   17.793 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321539
  mean =      2.986 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2570 
    [ 1.250,  2.500) = 51188 
    [ 2.500,  3.750) = 239965 
    [ 3.750,  5.000) = 26943 
    [ 5.000,  6.250) = 369 
    [ 6.250,  7.500) = 244 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 37 
    [16.250, 17.500) = 42 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      4.166 ms/op
     p(99.9000) =      6.947 ms/op
     p(99.9900) =     17.727 ms/op
     p(99.9990) =     19.588 ms/op
     p(99.9999) =     19.759 ms/op
    p(100.0000) =     19.759 ms/op


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
# Warmup Iteration   1: 4.374 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.231 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.156 ±(99.9%) 0.006 ms/op
Iteration   1: 3.119 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.593 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   4.014 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  8.558 ms/op
                 getUser·p0.9999: 12.108 ms/op
                 getUser·p1.00:   12.272 ms/op

Iteration   2: 3.106 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.867 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  7.089 ms/op
                 getUser·p0.9999: 15.125 ms/op
                 getUser·p1.00:   15.532 ms/op

Iteration   3: 3.087 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.978 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  7.217 ms/op
                 getUser·p0.9999: 15.985 ms/op
                 getUser·p1.00:   16.433 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309183
  mean =      3.104 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 424 
    [ 1.250,  2.500) = 23631 
    [ 2.500,  3.750) = 257484 
    [ 3.750,  5.000) = 26442 
    [ 5.000,  6.250) = 539 
    [ 6.250,  7.500) = 337 
    [ 7.500,  8.750) = 71 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 104 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.593 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      7.625 ms/op
     p(99.9900) =     14.976 ms/op
     p(99.9990) =     16.262 ms/op
     p(99.9999) =     16.433 ms/op
    p(100.0000) =     16.433 ms/op


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
# Warmup Iteration   1: 5.217 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.090 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.013 ±(99.9%) 0.010 ms/op
Iteration   1: 3.942 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.008 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  14.746 ms/op
                 listUser·p0.9999: 20.894 ms/op
                 listUser·p1.00:   21.332 ms/op

Iteration   2: 3.889 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.997 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   6.781 ms/op
                 listUser·p0.999:  15.528 ms/op
                 listUser·p0.9999: 27.551 ms/op
                 listUser·p1.00:   28.115 ms/op

Iteration   3: 3.922 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.866 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  14.909 ms/op
                 listUser·p0.9999: 19.623 ms/op
                 listUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244958
  mean =      3.918 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3423 
    [ 2.500,  5.000) = 218665 
    [ 5.000,  7.500) = 21789 
    [ 7.500, 10.000) = 636 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 135 
    [15.000, 17.500) = 159 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.866 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.940 ms/op
     p(95.0000) =      5.571 ms/op
     p(99.0000) =      6.750 ms/op
     p(99.9000) =     15.106 ms/op
     p(99.9900) =     26.166 ms/op
     p(99.9990) =     27.987 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.361 ± 2.651  ops/ms
ClientGrpc.existUser                       thrpt       3  10.871 ± 5.792  ops/ms
ClientGrpc.getUser                         thrpt       3  10.173 ± 0.584  ops/ms
ClientGrpc.listUser                        thrpt       3   7.929 ± 2.849  ops/ms
ClientGrpc.createUser                       avgt       3   3.139 ± 0.508   ms/op
ClientGrpc.existUser                        avgt       3   2.970 ± 0.778   ms/op
ClientGrpc.getUser                          avgt       3   3.122 ± 0.239   ms/op
ClientGrpc.listUser                         avgt       3   4.005 ± 1.025   ms/op
ClientGrpc.createUser                     sample  313011   3.067 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.450           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.039           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.662           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.887           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           6.799           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.417           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.712           ms/op
ClientGrpc.existUser                      sample  321539   2.986 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.628           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.998           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.711           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.879           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.166           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.947           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.727           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.759           ms/op
ClientGrpc.getUser                        sample  309183   3.104 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.593           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.072           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.707           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.953           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.399           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.625           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.976           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.433           ms/op
ClientGrpc.listUser                       sample  244958   3.918 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.866           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.764           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.940           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.571           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.750           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.106           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.166           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.115           ms/op
