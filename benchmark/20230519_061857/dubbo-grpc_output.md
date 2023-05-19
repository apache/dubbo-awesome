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
# Warmup Iteration   1: 1.972 ops/ms
# Warmup Iteration   2: 4.380 ops/ms
# Warmup Iteration   3: 6.673 ops/ms
Iteration   1: 7.204 ops/ms
Iteration   2: 7.061 ops/ms
Iteration   3: 6.851 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.039 ±(99.9%) 3.243 ops/ms [Average]
  (min, avg, max) = (6.851, 7.039, 7.204), stdev = 0.178
  CI (99.9%): [3.796, 10.281] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.871 ops/ms
# Warmup Iteration   2: 5.636 ops/ms
# Warmup Iteration   3: 6.350 ops/ms
Iteration   1: 6.543 ops/ms
Iteration   2: 6.778 ops/ms
Iteration   3: 7.010 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  6.777 ±(99.9%) 4.259 ops/ms [Average]
  (min, avg, max) = (6.543, 6.777, 7.010), stdev = 0.233
  CI (99.9%): [2.518, 11.036] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.640 ops/ms
# Warmup Iteration   2: 6.225 ops/ms
# Warmup Iteration   3: 6.993 ops/ms
Iteration   1: 7.023 ops/ms
Iteration   2: 7.121 ops/ms
Iteration   3: 7.258 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.134 ±(99.9%) 2.157 ops/ms [Average]
  (min, avg, max) = (7.023, 7.134, 7.258), stdev = 0.118
  CI (99.9%): [4.977, 9.291] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.427 ops/ms
# Warmup Iteration   2: 4.843 ops/ms
# Warmup Iteration   3: 5.390 ops/ms
Iteration   1: 5.524 ops/ms
Iteration   2: 5.291 ops/ms
Iteration   3: 5.596 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.470 ±(99.9%) 2.911 ops/ms [Average]
  (min, avg, max) = (5.291, 5.470, 5.596), stdev = 0.160
  CI (99.9%): [2.559, 8.381] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.363 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 5.169 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.651 ±(99.9%) 0.007 ms/op
Iteration   1: 4.322 ±(99.9%) 0.004 ms/op
Iteration   2: 4.598 ±(99.9%) 0.003 ms/op
Iteration   3: 4.537 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.486 ±(99.9%) 2.648 ms/op [Average]
  (min, avg, max) = (4.322, 4.486, 4.598), stdev = 0.145
  CI (99.9%): [1.837, 7.134] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.888 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.772 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.604 ±(99.9%) 0.004 ms/op
Iteration   1: 4.368 ±(99.9%) 0.004 ms/op
Iteration   2: 4.343 ±(99.9%) 0.004 ms/op
Iteration   3: 4.386 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.366 ±(99.9%) 0.387 ms/op [Average]
  (min, avg, max) = (4.343, 4.366, 4.386), stdev = 0.021
  CI (99.9%): [3.978, 4.753] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.348 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 5.007 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.804 ±(99.9%) 0.004 ms/op
Iteration   1: 4.550 ±(99.9%) 0.005 ms/op
Iteration   2: 4.378 ±(99.9%) 0.002 ms/op
Iteration   3: 4.522 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.484 ±(99.9%) 1.683 ms/op [Average]
  (min, avg, max) = (4.378, 4.484, 4.550), stdev = 0.092
  CI (99.9%): [2.801, 6.166] (assumes normal distribution)


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
# Warmup Iteration   1: 9.774 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 6.447 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.939 ±(99.9%) 0.011 ms/op
Iteration   1: 5.727 ±(99.9%) 0.014 ms/op
Iteration   2: 5.728 ±(99.9%) 0.013 ms/op
Iteration   3: 5.643 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.699 ±(99.9%) 0.894 ms/op [Average]
  (min, avg, max) = (5.643, 5.699, 5.728), stdev = 0.049
  CI (99.9%): [4.806, 6.593] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 6.872 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 5.206 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.558 ±(99.9%) 0.014 ms/op
Iteration   1: 4.472 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.063 ms/op
                 createUser·p0.50:   4.350 ms/op
                 createUser·p0.90:   5.751 ms/op
                 createUser·p0.95:   6.226 ms/op
                 createUser·p0.99:   7.766 ms/op
                 createUser·p0.999:  11.547 ms/op
                 createUser·p0.9999: 21.884 ms/op
                 createUser·p1.00:   25.461 ms/op

Iteration   2: 4.524 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.104 ms/op
                 createUser·p0.50:   4.350 ms/op
                 createUser·p0.90:   5.767 ms/op
                 createUser·p0.95:   6.406 ms/op
                 createUser·p0.99:   8.716 ms/op
                 createUser·p0.999:  17.433 ms/op
                 createUser·p0.9999: 25.458 ms/op
                 createUser·p1.00:   26.214 ms/op

Iteration   3: 4.353 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.069 ms/op
                 createUser·p0.50:   4.186 ms/op
                 createUser·p0.90:   5.448 ms/op
                 createUser·p0.95:   6.029 ms/op
                 createUser·p0.99:   8.065 ms/op
                 createUser·p0.999:  16.926 ms/op
                 createUser·p0.9999: 40.370 ms/op
                 createUser·p1.00:   40.829 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 215897
  mean =      4.449 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 167786 
    [ 5.000, 10.000) = 47289 
    [10.000, 15.000) = 565 
    [15.000, 20.000) = 93 
    [20.000, 25.000) = 78 
    [25.000, 30.000) = 35 
    [30.000, 35.000) = 19 
    [35.000, 40.000) = 19 
    [40.000, 45.000) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.063 ms/op
     p(50.0000) =      4.293 ms/op
     p(90.0000) =      5.669 ms/op
     p(95.0000) =      6.226 ms/op
     p(99.0000) =      8.176 ms/op
     p(99.9000) =     17.170 ms/op
     p(99.9900) =     39.715 ms/op
     p(99.9990) =     40.622 ms/op
     p(99.9999) =     40.829 ms/op
    p(100.0000) =     40.829 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.619 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.476 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.038 ±(99.9%) 0.011 ms/op
Iteration   1: 4.223 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.939 ms/op
                 existUser·p0.50:   4.084 ms/op
                 existUser·p0.90:   5.407 ms/op
                 existUser·p0.95:   5.980 ms/op
                 existUser·p0.99:   7.528 ms/op
                 existUser·p0.999:  10.572 ms/op
                 existUser·p0.9999: 18.673 ms/op
                 existUser·p1.00:   19.104 ms/op

Iteration   2: 4.282 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.851 ms/op
                 existUser·p0.50:   4.071 ms/op
                 existUser·p0.90:   5.497 ms/op
                 existUser·p0.95:   6.201 ms/op
                 existUser·p0.99:   8.733 ms/op
                 existUser·p0.999:  14.849 ms/op
                 existUser·p0.9999: 23.366 ms/op
                 existUser·p1.00:   23.888 ms/op

Iteration   3: 4.166 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.859 ms/op
                 existUser·p0.50:   4.063 ms/op
                 existUser·p0.90:   5.259 ms/op
                 existUser·p0.95:   5.710 ms/op
                 existUser·p0.99:   7.094 ms/op
                 existUser·p0.999:  10.558 ms/op
                 existUser·p0.9999: 21.375 ms/op
                 existUser·p1.00:   23.593 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 227236
  mean =      4.223 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6835 
    [ 2.500,  5.000) = 184173 
    [ 5.000,  7.500) = 33372 
    [ 7.500, 10.000) = 2209 
    [10.000, 12.500) = 418 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.851 ms/op
     p(50.0000) =      4.076 ms/op
     p(90.0000) =      5.374 ms/op
     p(95.0000) =      5.956 ms/op
     p(99.0000) =      7.856 ms/op
     p(99.9000) =     12.546 ms/op
     p(99.9900) =     22.500 ms/op
     p(99.9990) =     23.772 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.152 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 4.497 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.516 ±(99.9%) 0.014 ms/op
Iteration   1: 4.636 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.023 ms/op
                 getUser·p0.50:   4.456 ms/op
                 getUser·p0.90:   6.046 ms/op
                 getUser·p0.95:   6.709 ms/op
                 getUser·p0.99:   8.782 ms/op
                 getUser·p0.999:  14.798 ms/op
                 getUser·p0.9999: 18.226 ms/op
                 getUser·p1.00:   18.547 ms/op

Iteration   2: 4.434 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.255 ms/op
                 getUser·p0.50:   4.309 ms/op
                 getUser·p0.90:   5.538 ms/op
                 getUser·p0.95:   6.046 ms/op
                 getUser·p0.99:   7.528 ms/op
                 getUser·p0.999:  11.218 ms/op
                 getUser·p0.9999: 19.850 ms/op
                 getUser·p1.00:   20.480 ms/op

Iteration   3: 4.830 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.055 ms/op
                 getUser·p0.50:   4.612 ms/op
                 getUser·p0.90:   6.373 ms/op
                 getUser·p0.95:   7.108 ms/op
                 getUser·p0.99:   9.388 ms/op
                 getUser·p0.999:  15.029 ms/op
                 getUser·p0.9999: 24.900 ms/op
                 getUser·p1.00:   26.477 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 207301
  mean =      4.628 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3971 
    [ 2.500,  5.000) = 143283 
    [ 5.000,  7.500) = 55076 
    [ 7.500, 10.000) = 4221 
    [10.000, 12.500) = 502 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.023 ms/op
     p(50.0000) =      4.448 ms/op
     p(90.0000) =      5.997 ms/op
     p(95.0000) =      6.660 ms/op
     p(99.0000) =      8.667 ms/op
     p(99.9000) =     13.835 ms/op
     p(99.9900) =     24.257 ms/op
     p(99.9990) =     26.376 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


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
# Warmup Iteration   1: 7.670 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 6.558 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.845 ±(99.9%) 0.023 ms/op
Iteration   1: 5.787 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.884 ms/op
                 listUser·p0.50:   5.439 ms/op
                 listUser·p0.90:   7.815 ms/op
                 listUser·p0.95:   8.716 ms/op
                 listUser·p0.99:   10.928 ms/op
                 listUser·p0.999:  16.933 ms/op
                 listUser·p0.9999: 20.008 ms/op
                 listUser·p1.00:   21.758 ms/op

Iteration   2: 5.808 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   0.630 ms/op
                 listUser·p0.50:   5.407 ms/op
                 listUser·p0.90:   8.045 ms/op
                 listUser·p0.95:   9.028 ms/op
                 listUser·p0.99:   11.387 ms/op
                 listUser·p0.999:  18.983 ms/op
                 listUser·p0.9999: 24.248 ms/op
                 listUser·p1.00:   24.642 ms/op

Iteration   3: 6.255 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   1.798 ms/op
                 listUser·p0.50:   5.784 ms/op
                 listUser·p0.90:   8.634 ms/op
                 listUser·p0.95:   9.748 ms/op
                 listUser·p0.99:   12.698 ms/op
                 listUser·p0.999:  24.205 ms/op
                 listUser·p0.9999: 40.042 ms/op
                 listUser·p1.00:   40.567 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 161555
  mean =      5.942 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 51286 
    [ 5.000, 10.000) = 105556 
    [10.000, 15.000) = 4307 
    [15.000, 20.000) = 240 
    [20.000, 25.000) = 125 
    [25.000, 30.000) = 5 
    [30.000, 35.000) = 7 
    [35.000, 40.000) = 23 
    [40.000, 45.000) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.630 ms/op
     p(50.0000) =      5.538 ms/op
     p(90.0000) =      8.151 ms/op
     p(95.0000) =      9.191 ms/op
     p(99.0000) =     11.665 ms/op
     p(99.9000) =     20.462 ms/op
     p(99.9900) =     38.722 ms/op
     p(99.9990) =     40.446 ms/op
     p(99.9999) =     40.567 ms/op
    p(100.0000) =     40.567 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.039 ± 3.243  ops/ms
ClientGrpc.existUser                       thrpt       3   6.777 ± 4.259  ops/ms
ClientGrpc.getUser                         thrpt       3   7.134 ± 2.157  ops/ms
ClientGrpc.listUser                        thrpt       3   5.470 ± 2.911  ops/ms
ClientGrpc.createUser                       avgt       3   4.486 ± 2.648   ms/op
ClientGrpc.existUser                        avgt       3   4.366 ± 0.387   ms/op
ClientGrpc.getUser                          avgt       3   4.484 ± 1.683   ms/op
ClientGrpc.listUser                         avgt       3   5.699 ± 0.894   ms/op
ClientGrpc.createUser                     sample  215897   4.449 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.063           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.293           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.669           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.226           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.176           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          17.170           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          39.715           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          40.829           ms/op
ClientGrpc.existUser                      sample  227236   4.223 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.851           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.076           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.374           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.956           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.856           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.546           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.500           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.888           ms/op
ClientGrpc.getUser                        sample  207301   4.628 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.023           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.448           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.997           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.660           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.667           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.835           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.257           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.477           ms/op
ClientGrpc.listUser                       sample  161555   5.942 ± 0.015   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.630           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.538           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.151           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.191           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.665           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.462           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          38.722           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          40.567           ms/op
