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
# Warmup Iteration   1: 4.185 ops/ms
# Warmup Iteration   2: 8.963 ops/ms
# Warmup Iteration   3: 10.051 ops/ms
Iteration   1: 10.121 ops/ms
Iteration   2: 9.856 ops/ms
Iteration   3: 9.632 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.869 ±(99.9%) 4.470 ops/ms [Average]
  (min, avg, max) = (9.632, 9.869, 10.121), stdev = 0.245
  CI (99.9%): [5.400, 14.339] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.881 ops/ms
# Warmup Iteration   2: 10.061 ops/ms
# Warmup Iteration   3: 10.755 ops/ms
Iteration   1: 10.447 ops/ms
Iteration   2: 10.462 ops/ms
Iteration   3: 10.448 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.452 ±(99.9%) 0.153 ops/ms [Average]
  (min, avg, max) = (10.447, 10.452, 10.462), stdev = 0.008
  CI (99.9%): [10.299, 10.605] (assumes normal distribution)


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
# Warmup Iteration   1: 6.439 ops/ms
# Warmup Iteration   2: 9.583 ops/ms
# Warmup Iteration   3: 9.945 ops/ms
Iteration   1: 10.011 ops/ms
Iteration   2: 10.072 ops/ms
Iteration   3: 10.005 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.029 ±(99.9%) 0.673 ops/ms [Average]
  (min, avg, max) = (10.005, 10.029, 10.072), stdev = 0.037
  CI (99.9%): [9.356, 10.702] (assumes normal distribution)


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
# Warmup Iteration   1: 5.607 ops/ms
# Warmup Iteration   2: 7.625 ops/ms
# Warmup Iteration   3: 7.694 ops/ms
Iteration   1: 8.045 ops/ms
Iteration   2: 7.972 ops/ms
Iteration   3: 7.916 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.978 ±(99.9%) 1.183 ops/ms [Average]
  (min, avg, max) = (7.916, 7.978, 8.045), stdev = 0.065
  CI (99.9%): [6.795, 9.160] (assumes normal distribution)


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
# Warmup Iteration   1: 4.351 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.310 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.168 ±(99.9%) 0.002 ms/op
Iteration   1: 3.131 ±(99.9%) 0.009 ms/op
Iteration   2: 3.222 ±(99.9%) 0.002 ms/op
Iteration   3: 3.151 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.168 ±(99.9%) 0.873 ms/op [Average]
  (min, avg, max) = (3.131, 3.168, 3.222), stdev = 0.048
  CI (99.9%): [2.295, 4.041] (assumes normal distribution)


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
# Warmup Iteration   1: 4.114 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.107 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.073 ±(99.9%) 0.002 ms/op
Iteration   1: 2.978 ±(99.9%) 0.002 ms/op
Iteration   2: 3.089 ±(99.9%) 0.002 ms/op
Iteration   3: 3.006 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.024 ±(99.9%) 1.054 ms/op [Average]
  (min, avg, max) = (2.978, 3.024, 3.089), stdev = 0.058
  CI (99.9%): [1.970, 4.078] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.257 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.223 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.095 ±(99.9%) 0.003 ms/op
Iteration   1: 3.148 ±(99.9%) 0.002 ms/op
Iteration   2: 3.188 ±(99.9%) 0.003 ms/op
Iteration   3: 3.163 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.166 ±(99.9%) 0.377 ms/op [Average]
  (min, avg, max) = (3.148, 3.166, 3.188), stdev = 0.021
  CI (99.9%): [2.790, 3.543] (assumes normal distribution)


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
# Warmup Iteration   1: 5.780 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.093 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.931 ±(99.9%) 0.011 ms/op
Iteration   1: 4.039 ±(99.9%) 0.009 ms/op
Iteration   2: 3.998 ±(99.9%) 0.014 ms/op
Iteration   3: 4.029 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.022 ±(99.9%) 0.390 ms/op [Average]
  (min, avg, max) = (3.998, 4.022, 4.039), stdev = 0.021
  CI (99.9%): [3.632, 4.412] (assumes normal distribution)


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
# Warmup Iteration   1: 4.371 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.372 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.218 ±(99.9%) 0.007 ms/op
Iteration   1: 3.262 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.746 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.990 ms/op
                 createUser·p0.95:   4.157 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  7.452 ms/op
                 createUser·p0.9999: 23.283 ms/op
                 createUser·p1.00:   24.084 ms/op

Iteration   2: 3.177 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.676 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.875 ms/op
                 createUser·p0.95:   4.092 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  10.453 ms/op
                 createUser·p0.9999: 19.104 ms/op
                 createUser·p1.00:   20.349 ms/op

Iteration   3: 3.156 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.721 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   3.994 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  9.609 ms/op
                 createUser·p0.9999: 26.323 ms/op
                 createUser·p1.00:   27.951 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 300186
  mean =      3.198 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19536 
    [ 2.500,  5.000) = 279596 
    [ 5.000,  7.500) = 612 
    [ 7.500, 10.000) = 173 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.676 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.092 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      9.021 ms/op
     p(99.9900) =     24.412 ms/op
     p(99.9990) =     27.263 ms/op
     p(99.9999) =     27.951 ms/op
    p(100.0000) =     27.951 ms/op


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
# Warmup Iteration   1: 4.180 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.184 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.029 ±(99.9%) 0.007 ms/op
Iteration   1: 3.051 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.781 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   3.858 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  7.096 ms/op
                 existUser·p0.9999: 12.952 ms/op
                 existUser·p1.00:   13.287 ms/op

Iteration   2: 2.990 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.714 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.580 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  6.563 ms/op
                 existUser·p0.9999: 16.105 ms/op
                 existUser·p1.00:   16.433 ms/op

Iteration   3: 3.111 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.811 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.822 ms/op
                 existUser·p0.95:   3.973 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  6.653 ms/op
                 existUser·p0.9999: 16.229 ms/op
                 existUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 314604
  mean =      3.050 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1410 
    [ 1.250,  2.500) = 36633 
    [ 2.500,  3.750) = 248327 
    [ 3.750,  5.000) = 27227 
    [ 5.000,  6.250) = 477 
    [ 6.250,  7.500) = 347 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 73 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.714 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      6.734 ms/op
     p(99.9900) =     16.024 ms/op
     p(99.9990) =     18.125 ms/op
     p(99.9999) =     18.317 ms/op
    p(100.0000) =     18.317 ms/op


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
# Warmup Iteration   1: 4.316 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.251 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.146 ±(99.9%) 0.007 ms/op
Iteration   1: 3.143 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.727 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  7.553 ms/op
                 getUser·p0.9999: 12.433 ms/op
                 getUser·p1.00:   14.500 ms/op

Iteration   2: 3.121 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.864 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   3.994 ms/op
                 getUser·p0.99:   4.801 ms/op
                 getUser·p0.999:  7.648 ms/op
                 getUser·p0.9999: 17.547 ms/op
                 getUser·p1.00:   18.153 ms/op

Iteration   3: 3.172 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.757 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  6.834 ms/op
                 getUser·p0.9999: 15.972 ms/op
                 getUser·p1.00:   16.433 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 305143
  mean =      3.145 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 603 
    [ 1.250,  2.500) = 22824 
    [ 2.500,  3.750) = 247139 
    [ 3.750,  5.000) = 33144 
    [ 5.000,  6.250) = 827 
    [ 6.250,  7.500) = 317 
    [ 7.500,  8.750) = 86 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 57 
    [15.000, 16.250) = 37 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.727 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      7.404 ms/op
     p(99.9900) =     16.457 ms/op
     p(99.9990) =     18.145 ms/op
     p(99.9999) =     18.153 ms/op
    p(100.0000) =     18.153 ms/op


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
# Warmup Iteration   1: 5.591 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.187 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.090 ±(99.9%) 0.011 ms/op
Iteration   1: 4.091 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.071 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   5.300 ms/op
                 listUser·p0.95:   5.956 ms/op
                 listUser·p0.99:   7.420 ms/op
                 listUser·p0.999:  13.970 ms/op
                 listUser·p0.9999: 25.739 ms/op
                 listUser·p1.00:   25.985 ms/op

Iteration   2: 3.970 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.905 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  14.300 ms/op
                 listUser·p0.9999: 23.294 ms/op
                 listUser·p1.00:   23.986 ms/op

Iteration   3: 4.057 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.124 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  14.831 ms/op
                 listUser·p0.9999: 17.244 ms/op
                 listUser·p1.00:   18.776 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237754
  mean =      4.039 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2059 
    [ 2.500,  5.000) = 207742 
    [ 5.000,  7.500) = 26310 
    [ 7.500, 10.000) = 1132 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 160 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.905 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      5.177 ms/op
     p(95.0000) =      5.792 ms/op
     p(99.0000) =      7.102 ms/op
     p(99.9000) =     14.274 ms/op
     p(99.9900) =     24.452 ms/op
     p(99.9990) =     25.907 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.869 ± 4.470  ops/ms
ClientGrpc.existUser                       thrpt       3  10.452 ± 0.153  ops/ms
ClientGrpc.getUser                         thrpt       3  10.029 ± 0.673  ops/ms
ClientGrpc.listUser                        thrpt       3   7.978 ± 1.183  ops/ms
ClientGrpc.createUser                       avgt       3   3.168 ± 0.873   ms/op
ClientGrpc.existUser                        avgt       3   3.024 ± 1.054   ms/op
ClientGrpc.getUser                          avgt       3   3.166 ± 0.377   ms/op
ClientGrpc.listUser                         avgt       3   4.022 ± 0.390   ms/op
ClientGrpc.createUser                     sample  300186   3.198 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.676           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.162           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.895           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.092           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.021           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.412           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.951           ms/op
ClientGrpc.existUser                      sample  314604   3.050 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.714           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.031           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.719           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.891           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.268           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.734           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.024           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.317           ms/op
ClientGrpc.getUser                        sample  305143   3.145 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.727           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.117           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.789           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.977           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.489           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.404           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.457           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.153           ms/op
ClientGrpc.listUser                       sample  237754   4.039 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.905           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.854           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.177           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.792           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.102           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.274           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.452           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.985           ms/op
