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
# Warmup Iteration   1: 3.847 ops/ms
# Warmup Iteration   2: 8.478 ops/ms
# Warmup Iteration   3: 9.587 ops/ms
Iteration   1: 10.298 ops/ms
Iteration   2: 10.282 ops/ms
Iteration   3: 10.311 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.297 ±(99.9%) 0.268 ops/ms [Average]
  (min, avg, max) = (10.282, 10.297, 10.311), stdev = 0.015
  CI (99.9%): [10.029, 10.565] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 6.526 ops/ms
# Warmup Iteration   2: 9.920 ops/ms
# Warmup Iteration   3: 10.949 ops/ms
Iteration   1: 10.918 ops/ms
Iteration   2: 10.722 ops/ms
Iteration   3: 10.910 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.850 ±(99.9%) 2.024 ops/ms [Average]
  (min, avg, max) = (10.722, 10.850, 10.918), stdev = 0.111
  CI (99.9%): [8.826, 12.874] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.060 ops/ms
# Warmup Iteration   2: 9.688 ops/ms
# Warmup Iteration   3: 10.375 ops/ms
Iteration   1: 10.554 ops/ms
Iteration   2: 10.338 ops/ms
Iteration   3: 10.337 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.410 ±(99.9%) 2.282 ops/ms [Average]
  (min, avg, max) = (10.337, 10.410, 10.554), stdev = 0.125
  CI (99.9%): [8.128, 12.691] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.335 ops/ms
# Warmup Iteration   2: 7.545 ops/ms
# Warmup Iteration   3: 7.788 ops/ms
Iteration   1: 7.820 ops/ms
Iteration   2: 7.935 ops/ms
Iteration   3: 7.984 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.913 ±(99.9%) 1.537 ops/ms [Average]
  (min, avg, max) = (7.820, 7.913, 7.984), stdev = 0.084
  CI (99.9%): [6.376, 9.451] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.620 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.288 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 3.097 ±(99.9%) 0.002 ms/op
Iteration   1: 3.091 ±(99.9%) 0.001 ms/op
Iteration   2: 3.071 ±(99.9%) 0.002 ms/op
Iteration   3: 3.063 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.075 ±(99.9%) 0.268 ms/op [Average]
  (min, avg, max) = (3.063, 3.075, 3.091), stdev = 0.015
  CI (99.9%): [2.807, 3.343] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.216 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.082 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.029 ±(99.9%) 0.002 ms/op
Iteration   1: 2.898 ±(99.9%) 0.003 ms/op
Iteration   2: 2.910 ±(99.9%) 0.001 ms/op
Iteration   3: 2.929 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.912 ±(99.9%) 0.286 ms/op [Average]
  (min, avg, max) = (2.898, 2.912, 2.929), stdev = 0.016
  CI (99.9%): [2.626, 3.199] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.661 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 3.229 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.094 ±(99.9%) 0.003 ms/op
Iteration   1: 3.070 ±(99.9%) 0.001 ms/op
Iteration   2: 3.055 ±(99.9%) 0.002 ms/op
Iteration   3: 3.039 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.055 ±(99.9%) 0.280 ms/op [Average]
  (min, avg, max) = (3.039, 3.055, 3.070), stdev = 0.015
  CI (99.9%): [2.775, 3.334] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.912 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.245 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.992 ±(99.9%) 0.021 ms/op
Iteration   1: 4.109 ±(99.9%) 0.019 ms/op
Iteration   2: 4.048 ±(99.9%) 0.012 ms/op
Iteration   3: 4.033 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.064 ±(99.9%) 0.734 ms/op [Average]
  (min, avg, max) = (4.033, 4.064, 4.109), stdev = 0.040
  CI (99.9%): [3.330, 4.797] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.984 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.438 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.078 ±(99.9%) 0.006 ms/op
Iteration   1: 3.061 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.801 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.776 ms/op
                 createUser·p0.999:  7.482 ms/op
                 createUser·p0.9999: 18.237 ms/op
                 createUser·p1.00:   18.842 ms/op

Iteration   2: 3.124 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.521 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  9.230 ms/op
                 createUser·p0.9999: 16.384 ms/op
                 createUser·p1.00:   16.728 ms/op

Iteration   3: 3.094 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.944 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.768 ms/op
                 createUser·p0.999:  11.895 ms/op
                 createUser·p0.9999: 19.027 ms/op
                 createUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310296
  mean =      3.093 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 369 
    [ 1.250,  2.500) = 12878 
    [ 2.500,  3.750) = 278596 
    [ 3.750,  5.000) = 16317 
    [ 5.000,  6.250) = 1250 
    [ 6.250,  7.500) = 456 
    [ 7.500,  8.750) = 112 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 48 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 47 
    [16.250, 17.500) = 42 
    [17.500, 18.750) = 54 

  Percentiles, ms/op:
      p(0.0000) =      0.521 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.645 ms/op
     p(99.9000) =      9.306 ms/op
     p(99.9900) =     18.219 ms/op
     p(99.9990) =     19.392 ms/op
     p(99.9999) =     19.562 ms/op
    p(100.0000) =     19.562 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.345 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.064 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.967 ±(99.9%) 0.006 ms/op
Iteration   1: 2.929 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.784 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  6.877 ms/op
                 existUser·p0.9999: 14.587 ms/op
                 existUser·p1.00:   15.647 ms/op

Iteration   2: 2.938 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.766 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  6.294 ms/op
                 existUser·p0.9999: 17.408 ms/op
                 existUser·p1.00:   18.121 ms/op

Iteration   3: 2.954 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.731 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.452 ms/op
                 existUser·p0.999:  12.567 ms/op
                 existUser·p0.9999: 20.054 ms/op
                 existUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326266
  mean =      2.941 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31766 
    [ 2.500,  5.000) = 293002 
    [ 5.000,  7.500) = 1058 
    [ 7.500, 10.000) = 88 
    [10.000, 12.500) = 162 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.731 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.387 ms/op
     p(95.0000) =      3.629 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =     10.371 ms/op
     p(99.9900) =     17.609 ms/op
     p(99.9990) =     20.087 ms/op
     p(99.9999) =     20.087 ms/op
    p(100.0000) =     20.087 ms/op


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
# Warmup Iteration   1: 4.697 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.296 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.162 ±(99.9%) 0.006 ms/op
Iteration   1: 3.148 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.938 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   4.866 ms/op
                 getUser·p0.999:  8.792 ms/op
                 getUser·p0.9999: 15.735 ms/op
                 getUser·p1.00:   16.155 ms/op

Iteration   2: 3.118 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.898 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.920 ms/op
                 getUser·p0.99:   5.005 ms/op
                 getUser·p0.999:  9.560 ms/op
                 getUser·p0.9999: 15.315 ms/op
                 getUser·p1.00:   15.499 ms/op

Iteration   3: 3.107 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.760 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   4.940 ms/op
                 getUser·p0.999:  8.848 ms/op
                 getUser·p0.9999: 18.691 ms/op
                 getUser·p1.00:   19.104 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 307070
  mean =      3.124 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 525 
    [ 1.250,  2.500) = 12701 
    [ 2.500,  3.750) = 272061 
    [ 3.750,  5.000) = 18905 
    [ 5.000,  6.250) = 1681 
    [ 6.250,  7.500) = 666 
    [ 7.500,  8.750) = 197 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 53 
    [15.000, 16.250) = 62 
    [16.250, 17.500) = 39 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.760 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      4.940 ms/op
     p(99.9000) =      9.011 ms/op
     p(99.9900) =     17.334 ms/op
     p(99.9990) =     19.069 ms/op
     p(99.9999) =     19.104 ms/op
    p(100.0000) =     19.104 ms/op


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
# Warmup Iteration   1: 6.282 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.228 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.134 ±(99.9%) 0.012 ms/op
Iteration   1: 4.049 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.032 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   6.046 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  13.795 ms/op
                 listUser·p0.9999: 17.042 ms/op
                 listUser·p1.00:   17.662 ms/op

Iteration   2: 4.022 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.373 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   7.337 ms/op
                 listUser·p0.999:  16.379 ms/op
                 listUser·p0.9999: 21.465 ms/op
                 listUser·p1.00:   22.282 ms/op

Iteration   3: 3.985 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.274 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  22.309 ms/op
                 listUser·p0.9999: 32.767 ms/op
                 listUser·p1.00:   34.079 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238935
  mean =      4.018 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2074 
    [ 2.500,  5.000) = 213551 
    [ 5.000,  7.500) = 21649 
    [ 7.500, 10.000) = 1197 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.373 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.973 ms/op
     p(95.0000) =      5.800 ms/op
     p(99.0000) =      7.152 ms/op
     p(99.9000) =     15.222 ms/op
     p(99.9900) =     31.818 ms/op
     p(99.9990) =     33.267 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.297 ± 0.268  ops/ms
ClientGrpc.existUser                       thrpt       3  10.850 ± 2.024  ops/ms
ClientGrpc.getUser                         thrpt       3  10.410 ± 2.282  ops/ms
ClientGrpc.listUser                        thrpt       3   7.913 ± 1.537  ops/ms
ClientGrpc.createUser                       avgt       3   3.075 ± 0.268   ms/op
ClientGrpc.existUser                        avgt       3   2.912 ± 0.286   ms/op
ClientGrpc.getUser                          avgt       3   3.055 ± 0.280   ms/op
ClientGrpc.listUser                         avgt       3   4.064 ± 0.734   ms/op
ClientGrpc.createUser                     sample  310296   3.093 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.521           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.052           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.572           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.813           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.645           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.306           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.219           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.562           ms/op
ClientGrpc.existUser                      sample  326266   2.941 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.731           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.908           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.387           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.629           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.350           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.371           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.609           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.087           ms/op
ClientGrpc.getUser                        sample  307070   3.124 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.760           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.080           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.629           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.879           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.940           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.011           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.334           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.104           ms/op
ClientGrpc.listUser                       sample  238935   4.018 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.373           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.850           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.973           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.800           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.152           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.222           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.818           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.079           ms/op
