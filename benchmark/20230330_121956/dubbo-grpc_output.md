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
# Warmup Iteration   1: 2.259 ops/ms
# Warmup Iteration   2: 5.751 ops/ms
# Warmup Iteration   3: 7.358 ops/ms
Iteration   1: 7.731 ops/ms
Iteration   2: 7.655 ops/ms
Iteration   3: 7.829 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.738 ±(99.9%) 1.590 ops/ms [Average]
  (min, avg, max) = (7.655, 7.738, 7.829), stdev = 0.087
  CI (99.9%): [6.148, 9.328] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.933 ops/ms
# Warmup Iteration   2: 7.577 ops/ms
# Warmup Iteration   3: 8.457 ops/ms
Iteration   1: 8.706 ops/ms
Iteration   2: 8.384 ops/ms
Iteration   3: 8.458 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.516 ±(99.9%) 3.072 ops/ms [Average]
  (min, avg, max) = (8.384, 8.516, 8.706), stdev = 0.168
  CI (99.9%): [5.444, 11.587] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.798 ops/ms
# Warmup Iteration   2: 7.181 ops/ms
# Warmup Iteration   3: 7.587 ops/ms
Iteration   1: 7.686 ops/ms
Iteration   2: 7.814 ops/ms
Iteration   3: 7.657 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.719 ±(99.9%) 1.526 ops/ms [Average]
  (min, avg, max) = (7.657, 7.719, 7.814), stdev = 0.084
  CI (99.9%): [6.193, 9.245] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.760 ops/ms
# Warmup Iteration   2: 5.449 ops/ms
# Warmup Iteration   3: 5.833 ops/ms
Iteration   1: 5.846 ops/ms
Iteration   2: 5.921 ops/ms
Iteration   3: 5.831 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.866 ±(99.9%) 0.882 ops/ms [Average]
  (min, avg, max) = (5.831, 5.866, 5.921), stdev = 0.048
  CI (99.9%): [4.984, 6.748] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.848 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.366 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.304 ±(99.9%) 0.009 ms/op
Iteration   1: 4.180 ±(99.9%) 0.004 ms/op
Iteration   2: 4.131 ±(99.9%) 0.004 ms/op
Iteration   3: 4.074 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.128 ±(99.9%) 0.974 ms/op [Average]
  (min, avg, max) = (4.074, 4.128, 4.180), stdev = 0.053
  CI (99.9%): [3.155, 5.102] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.129 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.091 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.818 ±(99.9%) 0.013 ms/op
Iteration   1: 3.960 ±(99.9%) 0.006 ms/op
Iteration   2: 3.604 ±(99.9%) 0.003 ms/op
Iteration   3: 3.685 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.750 ±(99.9%) 3.399 ms/op [Average]
  (min, avg, max) = (3.604, 3.750, 3.960), stdev = 0.186
  CI (99.9%): [0.351, 7.149] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.232 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.600 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.499 ±(99.9%) 0.005 ms/op
Iteration   1: 4.161 ±(99.9%) 0.005 ms/op
Iteration   2: 4.015 ±(99.9%) 0.004 ms/op
Iteration   3: 4.081 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.086 ±(99.9%) 1.341 ms/op [Average]
  (min, avg, max) = (4.015, 4.086, 4.161), stdev = 0.074
  CI (99.9%): [2.745, 5.427] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.435 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 5.943 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.748 ±(99.9%) 0.010 ms/op
Iteration   1: 5.791 ±(99.9%) 0.017 ms/op
Iteration   2: 5.698 ±(99.9%) 0.013 ms/op
Iteration   3: 5.693 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.727 ±(99.9%) 1.008 ms/op [Average]
  (min, avg, max) = (5.693, 5.727, 5.791), stdev = 0.055
  CI (99.9%): [4.719, 6.735] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.495 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 5.169 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.692 ±(99.9%) 0.018 ms/op
Iteration   1: 4.515 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   0.873 ms/op
                 createUser·p0.50:   4.317 ms/op
                 createUser·p0.90:   5.718 ms/op
                 createUser·p0.95:   6.611 ms/op
                 createUser·p0.99:   10.273 ms/op
                 createUser·p0.999:  17.472 ms/op
                 createUser·p0.9999: 35.515 ms/op
                 createUser·p1.00:   35.848 ms/op

Iteration   2: 4.499 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   0.996 ms/op
                 createUser·p0.50:   4.301 ms/op
                 createUser·p0.90:   5.808 ms/op
                 createUser·p0.95:   6.472 ms/op
                 createUser·p0.99:   9.863 ms/op
                 createUser·p0.999:  17.957 ms/op
                 createUser·p0.9999: 20.338 ms/op
                 createUser·p1.00:   32.702 ms/op

Iteration   3: 4.575 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.116 ms/op
                 createUser·p0.50:   4.383 ms/op
                 createUser·p0.90:   5.956 ms/op
                 createUser·p0.95:   6.726 ms/op
                 createUser·p0.99:   11.125 ms/op
                 createUser·p0.999:  15.892 ms/op
                 createUser·p0.9999: 22.315 ms/op
                 createUser·p1.00:   25.199 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 211943
  mean =      4.529 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9094 
    [ 2.500,  5.000) = 151818 
    [ 5.000,  7.500) = 44543 
    [ 7.500, 10.000) = 3981 
    [10.000, 12.500) = 1575 
    [12.500, 15.000) = 529 
    [15.000, 17.500) = 217 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.873 ms/op
     p(50.0000) =      4.325 ms/op
     p(90.0000) =      5.841 ms/op
     p(95.0000) =      6.595 ms/op
     p(99.0000) =     10.420 ms/op
     p(99.9000) =     17.172 ms/op
     p(99.9900) =     34.459 ms/op
     p(99.9990) =     35.848 ms/op
     p(99.9999) =     35.848 ms/op
    p(100.0000) =     35.848 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.333 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.767 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.385 ±(99.9%) 0.017 ms/op
Iteration   1: 4.400 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.897 ms/op
                 existUser·p0.50:   4.194 ms/op
                 existUser·p0.90:   5.595 ms/op
                 existUser·p0.95:   6.250 ms/op
                 existUser·p0.99:   9.470 ms/op
                 existUser·p0.999:  14.320 ms/op
                 existUser·p0.9999: 22.321 ms/op
                 existUser·p1.00:   26.083 ms/op

Iteration   2: 4.154 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.890 ms/op
                 existUser·p0.50:   4.014 ms/op
                 existUser·p0.90:   5.243 ms/op
                 existUser·p0.95:   5.849 ms/op
                 existUser·p0.99:   9.378 ms/op
                 existUser·p0.999:  18.553 ms/op
                 existUser·p0.9999: 22.751 ms/op
                 existUser·p1.00:   23.200 ms/op

Iteration   3: 4.334 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.200 ms/op
                 existUser·p0.50:   4.125 ms/op
                 existUser·p0.90:   5.456 ms/op
                 existUser·p0.95:   6.087 ms/op
                 existUser·p0.99:   10.191 ms/op
                 existUser·p0.999:  15.780 ms/op
                 existUser·p0.9999: 24.302 ms/op
                 existUser·p1.00:   24.543 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 223397
  mean =      4.294 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7826 
    [ 2.500,  5.000) = 178377 
    [ 5.000,  7.500) = 32287 
    [ 7.500, 10.000) = 2976 
    [10.000, 12.500) = 1241 
    [12.500, 15.000) = 417 
    [15.000, 17.500) = 107 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.890 ms/op
     p(50.0000) =      4.108 ms/op
     p(90.0000) =      5.431 ms/op
     p(95.0000) =      6.078 ms/op
     p(99.0000) =      9.650 ms/op
     p(99.9000) =     15.820 ms/op
     p(99.9900) =     22.904 ms/op
     p(99.9990) =     24.536 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


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
# Warmup Iteration   1: 7.145 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 4.785 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.648 ±(99.9%) 0.019 ms/op
Iteration   1: 4.522 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.294 ms/op
                 getUser·p0.50:   4.334 ms/op
                 getUser·p0.90:   5.734 ms/op
                 getUser·p0.95:   6.308 ms/op
                 getUser·p0.99:   9.191 ms/op
                 getUser·p0.999:  15.066 ms/op
                 getUser·p0.9999: 19.268 ms/op
                 getUser·p1.00:   19.694 ms/op

Iteration   2: 4.454 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.212 ms/op
                 getUser·p0.50:   4.317 ms/op
                 getUser·p0.90:   5.710 ms/op
                 getUser·p0.95:   6.316 ms/op
                 getUser·p0.99:   9.388 ms/op
                 getUser·p0.999:  14.375 ms/op
                 getUser·p0.9999: 28.017 ms/op
                 getUser·p1.00:   28.115 ms/op

Iteration   3: 4.520 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.339 ms/op
                 getUser·p0.50:   4.325 ms/op
                 getUser·p0.90:   5.693 ms/op
                 getUser·p0.95:   6.283 ms/op
                 getUser·p0.99:   9.388 ms/op
                 getUser·p0.999:  15.908 ms/op
                 getUser·p0.9999: 23.023 ms/op
                 getUser·p1.00:   25.887 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 213358
  mean =      4.498 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5947 
    [ 2.500,  5.000) = 157254 
    [ 5.000,  7.500) = 45537 
    [ 7.500, 10.000) = 2996 
    [10.000, 12.500) = 1161 
    [12.500, 15.000) = 239 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.212 ms/op
     p(50.0000) =      4.325 ms/op
     p(90.0000) =      5.710 ms/op
     p(95.0000) =      6.308 ms/op
     p(99.0000) =      9.355 ms/op
     p(99.9000) =     15.383 ms/op
     p(99.9900) =     26.826 ms/op
     p(99.9990) =     28.078 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.908 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 6.243 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.766 ±(99.9%) 0.024 ms/op
Iteration   1: 5.929 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.552 ms/op
                 listUser·p0.50:   5.497 ms/op
                 listUser·p0.90:   8.217 ms/op
                 listUser·p0.95:   9.175 ms/op
                 listUser·p0.99:   12.386 ms/op
                 listUser·p0.999:  20.254 ms/op
                 listUser·p0.9999: 22.453 ms/op
                 listUser·p1.00:   32.113 ms/op

Iteration   2: 5.904 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.356 ms/op
                 listUser·p0.50:   5.423 ms/op
                 listUser·p0.90:   8.225 ms/op
                 listUser·p0.95:   9.486 ms/op
                 listUser·p0.99:   13.320 ms/op
                 listUser·p0.999:  21.168 ms/op
                 listUser·p0.9999: 26.362 ms/op
                 listUser·p1.00:   27.034 ms/op

Iteration   3: 5.871 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.303 ms/op
                 listUser·p0.50:   5.374 ms/op
                 listUser·p0.90:   8.233 ms/op
                 listUser·p0.95:   9.470 ms/op
                 listUser·p0.99:   12.993 ms/op
                 listUser·p0.999:  25.191 ms/op
                 listUser·p0.9999: 31.180 ms/op
                 listUser·p1.00:   31.556 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 162679
  mean =      5.901 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 295 
    [ 2.500,  5.000) = 54752 
    [ 5.000,  7.500) = 83343 
    [ 7.500, 10.000) = 18396 
    [10.000, 12.500) = 3906 
    [12.500, 15.000) = 1177 
    [15.000, 17.500) = 377 
    [17.500, 20.000) = 174 
    [20.000, 22.500) = 151 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.303 ms/op
     p(50.0000) =      5.431 ms/op
     p(90.0000) =      8.225 ms/op
     p(95.0000) =      9.372 ms/op
     p(99.0000) =     13.009 ms/op
     p(99.9000) =     21.529 ms/op
     p(99.9900) =     28.270 ms/op
     p(99.9990) =     31.763 ms/op
     p(99.9999) =     32.113 ms/op
    p(100.0000) =     32.113 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.738 ± 1.590  ops/ms
ClientGrpc.existUser                       thrpt       3   8.516 ± 3.072  ops/ms
ClientGrpc.getUser                         thrpt       3   7.719 ± 1.526  ops/ms
ClientGrpc.listUser                        thrpt       3   5.866 ± 0.882  ops/ms
ClientGrpc.createUser                       avgt       3   4.128 ± 0.974   ms/op
ClientGrpc.existUser                        avgt       3   3.750 ± 3.399   ms/op
ClientGrpc.getUser                          avgt       3   4.086 ± 1.341   ms/op
ClientGrpc.listUser                         avgt       3   5.727 ± 1.008   ms/op
ClientGrpc.createUser                     sample  211943   4.529 ± 0.011   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.873           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.325           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.841           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.595           ms/op
ClientGrpc.createUser:createUser·p0.99    sample          10.420           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          17.172           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          34.459           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          35.848           ms/op
ClientGrpc.existUser                      sample  223397   4.294 ± 0.009   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.890           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.108           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.431           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.078           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           9.650           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          15.820           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.904           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.083           ms/op
ClientGrpc.getUser                        sample  213358   4.498 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.212           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.325           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.710           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.308           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           9.355           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          15.383           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.826           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.115           ms/op
ClientGrpc.listUser                       sample  162679   5.901 ± 0.016   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.303           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.431           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.225           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.372           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          13.009           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          21.529           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.270           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.113           ms/op
