# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.311 ops/ms
# Warmup Iteration   2: 5.672 ops/ms
# Warmup Iteration   3: 7.121 ops/ms
Iteration   1: 7.350 ops/ms
Iteration   2: 7.440 ops/ms
Iteration   3: 7.174 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.321 ±(99.9%) 2.470 ops/ms [Average]
  (min, avg, max) = (7.174, 7.321, 7.440), stdev = 0.135
  CI (99.9%): [4.851, 9.792] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.925 ops/ms
# Warmup Iteration   2: 7.376 ops/ms
# Warmup Iteration   3: 7.518 ops/ms
Iteration   1: 7.615 ops/ms
Iteration   2: 8.047 ops/ms
Iteration   3: 7.687 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.783 ±(99.9%) 4.225 ops/ms [Average]
  (min, avg, max) = (7.615, 7.783, 8.047), stdev = 0.232
  CI (99.9%): [3.559, 12.008] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.272 ops/ms
# Warmup Iteration   2: 7.231 ops/ms
# Warmup Iteration   3: 7.326 ops/ms
Iteration   1: 7.306 ops/ms
Iteration   2: 7.395 ops/ms
Iteration   3: 7.494 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.398 ±(99.9%) 1.723 ops/ms [Average]
  (min, avg, max) = (7.306, 7.398, 7.494), stdev = 0.094
  CI (99.9%): [5.675, 9.121] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.881 ops/ms
# Warmup Iteration   2: 5.307 ops/ms
# Warmup Iteration   3: 5.886 ops/ms
Iteration   1: 5.839 ops/ms
Iteration   2: 5.939 ops/ms
Iteration   3: 6.031 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.936 ±(99.9%) 1.754 ops/ms [Average]
  (min, avg, max) = (5.839, 5.936, 6.031), stdev = 0.096
  CI (99.9%): [4.182, 7.690] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.269 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.554 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.414 ±(99.9%) 0.003 ms/op
Iteration   1: 4.494 ±(99.9%) 0.003 ms/op
Iteration   2: 4.415 ±(99.9%) 0.003 ms/op
Iteration   3: 4.493 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.467 ±(99.9%) 0.824 ms/op [Average]
  (min, avg, max) = (4.415, 4.467, 4.494), stdev = 0.045
  CI (99.9%): [3.644, 5.291] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.254 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.387 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.122 ±(99.9%) 0.003 ms/op
Iteration   1: 4.240 ±(99.9%) 0.003 ms/op
Iteration   2: 4.178 ±(99.9%) 0.003 ms/op
Iteration   3: 4.139 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.186 ±(99.9%) 0.933 ms/op [Average]
  (min, avg, max) = (4.139, 4.186, 4.240), stdev = 0.051
  CI (99.9%): [3.253, 5.118] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.947 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.784 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.576 ±(99.9%) 0.006 ms/op
Iteration   1: 4.515 ±(99.9%) 0.003 ms/op
Iteration   2: 4.435 ±(99.9%) 0.003 ms/op
Iteration   3: 4.376 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.442 ±(99.9%) 1.273 ms/op [Average]
  (min, avg, max) = (4.376, 4.442, 4.515), stdev = 0.070
  CI (99.9%): [3.168, 5.715] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.305 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 5.875 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.600 ±(99.9%) 0.040 ms/op
Iteration   1: 5.620 ±(99.9%) 0.041 ms/op
Iteration   2: 5.491 ±(99.9%) 0.015 ms/op
Iteration   3: 5.520 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.544 ±(99.9%) 1.236 ms/op [Average]
  (min, avg, max) = (5.491, 5.544, 5.620), stdev = 0.068
  CI (99.9%): [4.308, 6.779] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.582 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.581 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.335 ±(99.9%) 0.013 ms/op
Iteration   1: 4.515 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.087 ms/op
                 createUser·p0.50:   4.456 ms/op
                 createUser·p0.90:   5.775 ms/op
                 createUser·p0.95:   6.144 ms/op
                 createUser·p0.99:   7.840 ms/op
                 createUser·p0.999:  14.287 ms/op
                 createUser·p0.9999: 20.535 ms/op
                 createUser·p1.00:   20.840 ms/op

Iteration   2: 4.289 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.135 ms/op
                 createUser·p0.50:   4.202 ms/op
                 createUser·p0.90:   5.292 ms/op
                 createUser·p0.95:   5.636 ms/op
                 createUser·p0.99:   6.693 ms/op
                 createUser·p0.999:  11.185 ms/op
                 createUser·p0.9999: 23.038 ms/op
                 createUser·p1.00:   23.724 ms/op

Iteration   3: 4.374 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.011 ms/op
                 createUser·p0.50:   4.284 ms/op
                 createUser·p0.90:   5.472 ms/op
                 createUser·p0.95:   5.800 ms/op
                 createUser·p0.99:   7.537 ms/op
                 createUser·p0.999:  16.669 ms/op
                 createUser·p0.9999: 25.003 ms/op
                 createUser·p1.00:   25.625 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 218702
  mean =      4.391 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4448 
    [ 2.500,  5.000) = 163485 
    [ 5.000,  7.500) = 48756 
    [ 7.500, 10.000) = 1538 
    [10.000, 12.500) = 209 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.011 ms/op
     p(50.0000) =      4.301 ms/op
     p(90.0000) =      5.530 ms/op
     p(95.0000) =      5.898 ms/op
     p(99.0000) =      7.356 ms/op
     p(99.9000) =     14.287 ms/op
     p(99.9900) =     24.019 ms/op
     p(99.9990) =     25.508 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.078 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.391 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.147 ±(99.9%) 0.012 ms/op
Iteration   1: 4.228 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.914 ms/op
                 existUser·p0.50:   4.153 ms/op
                 existUser·p0.90:   5.300 ms/op
                 existUser·p0.95:   5.677 ms/op
                 existUser·p0.99:   7.307 ms/op
                 existUser·p0.999:  11.163 ms/op
                 existUser·p0.9999: 17.148 ms/op
                 existUser·p1.00:   19.464 ms/op

Iteration   2: 4.136 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.948 ms/op
                 existUser·p0.50:   4.063 ms/op
                 existUser·p0.90:   5.325 ms/op
                 existUser·p0.95:   5.669 ms/op
                 existUser·p0.99:   6.988 ms/op
                 existUser·p0.999:  9.390 ms/op
                 existUser·p0.9999: 20.120 ms/op
                 existUser·p1.00:   20.152 ms/op

Iteration   3: 4.231 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.972 ms/op
                 existUser·p0.50:   4.112 ms/op
                 existUser·p0.90:   5.300 ms/op
                 existUser·p0.95:   5.661 ms/op
                 existUser·p0.99:   7.351 ms/op
                 existUser·p0.999:  11.512 ms/op
                 existUser·p0.9999: 22.718 ms/op
                 existUser·p1.00:   23.003 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 228738
  mean =      4.198 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6875 
    [ 2.500,  5.000) = 181866 
    [ 5.000,  7.500) = 38151 
    [ 7.500, 10.000) = 1496 
    [10.000, 12.500) = 197 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.914 ms/op
     p(50.0000) =      4.112 ms/op
     p(90.0000) =      5.308 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      7.217 ms/op
     p(99.9000) =     10.666 ms/op
     p(99.9900) =     20.152 ms/op
     p(99.9990) =     23.003 ms/op
     p(99.9999) =     23.003 ms/op
    p(100.0000) =     23.003 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.667 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.715 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.530 ±(99.9%) 0.014 ms/op
Iteration   1: 4.340 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.120 ms/op
                 getUser·p0.50:   4.243 ms/op
                 getUser·p0.90:   5.505 ms/op
                 getUser·p0.95:   5.825 ms/op
                 getUser·p0.99:   6.906 ms/op
                 getUser·p0.999:  10.347 ms/op
                 getUser·p0.9999: 27.947 ms/op
                 getUser·p1.00:   29.622 ms/op

Iteration   2: 4.376 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.157 ms/op
                 getUser·p0.50:   4.301 ms/op
                 getUser·p0.90:   5.521 ms/op
                 getUser·p0.95:   5.865 ms/op
                 getUser·p0.99:   6.939 ms/op
                 getUser·p0.999:  10.468 ms/op
                 getUser·p0.9999: 26.797 ms/op
                 getUser·p1.00:   27.623 ms/op

Iteration   3: 4.417 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.031 ms/op
                 getUser·p0.50:   4.334 ms/op
                 getUser·p0.90:   5.538 ms/op
                 getUser·p0.95:   5.882 ms/op
                 getUser·p0.99:   7.365 ms/op
                 getUser·p0.999:  10.928 ms/op
                 getUser·p0.9999: 30.573 ms/op
                 getUser·p1.00:   31.916 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 219188
  mean =      4.377 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4590 
    [ 2.500,  5.000) = 162821 
    [ 5.000,  7.500) = 50237 
    [ 7.500, 10.000) = 1270 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.031 ms/op
     p(50.0000) =      4.293 ms/op
     p(90.0000) =      5.521 ms/op
     p(95.0000) =      5.857 ms/op
     p(99.0000) =      7.070 ms/op
     p(99.9000) =     10.551 ms/op
     p(99.9900) =     28.221 ms/op
     p(99.9990) =     30.822 ms/op
     p(99.9999) =     31.916 ms/op
    p(100.0000) =     31.916 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.503 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 5.815 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.354 ±(99.9%) 0.018 ms/op
Iteration   1: 5.408 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   0.589 ms/op
                 listUser·p0.50:   5.136 ms/op
                 listUser·p0.90:   7.119 ms/op
                 listUser·p0.95:   7.963 ms/op
                 listUser·p0.99:   10.469 ms/op
                 listUser·p0.999:  17.200 ms/op
                 listUser·p0.9999: 25.726 ms/op
                 listUser·p1.00:   25.854 ms/op

Iteration   2: 5.195 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.260 ms/op
                 listUser·p0.50:   4.981 ms/op
                 listUser·p0.90:   6.545 ms/op
                 listUser·p0.95:   7.373 ms/op
                 listUser·p0.99:   9.667 ms/op
                 listUser·p0.999:  17.479 ms/op
                 listUser·p0.9999: 22.562 ms/op
                 listUser·p1.00:   22.774 ms/op

Iteration   3: 5.217 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.176 ms/op
                 listUser·p0.50:   5.030 ms/op
                 listUser·p0.90:   6.603 ms/op
                 listUser·p0.95:   7.414 ms/op
                 listUser·p0.99:   9.322 ms/op
                 listUser·p0.999:  28.739 ms/op
                 listUser·p0.9999: 32.456 ms/op
                 listUser·p1.00:   33.063 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 182020
  mean =      5.272 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 201 
    [ 2.500,  5.000) = 87070 
    [ 5.000,  7.500) = 84827 
    [ 7.500, 10.000) = 8303 
    [10.000, 12.500) = 1062 
    [12.500, 15.000) = 213 
    [15.000, 17.500) = 150 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.589 ms/op
     p(50.0000) =      5.046 ms/op
     p(90.0000) =      6.775 ms/op
     p(95.0000) =      7.602 ms/op
     p(99.0000) =      9.830 ms/op
     p(99.9000) =     17.695 ms/op
     p(99.9900) =     31.680 ms/op
     p(99.9990) =     32.902 ms/op
     p(99.9999) =     33.063 ms/op
    p(100.0000) =     33.063 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.321 ± 2.470  ops/ms
ClientGrpc.existUser                       thrpt       3   7.783 ± 4.225  ops/ms
ClientGrpc.getUser                         thrpt       3   7.398 ± 1.723  ops/ms
ClientGrpc.listUser                        thrpt       3   5.936 ± 1.754  ops/ms
ClientGrpc.createUser                       avgt       3   4.467 ± 0.824   ms/op
ClientGrpc.existUser                        avgt       3   4.186 ± 0.933   ms/op
ClientGrpc.getUser                          avgt       3   4.442 ± 1.273   ms/op
ClientGrpc.listUser                         avgt       3   5.544 ± 1.236   ms/op
ClientGrpc.createUser                     sample  218702   4.391 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.011           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.301           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.530           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.898           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.356           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.287           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.019           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.625           ms/op
ClientGrpc.existUser                      sample  228738   4.198 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.914           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.112           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.308           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.669           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.217           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.666           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.152           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.003           ms/op
ClientGrpc.getUser                        sample  219188   4.377 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.031           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.293           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.521           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.857           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.070           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.551           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.221           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          31.916           ms/op
ClientGrpc.listUser                       sample  182020   5.272 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.589           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.046           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.775           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.602           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.830           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.695           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.680           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.063           ms/op
