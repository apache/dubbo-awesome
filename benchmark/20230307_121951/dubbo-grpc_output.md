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
# Warmup Iteration   1: 4.649 ops/ms
# Warmup Iteration   2: 8.961 ops/ms
# Warmup Iteration   3: 10.189 ops/ms
Iteration   1: 10.235 ops/ms
Iteration   2: 10.126 ops/ms
Iteration   3: 10.348 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.236 ±(99.9%) 2.023 ops/ms [Average]
  (min, avg, max) = (10.126, 10.236, 10.348), stdev = 0.111
  CI (99.9%): [8.213, 12.259] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.623 ops/ms
# Warmup Iteration   2: 10.400 ops/ms
# Warmup Iteration   3: 10.689 ops/ms
Iteration   1: 10.854 ops/ms
Iteration   2: 10.909 ops/ms
Iteration   3: 10.630 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.797 ±(99.9%) 2.699 ops/ms [Average]
  (min, avg, max) = (10.630, 10.797, 10.909), stdev = 0.148
  CI (99.9%): [8.098, 13.497] (assumes normal distribution)


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
# Warmup Iteration   1: 6.890 ops/ms
# Warmup Iteration   2: 10.218 ops/ms
# Warmup Iteration   3: 10.171 ops/ms
Iteration   1: 10.207 ops/ms
Iteration   2: 10.164 ops/ms
Iteration   3: 10.308 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.226 ±(99.9%) 1.354 ops/ms [Average]
  (min, avg, max) = (10.164, 10.226, 10.308), stdev = 0.074
  CI (99.9%): [8.872, 11.580] (assumes normal distribution)


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
# Warmup Iteration   1: 5.783 ops/ms
# Warmup Iteration   2: 7.554 ops/ms
# Warmup Iteration   3: 8.019 ops/ms
Iteration   1: 8.086 ops/ms
Iteration   2: 7.930 ops/ms
Iteration   3: 8.015 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.010 ±(99.9%) 1.428 ops/ms [Average]
  (min, avg, max) = (7.930, 8.010, 8.086), stdev = 0.078
  CI (99.9%): [6.582, 9.438] (assumes normal distribution)


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
# Warmup Iteration   1: 4.218 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.136 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.107 ±(99.9%) 0.008 ms/op
Iteration   1: 3.103 ±(99.9%) 0.002 ms/op
Iteration   2: 3.088 ±(99.9%) 0.002 ms/op
Iteration   3: 3.097 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.096 ±(99.9%) 0.135 ms/op [Average]
  (min, avg, max) = (3.088, 3.096, 3.103), stdev = 0.007
  CI (99.9%): [2.961, 3.231] (assumes normal distribution)


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
# Warmup Iteration   1: 3.924 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.059 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.956 ±(99.9%) 0.003 ms/op
Iteration   1: 2.920 ±(99.9%) 0.002 ms/op
Iteration   2: 2.909 ±(99.9%) 0.002 ms/op
Iteration   3: 2.930 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.920 ±(99.9%) 0.196 ms/op [Average]
  (min, avg, max) = (2.909, 2.920, 2.930), stdev = 0.011
  CI (99.9%): [2.723, 3.116] (assumes normal distribution)


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
# Warmup Iteration   1: 4.105 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.201 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.090 ±(99.9%) 0.003 ms/op
Iteration   1: 3.031 ±(99.9%) 0.002 ms/op
Iteration   2: 3.088 ±(99.9%) 0.002 ms/op
Iteration   3: 3.135 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.084 ±(99.9%) 0.948 ms/op [Average]
  (min, avg, max) = (3.031, 3.084, 3.135), stdev = 0.052
  CI (99.9%): [2.137, 4.032] (assumes normal distribution)


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
# Warmup Iteration   1: 5.179 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.074 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.101 ±(99.9%) 0.014 ms/op
Iteration   1: 4.042 ±(99.9%) 0.024 ms/op
Iteration   2: 4.012 ±(99.9%) 0.016 ms/op
Iteration   3: 3.902 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.986 ±(99.9%) 1.345 ms/op [Average]
  (min, avg, max) = (3.902, 3.986, 4.042), stdev = 0.074
  CI (99.9%): [2.641, 5.330] (assumes normal distribution)


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
# Warmup Iteration   1: 4.191 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.236 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.093 ±(99.9%) 0.008 ms/op
Iteration   1: 3.067 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.768 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.744 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  6.575 ms/op
                 createUser·p0.9999: 19.628 ms/op
                 createUser·p1.00:   20.775 ms/op

Iteration   2: 3.065 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.664 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   3.939 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  7.428 ms/op
                 createUser·p0.9999: 24.305 ms/op
                 createUser·p1.00:   24.871 ms/op

Iteration   3: 3.091 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.696 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.883 ms/op
                 createUser·p0.99:   4.141 ms/op
                 createUser·p0.999:  9.674 ms/op
                 createUser·p0.9999: 30.396 ms/op
                 createUser·p1.00:   32.408 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312439
  mean =      3.074 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34904 
    [ 2.500,  5.000) = 276688 
    [ 5.000,  7.500) = 522 
    [ 7.500, 10.000) = 97 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.664 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      7.793 ms/op
     p(99.9900) =     29.672 ms/op
     p(99.9990) =     32.170 ms/op
     p(99.9999) =     32.408 ms/op
    p(100.0000) =     32.408 ms/op


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
# Warmup Iteration   1: 3.918 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.973 ±(99.9%) 0.007 ms/op
Iteration   1: 2.925 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.734 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.629 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   4.092 ms/op
                 existUser·p0.999:  6.076 ms/op
                 existUser·p0.9999: 13.143 ms/op
                 existUser·p1.00:   13.517 ms/op

Iteration   2: 2.932 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.846 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   4.096 ms/op
                 existUser·p0.999:  6.397 ms/op
                 existUser·p0.9999: 14.942 ms/op
                 existUser·p1.00:   16.466 ms/op

Iteration   3: 3.011 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.653 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   4.100 ms/op
                 existUser·p0.999:  8.831 ms/op
                 existUser·p0.9999: 16.243 ms/op
                 existUser·p1.00:   16.761 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324694
  mean =      2.955 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1911 
    [ 1.250,  2.500) = 56557 
    [ 2.500,  3.750) = 248099 
    [ 3.750,  5.000) = 17418 
    [ 5.000,  6.250) = 240 
    [ 6.250,  7.500) = 201 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 44 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.096 ms/op
     p(99.9000) =      6.859 ms/op
     p(99.9900) =     15.672 ms/op
     p(99.9990) =     16.400 ms/op
     p(99.9999) =     16.761 ms/op
    p(100.0000) =     16.761 ms/op


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
# Warmup Iteration   1: 4.155 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.266 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.086 ±(99.9%) 0.006 ms/op
Iteration   1: 3.116 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.685 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  6.709 ms/op
                 getUser·p0.9999: 12.980 ms/op
                 getUser·p1.00:   13.566 ms/op

Iteration   2: 3.120 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.673 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.006 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  6.278 ms/op
                 getUser·p0.9999: 15.221 ms/op
                 getUser·p1.00:   16.105 ms/op

Iteration   3: 3.177 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.520 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.879 ms/op
                 getUser·p0.95:   4.051 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  6.460 ms/op
                 getUser·p0.9999: 25.919 ms/op
                 getUser·p1.00:   26.083 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 305899
  mean =      3.138 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28134 
    [ 2.500,  5.000) = 277087 
    [ 5.000,  7.500) = 449 
    [ 7.500, 10.000) = 44 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.520 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.006 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      6.578 ms/op
     p(99.9900) =     25.062 ms/op
     p(99.9990) =     25.985 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


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
# Warmup Iteration   1: 5.439 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.120 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.082 ±(99.9%) 0.011 ms/op
Iteration   1: 4.062 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.939 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.766 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  14.500 ms/op
                 listUser·p0.9999: 15.456 ms/op
                 listUser·p1.00:   16.318 ms/op

Iteration   2: 3.954 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.405 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.480 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  15.010 ms/op
                 listUser·p0.9999: 19.661 ms/op
                 listUser·p1.00:   19.923 ms/op

Iteration   3: 4.067 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.911 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  15.419 ms/op
                 listUser·p0.9999: 23.434 ms/op
                 listUser·p1.00:   27.361 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238248
  mean =      4.027 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2042 
    [ 2.500,  5.000) = 209815 
    [ 5.000,  7.500) = 25150 
    [ 7.500, 10.000) = 801 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.911 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      5.095 ms/op
     p(95.0000) =      5.661 ms/op
     p(99.0000) =      6.889 ms/op
     p(99.9000) =     14.729 ms/op
     p(99.9900) =     23.086 ms/op
     p(99.9990) =     25.808 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.236 ± 2.023  ops/ms
ClientGrpc.existUser                       thrpt       3  10.797 ± 2.699  ops/ms
ClientGrpc.getUser                         thrpt       3  10.226 ± 1.354  ops/ms
ClientGrpc.listUser                        thrpt       3   8.010 ± 1.428  ops/ms
ClientGrpc.createUser                       avgt       3   3.096 ± 0.135   ms/op
ClientGrpc.existUser                        avgt       3   2.920 ± 0.196   ms/op
ClientGrpc.getUser                          avgt       3   3.084 ± 0.948   ms/op
ClientGrpc.listUser                         avgt       3   3.986 ± 1.345   ms/op
ClientGrpc.createUser                     sample  312439   3.074 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.664           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.047           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.727           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.920           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.301           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.793           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.672           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.408           ms/op
ClientGrpc.existUser                      sample  324694   2.955 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.653           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.953           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.617           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.772           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.096           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.859           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.672           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.761           ms/op
ClientGrpc.getUser                        sample  305899   3.138 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.520           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.117           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.834           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.006           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.325           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.578           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.062           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.083           ms/op
ClientGrpc.listUser                       sample  238248   4.027 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.911           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.863           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.095           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.661           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.889           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.729           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.086           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.361           ms/op
