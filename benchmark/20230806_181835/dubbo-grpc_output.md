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
# Warmup Iteration   1: 3.232 ops/ms
# Warmup Iteration   2: 6.655 ops/ms
# Warmup Iteration   3: 8.283 ops/ms
Iteration   1: 8.557 ops/ms
Iteration   2: 8.595 ops/ms
Iteration   3: 8.728 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.627 ±(99.9%) 1.636 ops/ms [Average]
  (min, avg, max) = (8.557, 8.627, 8.728), stdev = 0.090
  CI (99.9%): [6.990, 10.263] (assumes normal distribution)


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
# Warmup Iteration   1: 5.845 ops/ms
# Warmup Iteration   2: 8.791 ops/ms
# Warmup Iteration   3: 9.111 ops/ms
Iteration   1: 9.337 ops/ms
Iteration   2: 9.311 ops/ms
Iteration   3: 9.430 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.360 ±(99.9%) 1.142 ops/ms [Average]
  (min, avg, max) = (9.311, 9.360, 9.430), stdev = 0.063
  CI (99.9%): [8.218, 10.502] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.363 ops/ms
# Warmup Iteration   2: 8.421 ops/ms
# Warmup Iteration   3: 8.880 ops/ms
Iteration   1: 8.895 ops/ms
Iteration   2: 8.997 ops/ms
Iteration   3: 9.079 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.990 ±(99.9%) 1.687 ops/ms [Average]
  (min, avg, max) = (8.895, 8.990, 9.079), stdev = 0.092
  CI (99.9%): [7.303, 10.678] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.601 ops/ms
# Warmup Iteration   2: 6.353 ops/ms
# Warmup Iteration   3: 6.779 ops/ms
Iteration   1: 6.731 ops/ms
Iteration   2: 6.766 ops/ms
Iteration   3: 6.753 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.750 ±(99.9%) 0.325 ops/ms [Average]
  (min, avg, max) = (6.731, 6.750, 6.766), stdev = 0.018
  CI (99.9%): [6.425, 7.075] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.299 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.755 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.733 ±(99.9%) 0.009 ms/op
Iteration   1: 3.604 ±(99.9%) 0.003 ms/op
Iteration   2: 3.574 ±(99.9%) 0.005 ms/op
Iteration   3: 3.569 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.582 ±(99.9%) 0.338 ms/op [Average]
  (min, avg, max) = (3.569, 3.582, 3.604), stdev = 0.019
  CI (99.9%): [3.244, 3.920] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.056 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.565 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.442 ±(99.9%) 0.003 ms/op
Iteration   1: 3.405 ±(99.9%) 0.003 ms/op
Iteration   2: 3.434 ±(99.9%) 0.004 ms/op
Iteration   3: 3.479 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.439 ±(99.9%) 0.684 ms/op [Average]
  (min, avg, max) = (3.405, 3.439, 3.479), stdev = 0.038
  CI (99.9%): [2.755, 4.124] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.170 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.802 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.660 ±(99.9%) 0.006 ms/op
Iteration   1: 3.600 ±(99.9%) 0.005 ms/op
Iteration   2: 3.590 ±(99.9%) 0.005 ms/op
Iteration   3: 3.615 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.602 ±(99.9%) 0.228 ms/op [Average]
  (min, avg, max) = (3.590, 3.602, 3.615), stdev = 0.013
  CI (99.9%): [3.373, 3.830] (assumes normal distribution)


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
# Warmup Iteration   1: 6.190 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.998 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.690 ±(99.9%) 0.016 ms/op
Iteration   1: 4.703 ±(99.9%) 0.018 ms/op
Iteration   2: 4.677 ±(99.9%) 0.010 ms/op
Iteration   3: 4.618 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.666 ±(99.9%) 0.792 ms/op [Average]
  (min, avg, max) = (4.618, 4.666, 4.703), stdev = 0.043
  CI (99.9%): [3.874, 5.457] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.346 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.808 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.686 ±(99.9%) 0.008 ms/op
Iteration   1: 3.653 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.970 ms/op
                 createUser·p0.50:   3.584 ms/op
                 createUser·p0.90:   4.358 ms/op
                 createUser·p0.95:   4.694 ms/op
                 createUser·p0.99:   5.865 ms/op
                 createUser·p0.999:  11.583 ms/op
                 createUser·p0.9999: 14.483 ms/op
                 createUser·p1.00:   14.647 ms/op

Iteration   2: 3.566 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.728 ms/op
                 createUser·p0.50:   3.547 ms/op
                 createUser·p0.90:   4.182 ms/op
                 createUser·p0.95:   4.506 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  8.039 ms/op
                 createUser·p0.9999: 15.943 ms/op
                 createUser·p1.00:   17.072 ms/op

Iteration   3: 3.594 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.763 ms/op
                 createUser·p0.50:   3.547 ms/op
                 createUser·p0.90:   4.202 ms/op
                 createUser·p0.95:   4.538 ms/op
                 createUser·p0.99:   5.743 ms/op
                 createUser·p0.999:  16.712 ms/op
                 createUser·p0.9999: 21.234 ms/op
                 createUser·p1.00:   23.855 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 266332
  mean =      3.604 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7955 
    [ 2.500,  5.000) = 252612 
    [ 5.000,  7.500) = 5009 
    [ 7.500, 10.000) = 479 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.728 ms/op
     p(50.0000) =      3.559 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     10.196 ms/op
     p(99.9900) =     18.886 ms/op
     p(99.9990) =     22.203 ms/op
     p(99.9999) =     23.855 ms/op
    p(100.0000) =     23.855 ms/op


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
# Warmup Iteration   1: 4.912 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.597 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.425 ±(99.9%) 0.007 ms/op
Iteration   1: 3.394 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.836 ms/op
                 existUser·p0.50:   3.383 ms/op
                 existUser·p0.90:   3.912 ms/op
                 existUser·p0.95:   4.182 ms/op
                 existUser·p0.99:   5.493 ms/op
                 existUser·p0.999:  9.241 ms/op
                 existUser·p0.9999: 15.541 ms/op
                 existUser·p1.00:   15.942 ms/op

Iteration   2: 3.466 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.871 ms/op
                 existUser·p0.50:   3.416 ms/op
                 existUser·p0.90:   3.985 ms/op
                 existUser·p0.95:   4.211 ms/op
                 existUser·p0.99:   5.317 ms/op
                 existUser·p0.999:  8.700 ms/op
                 existUser·p0.9999: 21.683 ms/op
                 existUser·p1.00:   22.348 ms/op

Iteration   3: 3.397 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.673 ms/op
                 existUser·p0.50:   3.375 ms/op
                 existUser·p0.90:   3.883 ms/op
                 existUser·p0.95:   4.202 ms/op
                 existUser·p0.99:   5.366 ms/op
                 existUser·p0.999:  8.964 ms/op
                 existUser·p0.9999: 21.285 ms/op
                 existUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 280911
  mean =      3.419 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9253 
    [ 2.500,  5.000) = 267590 
    [ 5.000,  7.500) = 3309 
    [ 7.500, 10.000) = 621 
    [10.000, 12.500) = 9 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.673 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      5.407 ms/op
     p(99.9000) =      9.044 ms/op
     p(99.9900) =     21.234 ms/op
     p(99.9990) =     22.315 ms/op
     p(99.9999) =     22.348 ms/op
    p(100.0000) =     22.348 ms/op


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
# Warmup Iteration   1: 5.157 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 3.814 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.623 ±(99.9%) 0.007 ms/op
Iteration   1: 3.680 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.233 ms/op
                 getUser·p0.50:   3.609 ms/op
                 getUser·p0.90:   4.293 ms/op
                 getUser·p0.95:   4.548 ms/op
                 getUser·p0.99:   5.915 ms/op
                 getUser·p0.999:  9.472 ms/op
                 getUser·p0.9999: 17.312 ms/op
                 getUser·p1.00:   17.924 ms/op

Iteration   2: 3.539 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.028 ms/op
                 getUser·p0.50:   3.510 ms/op
                 getUser·p0.90:   4.121 ms/op
                 getUser·p0.95:   4.489 ms/op
                 getUser·p0.99:   5.647 ms/op
                 getUser·p0.999:  7.807 ms/op
                 getUser·p0.9999: 15.710 ms/op
                 getUser·p1.00:   16.056 ms/op

Iteration   3: 3.587 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.061 ms/op
                 getUser·p0.50:   3.539 ms/op
                 getUser·p0.90:   4.190 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   5.865 ms/op
                 getUser·p0.999:  10.486 ms/op
                 getUser·p0.9999: 23.560 ms/op
                 getUser·p1.00:   25.494 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 266348
  mean =      3.601 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6715 
    [ 2.500,  5.000) = 253648 
    [ 5.000,  7.500) = 5179 
    [ 7.500, 10.000) = 601 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.028 ms/op
     p(50.0000) =      3.551 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =      9.382 ms/op
     p(99.9900) =     23.298 ms/op
     p(99.9990) =     24.787 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


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
# Warmup Iteration   1: 6.802 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 5.221 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.789 ±(99.9%) 0.014 ms/op
Iteration   1: 4.805 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.179 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   5.882 ms/op
                 listUser·p0.95:   6.734 ms/op
                 listUser·p0.99:   8.585 ms/op
                 listUser·p0.999:  14.347 ms/op
                 listUser·p0.9999: 17.684 ms/op
                 listUser·p1.00:   18.285 ms/op

Iteration   2: 4.790 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.149 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   5.825 ms/op
                 listUser·p0.95:   6.644 ms/op
                 listUser·p0.99:   8.290 ms/op
                 listUser·p0.999:  15.621 ms/op
                 listUser·p0.9999: 22.303 ms/op
                 listUser·p1.00:   24.248 ms/op

Iteration   3: 4.752 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.059 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.972 ms/op
                 listUser·p0.95:   6.717 ms/op
                 listUser·p0.99:   8.781 ms/op
                 listUser·p0.999:  18.219 ms/op
                 listUser·p0.9999: 21.498 ms/op
                 listUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 200868
  mean =      4.782 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 264 
    [ 2.500,  5.000) = 151384 
    [ 5.000,  7.500) = 44418 
    [ 7.500, 10.000) = 3992 
    [10.000, 12.500) = 454 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.059 ms/op
     p(50.0000) =      4.588 ms/op
     p(90.0000) =      5.890 ms/op
     p(95.0000) =      6.701 ms/op
     p(99.0000) =      8.536 ms/op
     p(99.9000) =     15.581 ms/op
     p(99.9900) =     21.752 ms/op
     p(99.9990) =     23.849 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.627 ± 1.636  ops/ms
ClientGrpc.existUser                       thrpt       3   9.360 ± 1.142  ops/ms
ClientGrpc.getUser                         thrpt       3   8.990 ± 1.687  ops/ms
ClientGrpc.listUser                        thrpt       3   6.750 ± 0.325  ops/ms
ClientGrpc.createUser                       avgt       3   3.582 ± 0.338   ms/op
ClientGrpc.existUser                        avgt       3   3.439 ± 0.684   ms/op
ClientGrpc.getUser                          avgt       3   3.602 ± 0.228   ms/op
ClientGrpc.listUser                         avgt       3   4.666 ± 0.792   ms/op
ClientGrpc.createUser                     sample  266332   3.604 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.728           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.559           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.243           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.588           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.751           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.196           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.886           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.855           ms/op
ClientGrpc.existUser                      sample  280911   3.419 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.673           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.391           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.932           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.202           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.407           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.044           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.234           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.348           ms/op
ClientGrpc.getUser                        sample  266348   3.601 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.028           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.551           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.211           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.522           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.792           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.382           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.298           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.494           ms/op
ClientGrpc.listUser                       sample  200868   4.782 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.059           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.588           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.890           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.701           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.536           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.581           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.752           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.248           ms/op
