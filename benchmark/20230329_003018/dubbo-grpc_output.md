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
# Warmup Iteration   1: 5.143 ops/ms
# Warmup Iteration   2: 9.695 ops/ms
# Warmup Iteration   3: 10.436 ops/ms
Iteration   1: 10.874 ops/ms
Iteration   2: 10.727 ops/ms
Iteration   3: 11.151 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.917 ±(99.9%) 3.932 ops/ms [Average]
  (min, avg, max) = (10.727, 10.917, 11.151), stdev = 0.216
  CI (99.9%): [6.985, 14.850] (assumes normal distribution)


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
# Warmup Iteration   1: 7.856 ops/ms
# Warmup Iteration   2: 11.169 ops/ms
# Warmup Iteration   3: 11.475 ops/ms
Iteration   1: 11.308 ops/ms
Iteration   2: 11.947 ops/ms
Iteration   3: 11.224 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.493 ±(99.9%) 7.210 ops/ms [Average]
  (min, avg, max) = (11.224, 11.493, 11.947), stdev = 0.395
  CI (99.9%): [4.283, 18.703] (assumes normal distribution)


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
# Warmup Iteration   1: 7.495 ops/ms
# Warmup Iteration   2: 10.606 ops/ms
# Warmup Iteration   3: 10.846 ops/ms
Iteration   1: 10.832 ops/ms
Iteration   2: 10.794 ops/ms
Iteration   3: 10.951 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.859 ±(99.9%) 1.500 ops/ms [Average]
  (min, avg, max) = (10.794, 10.859, 10.951), stdev = 0.082
  CI (99.9%): [9.359, 12.359] (assumes normal distribution)


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
# Warmup Iteration   1: 6.651 ops/ms
# Warmup Iteration   2: 7.947 ops/ms
# Warmup Iteration   3: 8.263 ops/ms
Iteration   1: 8.321 ops/ms
Iteration   2: 8.367 ops/ms
Iteration   3: 8.536 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.408 ±(99.9%) 2.065 ops/ms [Average]
  (min, avg, max) = (8.321, 8.408, 8.536), stdev = 0.113
  CI (99.9%): [6.343, 10.473] (assumes normal distribution)


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
# Warmup Iteration   1: 3.917 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.071 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.005 ms/op
Iteration   1: 2.945 ±(99.9%) 0.003 ms/op
Iteration   2: 3.009 ±(99.9%) 0.002 ms/op
Iteration   3: 2.964 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.973 ±(99.9%) 0.606 ms/op [Average]
  (min, avg, max) = (2.945, 2.973, 3.009), stdev = 0.033
  CI (99.9%): [2.367, 3.578] (assumes normal distribution)


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
# Warmup Iteration   1: 3.678 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 2.894 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.874 ±(99.9%) 0.003 ms/op
Iteration   1: 2.864 ±(99.9%) 0.003 ms/op
Iteration   2: 2.884 ±(99.9%) 0.002 ms/op
Iteration   3: 2.813 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.854 ±(99.9%) 0.675 ms/op [Average]
  (min, avg, max) = (2.813, 2.854, 2.884), stdev = 0.037
  CI (99.9%): [2.178, 3.529] (assumes normal distribution)


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
# Warmup Iteration   1: 3.830 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.039 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.929 ±(99.9%) 0.003 ms/op
Iteration   1: 2.956 ±(99.9%) 0.002 ms/op
Iteration   2: 2.970 ±(99.9%) 0.002 ms/op
Iteration   3: 2.908 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.945 ±(99.9%) 0.591 ms/op [Average]
  (min, avg, max) = (2.908, 2.945, 2.970), stdev = 0.032
  CI (99.9%): [2.354, 3.535] (assumes normal distribution)


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
# Warmup Iteration   1: 4.240 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.950 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.874 ±(99.9%) 0.020 ms/op
Iteration   1: 3.613 ±(99.9%) 0.049 ms/op
Iteration   2: 3.850 ±(99.9%) 0.038 ms/op
Iteration   3: 3.859 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.774 ±(99.9%) 2.553 ms/op [Average]
  (min, avg, max) = (3.613, 3.774, 3.859), stdev = 0.140
  CI (99.9%): [1.221, 6.327] (assumes normal distribution)


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
# Warmup Iteration   1: 3.909 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.045 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.977 ±(99.9%) 0.006 ms/op
Iteration   1: 2.879 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.695 ms/op
                 createUser·p0.50:   2.884 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  6.872 ms/op
                 createUser·p0.9999: 10.253 ms/op
                 createUser·p1.00:   10.748 ms/op

Iteration   2: 2.918 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.229 ms/op
                 createUser·p0.50:   2.925 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.710 ms/op
                 createUser·p0.999:  8.869 ms/op
                 createUser·p0.9999: 20.644 ms/op
                 createUser·p1.00:   20.972 ms/op

Iteration   3: 2.943 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.761 ms/op
                 createUser·p0.50:   2.925 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.662 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  11.409 ms/op
                 createUser·p0.9999: 26.218 ms/op
                 createUser·p1.00:   26.378 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 329607
  mean =      2.913 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 49192 
    [ 2.500,  5.000) = 278693 
    [ 5.000,  7.500) = 1272 
    [ 7.500, 10.000) = 192 
    [10.000, 12.500) = 131 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.229 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =      9.110 ms/op
     p(99.9900) =     21.158 ms/op
     p(99.9990) =     26.336 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


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
# Warmup Iteration   1: 3.749 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.001 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.878 ±(99.9%) 0.005 ms/op
Iteration   1: 2.857 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.578 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.523 ms/op
                 existUser·p0.99:   4.133 ms/op
                 existUser·p0.999:  7.566 ms/op
                 existUser·p0.9999: 12.366 ms/op
                 existUser·p1.00:   12.599 ms/op

Iteration   2: 2.845 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.468 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.289 ms/op
                 existUser·p0.95:   3.523 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  8.634 ms/op
                 existUser·p0.9999: 12.190 ms/op
                 existUser·p1.00:   12.419 ms/op

Iteration   3: 2.852 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.548 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.398 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  5.988 ms/op
                 existUser·p0.9999: 15.090 ms/op
                 existUser·p1.00:   15.499 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 336667
  mean =      2.851 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4018 
    [ 1.250,  2.500) = 47704 
    [ 2.500,  3.750) = 275598 
    [ 3.750,  5.000) = 8224 
    [ 5.000,  6.250) = 710 
    [ 6.250,  7.500) = 123 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 34 
    [11.250, 12.500) = 111 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.468 ms/op
     p(50.0000) =      2.851 ms/op
     p(90.0000) =      3.338 ms/op
     p(95.0000) =      3.559 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      6.955 ms/op
     p(99.9900) =     12.556 ms/op
     p(99.9990) =     15.383 ms/op
     p(99.9999) =     15.499 ms/op
    p(100.0000) =     15.499 ms/op


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
# Warmup Iteration   1: 3.717 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.026 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.958 ±(99.9%) 0.006 ms/op
Iteration   1: 2.960 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.676 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  7.876 ms/op
                 getUser·p0.9999: 12.523 ms/op
                 getUser·p1.00:   12.763 ms/op

Iteration   2: 2.999 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.658 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   4.132 ms/op
                 getUser·p0.999:  6.032 ms/op
                 getUser·p0.9999: 16.297 ms/op
                 getUser·p1.00:   16.777 ms/op

Iteration   3: 2.925 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.523 ms/op
                 getUser·p0.50:   2.929 ms/op
                 getUser·p0.90:   3.400 ms/op
                 getUser·p0.95:   3.621 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  6.081 ms/op
                 getUser·p0.9999: 25.234 ms/op
                 getUser·p1.00:   25.362 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 324143
  mean =      2.961 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30262 
    [ 2.500,  5.000) = 292713 
    [ 5.000,  7.500) = 924 
    [ 7.500, 10.000) = 52 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.523 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.654 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      6.471 ms/op
     p(99.9900) =     21.325 ms/op
     p(99.9990) =     25.330 ms/op
     p(99.9999) =     25.362 ms/op
    p(100.0000) =     25.362 ms/op


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
# Warmup Iteration   1: 5.140 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.977 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.925 ±(99.9%) 0.011 ms/op
Iteration   1: 3.785 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.180 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.358 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  14.524 ms/op
                 listUser·p0.9999: 18.648 ms/op
                 listUser·p1.00:   19.038 ms/op

Iteration   2: 3.852 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.286 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   5.153 ms/op
                 listUser·p0.99:   6.398 ms/op
                 listUser·p0.999:  15.562 ms/op
                 listUser·p0.9999: 20.623 ms/op
                 listUser·p1.00:   23.462 ms/op

Iteration   3: 3.862 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.862 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  18.883 ms/op
                 listUser·p0.9999: 24.353 ms/op
                 listUser·p1.00:   24.936 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 250387
  mean =      3.833 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4840 
    [ 2.500,  5.000) = 229302 
    [ 5.000,  7.500) = 15265 
    [ 7.500, 10.000) = 488 
    [10.000, 12.500) = 97 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.862 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      5.308 ms/op
     p(99.0000) =      6.619 ms/op
     p(99.9000) =     15.700 ms/op
     p(99.9900) =     23.264 ms/op
     p(99.9990) =     24.838 ms/op
     p(99.9999) =     24.936 ms/op
    p(100.0000) =     24.936 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.917 ± 3.932  ops/ms
ClientGrpc.existUser                       thrpt       3  11.493 ± 7.210  ops/ms
ClientGrpc.getUser                         thrpt       3  10.859 ± 1.500  ops/ms
ClientGrpc.listUser                        thrpt       3   8.408 ± 2.065  ops/ms
ClientGrpc.createUser                       avgt       3   2.973 ± 0.606   ms/op
ClientGrpc.existUser                        avgt       3   2.854 ± 0.675   ms/op
ClientGrpc.getUser                          avgt       3   2.945 ± 0.591   ms/op
ClientGrpc.listUser                         avgt       3   3.774 ± 2.553   ms/op
ClientGrpc.createUser                     sample  329607   2.913 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.229           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.912           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.465           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.740           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.588           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.110           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.158           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.378           ms/op
ClientGrpc.existUser                      sample  336667   2.851 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.468           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.851           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.338           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.559           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.252           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.955           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          12.556           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.499           ms/op
ClientGrpc.getUser                        sample  324143   2.961 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.523           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.953           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.469           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.654           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.284           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.471           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.325           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.362           ms/op
ClientGrpc.listUser                       sample  250387   3.833 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.862           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.727           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.538           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.308           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.619           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.700           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.264           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.936           ms/op
