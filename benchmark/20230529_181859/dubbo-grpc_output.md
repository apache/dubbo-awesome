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
# Warmup Iteration   1: 3.245 ops/ms
# Warmup Iteration   2: 6.497 ops/ms
# Warmup Iteration   3: 7.965 ops/ms
Iteration   1: 8.460 ops/ms
Iteration   2: 8.507 ops/ms
Iteration   3: 8.371 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.446 ±(99.9%) 1.264 ops/ms [Average]
  (min, avg, max) = (8.371, 8.446, 8.507), stdev = 0.069
  CI (99.9%): [7.182, 9.711] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 6.019 ops/ms
# Warmup Iteration   2: 8.530 ops/ms
# Warmup Iteration   3: 9.109 ops/ms
Iteration   1: 9.367 ops/ms
Iteration   2: 9.374 ops/ms
Iteration   3: 9.254 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.332 ±(99.9%) 1.229 ops/ms [Average]
  (min, avg, max) = (9.254, 9.332, 9.374), stdev = 0.067
  CI (99.9%): [8.103, 10.561] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.550 ops/ms
# Warmup Iteration   2: 8.176 ops/ms
# Warmup Iteration   3: 8.702 ops/ms
Iteration   1: 8.597 ops/ms
Iteration   2: 8.666 ops/ms
Iteration   3: 8.558 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.607 ±(99.9%) 0.997 ops/ms [Average]
  (min, avg, max) = (8.558, 8.607, 8.666), stdev = 0.055
  CI (99.9%): [7.609, 9.604] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.409 ops/ms
# Warmup Iteration   2: 6.601 ops/ms
# Warmup Iteration   3: 6.861 ops/ms
Iteration   1: 7.005 ops/ms
Iteration   2: 6.973 ops/ms
Iteration   3: 7.072 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.017 ±(99.9%) 0.924 ops/ms [Average]
  (min, avg, max) = (6.973, 7.017, 7.072), stdev = 0.051
  CI (99.9%): [6.093, 7.941] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.281 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.647 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.611 ±(99.9%) 0.011 ms/op
Iteration   1: 3.615 ±(99.9%) 0.003 ms/op
Iteration   2: 3.720 ±(99.9%) 0.003 ms/op
Iteration   3: 3.516 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.617 ±(99.9%) 1.856 ms/op [Average]
  (min, avg, max) = (3.516, 3.617, 3.720), stdev = 0.102
  CI (99.9%): [1.761, 5.473] (assumes normal distribution)


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
# Warmup Iteration   1: 4.478 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.503 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.487 ±(99.9%) 0.004 ms/op
Iteration   1: 3.473 ±(99.9%) 0.002 ms/op
Iteration   2: 3.383 ±(99.9%) 0.002 ms/op
Iteration   3: 3.379 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.412 ±(99.9%) 0.971 ms/op [Average]
  (min, avg, max) = (3.379, 3.412, 3.473), stdev = 0.053
  CI (99.9%): [2.441, 4.383] (assumes normal distribution)


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
# Warmup Iteration   1: 4.979 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 3.827 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.651 ±(99.9%) 0.004 ms/op
Iteration   1: 3.603 ±(99.9%) 0.003 ms/op
Iteration   2: 3.674 ±(99.9%) 0.004 ms/op
Iteration   3: 3.669 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.649 ±(99.9%) 0.727 ms/op [Average]
  (min, avg, max) = (3.603, 3.649, 3.674), stdev = 0.040
  CI (99.9%): [2.922, 4.376] (assumes normal distribution)


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
# Warmup Iteration   1: 6.930 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.907 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.582 ±(99.9%) 0.014 ms/op
Iteration   1: 4.852 ±(99.9%) 0.028 ms/op
Iteration   2: 4.708 ±(99.9%) 0.024 ms/op
Iteration   3: 4.688 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.749 ±(99.9%) 1.634 ms/op [Average]
  (min, avg, max) = (4.688, 4.749, 4.852), stdev = 0.090
  CI (99.9%): [3.115, 6.383] (assumes normal distribution)


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
# Warmup Iteration   1: 5.440 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.895 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.718 ±(99.9%) 0.009 ms/op
Iteration   1: 3.740 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.986 ms/op
                 createUser·p0.50:   3.666 ms/op
                 createUser·p0.90:   4.604 ms/op
                 createUser·p0.95:   5.014 ms/op
                 createUser·p0.99:   6.423 ms/op
                 createUser·p0.999:  11.092 ms/op
                 createUser·p0.9999: 16.326 ms/op
                 createUser·p1.00:   16.974 ms/op

Iteration   2: 3.539 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.864 ms/op
                 createUser·p0.50:   3.510 ms/op
                 createUser·p0.90:   4.133 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  7.513 ms/op
                 createUser·p0.9999: 17.004 ms/op
                 createUser·p1.00:   17.367 ms/op

Iteration   3: 3.655 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.834 ms/op
                 createUser·p0.50:   3.559 ms/op
                 createUser·p0.90:   4.375 ms/op
                 createUser·p0.95:   4.719 ms/op
                 createUser·p0.99:   5.931 ms/op
                 createUser·p0.999:  19.208 ms/op
                 createUser·p0.9999: 22.973 ms/op
                 createUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 263786
  mean =      3.643 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9110 
    [ 2.500,  5.000) = 245722 
    [ 5.000,  7.500) = 8118 
    [ 7.500, 10.000) = 564 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.834 ms/op
     p(50.0000) =      3.568 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      5.947 ms/op
     p(99.9000) =     10.764 ms/op
     p(99.9900) =     22.368 ms/op
     p(99.9990) =     23.331 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


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
# Warmup Iteration   1: 4.801 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.832 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.636 ±(99.9%) 0.008 ms/op
Iteration   1: 3.470 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.826 ms/op
                 existUser·p0.50:   3.424 ms/op
                 existUser·p0.90:   4.063 ms/op
                 existUser·p0.95:   4.399 ms/op
                 existUser·p0.99:   5.571 ms/op
                 existUser·p0.999:  8.804 ms/op
                 existUser·p0.9999: 15.050 ms/op
                 existUser·p1.00:   15.254 ms/op

Iteration   2: 3.430 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.851 ms/op
                 existUser·p0.50:   3.396 ms/op
                 existUser·p0.90:   4.047 ms/op
                 existUser·p0.95:   4.375 ms/op
                 existUser·p0.99:   5.169 ms/op
                 existUser·p0.999:  7.953 ms/op
                 existUser·p0.9999: 14.910 ms/op
                 existUser·p1.00:   17.203 ms/op

Iteration   3: 3.433 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.895 ms/op
                 existUser·p0.50:   3.408 ms/op
                 existUser·p0.90:   4.100 ms/op
                 existUser·p0.95:   4.456 ms/op
                 existUser·p0.99:   5.600 ms/op
                 existUser·p0.999:  9.093 ms/op
                 existUser·p0.9999: 26.302 ms/op
                 existUser·p1.00:   27.263 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 278727
  mean =      3.445 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11939 
    [ 2.500,  5.000) = 261718 
    [ 5.000,  7.500) = 4543 
    [ 7.500, 10.000) = 345 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.826 ms/op
     p(50.0000) =      3.408 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =      8.618 ms/op
     p(99.9900) =     24.613 ms/op
     p(99.9990) =     27.230 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


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
# Warmup Iteration   1: 5.145 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.856 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.710 ±(99.9%) 0.009 ms/op
Iteration   1: 3.612 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.137 ms/op
                 getUser·p0.50:   3.531 ms/op
                 getUser·p0.90:   4.309 ms/op
                 getUser·p0.95:   4.661 ms/op
                 getUser·p0.99:   5.997 ms/op
                 getUser·p0.999:  10.673 ms/op
                 getUser·p0.9999: 14.207 ms/op
                 getUser·p1.00:   14.336 ms/op

Iteration   2: 3.707 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.957 ms/op
                 getUser·p0.50:   3.596 ms/op
                 getUser·p0.90:   4.383 ms/op
                 getUser·p0.95:   4.768 ms/op
                 getUser·p0.99:   6.349 ms/op
                 getUser·p0.999:  11.758 ms/op
                 getUser·p0.9999: 17.194 ms/op
                 getUser·p1.00:   20.644 ms/op

Iteration   3: 3.662 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.996 ms/op
                 getUser·p0.50:   3.584 ms/op
                 getUser·p0.90:   4.432 ms/op
                 getUser·p0.95:   4.784 ms/op
                 getUser·p0.99:   6.087 ms/op
                 getUser·p0.999:  9.077 ms/op
                 getUser·p0.9999: 17.531 ms/op
                 getUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 262237
  mean =      3.660 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6125 
    [ 2.500,  5.000) = 247715 
    [ 5.000,  7.500) = 7220 
    [ 7.500, 10.000) = 821 
    [10.000, 12.500) = 181 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.957 ms/op
     p(50.0000) =      3.572 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      6.128 ms/op
     p(99.9000) =     10.465 ms/op
     p(99.9900) =     17.007 ms/op
     p(99.9990) =     20.296 ms/op
     p(99.9999) =     20.644 ms/op
    p(100.0000) =     20.644 ms/op


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
# Warmup Iteration   1: 6.728 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 5.026 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.703 ±(99.9%) 0.016 ms/op
Iteration   1: 4.678 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.481 ms/op
                 listUser·p0.50:   4.440 ms/op
                 listUser·p0.90:   6.046 ms/op
                 listUser·p0.95:   6.971 ms/op
                 listUser·p0.99:   9.093 ms/op
                 listUser·p0.999:  16.578 ms/op
                 listUser·p0.9999: 21.881 ms/op
                 listUser·p1.00:   22.544 ms/op

Iteration   2: 4.569 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.366 ms/op
                 listUser·p0.50:   4.366 ms/op
                 listUser·p0.90:   5.693 ms/op
                 listUser·p0.95:   6.611 ms/op
                 listUser·p0.99:   8.487 ms/op
                 listUser·p0.999:  17.945 ms/op
                 listUser·p0.9999: 23.593 ms/op
                 listUser·p1.00:   24.347 ms/op

Iteration   3: 4.827 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   0.886 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   6.169 ms/op
                 listUser·p0.95:   7.037 ms/op
                 listUser·p0.99:   9.454 ms/op
                 listUser·p0.999:  18.956 ms/op
                 listUser·p0.9999: 31.101 ms/op
                 listUser·p1.00:   31.523 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 204830
  mean =      4.689 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 746 
    [ 2.500,  5.000) = 159155 
    [ 5.000,  7.500) = 38849 
    [ 7.500, 10.000) = 4890 
    [10.000, 12.500) = 678 
    [12.500, 15.000) = 178 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.886 ms/op
     p(50.0000) =      4.448 ms/op
     p(90.0000) =      5.988 ms/op
     p(95.0000) =      6.881 ms/op
     p(99.0000) =      8.995 ms/op
     p(99.9000) =     18.454 ms/op
     p(99.9900) =     29.017 ms/op
     p(99.9990) =     31.195 ms/op
     p(99.9999) =     31.523 ms/op
    p(100.0000) =     31.523 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.446 ± 1.264  ops/ms
ClientGrpc.existUser                       thrpt       3   9.332 ± 1.229  ops/ms
ClientGrpc.getUser                         thrpt       3   8.607 ± 0.997  ops/ms
ClientGrpc.listUser                        thrpt       3   7.017 ± 0.924  ops/ms
ClientGrpc.createUser                       avgt       3   3.617 ± 1.856   ms/op
ClientGrpc.existUser                        avgt       3   3.412 ± 0.971   ms/op
ClientGrpc.getUser                          avgt       3   3.649 ± 0.727   ms/op
ClientGrpc.listUser                         avgt       3   4.749 ± 1.634   ms/op
ClientGrpc.createUser                     sample  263786   3.643 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.834           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.568           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.760           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.947           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.764           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.368           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.527           ms/op
ClientGrpc.existUser                      sample  278727   3.445 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.826           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.408           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.071           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.415           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.472           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.618           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.613           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.263           ms/op
ClientGrpc.getUser                        sample  262237   3.660 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.957           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.572           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.375           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.735           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.128           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.465           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.007           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.644           ms/op
ClientGrpc.listUser                       sample  204830   4.689 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.886           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.448           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.988           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.881           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.995           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.454           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.017           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.523           ms/op
