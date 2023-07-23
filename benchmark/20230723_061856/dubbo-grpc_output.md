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
# Warmup Iteration   1: 2.328 ops/ms
# Warmup Iteration   2: 5.349 ops/ms
# Warmup Iteration   3: 6.656 ops/ms
Iteration   1: 7.008 ops/ms
Iteration   2: 7.233 ops/ms
Iteration   3: 7.270 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.170 ±(99.9%) 2.592 ops/ms [Average]
  (min, avg, max) = (7.008, 7.170, 7.270), stdev = 0.142
  CI (99.9%): [4.578, 9.762] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.625 ops/ms
# Warmup Iteration   2: 7.162 ops/ms
# Warmup Iteration   3: 7.626 ops/ms
Iteration   1: 7.879 ops/ms
Iteration   2: 7.867 ops/ms
Iteration   3: 7.994 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.913 ±(99.9%) 1.283 ops/ms [Average]
  (min, avg, max) = (7.867, 7.913, 7.994), stdev = 0.070
  CI (99.9%): [6.630, 9.197] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.493 ops/ms
# Warmup Iteration   2: 6.715 ops/ms
# Warmup Iteration   3: 7.479 ops/ms
Iteration   1: 7.399 ops/ms
Iteration   2: 7.434 ops/ms
Iteration   3: 7.426 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.420 ±(99.9%) 0.341 ops/ms [Average]
  (min, avg, max) = (7.399, 7.420, 7.434), stdev = 0.019
  CI (99.9%): [7.079, 7.761] (assumes normal distribution)


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
# Warmup Iteration   1: 3.733 ops/ms
# Warmup Iteration   2: 5.312 ops/ms
# Warmup Iteration   3: 5.677 ops/ms
Iteration   1: 5.746 ops/ms
Iteration   2: 5.838 ops/ms
Iteration   3: 5.793 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.792 ±(99.9%) 0.837 ops/ms [Average]
  (min, avg, max) = (5.746, 5.792, 5.838), stdev = 0.046
  CI (99.9%): [4.956, 6.629] (assumes normal distribution)


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
# Warmup Iteration   1: 6.415 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.887 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.741 ±(99.9%) 0.006 ms/op
Iteration   1: 4.508 ±(99.9%) 0.003 ms/op
Iteration   2: 4.604 ±(99.9%) 0.003 ms/op
Iteration   3: 4.448 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.520 ±(99.9%) 1.437 ms/op [Average]
  (min, avg, max) = (4.448, 4.520, 4.604), stdev = 0.079
  CI (99.9%): [3.083, 5.957] (assumes normal distribution)


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
# Warmup Iteration   1: 6.387 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.275 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.203 ±(99.9%) 0.002 ms/op
Iteration   1: 4.174 ±(99.9%) 0.003 ms/op
Iteration   2: 4.095 ±(99.9%) 0.004 ms/op
Iteration   3: 4.092 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.121 ±(99.9%) 0.850 ms/op [Average]
  (min, avg, max) = (4.092, 4.121, 4.174), stdev = 0.047
  CI (99.9%): [3.270, 4.971] (assumes normal distribution)


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
# Warmup Iteration   1: 6.240 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.553 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.303 ±(99.9%) 0.004 ms/op
Iteration   1: 4.399 ±(99.9%) 0.005 ms/op
Iteration   2: 4.421 ±(99.9%) 0.002 ms/op
Iteration   3: 4.351 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.390 ±(99.9%) 0.653 ms/op [Average]
  (min, avg, max) = (4.351, 4.390, 4.421), stdev = 0.036
  CI (99.9%): [3.737, 5.044] (assumes normal distribution)


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
# Warmup Iteration   1: 7.825 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 6.234 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 5.717 ±(99.9%) 0.015 ms/op
Iteration   1: 5.476 ±(99.9%) 0.015 ms/op
Iteration   2: 5.645 ±(99.9%) 0.023 ms/op
Iteration   3: 5.840 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.653 ±(99.9%) 3.321 ms/op [Average]
  (min, avg, max) = (5.476, 5.653, 5.840), stdev = 0.182
  CI (99.9%): [2.332, 8.975] (assumes normal distribution)


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
# Warmup Iteration   1: 7.545 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 4.522 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.240 ±(99.9%) 0.012 ms/op
Iteration   1: 4.353 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.785 ms/op
                 createUser·p0.50:   4.227 ms/op
                 createUser·p0.90:   5.390 ms/op
                 createUser·p0.95:   5.849 ms/op
                 createUser·p0.99:   7.986 ms/op
                 createUser·p0.999:  13.894 ms/op
                 createUser·p0.9999: 17.508 ms/op
                 createUser·p1.00:   17.793 ms/op

Iteration   2: 4.218 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.190 ms/op
                 createUser·p0.50:   4.133 ms/op
                 createUser·p0.90:   5.128 ms/op
                 createUser·p0.95:   5.497 ms/op
                 createUser·p0.99:   7.135 ms/op
                 createUser·p0.999:  13.140 ms/op
                 createUser·p0.9999: 18.232 ms/op
                 createUser·p1.00:   18.711 ms/op

Iteration   3: 4.124 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.013 ms/op
                 createUser·p0.50:   4.067 ms/op
                 createUser·p0.90:   5.153 ms/op
                 createUser·p0.95:   5.546 ms/op
                 createUser·p0.99:   6.513 ms/op
                 createUser·p0.999:  10.469 ms/op
                 createUser·p0.9999: 28.352 ms/op
                 createUser·p1.00:   28.738 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 227102
  mean =      4.229 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4538 
    [ 2.500,  5.000) = 189128 
    [ 5.000,  7.500) = 31486 
    [ 7.500, 10.000) = 1362 
    [10.000, 12.500) = 368 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.785 ms/op
     p(50.0000) =      4.137 ms/op
     p(90.0000) =      5.226 ms/op
     p(95.0000) =      5.628 ms/op
     p(99.0000) =      7.242 ms/op
     p(99.9000) =     12.368 ms/op
     p(99.9900) =     26.472 ms/op
     p(99.9990) =     28.589 ms/op
     p(99.9999) =     28.738 ms/op
    p(100.0000) =     28.738 ms/op


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
# Warmup Iteration   1: 5.822 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.307 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.058 ±(99.9%) 0.011 ms/op
Iteration   1: 4.151 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.090 ms/op
                 existUser·p0.50:   4.026 ms/op
                 existUser·p0.90:   5.226 ms/op
                 existUser·p0.95:   5.661 ms/op
                 existUser·p0.99:   7.864 ms/op
                 existUser·p0.999:  14.696 ms/op
                 existUser·p0.9999: 15.964 ms/op
                 existUser·p1.00:   16.646 ms/op

Iteration   2: 4.076 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.751 ms/op
                 existUser·p0.50:   3.985 ms/op
                 existUser·p0.90:   5.120 ms/op
                 existUser·p0.95:   5.530 ms/op
                 existUser·p0.99:   6.930 ms/op
                 existUser·p0.999:  10.644 ms/op
                 existUser·p0.9999: 16.675 ms/op
                 existUser·p1.00:   18.973 ms/op

Iteration   3: 4.131 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.196 ms/op
                 existUser·p0.50:   3.998 ms/op
                 existUser·p0.90:   5.145 ms/op
                 existUser·p0.95:   5.538 ms/op
                 existUser·p0.99:   6.971 ms/op
                 existUser·p0.999:  9.552 ms/op
                 existUser·p0.9999: 22.348 ms/op
                 existUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 232927
  mean =      4.119 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4721 
    [ 2.500,  5.000) = 198110 
    [ 5.000,  7.500) = 28197 
    [ 7.500, 10.000) = 1470 
    [10.000, 12.500) = 246 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      4.002 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.571 ms/op
     p(99.0000) =      7.176 ms/op
     p(99.9000) =     11.571 ms/op
     p(99.9900) =     18.809 ms/op
     p(99.9990) =     22.370 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.638 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.613 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.431 ±(99.9%) 0.013 ms/op
Iteration   1: 4.305 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.264 ms/op
                 getUser·p0.50:   4.174 ms/op
                 getUser·p0.90:   5.366 ms/op
                 getUser·p0.95:   5.865 ms/op
                 getUser·p0.99:   7.528 ms/op
                 getUser·p0.999:  14.516 ms/op
                 getUser·p0.9999: 22.221 ms/op
                 getUser·p1.00:   22.741 ms/op

Iteration   2: 4.558 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.229 ms/op
                 getUser·p0.50:   4.448 ms/op
                 getUser·p0.90:   5.652 ms/op
                 getUser·p0.95:   6.070 ms/op
                 getUser·p0.99:   7.578 ms/op
                 getUser·p0.999:  10.296 ms/op
                 getUser·p0.9999: 18.054 ms/op
                 getUser·p1.00:   20.709 ms/op

Iteration   3: 4.398 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.039 ms/op
                 getUser·p0.50:   4.293 ms/op
                 getUser·p0.90:   5.448 ms/op
                 getUser·p0.95:   5.874 ms/op
                 getUser·p0.99:   7.586 ms/op
                 getUser·p0.999:  11.305 ms/op
                 getUser·p0.9999: 20.364 ms/op
                 getUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 217218
  mean =      4.418 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3683 
    [ 2.500,  5.000) = 167953 
    [ 5.000,  7.500) = 43298 
    [ 7.500, 10.000) = 1821 
    [10.000, 12.500) = 252 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.039 ms/op
     p(50.0000) =      4.301 ms/op
     p(90.0000) =      5.505 ms/op
     p(95.0000) =      5.956 ms/op
     p(99.0000) =      7.569 ms/op
     p(99.9000) =     12.248 ms/op
     p(99.9900) =     21.570 ms/op
     p(99.9990) =     22.631 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


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
# Warmup Iteration   1: 7.276 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 6.378 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.878 ±(99.9%) 0.023 ms/op
Iteration   1: 5.752 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.849 ms/op
                 listUser·p0.50:   5.472 ms/op
                 listUser·p0.90:   7.602 ms/op
                 listUser·p0.95:   8.602 ms/op
                 listUser·p0.99:   10.958 ms/op
                 listUser·p0.999:  16.876 ms/op
                 listUser·p0.9999: 28.504 ms/op
                 listUser·p1.00:   29.131 ms/op

Iteration   2: 5.964 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.536 ms/op
                 listUser·p0.50:   5.636 ms/op
                 listUser·p0.90:   7.774 ms/op
                 listUser·p0.95:   8.815 ms/op
                 listUser·p0.99:   11.674 ms/op
                 listUser·p0.999:  20.614 ms/op
                 listUser·p0.9999: 25.565 ms/op
                 listUser·p1.00:   26.247 ms/op

Iteration   3: 5.839 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.477 ms/op
                 listUser·p0.50:   5.554 ms/op
                 listUser·p0.90:   7.537 ms/op
                 listUser·p0.95:   8.585 ms/op
                 listUser·p0.99:   11.436 ms/op
                 listUser·p0.999:  22.544 ms/op
                 listUser·p0.9999: 34.836 ms/op
                 listUser·p1.00:   35.324 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 164068
  mean =      5.850 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 56 
    [ 2.500,  5.000) = 44069 
    [ 5.000,  7.500) = 101932 
    [ 7.500, 10.000) = 14505 
    [10.000, 12.500) = 2581 
    [12.500, 15.000) = 548 
    [15.000, 17.500) = 139 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.477 ms/op
     p(50.0000) =      5.554 ms/op
     p(90.0000) =      7.643 ms/op
     p(95.0000) =      8.667 ms/op
     p(99.0000) =     11.354 ms/op
     p(99.9000) =     20.729 ms/op
     p(99.9900) =     32.794 ms/op
     p(99.9990) =     35.282 ms/op
     p(99.9999) =     35.324 ms/op
    p(100.0000) =     35.324 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.170 ± 2.592  ops/ms
ClientGrpc.existUser                       thrpt       3   7.913 ± 1.283  ops/ms
ClientGrpc.getUser                         thrpt       3   7.420 ± 0.341  ops/ms
ClientGrpc.listUser                        thrpt       3   5.792 ± 0.837  ops/ms
ClientGrpc.createUser                       avgt       3   4.520 ± 1.437   ms/op
ClientGrpc.existUser                        avgt       3   4.121 ± 0.850   ms/op
ClientGrpc.getUser                          avgt       3   4.390 ± 0.653   ms/op
ClientGrpc.listUser                         avgt       3   5.653 ± 3.321   ms/op
ClientGrpc.createUser                     sample  227102   4.229 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.785           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.137           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.226           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.628           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.242           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.368           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.472           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.738           ms/op
ClientGrpc.existUser                      sample  232927   4.119 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.751           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.002           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.161           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.571           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.176           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.571           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.809           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.381           ms/op
ClientGrpc.getUser                        sample  217218   4.418 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.039           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.301           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.505           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.956           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.569           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.248           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.570           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.741           ms/op
ClientGrpc.listUser                       sample  164068   5.850 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.477           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.554           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.643           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.667           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.354           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.729           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.794           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          35.324           ms/op
