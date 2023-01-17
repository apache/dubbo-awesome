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
# Warmup Iteration   1: 2.303 ops/ms
# Warmup Iteration   2: 5.693 ops/ms
# Warmup Iteration   3: 6.841 ops/ms
Iteration   1: 7.003 ops/ms
Iteration   2: 6.997 ops/ms
Iteration   3: 7.198 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.066 ±(99.9%) 2.087 ops/ms [Average]
  (min, avg, max) = (6.997, 7.066, 7.198), stdev = 0.114
  CI (99.9%): [4.979, 9.153] (assumes normal distribution)


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
# Warmup Iteration   1: 4.631 ops/ms
# Warmup Iteration   2: 6.259 ops/ms
# Warmup Iteration   3: 7.244 ops/ms
Iteration   1: 7.395 ops/ms
Iteration   2: 7.409 ops/ms
Iteration   3: 7.577 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.460 ±(99.9%) 1.842 ops/ms [Average]
  (min, avg, max) = (7.395, 7.460, 7.577), stdev = 0.101
  CI (99.9%): [5.619, 9.302] (assumes normal distribution)


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
# Warmup Iteration   1: 4.096 ops/ms
# Warmup Iteration   2: 6.626 ops/ms
# Warmup Iteration   3: 6.985 ops/ms
Iteration   1: 7.275 ops/ms
Iteration   2: 6.768 ops/ms
Iteration   3: 6.900 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.981 ±(99.9%) 4.797 ops/ms [Average]
  (min, avg, max) = (6.768, 6.981, 7.275), stdev = 0.263
  CI (99.9%): [2.184, 11.779] (assumes normal distribution)


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
# Warmup Iteration   1: 3.645 ops/ms
# Warmup Iteration   2: 4.901 ops/ms
# Warmup Iteration   3: 5.323 ops/ms
Iteration   1: 5.082 ops/ms
Iteration   2: 5.706 ops/ms
Iteration   3: 5.639 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.476 ±(99.9%) 6.251 ops/ms [Average]
  (min, avg, max) = (5.082, 5.476, 5.706), stdev = 0.343
  CI (99.9%): [≈ 0, 11.727] (assumes normal distribution)


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
# Warmup Iteration   1: 6.224 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.608 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.414 ±(99.9%) 0.003 ms/op
Iteration   1: 4.503 ±(99.9%) 0.004 ms/op
Iteration   2: 4.778 ±(99.9%) 0.004 ms/op
Iteration   3: 4.831 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.704 ±(99.9%) 3.212 ms/op [Average]
  (min, avg, max) = (4.503, 4.704, 4.831), stdev = 0.176
  CI (99.9%): [1.492, 7.916] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.039 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.657 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.607 ±(99.9%) 0.010 ms/op
Iteration   1: 4.511 ±(99.9%) 0.003 ms/op
Iteration   2: 4.449 ±(99.9%) 0.004 ms/op
Iteration   3: 4.490 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.483 ±(99.9%) 0.578 ms/op [Average]
  (min, avg, max) = (4.449, 4.483, 4.511), stdev = 0.032
  CI (99.9%): [3.905, 5.061] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.697 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 5.025 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.880 ±(99.9%) 0.006 ms/op
Iteration   1: 4.645 ±(99.9%) 0.005 ms/op
Iteration   2: 4.566 ±(99.9%) 0.003 ms/op
Iteration   3: 4.543 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.585 ±(99.9%) 0.972 ms/op [Average]
  (min, avg, max) = (4.543, 4.585, 4.645), stdev = 0.053
  CI (99.9%): [3.612, 5.557] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.155 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 6.181 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.793 ±(99.9%) 0.018 ms/op
Iteration   1: 5.809 ±(99.9%) 0.010 ms/op
Iteration   2: 5.770 ±(99.9%) 0.026 ms/op
Iteration   3: 5.689 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.756 ±(99.9%) 1.112 ms/op [Average]
  (min, avg, max) = (5.689, 5.756, 5.809), stdev = 0.061
  CI (99.9%): [4.644, 6.869] (assumes normal distribution)


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
# Warmup Iteration   1: 7.239 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 5.015 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.597 ±(99.9%) 0.014 ms/op
Iteration   1: 4.554 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.764 ms/op
                 createUser·p0.50:   4.473 ms/op
                 createUser·p0.90:   5.710 ms/op
                 createUser·p0.95:   6.038 ms/op
                 createUser·p0.99:   7.542 ms/op
                 createUser·p0.999:  15.505 ms/op
                 createUser·p0.9999: 25.951 ms/op
                 createUser·p1.00:   26.771 ms/op

Iteration   2: 4.523 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.920 ms/op
                 createUser·p0.50:   4.407 ms/op
                 createUser·p0.90:   5.734 ms/op
                 createUser·p0.95:   6.201 ms/op
                 createUser·p0.99:   8.372 ms/op
                 createUser·p0.999:  11.485 ms/op
                 createUser·p0.9999: 20.333 ms/op
                 createUser·p1.00:   22.872 ms/op

Iteration   3: 4.378 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.710 ms/op
                 createUser·p0.50:   4.276 ms/op
                 createUser·p0.90:   5.480 ms/op
                 createUser·p0.95:   5.939 ms/op
                 createUser·p0.99:   7.770 ms/op
                 createUser·p0.999:  16.679 ms/op
                 createUser·p0.9999: 22.439 ms/op
                 createUser·p1.00:   23.134 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 213993
  mean =      4.484 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3463 
    [ 2.500,  5.000) = 154614 
    [ 5.000,  7.500) = 53207 
    [ 7.500, 10.000) = 2013 
    [10.000, 12.500) = 350 
    [12.500, 15.000) = 146 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.710 ms/op
     p(50.0000) =      4.375 ms/op
     p(90.0000) =      5.652 ms/op
     p(95.0000) =      6.062 ms/op
     p(99.0000) =      7.954 ms/op
     p(99.9000) =     14.598 ms/op
     p(99.9900) =     22.872 ms/op
     p(99.9990) =     26.566 ms/op
     p(99.9999) =     26.771 ms/op
    p(100.0000) =     26.771 ms/op


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
# Warmup Iteration   1: 6.227 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.564 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.396 ±(99.9%) 0.012 ms/op
Iteration   1: 4.383 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.167 ms/op
                 existUser·p0.50:   4.284 ms/op
                 existUser·p0.90:   5.489 ms/op
                 existUser·p0.95:   5.939 ms/op
                 existUser·p0.99:   7.897 ms/op
                 existUser·p0.999:  13.507 ms/op
                 existUser·p0.9999: 18.790 ms/op
                 existUser·p1.00:   19.366 ms/op

Iteration   2: 4.200 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.081 ms/op
                 existUser·p0.50:   4.121 ms/op
                 existUser·p0.90:   5.399 ms/op
                 existUser·p0.95:   5.792 ms/op
                 existUser·p0.99:   7.709 ms/op
                 existUser·p0.999:  13.268 ms/op
                 existUser·p0.9999: 19.567 ms/op
                 existUser·p1.00:   20.218 ms/op

Iteration   3: 4.285 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.028 ms/op
                 existUser·p0.50:   4.170 ms/op
                 existUser·p0.90:   5.407 ms/op
                 existUser·p0.95:   5.841 ms/op
                 existUser·p0.99:   7.979 ms/op
                 existUser·p0.999:  13.877 ms/op
                 existUser·p0.9999: 20.424 ms/op
                 existUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 223788
  mean =      4.288 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6354 
    [ 2.500,  5.000) = 173833 
    [ 5.000,  7.500) = 40896 
    [ 7.500, 10.000) = 1976 
    [10.000, 12.500) = 435 
    [12.500, 15.000) = 192 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.028 ms/op
     p(50.0000) =      4.194 ms/op
     p(90.0000) =      5.431 ms/op
     p(95.0000) =      5.854 ms/op
     p(99.0000) =      7.881 ms/op
     p(99.9000) =     13.684 ms/op
     p(99.9900) =     19.648 ms/op
     p(99.9990) =     21.039 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.789 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.739 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.708 ±(99.9%) 0.014 ms/op
Iteration   1: 4.548 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.950 ms/op
                 getUser·p0.50:   4.424 ms/op
                 getUser·p0.90:   5.775 ms/op
                 getUser·p0.95:   6.259 ms/op
                 getUser·p0.99:   7.889 ms/op
                 getUser·p0.999:  14.190 ms/op
                 getUser·p0.9999: 24.049 ms/op
                 getUser·p1.00:   24.478 ms/op

Iteration   2: 4.591 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.157 ms/op
                 getUser·p0.50:   4.522 ms/op
                 getUser·p0.90:   5.857 ms/op
                 getUser·p0.95:   6.234 ms/op
                 getUser·p0.99:   7.365 ms/op
                 getUser·p0.999:  10.737 ms/op
                 getUser·p0.9999: 17.403 ms/op
                 getUser·p1.00:   18.022 ms/op

Iteration   3: 4.452 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.206 ms/op
                 getUser·p0.50:   4.342 ms/op
                 getUser·p0.90:   5.571 ms/op
                 getUser·p0.95:   6.013 ms/op
                 getUser·p0.99:   7.815 ms/op
                 getUser·p0.999:  15.472 ms/op
                 getUser·p0.9999: 20.835 ms/op
                 getUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 211875
  mean =      4.529 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3709 
    [ 2.500,  5.000) = 149364 
    [ 5.000,  7.500) = 56429 
    [ 7.500, 10.000) = 1839 
    [10.000, 12.500) = 276 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.950 ms/op
     p(50.0000) =      4.424 ms/op
     p(90.0000) =      5.743 ms/op
     p(95.0000) =      6.185 ms/op
     p(99.0000) =      7.684 ms/op
     p(99.9000) =     13.306 ms/op
     p(99.9900) =     23.194 ms/op
     p(99.9990) =     24.397 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 7.936 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 6.813 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.758 ±(99.9%) 0.022 ms/op
Iteration   1: 5.514 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.313 ms/op
                 listUser·p0.50:   5.243 ms/op
                 listUser·p0.90:   7.201 ms/op
                 listUser·p0.95:   8.086 ms/op
                 listUser·p0.99:   10.240 ms/op
                 listUser·p0.999:  19.169 ms/op
                 listUser·p0.9999: 21.928 ms/op
                 listUser·p1.00:   24.576 ms/op

Iteration   2: 5.578 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.569 ms/op
                 listUser·p0.50:   5.308 ms/op
                 listUser·p0.90:   7.234 ms/op
                 listUser·p0.95:   8.053 ms/op
                 listUser·p0.99:   10.125 ms/op
                 listUser·p0.999:  17.629 ms/op
                 listUser·p0.9999: 20.416 ms/op
                 listUser·p1.00:   20.840 ms/op

Iteration   3: 5.649 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.511 ms/op
                 listUser·p0.50:   5.366 ms/op
                 listUser·p0.90:   7.414 ms/op
                 listUser·p0.95:   8.208 ms/op
                 listUser·p0.99:   10.568 ms/op
                 listUser·p0.999:  19.326 ms/op
                 listUser·p0.9999: 22.807 ms/op
                 listUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 171930
  mean =      5.580 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 106 
    [ 2.500,  5.000) = 62020 
    [ 5.000,  7.500) = 95366 
    [ 7.500, 10.000) = 12382 
    [10.000, 12.500) = 1419 
    [12.500, 15.000) = 261 
    [15.000, 17.500) = 154 
    [17.500, 20.000) = 140 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.313 ms/op
     p(50.0000) =      5.308 ms/op
     p(90.0000) =      7.274 ms/op
     p(95.0000) =      8.118 ms/op
     p(99.0000) =     10.289 ms/op
     p(99.9000) =     18.549 ms/op
     p(99.9900) =     21.915 ms/op
     p(99.9990) =     24.636 ms/op
     p(99.9999) =     24.707 ms/op
    p(100.0000) =     24.707 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.066 ± 2.087  ops/ms
ClientGrpc.existUser                       thrpt       3   7.460 ± 1.842  ops/ms
ClientGrpc.getUser                         thrpt       3   6.981 ± 4.797  ops/ms
ClientGrpc.listUser                        thrpt       3   5.476 ± 6.251  ops/ms
ClientGrpc.createUser                       avgt       3   4.704 ± 3.212   ms/op
ClientGrpc.existUser                        avgt       3   4.483 ± 0.578   ms/op
ClientGrpc.getUser                          avgt       3   4.585 ± 0.972   ms/op
ClientGrpc.listUser                         avgt       3   5.756 ± 1.112   ms/op
ClientGrpc.createUser                     sample  213993   4.484 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.710           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.652           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.062           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.954           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.598           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.872           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.771           ms/op
ClientGrpc.existUser                      sample  223788   4.288 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.028           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.431           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.854           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.881           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.684           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.648           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.675           ms/op
ClientGrpc.getUser                        sample  211875   4.529 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.950           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.424           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.743           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.185           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.684           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.306           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.194           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.478           ms/op
ClientGrpc.listUser                       sample  171930   5.580 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.313           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.308           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.274           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.118           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.289           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.549           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.915           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.707           ms/op
