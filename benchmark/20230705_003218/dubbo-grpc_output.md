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
# Warmup Iteration   1: 4.443 ops/ms
# Warmup Iteration   2: 9.293 ops/ms
# Warmup Iteration   3: 10.359 ops/ms
Iteration   1: 10.397 ops/ms
Iteration   2: 10.594 ops/ms
Iteration   3: 10.837 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.609 ±(99.9%) 4.019 ops/ms [Average]
  (min, avg, max) = (10.397, 10.609, 10.837), stdev = 0.220
  CI (99.9%): [6.591, 14.628] (assumes normal distribution)


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
# Warmup Iteration   1: 7.360 ops/ms
# Warmup Iteration   2: 10.600 ops/ms
# Warmup Iteration   3: 11.029 ops/ms
Iteration   1: 11.267 ops/ms
Iteration   2: 11.256 ops/ms
Iteration   3: 11.000 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.174 ±(99.9%) 2.755 ops/ms [Average]
  (min, avg, max) = (11.000, 11.174, 11.267), stdev = 0.151
  CI (99.9%): [8.419, 13.929] (assumes normal distribution)


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
# Warmup Iteration   1: 7.038 ops/ms
# Warmup Iteration   2: 10.059 ops/ms
# Warmup Iteration   3: 10.462 ops/ms
Iteration   1: 10.483 ops/ms
Iteration   2: 10.579 ops/ms
Iteration   3: 10.621 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.561 ±(99.9%) 1.293 ops/ms [Average]
  (min, avg, max) = (10.483, 10.561, 10.621), stdev = 0.071
  CI (99.9%): [9.268, 11.854] (assumes normal distribution)


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
# Warmup Iteration   1: 5.891 ops/ms
# Warmup Iteration   2: 7.885 ops/ms
# Warmup Iteration   3: 7.911 ops/ms
Iteration   1: 8.070 ops/ms
Iteration   2: 8.158 ops/ms
Iteration   3: 8.042 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.090 ±(99.9%) 1.105 ops/ms [Average]
  (min, avg, max) = (8.042, 8.090, 8.158), stdev = 0.061
  CI (99.9%): [6.985, 9.195] (assumes normal distribution)


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
# Warmup Iteration   1: 4.266 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.173 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.003 ms/op
Iteration   1: 3.037 ±(99.9%) 0.003 ms/op
Iteration   2: 3.002 ±(99.9%) 0.003 ms/op
Iteration   3: 2.986 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.008 ±(99.9%) 0.473 ms/op [Average]
  (min, avg, max) = (2.986, 3.008, 3.037), stdev = 0.026
  CI (99.9%): [2.535, 3.482] (assumes normal distribution)


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
# Warmup Iteration   1: 3.951 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.996 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.938 ±(99.9%) 0.002 ms/op
Iteration   1: 2.904 ±(99.9%) 0.002 ms/op
Iteration   2: 2.909 ±(99.9%) 0.003 ms/op
Iteration   3: 2.879 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.897 ±(99.9%) 0.295 ms/op [Average]
  (min, avg, max) = (2.879, 2.897, 2.909), stdev = 0.016
  CI (99.9%): [2.603, 3.192] (assumes normal distribution)


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
# Warmup Iteration   1: 4.244 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.133 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.003 ms/op
Iteration   1: 3.041 ±(99.9%) 0.004 ms/op
Iteration   2: 3.006 ±(99.9%) 0.003 ms/op
Iteration   3: 2.992 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.013 ±(99.9%) 0.455 ms/op [Average]
  (min, avg, max) = (2.992, 3.013, 3.041), stdev = 0.025
  CI (99.9%): [2.558, 3.468] (assumes normal distribution)


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
# Warmup Iteration   1: 4.803 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.118 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.958 ±(99.9%) 0.009 ms/op
Iteration   1: 3.932 ±(99.9%) 0.013 ms/op
Iteration   2: 3.907 ±(99.9%) 0.009 ms/op
Iteration   3: 3.941 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.927 ±(99.9%) 0.315 ms/op [Average]
  (min, avg, max) = (3.907, 3.927, 3.941), stdev = 0.017
  CI (99.9%): [3.612, 4.241] (assumes normal distribution)


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
# Warmup Iteration   1: 4.311 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.165 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.007 ms/op
Iteration   1: 2.989 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.660 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.641 ms/op
                 createUser·p0.99:   4.661 ms/op
                 createUser·p0.999:  9.290 ms/op
                 createUser·p0.9999: 17.367 ms/op
                 createUser·p1.00:   17.629 ms/op

Iteration   2: 2.962 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.732 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.428 ms/op
                 createUser·p0.95:   3.641 ms/op
                 createUser·p0.99:   4.604 ms/op
                 createUser·p0.999:  8.216 ms/op
                 createUser·p0.9999: 18.166 ms/op
                 createUser·p1.00:   18.907 ms/op

Iteration   3: 3.015 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.719 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.650 ms/op
                 createUser·p0.99:   4.547 ms/op
                 createUser·p0.999:  9.758 ms/op
                 createUser·p0.9999: 31.802 ms/op
                 createUser·p1.00:   32.866 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321233
  mean =      2.988 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28868 
    [ 2.500,  5.000) = 290569 
    [ 5.000,  7.500) = 1389 
    [ 7.500, 10.000) = 123 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 128 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.645 ms/op
     p(99.0000) =      4.612 ms/op
     p(99.9000) =      9.322 ms/op
     p(99.9900) =     29.184 ms/op
     p(99.9990) =     32.604 ms/op
     p(99.9999) =     32.866 ms/op
    p(100.0000) =     32.866 ms/op


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
# Warmup Iteration   1: 4.108 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.967 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.872 ±(99.9%) 0.006 ms/op
Iteration   1: 2.880 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.668 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.514 ms/op
                 existUser·p0.99:   3.985 ms/op
                 existUser·p0.999:  6.037 ms/op
                 existUser·p0.9999: 13.269 ms/op
                 existUser·p1.00:   13.468 ms/op

Iteration   2: 2.902 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.638 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   4.088 ms/op
                 existUser·p0.999:  6.328 ms/op
                 existUser·p0.9999: 13.680 ms/op
                 existUser·p1.00:   14.172 ms/op

Iteration   3: 2.926 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.748 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  6.180 ms/op
                 existUser·p0.9999: 15.484 ms/op
                 existUser·p1.00:   15.974 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330590
  mean =      2.903 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1534 
    [ 1.250,  2.500) = 37023 
    [ 2.500,  3.750) = 284259 
    [ 3.750,  5.000) = 6859 
    [ 5.000,  6.250) = 605 
    [ 6.250,  7.500) = 95 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 100 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.638 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.363 ms/op
     p(95.0000) =      3.580 ms/op
     p(99.0000) =      4.076 ms/op
     p(99.9000) =      6.180 ms/op
     p(99.9900) =     14.170 ms/op
     p(99.9990) =     15.642 ms/op
     p(99.9999) =     15.974 ms/op
    p(100.0000) =     15.974 ms/op


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
# Warmup Iteration   1: 4.044 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.247 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.006 ms/op
Iteration   1: 3.043 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.799 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   4.612 ms/op
                 getUser·p0.999:  8.633 ms/op
                 getUser·p0.9999: 13.295 ms/op
                 getUser·p1.00:   13.631 ms/op

Iteration   2: 3.013 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.660 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   4.719 ms/op
                 getUser·p0.999:  7.053 ms/op
                 getUser·p0.9999: 14.418 ms/op
                 getUser·p1.00:   14.762 ms/op

Iteration   3: 3.037 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.677 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  6.715 ms/op
                 getUser·p0.9999: 17.087 ms/op
                 getUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316624
  mean =      3.031 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 571 
    [ 1.250,  2.500) = 25398 
    [ 2.500,  3.750) = 273093 
    [ 3.750,  5.000) = 16056 
    [ 5.000,  6.250) = 951 
    [ 6.250,  7.500) = 216 
    [ 7.500,  8.750) = 110 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 37 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.620 ms/op
     p(99.9000) =      7.780 ms/op
     p(99.9900) =     16.302 ms/op
     p(99.9990) =     17.525 ms/op
     p(99.9999) =     17.531 ms/op
    p(100.0000) =     17.531 ms/op


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
# Warmup Iteration   1: 5.328 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.014 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.990 ±(99.9%) 0.011 ms/op
Iteration   1: 3.965 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.180 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  13.844 ms/op
                 listUser·p0.9999: 19.628 ms/op
                 listUser·p1.00:   20.152 ms/op

Iteration   2: 3.911 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.845 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.768 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  15.827 ms/op
                 listUser·p0.9999: 20.501 ms/op
                 listUser·p1.00:   20.906 ms/op

Iteration   3: 3.980 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.999 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  21.004 ms/op
                 listUser·p0.9999: 28.082 ms/op
                 listUser·p1.00:   29.098 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242989
  mean =      3.951 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2618 
    [ 2.500,  5.000) = 219987 
    [ 5.000,  7.500) = 19281 
    [ 7.500, 10.000) = 601 
    [10.000, 12.500) = 117 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.845 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.833 ms/op
     p(95.0000) =      5.628 ms/op
     p(99.0000) =      6.840 ms/op
     p(99.9000) =     15.827 ms/op
     p(99.9900) =     27.296 ms/op
     p(99.9990) =     29.098 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.609 ± 4.019  ops/ms
ClientGrpc.existUser                       thrpt       3  11.174 ± 2.755  ops/ms
ClientGrpc.getUser                         thrpt       3  10.561 ± 1.293  ops/ms
ClientGrpc.listUser                        thrpt       3   8.090 ± 1.105  ops/ms
ClientGrpc.createUser                       avgt       3   3.008 ± 0.473   ms/op
ClientGrpc.existUser                        avgt       3   2.897 ± 0.295   ms/op
ClientGrpc.getUser                          avgt       3   3.013 ± 0.455   ms/op
ClientGrpc.listUser                         avgt       3   3.927 ± 0.315   ms/op
ClientGrpc.createUser                     sample  321233   2.988 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.660           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.978           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.453           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.645           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.612           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.322           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.184           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.866           ms/op
ClientGrpc.existUser                      sample  330590   2.903 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.638           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.884           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.363           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.580           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.076           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.180           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.170           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.974           ms/op
ClientGrpc.getUser                        sample  316624   3.031 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.660           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.998           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.580           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.777           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.620           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.780           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.302           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.531           ms/op
ClientGrpc.listUser                       sample  242989   3.951 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.845           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.797           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.833           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.628           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.840           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.827           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.296           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.098           ms/op
