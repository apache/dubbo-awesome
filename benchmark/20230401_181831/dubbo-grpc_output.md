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
# Warmup Iteration   1: 4.448 ops/ms
# Warmup Iteration   2: 9.162 ops/ms
# Warmup Iteration   3: 9.899 ops/ms
Iteration   1: 10.565 ops/ms
Iteration   2: 10.346 ops/ms
Iteration   3: 10.321 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.411 ±(99.9%) 2.451 ops/ms [Average]
  (min, avg, max) = (10.321, 10.411, 10.565), stdev = 0.134
  CI (99.9%): [7.960, 12.861] (assumes normal distribution)


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
# Warmup Iteration   1: 7.606 ops/ms
# Warmup Iteration   2: 10.678 ops/ms
# Warmup Iteration   3: 11.238 ops/ms
Iteration   1: 11.274 ops/ms
Iteration   2: 10.946 ops/ms
Iteration   3: 11.066 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.095 ±(99.9%) 3.030 ops/ms [Average]
  (min, avg, max) = (10.946, 11.095, 11.274), stdev = 0.166
  CI (99.9%): [8.065, 14.126] (assumes normal distribution)


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
# Warmup Iteration   1: 7.388 ops/ms
# Warmup Iteration   2: 10.376 ops/ms
# Warmup Iteration   3: 10.816 ops/ms
Iteration   1: 10.725 ops/ms
Iteration   2: 10.622 ops/ms
Iteration   3: 10.718 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.688 ±(99.9%) 1.049 ops/ms [Average]
  (min, avg, max) = (10.622, 10.688, 10.725), stdev = 0.058
  CI (99.9%): [9.639, 11.737] (assumes normal distribution)


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
# Warmup Iteration   1: 5.671 ops/ms
# Warmup Iteration   2: 7.792 ops/ms
# Warmup Iteration   3: 8.019 ops/ms
Iteration   1: 8.117 ops/ms
Iteration   2: 8.064 ops/ms
Iteration   3: 8.035 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.072 ±(99.9%) 0.759 ops/ms [Average]
  (min, avg, max) = (8.035, 8.072, 8.117), stdev = 0.042
  CI (99.9%): [7.313, 8.831] (assumes normal distribution)


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
# Warmup Iteration   1: 4.256 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.145 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.948 ±(99.9%) 0.003 ms/op
Iteration   1: 3.018 ±(99.9%) 0.001 ms/op
Iteration   2: 2.956 ±(99.9%) 0.004 ms/op
Iteration   3: 3.001 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.992 ±(99.9%) 0.591 ms/op [Average]
  (min, avg, max) = (2.956, 2.992, 3.018), stdev = 0.032
  CI (99.9%): [2.401, 3.582] (assumes normal distribution)


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
# Warmup Iteration   1: 3.881 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.997 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.892 ±(99.9%) 0.002 ms/op
Iteration   1: 2.876 ±(99.9%) 0.003 ms/op
Iteration   2: 2.867 ±(99.9%) 0.003 ms/op
Iteration   3: 2.824 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.855 ±(99.9%) 0.512 ms/op [Average]
  (min, avg, max) = (2.824, 2.855, 2.876), stdev = 0.028
  CI (99.9%): [2.344, 3.367] (assumes normal distribution)


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
# Warmup Iteration   1: 4.055 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.089 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.003 ms/op
Iteration   1: 2.985 ±(99.9%) 0.002 ms/op
Iteration   2: 2.978 ±(99.9%) 0.004 ms/op
Iteration   3: 3.036 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.000 ±(99.9%) 0.579 ms/op [Average]
  (min, avg, max) = (2.978, 3.000, 3.036), stdev = 0.032
  CI (99.9%): [2.421, 3.578] (assumes normal distribution)


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
# Warmup Iteration   1: 5.474 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.075 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.949 ±(99.9%) 0.032 ms/op
Iteration   1: 3.911 ±(99.9%) 0.008 ms/op
Iteration   2: 3.914 ±(99.9%) 0.021 ms/op
Iteration   3: 3.831 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.886 ±(99.9%) 0.855 ms/op [Average]
  (min, avg, max) = (3.831, 3.886, 3.914), stdev = 0.047
  CI (99.9%): [3.030, 4.741] (assumes normal distribution)


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
# Warmup Iteration   1: 4.209 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.218 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.006 ms/op
Iteration   1: 3.019 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.892 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  6.940 ms/op
                 createUser·p0.9999: 20.788 ms/op
                 createUser·p1.00:   21.135 ms/op

Iteration   2: 3.064 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.640 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  9.748 ms/op
                 createUser·p0.9999: 15.761 ms/op
                 createUser·p1.00:   15.974 ms/op

Iteration   3: 3.090 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.751 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  10.551 ms/op
                 createUser·p0.9999: 18.928 ms/op
                 createUser·p1.00:   19.431 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313776
  mean =      3.057 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26945 
    [ 2.500,  5.000) = 285459 
    [ 5.000,  7.500) = 901 
    [ 7.500, 10.000) = 184 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.640 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      9.261 ms/op
     p(99.9900) =     20.050 ms/op
     p(99.9990) =     21.004 ms/op
     p(99.9999) =     21.135 ms/op
    p(100.0000) =     21.135 ms/op


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
# Warmup Iteration   1: 3.970 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.014 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.900 ±(99.9%) 0.005 ms/op
Iteration   1: 2.900 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.760 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.121 ms/op
                 existUser·p0.999:  5.408 ms/op
                 existUser·p0.9999: 12.401 ms/op
                 existUser·p1.00:   12.599 ms/op

Iteration   2: 2.876 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.863 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.170 ms/op
                 existUser·p0.95:   3.293 ms/op
                 existUser·p0.99:   3.924 ms/op
                 existUser·p0.999:  5.792 ms/op
                 existUser·p0.9999: 14.185 ms/op
                 existUser·p1.00:   16.007 ms/op

Iteration   3: 2.896 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.837 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   3.998 ms/op
                 existUser·p0.999:  6.632 ms/op
                 existUser·p0.9999: 14.401 ms/op
                 existUser·p1.00:   14.959 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331919
  mean =      2.890 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 582 
    [ 1.250,  2.500) = 35781 
    [ 2.500,  3.750) = 288458 
    [ 3.750,  5.000) = 6435 
    [ 5.000,  6.250) = 371 
    [ 6.250,  7.500) = 132 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.760 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.293 ms/op
     p(95.0000) =      3.527 ms/op
     p(99.0000) =      4.006 ms/op
     p(99.9000) =      6.078 ms/op
     p(99.9900) =     14.185 ms/op
     p(99.9990) =     14.883 ms/op
     p(99.9999) =     16.007 ms/op
    p(100.0000) =     16.007 ms/op


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
# Warmup Iteration   1: 4.250 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.006 ms/op
Iteration   1: 3.044 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.833 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  7.168 ms/op
                 getUser·p0.9999: 19.153 ms/op
                 getUser·p1.00:   19.628 ms/op

Iteration   2: 2.984 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.953 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  6.676 ms/op
                 getUser·p0.9999: 16.344 ms/op
                 getUser·p1.00:   16.728 ms/op

Iteration   3: 3.025 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.795 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.647 ms/op
                 getUser·p0.99:   4.145 ms/op
                 getUser·p0.999:  6.206 ms/op
                 getUser·p0.9999: 15.956 ms/op
                 getUser·p1.00:   16.400 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317936
  mean =      3.017 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 576 
    [ 1.250,  2.500) = 22632 
    [ 2.500,  3.750) = 278656 
    [ 3.750,  5.000) = 15030 
    [ 5.000,  6.250) = 613 
    [ 6.250,  7.500) = 236 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.795 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      6.545 ms/op
     p(99.9900) =     18.560 ms/op
     p(99.9990) =     19.452 ms/op
     p(99.9999) =     19.628 ms/op
    p(100.0000) =     19.628 ms/op


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
# Warmup Iteration   1: 5.265 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.083 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.024 ±(99.9%) 0.011 ms/op
Iteration   1: 3.904 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.327 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  12.972 ms/op
                 listUser·p0.9999: 22.020 ms/op
                 listUser·p1.00:   22.479 ms/op

Iteration   2: 4.029 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.891 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.757 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  15.540 ms/op
                 listUser·p0.9999: 23.334 ms/op
                 listUser·p1.00:   24.543 ms/op

Iteration   3: 3.940 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.016 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  16.777 ms/op
                 listUser·p0.9999: 21.841 ms/op
                 listUser·p1.00:   22.807 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242732
  mean =      3.957 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2945 
    [ 2.500,  5.000) = 218513 
    [ 5.000,  7.500) = 20088 
    [ 7.500, 10.000) = 739 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.891 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.866 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     15.385 ms/op
     p(99.9900) =     22.807 ms/op
     p(99.9990) =     23.982 ms/op
     p(99.9999) =     24.543 ms/op
    p(100.0000) =     24.543 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.411 ± 2.451  ops/ms
ClientGrpc.existUser                       thrpt       3  11.095 ± 3.030  ops/ms
ClientGrpc.getUser                         thrpt       3  10.688 ± 1.049  ops/ms
ClientGrpc.listUser                        thrpt       3   8.072 ± 0.759  ops/ms
ClientGrpc.createUser                       avgt       3   2.992 ± 0.591   ms/op
ClientGrpc.existUser                        avgt       3   2.855 ± 0.512   ms/op
ClientGrpc.getUser                          avgt       3   3.000 ± 0.579   ms/op
ClientGrpc.listUser                         avgt       3   3.886 ± 0.855   ms/op
ClientGrpc.createUser                     sample  313776   3.057 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.640           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.023           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.629           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.813           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.415           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.261           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.050           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.135           ms/op
ClientGrpc.existUser                      sample  331919   2.890 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.760           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.293           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.527           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.006           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.078           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.185           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.007           ms/op
ClientGrpc.getUser                        sample  317936   3.017 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.795           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.990           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.523           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.752           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.325           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.545           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.560           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.628           ms/op
ClientGrpc.listUser                       sample  242732   3.957 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.891           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.813           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.866           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.612           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.906           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.385           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.807           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.543           ms/op
