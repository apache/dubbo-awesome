# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.789 ops/ms
# Warmup Iteration   2: 4.474 ops/ms
# Warmup Iteration   3: 6.477 ops/ms
Iteration   1: 6.650 ops/ms
Iteration   2: 6.661 ops/ms
Iteration   3: 6.725 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.679 ±(99.9%) 0.733 ops/ms [Average]
  (min, avg, max) = (6.650, 6.679, 6.725), stdev = 0.040
  CI (99.9%): [5.946, 7.412] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.173 ops/ms
# Warmup Iteration   2: 6.966 ops/ms
# Warmup Iteration   3: 7.484 ops/ms
Iteration   1: 7.717 ops/ms
Iteration   2: 7.607 ops/ms
Iteration   3: 7.713 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.679 ±(99.9%) 1.141 ops/ms [Average]
  (min, avg, max) = (7.607, 7.679, 7.717), stdev = 0.063
  CI (99.9%): [6.538, 8.820] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.967 ops/ms
# Warmup Iteration   2: 6.618 ops/ms
# Warmup Iteration   3: 6.848 ops/ms
Iteration   1: 7.082 ops/ms
Iteration   2: 7.294 ops/ms
Iteration   3: 7.064 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.147 ±(99.9%) 2.329 ops/ms [Average]
  (min, avg, max) = (7.064, 7.147, 7.294), stdev = 0.128
  CI (99.9%): [4.818, 9.475] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.678 ops/ms
# Warmup Iteration   2: 4.806 ops/ms
# Warmup Iteration   3: 5.312 ops/ms
Iteration   1: 5.441 ops/ms
Iteration   2: 5.474 ops/ms
Iteration   3: 5.384 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.433 ±(99.9%) 0.829 ops/ms [Average]
  (min, avg, max) = (5.384, 5.433, 5.474), stdev = 0.045
  CI (99.9%): [4.603, 6.262] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.635 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.642 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.549 ±(99.9%) 0.006 ms/op
Iteration   1: 4.490 ±(99.9%) 0.003 ms/op
Iteration   2: 4.441 ±(99.9%) 0.003 ms/op
Iteration   3: 4.371 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.434 ±(99.9%) 1.093 ms/op [Average]
  (min, avg, max) = (4.371, 4.434, 4.490), stdev = 0.060
  CI (99.9%): [3.341, 5.527] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.366 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.472 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.208 ±(99.9%) 0.003 ms/op
Iteration   1: 4.299 ±(99.9%) 0.002 ms/op
Iteration   2: 4.285 ±(99.9%) 0.003 ms/op
Iteration   3: 4.176 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.254 ±(99.9%) 1.230 ms/op [Average]
  (min, avg, max) = (4.176, 4.254, 4.299), stdev = 0.067
  CI (99.9%): [3.024, 5.483] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.450 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.578 ±(99.9%) 0.070 ms/op
# Warmup Iteration   3: 4.536 ±(99.9%) 0.003 ms/op
Iteration   1: 4.712 ±(99.9%) 0.004 ms/op
Iteration   2: 4.492 ±(99.9%) 0.004 ms/op
Iteration   3: 4.429 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.544 ±(99.9%) 2.714 ms/op [Average]
  (min, avg, max) = (4.429, 4.544, 4.712), stdev = 0.149
  CI (99.9%): [1.830, 7.259] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.717 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 6.321 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.740 ±(99.9%) 0.016 ms/op
Iteration   1: 5.534 ±(99.9%) 0.013 ms/op
Iteration   2: 5.577 ±(99.9%) 0.023 ms/op
Iteration   3: 5.626 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.579 ±(99.9%) 0.844 ms/op [Average]
  (min, avg, max) = (5.534, 5.579, 5.626), stdev = 0.046
  CI (99.9%): [4.735, 6.423] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.462 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 4.804 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.515 ±(99.9%) 0.014 ms/op
Iteration   1: 4.414 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.077 ms/op
                 createUser·p0.50:   4.334 ms/op
                 createUser·p0.90:   5.415 ms/op
                 createUser·p0.95:   5.775 ms/op
                 createUser·p0.99:   7.037 ms/op
                 createUser·p0.999:  14.469 ms/op
                 createUser·p0.9999: 17.654 ms/op
                 createUser·p1.00:   19.071 ms/op

Iteration   2: 4.323 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.556 ms/op
                 createUser·p0.50:   4.252 ms/op
                 createUser·p0.90:   5.243 ms/op
                 createUser·p0.95:   5.603 ms/op
                 createUser·p0.99:   6.636 ms/op
                 createUser·p0.999:  12.256 ms/op
                 createUser·p0.9999: 16.817 ms/op
                 createUser·p1.00:   18.874 ms/op

Iteration   3: 4.466 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.900 ms/op
                 createUser·p0.50:   4.358 ms/op
                 createUser·p0.90:   5.423 ms/op
                 createUser·p0.95:   5.784 ms/op
                 createUser·p0.99:   7.536 ms/op
                 createUser·p0.999:  21.345 ms/op
                 createUser·p0.9999: 28.165 ms/op
                 createUser·p1.00:   28.475 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 218063
  mean =      4.400 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1738 
    [ 2.500,  5.000) = 173739 
    [ 5.000,  7.500) = 41037 
    [ 7.500, 10.000) = 1062 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.556 ms/op
     p(50.0000) =      4.309 ms/op
     p(90.0000) =      5.366 ms/op
     p(95.0000) =      5.718 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =     15.136 ms/op
     p(99.9900) =     27.237 ms/op
     p(99.9990) =     28.338 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.341 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.359 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.984 ±(99.9%) 0.009 ms/op
Iteration   1: 4.191 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.135 ms/op
                 existUser·p0.50:   4.080 ms/op
                 existUser·p0.90:   5.145 ms/op
                 existUser·p0.95:   5.587 ms/op
                 existUser·p0.99:   7.315 ms/op
                 existUser·p0.999:  10.136 ms/op
                 existUser·p0.9999: 15.499 ms/op
                 existUser·p1.00:   15.696 ms/op

Iteration   2: 4.073 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.247 ms/op
                 existUser·p0.50:   3.998 ms/op
                 existUser·p0.90:   4.981 ms/op
                 existUser·p0.95:   5.333 ms/op
                 existUser·p0.99:   6.521 ms/op
                 existUser·p0.999:  10.082 ms/op
                 existUser·p0.9999: 17.572 ms/op
                 existUser·p1.00:   18.055 ms/op

Iteration   3: 3.987 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.141 ms/op
                 existUser·p0.50:   3.916 ms/op
                 existUser·p0.90:   4.735 ms/op
                 existUser·p0.95:   5.120 ms/op
                 existUser·p0.99:   6.103 ms/op
                 existUser·p0.999:  9.257 ms/op
                 existUser·p0.9999: 20.348 ms/op
                 existUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 235222
  mean =      4.082 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3659 
    [ 2.500,  5.000) = 209365 
    [ 5.000,  7.500) = 20880 
    [ 7.500, 10.000) = 1088 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.135 ms/op
     p(50.0000) =      3.994 ms/op
     p(90.0000) =      4.964 ms/op
     p(95.0000) =      5.358 ms/op
     p(99.0000) =      6.627 ms/op
     p(99.9000) =      9.978 ms/op
     p(99.9900) =     19.840 ms/op
     p(99.9990) =     20.825 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.799 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 4.844 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.536 ±(99.9%) 0.013 ms/op
Iteration   1: 4.422 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.309 ms/op
                 getUser·p0.50:   4.334 ms/op
                 getUser·p0.90:   5.448 ms/op
                 getUser·p0.95:   5.833 ms/op
                 getUser·p0.99:   7.158 ms/op
                 getUser·p0.999:  10.633 ms/op
                 getUser·p0.9999: 18.015 ms/op
                 getUser·p1.00:   18.711 ms/op

Iteration   2: 4.440 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.264 ms/op
                 getUser·p0.50:   4.325 ms/op
                 getUser·p0.90:   5.521 ms/op
                 getUser·p0.95:   6.013 ms/op
                 getUser·p0.99:   7.545 ms/op
                 getUser·p0.999:  11.583 ms/op
                 getUser·p0.9999: 19.286 ms/op
                 getUser·p1.00:   19.792 ms/op

Iteration   3: 4.346 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.079 ms/op
                 getUser·p0.50:   4.252 ms/op
                 getUser·p0.90:   5.382 ms/op
                 getUser·p0.95:   5.808 ms/op
                 getUser·p0.99:   7.099 ms/op
                 getUser·p0.999:  10.049 ms/op
                 getUser·p0.9999: 22.434 ms/op
                 getUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 218085
  mean =      4.402 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4240 
    [ 2.500,  5.000) = 170013 
    [ 5.000,  7.500) = 41991 
    [ 7.500, 10.000) = 1472 
    [10.000, 12.500) = 207 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.079 ms/op
     p(50.0000) =      4.309 ms/op
     p(90.0000) =      5.448 ms/op
     p(95.0000) =      5.882 ms/op
     p(99.0000) =      7.266 ms/op
     p(99.9000) =     10.846 ms/op
     p(99.9900) =     20.583 ms/op
     p(99.9990) =     22.538 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.228 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 6.445 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.641 ±(99.9%) 0.020 ms/op
Iteration   1: 5.652 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.585 ms/op
                 listUser·p0.50:   5.390 ms/op
                 listUser·p0.90:   7.299 ms/op
                 listUser·p0.95:   8.298 ms/op
                 listUser·p0.99:   10.764 ms/op
                 listUser·p0.999:  18.416 ms/op
                 listUser·p0.9999: 20.688 ms/op
                 listUser·p1.00:   21.823 ms/op

Iteration   2: 5.719 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.198 ms/op
                 listUser·p0.50:   5.464 ms/op
                 listUser·p0.90:   7.291 ms/op
                 listUser·p0.95:   8.438 ms/op
                 listUser·p0.99:   10.666 ms/op
                 listUser·p0.999:  18.844 ms/op
                 listUser·p0.9999: 31.097 ms/op
                 listUser·p1.00:   32.145 ms/op

Iteration   3: 5.671 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.634 ms/op
                 listUser·p0.50:   5.382 ms/op
                 listUser·p0.90:   7.489 ms/op
                 listUser·p0.95:   8.536 ms/op
                 listUser·p0.99:   10.715 ms/op
                 listUser·p0.999:  21.487 ms/op
                 listUser·p0.9999: 25.522 ms/op
                 listUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 168970
  mean =      5.680 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 155 
    [ 2.500,  5.000) = 53841 
    [ 5.000,  7.500) = 99517 
    [ 7.500, 10.000) = 12741 
    [10.000, 12.500) = 1987 
    [12.500, 15.000) = 365 
    [15.000, 17.500) = 143 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 19 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.198 ms/op
     p(50.0000) =      5.415 ms/op
     p(90.0000) =      7.365 ms/op
     p(95.0000) =      8.421 ms/op
     p(99.0000) =     10.715 ms/op
     p(99.9000) =     18.745 ms/op
     p(99.9900) =     30.048 ms/op
     p(99.9990) =     31.445 ms/op
     p(99.9999) =     32.145 ms/op
    p(100.0000) =     32.145 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.679 ± 0.733  ops/ms
ClientGrpc.existUser                       thrpt       3   7.679 ± 1.141  ops/ms
ClientGrpc.getUser                         thrpt       3   7.147 ± 2.329  ops/ms
ClientGrpc.listUser                        thrpt       3   5.433 ± 0.829  ops/ms
ClientGrpc.createUser                       avgt       3   4.434 ± 1.093   ms/op
ClientGrpc.existUser                        avgt       3   4.254 ± 1.230   ms/op
ClientGrpc.getUser                          avgt       3   4.544 ± 2.714   ms/op
ClientGrpc.listUser                         avgt       3   5.579 ± 0.844   ms/op
ClientGrpc.createUser                     sample  218063   4.400 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.556           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.309           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.366           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.718           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.037           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          15.136           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.237           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.475           ms/op
ClientGrpc.existUser                      sample  235222   4.082 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.135           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.994           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.964           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.358           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.627           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.978           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.840           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.004           ms/op
ClientGrpc.getUser                        sample  218085   4.402 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.079           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.309           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.448           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.882           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.266           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.846           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.583           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.675           ms/op
ClientGrpc.listUser                       sample  168970   5.680 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.198           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.415           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.365           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.421           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.715           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.745           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.048           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.145           ms/op
