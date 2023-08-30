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
# Warmup Iteration   1: 3.596 ops/ms
# Warmup Iteration   2: 8.503 ops/ms
# Warmup Iteration   3: 9.405 ops/ms
Iteration   1: 9.836 ops/ms
Iteration   2: 9.760 ops/ms
Iteration   3: 9.818 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.805 ±(99.9%) 0.729 ops/ms [Average]
  (min, avg, max) = (9.760, 9.805, 9.836), stdev = 0.040
  CI (99.9%): [9.076, 10.533] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 6.940 ops/ms
# Warmup Iteration   2: 9.649 ops/ms
# Warmup Iteration   3: 9.987 ops/ms
Iteration   1: 10.630 ops/ms
Iteration   2: 10.037 ops/ms
Iteration   3: 9.930 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.199 ±(99.9%) 6.886 ops/ms [Average]
  (min, avg, max) = (9.930, 10.199, 10.630), stdev = 0.377
  CI (99.9%): [3.313, 17.085] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.087 ops/ms
# Warmup Iteration   2: 9.147 ops/ms
# Warmup Iteration   3: 9.495 ops/ms
Iteration   1: 9.623 ops/ms
Iteration   2: 9.719 ops/ms
Iteration   3: 10.138 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.826 ±(99.9%) 4.996 ops/ms [Average]
  (min, avg, max) = (9.623, 9.826, 10.138), stdev = 0.274
  CI (99.9%): [4.830, 14.822] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.790 ops/ms
# Warmup Iteration   2: 7.136 ops/ms
# Warmup Iteration   3: 7.671 ops/ms
Iteration   1: 7.896 ops/ms
Iteration   2: 7.688 ops/ms
Iteration   3: 7.599 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.728 ±(99.9%) 2.779 ops/ms [Average]
  (min, avg, max) = (7.599, 7.728, 7.896), stdev = 0.152
  CI (99.9%): [4.949, 10.507] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.907 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.545 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.268 ±(99.9%) 0.008 ms/op
Iteration   1: 3.283 ±(99.9%) 0.003 ms/op
Iteration   2: 3.324 ±(99.9%) 0.004 ms/op
Iteration   3: 3.590 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.399 ±(99.9%) 3.037 ms/op [Average]
  (min, avg, max) = (3.283, 3.399, 3.590), stdev = 0.166
  CI (99.9%): [0.362, 6.436] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.804 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.540 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.003 ms/op
Iteration   1: 3.130 ±(99.9%) 0.003 ms/op
Iteration   2: 3.229 ±(99.9%) 0.002 ms/op
Iteration   3: 3.081 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.146 ±(99.9%) 1.369 ms/op [Average]
  (min, avg, max) = (3.081, 3.146, 3.229), stdev = 0.075
  CI (99.9%): [1.777, 4.516] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.782 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.498 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.270 ±(99.9%) 0.003 ms/op
Iteration   1: 3.234 ±(99.9%) 0.003 ms/op
Iteration   2: 3.247 ±(99.9%) 0.003 ms/op
Iteration   3: 3.263 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.248 ±(99.9%) 0.266 ms/op [Average]
  (min, avg, max) = (3.234, 3.248, 3.263), stdev = 0.015
  CI (99.9%): [2.982, 3.514] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 6.395 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.344 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.198 ±(99.9%) 0.015 ms/op
Iteration   1: 4.104 ±(99.9%) 0.034 ms/op
Iteration   2: 4.210 ±(99.9%) 0.019 ms/op
Iteration   3: 4.273 ±(99.9%) 0.033 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.196 ±(99.9%) 1.562 ms/op [Average]
  (min, avg, max) = (4.104, 4.196, 4.273), stdev = 0.086
  CI (99.9%): [2.634, 5.758] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.875 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.448 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.378 ±(99.9%) 0.008 ms/op
Iteration   1: 3.192 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.870 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   4.137 ms/op
                 createUser·p0.99:   5.194 ms/op
                 createUser·p0.999:  9.238 ms/op
                 createUser·p0.9999: 20.610 ms/op
                 createUser·p1.00:   22.217 ms/op

Iteration   2: 3.284 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.634 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.875 ms/op
                 createUser·p0.95:   4.133 ms/op
                 createUser·p0.99:   5.145 ms/op
                 createUser·p0.999:  10.191 ms/op
                 createUser·p0.9999: 20.276 ms/op
                 createUser·p1.00:   21.168 ms/op

Iteration   3: 3.322 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.907 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   3.990 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   5.251 ms/op
                 createUser·p0.999:  9.535 ms/op
                 createUser·p0.9999: 21.856 ms/op
                 createUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 293854
  mean =      3.265 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21074 
    [ 2.500,  5.000) = 269180 
    [ 5.000,  7.500) = 2835 
    [ 7.500, 10.000) = 517 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.634 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      5.202 ms/op
     p(99.9000) =      9.486 ms/op
     p(99.9900) =     21.594 ms/op
     p(99.9990) =     22.186 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.207 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.243 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.100 ±(99.9%) 0.007 ms/op
Iteration   1: 3.069 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.744 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.662 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   4.792 ms/op
                 existUser·p0.999:  7.548 ms/op
                 existUser·p0.9999: 15.767 ms/op
                 existUser·p1.00:   16.908 ms/op

Iteration   2: 3.263 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.555 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.895 ms/op
                 existUser·p0.95:   4.108 ms/op
                 existUser·p0.99:   4.992 ms/op
                 existUser·p0.999:  9.392 ms/op
                 existUser·p0.9999: 23.620 ms/op
                 existUser·p1.00:   24.314 ms/op

Iteration   3: 3.180 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.833 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   5.076 ms/op
                 existUser·p0.999:  7.397 ms/op
                 existUser·p0.9999: 16.768 ms/op
                 existUser·p1.00:   17.564 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 302677
  mean =      3.169 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23889 
    [ 2.500,  5.000) = 275929 
    [ 5.000,  7.500) = 2419 
    [ 7.500, 10.000) = 248 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      3.981 ms/op
     p(99.0000) =      4.932 ms/op
     p(99.9000) =      8.389 ms/op
     p(99.9900) =     21.889 ms/op
     p(99.9990) =     23.920 ms/op
     p(99.9999) =     24.314 ms/op
    p(100.0000) =     24.314 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.875 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.487 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.292 ±(99.9%) 0.009 ms/op
Iteration   1: 3.434 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.971 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   4.096 ms/op
                 getUser·p0.95:   4.407 ms/op
                 getUser·p0.99:   5.554 ms/op
                 getUser·p0.999:  11.345 ms/op
                 getUser·p0.9999: 17.782 ms/op
                 getUser·p1.00:   18.121 ms/op

Iteration   2: 3.306 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.595 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   5.333 ms/op
                 getUser·p0.999:  9.951 ms/op
                 getUser·p0.9999: 25.285 ms/op
                 getUser·p1.00:   25.756 ms/op

Iteration   3: 3.272 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.568 ms/op
                 getUser·p0.50:   3.244 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.125 ms/op
                 getUser·p0.99:   5.220 ms/op
                 getUser·p0.999:  10.150 ms/op
                 getUser·p0.9999: 17.898 ms/op
                 getUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 287971
  mean =      3.336 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16311 
    [ 2.500,  5.000) = 267252 
    [ 5.000,  7.500) = 3729 
    [ 7.500, 10.000) = 388 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.568 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      5.374 ms/op
     p(99.9000) =     10.060 ms/op
     p(99.9900) =     23.351 ms/op
     p(99.9990) =     25.632 ms/op
     p(99.9999) =     25.756 ms/op
    p(100.0000) =     25.756 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.427 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.837 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.382 ±(99.9%) 0.012 ms/op
Iteration   1: 4.241 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.368 ms/op
                 listUser·p0.50:   4.096 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.988 ms/op
                 listUser·p0.99:   7.708 ms/op
                 listUser·p0.999:  14.647 ms/op
                 listUser·p0.9999: 16.646 ms/op
                 listUser·p1.00:   17.039 ms/op

Iteration   2: 4.207 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.021 ms/op
                 listUser·p0.50:   4.022 ms/op
                 listUser·p0.90:   5.480 ms/op
                 listUser·p0.95:   6.169 ms/op
                 listUser·p0.99:   7.479 ms/op
                 listUser·p0.999:  18.317 ms/op
                 listUser·p0.9999: 25.146 ms/op
                 listUser·p1.00:   27.525 ms/op

Iteration   3: 4.237 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.348 ms/op
                 listUser·p0.50:   4.076 ms/op
                 listUser·p0.90:   5.374 ms/op
                 listUser·p0.95:   6.201 ms/op
                 listUser·p0.99:   7.864 ms/op
                 listUser·p0.999:  19.431 ms/op
                 listUser·p0.9999: 26.997 ms/op
                 listUser·p1.00:   27.558 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 227037
  mean =      4.228 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2253 
    [ 2.500,  5.000) = 193785 
    [ 5.000,  7.500) = 28287 
    [ 7.500, 10.000) = 2019 
    [10.000, 12.500) = 208 
    [12.500, 15.000) = 134 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 116 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.021 ms/op
     p(50.0000) =      4.067 ms/op
     p(90.0000) =      5.358 ms/op
     p(95.0000) =      6.128 ms/op
     p(99.0000) =      7.692 ms/op
     p(99.9000) =     16.809 ms/op
     p(99.9900) =     25.110 ms/op
     p(99.9990) =     27.549 ms/op
     p(99.9999) =     27.558 ms/op
    p(100.0000) =     27.558 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.805 ± 0.729  ops/ms
ClientGrpc.existUser                       thrpt       3  10.199 ± 6.886  ops/ms
ClientGrpc.getUser                         thrpt       3   9.826 ± 4.996  ops/ms
ClientGrpc.listUser                        thrpt       3   7.728 ± 2.779  ops/ms
ClientGrpc.createUser                       avgt       3   3.399 ± 3.037   ms/op
ClientGrpc.existUser                        avgt       3   3.146 ± 1.369   ms/op
ClientGrpc.getUser                          avgt       3   3.248 ± 0.266   ms/op
ClientGrpc.listUser                         avgt       3   4.196 ± 1.562   ms/op
ClientGrpc.createUser                     sample  293854   3.265 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.634           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.224           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.899           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.194           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.202           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.486           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.594           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.675           ms/op
ClientGrpc.existUser                      sample  302677   3.169 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.555           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.142           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.748           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.981           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.932           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.389           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.889           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.314           ms/op
ClientGrpc.getUser                        sample  287971   3.336 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.568           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.297           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.957           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.268           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.374           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.060           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.351           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.756           ms/op
ClientGrpc.listUser                       sample  227037   4.228 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.021           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.067           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.358           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.128           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.692           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.809           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.110           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.558           ms/op
