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
# Warmup Iteration   1: 4.595 ops/ms
# Warmup Iteration   2: 9.041 ops/ms
# Warmup Iteration   3: 9.978 ops/ms
Iteration   1: 10.354 ops/ms
Iteration   2: 10.491 ops/ms
Iteration   3: 10.736 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.527 ±(99.9%) 3.524 ops/ms [Average]
  (min, avg, max) = (10.354, 10.527, 10.736), stdev = 0.193
  CI (99.9%): [7.003, 14.051] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.774 ops/ms
# Warmup Iteration   2: 10.528 ops/ms
# Warmup Iteration   3: 10.851 ops/ms
Iteration   1: 11.022 ops/ms
Iteration   2: 10.960 ops/ms
Iteration   3: 11.105 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.029 ±(99.9%) 1.331 ops/ms [Average]
  (min, avg, max) = (10.960, 11.029, 11.105), stdev = 0.073
  CI (99.9%): [9.698, 12.360] (assumes normal distribution)


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
# Warmup Iteration   1: 7.156 ops/ms
# Warmup Iteration   2: 10.210 ops/ms
# Warmup Iteration   3: 10.516 ops/ms
Iteration   1: 10.572 ops/ms
Iteration   2: 10.557 ops/ms
Iteration   3: 10.436 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.522 ±(99.9%) 1.366 ops/ms [Average]
  (min, avg, max) = (10.436, 10.522, 10.572), stdev = 0.075
  CI (99.9%): [9.156, 11.887] (assumes normal distribution)


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
# Warmup Iteration   1: 5.611 ops/ms
# Warmup Iteration   2: 7.869 ops/ms
# Warmup Iteration   3: 8.212 ops/ms
Iteration   1: 8.254 ops/ms
Iteration   2: 8.344 ops/ms
Iteration   3: 8.324 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.307 ±(99.9%) 0.859 ops/ms [Average]
  (min, avg, max) = (8.254, 8.307, 8.344), stdev = 0.047
  CI (99.9%): [7.449, 9.166] (assumes normal distribution)


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
# Warmup Iteration   1: 4.029 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.146 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.003 ms/op
Iteration   1: 3.053 ±(99.9%) 0.002 ms/op
Iteration   2: 3.024 ±(99.9%) 0.003 ms/op
Iteration   3: 3.031 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.036 ±(99.9%) 0.280 ms/op [Average]
  (min, avg, max) = (3.024, 3.036, 3.053), stdev = 0.015
  CI (99.9%): [2.757, 3.316] (assumes normal distribution)


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
# Warmup Iteration   1: 3.646 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.975 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.945 ±(99.9%) 0.003 ms/op
Iteration   1: 2.943 ±(99.9%) 0.003 ms/op
Iteration   2: 2.904 ±(99.9%) 0.004 ms/op
Iteration   3: 2.885 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.911 ±(99.9%) 0.535 ms/op [Average]
  (min, avg, max) = (2.885, 2.911, 2.943), stdev = 0.029
  CI (99.9%): [2.375, 3.446] (assumes normal distribution)


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
# Warmup Iteration   1: 3.902 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.130 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.031 ±(99.9%) 0.016 ms/op
Iteration   1: 3.048 ±(99.9%) 0.003 ms/op
Iteration   2: 3.014 ±(99.9%) 0.004 ms/op
Iteration   3: 3.004 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.022 ±(99.9%) 0.414 ms/op [Average]
  (min, avg, max) = (3.004, 3.022, 3.048), stdev = 0.023
  CI (99.9%): [2.608, 3.436] (assumes normal distribution)


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
# Warmup Iteration   1: 5.282 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.980 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.911 ±(99.9%) 0.009 ms/op
Iteration   1: 3.883 ±(99.9%) 0.035 ms/op
Iteration   2: 3.821 ±(99.9%) 0.011 ms/op
Iteration   3: 3.913 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.872 ±(99.9%) 0.854 ms/op [Average]
  (min, avg, max) = (3.821, 3.872, 3.913), stdev = 0.047
  CI (99.9%): [3.018, 4.726] (assumes normal distribution)


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
# Warmup Iteration   1: 4.159 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.193 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.006 ms/op
Iteration   1: 3.039 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.660 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   4.719 ms/op
                 createUser·p0.999:  10.367 ms/op
                 createUser·p0.9999: 13.041 ms/op
                 createUser·p1.00:   13.468 ms/op

Iteration   2: 3.048 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.767 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.547 ms/op
                 createUser·p0.999:  8.053 ms/op
                 createUser·p0.9999: 13.214 ms/op
                 createUser·p1.00:   13.418 ms/op

Iteration   3: 3.111 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.558 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   4.940 ms/op
                 createUser·p0.999:  22.689 ms/op
                 createUser·p0.9999: 34.191 ms/op
                 createUser·p1.00:   35.193 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313015
  mean =      3.066 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27810 
    [ 2.500,  5.000) = 283122 
    [ 5.000,  7.500) = 1331 
    [ 7.500, 10.000) = 157 
    [10.000, 12.500) = 204 
    [12.500, 15.000) = 153 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.899 ms/op
     p(99.0000) =      4.719 ms/op
     p(99.9000) =     13.418 ms/op
     p(99.9900) =     30.366 ms/op
     p(99.9990) =     35.053 ms/op
     p(99.9999) =     35.193 ms/op
    p(100.0000) =     35.193 ms/op


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
# Warmup Iteration   1: 4.198 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.236 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.084 ±(99.9%) 0.017 ms/op
Iteration   1: 3.311 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.705 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   3.867 ms/op
                 existUser·p0.99:   19.682 ms/op
                 existUser·p0.999:  29.402 ms/op
                 existUser·p0.9999: 35.583 ms/op
                 existUser·p1.00:   40.305 ms/op

Iteration   2: 3.042 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.528 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   13.297 ms/op
                 existUser·p0.999:  26.968 ms/op
                 existUser·p0.9999: 36.470 ms/op
                 existUser·p1.00:   42.729 ms/op

Iteration   3: 3.198 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.687 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   21.758 ms/op
                 existUser·p0.999:  30.016 ms/op
                 existUser·p0.9999: 33.260 ms/op
                 existUser·p1.00:   38.142 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 301853
  mean =      3.180 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 295313 
    [ 5.000, 10.000) = 1864 
    [10.000, 15.000) = 921 
    [15.000, 20.000) = 1119 
    [20.000, 25.000) = 1604 
    [25.000, 30.000) = 805 
    [30.000, 35.000) = 197 
    [35.000, 40.000) = 23 
    [40.000, 45.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.528 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =     18.153 ms/op
     p(99.9000) =     28.967 ms/op
     p(99.9900) =     35.050 ms/op
     p(99.9990) =     42.594 ms/op
     p(99.9999) =     42.729 ms/op
    p(100.0000) =     42.729 ms/op


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
# Warmup Iteration   1: 4.099 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.116 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.006 ms/op
Iteration   1: 3.039 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.889 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  10.813 ms/op
                 getUser·p0.9999: 12.780 ms/op
                 getUser·p1.00:   13.009 ms/op

Iteration   2: 3.043 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.698 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.699 ms/op
                 getUser·p0.99:   4.339 ms/op
                 getUser·p0.999:  8.362 ms/op
                 getUser·p0.9999: 14.294 ms/op
                 getUser·p1.00:   14.729 ms/op

Iteration   3: 3.021 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.778 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  6.031 ms/op
                 getUser·p0.9999: 16.332 ms/op
                 getUser·p1.00:   16.744 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316300
  mean =      3.034 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 807 
    [ 1.250,  2.500) = 18236 
    [ 2.500,  3.750) = 281809 
    [ 3.750,  5.000) = 13969 
    [ 5.000,  6.250) = 951 
    [ 6.250,  7.500) = 204 
    [ 7.500,  8.750) = 43 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 49 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 63 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.698 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      7.641 ms/op
     p(99.9900) =     14.801 ms/op
     p(99.9990) =     16.594 ms/op
     p(99.9999) =     16.744 ms/op
    p(100.0000) =     16.744 ms/op


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
# Warmup Iteration   1: 5.371 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.939 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.829 ±(99.9%) 0.011 ms/op
Iteration   1: 3.833 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.108 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.529 ms/op
                 listUser·p0.999:  22.053 ms/op
                 listUser·p0.9999: 34.275 ms/op
                 listUser·p1.00:   34.603 ms/op

Iteration   2: 3.868 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.186 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  13.359 ms/op
                 listUser·p0.9999: 20.414 ms/op
                 listUser·p1.00:   20.840 ms/op

Iteration   3: 3.841 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.245 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   6.712 ms/op
                 listUser·p0.999:  15.102 ms/op
                 listUser·p0.9999: 27.173 ms/op
                 listUser·p1.00:   28.312 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249373
  mean =      3.847 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4931 
    [ 2.500,  5.000) = 224813 
    [ 5.000,  7.500) = 18554 
    [ 7.500, 10.000) = 556 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 141 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.108 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.719 ms/op
     p(95.0000) =      5.579 ms/op
     p(99.0000) =      6.636 ms/op
     p(99.9000) =     15.516 ms/op
     p(99.9900) =     30.970 ms/op
     p(99.9990) =     34.538 ms/op
     p(99.9999) =     34.603 ms/op
    p(100.0000) =     34.603 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.527 ± 3.524  ops/ms
ClientGrpc.existUser                       thrpt       3  11.029 ± 1.331  ops/ms
ClientGrpc.getUser                         thrpt       3  10.522 ± 1.366  ops/ms
ClientGrpc.listUser                        thrpt       3   8.307 ± 0.859  ops/ms
ClientGrpc.createUser                       avgt       3   3.036 ± 0.280   ms/op
ClientGrpc.existUser                        avgt       3   2.911 ± 0.535   ms/op
ClientGrpc.getUser                          avgt       3   3.022 ± 0.414   ms/op
ClientGrpc.listUser                         avgt       3   3.872 ± 0.854   ms/op
ClientGrpc.createUser                     sample  313015   3.066 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.558           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.019           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.633           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.899           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.719           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.418           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          30.366           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          35.193           ms/op
ClientGrpc.existUser                      sample  301853   3.180 ± 0.014   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.528           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.912           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.486           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.826           ms/op
ClientGrpc.existUser:existUser·p0.99      sample          18.153           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          28.967           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          35.050           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          42.729           ms/op
ClientGrpc.getUser                        sample  316300   3.034 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.698           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.015           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.539           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.744           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.383           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.641           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.801           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.744           ms/op
ClientGrpc.listUser                       sample  249373   3.847 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.108           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.699           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.719           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.579           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.636           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.516           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.970           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.603           ms/op
