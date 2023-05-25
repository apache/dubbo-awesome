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
# Warmup Iteration   1: 4.357 ops/ms
# Warmup Iteration   2: 9.643 ops/ms
# Warmup Iteration   3: 10.396 ops/ms
Iteration   1: 10.798 ops/ms
Iteration   2: 10.963 ops/ms
Iteration   3: 10.662 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.808 ±(99.9%) 2.746 ops/ms [Average]
  (min, avg, max) = (10.662, 10.808, 10.963), stdev = 0.151
  CI (99.9%): [8.062, 13.553] (assumes normal distribution)


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
# Warmup Iteration   1: 7.740 ops/ms
# Warmup Iteration   2: 10.688 ops/ms
# Warmup Iteration   3: 10.969 ops/ms
Iteration   1: 11.141 ops/ms
Iteration   2: 11.324 ops/ms
Iteration   3: 11.261 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.242 ±(99.9%) 1.699 ops/ms [Average]
  (min, avg, max) = (11.141, 11.242, 11.324), stdev = 0.093
  CI (99.9%): [9.543, 12.941] (assumes normal distribution)


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
# Warmup Iteration   1: 7.845 ops/ms
# Warmup Iteration   2: 10.378 ops/ms
# Warmup Iteration   3: 10.717 ops/ms
Iteration   1: 10.690 ops/ms
Iteration   2: 10.792 ops/ms
Iteration   3: 10.880 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.787 ±(99.9%) 1.739 ops/ms [Average]
  (min, avg, max) = (10.690, 10.787, 10.880), stdev = 0.095
  CI (99.9%): [9.048, 12.526] (assumes normal distribution)


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
# Warmup Iteration   1: 5.669 ops/ms
# Warmup Iteration   2: 8.022 ops/ms
# Warmup Iteration   3: 8.287 ops/ms
Iteration   1: 8.276 ops/ms
Iteration   2: 8.359 ops/ms
Iteration   3: 8.223 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.286 ±(99.9%) 1.254 ops/ms [Average]
  (min, avg, max) = (8.223, 8.286, 8.359), stdev = 0.069
  CI (99.9%): [7.032, 9.541] (assumes normal distribution)


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
# Warmup Iteration   1: 3.858 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.091 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.979 ±(99.9%) 0.002 ms/op
Iteration   1: 2.984 ±(99.9%) 0.002 ms/op
Iteration   2: 2.988 ±(99.9%) 0.002 ms/op
Iteration   3: 2.973 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.982 ±(99.9%) 0.144 ms/op [Average]
  (min, avg, max) = (2.973, 2.982, 2.988), stdev = 0.008
  CI (99.9%): [2.838, 3.126] (assumes normal distribution)


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
# Warmup Iteration   1: 3.916 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.973 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.890 ±(99.9%) 0.004 ms/op
Iteration   1: 2.864 ±(99.9%) 0.005 ms/op
Iteration   2: 2.850 ±(99.9%) 0.003 ms/op
Iteration   3: 2.913 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.876 ±(99.9%) 0.606 ms/op [Average]
  (min, avg, max) = (2.850, 2.876, 2.913), stdev = 0.033
  CI (99.9%): [2.270, 3.482] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.802 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.097 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.935 ±(99.9%) 0.004 ms/op
Iteration   1: 2.994 ±(99.9%) 0.004 ms/op
Iteration   2: 2.987 ±(99.9%) 0.002 ms/op
Iteration   3: 3.027 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.002 ±(99.9%) 0.390 ms/op [Average]
  (min, avg, max) = (2.987, 3.002, 3.027), stdev = 0.021
  CI (99.9%): [2.613, 3.392] (assumes normal distribution)


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
# Warmup Iteration   1: 5.446 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.920 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 3.858 ±(99.9%) 0.010 ms/op
Iteration   1: 3.900 ±(99.9%) 0.009 ms/op
Iteration   2: 3.925 ±(99.9%) 0.041 ms/op
Iteration   3: 3.906 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.910 ±(99.9%) 0.235 ms/op [Average]
  (min, avg, max) = (3.900, 3.910, 3.925), stdev = 0.013
  CI (99.9%): [3.675, 4.145] (assumes normal distribution)


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
# Warmup Iteration   1: 4.067 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.102 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.018 ±(99.9%) 0.005 ms/op
Iteration   1: 2.951 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.719 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.731 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  7.072 ms/op
                 createUser·p0.9999: 12.506 ms/op
                 createUser·p1.00:   12.780 ms/op

Iteration   2: 2.973 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.545 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.424 ms/op
                 createUser·p0.95:   3.576 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  10.655 ms/op
                 createUser·p0.9999: 13.406 ms/op
                 createUser·p1.00:   14.565 ms/op

Iteration   3: 3.045 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.811 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.707 ms/op
                 createUser·p0.99:   4.227 ms/op
                 createUser·p0.999:  9.748 ms/op
                 createUser·p0.9999: 21.447 ms/op
                 createUser·p1.00:   21.823 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320937
  mean =      2.989 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30314 
    [ 2.500,  5.000) = 289435 
    [ 5.000,  7.500) = 785 
    [ 7.500, 10.000) = 115 
    [10.000, 12.500) = 154 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.545 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      9.030 ms/op
     p(99.9900) =     19.524 ms/op
     p(99.9990) =     21.686 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.814 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.938 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.855 ±(99.9%) 0.005 ms/op
Iteration   1: 2.855 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.514 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  5.710 ms/op
                 existUser·p0.9999: 10.928 ms/op
                 existUser·p1.00:   11.158 ms/op

Iteration   2: 2.896 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.532 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   4.465 ms/op
                 existUser·p0.999:  7.995 ms/op
                 existUser·p0.9999: 13.025 ms/op
                 existUser·p1.00:   13.173 ms/op

Iteration   3: 2.895 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.637 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  11.359 ms/op
                 existUser·p0.9999: 15.072 ms/op
                 existUser·p1.00:   16.351 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332946
  mean =      2.882 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2065 
    [ 1.250,  2.500) = 41520 
    [ 2.500,  3.750) = 280332 
    [ 3.750,  5.000) = 7787 
    [ 5.000,  6.250) = 640 
    [ 6.250,  7.500) = 202 
    [ 7.500,  8.750) = 104 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.514 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.355 ms/op
     p(95.0000) =      3.547 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      8.137 ms/op
     p(99.9900) =     14.577 ms/op
     p(99.9990) =     15.483 ms/op
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
# Warmup Iteration   1: 3.945 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.107 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.020 ±(99.9%) 0.006 ms/op
Iteration   1: 3.008 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.774 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  8.914 ms/op
                 getUser·p0.9999: 14.927 ms/op
                 getUser·p1.00:   15.286 ms/op

Iteration   2: 2.999 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.811 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  8.389 ms/op
                 getUser·p0.9999: 21.444 ms/op
                 getUser·p1.00:   22.348 ms/op

Iteration   3: 3.013 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.583 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  8.077 ms/op
                 getUser·p0.9999: 17.629 ms/op
                 getUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319168
  mean =      3.007 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26523 
    [ 2.500,  5.000) = 291389 
    [ 5.000,  7.500) = 811 
    [ 7.500, 10.000) = 219 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.583 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      8.645 ms/op
     p(99.9900) =     20.352 ms/op
     p(99.9990) =     22.134 ms/op
     p(99.9999) =     22.348 ms/op
    p(100.0000) =     22.348 ms/op


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
# Warmup Iteration   1: 4.244 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.083 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.880 ±(99.9%) 0.011 ms/op
Iteration   1: 3.886 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.048 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.675 ms/op
                 listUser·p0.999:  12.796 ms/op
                 listUser·p0.9999: 14.689 ms/op
                 listUser·p1.00:   15.581 ms/op

Iteration   2: 3.889 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.118 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   6.650 ms/op
                 listUser·p0.999:  16.114 ms/op
                 listUser·p0.9999: 25.355 ms/op
                 listUser·p1.00:   25.592 ms/op

Iteration   3: 3.895 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.298 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  13.738 ms/op
                 listUser·p0.9999: 18.787 ms/op
                 listUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246799
  mean =      3.890 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4981 
    [ 2.500,  5.000) = 222033 
    [ 5.000,  7.500) = 18626 
    [ 7.500, 10.000) = 652 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 246 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.048 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.809 ms/op
     p(95.0000) =      5.489 ms/op
     p(99.0000) =      6.676 ms/op
     p(99.9000) =     13.861 ms/op
     p(99.9900) =     23.188 ms/op
     p(99.9990) =     25.544 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.808 ± 2.746  ops/ms
ClientGrpc.existUser                       thrpt       3  11.242 ± 1.699  ops/ms
ClientGrpc.getUser                         thrpt       3  10.787 ± 1.739  ops/ms
ClientGrpc.listUser                        thrpt       3   8.286 ± 1.254  ops/ms
ClientGrpc.createUser                       avgt       3   2.982 ± 0.144   ms/op
ClientGrpc.existUser                        avgt       3   2.876 ± 0.606   ms/op
ClientGrpc.getUser                          avgt       3   3.002 ± 0.390   ms/op
ClientGrpc.listUser                         avgt       3   3.910 ± 0.235   ms/op
ClientGrpc.createUser                     sample  320937   2.989 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.545           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.974           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.506           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.678           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.030           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.524           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.823           ms/op
ClientGrpc.existUser                      sample  332946   2.882 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.514           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.355           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.547           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.399           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.137           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.577           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.351           ms/op
ClientGrpc.getUser                        sample  319168   3.007 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.583           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.990           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.543           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.744           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.309           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.645           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.352           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.348           ms/op
ClientGrpc.listUser                       sample  246799   3.890 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.048           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.752           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.809           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.489           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.676           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.861           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.188           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.592           ms/op
