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
# Warmup Iteration   1: 2.339 ops/ms
# Warmup Iteration   2: 6.074 ops/ms
# Warmup Iteration   3: 7.392 ops/ms
Iteration   1: 7.683 ops/ms
Iteration   2: 7.348 ops/ms
Iteration   3: 7.466 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.499 ±(99.9%) 3.093 ops/ms [Average]
  (min, avg, max) = (7.348, 7.499, 7.683), stdev = 0.170
  CI (99.9%): [4.406, 10.592] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.147 ops/ms
# Warmup Iteration   2: 7.095 ops/ms
# Warmup Iteration   3: 7.885 ops/ms
Iteration   1: 7.858 ops/ms
Iteration   2: 8.097 ops/ms
Iteration   3: 8.160 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.038 ±(99.9%) 2.905 ops/ms [Average]
  (min, avg, max) = (7.858, 8.038, 8.160), stdev = 0.159
  CI (99.9%): [5.133, 10.943] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.481 ops/ms
# Warmup Iteration   2: 7.205 ops/ms
# Warmup Iteration   3: 7.643 ops/ms
Iteration   1: 7.910 ops/ms
Iteration   2: 7.818 ops/ms
Iteration   3: 7.974 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.901 ±(99.9%) 1.427 ops/ms [Average]
  (min, avg, max) = (7.818, 7.901, 7.974), stdev = 0.078
  CI (99.9%): [6.474, 9.328] (assumes normal distribution)


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
# Warmup Iteration   1: 4.085 ops/ms
# Warmup Iteration   2: 5.509 ops/ms
# Warmup Iteration   3: 5.848 ops/ms
Iteration   1: 6.092 ops/ms
Iteration   2: 5.997 ops/ms
Iteration   3: 5.980 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.023 ±(99.9%) 1.096 ops/ms [Average]
  (min, avg, max) = (5.980, 6.023, 6.092), stdev = 0.060
  CI (99.9%): [4.927, 7.119] (assumes normal distribution)


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
# Warmup Iteration   1: 6.728 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.428 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.257 ±(99.9%) 0.004 ms/op
Iteration   1: 4.095 ±(99.9%) 0.005 ms/op
Iteration   2: 4.423 ±(99.9%) 0.003 ms/op
Iteration   3: 4.232 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.250 ±(99.9%) 3.005 ms/op [Average]
  (min, avg, max) = (4.095, 4.250, 4.423), stdev = 0.165
  CI (99.9%): [1.245, 7.256] (assumes normal distribution)


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
# Warmup Iteration   1: 5.889 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.220 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.048 ±(99.9%) 0.004 ms/op
Iteration   1: 4.000 ±(99.9%) 0.003 ms/op
Iteration   2: 3.937 ±(99.9%) 0.003 ms/op
Iteration   3: 4.098 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.012 ±(99.9%) 1.480 ms/op [Average]
  (min, avg, max) = (3.937, 4.012, 4.098), stdev = 0.081
  CI (99.9%): [2.532, 5.492] (assumes normal distribution)


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
# Warmup Iteration   1: 6.150 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.787 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.268 ±(99.9%) 0.010 ms/op
Iteration   1: 4.264 ±(99.9%) 0.004 ms/op
Iteration   2: 4.270 ±(99.9%) 0.004 ms/op
Iteration   3: 4.220 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.251 ±(99.9%) 0.496 ms/op [Average]
  (min, avg, max) = (4.220, 4.251, 4.270), stdev = 0.027
  CI (99.9%): [3.756, 4.747] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.590 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 5.914 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 5.427 ±(99.9%) 0.009 ms/op
Iteration   1: 5.406 ±(99.9%) 0.013 ms/op
Iteration   2: 5.336 ±(99.9%) 0.010 ms/op
Iteration   3: 5.226 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.323 ±(99.9%) 1.655 ms/op [Average]
  (min, avg, max) = (5.226, 5.323, 5.406), stdev = 0.091
  CI (99.9%): [3.668, 6.978] (assumes normal distribution)


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
# Warmup Iteration   1: 6.462 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.306 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.068 ±(99.9%) 0.013 ms/op
Iteration   1: 4.298 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.069 ms/op
                 createUser·p0.50:   4.178 ms/op
                 createUser·p0.90:   5.546 ms/op
                 createUser·p0.95:   5.997 ms/op
                 createUser·p0.99:   8.167 ms/op
                 createUser·p0.999:  14.236 ms/op
                 createUser·p0.9999: 23.302 ms/op
                 createUser·p1.00:   23.626 ms/op

Iteration   2: 4.295 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.971 ms/op
                 createUser·p0.50:   4.182 ms/op
                 createUser·p0.90:   5.415 ms/op
                 createUser·p0.95:   5.808 ms/op
                 createUser·p0.99:   7.931 ms/op
                 createUser·p0.999:  14.099 ms/op
                 createUser·p0.9999: 22.430 ms/op
                 createUser·p1.00:   23.953 ms/op

Iteration   3: 4.351 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.037 ms/op
                 createUser·p0.50:   4.235 ms/op
                 createUser·p0.90:   5.521 ms/op
                 createUser·p0.95:   5.923 ms/op
                 createUser·p0.99:   7.700 ms/op
                 createUser·p0.999:  13.598 ms/op
                 createUser·p0.9999: 24.607 ms/op
                 createUser·p1.00:   25.100 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 222338
  mean =      4.315 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4058 
    [ 2.500,  5.000) = 170653 
    [ 5.000,  7.500) = 44877 
    [ 7.500, 10.000) = 1929 
    [10.000, 12.500) = 457 
    [12.500, 15.000) = 168 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.971 ms/op
     p(50.0000) =      4.194 ms/op
     p(90.0000) =      5.489 ms/op
     p(95.0000) =      5.915 ms/op
     p(99.0000) =      7.963 ms/op
     p(99.9000) =     14.014 ms/op
     p(99.9900) =     23.651 ms/op
     p(99.9990) =     25.013 ms/op
     p(99.9999) =     25.100 ms/op
    p(100.0000) =     25.100 ms/op


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
# Warmup Iteration   1: 5.827 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.292 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.997 ±(99.9%) 0.010 ms/op
Iteration   1: 4.021 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.116 ms/op
                 existUser·p0.50:   3.912 ms/op
                 existUser·p0.90:   5.186 ms/op
                 existUser·p0.95:   5.673 ms/op
                 existUser·p0.99:   7.545 ms/op
                 existUser·p0.999:  13.198 ms/op
                 existUser·p0.9999: 17.829 ms/op
                 existUser·p1.00:   22.544 ms/op

Iteration   2: 3.977 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.949 ms/op
                 existUser·p0.50:   3.867 ms/op
                 existUser·p0.90:   5.112 ms/op
                 existUser·p0.95:   5.554 ms/op
                 existUser·p0.99:   7.755 ms/op
                 existUser·p0.999:  12.760 ms/op
                 existUser·p0.9999: 33.286 ms/op
                 existUser·p1.00:   33.948 ms/op

Iteration   3: 4.054 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.831 ms/op
                 existUser·p0.50:   3.949 ms/op
                 existUser·p0.90:   5.186 ms/op
                 existUser·p0.95:   5.554 ms/op
                 existUser·p0.99:   6.799 ms/op
                 existUser·p0.999:  12.487 ms/op
                 existUser·p0.9999: 20.447 ms/op
                 existUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 239209
  mean =      4.017 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9525 
    [ 2.500,  5.000) = 199001 
    [ 5.000,  7.500) = 28390 
    [ 7.500, 10.000) = 1573 
    [10.000, 12.500) = 456 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.831 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.587 ms/op
     p(99.0000) =      7.414 ms/op
     p(99.9000) =     12.858 ms/op
     p(99.9900) =     31.099 ms/op
     p(99.9990) =     33.882 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


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
# Warmup Iteration   1: 6.226 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.483 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.301 ±(99.9%) 0.013 ms/op
Iteration   1: 4.202 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.112 ms/op
                 getUser·p0.50:   4.108 ms/op
                 getUser·p0.90:   5.358 ms/op
                 getUser·p0.95:   5.784 ms/op
                 getUser·p0.99:   7.545 ms/op
                 getUser·p0.999:  12.692 ms/op
                 getUser·p0.9999: 16.655 ms/op
                 getUser·p1.00:   17.433 ms/op

Iteration   2: 4.347 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.114 ms/op
                 getUser·p0.50:   4.227 ms/op
                 getUser·p0.90:   5.546 ms/op
                 getUser·p0.95:   5.939 ms/op
                 getUser·p0.99:   7.462 ms/op
                 getUser·p0.999:  13.074 ms/op
                 getUser·p0.9999: 20.872 ms/op
                 getUser·p1.00:   21.398 ms/op

Iteration   3: 4.223 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.712 ms/op
                 getUser·p0.50:   4.141 ms/op
                 getUser·p0.90:   5.317 ms/op
                 getUser·p0.95:   5.726 ms/op
                 getUser·p0.99:   7.078 ms/op
                 getUser·p0.999:  10.359 ms/op
                 getUser·p0.9999: 19.871 ms/op
                 getUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 225369
  mean =      4.256 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5288 
    [ 2.500,  5.000) = 177427 
    [ 5.000,  7.500) = 40619 
    [ 7.500, 10.000) = 1583 
    [10.000, 12.500) = 249 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.712 ms/op
     p(50.0000) =      4.157 ms/op
     p(90.0000) =      5.415 ms/op
     p(95.0000) =      5.825 ms/op
     p(99.0000) =      7.332 ms/op
     p(99.9000) =     12.118 ms/op
     p(99.9900) =     20.102 ms/op
     p(99.9990) =     21.307 ms/op
     p(99.9999) =     21.398 ms/op
    p(100.0000) =     21.398 ms/op


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
# Warmup Iteration   1: 7.559 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 5.935 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.544 ±(99.9%) 0.024 ms/op
Iteration   1: 5.549 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.286 ms/op
                 listUser·p0.50:   5.202 ms/op
                 listUser·p0.90:   7.668 ms/op
                 listUser·p0.95:   8.487 ms/op
                 listUser·p0.99:   10.682 ms/op
                 listUser·p0.999:  17.793 ms/op
                 listUser·p0.9999: 21.838 ms/op
                 listUser·p1.00:   23.036 ms/op

Iteration   2: 5.358 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.331 ms/op
                 listUser·p0.50:   4.964 ms/op
                 listUser·p0.90:   7.496 ms/op
                 listUser·p0.95:   8.421 ms/op
                 listUser·p0.99:   10.571 ms/op
                 listUser·p0.999:  27.851 ms/op
                 listUser·p0.9999: 31.315 ms/op
                 listUser·p1.00:   37.028 ms/op

Iteration   3: 5.539 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.491 ms/op
                 listUser·p0.50:   5.169 ms/op
                 listUser·p0.90:   7.569 ms/op
                 listUser·p0.95:   8.503 ms/op
                 listUser·p0.99:   10.666 ms/op
                 listUser·p0.999:  23.925 ms/op
                 listUser·p0.9999: 33.353 ms/op
                 listUser·p1.00:   36.635 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 175261
  mean =      5.481 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 588 
    [ 2.500,  5.000) = 79972 
    [ 5.000,  7.500) = 76096 
    [ 7.500, 10.000) = 16021 
    [10.000, 12.500) = 1847 
    [12.500, 15.000) = 280 
    [15.000, 17.500) = 159 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.286 ms/op
     p(50.0000) =      5.112 ms/op
     p(90.0000) =      7.578 ms/op
     p(95.0000) =      8.471 ms/op
     p(99.0000) =     10.633 ms/op
     p(99.9000) =     22.739 ms/op
     p(99.9900) =     32.489 ms/op
     p(99.9990) =     36.732 ms/op
     p(99.9999) =     37.028 ms/op
    p(100.0000) =     37.028 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.499 ± 3.093  ops/ms
ClientGrpc.existUser                       thrpt       3   8.038 ± 2.905  ops/ms
ClientGrpc.getUser                         thrpt       3   7.901 ± 1.427  ops/ms
ClientGrpc.listUser                        thrpt       3   6.023 ± 1.096  ops/ms
ClientGrpc.createUser                       avgt       3   4.250 ± 3.005   ms/op
ClientGrpc.existUser                        avgt       3   4.012 ± 1.480   ms/op
ClientGrpc.getUser                          avgt       3   4.251 ± 0.496   ms/op
ClientGrpc.listUser                         avgt       3   5.323 ± 1.655   ms/op
ClientGrpc.createUser                     sample  222338   4.315 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.971           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.194           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.489           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.915           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.963           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.014           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.651           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.100           ms/op
ClientGrpc.existUser                      sample  239209   4.017 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.831           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.908           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.161           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.587           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.414           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.858           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          31.099           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          33.948           ms/op
ClientGrpc.getUser                        sample  225369   4.256 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.712           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.157           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.415           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.825           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.332           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.118           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.102           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.398           ms/op
ClientGrpc.listUser                       sample  175261   5.481 ± 0.014   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.286           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.112           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.578           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.471           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.633           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          22.739           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.489           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          37.028           ms/op
