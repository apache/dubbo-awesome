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
# Warmup Iteration   1: 4.616 ops/ms
# Warmup Iteration   2: 9.352 ops/ms
# Warmup Iteration   3: 10.175 ops/ms
Iteration   1: 10.456 ops/ms
Iteration   2: 10.289 ops/ms
Iteration   3: 10.181 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.308 ±(99.9%) 2.529 ops/ms [Average]
  (min, avg, max) = (10.181, 10.308, 10.456), stdev = 0.139
  CI (99.9%): [7.779, 12.837] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.825 ops/ms
# Warmup Iteration   2: 10.682 ops/ms
# Warmup Iteration   3: 10.516 ops/ms
Iteration   1: 10.758 ops/ms
Iteration   2: 10.685 ops/ms
Iteration   3: 10.697 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.713 ±(99.9%) 0.718 ops/ms [Average]
  (min, avg, max) = (10.685, 10.713, 10.758), stdev = 0.039
  CI (99.9%): [9.995, 11.431] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:50
# Fork: 1 of 1
# Warmup Iteration   1: 7.867 ops/ms
# Warmup Iteration   2: 9.997 ops/ms
# Warmup Iteration   3: 10.126 ops/ms
Iteration   1: 10.399 ops/ms
Iteration   2: 10.068 ops/ms
Iteration   3: 10.167 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.211 ±(99.9%) 3.092 ops/ms [Average]
  (min, avg, max) = (10.068, 10.211, 10.399), stdev = 0.169
  CI (99.9%): [7.120, 13.303] (assumes normal distribution)


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
# Warmup Iteration   1: 5.862 ops/ms
# Warmup Iteration   2: 7.985 ops/ms
# Warmup Iteration   3: 8.262 ops/ms
Iteration   1: 8.211 ops/ms
Iteration   2: 8.088 ops/ms
Iteration   3: 8.504 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.268 ±(99.9%) 3.903 ops/ms [Average]
  (min, avg, max) = (8.088, 8.268, 8.504), stdev = 0.214
  CI (99.9%): [4.364, 12.171] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.010 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.144 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.983 ±(99.9%) 0.004 ms/op
Iteration   1: 3.096 ±(99.9%) 0.002 ms/op
Iteration   2: 3.097 ±(99.9%) 0.003 ms/op
Iteration   3: 3.015 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.069 ±(99.9%) 0.862 ms/op [Average]
  (min, avg, max) = (3.015, 3.069, 3.097), stdev = 0.047
  CI (99.9%): [2.207, 3.932] (assumes normal distribution)


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
# Warmup Iteration   1: 3.775 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.018 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.003 ms/op
Iteration   1: 3.047 ±(99.9%) 0.001 ms/op
Iteration   2: 2.989 ±(99.9%) 0.002 ms/op
Iteration   3: 2.991 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.009 ±(99.9%) 0.598 ms/op [Average]
  (min, avg, max) = (2.989, 3.009, 3.047), stdev = 0.033
  CI (99.9%): [2.411, 3.607] (assumes normal distribution)


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
# Warmup Iteration   1: 3.835 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.211 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.064 ±(99.9%) 0.003 ms/op
Iteration   1: 3.075 ±(99.9%) 0.002 ms/op
Iteration   2: 3.046 ±(99.9%) 0.002 ms/op
Iteration   3: 3.137 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.086 ±(99.9%) 0.842 ms/op [Average]
  (min, avg, max) = (3.046, 3.086, 3.137), stdev = 0.046
  CI (99.9%): [2.244, 3.928] (assumes normal distribution)


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
# Warmup Iteration   1: 4.905 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.055 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.027 ±(99.9%) 0.021 ms/op
Iteration   1: 3.987 ±(99.9%) 0.014 ms/op
Iteration   2: 3.941 ±(99.9%) 0.019 ms/op
Iteration   3: 3.878 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.935 ±(99.9%) 0.996 ms/op [Average]
  (min, avg, max) = (3.878, 3.935, 3.987), stdev = 0.055
  CI (99.9%): [2.940, 4.931] (assumes normal distribution)


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
# Warmup Iteration   1: 4.113 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.173 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.118 ±(99.9%) 0.007 ms/op
Iteration   1: 3.155 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.664 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  8.328 ms/op
                 createUser·p0.9999: 14.163 ms/op
                 createUser·p1.00:   14.713 ms/op

Iteration   2: 3.167 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.591 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.895 ms/op
                 createUser·p0.95:   4.051 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  7.742 ms/op
                 createUser·p0.9999: 18.642 ms/op
                 createUser·p1.00:   19.464 ms/op

Iteration   3: 3.015 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.243 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.396 ms/op
                 createUser·p0.95:   3.604 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  14.418 ms/op
                 createUser·p0.9999: 18.860 ms/op
                 createUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308417
  mean =      3.111 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1250 
    [ 1.250,  2.500) = 20655 
    [ 2.500,  3.750) = 255561 
    [ 3.750,  5.000) = 29232 
    [ 5.000,  6.250) = 934 
    [ 6.250,  7.500) = 354 
    [ 7.500,  8.750) = 151 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 63 
    [15.000, 16.250) = 34 
    [16.250, 17.500) = 47 
    [17.500, 18.750) = 47 

  Percentiles, ms/op:
      p(0.0000) =      0.243 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      3.981 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      8.398 ms/op
     p(99.9900) =     18.552 ms/op
     p(99.9990) =     19.461 ms/op
     p(99.9999) =     19.726 ms/op
    p(100.0000) =     19.726 ms/op


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
# Warmup Iteration   1: 3.808 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.049 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.007 ms/op
Iteration   1: 2.961 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.588 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  6.861 ms/op
                 existUser·p0.9999: 11.278 ms/op
                 existUser·p1.00:   11.764 ms/op

Iteration   2: 3.001 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.720 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  7.266 ms/op
                 existUser·p0.9999: 15.428 ms/op
                 existUser·p1.00:   15.598 ms/op

Iteration   3: 2.902 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.689 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.629 ms/op
                 existUser·p0.95:   3.936 ms/op
                 existUser·p0.99:   4.661 ms/op
                 existUser·p0.999:  7.797 ms/op
                 existUser·p0.9999: 22.608 ms/op
                 existUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325071
  mean =      2.954 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50706 
    [ 2.500,  5.000) = 273007 
    [ 5.000,  7.500) = 1070 
    [ 7.500, 10.000) = 127 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.588 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      7.364 ms/op
     p(99.9900) =     18.181 ms/op
     p(99.9990) =     22.921 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


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
# Warmup Iteration   1: 4.077 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.129 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.005 ms/op
Iteration   1: 3.009 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.745 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.253 ms/op
                 getUser·p0.999:  5.961 ms/op
                 getUser·p0.9999: 11.835 ms/op
                 getUser·p1.00:   12.042 ms/op

Iteration   2: 3.093 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.708 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  7.216 ms/op
                 getUser·p0.9999: 13.943 ms/op
                 getUser·p1.00:   17.433 ms/op

Iteration   3: 3.023 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.225 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  7.563 ms/op
                 getUser·p0.9999: 19.445 ms/op
                 getUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315580
  mean =      3.041 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27092 
    [ 2.500,  5.000) = 287334 
    [ 5.000,  7.500) = 886 
    [ 7.500, 10.000) = 76 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.225 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      7.119 ms/op
     p(99.9900) =     17.462 ms/op
     p(99.9990) =     19.716 ms/op
     p(99.9999) =     20.316 ms/op
    p(100.0000) =     20.316 ms/op


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
# Warmup Iteration   1: 5.061 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.034 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.957 ±(99.9%) 0.011 ms/op
Iteration   1: 3.957 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.317 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  12.700 ms/op
                 listUser·p0.9999: 17.531 ms/op
                 listUser·p1.00:   18.121 ms/op

Iteration   2: 3.820 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.937 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   5.186 ms/op
                 listUser·p0.99:   6.537 ms/op
                 listUser·p0.999:  20.816 ms/op
                 listUser·p0.9999: 23.192 ms/op
                 listUser·p1.00:   23.822 ms/op

Iteration   3: 3.899 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.778 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   5.439 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  22.253 ms/op
                 listUser·p0.9999: 26.012 ms/op
                 listUser·p1.00:   27.165 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246454
  mean =      3.891 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3301 
    [ 2.500,  5.000) = 224615 
    [ 5.000,  7.500) = 17575 
    [ 7.500, 10.000) = 533 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 111 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      0.778 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.719 ms/op
     p(95.0000) =      5.399 ms/op
     p(99.0000) =      6.611 ms/op
     p(99.9000) =     17.924 ms/op
     p(99.9900) =     25.505 ms/op
     p(99.9990) =     26.461 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.308 ± 2.529  ops/ms
ClientGrpc.existUser                       thrpt       3  10.713 ± 0.718  ops/ms
ClientGrpc.getUser                         thrpt       3  10.211 ± 3.092  ops/ms
ClientGrpc.listUser                        thrpt       3   8.268 ± 3.903  ops/ms
ClientGrpc.createUser                       avgt       3   3.069 ± 0.862   ms/op
ClientGrpc.existUser                        avgt       3   3.009 ± 0.598   ms/op
ClientGrpc.getUser                          avgt       3   3.086 ± 0.842   ms/op
ClientGrpc.listUser                         avgt       3   3.935 ± 0.996   ms/op
ClientGrpc.createUser                     sample  308417   3.111 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.243           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.072           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.752           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.981           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.473           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.398           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.552           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.726           ms/op
ClientGrpc.existUser                      sample  325071   2.954 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.588           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.949           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.621           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.846           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.432           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.364           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.181           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.101           ms/op
ClientGrpc.getUser                        sample  315580   3.041 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.225           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.043           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.600           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.785           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.309           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.119           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.462           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.316           ms/op
ClientGrpc.listUser                       sample  246454   3.891 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.778           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.760           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.719           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.399           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.611           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.924           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.505           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.165           ms/op
