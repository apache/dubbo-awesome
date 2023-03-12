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
# Warmup Iteration   1: 4.826 ops/ms
# Warmup Iteration   2: 9.083 ops/ms
# Warmup Iteration   3: 10.280 ops/ms
Iteration   1: 10.651 ops/ms
Iteration   2: 10.990 ops/ms
Iteration   3: 10.681 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.774 ±(99.9%) 3.421 ops/ms [Average]
  (min, avg, max) = (10.651, 10.774, 10.990), stdev = 0.188
  CI (99.9%): [7.353, 14.195] (assumes normal distribution)


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
# Warmup Iteration   1: 8.010 ops/ms
# Warmup Iteration   2: 11.003 ops/ms
# Warmup Iteration   3: 11.441 ops/ms
Iteration   1: 11.441 ops/ms
Iteration   2: 11.116 ops/ms
Iteration   3: 11.203 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.254 ±(99.9%) 3.069 ops/ms [Average]
  (min, avg, max) = (11.116, 11.254, 11.441), stdev = 0.168
  CI (99.9%): [8.184, 14.323] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.524 ops/ms
# Warmup Iteration   2: 10.547 ops/ms
# Warmup Iteration   3: 10.724 ops/ms
Iteration   1: 10.832 ops/ms
Iteration   2: 10.714 ops/ms
Iteration   3: 10.849 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.798 ±(99.9%) 1.333 ops/ms [Average]
  (min, avg, max) = (10.714, 10.798, 10.849), stdev = 0.073
  CI (99.9%): [9.465, 12.131] (assumes normal distribution)


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
# Warmup Iteration   1: 6.878 ops/ms
# Warmup Iteration   2: 7.844 ops/ms
# Warmup Iteration   3: 8.407 ops/ms
Iteration   1: 8.169 ops/ms
Iteration   2: 8.254 ops/ms
Iteration   3: 8.266 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.229 ±(99.9%) 0.967 ops/ms [Average]
  (min, avg, max) = (8.169, 8.229, 8.266), stdev = 0.053
  CI (99.9%): [7.263, 9.196] (assumes normal distribution)


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
# Warmup Iteration   1: 3.956 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.077 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.002 ms/op
Iteration   1: 3.010 ±(99.9%) 0.003 ms/op
Iteration   2: 2.968 ±(99.9%) 0.002 ms/op
Iteration   3: 2.974 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.984 ±(99.9%) 0.415 ms/op [Average]
  (min, avg, max) = (2.968, 2.984, 3.010), stdev = 0.023
  CI (99.9%): [2.569, 3.399] (assumes normal distribution)


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
# Warmup Iteration   1: 3.873 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.973 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.840 ±(99.9%) 0.003 ms/op
Iteration   1: 2.850 ±(99.9%) 0.004 ms/op
Iteration   2: 2.842 ±(99.9%) 0.003 ms/op
Iteration   3: 2.831 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.841 ±(99.9%) 0.174 ms/op [Average]
  (min, avg, max) = (2.831, 2.841, 2.850), stdev = 0.010
  CI (99.9%): [2.667, 3.015] (assumes normal distribution)


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
# Warmup Iteration   1: 3.890 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.043 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.957 ±(99.9%) 0.002 ms/op
Iteration   1: 3.010 ±(99.9%) 0.003 ms/op
Iteration   2: 2.910 ±(99.9%) 0.003 ms/op
Iteration   3: 2.988 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.970 ±(99.9%) 0.960 ms/op [Average]
  (min, avg, max) = (2.910, 2.970, 3.010), stdev = 0.053
  CI (99.9%): [2.009, 3.930] (assumes normal distribution)


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
# Warmup Iteration   1: 5.069 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.986 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 3.847 ±(99.9%) 0.031 ms/op
Iteration   1: 3.875 ±(99.9%) 0.059 ms/op
Iteration   2: 3.700 ±(99.9%) 0.022 ms/op
Iteration   3: 3.864 ±(99.9%) 0.031 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.813 ±(99.9%) 1.790 ms/op [Average]
  (min, avg, max) = (3.700, 3.813, 3.875), stdev = 0.098
  CI (99.9%): [2.023, 5.604] (assumes normal distribution)


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
# Warmup Iteration   1: 3.939 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.172 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.005 ms/op
Iteration   1: 2.962 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.721 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  6.382 ms/op
                 createUser·p0.9999: 17.905 ms/op
                 createUser·p1.00:   18.252 ms/op

Iteration   2: 2.989 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.599 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.707 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  10.404 ms/op
                 createUser·p0.9999: 12.768 ms/op
                 createUser·p1.00:   13.042 ms/op

Iteration   3: 2.953 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.760 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.461 ms/op
                 createUser·p0.95:   3.682 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  8.487 ms/op
                 createUser·p0.9999: 15.177 ms/op
                 createUser·p1.00:   15.548 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 323434
  mean =      2.968 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2565 
    [ 1.250,  2.500) = 27284 
    [ 2.500,  3.750) = 280313 
    [ 3.750,  5.000) = 12039 
    [ 5.000,  6.250) = 616 
    [ 6.250,  7.500) = 212 
    [ 7.500,  8.750) = 128 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.599 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      8.290 ms/op
     p(99.9900) =     16.570 ms/op
     p(99.9990) =     18.153 ms/op
     p(99.9999) =     18.252 ms/op
    p(100.0000) =     18.252 ms/op


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
# Warmup Iteration   1: 3.496 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.952 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.856 ±(99.9%) 0.006 ms/op
Iteration   1: 2.818 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.714 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.219 ms/op
                 existUser·p0.95:   3.396 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  6.507 ms/op
                 existUser·p0.9999: 12.063 ms/op
                 existUser·p1.00:   12.386 ms/op

Iteration   2: 2.853 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.705 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.273 ms/op
                 existUser·p0.95:   3.469 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  6.474 ms/op
                 existUser·p0.9999: 14.287 ms/op
                 existUser·p1.00:   14.746 ms/op

Iteration   3: 2.858 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.606 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.289 ms/op
                 existUser·p0.95:   3.449 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  6.243 ms/op
                 existUser·p0.9999: 16.176 ms/op
                 existUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 337735
  mean =      2.843 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3793 
    [ 1.250,  2.500) = 41565 
    [ 2.500,  3.750) = 284692 
    [ 3.750,  5.000) = 6885 
    [ 5.000,  6.250) = 423 
    [ 6.250,  7.500) = 130 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 80 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.606 ms/op
     p(50.0000) =      2.863 ms/op
     p(90.0000) =      3.260 ms/op
     p(95.0000) =      3.437 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      6.398 ms/op
     p(99.9900) =     14.708 ms/op
     p(99.9990) =     18.897 ms/op
     p(99.9999) =     19.333 ms/op
    p(100.0000) =     19.333 ms/op


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
# Warmup Iteration   1: 3.825 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.093 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.006 ms/op
Iteration   1: 2.937 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.254 ms/op
                 getUser·p0.50:   2.941 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.555 ms/op
                 getUser·p0.999:  6.439 ms/op
                 getUser·p0.9999: 14.701 ms/op
                 getUser·p1.00:   15.401 ms/op

Iteration   2: 2.940 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.256 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.432 ms/op
                 getUser·p0.95:   3.650 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  6.923 ms/op
                 getUser·p0.9999: 28.741 ms/op
                 getUser·p1.00:   32.080 ms/op

Iteration   3: 2.958 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.767 ms/op
                 getUser·p0.50:   2.945 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  7.397 ms/op
                 getUser·p0.9999: 17.412 ms/op
                 getUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 326061
  mean =      2.945 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36921 
    [ 2.500,  5.000) = 287826 
    [ 5.000,  7.500) = 1060 
    [ 7.500, 10.000) = 62 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.254 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      7.003 ms/op
     p(99.9900) =     22.002 ms/op
     p(99.9990) =     31.878 ms/op
     p(99.9999) =     32.080 ms/op
    p(100.0000) =     32.080 ms/op


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
# Warmup Iteration   1: 4.812 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.841 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.825 ±(99.9%) 0.009 ms/op
Iteration   1: 3.796 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.221 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.678 ms/op
                 listUser·p0.95:   5.202 ms/op
                 listUser·p0.99:   6.504 ms/op
                 listUser·p0.999:  11.809 ms/op
                 listUser·p0.9999: 19.993 ms/op
                 listUser·p1.00:   22.872 ms/op

Iteration   2: 3.874 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.854 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  13.491 ms/op
                 listUser·p0.9999: 15.090 ms/op
                 listUser·p1.00:   15.909 ms/op

Iteration   3: 3.842 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.253 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.678 ms/op
                 listUser·p0.95:   5.308 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  13.348 ms/op
                 listUser·p0.9999: 27.186 ms/op
                 listUser·p1.00:   27.460 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 250244
  mean =      3.837 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5425 
    [ 2.500,  5.000) = 224710 
    [ 5.000,  7.500) = 18839 
    [ 7.500, 10.000) = 817 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 172 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.253 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.817 ms/op
     p(95.0000) =      5.399 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     13.222 ms/op
     p(99.9900) =     24.421 ms/op
     p(99.9990) =     27.329 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.774 ± 3.421  ops/ms
ClientGrpc.existUser                       thrpt       3  11.254 ± 3.069  ops/ms
ClientGrpc.getUser                         thrpt       3  10.798 ± 1.333  ops/ms
ClientGrpc.listUser                        thrpt       3   8.229 ± 0.967  ops/ms
ClientGrpc.createUser                       avgt       3   2.984 ± 0.415   ms/op
ClientGrpc.existUser                        avgt       3   2.841 ± 0.174   ms/op
ClientGrpc.getUser                          avgt       3   2.970 ± 0.960   ms/op
ClientGrpc.listUser                         avgt       3   3.813 ± 1.790   ms/op
ClientGrpc.createUser                     sample  323434   2.968 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.599           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.966           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.482           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.690           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.290           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.570           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.252           ms/op
ClientGrpc.existUser                      sample  337735   2.843 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.606           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.863           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.260           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.437           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.235           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.398           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.708           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.333           ms/op
ClientGrpc.getUser                        sample  326061   2.945 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.254           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.945           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.445           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.690           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.465           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.003           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.002           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          32.080           ms/op
ClientGrpc.listUser                       sample  250244   3.837 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.253           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.703           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.817           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.399           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.726           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.222           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.421           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.460           ms/op
