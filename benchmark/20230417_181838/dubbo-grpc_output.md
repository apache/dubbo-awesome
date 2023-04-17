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
# Warmup Iteration   1: 1.913 ops/ms
# Warmup Iteration   2: 4.581 ops/ms
# Warmup Iteration   3: 6.868 ops/ms
Iteration   1: 7.288 ops/ms
Iteration   2: 7.436 ops/ms
Iteration   3: 7.402 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.375 ±(99.9%) 1.416 ops/ms [Average]
  (min, avg, max) = (7.288, 7.375, 7.436), stdev = 0.078
  CI (99.9%): [5.959, 8.791] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.215 ops/ms
# Warmup Iteration   2: 7.059 ops/ms
# Warmup Iteration   3: 7.910 ops/ms
Iteration   1: 8.141 ops/ms
Iteration   2: 7.997 ops/ms
Iteration   3: 8.359 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.166 ±(99.9%) 3.328 ops/ms [Average]
  (min, avg, max) = (7.997, 8.166, 8.359), stdev = 0.182
  CI (99.9%): [4.838, 11.493] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.149 ops/ms
# Warmup Iteration   2: 6.845 ops/ms
# Warmup Iteration   3: 7.354 ops/ms
Iteration   1: 7.407 ops/ms
Iteration   2: 7.469 ops/ms
Iteration   3: 7.600 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.492 ±(99.9%) 1.799 ops/ms [Average]
  (min, avg, max) = (7.407, 7.492, 7.600), stdev = 0.099
  CI (99.9%): [5.693, 9.291] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.489 ops/ms
# Warmup Iteration   2: 5.143 ops/ms
# Warmup Iteration   3: 5.727 ops/ms
Iteration   1: 5.692 ops/ms
Iteration   2: 5.645 ops/ms
Iteration   3: 5.667 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.668 ±(99.9%) 0.429 ops/ms [Average]
  (min, avg, max) = (5.645, 5.668, 5.692), stdev = 0.024
  CI (99.9%): [5.239, 6.098] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.002 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.710 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.573 ±(99.9%) 0.029 ms/op
Iteration   1: 4.432 ±(99.9%) 0.005 ms/op
Iteration   2: 4.326 ±(99.9%) 0.003 ms/op
Iteration   3: 4.271 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.343 ±(99.9%) 1.490 ms/op [Average]
  (min, avg, max) = (4.271, 4.343, 4.432), stdev = 0.082
  CI (99.9%): [2.853, 5.833] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.493 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.273 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.970 ±(99.9%) 0.005 ms/op
Iteration   1: 3.971 ±(99.9%) 0.005 ms/op
Iteration   2: 4.067 ±(99.9%) 0.005 ms/op
Iteration   3: 4.100 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.046 ±(99.9%) 1.224 ms/op [Average]
  (min, avg, max) = (3.971, 4.046, 4.100), stdev = 0.067
  CI (99.9%): [2.822, 5.271] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.704 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.689 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.465 ±(99.9%) 0.007 ms/op
Iteration   1: 4.272 ±(99.9%) 0.006 ms/op
Iteration   2: 4.179 ±(99.9%) 0.006 ms/op
Iteration   3: 4.254 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.235 ±(99.9%) 0.903 ms/op [Average]
  (min, avg, max) = (4.179, 4.235, 4.272), stdev = 0.050
  CI (99.9%): [3.332, 5.139] (assumes normal distribution)


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
# Warmup Iteration   1: 8.645 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 5.862 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.504 ±(99.9%) 0.015 ms/op
Iteration   1: 5.381 ±(99.9%) 0.015 ms/op
Iteration   2: 5.458 ±(99.9%) 0.021 ms/op
Iteration   3: 5.342 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.394 ±(99.9%) 1.078 ms/op [Average]
  (min, avg, max) = (5.342, 5.394, 5.458), stdev = 0.059
  CI (99.9%): [4.316, 6.471] (assumes normal distribution)


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
# Warmup Iteration   1: 7.187 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 4.804 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.348 ±(99.9%) 0.015 ms/op
Iteration   1: 4.158 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.028 ms/op
                 createUser·p0.50:   3.977 ms/op
                 createUser·p0.90:   5.439 ms/op
                 createUser·p0.95:   6.210 ms/op
                 createUser·p0.99:   8.897 ms/op
                 createUser·p0.999:  12.254 ms/op
                 createUser·p0.9999: 23.537 ms/op
                 createUser·p1.00:   23.757 ms/op

Iteration   2: 4.355 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.037 ms/op
                 createUser·p0.50:   4.116 ms/op
                 createUser·p0.90:   5.587 ms/op
                 createUser·p0.95:   6.332 ms/op
                 createUser·p0.99:   9.290 ms/op
                 createUser·p0.999:  20.733 ms/op
                 createUser·p0.9999: 31.097 ms/op
                 createUser·p1.00:   31.130 ms/op

Iteration   3: 4.285 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.087 ms/op
                 createUser·p0.50:   4.104 ms/op
                 createUser·p0.90:   5.521 ms/op
                 createUser·p0.95:   6.160 ms/op
                 createUser·p0.99:   8.634 ms/op
                 createUser·p0.999:  14.222 ms/op
                 createUser·p0.9999: 20.727 ms/op
                 createUser·p1.00:   21.201 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 225106
  mean =      4.264 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7013 
    [ 2.500,  5.000) = 177636 
    [ 5.000,  7.500) = 35460 
    [ 7.500, 10.000) = 3837 
    [10.000, 12.500) = 677 
    [12.500, 15.000) = 296 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.028 ms/op
     p(50.0000) =      4.063 ms/op
     p(90.0000) =      5.521 ms/op
     p(95.0000) =      6.226 ms/op
     p(99.0000) =      8.946 ms/op
     p(99.9000) =     14.533 ms/op
     p(99.9900) =     28.523 ms/op
     p(99.9990) =     31.130 ms/op
     p(99.9999) =     31.130 ms/op
    p(100.0000) =     31.130 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.353 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.577 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.222 ±(99.9%) 0.019 ms/op
Iteration   1: 4.070 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.987 ms/op
                 existUser·p0.50:   3.863 ms/op
                 existUser·p0.90:   5.325 ms/op
                 existUser·p0.95:   6.144 ms/op
                 existUser·p0.99:   8.815 ms/op
                 existUser·p0.999:  12.288 ms/op
                 existUser·p0.9999: 16.085 ms/op
                 existUser·p1.00:   16.761 ms/op

Iteration   2: 4.027 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.887 ms/op
                 existUser·p0.50:   3.891 ms/op
                 existUser·p0.90:   5.087 ms/op
                 existUser·p0.95:   5.677 ms/op
                 existUser·p0.99:   8.315 ms/op
                 existUser·p0.999:  14.066 ms/op
                 existUser·p0.9999: 21.791 ms/op
                 existUser·p1.00:   23.101 ms/op

Iteration   3: 4.038 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.857 ms/op
                 existUser·p0.50:   3.858 ms/op
                 existUser·p0.90:   5.210 ms/op
                 existUser·p0.95:   5.898 ms/op
                 existUser·p0.99:   8.520 ms/op
                 existUser·p0.999:  12.255 ms/op
                 existUser·p0.9999: 23.498 ms/op
                 existUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 237130
  mean =      4.045 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10557 
    [ 2.500,  5.000) = 196436 
    [ 5.000,  7.500) = 25570 
    [ 7.500, 10.000) = 3551 
    [10.000, 12.500) = 794 
    [12.500, 15.000) = 130 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.857 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      5.202 ms/op
     p(95.0000) =      5.906 ms/op
     p(99.0000) =      8.520 ms/op
     p(99.9000) =     12.403 ms/op
     p(99.9900) =     23.134 ms/op
     p(99.9990) =     23.822 ms/op
     p(99.9999) =     23.921 ms/op
    p(100.0000) =     23.921 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.703 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.702 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.425 ±(99.9%) 0.016 ms/op
Iteration   1: 4.333 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.927 ms/op
                 getUser·p0.50:   4.137 ms/op
                 getUser·p0.90:   5.554 ms/op
                 getUser·p0.95:   6.201 ms/op
                 getUser·p0.99:   8.798 ms/op
                 getUser·p0.999:  13.173 ms/op
                 getUser·p0.9999: 16.677 ms/op
                 getUser·p1.00:   16.974 ms/op

Iteration   2: 4.417 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.041 ms/op
                 getUser·p0.50:   4.211 ms/op
                 getUser·p0.90:   5.743 ms/op
                 getUser·p0.95:   6.504 ms/op
                 getUser·p0.99:   8.946 ms/op
                 getUser·p0.999:  14.148 ms/op
                 getUser·p0.9999: 20.399 ms/op
                 getUser·p1.00:   20.709 ms/op

Iteration   3: 4.323 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.174 ms/op
                 getUser·p0.50:   4.100 ms/op
                 getUser·p0.90:   5.464 ms/op
                 getUser·p0.95:   6.324 ms/op
                 getUser·p0.99:   9.322 ms/op
                 getUser·p0.999:  14.566 ms/op
                 getUser·p0.9999: 23.929 ms/op
                 getUser·p1.00:   24.904 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 220193
  mean =      4.357 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4017 
    [ 2.500,  5.000) = 172748 
    [ 5.000,  7.500) = 38178 
    [ 7.500, 10.000) = 4039 
    [10.000, 12.500) = 820 
    [12.500, 15.000) = 237 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.927 ms/op
     p(50.0000) =      4.145 ms/op
     p(90.0000) =      5.595 ms/op
     p(95.0000) =      6.349 ms/op
     p(99.0000) =      9.044 ms/op
     p(99.9000) =     13.792 ms/op
     p(99.9900) =     22.216 ms/op
     p(99.9990) =     24.786 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


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
# Warmup Iteration   1: 8.244 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 6.094 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.637 ±(99.9%) 0.026 ms/op
Iteration   1: 5.548 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.694 ms/op
                 listUser·p0.50:   5.128 ms/op
                 listUser·p0.90:   7.610 ms/op
                 listUser·p0.95:   8.634 ms/op
                 listUser·p0.99:   11.436 ms/op
                 listUser·p0.999:  18.648 ms/op
                 listUser·p0.9999: 26.055 ms/op
                 listUser·p1.00:   27.754 ms/op

Iteration   2: 5.477 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   0.876 ms/op
                 listUser·p0.50:   5.005 ms/op
                 listUser·p0.90:   7.755 ms/op
                 listUser·p0.95:   8.815 ms/op
                 listUser·p0.99:   12.599 ms/op
                 listUser·p0.999:  23.085 ms/op
                 listUser·p0.9999: 34.361 ms/op
                 listUser·p1.00:   34.800 ms/op

Iteration   3: 5.519 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   0.739 ms/op
                 listUser·p0.50:   5.038 ms/op
                 listUser·p0.90:   7.963 ms/op
                 listUser·p0.95:   8.995 ms/op
                 listUser·p0.99:   11.813 ms/op
                 listUser·p0.999:  23.233 ms/op
                 listUser·p0.9999: 28.089 ms/op
                 listUser·p1.00:   28.508 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 174131
  mean =      5.514 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 552 
    [ 2.500,  5.000) = 82685 
    [ 5.000,  7.500) = 70211 
    [ 7.500, 10.000) = 16271 
    [10.000, 12.500) = 3074 
    [12.500, 15.000) = 788 
    [15.000, 17.500) = 209 
    [17.500, 20.000) = 123 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.739 ms/op
     p(50.0000) =      5.063 ms/op
     p(90.0000) =      7.782 ms/op
     p(95.0000) =      8.815 ms/op
     p(99.0000) =     11.928 ms/op
     p(99.9000) =     22.105 ms/op
     p(99.9900) =     33.232 ms/op
     p(99.9990) =     34.702 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.375 ± 1.416  ops/ms
ClientGrpc.existUser                       thrpt       3   8.166 ± 3.328  ops/ms
ClientGrpc.getUser                         thrpt       3   7.492 ± 1.799  ops/ms
ClientGrpc.listUser                        thrpt       3   5.668 ± 0.429  ops/ms
ClientGrpc.createUser                       avgt       3   4.343 ± 1.490   ms/op
ClientGrpc.existUser                        avgt       3   4.046 ± 1.224   ms/op
ClientGrpc.getUser                          avgt       3   4.235 ± 0.903   ms/op
ClientGrpc.listUser                         avgt       3   5.394 ± 1.078   ms/op
ClientGrpc.createUser                     sample  225106   4.264 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.028           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.063           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.521           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.226           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.946           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.533           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.523           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.130           ms/op
ClientGrpc.existUser                      sample  237130   4.045 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.857           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.202           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.906           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.520           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.403           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.134           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.921           ms/op
ClientGrpc.getUser                        sample  220193   4.357 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.927           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.145           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.595           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.349           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           9.044           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.792           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.216           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.904           ms/op
ClientGrpc.listUser                       sample  174131   5.514 ± 0.015   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.739           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.063           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.782           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.815           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.928           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          22.105           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          33.232           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.800           ms/op
