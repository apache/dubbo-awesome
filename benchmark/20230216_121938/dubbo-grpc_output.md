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
# Warmup Iteration   1: 4.386 ops/ms
# Warmup Iteration   2: 9.450 ops/ms
# Warmup Iteration   3: 10.760 ops/ms
Iteration   1: 10.491 ops/ms
Iteration   2: 10.452 ops/ms
Iteration   3: 10.223 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.389 ±(99.9%) 2.647 ops/ms [Average]
  (min, avg, max) = (10.223, 10.389, 10.491), stdev = 0.145
  CI (99.9%): [7.742, 13.035] (assumes normal distribution)


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
# Warmup Iteration   1: 8.518 ops/ms
# Warmup Iteration   2: 10.679 ops/ms
# Warmup Iteration   3: 10.867 ops/ms
Iteration   1: 10.625 ops/ms
Iteration   2: 11.080 ops/ms
Iteration   3: 11.075 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.927 ±(99.9%) 4.769 ops/ms [Average]
  (min, avg, max) = (10.625, 10.927, 11.080), stdev = 0.261
  CI (99.9%): [6.157, 15.696] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.620 ops/ms
# Warmup Iteration   2: 10.260 ops/ms
# Warmup Iteration   3: 10.226 ops/ms
Iteration   1: 10.290 ops/ms
Iteration   2: 10.598 ops/ms
Iteration   3: 10.691 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.526 ±(99.9%) 3.835 ops/ms [Average]
  (min, avg, max) = (10.290, 10.526, 10.691), stdev = 0.210
  CI (99.9%): [6.691, 14.361] (assumes normal distribution)


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
# Warmup Iteration   1: 6.596 ops/ms
# Warmup Iteration   2: 7.616 ops/ms
# Warmup Iteration   3: 8.008 ops/ms
Iteration   1: 8.058 ops/ms
Iteration   2: 7.971 ops/ms
Iteration   3: 7.995 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.008 ±(99.9%) 0.818 ops/ms [Average]
  (min, avg, max) = (7.971, 8.008, 8.058), stdev = 0.045
  CI (99.9%): [7.190, 8.827] (assumes normal distribution)


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
# Warmup Iteration   1: 4.209 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.147 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.002 ms/op
Iteration   1: 3.019 ±(99.9%) 0.002 ms/op
Iteration   2: 3.107 ±(99.9%) 0.002 ms/op
Iteration   3: 3.210 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.112 ±(99.9%) 1.736 ms/op [Average]
  (min, avg, max) = (3.019, 3.112, 3.210), stdev = 0.095
  CI (99.9%): [1.376, 4.848] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.472 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.950 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.919 ±(99.9%) 0.003 ms/op
Iteration   1: 2.880 ±(99.9%) 0.003 ms/op
Iteration   2: 2.978 ±(99.9%) 0.002 ms/op
Iteration   3: 2.848 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.902 ±(99.9%) 1.241 ms/op [Average]
  (min, avg, max) = (2.848, 2.902, 2.978), stdev = 0.068
  CI (99.9%): [1.661, 4.143] (assumes normal distribution)


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
# Warmup Iteration   1: 3.837 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.134 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.022 ±(99.9%) 0.002 ms/op
Iteration   1: 2.993 ±(99.9%) 0.003 ms/op
Iteration   2: 3.088 ±(99.9%) 0.003 ms/op
Iteration   3: 3.114 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.065 ±(99.9%) 1.165 ms/op [Average]
  (min, avg, max) = (2.993, 3.065, 3.114), stdev = 0.064
  CI (99.9%): [1.900, 4.230] (assumes normal distribution)


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
# Warmup Iteration   1: 5.201 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.031 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 3.871 ±(99.9%) 0.008 ms/op
Iteration   1: 4.041 ±(99.9%) 0.032 ms/op
Iteration   2: 3.975 ±(99.9%) 0.019 ms/op
Iteration   3: 3.943 ±(99.9%) 0.032 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.986 ±(99.9%) 0.916 ms/op [Average]
  (min, avg, max) = (3.943, 3.986, 4.041), stdev = 0.050
  CI (99.9%): [3.071, 4.902] (assumes normal distribution)


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
# Warmup Iteration   1: 3.971 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.006 ms/op
Iteration   1: 2.979 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.722 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.355 ms/op
                 createUser·p0.95:   3.478 ms/op
                 createUser·p0.99:   3.961 ms/op
                 createUser·p0.999:  10.256 ms/op
                 createUser·p0.9999: 11.064 ms/op
                 createUser·p1.00:   11.370 ms/op

Iteration   2: 3.093 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.709 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   4.202 ms/op
                 createUser·p0.999:  7.719 ms/op
                 createUser·p0.9999: 17.147 ms/op
                 createUser·p1.00:   17.564 ms/op

Iteration   3: 2.961 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.441 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.441 ms/op
                 createUser·p0.95:   3.707 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  8.569 ms/op
                 createUser·p0.9999: 16.368 ms/op
                 createUser·p1.00:   16.810 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318842
  mean =      3.010 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3031 
    [ 1.250,  2.500) = 22927 
    [ 2.500,  3.750) = 276138 
    [ 3.750,  5.000) = 15787 
    [ 5.000,  6.250) = 448 
    [ 6.250,  7.500) = 142 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 123 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 48 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.441 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      8.909 ms/op
     p(99.9900) =     16.501 ms/op
     p(99.9990) =     17.492 ms/op
     p(99.9999) =     17.564 ms/op
    p(100.0000) =     17.564 ms/op


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
# Warmup Iteration   1: 3.811 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.011 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.891 ±(99.9%) 0.007 ms/op
Iteration   1: 2.980 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.666 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   3.850 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  5.333 ms/op
                 existUser·p0.9999: 11.305 ms/op
                 existUser·p1.00:   12.026 ms/op

Iteration   2: 2.874 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.581 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.456 ms/op
                 existUser·p0.999:  7.911 ms/op
                 existUser·p0.9999: 20.541 ms/op
                 existUser·p1.00:   20.939 ms/op

Iteration   3: 3.011 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.743 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   4.129 ms/op
                 existUser·p0.999:  6.469 ms/op
                 existUser·p0.9999: 14.162 ms/op
                 existUser·p1.00:   14.926 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324794
  mean =      2.954 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51172 
    [ 2.500,  5.000) = 272822 
    [ 5.000,  7.500) = 531 
    [ 7.500, 10.000) = 45 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.581 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      6.483 ms/op
     p(99.9900) =     17.727 ms/op
     p(99.9990) =     20.751 ms/op
     p(99.9999) =     20.939 ms/op
    p(100.0000) =     20.939 ms/op


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
# Warmup Iteration   1: 4.039 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.151 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.093 ±(99.9%) 0.006 ms/op
Iteration   1: 3.033 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.672 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.858 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  6.449 ms/op
                 getUser·p0.9999: 12.009 ms/op
                 getUser·p1.00:   12.304 ms/op

Iteration   2: 2.985 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.632 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  6.830 ms/op
                 getUser·p0.9999: 16.744 ms/op
                 getUser·p1.00:   17.039 ms/op

Iteration   3: 3.083 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.535 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.858 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  5.944 ms/op
                 getUser·p0.9999: 25.383 ms/op
                 getUser·p1.00:   25.690 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316360
  mean =      3.033 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28693 
    [ 2.500,  5.000) = 286802 
    [ 5.000,  7.500) = 663 
    [ 7.500, 10.000) = 10 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.535 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      6.562 ms/op
     p(99.9900) =     24.546 ms/op
     p(99.9990) =     25.614 ms/op
     p(99.9999) =     25.690 ms/op
    p(100.0000) =     25.690 ms/op


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
# Warmup Iteration   1: 4.536 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.200 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.054 ±(99.9%) 0.011 ms/op
Iteration   1: 4.066 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.397 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  12.424 ms/op
                 listUser·p0.9999: 15.098 ms/op
                 listUser·p1.00:   15.516 ms/op

Iteration   2: 3.957 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.194 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  12.701 ms/op
                 listUser·p0.9999: 15.876 ms/op
                 listUser·p1.00:   16.318 ms/op

Iteration   3: 4.022 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.053 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  14.752 ms/op
                 listUser·p0.9999: 24.282 ms/op
                 listUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239114
  mean =      4.015 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3079 
    [ 2.500,  5.000) = 209791 
    [ 5.000,  7.500) = 25191 
    [ 7.500, 10.000) = 674 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 192 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      5.071 ms/op
     p(95.0000) =      5.620 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     12.943 ms/op
     p(99.9900) =     21.832 ms/op
     p(99.9990) =     24.577 ms/op
     p(99.9999) =     24.707 ms/op
    p(100.0000) =     24.707 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.389 ± 2.647  ops/ms
ClientGrpc.existUser                       thrpt       3  10.927 ± 4.769  ops/ms
ClientGrpc.getUser                         thrpt       3  10.526 ± 3.835  ops/ms
ClientGrpc.listUser                        thrpt       3   8.008 ± 0.818  ops/ms
ClientGrpc.createUser                       avgt       3   3.112 ± 1.736   ms/op
ClientGrpc.existUser                        avgt       3   2.902 ± 1.241   ms/op
ClientGrpc.getUser                          avgt       3   3.065 ± 1.165   ms/op
ClientGrpc.listUser                         avgt       3   3.986 ± 0.916   ms/op
ClientGrpc.createUser                     sample  318842   3.010 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.441           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.019           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.527           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.764           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.211           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.909           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.501           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.564           ms/op
ClientGrpc.existUser                      sample  324794   2.954 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.581           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.937           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.600           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.789           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.243           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.483           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.727           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.939           ms/op
ClientGrpc.getUser                        sample  316360   3.033 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.535           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.039           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.617           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.838           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.309           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.562           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.546           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.690           ms/op
ClientGrpc.listUser                       sample  239114   4.015 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.053           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.858           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.071           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.620           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.791           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.943           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.832           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.707           ms/op
