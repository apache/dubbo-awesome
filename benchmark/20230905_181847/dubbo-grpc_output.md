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
# Warmup Iteration   1: 4.317 ops/ms
# Warmup Iteration   2: 9.100 ops/ms
# Warmup Iteration   3: 10.316 ops/ms
Iteration   1: 10.465 ops/ms
Iteration   2: 10.264 ops/ms
Iteration   3: 10.589 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.439 ±(99.9%) 2.994 ops/ms [Average]
  (min, avg, max) = (10.264, 10.439, 10.589), stdev = 0.164
  CI (99.9%): [7.446, 13.433] (assumes normal distribution)


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
# Warmup Iteration   1: 7.571 ops/ms
# Warmup Iteration   2: 10.474 ops/ms
# Warmup Iteration   3: 10.857 ops/ms
Iteration   1: 10.877 ops/ms
Iteration   2: 11.035 ops/ms
Iteration   3: 11.068 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.994 ±(99.9%) 1.859 ops/ms [Average]
  (min, avg, max) = (10.877, 10.994, 11.068), stdev = 0.102
  CI (99.9%): [9.135, 12.852] (assumes normal distribution)


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
# Warmup Iteration   1: 6.901 ops/ms
# Warmup Iteration   2: 10.232 ops/ms
# Warmup Iteration   3: 10.371 ops/ms
Iteration   1: 10.469 ops/ms
Iteration   2: 10.444 ops/ms
Iteration   3: 10.380 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.431 ±(99.9%) 0.833 ops/ms [Average]
  (min, avg, max) = (10.380, 10.431, 10.469), stdev = 0.046
  CI (99.9%): [9.598, 11.264] (assumes normal distribution)


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
# Warmup Iteration   1: 6.508 ops/ms
# Warmup Iteration   2: 7.390 ops/ms
# Warmup Iteration   3: 7.842 ops/ms
Iteration   1: 8.003 ops/ms
Iteration   2: 7.916 ops/ms
Iteration   3: 8.020 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.980 ±(99.9%) 1.014 ops/ms [Average]
  (min, avg, max) = (7.916, 7.980, 8.020), stdev = 0.056
  CI (99.9%): [6.965, 8.994] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.164 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.218 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.112 ±(99.9%) 0.003 ms/op
Iteration   1: 3.034 ±(99.9%) 0.003 ms/op
Iteration   2: 3.039 ±(99.9%) 0.003 ms/op
Iteration   3: 3.071 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.048 ±(99.9%) 0.370 ms/op [Average]
  (min, avg, max) = (3.034, 3.048, 3.071), stdev = 0.020
  CI (99.9%): [2.678, 3.418] (assumes normal distribution)


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
# Warmup Iteration   1: 4.070 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.019 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 2.976 ±(99.9%) 0.004 ms/op
Iteration   1: 2.927 ±(99.9%) 0.002 ms/op
Iteration   2: 2.882 ±(99.9%) 0.003 ms/op
Iteration   3: 2.911 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.907 ±(99.9%) 0.423 ms/op [Average]
  (min, avg, max) = (2.882, 2.907, 2.927), stdev = 0.023
  CI (99.9%): [2.484, 3.330] (assumes normal distribution)


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
# Warmup Iteration   1: 3.824 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.096 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.003 ms/op
Iteration   1: 3.012 ±(99.9%) 0.004 ms/op
Iteration   2: 3.043 ±(99.9%) 0.003 ms/op
Iteration   3: 2.998 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.017 ±(99.9%) 0.422 ms/op [Average]
  (min, avg, max) = (2.998, 3.017, 3.043), stdev = 0.023
  CI (99.9%): [2.596, 3.439] (assumes normal distribution)


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
# Warmup Iteration   1: 4.786 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.130 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 4.036 ±(99.9%) 0.024 ms/op
Iteration   1: 4.042 ±(99.9%) 0.021 ms/op
Iteration   2: 3.989 ±(99.9%) 0.011 ms/op
Iteration   3: 3.998 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.009 ±(99.9%) 0.515 ms/op [Average]
  (min, avg, max) = (3.989, 4.009, 4.042), stdev = 0.028
  CI (99.9%): [3.494, 4.525] (assumes normal distribution)


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
# Warmup Iteration   1: 4.280 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.248 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.094 ±(99.9%) 0.007 ms/op
Iteration   1: 3.066 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.822 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.977 ms/op
                 createUser·p0.99:   4.698 ms/op
                 createUser·p0.999:  7.267 ms/op
                 createUser·p0.9999: 11.944 ms/op
                 createUser·p1.00:   12.288 ms/op

Iteration   2: 3.067 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.817 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.637 ms/op
                 createUser·p0.999:  8.359 ms/op
                 createUser·p0.9999: 13.435 ms/op
                 createUser·p1.00:   13.648 ms/op

Iteration   3: 3.084 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.445 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  7.864 ms/op
                 createUser·p0.9999: 14.920 ms/op
                 createUser·p1.00:   16.712 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312453
  mean =      3.073 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 755 
    [ 1.250,  2.500) = 15175 
    [ 2.500,  3.750) = 276931 
    [ 3.750,  5.000) = 17670 
    [ 5.000,  6.250) = 998 
    [ 6.250,  7.500) = 548 
    [ 7.500,  8.750) = 138 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 72 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 57 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.445 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =      7.881 ms/op
     p(99.9900) =     14.496 ms/op
     p(99.9990) =     16.288 ms/op
     p(99.9999) =     16.712 ms/op
    p(100.0000) =     16.712 ms/op


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
# Warmup Iteration   1: 4.053 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.004 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.965 ±(99.9%) 0.006 ms/op
Iteration   1: 2.890 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.520 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.506 ms/op
                 existUser·p0.999:  7.687 ms/op
                 existUser·p0.9999: 12.829 ms/op
                 existUser·p1.00:   13.058 ms/op

Iteration   2: 2.939 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.695 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  6.701 ms/op
                 existUser·p0.9999: 13.617 ms/op
                 existUser·p1.00:   13.828 ms/op

Iteration   3: 2.925 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.621 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   4.604 ms/op
                 existUser·p0.999:  7.747 ms/op
                 existUser·p0.9999: 19.010 ms/op
                 existUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328778
  mean =      2.918 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2676 
    [ 1.250,  2.500) = 36210 
    [ 2.500,  3.750) = 277139 
    [ 3.750,  5.000) = 11083 
    [ 5.000,  6.250) = 1025 
    [ 6.250,  7.500) = 339 
    [ 7.500,  8.750) = 146 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.520 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.650 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =      7.348 ms/op
     p(99.9900) =     14.883 ms/op
     p(99.9990) =     19.356 ms/op
     p(99.9999) =     19.497 ms/op
    p(100.0000) =     19.497 ms/op


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
# Warmup Iteration   1: 4.002 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.205 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.007 ms/op
Iteration   1: 3.113 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.568 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.545 ms/op
                 getUser·p0.999:  8.325 ms/op
                 getUser·p0.9999: 12.754 ms/op
                 getUser·p1.00:   13.074 ms/op

Iteration   2: 3.012 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.648 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  6.472 ms/op
                 getUser·p0.9999: 15.201 ms/op
                 getUser·p1.00:   17.433 ms/op

Iteration   3: 3.082 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.665 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  7.456 ms/op
                 getUser·p0.9999: 16.283 ms/op
                 getUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312683
  mean =      3.068 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1693 
    [ 1.250,  2.500) = 22076 
    [ 2.500,  3.750) = 268696 
    [ 3.750,  5.000) = 18630 
    [ 5.000,  6.250) = 884 
    [ 6.250,  7.500) = 338 
    [ 7.500,  8.750) = 152 
    [ 8.750, 10.000) = 46 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 50 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.568 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      7.823 ms/op
     p(99.9900) =     15.708 ms/op
     p(99.9990) =     17.654 ms/op
     p(99.9999) =     17.760 ms/op
    p(100.0000) =     17.760 ms/op


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
# Warmup Iteration   1: 5.634 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.154 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.008 ±(99.9%) 0.011 ms/op
Iteration   1: 4.008 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.319 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   7.190 ms/op
                 listUser·p0.999:  12.321 ms/op
                 listUser·p0.9999: 19.399 ms/op
                 listUser·p1.00:   19.661 ms/op

Iteration   2: 4.034 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.337 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   7.178 ms/op
                 listUser·p0.999:  13.386 ms/op
                 listUser·p0.9999: 15.045 ms/op
                 listUser·p1.00:   16.269 ms/op

Iteration   3: 4.023 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.161 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.480 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  19.425 ms/op
                 listUser·p0.9999: 26.614 ms/op
                 listUser·p1.00:   27.329 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238696
  mean =      4.021 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2655 
    [ 2.500,  5.000) = 213955 
    [ 5.000,  7.500) = 20431 
    [ 7.500, 10.000) = 1246 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 151 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.932 ms/op
     p(95.0000) =      5.620 ms/op
     p(99.0000) =      7.119 ms/op
     p(99.9000) =     13.533 ms/op
     p(99.9900) =     25.264 ms/op
     p(99.9990) =     27.167 ms/op
     p(99.9999) =     27.329 ms/op
    p(100.0000) =     27.329 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.439 ± 2.994  ops/ms
ClientGrpc.existUser                       thrpt       3  10.994 ± 1.859  ops/ms
ClientGrpc.getUser                         thrpt       3  10.431 ± 0.833  ops/ms
ClientGrpc.listUser                        thrpt       3   7.980 ± 1.014  ops/ms
ClientGrpc.createUser                       avgt       3   3.048 ± 0.370   ms/op
ClientGrpc.existUser                        avgt       3   2.907 ± 0.423   ms/op
ClientGrpc.getUser                          avgt       3   3.017 ± 0.422   ms/op
ClientGrpc.listUser                         avgt       3   4.009 ± 0.515   ms/op
ClientGrpc.createUser                     sample  312453   3.073 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.445           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.039           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.559           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.838           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.588           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.881           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          14.496           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.712           ms/op
ClientGrpc.existUser                      sample  328778   2.918 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.520           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.916           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.400           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.650           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.522           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.348           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.883           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.497           ms/op
ClientGrpc.getUser                        sample  312683   3.068 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.568           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.072           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.617           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.838           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.465           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.823           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.708           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.760           ms/op
ClientGrpc.listUser                       sample  238696   4.021 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.161           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.871           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.932           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.620           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.119           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.533           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.264           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.329           ms/op
