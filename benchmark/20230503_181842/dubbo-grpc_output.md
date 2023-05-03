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
# Warmup Iteration   1: 3.812 ops/ms
# Warmup Iteration   2: 8.458 ops/ms
# Warmup Iteration   3: 9.783 ops/ms
Iteration   1: 9.832 ops/ms
Iteration   2: 10.166 ops/ms
Iteration   3: 10.395 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.131 ±(99.9%) 5.159 ops/ms [Average]
  (min, avg, max) = (9.832, 10.131, 10.395), stdev = 0.283
  CI (99.9%): [4.972, 15.290] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.911 ops/ms
# Warmup Iteration   2: 10.176 ops/ms
# Warmup Iteration   3: 10.785 ops/ms
Iteration   1: 11.038 ops/ms
Iteration   2: 10.636 ops/ms
Iteration   3: 10.968 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.881 ±(99.9%) 3.917 ops/ms [Average]
  (min, avg, max) = (10.636, 10.881, 11.038), stdev = 0.215
  CI (99.9%): [6.964, 14.798] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.596 ops/ms
# Warmup Iteration   2: 9.916 ops/ms
# Warmup Iteration   3: 10.312 ops/ms
Iteration   1: 10.393 ops/ms
Iteration   2: 10.382 ops/ms
Iteration   3: 10.189 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.321 ±(99.9%) 2.090 ops/ms [Average]
  (min, avg, max) = (10.189, 10.321, 10.393), stdev = 0.115
  CI (99.9%): [8.231, 12.412] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.297 ops/ms
# Warmup Iteration   2: 7.227 ops/ms
# Warmup Iteration   3: 7.623 ops/ms
Iteration   1: 7.793 ops/ms
Iteration   2: 7.875 ops/ms
Iteration   3: 7.721 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.796 ±(99.9%) 1.411 ops/ms [Average]
  (min, avg, max) = (7.721, 7.796, 7.875), stdev = 0.077
  CI (99.9%): [6.385, 9.208] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.420 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.350 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.004 ms/op
Iteration   1: 3.107 ±(99.9%) 0.002 ms/op
Iteration   2: 3.208 ±(99.9%) 0.002 ms/op
Iteration   3: 3.093 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.136 ±(99.9%) 1.139 ms/op [Average]
  (min, avg, max) = (3.093, 3.136, 3.208), stdev = 0.062
  CI (99.9%): [1.997, 4.275] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.377 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.105 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.966 ±(99.9%) 0.003 ms/op
Iteration   1: 3.057 ±(99.9%) 0.002 ms/op
Iteration   2: 2.981 ±(99.9%) 0.003 ms/op
Iteration   3: 2.996 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.011 ±(99.9%) 0.736 ms/op [Average]
  (min, avg, max) = (2.981, 3.011, 3.057), stdev = 0.040
  CI (99.9%): [2.275, 3.748] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.597 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.183 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.168 ±(99.9%) 0.003 ms/op
Iteration   1: 3.194 ±(99.9%) 0.002 ms/op
Iteration   2: 3.175 ±(99.9%) 0.003 ms/op
Iteration   3: 3.117 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.162 ±(99.9%) 0.736 ms/op [Average]
  (min, avg, max) = (3.117, 3.162, 3.194), stdev = 0.040
  CI (99.9%): [2.426, 3.898] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.528 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.167 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.214 ±(99.9%) 0.021 ms/op
Iteration   1: 4.075 ±(99.9%) 0.014 ms/op
Iteration   2: 3.950 ±(99.9%) 0.013 ms/op
Iteration   3: 4.078 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.034 ±(99.9%) 1.329 ms/op [Average]
  (min, avg, max) = (3.950, 4.034, 4.078), stdev = 0.073
  CI (99.9%): [2.706, 5.363] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.540 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.360 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.135 ±(99.9%) 0.007 ms/op
Iteration   1: 3.082 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.946 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   4.686 ms/op
                 createUser·p0.999:  10.428 ms/op
                 createUser·p0.9999: 16.994 ms/op
                 createUser·p1.00:   18.121 ms/op

Iteration   2: 3.081 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.873 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   4.596 ms/op
                 createUser·p0.999:  10.247 ms/op
                 createUser·p0.9999: 19.386 ms/op
                 createUser·p1.00:   19.497 ms/op

Iteration   3: 3.130 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.643 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   4.153 ms/op
                 createUser·p0.99:   5.145 ms/op
                 createUser·p0.999:  8.191 ms/op
                 createUser·p0.9999: 22.537 ms/op
                 createUser·p1.00:   23.888 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309725
  mean =      3.098 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21060 
    [ 2.500,  5.000) = 286071 
    [ 5.000,  7.500) = 2011 
    [ 7.500, 10.000) = 276 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.643 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      4.850 ms/op
     p(99.9000) =      9.978 ms/op
     p(99.9900) =     21.645 ms/op
     p(99.9990) =     22.735 ms/op
     p(99.9999) =     23.888 ms/op
    p(100.0000) =     23.888 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.086 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.107 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.007 ms/op
Iteration   1: 2.954 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.885 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.571 ms/op
                 existUser·p0.999:  7.956 ms/op
                 existUser·p0.9999: 14.339 ms/op
                 existUser·p1.00:   14.926 ms/op

Iteration   2: 2.984 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.713 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.580 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   4.973 ms/op
                 existUser·p0.999:  9.023 ms/op
                 existUser·p0.9999: 16.744 ms/op
                 existUser·p1.00:   17.072 ms/op

Iteration   3: 3.053 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.694 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.912 ms/op
                 existUser·p0.99:   5.489 ms/op
                 existUser·p0.999:  11.387 ms/op
                 existUser·p0.9999: 21.561 ms/op
                 existUser·p1.00:   21.823 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 320336
  mean =      2.996 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31477 
    [ 2.500,  5.000) = 285598 
    [ 5.000,  7.500) = 2551 
    [ 7.500, 10.000) = 424 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.694 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      5.022 ms/op
     p(99.9000) =      8.907 ms/op
     p(99.9900) =     19.431 ms/op
     p(99.9990) =     21.751 ms/op
     p(99.9999) =     21.823 ms/op
    p(100.0000) =     21.823 ms/op


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
# Warmup Iteration   1: 4.358 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.404 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.120 ±(99.9%) 0.006 ms/op
Iteration   1: 3.131 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.678 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   3.953 ms/op
                 getUser·p0.99:   4.781 ms/op
                 getUser·p0.999:  9.119 ms/op
                 getUser·p0.9999: 13.900 ms/op
                 getUser·p1.00:   14.156 ms/op

Iteration   2: 3.129 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.694 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   4.039 ms/op
                 getUser·p0.99:   5.120 ms/op
                 getUser·p0.999:  10.632 ms/op
                 getUser·p0.9999: 16.222 ms/op
                 getUser·p1.00:   16.712 ms/op

Iteration   3: 3.107 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.787 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   4.002 ms/op
                 getUser·p0.99:   5.038 ms/op
                 getUser·p0.999:  10.004 ms/op
                 getUser·p0.9999: 18.354 ms/op
                 getUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 307314
  mean =      3.122 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 506 
    [ 1.250,  2.500) = 19807 
    [ 2.500,  3.750) = 257861 
    [ 3.750,  5.000) = 26102 
    [ 5.000,  6.250) = 1757 
    [ 6.250,  7.500) = 698 
    [ 7.500,  8.750) = 196 
    [ 8.750, 10.000) = 115 
    [10.000, 11.250) = 43 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 59 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.678 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      4.989 ms/op
     p(99.9000) =      9.699 ms/op
     p(99.9900) =     17.236 ms/op
     p(99.9990) =     19.202 ms/op
     p(99.9999) =     19.235 ms/op
    p(100.0000) =     19.235 ms/op


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
# Warmup Iteration   1: 5.316 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.550 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.180 ±(99.9%) 0.012 ms/op
Iteration   1: 4.093 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.826 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   5.259 ms/op
                 listUser·p0.95:   6.111 ms/op
                 listUser·p0.99:   7.807 ms/op
                 listUser·p0.999:  14.254 ms/op
                 listUser·p0.9999: 20.289 ms/op
                 listUser·p1.00:   20.709 ms/op

Iteration   2: 4.087 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.067 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.259 ms/op
                 listUser·p0.95:   5.988 ms/op
                 listUser·p0.99:   7.569 ms/op
                 listUser·p0.999:  20.406 ms/op
                 listUser·p0.9999: 28.696 ms/op
                 listUser·p1.00:   29.655 ms/op

Iteration   3: 4.061 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.188 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   6.013 ms/op
                 listUser·p0.99:   7.545 ms/op
                 listUser·p0.999:  19.112 ms/op
                 listUser·p0.9999: 25.297 ms/op
                 listUser·p1.00:   26.804 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235228
  mean =      4.080 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2873 
    [ 2.500,  5.000) = 202325 
    [ 5.000,  7.500) = 27366 
    [ 7.500, 10.000) = 2005 
    [10.000, 12.500) = 267 
    [12.500, 15.000) = 120 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      0.826 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      5.235 ms/op
     p(95.0000) =      6.038 ms/op
     p(99.0000) =      7.643 ms/op
     p(99.9000) =     18.547 ms/op
     p(99.9900) =     26.770 ms/op
     p(99.9990) =     29.545 ms/op
     p(99.9999) =     29.655 ms/op
    p(100.0000) =     29.655 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.131 ± 5.159  ops/ms
ClientGrpc.existUser                       thrpt       3  10.881 ± 3.917  ops/ms
ClientGrpc.getUser                         thrpt       3  10.321 ± 2.090  ops/ms
ClientGrpc.listUser                        thrpt       3   7.796 ± 1.411  ops/ms
ClientGrpc.createUser                       avgt       3   3.136 ± 1.139   ms/op
ClientGrpc.existUser                        avgt       3   3.011 ± 0.736   ms/op
ClientGrpc.getUser                          avgt       3   3.162 ± 0.736   ms/op
ClientGrpc.listUser                         avgt       3   4.034 ± 1.329   ms/op
ClientGrpc.createUser                     sample  309725   3.098 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.643           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.039           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.670           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.949           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.850           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.978           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.645           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.888           ms/op
ClientGrpc.existUser                      sample  320336   2.996 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.694           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.937           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.514           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.817           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.022           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.907           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.431           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.823           ms/op
ClientGrpc.getUser                        sample  307314   3.122 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.678           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.072           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.731           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.994           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.989           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.699           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.236           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.235           ms/op
ClientGrpc.listUser                       sample  235228   4.080 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.826           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.867           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.235           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.038           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.643           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.547           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.770           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.655           ms/op
