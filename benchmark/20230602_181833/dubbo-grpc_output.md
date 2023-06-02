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
# Warmup Iteration   1: 4.189 ops/ms
# Warmup Iteration   2: 8.927 ops/ms
# Warmup Iteration   3: 10.364 ops/ms
Iteration   1: 10.363 ops/ms
Iteration   2: 10.381 ops/ms
Iteration   3: 10.512 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.419 ±(99.9%) 1.490 ops/ms [Average]
  (min, avg, max) = (10.363, 10.419, 10.512), stdev = 0.082
  CI (99.9%): [8.928, 11.909] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.371 ops/ms
# Warmup Iteration   2: 10.553 ops/ms
# Warmup Iteration   3: 11.087 ops/ms
Iteration   1: 11.008 ops/ms
Iteration   2: 11.060 ops/ms
Iteration   3: 11.012 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.027 ±(99.9%) 0.527 ops/ms [Average]
  (min, avg, max) = (11.008, 11.027, 11.060), stdev = 0.029
  CI (99.9%): [10.500, 11.553] (assumes normal distribution)


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
# Warmup Iteration   1: 6.745 ops/ms
# Warmup Iteration   2: 10.149 ops/ms
# Warmup Iteration   3: 10.335 ops/ms
Iteration   1: 10.575 ops/ms
Iteration   2: 10.664 ops/ms
Iteration   3: 10.593 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.610 ±(99.9%) 0.859 ops/ms [Average]
  (min, avg, max) = (10.575, 10.610, 10.664), stdev = 0.047
  CI (99.9%): [9.751, 11.470] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.703 ops/ms
# Warmup Iteration   2: 7.586 ops/ms
# Warmup Iteration   3: 8.041 ops/ms
Iteration   1: 7.993 ops/ms
Iteration   2: 8.026 ops/ms
Iteration   3: 8.080 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.033 ±(99.9%) 0.802 ops/ms [Average]
  (min, avg, max) = (7.993, 8.033, 8.080), stdev = 0.044
  CI (99.9%): [7.231, 8.835] (assumes normal distribution)


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
# Warmup Iteration   1: 4.247 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.168 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.002 ms/op
Iteration   1: 2.997 ±(99.9%) 0.003 ms/op
Iteration   2: 3.020 ±(99.9%) 0.002 ms/op
Iteration   3: 2.919 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.979 ±(99.9%) 0.973 ms/op [Average]
  (min, avg, max) = (2.919, 2.979, 3.020), stdev = 0.053
  CI (99.9%): [2.005, 3.952] (assumes normal distribution)


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
# Warmup Iteration   1: 4.008 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.071 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.924 ±(99.9%) 0.004 ms/op
Iteration   1: 2.860 ±(99.9%) 0.003 ms/op
Iteration   2: 2.886 ±(99.9%) 0.003 ms/op
Iteration   3: 2.861 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.869 ±(99.9%) 0.266 ms/op [Average]
  (min, avg, max) = (2.860, 2.869, 2.886), stdev = 0.015
  CI (99.9%): [2.602, 3.135] (assumes normal distribution)


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
# Warmup Iteration   1: 3.876 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.002 ms/op
Iteration   1: 2.993 ±(99.9%) 0.003 ms/op
Iteration   2: 3.028 ±(99.9%) 0.002 ms/op
Iteration   3: 3.002 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.008 ±(99.9%) 0.331 ms/op [Average]
  (min, avg, max) = (2.993, 3.008, 3.028), stdev = 0.018
  CI (99.9%): [2.677, 3.338] (assumes normal distribution)


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
# Warmup Iteration   1: 4.842 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.149 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.983 ±(99.9%) 0.010 ms/op
Iteration   1: 3.977 ±(99.9%) 0.009 ms/op
Iteration   2: 3.942 ±(99.9%) 0.009 ms/op
Iteration   3: 3.967 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.962 ±(99.9%) 0.330 ms/op [Average]
  (min, avg, max) = (3.942, 3.962, 3.977), stdev = 0.018
  CI (99.9%): [3.631, 4.292] (assumes normal distribution)


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
# Warmup Iteration   1: 4.241 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.204 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.084 ±(99.9%) 0.006 ms/op
Iteration   1: 3.054 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.291 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.682 ms/op
                 createUser·p0.99:   4.611 ms/op
                 createUser·p0.999:  6.797 ms/op
                 createUser·p0.9999: 16.746 ms/op
                 createUser·p1.00:   17.236 ms/op

Iteration   2: 3.044 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.507 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   4.405 ms/op
                 createUser·p0.999:  6.791 ms/op
                 createUser·p0.9999: 17.482 ms/op
                 createUser·p1.00:   17.727 ms/op

Iteration   3: 3.023 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.889 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.617 ms/op
                 createUser·p0.99:   4.137 ms/op
                 createUser·p0.999:  7.083 ms/op
                 createUser·p0.9999: 19.014 ms/op
                 createUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315626
  mean =      3.040 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23859 
    [ 2.500,  5.000) = 290263 
    [ 5.000,  7.500) = 1243 
    [ 7.500, 10.000) = 45 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.291 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.695 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      6.865 ms/op
     p(99.9900) =     18.416 ms/op
     p(99.9990) =     20.151 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


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
# Warmup Iteration   1: 3.917 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.018 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.960 ±(99.9%) 0.007 ms/op
Iteration   1: 2.921 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   1.059 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.244 ms/op
                 existUser·p0.95:   3.351 ms/op
                 existUser·p0.99:   3.871 ms/op
                 existUser·p0.999:  6.083 ms/op
                 existUser·p0.9999: 14.992 ms/op
                 existUser·p1.00:   15.303 ms/op

Iteration   2: 2.942 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.583 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  12.522 ms/op
                 existUser·p0.9999: 18.066 ms/op
                 existUser·p1.00:   18.907 ms/op

Iteration   3: 2.960 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.412 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  6.324 ms/op
                 existUser·p0.9999: 24.415 ms/op
                 existUser·p1.00:   25.887 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326494
  mean =      2.941 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29315 
    [ 2.500,  5.000) = 296098 
    [ 5.000,  7.500) = 812 
    [ 7.500, 10.000) = 41 
    [10.000, 12.500) = 19 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.412 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.363 ms/op
     p(95.0000) =      3.543 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      6.619 ms/op
     p(99.9900) =     20.297 ms/op
     p(99.9990) =     25.756 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


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
# Warmup Iteration   1: 4.191 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.198 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.006 ms/op
Iteration   1: 3.045 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.758 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   4.588 ms/op
                 getUser·p0.999:  6.529 ms/op
                 getUser·p0.9999: 11.952 ms/op
                 getUser·p1.00:   12.239 ms/op

Iteration   2: 2.984 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.589 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.658 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  6.172 ms/op
                 getUser·p0.9999: 13.444 ms/op
                 getUser·p1.00:   15.303 ms/op

Iteration   3: 3.061 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.597 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  7.451 ms/op
                 getUser·p0.9999: 18.535 ms/op
                 getUser·p1.00:   19.694 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316820
  mean =      3.030 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 770 
    [ 1.250,  2.500) = 21535 
    [ 2.500,  3.750) = 277896 
    [ 3.750,  5.000) = 15248 
    [ 5.000,  6.250) = 939 
    [ 6.250,  7.500) = 207 
    [ 7.500,  8.750) = 65 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.589 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      6.758 ms/op
     p(99.9900) =     17.935 ms/op
     p(99.9990) =     19.491 ms/op
     p(99.9999) =     19.694 ms/op
    p(100.0000) =     19.694 ms/op


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
# Warmup Iteration   1: 5.538 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.090 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.954 ±(99.9%) 0.010 ms/op
Iteration   1: 3.947 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.153 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.862 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  12.648 ms/op
                 listUser·p0.9999: 14.038 ms/op
                 listUser·p1.00:   15.254 ms/op

Iteration   2: 3.929 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.489 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  14.627 ms/op
                 listUser·p0.9999: 19.366 ms/op
                 listUser·p1.00:   19.825 ms/op

Iteration   3: 3.961 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.010 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.857 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  16.348 ms/op
                 listUser·p0.9999: 18.579 ms/op
                 listUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243223
  mean =      3.945 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3218 
    [ 2.500,  5.000) = 218267 
    [ 5.000,  7.500) = 20394 
    [ 7.500, 10.000) = 903 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 148 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.010 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.858 ms/op
     p(95.0000) =      5.825 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     13.854 ms/op
     p(99.9900) =     18.657 ms/op
     p(99.9990) =     20.039 ms/op
     p(99.9999) =     20.283 ms/op
    p(100.0000) =     20.283 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.419 ± 1.490  ops/ms
ClientGrpc.existUser                       thrpt       3  11.027 ± 0.527  ops/ms
ClientGrpc.getUser                         thrpt       3  10.610 ± 0.859  ops/ms
ClientGrpc.listUser                        thrpt       3   8.033 ± 0.802  ops/ms
ClientGrpc.createUser                       avgt       3   2.979 ± 0.973   ms/op
ClientGrpc.existUser                        avgt       3   2.869 ± 0.266   ms/op
ClientGrpc.getUser                          avgt       3   3.008 ± 0.331   ms/op
ClientGrpc.listUser                         avgt       3   3.962 ± 0.330   ms/op
ClientGrpc.createUser                     sample  315626   3.040 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.291           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.011           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.523           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.695           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           6.865           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.416           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.775           ms/op
ClientGrpc.existUser                      sample  326494   2.941 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.412           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.916           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.363           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.543           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.619           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.297           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.887           ms/op
ClientGrpc.getUser                        sample  316820   3.030 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.589           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.019           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.523           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.768           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.506           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.758           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.935           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.694           ms/op
ClientGrpc.listUser                       sample  243223   3.945 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.010           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.793           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.858           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.825           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.930           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.854           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.657           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.283           ms/op
