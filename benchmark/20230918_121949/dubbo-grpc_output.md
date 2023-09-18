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
# Warmup Iteration   1: 3.966 ops/ms
# Warmup Iteration   2: 8.438 ops/ms
# Warmup Iteration   3: 9.423 ops/ms
Iteration   1: 9.799 ops/ms
Iteration   2: 10.125 ops/ms
Iteration   3: 10.286 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.070 ±(99.9%) 4.533 ops/ms [Average]
  (min, avg, max) = (9.799, 10.070, 10.286), stdev = 0.248
  CI (99.9%): [5.538, 14.603] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.046 ops/ms
# Warmup Iteration   2: 10.124 ops/ms
# Warmup Iteration   3: 10.854 ops/ms
Iteration   1: 10.442 ops/ms
Iteration   2: 10.462 ops/ms
Iteration   3: 10.318 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.407 ±(99.9%) 1.427 ops/ms [Average]
  (min, avg, max) = (10.318, 10.407, 10.462), stdev = 0.078
  CI (99.9%): [8.980, 11.834] (assumes normal distribution)


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
# Warmup Iteration   1: 6.329 ops/ms
# Warmup Iteration   2: 9.707 ops/ms
# Warmup Iteration   3: 9.865 ops/ms
Iteration   1: 9.860 ops/ms
Iteration   2: 9.968 ops/ms
Iteration   3: 10.150 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.993 ±(99.9%) 2.671 ops/ms [Average]
  (min, avg, max) = (9.860, 9.993, 10.150), stdev = 0.146
  CI (99.9%): [7.321, 12.664] (assumes normal distribution)


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
# Warmup Iteration   1: 5.418 ops/ms
# Warmup Iteration   2: 7.814 ops/ms
# Warmup Iteration   3: 7.854 ops/ms
Iteration   1: 8.074 ops/ms
Iteration   2: 8.118 ops/ms
Iteration   3: 8.177 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.123 ±(99.9%) 0.940 ops/ms [Average]
  (min, avg, max) = (8.074, 8.123, 8.177), stdev = 0.052
  CI (99.9%): [7.183, 9.063] (assumes normal distribution)


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
# Warmup Iteration   1: 4.236 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.312 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.249 ±(99.9%) 0.002 ms/op
Iteration   1: 3.178 ±(99.9%) 0.011 ms/op
Iteration   2: 3.241 ±(99.9%) 0.001 ms/op
Iteration   3: 3.134 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.184 ±(99.9%) 0.986 ms/op [Average]
  (min, avg, max) = (3.134, 3.184, 3.241), stdev = 0.054
  CI (99.9%): [2.198, 4.171] (assumes normal distribution)


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
# Warmup Iteration   1: 4.185 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.208 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.022 ±(99.9%) 0.002 ms/op
Iteration   1: 3.057 ±(99.9%) 0.002 ms/op
Iteration   2: 3.103 ±(99.9%) 0.001 ms/op
Iteration   3: 3.007 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.056 ±(99.9%) 0.873 ms/op [Average]
  (min, avg, max) = (3.007, 3.056, 3.103), stdev = 0.048
  CI (99.9%): [2.183, 3.928] (assumes normal distribution)


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
# Warmup Iteration   1: 4.621 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.308 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.179 ±(99.9%) 0.003 ms/op
Iteration   1: 3.157 ±(99.9%) 0.003 ms/op
Iteration   2: 3.184 ±(99.9%) 0.003 ms/op
Iteration   3: 3.131 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.157 ±(99.9%) 0.478 ms/op [Average]
  (min, avg, max) = (3.131, 3.157, 3.184), stdev = 0.026
  CI (99.9%): [2.679, 3.636] (assumes normal distribution)


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
# Warmup Iteration   1: 4.895 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.265 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.147 ±(99.9%) 0.021 ms/op
Iteration   1: 3.997 ±(99.9%) 0.006 ms/op
Iteration   2: 4.018 ±(99.9%) 0.011 ms/op
Iteration   3: 3.830 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.948 ±(99.9%) 1.886 ms/op [Average]
  (min, avg, max) = (3.830, 3.948, 4.018), stdev = 0.103
  CI (99.9%): [2.062, 5.835] (assumes normal distribution)


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
# Warmup Iteration   1: 4.519 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.317 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.227 ±(99.9%) 0.007 ms/op
Iteration   1: 3.259 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.795 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.035 ms/op
                 createUser·p0.99:   5.243 ms/op
                 createUser·p0.999:  8.380 ms/op
                 createUser·p0.9999: 16.338 ms/op
                 createUser·p1.00:   16.974 ms/op

Iteration   2: 3.227 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.882 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.108 ms/op
                 createUser·p0.99:   5.333 ms/op
                 createUser·p0.999:  9.847 ms/op
                 createUser·p0.9999: 18.356 ms/op
                 createUser·p1.00:   18.481 ms/op

Iteration   3: 3.167 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.796 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   5.218 ms/op
                 createUser·p0.999:  10.649 ms/op
                 createUser·p0.9999: 21.686 ms/op
                 createUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 298299
  mean =      3.217 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12213 
    [ 2.500,  5.000) = 282329 
    [ 5.000,  7.500) = 3179 
    [ 7.500, 10.000) = 335 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.795 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      5.267 ms/op
     p(99.9000) =      9.088 ms/op
     p(99.9900) =     19.726 ms/op
     p(99.9990) =     22.054 ms/op
     p(99.9999) =     22.184 ms/op
    p(100.0000) =     22.184 ms/op


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
# Warmup Iteration   1: 4.128 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.186 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.069 ±(99.9%) 0.006 ms/op
Iteration   1: 3.107 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.664 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.740 ms/op
                 existUser·p0.95:   4.051 ms/op
                 existUser·p0.99:   5.404 ms/op
                 existUser·p0.999:  7.840 ms/op
                 existUser·p0.9999: 13.386 ms/op
                 existUser·p1.00:   13.746 ms/op

Iteration   2: 3.021 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.589 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   4.645 ms/op
                 existUser·p0.999:  7.972 ms/op
                 existUser·p0.9999: 14.146 ms/op
                 existUser·p1.00:   14.369 ms/op

Iteration   3: 3.015 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.850 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.506 ms/op
                 existUser·p0.999:  8.583 ms/op
                 existUser·p0.9999: 16.653 ms/op
                 existUser·p1.00:   16.941 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 314943
  mean =      3.047 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 959 
    [ 1.250,  2.500) = 20594 
    [ 2.500,  3.750) = 273714 
    [ 3.750,  5.000) = 16756 
    [ 5.000,  6.250) = 1642 
    [ 6.250,  7.500) = 801 
    [ 7.500,  8.750) = 251 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.589 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      4.915 ms/op
     p(99.9000) =      8.177 ms/op
     p(99.9900) =     15.852 ms/op
     p(99.9990) =     16.838 ms/op
     p(99.9999) =     16.941 ms/op
    p(100.0000) =     16.941 ms/op


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
# Warmup Iteration   1: 4.443 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.304 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.227 ±(99.9%) 0.007 ms/op
Iteration   1: 3.153 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.864 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   4.059 ms/op
                 getUser·p0.99:   5.052 ms/op
                 getUser·p0.999:  8.332 ms/op
                 getUser·p0.9999: 18.954 ms/op
                 getUser·p1.00:   19.923 ms/op

Iteration   2: 3.171 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.628 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   4.121 ms/op
                 getUser·p0.99:   5.915 ms/op
                 getUser·p0.999:  9.928 ms/op
                 getUser·p0.9999: 19.720 ms/op
                 getUser·p1.00:   20.120 ms/op

Iteration   3: 3.195 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.629 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   5.112 ms/op
                 getUser·p0.999:  9.937 ms/op
                 getUser·p0.9999: 20.382 ms/op
                 getUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 302681
  mean =      3.173 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12049 
    [ 2.500,  5.000) = 286852 
    [ 5.000,  7.500) = 3034 
    [ 7.500, 10.000) = 473 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 126 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      4.026 ms/op
     p(99.0000) =      5.284 ms/op
     p(99.9000) =      9.552 ms/op
     p(99.9900) =     19.792 ms/op
     p(99.9990) =     20.642 ms/op
     p(99.9999) =     20.742 ms/op
    p(100.0000) =     20.742 ms/op


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
# Warmup Iteration   1: 5.427 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.111 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.002 ±(99.9%) 0.010 ms/op
Iteration   1: 3.918 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.016 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   5.194 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  13.791 ms/op
                 listUser·p0.9999: 15.459 ms/op
                 listUser·p1.00:   15.860 ms/op

Iteration   2: 3.972 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.499 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   5.358 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  14.098 ms/op
                 listUser·p0.9999: 15.744 ms/op
                 listUser·p1.00:   16.810 ms/op

Iteration   3: 4.044 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.403 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  15.301 ms/op
                 listUser·p0.9999: 18.356 ms/op
                 listUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241201
  mean =      3.977 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 2043 
    [ 2.500,  3.750) = 91819 
    [ 3.750,  5.000) = 130473 
    [ 5.000,  6.250) = 10581 
    [ 6.250,  7.500) = 4634 
    [ 7.500,  8.750) = 891 
    [ 8.750, 10.000) = 240 
    [10.000, 11.250) = 124 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 157 
    [15.000, 16.250) = 69 
    [16.250, 17.500) = 58 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.016 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      5.415 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     14.251 ms/op
     p(99.9900) =     17.170 ms/op
     p(99.9990) =     18.847 ms/op
     p(99.9999) =     18.973 ms/op
    p(100.0000) =     18.973 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.070 ± 4.533  ops/ms
ClientGrpc.existUser                       thrpt       3  10.407 ± 1.427  ops/ms
ClientGrpc.getUser                         thrpt       3   9.993 ± 2.671  ops/ms
ClientGrpc.listUser                        thrpt       3   8.123 ± 0.940  ops/ms
ClientGrpc.createUser                       avgt       3   3.184 ± 0.986   ms/op
ClientGrpc.existUser                        avgt       3   3.056 ± 0.873   ms/op
ClientGrpc.getUser                          avgt       3   3.157 ± 0.478   ms/op
ClientGrpc.listUser                         avgt       3   3.948 ± 1.886   ms/op
ClientGrpc.createUser                     sample  298299   3.217 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.795           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.162           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.834           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.071           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.267           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.088           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.726           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.184           ms/op
ClientGrpc.existUser                      sample  314943   3.047 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.589           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.994           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.576           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.842           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.915           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.177           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.852           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.941           ms/op
ClientGrpc.getUser                        sample  302681   3.173 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.628           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.105           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.756           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.026           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.284           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.552           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.792           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.742           ms/op
ClientGrpc.listUser                       sample  241201   3.977 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.016           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.867           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.628           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.415           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.053           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.251           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.170           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          18.973           ms/op
