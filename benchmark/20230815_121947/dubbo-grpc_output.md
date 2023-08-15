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
# Warmup Iteration   1: 2.568 ops/ms
# Warmup Iteration   2: 6.136 ops/ms
# Warmup Iteration   3: 8.000 ops/ms
Iteration   1: 8.275 ops/ms
Iteration   2: 8.540 ops/ms
Iteration   3: 8.573 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.463 ±(99.9%) 2.982 ops/ms [Average]
  (min, avg, max) = (8.275, 8.463, 8.573), stdev = 0.163
  CI (99.9%): [5.481, 11.445] (assumes normal distribution)


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
# Warmup Iteration   1: 5.478 ops/ms
# Warmup Iteration   2: 8.456 ops/ms
# Warmup Iteration   3: 8.825 ops/ms
Iteration   1: 9.028 ops/ms
Iteration   2: 9.410 ops/ms
Iteration   3: 9.507 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.315 ±(99.9%) 4.620 ops/ms [Average]
  (min, avg, max) = (9.028, 9.315, 9.507), stdev = 0.253
  CI (99.9%): [4.695, 13.935] (assumes normal distribution)


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
# Warmup Iteration   1: 4.883 ops/ms
# Warmup Iteration   2: 7.390 ops/ms
# Warmup Iteration   3: 7.958 ops/ms
Iteration   1: 7.659 ops/ms
Iteration   2: 8.049 ops/ms
Iteration   3: 8.662 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.123 ±(99.9%) 9.226 ops/ms [Average]
  (min, avg, max) = (7.659, 8.123, 8.662), stdev = 0.506
  CI (99.9%): [≈ 0, 17.349] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.123 ops/ms
# Warmup Iteration   2: 5.844 ops/ms
# Warmup Iteration   3: 6.614 ops/ms
Iteration   1: 6.776 ops/ms
Iteration   2: 6.433 ops/ms
Iteration   3: 6.698 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.636 ±(99.9%) 3.277 ops/ms [Average]
  (min, avg, max) = (6.433, 6.636, 6.776), stdev = 0.180
  CI (99.9%): [3.359, 9.913] (assumes normal distribution)


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
# Warmup Iteration   1: 5.964 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.178 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.190 ±(99.9%) 0.007 ms/op
Iteration   1: 4.111 ±(99.9%) 0.002 ms/op
Iteration   2: 4.071 ±(99.9%) 0.004 ms/op
Iteration   3: 3.850 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.011 ±(99.9%) 2.561 ms/op [Average]
  (min, avg, max) = (3.850, 4.011, 4.111), stdev = 0.140
  CI (99.9%): [1.450, 6.571] (assumes normal distribution)


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
# Warmup Iteration   1: 5.900 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.953 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.696 ±(99.9%) 0.005 ms/op
Iteration   1: 3.606 ±(99.9%) 0.003 ms/op
Iteration   2: 3.636 ±(99.9%) 0.004 ms/op
Iteration   3: 3.410 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.551 ±(99.9%) 2.240 ms/op [Average]
  (min, avg, max) = (3.410, 3.551, 3.636), stdev = 0.123
  CI (99.9%): [1.311, 5.791] (assumes normal distribution)


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
# Warmup Iteration   1: 5.624 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.887 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.934 ±(99.9%) 0.010 ms/op
Iteration   1: 3.880 ±(99.9%) 0.004 ms/op
Iteration   2: 3.796 ±(99.9%) 0.004 ms/op
Iteration   3: 3.888 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.855 ±(99.9%) 0.928 ms/op [Average]
  (min, avg, max) = (3.796, 3.855, 3.888), stdev = 0.051
  CI (99.9%): [2.926, 4.783] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.255 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 5.002 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.799 ±(99.9%) 0.015 ms/op
Iteration   1: 4.748 ±(99.9%) 0.028 ms/op
Iteration   2: 4.854 ±(99.9%) 0.015 ms/op
Iteration   3: 4.905 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.836 ±(99.9%) 1.458 ms/op [Average]
  (min, avg, max) = (4.748, 4.836, 4.905), stdev = 0.080
  CI (99.9%): [3.377, 6.294] (assumes normal distribution)


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
# Warmup Iteration   1: 5.360 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.016 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.994 ±(99.9%) 0.012 ms/op
Iteration   1: 3.810 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.110 ms/op
                 createUser·p0.50:   3.707 ms/op
                 createUser·p0.90:   4.866 ms/op
                 createUser·p0.95:   5.276 ms/op
                 createUser·p0.99:   7.012 ms/op
                 createUser·p0.999:  11.551 ms/op
                 createUser·p0.9999: 16.017 ms/op
                 createUser·p1.00:   16.712 ms/op

Iteration   2: 3.821 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.830 ms/op
                 createUser·p0.50:   3.695 ms/op
                 createUser·p0.90:   4.882 ms/op
                 createUser·p0.95:   5.480 ms/op
                 createUser·p0.99:   8.221 ms/op
                 createUser·p0.999:  16.130 ms/op
                 createUser·p0.9999: 25.022 ms/op
                 createUser·p1.00:   25.461 ms/op

Iteration   3: 4.027 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.751 ms/op
                 createUser·p0.50:   3.875 ms/op
                 createUser·p0.90:   5.079 ms/op
                 createUser·p0.95:   5.579 ms/op
                 createUser·p0.99:   7.780 ms/op
                 createUser·p0.999:  12.628 ms/op
                 createUser·p0.9999: 20.680 ms/op
                 createUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 247084
  mean =      3.883 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12323 
    [ 2.500,  5.000) = 212069 
    [ 5.000,  7.500) = 19902 
    [ 7.500, 10.000) = 2033 
    [10.000, 12.500) = 451 
    [12.500, 15.000) = 156 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.948 ms/op
     p(95.0000) =      5.439 ms/op
     p(99.0000) =      7.733 ms/op
     p(99.9000) =     12.943 ms/op
     p(99.9900) =     24.281 ms/op
     p(99.9990) =     25.316 ms/op
     p(99.9999) =     25.461 ms/op
    p(100.0000) =     25.461 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.028 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.037 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.703 ±(99.9%) 0.010 ms/op
Iteration   1: 3.707 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.809 ms/op
                 existUser·p0.50:   3.613 ms/op
                 existUser·p0.90:   4.669 ms/op
                 existUser·p0.95:   5.128 ms/op
                 existUser·p0.99:   7.340 ms/op
                 existUser·p0.999:  11.815 ms/op
                 existUser·p0.9999: 19.030 ms/op
                 existUser·p1.00:   19.530 ms/op

Iteration   2: 3.659 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.762 ms/op
                 existUser·p0.50:   3.551 ms/op
                 existUser·p0.90:   4.489 ms/op
                 existUser·p0.95:   5.022 ms/op
                 existUser·p0.99:   6.922 ms/op
                 existUser·p0.999:  13.058 ms/op
                 existUser·p0.9999: 33.351 ms/op
                 existUser·p1.00:   35.848 ms/op

Iteration   3: 3.635 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.916 ms/op
                 existUser·p0.50:   3.564 ms/op
                 existUser·p0.90:   4.350 ms/op
                 existUser·p0.95:   4.874 ms/op
                 existUser·p0.99:   6.529 ms/op
                 existUser·p0.999:  11.534 ms/op
                 existUser·p0.9999: 19.300 ms/op
                 existUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 261769
  mean =      3.667 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14134 
    [ 2.500,  5.000) = 234179 
    [ 5.000,  7.500) = 11421 
    [ 7.500, 10.000) = 1557 
    [10.000, 12.500) = 221 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.762 ms/op
     p(50.0000) =      3.572 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      5.022 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     12.419 ms/op
     p(99.9900) =     32.303 ms/op
     p(99.9990) =     33.736 ms/op
     p(99.9999) =     35.848 ms/op
    p(100.0000) =     35.848 ms/op


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
# Warmup Iteration   1: 6.371 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.254 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.921 ±(99.9%) 0.011 ms/op
Iteration   1: 3.949 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.709 ms/op
                 getUser·p0.50:   3.842 ms/op
                 getUser·p0.90:   4.882 ms/op
                 getUser·p0.95:   5.366 ms/op
                 getUser·p0.99:   8.200 ms/op
                 getUser·p0.999:  13.207 ms/op
                 getUser·p0.9999: 19.551 ms/op
                 getUser·p1.00:   20.906 ms/op

Iteration   2: 3.761 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.952 ms/op
                 getUser·p0.50:   3.645 ms/op
                 getUser·p0.90:   4.694 ms/op
                 getUser·p0.95:   5.136 ms/op
                 getUser·p0.99:   6.668 ms/op
                 getUser·p0.999:  12.124 ms/op
                 getUser·p0.9999: 20.332 ms/op
                 getUser·p1.00:   20.677 ms/op

Iteration   3: 3.742 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.837 ms/op
                 getUser·p0.50:   3.633 ms/op
                 getUser·p0.90:   4.571 ms/op
                 getUser·p0.95:   5.005 ms/op
                 getUser·p0.99:   7.053 ms/op
                 getUser·p0.999:  13.205 ms/op
                 getUser·p0.9999: 24.150 ms/op
                 getUser·p1.00:   24.576 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 251483
  mean =      3.815 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8584 
    [ 2.500,  5.000) = 226677 
    [ 5.000,  7.500) = 14028 
    [ 7.500, 10.000) = 1473 
    [10.000, 12.500) = 427 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.709 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.719 ms/op
     p(95.0000) =      5.177 ms/op
     p(99.0000) =      7.193 ms/op
     p(99.9000) =     12.976 ms/op
     p(99.9900) =     23.888 ms/op
     p(99.9990) =     24.525 ms/op
     p(99.9999) =     24.576 ms/op
    p(100.0000) =     24.576 ms/op


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
# Warmup Iteration   1: 7.074 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 5.177 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.864 ±(99.9%) 0.017 ms/op
Iteration   1: 4.899 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.735 ms/op
                 listUser·p0.50:   4.620 ms/op
                 listUser·p0.90:   6.513 ms/op
                 listUser·p0.95:   7.471 ms/op
                 listUser·p0.99:   9.978 ms/op
                 listUser·p0.999:  14.807 ms/op
                 listUser·p0.9999: 17.333 ms/op
                 listUser·p1.00:   18.219 ms/op

Iteration   2: 4.797 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.087 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   6.365 ms/op
                 listUser·p0.95:   7.381 ms/op
                 listUser·p0.99:   9.945 ms/op
                 listUser·p0.999:  15.663 ms/op
                 listUser·p0.9999: 18.416 ms/op
                 listUser·p1.00:   18.842 ms/op

Iteration   3: 4.717 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.270 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   6.087 ms/op
                 listUser·p0.95:   7.045 ms/op
                 listUser·p0.99:   9.190 ms/op
                 listUser·p0.999:  17.924 ms/op
                 listUser·p0.9999: 19.275 ms/op
                 listUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 199845
  mean =      4.803 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 843 
    [ 2.500,  5.000) = 140061 
    [ 5.000,  7.500) = 50366 
    [ 7.500, 10.000) = 6862 
    [10.000, 12.500) = 1125 
    [12.500, 15.000) = 302 
    [15.000, 17.500) = 142 
    [17.500, 20.000) = 141 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.087 ms/op
     p(50.0000) =      4.555 ms/op
     p(90.0000) =      6.308 ms/op
     p(95.0000) =      7.315 ms/op
     p(99.0000) =      9.699 ms/op
     p(99.9000) =     16.141 ms/op
     p(99.9900) =     19.006 ms/op
     p(99.9990) =     21.136 ms/op
     p(99.9999) =     21.791 ms/op
    p(100.0000) =     21.791 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.463 ± 2.982  ops/ms
ClientGrpc.existUser                       thrpt       3   9.315 ± 4.620  ops/ms
ClientGrpc.getUser                         thrpt       3   8.123 ± 9.226  ops/ms
ClientGrpc.listUser                        thrpt       3   6.636 ± 3.277  ops/ms
ClientGrpc.createUser                       avgt       3   4.011 ± 2.561   ms/op
ClientGrpc.existUser                        avgt       3   3.551 ± 2.240   ms/op
ClientGrpc.getUser                          avgt       3   3.855 ± 0.928   ms/op
ClientGrpc.listUser                         avgt       3   4.836 ± 1.458   ms/op
ClientGrpc.createUser                     sample  247084   3.883 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.751           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.756           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.948           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.439           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.733           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.943           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.281           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.461           ms/op
ClientGrpc.existUser                      sample  261769   3.667 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.762           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.572           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.522           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.022           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.939           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.419           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          32.303           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          35.848           ms/op
ClientGrpc.getUser                        sample  251483   3.815 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.709           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.699           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.719           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.177           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.193           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.976           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.888           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.576           ms/op
ClientGrpc.listUser                       sample  199845   4.803 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.087           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.555           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.308           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.315           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.699           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.141           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.006           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.791           ms/op
