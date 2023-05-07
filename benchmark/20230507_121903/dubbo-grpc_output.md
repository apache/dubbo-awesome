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
# Warmup Iteration   1: 3.035 ops/ms
# Warmup Iteration   2: 6.992 ops/ms
# Warmup Iteration   3: 8.216 ops/ms
Iteration   1: 8.906 ops/ms
Iteration   2: 9.219 ops/ms
Iteration   3: 8.750 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.958 ±(99.9%) 4.353 ops/ms [Average]
  (min, avg, max) = (8.750, 8.958, 9.219), stdev = 0.239
  CI (99.9%): [4.605, 13.311] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 6.070 ops/ms
# Warmup Iteration   2: 9.049 ops/ms
# Warmup Iteration   3: 9.312 ops/ms
Iteration   1: 9.524 ops/ms
Iteration   2: 9.440 ops/ms
Iteration   3: 9.885 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.616 ±(99.9%) 4.312 ops/ms [Average]
  (min, avg, max) = (9.440, 9.616, 9.885), stdev = 0.236
  CI (99.9%): [5.305, 13.928] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 5.496 ops/ms
# Warmup Iteration   2: 8.300 ops/ms
# Warmup Iteration   3: 9.082 ops/ms
Iteration   1: 8.962 ops/ms
Iteration   2: 8.725 ops/ms
Iteration   3: 8.811 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.833 ±(99.9%) 2.186 ops/ms [Average]
  (min, avg, max) = (8.725, 8.833, 8.962), stdev = 0.120
  CI (99.9%): [6.647, 11.019] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 4.639 ops/ms
# Warmup Iteration   2: 6.538 ops/ms
# Warmup Iteration   3: 6.656 ops/ms
Iteration   1: 6.815 ops/ms
Iteration   2: 6.826 ops/ms
Iteration   3: 6.518 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.720 ±(99.9%) 3.191 ops/ms [Average]
  (min, avg, max) = (6.518, 6.720, 6.826), stdev = 0.175
  CI (99.9%): [3.529, 9.911] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.858 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.769 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.589 ±(99.9%) 0.003 ms/op
Iteration   1: 3.635 ±(99.9%) 0.003 ms/op
Iteration   2: 3.595 ±(99.9%) 0.002 ms/op
Iteration   3: 3.503 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.578 ±(99.9%) 1.231 ms/op [Average]
  (min, avg, max) = (3.503, 3.578, 3.635), stdev = 0.067
  CI (99.9%): [2.347, 4.808] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.659 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.488 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.258 ±(99.9%) 0.002 ms/op
Iteration   1: 3.392 ±(99.9%) 0.002 ms/op
Iteration   2: 3.369 ±(99.9%) 0.003 ms/op
Iteration   3: 3.453 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.405 ±(99.9%) 0.792 ms/op [Average]
  (min, avg, max) = (3.369, 3.405, 3.453), stdev = 0.043
  CI (99.9%): [2.612, 4.197] (assumes normal distribution)


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
# Warmup Iteration   1: 4.691 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.672 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.556 ±(99.9%) 0.003 ms/op
Iteration   1: 3.572 ±(99.9%) 0.002 ms/op
Iteration   2: 3.525 ±(99.9%) 0.003 ms/op
Iteration   3: 3.510 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.536 ±(99.9%) 0.584 ms/op [Average]
  (min, avg, max) = (3.510, 3.536, 3.572), stdev = 0.032
  CI (99.9%): [2.951, 4.120] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 6.447 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.978 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.746 ±(99.9%) 0.017 ms/op
Iteration   1: 4.652 ±(99.9%) 0.016 ms/op
Iteration   2: 4.662 ±(99.9%) 0.010 ms/op
Iteration   3: 4.691 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.668 ±(99.9%) 0.375 ms/op [Average]
  (min, avg, max) = (4.652, 4.668, 4.691), stdev = 0.021
  CI (99.9%): [4.293, 5.044] (assumes normal distribution)


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
# Warmup Iteration   1: 5.296 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.843 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.643 ±(99.9%) 0.010 ms/op
Iteration   1: 3.444 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.872 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   4.350 ms/op
                 createUser·p0.95:   4.768 ms/op
                 createUser·p0.99:   5.968 ms/op
                 createUser·p0.999:  11.291 ms/op
                 createUser·p0.9999: 14.921 ms/op
                 createUser·p1.00:   16.646 ms/op

Iteration   2: 3.509 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.624 ms/op
                 createUser·p0.50:   3.428 ms/op
                 createUser·p0.90:   4.342 ms/op
                 createUser·p0.95:   4.743 ms/op
                 createUser·p0.99:   5.906 ms/op
                 createUser·p0.999:  13.858 ms/op
                 createUser·p0.9999: 25.264 ms/op
                 createUser·p1.00:   25.723 ms/op

Iteration   3: 3.660 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.794 ms/op
                 createUser·p0.50:   3.576 ms/op
                 createUser·p0.90:   4.596 ms/op
                 createUser·p0.95:   5.030 ms/op
                 createUser·p0.99:   6.185 ms/op
                 createUser·p0.999:  12.274 ms/op
                 createUser·p0.9999: 18.620 ms/op
                 createUser·p1.00:   19.137 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 271573
  mean =      3.535 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15627 
    [ 2.500,  5.000) = 245059 
    [ 5.000,  7.500) = 9946 
    [ 7.500, 10.000) = 480 
    [10.000, 12.500) = 255 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.624 ms/op
     p(50.0000) =      3.457 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      6.029 ms/op
     p(99.9000) =     12.033 ms/op
     p(99.9900) =     22.769 ms/op
     p(99.9990) =     25.554 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


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
# Warmup Iteration   1: 4.624 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.683 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.555 ±(99.9%) 0.010 ms/op
Iteration   1: 3.691 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.501 ms/op
                 existUser·p0.50:   3.576 ms/op
                 existUser·p0.90:   4.612 ms/op
                 existUser·p0.95:   5.071 ms/op
                 existUser·p0.99:   6.406 ms/op
                 existUser·p0.999:  13.994 ms/op
                 existUser·p0.9999: 20.718 ms/op
                 existUser·p1.00:   22.741 ms/op

Iteration   2: 3.665 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.795 ms/op
                 existUser·p0.50:   3.518 ms/op
                 existUser·p0.90:   4.661 ms/op
                 existUser·p0.95:   5.054 ms/op
                 existUser·p0.99:   6.398 ms/op
                 existUser·p0.999:  8.897 ms/op
                 existUser·p0.9999: 14.832 ms/op
                 existUser·p1.00:   17.302 ms/op

Iteration   3: 3.427 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.950 ms/op
                 existUser·p0.50:   3.359 ms/op
                 existUser·p0.90:   4.194 ms/op
                 existUser·p0.95:   4.514 ms/op
                 existUser·p0.99:   5.397 ms/op
                 existUser·p0.999:  6.930 ms/op
                 existUser·p0.9999: 21.037 ms/op
                 existUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 267336
  mean =      3.590 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7359 
    [ 2.500,  5.000) = 248502 
    [ 5.000,  7.500) = 10672 
    [ 7.500, 10.000) = 523 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.501 ms/op
     p(50.0000) =      3.478 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.907 ms/op
     p(99.0000) =      6.070 ms/op
     p(99.9000) =     10.223 ms/op
     p(99.9900) =     20.513 ms/op
     p(99.9990) =     22.643 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.399 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.723 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.539 ±(99.9%) 0.009 ms/op
Iteration   1: 3.496 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.020 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   4.317 ms/op
                 getUser·p0.95:   4.735 ms/op
                 getUser·p0.99:   5.857 ms/op
                 getUser·p0.999:  9.906 ms/op
                 getUser·p0.9999: 14.118 ms/op
                 getUser·p1.00:   14.451 ms/op

Iteration   2: 3.489 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.800 ms/op
                 getUser·p0.50:   3.416 ms/op
                 getUser·p0.90:   4.334 ms/op
                 getUser·p0.95:   4.702 ms/op
                 getUser·p0.99:   5.849 ms/op
                 getUser·p0.999:  11.023 ms/op
                 getUser·p0.9999: 21.627 ms/op
                 getUser·p1.00:   22.282 ms/op

Iteration   3: 3.549 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.922 ms/op
                 getUser·p0.50:   3.424 ms/op
                 getUser·p0.90:   4.473 ms/op
                 getUser·p0.95:   4.899 ms/op
                 getUser·p0.99:   6.062 ms/op
                 getUser·p0.999:  13.605 ms/op
                 getUser·p0.9999: 22.969 ms/op
                 getUser·p1.00:   23.724 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 273261
  mean =      3.511 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10544 
    [ 2.500,  5.000) = 253223 
    [ 5.000,  7.500) = 8694 
    [ 7.500, 10.000) = 507 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      3.412 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.784 ms/op
     p(99.0000) =      5.931 ms/op
     p(99.9000) =     10.985 ms/op
     p(99.9900) =     21.430 ms/op
     p(99.9990) =     23.506 ms/op
     p(99.9999) =     23.724 ms/op
    p(100.0000) =     23.724 ms/op


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
# Warmup Iteration   1: 6.985 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.820 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.552 ±(99.9%) 0.017 ms/op
Iteration   1: 4.626 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.612 ms/op
                 listUser·p0.50:   4.424 ms/op
                 listUser·p0.90:   5.841 ms/op
                 listUser·p0.95:   6.611 ms/op
                 listUser·p0.99:   8.454 ms/op
                 listUser·p0.999:  14.798 ms/op
                 listUser·p0.9999: 25.663 ms/op
                 listUser·p1.00:   26.051 ms/op

Iteration   2: 4.621 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.149 ms/op
                 listUser·p0.50:   4.432 ms/op
                 listUser·p0.90:   5.890 ms/op
                 listUser·p0.95:   6.668 ms/op
                 listUser·p0.99:   8.442 ms/op
                 listUser·p0.999:  17.299 ms/op
                 listUser·p0.9999: 21.931 ms/op
                 listUser·p1.00:   22.446 ms/op

Iteration   3: 4.773 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.337 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   6.267 ms/op
                 listUser·p0.95:   7.136 ms/op
                 listUser·p0.99:   9.683 ms/op
                 listUser·p0.999:  20.151 ms/op
                 listUser·p0.9999: 30.887 ms/op
                 listUser·p1.00:   31.195 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 205243
  mean =      4.672 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 518 
    [ 2.500,  5.000) = 149531 
    [ 5.000,  7.500) = 49558 
    [ 7.500, 10.000) = 4638 
    [10.000, 12.500) = 532 
    [12.500, 15.000) = 147 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.149 ms/op
     p(50.0000) =      4.448 ms/op
     p(90.0000) =      5.988 ms/op
     p(95.0000) =      6.799 ms/op
     p(99.0000) =      8.815 ms/op
     p(99.9000) =     18.047 ms/op
     p(99.9900) =     30.342 ms/op
     p(99.9990) =     31.161 ms/op
     p(99.9999) =     31.195 ms/op
    p(100.0000) =     31.195 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.958 ± 4.353  ops/ms
ClientGrpc.existUser                       thrpt       3   9.616 ± 4.312  ops/ms
ClientGrpc.getUser                         thrpt       3   8.833 ± 2.186  ops/ms
ClientGrpc.listUser                        thrpt       3   6.720 ± 3.191  ops/ms
ClientGrpc.createUser                       avgt       3   3.578 ± 1.231   ms/op
ClientGrpc.existUser                        avgt       3   3.405 ± 0.792   ms/op
ClientGrpc.getUser                          avgt       3   3.536 ± 0.584   ms/op
ClientGrpc.listUser                         avgt       3   4.668 ± 0.375   ms/op
ClientGrpc.createUser                     sample  271573   3.535 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.624           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.457           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.858           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.029           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.033           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.769           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.723           ms/op
ClientGrpc.existUser                      sample  267336   3.590 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.501           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.478           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.489           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.907           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.070           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.223           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.513           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.741           ms/op
ClientGrpc.getUser                        sample  273261   3.511 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.800           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.412           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.375           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.784           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.931           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.985           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.430           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.724           ms/op
ClientGrpc.listUser                       sample  205243   4.672 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.149           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.448           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.988           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.799           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.815           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.047           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.342           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.195           ms/op
