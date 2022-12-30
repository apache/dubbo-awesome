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
# Warmup Iteration   1: 2.919 ops/ms
# Warmup Iteration   2: 7.125 ops/ms
# Warmup Iteration   3: 7.983 ops/ms
Iteration   1: 8.335 ops/ms
Iteration   2: 8.262 ops/ms
Iteration   3: 8.366 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.321 ±(99.9%) 0.981 ops/ms [Average]
  (min, avg, max) = (8.262, 8.321, 8.366), stdev = 0.054
  CI (99.9%): [7.340, 9.302] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.712 ops/ms
# Warmup Iteration   2: 8.212 ops/ms
# Warmup Iteration   3: 8.475 ops/ms
Iteration   1: 8.576 ops/ms
Iteration   2: 8.595 ops/ms
Iteration   3: 8.862 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.678 ±(99.9%) 2.916 ops/ms [Average]
  (min, avg, max) = (8.576, 8.678, 8.862), stdev = 0.160
  CI (99.9%): [5.762, 11.594] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.616 ops/ms
# Warmup Iteration   2: 8.155 ops/ms
# Warmup Iteration   3: 8.138 ops/ms
Iteration   1: 8.559 ops/ms
Iteration   2: 8.432 ops/ms
Iteration   3: 8.347 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.446 ±(99.9%) 1.943 ops/ms [Average]
  (min, avg, max) = (8.347, 8.446, 8.559), stdev = 0.107
  CI (99.9%): [6.503, 10.389] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.248 ops/ms
# Warmup Iteration   2: 6.355 ops/ms
# Warmup Iteration   3: 6.649 ops/ms
Iteration   1: 6.558 ops/ms
Iteration   2: 7.004 ops/ms
Iteration   3: 6.619 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.727 ±(99.9%) 4.411 ops/ms [Average]
  (min, avg, max) = (6.558, 6.727, 7.004), stdev = 0.242
  CI (99.9%): [2.316, 11.138] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.421 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.975 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.864 ±(99.9%) 0.003 ms/op
Iteration   1: 3.906 ±(99.9%) 0.003 ms/op
Iteration   2: 3.941 ±(99.9%) 0.003 ms/op
Iteration   3: 3.968 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.939 ±(99.9%) 0.567 ms/op [Average]
  (min, avg, max) = (3.906, 3.939, 3.968), stdev = 0.031
  CI (99.9%): [3.371, 4.506] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.015 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.836 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.744 ±(99.9%) 0.003 ms/op
Iteration   1: 3.770 ±(99.9%) 0.003 ms/op
Iteration   2: 3.758 ±(99.9%) 0.003 ms/op
Iteration   3: 3.698 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.742 ±(99.9%) 0.701 ms/op [Average]
  (min, avg, max) = (3.698, 3.742, 3.770), stdev = 0.038
  CI (99.9%): [3.041, 4.443] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.247 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.048 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.797 ±(99.9%) 0.003 ms/op
Iteration   1: 3.953 ±(99.9%) 0.005 ms/op
Iteration   2: 3.794 ±(99.9%) 0.009 ms/op
Iteration   3: 3.756 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.834 ±(99.9%) 1.905 ms/op [Average]
  (min, avg, max) = (3.756, 3.834, 3.953), stdev = 0.104
  CI (99.9%): [1.930, 5.739] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.310 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 5.161 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.954 ±(99.9%) 0.011 ms/op
Iteration   1: 4.790 ±(99.9%) 0.028 ms/op
Iteration   2: 4.740 ±(99.9%) 0.014 ms/op
Iteration   3: 4.909 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.813 ±(99.9%) 1.578 ms/op [Average]
  (min, avg, max) = (4.740, 4.813, 4.909), stdev = 0.087
  CI (99.9%): [3.235, 6.391] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.483 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.892 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.627 ±(99.9%) 0.010 ms/op
Iteration   1: 3.800 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.995 ms/op
                 createUser·p0.50:   3.711 ms/op
                 createUser·p0.90:   4.710 ms/op
                 createUser·p0.95:   5.104 ms/op
                 createUser·p0.99:   6.398 ms/op
                 createUser·p0.999:  12.250 ms/op
                 createUser·p0.9999: 23.855 ms/op
                 createUser·p1.00:   24.216 ms/op

Iteration   2: 3.766 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.600 ms/op
                 createUser·p0.50:   3.703 ms/op
                 createUser·p0.90:   4.669 ms/op
                 createUser·p0.95:   5.004 ms/op
                 createUser·p0.99:   6.218 ms/op
                 createUser·p0.999:  13.826 ms/op
                 createUser·p0.9999: 27.066 ms/op
                 createUser·p1.00:   29.164 ms/op

Iteration   3: 3.706 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.797 ms/op
                 createUser·p0.50:   3.666 ms/op
                 createUser·p0.90:   4.571 ms/op
                 createUser·p0.95:   4.866 ms/op
                 createUser·p0.99:   5.841 ms/op
                 createUser·p0.999:  8.288 ms/op
                 createUser·p0.9999: 19.469 ms/op
                 createUser·p1.00:   20.480 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 255504
  mean =      3.757 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9981 
    [ 2.500,  5.000) = 233103 
    [ 5.000,  7.500) = 11467 
    [ 7.500, 10.000) = 560 
    [10.000, 12.500) = 180 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 45 

  Percentiles, ms/op:
      p(0.0000) =      0.600 ms/op
     p(50.0000) =      3.695 ms/op
     p(90.0000) =      4.645 ms/op
     p(95.0000) =      4.989 ms/op
     p(99.0000) =      6.152 ms/op
     p(99.9000) =     11.641 ms/op
     p(99.9900) =     26.640 ms/op
     p(99.9990) =     28.782 ms/op
     p(99.9999) =     29.164 ms/op
    p(100.0000) =     29.164 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.076 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.904 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.717 ±(99.9%) 0.011 ms/op
Iteration   1: 3.700 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.710 ms/op
                 existUser·p0.50:   3.637 ms/op
                 existUser·p0.90:   4.612 ms/op
                 existUser·p0.95:   4.940 ms/op
                 existUser·p0.99:   6.209 ms/op
                 existUser·p0.999:  10.224 ms/op
                 existUser·p0.9999: 15.773 ms/op
                 existUser·p1.00:   16.220 ms/op

Iteration   2: 3.538 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.697 ms/op
                 existUser·p0.50:   3.506 ms/op
                 existUser·p0.90:   4.489 ms/op
                 existUser·p0.95:   4.784 ms/op
                 existUser·p0.99:   5.734 ms/op
                 existUser·p0.999:  8.033 ms/op
                 existUser·p0.9999: 19.399 ms/op
                 existUser·p1.00:   19.923 ms/op

Iteration   3: 3.789 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.991 ms/op
                 existUser·p0.50:   3.695 ms/op
                 existUser·p0.90:   4.661 ms/op
                 existUser·p0.95:   4.997 ms/op
                 existUser·p0.99:   6.660 ms/op
                 existUser·p0.999:  11.626 ms/op
                 existUser·p0.9999: 24.023 ms/op
                 existUser·p1.00:   24.838 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 261313
  mean =      3.673 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12916 
    [ 2.500,  5.000) = 237583 
    [ 5.000,  7.500) = 9740 
    [ 7.500, 10.000) = 792 
    [10.000, 12.500) = 154 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.697 ms/op
     p(50.0000) =      3.613 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      4.907 ms/op
     p(99.0000) =      6.144 ms/op
     p(99.9000) =     10.169 ms/op
     p(99.9900) =     22.038 ms/op
     p(99.9990) =     24.266 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.268 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.008 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.754 ±(99.9%) 0.009 ms/op
Iteration   1: 3.781 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.059 ms/op
                 getUser·p0.50:   3.731 ms/op
                 getUser·p0.90:   4.751 ms/op
                 getUser·p0.95:   5.145 ms/op
                 getUser·p0.99:   6.652 ms/op
                 getUser·p0.999:  12.255 ms/op
                 getUser·p0.9999: 14.877 ms/op
                 getUser·p1.00:   15.368 ms/op

Iteration   2: 3.854 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.954 ms/op
                 getUser·p0.50:   3.797 ms/op
                 getUser·p0.90:   4.833 ms/op
                 getUser·p0.95:   5.202 ms/op
                 getUser·p0.99:   6.545 ms/op
                 getUser·p0.999:  10.818 ms/op
                 getUser·p0.9999: 20.255 ms/op
                 getUser·p1.00:   20.414 ms/op

Iteration   3: 3.888 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.950 ms/op
                 getUser·p0.50:   3.797 ms/op
                 getUser·p0.90:   4.776 ms/op
                 getUser·p0.95:   5.128 ms/op
                 getUser·p0.99:   6.449 ms/op
                 getUser·p0.999:  11.139 ms/op
                 getUser·p0.9999: 22.595 ms/op
                 getUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 249792
  mean =      3.840 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10541 
    [ 2.500,  5.000) = 222565 
    [ 5.000,  7.500) = 15405 
    [ 7.500, 10.000) = 913 
    [10.000, 12.500) = 154 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.950 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.161 ms/op
     p(99.0000) =      6.554 ms/op
     p(99.9000) =     11.931 ms/op
     p(99.9900) =     21.103 ms/op
     p(99.9990) =     22.823 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


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
# Warmup Iteration   1: 6.619 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 5.024 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.815 ±(99.9%) 0.016 ms/op
Iteration   1: 4.678 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.137 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   6.062 ms/op
                 listUser·p0.95:   6.734 ms/op
                 listUser·p0.99:   8.310 ms/op
                 listUser·p0.999:  15.373 ms/op
                 listUser·p0.9999: 22.954 ms/op
                 listUser·p1.00:   23.724 ms/op

Iteration   2: 4.751 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.565 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   6.242 ms/op
                 listUser·p0.95:   7.012 ms/op
                 listUser·p0.99:   8.381 ms/op
                 listUser·p0.999:  18.448 ms/op
                 listUser·p0.9999: 22.258 ms/op
                 listUser·p1.00:   22.807 ms/op

Iteration   3: 4.756 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.077 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   6.152 ms/op
                 listUser·p0.95:   6.865 ms/op
                 listUser·p0.99:   8.777 ms/op
                 listUser·p0.999:  20.480 ms/op
                 listUser·p0.9999: 28.616 ms/op
                 listUser·p1.00:   29.131 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 202885
  mean =      4.728 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 746 
    [ 2.500,  5.000) = 149250 
    [ 5.000,  7.500) = 47634 
    [ 7.500, 10.000) = 4569 
    [10.000, 12.500) = 311 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 114 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.077 ms/op
     p(50.0000) =      4.497 ms/op
     p(90.0000) =      6.152 ms/op
     p(95.0000) =      6.873 ms/op
     p(99.0000) =      8.471 ms/op
     p(99.9000) =     19.399 ms/op
     p(99.9900) =     26.402 ms/op
     p(99.9990) =     29.090 ms/op
     p(99.9999) =     29.131 ms/op
    p(100.0000) =     29.131 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.321 ± 0.981  ops/ms
ClientGrpc.existUser                       thrpt       3   8.678 ± 2.916  ops/ms
ClientGrpc.getUser                         thrpt       3   8.446 ± 1.943  ops/ms
ClientGrpc.listUser                        thrpt       3   6.727 ± 4.411  ops/ms
ClientGrpc.createUser                       avgt       3   3.939 ± 0.567   ms/op
ClientGrpc.existUser                        avgt       3   3.742 ± 0.701   ms/op
ClientGrpc.getUser                          avgt       3   3.834 ± 1.905   ms/op
ClientGrpc.listUser                         avgt       3   4.813 ± 1.578   ms/op
ClientGrpc.createUser                     sample  255504   3.757 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.600           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.695           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.645           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.989           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.152           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.641           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.640           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.164           ms/op
ClientGrpc.existUser                      sample  261313   3.673 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.697           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.613           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.588           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.907           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.144           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.169           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.038           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.838           ms/op
ClientGrpc.getUser                        sample  249792   3.840 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.950           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.772           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.784           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.161           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.554           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.931           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.103           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.872           ms/op
ClientGrpc.listUser                       sample  202885   4.728 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.077           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.497           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.152           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.873           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.471           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.399           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.402           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.131           ms/op
