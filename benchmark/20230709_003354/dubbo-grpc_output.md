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
# Warmup Iteration   1: 4.151 ops/ms
# Warmup Iteration   2: 8.626 ops/ms
# Warmup Iteration   3: 10.007 ops/ms
Iteration   1: 10.087 ops/ms
Iteration   2: 10.520 ops/ms
Iteration   3: 10.639 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.415 ±(99.9%) 5.303 ops/ms [Average]
  (min, avg, max) = (10.087, 10.415, 10.639), stdev = 0.291
  CI (99.9%): [5.112, 15.718] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.364 ops/ms
# Warmup Iteration   2: 10.291 ops/ms
# Warmup Iteration   3: 10.680 ops/ms
Iteration   1: 10.851 ops/ms
Iteration   2: 10.951 ops/ms
Iteration   3: 11.134 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.978 ±(99.9%) 2.618 ops/ms [Average]
  (min, avg, max) = (10.851, 10.978, 11.134), stdev = 0.144
  CI (99.9%): [8.360, 13.597] (assumes normal distribution)


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
# Warmup Iteration   1: 6.944 ops/ms
# Warmup Iteration   2: 9.812 ops/ms
# Warmup Iteration   3: 10.258 ops/ms
Iteration   1: 10.348 ops/ms
Iteration   2: 10.108 ops/ms
Iteration   3: 10.133 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.197 ±(99.9%) 2.410 ops/ms [Average]
  (min, avg, max) = (10.108, 10.197, 10.348), stdev = 0.132
  CI (99.9%): [7.787, 12.606] (assumes normal distribution)


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
# Warmup Iteration   1: 6.328 ops/ms
# Warmup Iteration   2: 7.063 ops/ms
# Warmup Iteration   3: 7.762 ops/ms
Iteration   1: 7.709 ops/ms
Iteration   2: 7.786 ops/ms
Iteration   3: 7.956 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.817 ±(99.9%) 2.306 ops/ms [Average]
  (min, avg, max) = (7.709, 7.817, 7.956), stdev = 0.126
  CI (99.9%): [5.512, 10.123] (assumes normal distribution)


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
# Warmup Iteration   1: 4.771 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.354 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.139 ±(99.9%) 0.003 ms/op
Iteration   1: 3.119 ±(99.9%) 0.002 ms/op
Iteration   2: 3.208 ±(99.9%) 0.002 ms/op
Iteration   3: 3.163 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.163 ±(99.9%) 0.806 ms/op [Average]
  (min, avg, max) = (3.119, 3.163, 3.208), stdev = 0.044
  CI (99.9%): [2.357, 3.970] (assumes normal distribution)


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
# Warmup Iteration   1: 4.272 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.078 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.961 ±(99.9%) 0.003 ms/op
Iteration   1: 2.960 ±(99.9%) 0.002 ms/op
Iteration   2: 2.991 ±(99.9%) 0.002 ms/op
Iteration   3: 3.033 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.995 ±(99.9%) 0.675 ms/op [Average]
  (min, avg, max) = (2.960, 2.995, 3.033), stdev = 0.037
  CI (99.9%): [2.320, 3.670] (assumes normal distribution)


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
# Warmup Iteration   1: 4.510 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.212 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.122 ±(99.9%) 0.004 ms/op
Iteration   1: 3.149 ±(99.9%) 0.002 ms/op
Iteration   2: 3.135 ±(99.9%) 0.003 ms/op
Iteration   3: 3.179 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.154 ±(99.9%) 0.408 ms/op [Average]
  (min, avg, max) = (3.135, 3.154, 3.179), stdev = 0.022
  CI (99.9%): [2.747, 3.562] (assumes normal distribution)


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
# Warmup Iteration   1: 5.477 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.323 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.189 ±(99.9%) 0.009 ms/op
Iteration   1: 4.214 ±(99.9%) 0.016 ms/op
Iteration   2: 4.034 ±(99.9%) 0.010 ms/op
Iteration   3: 4.104 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.117 ±(99.9%) 1.659 ms/op [Average]
  (min, avg, max) = (4.034, 4.117, 4.214), stdev = 0.091
  CI (99.9%): [2.458, 5.777] (assumes normal distribution)


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
# Warmup Iteration   1: 4.962 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.392 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.155 ±(99.9%) 0.006 ms/op
Iteration   1: 3.180 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.941 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   4.620 ms/op
                 createUser·p0.999:  8.183 ms/op
                 createUser·p0.9999: 13.482 ms/op
                 createUser·p1.00:   13.910 ms/op

Iteration   2: 3.103 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.821 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  11.305 ms/op
                 createUser·p0.9999: 14.889 ms/op
                 createUser·p1.00:   15.417 ms/op

Iteration   3: 3.050 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.618 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.613 ms/op
                 createUser·p0.99:   4.145 ms/op
                 createUser·p0.999:  11.976 ms/op
                 createUser·p0.9999: 26.477 ms/op
                 createUser·p1.00:   26.706 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308624
  mean =      3.110 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13076 
    [ 2.500,  5.000) = 293947 
    [ 5.000,  7.500) = 1126 
    [ 7.500, 10.000) = 168 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 143 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.618 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      9.288 ms/op
     p(99.9900) =     24.642 ms/op
     p(99.9990) =     26.640 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


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
# Warmup Iteration   1: 3.947 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.088 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.005 ms/op
Iteration   1: 2.977 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.690 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  8.526 ms/op
                 existUser·p0.9999: 14.983 ms/op
                 existUser·p1.00:   21.529 ms/op

Iteration   2: 2.959 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.852 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  6.553 ms/op
                 existUser·p0.9999: 14.604 ms/op
                 existUser·p1.00:   15.024 ms/op

Iteration   3: 2.975 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.673 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  6.982 ms/op
                 existUser·p0.9999: 16.051 ms/op
                 existUser·p1.00:   16.630 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323370
  mean =      2.970 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20141 
    [ 2.500,  5.000) = 301912 
    [ 5.000,  7.500) = 984 
    [ 7.500, 10.000) = 165 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.673 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.387 ms/op
     p(95.0000) =      3.617 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      7.621 ms/op
     p(99.9900) =     14.997 ms/op
     p(99.9990) =     16.569 ms/op
     p(99.9999) =     21.529 ms/op
    p(100.0000) =     21.529 ms/op


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
# Warmup Iteration   1: 4.347 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.206 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.158 ±(99.9%) 0.007 ms/op
Iteration   1: 3.103 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.600 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.645 ms/op
                 getUser·p0.999:  7.086 ms/op
                 getUser·p0.9999: 18.635 ms/op
                 getUser·p1.00:   19.137 ms/op

Iteration   2: 3.069 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.697 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.690 ms/op
                 getUser·p0.99:   4.701 ms/op
                 getUser·p0.999:  7.502 ms/op
                 getUser·p0.9999: 17.039 ms/op
                 getUser·p1.00:   17.269 ms/op

Iteration   3: 3.079 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.322 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.562 ms/op
                 getUser·p0.999:  6.414 ms/op
                 getUser·p0.9999: 16.993 ms/op
                 getUser·p1.00:   17.465 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311376
  mean =      3.084 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 605 
    [ 1.250,  2.500) = 13887 
    [ 2.500,  3.750) = 280299 
    [ 3.750,  5.000) = 14627 
    [ 5.000,  6.250) = 1290 
    [ 6.250,  7.500) = 444 
    [ 7.500,  8.750) = 60 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 38 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.322 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.628 ms/op
     p(99.9000) =      6.960 ms/op
     p(99.9900) =     17.494 ms/op
     p(99.9990) =     18.998 ms/op
     p(99.9999) =     19.137 ms/op
    p(100.0000) =     19.137 ms/op


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
# Warmup Iteration   1: 4.744 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.216 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.046 ±(99.9%) 0.011 ms/op
Iteration   1: 4.069 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.007 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  14.031 ms/op
                 listUser·p0.9999: 23.583 ms/op
                 listUser·p1.00:   24.019 ms/op

Iteration   2: 4.021 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.971 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.743 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  14.768 ms/op
                 listUser·p0.9999: 22.908 ms/op
                 listUser·p1.00:   23.396 ms/op

Iteration   3: 4.057 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.296 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   5.964 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  20.513 ms/op
                 listUser·p0.9999: 29.036 ms/op
                 listUser·p1.00:   29.491 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237005
  mean =      4.049 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2668 
    [ 2.500,  5.000) = 211570 
    [ 5.000,  7.500) = 21393 
    [ 7.500, 10.000) = 882 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 161 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.971 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      4.956 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =      7.012 ms/op
     p(99.9000) =     15.188 ms/op
     p(99.9900) =     28.584 ms/op
     p(99.9990) =     29.381 ms/op
     p(99.9999) =     29.491 ms/op
    p(100.0000) =     29.491 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.415 ± 5.303  ops/ms
ClientGrpc.existUser                       thrpt       3  10.978 ± 2.618  ops/ms
ClientGrpc.getUser                         thrpt       3  10.197 ± 2.410  ops/ms
ClientGrpc.listUser                        thrpt       3   7.817 ± 2.306  ops/ms
ClientGrpc.createUser                       avgt       3   3.163 ± 0.806   ms/op
ClientGrpc.existUser                        avgt       3   2.995 ± 0.675   ms/op
ClientGrpc.getUser                          avgt       3   3.154 ± 0.408   ms/op
ClientGrpc.listUser                         avgt       3   4.117 ± 1.659   ms/op
ClientGrpc.createUser                     sample  308624   3.110 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.618           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.076           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.621           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.822           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.288           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.642           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.706           ms/op
ClientGrpc.existUser                      sample  323370   2.970 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.673           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.945           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.387           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.617           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.301           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.621           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.997           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.529           ms/op
ClientGrpc.getUser                        sample  311376   3.084 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.322           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.056           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.555           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.772           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.628           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.960           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.494           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.137           ms/op
ClientGrpc.listUser                       sample  237005   4.049 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.971           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.899           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.956           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.743           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.012           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.188           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.584           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.491           ms/op
