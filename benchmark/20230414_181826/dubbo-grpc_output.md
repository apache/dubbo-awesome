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
# Warmup Iteration   1: 4.419 ops/ms
# Warmup Iteration   2: 8.790 ops/ms
# Warmup Iteration   3: 9.631 ops/ms
Iteration   1: 10.369 ops/ms
Iteration   2: 10.559 ops/ms
Iteration   3: 10.558 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.495 ±(99.9%) 1.991 ops/ms [Average]
  (min, avg, max) = (10.369, 10.495, 10.559), stdev = 0.109
  CI (99.9%): [8.504, 12.486] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.585 ops/ms
# Warmup Iteration   2: 10.629 ops/ms
# Warmup Iteration   3: 10.903 ops/ms
Iteration   1: 10.932 ops/ms
Iteration   2: 11.368 ops/ms
Iteration   3: 11.324 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.208 ±(99.9%) 4.375 ops/ms [Average]
  (min, avg, max) = (10.932, 11.208, 11.368), stdev = 0.240
  CI (99.9%): [6.833, 15.583] (assumes normal distribution)


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
# Warmup Iteration   1: 7.356 ops/ms
# Warmup Iteration   2: 10.445 ops/ms
# Warmup Iteration   3: 10.568 ops/ms
Iteration   1: 10.721 ops/ms
Iteration   2: 10.807 ops/ms
Iteration   3: 10.580 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.702 ±(99.9%) 2.093 ops/ms [Average]
  (min, avg, max) = (10.580, 10.702, 10.807), stdev = 0.115
  CI (99.9%): [8.609, 12.796] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.365 ops/ms
# Warmup Iteration   2: 7.794 ops/ms
# Warmup Iteration   3: 7.756 ops/ms
Iteration   1: 7.983 ops/ms
Iteration   2: 8.230 ops/ms
Iteration   3: 8.047 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.087 ±(99.9%) 2.336 ops/ms [Average]
  (min, avg, max) = (7.983, 8.087, 8.230), stdev = 0.128
  CI (99.9%): [5.751, 10.423] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.376 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.184 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.101 ±(99.9%) 0.002 ms/op
Iteration   1: 3.057 ±(99.9%) 0.004 ms/op
Iteration   2: 3.092 ±(99.9%) 0.003 ms/op
Iteration   3: 3.047 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.065 ±(99.9%) 0.438 ms/op [Average]
  (min, avg, max) = (3.047, 3.065, 3.092), stdev = 0.024
  CI (99.9%): [2.627, 3.503] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.094 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.038 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.906 ±(99.9%) 0.002 ms/op
Iteration   1: 2.850 ±(99.9%) 0.003 ms/op
Iteration   2: 2.864 ±(99.9%) 0.002 ms/op
Iteration   3: 2.885 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.866 ±(99.9%) 0.318 ms/op [Average]
  (min, avg, max) = (2.850, 2.866, 2.885), stdev = 0.017
  CI (99.9%): [2.548, 3.184] (assumes normal distribution)


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
# Warmup Iteration   1: 4.267 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.144 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.003 ms/op
Iteration   1: 3.012 ±(99.9%) 0.003 ms/op
Iteration   2: 3.030 ±(99.9%) 0.003 ms/op
Iteration   3: 2.975 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.006 ±(99.9%) 0.514 ms/op [Average]
  (min, avg, max) = (2.975, 3.006, 3.030), stdev = 0.028
  CI (99.9%): [2.492, 3.520] (assumes normal distribution)


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
# Warmup Iteration   1: 5.479 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.145 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.010 ±(99.9%) 0.008 ms/op
Iteration   1: 3.950 ±(99.9%) 0.017 ms/op
Iteration   2: 4.036 ±(99.9%) 0.022 ms/op
Iteration   3: 3.928 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.972 ±(99.9%) 1.045 ms/op [Average]
  (min, avg, max) = (3.928, 3.972, 4.036), stdev = 0.057
  CI (99.9%): [2.927, 5.016] (assumes normal distribution)


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
# Warmup Iteration   1: 4.302 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.175 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.090 ±(99.9%) 0.007 ms/op
Iteration   1: 3.001 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.580 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.666 ms/op
                 createUser·p0.99:   4.227 ms/op
                 createUser·p0.999:  7.471 ms/op
                 createUser·p0.9999: 12.578 ms/op
                 createUser·p1.00:   15.303 ms/op

Iteration   2: 3.071 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.697 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  8.662 ms/op
                 createUser·p0.9999: 14.938 ms/op
                 createUser·p1.00:   19.694 ms/op

Iteration   3: 3.031 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.663 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.604 ms/op
                 createUser·p0.999:  7.943 ms/op
                 createUser·p0.9999: 17.039 ms/op
                 createUser·p1.00:   17.433 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316216
  mean =      3.034 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 517 
    [ 1.250,  2.500) = 26538 
    [ 2.500,  3.750) = 271971 
    [ 3.750,  5.000) = 15854 
    [ 5.000,  6.250) = 645 
    [ 6.250,  7.500) = 318 
    [ 7.500,  8.750) = 122 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 59 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 36 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.580 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      7.864 ms/op
     p(99.9900) =     16.517 ms/op
     p(99.9990) =     17.258 ms/op
     p(99.9999) =     19.694 ms/op
    p(100.0000) =     19.694 ms/op


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
# Warmup Iteration   1: 3.993 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.031 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.942 ±(99.9%) 0.006 ms/op
Iteration   1: 2.795 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.820 ms/op
                 existUser·p0.50:   2.834 ms/op
                 existUser·p0.90:   3.183 ms/op
                 existUser·p0.95:   3.428 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  7.166 ms/op
                 existUser·p0.9999: 21.055 ms/op
                 existUser·p1.00:   21.856 ms/op

Iteration   2: 2.908 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.711 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  5.678 ms/op
                 existUser·p0.9999: 14.041 ms/op
                 existUser·p1.00:   14.631 ms/op

Iteration   3: 2.877 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.717 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  11.267 ms/op
                 existUser·p0.9999: 18.317 ms/op
                 existUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 335861
  mean =      2.859 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51332 
    [ 2.500,  5.000) = 283445 
    [ 5.000,  7.500) = 801 
    [ 7.500, 10.000) = 42 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.711 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.379 ms/op
     p(95.0000) =      3.613 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      7.037 ms/op
     p(99.9900) =     19.133 ms/op
     p(99.9990) =     21.746 ms/op
     p(99.9999) =     21.856 ms/op
    p(100.0000) =     21.856 ms/op


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
# Warmup Iteration   1: 4.123 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.153 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.062 ±(99.9%) 0.006 ms/op
Iteration   1: 3.017 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.449 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.400 ms/op
                 getUser·p0.95:   3.604 ms/op
                 getUser·p0.99:   4.385 ms/op
                 getUser·p0.999:  7.316 ms/op
                 getUser·p0.9999: 16.384 ms/op
                 getUser·p1.00:   17.105 ms/op

Iteration   2: 3.041 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.653 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.547 ms/op
                 getUser·p0.999:  7.702 ms/op
                 getUser·p0.9999: 22.575 ms/op
                 getUser·p1.00:   23.888 ms/op

Iteration   3: 3.065 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.836 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  6.980 ms/op
                 getUser·p0.9999: 18.088 ms/op
                 getUser·p1.00:   18.448 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315596
  mean =      3.041 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19867 
    [ 2.500,  5.000) = 294322 
    [ 5.000,  7.500) = 1134 
    [ 7.500, 10.000) = 81 
    [10.000, 12.500) = 13 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.449 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      7.261 ms/op
     p(99.9900) =     21.936 ms/op
     p(99.9990) =     22.801 ms/op
     p(99.9999) =     23.888 ms/op
    p(100.0000) =     23.888 ms/op


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
# Warmup Iteration   1: 5.525 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.042 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.991 ±(99.9%) 0.012 ms/op
Iteration   1: 3.999 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.239 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   6.809 ms/op
                 listUser·p0.999:  15.322 ms/op
                 listUser·p0.9999: 29.098 ms/op
                 listUser·p1.00:   29.360 ms/op

Iteration   2: 4.007 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.411 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  16.030 ms/op
                 listUser·p0.9999: 21.692 ms/op
                 listUser·p1.00:   22.053 ms/op

Iteration   3: 4.015 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.110 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  16.215 ms/op
                 listUser·p0.9999: 20.418 ms/op
                 listUser·p1.00:   20.939 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239426
  mean =      4.007 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3004 
    [ 2.500,  5.000) = 214569 
    [ 5.000,  7.500) = 20416 
    [ 7.500, 10.000) = 1023 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 154 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 47 

  Percentiles, ms/op:
      p(0.0000) =      1.110 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.907 ms/op
     p(95.0000) =      5.685 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     16.056 ms/op
     p(99.9900) =     27.134 ms/op
     p(99.9990) =     29.314 ms/op
     p(99.9999) =     29.360 ms/op
    p(100.0000) =     29.360 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.495 ± 1.991  ops/ms
ClientGrpc.existUser                       thrpt       3  11.208 ± 4.375  ops/ms
ClientGrpc.getUser                         thrpt       3  10.702 ± 2.093  ops/ms
ClientGrpc.listUser                        thrpt       3   8.087 ± 2.336  ops/ms
ClientGrpc.createUser                       avgt       3   3.065 ± 0.438   ms/op
ClientGrpc.existUser                        avgt       3   2.866 ± 0.318   ms/op
ClientGrpc.getUser                          avgt       3   3.006 ± 0.514   ms/op
ClientGrpc.listUser                         avgt       3   3.972 ± 1.045   ms/op
ClientGrpc.createUser                     sample  316216   3.034 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.580           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.002           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.584           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.772           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.399           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.864           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.517           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.694           ms/op
ClientGrpc.existUser                      sample  335861   2.859 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.711           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.379           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.613           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.350           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.037           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.133           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.856           ms/op
ClientGrpc.getUser                        sample  315596   3.041 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.449           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.011           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.514           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.744           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.407           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.261           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.936           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.888           ms/op
ClientGrpc.listUser                       sample  239426   4.007 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.110           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.863           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.907           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.685           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.971           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.056           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.134           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.360           ms/op
