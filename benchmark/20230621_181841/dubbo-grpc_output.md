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
# Warmup Iteration   1: 3.667 ops/ms
# Warmup Iteration   2: 7.426 ops/ms
# Warmup Iteration   3: 8.814 ops/ms
Iteration   1: 8.964 ops/ms
Iteration   2: 9.219 ops/ms
Iteration   3: 9.154 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.112 ±(99.9%) 2.417 ops/ms [Average]
  (min, avg, max) = (8.964, 9.112, 9.219), stdev = 0.132
  CI (99.9%): [6.695, 11.529] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 6.065 ops/ms
# Warmup Iteration   2: 8.884 ops/ms
# Warmup Iteration   3: 9.277 ops/ms
Iteration   1: 9.377 ops/ms
Iteration   2: 10.066 ops/ms
Iteration   3: 9.695 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.712 ±(99.9%) 6.296 ops/ms [Average]
  (min, avg, max) = (9.377, 9.712, 10.066), stdev = 0.345
  CI (99.9%): [3.417, 16.008] (assumes normal distribution)


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
# Warmup Iteration   1: 5.904 ops/ms
# Warmup Iteration   2: 8.800 ops/ms
# Warmup Iteration   3: 8.924 ops/ms
Iteration   1: 9.002 ops/ms
Iteration   2: 8.928 ops/ms
Iteration   3: 9.073 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.001 ±(99.9%) 1.322 ops/ms [Average]
  (min, avg, max) = (8.928, 9.001, 9.073), stdev = 0.072
  CI (99.9%): [7.680, 10.323] (assumes normal distribution)


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
# Warmup Iteration   1: 4.284 ops/ms
# Warmup Iteration   2: 6.534 ops/ms
# Warmup Iteration   3: 6.816 ops/ms
Iteration   1: 6.628 ops/ms
Iteration   2: 6.762 ops/ms
Iteration   3: 6.687 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.692 ±(99.9%) 1.228 ops/ms [Average]
  (min, avg, max) = (6.628, 6.692, 6.762), stdev = 0.067
  CI (99.9%): [5.464, 7.921] (assumes normal distribution)


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
# Warmup Iteration   1: 5.249 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.782 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.667 ±(99.9%) 0.004 ms/op
Iteration   1: 3.583 ±(99.9%) 0.005 ms/op
Iteration   2: 3.602 ±(99.9%) 0.002 ms/op
Iteration   3: 3.651 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.612 ±(99.9%) 0.643 ms/op [Average]
  (min, avg, max) = (3.583, 3.612, 3.651), stdev = 0.035
  CI (99.9%): [2.969, 4.255] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.941 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.618 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.411 ±(99.9%) 0.004 ms/op
Iteration   1: 3.416 ±(99.9%) 0.003 ms/op
Iteration   2: 3.404 ±(99.9%) 0.003 ms/op
Iteration   3: 3.453 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.425 ±(99.9%) 0.463 ms/op [Average]
  (min, avg, max) = (3.404, 3.425, 3.453), stdev = 0.025
  CI (99.9%): [2.961, 3.888] (assumes normal distribution)


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
# Warmup Iteration   1: 5.107 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.814 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.781 ±(99.9%) 0.007 ms/op
Iteration   1: 3.755 ±(99.9%) 0.005 ms/op
Iteration   2: 3.577 ±(99.9%) 0.003 ms/op
Iteration   3: 3.493 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.608 ±(99.9%) 2.443 ms/op [Average]
  (min, avg, max) = (3.493, 3.608, 3.755), stdev = 0.134
  CI (99.9%): [1.165, 6.052] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.315 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.847 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.650 ±(99.9%) 0.017 ms/op
Iteration   1: 4.588 ±(99.9%) 0.010 ms/op
Iteration   2: 4.500 ±(99.9%) 0.015 ms/op
Iteration   3: 4.606 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.565 ±(99.9%) 1.031 ms/op [Average]
  (min, avg, max) = (4.500, 4.565, 4.606), stdev = 0.056
  CI (99.9%): [3.534, 5.596] (assumes normal distribution)


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
# Warmup Iteration   1: 5.068 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.825 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.650 ±(99.9%) 0.010 ms/op
Iteration   1: 3.545 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.807 ms/op
                 createUser·p0.50:   3.506 ms/op
                 createUser·p0.90:   4.284 ms/op
                 createUser·p0.95:   4.669 ms/op
                 createUser·p0.99:   5.966 ms/op
                 createUser·p0.999:  12.285 ms/op
                 createUser·p0.9999: 20.118 ms/op
                 createUser·p1.00:   20.447 ms/op

Iteration   2: 3.584 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.987 ms/op
                 createUser·p0.50:   3.502 ms/op
                 createUser·p0.90:   4.186 ms/op
                 createUser·p0.95:   4.538 ms/op
                 createUser·p0.99:   5.997 ms/op
                 createUser·p0.999:  14.842 ms/op
                 createUser·p0.9999: 21.103 ms/op
                 createUser·p1.00:   23.593 ms/op

Iteration   3: 3.571 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.079 ms/op
                 createUser·p0.50:   3.510 ms/op
                 createUser·p0.90:   4.194 ms/op
                 createUser·p0.95:   4.547 ms/op
                 createUser·p0.99:   5.947 ms/op
                 createUser·p0.999:  8.905 ms/op
                 createUser·p0.9999: 32.154 ms/op
                 createUser·p1.00:   32.801 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 268912
  mean =      3.567 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9611 
    [ 2.500,  5.000) = 252123 
    [ 5.000,  7.500) = 6114 
    [ 7.500, 10.000) = 724 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      3.506 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      5.964 ms/op
     p(99.9000) =     11.731 ms/op
     p(99.9900) =     30.835 ms/op
     p(99.9990) =     32.473 ms/op
     p(99.9999) =     32.801 ms/op
    p(100.0000) =     32.801 ms/op


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
# Warmup Iteration   1: 4.645 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.534 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.388 ±(99.9%) 0.007 ms/op
Iteration   1: 3.424 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.566 ms/op
                 existUser·p0.50:   3.387 ms/op
                 existUser·p0.90:   4.030 ms/op
                 existUser·p0.95:   4.276 ms/op
                 existUser·p0.99:   5.070 ms/op
                 existUser·p0.999:  8.474 ms/op
                 existUser·p0.9999: 18.295 ms/op
                 existUser·p1.00:   19.333 ms/op

Iteration   2: 3.260 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.640 ms/op
                 existUser·p0.50:   3.330 ms/op
                 existUser·p0.90:   3.932 ms/op
                 existUser·p0.95:   4.157 ms/op
                 existUser·p0.99:   5.054 ms/op
                 existUser·p0.999:  7.371 ms/op
                 existUser·p0.9999: 17.832 ms/op
                 existUser·p1.00:   18.153 ms/op

Iteration   3: 3.485 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.833 ms/op
                 existUser·p0.50:   3.432 ms/op
                 existUser·p0.90:   4.141 ms/op
                 existUser·p0.95:   4.342 ms/op
                 existUser·p0.99:   5.276 ms/op
                 existUser·p0.999:  12.312 ms/op
                 existUser·p0.9999: 21.027 ms/op
                 existUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 283514
  mean =      3.387 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15370 
    [ 2.500,  5.000) = 264916 
    [ 5.000,  7.500) = 2811 
    [ 7.500, 10.000) = 224 
    [10.000, 12.500) = 8 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.566 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      4.039 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      5.128 ms/op
     p(99.9000) =      8.257 ms/op
     p(99.9900) =     19.038 ms/op
     p(99.9990) =     21.272 ms/op
     p(99.9999) =     21.299 ms/op
    p(100.0000) =     21.299 ms/op


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
# Warmup Iteration   1: 5.208 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.785 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.644 ±(99.9%) 0.010 ms/op
Iteration   1: 3.587 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.855 ms/op
                 getUser·p0.50:   3.535 ms/op
                 getUser·p0.90:   4.284 ms/op
                 getUser·p0.95:   4.645 ms/op
                 getUser·p0.99:   5.661 ms/op
                 getUser·p0.999:  9.088 ms/op
                 getUser·p0.9999: 15.766 ms/op
                 getUser·p1.00:   16.286 ms/op

Iteration   2: 3.568 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.990 ms/op
                 getUser·p0.50:   3.514 ms/op
                 getUser·p0.90:   4.182 ms/op
                 getUser·p0.95:   4.522 ms/op
                 getUser·p0.99:   5.562 ms/op
                 getUser·p0.999:  7.910 ms/op
                 getUser·p0.9999: 24.150 ms/op
                 getUser·p1.00:   25.559 ms/op

Iteration   3: 3.575 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.740 ms/op
                 getUser·p0.50:   3.518 ms/op
                 getUser·p0.90:   4.194 ms/op
                 getUser·p0.95:   4.506 ms/op
                 getUser·p0.99:   5.710 ms/op
                 getUser·p0.999:  9.618 ms/op
                 getUser·p0.9999: 18.743 ms/op
                 getUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 268477
  mean =      3.577 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7386 
    [ 2.500,  5.000) = 255026 
    [ 5.000,  7.500) = 5469 
    [ 7.500, 10.000) = 377 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.740 ms/op
     p(50.0000) =      3.523 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      5.638 ms/op
     p(99.9000) =      8.930 ms/op
     p(99.9900) =     23.532 ms/op
     p(99.9990) =     25.404 ms/op
     p(99.9999) =     25.559 ms/op
    p(100.0000) =     25.559 ms/op


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
# Warmup Iteration   1: 6.115 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 5.007 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.575 ±(99.9%) 0.015 ms/op
Iteration   1: 4.676 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.438 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.792 ms/op
                 listUser·p0.95:   6.783 ms/op
                 listUser·p0.99:   8.438 ms/op
                 listUser·p0.999:  17.142 ms/op
                 listUser·p0.9999: 20.500 ms/op
                 listUser·p1.00:   22.053 ms/op

Iteration   2: 4.693 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.081 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.685 ms/op
                 listUser·p0.95:   6.734 ms/op
                 listUser·p0.99:   8.364 ms/op
                 listUser·p0.999:  15.958 ms/op
                 listUser·p0.9999: 21.318 ms/op
                 listUser·p1.00:   21.823 ms/op

Iteration   3: 4.816 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.382 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   6.160 ms/op
                 listUser·p0.95:   6.914 ms/op
                 listUser·p0.99:   9.126 ms/op
                 listUser·p0.999:  19.373 ms/op
                 listUser·p0.9999: 22.949 ms/op
                 listUser·p1.00:   23.724 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 202937
  mean =      4.728 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 564 
    [ 2.500,  5.000) = 156783 
    [ 5.000,  7.500) = 40266 
    [ 7.500, 10.000) = 4375 
    [10.000, 12.500) = 523 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.081 ms/op
     p(50.0000) =      4.522 ms/op
     p(90.0000) =      5.931 ms/op
     p(95.0000) =      6.808 ms/op
     p(99.0000) =      8.618 ms/op
     p(99.9000) =     17.306 ms/op
     p(99.9900) =     22.436 ms/op
     p(99.9990) =     23.588 ms/op
     p(99.9999) =     23.724 ms/op
    p(100.0000) =     23.724 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.112 ± 2.417  ops/ms
ClientGrpc.existUser                       thrpt       3   9.712 ± 6.296  ops/ms
ClientGrpc.getUser                         thrpt       3   9.001 ± 1.322  ops/ms
ClientGrpc.listUser                        thrpt       3   6.692 ± 1.228  ops/ms
ClientGrpc.createUser                       avgt       3   3.612 ± 0.643   ms/op
ClientGrpc.existUser                        avgt       3   3.425 ± 0.463   ms/op
ClientGrpc.getUser                          avgt       3   3.608 ± 2.443   ms/op
ClientGrpc.listUser                         avgt       3   4.565 ± 1.031   ms/op
ClientGrpc.createUser                     sample  268912   3.567 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.807           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.506           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.219           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.588           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.964           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.731           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          30.835           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.801           ms/op
ClientGrpc.existUser                      sample  283514   3.387 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.566           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.379           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.039           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.276           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.128           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.257           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.038           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.299           ms/op
ClientGrpc.getUser                        sample  268477   3.577 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.740           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.523           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.219           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.563           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.638           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.930           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.532           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.559           ms/op
ClientGrpc.listUser                       sample  202937   4.728 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.081           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.522           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.931           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.808           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.618           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.306           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.436           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.724           ms/op
