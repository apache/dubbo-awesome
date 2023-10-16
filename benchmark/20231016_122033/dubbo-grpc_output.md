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
# Warmup Iteration   1: 2.187 ops/ms
# Warmup Iteration   2: 5.301 ops/ms
# Warmup Iteration   3: 7.121 ops/ms
Iteration   1: 7.499 ops/ms
Iteration   2: 7.703 ops/ms
Iteration   3: 7.800 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.667 ±(99.9%) 2.806 ops/ms [Average]
  (min, avg, max) = (7.499, 7.667, 7.800), stdev = 0.154
  CI (99.9%): [4.862, 10.473] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.677 ops/ms
# Warmup Iteration   2: 7.490 ops/ms
# Warmup Iteration   3: 7.699 ops/ms
Iteration   1: 8.057 ops/ms
Iteration   2: 8.187 ops/ms
Iteration   3: 8.007 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.084 ±(99.9%) 1.694 ops/ms [Average]
  (min, avg, max) = (8.007, 8.084, 8.187), stdev = 0.093
  CI (99.9%): [6.390, 9.777] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.165 ops/ms
# Warmup Iteration   2: 6.727 ops/ms
# Warmup Iteration   3: 7.100 ops/ms
Iteration   1: 7.367 ops/ms
Iteration   2: 7.557 ops/ms
Iteration   3: 7.416 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.446 ±(99.9%) 1.801 ops/ms [Average]
  (min, avg, max) = (7.367, 7.446, 7.557), stdev = 0.099
  CI (99.9%): [5.646, 9.247] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.784 ops/ms
# Warmup Iteration   2: 5.296 ops/ms
# Warmup Iteration   3: 5.776 ops/ms
Iteration   1: 5.755 ops/ms
Iteration   2: 5.735 ops/ms
Iteration   3: 5.742 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.744 ±(99.9%) 0.183 ops/ms [Average]
  (min, avg, max) = (5.735, 5.744, 5.755), stdev = 0.010
  CI (99.9%): [5.560, 5.927] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.879 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.690 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.397 ±(99.9%) 0.009 ms/op
Iteration   1: 4.356 ±(99.9%) 0.007 ms/op
Iteration   2: 4.228 ±(99.9%) 0.003 ms/op
Iteration   3: 4.211 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.265 ±(99.9%) 1.451 ms/op [Average]
  (min, avg, max) = (4.211, 4.265, 4.356), stdev = 0.080
  CI (99.9%): [2.814, 5.716] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 5.989 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.206 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.030 ±(99.9%) 0.005 ms/op
Iteration   1: 4.038 ±(99.9%) 0.004 ms/op
Iteration   2: 3.978 ±(99.9%) 0.004 ms/op
Iteration   3: 3.968 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.995 ±(99.9%) 0.690 ms/op [Average]
  (min, avg, max) = (3.968, 3.995, 4.038), stdev = 0.038
  CI (99.9%): [3.305, 4.684] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.075 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.728 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.209 ±(99.9%) 0.005 ms/op
Iteration   1: 4.350 ±(99.9%) 0.005 ms/op
Iteration   2: 4.229 ±(99.9%) 0.009 ms/op
Iteration   3: 4.233 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.271 ±(99.9%) 1.255 ms/op [Average]
  (min, avg, max) = (4.229, 4.271, 4.350), stdev = 0.069
  CI (99.9%): [3.015, 5.526] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.454 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 5.833 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 5.525 ±(99.9%) 0.018 ms/op
Iteration   1: 5.648 ±(99.9%) 0.028 ms/op
Iteration   2: 5.591 ±(99.9%) 0.017 ms/op
Iteration   3: 5.648 ±(99.9%) 0.034 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.629 ±(99.9%) 0.603 ms/op [Average]
  (min, avg, max) = (5.591, 5.629, 5.648), stdev = 0.033
  CI (99.9%): [5.026, 6.232] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.891 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 4.697 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.411 ±(99.9%) 0.015 ms/op
Iteration   1: 4.381 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.038 ms/op
                 createUser·p0.50:   4.211 ms/op
                 createUser·p0.90:   5.612 ms/op
                 createUser·p0.95:   6.234 ms/op
                 createUser·p0.99:   8.602 ms/op
                 createUser·p0.999:  17.859 ms/op
                 createUser·p0.9999: 33.525 ms/op
                 createUser·p1.00:   36.569 ms/op

Iteration   2: 4.325 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.212 ms/op
                 createUser·p0.50:   4.157 ms/op
                 createUser·p0.90:   5.489 ms/op
                 createUser·p0.95:   6.054 ms/op
                 createUser·p0.99:   8.225 ms/op
                 createUser·p0.999:  14.337 ms/op
                 createUser·p0.9999: 24.347 ms/op
                 createUser·p1.00:   24.904 ms/op

Iteration   3: 4.314 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.744 ms/op
                 createUser·p0.50:   4.125 ms/op
                 createUser·p0.90:   5.530 ms/op
                 createUser·p0.95:   6.078 ms/op
                 createUser·p0.99:   8.503 ms/op
                 createUser·p0.999:  21.496 ms/op
                 createUser·p0.9999: 30.283 ms/op
                 createUser·p1.00:   30.638 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 221073
  mean =      4.340 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5560 
    [ 2.500,  5.000) = 172726 
    [ 5.000,  7.500) = 39255 
    [ 7.500, 10.000) = 2339 
    [10.000, 12.500) = 663 
    [12.500, 15.000) = 239 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      4.162 ms/op
     p(90.0000) =      5.538 ms/op
     p(95.0000) =      6.119 ms/op
     p(99.0000) =      8.438 ms/op
     p(99.9000) =     17.367 ms/op
     p(99.9900) =     32.692 ms/op
     p(99.9990) =     36.027 ms/op
     p(99.9999) =     36.569 ms/op
    p(100.0000) =     36.569 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.323 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.426 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.956 ±(99.9%) 0.013 ms/op
Iteration   1: 4.014 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.735 ms/op
                 existUser·p0.50:   3.912 ms/op
                 existUser·p0.90:   5.161 ms/op
                 existUser·p0.95:   5.710 ms/op
                 existUser·p0.99:   7.766 ms/op
                 existUser·p0.999:  12.522 ms/op
                 existUser·p0.9999: 21.332 ms/op
                 existUser·p1.00:   21.332 ms/op

Iteration   2: 3.934 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.785 ms/op
                 existUser·p0.50:   3.809 ms/op
                 existUser·p0.90:   4.882 ms/op
                 existUser·p0.95:   5.382 ms/op
                 existUser·p0.99:   7.340 ms/op
                 existUser·p0.999:  13.399 ms/op
                 existUser·p0.9999: 36.996 ms/op
                 existUser·p1.00:   38.666 ms/op

Iteration   3: 4.002 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.656 ms/op
                 existUser·p0.50:   3.867 ms/op
                 existUser·p0.90:   4.989 ms/op
                 existUser·p0.95:   5.472 ms/op
                 existUser·p0.99:   7.342 ms/op
                 existUser·p0.999:  12.288 ms/op
                 existUser·p0.9999: 34.997 ms/op
                 existUser·p1.00:   35.324 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 241012
  mean =      3.983 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10445 
    [ 2.500,  5.000) = 206190 
    [ 5.000,  7.500) = 21943 
    [ 7.500, 10.000) = 1757 
    [10.000, 12.500) = 420 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 35 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.656 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      5.014 ms/op
     p(95.0000) =      5.530 ms/op
     p(99.0000) =      7.512 ms/op
     p(99.9000) =     12.550 ms/op
     p(99.9900) =     34.996 ms/op
     p(99.9990) =     38.574 ms/op
     p(99.9999) =     38.666 ms/op
    p(100.0000) =     38.666 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.342 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 4.766 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.437 ±(99.9%) 0.015 ms/op
Iteration   1: 4.370 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.959 ms/op
                 getUser·p0.50:   4.194 ms/op
                 getUser·p0.90:   5.595 ms/op
                 getUser·p0.95:   6.234 ms/op
                 getUser·p0.99:   8.552 ms/op
                 getUser·p0.999:  14.390 ms/op
                 getUser·p0.9999: 30.638 ms/op
                 getUser·p1.00:   31.392 ms/op

Iteration   2: 4.337 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.325 ms/op
                 getUser·p0.50:   4.194 ms/op
                 getUser·p0.90:   5.399 ms/op
                 getUser·p0.95:   5.898 ms/op
                 getUser·p0.99:   8.004 ms/op
                 getUser·p0.999:  16.056 ms/op
                 getUser·p0.9999: 27.283 ms/op
                 getUser·p1.00:   28.148 ms/op

Iteration   3: 4.417 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.934 ms/op
                 getUser·p0.50:   4.227 ms/op
                 getUser·p0.90:   5.505 ms/op
                 getUser·p0.95:   6.054 ms/op
                 getUser·p0.99:   9.139 ms/op
                 getUser·p0.999:  21.479 ms/op
                 getUser·p0.9999: 22.847 ms/op
                 getUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 219467
  mean =      4.374 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3756 
    [ 2.500,  5.000) = 173289 
    [ 5.000,  7.500) = 38884 
    [ 7.500, 10.000) = 2272 
    [10.000, 12.500) = 704 
    [12.500, 15.000) = 265 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.934 ms/op
     p(50.0000) =      4.202 ms/op
     p(90.0000) =      5.497 ms/op
     p(95.0000) =      6.062 ms/op
     p(99.0000) =      8.569 ms/op
     p(99.9000) =     16.187 ms/op
     p(99.9900) =     30.573 ms/op
     p(99.9990) =     31.059 ms/op
     p(99.9999) =     31.392 ms/op
    p(100.0000) =     31.392 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.312 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 5.956 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.659 ±(99.9%) 0.026 ms/op
Iteration   1: 5.640 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.722 ms/op
                 listUser·p0.50:   5.243 ms/op
                 listUser·p0.90:   7.758 ms/op
                 listUser·p0.95:   8.782 ms/op
                 listUser·p0.99:   11.337 ms/op
                 listUser·p0.999:  28.256 ms/op
                 listUser·p0.9999: 34.728 ms/op
                 listUser·p1.00:   36.831 ms/op

Iteration   2: 5.802 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   1.593 ms/op
                 listUser·p0.50:   5.308 ms/op
                 listUser·p0.90:   8.012 ms/op
                 listUser·p0.95:   9.159 ms/op
                 listUser·p0.99:   12.370 ms/op
                 listUser·p0.999:  31.521 ms/op
                 listUser·p0.9999: 46.724 ms/op
                 listUser·p1.00:   47.251 ms/op

Iteration   3: 5.803 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   1.581 ms/op
                 listUser·p0.50:   5.317 ms/op
                 listUser·p0.90:   8.110 ms/op
                 listUser·p0.95:   9.273 ms/op
                 listUser·p0.99:   12.638 ms/op
                 listUser·p0.999:  26.756 ms/op
                 listUser·p0.9999: 54.361 ms/op
                 listUser·p1.00:   54.788 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 167141
  mean =      5.747 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 66809 
    [ 5.000, 10.000) = 95502 
    [10.000, 15.000) = 4130 
    [15.000, 20.000) = 332 
    [20.000, 25.000) = 82 
    [25.000, 30.000) = 153 
    [30.000, 35.000) = 60 
    [35.000, 40.000) = 5 
    [40.000, 45.000) = 6 
    [45.000, 50.000) = 46 
    [50.000, 55.000) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.581 ms/op
     p(50.0000) =      5.284 ms/op
     p(90.0000) =      7.954 ms/op
     p(95.0000) =      9.077 ms/op
     p(99.0000) =     12.075 ms/op
     p(99.9000) =     29.388 ms/op
     p(99.9900) =     50.585 ms/op
     p(99.9990) =     54.612 ms/op
     p(99.9999) =     54.788 ms/op
    p(100.0000) =     54.788 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.667 ± 2.806  ops/ms
ClientGrpc.existUser                       thrpt       3   8.084 ± 1.694  ops/ms
ClientGrpc.getUser                         thrpt       3   7.446 ± 1.801  ops/ms
ClientGrpc.listUser                        thrpt       3   5.744 ± 0.183  ops/ms
ClientGrpc.createUser                       avgt       3   4.265 ± 1.451   ms/op
ClientGrpc.existUser                        avgt       3   3.995 ± 0.690   ms/op
ClientGrpc.getUser                          avgt       3   4.271 ± 1.255   ms/op
ClientGrpc.listUser                         avgt       3   5.629 ± 0.603   ms/op
ClientGrpc.createUser                     sample  221073   4.340 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.744           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.162           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.538           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.119           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.438           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          17.367           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          32.692           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          36.569           ms/op
ClientGrpc.existUser                      sample  241012   3.983 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.656           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.858           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.014           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.530           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.512           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.550           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          34.996           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          38.666           ms/op
ClientGrpc.getUser                        sample  219467   4.374 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.934           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.202           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.497           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.062           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.569           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          16.187           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          30.573           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          31.392           ms/op
ClientGrpc.listUser                       sample  167141   5.747 ± 0.017   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.581           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.284           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.954           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.077           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.075           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          29.388           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          50.585           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          54.788           ms/op
