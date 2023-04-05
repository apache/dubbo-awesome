# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.686 ops/ms
# Warmup Iteration   2: 9.797 ops/ms
# Warmup Iteration   3: 10.482 ops/ms
Iteration   1: 10.966 ops/ms
Iteration   2: 10.837 ops/ms
Iteration   3: 10.964 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.922 ±(99.9%) 1.349 ops/ms [Average]
  (min, avg, max) = (10.837, 10.922, 10.966), stdev = 0.074
  CI (99.9%): [9.573, 12.272] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.096 ops/ms
# Warmup Iteration   2: 11.039 ops/ms
# Warmup Iteration   3: 11.482 ops/ms
Iteration   1: 11.296 ops/ms
Iteration   2: 11.342 ops/ms
Iteration   3: 11.131 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.256 ±(99.9%) 2.026 ops/ms [Average]
  (min, avg, max) = (11.131, 11.256, 11.342), stdev = 0.111
  CI (99.9%): [9.231, 13.282] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.412 ops/ms
# Warmup Iteration   2: 10.358 ops/ms
# Warmup Iteration   3: 10.935 ops/ms
Iteration   1: 10.969 ops/ms
Iteration   2: 11.008 ops/ms
Iteration   3: 11.021 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.999 ±(99.9%) 0.491 ops/ms [Average]
  (min, avg, max) = (10.969, 10.999, 11.021), stdev = 0.027
  CI (99.9%): [10.508, 11.490] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.024 ops/ms
# Warmup Iteration   2: 8.057 ops/ms
# Warmup Iteration   3: 8.570 ops/ms
Iteration   1: 8.518 ops/ms
Iteration   2: 8.424 ops/ms
Iteration   3: 8.568 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.503 ±(99.9%) 1.333 ops/ms [Average]
  (min, avg, max) = (8.424, 8.503, 8.568), stdev = 0.073
  CI (99.9%): [7.170, 9.836] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.783 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.014 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.929 ±(99.9%) 0.003 ms/op
Iteration   1: 2.974 ±(99.9%) 0.003 ms/op
Iteration   2: 2.878 ±(99.9%) 0.003 ms/op
Iteration   3: 2.935 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.929 ±(99.9%) 0.886 ms/op [Average]
  (min, avg, max) = (2.878, 2.929, 2.974), stdev = 0.049
  CI (99.9%): [2.043, 3.815] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.835 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.879 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.805 ±(99.9%) 0.004 ms/op
Iteration   1: 2.840 ±(99.9%) 0.002 ms/op
Iteration   2: 2.800 ±(99.9%) 0.003 ms/op
Iteration   3: 2.836 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.826 ±(99.9%) 0.405 ms/op [Average]
  (min, avg, max) = (2.800, 2.826, 2.840), stdev = 0.022
  CI (99.9%): [2.421, 3.231] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.830 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.001 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.926 ±(99.9%) 0.003 ms/op
Iteration   1: 2.919 ±(99.9%) 0.003 ms/op
Iteration   2: 2.917 ±(99.9%) 0.003 ms/op
Iteration   3: 2.897 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.911 ±(99.9%) 0.224 ms/op [Average]
  (min, avg, max) = (2.897, 2.911, 2.919), stdev = 0.012
  CI (99.9%): [2.687, 3.135] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.114 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.840 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.776 ±(99.9%) 0.022 ms/op
Iteration   1: 3.842 ±(99.9%) 0.023 ms/op
Iteration   2: 3.789 ±(99.9%) 0.044 ms/op
Iteration   3: 3.703 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.778 ±(99.9%) 1.277 ms/op [Average]
  (min, avg, max) = (3.703, 3.778, 3.842), stdev = 0.070
  CI (99.9%): [2.501, 5.055] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.783 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.099 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.006 ms/op
Iteration   1: 2.929 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.746 ms/op
                 createUser·p0.50:   2.929 ms/op
                 createUser·p0.90:   3.375 ms/op
                 createUser·p0.95:   3.695 ms/op
                 createUser·p0.99:   4.211 ms/op
                 createUser·p0.999:  7.733 ms/op
                 createUser·p0.9999: 13.112 ms/op
                 createUser·p1.00:   13.533 ms/op

Iteration   2: 2.951 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.570 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  7.281 ms/op
                 createUser·p0.9999: 13.967 ms/op
                 createUser·p1.00:   15.172 ms/op

Iteration   3: 2.912 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.581 ms/op
                 createUser·p0.50:   2.920 ms/op
                 createUser·p0.90:   3.265 ms/op
                 createUser·p0.95:   3.469 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  8.548 ms/op
                 createUser·p0.9999: 17.138 ms/op
                 createUser·p1.00:   17.465 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 327406
  mean =      2.931 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2358 
    [ 1.250,  2.500) = 30087 
    [ 2.500,  3.750) = 282086 
    [ 3.750,  5.000) = 11808 
    [ 5.000,  6.250) = 444 
    [ 6.250,  7.500) = 221 
    [ 7.500,  8.750) = 141 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.570 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.654 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      7.930 ms/op
     p(99.9900) =     15.613 ms/op
     p(99.9990) =     17.391 ms/op
     p(99.9999) =     17.465 ms/op
    p(100.0000) =     17.465 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.765 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.908 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.903 ±(99.9%) 0.006 ms/op
Iteration   1: 2.793 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.656 ms/op
                 existUser·p0.50:   2.793 ms/op
                 existUser·p0.90:   3.170 ms/op
                 existUser·p0.95:   3.396 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  6.623 ms/op
                 existUser·p0.9999: 11.740 ms/op
                 existUser·p1.00:   11.977 ms/op

Iteration   2: 2.843 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.515 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  7.276 ms/op
                 existUser·p0.9999: 19.144 ms/op
                 existUser·p1.00:   19.988 ms/op

Iteration   3: 2.877 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.475 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.555 ms/op
                 existUser·p0.999:  6.362 ms/op
                 existUser·p0.9999: 18.961 ms/op
                 existUser·p1.00:   19.399 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 338281
  mean =      2.837 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3278 
    [ 1.250,  2.500) = 53037 
    [ 2.500,  3.750) = 270859 
    [ 3.750,  5.000) = 9689 
    [ 5.000,  6.250) = 939 
    [ 6.250,  7.500) = 212 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.475 ms/op
     p(50.0000) =      2.826 ms/op
     p(90.0000) =      3.305 ms/op
     p(95.0000) =      3.543 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      6.721 ms/op
     p(99.9900) =     18.099 ms/op
     p(99.9990) =     19.845 ms/op
     p(99.9999) =     19.988 ms/op
    p(100.0000) =     19.988 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.762 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.048 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.903 ±(99.9%) 0.006 ms/op
Iteration   1: 2.919 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.639 ms/op
                 getUser·p0.50:   2.908 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  6.605 ms/op
                 getUser·p0.9999: 11.502 ms/op
                 getUser·p1.00:   11.764 ms/op

Iteration   2: 2.918 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.531 ms/op
                 getUser·p0.50:   2.892 ms/op
                 getUser·p0.90:   3.387 ms/op
                 getUser·p0.95:   3.666 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  6.860 ms/op
                 getUser·p0.9999: 21.892 ms/op
                 getUser·p1.00:   22.315 ms/op

Iteration   3: 2.922 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.531 ms/op
                 getUser·p0.50:   2.904 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   4.178 ms/op
                 getUser·p0.999:  6.816 ms/op
                 getUser·p0.9999: 17.729 ms/op
                 getUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 328874
  mean =      2.920 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44747 
    [ 2.500,  5.000) = 283096 
    [ 5.000,  7.500) = 788 
    [ 7.500, 10.000) = 51 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.531 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      6.799 ms/op
     p(99.9900) =     18.347 ms/op
     p(99.9990) =     22.198 ms/op
     p(99.9999) =     22.315 ms/op
    p(100.0000) =     22.315 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.409 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.886 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.807 ±(99.9%) 0.009 ms/op
Iteration   1: 3.816 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.108 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.678 ms/op
                 listUser·p0.95:   5.325 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  12.990 ms/op
                 listUser·p0.9999: 18.980 ms/op
                 listUser·p1.00:   19.399 ms/op

Iteration   2: 3.714 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.651 ms/op
                 listUser·p0.50:   3.617 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   5.259 ms/op
                 listUser·p0.99:   6.439 ms/op
                 listUser·p0.999:  14.025 ms/op
                 listUser·p0.9999: 17.789 ms/op
                 listUser·p1.00:   18.547 ms/op

Iteration   3: 3.849 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.053 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  13.992 ms/op
                 listUser·p0.9999: 22.427 ms/op
                 listUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 253036
  mean =      3.792 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6977 
    [ 2.500,  5.000) = 226327 
    [ 5.000,  7.500) = 18786 
    [ 7.500, 10.000) = 474 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 215 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.651 ms/op
     p(50.0000) =      3.654 ms/op
     p(90.0000) =      4.768 ms/op
     p(95.0000) =      5.423 ms/op
     p(99.0000) =      6.619 ms/op
     p(99.9000) =     13.943 ms/op
     p(99.9900) =     21.214 ms/op
     p(99.9990) =     22.754 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.922 ± 1.349  ops/ms
ClientGrpc.existUser                       thrpt       3  11.256 ± 2.026  ops/ms
ClientGrpc.getUser                         thrpt       3  10.999 ± 0.491  ops/ms
ClientGrpc.listUser                        thrpt       3   8.503 ± 1.333  ops/ms
ClientGrpc.createUser                       avgt       3   2.929 ± 0.886   ms/op
ClientGrpc.existUser                        avgt       3   2.826 ± 0.405   ms/op
ClientGrpc.getUser                          avgt       3   2.911 ± 0.224   ms/op
ClientGrpc.listUser                         avgt       3   3.778 ± 1.277   ms/op
ClientGrpc.createUser                     sample  327406   2.931 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.570           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.929           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.400           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.654           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.252           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.930           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.613           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.465           ms/op
ClientGrpc.existUser                      sample  338281   2.837 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.475           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.826           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.305           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.543           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.432           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.721           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.099           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.988           ms/op
ClientGrpc.getUser                        sample  328874   2.920 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.531           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.900           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.473           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.711           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.284           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.799           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.347           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.315           ms/op
ClientGrpc.listUser                       sample  253036   3.792 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.651           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.654           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.768           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.423           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.619           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.943           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.214           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.872           ms/op
