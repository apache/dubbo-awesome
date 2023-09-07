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
# Warmup Iteration   1: 3.540 ops/ms
# Warmup Iteration   2: 8.359 ops/ms
# Warmup Iteration   3: 9.864 ops/ms
Iteration   1: 10.158 ops/ms
Iteration   2: 9.886 ops/ms
Iteration   3: 9.994 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.013 ±(99.9%) 2.503 ops/ms [Average]
  (min, avg, max) = (9.886, 10.013, 10.158), stdev = 0.137
  CI (99.9%): [7.510, 12.515] (assumes normal distribution)


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
# Warmup Iteration   1: 6.571 ops/ms
# Warmup Iteration   2: 10.128 ops/ms
# Warmup Iteration   3: 10.652 ops/ms
Iteration   1: 10.925 ops/ms
Iteration   2: 10.818 ops/ms
Iteration   3: 10.597 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.780 ±(99.9%) 3.055 ops/ms [Average]
  (min, avg, max) = (10.597, 10.780, 10.925), stdev = 0.167
  CI (99.9%): [7.725, 13.834] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.230 ops/ms
# Warmup Iteration   2: 9.604 ops/ms
# Warmup Iteration   3: 10.126 ops/ms
Iteration   1: 9.997 ops/ms
Iteration   2: 10.168 ops/ms
Iteration   3: 10.088 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.084 ±(99.9%) 1.560 ops/ms [Average]
  (min, avg, max) = (9.997, 10.084, 10.168), stdev = 0.086
  CI (99.9%): [8.524, 11.645] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.009 ops/ms
# Warmup Iteration   2: 7.373 ops/ms
# Warmup Iteration   3: 7.425 ops/ms
Iteration   1: 7.602 ops/ms
Iteration   2: 7.640 ops/ms
Iteration   3: 7.454 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.565 ±(99.9%) 1.794 ops/ms [Average]
  (min, avg, max) = (7.454, 7.565, 7.640), stdev = 0.098
  CI (99.9%): [5.771, 9.359] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.560 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.298 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.164 ±(99.9%) 0.002 ms/op
Iteration   1: 3.183 ±(99.9%) 0.013 ms/op
Iteration   2: 3.103 ±(99.9%) 0.003 ms/op
Iteration   3: 3.178 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.155 ±(99.9%) 0.821 ms/op [Average]
  (min, avg, max) = (3.103, 3.155, 3.183), stdev = 0.045
  CI (99.9%): [2.334, 3.975] (assumes normal distribution)


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
# Warmup Iteration   1: 4.335 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.097 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.002 ms/op
Iteration   1: 2.994 ±(99.9%) 0.002 ms/op
Iteration   2: 2.910 ±(99.9%) 0.002 ms/op
Iteration   3: 3.014 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.973 ±(99.9%) 1.004 ms/op [Average]
  (min, avg, max) = (2.910, 2.973, 3.014), stdev = 0.055
  CI (99.9%): [1.969, 3.977] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.916 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.412 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.193 ±(99.9%) 0.003 ms/op
Iteration   1: 3.136 ±(99.9%) 0.003 ms/op
Iteration   2: 3.182 ±(99.9%) 0.002 ms/op
Iteration   3: 3.133 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.151 ±(99.9%) 0.504 ms/op [Average]
  (min, avg, max) = (3.133, 3.151, 3.182), stdev = 0.028
  CI (99.9%): [2.647, 3.655] (assumes normal distribution)


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
# Warmup Iteration   1: 5.681 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.204 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.210 ±(99.9%) 0.016 ms/op
Iteration   1: 4.170 ±(99.9%) 0.025 ms/op
Iteration   2: 4.190 ±(99.9%) 0.024 ms/op
Iteration   3: 3.996 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.119 ±(99.9%) 1.947 ms/op [Average]
  (min, avg, max) = (3.996, 4.119, 4.190), stdev = 0.107
  CI (99.9%): [2.172, 6.066] (assumes normal distribution)


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
# Warmup Iteration   1: 4.578 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.330 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.146 ±(99.9%) 0.006 ms/op
Iteration   1: 3.148 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.887 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   4.645 ms/op
                 createUser·p0.999:  8.273 ms/op
                 createUser·p0.9999: 13.980 ms/op
                 createUser·p1.00:   14.369 ms/op

Iteration   2: 3.190 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.010 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.133 ms/op
                 createUser·p0.99:   5.022 ms/op
                 createUser·p0.999:  8.002 ms/op
                 createUser·p0.9999: 22.772 ms/op
                 createUser·p1.00:   23.003 ms/op

Iteration   3: 3.088 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.954 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   4.768 ms/op
                 createUser·p0.999:  8.674 ms/op
                 createUser·p0.9999: 16.885 ms/op
                 createUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305490
  mean =      3.141 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15770 
    [ 2.500,  5.000) = 287193 
    [ 5.000,  7.500) = 2016 
    [ 7.500, 10.000) = 286 
    [10.000, 12.500) = 25 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.887 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      3.981 ms/op
     p(99.0000) =      4.866 ms/op
     p(99.9000) =      8.298 ms/op
     p(99.9900) =     21.835 ms/op
     p(99.9990) =     22.936 ms/op
     p(99.9999) =     23.003 ms/op
    p(100.0000) =     23.003 ms/op


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
# Warmup Iteration   1: 4.418 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.157 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.006 ms/op
Iteration   1: 2.975 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.847 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  7.635 ms/op
                 existUser·p0.9999: 12.952 ms/op
                 existUser·p1.00:   13.271 ms/op

Iteration   2: 3.063 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.798 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   4.645 ms/op
                 existUser·p0.999:  8.220 ms/op
                 existUser·p0.9999: 17.730 ms/op
                 existUser·p1.00:   18.022 ms/op

Iteration   3: 3.022 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.688 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.735 ms/op
                 existUser·p0.999:  10.800 ms/op
                 existUser·p0.9999: 18.612 ms/op
                 existUser·p1.00:   18.776 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 317864
  mean =      3.020 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1170 
    [ 1.250,  2.500) = 20815 
    [ 2.500,  3.750) = 280532 
    [ 3.750,  5.000) = 13016 
    [ 5.000,  6.250) = 1052 
    [ 6.250,  7.500) = 628 
    [ 7.500,  8.750) = 287 
    [ 8.750, 10.000) = 100 
    [10.000, 11.250) = 49 
    [11.250, 12.500) = 70 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 43 

  Percentiles, ms/op:
      p(0.0000) =      0.688 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      4.620 ms/op
     p(99.9000) =      9.470 ms/op
     p(99.9900) =     17.957 ms/op
     p(99.9990) =     18.737 ms/op
     p(99.9999) =     18.776 ms/op
    p(100.0000) =     18.776 ms/op


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
# Warmup Iteration   1: 4.394 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.357 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.196 ±(99.9%) 0.006 ms/op
Iteration   1: 3.167 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.990 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   4.891 ms/op
                 getUser·p0.999:  10.290 ms/op
                 getUser·p0.9999: 16.553 ms/op
                 getUser·p1.00:   20.218 ms/op

Iteration   2: 3.107 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.556 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.727 ms/op
                 getUser·p0.999:  8.895 ms/op
                 getUser·p0.9999: 15.440 ms/op
                 getUser·p1.00:   19.792 ms/op

Iteration   3: 3.192 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.919 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   3.994 ms/op
                 getUser·p0.99:   4.915 ms/op
                 getUser·p0.999:  8.416 ms/op
                 getUser·p0.9999: 18.415 ms/op
                 getUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 304156
  mean =      3.155 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11000 
    [ 2.500,  5.000) = 290528 
    [ 5.000,  7.500) = 1980 
    [ 7.500, 10.000) = 338 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.556 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      4.858 ms/op
     p(99.9000) =     10.106 ms/op
     p(99.9900) =     18.107 ms/op
     p(99.9990) =     19.725 ms/op
     p(99.9999) =     20.218 ms/op
    p(100.0000) =     20.218 ms/op


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
# Warmup Iteration   1: 6.269 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.182 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.173 ±(99.9%) 0.014 ms/op
Iteration   1: 4.046 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.958 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   6.144 ms/op
                 listUser·p0.99:   7.365 ms/op
                 listUser·p0.999:  17.365 ms/op
                 listUser·p0.9999: 20.257 ms/op
                 listUser·p1.00:   20.677 ms/op

Iteration   2: 4.148 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.198 ms/op
                 listUser·p0.50:   3.934 ms/op
                 listUser·p0.90:   5.259 ms/op
                 listUser·p0.95:   6.038 ms/op
                 listUser·p0.99:   7.421 ms/op
                 listUser·p0.999:  17.396 ms/op
                 listUser·p0.9999: 29.229 ms/op
                 listUser·p1.00:   30.540 ms/op

Iteration   3: 4.011 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.128 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   7.094 ms/op
                 listUser·p0.999:  15.918 ms/op
                 listUser·p0.9999: 17.827 ms/op
                 listUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235886
  mean =      4.068 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2366 
    [ 2.500,  5.000) = 207357 
    [ 5.000,  7.500) = 24262 
    [ 7.500, 10.000) = 1361 
    [10.000, 12.500) = 158 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 173 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.958 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      5.120 ms/op
     p(95.0000) =      6.021 ms/op
     p(99.0000) =      7.283 ms/op
     p(99.9000) =     16.777 ms/op
     p(99.9900) =     28.869 ms/op
     p(99.9990) =     29.262 ms/op
     p(99.9999) =     30.540 ms/op
    p(100.0000) =     30.540 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.013 ± 2.503  ops/ms
ClientGrpc.existUser                       thrpt       3  10.780 ± 3.055  ops/ms
ClientGrpc.getUser                         thrpt       3  10.084 ± 1.560  ops/ms
ClientGrpc.listUser                        thrpt       3   7.565 ± 1.794  ops/ms
ClientGrpc.createUser                       avgt       3   3.155 ± 0.821   ms/op
ClientGrpc.existUser                        avgt       3   2.973 ± 1.004   ms/op
ClientGrpc.getUser                          avgt       3   3.151 ± 0.504   ms/op
ClientGrpc.listUser                         avgt       3   4.119 ± 1.947   ms/op
ClientGrpc.createUser                     sample  305490   3.141 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.887           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.092           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.715           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.981           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.866           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.298           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.835           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.003           ms/op
ClientGrpc.existUser                      sample  317864   3.020 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.688           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.990           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.494           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.736           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.620           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.470           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.957           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.776           ms/op
ClientGrpc.getUser                        sample  304156   3.155 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.556           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.109           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.666           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.895           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.858           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.106           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.107           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.218           ms/op
ClientGrpc.listUser                       sample  235886   4.068 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.958           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.879           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.120           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.021           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.283           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.777           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.869           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.540           ms/op
