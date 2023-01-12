# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.740 ops/ms
# Warmup Iteration   2: 9.654 ops/ms
# Warmup Iteration   3: 10.481 ops/ms
Iteration   1: 10.480 ops/ms
Iteration   2: 10.459 ops/ms
Iteration   3: 10.367 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.435 ±(99.9%) 1.095 ops/ms [Average]
  (min, avg, max) = (10.367, 10.435, 10.480), stdev = 0.060
  CI (99.9%): [9.340, 11.531] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.012 ops/ms
# Warmup Iteration   2: 10.875 ops/ms
# Warmup Iteration   3: 11.072 ops/ms
Iteration   1: 11.077 ops/ms
Iteration   2: 11.133 ops/ms
Iteration   3: 11.218 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.142 ±(99.9%) 1.295 ops/ms [Average]
  (min, avg, max) = (11.077, 11.142, 11.218), stdev = 0.071
  CI (99.9%): [9.847, 12.438] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:50
# Fork: 1 of 1
# Warmup Iteration   1: 7.533 ops/ms
# Warmup Iteration   2: 10.323 ops/ms
# Warmup Iteration   3: 10.456 ops/ms
Iteration   1: 10.302 ops/ms
Iteration   2: 10.509 ops/ms
Iteration   3: 10.688 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.500 ±(99.9%) 3.519 ops/ms [Average]
  (min, avg, max) = (10.302, 10.500, 10.688), stdev = 0.193
  CI (99.9%): [6.980, 14.019] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.996 ops/ms
# Warmup Iteration   2: 7.871 ops/ms
# Warmup Iteration   3: 8.012 ops/ms
Iteration   1: 8.352 ops/ms
Iteration   2: 8.229 ops/ms
Iteration   3: 8.110 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.230 ±(99.9%) 2.210 ops/ms [Average]
  (min, avg, max) = (8.110, 8.230, 8.352), stdev = 0.121
  CI (99.9%): [6.020, 10.440] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.884 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.103 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.967 ±(99.9%) 0.002 ms/op
Iteration   1: 2.956 ±(99.9%) 0.002 ms/op
Iteration   2: 3.068 ±(99.9%) 0.002 ms/op
Iteration   3: 3.124 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.049 ±(99.9%) 1.564 ms/op [Average]
  (min, avg, max) = (2.956, 3.049, 3.124), stdev = 0.086
  CI (99.9%): [1.485, 4.613] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.693 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.065 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.941 ±(99.9%) 0.003 ms/op
Iteration   1: 2.881 ±(99.9%) 0.002 ms/op
Iteration   2: 2.901 ±(99.9%) 0.003 ms/op
Iteration   3: 2.903 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.895 ±(99.9%) 0.220 ms/op [Average]
  (min, avg, max) = (2.881, 2.895, 2.903), stdev = 0.012
  CI (99.9%): [2.675, 3.115] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.872 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.071 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.935 ±(99.9%) 0.003 ms/op
Iteration   1: 2.976 ±(99.9%) 0.002 ms/op
Iteration   2: 2.949 ±(99.9%) 0.003 ms/op
Iteration   3: 3.003 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.976 ±(99.9%) 0.492 ms/op [Average]
  (min, avg, max) = (2.949, 2.976, 3.003), stdev = 0.027
  CI (99.9%): [2.484, 3.468] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.222 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.049 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.946 ±(99.9%) 0.012 ms/op
Iteration   1: 3.972 ±(99.9%) 0.007 ms/op
Iteration   2: 3.988 ±(99.9%) 0.015 ms/op
Iteration   3: 3.882 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.948 ±(99.9%) 1.042 ms/op [Average]
  (min, avg, max) = (3.882, 3.948, 3.988), stdev = 0.057
  CI (99.9%): [2.905, 4.990] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.023 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.087 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.959 ±(99.9%) 0.006 ms/op
Iteration   1: 3.051 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.565 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   4.194 ms/op
                 createUser·p0.999:  7.662 ms/op
                 createUser·p0.9999: 14.550 ms/op
                 createUser·p1.00:   15.024 ms/op

Iteration   2: 3.052 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.592 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  8.755 ms/op
                 createUser·p0.9999: 15.852 ms/op
                 createUser·p1.00:   16.368 ms/op

Iteration   3: 3.154 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.499 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.002 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  12.437 ms/op
                 createUser·p0.9999: 31.621 ms/op
                 createUser·p1.00:   32.571 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311110
  mean =      3.085 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30837 
    [ 2.500,  5.000) = 279381 
    [ 5.000,  7.500) = 450 
    [ 7.500, 10.000) = 152 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.499 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      9.894 ms/op
     p(99.9900) =     31.446 ms/op
     p(99.9990) =     32.131 ms/op
     p(99.9999) =     32.571 ms/op
    p(100.0000) =     32.571 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.588 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.019 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.981 ±(99.9%) 0.006 ms/op
Iteration   1: 2.930 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.621 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  6.529 ms/op
                 existUser·p0.9999: 12.044 ms/op
                 existUser·p1.00:   12.468 ms/op

Iteration   2: 2.862 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.643 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.510 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  6.499 ms/op
                 existUser·p0.9999: 14.095 ms/op
                 existUser·p1.00:   15.106 ms/op

Iteration   3: 2.825 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.562 ms/op
                 existUser·p0.50:   2.839 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  7.002 ms/op
                 existUser·p0.9999: 16.734 ms/op
                 existUser·p1.00:   17.302 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 334054
  mean =      2.872 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3897 
    [ 1.250,  2.500) = 55125 
    [ 2.500,  3.750) = 261967 
    [ 3.750,  5.000) = 12157 
    [ 5.000,  6.250) = 487 
    [ 6.250,  7.500) = 168 
    [ 7.500,  8.750) = 54 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 42 
    [11.250, 12.500) = 48 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 36 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.562 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.437 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      6.595 ms/op
     p(99.9900) =     16.050 ms/op
     p(99.9990) =     17.302 ms/op
     p(99.9999) =     17.302 ms/op
    p(100.0000) =     17.302 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.873 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.086 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.006 ms/op
Iteration   1: 2.931 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.629 ms/op
                 getUser·p0.50:   2.937 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.625 ms/op
                 getUser·p0.99:   4.271 ms/op
                 getUser·p0.999:  6.353 ms/op
                 getUser·p0.9999: 17.334 ms/op
                 getUser·p1.00:   17.531 ms/op

Iteration   2: 3.041 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.690 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.895 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  5.806 ms/op
                 getUser·p0.9999: 21.768 ms/op
                 getUser·p1.00:   23.331 ms/op

Iteration   3: 2.957 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.562 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   4.153 ms/op
                 getUser·p0.999:  6.226 ms/op
                 getUser·p0.9999: 20.447 ms/op
                 getUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 322671
  mean =      2.976 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40342 
    [ 2.500,  5.000) = 281447 
    [ 5.000,  7.500) = 680 
    [ 7.500, 10.000) = 10 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.562 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      6.210 ms/op
     p(99.9900) =     20.825 ms/op
     p(99.9990) =     23.268 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.401 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.119 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.742 ±(99.9%) 0.010 ms/op
Iteration   1: 3.964 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.339 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  12.599 ms/op
                 listUser·p0.9999: 16.593 ms/op
                 listUser·p1.00:   17.007 ms/op

Iteration   2: 3.773 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.968 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   4.817 ms/op
                 listUser·p0.95:   5.423 ms/op
                 listUser·p0.99:   6.480 ms/op
                 listUser·p0.999:  16.260 ms/op
                 listUser·p0.9999: 24.822 ms/op
                 listUser·p1.00:   25.231 ms/op

Iteration   3: 3.931 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.829 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   7.242 ms/op
                 listUser·p0.999:  16.893 ms/op
                 listUser·p0.9999: 24.637 ms/op
                 listUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246907
  mean =      3.888 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5543 
    [ 2.500,  5.000) = 212746 
    [ 5.000,  7.500) = 27356 
    [ 7.500, 10.000) = 727 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 128 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.829 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      5.095 ms/op
     p(95.0000) =      5.538 ms/op
     p(99.0000) =      6.840 ms/op
     p(99.9000) =     15.598 ms/op
     p(99.9900) =     24.498 ms/op
     p(99.9990) =     25.150 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.435 ± 1.095  ops/ms
ClientGrpc.existUser                       thrpt       3  11.142 ± 1.295  ops/ms
ClientGrpc.getUser                         thrpt       3  10.500 ± 3.519  ops/ms
ClientGrpc.listUser                        thrpt       3   8.230 ± 2.210  ops/ms
ClientGrpc.createUser                       avgt       3   3.049 ± 1.564   ms/op
ClientGrpc.existUser                        avgt       3   2.895 ± 0.220   ms/op
ClientGrpc.getUser                          avgt       3   2.976 ± 0.492   ms/op
ClientGrpc.listUser                         avgt       3   3.948 ± 1.042   ms/op
ClientGrpc.createUser                     sample  311110   3.085 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.499           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.052           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.756           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.920           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.243           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.894           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          31.446           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.571           ms/op
ClientGrpc.existUser                      sample  334054   2.872 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.562           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.437           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.670           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.260           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.595           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.050           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.302           ms/op
ClientGrpc.getUser                        sample  322671   2.976 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.562           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.978           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.576           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.801           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.194           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.210           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.825           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.331           ms/op
ClientGrpc.listUser                       sample  246907   3.888 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.829           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.674           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.095           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.538           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.840           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.598           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.498           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.231           ms/op
