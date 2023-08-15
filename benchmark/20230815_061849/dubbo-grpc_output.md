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
# Warmup Iteration   1: 4.184 ops/ms
# Warmup Iteration   2: 9.006 ops/ms
# Warmup Iteration   3: 10.285 ops/ms
Iteration   1: 10.192 ops/ms
Iteration   2: 10.462 ops/ms
Iteration   3: 10.332 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.329 ±(99.9%) 2.463 ops/ms [Average]
  (min, avg, max) = (10.192, 10.329, 10.462), stdev = 0.135
  CI (99.9%): [7.866, 12.791] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.168 ops/ms
# Warmup Iteration   2: 10.600 ops/ms
# Warmup Iteration   3: 10.985 ops/ms
Iteration   1: 11.034 ops/ms
Iteration   2: 11.051 ops/ms
Iteration   3: 11.070 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.052 ±(99.9%) 0.324 ops/ms [Average]
  (min, avg, max) = (11.034, 11.052, 11.070), stdev = 0.018
  CI (99.9%): [10.727, 11.376] (assumes normal distribution)


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
# Warmup Iteration   1: 6.859 ops/ms
# Warmup Iteration   2: 9.894 ops/ms
# Warmup Iteration   3: 10.436 ops/ms
Iteration   1: 10.312 ops/ms
Iteration   2: 10.236 ops/ms
Iteration   3: 10.327 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.292 ±(99.9%) 0.885 ops/ms [Average]
  (min, avg, max) = (10.236, 10.292, 10.327), stdev = 0.048
  CI (99.9%): [9.407, 11.176] (assumes normal distribution)


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
# Warmup Iteration   1: 5.442 ops/ms
# Warmup Iteration   2: 7.173 ops/ms
# Warmup Iteration   3: 7.579 ops/ms
Iteration   1: 7.759 ops/ms
Iteration   2: 7.880 ops/ms
Iteration   3: 7.530 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.723 ±(99.9%) 3.238 ops/ms [Average]
  (min, avg, max) = (7.530, 7.723, 7.880), stdev = 0.177
  CI (99.9%): [4.485, 10.961] (assumes normal distribution)


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
# Warmup Iteration   1: 4.422 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.282 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.110 ±(99.9%) 0.002 ms/op
Iteration   1: 3.061 ±(99.9%) 0.011 ms/op
Iteration   2: 3.076 ±(99.9%) 0.003 ms/op
Iteration   3: 3.012 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.049 ±(99.9%) 0.609 ms/op [Average]
  (min, avg, max) = (3.012, 3.049, 3.076), stdev = 0.033
  CI (99.9%): [2.440, 3.658] (assumes normal distribution)


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
# Warmup Iteration   1: 3.967 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.066 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 2.911 ±(99.9%) 0.004 ms/op
Iteration   1: 2.931 ±(99.9%) 0.002 ms/op
Iteration   2: 2.971 ±(99.9%) 0.002 ms/op
Iteration   3: 2.945 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.949 ±(99.9%) 0.370 ms/op [Average]
  (min, avg, max) = (2.931, 2.949, 2.971), stdev = 0.020
  CI (99.9%): [2.579, 3.319] (assumes normal distribution)


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
# Warmup Iteration   1: 4.190 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.241 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.003 ms/op
Iteration   1: 3.113 ±(99.9%) 0.003 ms/op
Iteration   2: 3.064 ±(99.9%) 0.003 ms/op
Iteration   3: 3.080 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.086 ±(99.9%) 0.461 ms/op [Average]
  (min, avg, max) = (3.064, 3.086, 3.113), stdev = 0.025
  CI (99.9%): [2.625, 3.546] (assumes normal distribution)


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
# Warmup Iteration   1: 5.734 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.176 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.106 ±(99.9%) 0.007 ms/op
Iteration   1: 4.213 ±(99.9%) 0.017 ms/op
Iteration   2: 4.151 ±(99.9%) 0.012 ms/op
Iteration   3: 4.083 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.149 ±(99.9%) 1.182 ms/op [Average]
  (min, avg, max) = (4.083, 4.149, 4.213), stdev = 0.065
  CI (99.9%): [2.966, 5.331] (assumes normal distribution)


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
# Warmup Iteration   1: 4.607 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.210 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.007 ms/op
Iteration   1: 3.110 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.939 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.841 ms/op
                 createUser·p0.999:  8.366 ms/op
                 createUser·p0.9999: 19.717 ms/op
                 createUser·p1.00:   20.349 ms/op

Iteration   2: 3.107 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.812 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   3.928 ms/op
                 createUser·p0.99:   4.628 ms/op
                 createUser·p0.999:  8.266 ms/op
                 createUser·p0.9999: 15.122 ms/op
                 createUser·p1.00:   15.565 ms/op

Iteration   3: 3.040 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.760 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.628 ms/op
                 createUser·p0.999:  11.223 ms/op
                 createUser·p0.9999: 26.998 ms/op
                 createUser·p1.00:   28.672 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311220
  mean =      3.085 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20160 
    [ 2.500,  5.000) = 288821 
    [ 5.000,  7.500) = 1715 
    [ 7.500, 10.000) = 268 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.760 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      4.710 ms/op
     p(99.9000) =      8.483 ms/op
     p(99.9900) =     26.374 ms/op
     p(99.9990) =     28.603 ms/op
     p(99.9999) =     28.672 ms/op
    p(100.0000) =     28.672 ms/op


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
# Warmup Iteration   1: 4.230 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.963 ±(99.9%) 0.006 ms/op
Iteration   1: 2.941 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.861 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   4.571 ms/op
                 existUser·p0.999:  8.119 ms/op
                 existUser·p0.9999: 14.387 ms/op
                 existUser·p1.00:   14.746 ms/op

Iteration   2: 2.905 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.741 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   4.258 ms/op
                 existUser·p0.999:  7.482 ms/op
                 existUser·p0.9999: 14.155 ms/op
                 existUser·p1.00:   14.352 ms/op

Iteration   3: 2.929 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.732 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   4.588 ms/op
                 existUser·p0.999:  8.307 ms/op
                 existUser·p0.9999: 17.239 ms/op
                 existUser·p1.00:   19.399 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328307
  mean =      2.925 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1448 
    [ 1.250,  2.500) = 34292 
    [ 2.500,  3.750) = 282726 
    [ 3.750,  5.000) = 8217 
    [ 5.000,  6.250) = 898 
    [ 6.250,  7.500) = 315 
    [ 7.500,  8.750) = 204 
    [ 8.750, 10.000) = 15 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 74 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 46 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.732 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.375 ms/op
     p(95.0000) =      3.568 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      8.140 ms/op
     p(99.9900) =     16.843 ms/op
     p(99.9990) =     18.055 ms/op
     p(99.9999) =     19.399 ms/op
    p(100.0000) =     19.399 ms/op


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
# Warmup Iteration   1: 4.455 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.268 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.141 ±(99.9%) 0.008 ms/op
Iteration   1: 3.130 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.692 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   4.784 ms/op
                 getUser·p0.999:  8.614 ms/op
                 getUser·p0.9999: 18.901 ms/op
                 getUser·p1.00:   20.185 ms/op

Iteration   2: 3.114 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.881 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   4.801 ms/op
                 getUser·p0.999:  8.448 ms/op
                 getUser·p0.9999: 19.086 ms/op
                 getUser·p1.00:   19.268 ms/op

Iteration   3: 3.082 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.950 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.579 ms/op
                 getUser·p0.999:  8.268 ms/op
                 getUser·p0.9999: 29.106 ms/op
                 getUser·p1.00:   29.426 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 308732
  mean =      3.109 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17766 
    [ 2.500,  5.000) = 288720 
    [ 5.000,  7.500) = 1683 
    [ 7.500, 10.000) = 346 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.692 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      4.751 ms/op
     p(99.9000) =      8.438 ms/op
     p(99.9900) =     27.623 ms/op
     p(99.9990) =     29.423 ms/op
     p(99.9999) =     29.426 ms/op
    p(100.0000) =     29.426 ms/op


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
# Warmup Iteration   1: 6.324 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.284 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.183 ±(99.9%) 0.013 ms/op
Iteration   1: 4.096 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.092 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   6.046 ms/op
                 listUser·p0.99:   7.143 ms/op
                 listUser·p0.999:  23.779 ms/op
                 listUser·p0.9999: 30.415 ms/op
                 listUser·p1.00:   31.490 ms/op

Iteration   2: 4.152 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.204 ms/op
                 listUser·p0.50:   3.990 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   6.111 ms/op
                 listUser·p0.99:   7.225 ms/op
                 listUser·p0.999:  14.024 ms/op
                 listUser·p0.9999: 16.839 ms/op
                 listUser·p1.00:   17.531 ms/op

Iteration   3: 4.030 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.867 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   5.988 ms/op
                 listUser·p0.99:   7.528 ms/op
                 listUser·p0.999:  17.680 ms/op
                 listUser·p0.9999: 26.839 ms/op
                 listUser·p1.00:   27.132 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234590
  mean =      4.092 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2876 
    [ 2.500,  5.000) = 203641 
    [ 5.000,  7.500) = 26215 
    [ 7.500, 10.000) = 1364 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.867 ms/op
     p(50.0000) =      3.924 ms/op
     p(90.0000) =      5.210 ms/op
     p(95.0000) =      6.062 ms/op
     p(99.0000) =      7.274 ms/op
     p(99.9000) =     16.447 ms/op
     p(99.9900) =     29.542 ms/op
     p(99.9990) =     31.292 ms/op
     p(99.9999) =     31.490 ms/op
    p(100.0000) =     31.490 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.329 ± 2.463  ops/ms
ClientGrpc.existUser                       thrpt       3  11.052 ± 0.324  ops/ms
ClientGrpc.getUser                         thrpt       3  10.292 ± 0.885  ops/ms
ClientGrpc.listUser                        thrpt       3   7.723 ± 3.238  ops/ms
ClientGrpc.createUser                       avgt       3   3.049 ± 0.609   ms/op
ClientGrpc.existUser                        avgt       3   2.949 ± 0.370   ms/op
ClientGrpc.getUser                          avgt       3   3.086 ± 0.461   ms/op
ClientGrpc.listUser                         avgt       3   4.149 ± 1.182   ms/op
ClientGrpc.createUser                     sample  311220   3.085 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.760           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.043           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.650           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.879           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.710           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.483           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.374           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.672           ms/op
ClientGrpc.existUser                      sample  328307   2.925 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.732           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.908           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.375           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.568           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.481           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.140           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.843           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.399           ms/op
ClientGrpc.getUser                        sample  308732   3.109 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.692           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.076           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.658           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.887           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.751           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.438           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.623           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.426           ms/op
ClientGrpc.listUser                       sample  234590   4.092 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.867           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.924           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.210           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.062           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.274           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.447           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.542           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.490           ms/op
