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
# Warmup Iteration   1: 4.492 ops/ms
# Warmup Iteration   2: 9.586 ops/ms
# Warmup Iteration   3: 10.472 ops/ms
Iteration   1: 10.552 ops/ms
Iteration   2: 10.585 ops/ms
Iteration   3: 10.565 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.568 ±(99.9%) 0.303 ops/ms [Average]
  (min, avg, max) = (10.552, 10.568, 10.585), stdev = 0.017
  CI (99.9%): [10.265, 10.870] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.987 ops/ms
# Warmup Iteration   2: 10.751 ops/ms
# Warmup Iteration   3: 11.125 ops/ms
Iteration   1: 11.096 ops/ms
Iteration   2: 11.108 ops/ms
Iteration   3: 11.237 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.147 ±(99.9%) 1.422 ops/ms [Average]
  (min, avg, max) = (11.096, 11.147, 11.237), stdev = 0.078
  CI (99.9%): [9.725, 12.569] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.272 ops/ms
# Warmup Iteration   2: 10.159 ops/ms
# Warmup Iteration   3: 10.652 ops/ms
Iteration   1: 10.615 ops/ms
Iteration   2: 10.827 ops/ms
Iteration   3: 10.825 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.756 ±(99.9%) 2.221 ops/ms [Average]
  (min, avg, max) = (10.615, 10.756, 10.827), stdev = 0.122
  CI (99.9%): [8.535, 12.977] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.838 ops/ms
# Warmup Iteration   2: 8.118 ops/ms
# Warmup Iteration   3: 8.404 ops/ms
Iteration   1: 8.393 ops/ms
Iteration   2: 8.439 ops/ms
Iteration   3: 8.354 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.395 ±(99.9%) 0.773 ops/ms [Average]
  (min, avg, max) = (8.354, 8.395, 8.439), stdev = 0.042
  CI (99.9%): [7.622, 9.169] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.971 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.057 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.003 ms/op
Iteration   1: 3.013 ±(99.9%) 0.002 ms/op
Iteration   2: 3.027 ±(99.9%) 0.002 ms/op
Iteration   3: 2.951 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.997 ±(99.9%) 0.733 ms/op [Average]
  (min, avg, max) = (2.951, 2.997, 3.027), stdev = 0.040
  CI (99.9%): [2.264, 3.730] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.863 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 2.910 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.855 ±(99.9%) 0.002 ms/op
Iteration   1: 2.797 ±(99.9%) 0.003 ms/op
Iteration   2: 2.834 ±(99.9%) 0.003 ms/op
Iteration   3: 2.826 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.819 ±(99.9%) 0.357 ms/op [Average]
  (min, avg, max) = (2.797, 2.819, 2.834), stdev = 0.020
  CI (99.9%): [2.462, 3.176] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.776 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.061 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.022 ±(99.9%) 0.003 ms/op
Iteration   1: 2.999 ±(99.9%) 0.001 ms/op
Iteration   2: 2.961 ±(99.9%) 0.003 ms/op
Iteration   3: 2.955 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.972 ±(99.9%) 0.443 ms/op [Average]
  (min, avg, max) = (2.955, 2.972, 2.999), stdev = 0.024
  CI (99.9%): [2.529, 3.414] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.113 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.959 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.825 ±(99.9%) 0.030 ms/op
Iteration   1: 3.834 ±(99.9%) 0.017 ms/op
Iteration   2: 3.756 ±(99.9%) 0.016 ms/op
Iteration   3: 3.706 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.765 ±(99.9%) 1.173 ms/op [Average]
  (min, avg, max) = (3.706, 3.765, 3.834), stdev = 0.064
  CI (99.9%): [2.592, 4.939] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.458 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.195 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.986 ±(99.9%) 0.007 ms/op
Iteration   1: 3.007 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.766 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   4.588 ms/op
                 createUser·p0.999:  7.804 ms/op
                 createUser·p0.9999: 15.073 ms/op
                 createUser·p1.00:   15.286 ms/op

Iteration   2: 3.029 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.631 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.883 ms/op
                 createUser·p0.99:   4.604 ms/op
                 createUser·p0.999:  9.380 ms/op
                 createUser·p0.9999: 23.345 ms/op
                 createUser·p1.00:   23.691 ms/op

Iteration   3: 3.041 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.613 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.699 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  7.674 ms/op
                 createUser·p0.9999: 23.674 ms/op
                 createUser·p1.00:   24.052 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317346
  mean =      3.026 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26731 
    [ 2.500,  5.000) = 289415 
    [ 5.000,  7.500) = 818 
    [ 7.500, 10.000) = 126 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.613 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      8.375 ms/op
     p(99.9900) =     23.283 ms/op
     p(99.9990) =     23.963 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.522 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.927 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.873 ±(99.9%) 0.006 ms/op
Iteration   1: 2.895 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.507 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   4.080 ms/op
                 existUser·p0.999:  7.329 ms/op
                 existUser·p0.9999: 12.204 ms/op
                 existUser·p1.00:   12.403 ms/op

Iteration   2: 2.877 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.657 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  5.758 ms/op
                 existUser·p0.9999: 12.106 ms/op
                 existUser·p1.00:   13.402 ms/op

Iteration   3: 2.808 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.638 ms/op
                 existUser·p0.50:   2.830 ms/op
                 existUser·p0.90:   3.199 ms/op
                 existUser·p0.95:   3.375 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  6.185 ms/op
                 existUser·p0.9999: 14.231 ms/op
                 existUser·p1.00:   14.565 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 335721
  mean =      2.860 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2456 
    [ 1.250,  2.500) = 43513 
    [ 2.500,  3.750) = 281786 
    [ 3.750,  5.000) = 7178 
    [ 5.000,  6.250) = 460 
    [ 6.250,  7.500) = 94 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 90 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.507 ms/op
     p(50.0000) =      2.855 ms/op
     p(90.0000) =      3.318 ms/op
     p(95.0000) =      3.535 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      6.218 ms/op
     p(99.9900) =     13.999 ms/op
     p(99.9990) =     14.385 ms/op
     p(99.9999) =     14.565 ms/op
    p(100.0000) =     14.565 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.058 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.103 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.009 ±(99.9%) 0.006 ms/op
Iteration   1: 2.986 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.510 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.569 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   4.367 ms/op
                 getUser·p0.999:  6.390 ms/op
                 getUser·p0.9999: 21.365 ms/op
                 getUser·p1.00:   21.561 ms/op

Iteration   2: 2.966 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.690 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.387 ms/op
                 getUser·p0.95:   3.596 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  6.806 ms/op
                 getUser·p0.9999: 25.625 ms/op
                 getUser·p1.00:   26.051 ms/op

Iteration   3: 2.974 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.596 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  7.061 ms/op
                 getUser·p0.9999: 21.209 ms/op
                 getUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 322797
  mean =      2.975 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30755 
    [ 2.500,  5.000) = 291007 
    [ 5.000,  7.500) = 808 
    [ 7.500, 10.000) = 35 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.510 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      6.735 ms/op
     p(99.9900) =     21.585 ms/op
     p(99.9990) =     26.018 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


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
# Warmup Iteration   1: 5.029 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.981 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.897 ±(99.9%) 0.010 ms/op
Iteration   1: 3.830 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.990 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   6.570 ms/op
                 listUser·p0.999:  11.810 ms/op
                 listUser·p0.9999: 15.237 ms/op
                 listUser·p1.00:   15.532 ms/op

Iteration   2: 3.826 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.739 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.170 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   6.275 ms/op
                 listUser·p0.999:  13.227 ms/op
                 listUser·p0.9999: 23.188 ms/op
                 listUser·p1.00:   25.330 ms/op

Iteration   3: 3.777 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.779 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   5.407 ms/op
                 listUser·p0.99:   6.431 ms/op
                 listUser·p0.999:  15.155 ms/op
                 listUser·p0.9999: 18.433 ms/op
                 listUser·p1.00:   19.104 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 251944
  mean =      3.811 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5136 
    [ 2.500,  5.000) = 230627 
    [ 5.000,  7.500) = 15320 
    [ 7.500, 10.000) = 483 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 145 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.779 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      5.374 ms/op
     p(99.0000) =      6.455 ms/op
     p(99.9000) =     13.615 ms/op
     p(99.9900) =     21.601 ms/op
     p(99.9990) =     23.756 ms/op
     p(99.9999) =     25.330 ms/op
    p(100.0000) =     25.330 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.568 ± 0.303  ops/ms
ClientGrpc.existUser                       thrpt       3  11.147 ± 1.422  ops/ms
ClientGrpc.getUser                         thrpt       3  10.756 ± 2.221  ops/ms
ClientGrpc.listUser                        thrpt       3   8.395 ± 0.773  ops/ms
ClientGrpc.createUser                       avgt       3   2.997 ± 0.733   ms/op
ClientGrpc.existUser                        avgt       3   2.819 ± 0.357   ms/op
ClientGrpc.getUser                          avgt       3   2.972 ± 0.443   ms/op
ClientGrpc.listUser                         avgt       3   3.765 ± 1.173   ms/op
ClientGrpc.createUser                     sample  317346   3.026 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.613           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.998           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.584           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.805           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.530           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.375           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.283           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.052           ms/op
ClientGrpc.existUser                      sample  335721   2.860 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.507           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.855           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.318           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.535           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.218           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.999           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          14.565           ms/op
ClientGrpc.getUser                        sample  322797   2.975 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.510           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.961           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.486           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.707           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.342           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.735           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.585           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.051           ms/op
ClientGrpc.listUser                       sample  251944   3.811 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.779           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.699           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.424           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.374           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.455           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.615           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.601           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.330           ms/op
