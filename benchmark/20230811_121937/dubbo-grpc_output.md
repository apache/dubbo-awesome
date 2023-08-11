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
# Warmup Iteration   1: 4.146 ops/ms
# Warmup Iteration   2: 9.127 ops/ms
# Warmup Iteration   3: 10.250 ops/ms
Iteration   1: 10.723 ops/ms
Iteration   2: 10.374 ops/ms
Iteration   3: 10.533 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.543 ±(99.9%) 3.189 ops/ms [Average]
  (min, avg, max) = (10.374, 10.543, 10.723), stdev = 0.175
  CI (99.9%): [7.354, 13.732] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.491 ops/ms
# Warmup Iteration   2: 10.683 ops/ms
# Warmup Iteration   3: 11.249 ops/ms
Iteration   1: 11.263 ops/ms
Iteration   2: 11.084 ops/ms
Iteration   3: 10.966 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.104 ±(99.9%) 2.728 ops/ms [Average]
  (min, avg, max) = (10.966, 11.104, 11.263), stdev = 0.150
  CI (99.9%): [8.377, 13.832] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.987 ops/ms
# Warmup Iteration   2: 10.168 ops/ms
# Warmup Iteration   3: 10.532 ops/ms
Iteration   1: 10.389 ops/ms
Iteration   2: 10.461 ops/ms
Iteration   3: 10.962 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.604 ±(99.9%) 5.692 ops/ms [Average]
  (min, avg, max) = (10.389, 10.604, 10.962), stdev = 0.312
  CI (99.9%): [4.912, 16.296] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.437 ops/ms
# Warmup Iteration   2: 7.690 ops/ms
# Warmup Iteration   3: 7.871 ops/ms
Iteration   1: 7.914 ops/ms
Iteration   2: 7.876 ops/ms
Iteration   3: 7.924 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.905 ±(99.9%) 0.459 ops/ms [Average]
  (min, avg, max) = (7.876, 7.905, 7.924), stdev = 0.025
  CI (99.9%): [7.446, 8.364] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.485 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.189 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.003 ms/op
Iteration   1: 3.052 ±(99.9%) 0.010 ms/op
Iteration   2: 3.004 ±(99.9%) 0.002 ms/op
Iteration   3: 3.015 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.024 ±(99.9%) 0.454 ms/op [Average]
  (min, avg, max) = (3.004, 3.024, 3.052), stdev = 0.025
  CI (99.9%): [2.570, 3.478] (assumes normal distribution)


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
# Warmup Iteration   1: 4.084 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.976 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.867 ±(99.9%) 0.003 ms/op
Iteration   1: 2.913 ±(99.9%) 0.002 ms/op
Iteration   2: 2.851 ±(99.9%) 0.002 ms/op
Iteration   3: 2.921 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.895 ±(99.9%) 0.696 ms/op [Average]
  (min, avg, max) = (2.851, 2.895, 2.921), stdev = 0.038
  CI (99.9%): [2.199, 3.591] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.248 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.136 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.122 ±(99.9%) 0.004 ms/op
Iteration   1: 3.009 ±(99.9%) 0.003 ms/op
Iteration   2: 3.103 ±(99.9%) 0.003 ms/op
Iteration   3: 3.047 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.053 ±(99.9%) 0.863 ms/op [Average]
  (min, avg, max) = (3.009, 3.053, 3.103), stdev = 0.047
  CI (99.9%): [2.190, 3.916] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.560 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.170 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.026 ±(99.9%) 0.016 ms/op
Iteration   1: 4.025 ±(99.9%) 0.010 ms/op
Iteration   2: 3.961 ±(99.9%) 0.010 ms/op
Iteration   3: 4.014 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.000 ±(99.9%) 0.628 ms/op [Average]
  (min, avg, max) = (3.961, 4.000, 4.025), stdev = 0.034
  CI (99.9%): [3.371, 4.628] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.383 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.185 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.079 ±(99.9%) 0.006 ms/op
Iteration   1: 2.963 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.882 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  7.972 ms/op
                 createUser·p0.9999: 12.714 ms/op
                 createUser·p1.00:   12.993 ms/op

Iteration   2: 2.979 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.932 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  9.246 ms/op
                 createUser·p0.9999: 15.021 ms/op
                 createUser·p1.00:   15.581 ms/op

Iteration   3: 3.045 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.683 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.674 ms/op
                 createUser·p0.999:  8.257 ms/op
                 createUser·p0.9999: 24.297 ms/op
                 createUser·p1.00:   24.642 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320376
  mean =      2.995 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32904 
    [ 2.500,  5.000) = 285493 
    [ 5.000,  7.500) = 1449 
    [ 7.500, 10.000) = 278 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.683 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.548 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      8.448 ms/op
     p(99.9900) =     22.542 ms/op
     p(99.9990) =     24.478 ms/op
     p(99.9999) =     24.642 ms/op
    p(100.0000) =     24.642 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.139 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.997 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.931 ±(99.9%) 0.006 ms/op
Iteration   1: 2.963 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.278 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  7.584 ms/op
                 existUser·p0.9999: 13.638 ms/op
                 existUser·p1.00:   13.828 ms/op

Iteration   2: 2.920 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.779 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.564 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  6.914 ms/op
                 existUser·p0.9999: 21.859 ms/op
                 existUser·p1.00:   22.217 ms/op

Iteration   3: 2.885 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.662 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  6.972 ms/op
                 existUser·p0.9999: 14.662 ms/op
                 existUser·p1.00:   15.581 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328601
  mean =      2.923 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40811 
    [ 2.500,  5.000) = 286287 
    [ 5.000,  7.500) = 1239 
    [ 7.500, 10.000) = 135 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.278 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.621 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      7.078 ms/op
     p(99.9900) =     16.344 ms/op
     p(99.9990) =     22.142 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


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
# Warmup Iteration   1: 4.232 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.132 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.006 ms/op
Iteration   1: 3.081 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.722 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   4.801 ms/op
                 getUser·p0.999:  8.716 ms/op
                 getUser·p0.9999: 15.139 ms/op
                 getUser·p1.00:   17.891 ms/op

Iteration   2: 3.047 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.311 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.850 ms/op
                 getUser·p0.999:  8.313 ms/op
                 getUser·p0.9999: 20.037 ms/op
                 getUser·p1.00:   20.480 ms/op

Iteration   3: 3.034 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.636 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   4.620 ms/op
                 getUser·p0.999:  8.237 ms/op
                 getUser·p0.9999: 20.345 ms/op
                 getUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314309
  mean =      3.054 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22312 
    [ 2.500,  5.000) = 289678 
    [ 5.000,  7.500) = 1770 
    [ 7.500, 10.000) = 309 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.311 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.760 ms/op
     p(99.9000) =      8.482 ms/op
     p(99.9900) =     19.825 ms/op
     p(99.9990) =     20.677 ms/op
     p(99.9999) =     21.955 ms/op
    p(100.0000) =     21.955 ms/op


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
# Warmup Iteration   1: 5.872 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.158 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.062 ±(99.9%) 0.013 ms/op
Iteration   1: 3.954 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.092 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  20.546 ms/op
                 listUser·p0.9999: 26.018 ms/op
                 listUser·p1.00:   27.197 ms/op

Iteration   2: 4.006 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.364 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   7.044 ms/op
                 listUser·p0.999:  17.090 ms/op
                 listUser·p0.9999: 22.709 ms/op
                 listUser·p1.00:   23.888 ms/op

Iteration   3: 4.058 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.100 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   7.197 ms/op
                 listUser·p0.999:  16.649 ms/op
                 listUser·p0.9999: 22.413 ms/op
                 listUser·p1.00:   23.003 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239556
  mean =      4.006 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2512 
    [ 2.500,  5.000) = 214851 
    [ 5.000,  7.500) = 20611 
    [ 7.500, 10.000) = 1157 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 114 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.092 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.923 ms/op
     p(95.0000) =      5.644 ms/op
     p(99.0000) =      7.102 ms/op
     p(99.9000) =     17.170 ms/op
     p(99.9900) =     25.169 ms/op
     p(99.9990) =     26.896 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.543 ± 3.189  ops/ms
ClientGrpc.existUser                       thrpt       3  11.104 ± 2.728  ops/ms
ClientGrpc.getUser                         thrpt       3  10.604 ± 5.692  ops/ms
ClientGrpc.listUser                        thrpt       3   7.905 ± 0.459  ops/ms
ClientGrpc.createUser                       avgt       3   3.024 ± 0.454   ms/op
ClientGrpc.existUser                        avgt       3   2.895 ± 0.696   ms/op
ClientGrpc.getUser                          avgt       3   3.053 ± 0.863   ms/op
ClientGrpc.listUser                         avgt       3   4.000 ± 0.628   ms/op
ClientGrpc.createUser                     sample  320376   2.995 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.683           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.002           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.548           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.772           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.530           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.448           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.542           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.642           ms/op
ClientGrpc.existUser                      sample  328601   2.923 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.278           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.896           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.441           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.621           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.375           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.078           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.344           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.217           ms/op
ClientGrpc.getUser                        sample  314309   3.054 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.311           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.011           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.576           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.826           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.760           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.482           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.825           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.955           ms/op
ClientGrpc.listUser                       sample  239556   4.006 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.092           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.850           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.923           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.644           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.102           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.170           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.169           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.197           ms/op
