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
# Warmup Iteration   1: 3.309 ops/ms
# Warmup Iteration   2: 7.152 ops/ms
# Warmup Iteration   3: 8.372 ops/ms
Iteration   1: 9.227 ops/ms
Iteration   2: 8.876 ops/ms
Iteration   3: 8.803 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.969 ±(99.9%) 4.135 ops/ms [Average]
  (min, avg, max) = (8.803, 8.969, 9.227), stdev = 0.227
  CI (99.9%): [4.834, 13.103] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.139 ops/ms
# Warmup Iteration   2: 8.597 ops/ms
# Warmup Iteration   3: 9.041 ops/ms
Iteration   1: 9.327 ops/ms
Iteration   2: 9.240 ops/ms
Iteration   3: 9.313 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.293 ±(99.9%) 0.848 ops/ms [Average]
  (min, avg, max) = (9.240, 9.293, 9.327), stdev = 0.047
  CI (99.9%): [8.445, 10.142] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.382 ops/ms
# Warmup Iteration   2: 8.317 ops/ms
# Warmup Iteration   3: 8.758 ops/ms
Iteration   1: 8.641 ops/ms
Iteration   2: 8.740 ops/ms
Iteration   3: 8.736 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.706 ±(99.9%) 1.025 ops/ms [Average]
  (min, avg, max) = (8.641, 8.706, 8.740), stdev = 0.056
  CI (99.9%): [7.681, 9.730] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.728 ops/ms
# Warmup Iteration   2: 6.096 ops/ms
# Warmup Iteration   3: 6.614 ops/ms
Iteration   1: 6.656 ops/ms
Iteration   2: 6.710 ops/ms
Iteration   3: 7.067 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.811 ±(99.9%) 4.077 ops/ms [Average]
  (min, avg, max) = (6.656, 6.811, 7.067), stdev = 0.223
  CI (99.9%): [2.735, 10.888] (assumes normal distribution)


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
# Warmup Iteration   1: 5.258 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.828 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.715 ±(99.9%) 0.009 ms/op
Iteration   1: 3.554 ±(99.9%) 0.003 ms/op
Iteration   2: 3.586 ±(99.9%) 0.004 ms/op
Iteration   3: 3.572 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.571 ±(99.9%) 0.293 ms/op [Average]
  (min, avg, max) = (3.554, 3.571, 3.586), stdev = 0.016
  CI (99.9%): [3.277, 3.864] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.927 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.563 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.481 ±(99.9%) 0.003 ms/op
Iteration   1: 3.423 ±(99.9%) 0.004 ms/op
Iteration   2: 3.410 ±(99.9%) 0.003 ms/op
Iteration   3: 3.441 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.425 ±(99.9%) 0.286 ms/op [Average]
  (min, avg, max) = (3.410, 3.425, 3.441), stdev = 0.016
  CI (99.9%): [3.139, 3.711] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.258 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.769 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.613 ±(99.9%) 0.004 ms/op
Iteration   1: 3.622 ±(99.9%) 0.005 ms/op
Iteration   2: 3.496 ±(99.9%) 0.004 ms/op
Iteration   3: 3.510 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.542 ±(99.9%) 1.263 ms/op [Average]
  (min, avg, max) = (3.496, 3.542, 3.622), stdev = 0.069
  CI (99.9%): [2.279, 4.806] (assumes normal distribution)


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
# Warmup Iteration   1: 5.907 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.996 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.625 ±(99.9%) 0.011 ms/op
Iteration   1: 4.668 ±(99.9%) 0.020 ms/op
Iteration   2: 4.476 ±(99.9%) 0.016 ms/op
Iteration   3: 4.495 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.546 ±(99.9%) 1.930 ms/op [Average]
  (min, avg, max) = (4.476, 4.546, 4.668), stdev = 0.106
  CI (99.9%): [2.616, 6.476] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.253 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.735 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.494 ±(99.9%) 0.009 ms/op
Iteration   1: 3.602 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.671 ms/op
                 createUser·p0.50:   3.551 ms/op
                 createUser·p0.90:   4.190 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   5.120 ms/op
                 createUser·p0.999:  11.559 ms/op
                 createUser·p0.9999: 14.270 ms/op
                 createUser·p1.00:   15.303 ms/op

Iteration   2: 3.549 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.972 ms/op
                 createUser·p0.50:   3.518 ms/op
                 createUser·p0.90:   4.051 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   5.071 ms/op
                 createUser·p0.999:  7.643 ms/op
                 createUser·p0.9999: 15.843 ms/op
                 createUser·p1.00:   16.138 ms/op

Iteration   3: 3.567 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.937 ms/op
                 createUser·p0.50:   3.531 ms/op
                 createUser·p0.90:   4.137 ms/op
                 createUser·p0.95:   4.391 ms/op
                 createUser·p0.99:   5.241 ms/op
                 createUser·p0.999:  8.230 ms/op
                 createUser·p0.9999: 21.594 ms/op
                 createUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 268567
  mean =      3.573 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4595 
    [ 2.500,  5.000) = 260598 
    [ 5.000,  7.500) = 2875 
    [ 7.500, 10.000) = 238 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.671 ms/op
     p(50.0000) =      3.535 ms/op
     p(90.0000) =      4.125 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.136 ms/op
     p(99.9000) =      9.498 ms/op
     p(99.9900) =     19.567 ms/op
     p(99.9990) =     21.854 ms/op
     p(99.9999) =     21.922 ms/op
    p(100.0000) =     21.922 ms/op


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
# Warmup Iteration   1: 4.821 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.555 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.439 ±(99.9%) 0.007 ms/op
Iteration   1: 3.432 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.951 ms/op
                 existUser·p0.50:   3.408 ms/op
                 existUser·p0.90:   3.998 ms/op
                 existUser·p0.95:   4.252 ms/op
                 existUser·p0.99:   4.956 ms/op
                 existUser·p0.999:  7.266 ms/op
                 existUser·p0.9999: 14.375 ms/op
                 existUser·p1.00:   14.713 ms/op

Iteration   2: 3.394 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.863 ms/op
                 existUser·p0.50:   3.371 ms/op
                 existUser·p0.90:   3.903 ms/op
                 existUser·p0.95:   4.104 ms/op
                 existUser·p0.99:   4.964 ms/op
                 existUser·p0.999:  10.649 ms/op
                 existUser·p0.9999: 13.222 ms/op
                 existUser·p1.00:   13.713 ms/op

Iteration   3: 3.349 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.783 ms/op
                 existUser·p0.50:   3.355 ms/op
                 existUser·p0.90:   3.842 ms/op
                 existUser·p0.95:   4.076 ms/op
                 existUser·p0.99:   4.841 ms/op
                 existUser·p0.999:  6.408 ms/op
                 existUser·p0.9999: 20.312 ms/op
                 existUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 283320
  mean =      3.391 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9395 
    [ 2.500,  5.000) = 271347 
    [ 5.000,  7.500) = 2224 
    [ 7.500, 10.000) = 144 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.783 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      3.919 ms/op
     p(95.0000) =      4.145 ms/op
     p(99.0000) =      4.915 ms/op
     p(99.9000) =      8.042 ms/op
     p(99.9900) =     18.208 ms/op
     p(99.9990) =     20.682 ms/op
     p(99.9999) =     20.808 ms/op
    p(100.0000) =     20.808 ms/op


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
# Warmup Iteration   1: 5.191 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.769 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.583 ±(99.9%) 0.007 ms/op
Iteration   1: 3.601 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.944 ms/op
                 getUser·p0.50:   3.547 ms/op
                 getUser·p0.90:   4.219 ms/op
                 getUser·p0.95:   4.465 ms/op
                 getUser·p0.99:   5.489 ms/op
                 getUser·p0.999:  9.244 ms/op
                 getUser·p0.9999: 16.845 ms/op
                 getUser·p1.00:   18.547 ms/op

Iteration   2: 3.576 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.899 ms/op
                 getUser·p0.50:   3.535 ms/op
                 getUser·p0.90:   4.162 ms/op
                 getUser·p0.95:   4.440 ms/op
                 getUser·p0.99:   5.448 ms/op
                 getUser·p0.999:  8.191 ms/op
                 getUser·p0.9999: 28.642 ms/op
                 getUser·p1.00:   29.753 ms/op

Iteration   3: 3.570 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.819 ms/op
                 getUser·p0.50:   3.564 ms/op
                 getUser·p0.90:   4.141 ms/op
                 getUser·p0.95:   4.440 ms/op
                 getUser·p0.99:   5.284 ms/op
                 getUser·p0.999:  7.846 ms/op
                 getUser·p0.9999: 19.138 ms/op
                 getUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 267862
  mean =      3.582 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6650 
    [ 2.500,  5.000) = 256932 
    [ 5.000,  7.500) = 3843 
    [ 7.500, 10.000) = 251 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.819 ms/op
     p(50.0000) =      3.547 ms/op
     p(90.0000) =      4.174 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.415 ms/op
     p(99.9000) =      8.489 ms/op
     p(99.9900) =     27.761 ms/op
     p(99.9990) =     29.375 ms/op
     p(99.9999) =     29.753 ms/op
    p(100.0000) =     29.753 ms/op


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
# Warmup Iteration   1: 5.849 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 5.057 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.697 ±(99.9%) 0.015 ms/op
Iteration   1: 4.701 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.071 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.890 ms/op
                 listUser·p0.95:   6.595 ms/op
                 listUser·p0.99:   8.241 ms/op
                 listUser·p0.999:  15.711 ms/op
                 listUser·p0.9999: 17.937 ms/op
                 listUser·p1.00:   21.070 ms/op

Iteration   2: 4.733 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.282 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   6.005 ms/op
                 listUser·p0.95:   6.709 ms/op
                 listUser·p0.99:   8.274 ms/op
                 listUser·p0.999:  16.637 ms/op
                 listUser·p0.9999: 23.175 ms/op
                 listUser·p1.00:   23.495 ms/op

Iteration   3: 4.618 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.053 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   5.743 ms/op
                 listUser·p0.95:   6.627 ms/op
                 listUser·p0.99:   8.067 ms/op
                 listUser·p0.999:  19.195 ms/op
                 listUser·p0.9999: 22.159 ms/op
                 listUser·p1.00:   22.643 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 204876
  mean =      4.684 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 535 
    [ 2.500,  5.000) = 159274 
    [ 5.000,  7.500) = 40684 
    [ 7.500, 10.000) = 3682 
    [10.000, 12.500) = 310 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 130 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      4.497 ms/op
     p(90.0000) =      5.898 ms/op
     p(95.0000) =      6.644 ms/op
     p(99.0000) =      8.200 ms/op
     p(99.9000) =     16.476 ms/op
     p(99.9900) =     22.348 ms/op
     p(99.9990) =     23.393 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.969 ± 4.135  ops/ms
ClientGrpc.existUser                       thrpt       3   9.293 ± 0.848  ops/ms
ClientGrpc.getUser                         thrpt       3   8.706 ± 1.025  ops/ms
ClientGrpc.listUser                        thrpt       3   6.811 ± 4.077  ops/ms
ClientGrpc.createUser                       avgt       3   3.571 ± 0.293   ms/op
ClientGrpc.existUser                        avgt       3   3.425 ± 0.286   ms/op
ClientGrpc.getUser                          avgt       3   3.542 ± 1.263   ms/op
ClientGrpc.listUser                         avgt       3   4.546 ± 1.930   ms/op
ClientGrpc.createUser                     sample  268567   3.573 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.671           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.535           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.125           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.383           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.136           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.498           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.567           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.922           ms/op
ClientGrpc.existUser                      sample  283320   3.391 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.783           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.375           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.919           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.145           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.915           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.042           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.208           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.808           ms/op
ClientGrpc.getUser                        sample  267862   3.582 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.819           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.547           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.174           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.448           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.415           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.489           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.761           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.753           ms/op
ClientGrpc.listUser                       sample  204876   4.684 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.053           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.497           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.898           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.644           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.200           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.476           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.348           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.495           ms/op
