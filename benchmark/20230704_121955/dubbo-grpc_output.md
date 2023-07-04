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
# Warmup Iteration   1: 4.441 ops/ms
# Warmup Iteration   2: 9.779 ops/ms
# Warmup Iteration   3: 10.425 ops/ms
Iteration   1: 10.639 ops/ms
Iteration   2: 10.786 ops/ms
Iteration   3: 10.773 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.732 ±(99.9%) 1.488 ops/ms [Average]
  (min, avg, max) = (10.639, 10.732, 10.786), stdev = 0.082
  CI (99.9%): [9.245, 12.220] (assumes normal distribution)


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
# Warmup Iteration   1: 8.675 ops/ms
# Warmup Iteration   2: 10.582 ops/ms
# Warmup Iteration   3: 10.900 ops/ms
Iteration   1: 11.291 ops/ms
Iteration   2: 11.377 ops/ms
Iteration   3: 11.273 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.314 ±(99.9%) 1.010 ops/ms [Average]
  (min, avg, max) = (11.273, 11.314, 11.377), stdev = 0.055
  CI (99.9%): [10.304, 12.324] (assumes normal distribution)


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
# Warmup Iteration   1: 7.734 ops/ms
# Warmup Iteration   2: 10.057 ops/ms
# Warmup Iteration   3: 10.531 ops/ms
Iteration   1: 10.575 ops/ms
Iteration   2: 10.885 ops/ms
Iteration   3: 10.520 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.660 ±(99.9%) 3.594 ops/ms [Average]
  (min, avg, max) = (10.520, 10.660, 10.885), stdev = 0.197
  CI (99.9%): [7.066, 14.254] (assumes normal distribution)


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
# Warmup Iteration   1: 6.257 ops/ms
# Warmup Iteration   2: 8.455 ops/ms
# Warmup Iteration   3: 8.363 ops/ms
Iteration   1: 8.347 ops/ms
Iteration   2: 8.433 ops/ms
Iteration   3: 8.267 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.349 ±(99.9%) 1.515 ops/ms [Average]
  (min, avg, max) = (8.267, 8.349, 8.433), stdev = 0.083
  CI (99.9%): [6.834, 9.863] (assumes normal distribution)


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
# Warmup Iteration   1: 4.177 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.104 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.941 ±(99.9%) 0.004 ms/op
Iteration   1: 2.939 ±(99.9%) 0.003 ms/op
Iteration   2: 2.987 ±(99.9%) 0.004 ms/op
Iteration   3: 2.929 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.952 ±(99.9%) 0.559 ms/op [Average]
  (min, avg, max) = (2.929, 2.952, 2.987), stdev = 0.031
  CI (99.9%): [2.393, 3.511] (assumes normal distribution)


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
# Warmup Iteration   1: 3.524 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.961 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.802 ±(99.9%) 0.004 ms/op
Iteration   1: 2.902 ±(99.9%) 0.003 ms/op
Iteration   2: 2.932 ±(99.9%) 0.002 ms/op
Iteration   3: 2.909 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.914 ±(99.9%) 0.291 ms/op [Average]
  (min, avg, max) = (2.902, 2.914, 2.932), stdev = 0.016
  CI (99.9%): [2.623, 3.206] (assumes normal distribution)


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
# Warmup Iteration   1: 3.913 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.062 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.968 ±(99.9%) 0.003 ms/op
Iteration   1: 2.988 ±(99.9%) 0.002 ms/op
Iteration   2: 2.958 ±(99.9%) 0.004 ms/op
Iteration   3: 2.937 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.961 ±(99.9%) 0.465 ms/op [Average]
  (min, avg, max) = (2.937, 2.961, 2.988), stdev = 0.025
  CI (99.9%): [2.496, 3.426] (assumes normal distribution)


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
# Warmup Iteration   1: 4.843 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.885 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.818 ±(99.9%) 0.036 ms/op
Iteration   1: 3.742 ±(99.9%) 0.015 ms/op
Iteration   2: 3.838 ±(99.9%) 0.050 ms/op
Iteration   3: 3.798 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.793 ±(99.9%) 0.877 ms/op [Average]
  (min, avg, max) = (3.742, 3.793, 3.838), stdev = 0.048
  CI (99.9%): [2.915, 4.670] (assumes normal distribution)


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
# Warmup Iteration   1: 4.110 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.180 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.097 ±(99.9%) 0.006 ms/op
Iteration   1: 3.038 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.873 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.709 ms/op
                 createUser·p0.99:   4.202 ms/op
                 createUser·p0.999:  6.223 ms/op
                 createUser·p0.9999: 11.321 ms/op
                 createUser·p1.00:   11.796 ms/op

Iteration   2: 3.028 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.767 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.695 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  8.739 ms/op
                 createUser·p0.9999: 18.987 ms/op
                 createUser·p1.00:   19.431 ms/op

Iteration   3: 3.030 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.614 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  7.535 ms/op
                 createUser·p0.9999: 15.519 ms/op
                 createUser·p1.00:   16.466 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316563
  mean =      3.032 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 695 
    [ 1.250,  2.500) = 22489 
    [ 2.500,  3.750) = 278899 
    [ 3.750,  5.000) = 13451 
    [ 5.000,  6.250) = 483 
    [ 6.250,  7.500) = 187 
    [ 7.500,  8.750) = 127 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.614 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      7.881 ms/op
     p(99.9900) =     17.535 ms/op
     p(99.9990) =     19.328 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.770 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.892 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.866 ±(99.9%) 0.007 ms/op
Iteration   1: 2.812 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.479 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.252 ms/op
                 existUser·p0.95:   3.424 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  6.179 ms/op
                 existUser·p0.9999: 15.198 ms/op
                 existUser·p1.00:   15.516 ms/op

Iteration   2: 2.867 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.526 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.506 ms/op
                 existUser·p0.999:  7.037 ms/op
                 existUser·p0.9999: 19.530 ms/op
                 existUser·p1.00:   20.611 ms/op

Iteration   3: 2.830 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.709 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.444 ms/op
                 existUser·p0.999:  6.716 ms/op
                 existUser·p0.9999: 18.241 ms/op
                 existUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 338413
  mean =      2.836 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 54046 
    [ 2.500,  5.000) = 283281 
    [ 5.000,  7.500) = 853 
    [ 7.500, 10.000) = 73 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.479 ms/op
     p(50.0000) =      2.859 ms/op
     p(90.0000) =      3.330 ms/op
     p(95.0000) =      3.568 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      6.771 ms/op
     p(99.9900) =     18.335 ms/op
     p(99.9990) =     19.615 ms/op
     p(99.9999) =     20.611 ms/op
    p(100.0000) =     20.611 ms/op


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
# Warmup Iteration   1: 4.051 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.044 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.006 ms/op
Iteration   1: 2.982 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.578 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  6.508 ms/op
                 getUser·p0.9999: 12.297 ms/op
                 getUser·p1.00:   12.583 ms/op

Iteration   2: 3.025 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.641 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  6.896 ms/op
                 getUser·p0.9999: 13.032 ms/op
                 getUser·p1.00:   14.664 ms/op

Iteration   3: 3.021 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.788 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  6.850 ms/op
                 getUser·p0.9999: 23.181 ms/op
                 getUser·p1.00:   25.330 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318901
  mean =      3.009 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28261 
    [ 2.500,  5.000) = 289572 
    [ 5.000,  7.500) = 808 
    [ 7.500, 10.000) = 39 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.578 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      6.792 ms/op
     p(99.9900) =     22.482 ms/op
     p(99.9990) =     23.515 ms/op
     p(99.9999) =     25.330 ms/op
    p(100.0000) =     25.330 ms/op


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
# Warmup Iteration   1: 5.090 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.910 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.742 ±(99.9%) 0.008 ms/op
Iteration   1: 3.822 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.848 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.439 ms/op
                 listUser·p0.99:   6.644 ms/op
                 listUser·p0.999:  11.977 ms/op
                 listUser·p0.9999: 14.852 ms/op
                 listUser·p1.00:   16.679 ms/op

Iteration   2: 3.841 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.241 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   5.423 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  13.086 ms/op
                 listUser·p0.9999: 16.040 ms/op
                 listUser·p1.00:   16.384 ms/op

Iteration   3: 3.809 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.834 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.768 ms/op
                 listUser·p0.95:   5.226 ms/op
                 listUser·p0.99:   6.472 ms/op
                 listUser·p0.999:  13.091 ms/op
                 listUser·p0.9999: 16.159 ms/op
                 listUser·p1.00:   16.810 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 251163
  mean =      3.824 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 31 
    [ 1.250,  2.500) = 4360 
    [ 2.500,  3.750) = 135904 
    [ 3.750,  5.000) = 93086 
    [ 5.000,  6.250) = 13411 
    [ 6.250,  7.500) = 3238 
    [ 7.500,  8.750) = 456 
    [ 8.750, 10.000) = 141 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 146 
    [12.500, 13.750) = 187 
    [13.750, 15.000) = 57 
    [15.000, 16.250) = 54 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.834 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.678 ms/op
     p(95.0000) =      5.358 ms/op
     p(99.0000) =      6.685 ms/op
     p(99.9000) =     12.894 ms/op
     p(99.9900) =     15.925 ms/op
     p(99.9990) =     16.711 ms/op
     p(99.9999) =     16.810 ms/op
    p(100.0000) =     16.810 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.732 ± 1.488  ops/ms
ClientGrpc.existUser                       thrpt       3  11.314 ± 1.010  ops/ms
ClientGrpc.getUser                         thrpt       3  10.660 ± 3.594  ops/ms
ClientGrpc.listUser                        thrpt       3   8.349 ± 1.515  ops/ms
ClientGrpc.createUser                       avgt       3   2.952 ± 0.559   ms/op
ClientGrpc.existUser                        avgt       3   2.914 ± 0.291   ms/op
ClientGrpc.getUser                          avgt       3   2.961 ± 0.465   ms/op
ClientGrpc.listUser                         avgt       3   3.793 ± 0.877   ms/op
ClientGrpc.createUser                     sample  316563   3.032 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.614           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.011           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.535           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.723           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.881           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.535           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.431           ms/op
ClientGrpc.existUser                      sample  338413   2.836 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.479           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.859           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.330           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.568           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.440           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.771           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.335           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.611           ms/op
ClientGrpc.getUser                        sample  318901   3.009 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.578           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.994           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.572           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.768           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.383           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.792           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.482           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.330           ms/op
ClientGrpc.listUser                       sample  251163   3.824 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.834           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.690           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.678           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.358           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.685           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.894           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          15.925           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          16.810           ms/op
