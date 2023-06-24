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
# Warmup Iteration   1: 3.248 ops/ms
# Warmup Iteration   2: 7.337 ops/ms
# Warmup Iteration   3: 8.532 ops/ms
Iteration   1: 9.016 ops/ms
Iteration   2: 9.203 ops/ms
Iteration   3: 9.236 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.152 ±(99.9%) 2.164 ops/ms [Average]
  (min, avg, max) = (9.016, 9.152, 9.236), stdev = 0.119
  CI (99.9%): [6.988, 11.315] (assumes normal distribution)


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
# Warmup Iteration   1: 6.021 ops/ms
# Warmup Iteration   2: 8.651 ops/ms
# Warmup Iteration   3: 9.242 ops/ms
Iteration   1: 9.364 ops/ms
Iteration   2: 9.498 ops/ms
Iteration   3: 9.548 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.470 ±(99.9%) 1.733 ops/ms [Average]
  (min, avg, max) = (9.364, 9.470, 9.548), stdev = 0.095
  CI (99.9%): [7.737, 11.204] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.462 ops/ms
# Warmup Iteration   2: 8.619 ops/ms
# Warmup Iteration   3: 8.888 ops/ms
Iteration   1: 9.079 ops/ms
Iteration   2: 8.919 ops/ms
Iteration   3: 9.076 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.024 ±(99.9%) 1.669 ops/ms [Average]
  (min, avg, max) = (8.919, 9.024, 9.079), stdev = 0.092
  CI (99.9%): [7.355, 10.694] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.501 ops/ms
# Warmup Iteration   2: 6.772 ops/ms
# Warmup Iteration   3: 6.813 ops/ms
Iteration   1: 7.005 ops/ms
Iteration   2: 6.982 ops/ms
Iteration   3: 6.882 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.956 ±(99.9%) 1.197 ops/ms [Average]
  (min, avg, max) = (6.882, 6.956, 7.005), stdev = 0.066
  CI (99.9%): [5.759, 8.154] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.140 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.788 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 3.635 ±(99.9%) 0.004 ms/op
Iteration   1: 3.591 ±(99.9%) 0.013 ms/op
Iteration   2: 3.555 ±(99.9%) 0.003 ms/op
Iteration   3: 3.522 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.556 ±(99.9%) 0.629 ms/op [Average]
  (min, avg, max) = (3.522, 3.556, 3.591), stdev = 0.035
  CI (99.9%): [2.927, 4.185] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 5.063 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.577 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.321 ±(99.9%) 0.004 ms/op
Iteration   1: 3.397 ±(99.9%) 0.003 ms/op
Iteration   2: 3.366 ±(99.9%) 0.002 ms/op
Iteration   3: 3.412 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.391 ±(99.9%) 0.425 ms/op [Average]
  (min, avg, max) = (3.366, 3.391, 3.412), stdev = 0.023
  CI (99.9%): [2.967, 3.816] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.014 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.726 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.613 ±(99.9%) 0.003 ms/op
Iteration   1: 3.517 ±(99.9%) 0.004 ms/op
Iteration   2: 3.545 ±(99.9%) 0.004 ms/op
Iteration   3: 3.539 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.534 ±(99.9%) 0.261 ms/op [Average]
  (min, avg, max) = (3.517, 3.534, 3.545), stdev = 0.014
  CI (99.9%): [3.272, 3.795] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.590 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.774 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.711 ±(99.9%) 0.015 ms/op
Iteration   1: 4.519 ±(99.9%) 0.016 ms/op
Iteration   2: 4.733 ±(99.9%) 0.016 ms/op
Iteration   3: 4.572 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.608 ±(99.9%) 2.030 ms/op [Average]
  (min, avg, max) = (4.519, 4.608, 4.733), stdev = 0.111
  CI (99.9%): [2.578, 6.638] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.137 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.823 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.613 ±(99.9%) 0.009 ms/op
Iteration   1: 3.605 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.824 ms/op
                 createUser·p0.50:   3.543 ms/op
                 createUser·p0.90:   4.350 ms/op
                 createUser·p0.95:   4.710 ms/op
                 createUser·p0.99:   5.731 ms/op
                 createUser·p0.999:  11.428 ms/op
                 createUser·p0.9999: 21.398 ms/op
                 createUser·p1.00:   21.856 ms/op

Iteration   2: 3.544 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.787 ms/op
                 createUser·p0.50:   3.518 ms/op
                 createUser·p0.90:   4.202 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   5.325 ms/op
                 createUser·p0.999:  8.696 ms/op
                 createUser·p0.9999: 21.660 ms/op
                 createUser·p1.00:   21.725 ms/op

Iteration   3: 3.581 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.887 ms/op
                 createUser·p0.50:   3.523 ms/op
                 createUser·p0.90:   4.284 ms/op
                 createUser·p0.95:   4.555 ms/op
                 createUser·p0.99:   5.374 ms/op
                 createUser·p0.999:  11.195 ms/op
                 createUser·p0.9999: 25.919 ms/op
                 createUser·p1.00:   26.608 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 268344
  mean =      3.576 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9332 
    [ 2.500,  5.000) = 253567 
    [ 5.000,  7.500) = 4720 
    [ 7.500, 10.000) = 420 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.787 ms/op
     p(50.0000) =      3.531 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =     10.709 ms/op
     p(99.9900) =     25.728 ms/op
     p(99.9990) =     26.006 ms/op
     p(99.9999) =     26.608 ms/op
    p(100.0000) =     26.608 ms/op


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
# Warmup Iteration   1: 4.599 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.558 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.333 ±(99.9%) 0.008 ms/op
Iteration   1: 3.289 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.752 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.895 ms/op
                 existUser·p0.95:   4.157 ms/op
                 existUser·p0.99:   4.948 ms/op
                 existUser·p0.999:  7.976 ms/op
                 existUser·p0.9999: 15.992 ms/op
                 existUser·p1.00:   16.302 ms/op

Iteration   2: 3.403 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.219 ms/op
                 existUser·p0.50:   3.359 ms/op
                 existUser·p0.90:   3.920 ms/op
                 existUser·p0.95:   4.149 ms/op
                 existUser·p0.99:   4.751 ms/op
                 existUser·p0.999:  7.445 ms/op
                 existUser·p0.9999: 17.170 ms/op
                 existUser·p1.00:   17.695 ms/op

Iteration   3: 3.370 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.849 ms/op
                 existUser·p0.50:   3.363 ms/op
                 existUser·p0.90:   3.944 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   5.087 ms/op
                 existUser·p0.999:  6.578 ms/op
                 existUser·p0.9999: 18.317 ms/op
                 existUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 286524
  mean =      3.353 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 286 
    [ 1.250,  2.500) = 10185 
    [ 2.500,  3.750) = 227678 
    [ 3.750,  5.000) = 45774 
    [ 5.000,  6.250) = 2010 
    [ 6.250,  7.500) = 329 
    [ 7.500,  8.750) = 102 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 53 
    [16.250, 17.500) = 45 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.752 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.174 ms/op
     p(99.0000) =      4.940 ms/op
     p(99.9000) =      7.368 ms/op
     p(99.9900) =     17.619 ms/op
     p(99.9990) =     18.719 ms/op
     p(99.9999) =     18.973 ms/op
    p(100.0000) =     18.973 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.683 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.696 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.508 ±(99.9%) 0.008 ms/op
Iteration   1: 3.513 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.907 ms/op
                 getUser·p0.50:   3.478 ms/op
                 getUser·p0.90:   4.293 ms/op
                 getUser·p0.95:   4.612 ms/op
                 getUser·p0.99:   5.497 ms/op
                 getUser·p0.999:  12.401 ms/op
                 getUser·p0.9999: 15.122 ms/op
                 getUser·p1.00:   15.303 ms/op

Iteration   2: 3.450 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.856 ms/op
                 getUser·p0.50:   3.424 ms/op
                 getUser·p0.90:   4.026 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   5.546 ms/op
                 getUser·p0.999:  8.604 ms/op
                 getUser·p0.9999: 19.792 ms/op
                 getUser·p1.00:   20.283 ms/op

Iteration   3: 3.559 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.887 ms/op
                 getUser·p0.50:   3.523 ms/op
                 getUser·p0.90:   4.157 ms/op
                 getUser·p0.95:   4.415 ms/op
                 getUser·p0.99:   5.243 ms/op
                 getUser·p0.999:  7.438 ms/op
                 getUser·p0.9999: 19.759 ms/op
                 getUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 273838
  mean =      3.507 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10264 
    [ 2.500,  5.000) = 258888 
    [ 5.000,  7.500) = 4263 
    [ 7.500, 10.000) = 218 
    [10.000, 12.500) = 19 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.856 ms/op
     p(50.0000) =      3.473 ms/op
     p(90.0000) =      4.157 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      5.423 ms/op
     p(99.9000) =      8.184 ms/op
     p(99.9900) =     19.681 ms/op
     p(99.9990) =     20.661 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


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
# Warmup Iteration   1: 5.594 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 5.041 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.773 ±(99.9%) 0.015 ms/op
Iteration   1: 4.595 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.651 ms/op
                 listUser·p0.50:   4.366 ms/op
                 listUser·p0.90:   5.775 ms/op
                 listUser·p0.95:   6.611 ms/op
                 listUser·p0.99:   8.331 ms/op
                 listUser·p0.999:  16.286 ms/op
                 listUser·p0.9999: 23.791 ms/op
                 listUser·p1.00:   24.117 ms/op

Iteration   2: 4.628 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.212 ms/op
                 listUser·p0.50:   4.391 ms/op
                 listUser·p0.90:   5.939 ms/op
                 listUser·p0.95:   6.693 ms/op
                 listUser·p0.99:   8.290 ms/op
                 listUser·p0.999:  18.216 ms/op
                 listUser·p0.9999: 33.471 ms/op
                 listUser·p1.00:   34.144 ms/op

Iteration   3: 4.591 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.384 ms/op
                 listUser·p0.50:   4.391 ms/op
                 listUser·p0.90:   5.710 ms/op
                 listUser·p0.95:   6.627 ms/op
                 listUser·p0.99:   8.061 ms/op
                 listUser·p0.999:  20.185 ms/op
                 listUser·p0.9999: 32.768 ms/op
                 listUser·p1.00:   33.260 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 208432
  mean =      4.604 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 505 
    [ 2.500,  5.000) = 166637 
    [ 5.000,  7.500) = 36968 
    [ 7.500, 10.000) = 3461 
    [10.000, 12.500) = 343 
    [12.500, 15.000) = 181 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.212 ms/op
     p(50.0000) =      4.383 ms/op
     p(90.0000) =      5.816 ms/op
     p(95.0000) =      6.644 ms/op
     p(99.0000) =      8.208 ms/op
     p(99.9000) =     17.859 ms/op
     p(99.9900) =     32.577 ms/op
     p(99.9990) =     34.062 ms/op
     p(99.9999) =     34.144 ms/op
    p(100.0000) =     34.144 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.152 ± 2.164  ops/ms
ClientGrpc.existUser                       thrpt       3   9.470 ± 1.733  ops/ms
ClientGrpc.getUser                         thrpt       3   9.024 ± 1.669  ops/ms
ClientGrpc.listUser                        thrpt       3   6.956 ± 1.197  ops/ms
ClientGrpc.createUser                       avgt       3   3.556 ± 0.629   ms/op
ClientGrpc.existUser                        avgt       3   3.391 ± 0.425   ms/op
ClientGrpc.getUser                          avgt       3   3.534 ± 0.261   ms/op
ClientGrpc.listUser                         avgt       3   4.608 ± 2.030   ms/op
ClientGrpc.createUser                     sample  268344   3.576 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.787           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.531           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.276           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.579           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.489           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.709           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.728           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.608           ms/op
ClientGrpc.existUser                      sample  286524   3.353 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.752           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.326           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.920           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.174           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.940           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.368           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.619           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.973           ms/op
ClientGrpc.getUser                        sample  273838   3.507 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.856           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.473           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.157           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.465           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.423           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.184           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.681           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.775           ms/op
ClientGrpc.listUser                       sample  208432   4.604 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.212           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.383           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.816           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.644           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.208           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.859           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.577           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.144           ms/op
