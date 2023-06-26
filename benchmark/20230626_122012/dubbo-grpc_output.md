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
# Warmup Iteration   1: 2.104 ops/ms
# Warmup Iteration   2: 5.394 ops/ms
# Warmup Iteration   3: 6.739 ops/ms
Iteration   1: 6.956 ops/ms
Iteration   2: 7.229 ops/ms
Iteration   3: 7.190 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.125 ±(99.9%) 2.694 ops/ms [Average]
  (min, avg, max) = (6.956, 7.125, 7.229), stdev = 0.148
  CI (99.9%): [4.431, 9.819] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.443 ops/ms
# Warmup Iteration   2: 6.888 ops/ms
# Warmup Iteration   3: 7.795 ops/ms
Iteration   1: 7.574 ops/ms
Iteration   2: 7.820 ops/ms
Iteration   3: 7.883 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.759 ±(99.9%) 2.984 ops/ms [Average]
  (min, avg, max) = (7.574, 7.759, 7.883), stdev = 0.164
  CI (99.9%): [4.775, 10.743] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 4.216 ops/ms
# Warmup Iteration   2: 6.626 ops/ms
# Warmup Iteration   3: 6.982 ops/ms
Iteration   1: 7.651 ops/ms
Iteration   2: 7.433 ops/ms
Iteration   3: 7.792 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.625 ±(99.9%) 3.295 ops/ms [Average]
  (min, avg, max) = (7.433, 7.625, 7.792), stdev = 0.181
  CI (99.9%): [4.330, 10.920] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.424 ops/ms
# Warmup Iteration   2: 4.928 ops/ms
# Warmup Iteration   3: 5.410 ops/ms
Iteration   1: 5.665 ops/ms
Iteration   2: 5.552 ops/ms
Iteration   3: 5.437 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.551 ±(99.9%) 2.078 ops/ms [Average]
  (min, avg, max) = (5.437, 5.551, 5.665), stdev = 0.114
  CI (99.9%): [3.473, 7.629] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.041 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.971 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.765 ±(99.9%) 0.009 ms/op
Iteration   1: 4.431 ±(99.9%) 0.002 ms/op
Iteration   2: 4.326 ±(99.9%) 0.003 ms/op
Iteration   3: 4.376 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.378 ±(99.9%) 0.951 ms/op [Average]
  (min, avg, max) = (4.326, 4.378, 4.431), stdev = 0.052
  CI (99.9%): [3.427, 5.329] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.729 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.412 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.238 ±(99.9%) 0.004 ms/op
Iteration   1: 4.146 ±(99.9%) 0.004 ms/op
Iteration   2: 4.160 ±(99.9%) 0.003 ms/op
Iteration   3: 3.938 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.082 ±(99.9%) 2.268 ms/op [Average]
  (min, avg, max) = (3.938, 4.082, 4.160), stdev = 0.124
  CI (99.9%): [1.814, 6.349] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.528 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 5.163 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.577 ±(99.9%) 0.004 ms/op
Iteration   1: 4.534 ±(99.9%) 0.004 ms/op
Iteration   2: 4.471 ±(99.9%) 0.004 ms/op
Iteration   3: 4.221 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.409 ±(99.9%) 3.018 ms/op [Average]
  (min, avg, max) = (4.221, 4.409, 4.534), stdev = 0.165
  CI (99.9%): [1.390, 7.427] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 8.656 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 6.597 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.903 ±(99.9%) 0.015 ms/op
Iteration   1: 5.344 ±(99.9%) 0.017 ms/op
Iteration   2: 5.673 ±(99.9%) 0.020 ms/op
Iteration   3: 5.462 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.493 ±(99.9%) 3.046 ms/op [Average]
  (min, avg, max) = (5.344, 5.493, 5.673), stdev = 0.167
  CI (99.9%): [2.447, 8.539] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 6.459 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 5.204 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.737 ±(99.9%) 0.015 ms/op
Iteration   1: 4.313 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.063 ms/op
                 createUser·p0.50:   4.186 ms/op
                 createUser·p0.90:   5.571 ms/op
                 createUser·p0.95:   6.054 ms/op
                 createUser·p0.99:   7.938 ms/op
                 createUser·p0.999:  10.879 ms/op
                 createUser·p0.9999: 23.153 ms/op
                 createUser·p1.00:   23.560 ms/op

Iteration   2: 4.400 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.147 ms/op
                 createUser·p0.50:   4.301 ms/op
                 createUser·p0.90:   5.513 ms/op
                 createUser·p0.95:   6.013 ms/op
                 createUser·p0.99:   7.537 ms/op
                 createUser·p0.999:  11.133 ms/op
                 createUser·p0.9999: 20.447 ms/op
                 createUser·p1.00:   20.513 ms/op

Iteration   3: 4.525 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.029 ms/op
                 createUser·p0.50:   4.375 ms/op
                 createUser·p0.90:   5.661 ms/op
                 createUser·p0.95:   6.250 ms/op
                 createUser·p0.99:   8.241 ms/op
                 createUser·p0.999:  17.575 ms/op
                 createUser·p0.9999: 23.558 ms/op
                 createUser·p1.00:   23.888 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 217633
  mean =      4.411 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5026 
    [ 2.500,  5.000) = 164569 
    [ 5.000,  7.500) = 45199 
    [ 7.500, 10.000) = 2248 
    [10.000, 12.500) = 337 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.029 ms/op
     p(50.0000) =      4.293 ms/op
     p(90.0000) =      5.579 ms/op
     p(95.0000) =      6.095 ms/op
     p(99.0000) =      7.897 ms/op
     p(99.9000) =     13.025 ms/op
     p(99.9900) =     23.207 ms/op
     p(99.9990) =     23.757 ms/op
     p(99.9999) =     23.888 ms/op
    p(100.0000) =     23.888 ms/op


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
# Warmup Iteration   1: 6.441 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.479 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.213 ±(99.9%) 0.011 ms/op
Iteration   1: 4.095 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.069 ms/op
                 existUser·p0.50:   4.002 ms/op
                 existUser·p0.90:   5.153 ms/op
                 existUser·p0.95:   5.702 ms/op
                 existUser·p0.99:   7.569 ms/op
                 existUser·p0.999:  11.043 ms/op
                 existUser·p0.9999: 15.970 ms/op
                 existUser·p1.00:   31.982 ms/op

Iteration   2: 4.288 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.280 ms/op
                 existUser·p0.50:   4.112 ms/op
                 existUser·p0.90:   5.382 ms/op
                 existUser·p0.95:   5.964 ms/op
                 existUser·p0.99:   8.339 ms/op
                 existUser·p0.999:  14.959 ms/op
                 existUser·p0.9999: 20.152 ms/op
                 existUser·p1.00:   20.513 ms/op

Iteration   3: 4.234 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.822 ms/op
                 existUser·p0.50:   4.104 ms/op
                 existUser·p0.90:   5.210 ms/op
                 existUser·p0.95:   5.718 ms/op
                 existUser·p0.99:   8.471 ms/op
                 existUser·p0.999:  12.997 ms/op
                 existUser·p0.9999: 23.866 ms/op
                 existUser·p1.00:   24.347 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 228331
  mean =      4.204 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8254 
    [ 2.500,  5.000) = 187633 
    [ 5.000,  7.500) = 29281 
    [ 7.500, 10.000) = 2498 
    [10.000, 12.500) = 366 
    [12.500, 15.000) = 146 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.822 ms/op
     p(50.0000) =      4.067 ms/op
     p(90.0000) =      5.251 ms/op
     p(95.0000) =      5.800 ms/op
     p(99.0000) =      8.118 ms/op
     p(99.9000) =     13.222 ms/op
     p(99.9900) =     22.981 ms/op
     p(99.9990) =     24.328 ms/op
     p(99.9999) =     31.982 ms/op
    p(100.0000) =     31.982 ms/op


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
# Warmup Iteration   1: 6.556 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.713 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.548 ±(99.9%) 0.015 ms/op
Iteration   1: 4.524 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.270 ms/op
                 getUser·p0.50:   4.391 ms/op
                 getUser·p0.90:   5.964 ms/op
                 getUser·p0.95:   6.488 ms/op
                 getUser·p0.99:   8.798 ms/op
                 getUser·p0.999:  12.681 ms/op
                 getUser·p0.9999: 20.838 ms/op
                 getUser·p1.00:   21.070 ms/op

Iteration   2: 4.452 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.409 ms/op
                 getUser·p0.50:   4.325 ms/op
                 getUser·p0.90:   5.546 ms/op
                 getUser·p0.95:   6.078 ms/op
                 getUser·p0.99:   7.660 ms/op
                 getUser·p0.999:  10.690 ms/op
                 getUser·p0.9999: 17.501 ms/op
                 getUser·p1.00:   17.793 ms/op

Iteration   3: 4.479 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.049 ms/op
                 getUser·p0.50:   4.350 ms/op
                 getUser·p0.90:   5.587 ms/op
                 getUser·p0.95:   6.087 ms/op
                 getUser·p0.99:   7.719 ms/op
                 getUser·p0.999:  11.190 ms/op
                 getUser·p0.9999: 22.900 ms/op
                 getUser·p1.00:   23.429 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 213988
  mean =      4.485 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5651 
    [ 2.500,  5.000) = 157509 
    [ 5.000,  7.500) = 47768 
    [ 7.500, 10.000) = 2425 
    [10.000, 12.500) = 477 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.049 ms/op
     p(50.0000) =      4.358 ms/op
     p(90.0000) =      5.702 ms/op
     p(95.0000) =      6.250 ms/op
     p(99.0000) =      7.979 ms/op
     p(99.9000) =     11.747 ms/op
     p(99.9900) =     21.765 ms/op
     p(99.9990) =     23.317 ms/op
     p(99.9999) =     23.429 ms/op
    p(100.0000) =     23.429 ms/op


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
# Warmup Iteration   1: 8.233 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 6.851 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 6.099 ±(99.9%) 0.027 ms/op
Iteration   1: 6.051 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.747 ms/op
                 listUser·p0.50:   5.620 ms/op
                 listUser·p0.90:   8.503 ms/op
                 listUser·p0.95:   9.617 ms/op
                 listUser·p0.99:   12.239 ms/op
                 listUser·p0.999:  17.203 ms/op
                 listUser·p0.9999: 20.980 ms/op
                 listUser·p1.00:   22.184 ms/op

Iteration   2: 5.983 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.104 ms/op
                 listUser·p0.50:   5.636 ms/op
                 listUser·p0.90:   8.036 ms/op
                 listUser·p0.95:   9.077 ms/op
                 listUser·p0.99:   11.616 ms/op
                 listUser·p0.999:  19.679 ms/op
                 listUser·p0.9999: 22.845 ms/op
                 listUser·p1.00:   27.787 ms/op

Iteration   3: 5.925 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.530 ms/op
                 listUser·p0.50:   5.554 ms/op
                 listUser·p0.90:   7.946 ms/op
                 listUser·p0.95:   8.929 ms/op
                 listUser·p0.99:   11.376 ms/op
                 listUser·p0.999:  21.625 ms/op
                 listUser·p0.9999: 31.194 ms/op
                 listUser·p1.00:   31.621 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 160387
  mean =      5.986 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 132 
    [ 2.500,  5.000) = 44182 
    [ 5.000,  7.500) = 92273 
    [ 7.500, 10.000) = 19019 
    [10.000, 12.500) = 3729 
    [12.500, 15.000) = 644 
    [15.000, 17.500) = 181 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 11 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      5.603 ms/op
     p(90.0000) =      8.151 ms/op
     p(95.0000) =      9.224 ms/op
     p(99.0000) =     11.782 ms/op
     p(99.9000) =     19.419 ms/op
     p(99.9900) =     29.974 ms/op
     p(99.9990) =     31.502 ms/op
     p(99.9999) =     31.621 ms/op
    p(100.0000) =     31.621 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.125 ± 2.694  ops/ms
ClientGrpc.existUser                       thrpt       3   7.759 ± 2.984  ops/ms
ClientGrpc.getUser                         thrpt       3   7.625 ± 3.295  ops/ms
ClientGrpc.listUser                        thrpt       3   5.551 ± 2.078  ops/ms
ClientGrpc.createUser                       avgt       3   4.378 ± 0.951   ms/op
ClientGrpc.existUser                        avgt       3   4.082 ± 2.268   ms/op
ClientGrpc.getUser                          avgt       3   4.409 ± 3.018   ms/op
ClientGrpc.listUser                         avgt       3   5.493 ± 3.046   ms/op
ClientGrpc.createUser                     sample  217633   4.411 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.029           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.293           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.579           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.095           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.897           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.025           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.207           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.888           ms/op
ClientGrpc.existUser                      sample  228331   4.204 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.822           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.067           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.251           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.800           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.118           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.222           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.981           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          31.982           ms/op
ClientGrpc.getUser                        sample  213988   4.485 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.049           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.702           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.250           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.979           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.747           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.765           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.429           ms/op
ClientGrpc.listUser                       sample  160387   5.986 ± 0.014   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.104           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.603           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.151           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.224           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.782           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.419           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.974           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.621           ms/op
