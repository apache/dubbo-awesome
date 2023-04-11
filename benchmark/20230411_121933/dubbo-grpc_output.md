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
# Warmup Iteration   1: 4.757 ops/ms
# Warmup Iteration   2: 9.603 ops/ms
# Warmup Iteration   3: 10.543 ops/ms
Iteration   1: 10.642 ops/ms
Iteration   2: 10.772 ops/ms
Iteration   3: 10.608 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.674 ±(99.9%) 1.582 ops/ms [Average]
  (min, avg, max) = (10.608, 10.674, 10.772), stdev = 0.087
  CI (99.9%): [9.093, 12.256] (assumes normal distribution)


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
# Warmup Iteration   1: 7.952 ops/ms
# Warmup Iteration   2: 11.308 ops/ms
# Warmup Iteration   3: 11.418 ops/ms
Iteration   1: 11.491 ops/ms
Iteration   2: 11.468 ops/ms
Iteration   3: 11.396 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.452 ±(99.9%) 0.903 ops/ms [Average]
  (min, avg, max) = (11.396, 11.452, 11.491), stdev = 0.050
  CI (99.9%): [10.549, 12.355] (assumes normal distribution)


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
# Warmup Iteration   1: 7.897 ops/ms
# Warmup Iteration   2: 10.456 ops/ms
# Warmup Iteration   3: 10.741 ops/ms
Iteration   1: 10.813 ops/ms
Iteration   2: 10.818 ops/ms
Iteration   3: 10.621 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.751 ±(99.9%) 2.057 ops/ms [Average]
  (min, avg, max) = (10.621, 10.751, 10.818), stdev = 0.113
  CI (99.9%): [8.694, 12.808] (assumes normal distribution)


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
# Warmup Iteration   1: 6.765 ops/ms
# Warmup Iteration   2: 7.999 ops/ms
# Warmup Iteration   3: 8.256 ops/ms
Iteration   1: 8.355 ops/ms
Iteration   2: 8.484 ops/ms
Iteration   3: 8.408 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.415 ±(99.9%) 1.184 ops/ms [Average]
  (min, avg, max) = (8.355, 8.415, 8.484), stdev = 0.065
  CI (99.9%): [7.232, 9.599] (assumes normal distribution)


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
# Warmup Iteration   1: 3.836 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.061 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.003 ms/op
Iteration   1: 2.962 ±(99.9%) 0.002 ms/op
Iteration   2: 2.905 ±(99.9%) 0.002 ms/op
Iteration   3: 2.976 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.947 ±(99.9%) 0.687 ms/op [Average]
  (min, avg, max) = (2.905, 2.947, 2.976), stdev = 0.038
  CI (99.9%): [2.261, 3.634] (assumes normal distribution)


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
# Warmup Iteration   1: 3.524 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.973 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.911 ±(99.9%) 0.003 ms/op
Iteration   1: 2.826 ±(99.9%) 0.003 ms/op
Iteration   2: 2.889 ±(99.9%) 0.002 ms/op
Iteration   3: 2.874 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.863 ±(99.9%) 0.600 ms/op [Average]
  (min, avg, max) = (2.826, 2.863, 2.889), stdev = 0.033
  CI (99.9%): [2.263, 3.463] (assumes normal distribution)


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
# Warmup Iteration   1: 4.039 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.045 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.962 ±(99.9%) 0.002 ms/op
Iteration   1: 2.919 ±(99.9%) 0.002 ms/op
Iteration   2: 2.981 ±(99.9%) 0.002 ms/op
Iteration   3: 2.935 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.945 ±(99.9%) 0.586 ms/op [Average]
  (min, avg, max) = (2.919, 2.945, 2.981), stdev = 0.032
  CI (99.9%): [2.359, 3.530] (assumes normal distribution)


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
# Warmup Iteration   1: 3.929 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.975 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 3.822 ±(99.9%) 0.013 ms/op
Iteration   1: 3.832 ±(99.9%) 0.036 ms/op
Iteration   2: 3.812 ±(99.9%) 0.008 ms/op
Iteration   3: 3.802 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.815 ±(99.9%) 0.281 ms/op [Average]
  (min, avg, max) = (3.802, 3.815, 3.832), stdev = 0.015
  CI (99.9%): [3.534, 4.096] (assumes normal distribution)


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
# Warmup Iteration   1: 3.863 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.113 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.007 ms/op
Iteration   1: 2.945 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.561 ms/op
                 createUser·p0.50:   2.941 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  6.574 ms/op
                 createUser·p0.9999: 20.091 ms/op
                 createUser·p1.00:   20.447 ms/op

Iteration   2: 2.982 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.899 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.478 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   4.186 ms/op
                 createUser·p0.999:  6.527 ms/op
                 createUser·p0.9999: 13.194 ms/op
                 createUser·p1.00:   13.353 ms/op

Iteration   3: 2.987 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.662 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  7.788 ms/op
                 createUser·p0.9999: 26.126 ms/op
                 createUser·p1.00:   26.378 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 322845
  mean =      2.972 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31841 
    [ 2.500,  5.000) = 289908 
    [ 5.000,  7.500) = 818 
    [ 7.500, 10.000) = 55 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.561 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      6.652 ms/op
     p(99.9900) =     23.917 ms/op
     p(99.9990) =     26.338 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


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
# Warmup Iteration   1: 3.758 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.933 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.819 ±(99.9%) 0.005 ms/op
Iteration   1: 2.865 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.600 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.523 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  7.302 ms/op
                 existUser·p0.9999: 16.171 ms/op
                 existUser·p1.00:   16.384 ms/op

Iteration   2: 2.901 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.573 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  8.622 ms/op
                 existUser·p0.9999: 18.513 ms/op
                 existUser·p1.00:   18.743 ms/op

Iteration   3: 2.853 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.717 ms/op
                 existUser·p0.50:   2.839 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.523 ms/op
                 existUser·p0.99:   4.108 ms/op
                 existUser·p0.999:  6.169 ms/op
                 existUser·p0.9999: 14.346 ms/op
                 existUser·p1.00:   14.516 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 334083
  mean =      2.873 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2847 
    [ 1.250,  2.500) = 45357 
    [ 2.500,  3.750) = 277974 
    [ 3.750,  5.000) = 6680 
    [ 5.000,  6.250) = 659 
    [ 6.250,  7.500) = 242 
    [ 7.500,  8.750) = 118 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 35 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 54 
    [15.000, 16.250) = 39 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.573 ms/op
     p(50.0000) =      2.863 ms/op
     p(90.0000) =      3.379 ms/op
     p(95.0000) =      3.551 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      7.422 ms/op
     p(99.9900) =     16.377 ms/op
     p(99.9990) =     18.645 ms/op
     p(99.9999) =     18.743 ms/op
    p(100.0000) =     18.743 ms/op


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
# Warmup Iteration   1: 3.750 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.031 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.970 ±(99.9%) 0.006 ms/op
Iteration   1: 2.947 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.696 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.379 ms/op
                 getUser·p0.95:   3.572 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  6.250 ms/op
                 getUser·p0.9999: 14.259 ms/op
                 getUser·p1.00:   14.877 ms/op

Iteration   2: 3.008 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.558 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  7.428 ms/op
                 getUser·p0.9999: 15.282 ms/op
                 getUser·p1.00:   15.647 ms/op

Iteration   3: 2.968 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.695 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  7.340 ms/op
                 getUser·p0.9999: 24.387 ms/op
                 getUser·p1.00:   24.904 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 322499
  mean =      2.974 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31896 
    [ 2.500,  5.000) = 289525 
    [ 5.000,  7.500) = 820 
    [ 7.500, 10.000) = 117 
    [10.000, 12.500) = 13 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      7.090 ms/op
     p(99.9900) =     21.385 ms/op
     p(99.9990) =     24.758 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


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
# Warmup Iteration   1: 4.300 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.164 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.841 ±(99.9%) 0.009 ms/op
Iteration   1: 3.749 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.161 ms/op
                 listUser·p0.50:   3.604 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.374 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  12.452 ms/op
                 listUser·p0.9999: 14.179 ms/op
                 listUser·p1.00:   14.631 ms/op

Iteration   2: 3.873 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.926 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  13.913 ms/op
                 listUser·p0.9999: 18.907 ms/op
                 listUser·p1.00:   19.431 ms/op

Iteration   3: 3.840 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.010 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  14.376 ms/op
                 listUser·p0.9999: 22.872 ms/op
                 listUser·p1.00:   25.854 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 251300
  mean =      3.820 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6422 
    [ 2.500,  5.000) = 222587 
    [ 5.000,  7.500) = 21190 
    [ 7.500, 10.000) = 637 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 217 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.926 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.899 ms/op
     p(95.0000) =      5.521 ms/op
     p(99.0000) =      6.693 ms/op
     p(99.9000) =     13.353 ms/op
     p(99.9900) =     22.606 ms/op
     p(99.9990) =     23.953 ms/op
     p(99.9999) =     25.854 ms/op
    p(100.0000) =     25.854 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.674 ± 1.582  ops/ms
ClientGrpc.existUser                       thrpt       3  11.452 ± 0.903  ops/ms
ClientGrpc.getUser                         thrpt       3  10.751 ± 2.057  ops/ms
ClientGrpc.listUser                        thrpt       3   8.415 ± 1.184  ops/ms
ClientGrpc.createUser                       avgt       3   2.947 ± 0.687   ms/op
ClientGrpc.existUser                        avgt       3   2.863 ± 0.600   ms/op
ClientGrpc.getUser                          avgt       3   2.945 ± 0.586   ms/op
ClientGrpc.listUser                         avgt       3   3.815 ± 0.281   ms/op
ClientGrpc.createUser                     sample  322845   2.972 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.561           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.949           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.510           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.723           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.309           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           6.652           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.917           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.378           ms/op
ClientGrpc.existUser                      sample  334083   2.873 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.573           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.863           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.379           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.551           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.276           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.422           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.377           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.743           ms/op
ClientGrpc.getUser                        sample  322499   2.974 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.558           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.974           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.506           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.740           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.383           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.090           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.385           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.904           ms/op
ClientGrpc.listUser                       sample  251300   3.820 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.926           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.678           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.899           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.521           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.693           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.353           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.606           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.854           ms/op
