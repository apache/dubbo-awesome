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
# Warmup Iteration   1: 4.878 ops/ms
# Warmup Iteration   2: 9.738 ops/ms
# Warmup Iteration   3: 10.560 ops/ms
Iteration   1: 10.764 ops/ms
Iteration   2: 10.770 ops/ms
Iteration   3: 10.703 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.746 ±(99.9%) 0.683 ops/ms [Average]
  (min, avg, max) = (10.703, 10.746, 10.770), stdev = 0.037
  CI (99.9%): [10.063, 11.428] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.460 ops/ms
# Warmup Iteration   2: 11.280 ops/ms
# Warmup Iteration   3: 11.428 ops/ms
Iteration   1: 11.408 ops/ms
Iteration   2: 11.443 ops/ms
Iteration   3: 11.401 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.417 ±(99.9%) 0.405 ops/ms [Average]
  (min, avg, max) = (11.401, 11.417, 11.443), stdev = 0.022
  CI (99.9%): [11.012, 11.822] (assumes normal distribution)


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
# Warmup Iteration   1: 8.289 ops/ms
# Warmup Iteration   2: 10.378 ops/ms
# Warmup Iteration   3: 10.720 ops/ms
Iteration   1: 10.866 ops/ms
Iteration   2: 10.974 ops/ms
Iteration   3: 10.857 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.899 ±(99.9%) 1.184 ops/ms [Average]
  (min, avg, max) = (10.857, 10.899, 10.974), stdev = 0.065
  CI (99.9%): [9.715, 12.083] (assumes normal distribution)


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
# Warmup Iteration   1: 5.784 ops/ms
# Warmup Iteration   2: 8.000 ops/ms
# Warmup Iteration   3: 8.149 ops/ms
Iteration   1: 8.066 ops/ms
Iteration   2: 8.130 ops/ms
Iteration   3: 8.143 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.113 ±(99.9%) 0.751 ops/ms [Average]
  (min, avg, max) = (8.066, 8.113, 8.143), stdev = 0.041
  CI (99.9%): [7.362, 8.863] (assumes normal distribution)


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
# Warmup Iteration   1: 3.932 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.062 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.983 ±(99.9%) 0.006 ms/op
Iteration   1: 2.959 ±(99.9%) 0.003 ms/op
Iteration   2: 3.017 ±(99.9%) 0.002 ms/op
Iteration   3: 2.960 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.979 ±(99.9%) 0.606 ms/op [Average]
  (min, avg, max) = (2.959, 2.979, 3.017), stdev = 0.033
  CI (99.9%): [2.373, 3.584] (assumes normal distribution)


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
# Warmup Iteration   1: 3.734 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.840 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.820 ±(99.9%) 0.005 ms/op
Iteration   1: 2.808 ±(99.9%) 0.003 ms/op
Iteration   2: 2.843 ±(99.9%) 0.005 ms/op
Iteration   3: 2.825 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.825 ±(99.9%) 0.318 ms/op [Average]
  (min, avg, max) = (2.808, 2.825, 2.843), stdev = 0.017
  CI (99.9%): [2.507, 3.144] (assumes normal distribution)


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
# Warmup Iteration   1: 3.915 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.004 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.989 ±(99.9%) 0.003 ms/op
Iteration   1: 2.914 ±(99.9%) 0.002 ms/op
Iteration   2: 2.957 ±(99.9%) 0.002 ms/op
Iteration   3: 2.945 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.938 ±(99.9%) 0.406 ms/op [Average]
  (min, avg, max) = (2.914, 2.938, 2.957), stdev = 0.022
  CI (99.9%): [2.532, 3.345] (assumes normal distribution)


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
# Warmup Iteration   1: 4.257 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.889 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.835 ±(99.9%) 0.014 ms/op
Iteration   1: 3.855 ±(99.9%) 0.011 ms/op
Iteration   2: 3.830 ±(99.9%) 0.006 ms/op
Iteration   3: 3.868 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.851 ±(99.9%) 0.356 ms/op [Average]
  (min, avg, max) = (3.830, 3.851, 3.868), stdev = 0.020
  CI (99.9%): [3.495, 4.207] (assumes normal distribution)


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
# Warmup Iteration   1: 3.854 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.062 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.950 ±(99.9%) 0.007 ms/op
Iteration   1: 2.968 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.439 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  7.949 ms/op
                 createUser·p0.9999: 15.939 ms/op
                 createUser·p1.00:   16.335 ms/op

Iteration   2: 3.007 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.516 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  9.038 ms/op
                 createUser·p0.9999: 18.329 ms/op
                 createUser·p1.00:   18.711 ms/op

Iteration   3: 2.931 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.731 ms/op
                 createUser·p0.50:   2.920 ms/op
                 createUser·p0.90:   3.273 ms/op
                 createUser·p0.95:   3.428 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  8.978 ms/op
                 createUser·p0.9999: 29.426 ms/op
                 createUser·p1.00:   29.819 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 323351
  mean =      2.969 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31634 
    [ 2.500,  5.000) = 290335 
    [ 5.000,  7.500) = 970 
    [ 7.500, 10.000) = 165 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.439 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      8.798 ms/op
     p(99.9900) =     24.462 ms/op
     p(99.9990) =     29.721 ms/op
     p(99.9999) =     29.819 ms/op
    p(100.0000) =     29.819 ms/op


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
# Warmup Iteration   1: 3.716 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.912 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.873 ±(99.9%) 0.006 ms/op
Iteration   1: 2.888 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.506 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  6.054 ms/op
                 existUser·p0.9999: 16.350 ms/op
                 existUser·p1.00:   16.564 ms/op

Iteration   2: 2.834 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.487 ms/op
                 existUser·p0.50:   2.826 ms/op
                 existUser·p0.90:   3.203 ms/op
                 existUser·p0.95:   3.441 ms/op
                 existUser·p0.99:   4.465 ms/op
                 existUser·p0.999:  5.597 ms/op
                 existUser·p0.9999: 22.479 ms/op
                 existUser·p1.00:   22.872 ms/op

Iteration   3: 2.850 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.614 ms/op
                 existUser·p0.50:   2.826 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   4.604 ms/op
                 existUser·p0.999:  6.673 ms/op
                 existUser·p0.9999: 16.524 ms/op
                 existUser·p1.00:   16.941 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 335834
  mean =      2.857 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55033 
    [ 2.500,  5.000) = 279767 
    [ 5.000,  7.500) = 821 
    [ 7.500, 10.000) = 53 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.487 ms/op
     p(50.0000) =      2.847 ms/op
     p(90.0000) =      3.396 ms/op
     p(95.0000) =      3.621 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      6.129 ms/op
     p(99.9900) =     21.884 ms/op
     p(99.9990) =     22.795 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


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
# Warmup Iteration   1: 3.874 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.996 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.970 ±(99.9%) 0.006 ms/op
Iteration   1: 2.923 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.501 ms/op
                 getUser·p0.50:   2.920 ms/op
                 getUser·p0.90:   3.391 ms/op
                 getUser·p0.95:   3.645 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  6.878 ms/op
                 getUser·p0.9999: 19.073 ms/op
                 getUser·p1.00:   19.399 ms/op

Iteration   2: 2.935 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.528 ms/op
                 getUser·p0.50:   2.945 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  7.298 ms/op
                 getUser·p0.9999: 15.796 ms/op
                 getUser·p1.00:   16.515 ms/op

Iteration   3: 2.982 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.469 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.641 ms/op
                 getUser·p0.99:   4.088 ms/op
                 getUser·p0.999:  6.087 ms/op
                 getUser·p0.9999: 24.224 ms/op
                 getUser·p1.00:   24.543 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 325965
  mean =      2.946 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29766 
    [ 2.500,  5.000) = 295131 
    [ 5.000,  7.500) = 824 
    [ 7.500, 10.000) = 79 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.469 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.662 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      6.881 ms/op
     p(99.9900) =     20.535 ms/op
     p(99.9990) =     24.428 ms/op
     p(99.9999) =     24.543 ms/op
    p(100.0000) =     24.543 ms/op


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
# Warmup Iteration   1: 4.578 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.993 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.906 ±(99.9%) 0.011 ms/op
Iteration   1: 3.837 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.956 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  12.795 ms/op
                 listUser·p0.9999: 15.144 ms/op
                 listUser·p1.00:   15.450 ms/op

Iteration   2: 3.845 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.819 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  14.940 ms/op
                 listUser·p0.9999: 17.346 ms/op
                 listUser·p1.00:   17.727 ms/op

Iteration   3: 3.936 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.826 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  17.433 ms/op
                 listUser·p0.9999: 20.509 ms/op
                 listUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247925
  mean =      3.872 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5347 
    [ 2.500,  5.000) = 217550 
    [ 5.000,  7.500) = 23663 
    [ 7.500, 10.000) = 806 
    [10.000, 12.500) = 164 
    [12.500, 15.000) = 210 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.819 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      5.014 ms/op
     p(95.0000) =      5.538 ms/op
     p(99.0000) =      6.873 ms/op
     p(99.9000) =     14.272 ms/op
     p(99.9900) =     19.242 ms/op
     p(99.9990) =     20.906 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.746 ± 0.683  ops/ms
ClientGrpc.existUser                       thrpt       3  11.417 ± 0.405  ops/ms
ClientGrpc.getUser                         thrpt       3  10.899 ± 1.184  ops/ms
ClientGrpc.listUser                        thrpt       3   8.113 ± 0.751  ops/ms
ClientGrpc.createUser                       avgt       3   2.979 ± 0.606   ms/op
ClientGrpc.existUser                        avgt       3   2.825 ± 0.318   ms/op
ClientGrpc.getUser                          avgt       3   2.938 ± 0.406   ms/op
ClientGrpc.listUser                         avgt       3   3.851 ± 0.356   ms/op
ClientGrpc.createUser                     sample  323351   2.969 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.439           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.953           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.510           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.744           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.383           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.798           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.462           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.819           ms/op
ClientGrpc.existUser                      sample  335834   2.857 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.487           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.847           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.396           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.621           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.489           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.129           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.884           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.872           ms/op
ClientGrpc.getUser                        sample  325965   2.946 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.469           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.941           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.441           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.662           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.202           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.881           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.535           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.543           ms/op
ClientGrpc.listUser                       sample  247925   3.872 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.819           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.719           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.014           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.538           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.873           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.272           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.242           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.004           ms/op
