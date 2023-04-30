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
# Warmup Iteration   1: 3.320 ops/ms
# Warmup Iteration   2: 7.082 ops/ms
# Warmup Iteration   3: 7.972 ops/ms
Iteration   1: 8.711 ops/ms
Iteration   2: 8.778 ops/ms
Iteration   3: 8.561 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.684 ±(99.9%) 2.022 ops/ms [Average]
  (min, avg, max) = (8.561, 8.684, 8.778), stdev = 0.111
  CI (99.9%): [6.662, 10.705] (assumes normal distribution)


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
# Warmup Iteration   1: 5.913 ops/ms
# Warmup Iteration   2: 8.490 ops/ms
# Warmup Iteration   3: 9.085 ops/ms
Iteration   1: 9.321 ops/ms
Iteration   2: 9.337 ops/ms
Iteration   3: 9.564 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.407 ±(99.9%) 2.487 ops/ms [Average]
  (min, avg, max) = (9.321, 9.407, 9.564), stdev = 0.136
  CI (99.9%): [6.920, 11.894] (assumes normal distribution)


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
# Warmup Iteration   1: 5.168 ops/ms
# Warmup Iteration   2: 8.336 ops/ms
# Warmup Iteration   3: 8.601 ops/ms
Iteration   1: 8.697 ops/ms
Iteration   2: 8.820 ops/ms
Iteration   3: 8.962 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.826 ±(99.9%) 2.421 ops/ms [Average]
  (min, avg, max) = (8.697, 8.826, 8.962), stdev = 0.133
  CI (99.9%): [6.405, 11.248] (assumes normal distribution)


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
# Warmup Iteration   1: 4.820 ops/ms
# Warmup Iteration   2: 6.144 ops/ms
# Warmup Iteration   3: 6.692 ops/ms
Iteration   1: 6.825 ops/ms
Iteration   2: 7.098 ops/ms
Iteration   3: 7.068 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.997 ±(99.9%) 2.731 ops/ms [Average]
  (min, avg, max) = (6.825, 6.997, 7.098), stdev = 0.150
  CI (99.9%): [4.266, 9.729] (assumes normal distribution)


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
# Warmup Iteration   1: 5.551 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.936 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.798 ±(99.9%) 0.018 ms/op
Iteration   1: 3.683 ±(99.9%) 0.003 ms/op
Iteration   2: 3.685 ±(99.9%) 0.003 ms/op
Iteration   3: 3.632 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.667 ±(99.9%) 0.550 ms/op [Average]
  (min, avg, max) = (3.632, 3.667, 3.685), stdev = 0.030
  CI (99.9%): [3.117, 4.217] (assumes normal distribution)


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
# Warmup Iteration   1: 4.920 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.647 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.475 ±(99.9%) 0.003 ms/op
Iteration   1: 3.464 ±(99.9%) 0.004 ms/op
Iteration   2: 3.475 ±(99.9%) 0.002 ms/op
Iteration   3: 3.548 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.496 ±(99.9%) 0.836 ms/op [Average]
  (min, avg, max) = (3.464, 3.496, 3.548), stdev = 0.046
  CI (99.9%): [2.660, 4.332] (assumes normal distribution)


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
# Warmup Iteration   1: 5.199 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.823 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.766 ±(99.9%) 0.007 ms/op
Iteration   1: 3.661 ±(99.9%) 0.010 ms/op
Iteration   2: 3.651 ±(99.9%) 0.003 ms/op
Iteration   3: 3.662 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.658 ±(99.9%) 0.115 ms/op [Average]
  (min, avg, max) = (3.651, 3.658, 3.662), stdev = 0.006
  CI (99.9%): [3.543, 3.773] (assumes normal distribution)


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
# Warmup Iteration   1: 6.164 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 5.165 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 4.658 ±(99.9%) 0.016 ms/op
Iteration   1: 4.564 ±(99.9%) 0.009 ms/op
Iteration   2: 4.705 ±(99.9%) 0.008 ms/op
Iteration   3: 4.564 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.611 ±(99.9%) 1.484 ms/op [Average]
  (min, avg, max) = (4.564, 4.611, 4.705), stdev = 0.081
  CI (99.9%): [3.127, 6.095] (assumes normal distribution)


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
# Warmup Iteration   1: 5.608 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.871 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.701 ±(99.9%) 0.008 ms/op
Iteration   1: 3.636 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.522 ms/op
                 createUser·p0.50:   3.600 ms/op
                 createUser·p0.90:   4.284 ms/op
                 createUser·p0.95:   4.579 ms/op
                 createUser·p0.99:   5.702 ms/op
                 createUser·p0.999:  9.284 ms/op
                 createUser·p0.9999: 13.982 ms/op
                 createUser·p1.00:   14.254 ms/op

Iteration   2: 3.567 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.955 ms/op
                 createUser·p0.50:   3.531 ms/op
                 createUser·p0.90:   4.125 ms/op
                 createUser·p0.95:   4.481 ms/op
                 createUser·p0.99:   5.775 ms/op
                 createUser·p0.999:  9.131 ms/op
                 createUser·p0.9999: 16.975 ms/op
                 createUser·p1.00:   17.465 ms/op

Iteration   3: 3.644 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.901 ms/op
                 createUser·p0.50:   3.574 ms/op
                 createUser·p0.90:   4.350 ms/op
                 createUser·p0.95:   4.678 ms/op
                 createUser·p0.99:   5.972 ms/op
                 createUser·p0.999:  12.796 ms/op
                 createUser·p0.9999: 23.167 ms/op
                 createUser·p1.00:   30.671 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 265779
  mean =      3.615 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8818 
    [ 2.500,  5.000) = 250686 
    [ 5.000,  7.500) = 5463 
    [ 7.500, 10.000) = 488 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.522 ms/op
     p(50.0000) =      3.564 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      5.800 ms/op
     p(99.9000) =     11.258 ms/op
     p(99.9900) =     18.711 ms/op
     p(99.9990) =     27.548 ms/op
     p(99.9999) =     30.671 ms/op
    p(100.0000) =     30.671 ms/op


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
# Warmup Iteration   1: 5.284 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.700 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.518 ±(99.9%) 0.008 ms/op
Iteration   1: 3.545 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.963 ms/op
                 existUser·p0.50:   3.478 ms/op
                 existUser·p0.90:   4.211 ms/op
                 existUser·p0.95:   4.522 ms/op
                 existUser·p0.99:   5.939 ms/op
                 existUser·p0.999:  10.581 ms/op
                 existUser·p0.9999: 16.482 ms/op
                 existUser·p1.00:   16.908 ms/op

Iteration   2: 3.549 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.137 ms/op
                 existUser·p0.50:   3.465 ms/op
                 existUser·p0.90:   4.174 ms/op
                 existUser·p0.95:   4.432 ms/op
                 existUser·p0.99:   5.734 ms/op
                 existUser·p0.999:  12.151 ms/op
                 existUser·p0.9999: 15.400 ms/op
                 existUser·p1.00:   17.072 ms/op

Iteration   3: 3.546 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.981 ms/op
                 existUser·p0.50:   3.457 ms/op
                 existUser·p0.90:   4.125 ms/op
                 existUser·p0.95:   4.448 ms/op
                 existUser·p0.99:   5.857 ms/op
                 existUser·p0.999:  15.476 ms/op
                 existUser·p0.9999: 18.284 ms/op
                 existUser·p1.00:   18.481 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 270490
  mean =      3.547 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 5024 
    [ 2.500,  3.750) = 194014 
    [ 3.750,  5.000) = 65707 
    [ 5.000,  6.250) = 3659 
    [ 6.250,  7.500) = 899 
    [ 7.500,  8.750) = 453 
    [ 8.750, 10.000) = 219 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 152 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 59 
    [16.250, 17.500) = 53 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.963 ms/op
     p(50.0000) =      3.465 ms/op
     p(90.0000) =      4.174 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      5.857 ms/op
     p(99.9000) =     12.255 ms/op
     p(99.9900) =     17.657 ms/op
     p(99.9990) =     18.425 ms/op
     p(99.9999) =     18.481 ms/op
    p(100.0000) =     18.481 ms/op


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
# Warmup Iteration   1: 5.489 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 3.786 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.746 ±(99.9%) 0.009 ms/op
Iteration   1: 3.610 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.027 ms/op
                 getUser·p0.50:   3.555 ms/op
                 getUser·p0.90:   4.211 ms/op
                 getUser·p0.95:   4.538 ms/op
                 getUser·p0.99:   6.103 ms/op
                 getUser·p0.999:  9.716 ms/op
                 getUser·p0.9999: 22.249 ms/op
                 getUser·p1.00:   22.675 ms/op

Iteration   2: 3.612 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.073 ms/op
                 getUser·p0.50:   3.539 ms/op
                 getUser·p0.90:   4.293 ms/op
                 getUser·p0.95:   4.620 ms/op
                 getUser·p0.99:   5.825 ms/op
                 getUser·p0.999:  11.132 ms/op
                 getUser·p0.9999: 17.302 ms/op
                 getUser·p1.00:   17.695 ms/op

Iteration   3: 3.650 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.921 ms/op
                 getUser·p0.50:   3.596 ms/op
                 getUser·p0.90:   4.440 ms/op
                 getUser·p0.95:   4.760 ms/op
                 getUser·p0.99:   5.956 ms/op
                 getUser·p0.999:  9.565 ms/op
                 getUser·p0.9999: 20.110 ms/op
                 getUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 264710
  mean =      3.624 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8972 
    [ 2.500,  5.000) = 248490 
    [ 5.000,  7.500) = 6415 
    [ 7.500, 10.000) = 594 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.921 ms/op
     p(50.0000) =      3.559 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      5.939 ms/op
     p(99.9000) =      9.725 ms/op
     p(99.9900) =     21.758 ms/op
     p(99.9990) =     22.600 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


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
# Warmup Iteration   1: 5.682 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 5.155 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.719 ±(99.9%) 0.015 ms/op
Iteration   1: 4.750 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.464 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   6.095 ms/op
                 listUser·p0.95:   6.963 ms/op
                 listUser·p0.99:   8.995 ms/op
                 listUser·p0.999:  15.230 ms/op
                 listUser·p0.9999: 18.335 ms/op
                 listUser·p1.00:   18.678 ms/op

Iteration   2: 4.557 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.251 ms/op
                 listUser·p0.50:   4.399 ms/op
                 listUser·p0.90:   5.628 ms/op
                 listUser·p0.95:   6.472 ms/op
                 listUser·p0.99:   8.063 ms/op
                 listUser·p0.999:  17.582 ms/op
                 listUser·p0.9999: 21.851 ms/op
                 listUser·p1.00:   21.889 ms/op

Iteration   3: 4.737 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.106 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   6.087 ms/op
                 listUser·p0.95:   7.111 ms/op
                 listUser·p0.99:   8.831 ms/op
                 listUser·p0.999:  20.889 ms/op
                 listUser·p0.9999: 30.957 ms/op
                 listUser·p1.00:   31.425 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 205109
  mean =      4.680 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 704 
    [ 2.500,  5.000) = 159517 
    [ 5.000,  7.500) = 39677 
    [ 7.500, 10.000) = 4318 
    [10.000, 12.500) = 471 
    [12.500, 15.000) = 161 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.106 ms/op
     p(50.0000) =      4.473 ms/op
     p(90.0000) =      5.939 ms/op
     p(95.0000) =      6.857 ms/op
     p(99.0000) =      8.684 ms/op
     p(99.9000) =     16.513 ms/op
     p(99.9900) =     29.426 ms/op
     p(99.9990) =     31.321 ms/op
     p(99.9999) =     31.425 ms/op
    p(100.0000) =     31.425 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.684 ± 2.022  ops/ms
ClientGrpc.existUser                       thrpt       3   9.407 ± 2.487  ops/ms
ClientGrpc.getUser                         thrpt       3   8.826 ± 2.421  ops/ms
ClientGrpc.listUser                        thrpt       3   6.997 ± 2.731  ops/ms
ClientGrpc.createUser                       avgt       3   3.667 ± 0.550   ms/op
ClientGrpc.existUser                        avgt       3   3.496 ± 0.836   ms/op
ClientGrpc.getUser                          avgt       3   3.658 ± 0.115   ms/op
ClientGrpc.listUser                         avgt       3   4.611 ± 1.484   ms/op
ClientGrpc.createUser                     sample  265779   3.615 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.522           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.564           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.260           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.596           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.800           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.258           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.711           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.671           ms/op
ClientGrpc.existUser                      sample  270490   3.547 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.963           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.465           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.174           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.465           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.857           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.255           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.657           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.481           ms/op
ClientGrpc.getUser                        sample  264710   3.624 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.921           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.559           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.325           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.653           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.939           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.725           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.758           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.675           ms/op
ClientGrpc.listUser                       sample  205109   4.680 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.106           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.473           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.939           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.857           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.684           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.513           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.426           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.425           ms/op
