# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.176 ops/ms
# Warmup Iteration   2: 6.604 ops/ms
# Warmup Iteration   3: 8.224 ops/ms
Iteration   1: 8.740 ops/ms
Iteration   2: 8.826 ops/ms
Iteration   3: 8.698 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.755 ±(99.9%) 1.192 ops/ms [Average]
  (min, avg, max) = (8.698, 8.755, 8.826), stdev = 0.065
  CI (99.9%): [7.563, 9.946] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.955 ops/ms
# Warmup Iteration   2: 8.127 ops/ms
# Warmup Iteration   3: 8.553 ops/ms
Iteration   1: 9.231 ops/ms
Iteration   2: 9.281 ops/ms
Iteration   3: 9.359 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.290 ±(99.9%) 1.179 ops/ms [Average]
  (min, avg, max) = (9.231, 9.290, 9.359), stdev = 0.065
  CI (99.9%): [8.111, 10.470] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.472 ops/ms
# Warmup Iteration   2: 8.125 ops/ms
# Warmup Iteration   3: 8.668 ops/ms
Iteration   1: 8.657 ops/ms
Iteration   2: 8.743 ops/ms
Iteration   3: 8.841 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.747 ±(99.9%) 1.686 ops/ms [Average]
  (min, avg, max) = (8.657, 8.747, 8.841), stdev = 0.092
  CI (99.9%): [7.061, 10.433] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.318 ops/ms
# Warmup Iteration   2: 6.394 ops/ms
# Warmup Iteration   3: 6.703 ops/ms
Iteration   1: 6.784 ops/ms
Iteration   2: 6.807 ops/ms
Iteration   3: 6.970 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.854 ±(99.9%) 1.852 ops/ms [Average]
  (min, avg, max) = (6.784, 6.854, 6.970), stdev = 0.102
  CI (99.9%): [5.002, 8.706] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.569 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.867 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.787 ±(99.9%) 0.011 ms/op
Iteration   1: 3.736 ±(99.9%) 0.003 ms/op
Iteration   2: 3.609 ±(99.9%) 0.004 ms/op
Iteration   3: 3.585 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.643 ±(99.9%) 1.482 ms/op [Average]
  (min, avg, max) = (3.585, 3.643, 3.736), stdev = 0.081
  CI (99.9%): [2.161, 5.126] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.028 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.662 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.645 ±(99.9%) 0.004 ms/op
Iteration   1: 3.650 ±(99.9%) 0.003 ms/op
Iteration   2: 3.474 ±(99.9%) 0.003 ms/op
Iteration   3: 3.396 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.506 ±(99.9%) 2.378 ms/op [Average]
  (min, avg, max) = (3.396, 3.506, 3.650), stdev = 0.130
  CI (99.9%): [1.129, 5.884] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 4.709 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.802 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.687 ±(99.9%) 0.005 ms/op
Iteration   1: 3.685 ±(99.9%) 0.003 ms/op
Iteration   2: 3.603 ±(99.9%) 0.003 ms/op
Iteration   3: 3.593 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.627 ±(99.9%) 0.920 ms/op [Average]
  (min, avg, max) = (3.593, 3.627, 3.685), stdev = 0.050
  CI (99.9%): [2.707, 4.547] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.666 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 5.226 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.779 ±(99.9%) 0.016 ms/op
Iteration   1: 4.806 ±(99.9%) 0.009 ms/op
Iteration   2: 4.678 ±(99.9%) 0.009 ms/op
Iteration   3: 4.815 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.767 ±(99.9%) 1.395 ms/op [Average]
  (min, avg, max) = (4.678, 4.767, 4.815), stdev = 0.076
  CI (99.9%): [3.371, 6.162] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.926 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.027 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.770 ±(99.9%) 0.010 ms/op
Iteration   1: 3.706 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.114 ms/op
                 createUser·p0.50:   3.629 ms/op
                 createUser·p0.90:   4.407 ms/op
                 createUser·p0.95:   4.776 ms/op
                 createUser·p0.99:   6.259 ms/op
                 createUser·p0.999:  10.247 ms/op
                 createUser·p0.9999: 21.819 ms/op
                 createUser·p1.00:   22.086 ms/op

Iteration   2: 3.573 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.873 ms/op
                 createUser·p0.50:   3.531 ms/op
                 createUser·p0.90:   4.166 ms/op
                 createUser·p0.95:   4.555 ms/op
                 createUser·p0.99:   5.957 ms/op
                 createUser·p0.999:  9.631 ms/op
                 createUser·p0.9999: 27.690 ms/op
                 createUser·p1.00:   27.951 ms/op

Iteration   3: 3.688 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.813 ms/op
                 createUser·p0.50:   3.600 ms/op
                 createUser·p0.90:   4.350 ms/op
                 createUser·p0.95:   4.710 ms/op
                 createUser·p0.99:   6.226 ms/op
                 createUser·p0.999:  9.191 ms/op
                 createUser·p0.9999: 31.796 ms/op
                 createUser·p1.00:   36.438 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 262575
  mean =      3.655 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7459 
    [ 2.500,  5.000) = 246891 
    [ 5.000,  7.500) = 7059 
    [ 7.500, 10.000) = 942 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 19 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.813 ms/op
     p(50.0000) =      3.584 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      6.136 ms/op
     p(99.9000) =      9.667 ms/op
     p(99.9900) =     31.121 ms/op
     p(99.9990) =     33.310 ms/op
     p(99.9999) =     36.438 ms/op
    p(100.0000) =     36.438 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.305 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.023 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.756 ±(99.9%) 0.011 ms/op
Iteration   1: 3.757 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.887 ms/op
                 existUser·p0.50:   3.695 ms/op
                 existUser·p0.90:   4.596 ms/op
                 existUser·p0.95:   4.973 ms/op
                 existUser·p0.99:   6.496 ms/op
                 existUser·p0.999:  10.134 ms/op
                 existUser·p0.9999: 15.294 ms/op
                 existUser·p1.00:   15.499 ms/op

Iteration   2: 3.537 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.938 ms/op
                 existUser·p0.50:   3.478 ms/op
                 existUser·p0.90:   4.178 ms/op
                 existUser·p0.95:   4.571 ms/op
                 existUser·p0.99:   6.021 ms/op
                 existUser·p0.999:  8.857 ms/op
                 existUser·p0.9999: 16.362 ms/op
                 existUser·p1.00:   17.105 ms/op

Iteration   3: 3.602 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.614 ms/op
                 existUser·p0.50:   3.523 ms/op
                 existUser·p0.90:   4.268 ms/op
                 existUser·p0.95:   4.661 ms/op
                 existUser·p0.99:   5.957 ms/op
                 existUser·p0.999:  11.659 ms/op
                 existUser·p0.9999: 19.333 ms/op
                 existUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 264210
  mean =      3.630 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 395 
    [ 1.250,  2.500) = 9243 
    [ 2.500,  3.750) = 163103 
    [ 3.750,  5.000) = 82557 
    [ 5.000,  6.250) = 6476 
    [ 6.250,  7.500) = 1343 
    [ 7.500,  8.750) = 652 
    [ 8.750, 10.000) = 187 
    [10.000, 11.250) = 56 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 45 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.614 ms/op
     p(50.0000) =      3.551 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      6.144 ms/op
     p(99.9000) =      9.905 ms/op
     p(99.9900) =     18.899 ms/op
     p(99.9990) =     19.717 ms/op
     p(99.9999) =     19.857 ms/op
    p(100.0000) =     19.857 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.623 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.214 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.073 ±(99.9%) 0.011 ms/op
Iteration   1: 3.696 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.956 ms/op
                 getUser·p0.50:   3.621 ms/op
                 getUser·p0.90:   4.489 ms/op
                 getUser·p0.95:   4.907 ms/op
                 getUser·p0.99:   6.266 ms/op
                 getUser·p0.999:  12.481 ms/op
                 getUser·p0.9999: 14.653 ms/op
                 getUser·p1.00:   15.942 ms/op

Iteration   2: 3.606 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.864 ms/op
                 getUser·p0.50:   3.572 ms/op
                 getUser·p0.90:   4.235 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   5.251 ms/op
                 getUser·p0.999:  8.541 ms/op
                 getUser·p0.9999: 18.944 ms/op
                 getUser·p1.00:   19.038 ms/op

Iteration   3: 3.628 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.022 ms/op
                 getUser·p0.50:   3.572 ms/op
                 getUser·p0.90:   4.243 ms/op
                 getUser·p0.95:   4.497 ms/op
                 getUser·p0.99:   5.210 ms/op
                 getUser·p0.999:  8.050 ms/op
                 getUser·p0.9999: 20.087 ms/op
                 getUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 263480
  mean =      3.643 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7088 
    [ 2.500,  5.000) = 250243 
    [ 5.000,  7.500) = 5392 
    [ 7.500, 10.000) = 501 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.864 ms/op
     p(50.0000) =      3.588 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =      9.970 ms/op
     p(99.9900) =     18.961 ms/op
     p(99.9990) =     20.426 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.108 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 5.056 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.726 ±(99.9%) 0.016 ms/op
Iteration   1: 4.827 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.155 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   6.300 ms/op
                 listUser·p0.95:   7.201 ms/op
                 listUser·p0.99:   9.191 ms/op
                 listUser·p0.999:  16.067 ms/op
                 listUser·p0.9999: 18.714 ms/op
                 listUser·p1.00:   19.300 ms/op

Iteration   2: 4.636 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.288 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   5.652 ms/op
                 listUser·p0.95:   6.570 ms/op
                 listUser·p0.99:   8.634 ms/op
                 listUser·p0.999:  17.628 ms/op
                 listUser·p0.9999: 20.057 ms/op
                 listUser·p1.00:   20.218 ms/op

Iteration   3: 4.650 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.317 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.587 ms/op
                 listUser·p0.95:   6.693 ms/op
                 listUser·p0.99:   8.348 ms/op
                 listUser·p0.999:  19.464 ms/op
                 listUser·p0.9999: 21.851 ms/op
                 listUser·p1.00:   22.413 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 204177
  mean =      4.703 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 554 
    [ 2.500,  5.000) = 160002 
    [ 5.000,  7.500) = 37969 
    [ 7.500, 10.000) = 4738 
    [10.000, 12.500) = 527 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 127 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.155 ms/op
     p(50.0000) =      4.497 ms/op
     p(90.0000) =      5.882 ms/op
     p(95.0000) =      6.865 ms/op
     p(99.0000) =      8.749 ms/op
     p(99.9000) =     16.774 ms/op
     p(99.9900) =     21.496 ms/op
     p(99.9990) =     22.381 ms/op
     p(99.9999) =     22.413 ms/op
    p(100.0000) =     22.413 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.755 ± 1.192  ops/ms
ClientGrpc.existUser                       thrpt       3   9.290 ± 1.179  ops/ms
ClientGrpc.getUser                         thrpt       3   8.747 ± 1.686  ops/ms
ClientGrpc.listUser                        thrpt       3   6.854 ± 1.852  ops/ms
ClientGrpc.createUser                       avgt       3   3.643 ± 1.482   ms/op
ClientGrpc.existUser                        avgt       3   3.506 ± 2.378   ms/op
ClientGrpc.getUser                          avgt       3   3.627 ± 0.920   ms/op
ClientGrpc.listUser                         avgt       3   4.767 ± 1.395   ms/op
ClientGrpc.createUser                     sample  262575   3.655 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.813           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.584           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.317           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.702           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.136           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.667           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          31.121           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          36.438           ms/op
ClientGrpc.existUser                      sample  264210   3.630 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.614           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.551           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.383           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.760           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.144           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.905           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.899           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.857           ms/op
ClientGrpc.getUser                        sample  263480   3.643 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.864           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.588           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.309           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.604           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.693           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.970           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.961           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.775           ms/op
ClientGrpc.listUser                       sample  204177   4.703 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.155           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.497           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.882           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.865           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.749           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.774           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.496           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.413           ms/op
