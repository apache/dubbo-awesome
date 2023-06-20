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
# Warmup Iteration   1: 1.889 ops/ms
# Warmup Iteration   2: 5.128 ops/ms
# Warmup Iteration   3: 6.720 ops/ms
Iteration   1: 6.880 ops/ms
Iteration   2: 7.264 ops/ms
Iteration   3: 7.150 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.098 ±(99.9%) 3.601 ops/ms [Average]
  (min, avg, max) = (6.880, 7.098, 7.264), stdev = 0.197
  CI (99.9%): [3.497, 10.699] (assumes normal distribution)


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
# Warmup Iteration   1: 4.446 ops/ms
# Warmup Iteration   2: 6.731 ops/ms
# Warmup Iteration   3: 7.401 ops/ms
Iteration   1: 7.537 ops/ms
Iteration   2: 7.586 ops/ms
Iteration   3: 7.890 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.671 ±(99.9%) 3.489 ops/ms [Average]
  (min, avg, max) = (7.537, 7.671, 7.890), stdev = 0.191
  CI (99.9%): [4.182, 11.160] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.698 ops/ms
# Warmup Iteration   2: 6.622 ops/ms
# Warmup Iteration   3: 7.203 ops/ms
Iteration   1: 7.245 ops/ms
Iteration   2: 7.242 ops/ms
Iteration   3: 7.267 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.251 ±(99.9%) 0.247 ops/ms [Average]
  (min, avg, max) = (7.242, 7.251, 7.267), stdev = 0.014
  CI (99.9%): [7.004, 7.499] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.408 ops/ms
# Warmup Iteration   2: 4.951 ops/ms
# Warmup Iteration   3: 5.519 ops/ms
Iteration   1: 5.626 ops/ms
Iteration   2: 5.303 ops/ms
Iteration   3: 5.458 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.462 ±(99.9%) 2.946 ops/ms [Average]
  (min, avg, max) = (5.303, 5.462, 5.626), stdev = 0.162
  CI (99.9%): [2.516, 8.409] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.947 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 5.040 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.616 ±(99.9%) 0.008 ms/op
Iteration   1: 4.554 ±(99.9%) 0.003 ms/op
Iteration   2: 4.497 ±(99.9%) 0.003 ms/op
Iteration   3: 4.490 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.514 ±(99.9%) 0.640 ms/op [Average]
  (min, avg, max) = (4.490, 4.514, 4.554), stdev = 0.035
  CI (99.9%): [3.874, 5.154] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.278 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.566 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.227 ±(99.9%) 0.003 ms/op
Iteration   1: 4.407 ±(99.9%) 0.003 ms/op
Iteration   2: 4.415 ±(99.9%) 0.002 ms/op
Iteration   3: 4.330 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.384 ±(99.9%) 0.853 ms/op [Average]
  (min, avg, max) = (4.330, 4.384, 4.415), stdev = 0.047
  CI (99.9%): [3.531, 5.237] (assumes normal distribution)


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
# Warmup Iteration   1: 7.359 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.747 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.524 ±(99.9%) 0.005 ms/op
Iteration   1: 4.581 ±(99.9%) 0.004 ms/op
Iteration   2: 4.423 ±(99.9%) 0.003 ms/op
Iteration   3: 4.406 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.470 ±(99.9%) 1.758 ms/op [Average]
  (min, avg, max) = (4.406, 4.470, 4.581), stdev = 0.096
  CI (99.9%): [2.712, 6.229] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 8.947 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 6.470 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.871 ±(99.9%) 0.016 ms/op
Iteration   1: 5.846 ±(99.9%) 0.038 ms/op
Iteration   2: 5.809 ±(99.9%) 0.019 ms/op
Iteration   3: 5.829 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.828 ±(99.9%) 0.337 ms/op [Average]
  (min, avg, max) = (5.809, 5.828, 5.846), stdev = 0.018
  CI (99.9%): [5.491, 6.164] (assumes normal distribution)


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
# Warmup Iteration   1: 6.869 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 5.518 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.718 ±(99.9%) 0.015 ms/op
Iteration   1: 4.743 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.341 ms/op
                 createUser·p0.50:   4.506 ms/op
                 createUser·p0.90:   5.964 ms/op
                 createUser·p0.95:   6.775 ms/op
                 createUser·p0.99:   9.535 ms/op
                 createUser·p0.999:  16.735 ms/op
                 createUser·p0.9999: 20.423 ms/op
                 createUser·p1.00:   20.775 ms/op

Iteration   2: 4.604 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.915 ms/op
                 createUser·p0.50:   4.481 ms/op
                 createUser·p0.90:   5.685 ms/op
                 createUser·p0.95:   6.234 ms/op
                 createUser·p0.99:   8.847 ms/op
                 createUser·p0.999:  18.285 ms/op
                 createUser·p0.9999: 24.153 ms/op
                 createUser·p1.00:   24.576 ms/op

Iteration   3: 4.546 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.098 ms/op
                 createUser·p0.50:   4.415 ms/op
                 createUser·p0.90:   5.587 ms/op
                 createUser·p0.95:   6.103 ms/op
                 createUser·p0.99:   8.323 ms/op
                 createUser·p0.999:  16.910 ms/op
                 createUser·p0.9999: 21.889 ms/op
                 createUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 207378
  mean =      4.630 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3494 
    [ 2.500,  5.000) = 150583 
    [ 5.000,  7.500) = 48719 
    [ 7.500, 10.000) = 3316 
    [10.000, 12.500) = 771 
    [12.500, 15.000) = 203 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.915 ms/op
     p(50.0000) =      4.465 ms/op
     p(90.0000) =      5.734 ms/op
     p(95.0000) =      6.357 ms/op
     p(99.0000) =      9.060 ms/op
     p(99.9000) =     17.531 ms/op
     p(99.9900) =     23.315 ms/op
     p(99.9990) =     24.473 ms/op
     p(99.9999) =     24.576 ms/op
    p(100.0000) =     24.576 ms/op


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
# Warmup Iteration   1: 6.388 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.600 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.514 ±(99.9%) 0.013 ms/op
Iteration   1: 4.371 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.233 ms/op
                 existUser·p0.50:   4.252 ms/op
                 existUser·p0.90:   5.366 ms/op
                 existUser·p0.95:   5.792 ms/op
                 existUser·p0.99:   7.438 ms/op
                 existUser·p0.999:  12.213 ms/op
                 existUser·p0.9999: 16.341 ms/op
                 existUser·p1.00:   16.908 ms/op

Iteration   2: 4.353 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.323 ms/op
                 existUser·p0.50:   4.252 ms/op
                 existUser·p0.90:   5.300 ms/op
                 existUser·p0.95:   5.726 ms/op
                 existUser·p0.99:   7.597 ms/op
                 existUser·p0.999:  11.534 ms/op
                 existUser·p0.9999: 17.334 ms/op
                 existUser·p1.00:   17.465 ms/op

Iteration   3: 4.366 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.984 ms/op
                 existUser·p0.50:   4.235 ms/op
                 existUser·p0.90:   5.333 ms/op
                 existUser·p0.95:   5.865 ms/op
                 existUser·p0.99:   8.233 ms/op
                 existUser·p0.999:  12.162 ms/op
                 existUser·p0.9999: 23.812 ms/op
                 existUser·p1.00:   23.986 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 219834
  mean =      4.363 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3596 
    [ 2.500,  5.000) = 178295 
    [ 5.000,  7.500) = 35326 
    [ 7.500, 10.000) = 2003 
    [10.000, 12.500) = 440 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.984 ms/op
     p(50.0000) =      4.243 ms/op
     p(90.0000) =      5.333 ms/op
     p(95.0000) =      5.792 ms/op
     p(99.0000) =      7.807 ms/op
     p(99.9000) =     11.947 ms/op
     p(99.9900) =     23.561 ms/op
     p(99.9990) =     23.881 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


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
# Warmup Iteration   1: 7.293 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 4.535 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.905 ±(99.9%) 0.018 ms/op
Iteration   1: 4.697 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.895 ms/op
                 getUser·p0.50:   4.538 ms/op
                 getUser·p0.90:   6.054 ms/op
                 getUser·p0.95:   6.627 ms/op
                 getUser·p0.99:   8.487 ms/op
                 getUser·p0.999:  15.988 ms/op
                 getUser·p0.9999: 17.838 ms/op
                 getUser·p1.00:   18.416 ms/op

Iteration   2: 4.646 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.159 ms/op
                 getUser·p0.50:   4.489 ms/op
                 getUser·p0.90:   5.980 ms/op
                 getUser·p0.95:   6.644 ms/op
                 getUser·p0.99:   9.060 ms/op
                 getUser·p0.999:  14.226 ms/op
                 getUser·p0.9999: 21.769 ms/op
                 getUser·p1.00:   23.167 ms/op

Iteration   3: 4.615 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.200 ms/op
                 getUser·p0.50:   4.489 ms/op
                 getUser·p0.90:   5.841 ms/op
                 getUser·p0.95:   6.488 ms/op
                 getUser·p0.99:   8.634 ms/op
                 getUser·p0.999:  13.091 ms/op
                 getUser·p0.9999: 23.134 ms/op
                 getUser·p1.00:   23.495 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 206303
  mean =      4.652 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5988 
    [ 2.500,  5.000) = 139425 
    [ 5.000,  7.500) = 56112 
    [ 7.500, 10.000) = 3808 
    [10.000, 12.500) = 613 
    [12.500, 15.000) = 170 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.895 ms/op
     p(50.0000) =      4.506 ms/op
     p(90.0000) =      5.972 ms/op
     p(95.0000) =      6.586 ms/op
     p(99.0000) =      8.716 ms/op
     p(99.9000) =     14.200 ms/op
     p(99.9900) =     22.667 ms/op
     p(99.9990) =     23.394 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


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
# Warmup Iteration   1: 9.149 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 6.776 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 6.255 ±(99.9%) 0.029 ms/op
Iteration   1: 6.243 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.384 ms/op
                 listUser·p0.50:   5.751 ms/op
                 listUser·p0.90:   8.815 ms/op
                 listUser·p0.95:   9.880 ms/op
                 listUser·p0.99:   12.612 ms/op
                 listUser·p0.999:  18.769 ms/op
                 listUser·p0.9999: 31.831 ms/op
                 listUser·p1.00:   32.178 ms/op

Iteration   2: 6.116 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.438 ms/op
                 listUser·p0.50:   5.702 ms/op
                 listUser·p0.90:   8.471 ms/op
                 listUser·p0.95:   9.503 ms/op
                 listUser·p0.99:   11.993 ms/op
                 listUser·p0.999:  25.415 ms/op
                 listUser·p0.9999: 28.263 ms/op
                 listUser·p1.00:   28.836 ms/op

Iteration   3: 6.002 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.751 ms/op
                 listUser·p0.50:   5.546 ms/op
                 listUser·p0.90:   8.405 ms/op
                 listUser·p0.95:   9.503 ms/op
                 listUser·p0.99:   12.768 ms/op
                 listUser·p0.999:  25.222 ms/op
                 listUser·p0.9999: 28.632 ms/op
                 listUser·p1.00:   28.803 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 156895
  mean =      6.119 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 244 
    [ 2.500,  5.000) = 43322 
    [ 5.000,  7.500) = 84504 
    [ 7.500, 10.000) = 22640 
    [10.000, 12.500) = 4649 
    [12.500, 15.000) = 949 
    [15.000, 17.500) = 235 
    [17.500, 20.000) = 133 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 91 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.384 ms/op
     p(50.0000) =      5.661 ms/op
     p(90.0000) =      8.585 ms/op
     p(95.0000) =      9.634 ms/op
     p(99.0000) =     12.435 ms/op
     p(99.9000) =     23.964 ms/op
     p(99.9900) =     28.635 ms/op
     p(99.9990) =     32.160 ms/op
     p(99.9999) =     32.178 ms/op
    p(100.0000) =     32.178 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.098 ± 3.601  ops/ms
ClientGrpc.existUser                       thrpt       3   7.671 ± 3.489  ops/ms
ClientGrpc.getUser                         thrpt       3   7.251 ± 0.247  ops/ms
ClientGrpc.listUser                        thrpt       3   5.462 ± 2.946  ops/ms
ClientGrpc.createUser                       avgt       3   4.514 ± 0.640   ms/op
ClientGrpc.existUser                        avgt       3   4.384 ± 0.853   ms/op
ClientGrpc.getUser                          avgt       3   4.470 ± 1.758   ms/op
ClientGrpc.listUser                         avgt       3   5.828 ± 0.337   ms/op
ClientGrpc.createUser                     sample  207378   4.630 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.915           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.465           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.734           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.357           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           9.060           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          17.531           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.315           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.576           ms/op
ClientGrpc.existUser                      sample  219834   4.363 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.984           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.243           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.333           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.792           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.807           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.947           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.561           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.986           ms/op
ClientGrpc.getUser                        sample  206303   4.652 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.895           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.506           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.972           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.586           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.716           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.200           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.667           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.495           ms/op
ClientGrpc.listUser                       sample  156895   6.119 ± 0.016   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.384           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.661           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.585           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.634           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.435           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          23.964           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.635           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.178           ms/op
