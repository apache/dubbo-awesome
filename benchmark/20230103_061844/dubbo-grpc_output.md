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
# Warmup Iteration   1: 2.297 ops/ms
# Warmup Iteration   2: 5.562 ops/ms
# Warmup Iteration   3: 7.076 ops/ms
Iteration   1: 7.334 ops/ms
Iteration   2: 7.343 ops/ms
Iteration   3: 7.355 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.344 ±(99.9%) 0.191 ops/ms [Average]
  (min, avg, max) = (7.334, 7.344, 7.355), stdev = 0.010
  CI (99.9%): [7.153, 7.535] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.696 ops/ms
# Warmup Iteration   2: 7.440 ops/ms
# Warmup Iteration   3: 7.567 ops/ms
Iteration   1: 7.906 ops/ms
Iteration   2: 7.732 ops/ms
Iteration   3: 8.118 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.919 ±(99.9%) 3.533 ops/ms [Average]
  (min, avg, max) = (7.732, 7.919, 8.118), stdev = 0.194
  CI (99.9%): [4.386, 11.452] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.451 ops/ms
# Warmup Iteration   2: 6.784 ops/ms
# Warmup Iteration   3: 7.216 ops/ms
Iteration   1: 7.697 ops/ms
Iteration   2: 7.768 ops/ms
Iteration   3: 7.835 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.767 ±(99.9%) 1.257 ops/ms [Average]
  (min, avg, max) = (7.697, 7.767, 7.835), stdev = 0.069
  CI (99.9%): [6.510, 9.024] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.740 ops/ms
# Warmup Iteration   2: 5.172 ops/ms
# Warmup Iteration   3: 5.785 ops/ms
Iteration   1: 5.687 ops/ms
Iteration   2: 5.873 ops/ms
Iteration   3: 5.723 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.761 ±(99.9%) 1.795 ops/ms [Average]
  (min, avg, max) = (5.687, 5.761, 5.873), stdev = 0.098
  CI (99.9%): [3.966, 7.556] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.803 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.630 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.702 ±(99.9%) 0.014 ms/op
Iteration   1: 4.598 ±(99.9%) 0.003 ms/op
Iteration   2: 4.499 ±(99.9%) 0.005 ms/op
Iteration   3: 4.675 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.590 ±(99.9%) 1.613 ms/op [Average]
  (min, avg, max) = (4.499, 4.590, 4.675), stdev = 0.088
  CI (99.9%): [2.978, 6.203] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.323 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.424 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.171 ±(99.9%) 0.010 ms/op
Iteration   1: 4.288 ±(99.9%) 0.004 ms/op
Iteration   2: 4.184 ±(99.9%) 0.003 ms/op
Iteration   3: 4.120 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.197 ±(99.9%) 1.548 ms/op [Average]
  (min, avg, max) = (4.120, 4.197, 4.288), stdev = 0.085
  CI (99.9%): [2.649, 5.745] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.671 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.791 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.582 ±(99.9%) 0.010 ms/op
Iteration   1: 4.330 ±(99.9%) 0.003 ms/op
Iteration   2: 4.512 ±(99.9%) 0.009 ms/op
Iteration   3: 4.329 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.390 ±(99.9%) 1.922 ms/op [Average]
  (min, avg, max) = (4.329, 4.390, 4.512), stdev = 0.105
  CI (99.9%): [2.469, 6.312] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.603 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 5.963 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.425 ±(99.9%) 0.011 ms/op
Iteration   1: 5.623 ±(99.9%) 0.011 ms/op
Iteration   2: 5.426 ±(99.9%) 0.018 ms/op
Iteration   3: 5.303 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.451 ±(99.9%) 2.946 ms/op [Average]
  (min, avg, max) = (5.303, 5.451, 5.623), stdev = 0.161
  CI (99.9%): [2.505, 8.397] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.607 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.684 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.392 ±(99.9%) 0.013 ms/op
Iteration   1: 4.371 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.481 ms/op
                 createUser·p0.50:   4.190 ms/op
                 createUser·p0.90:   5.571 ms/op
                 createUser·p0.95:   6.054 ms/op
                 createUser·p0.99:   8.339 ms/op
                 createUser·p0.999:  16.159 ms/op
                 createUser·p0.9999: 26.193 ms/op
                 createUser·p1.00:   28.508 ms/op

Iteration   2: 4.469 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.257 ms/op
                 createUser·p0.50:   4.350 ms/op
                 createUser·p0.90:   5.702 ms/op
                 createUser·p0.95:   6.128 ms/op
                 createUser·p0.99:   7.586 ms/op
                 createUser·p0.999:  11.280 ms/op
                 createUser·p0.9999: 25.811 ms/op
                 createUser·p1.00:   26.313 ms/op

Iteration   3: 4.445 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.611 ms/op
                 createUser·p0.50:   4.342 ms/op
                 createUser·p0.90:   5.661 ms/op
                 createUser·p0.95:   6.087 ms/op
                 createUser·p0.99:   7.507 ms/op
                 createUser·p0.999:  11.240 ms/op
                 createUser·p0.9999: 43.674 ms/op
                 createUser·p1.00:   44.302 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 216742
  mean =      4.428 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 163685 
    [ 5.000, 10.000) = 52460 
    [10.000, 15.000) = 449 
    [15.000, 20.000) = 20 
    [20.000, 25.000) = 72 
    [25.000, 30.000) = 24 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.481 ms/op
     p(50.0000) =      4.284 ms/op
     p(90.0000) =      5.652 ms/op
     p(95.0000) =      6.087 ms/op
     p(99.0000) =      7.758 ms/op
     p(99.9000) =     11.965 ms/op
     p(99.9900) =     41.157 ms/op
     p(99.9990) =     44.160 ms/op
     p(99.9999) =     44.302 ms/op
    p(100.0000) =     44.302 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.969 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.401 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.512 ±(99.9%) 0.014 ms/op
Iteration   1: 4.409 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.317 ms/op
                 existUser·p0.50:   4.284 ms/op
                 existUser·p0.90:   5.521 ms/op
                 existUser·p0.95:   6.029 ms/op
                 existUser·p0.99:   8.339 ms/op
                 existUser·p0.999:  14.212 ms/op
                 existUser·p0.9999: 15.589 ms/op
                 existUser·p1.00:   15.843 ms/op

Iteration   2: 4.228 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.035 ms/op
                 existUser·p0.50:   4.141 ms/op
                 existUser·p0.90:   5.349 ms/op
                 existUser·p0.95:   5.775 ms/op
                 existUser·p0.99:   8.292 ms/op
                 existUser·p0.999:  12.260 ms/op
                 existUser·p0.9999: 18.241 ms/op
                 existUser·p1.00:   19.497 ms/op

Iteration   3: 4.180 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.135 ms/op
                 existUser·p0.50:   4.116 ms/op
                 existUser·p0.90:   5.374 ms/op
                 existUser·p0.95:   5.726 ms/op
                 existUser·p0.99:   6.980 ms/op
                 existUser·p0.999:  12.279 ms/op
                 existUser·p0.9999: 21.628 ms/op
                 existUser·p1.00:   22.086 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 224843
  mean =      4.270 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6947 
    [ 2.500,  5.000) = 173637 
    [ 5.000,  7.500) = 41498 
    [ 7.500, 10.000) = 2153 
    [10.000, 12.500) = 298 
    [12.500, 15.000) = 205 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.035 ms/op
     p(50.0000) =      4.182 ms/op
     p(90.0000) =      5.415 ms/op
     p(95.0000) =      5.833 ms/op
     p(99.0000) =      7.848 ms/op
     p(99.9000) =     13.506 ms/op
     p(99.9900) =     19.220 ms/op
     p(99.9990) =     21.963 ms/op
     p(99.9999) =     22.086 ms/op
    p(100.0000) =     22.086 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.338 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.832 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.581 ±(99.9%) 0.014 ms/op
Iteration   1: 4.344 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.008 ms/op
                 getUser·p0.50:   4.211 ms/op
                 getUser·p0.90:   5.603 ms/op
                 getUser·p0.95:   6.062 ms/op
                 getUser·p0.99:   7.692 ms/op
                 getUser·p0.999:  14.598 ms/op
                 getUser·p0.9999: 15.535 ms/op
                 getUser·p1.00:   16.056 ms/op

Iteration   2: 4.369 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.024 ms/op
                 getUser·p0.50:   4.260 ms/op
                 getUser·p0.90:   5.620 ms/op
                 getUser·p0.95:   6.078 ms/op
                 getUser·p0.99:   7.810 ms/op
                 getUser·p0.999:  14.049 ms/op
                 getUser·p0.9999: 27.570 ms/op
                 getUser·p1.00:   28.017 ms/op

Iteration   3: 4.417 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.937 ms/op
                 getUser·p0.50:   4.301 ms/op
                 getUser·p0.90:   5.636 ms/op
                 getUser·p0.95:   6.029 ms/op
                 getUser·p0.99:   7.782 ms/op
                 getUser·p0.999:  12.747 ms/op
                 getUser·p0.9999: 22.610 ms/op
                 getUser·p1.00:   23.134 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 219220
  mean =      4.376 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4323 
    [ 2.500,  5.000) = 163264 
    [ 5.000,  7.500) = 49022 
    [ 7.500, 10.000) = 1902 
    [10.000, 12.500) = 411 
    [12.500, 15.000) = 179 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.937 ms/op
     p(50.0000) =      4.252 ms/op
     p(90.0000) =      5.620 ms/op
     p(95.0000) =      6.062 ms/op
     p(99.0000) =      7.758 ms/op
     p(99.9000) =     13.661 ms/op
     p(99.9900) =     27.074 ms/op
     p(99.9990) =     27.893 ms/op
     p(99.9999) =     28.017 ms/op
    p(100.0000) =     28.017 ms/op


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
# Warmup Iteration   1: 7.968 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 6.077 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.292 ±(99.9%) 0.019 ms/op
Iteration   1: 5.429 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.667 ms/op
                 listUser·p0.50:   5.169 ms/op
                 listUser·p0.90:   7.168 ms/op
                 listUser·p0.95:   8.028 ms/op
                 listUser·p0.99:   10.011 ms/op
                 listUser·p0.999:  16.581 ms/op
                 listUser·p0.9999: 21.088 ms/op
                 listUser·p1.00:   21.561 ms/op

Iteration   2: 5.258 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.477 ms/op
                 listUser·p0.50:   5.014 ms/op
                 listUser·p0.90:   6.898 ms/op
                 listUser·p0.95:   7.791 ms/op
                 listUser·p0.99:   9.529 ms/op
                 listUser·p0.999:  18.114 ms/op
                 listUser·p0.9999: 25.450 ms/op
                 listUser·p1.00:   25.985 ms/op

Iteration   3: 5.421 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.391 ms/op
                 listUser·p0.50:   5.186 ms/op
                 listUser·p0.90:   7.086 ms/op
                 listUser·p0.95:   7.930 ms/op
                 listUser·p0.99:   10.125 ms/op
                 listUser·p0.999:  24.085 ms/op
                 listUser·p0.9999: 29.799 ms/op
                 listUser·p1.00:   33.554 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 178739
  mean =      5.368 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 231 
    [ 2.500,  5.000) = 79812 
    [ 5.000,  7.500) = 86074 
    [ 7.500, 10.000) = 10962 
    [10.000, 12.500) = 1185 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.391 ms/op
     p(50.0000) =      5.120 ms/op
     p(90.0000) =      7.053 ms/op
     p(95.0000) =      7.913 ms/op
     p(99.0000) =      9.896 ms/op
     p(99.9000) =     20.456 ms/op
     p(99.9900) =     28.406 ms/op
     p(99.9990) =     33.271 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.344 ± 0.191  ops/ms
ClientGrpc.existUser                       thrpt       3   7.919 ± 3.533  ops/ms
ClientGrpc.getUser                         thrpt       3   7.767 ± 1.257  ops/ms
ClientGrpc.listUser                        thrpt       3   5.761 ± 1.795  ops/ms
ClientGrpc.createUser                       avgt       3   4.590 ± 1.613   ms/op
ClientGrpc.existUser                        avgt       3   4.197 ± 1.548   ms/op
ClientGrpc.getUser                          avgt       3   4.390 ± 1.922   ms/op
ClientGrpc.listUser                         avgt       3   5.451 ± 2.946   ms/op
ClientGrpc.createUser                     sample  216742   4.428 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.481           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.284           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.652           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.087           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.758           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.965           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          41.157           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          44.302           ms/op
ClientGrpc.existUser                      sample  224843   4.270 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.035           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.182           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.415           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.833           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.848           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.506           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.220           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.086           ms/op
ClientGrpc.getUser                        sample  219220   4.376 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.937           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.252           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.620           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.062           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.758           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.661           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.074           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.017           ms/op
ClientGrpc.listUser                       sample  178739   5.368 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.391           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.120           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.053           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.913           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.896           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.456           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.406           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.554           ms/op
