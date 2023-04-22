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
# Warmup Iteration   1: 4.059 ops/ms
# Warmup Iteration   2: 9.075 ops/ms
# Warmup Iteration   3: 10.076 ops/ms
Iteration   1: 10.369 ops/ms
Iteration   2: 10.226 ops/ms
Iteration   3: 10.523 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.373 ±(99.9%) 2.712 ops/ms [Average]
  (min, avg, max) = (10.226, 10.373, 10.523), stdev = 0.149
  CI (99.9%): [7.661, 13.085] (assumes normal distribution)


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
# Warmup Iteration   1: 7.808 ops/ms
# Warmup Iteration   2: 10.705 ops/ms
# Warmup Iteration   3: 11.065 ops/ms
Iteration   1: 10.956 ops/ms
Iteration   2: 11.020 ops/ms
Iteration   3: 11.050 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.009 ±(99.9%) 0.873 ops/ms [Average]
  (min, avg, max) = (10.956, 11.009, 11.050), stdev = 0.048
  CI (99.9%): [10.136, 11.882] (assumes normal distribution)


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
# Warmup Iteration   1: 7.020 ops/ms
# Warmup Iteration   2: 9.757 ops/ms
# Warmup Iteration   3: 10.427 ops/ms
Iteration   1: 10.151 ops/ms
Iteration   2: 10.431 ops/ms
Iteration   3: 10.430 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.337 ±(99.9%) 2.946 ops/ms [Average]
  (min, avg, max) = (10.151, 10.337, 10.431), stdev = 0.161
  CI (99.9%): [7.391, 13.283] (assumes normal distribution)


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
# Warmup Iteration   1: 5.270 ops/ms
# Warmup Iteration   2: 7.845 ops/ms
# Warmup Iteration   3: 7.895 ops/ms
Iteration   1: 7.931 ops/ms
Iteration   2: 7.977 ops/ms
Iteration   3: 8.049 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.985 ±(99.9%) 1.082 ops/ms [Average]
  (min, avg, max) = (7.931, 7.985, 8.049), stdev = 0.059
  CI (99.9%): [6.903, 9.068] (assumes normal distribution)


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
# Warmup Iteration   1: 4.349 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.206 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.098 ±(99.9%) 0.005 ms/op
Iteration   1: 3.043 ±(99.9%) 0.002 ms/op
Iteration   2: 3.084 ±(99.9%) 0.002 ms/op
Iteration   3: 2.983 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.037 ±(99.9%) 0.930 ms/op [Average]
  (min, avg, max) = (2.983, 3.037, 3.084), stdev = 0.051
  CI (99.9%): [2.106, 3.967] (assumes normal distribution)


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
# Warmup Iteration   1: 4.232 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.999 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.945 ±(99.9%) 0.003 ms/op
Iteration   1: 2.896 ±(99.9%) 0.004 ms/op
Iteration   2: 2.918 ±(99.9%) 0.003 ms/op
Iteration   3: 2.899 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.904 ±(99.9%) 0.212 ms/op [Average]
  (min, avg, max) = (2.896, 2.904, 2.918), stdev = 0.012
  CI (99.9%): [2.692, 3.117] (assumes normal distribution)


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
# Warmup Iteration   1: 4.348 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.115 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.003 ms/op
Iteration   1: 3.055 ±(99.9%) 0.003 ms/op
Iteration   2: 3.070 ±(99.9%) 0.002 ms/op
Iteration   3: 3.048 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.058 ±(99.9%) 0.198 ms/op [Average]
  (min, avg, max) = (3.048, 3.058, 3.070), stdev = 0.011
  CI (99.9%): [2.859, 3.256] (assumes normal distribution)


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
# Warmup Iteration   1: 5.302 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.121 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.038 ±(99.9%) 0.018 ms/op
Iteration   1: 4.013 ±(99.9%) 0.019 ms/op
Iteration   2: 3.889 ±(99.9%) 0.011 ms/op
Iteration   3: 3.943 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.949 ±(99.9%) 1.134 ms/op [Average]
  (min, avg, max) = (3.889, 3.949, 4.013), stdev = 0.062
  CI (99.9%): [2.815, 5.082] (assumes normal distribution)


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
# Warmup Iteration   1: 4.375 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.234 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.005 ms/op
Iteration   1: 3.031 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.624 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  6.177 ms/op
                 createUser·p0.9999: 12.654 ms/op
                 createUser·p1.00:   15.139 ms/op

Iteration   2: 3.032 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.806 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  8.536 ms/op
                 createUser·p0.9999: 22.264 ms/op
                 createUser·p1.00:   23.331 ms/op

Iteration   3: 3.082 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.811 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   4.710 ms/op
                 createUser·p0.999:  7.225 ms/op
                 createUser·p0.9999: 16.687 ms/op
                 createUser·p1.00:   17.302 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314790
  mean =      3.048 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23778 
    [ 2.500,  5.000) = 289378 
    [ 5.000,  7.500) = 1306 
    [ 7.500, 10.000) = 134 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.624 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =      7.901 ms/op
     p(99.9900) =     21.742 ms/op
     p(99.9990) =     23.157 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


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
# Warmup Iteration   1: 4.014 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.050 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.005 ms/op
Iteration   1: 2.950 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.760 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  8.407 ms/op
                 existUser·p0.9999: 12.134 ms/op
                 existUser·p1.00:   12.747 ms/op

Iteration   2: 2.870 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.830 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   4.427 ms/op
                 existUser·p0.999:  6.849 ms/op
                 existUser·p0.9999: 13.889 ms/op
                 existUser·p1.00:   15.499 ms/op

Iteration   3: 2.928 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.817 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.456 ms/op
                 existUser·p0.999:  6.226 ms/op
                 existUser·p0.9999: 15.749 ms/op
                 existUser·p1.00:   16.400 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329140
  mean =      2.916 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1072 
    [ 1.250,  2.500) = 36400 
    [ 2.500,  3.750) = 280262 
    [ 3.750,  5.000) = 10131 
    [ 5.000,  6.250) = 746 
    [ 6.250,  7.500) = 240 
    [ 7.500,  8.750) = 64 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 43 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.760 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.625 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      6.880 ms/op
     p(99.9900) =     15.142 ms/op
     p(99.9990) =     16.091 ms/op
     p(99.9999) =     16.400 ms/op
    p(100.0000) =     16.400 ms/op


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
# Warmup Iteration   1: 4.238 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.171 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.133 ±(99.9%) 0.006 ms/op
Iteration   1: 3.059 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.815 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.743 ms/op
                 getUser·p0.999:  7.332 ms/op
                 getUser·p0.9999: 21.266 ms/op
                 getUser·p1.00:   21.660 ms/op

Iteration   2: 3.107 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.857 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  7.895 ms/op
                 getUser·p0.9999: 13.959 ms/op
                 getUser·p1.00:   16.466 ms/op

Iteration   3: 3.047 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.632 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  7.710 ms/op
                 getUser·p0.9999: 16.196 ms/op
                 getUser·p1.00:   16.417 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312481
  mean =      3.071 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17034 
    [ 2.500,  5.000) = 293701 
    [ 5.000,  7.500) = 1425 
    [ 7.500, 10.000) = 112 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.632 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =      7.557 ms/op
     p(99.9900) =     20.660 ms/op
     p(99.9990) =     21.520 ms/op
     p(99.9999) =     21.660 ms/op
    p(100.0000) =     21.660 ms/op


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
# Warmup Iteration   1: 5.465 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.197 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.005 ±(99.9%) 0.011 ms/op
Iteration   1: 3.989 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.346 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  14.074 ms/op
                 listUser·p0.9999: 17.887 ms/op
                 listUser·p1.00:   18.219 ms/op

Iteration   2: 3.990 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.290 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   7.124 ms/op
                 listUser·p0.999:  14.645 ms/op
                 listUser·p0.9999: 23.003 ms/op
                 listUser·p1.00:   23.364 ms/op

Iteration   3: 3.960 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.040 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  21.531 ms/op
                 listUser·p0.9999: 28.338 ms/op
                 listUser·p1.00:   28.738 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241396
  mean =      3.979 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3736 
    [ 2.500,  5.000) = 211376 
    [ 5.000,  7.500) = 24804 
    [ 7.500, 10.000) = 1029 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 143 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.040 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      5.087 ms/op
     p(95.0000) =      5.792 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     15.044 ms/op
     p(99.9900) =     26.636 ms/op
     p(99.9990) =     28.672 ms/op
     p(99.9999) =     28.738 ms/op
    p(100.0000) =     28.738 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.373 ± 2.712  ops/ms
ClientGrpc.existUser                       thrpt       3  11.009 ± 0.873  ops/ms
ClientGrpc.getUser                         thrpt       3  10.337 ± 2.946  ops/ms
ClientGrpc.listUser                        thrpt       3   7.985 ± 1.082  ops/ms
ClientGrpc.createUser                       avgt       3   3.037 ± 0.930   ms/op
ClientGrpc.existUser                        avgt       3   2.904 ± 0.212   ms/op
ClientGrpc.getUser                          avgt       3   3.058 ± 0.198   ms/op
ClientGrpc.listUser                         avgt       3   3.949 ± 1.134   ms/op
ClientGrpc.createUser                     sample  314790   3.048 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.624           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.015           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.580           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.785           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.555           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.901           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.742           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.331           ms/op
ClientGrpc.existUser                      sample  329140   2.916 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.760           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.896           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.391           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.625           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.383           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.880           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.142           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.400           ms/op
ClientGrpc.getUser                        sample  312481   3.071 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.632           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.039           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.576           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.781           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.571           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.557           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.660           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.660           ms/op
ClientGrpc.listUser                       sample  241396   3.979 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.040           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.805           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.087           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.792           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.053           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.044           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.636           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.738           ms/op
