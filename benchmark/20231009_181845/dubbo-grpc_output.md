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
# Warmup Iteration   1: 3.866 ops/ms
# Warmup Iteration   2: 8.475 ops/ms
# Warmup Iteration   3: 9.674 ops/ms
Iteration   1: 10.226 ops/ms
Iteration   2: 10.050 ops/ms
Iteration   3: 9.950 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.076 ±(99.9%) 2.550 ops/ms [Average]
  (min, avg, max) = (9.950, 10.076, 10.226), stdev = 0.140
  CI (99.9%): [7.526, 12.626] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 7.224 ops/ms
# Warmup Iteration   2: 10.073 ops/ms
# Warmup Iteration   3: 10.661 ops/ms
Iteration   1: 10.648 ops/ms
Iteration   2: 10.547 ops/ms
Iteration   3: 10.496 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.564 ±(99.9%) 1.407 ops/ms [Average]
  (min, avg, max) = (10.496, 10.564, 10.648), stdev = 0.077
  CI (99.9%): [9.156, 11.971] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.714 ops/ms
# Warmup Iteration   2: 9.507 ops/ms
# Warmup Iteration   3: 10.172 ops/ms
Iteration   1: 10.178 ops/ms
Iteration   2: 10.217 ops/ms
Iteration   3: 10.023 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.140 ±(99.9%) 1.872 ops/ms [Average]
  (min, avg, max) = (10.023, 10.140, 10.217), stdev = 0.103
  CI (99.9%): [8.268, 12.012] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 5.463 ops/ms
# Warmup Iteration   2: 7.838 ops/ms
# Warmup Iteration   3: 7.987 ops/ms
Iteration   1: 7.954 ops/ms
Iteration   2: 8.321 ops/ms
Iteration   3: 8.056 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.110 ±(99.9%) 3.462 ops/ms [Average]
  (min, avg, max) = (7.954, 8.110, 8.321), stdev = 0.190
  CI (99.9%): [4.648, 11.572] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.453 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.290 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.163 ±(99.9%) 0.004 ms/op
Iteration   1: 3.221 ±(99.9%) 0.004 ms/op
Iteration   2: 3.216 ±(99.9%) 0.003 ms/op
Iteration   3: 3.148 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.195 ±(99.9%) 0.748 ms/op [Average]
  (min, avg, max) = (3.148, 3.195, 3.221), stdev = 0.041
  CI (99.9%): [2.446, 3.943] (assumes normal distribution)


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
# Warmup Iteration   1: 3.962 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.168 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.123 ±(99.9%) 0.002 ms/op
Iteration   1: 3.099 ±(99.9%) 0.003 ms/op
Iteration   2: 3.062 ±(99.9%) 0.003 ms/op
Iteration   3: 3.012 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.058 ±(99.9%) 0.798 ms/op [Average]
  (min, avg, max) = (3.012, 3.058, 3.099), stdev = 0.044
  CI (99.9%): [2.260, 3.855] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.478 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.301 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.191 ±(99.9%) 0.009 ms/op
Iteration   1: 3.132 ±(99.9%) 0.003 ms/op
Iteration   2: 3.172 ±(99.9%) 0.002 ms/op
Iteration   3: 3.090 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.131 ±(99.9%) 0.741 ms/op [Average]
  (min, avg, max) = (3.090, 3.131, 3.172), stdev = 0.041
  CI (99.9%): [2.390, 3.872] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.751 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.071 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 3.946 ±(99.9%) 0.019 ms/op
Iteration   1: 3.920 ±(99.9%) 0.033 ms/op
Iteration   2: 3.883 ±(99.9%) 0.032 ms/op
Iteration   3: 3.905 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.903 ±(99.9%) 0.335 ms/op [Average]
  (min, avg, max) = (3.883, 3.903, 3.920), stdev = 0.018
  CI (99.9%): [3.567, 4.238] (assumes normal distribution)


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
# Warmup Iteration   1: 4.452 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.282 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.124 ±(99.9%) 0.007 ms/op
Iteration   1: 3.111 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.315 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  8.223 ms/op
                 createUser·p0.9999: 20.303 ms/op
                 createUser·p1.00:   21.955 ms/op

Iteration   2: 3.154 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.606 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.883 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  9.118 ms/op
                 createUser·p0.9999: 22.086 ms/op
                 createUser·p1.00:   22.184 ms/op

Iteration   3: 3.152 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.518 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   4.710 ms/op
                 createUser·p0.999:  20.021 ms/op
                 createUser·p0.9999: 26.182 ms/op
                 createUser·p1.00:   26.640 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305999
  mean =      3.139 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10788 
    [ 2.500,  5.000) = 293132 
    [ 5.000,  7.500) = 1571 
    [ 7.500, 10.000) = 180 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      0.315 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =     10.535 ms/op
     p(99.9900) =     25.467 ms/op
     p(99.9990) =     26.407 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.532 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.188 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.006 ms/op
Iteration   1: 3.052 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.824 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  7.211 ms/op
                 existUser·p0.9999: 13.575 ms/op
                 existUser·p1.00:   14.877 ms/op

Iteration   2: 3.068 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.560 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   4.817 ms/op
                 existUser·p0.999:  13.099 ms/op
                 existUser·p0.9999: 18.336 ms/op
                 existUser·p1.00:   18.481 ms/op

Iteration   3: 3.070 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.757 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.699 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   4.669 ms/op
                 existUser·p0.999:  14.939 ms/op
                 existUser·p0.9999: 18.192 ms/op
                 existUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 313110
  mean =      3.063 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 634 
    [ 1.250,  2.500) = 14079 
    [ 2.500,  3.750) = 276288 
    [ 3.750,  5.000) = 19879 
    [ 5.000,  6.250) = 1060 
    [ 6.250,  7.500) = 468 
    [ 7.500,  8.750) = 226 
    [ 8.750, 10.000) = 101 
    [10.000, 11.250) = 49 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 62 
    [15.000, 16.250) = 49 
    [16.250, 17.500) = 42 
    [17.500, 18.750) = 42 

  Percentiles, ms/op:
      p(0.0000) =      0.560 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.854 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =     11.773 ms/op
     p(99.9900) =     18.186 ms/op
     p(99.9990) =     18.636 ms/op
     p(99.9999) =     18.809 ms/op
    p(100.0000) =     18.809 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.617 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.304 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.182 ±(99.9%) 0.007 ms/op
Iteration   1: 3.155 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.649 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   4.006 ms/op
                 getUser·p0.99:   5.005 ms/op
                 getUser·p0.999:  9.421 ms/op
                 getUser·p0.9999: 20.438 ms/op
                 getUser·p1.00:   20.873 ms/op

Iteration   2: 3.200 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.770 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   4.956 ms/op
                 getUser·p0.999:  10.550 ms/op
                 getUser·p0.9999: 24.773 ms/op
                 getUser·p1.00:   28.738 ms/op

Iteration   3: 3.135 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.632 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.895 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  8.110 ms/op
                 getUser·p0.9999: 23.324 ms/op
                 getUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 303436
  mean =      3.163 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9173 
    [ 2.500,  5.000) = 291730 
    [ 5.000,  7.500) = 2003 
    [ 7.500, 10.000) = 257 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.632 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      4.817 ms/op
     p(99.9000) =      9.210 ms/op
     p(99.9900) =     24.062 ms/op
     p(99.9990) =     25.002 ms/op
     p(99.9999) =     28.738 ms/op
    p(100.0000) =     28.738 ms/op


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
# Warmup Iteration   1: 5.540 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.188 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.952 ±(99.9%) 0.009 ms/op
Iteration   1: 3.950 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.200 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   5.333 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  13.631 ms/op
                 listUser·p0.9999: 19.464 ms/op
                 listUser·p1.00:   20.087 ms/op

Iteration   2: 3.948 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.828 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  14.828 ms/op
                 listUser·p0.9999: 21.135 ms/op
                 listUser·p1.00:   23.396 ms/op

Iteration   3: 3.903 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.995 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  15.827 ms/op
                 listUser·p0.9999: 19.097 ms/op
                 listUser·p1.00:   23.462 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244035
  mean =      3.934 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2837 
    [ 2.500,  5.000) = 223790 
    [ 5.000,  7.500) = 16252 
    [ 7.500, 10.000) = 630 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 237 
    [15.000, 17.500) = 159 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.828 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      5.472 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     14.941 ms/op
     p(99.9900) =     19.530 ms/op
     p(99.9990) =     23.353 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.076 ± 2.550  ops/ms
ClientGrpc.existUser                       thrpt       3  10.564 ± 1.407  ops/ms
ClientGrpc.getUser                         thrpt       3  10.140 ± 1.872  ops/ms
ClientGrpc.listUser                        thrpt       3   8.110 ± 3.462  ops/ms
ClientGrpc.createUser                       avgt       3   3.195 ± 0.748   ms/op
ClientGrpc.existUser                        avgt       3   3.058 ± 0.798   ms/op
ClientGrpc.getUser                          avgt       3   3.131 ± 0.741   ms/op
ClientGrpc.listUser                         avgt       3   3.903 ± 0.335   ms/op
ClientGrpc.createUser                     sample  305999   3.139 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.315           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.088           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.666           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.871           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.555           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.535           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.467           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.640           ms/op
ClientGrpc.existUser                      sample  313110   3.063 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.560           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.998           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.625           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.854           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.604           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.773           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.186           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.809           ms/op
ClientGrpc.getUser                        sample  303436   3.163 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.632           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.105           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.719           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.936           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.817           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.210           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.062           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.738           ms/op
ClientGrpc.listUser                       sample  244035   3.934 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.828           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.813           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.620           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.472           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.717           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.941           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.530           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.462           ms/op
