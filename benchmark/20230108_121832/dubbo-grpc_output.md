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
# Warmup Iteration   1: 3.806 ops/ms
# Warmup Iteration   2: 8.189 ops/ms
# Warmup Iteration   3: 9.179 ops/ms
Iteration   1: 9.425 ops/ms
Iteration   2: 9.822 ops/ms
Iteration   3: 9.697 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.648 ±(99.9%) 3.704 ops/ms [Average]
  (min, avg, max) = (9.425, 9.648, 9.822), stdev = 0.203
  CI (99.9%): [5.944, 13.352] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 6.824 ops/ms
# Warmup Iteration   2: 9.800 ops/ms
# Warmup Iteration   3: 10.249 ops/ms
Iteration   1: 10.099 ops/ms
Iteration   2: 10.182 ops/ms
Iteration   3: 10.154 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.145 ±(99.9%) 0.771 ops/ms [Average]
  (min, avg, max) = (10.099, 10.145, 10.182), stdev = 0.042
  CI (99.9%): [9.374, 10.916] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 5.985 ops/ms
# Warmup Iteration   2: 9.390 ops/ms
# Warmup Iteration   3: 9.809 ops/ms
Iteration   1: 9.701 ops/ms
Iteration   2: 9.847 ops/ms
Iteration   3: 9.515 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.688 ±(99.9%) 3.030 ops/ms [Average]
  (min, avg, max) = (9.515, 9.688, 9.847), stdev = 0.166
  CI (99.9%): [6.658, 12.718] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.310 ops/ms
# Warmup Iteration   2: 6.596 ops/ms
# Warmup Iteration   3: 7.291 ops/ms
Iteration   1: 7.239 ops/ms
Iteration   2: 7.397 ops/ms
Iteration   3: 7.211 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.282 ±(99.9%) 1.824 ops/ms [Average]
  (min, avg, max) = (7.211, 7.282, 7.397), stdev = 0.100
  CI (99.9%): [5.458, 9.106] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.923 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.611 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.493 ±(99.9%) 0.003 ms/op
Iteration   1: 3.549 ±(99.9%) 0.002 ms/op
Iteration   2: 3.575 ±(99.9%) 0.002 ms/op
Iteration   3: 3.559 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.561 ±(99.9%) 0.236 ms/op [Average]
  (min, avg, max) = (3.549, 3.561, 3.575), stdev = 0.013
  CI (99.9%): [3.325, 3.797] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.749 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.680 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.327 ±(99.9%) 0.003 ms/op
Iteration   1: 3.251 ±(99.9%) 0.002 ms/op
Iteration   2: 3.427 ±(99.9%) 0.002 ms/op
Iteration   3: 3.353 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.344 ±(99.9%) 1.612 ms/op [Average]
  (min, avg, max) = (3.251, 3.344, 3.427), stdev = 0.088
  CI (99.9%): [1.732, 4.956] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.810 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.523 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.342 ±(99.9%) 0.002 ms/op
Iteration   1: 3.247 ±(99.9%) 0.002 ms/op
Iteration   2: 3.351 ±(99.9%) 0.002 ms/op
Iteration   3: 3.356 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.318 ±(99.9%) 1.120 ms/op [Average]
  (min, avg, max) = (3.247, 3.318, 3.356), stdev = 0.061
  CI (99.9%): [2.198, 4.438] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 6.219 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.525 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.255 ±(99.9%) 0.008 ms/op
Iteration   1: 4.232 ±(99.9%) 0.009 ms/op
Iteration   2: 3.947 ±(99.9%) 0.005 ms/op
Iteration   3: 4.317 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.165 ±(99.9%) 3.531 ms/op [Average]
  (min, avg, max) = (3.947, 4.165, 4.317), stdev = 0.194
  CI (99.9%): [0.634, 7.697] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.746 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.457 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.397 ±(99.9%) 0.007 ms/op
Iteration   1: 3.428 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.685 ms/op
                 createUser·p0.50:   3.437 ms/op
                 createUser·p0.90:   4.219 ms/op
                 createUser·p0.95:   4.415 ms/op
                 createUser·p0.99:   4.891 ms/op
                 createUser·p0.999:  7.059 ms/op
                 createUser·p0.9999: 13.418 ms/op
                 createUser·p1.00:   13.976 ms/op

Iteration   2: 3.328 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.932 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.990 ms/op
                 createUser·p0.95:   4.190 ms/op
                 createUser·p0.99:   4.637 ms/op
                 createUser·p0.999:  7.626 ms/op
                 createUser·p0.9999: 15.499 ms/op
                 createUser·p1.00:   15.712 ms/op

Iteration   3: 3.263 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.282 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   4.765 ms/op
                 createUser·p0.999:  10.584 ms/op
                 createUser·p0.9999: 28.885 ms/op
                 createUser·p1.00:   29.327 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 287573
  mean =      3.338 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10688 
    [ 2.500,  5.000) = 275038 
    [ 5.000,  7.500) = 1484 
    [ 7.500, 10.000) = 145 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.282 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      4.784 ms/op
     p(99.9000) =      7.842 ms/op
     p(99.9900) =     27.918 ms/op
     p(99.9990) =     29.233 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.612 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.312 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.270 ±(99.9%) 0.007 ms/op
Iteration   1: 3.146 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.656 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.867 ms/op
                 existUser·p0.95:   4.092 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  8.566 ms/op
                 existUser·p0.9999: 16.277 ms/op
                 existUser·p1.00:   16.744 ms/op

Iteration   2: 3.235 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.881 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.973 ms/op
                 existUser·p0.95:   4.178 ms/op
                 existUser·p0.99:   4.547 ms/op
                 existUser·p0.999:  6.523 ms/op
                 existUser·p0.9999: 16.663 ms/op
                 existUser·p1.00:   17.236 ms/op

Iteration   3: 3.252 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.826 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   4.030 ms/op
                 existUser·p0.95:   4.276 ms/op
                 existUser·p0.99:   4.792 ms/op
                 existUser·p0.999:  7.354 ms/op
                 existUser·p0.9999: 18.525 ms/op
                 existUser·p1.00:   19.169 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 298962
  mean =      3.210 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1046 
    [ 1.250,  2.500) = 22768 
    [ 2.500,  3.750) = 224444 
    [ 3.750,  5.000) = 49382 
    [ 5.000,  6.250) = 826 
    [ 6.250,  7.500) = 205 
    [ 7.500,  8.750) = 99 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 47 
    [17.500, 18.750) = 41 

  Percentiles, ms/op:
      p(0.0000) =      0.656 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.186 ms/op
     p(99.0000) =      4.620 ms/op
     p(99.9000) =      7.463 ms/op
     p(99.9900) =     17.924 ms/op
     p(99.9990) =     19.071 ms/op
     p(99.9999) =     19.169 ms/op
    p(100.0000) =     19.169 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.880 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.550 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.342 ±(99.9%) 0.007 ms/op
Iteration   1: 3.382 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.859 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   4.100 ms/op
                 getUser·p0.95:   4.317 ms/op
                 getUser·p0.99:   4.743 ms/op
                 getUser·p0.999:  8.265 ms/op
                 getUser·p0.9999: 15.770 ms/op
                 getUser·p1.00:   16.564 ms/op

Iteration   2: 3.420 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.014 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   4.129 ms/op
                 getUser·p0.95:   4.342 ms/op
                 getUser·p0.99:   4.882 ms/op
                 getUser·p0.999:  9.707 ms/op
                 getUser·p0.9999: 15.351 ms/op
                 getUser·p1.00:   15.860 ms/op

Iteration   3: 3.305 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.659 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   4.030 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   4.719 ms/op
                 getUser·p0.999:  7.291 ms/op
                 getUser·p0.9999: 17.891 ms/op
                 getUser·p1.00:   18.219 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 284829
  mean =      3.368 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 304 
    [ 1.250,  2.500) = 14773 
    [ 2.500,  3.750) = 200163 
    [ 3.750,  5.000) = 67888 
    [ 5.000,  6.250) = 972 
    [ 6.250,  7.500) = 245 
    [ 7.500,  8.750) = 205 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 56 
    [15.000, 16.250) = 69 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.659 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      4.088 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      4.784 ms/op
     p(99.9000) =      8.703 ms/op
     p(99.9900) =     17.482 ms/op
     p(99.9990) =     18.131 ms/op
     p(99.9999) =     18.219 ms/op
    p(100.0000) =     18.219 ms/op


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
# Warmup Iteration   1: 5.544 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.525 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.307 ±(99.9%) 0.012 ms/op
Iteration   1: 4.390 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.642 ms/op
                 listUser·p0.50:   4.166 ms/op
                 listUser·p0.90:   5.628 ms/op
                 listUser·p0.95:   6.259 ms/op
                 listUser·p0.99:   7.610 ms/op
                 listUser·p0.999:  14.828 ms/op
                 listUser·p0.9999: 17.175 ms/op
                 listUser·p1.00:   18.121 ms/op

Iteration   2: 4.282 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.548 ms/op
                 listUser·p0.50:   4.071 ms/op
                 listUser·p0.90:   5.489 ms/op
                 listUser·p0.95:   6.078 ms/op
                 listUser·p0.99:   7.447 ms/op
                 listUser·p0.999:  15.508 ms/op
                 listUser·p0.9999: 21.496 ms/op
                 listUser·p1.00:   22.020 ms/op

Iteration   3: 4.318 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.163 ms/op
                 listUser·p0.50:   4.108 ms/op
                 listUser·p0.90:   5.472 ms/op
                 listUser·p0.95:   5.997 ms/op
                 listUser·p0.99:   7.627 ms/op
                 listUser·p0.999:  18.872 ms/op
                 listUser·p0.9999: 26.725 ms/op
                 listUser·p1.00:   27.558 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 221673
  mean =      4.330 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 725 
    [ 2.500,  5.000) = 184843 
    [ 5.000,  7.500) = 33757 
    [ 7.500, 10.000) = 1909 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 153 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.163 ms/op
     p(50.0000) =      4.112 ms/op
     p(90.0000) =      5.538 ms/op
     p(95.0000) =      6.111 ms/op
     p(99.0000) =      7.553 ms/op
     p(99.9000) =     15.598 ms/op
     p(99.9900) =     26.209 ms/op
     p(99.9990) =     27.125 ms/op
     p(99.9999) =     27.558 ms/op
    p(100.0000) =     27.558 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.648 ± 3.704  ops/ms
ClientGrpc.existUser                       thrpt       3  10.145 ± 0.771  ops/ms
ClientGrpc.getUser                         thrpt       3   9.688 ± 3.030  ops/ms
ClientGrpc.listUser                        thrpt       3   7.282 ± 1.824  ops/ms
ClientGrpc.createUser                       avgt       3   3.561 ± 0.236   ms/op
ClientGrpc.existUser                        avgt       3   3.344 ± 1.612   ms/op
ClientGrpc.getUser                          avgt       3   3.318 ± 1.120   ms/op
ClientGrpc.listUser                         avgt       3   4.165 ± 3.531   ms/op
ClientGrpc.createUser                     sample  287573   3.338 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.282           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.305           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.010           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.260           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.784           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.842           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.918           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.327           ms/op
ClientGrpc.existUser                      sample  298962   3.210 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.656           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.195           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.961           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.186           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.620           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.463           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.924           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.169           ms/op
ClientGrpc.getUser                        sample  284829   3.368 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.659           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.355           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.088           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.301           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.784           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.703           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.482           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.219           ms/op
ClientGrpc.listUser                       sample  221673   4.330 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.163           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.112           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.538           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.111           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.553           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.598           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.209           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.558           ms/op
