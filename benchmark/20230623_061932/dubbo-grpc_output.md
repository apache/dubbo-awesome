# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.143 ops/ms
# Warmup Iteration   2: 8.906 ops/ms
# Warmup Iteration   3: 9.909 ops/ms
Iteration   1: 10.208 ops/ms
Iteration   2: 10.319 ops/ms
Iteration   3: 10.200 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.242 ±(99.9%) 1.217 ops/ms [Average]
  (min, avg, max) = (10.200, 10.242, 10.319), stdev = 0.067
  CI (99.9%): [9.025, 11.459] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.043 ops/ms
# Warmup Iteration   2: 10.366 ops/ms
# Warmup Iteration   3: 10.675 ops/ms
Iteration   1: 10.786 ops/ms
Iteration   2: 10.844 ops/ms
Iteration   3: 11.090 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.907 ±(99.9%) 2.945 ops/ms [Average]
  (min, avg, max) = (10.786, 10.907, 11.090), stdev = 0.161
  CI (99.9%): [7.962, 13.852] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.084 ops/ms
# Warmup Iteration   2: 10.224 ops/ms
# Warmup Iteration   3: 10.314 ops/ms
Iteration   1: 10.403 ops/ms
Iteration   2: 10.514 ops/ms
Iteration   3: 10.419 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.445 ±(99.9%) 1.090 ops/ms [Average]
  (min, avg, max) = (10.403, 10.445, 10.514), stdev = 0.060
  CI (99.9%): [9.355, 11.535] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.179 ops/ms
# Warmup Iteration   2: 7.411 ops/ms
# Warmup Iteration   3: 8.056 ops/ms
Iteration   1: 7.707 ops/ms
Iteration   2: 7.941 ops/ms
Iteration   3: 7.911 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.853 ±(99.9%) 2.323 ops/ms [Average]
  (min, avg, max) = (7.707, 7.853, 7.941), stdev = 0.127
  CI (99.9%): [5.531, 10.176] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.559 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.190 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.004 ms/op
Iteration   1: 3.051 ±(99.9%) 0.002 ms/op
Iteration   2: 3.072 ±(99.9%) 0.002 ms/op
Iteration   3: 3.115 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.079 ±(99.9%) 0.592 ms/op [Average]
  (min, avg, max) = (3.051, 3.079, 3.115), stdev = 0.032
  CI (99.9%): [2.487, 3.672] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.981 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.992 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.951 ±(99.9%) 0.002 ms/op
Iteration   1: 2.933 ±(99.9%) 0.003 ms/op
Iteration   2: 2.907 ±(99.9%) 0.002 ms/op
Iteration   3: 2.888 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.909 ±(99.9%) 0.419 ms/op [Average]
  (min, avg, max) = (2.888, 2.909, 2.933), stdev = 0.023
  CI (99.9%): [2.490, 3.328] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.272 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.168 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.003 ms/op
Iteration   1: 3.029 ±(99.9%) 0.004 ms/op
Iteration   2: 3.058 ±(99.9%) 0.003 ms/op
Iteration   3: 3.007 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.031 ±(99.9%) 0.473 ms/op [Average]
  (min, avg, max) = (3.007, 3.031, 3.058), stdev = 0.026
  CI (99.9%): [2.558, 3.504] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.365 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.178 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.028 ±(99.9%) 0.010 ms/op
Iteration   1: 3.959 ±(99.9%) 0.021 ms/op
Iteration   2: 3.993 ±(99.9%) 0.010 ms/op
Iteration   3: 3.935 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.962 ±(99.9%) 0.535 ms/op [Average]
  (min, avg, max) = (3.935, 3.962, 3.993), stdev = 0.029
  CI (99.9%): [3.427, 4.497] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.240 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.272 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.069 ±(99.9%) 0.007 ms/op
Iteration   1: 3.109 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.781 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  7.399 ms/op
                 createUser·p0.9999: 20.438 ms/op
                 createUser·p1.00:   20.808 ms/op

Iteration   2: 3.075 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.807 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   4.227 ms/op
                 createUser·p0.999:  6.806 ms/op
                 createUser·p0.9999: 21.646 ms/op
                 createUser·p1.00:   21.955 ms/op

Iteration   3: 3.052 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.741 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.778 ms/op
                 createUser·p0.999:  11.434 ms/op
                 createUser·p0.9999: 22.891 ms/op
                 createUser·p1.00:   23.757 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311788
  mean =      3.079 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18160 
    [ 2.500,  5.000) = 292137 
    [ 5.000,  7.500) = 1150 
    [ 7.500, 10.000) = 55 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.741 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      8.237 ms/op
     p(99.9900) =     21.752 ms/op
     p(99.9990) =     23.331 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.039 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.038 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.005 ms/op
Iteration   1: 2.891 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.594 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.232 ms/op
                 existUser·p0.95:   3.396 ms/op
                 existUser·p0.99:   3.973 ms/op
                 existUser·p0.999:  5.404 ms/op
                 existUser·p0.9999: 10.761 ms/op
                 existUser·p1.00:   12.861 ms/op

Iteration   2: 2.982 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.684 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  10.895 ms/op
                 existUser·p0.9999: 26.354 ms/op
                 existUser·p1.00:   27.034 ms/op

Iteration   3: 2.942 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.529 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  6.909 ms/op
                 existUser·p0.9999: 16.626 ms/op
                 existUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326829
  mean =      2.938 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31221 
    [ 2.500,  5.000) = 294491 
    [ 5.000,  7.500) = 852 
    [ 7.500, 10.000) = 23 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.529 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.383 ms/op
     p(95.0000) =      3.613 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      6.816 ms/op
     p(99.9900) =     16.581 ms/op
     p(99.9990) =     26.697 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.495 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.167 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.118 ±(99.9%) 0.007 ms/op
Iteration   1: 3.063 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.595 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  8.051 ms/op
                 getUser·p0.9999: 17.990 ms/op
                 getUser·p1.00:   18.186 ms/op

Iteration   2: 3.044 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.895 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  7.036 ms/op
                 getUser·p0.9999: 14.573 ms/op
                 getUser·p1.00:   15.008 ms/op

Iteration   3: 3.089 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.737 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  7.891 ms/op
                 getUser·p0.9999: 16.863 ms/op
                 getUser·p1.00:   19.431 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313208
  mean =      3.065 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 622 
    [ 1.250,  2.500) = 16164 
    [ 2.500,  3.750) = 278186 
    [ 3.750,  5.000) = 16778 
    [ 5.000,  6.250) = 863 
    [ 6.250,  7.500) = 272 
    [ 7.500,  8.750) = 95 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 62 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 58 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.595 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      7.609 ms/op
     p(99.9900) =     17.651 ms/op
     p(99.9990) =     18.178 ms/op
     p(99.9999) =     19.431 ms/op
    p(100.0000) =     19.431 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.708 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.170 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.043 ±(99.9%) 0.011 ms/op
Iteration   1: 4.128 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.705 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  15.467 ms/op
                 listUser·p0.9999: 20.226 ms/op
                 listUser·p1.00:   20.709 ms/op

Iteration   2: 4.042 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.779 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  14.677 ms/op
                 listUser·p0.9999: 16.223 ms/op
                 listUser·p1.00:   16.630 ms/op

Iteration   3: 4.044 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.077 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   7.176 ms/op
                 listUser·p0.999:  17.793 ms/op
                 listUser·p0.9999: 21.007 ms/op
                 listUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235716
  mean =      4.071 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1922 
    [ 2.500,  5.000) = 207964 
    [ 5.000,  7.500) = 24041 
    [ 7.500, 10.000) = 1254 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 161 
    [15.000, 17.500) = 146 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.705 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      5.087 ms/op
     p(95.0000) =      5.759 ms/op
     p(99.0000) =      7.193 ms/op
     p(99.9000) =     15.254 ms/op
     p(99.9900) =     20.677 ms/op
     p(99.9990) =     21.657 ms/op
     p(99.9999) =     22.315 ms/op
    p(100.0000) =     22.315 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.242 ± 1.217  ops/ms
ClientGrpc.existUser                       thrpt       3  10.907 ± 2.945  ops/ms
ClientGrpc.getUser                         thrpt       3  10.445 ± 1.090  ops/ms
ClientGrpc.listUser                        thrpt       3   7.853 ± 2.323  ops/ms
ClientGrpc.createUser                       avgt       3   3.079 ± 0.592   ms/op
ClientGrpc.existUser                        avgt       3   2.909 ± 0.419   ms/op
ClientGrpc.getUser                          avgt       3   3.031 ± 0.473   ms/op
ClientGrpc.listUser                         avgt       3   3.962 ± 0.535   ms/op
ClientGrpc.createUser                     sample  311788   3.079 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.741           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.052           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.596           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.785           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.415           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.237           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.752           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.757           ms/op
ClientGrpc.existUser                      sample  326829   2.938 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.529           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.908           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.383           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.613           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.202           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.816           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.581           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.034           ms/op
ClientGrpc.getUser                        sample  313208   3.065 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.595           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.035           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.568           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.805           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.473           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.609           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.651           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.431           ms/op
ClientGrpc.listUser                       sample  235716   4.071 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.705           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.891           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.087           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.759           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.193           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.254           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.677           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.315           ms/op
