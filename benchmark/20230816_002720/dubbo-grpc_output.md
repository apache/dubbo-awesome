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
# Warmup Iteration   1: 4.424 ops/ms
# Warmup Iteration   2: 9.179 ops/ms
# Warmup Iteration   3: 10.077 ops/ms
Iteration   1: 10.397 ops/ms
Iteration   2: 10.349 ops/ms
Iteration   3: 10.515 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.420 ±(99.9%) 1.554 ops/ms [Average]
  (min, avg, max) = (10.349, 10.420, 10.515), stdev = 0.085
  CI (99.9%): [8.866, 11.974] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.875 ops/ms
# Warmup Iteration   2: 10.542 ops/ms
# Warmup Iteration   3: 10.958 ops/ms
Iteration   1: 11.179 ops/ms
Iteration   2: 11.197 ops/ms
Iteration   3: 10.955 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.110 ±(99.9%) 2.462 ops/ms [Average]
  (min, avg, max) = (10.955, 11.110, 11.197), stdev = 0.135
  CI (99.9%): [8.648, 13.573] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.659 ops/ms
# Warmup Iteration   2: 10.265 ops/ms
# Warmup Iteration   3: 10.588 ops/ms
Iteration   1: 10.466 ops/ms
Iteration   2: 10.583 ops/ms
Iteration   3: 10.635 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.561 ±(99.9%) 1.577 ops/ms [Average]
  (min, avg, max) = (10.466, 10.561, 10.635), stdev = 0.086
  CI (99.9%): [8.984, 12.139] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.775 ops/ms
# Warmup Iteration   2: 7.715 ops/ms
# Warmup Iteration   3: 8.118 ops/ms
Iteration   1: 8.191 ops/ms
Iteration   2: 8.368 ops/ms
Iteration   3: 8.179 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.246 ±(99.9%) 1.932 ops/ms [Average]
  (min, avg, max) = (8.179, 8.246, 8.368), stdev = 0.106
  CI (99.9%): [6.314, 10.178] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.201 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.177 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.003 ms/op
Iteration   1: 3.003 ±(99.9%) 0.003 ms/op
Iteration   2: 3.002 ±(99.9%) 0.002 ms/op
Iteration   3: 3.038 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.015 ±(99.9%) 0.377 ms/op [Average]
  (min, avg, max) = (3.002, 3.015, 3.038), stdev = 0.021
  CI (99.9%): [2.638, 3.391] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.033 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 2.985 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.003 ms/op
Iteration   1: 2.925 ±(99.9%) 0.003 ms/op
Iteration   2: 2.937 ±(99.9%) 0.003 ms/op
Iteration   3: 2.896 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.919 ±(99.9%) 0.392 ms/op [Average]
  (min, avg, max) = (2.896, 2.919, 2.937), stdev = 0.021
  CI (99.9%): [2.527, 3.311] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.202 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.088 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.071 ±(99.9%) 0.002 ms/op
Iteration   1: 3.061 ±(99.9%) 0.002 ms/op
Iteration   2: 3.012 ±(99.9%) 0.003 ms/op
Iteration   3: 3.010 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.028 ±(99.9%) 0.521 ms/op [Average]
  (min, avg, max) = (3.010, 3.028, 3.061), stdev = 0.029
  CI (99.9%): [2.506, 3.549] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.841 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.055 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.999 ±(99.9%) 0.023 ms/op
Iteration   1: 3.896 ±(99.9%) 0.022 ms/op
Iteration   2: 3.970 ±(99.9%) 0.041 ms/op
Iteration   3: 3.921 ±(99.9%) 0.031 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.929 ±(99.9%) 0.687 ms/op [Average]
  (min, avg, max) = (3.896, 3.929, 3.970), stdev = 0.038
  CI (99.9%): [3.242, 4.616] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.858 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.185 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.007 ms/op
Iteration   1: 3.005 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.681 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.653 ms/op
                 createUser·p0.999:  8.667 ms/op
                 createUser·p0.9999: 12.943 ms/op
                 createUser·p1.00:   13.255 ms/op

Iteration   2: 3.071 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.836 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   4.760 ms/op
                 createUser·p0.999:  10.160 ms/op
                 createUser·p0.9999: 16.630 ms/op
                 createUser·p1.00:   17.236 ms/op

Iteration   3: 3.074 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.740 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   4.646 ms/op
                 createUser·p0.999:  9.501 ms/op
                 createUser·p0.9999: 17.589 ms/op
                 createUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314792
  mean =      3.050 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1681 
    [ 1.250,  2.500) = 21363 
    [ 2.500,  3.750) = 271127 
    [ 3.750,  5.000) = 18501 
    [ 5.000,  6.250) = 1008 
    [ 6.250,  7.500) = 489 
    [ 7.500,  8.750) = 188 
    [ 8.750, 10.000) = 164 
    [10.000, 11.250) = 49 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 49 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 36 
    [16.250, 17.500) = 33 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.681 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      4.678 ms/op
     p(99.9000) =      9.555 ms/op
     p(99.9900) =     16.597 ms/op
     p(99.9990) =     18.022 ms/op
     p(99.9999) =     18.088 ms/op
    p(100.0000) =     18.088 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.916 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.010 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.969 ±(99.9%) 0.007 ms/op
Iteration   1: 2.975 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.586 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   4.579 ms/op
                 existUser·p0.999:  8.367 ms/op
                 existUser·p0.9999: 17.375 ms/op
                 existUser·p1.00:   17.629 ms/op

Iteration   2: 2.912 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.570 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   4.604 ms/op
                 existUser·p0.999:  6.816 ms/op
                 existUser·p0.9999: 13.092 ms/op
                 existUser·p1.00:   13.500 ms/op

Iteration   3: 2.913 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.748 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.661 ms/op
                 existUser·p0.999:  9.851 ms/op
                 existUser·p0.9999: 19.433 ms/op
                 existUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327245
  mean =      2.933 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2861 
    [ 1.250,  2.500) = 40756 
    [ 2.500,  3.750) = 267767 
    [ 3.750,  5.000) = 14130 
    [ 5.000,  6.250) = 864 
    [ 6.250,  7.500) = 462 
    [ 7.500,  8.750) = 137 
    [ 8.750, 10.000) = 72 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.570 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.612 ms/op
     p(99.9000) =      8.149 ms/op
     p(99.9900) =     17.936 ms/op
     p(99.9990) =     19.554 ms/op
     p(99.9999) =     19.562 ms/op
    p(100.0000) =     19.562 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.112 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.189 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.116 ±(99.9%) 0.006 ms/op
Iteration   1: 3.005 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.636 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  8.319 ms/op
                 getUser·p0.9999: 11.781 ms/op
                 getUser·p1.00:   14.778 ms/op

Iteration   2: 3.080 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.748 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  8.567 ms/op
                 getUser·p0.9999: 12.884 ms/op
                 getUser·p1.00:   13.861 ms/op

Iteration   3: 2.989 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.546 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  7.848 ms/op
                 getUser·p0.9999: 15.537 ms/op
                 getUser·p1.00:   15.958 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317450
  mean =      3.024 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1593 
    [ 1.250,  2.500) = 21366 
    [ 2.500,  3.750) = 279166 
    [ 3.750,  5.000) = 13836 
    [ 5.000,  6.250) = 718 
    [ 6.250,  7.500) = 274 
    [ 7.500,  8.750) = 272 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 37 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      8.200 ms/op
     p(99.9900) =     14.680 ms/op
     p(99.9990) =     15.769 ms/op
     p(99.9999) =     15.958 ms/op
    p(100.0000) =     15.958 ms/op


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
# Warmup Iteration   1: 5.090 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.228 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.981 ±(99.9%) 0.011 ms/op
Iteration   1: 3.952 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.219 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  12.894 ms/op
                 listUser·p0.9999: 15.106 ms/op
                 listUser·p1.00:   15.352 ms/op

Iteration   2: 3.822 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.118 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.390 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  13.227 ms/op
                 listUser·p0.9999: 21.491 ms/op
                 listUser·p1.00:   21.987 ms/op

Iteration   3: 3.938 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.957 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   7.209 ms/op
                 listUser·p0.999:  16.760 ms/op
                 listUser·p0.9999: 22.610 ms/op
                 listUser·p1.00:   23.134 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245986
  mean =      3.903 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4272 
    [ 2.500,  5.000) = 221209 
    [ 5.000,  7.500) = 18832 
    [ 7.500, 10.000) = 1160 
    [10.000, 12.500) = 177 
    [12.500, 15.000) = 163 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.957 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.841 ms/op
     p(95.0000) =      5.472 ms/op
     p(99.0000) =      7.029 ms/op
     p(99.9000) =     13.222 ms/op
     p(99.9900) =     21.561 ms/op
     p(99.9990) =     23.021 ms/op
     p(99.9999) =     23.134 ms/op
    p(100.0000) =     23.134 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.420 ± 1.554  ops/ms
ClientGrpc.existUser                       thrpt       3  11.110 ± 2.462  ops/ms
ClientGrpc.getUser                         thrpt       3  10.561 ± 1.577  ops/ms
ClientGrpc.listUser                        thrpt       3   8.246 ± 1.932  ops/ms
ClientGrpc.createUser                       avgt       3   3.015 ± 0.377   ms/op
ClientGrpc.existUser                        avgt       3   2.919 ± 0.392   ms/op
ClientGrpc.getUser                          avgt       3   3.028 ± 0.521   ms/op
ClientGrpc.listUser                         avgt       3   3.929 ± 0.687   ms/op
ClientGrpc.createUser                     sample  314792   3.050 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.681           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.027           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.584           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.846           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.678           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.555           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.597           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.088           ms/op
ClientGrpc.existUser                      sample  327245   2.933 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.570           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.912           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.490           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.740           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.612           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.149           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.936           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.562           ms/op
ClientGrpc.getUser                        sample  317450   3.024 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.546           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.015           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.543           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.740           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.432           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.200           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.680           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          15.958           ms/op
ClientGrpc.listUser                       sample  245986   3.903 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.957           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.768           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.841           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.472           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.029           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.222           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.561           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.134           ms/op
