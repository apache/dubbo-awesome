# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.064 ops/ms
# Warmup Iteration   2: 5.029 ops/ms
# Warmup Iteration   3: 6.564 ops/ms
Iteration   1: 6.646 ops/ms
Iteration   2: 6.950 ops/ms
Iteration   3: 7.252 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.950 ±(99.9%) 5.533 ops/ms [Average]
  (min, avg, max) = (6.646, 6.950, 7.252), stdev = 0.303
  CI (99.9%): [1.416, 12.483] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.743 ops/ms
# Warmup Iteration   2: 7.008 ops/ms
# Warmup Iteration   3: 7.640 ops/ms
Iteration   1: 7.501 ops/ms
Iteration   2: 7.679 ops/ms
Iteration   3: 7.871 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.684 ±(99.9%) 3.378 ops/ms [Average]
  (min, avg, max) = (7.501, 7.684, 7.871), stdev = 0.185
  CI (99.9%): [4.306, 11.062] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.815 ops/ms
# Warmup Iteration   2: 6.443 ops/ms
# Warmup Iteration   3: 6.973 ops/ms
Iteration   1: 6.978 ops/ms
Iteration   2: 7.281 ops/ms
Iteration   3: 7.366 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.208 ±(99.9%) 3.723 ops/ms [Average]
  (min, avg, max) = (6.978, 7.208, 7.366), stdev = 0.204
  CI (99.9%): [3.485, 10.932] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.699 ops/ms
# Warmup Iteration   2: 4.988 ops/ms
# Warmup Iteration   3: 5.390 ops/ms
Iteration   1: 5.476 ops/ms
Iteration   2: 5.694 ops/ms
Iteration   3: 5.296 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.489 ±(99.9%) 3.639 ops/ms [Average]
  (min, avg, max) = (5.296, 5.489, 5.694), stdev = 0.199
  CI (99.9%): [1.849, 9.128] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.888 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.556 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.504 ±(99.9%) 0.013 ms/op
Iteration   1: 4.416 ±(99.9%) 0.004 ms/op
Iteration   2: 4.412 ±(99.9%) 0.003 ms/op
Iteration   3: 4.531 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.453 ±(99.9%) 1.237 ms/op [Average]
  (min, avg, max) = (4.412, 4.453, 4.531), stdev = 0.068
  CI (99.9%): [3.216, 5.690] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.290 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.307 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.288 ±(99.9%) 0.011 ms/op
Iteration   1: 4.099 ±(99.9%) 0.004 ms/op
Iteration   2: 4.236 ±(99.9%) 0.002 ms/op
Iteration   3: 4.085 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.140 ±(99.9%) 1.522 ms/op [Average]
  (min, avg, max) = (4.085, 4.140, 4.236), stdev = 0.083
  CI (99.9%): [2.618, 5.661] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 6.341 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.749 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.598 ±(99.9%) 0.003 ms/op
Iteration   1: 4.484 ±(99.9%) 0.004 ms/op
Iteration   2: 4.477 ±(99.9%) 0.004 ms/op
Iteration   3: 4.419 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.460 ±(99.9%) 0.650 ms/op [Average]
  (min, avg, max) = (4.419, 4.460, 4.484), stdev = 0.036
  CI (99.9%): [3.809, 5.110] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 8.269 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 6.518 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.951 ±(99.9%) 0.011 ms/op
Iteration   1: 5.837 ±(99.9%) 0.019 ms/op
Iteration   2: 5.941 ±(99.9%) 0.017 ms/op
Iteration   3: 5.778 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.852 ±(99.9%) 1.509 ms/op [Average]
  (min, avg, max) = (5.778, 5.852, 5.941), stdev = 0.083
  CI (99.9%): [4.343, 7.361] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 6.697 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.943 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.555 ±(99.9%) 0.016 ms/op
Iteration   1: 4.477 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.161 ms/op
                 createUser·p0.50:   4.301 ms/op
                 createUser·p0.90:   5.628 ms/op
                 createUser·p0.95:   6.283 ms/op
                 createUser·p0.99:   8.447 ms/op
                 createUser·p0.999:  17.896 ms/op
                 createUser·p0.9999: 22.151 ms/op
                 createUser·p1.00:   22.348 ms/op

Iteration   2: 4.483 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.116 ms/op
                 createUser·p0.50:   4.301 ms/op
                 createUser·p0.90:   5.652 ms/op
                 createUser·p0.95:   6.259 ms/op
                 createUser·p0.99:   8.618 ms/op
                 createUser·p0.999:  27.777 ms/op
                 createUser·p0.9999: 39.846 ms/op
                 createUser·p1.00:   39.911 ms/op

Iteration   3: 4.360 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.096 ms/op
                 createUser·p0.50:   4.227 ms/op
                 createUser·p0.90:   5.448 ms/op
                 createUser·p0.95:   5.980 ms/op
                 createUser·p0.99:   7.815 ms/op
                 createUser·p0.999:  12.084 ms/op
                 createUser·p0.9999: 25.013 ms/op
                 createUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 216068
  mean =      4.439 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2705 
    [ 2.500,  5.000) = 168035 
    [ 5.000,  7.500) = 41814 
    [ 7.500, 10.000) = 2687 
    [10.000, 12.500) = 466 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.096 ms/op
     p(50.0000) =      4.276 ms/op
     p(90.0000) =      5.579 ms/op
     p(95.0000) =      6.177 ms/op
     p(99.0000) =      8.258 ms/op
     p(99.9000) =     19.722 ms/op
     p(99.9900) =     39.478 ms/op
     p(99.9990) =     39.911 ms/op
     p(99.9999) =     39.911 ms/op
    p(100.0000) =     39.911 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.318 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.466 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.250 ±(99.9%) 0.012 ms/op
Iteration   1: 4.118 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.961 ms/op
                 existUser·p0.50:   3.998 ms/op
                 existUser·p0.90:   5.251 ms/op
                 existUser·p0.95:   5.931 ms/op
                 existUser·p0.99:   7.964 ms/op
                 existUser·p0.999:  11.457 ms/op
                 existUser·p0.9999: 14.961 ms/op
                 existUser·p1.00:   15.254 ms/op

Iteration   2: 4.231 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.967 ms/op
                 existUser·p0.50:   4.055 ms/op
                 existUser·p0.90:   5.259 ms/op
                 existUser·p0.95:   5.931 ms/op
                 existUser·p0.99:   8.300 ms/op
                 existUser·p0.999:  13.533 ms/op
                 existUser·p0.9999: 19.497 ms/op
                 existUser·p1.00:   20.611 ms/op

Iteration   3: 4.176 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.910 ms/op
                 existUser·p0.50:   4.051 ms/op
                 existUser·p0.90:   5.325 ms/op
                 existUser·p0.95:   5.939 ms/op
                 existUser·p0.99:   8.036 ms/op
                 existUser·p0.999:  15.039 ms/op
                 existUser·p0.9999: 21.813 ms/op
                 existUser·p1.00:   22.643 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 229886
  mean =      4.174 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8135 
    [ 2.500,  5.000) = 190119 
    [ 5.000,  7.500) = 28499 
    [ 7.500, 10.000) = 2318 
    [10.000, 12.500) = 552 
    [12.500, 15.000) = 146 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.910 ms/op
     p(50.0000) =      4.035 ms/op
     p(90.0000) =      5.276 ms/op
     p(95.0000) =      5.939 ms/op
     p(99.0000) =      8.086 ms/op
     p(99.9000) =     13.338 ms/op
     p(99.9900) =     21.005 ms/op
     p(99.9990) =     22.178 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.506 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 5.088 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.658 ±(99.9%) 0.015 ms/op
Iteration   1: 4.514 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.274 ms/op
                 getUser·p0.50:   4.334 ms/op
                 getUser·p0.90:   5.825 ms/op
                 getUser·p0.95:   6.398 ms/op
                 getUser·p0.99:   8.176 ms/op
                 getUser·p0.999:  12.435 ms/op
                 getUser·p0.9999: 21.881 ms/op
                 getUser·p1.00:   22.544 ms/op

Iteration   2: 4.255 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.141 ms/op
                 getUser·p0.50:   4.137 ms/op
                 getUser·p0.90:   5.382 ms/op
                 getUser·p0.95:   5.939 ms/op
                 getUser·p0.99:   7.709 ms/op
                 getUser·p0.999:  11.600 ms/op
                 getUser·p0.9999: 19.611 ms/op
                 getUser·p1.00:   20.054 ms/op

Iteration   3: 4.403 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.165 ms/op
                 getUser·p0.50:   4.260 ms/op
                 getUser·p0.90:   5.620 ms/op
                 getUser·p0.95:   6.160 ms/op
                 getUser·p0.99:   7.889 ms/op
                 getUser·p0.999:  10.798 ms/op
                 getUser·p0.9999: 19.267 ms/op
                 getUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 218657
  mean =      4.388 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4714 
    [ 2.500,  5.000) = 168084 
    [ 5.000,  7.500) = 42783 
    [ 7.500, 10.000) = 2565 
    [10.000, 12.500) = 332 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      4.243 ms/op
     p(90.0000) =      5.620 ms/op
     p(95.0000) =      6.185 ms/op
     p(99.0000) =      7.971 ms/op
     p(99.9000) =     11.759 ms/op
     p(99.9900) =     20.694 ms/op
     p(99.9990) =     22.153 ms/op
     p(99.9999) =     22.544 ms/op
    p(100.0000) =     22.544 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.438 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 6.536 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.843 ±(99.9%) 0.023 ms/op
Iteration   1: 6.024 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.735 ms/op
                 listUser·p0.50:   5.571 ms/op
                 listUser·p0.90:   8.348 ms/op
                 listUser·p0.95:   9.470 ms/op
                 listUser·p0.99:   12.157 ms/op
                 listUser·p0.999:  16.843 ms/op
                 listUser·p0.9999: 19.902 ms/op
                 listUser·p1.00:   20.316 ms/op

Iteration   2: 5.964 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.782 ms/op
                 listUser·p0.50:   5.562 ms/op
                 listUser·p0.90:   8.045 ms/op
                 listUser·p0.95:   9.208 ms/op
                 listUser·p0.99:   12.009 ms/op
                 listUser·p0.999:  20.611 ms/op
                 listUser·p0.9999: 30.918 ms/op
                 listUser·p1.00:   31.687 ms/op

Iteration   3: 5.740 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.184 ms/op
                 listUser·p0.50:   5.358 ms/op
                 listUser·p0.90:   7.782 ms/op
                 listUser·p0.95:   8.913 ms/op
                 listUser·p0.99:   11.715 ms/op
                 listUser·p0.999:  21.315 ms/op
                 listUser·p0.9999: 27.549 ms/op
                 listUser·p1.00:   29.622 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 162557
  mean =      5.907 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 142 
    [ 2.500,  5.000) = 49952 
    [ 5.000,  7.500) = 89603 
    [ 7.500, 10.000) = 17977 
    [10.000, 12.500) = 3640 
    [12.500, 15.000) = 790 
    [15.000, 17.500) = 199 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.184 ms/op
     p(50.0000) =      5.497 ms/op
     p(90.0000) =      8.077 ms/op
     p(95.0000) =      9.208 ms/op
     p(99.0000) =     11.977 ms/op
     p(99.9000) =     19.792 ms/op
     p(99.9900) =     29.793 ms/op
     p(99.9990) =     31.461 ms/op
     p(99.9999) =     31.687 ms/op
    p(100.0000) =     31.687 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.950 ± 5.533  ops/ms
ClientGrpc.existUser                       thrpt       3   7.684 ± 3.378  ops/ms
ClientGrpc.getUser                         thrpt       3   7.208 ± 3.723  ops/ms
ClientGrpc.listUser                        thrpt       3   5.489 ± 3.639  ops/ms
ClientGrpc.createUser                       avgt       3   4.453 ± 1.237   ms/op
ClientGrpc.existUser                        avgt       3   4.140 ± 1.522   ms/op
ClientGrpc.getUser                          avgt       3   4.460 ± 0.650   ms/op
ClientGrpc.listUser                         avgt       3   5.852 ± 1.509   ms/op
ClientGrpc.createUser                     sample  216068   4.439 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.096           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.276           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.579           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.177           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.258           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          19.722           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          39.478           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          39.911           ms/op
ClientGrpc.existUser                      sample  229886   4.174 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.910           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.035           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.276           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.939           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.086           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.338           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.005           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.643           ms/op
ClientGrpc.getUser                        sample  218657   4.388 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.141           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.243           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.620           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.185           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.971           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.759           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.694           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.544           ms/op
ClientGrpc.listUser                       sample  162557   5.907 ± 0.014   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.184           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.497           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.077           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.208           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.977           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.792           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.793           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.687           ms/op
