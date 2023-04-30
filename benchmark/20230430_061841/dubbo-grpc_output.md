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
# Warmup Iteration   1: 4.443 ops/ms
# Warmup Iteration   2: 9.297 ops/ms
# Warmup Iteration   3: 9.963 ops/ms
Iteration   1: 10.422 ops/ms
Iteration   2: 10.859 ops/ms
Iteration   3: 10.840 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.707 ±(99.9%) 4.505 ops/ms [Average]
  (min, avg, max) = (10.422, 10.707, 10.859), stdev = 0.247
  CI (99.9%): [6.202, 15.212] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 8.211 ops/ms
# Warmup Iteration   2: 11.074 ops/ms
# Warmup Iteration   3: 11.379 ops/ms
Iteration   1: 11.220 ops/ms
Iteration   2: 11.318 ops/ms
Iteration   3: 11.399 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.312 ±(99.9%) 1.637 ops/ms [Average]
  (min, avg, max) = (11.220, 11.312, 11.399), stdev = 0.090
  CI (99.9%): [9.675, 12.950] (assumes normal distribution)


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
# Warmup Iteration   1: 8.021 ops/ms
# Warmup Iteration   2: 10.616 ops/ms
# Warmup Iteration   3: 10.890 ops/ms
Iteration   1: 10.993 ops/ms
Iteration   2: 10.984 ops/ms
Iteration   3: 10.926 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.968 ±(99.9%) 0.658 ops/ms [Average]
  (min, avg, max) = (10.926, 10.968, 10.993), stdev = 0.036
  CI (99.9%): [10.310, 11.626] (assumes normal distribution)


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
# Warmup Iteration   1: 7.140 ops/ms
# Warmup Iteration   2: 8.050 ops/ms
# Warmup Iteration   3: 8.357 ops/ms
Iteration   1: 8.416 ops/ms
Iteration   2: 8.751 ops/ms
Iteration   3: 8.649 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.605 ±(99.9%) 3.139 ops/ms [Average]
  (min, avg, max) = (8.416, 8.605, 8.751), stdev = 0.172
  CI (99.9%): [5.467, 11.744] (assumes normal distribution)


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
# Warmup Iteration   1: 3.822 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.014 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.930 ±(99.9%) 0.003 ms/op
Iteration   1: 2.914 ±(99.9%) 0.001 ms/op
Iteration   2: 2.848 ±(99.9%) 0.002 ms/op
Iteration   3: 2.928 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.897 ±(99.9%) 0.774 ms/op [Average]
  (min, avg, max) = (2.848, 2.897, 2.928), stdev = 0.042
  CI (99.9%): [2.123, 3.670] (assumes normal distribution)


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
# Warmup Iteration   1: 3.464 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.875 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.845 ±(99.9%) 0.003 ms/op
Iteration   1: 2.859 ±(99.9%) 0.003 ms/op
Iteration   2: 2.854 ±(99.9%) 0.003 ms/op
Iteration   3: 2.796 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.836 ±(99.9%) 0.634 ms/op [Average]
  (min, avg, max) = (2.796, 2.836, 2.859), stdev = 0.035
  CI (99.9%): [2.202, 3.471] (assumes normal distribution)


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
# Warmup Iteration   1: 4.011 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.128 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.031 ±(99.9%) 0.002 ms/op
Iteration   1: 2.996 ±(99.9%) 0.002 ms/op
Iteration   2: 3.025 ±(99.9%) 0.003 ms/op
Iteration   3: 3.020 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.014 ±(99.9%) 0.281 ms/op [Average]
  (min, avg, max) = (2.996, 3.014, 3.025), stdev = 0.015
  CI (99.9%): [2.733, 3.295] (assumes normal distribution)


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
# Warmup Iteration   1: 4.023 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 4.226 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 3.832 ±(99.9%) 0.011 ms/op
Iteration   1: 3.824 ±(99.9%) 0.006 ms/op
Iteration   2: 3.785 ±(99.9%) 0.007 ms/op
Iteration   3: 3.785 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.798 ±(99.9%) 0.407 ms/op [Average]
  (min, avg, max) = (3.785, 3.798, 3.824), stdev = 0.022
  CI (99.9%): [3.391, 4.205] (assumes normal distribution)


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
# Warmup Iteration   1: 3.719 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.091 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.952 ±(99.9%) 0.007 ms/op
Iteration   1: 2.934 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.612 ms/op
                 createUser·p0.50:   2.929 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.617 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  9.384 ms/op
                 createUser·p0.9999: 18.126 ms/op
                 createUser·p1.00:   18.711 ms/op

Iteration   2: 3.005 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.776 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  7.868 ms/op
                 createUser·p0.9999: 16.078 ms/op
                 createUser·p1.00:   16.384 ms/op

Iteration   3: 2.934 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.613 ms/op
                 createUser·p0.50:   2.925 ms/op
                 createUser·p0.90:   3.453 ms/op
                 createUser·p0.95:   3.658 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  7.018 ms/op
                 createUser·p0.9999: 30.477 ms/op
                 createUser·p1.00:   30.867 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 324768
  mean =      2.957 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35903 
    [ 2.500,  5.000) = 287646 
    [ 5.000,  7.500) = 854 
    [ 7.500, 10.000) = 128 
    [10.000, 12.500) = 13 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.612 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      7.840 ms/op
     p(99.9900) =     24.418 ms/op
     p(99.9990) =     30.761 ms/op
     p(99.9999) =     30.867 ms/op
    p(100.0000) =     30.867 ms/op


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
# Warmup Iteration   1: 3.627 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.890 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.832 ±(99.9%) 0.006 ms/op
Iteration   1: 2.821 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.712 ms/op
                 existUser·p0.50:   2.818 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  6.477 ms/op
                 existUser·p0.9999: 15.729 ms/op
                 existUser·p1.00:   16.286 ms/op

Iteration   2: 2.798 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.585 ms/op
                 existUser·p0.50:   2.810 ms/op
                 existUser·p0.90:   3.289 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   4.157 ms/op
                 existUser·p0.999:  6.226 ms/op
                 existUser·p0.9999: 12.517 ms/op
                 existUser·p1.00:   12.763 ms/op

Iteration   3: 2.839 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.478 ms/op
                 existUser·p0.50:   2.826 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  7.413 ms/op
                 existUser·p0.9999: 15.865 ms/op
                 existUser·p1.00:   16.351 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 340437
  mean =      2.820 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4049 
    [ 1.250,  2.500) = 56086 
    [ 2.500,  3.750) = 269279 
    [ 3.750,  5.000) = 9913 
    [ 5.000,  6.250) = 667 
    [ 6.250,  7.500) = 183 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 34 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.478 ms/op
     p(50.0000) =      2.818 ms/op
     p(90.0000) =      3.310 ms/op
     p(95.0000) =      3.576 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      6.607 ms/op
     p(99.9900) =     15.384 ms/op
     p(99.9990) =     16.286 ms/op
     p(99.9999) =     16.351 ms/op
    p(100.0000) =     16.351 ms/op


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
# Warmup Iteration   1: 3.917 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.004 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.940 ±(99.9%) 0.006 ms/op
Iteration   1: 2.955 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.642 ms/op
                 getUser·p0.50:   2.937 ms/op
                 getUser·p0.90:   3.318 ms/op
                 getUser·p0.95:   3.588 ms/op
                 getUser·p0.99:   4.062 ms/op
                 getUser·p0.999:  7.133 ms/op
                 getUser·p0.9999: 12.911 ms/op
                 getUser·p1.00:   13.074 ms/op

Iteration   2: 2.922 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.684 ms/op
                 getUser·p0.50:   2.920 ms/op
                 getUser·p0.90:   3.346 ms/op
                 getUser·p0.95:   3.555 ms/op
                 getUser·p0.99:   4.137 ms/op
                 getUser·p0.999:  7.589 ms/op
                 getUser·p0.9999: 12.321 ms/op
                 getUser·p1.00:   12.534 ms/op

Iteration   3: 2.938 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.517 ms/op
                 getUser·p0.50:   2.933 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  7.012 ms/op
                 getUser·p0.9999: 21.696 ms/op
                 getUser·p1.00:   22.086 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 326726
  mean =      2.938 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26399 
    [ 2.500,  5.000) = 299380 
    [ 5.000,  7.500) = 684 
    [ 7.500, 10.000) = 74 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.517 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.375 ms/op
     p(95.0000) =      3.633 ms/op
     p(99.0000) =      4.157 ms/op
     p(99.9000) =      7.193 ms/op
     p(99.9900) =     15.434 ms/op
     p(99.9990) =     21.979 ms/op
     p(99.9999) =     22.086 ms/op
    p(100.0000) =     22.086 ms/op


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
# Warmup Iteration   1: 5.091 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.916 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.901 ±(99.9%) 0.010 ms/op
Iteration   1: 3.861 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.800 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.382 ms/op
                 listUser·p0.99:   6.504 ms/op
                 listUser·p0.999:  12.354 ms/op
                 listUser·p0.9999: 14.056 ms/op
                 listUser·p1.00:   15.630 ms/op

Iteration   2: 3.734 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.508 ms/op
                 listUser·p0.50:   3.604 ms/op
                 listUser·p0.90:   4.751 ms/op
                 listUser·p0.95:   5.341 ms/op
                 listUser·p0.99:   6.545 ms/op
                 listUser·p0.999:  14.226 ms/op
                 listUser·p0.9999: 16.635 ms/op
                 listUser·p1.00:   17.039 ms/op

Iteration   3: 3.829 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.644 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  13.705 ms/op
                 listUser·p0.9999: 18.711 ms/op
                 listUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 252195
  mean =      3.807 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 29 
    [ 1.250,  2.500) = 5170 
    [ 2.500,  3.750) = 137945 
    [ 3.750,  5.000) = 88675 
    [ 5.000,  6.250) = 15827 
    [ 6.250,  7.500) = 3538 
    [ 7.500,  8.750) = 467 
    [ 8.750, 10.000) = 121 
    [10.000, 11.250) = 37 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 109 
    [13.750, 15.000) = 84 
    [15.000, 16.250) = 58 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.508 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.464 ms/op
     p(99.0000) =      6.693 ms/op
     p(99.9000) =     13.137 ms/op
     p(99.9900) =     18.383 ms/op
     p(99.9990) =     18.824 ms/op
     p(99.9999) =     19.497 ms/op
    p(100.0000) =     19.497 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.707 ± 4.505  ops/ms
ClientGrpc.existUser                       thrpt       3  11.312 ± 1.637  ops/ms
ClientGrpc.getUser                         thrpt       3  10.968 ± 0.658  ops/ms
ClientGrpc.listUser                        thrpt       3   8.605 ± 3.139  ops/ms
ClientGrpc.createUser                       avgt       3   2.897 ± 0.774   ms/op
ClientGrpc.existUser                        avgt       3   2.836 ± 0.634   ms/op
ClientGrpc.getUser                          avgt       3   3.014 ± 0.281   ms/op
ClientGrpc.listUser                         avgt       3   3.798 ± 0.407   ms/op
ClientGrpc.createUser                     sample  324768   2.957 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.612           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.941           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.482           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.678           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.301           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.840           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.418           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.867           ms/op
ClientGrpc.existUser                      sample  340437   2.820 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.478           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.818           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.310           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.576           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.309           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.607           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.384           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.351           ms/op
ClientGrpc.getUser                        sample  326726   2.938 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.517           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.929           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.375           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.633           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.157           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.193           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.434           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.086           ms/op
ClientGrpc.listUser                       sample  252195   3.807 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.508           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.678           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.784           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.464           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.693           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.137           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.383           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.497           ms/op
