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
# Warmup Iteration   1: 4.842 ops/ms
# Warmup Iteration   2: 9.054 ops/ms
# Warmup Iteration   3: 10.134 ops/ms
Iteration   1: 10.916 ops/ms
Iteration   2: 10.733 ops/ms
Iteration   3: 10.517 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.722 ±(99.9%) 3.639 ops/ms [Average]
  (min, avg, max) = (10.517, 10.722, 10.916), stdev = 0.199
  CI (99.9%): [7.083, 14.361] (assumes normal distribution)


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
# Warmup Iteration   1: 8.588 ops/ms
# Warmup Iteration   2: 11.061 ops/ms
# Warmup Iteration   3: 11.372 ops/ms
Iteration   1: 11.371 ops/ms
Iteration   2: 11.252 ops/ms
Iteration   3: 11.183 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.269 ±(99.9%) 1.730 ops/ms [Average]
  (min, avg, max) = (11.183, 11.269, 11.371), stdev = 0.095
  CI (99.9%): [9.538, 12.999] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.370 ops/ms
# Warmup Iteration   2: 10.307 ops/ms
# Warmup Iteration   3: 10.626 ops/ms
Iteration   1: 10.640 ops/ms
Iteration   2: 10.605 ops/ms
Iteration   3: 10.564 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.603 ±(99.9%) 0.692 ops/ms [Average]
  (min, avg, max) = (10.564, 10.603, 10.640), stdev = 0.038
  CI (99.9%): [9.911, 11.295] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.565 ops/ms
# Warmup Iteration   2: 8.080 ops/ms
# Warmup Iteration   3: 8.178 ops/ms
Iteration   1: 8.450 ops/ms
Iteration   2: 8.224 ops/ms
Iteration   3: 8.285 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.320 ±(99.9%) 2.134 ops/ms [Average]
  (min, avg, max) = (8.224, 8.320, 8.450), stdev = 0.117
  CI (99.9%): [6.186, 10.454] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.983 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.095 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.007 ms/op
Iteration   1: 3.017 ±(99.9%) 0.003 ms/op
Iteration   2: 3.012 ±(99.9%) 0.002 ms/op
Iteration   3: 3.005 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.011 ±(99.9%) 0.108 ms/op [Average]
  (min, avg, max) = (3.005, 3.011, 3.017), stdev = 0.006
  CI (99.9%): [2.904, 3.119] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.887 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.909 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.913 ±(99.9%) 0.004 ms/op
Iteration   1: 2.879 ±(99.9%) 0.003 ms/op
Iteration   2: 2.910 ±(99.9%) 0.004 ms/op
Iteration   3: 2.865 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.885 ±(99.9%) 0.423 ms/op [Average]
  (min, avg, max) = (2.865, 2.885, 2.910), stdev = 0.023
  CI (99.9%): [2.462, 3.307] (assumes normal distribution)


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
# Warmup Iteration   1: 4.037 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.002 ms/op
Iteration   1: 2.994 ±(99.9%) 0.002 ms/op
Iteration   2: 2.962 ±(99.9%) 0.003 ms/op
Iteration   3: 3.014 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.990 ±(99.9%) 0.474 ms/op [Average]
  (min, avg, max) = (2.962, 2.990, 3.014), stdev = 0.026
  CI (99.9%): [2.516, 3.464] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.195 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.944 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.958 ±(99.9%) 0.023 ms/op
Iteration   1: 3.897 ±(99.9%) 0.012 ms/op
Iteration   2: 3.839 ±(99.9%) 0.013 ms/op
Iteration   3: 3.872 ±(99.9%) 0.067 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.869 ±(99.9%) 0.536 ms/op [Average]
  (min, avg, max) = (3.839, 3.869, 3.897), stdev = 0.029
  CI (99.9%): [3.334, 4.405] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.107 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.151 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.070 ±(99.9%) 0.007 ms/op
Iteration   1: 2.980 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.642 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   3.908 ms/op
                 createUser·p0.99:   4.850 ms/op
                 createUser·p0.999:  8.141 ms/op
                 createUser·p0.9999: 19.473 ms/op
                 createUser·p1.00:   19.792 ms/op

Iteration   2: 2.981 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.610 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.396 ms/op
                 createUser·p0.95:   3.674 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  11.578 ms/op
                 createUser·p0.9999: 19.268 ms/op
                 createUser·p1.00:   19.464 ms/op

Iteration   3: 3.021 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.779 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   4.596 ms/op
                 createUser·p0.999:  11.125 ms/op
                 createUser·p0.9999: 17.007 ms/op
                 createUser·p1.00:   17.465 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320462
  mean =      2.994 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2531 
    [ 1.250,  2.500) = 30292 
    [ 2.500,  3.750) = 269371 
    [ 3.750,  5.000) = 16281 
    [ 5.000,  6.250) = 1102 
    [ 6.250,  7.500) = 417 
    [ 7.500,  8.750) = 119 
    [ 8.750, 10.000) = 15 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 101 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.610 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.689 ms/op
     p(99.9000) =     11.026 ms/op
     p(99.9900) =     19.233 ms/op
     p(99.9990) =     19.713 ms/op
     p(99.9999) =     19.792 ms/op
    p(100.0000) =     19.792 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.911 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.980 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.904 ±(99.9%) 0.006 ms/op
Iteration   1: 2.832 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.596 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.502 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  7.373 ms/op
                 existUser·p0.9999: 15.784 ms/op
                 existUser·p1.00:   16.187 ms/op

Iteration   2: 2.866 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.615 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.793 ms/op
                 existUser·p0.99:   4.588 ms/op
                 existUser·p0.999:  7.652 ms/op
                 existUser·p0.9999: 20.251 ms/op
                 existUser·p1.00:   20.677 ms/op

Iteration   3: 2.968 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.558 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   4.506 ms/op
                 existUser·p0.999:  8.782 ms/op
                 existUser·p0.9999: 26.572 ms/op
                 existUser·p1.00:   27.918 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332475
  mean =      2.887 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 54284 
    [ 2.500,  5.000) = 276522 
    [ 5.000,  7.500) = 1248 
    [ 7.500, 10.000) = 250 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      7.893 ms/op
     p(99.9900) =     20.620 ms/op
     p(99.9990) =     27.121 ms/op
     p(99.9999) =     27.918 ms/op
    p(100.0000) =     27.918 ms/op


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
# Warmup Iteration   1: 3.949 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.171 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.007 ms/op
Iteration   1: 3.084 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.628 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.850 ms/op
                 getUser·p0.999:  11.544 ms/op
                 getUser·p0.9999: 14.897 ms/op
                 getUser·p1.00:   15.155 ms/op

Iteration   2: 2.999 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.546 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   4.686 ms/op
                 getUser·p0.999:  7.062 ms/op
                 getUser·p0.9999: 14.817 ms/op
                 getUser·p1.00:   15.303 ms/op

Iteration   3: 2.965 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.753 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.391 ms/op
                 getUser·p0.95:   3.609 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  7.397 ms/op
                 getUser·p0.9999: 17.931 ms/op
                 getUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318335
  mean =      3.015 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1992 
    [ 1.250,  2.500) = 24733 
    [ 2.500,  3.750) = 274868 
    [ 3.750,  5.000) = 14539 
    [ 5.000,  6.250) = 1204 
    [ 6.250,  7.500) = 522 
    [ 7.500,  8.750) = 135 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 109 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.626 ms/op
     p(99.9000) =      9.656 ms/op
     p(99.9900) =     16.734 ms/op
     p(99.9990) =     18.612 ms/op
     p(99.9999) =     18.678 ms/op
    p(100.0000) =     18.678 ms/op


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
# Warmup Iteration   1: 4.507 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.148 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.970 ±(99.9%) 0.011 ms/op
Iteration   1: 3.948 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.520 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  12.599 ms/op
                 listUser·p0.9999: 16.499 ms/op
                 listUser·p1.00:   17.170 ms/op

Iteration   2: 3.925 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.081 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.751 ms/op
                 listUser·p0.95:   5.423 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  14.599 ms/op
                 listUser·p0.9999: 17.619 ms/op
                 listUser·p1.00:   17.957 ms/op

Iteration   3: 3.975 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.774 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   7.414 ms/op
                 listUser·p0.999:  16.506 ms/op
                 listUser·p0.9999: 21.856 ms/op
                 listUser·p1.00:   25.068 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243064
  mean =      3.949 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3938 
    [ 2.500,  5.000) = 215484 
    [ 5.000,  7.500) = 22004 
    [ 7.500, 10.000) = 1039 
    [10.000, 12.500) = 202 
    [12.500, 15.000) = 176 
    [15.000, 17.500) = 146 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.774 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.981 ms/op
     p(95.0000) =      5.628 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     14.695 ms/op
     p(99.9900) =     21.256 ms/op
     p(99.9990) =     22.174 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.722 ± 3.639  ops/ms
ClientGrpc.existUser                       thrpt       3  11.269 ± 1.730  ops/ms
ClientGrpc.getUser                         thrpt       3  10.603 ± 0.692  ops/ms
ClientGrpc.listUser                        thrpt       3   8.320 ± 2.134  ops/ms
ClientGrpc.createUser                       avgt       3   3.011 ± 0.108   ms/op
ClientGrpc.existUser                        avgt       3   2.885 ± 0.423   ms/op
ClientGrpc.getUser                          avgt       3   2.990 ± 0.474   ms/op
ClientGrpc.listUser                         avgt       3   3.869 ± 0.536   ms/op
ClientGrpc.createUser                     sample  320462   2.994 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.610           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.986           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.535           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.801           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.689           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.026           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.233           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.792           ms/op
ClientGrpc.existUser                      sample  332475   2.887 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.558           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.888           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.490           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.711           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.514           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.893           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.620           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.918           ms/op
ClientGrpc.getUser                        sample  318335   3.015 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.546           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.002           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.535           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.768           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.626           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.656           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.734           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.678           ms/op
ClientGrpc.listUser                       sample  243064   3.949 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.774           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.785           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.981           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.628           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.021           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.695           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.256           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.068           ms/op
