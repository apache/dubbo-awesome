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
# Warmup Iteration   1: 3.186 ops/ms
# Warmup Iteration   2: 6.647 ops/ms
# Warmup Iteration   3: 8.121 ops/ms
Iteration   1: 8.469 ops/ms
Iteration   2: 8.274 ops/ms
Iteration   3: 8.660 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.468 ±(99.9%) 3.520 ops/ms [Average]
  (min, avg, max) = (8.274, 8.468, 8.660), stdev = 0.193
  CI (99.9%): [4.948, 11.988] (assumes normal distribution)


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
# Warmup Iteration   1: 5.994 ops/ms
# Warmup Iteration   2: 8.548 ops/ms
# Warmup Iteration   3: 8.982 ops/ms
Iteration   1: 9.328 ops/ms
Iteration   2: 8.612 ops/ms
Iteration   3: 9.309 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.083 ±(99.9%) 7.444 ops/ms [Average]
  (min, avg, max) = (8.612, 9.083, 9.328), stdev = 0.408
  CI (99.9%): [1.639, 16.527] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.261 ops/ms
# Warmup Iteration   2: 8.042 ops/ms
# Warmup Iteration   3: 8.611 ops/ms
Iteration   1: 8.801 ops/ms
Iteration   2: 8.417 ops/ms
Iteration   3: 8.807 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.675 ±(99.9%) 4.077 ops/ms [Average]
  (min, avg, max) = (8.417, 8.675, 8.807), stdev = 0.223
  CI (99.9%): [4.598, 12.752] (assumes normal distribution)


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
# Warmup Iteration   1: 4.878 ops/ms
# Warmup Iteration   2: 6.196 ops/ms
# Warmup Iteration   3: 6.620 ops/ms
Iteration   1: 6.562 ops/ms
Iteration   2: 6.326 ops/ms
Iteration   3: 6.721 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.536 ±(99.9%) 3.623 ops/ms [Average]
  (min, avg, max) = (6.326, 6.536, 6.721), stdev = 0.199
  CI (99.9%): [2.913, 10.159] (assumes normal distribution)


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
# Warmup Iteration   1: 5.650 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.897 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.869 ±(99.9%) 0.015 ms/op
Iteration   1: 3.685 ±(99.9%) 0.003 ms/op
Iteration   2: 3.832 ±(99.9%) 0.004 ms/op
Iteration   3: 3.744 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.754 ±(99.9%) 1.356 ms/op [Average]
  (min, avg, max) = (3.685, 3.754, 3.832), stdev = 0.074
  CI (99.9%): [2.397, 5.110] (assumes normal distribution)


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
# Warmup Iteration   1: 4.931 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.778 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.504 ±(99.9%) 0.003 ms/op
Iteration   1: 3.587 ±(99.9%) 0.003 ms/op
Iteration   2: 3.846 ±(99.9%) 0.003 ms/op
Iteration   3: 3.599 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.678 ±(99.9%) 2.666 ms/op [Average]
  (min, avg, max) = (3.587, 3.678, 3.846), stdev = 0.146
  CI (99.9%): [1.011, 6.344] (assumes normal distribution)


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
# Warmup Iteration   1: 5.251 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.971 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.759 ±(99.9%) 0.004 ms/op
Iteration   1: 3.833 ±(99.9%) 0.033 ms/op
Iteration   2: 4.106 ±(99.9%) 0.004 ms/op
Iteration   3: 3.754 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.898 ±(99.9%) 3.365 ms/op [Average]
  (min, avg, max) = (3.754, 3.898, 4.106), stdev = 0.184
  CI (99.9%): [0.532, 7.263] (assumes normal distribution)


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
# Warmup Iteration   1: 6.786 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 5.152 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.846 ±(99.9%) 0.010 ms/op
Iteration   1: 4.843 ±(99.9%) 0.014 ms/op
Iteration   2: 5.014 ±(99.9%) 0.007 ms/op
Iteration   3: 5.012 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.956 ±(99.9%) 1.788 ms/op [Average]
  (min, avg, max) = (4.843, 4.956, 5.014), stdev = 0.098
  CI (99.9%): [3.168, 6.744] (assumes normal distribution)


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
# Warmup Iteration   1: 5.236 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.066 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.616 ±(99.9%) 0.009 ms/op
Iteration   1: 3.776 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.053 ms/op
                 createUser·p0.50:   3.658 ms/op
                 createUser·p0.90:   4.612 ms/op
                 createUser·p0.95:   5.014 ms/op
                 createUser·p0.99:   6.332 ms/op
                 createUser·p0.999:  9.419 ms/op
                 createUser·p0.9999: 13.673 ms/op
                 createUser·p1.00:   13.779 ms/op

Iteration   2: 3.737 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.870 ms/op
                 createUser·p0.50:   3.641 ms/op
                 createUser·p0.90:   4.489 ms/op
                 createUser·p0.95:   4.801 ms/op
                 createUser·p0.99:   6.020 ms/op
                 createUser·p0.999:  10.948 ms/op
                 createUser·p0.9999: 26.046 ms/op
                 createUser·p1.00:   26.444 ms/op

Iteration   3: 3.848 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.756 ms/op
                 createUser·p0.50:   3.719 ms/op
                 createUser·p0.90:   4.669 ms/op
                 createUser·p0.95:   5.153 ms/op
                 createUser·p0.99:   6.619 ms/op
                 createUser·p0.999:  10.595 ms/op
                 createUser·p0.9999: 29.524 ms/op
                 createUser·p1.00:   29.721 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 253763
  mean =      3.786 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5001 
    [ 2.500,  5.000) = 236355 
    [ 5.000,  7.500) = 11240 
    [ 7.500, 10.000) = 879 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.756 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      4.989 ms/op
     p(99.0000) =      6.349 ms/op
     p(99.9000) =     10.359 ms/op
     p(99.9900) =     29.086 ms/op
     p(99.9990) =     29.655 ms/op
     p(99.9999) =     29.721 ms/op
    p(100.0000) =     29.721 ms/op


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
# Warmup Iteration   1: 4.753 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.771 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.518 ±(99.9%) 0.007 ms/op
Iteration   1: 3.606 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.829 ms/op
                 existUser·p0.50:   3.531 ms/op
                 existUser·p0.90:   4.342 ms/op
                 existUser·p0.95:   4.743 ms/op
                 existUser·p0.99:   5.907 ms/op
                 existUser·p0.999:  10.594 ms/op
                 existUser·p0.9999: 16.501 ms/op
                 existUser·p1.00:   16.810 ms/op

Iteration   2: 3.615 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.912 ms/op
                 existUser·p0.50:   3.527 ms/op
                 existUser·p0.90:   4.358 ms/op
                 existUser·p0.95:   4.653 ms/op
                 existUser·p0.99:   5.865 ms/op
                 existUser·p0.999:  8.214 ms/op
                 existUser·p0.9999: 17.312 ms/op
                 existUser·p1.00:   17.564 ms/op

Iteration   3: 3.811 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.711 ms/op
                 existUser·p0.50:   3.670 ms/op
                 existUser·p0.90:   4.653 ms/op
                 existUser·p0.95:   5.153 ms/op
                 existUser·p0.99:   6.881 ms/op
                 existUser·p0.999:  11.241 ms/op
                 existUser·p0.9999: 23.233 ms/op
                 existUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 261075
  mean =      3.675 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6613 
    [ 2.500,  5.000) = 243870 
    [ 5.000,  7.500) = 9546 
    [ 7.500, 10.000) = 782 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.711 ms/op
     p(50.0000) =      3.572 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      6.218 ms/op
     p(99.9000) =     10.074 ms/op
     p(99.9900) =     22.302 ms/op
     p(99.9990) =     23.265 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


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
# Warmup Iteration   1: 5.423 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.003 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.938 ±(99.9%) 0.011 ms/op
Iteration   1: 3.754 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.734 ms/op
                 getUser·p0.50:   3.654 ms/op
                 getUser·p0.90:   4.481 ms/op
                 getUser·p0.95:   4.809 ms/op
                 getUser·p0.99:   6.210 ms/op
                 getUser·p0.999:  10.671 ms/op
                 getUser·p0.9999: 20.396 ms/op
                 getUser·p1.00:   21.004 ms/op

Iteration   2: 3.784 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.897 ms/op
                 getUser·p0.50:   3.719 ms/op
                 getUser·p0.90:   4.620 ms/op
                 getUser·p0.95:   4.973 ms/op
                 getUser·p0.99:   5.972 ms/op
                 getUser·p0.999:  8.552 ms/op
                 getUser·p0.9999: 26.349 ms/op
                 getUser·p1.00:   27.066 ms/op

Iteration   3: 3.861 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.795 ms/op
                 getUser·p0.50:   3.740 ms/op
                 getUser·p0.90:   4.760 ms/op
                 getUser·p0.95:   5.211 ms/op
                 getUser·p0.99:   6.734 ms/op
                 getUser·p0.999:  10.129 ms/op
                 getUser·p0.9999: 29.833 ms/op
                 getUser·p1.00:   30.343 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 252590
  mean =      3.799 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6581 
    [ 2.500,  5.000) = 233358 
    [ 5.000,  7.500) = 11516 
    [ 7.500, 10.000) = 922 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.734 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      5.005 ms/op
     p(99.0000) =      6.332 ms/op
     p(99.9000) =      9.716 ms/op
     p(99.9900) =     28.949 ms/op
     p(99.9990) =     30.343 ms/op
     p(99.9999) =     30.343 ms/op
    p(100.0000) =     30.343 ms/op


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
# Warmup Iteration   1: 6.912 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 5.303 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.962 ±(99.9%) 0.016 ms/op
Iteration   1: 4.950 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.700 ms/op
                 listUser·p0.50:   4.710 ms/op
                 listUser·p0.90:   6.332 ms/op
                 listUser·p0.95:   7.242 ms/op
                 listUser·p0.99:   8.962 ms/op
                 listUser·p0.999:  17.039 ms/op
                 listUser·p0.9999: 24.069 ms/op
                 listUser·p1.00:   24.281 ms/op

Iteration   2: 5.056 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.460 ms/op
                 listUser·p0.50:   4.801 ms/op
                 listUser·p0.90:   6.431 ms/op
                 listUser·p0.95:   7.324 ms/op
                 listUser·p0.99:   9.290 ms/op
                 listUser·p0.999:  18.963 ms/op
                 listUser·p0.9999: 26.554 ms/op
                 listUser·p1.00:   28.148 ms/op

Iteration   3: 4.895 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.079 ms/op
                 listUser·p0.50:   4.653 ms/op
                 listUser·p0.90:   6.250 ms/op
                 listUser·p0.95:   7.152 ms/op
                 listUser·p0.99:   9.126 ms/op
                 listUser·p0.999:  19.890 ms/op
                 listUser·p0.9999: 25.736 ms/op
                 listUser·p1.00:   26.313 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 193328
  mean =      4.966 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 315 
    [ 2.500,  5.000) = 125763 
    [ 5.000,  7.500) = 59534 
    [ 7.500, 10.000) = 6636 
    [10.000, 12.500) = 652 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      1.079 ms/op
     p(50.0000) =      4.719 ms/op
     p(90.0000) =      6.341 ms/op
     p(95.0000) =      7.238 ms/op
     p(99.0000) =      9.110 ms/op
     p(99.9000) =     18.896 ms/op
     p(99.9900) =     26.018 ms/op
     p(99.9990) =     28.087 ms/op
     p(99.9999) =     28.148 ms/op
    p(100.0000) =     28.148 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.468 ± 3.520  ops/ms
ClientGrpc.existUser                       thrpt       3   9.083 ± 7.444  ops/ms
ClientGrpc.getUser                         thrpt       3   8.675 ± 4.077  ops/ms
ClientGrpc.listUser                        thrpt       3   6.536 ± 3.623  ops/ms
ClientGrpc.createUser                       avgt       3   3.754 ± 1.356   ms/op
ClientGrpc.existUser                        avgt       3   3.678 ± 2.666   ms/op
ClientGrpc.getUser                          avgt       3   3.898 ± 3.365   ms/op
ClientGrpc.listUser                         avgt       3   4.956 ± 1.788   ms/op
ClientGrpc.createUser                     sample  253763   3.786 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.756           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.674           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.579           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.989           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.349           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.359           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.086           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.721           ms/op
ClientGrpc.existUser                      sample  261075   3.675 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.711           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.572           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.440           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.850           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.218           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.074           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.302           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.298           ms/op
ClientGrpc.getUser                        sample  252590   3.799 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.734           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.703           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.620           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.005           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.332           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.716           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.949           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.343           ms/op
ClientGrpc.listUser                       sample  193328   4.966 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.079           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.719           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.341           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.238           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.110           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.896           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.018           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.148           ms/op
