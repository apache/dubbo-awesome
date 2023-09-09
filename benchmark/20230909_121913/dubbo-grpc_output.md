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
# Warmup Iteration   1: 3.488 ops/ms
# Warmup Iteration   2: 7.716 ops/ms
# Warmup Iteration   3: 8.928 ops/ms
Iteration   1: 9.366 ops/ms
Iteration   2: 9.387 ops/ms
Iteration   3: 9.268 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.340 ±(99.9%) 1.160 ops/ms [Average]
  (min, avg, max) = (9.268, 9.340, 9.387), stdev = 0.064
  CI (99.9%): [8.180, 10.501] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.611 ops/ms
# Warmup Iteration   2: 9.237 ops/ms
# Warmup Iteration   3: 9.840 ops/ms
Iteration   1: 9.605 ops/ms
Iteration   2: 9.574 ops/ms
Iteration   3: 9.925 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.701 ±(99.9%) 3.551 ops/ms [Average]
  (min, avg, max) = (9.574, 9.701, 9.925), stdev = 0.195
  CI (99.9%): [6.150, 13.253] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.746 ops/ms
# Warmup Iteration   2: 8.721 ops/ms
# Warmup Iteration   3: 8.970 ops/ms
Iteration   1: 9.226 ops/ms
Iteration   2: 9.143 ops/ms
Iteration   3: 9.382 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.250 ±(99.9%) 2.220 ops/ms [Average]
  (min, avg, max) = (9.143, 9.250, 9.382), stdev = 0.122
  CI (99.9%): [7.030, 11.470] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.421 ops/ms
# Warmup Iteration   2: 6.721 ops/ms
# Warmup Iteration   3: 6.833 ops/ms
Iteration   1: 7.100 ops/ms
Iteration   2: 7.060 ops/ms
Iteration   3: 7.068 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.076 ±(99.9%) 0.389 ops/ms [Average]
  (min, avg, max) = (7.060, 7.076, 7.100), stdev = 0.021
  CI (99.9%): [6.687, 7.465] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.878 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.736 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.501 ±(99.9%) 0.003 ms/op
Iteration   1: 3.576 ±(99.9%) 0.005 ms/op
Iteration   2: 3.495 ±(99.9%) 0.004 ms/op
Iteration   3: 3.560 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.544 ±(99.9%) 0.782 ms/op [Average]
  (min, avg, max) = (3.495, 3.544, 3.576), stdev = 0.043
  CI (99.9%): [2.761, 4.326] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.187 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.415 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.284 ±(99.9%) 0.004 ms/op
Iteration   1: 3.272 ±(99.9%) 0.004 ms/op
Iteration   2: 3.193 ±(99.9%) 0.003 ms/op
Iteration   3: 3.329 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.265 ±(99.9%) 1.241 ms/op [Average]
  (min, avg, max) = (3.193, 3.265, 3.329), stdev = 0.068
  CI (99.9%): [2.023, 4.506] (assumes normal distribution)


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
# Warmup Iteration   1: 4.947 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.613 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.538 ±(99.9%) 0.004 ms/op
Iteration   1: 3.523 ±(99.9%) 0.004 ms/op
Iteration   2: 3.459 ±(99.9%) 0.003 ms/op
Iteration   3: 3.396 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.459 ±(99.9%) 1.159 ms/op [Average]
  (min, avg, max) = (3.396, 3.459, 3.523), stdev = 0.064
  CI (99.9%): [2.300, 4.618] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.497 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.698 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.505 ±(99.9%) 0.023 ms/op
Iteration   1: 4.392 ±(99.9%) 0.008 ms/op
Iteration   2: 4.500 ±(99.9%) 0.015 ms/op
Iteration   3: 4.368 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.420 ±(99.9%) 1.282 ms/op [Average]
  (min, avg, max) = (4.368, 4.420, 4.500), stdev = 0.070
  CI (99.9%): [3.138, 5.702] (assumes normal distribution)


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
# Warmup Iteration   1: 5.234 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.746 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.485 ±(99.9%) 0.009 ms/op
Iteration   1: 3.554 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.004 ms/op
                 createUser·p0.50:   3.502 ms/op
                 createUser·p0.90:   4.325 ms/op
                 createUser·p0.95:   4.669 ms/op
                 createUser·p0.99:   5.702 ms/op
                 createUser·p0.999:  10.192 ms/op
                 createUser·p0.9999: 15.598 ms/op
                 createUser·p1.00:   16.056 ms/op

Iteration   2: 3.457 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.657 ms/op
                 createUser·p0.50:   3.424 ms/op
                 createUser·p0.90:   4.174 ms/op
                 createUser·p0.95:   4.522 ms/op
                 createUser·p0.99:   5.595 ms/op
                 createUser·p0.999:  8.471 ms/op
                 createUser·p0.9999: 16.989 ms/op
                 createUser·p1.00:   17.564 ms/op

Iteration   3: 3.478 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.920 ms/op
                 createUser·p0.50:   3.391 ms/op
                 createUser·p0.90:   4.055 ms/op
                 createUser·p0.95:   4.415 ms/op
                 createUser·p0.99:   5.964 ms/op
                 createUser·p0.999:  12.831 ms/op
                 createUser·p0.9999: 36.687 ms/op
                 createUser·p1.00:   36.962 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 274554
  mean =      3.496 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11679 
    [ 2.500,  5.000) = 256729 
    [ 5.000,  7.500) = 5269 
    [ 7.500, 10.000) = 539 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.657 ms/op
     p(50.0000) =      3.437 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =     10.608 ms/op
     p(99.9900) =     35.949 ms/op
     p(99.9990) =     36.913 ms/op
     p(99.9999) =     36.962 ms/op
    p(100.0000) =     36.962 ms/op


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
# Warmup Iteration   1: 4.724 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.675 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.313 ±(99.9%) 0.007 ms/op
Iteration   1: 3.365 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.846 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   3.953 ms/op
                 existUser·p0.95:   4.235 ms/op
                 existUser·p0.99:   5.472 ms/op
                 existUser·p0.999:  10.612 ms/op
                 existUser·p0.9999: 26.902 ms/op
                 existUser·p1.00:   27.197 ms/op

Iteration   2: 3.367 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.903 ms/op
                 existUser·p0.50:   3.314 ms/op
                 existUser·p0.90:   3.981 ms/op
                 existUser·p0.95:   4.407 ms/op
                 existUser·p0.99:   5.538 ms/op
                 existUser·p0.999:  8.947 ms/op
                 existUser·p0.9999: 25.395 ms/op
                 existUser·p1.00:   28.639 ms/op

Iteration   3: 3.427 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.866 ms/op
                 existUser·p0.50:   3.383 ms/op
                 existUser·p0.90:   4.043 ms/op
                 existUser·p0.95:   4.334 ms/op
                 existUser·p0.99:   5.325 ms/op
                 existUser·p0.999:  8.298 ms/op
                 existUser·p0.9999: 18.132 ms/op
                 existUser·p1.00:   19.694 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 283467
  mean =      3.386 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12421 
    [ 2.500,  5.000) = 265885 
    [ 5.000,  7.500) = 4533 
    [ 7.500, 10.000) = 392 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      0.846 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =      8.782 ms/op
     p(99.9900) =     25.864 ms/op
     p(99.9990) =     28.426 ms/op
     p(99.9999) =     28.639 ms/op
    p(100.0000) =     28.639 ms/op


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
# Warmup Iteration   1: 5.045 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.673 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.518 ±(99.9%) 0.008 ms/op
Iteration   1: 3.433 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.659 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   4.133 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   5.775 ms/op
                 getUser·p0.999:  10.076 ms/op
                 getUser·p0.9999: 14.019 ms/op
                 getUser·p1.00:   15.204 ms/op

Iteration   2: 3.515 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.846 ms/op
                 getUser·p0.50:   3.465 ms/op
                 getUser·p0.90:   4.137 ms/op
                 getUser·p0.95:   4.440 ms/op
                 getUser·p0.99:   5.923 ms/op
                 getUser·p0.999:  9.060 ms/op
                 getUser·p0.9999: 18.823 ms/op
                 getUser·p1.00:   19.628 ms/op

Iteration   3: 3.489 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.695 ms/op
                 getUser·p0.50:   3.437 ms/op
                 getUser·p0.90:   4.153 ms/op
                 getUser·p0.95:   4.424 ms/op
                 getUser·p0.99:   5.587 ms/op
                 getUser·p0.999:  10.131 ms/op
                 getUser·p0.9999: 20.693 ms/op
                 getUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 275950
  mean =      3.478 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11160 
    [ 2.500,  5.000) = 259115 
    [ 5.000,  7.500) = 4773 
    [ 7.500, 10.000) = 668 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.659 ms/op
     p(50.0000) =      3.428 ms/op
     p(90.0000) =      4.141 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =      9.830 ms/op
     p(99.9900) =     19.445 ms/op
     p(99.9990) =     20.816 ms/op
     p(99.9999) =     20.840 ms/op
    p(100.0000) =     20.840 ms/op


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
# Warmup Iteration   1: 6.046 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.984 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.573 ±(99.9%) 0.015 ms/op
Iteration   1: 4.612 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.579 ms/op
                 listUser·p0.50:   4.391 ms/op
                 listUser·p0.90:   5.923 ms/op
                 listUser·p0.95:   6.767 ms/op
                 listUser·p0.99:   8.360 ms/op
                 listUser·p0.999:  15.439 ms/op
                 listUser·p0.9999: 17.238 ms/op
                 listUser·p1.00:   17.826 ms/op

Iteration   2: 4.617 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.200 ms/op
                 listUser·p0.50:   4.432 ms/op
                 listUser·p0.90:   5.652 ms/op
                 listUser·p0.95:   6.521 ms/op
                 listUser·p0.99:   8.389 ms/op
                 listUser·p0.999:  18.078 ms/op
                 listUser·p0.9999: 20.616 ms/op
                 listUser·p1.00:   22.053 ms/op

Iteration   3: 4.661 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   0.986 ms/op
                 listUser·p0.50:   4.415 ms/op
                 listUser·p0.90:   6.054 ms/op
                 listUser·p0.95:   6.947 ms/op
                 listUser·p0.99:   8.809 ms/op
                 listUser·p0.999:  21.399 ms/op
                 listUser·p0.9999: 28.975 ms/op
                 listUser·p1.00:   29.590 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 207383
  mean =      4.630 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 560 
    [ 2.500,  5.000) = 163561 
    [ 5.000,  7.500) = 38372 
    [ 7.500, 10.000) = 4042 
    [10.000, 12.500) = 425 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 134 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.986 ms/op
     p(50.0000) =      4.415 ms/op
     p(90.0000) =      5.874 ms/op
     p(95.0000) =      6.775 ms/op
     p(99.0000) =      8.520 ms/op
     p(99.9000) =     17.269 ms/op
     p(99.9900) =     28.508 ms/op
     p(99.9990) =     29.353 ms/op
     p(99.9999) =     29.590 ms/op
    p(100.0000) =     29.590 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.340 ± 1.160  ops/ms
ClientGrpc.existUser                       thrpt       3   9.701 ± 3.551  ops/ms
ClientGrpc.getUser                         thrpt       3   9.250 ± 2.220  ops/ms
ClientGrpc.listUser                        thrpt       3   7.076 ± 0.389  ops/ms
ClientGrpc.createUser                       avgt       3   3.544 ± 0.782   ms/op
ClientGrpc.existUser                        avgt       3   3.265 ± 1.241   ms/op
ClientGrpc.getUser                          avgt       3   3.459 ± 1.159   ms/op
ClientGrpc.listUser                         avgt       3   4.420 ± 1.282   ms/op
ClientGrpc.createUser                     sample  274554   3.496 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.657           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.437           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.190           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.555           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.718           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.608           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          35.949           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          36.962           ms/op
ClientGrpc.existUser                      sample  283467   3.386 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.846           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.338           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.990           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.325           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.472           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.782           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.864           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.639           ms/op
ClientGrpc.getUser                        sample  275950   3.478 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.659           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.428           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.141           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.456           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.751           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.830           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.445           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.840           ms/op
ClientGrpc.listUser                       sample  207383   4.630 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.986           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.415           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.874           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.775           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.520           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.269           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.508           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.590           ms/op
