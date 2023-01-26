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
# Warmup Iteration   1: 2.640 ops/ms
# Warmup Iteration   2: 6.410 ops/ms
# Warmup Iteration   3: 7.906 ops/ms
Iteration   1: 8.035 ops/ms
Iteration   2: 8.260 ops/ms
Iteration   3: 8.154 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.150 ±(99.9%) 2.049 ops/ms [Average]
  (min, avg, max) = (8.035, 8.150, 8.260), stdev = 0.112
  CI (99.9%): [6.100, 10.199] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.654 ops/ms
# Warmup Iteration   2: 7.885 ops/ms
# Warmup Iteration   3: 8.198 ops/ms
Iteration   1: 8.382 ops/ms
Iteration   2: 8.153 ops/ms
Iteration   3: 8.515 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.350 ±(99.9%) 3.339 ops/ms [Average]
  (min, avg, max) = (8.153, 8.350, 8.515), stdev = 0.183
  CI (99.9%): [5.010, 11.689] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.055 ops/ms
# Warmup Iteration   2: 7.589 ops/ms
# Warmup Iteration   3: 7.966 ops/ms
Iteration   1: 7.861 ops/ms
Iteration   2: 8.013 ops/ms
Iteration   3: 8.118 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.997 ±(99.9%) 2.357 ops/ms [Average]
  (min, avg, max) = (7.861, 7.997, 8.118), stdev = 0.129
  CI (99.9%): [5.640, 10.354] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.760 ops/ms
# Warmup Iteration   2: 5.931 ops/ms
# Warmup Iteration   3: 6.405 ops/ms
Iteration   1: 6.463 ops/ms
Iteration   2: 6.465 ops/ms
Iteration   3: 6.640 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.523 ±(99.9%) 1.850 ops/ms [Average]
  (min, avg, max) = (6.463, 6.523, 6.640), stdev = 0.101
  CI (99.9%): [4.673, 8.373] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.755 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.237 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.907 ±(99.9%) 0.003 ms/op
Iteration   1: 3.907 ±(99.9%) 0.003 ms/op
Iteration   2: 4.087 ±(99.9%) 0.003 ms/op
Iteration   3: 4.060 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.018 ±(99.9%) 1.771 ms/op [Average]
  (min, avg, max) = (3.907, 4.018, 4.087), stdev = 0.097
  CI (99.9%): [2.247, 5.789] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.669 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.209 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.079 ±(99.9%) 0.002 ms/op
Iteration   1: 3.976 ±(99.9%) 0.002 ms/op
Iteration   2: 3.918 ±(99.9%) 0.003 ms/op
Iteration   3: 3.925 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.940 ±(99.9%) 0.578 ms/op [Average]
  (min, avg, max) = (3.918, 3.940, 3.976), stdev = 0.032
  CI (99.9%): [3.362, 4.517] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.448 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.336 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.171 ±(99.9%) 0.002 ms/op
Iteration   1: 4.132 ±(99.9%) 0.003 ms/op
Iteration   2: 4.127 ±(99.9%) 0.002 ms/op
Iteration   3: 4.118 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.126 ±(99.9%) 0.128 ms/op [Average]
  (min, avg, max) = (4.118, 4.126, 4.132), stdev = 0.007
  CI (99.9%): [3.997, 4.254] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 7.349 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 5.708 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.315 ±(99.9%) 0.024 ms/op
Iteration   1: 4.930 ±(99.9%) 0.016 ms/op
Iteration   2: 4.991 ±(99.9%) 0.018 ms/op
Iteration   3: 5.022 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.981 ±(99.9%) 0.859 ms/op [Average]
  (min, avg, max) = (4.930, 4.981, 5.022), stdev = 0.047
  CI (99.9%): [4.122, 5.840] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.718 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.181 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.858 ±(99.9%) 0.010 ms/op
Iteration   1: 4.018 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.124 ms/op
                 createUser·p0.50:   3.924 ms/op
                 createUser·p0.90:   5.046 ms/op
                 createUser·p0.95:   5.431 ms/op
                 createUser·p0.99:   7.136 ms/op
                 createUser·p0.999:  12.266 ms/op
                 createUser·p0.9999: 19.598 ms/op
                 createUser·p1.00:   20.120 ms/op

Iteration   2: 3.850 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.004 ms/op
                 createUser·p0.50:   3.756 ms/op
                 createUser·p0.90:   4.801 ms/op
                 createUser·p0.95:   5.186 ms/op
                 createUser·p0.99:   6.038 ms/op
                 createUser·p0.999:  14.941 ms/op
                 createUser·p0.9999: 21.725 ms/op
                 createUser·p1.00:   22.249 ms/op

Iteration   3: 4.070 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.838 ms/op
                 createUser·p0.50:   3.998 ms/op
                 createUser·p0.90:   5.128 ms/op
                 createUser·p0.95:   5.423 ms/op
                 createUser·p0.99:   6.152 ms/op
                 createUser·p0.999:  8.767 ms/op
                 createUser·p0.9999: 33.554 ms/op
                 createUser·p1.00:   35.258 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 241237
  mean =      3.977 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3655 
    [ 2.500,  5.000) = 212890 
    [ 5.000,  7.500) = 23522 
    [ 7.500, 10.000) = 822 
    [10.000, 12.500) = 148 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.838 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      5.014 ms/op
     p(95.0000) =      5.358 ms/op
     p(99.0000) =      6.387 ms/op
     p(99.9000) =     11.678 ms/op
     p(99.9900) =     32.395 ms/op
     p(99.9990) =     35.204 ms/op
     p(99.9999) =     35.258 ms/op
    p(100.0000) =     35.258 ms/op


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
# Warmup Iteration   1: 5.264 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.064 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.950 ±(99.9%) 0.010 ms/op
Iteration   1: 3.845 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.035 ms/op
                 existUser·p0.50:   3.748 ms/op
                 existUser·p0.90:   4.792 ms/op
                 existUser·p0.95:   5.145 ms/op
                 existUser·p0.99:   6.381 ms/op
                 existUser·p0.999:  11.776 ms/op
                 existUser·p0.9999: 14.790 ms/op
                 existUser·p1.00:   15.925 ms/op

Iteration   2: 3.966 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.032 ms/op
                 existUser·p0.50:   3.871 ms/op
                 existUser·p0.90:   5.030 ms/op
                 existUser·p0.95:   5.374 ms/op
                 existUser·p0.99:   6.865 ms/op
                 existUser·p0.999:  10.978 ms/op
                 existUser·p0.9999: 20.572 ms/op
                 existUser·p1.00:   23.265 ms/op

Iteration   3: 3.926 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.884 ms/op
                 existUser·p0.50:   3.867 ms/op
                 existUser·p0.90:   4.989 ms/op
                 existUser·p0.95:   5.305 ms/op
                 existUser·p0.99:   6.521 ms/op
                 existUser·p0.999:  12.576 ms/op
                 existUser·p0.9999: 27.160 ms/op
                 existUser·p1.00:   27.492 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 245448
  mean =      3.911 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6547 
    [ 2.500,  5.000) = 216950 
    [ 5.000,  7.500) = 20558 
    [ 7.500, 10.000) = 978 
    [10.000, 12.500) = 219 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.884 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      4.948 ms/op
     p(95.0000) =      5.284 ms/op
     p(99.0000) =      6.595 ms/op
     p(99.9000) =     11.796 ms/op
     p(99.9900) =     25.115 ms/op
     p(99.9990) =     27.361 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.685 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.341 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.095 ±(99.9%) 0.012 ms/op
Iteration   1: 4.007 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.571 ms/op
                 getUser·p0.50:   3.908 ms/op
                 getUser·p0.90:   5.071 ms/op
                 getUser·p0.95:   5.489 ms/op
                 getUser·p0.99:   7.356 ms/op
                 getUser·p0.999:  13.666 ms/op
                 getUser·p0.9999: 17.269 ms/op
                 getUser·p1.00:   17.760 ms/op

Iteration   2: 4.087 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.171 ms/op
                 getUser·p0.50:   4.022 ms/op
                 getUser·p0.90:   5.169 ms/op
                 getUser·p0.95:   5.497 ms/op
                 getUser·p0.99:   6.357 ms/op
                 getUser·p0.999:  11.064 ms/op
                 getUser·p0.9999: 17.203 ms/op
                 getUser·p1.00:   19.300 ms/op

Iteration   3: 4.024 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.200 ms/op
                 getUser·p0.50:   3.924 ms/op
                 getUser·p0.90:   5.071 ms/op
                 getUser·p0.95:   5.415 ms/op
                 getUser·p0.99:   6.283 ms/op
                 getUser·p0.999:  8.707 ms/op
                 getUser·p0.9999: 20.972 ms/op
                 getUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 237835
  mean =      4.039 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6213 
    [ 2.500,  5.000) = 202831 
    [ 5.000,  7.500) = 27445 
    [ 7.500, 10.000) = 946 
    [10.000, 12.500) = 229 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.571 ms/op
     p(50.0000) =      3.949 ms/op
     p(90.0000) =      5.112 ms/op
     p(95.0000) =      5.472 ms/op
     p(99.0000) =      6.586 ms/op
     p(99.9000) =     11.258 ms/op
     p(99.9900) =     20.035 ms/op
     p(99.9990) =     21.201 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


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
# Warmup Iteration   1: 7.499 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 5.428 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 5.314 ±(99.9%) 0.018 ms/op
Iteration   1: 5.018 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.227 ms/op
                 listUser·p0.50:   4.841 ms/op
                 listUser·p0.90:   6.260 ms/op
                 listUser·p0.95:   7.102 ms/op
                 listUser·p0.99:   8.978 ms/op
                 listUser·p0.999:  14.045 ms/op
                 listUser·p0.9999: 19.124 ms/op
                 listUser·p1.00:   19.300 ms/op

Iteration   2: 5.033 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.655 ms/op
                 listUser·p0.50:   4.825 ms/op
                 listUser·p0.90:   6.341 ms/op
                 listUser·p0.95:   7.184 ms/op
                 listUser·p0.99:   9.322 ms/op
                 listUser·p0.999:  18.035 ms/op
                 listUser·p0.9999: 22.893 ms/op
                 listUser·p1.00:   23.331 ms/op

Iteration   3: 5.030 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.663 ms/op
                 listUser·p0.50:   4.817 ms/op
                 listUser·p0.90:   6.521 ms/op
                 listUser·p0.95:   7.299 ms/op
                 listUser·p0.99:   9.093 ms/op
                 listUser·p0.999:  22.493 ms/op
                 listUser·p0.9999: 27.513 ms/op
                 listUser·p1.00:   28.082 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 190952
  mean =      5.027 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 253 
    [ 2.500,  5.000) = 111707 
    [ 5.000,  7.500) = 71576 
    [ 7.500, 10.000) = 6422 
    [10.000, 12.500) = 604 
    [12.500, 15.000) = 156 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.227 ms/op
     p(50.0000) =      4.825 ms/op
     p(90.0000) =      6.382 ms/op
     p(95.0000) =      7.201 ms/op
     p(99.0000) =      9.126 ms/op
     p(99.9000) =     17.531 ms/op
     p(99.9900) =     25.392 ms/op
     p(99.9990) =     27.963 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.150 ± 2.049  ops/ms
ClientGrpc.existUser                       thrpt       3   8.350 ± 3.339  ops/ms
ClientGrpc.getUser                         thrpt       3   7.997 ± 2.357  ops/ms
ClientGrpc.listUser                        thrpt       3   6.523 ± 1.850  ops/ms
ClientGrpc.createUser                       avgt       3   4.018 ± 1.771   ms/op
ClientGrpc.existUser                        avgt       3   3.940 ± 0.578   ms/op
ClientGrpc.getUser                          avgt       3   4.126 ± 0.128   ms/op
ClientGrpc.listUser                         avgt       3   4.981 ± 0.859   ms/op
ClientGrpc.createUser                     sample  241237   3.977 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.838           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.879           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.014           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.358           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.387           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.678           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          32.395           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          35.258           ms/op
ClientGrpc.existUser                      sample  245448   3.911 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.884           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.826           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.948           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.284           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.595           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.796           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.115           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.492           ms/op
ClientGrpc.getUser                        sample  237835   4.039 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.571           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.949           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.112           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.472           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.586           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.258           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.035           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.332           ms/op
ClientGrpc.listUser                       sample  190952   5.027 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.227           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.825           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.382           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.201           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.126           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.531           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.392           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.082           ms/op
