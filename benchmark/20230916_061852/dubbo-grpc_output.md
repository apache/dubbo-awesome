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
# Warmup Iteration   1: 3.795 ops/ms
# Warmup Iteration   2: 8.100 ops/ms
# Warmup Iteration   3: 9.513 ops/ms
Iteration   1: 9.996 ops/ms
Iteration   2: 10.252 ops/ms
Iteration   3: 10.121 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.123 ±(99.9%) 2.332 ops/ms [Average]
  (min, avg, max) = (9.996, 10.123, 10.252), stdev = 0.128
  CI (99.9%): [7.791, 12.455] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 6.696 ops/ms
# Warmup Iteration   2: 10.019 ops/ms
# Warmup Iteration   3: 10.559 ops/ms
Iteration   1: 10.821 ops/ms
Iteration   2: 10.661 ops/ms
Iteration   3: 10.713 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.732 ±(99.9%) 1.496 ops/ms [Average]
  (min, avg, max) = (10.661, 10.732, 10.821), stdev = 0.082
  CI (99.9%): [9.235, 12.228] (assumes normal distribution)


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
# Warmup Iteration   1: 6.368 ops/ms
# Warmup Iteration   2: 9.919 ops/ms
# Warmup Iteration   3: 9.990 ops/ms
Iteration   1: 10.134 ops/ms
Iteration   2: 10.162 ops/ms
Iteration   3: 10.213 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.170 ±(99.9%) 0.727 ops/ms [Average]
  (min, avg, max) = (10.134, 10.170, 10.213), stdev = 0.040
  CI (99.9%): [9.443, 10.897] (assumes normal distribution)


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
# Warmup Iteration   1: 5.021 ops/ms
# Warmup Iteration   2: 7.785 ops/ms
# Warmup Iteration   3: 8.104 ops/ms
Iteration   1: 7.963 ops/ms
Iteration   2: 7.957 ops/ms
Iteration   3: 8.076 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.999 ±(99.9%) 1.216 ops/ms [Average]
  (min, avg, max) = (7.957, 7.999, 8.076), stdev = 0.067
  CI (99.9%): [6.782, 9.215] (assumes normal distribution)


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
# Warmup Iteration   1: 4.555 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.281 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.188 ±(99.9%) 0.002 ms/op
Iteration   1: 3.115 ±(99.9%) 0.002 ms/op
Iteration   2: 3.168 ±(99.9%) 0.001 ms/op
Iteration   3: 3.131 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.138 ±(99.9%) 0.496 ms/op [Average]
  (min, avg, max) = (3.115, 3.138, 3.168), stdev = 0.027
  CI (99.9%): [2.642, 3.634] (assumes normal distribution)


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
# Warmup Iteration   1: 4.264 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.110 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.071 ±(99.9%) 0.002 ms/op
Iteration   1: 3.030 ±(99.9%) 0.002 ms/op
Iteration   2: 3.070 ±(99.9%) 0.001 ms/op
Iteration   3: 3.038 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.046 ±(99.9%) 0.382 ms/op [Average]
  (min, avg, max) = (3.030, 3.046, 3.070), stdev = 0.021
  CI (99.9%): [2.664, 3.428] (assumes normal distribution)


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
# Warmup Iteration   1: 4.436 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.277 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.160 ±(99.9%) 0.002 ms/op
Iteration   1: 3.084 ±(99.9%) 0.003 ms/op
Iteration   2: 3.163 ±(99.9%) 0.002 ms/op
Iteration   3: 3.112 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.120 ±(99.9%) 0.724 ms/op [Average]
  (min, avg, max) = (3.084, 3.120, 3.163), stdev = 0.040
  CI (99.9%): [2.396, 3.843] (assumes normal distribution)


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
# Warmup Iteration   1: 6.007 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.082 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.019 ±(99.9%) 0.020 ms/op
Iteration   1: 4.001 ±(99.9%) 0.015 ms/op
Iteration   2: 3.951 ±(99.9%) 0.020 ms/op
Iteration   3: 3.956 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.970 ±(99.9%) 0.497 ms/op [Average]
  (min, avg, max) = (3.951, 3.970, 4.001), stdev = 0.027
  CI (99.9%): [3.472, 4.467] (assumes normal distribution)


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
# Warmup Iteration   1: 4.470 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.329 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.182 ±(99.9%) 0.006 ms/op
Iteration   1: 3.144 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.692 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   4.588 ms/op
                 createUser·p0.999:  8.259 ms/op
                 createUser·p0.9999: 13.320 ms/op
                 createUser·p1.00:   13.730 ms/op

Iteration   2: 3.125 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.744 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  7.109 ms/op
                 createUser·p0.9999: 15.204 ms/op
                 createUser·p1.00:   15.729 ms/op

Iteration   3: 3.188 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.634 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.744 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   4.743 ms/op
                 createUser·p0.999:  8.372 ms/op
                 createUser·p0.9999: 19.004 ms/op
                 createUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 304519
  mean =      3.152 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 292 
    [ 1.250,  2.500) = 8519 
    [ 2.500,  3.750) = 270772 
    [ 3.750,  5.000) = 22892 
    [ 5.000,  6.250) = 1140 
    [ 6.250,  7.500) = 498 
    [ 7.500,  8.750) = 162 
    [ 8.750, 10.000) = 16 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 82 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 33 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.634 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =      8.081 ms/op
     p(99.9900) =     17.642 ms/op
     p(99.9990) =     19.330 ms/op
     p(99.9999) =     19.464 ms/op
    p(100.0000) =     19.464 ms/op


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
# Warmup Iteration   1: 4.127 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.201 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.005 ms/op
Iteration   1: 3.004 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.894 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   4.062 ms/op
                 existUser·p0.999:  6.504 ms/op
                 existUser·p0.9999: 12.961 ms/op
                 existUser·p1.00:   13.337 ms/op

Iteration   2: 3.057 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.721 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  8.831 ms/op
                 existUser·p0.9999: 14.148 ms/op
                 existUser·p1.00:   15.270 ms/op

Iteration   3: 3.034 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.570 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  7.995 ms/op
                 existUser·p0.9999: 15.327 ms/op
                 existUser·p1.00:   15.581 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 316628
  mean =      3.032 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 432 
    [ 1.250,  2.500) = 18356 
    [ 2.500,  3.750) = 282322 
    [ 3.750,  5.000) = 14225 
    [ 5.000,  6.250) = 590 
    [ 6.250,  7.500) = 304 
    [ 7.500,  8.750) = 151 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 45 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.570 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      8.110 ms/op
     p(99.9900) =     15.221 ms/op
     p(99.9990) =     15.510 ms/op
     p(99.9999) =     15.581 ms/op
    p(100.0000) =     15.581 ms/op


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
# Warmup Iteration   1: 4.602 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.347 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.204 ±(99.9%) 0.008 ms/op
Iteration   1: 3.209 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.730 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.030 ms/op
                 getUser·p0.99:   4.719 ms/op
                 getUser·p0.999:  7.258 ms/op
                 getUser·p0.9999: 22.315 ms/op
                 getUser·p1.00:   23.593 ms/op

Iteration   2: 3.105 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.285 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  7.449 ms/op
                 getUser·p0.9999: 25.320 ms/op
                 getUser·p1.00:   26.542 ms/op

Iteration   3: 3.153 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.924 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   4.735 ms/op
                 getUser·p0.999:  7.504 ms/op
                 getUser·p0.9999: 26.294 ms/op
                 getUser·p1.00:   27.296 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 304056
  mean =      3.155 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11917 
    [ 2.500,  5.000) = 290059 
    [ 5.000,  7.500) = 1797 
    [ 7.500, 10.000) = 123 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 68 

  Percentiles, ms/op:
      p(0.0000) =      0.285 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      4.628 ms/op
     p(99.9000) =      7.414 ms/op
     p(99.9900) =     25.480 ms/op
     p(99.9990) =     26.574 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


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
# Warmup Iteration   1: 5.876 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.119 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.020 ±(99.9%) 0.009 ms/op
Iteration   1: 3.938 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.411 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   5.407 ms/op
                 listUser·p0.99:   6.854 ms/op
                 listUser·p0.999:  12.424 ms/op
                 listUser·p0.9999: 16.489 ms/op
                 listUser·p1.00:   17.400 ms/op

Iteration   2: 4.001 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.348 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   5.480 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  15.122 ms/op
                 listUser·p0.9999: 17.072 ms/op
                 listUser·p1.00:   18.317 ms/op

Iteration   3: 3.918 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.473 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.899 ms/op
                 listUser·p0.99:   6.829 ms/op
                 listUser·p0.999:  16.543 ms/op
                 listUser·p0.9999: 19.033 ms/op
                 listUser·p1.00:   19.104 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242891
  mean =      3.952 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1705 
    [ 2.500,  3.750) = 97112 
    [ 3.750,  5.000) = 128941 
    [ 5.000,  6.250) = 9355 
    [ 6.250,  7.500) = 4446 
    [ 7.500,  8.750) = 720 
    [ 8.750, 10.000) = 114 
    [10.000, 11.250) = 120 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 60 
    [15.000, 16.250) = 97 
    [16.250, 17.500) = 101 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.348 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      5.308 ms/op
     p(99.0000) =      6.873 ms/op
     p(99.9000) =     15.008 ms/op
     p(99.9900) =     18.907 ms/op
     p(99.9990) =     19.071 ms/op
     p(99.9999) =     19.104 ms/op
    p(100.0000) =     19.104 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.123 ± 2.332  ops/ms
ClientGrpc.existUser                       thrpt       3  10.732 ± 1.496  ops/ms
ClientGrpc.getUser                         thrpt       3  10.170 ± 0.727  ops/ms
ClientGrpc.listUser                        thrpt       3   7.999 ± 1.216  ops/ms
ClientGrpc.createUser                       avgt       3   3.138 ± 0.496   ms/op
ClientGrpc.existUser                        avgt       3   3.046 ± 0.382   ms/op
ClientGrpc.getUser                          avgt       3   3.120 ± 0.724   ms/op
ClientGrpc.listUser                         avgt       3   3.970 ± 0.497   ms/op
ClientGrpc.createUser                     sample  304519   3.152 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.634           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.101           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.682           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.903           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.604           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.081           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.642           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.464           ms/op
ClientGrpc.existUser                      sample  316628   3.032 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.570           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.986           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.551           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.744           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.235           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.110           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.221           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.581           ms/op
ClientGrpc.getUser                        sample  304056   3.155 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.285           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.101           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.736           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.953           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.628           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.414           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.480           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.296           ms/op
ClientGrpc.listUser                       sample  242891   3.952 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.348           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.846           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.489           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.308           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.873           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.008           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.907           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.104           ms/op
