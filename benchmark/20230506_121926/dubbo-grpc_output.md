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
# Warmup Iteration   1: 2.982 ops/ms
# Warmup Iteration   2: 6.541 ops/ms
# Warmup Iteration   3: 7.948 ops/ms
Iteration   1: 8.329 ops/ms
Iteration   2: 8.350 ops/ms
Iteration   3: 8.473 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.384 ±(99.9%) 1.422 ops/ms [Average]
  (min, avg, max) = (8.329, 8.384, 8.473), stdev = 0.078
  CI (99.9%): [6.962, 9.806] (assumes normal distribution)


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
# Warmup Iteration   1: 5.670 ops/ms
# Warmup Iteration   2: 8.514 ops/ms
# Warmup Iteration   3: 8.661 ops/ms
Iteration   1: 8.780 ops/ms
Iteration   2: 9.037 ops/ms
Iteration   3: 9.187 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.002 ±(99.9%) 3.757 ops/ms [Average]
  (min, avg, max) = (8.780, 9.002, 9.187), stdev = 0.206
  CI (99.9%): [5.245, 12.759] (assumes normal distribution)


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
# Warmup Iteration   1: 5.098 ops/ms
# Warmup Iteration   2: 7.627 ops/ms
# Warmup Iteration   3: 8.500 ops/ms
Iteration   1: 8.283 ops/ms
Iteration   2: 8.765 ops/ms
Iteration   3: 8.566 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.538 ±(99.9%) 4.422 ops/ms [Average]
  (min, avg, max) = (8.283, 8.538, 8.765), stdev = 0.242
  CI (99.9%): [4.116, 12.961] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.042 ops/ms
# Warmup Iteration   2: 6.380 ops/ms
# Warmup Iteration   3: 6.518 ops/ms
Iteration   1: 6.652 ops/ms
Iteration   2: 6.589 ops/ms
Iteration   3: 6.564 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.602 ±(99.9%) 0.823 ops/ms [Average]
  (min, avg, max) = (6.564, 6.602, 6.652), stdev = 0.045
  CI (99.9%): [5.778, 7.425] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.580 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.892 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.820 ±(99.9%) 0.015 ms/op
Iteration   1: 3.796 ±(99.9%) 0.003 ms/op
Iteration   2: 3.748 ±(99.9%) 0.002 ms/op
Iteration   3: 3.705 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.750 ±(99.9%) 0.837 ms/op [Average]
  (min, avg, max) = (3.705, 3.750, 3.796), stdev = 0.046
  CI (99.9%): [2.912, 4.587] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.270 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.676 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.632 ±(99.9%) 0.002 ms/op
Iteration   1: 3.547 ±(99.9%) 0.002 ms/op
Iteration   2: 3.514 ±(99.9%) 0.003 ms/op
Iteration   3: 3.595 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.552 ±(99.9%) 0.740 ms/op [Average]
  (min, avg, max) = (3.514, 3.552, 3.595), stdev = 0.041
  CI (99.9%): [2.812, 4.292] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.366 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.969 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.726 ±(99.9%) 0.005 ms/op
Iteration   1: 3.745 ±(99.9%) 0.003 ms/op
Iteration   2: 3.706 ±(99.9%) 0.003 ms/op
Iteration   3: 3.736 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.729 ±(99.9%) 0.367 ms/op [Average]
  (min, avg, max) = (3.706, 3.729, 3.745), stdev = 0.020
  CI (99.9%): [3.362, 4.096] (assumes normal distribution)


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
# Warmup Iteration   1: 7.446 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.998 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.888 ±(99.9%) 0.008 ms/op
Iteration   1: 4.672 ±(99.9%) 0.013 ms/op
Iteration   2: 4.887 ±(99.9%) 0.013 ms/op
Iteration   3: 4.940 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.833 ±(99.9%) 2.593 ms/op [Average]
  (min, avg, max) = (4.672, 4.833, 4.940), stdev = 0.142
  CI (99.9%): [2.240, 7.426] (assumes normal distribution)


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
# Warmup Iteration   1: 5.931 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 3.991 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.939 ±(99.9%) 0.011 ms/op
Iteration   1: 3.701 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.793 ms/op
                 createUser·p0.50:   3.641 ms/op
                 createUser·p0.90:   4.522 ms/op
                 createUser·p0.95:   4.956 ms/op
                 createUser·p0.99:   6.627 ms/op
                 createUser·p0.999:  10.273 ms/op
                 createUser·p0.9999: 15.991 ms/op
                 createUser·p1.00:   16.450 ms/op

Iteration   2: 3.630 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.973 ms/op
                 createUser·p0.50:   3.564 ms/op
                 createUser·p0.90:   4.268 ms/op
                 createUser·p0.95:   4.669 ms/op
                 createUser·p0.99:   6.103 ms/op
                 createUser·p0.999:  10.578 ms/op
                 createUser·p0.9999: 26.811 ms/op
                 createUser·p1.00:   27.099 ms/op

Iteration   3: 3.816 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.057 ms/op
                 createUser·p0.50:   3.690 ms/op
                 createUser·p0.90:   4.637 ms/op
                 createUser·p0.95:   5.022 ms/op
                 createUser·p0.99:   6.996 ms/op
                 createUser·p0.999:  13.240 ms/op
                 createUser·p0.9999: 31.989 ms/op
                 createUser·p1.00:   32.473 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 258475
  mean =      3.714 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9622 
    [ 2.500,  5.000) = 237916 
    [ 5.000,  7.500) = 9454 
    [ 7.500, 10.000) = 1100 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.793 ms/op
     p(50.0000) =      3.629 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.899 ms/op
     p(99.0000) =      6.521 ms/op
     p(99.9000) =     12.118 ms/op
     p(99.9900) =     30.910 ms/op
     p(99.9990) =     32.336 ms/op
     p(99.9999) =     32.473 ms/op
    p(100.0000) =     32.473 ms/op


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
# Warmup Iteration   1: 4.846 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.701 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.672 ±(99.9%) 0.009 ms/op
Iteration   1: 3.645 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.784 ms/op
                 existUser·p0.50:   3.535 ms/op
                 existUser·p0.90:   4.563 ms/op
                 existUser·p0.95:   5.014 ms/op
                 existUser·p0.99:   7.119 ms/op
                 existUser·p0.999:  11.979 ms/op
                 existUser·p0.9999: 15.671 ms/op
                 existUser·p1.00:   18.448 ms/op

Iteration   2: 3.565 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.989 ms/op
                 existUser·p0.50:   3.498 ms/op
                 existUser·p0.90:   4.133 ms/op
                 existUser·p0.95:   4.522 ms/op
                 existUser·p0.99:   5.939 ms/op
                 existUser·p0.999:  8.737 ms/op
                 existUser·p0.9999: 19.563 ms/op
                 existUser·p1.00:   19.923 ms/op

Iteration   3: 3.576 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.829 ms/op
                 existUser·p0.50:   3.498 ms/op
                 existUser·p0.90:   4.235 ms/op
                 existUser·p0.95:   4.678 ms/op
                 existUser·p0.99:   6.136 ms/op
                 existUser·p0.999:  11.207 ms/op
                 existUser·p0.9999: 19.695 ms/op
                 existUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 266997
  mean =      3.595 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10040 
    [ 2.500,  5.000) = 247153 
    [ 5.000,  7.500) = 8478 
    [ 7.500, 10.000) = 969 
    [10.000, 12.500) = 198 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.784 ms/op
     p(50.0000) =      3.510 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      6.431 ms/op
     p(99.9000) =     11.076 ms/op
     p(99.9900) =     19.464 ms/op
     p(99.9990) =     20.152 ms/op
     p(99.9999) =     20.218 ms/op
    p(100.0000) =     20.218 ms/op


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
# Warmup Iteration   1: 5.164 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.100 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.860 ±(99.9%) 0.010 ms/op
Iteration   1: 3.879 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.032 ms/op
                 getUser·p0.50:   3.781 ms/op
                 getUser·p0.90:   4.751 ms/op
                 getUser·p0.95:   5.243 ms/op
                 getUser·p0.99:   7.105 ms/op
                 getUser·p0.999:  14.523 ms/op
                 getUser·p0.9999: 27.689 ms/op
                 getUser·p1.00:   27.820 ms/op

Iteration   2: 3.859 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.043 ms/op
                 getUser·p0.50:   3.781 ms/op
                 getUser·p0.90:   4.743 ms/op
                 getUser·p0.95:   5.218 ms/op
                 getUser·p0.99:   6.750 ms/op
                 getUser·p0.999:  11.931 ms/op
                 getUser·p0.9999: 23.375 ms/op
                 getUser·p1.00:   24.412 ms/op

Iteration   3: 3.872 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.408 ms/op
                 getUser·p0.50:   3.748 ms/op
                 getUser·p0.90:   4.571 ms/op
                 getUser·p0.95:   5.046 ms/op
                 getUser·p0.99:   6.971 ms/op
                 getUser·p0.999:  11.469 ms/op
                 getUser·p0.9999: 22.921 ms/op
                 getUser·p1.00:   23.396 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 248087
  mean =      3.870 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7795 
    [ 2.500,  5.000) = 224453 
    [ 5.000,  7.500) = 14070 
    [ 7.500, 10.000) = 1330 
    [10.000, 12.500) = 208 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.408 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.694 ms/op
     p(95.0000) =      5.177 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     11.777 ms/op
     p(99.9900) =     23.317 ms/op
     p(99.9990) =     27.787 ms/op
     p(99.9999) =     27.820 ms/op
    p(100.0000) =     27.820 ms/op


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
# Warmup Iteration   1: 6.763 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 5.443 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.990 ±(99.9%) 0.018 ms/op
Iteration   1: 4.893 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.505 ms/op
                 listUser·p0.50:   4.661 ms/op
                 listUser·p0.90:   6.210 ms/op
                 listUser·p0.95:   7.102 ms/op
                 listUser·p0.99:   9.241 ms/op
                 listUser·p0.999:  15.681 ms/op
                 listUser·p0.9999: 18.463 ms/op
                 listUser·p1.00:   18.645 ms/op

Iteration   2: 4.923 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.036 ms/op
                 listUser·p0.50:   4.678 ms/op
                 listUser·p0.90:   6.259 ms/op
                 listUser·p0.95:   7.012 ms/op
                 listUser·p0.99:   8.880 ms/op
                 listUser·p0.999:  16.744 ms/op
                 listUser·p0.9999: 20.677 ms/op
                 listUser·p1.00:   22.446 ms/op

Iteration   3: 4.915 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.282 ms/op
                 listUser·p0.50:   4.669 ms/op
                 listUser·p0.90:   6.382 ms/op
                 listUser·p0.95:   7.168 ms/op
                 listUser·p0.99:   9.019 ms/op
                 listUser·p0.999:  19.300 ms/op
                 listUser·p0.9999: 25.018 ms/op
                 listUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 195574
  mean =      4.911 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 294 
    [ 2.500,  5.000) = 133031 
    [ 5.000,  7.500) = 55277 
    [ 7.500, 10.000) = 5831 
    [10.000, 12.500) = 680 
    [12.500, 15.000) = 148 
    [15.000, 17.500) = 146 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.036 ms/op
     p(50.0000) =      4.669 ms/op
     p(90.0000) =      6.291 ms/op
     p(95.0000) =      7.094 ms/op
     p(99.0000) =      9.028 ms/op
     p(99.9000) =     16.735 ms/op
     p(99.9900) =     23.134 ms/op
     p(99.9990) =     26.418 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.384 ± 1.422  ops/ms
ClientGrpc.existUser                       thrpt       3   9.002 ± 3.757  ops/ms
ClientGrpc.getUser                         thrpt       3   8.538 ± 4.422  ops/ms
ClientGrpc.listUser                        thrpt       3   6.602 ± 0.823  ops/ms
ClientGrpc.createUser                       avgt       3   3.750 ± 0.837   ms/op
ClientGrpc.existUser                        avgt       3   3.552 ± 0.740   ms/op
ClientGrpc.getUser                          avgt       3   3.729 ± 0.367   ms/op
ClientGrpc.listUser                         avgt       3   4.833 ± 2.593   ms/op
ClientGrpc.createUser                     sample  258475   3.714 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.793           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.629           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.489           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.899           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.521           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.118           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          30.910           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.473           ms/op
ClientGrpc.existUser                      sample  266997   3.595 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.784           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.510           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.301           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.776           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.431           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.076           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.464           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.218           ms/op
ClientGrpc.getUser                        sample  248087   3.870 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.408           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.768           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.694           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.177           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.914           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.777           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.317           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.820           ms/op
ClientGrpc.listUser                       sample  195574   4.911 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.036           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.669           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.291           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.094           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.028           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.735           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.134           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.575           ms/op
