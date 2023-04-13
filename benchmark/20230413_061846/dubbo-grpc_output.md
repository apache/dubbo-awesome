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
# Warmup Iteration   1: 4.355 ops/ms
# Warmup Iteration   2: 9.169 ops/ms
# Warmup Iteration   3: 9.969 ops/ms
Iteration   1: 10.223 ops/ms
Iteration   2: 10.806 ops/ms
Iteration   3: 10.349 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.459 ±(99.9%) 5.600 ops/ms [Average]
  (min, avg, max) = (10.223, 10.459, 10.806), stdev = 0.307
  CI (99.9%): [4.860, 16.059] (assumes normal distribution)


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
# Warmup Iteration   1: 7.476 ops/ms
# Warmup Iteration   2: 10.616 ops/ms
# Warmup Iteration   3: 10.999 ops/ms
Iteration   1: 10.862 ops/ms
Iteration   2: 11.062 ops/ms
Iteration   3: 10.737 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.887 ±(99.9%) 2.989 ops/ms [Average]
  (min, avg, max) = (10.737, 10.887, 11.062), stdev = 0.164
  CI (99.9%): [7.899, 13.876] (assumes normal distribution)


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
# Warmup Iteration   1: 7.137 ops/ms
# Warmup Iteration   2: 10.063 ops/ms
# Warmup Iteration   3: 10.361 ops/ms
Iteration   1: 10.361 ops/ms
Iteration   2: 10.471 ops/ms
Iteration   3: 10.533 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.455 ±(99.9%) 1.582 ops/ms [Average]
  (min, avg, max) = (10.361, 10.455, 10.533), stdev = 0.087
  CI (99.9%): [8.873, 12.037] (assumes normal distribution)


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
# Warmup Iteration   1: 5.663 ops/ms
# Warmup Iteration   2: 7.852 ops/ms
# Warmup Iteration   3: 8.053 ops/ms
Iteration   1: 7.938 ops/ms
Iteration   2: 8.121 ops/ms
Iteration   3: 8.091 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.050 ±(99.9%) 1.786 ops/ms [Average]
  (min, avg, max) = (7.938, 8.050, 8.121), stdev = 0.098
  CI (99.9%): [6.264, 9.836] (assumes normal distribution)


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
# Warmup Iteration   1: 4.141 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.215 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.004 ms/op
Iteration   1: 3.095 ±(99.9%) 0.001 ms/op
Iteration   2: 3.003 ±(99.9%) 0.003 ms/op
Iteration   3: 3.073 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.057 ±(99.9%) 0.871 ms/op [Average]
  (min, avg, max) = (3.003, 3.057, 3.095), stdev = 0.048
  CI (99.9%): [2.186, 3.928] (assumes normal distribution)


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
# Warmup Iteration   1: 3.945 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.066 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.931 ±(99.9%) 0.003 ms/op
Iteration   1: 2.978 ±(99.9%) 0.002 ms/op
Iteration   2: 2.955 ±(99.9%) 0.003 ms/op
Iteration   3: 2.949 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.961 ±(99.9%) 0.276 ms/op [Average]
  (min, avg, max) = (2.949, 2.961, 2.978), stdev = 0.015
  CI (99.9%): [2.684, 3.237] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.416 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.206 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.174 ±(99.9%) 0.002 ms/op
Iteration   1: 3.090 ±(99.9%) 0.003 ms/op
Iteration   2: 3.110 ±(99.9%) 0.001 ms/op
Iteration   3: 3.086 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.095 ±(99.9%) 0.237 ms/op [Average]
  (min, avg, max) = (3.086, 3.095, 3.110), stdev = 0.013
  CI (99.9%): [2.859, 3.332] (assumes normal distribution)


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
# Warmup Iteration   1: 4.903 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.342 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.031 ±(99.9%) 0.007 ms/op
Iteration   1: 3.992 ±(99.9%) 0.013 ms/op
Iteration   2: 4.022 ±(99.9%) 0.015 ms/op
Iteration   3: 3.875 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.963 ±(99.9%) 1.416 ms/op [Average]
  (min, avg, max) = (3.875, 3.963, 4.022), stdev = 0.078
  CI (99.9%): [2.547, 5.379] (assumes normal distribution)


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
# Warmup Iteration   1: 4.379 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.294 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.110 ±(99.9%) 0.006 ms/op
Iteration   1: 3.110 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.886 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  9.880 ms/op
                 createUser·p0.9999: 13.196 ms/op
                 createUser·p1.00:   13.369 ms/op

Iteration   2: 3.092 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.851 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.908 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  10.099 ms/op
                 createUser·p0.9999: 19.420 ms/op
                 createUser·p1.00:   19.857 ms/op

Iteration   3: 3.144 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.611 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.744 ms/op
                 createUser·p0.95:   4.022 ms/op
                 createUser·p0.99:   4.719 ms/op
                 createUser·p0.999:  10.589 ms/op
                 createUser·p0.9999: 27.350 ms/op
                 createUser·p1.00:   28.049 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308283
  mean =      3.115 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19188 
    [ 2.500,  5.000) = 287483 
    [ 5.000,  7.500) = 1080 
    [ 7.500, 10.000) = 187 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.611 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      4.563 ms/op
     p(99.9000) =     10.256 ms/op
     p(99.9900) =     26.673 ms/op
     p(99.9990) =     27.588 ms/op
     p(99.9999) =     28.049 ms/op
    p(100.0000) =     28.049 ms/op


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
# Warmup Iteration   1: 4.063 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.069 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.006 ms/op
Iteration   1: 2.960 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.629 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   4.555 ms/op
                 existUser·p0.999:  8.336 ms/op
                 existUser·p0.9999: 19.857 ms/op
                 existUser·p1.00:   20.185 ms/op

Iteration   2: 2.907 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.733 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  7.028 ms/op
                 existUser·p0.9999: 23.888 ms/op
                 existUser·p1.00:   25.068 ms/op

Iteration   3: 2.972 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.706 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  6.686 ms/op
                 existUser·p0.9999: 28.312 ms/op
                 existUser·p1.00:   28.508 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325858
  mean =      2.946 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38231 
    [ 2.500,  5.000) = 286634 
    [ 5.000,  7.500) = 658 
    [ 7.500, 10.000) = 80 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.629 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.449 ms/op
     p(95.0000) =      3.674 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      7.613 ms/op
     p(99.9900) =     26.207 ms/op
     p(99.9990) =     28.443 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


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
# Warmup Iteration   1: 4.400 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.205 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.108 ±(99.9%) 0.007 ms/op
Iteration   1: 3.111 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.855 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  7.311 ms/op
                 getUser·p0.9999: 13.639 ms/op
                 getUser·p1.00:   16.155 ms/op

Iteration   2: 3.097 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.945 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  7.084 ms/op
                 getUser·p0.9999: 15.205 ms/op
                 getUser·p1.00:   15.565 ms/op

Iteration   3: 3.130 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.955 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.903 ms/op
                 getUser·p0.99:   4.555 ms/op
                 getUser·p0.999:  9.054 ms/op
                 getUser·p0.9999: 19.982 ms/op
                 getUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 308164
  mean =      3.113 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11509 
    [ 2.500,  5.000) = 295218 
    [ 5.000,  7.500) = 1109 
    [ 7.500, 10.000) = 136 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.855 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      7.837 ms/op
     p(99.9900) =     18.088 ms/op
     p(99.9990) =     20.152 ms/op
     p(99.9999) =     20.251 ms/op
    p(100.0000) =     20.251 ms/op


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
# Warmup Iteration   1: 4.511 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.351 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.077 ±(99.9%) 0.012 ms/op
Iteration   1: 3.916 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.442 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.751 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  15.565 ms/op
                 listUser·p0.9999: 23.375 ms/op
                 listUser·p1.00:   23.757 ms/op

Iteration   2: 4.035 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.017 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.857 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  14.905 ms/op
                 listUser·p0.9999: 18.234 ms/op
                 listUser·p1.00:   20.218 ms/op

Iteration   3: 4.011 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.200 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  17.072 ms/op
                 listUser·p0.9999: 26.804 ms/op
                 listUser·p1.00:   28.049 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240634
  mean =      3.987 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2585 
    [ 2.500,  5.000) = 216528 
    [ 5.000,  7.500) = 20157 
    [ 7.500, 10.000) = 979 
    [10.000, 12.500) = 17 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 146 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.017 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.882 ms/op
     p(95.0000) =      5.726 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     16.253 ms/op
     p(99.9900) =     25.819 ms/op
     p(99.9990) =     27.034 ms/op
     p(99.9999) =     28.049 ms/op
    p(100.0000) =     28.049 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.459 ± 5.600  ops/ms
ClientGrpc.existUser                       thrpt       3  10.887 ± 2.989  ops/ms
ClientGrpc.getUser                         thrpt       3  10.455 ± 1.582  ops/ms
ClientGrpc.listUser                        thrpt       3   8.050 ± 1.786  ops/ms
ClientGrpc.createUser                       avgt       3   3.057 ± 0.871   ms/op
ClientGrpc.existUser                        avgt       3   2.961 ± 0.276   ms/op
ClientGrpc.getUser                          avgt       3   3.095 ± 0.237   ms/op
ClientGrpc.listUser                         avgt       3   3.963 ± 1.416   ms/op
ClientGrpc.createUser                     sample  308283   3.115 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.611           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.080           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.662           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.908           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.563           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.256           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.673           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.049           ms/op
ClientGrpc.existUser                      sample  325858   2.946 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.629           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.449           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.674           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.375           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.613           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.207           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.508           ms/op
ClientGrpc.getUser                        sample  308164   3.113 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.855           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.088           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.600           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.817           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.473           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.837           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.088           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.251           ms/op
ClientGrpc.listUser                       sample  240634   3.987 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.017           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.834           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.882           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.726           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.021           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.253           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.819           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.049           ms/op
