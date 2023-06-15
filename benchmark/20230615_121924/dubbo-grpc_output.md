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
# Warmup Iteration   1: 3.923 ops/ms
# Warmup Iteration   2: 8.864 ops/ms
# Warmup Iteration   3: 10.387 ops/ms
Iteration   1: 10.616 ops/ms
Iteration   2: 10.536 ops/ms
Iteration   3: 10.440 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.531 ±(99.9%) 1.603 ops/ms [Average]
  (min, avg, max) = (10.440, 10.531, 10.616), stdev = 0.088
  CI (99.9%): [8.928, 12.134] (assumes normal distribution)


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
# Warmup Iteration   1: 7.522 ops/ms
# Warmup Iteration   2: 10.493 ops/ms
# Warmup Iteration   3: 10.919 ops/ms
Iteration   1: 10.978 ops/ms
Iteration   2: 11.147 ops/ms
Iteration   3: 10.908 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.011 ±(99.9%) 2.248 ops/ms [Average]
  (min, avg, max) = (10.908, 11.011, 11.147), stdev = 0.123
  CI (99.9%): [8.763, 13.259] (assumes normal distribution)


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
# Warmup Iteration   1: 6.745 ops/ms
# Warmup Iteration   2: 10.132 ops/ms
# Warmup Iteration   3: 10.487 ops/ms
Iteration   1: 10.763 ops/ms
Iteration   2: 10.680 ops/ms
Iteration   3: 10.685 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.709 ±(99.9%) 0.850 ops/ms [Average]
  (min, avg, max) = (10.680, 10.709, 10.763), stdev = 0.047
  CI (99.9%): [9.859, 11.560] (assumes normal distribution)


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
# Warmup Iteration   1: 6.242 ops/ms
# Warmup Iteration   2: 7.805 ops/ms
# Warmup Iteration   3: 8.150 ops/ms
Iteration   1: 7.954 ops/ms
Iteration   2: 8.064 ops/ms
Iteration   3: 8.135 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.051 ±(99.9%) 1.663 ops/ms [Average]
  (min, avg, max) = (7.954, 8.051, 8.135), stdev = 0.091
  CI (99.9%): [6.387, 9.714] (assumes normal distribution)


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
# Warmup Iteration   1: 4.521 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.229 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.115 ±(99.9%) 0.004 ms/op
Iteration   1: 3.093 ±(99.9%) 0.002 ms/op
Iteration   2: 3.064 ±(99.9%) 0.003 ms/op
Iteration   3: 3.102 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.086 ±(99.9%) 0.362 ms/op [Average]
  (min, avg, max) = (3.064, 3.086, 3.102), stdev = 0.020
  CI (99.9%): [2.724, 3.449] (assumes normal distribution)


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
# Warmup Iteration   1: 4.010 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.048 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.932 ±(99.9%) 0.003 ms/op
Iteration   1: 2.914 ±(99.9%) 0.003 ms/op
Iteration   2: 2.898 ±(99.9%) 0.003 ms/op
Iteration   3: 2.941 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.918 ±(99.9%) 0.400 ms/op [Average]
  (min, avg, max) = (2.898, 2.918, 2.941), stdev = 0.022
  CI (99.9%): [2.518, 3.318] (assumes normal distribution)


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
# Warmup Iteration   1: 4.194 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.155 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.096 ±(99.9%) 0.003 ms/op
Iteration   1: 3.060 ±(99.9%) 0.002 ms/op
Iteration   2: 3.078 ±(99.9%) 0.003 ms/op
Iteration   3: 3.055 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.064 ±(99.9%) 0.216 ms/op [Average]
  (min, avg, max) = (3.055, 3.064, 3.078), stdev = 0.012
  CI (99.9%): [2.848, 3.281] (assumes normal distribution)


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
# Warmup Iteration   1: 5.299 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.283 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.931 ±(99.9%) 0.010 ms/op
Iteration   1: 4.048 ±(99.9%) 0.008 ms/op
Iteration   2: 4.054 ±(99.9%) 0.011 ms/op
Iteration   3: 3.972 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.024 ±(99.9%) 0.835 ms/op [Average]
  (min, avg, max) = (3.972, 4.024, 4.054), stdev = 0.046
  CI (99.9%): [3.189, 4.859] (assumes normal distribution)


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
# Warmup Iteration   1: 4.362 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.233 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.007 ms/op
Iteration   1: 3.031 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.987 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  6.824 ms/op
                 createUser·p0.9999: 21.637 ms/op
                 createUser·p1.00:   22.348 ms/op

Iteration   2: 2.978 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.758 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.367 ms/op
                 createUser·p0.95:   3.523 ms/op
                 createUser·p0.99:   4.145 ms/op
                 createUser·p0.999:  6.681 ms/op
                 createUser·p0.9999: 18.850 ms/op
                 createUser·p1.00:   19.235 ms/op

Iteration   3: 3.007 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.867 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  8.416 ms/op
                 createUser·p0.9999: 25.112 ms/op
                 createUser·p1.00:   25.592 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319453
  mean =      3.005 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24721 
    [ 2.500,  5.000) = 293268 
    [ 5.000,  7.500) = 1184 
    [ 7.500, 10.000) = 56 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.758 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      7.013 ms/op
     p(99.9900) =     21.599 ms/op
     p(99.9990) =     25.514 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


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
# Warmup Iteration   1: 4.010 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.016 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.007 ms/op
Iteration   1: 2.856 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.688 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  6.218 ms/op
                 existUser·p0.9999: 12.544 ms/op
                 existUser·p1.00:   12.894 ms/op

Iteration   2: 2.942 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.785 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.559 ms/op
                 existUser·p0.99:   4.047 ms/op
                 existUser·p0.999:  5.933 ms/op
                 existUser·p0.9999: 14.635 ms/op
                 existUser·p1.00:   14.909 ms/op

Iteration   3: 2.940 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.598 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.523 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  11.960 ms/op
                 existUser·p0.9999: 17.764 ms/op
                 existUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329470
  mean =      2.912 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1534 
    [ 1.250,  2.500) = 41189 
    [ 2.500,  3.750) = 278093 
    [ 3.750,  5.000) = 7592 
    [ 5.000,  6.250) = 456 
    [ 6.250,  7.500) = 154 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 194 
    [12.500, 13.750) = 38 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 35 

  Percentiles, ms/op:
      p(0.0000) =      0.598 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.404 ms/op
     p(95.0000) =      3.584 ms/op
     p(99.0000) =      4.182 ms/op
     p(99.9000) =     11.239 ms/op
     p(99.9900) =     17.533 ms/op
     p(99.9990) =     18.138 ms/op
     p(99.9999) =     18.383 ms/op
    p(100.0000) =     18.383 ms/op


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
# Warmup Iteration   1: 4.181 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.210 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.110 ±(99.9%) 0.006 ms/op
Iteration   1: 3.022 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.819 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.371 ms/op
                 getUser·p0.95:   3.506 ms/op
                 getUser·p0.99:   4.080 ms/op
                 getUser·p0.999:  6.783 ms/op
                 getUser·p0.9999: 20.231 ms/op
                 getUser·p1.00:   20.480 ms/op

Iteration   2: 3.066 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.801 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  7.330 ms/op
                 getUser·p0.9999: 15.230 ms/op
                 getUser·p1.00:   15.794 ms/op

Iteration   3: 3.053 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.659 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.428 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  6.752 ms/op
                 getUser·p0.9999: 15.074 ms/op
                 getUser·p1.00:   15.286 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314992
  mean =      3.047 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12010 
    [ 2.500,  5.000) = 301992 
    [ 5.000,  7.500) = 762 
    [ 7.500, 10.000) = 68 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.659 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.682 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      6.955 ms/op
     p(99.9900) =     19.743 ms/op
     p(99.9990) =     20.382 ms/op
     p(99.9999) =     20.480 ms/op
    p(100.0000) =     20.480 ms/op


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
# Warmup Iteration   1: 5.679 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.183 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.957 ±(99.9%) 0.010 ms/op
Iteration   1: 4.044 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.303 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  12.975 ms/op
                 listUser·p0.9999: 19.208 ms/op
                 listUser·p1.00:   19.857 ms/op

Iteration   2: 3.978 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.440 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.743 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  15.441 ms/op
                 listUser·p0.9999: 19.661 ms/op
                 listUser·p1.00:   23.331 ms/op

Iteration   3: 4.023 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.401 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  22.120 ms/op
                 listUser·p0.9999: 29.231 ms/op
                 listUser·p1.00:   29.819 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239095
  mean =      4.015 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2697 
    [ 2.500,  5.000) = 215141 
    [ 5.000,  7.500) = 19939 
    [ 7.500, 10.000) = 871 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 167 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.303 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.874 ms/op
     p(95.0000) =      5.710 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =     14.662 ms/op
     p(99.9900) =     28.806 ms/op
     p(99.9990) =     29.715 ms/op
     p(99.9999) =     29.819 ms/op
    p(100.0000) =     29.819 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.531 ± 1.603  ops/ms
ClientGrpc.existUser                       thrpt       3  11.011 ± 2.248  ops/ms
ClientGrpc.getUser                         thrpt       3  10.709 ± 0.850  ops/ms
ClientGrpc.listUser                        thrpt       3   8.051 ± 1.663  ops/ms
ClientGrpc.createUser                       avgt       3   3.086 ± 0.362   ms/op
ClientGrpc.existUser                        avgt       3   2.918 ± 0.400   ms/op
ClientGrpc.getUser                          avgt       3   3.064 ± 0.216   ms/op
ClientGrpc.listUser                         avgt       3   4.024 ± 0.835   ms/op
ClientGrpc.createUser                     sample  319453   3.005 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.758           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.966           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.473           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.719           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.013           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.599           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.592           ms/op
ClientGrpc.existUser                      sample  329470   2.912 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.598           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.908           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.404           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.584           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.182           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.239           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.533           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.383           ms/op
ClientGrpc.getUser                        sample  314992   3.047 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.659           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.027           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.457           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.682           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.334           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.955           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.743           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.480           ms/op
ClientGrpc.listUser                       sample  239095   4.015 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.303           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.867           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.874           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.710           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.963           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.662           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.806           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.819           ms/op
