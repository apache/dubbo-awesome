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
# Warmup Iteration   1: 2.699 ops/ms
# Warmup Iteration   2: 6.213 ops/ms
# Warmup Iteration   3: 7.770 ops/ms
Iteration   1: 8.207 ops/ms
Iteration   2: 8.169 ops/ms
Iteration   3: 8.334 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.237 ±(99.9%) 1.575 ops/ms [Average]
  (min, avg, max) = (8.169, 8.237, 8.334), stdev = 0.086
  CI (99.9%): [6.662, 9.811] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.587 ops/ms
# Warmup Iteration   2: 8.050 ops/ms
# Warmup Iteration   3: 8.572 ops/ms
Iteration   1: 8.787 ops/ms
Iteration   2: 8.712 ops/ms
Iteration   3: 8.637 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.712 ±(99.9%) 1.369 ops/ms [Average]
  (min, avg, max) = (8.637, 8.712, 8.787), stdev = 0.075
  CI (99.9%): [7.343, 10.080] (assumes normal distribution)


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
# Warmup Iteration   1: 5.186 ops/ms
# Warmup Iteration   2: 7.887 ops/ms
# Warmup Iteration   3: 8.287 ops/ms
Iteration   1: 8.394 ops/ms
Iteration   2: 8.086 ops/ms
Iteration   3: 8.235 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.238 ±(99.9%) 2.818 ops/ms [Average]
  (min, avg, max) = (8.086, 8.238, 8.394), stdev = 0.154
  CI (99.9%): [5.420, 11.057] (assumes normal distribution)


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
# Warmup Iteration   1: 3.601 ops/ms
# Warmup Iteration   2: 5.924 ops/ms
# Warmup Iteration   3: 6.309 ops/ms
Iteration   1: 6.399 ops/ms
Iteration   2: 6.274 ops/ms
Iteration   3: 6.482 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.385 ±(99.9%) 1.910 ops/ms [Average]
  (min, avg, max) = (6.274, 6.385, 6.482), stdev = 0.105
  CI (99.9%): [4.475, 8.296] (assumes normal distribution)


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
# Warmup Iteration   1: 6.247 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.221 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.180 ±(99.9%) 0.021 ms/op
Iteration   1: 4.153 ±(99.9%) 0.004 ms/op
Iteration   2: 4.015 ±(99.9%) 0.003 ms/op
Iteration   3: 3.805 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.991 ±(99.9%) 3.194 ms/op [Average]
  (min, avg, max) = (3.805, 3.991, 4.153), stdev = 0.175
  CI (99.9%): [0.797, 7.185] (assumes normal distribution)


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
# Warmup Iteration   1: 5.262 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.996 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.938 ±(99.9%) 0.004 ms/op
Iteration   1: 3.532 ±(99.9%) 0.003 ms/op
Iteration   2: 3.574 ±(99.9%) 0.003 ms/op
Iteration   3: 3.659 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.589 ±(99.9%) 1.185 ms/op [Average]
  (min, avg, max) = (3.532, 3.589, 3.659), stdev = 0.065
  CI (99.9%): [2.403, 4.774] (assumes normal distribution)


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
# Warmup Iteration   1: 5.800 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.226 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.051 ±(99.9%) 0.004 ms/op
Iteration   1: 3.816 ±(99.9%) 0.005 ms/op
Iteration   2: 3.768 ±(99.9%) 0.004 ms/op
Iteration   3: 3.833 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.806 ±(99.9%) 0.617 ms/op [Average]
  (min, avg, max) = (3.768, 3.806, 3.833), stdev = 0.034
  CI (99.9%): [3.189, 4.423] (assumes normal distribution)


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
# Warmup Iteration   1: 7.808 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 5.437 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.001 ±(99.9%) 0.009 ms/op
Iteration   1: 5.109 ±(99.9%) 0.016 ms/op
Iteration   2: 4.880 ±(99.9%) 0.028 ms/op
Iteration   3: 4.904 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.964 ±(99.9%) 2.303 ms/op [Average]
  (min, avg, max) = (4.880, 4.964, 5.109), stdev = 0.126
  CI (99.9%): [2.661, 7.267] (assumes normal distribution)


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
# Warmup Iteration   1: 5.810 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.307 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.911 ±(99.9%) 0.011 ms/op
Iteration   1: 3.785 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.906 ms/op
                 createUser·p0.50:   3.731 ms/op
                 createUser·p0.90:   4.465 ms/op
                 createUser·p0.95:   4.833 ms/op
                 createUser·p0.99:   5.759 ms/op
                 createUser·p0.999:  9.176 ms/op
                 createUser·p0.9999: 18.892 ms/op
                 createUser·p1.00:   19.825 ms/op

Iteration   2: 3.768 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.790 ms/op
                 createUser·p0.50:   3.711 ms/op
                 createUser·p0.90:   4.432 ms/op
                 createUser·p0.95:   4.751 ms/op
                 createUser·p0.99:   5.849 ms/op
                 createUser·p0.999:  15.417 ms/op
                 createUser·p0.9999: 20.907 ms/op
                 createUser·p1.00:   21.201 ms/op

Iteration   3: 3.900 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.182 ms/op
                 createUser·p0.50:   3.805 ms/op
                 createUser·p0.90:   4.686 ms/op
                 createUser·p0.95:   5.014 ms/op
                 createUser·p0.99:   6.308 ms/op
                 createUser·p0.999:  12.747 ms/op
                 createUser·p0.9999: 27.085 ms/op
                 createUser·p1.00:   27.558 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 251564
  mean =      3.817 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5700 
    [ 2.500,  5.000) = 236028 
    [ 5.000,  7.500) = 8918 
    [ 7.500, 10.000) = 594 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.790 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      5.972 ms/op
     p(99.9000) =     12.468 ms/op
     p(99.9900) =     23.976 ms/op
     p(99.9990) =     27.459 ms/op
     p(99.9999) =     27.558 ms/op
    p(100.0000) =     27.558 ms/op


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
# Warmup Iteration   1: 4.998 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.756 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.660 ±(99.9%) 0.009 ms/op
Iteration   1: 3.602 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.899 ms/op
                 existUser·p0.50:   3.531 ms/op
                 existUser·p0.90:   4.129 ms/op
                 existUser·p0.95:   4.497 ms/op
                 existUser·p0.99:   5.906 ms/op
                 existUser·p0.999:  8.847 ms/op
                 existUser·p0.9999: 14.586 ms/op
                 existUser·p1.00:   14.729 ms/op

Iteration   2: 3.545 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.108 ms/op
                 existUser·p0.50:   3.510 ms/op
                 existUser·p0.90:   3.936 ms/op
                 existUser·p0.95:   4.194 ms/op
                 existUser·p0.99:   5.439 ms/op
                 existUser·p0.999:  9.695 ms/op
                 existUser·p0.9999: 17.956 ms/op
                 existUser·p1.00:   18.612 ms/op

Iteration   3: 3.644 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.962 ms/op
                 existUser·p0.50:   3.564 ms/op
                 existUser·p0.90:   4.235 ms/op
                 existUser·p0.95:   4.628 ms/op
                 existUser·p0.99:   6.026 ms/op
                 existUser·p0.999:  12.047 ms/op
                 existUser·p0.9999: 19.472 ms/op
                 existUser·p1.00:   20.677 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 266785
  mean =      3.597 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4012 
    [ 2.500,  5.000) = 256842 
    [ 5.000,  7.500) = 5058 
    [ 7.500, 10.000) = 576 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.899 ms/op
     p(50.0000) =      3.531 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     10.260 ms/op
     p(99.9900) =     18.383 ms/op
     p(99.9990) =     20.524 ms/op
     p(99.9999) =     20.677 ms/op
    p(100.0000) =     20.677 ms/op


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
# Warmup Iteration   1: 5.678 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.115 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.925 ±(99.9%) 0.009 ms/op
Iteration   1: 3.875 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.927 ms/op
                 getUser·p0.50:   3.789 ms/op
                 getUser·p0.90:   4.604 ms/op
                 getUser·p0.95:   4.956 ms/op
                 getUser·p0.99:   6.160 ms/op
                 getUser·p0.999:  12.418 ms/op
                 getUser·p0.9999: 15.757 ms/op
                 getUser·p1.00:   16.122 ms/op

Iteration   2: 3.812 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.071 ms/op
                 getUser·p0.50:   3.731 ms/op
                 getUser·p0.90:   4.497 ms/op
                 getUser·p0.95:   4.858 ms/op
                 getUser·p0.99:   6.259 ms/op
                 getUser·p0.999:  12.764 ms/op
                 getUser·p0.9999: 17.629 ms/op
                 getUser·p1.00:   18.088 ms/op

Iteration   3: 3.834 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.047 ms/op
                 getUser·p0.50:   3.768 ms/op
                 getUser·p0.90:   4.612 ms/op
                 getUser·p0.95:   4.989 ms/op
                 getUser·p0.99:   6.308 ms/op
                 getUser·p0.999:  9.748 ms/op
                 getUser·p0.9999: 28.377 ms/op
                 getUser·p1.00:   30.540 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 249848
  mean =      3.840 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5200 
    [ 2.500,  5.000) = 233512 
    [ 5.000,  7.500) = 10199 
    [ 7.500, 10.000) = 648 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.927 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      4.940 ms/op
     p(99.0000) =      6.242 ms/op
     p(99.9000) =     10.360 ms/op
     p(99.9900) =     27.853 ms/op
     p(99.9990) =     29.494 ms/op
     p(99.9999) =     30.540 ms/op
    p(100.0000) =     30.540 ms/op


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
# Warmup Iteration   1: 7.463 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 5.231 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.895 ±(99.9%) 0.014 ms/op
Iteration   1: 4.883 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.612 ms/op
                 listUser·p0.50:   4.678 ms/op
                 listUser·p0.90:   6.087 ms/op
                 listUser·p0.95:   6.971 ms/op
                 listUser·p0.99:   8.815 ms/op
                 listUser·p0.999:  15.172 ms/op
                 listUser·p0.9999: 19.101 ms/op
                 listUser·p1.00:   19.726 ms/op

Iteration   2: 4.930 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.530 ms/op
                 listUser·p0.50:   4.686 ms/op
                 listUser·p0.90:   6.267 ms/op
                 listUser·p0.95:   7.135 ms/op
                 listUser·p0.99:   9.110 ms/op
                 listUser·p0.999:  18.065 ms/op
                 listUser·p0.9999: 21.103 ms/op
                 listUser·p1.00:   21.398 ms/op

Iteration   3: 4.852 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.364 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   6.185 ms/op
                 listUser·p0.95:   6.955 ms/op
                 listUser·p0.99:   8.978 ms/op
                 listUser·p0.999:  21.138 ms/op
                 listUser·p0.9999: 34.460 ms/op
                 listUser·p1.00:   35.062 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 196323
  mean =      4.888 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 194 
    [ 2.500,  5.000) = 136458 
    [ 5.000,  7.500) = 52984 
    [ 7.500, 10.000) = 5804 
    [10.000, 12.500) = 471 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 123 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.364 ms/op
     p(50.0000) =      4.661 ms/op
     p(90.0000) =      6.185 ms/op
     p(95.0000) =      7.021 ms/op
     p(99.0000) =      8.962 ms/op
     p(99.9000) =     17.924 ms/op
     p(99.9900) =     33.734 ms/op
     p(99.9990) =     34.936 ms/op
     p(99.9999) =     35.062 ms/op
    p(100.0000) =     35.062 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.237 ± 1.575  ops/ms
ClientGrpc.existUser                       thrpt       3   8.712 ± 1.369  ops/ms
ClientGrpc.getUser                         thrpt       3   8.238 ± 2.818  ops/ms
ClientGrpc.listUser                        thrpt       3   6.385 ± 1.910  ops/ms
ClientGrpc.createUser                       avgt       3   3.991 ± 3.194   ms/op
ClientGrpc.existUser                        avgt       3   3.589 ± 1.185   ms/op
ClientGrpc.getUser                          avgt       3   3.806 ± 0.617   ms/op
ClientGrpc.listUser                         avgt       3   4.964 ± 2.303   ms/op
ClientGrpc.createUser                     sample  251564   3.817 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.790           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.748           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.538           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.882           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.972           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.468           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.976           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.558           ms/op
ClientGrpc.existUser                      sample  266785   3.597 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.899           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.531           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.100           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.465           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.792           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.260           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.383           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.677           ms/op
ClientGrpc.getUser                        sample  249848   3.840 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.927           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.760           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.579           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.940           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.242           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.360           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.853           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.540           ms/op
ClientGrpc.listUser                       sample  196323   4.888 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.364           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.661           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.185           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.021           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.962           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.924           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          33.734           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          35.062           ms/op
