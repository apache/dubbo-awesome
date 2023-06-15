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
# Warmup Iteration   1: 2.522 ops/ms
# Warmup Iteration   2: 5.960 ops/ms
# Warmup Iteration   3: 7.252 ops/ms
Iteration   1: 7.482 ops/ms
Iteration   2: 7.887 ops/ms
Iteration   3: 7.890 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.753 ±(99.9%) 4.287 ops/ms [Average]
  (min, avg, max) = (7.482, 7.753, 7.890), stdev = 0.235
  CI (99.9%): [3.466, 12.040] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.872 ops/ms
# Warmup Iteration   2: 7.557 ops/ms
# Warmup Iteration   3: 7.675 ops/ms
Iteration   1: 8.259 ops/ms
Iteration   2: 7.997 ops/ms
Iteration   3: 8.028 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.095 ±(99.9%) 2.616 ops/ms [Average]
  (min, avg, max) = (7.997, 8.095, 8.259), stdev = 0.143
  CI (99.9%): [5.479, 10.711] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.774 ops/ms
# Warmup Iteration   2: 7.327 ops/ms
# Warmup Iteration   3: 7.725 ops/ms
Iteration   1: 7.827 ops/ms
Iteration   2: 7.689 ops/ms
Iteration   3: 7.806 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.774 ±(99.9%) 1.355 ops/ms [Average]
  (min, avg, max) = (7.689, 7.774, 7.827), stdev = 0.074
  CI (99.9%): [6.419, 9.129] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 4.052 ops/ms
# Warmup Iteration   2: 5.328 ops/ms
# Warmup Iteration   3: 5.911 ops/ms
Iteration   1: 5.924 ops/ms
Iteration   2: 5.912 ops/ms
Iteration   3: 6.243 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.027 ±(99.9%) 3.428 ops/ms [Average]
  (min, avg, max) = (5.912, 6.027, 6.243), stdev = 0.188
  CI (99.9%): [2.598, 9.455] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.060 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.491 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.417 ±(99.9%) 0.007 ms/op
Iteration   1: 4.301 ±(99.9%) 0.004 ms/op
Iteration   2: 4.420 ±(99.9%) 0.002 ms/op
Iteration   3: 4.291 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.337 ±(99.9%) 1.309 ms/op [Average]
  (min, avg, max) = (4.291, 4.337, 4.420), stdev = 0.072
  CI (99.9%): [3.029, 5.646] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.524 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.154 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.050 ±(99.9%) 0.004 ms/op
Iteration   1: 3.982 ±(99.9%) 0.004 ms/op
Iteration   2: 3.967 ±(99.9%) 0.003 ms/op
Iteration   3: 3.883 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.944 ±(99.9%) 0.971 ms/op [Average]
  (min, avg, max) = (3.883, 3.944, 3.982), stdev = 0.053
  CI (99.9%): [2.973, 4.915] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.321 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.919 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.222 ±(99.9%) 0.009 ms/op
Iteration   1: 4.114 ±(99.9%) 0.003 ms/op
Iteration   2: 4.327 ±(99.9%) 0.004 ms/op
Iteration   3: 4.540 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.327 ±(99.9%) 3.884 ms/op [Average]
  (min, avg, max) = (4.114, 4.327, 4.540), stdev = 0.213
  CI (99.9%): [0.443, 8.211] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.315 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 6.415 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.908 ±(99.9%) 0.024 ms/op
Iteration   1: 5.970 ±(99.9%) 0.013 ms/op
Iteration   2: 6.110 ±(99.9%) 0.018 ms/op
Iteration   3: 6.018 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.033 ±(99.9%) 1.296 ms/op [Average]
  (min, avg, max) = (5.970, 6.033, 6.110), stdev = 0.071
  CI (99.9%): [4.737, 7.329] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.219 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 5.267 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.700 ±(99.9%) 0.020 ms/op
Iteration   1: 4.901 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   0.887 ms/op
                 createUser·p0.50:   4.669 ms/op
                 createUser·p0.90:   6.455 ms/op
                 createUser·p0.95:   7.381 ms/op
                 createUser·p0.99:   9.929 ms/op
                 createUser·p0.999:  14.074 ms/op
                 createUser·p0.9999: 27.656 ms/op
                 createUser·p1.00:   27.722 ms/op

Iteration   2: 4.815 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   0.488 ms/op
                 createUser·p0.50:   4.555 ms/op
                 createUser·p0.90:   6.250 ms/op
                 createUser·p0.95:   7.225 ms/op
                 createUser·p0.99:   10.306 ms/op
                 createUser·p0.999:  16.261 ms/op
                 createUser·p0.9999: 22.949 ms/op
                 createUser·p1.00:   23.888 ms/op

Iteration   3: 4.804 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.033 ms/op
                 createUser·p0.50:   4.514 ms/op
                 createUser·p0.90:   6.398 ms/op
                 createUser·p0.95:   7.406 ms/op
                 createUser·p0.99:   10.289 ms/op
                 createUser·p0.999:  16.211 ms/op
                 createUser·p0.9999: 36.264 ms/op
                 createUser·p1.00:   36.700 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 198341
  mean =      4.840 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2805 
    [ 2.500,  5.000) = 125891 
    [ 5.000,  7.500) = 60629 
    [ 7.500, 10.000) = 6834 
    [10.000, 12.500) = 1610 
    [12.500, 15.000) = 299 
    [15.000, 17.500) = 135 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.488 ms/op
     p(50.0000) =      4.579 ms/op
     p(90.0000) =      6.373 ms/op
     p(95.0000) =      7.348 ms/op
     p(99.0000) =     10.158 ms/op
     p(99.9000) =     15.854 ms/op
     p(99.9900) =     32.604 ms/op
     p(99.9990) =     36.571 ms/op
     p(99.9999) =     36.700 ms/op
    p(100.0000) =     36.700 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.054 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 4.989 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.411 ±(99.9%) 0.016 ms/op
Iteration   1: 4.237 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.733 ms/op
                 existUser·p0.50:   4.039 ms/op
                 existUser·p0.90:   5.612 ms/op
                 existUser·p0.95:   6.521 ms/op
                 existUser·p0.99:   8.716 ms/op
                 existUser·p0.999:  11.502 ms/op
                 existUser·p0.9999: 15.334 ms/op
                 existUser·p1.00:   15.679 ms/op

Iteration   2: 4.091 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.075 ms/op
                 existUser·p0.50:   3.867 ms/op
                 existUser·p0.90:   5.243 ms/op
                 existUser·p0.95:   6.013 ms/op
                 existUser·p0.99:   8.186 ms/op
                 existUser·p0.999:  11.854 ms/op
                 existUser·p0.9999: 21.670 ms/op
                 existUser·p1.00:   25.166 ms/op

Iteration   3: 4.198 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.559 ms/op
                 existUser·p0.50:   3.912 ms/op
                 existUser·p0.90:   5.644 ms/op
                 existUser·p0.95:   6.611 ms/op
                 existUser·p0.99:   9.126 ms/op
                 existUser·p0.999:  12.321 ms/op
                 existUser·p0.9999: 20.447 ms/op
                 existUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 229915
  mean =      4.174 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5038 
    [ 2.500,  5.000) = 188372 
    [ 5.000,  7.500) = 31249 
    [ 7.500, 10.000) = 4338 
    [10.000, 12.500) = 741 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.559 ms/op
     p(50.0000) =      3.932 ms/op
     p(90.0000) =      5.497 ms/op
     p(95.0000) =      6.398 ms/op
     p(99.0000) =      8.684 ms/op
     p(99.9000) =     12.157 ms/op
     p(99.9900) =     21.037 ms/op
     p(99.9990) =     24.996 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 5.950 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.323 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.003 ±(99.9%) 0.010 ms/op
Iteration   1: 3.960 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.844 ms/op
                 getUser·p0.50:   3.879 ms/op
                 getUser·p0.90:   4.907 ms/op
                 getUser·p0.95:   5.325 ms/op
                 getUser·p0.99:   6.898 ms/op
                 getUser·p0.999:  11.740 ms/op
                 getUser·p0.9999: 36.831 ms/op
                 getUser·p1.00:   37.290 ms/op

Iteration   2: 3.997 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.945 ms/op
                 getUser·p0.50:   3.924 ms/op
                 getUser·p0.90:   4.899 ms/op
                 getUser·p0.95:   5.261 ms/op
                 getUser·p0.99:   6.480 ms/op
                 getUser·p0.999:  11.534 ms/op
                 getUser·p0.9999: 21.332 ms/op
                 getUser·p1.00:   22.020 ms/op

Iteration   3: 3.968 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.806 ms/op
                 getUser·p0.50:   3.883 ms/op
                 getUser·p0.90:   4.801 ms/op
                 getUser·p0.95:   5.169 ms/op
                 getUser·p0.99:   6.498 ms/op
                 getUser·p0.999:  12.698 ms/op
                 getUser·p0.9999: 24.438 ms/op
                 getUser·p1.00:   25.002 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 241542
  mean =      3.975 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7466 
    [ 2.500,  5.000) = 214994 
    [ 5.000,  7.500) = 17558 
    [ 7.500, 10.000) = 1088 
    [10.000, 12.500) = 240 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.806 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      4.874 ms/op
     p(95.0000) =      5.259 ms/op
     p(99.0000) =      6.636 ms/op
     p(99.9000) =     11.960 ms/op
     p(99.9900) =     35.510 ms/op
     p(99.9990) =     37.197 ms/op
     p(99.9999) =     37.290 ms/op
    p(100.0000) =     37.290 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 7.516 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 5.436 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.361 ±(99.9%) 0.018 ms/op
Iteration   1: 5.339 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.995 ms/op
                 listUser·p0.50:   5.104 ms/op
                 listUser·p0.90:   6.758 ms/op
                 listUser·p0.95:   7.791 ms/op
                 listUser·p0.99:   9.929 ms/op
                 listUser·p0.999:  15.958 ms/op
                 listUser·p0.9999: 17.498 ms/op
                 listUser·p1.00:   18.350 ms/op

Iteration   2: 5.528 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.272 ms/op
                 listUser·p0.50:   5.235 ms/op
                 listUser·p0.90:   7.389 ms/op
                 listUser·p0.95:   8.323 ms/op
                 listUser·p0.99:   10.961 ms/op
                 listUser·p0.999:  17.077 ms/op
                 listUser·p0.9999: 20.693 ms/op
                 listUser·p1.00:   22.053 ms/op

Iteration   3: 5.461 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.434 ms/op
                 listUser·p0.50:   5.136 ms/op
                 listUser·p0.90:   7.137 ms/op
                 listUser·p0.95:   8.217 ms/op
                 listUser·p0.99:   10.961 ms/op
                 listUser·p0.999:  20.962 ms/op
                 listUser·p0.9999: 29.378 ms/op
                 listUser·p1.00:   30.015 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 176489
  mean =      5.441 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 199 
    [ 2.500,  5.000) = 75959 
    [ 5.000,  7.500) = 86635 
    [ 7.500, 10.000) = 11173 
    [10.000, 12.500) = 1793 
    [12.500, 15.000) = 366 
    [15.000, 17.500) = 212 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 11 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.272 ms/op
     p(50.0000) =      5.153 ms/op
     p(90.0000) =      7.127 ms/op
     p(95.0000) =      8.110 ms/op
     p(99.0000) =     10.682 ms/op
     p(99.9000) =     17.039 ms/op
     p(99.9900) =     27.702 ms/op
     p(99.9990) =     29.890 ms/op
     p(99.9999) =     30.015 ms/op
    p(100.0000) =     30.015 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.753 ± 4.287  ops/ms
ClientGrpc.existUser                       thrpt       3   8.095 ± 2.616  ops/ms
ClientGrpc.getUser                         thrpt       3   7.774 ± 1.355  ops/ms
ClientGrpc.listUser                        thrpt       3   6.027 ± 3.428  ops/ms
ClientGrpc.createUser                       avgt       3   4.337 ± 1.309   ms/op
ClientGrpc.existUser                        avgt       3   3.944 ± 0.971   ms/op
ClientGrpc.getUser                          avgt       3   4.327 ± 3.884   ms/op
ClientGrpc.listUser                         avgt       3   6.033 ± 1.296   ms/op
ClientGrpc.createUser                     sample  198341   4.840 ± 0.011   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.488           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.579           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.373           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           7.348           ms/op
ClientGrpc.createUser:createUser·p0.99    sample          10.158           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          15.854           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          32.604           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          36.700           ms/op
ClientGrpc.existUser                      sample  229915   4.174 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.559           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.932           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.497           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.398           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.684           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.157           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.037           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.166           ms/op
ClientGrpc.getUser                        sample  241542   3.975 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.806           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.895           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.874           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.259           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.636           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.960           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          35.510           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          37.290           ms/op
ClientGrpc.listUser                       sample  176489   5.441 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.272           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.153           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.127           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.110           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.682           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.039           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.702           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.015           ms/op
