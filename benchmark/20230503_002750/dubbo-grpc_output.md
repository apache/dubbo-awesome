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
# Warmup Iteration   1: 3.049 ops/ms
# Warmup Iteration   2: 7.331 ops/ms
# Warmup Iteration   3: 8.478 ops/ms
Iteration   1: 9.029 ops/ms
Iteration   2: 9.251 ops/ms
Iteration   3: 9.221 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.167 ±(99.9%) 2.192 ops/ms [Average]
  (min, avg, max) = (9.029, 9.167, 9.251), stdev = 0.120
  CI (99.9%): [6.975, 11.359] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.259 ops/ms
# Warmup Iteration   2: 8.919 ops/ms
# Warmup Iteration   3: 9.488 ops/ms
Iteration   1: 9.267 ops/ms
Iteration   2: 9.500 ops/ms
Iteration   3: 9.421 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.396 ±(99.9%) 2.162 ops/ms [Average]
  (min, avg, max) = (9.267, 9.396, 9.500), stdev = 0.118
  CI (99.9%): [7.234, 11.558] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.706 ops/ms
# Warmup Iteration   2: 8.713 ops/ms
# Warmup Iteration   3: 9.005 ops/ms
Iteration   1: 9.252 ops/ms
Iteration   2: 9.215 ops/ms
Iteration   3: 9.226 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.231 ±(99.9%) 0.352 ops/ms [Average]
  (min, avg, max) = (9.215, 9.231, 9.252), stdev = 0.019
  CI (99.9%): [8.879, 9.583] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 5.212 ops/ms
# Warmup Iteration   2: 6.651 ops/ms
# Warmup Iteration   3: 7.102 ops/ms
Iteration   1: 6.982 ops/ms
Iteration   2: 7.008 ops/ms
Iteration   3: 7.304 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.098 ±(99.9%) 3.269 ops/ms [Average]
  (min, avg, max) = (6.982, 7.098, 7.304), stdev = 0.179
  CI (99.9%): [3.828, 10.367] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 4.725 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.611 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.376 ±(99.9%) 0.005 ms/op
Iteration   1: 3.437 ±(99.9%) 0.004 ms/op
Iteration   2: 3.391 ±(99.9%) 0.006 ms/op
Iteration   3: 3.422 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.417 ±(99.9%) 0.431 ms/op [Average]
  (min, avg, max) = (3.391, 3.417, 3.437), stdev = 0.024
  CI (99.9%): [2.986, 3.848] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.721 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.411 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.337 ±(99.9%) 0.004 ms/op
Iteration   1: 3.301 ±(99.9%) 0.002 ms/op
Iteration   2: 3.178 ±(99.9%) 0.003 ms/op
Iteration   3: 3.259 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.246 ±(99.9%) 1.142 ms/op [Average]
  (min, avg, max) = (3.178, 3.246, 3.301), stdev = 0.063
  CI (99.9%): [2.104, 4.389] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.955 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.553 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.468 ±(99.9%) 0.004 ms/op
Iteration   1: 3.439 ±(99.9%) 0.003 ms/op
Iteration   2: 3.400 ±(99.9%) 0.007 ms/op
Iteration   3: 3.386 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.408 ±(99.9%) 0.507 ms/op [Average]
  (min, avg, max) = (3.386, 3.408, 3.439), stdev = 0.028
  CI (99.9%): [2.901, 3.915] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.852 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.347 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.540 ±(99.9%) 0.012 ms/op
Iteration   1: 4.496 ±(99.9%) 0.015 ms/op
Iteration   2: 4.552 ±(99.9%) 0.011 ms/op
Iteration   3: 4.469 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.505 ±(99.9%) 0.769 ms/op [Average]
  (min, avg, max) = (4.469, 4.505, 4.552), stdev = 0.042
  CI (99.9%): [3.736, 5.275] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.775 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.597 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.453 ±(99.9%) 0.008 ms/op
Iteration   1: 3.341 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.071 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   4.022 ms/op
                 createUser·p0.99:   5.018 ms/op
                 createUser·p0.999:  6.966 ms/op
                 createUser·p0.9999: 19.806 ms/op
                 createUser·p1.00:   20.054 ms/op

Iteration   2: 3.396 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.985 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   4.727 ms/op
                 createUser·p0.999:  7.674 ms/op
                 createUser·p0.9999: 15.319 ms/op
                 createUser·p1.00:   15.974 ms/op

Iteration   3: 3.434 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.767 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   3.953 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   5.464 ms/op
                 createUser·p0.999:  16.613 ms/op
                 createUser·p0.9999: 27.722 ms/op
                 createUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 283002
  mean =      3.390 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7233 
    [ 2.500,  5.000) = 272760 
    [ 5.000,  7.500) = 2507 
    [ 7.500, 10.000) = 169 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.767 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.170 ms/op
     p(99.0000) =      5.071 ms/op
     p(99.9000) =     10.912 ms/op
     p(99.9900) =     27.407 ms/op
     p(99.9990) =     27.858 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.618 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.447 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.294 ±(99.9%) 0.007 ms/op
Iteration   1: 3.275 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.862 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   3.772 ms/op
                 existUser·p0.95:   3.953 ms/op
                 existUser·p0.99:   4.801 ms/op
                 existUser·p0.999:  8.233 ms/op
                 existUser·p0.9999: 29.335 ms/op
                 existUser·p1.00:   29.622 ms/op

Iteration   2: 3.230 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.840 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.768 ms/op
                 existUser·p0.95:   3.969 ms/op
                 existUser·p0.99:   4.628 ms/op
                 existUser·p0.999:  7.136 ms/op
                 existUser·p0.9999: 14.189 ms/op
                 existUser·p1.00:   16.695 ms/op

Iteration   3: 3.270 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.673 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.768 ms/op
                 existUser·p0.95:   4.092 ms/op
                 existUser·p0.99:   4.940 ms/op
                 existUser·p0.999:  9.644 ms/op
                 existUser·p0.9999: 19.439 ms/op
                 existUser·p1.00:   19.694 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 294506
  mean =      3.259 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17084 
    [ 2.500,  5.000) = 275102 
    [ 5.000,  7.500) = 1966 
    [ 7.500, 10.000) = 139 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.673 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.768 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      4.792 ms/op
     p(99.9000) =      8.233 ms/op
     p(99.9900) =     28.497 ms/op
     p(99.9990) =     29.526 ms/op
     p(99.9999) =     29.622 ms/op
    p(100.0000) =     29.622 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.966 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.550 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.515 ±(99.9%) 0.007 ms/op
Iteration   1: 3.446 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.529 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   3.998 ms/op
                 getUser·p0.95:   4.301 ms/op
                 getUser·p0.99:   5.562 ms/op
                 getUser·p0.999:  13.189 ms/op
                 getUser·p0.9999: 16.653 ms/op
                 getUser·p1.00:   16.974 ms/op

Iteration   2: 3.473 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.872 ms/op
                 getUser·p0.50:   3.428 ms/op
                 getUser·p0.90:   4.084 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   5.390 ms/op
                 getUser·p0.999:  10.198 ms/op
                 getUser·p0.9999: 15.479 ms/op
                 getUser·p1.00:   15.794 ms/op

Iteration   3: 3.461 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.935 ms/op
                 getUser·p0.50:   3.424 ms/op
                 getUser·p0.90:   4.211 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   5.210 ms/op
                 getUser·p0.999:  7.092 ms/op
                 getUser·p0.9999: 16.245 ms/op
                 getUser·p1.00:   16.613 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 277352
  mean =      3.460 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 261 
    [ 1.250,  2.500) = 9683 
    [ 2.500,  3.750) = 199928 
    [ 3.750,  5.000) = 63323 
    [ 5.000,  6.250) = 3076 
    [ 6.250,  7.500) = 480 
    [ 7.500,  8.750) = 205 
    [ 8.750, 10.000) = 117 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 86 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 58 
    [16.250, 17.500) = 37 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.529 ms/op
     p(50.0000) =      3.416 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.374 ms/op
     p(99.9000) =     10.065 ms/op
     p(99.9900) =     16.433 ms/op
     p(99.9990) =     16.883 ms/op
     p(99.9999) =     16.974 ms/op
    p(100.0000) =     16.974 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.415 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.741 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.519 ±(99.9%) 0.012 ms/op
Iteration   1: 4.509 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.534 ms/op
                 listUser·p0.50:   4.309 ms/op
                 listUser·p0.90:   5.693 ms/op
                 listUser·p0.95:   6.554 ms/op
                 listUser·p0.99:   8.271 ms/op
                 listUser·p0.999:  16.324 ms/op
                 listUser·p0.9999: 24.665 ms/op
                 listUser·p1.00:   25.035 ms/op

Iteration   2: 4.458 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.188 ms/op
                 listUser·p0.50:   4.301 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   6.144 ms/op
                 listUser·p0.99:   7.864 ms/op
                 listUser·p0.999:  16.454 ms/op
                 listUser·p0.9999: 23.805 ms/op
                 listUser·p1.00:   24.281 ms/op

Iteration   3: 4.359 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.967 ms/op
                 listUser·p0.50:   4.190 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   6.152 ms/op
                 listUser·p0.99:   7.782 ms/op
                 listUser·p0.999:  19.464 ms/op
                 listUser·p0.9999: 22.053 ms/op
                 listUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 216031
  mean =      4.441 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 646 
    [ 2.500,  5.000) = 184921 
    [ 5.000,  7.500) = 27055 
    [ 7.500, 10.000) = 2766 
    [10.000, 12.500) = 216 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 139 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.967 ms/op
     p(50.0000) =      4.268 ms/op
     p(90.0000) =      5.407 ms/op
     p(95.0000) =      6.308 ms/op
     p(99.0000) =      7.954 ms/op
     p(99.9000) =     17.660 ms/op
     p(99.9900) =     23.691 ms/op
     p(99.9990) =     24.970 ms/op
     p(99.9999) =     25.035 ms/op
    p(100.0000) =     25.035 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.167 ± 2.192  ops/ms
ClientGrpc.existUser                       thrpt       3   9.396 ± 2.162  ops/ms
ClientGrpc.getUser                         thrpt       3   9.231 ± 0.352  ops/ms
ClientGrpc.listUser                        thrpt       3   7.098 ± 3.269  ops/ms
ClientGrpc.createUser                       avgt       3   3.417 ± 0.431   ms/op
ClientGrpc.existUser                        avgt       3   3.246 ± 1.142   ms/op
ClientGrpc.getUser                          avgt       3   3.408 ± 0.507   ms/op
ClientGrpc.listUser                         avgt       3   4.505 ± 0.769   ms/op
ClientGrpc.createUser                     sample  283002   3.390 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.767           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.355           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.883           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.170           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.071           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.912           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.407           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.886           ms/op
ClientGrpc.existUser                      sample  294506   3.259 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.673           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.265           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.768           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.994           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.792           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.233           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          28.497           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.622           ms/op
ClientGrpc.getUser                        sample  277352   3.460 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.529           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.416           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.100           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.366           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.374           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.065           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.433           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.974           ms/op
ClientGrpc.listUser                       sample  216031   4.441 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.967           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.268           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.407           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.308           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.954           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.660           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.691           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.035           ms/op
