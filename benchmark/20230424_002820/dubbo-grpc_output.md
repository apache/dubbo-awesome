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
# Warmup Iteration   1: 4.866 ops/ms
# Warmup Iteration   2: 9.649 ops/ms
# Warmup Iteration   3: 10.343 ops/ms
Iteration   1: 11.151 ops/ms
Iteration   2: 10.742 ops/ms
Iteration   3: 10.764 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.886 ±(99.9%) 4.189 ops/ms [Average]
  (min, avg, max) = (10.742, 10.886, 11.151), stdev = 0.230
  CI (99.9%): [6.697, 15.075] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.810 ops/ms
# Warmup Iteration   2: 10.970 ops/ms
# Warmup Iteration   3: 11.193 ops/ms
Iteration   1: 11.237 ops/ms
Iteration   2: 11.393 ops/ms
Iteration   3: 11.710 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.447 ±(99.9%) 4.394 ops/ms [Average]
  (min, avg, max) = (11.237, 11.447, 11.710), stdev = 0.241
  CI (99.9%): [7.053, 15.841] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.056 ops/ms
# Warmup Iteration   2: 10.172 ops/ms
# Warmup Iteration   3: 10.690 ops/ms
Iteration   1: 10.717 ops/ms
Iteration   2: 10.694 ops/ms
Iteration   3: 10.706 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.706 ±(99.9%) 0.211 ops/ms [Average]
  (min, avg, max) = (10.694, 10.706, 10.717), stdev = 0.012
  CI (99.9%): [10.495, 10.917] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.275 ops/ms
# Warmup Iteration   2: 8.010 ops/ms
# Warmup Iteration   3: 8.562 ops/ms
Iteration   1: 8.205 ops/ms
Iteration   2: 8.274 ops/ms
Iteration   3: 8.351 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.276 ±(99.9%) 1.334 ops/ms [Average]
  (min, avg, max) = (8.205, 8.276, 8.351), stdev = 0.073
  CI (99.9%): [6.943, 9.610] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.952 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.049 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.969 ±(99.9%) 0.003 ms/op
Iteration   1: 2.921 ±(99.9%) 0.008 ms/op
Iteration   2: 2.988 ±(99.9%) 0.003 ms/op
Iteration   3: 2.997 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.969 ±(99.9%) 0.753 ms/op [Average]
  (min, avg, max) = (2.921, 2.969, 2.997), stdev = 0.041
  CI (99.9%): [2.216, 3.722] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.588 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.951 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.822 ±(99.9%) 0.003 ms/op
Iteration   1: 2.856 ±(99.9%) 0.004 ms/op
Iteration   2: 2.825 ±(99.9%) 0.004 ms/op
Iteration   3: 2.876 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.852 ±(99.9%) 0.470 ms/op [Average]
  (min, avg, max) = (2.825, 2.852, 2.876), stdev = 0.026
  CI (99.9%): [2.382, 3.322] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.824 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.038 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.002 ms/op
Iteration   1: 2.939 ±(99.9%) 0.003 ms/op
Iteration   2: 2.952 ±(99.9%) 0.003 ms/op
Iteration   3: 2.977 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.956 ±(99.9%) 0.353 ms/op [Average]
  (min, avg, max) = (2.939, 2.956, 2.977), stdev = 0.019
  CI (99.9%): [2.603, 3.309] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.824 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.923 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 3.847 ±(99.9%) 0.011 ms/op
Iteration   1: 3.821 ±(99.9%) 0.009 ms/op
Iteration   2: 3.826 ±(99.9%) 0.041 ms/op
Iteration   3: 3.827 ±(99.9%) 0.040 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.825 ±(99.9%) 0.055 ms/op [Average]
  (min, avg, max) = (3.821, 3.825, 3.827), stdev = 0.003
  CI (99.9%): [3.770, 3.880] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.460 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.123 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.985 ±(99.9%) 0.007 ms/op
Iteration   1: 2.950 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.721 ms/op
                 createUser·p0.50:   2.929 ms/op
                 createUser·p0.90:   3.432 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.694 ms/op
                 createUser·p0.999:  6.898 ms/op
                 createUser·p0.9999: 14.893 ms/op
                 createUser·p1.00:   15.254 ms/op

Iteration   2: 2.961 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.569 ms/op
                 createUser·p0.50:   2.933 ms/op
                 createUser·p0.90:   3.428 ms/op
                 createUser·p0.95:   3.641 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  9.683 ms/op
                 createUser·p0.9999: 20.316 ms/op
                 createUser·p1.00:   20.709 ms/op

Iteration   3: 2.964 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.702 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  6.667 ms/op
                 createUser·p0.9999: 24.190 ms/op
                 createUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 324253
  mean =      2.958 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35083 
    [ 2.500,  5.000) = 287749 
    [ 5.000,  7.500) = 1089 
    [ 7.500, 10.000) = 100 
    [10.000, 12.500) = 10 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.569 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      7.713 ms/op
     p(99.9900) =     22.385 ms/op
     p(99.9990) =     26.108 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


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
# Warmup Iteration   1: 3.580 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 2.932 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.857 ±(99.9%) 0.006 ms/op
Iteration   1: 2.869 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.616 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  6.073 ms/op
                 existUser·p0.9999: 13.399 ms/op
                 existUser·p1.00:   13.697 ms/op

Iteration   2: 2.819 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.260 ms/op
                 existUser·p0.50:   2.830 ms/op
                 existUser·p0.90:   3.248 ms/op
                 existUser·p0.95:   3.445 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  7.335 ms/op
                 existUser·p0.9999: 23.036 ms/op
                 existUser·p1.00:   24.019 ms/op

Iteration   3: 2.851 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.581 ms/op
                 existUser·p0.50:   2.839 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.510 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  8.249 ms/op
                 existUser·p0.9999: 15.598 ms/op
                 existUser·p1.00:   25.821 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 337462
  mean =      2.846 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 54843 
    [ 2.500,  5.000) = 281590 
    [ 5.000,  7.500) = 712 
    [ 7.500, 10.000) = 108 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.260 ms/op
     p(50.0000) =      2.847 ms/op
     p(90.0000) =      3.342 ms/op
     p(95.0000) =      3.555 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      7.332 ms/op
     p(99.9900) =     17.783 ms/op
     p(99.9990) =     23.822 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


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
# Warmup Iteration   1: 3.927 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.083 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.006 ms/op
Iteration   1: 2.941 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.702 ms/op
                 getUser·p0.50:   2.941 ms/op
                 getUser·p0.90:   3.400 ms/op
                 getUser·p0.95:   3.564 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  7.214 ms/op
                 getUser·p0.9999: 11.882 ms/op
                 getUser·p1.00:   12.124 ms/op

Iteration   2: 2.967 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.585 ms/op
                 getUser·p0.50:   2.945 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  9.390 ms/op
                 getUser·p0.9999: 20.002 ms/op
                 getUser·p1.00:   20.414 ms/op

Iteration   3: 2.949 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.710 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  6.267 ms/op
                 getUser·p0.9999: 15.488 ms/op
                 getUser·p1.00:   15.778 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 325210
  mean =      2.952 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33671 
    [ 2.500,  5.000) = 290424 
    [ 5.000,  7.500) = 780 
    [ 7.500, 10.000) = 132 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.585 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.449 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      8.028 ms/op
     p(99.9900) =     17.512 ms/op
     p(99.9990) =     20.300 ms/op
     p(99.9999) =     20.414 ms/op
    p(100.0000) =     20.414 ms/op


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
# Warmup Iteration   1: 4.583 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.892 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.795 ±(99.9%) 0.009 ms/op
Iteration   1: 3.806 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.882 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.308 ms/op
                 listUser·p0.99:   6.496 ms/op
                 listUser·p0.999:  13.681 ms/op
                 listUser·p0.9999: 18.048 ms/op
                 listUser·p1.00:   19.300 ms/op

Iteration   2: 3.806 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.662 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.259 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  15.179 ms/op
                 listUser·p0.9999: 19.653 ms/op
                 listUser·p1.00:   20.644 ms/op

Iteration   3: 3.864 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.843 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  18.424 ms/op
                 listUser·p0.9999: 27.063 ms/op
                 listUser·p1.00:   27.558 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 250960
  mean =      3.825 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5406 
    [ 2.500,  5.000) = 228182 
    [ 5.000,  7.500) = 16305 
    [ 7.500, 10.000) = 592 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 169 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.662 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.710 ms/op
     p(95.0000) =      5.333 ms/op
     p(99.0000) =      6.611 ms/op
     p(99.9000) =     15.419 ms/op
     p(99.9900) =     25.294 ms/op
     p(99.9990) =     27.524 ms/op
     p(99.9999) =     27.558 ms/op
    p(100.0000) =     27.558 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.886 ± 4.189  ops/ms
ClientGrpc.existUser                       thrpt       3  11.447 ± 4.394  ops/ms
ClientGrpc.getUser                         thrpt       3  10.706 ± 0.211  ops/ms
ClientGrpc.listUser                        thrpt       3   8.276 ± 1.334  ops/ms
ClientGrpc.createUser                       avgt       3   2.969 ± 0.753   ms/op
ClientGrpc.existUser                        avgt       3   2.852 ± 0.470   ms/op
ClientGrpc.getUser                          avgt       3   2.956 ± 0.353   ms/op
ClientGrpc.listUser                         avgt       3   3.825 ± 0.055   ms/op
ClientGrpc.createUser                     sample  324253   2.958 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.569           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.937           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.453           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.711           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.530           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.713           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.385           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.575           ms/op
ClientGrpc.existUser                      sample  337462   2.846 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.260           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.847           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.342           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.555           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.375           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.332           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.783           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.821           ms/op
ClientGrpc.getUser                        sample  325210   2.952 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.585           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.945           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.449           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.678           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.415           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.028           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.512           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.414           ms/op
ClientGrpc.listUser                       sample  250960   3.825 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.662           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.690           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.710           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.333           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.611           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.419           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.294           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.558           ms/op
