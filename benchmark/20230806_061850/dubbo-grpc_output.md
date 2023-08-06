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
# Warmup Iteration   1: 4.353 ops/ms
# Warmup Iteration   2: 9.246 ops/ms
# Warmup Iteration   3: 10.274 ops/ms
Iteration   1: 10.582 ops/ms
Iteration   2: 10.842 ops/ms
Iteration   3: 10.675 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.700 ±(99.9%) 2.405 ops/ms [Average]
  (min, avg, max) = (10.582, 10.700, 10.842), stdev = 0.132
  CI (99.9%): [8.294, 13.105] (assumes normal distribution)


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
# Warmup Iteration   1: 7.861 ops/ms
# Warmup Iteration   2: 10.735 ops/ms
# Warmup Iteration   3: 11.077 ops/ms
Iteration   1: 11.196 ops/ms
Iteration   2: 11.115 ops/ms
Iteration   3: 11.269 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.193 ±(99.9%) 1.400 ops/ms [Average]
  (min, avg, max) = (11.115, 11.193, 11.269), stdev = 0.077
  CI (99.9%): [9.793, 12.593] (assumes normal distribution)


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
# Warmup Iteration   1: 7.638 ops/ms
# Warmup Iteration   2: 10.305 ops/ms
# Warmup Iteration   3: 10.842 ops/ms
Iteration   1: 10.737 ops/ms
Iteration   2: 10.603 ops/ms
Iteration   3: 10.541 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.627 ±(99.9%) 1.825 ops/ms [Average]
  (min, avg, max) = (10.541, 10.627, 10.737), stdev = 0.100
  CI (99.9%): [8.802, 12.453] (assumes normal distribution)


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
# Warmup Iteration   1: 6.136 ops/ms
# Warmup Iteration   2: 7.970 ops/ms
# Warmup Iteration   3: 8.156 ops/ms
Iteration   1: 8.161 ops/ms
Iteration   2: 8.159 ops/ms
Iteration   3: 8.301 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.207 ±(99.9%) 1.484 ops/ms [Average]
  (min, avg, max) = (8.159, 8.207, 8.301), stdev = 0.081
  CI (99.9%): [6.723, 9.691] (assumes normal distribution)


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
# Warmup Iteration   1: 4.013 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.130 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.007 ms/op
Iteration   1: 3.047 ±(99.9%) 0.003 ms/op
Iteration   2: 2.957 ±(99.9%) 0.003 ms/op
Iteration   3: 3.023 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.009 ±(99.9%) 0.851 ms/op [Average]
  (min, avg, max) = (2.957, 3.009, 3.047), stdev = 0.047
  CI (99.9%): [2.158, 3.861] (assumes normal distribution)


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
# Warmup Iteration   1: 3.797 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.011 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.913 ±(99.9%) 0.005 ms/op
Iteration   1: 2.861 ±(99.9%) 0.004 ms/op
Iteration   2: 2.862 ±(99.9%) 0.004 ms/op
Iteration   3: 2.952 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.892 ±(99.9%) 0.949 ms/op [Average]
  (min, avg, max) = (2.861, 2.892, 2.952), stdev = 0.052
  CI (99.9%): [1.943, 3.840] (assumes normal distribution)


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
# Warmup Iteration   1: 4.055 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.092 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.051 ±(99.9%) 0.003 ms/op
Iteration   1: 3.032 ±(99.9%) 0.002 ms/op
Iteration   2: 3.003 ±(99.9%) 0.003 ms/op
Iteration   3: 3.007 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.014 ±(99.9%) 0.286 ms/op [Average]
  (min, avg, max) = (3.003, 3.014, 3.032), stdev = 0.016
  CI (99.9%): [2.728, 3.300] (assumes normal distribution)


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
# Warmup Iteration   1: 3.972 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 4.065 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.972 ±(99.9%) 0.011 ms/op
Iteration   1: 3.924 ±(99.9%) 0.020 ms/op
Iteration   2: 3.988 ±(99.9%) 0.020 ms/op
Iteration   3: 3.872 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.928 ±(99.9%) 1.064 ms/op [Average]
  (min, avg, max) = (3.872, 3.928, 3.988), stdev = 0.058
  CI (99.9%): [2.863, 4.992] (assumes normal distribution)


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
# Warmup Iteration   1: 3.992 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.162 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.006 ms/op
Iteration   1: 2.989 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.571 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.437 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  8.249 ms/op
                 createUser·p0.9999: 16.120 ms/op
                 createUser·p1.00:   16.548 ms/op

Iteration   2: 3.037 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.579 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  9.740 ms/op
                 createUser·p0.9999: 17.957 ms/op
                 createUser·p1.00:   19.137 ms/op

Iteration   3: 3.005 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.376 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.669 ms/op
                 createUser·p0.999:  10.682 ms/op
                 createUser·p0.9999: 25.035 ms/op
                 createUser·p1.00:   25.231 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318747
  mean =      3.010 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25517 
    [ 2.500,  5.000) = 291292 
    [ 5.000,  7.500) = 1340 
    [ 7.500, 10.000) = 268 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.376 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      4.579 ms/op
     p(99.9000) =     10.310 ms/op
     p(99.9900) =     24.445 ms/op
     p(99.9990) =     25.199 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


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
# Warmup Iteration   1: 3.829 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.961 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.874 ±(99.9%) 0.006 ms/op
Iteration   1: 2.889 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.683 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.651 ms/op
                 existUser·p0.99:   4.612 ms/op
                 existUser·p0.999:  7.842 ms/op
                 existUser·p0.9999: 11.516 ms/op
                 existUser·p1.00:   11.747 ms/op

Iteration   2: 2.898 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.537 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   4.596 ms/op
                 existUser·p0.999:  8.454 ms/op
                 existUser·p0.9999: 15.203 ms/op
                 existUser·p1.00:   15.417 ms/op

Iteration   3: 2.870 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.700 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   4.448 ms/op
                 existUser·p0.999:  6.558 ms/op
                 existUser·p0.9999: 13.018 ms/op
                 existUser·p1.00:   13.550 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332569
  mean =      2.885 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2756 
    [ 1.250,  2.500) = 44204 
    [ 2.500,  3.750) = 273090 
    [ 3.750,  5.000) = 10805 
    [ 5.000,  6.250) = 915 
    [ 6.250,  7.500) = 451 
    [ 7.500,  8.750) = 123 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 66 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.537 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.412 ms/op
     p(95.0000) =      3.641 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =      7.545 ms/op
     p(99.9900) =     13.491 ms/op
     p(99.9990) =     15.358 ms/op
     p(99.9999) =     15.417 ms/op
    p(100.0000) =     15.417 ms/op


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
# Warmup Iteration   1: 4.066 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.149 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.035 ±(99.9%) 0.006 ms/op
Iteration   1: 3.028 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.580 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.850 ms/op
                 getUser·p0.999:  10.055 ms/op
                 getUser·p0.9999: 17.400 ms/op
                 getUser·p1.00:   17.564 ms/op

Iteration   2: 3.035 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.589 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  8.198 ms/op
                 getUser·p0.9999: 16.080 ms/op
                 getUser·p1.00:   16.450 ms/op

Iteration   3: 3.000 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.793 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.396 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  7.940 ms/op
                 getUser·p0.9999: 22.205 ms/op
                 getUser·p1.00:   23.036 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317872
  mean =      3.021 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25636 
    [ 2.500,  5.000) = 290101 
    [ 5.000,  7.500) = 1661 
    [ 7.500, 10.000) = 239 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.580 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =      8.331 ms/op
     p(99.9900) =     20.094 ms/op
     p(99.9990) =     22.768 ms/op
     p(99.9999) =     23.036 ms/op
    p(100.0000) =     23.036 ms/op


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
# Warmup Iteration   1: 4.684 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.075 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.953 ±(99.9%) 0.011 ms/op
Iteration   1: 3.996 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.108 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  13.092 ms/op
                 listUser·p0.9999: 18.710 ms/op
                 listUser·p1.00:   19.235 ms/op

Iteration   2: 3.916 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.161 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  15.352 ms/op
                 listUser·p0.9999: 24.865 ms/op
                 listUser·p1.00:   25.395 ms/op

Iteration   3: 3.947 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.180 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   7.291 ms/op
                 listUser·p0.999:  14.237 ms/op
                 listUser·p0.9999: 17.302 ms/op
                 listUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242957
  mean =      3.953 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3956 
    [ 2.500,  5.000) = 217063 
    [ 5.000,  7.500) = 20180 
    [ 7.500, 10.000) = 1177 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 293 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.108 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      4.907 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      7.111 ms/op
     p(99.9000) =     14.075 ms/op
     p(99.9900) =     21.313 ms/op
     p(99.9990) =     25.320 ms/op
     p(99.9999) =     25.395 ms/op
    p(100.0000) =     25.395 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.700 ± 2.405  ops/ms
ClientGrpc.existUser                       thrpt       3  11.193 ± 1.400  ops/ms
ClientGrpc.getUser                         thrpt       3  10.627 ± 1.825  ops/ms
ClientGrpc.listUser                        thrpt       3   8.207 ± 1.484  ops/ms
ClientGrpc.createUser                       avgt       3   3.009 ± 0.851   ms/op
ClientGrpc.existUser                        avgt       3   2.892 ± 0.949   ms/op
ClientGrpc.getUser                          avgt       3   3.014 ± 0.286   ms/op
ClientGrpc.listUser                         avgt       3   3.928 ± 1.064   ms/op
ClientGrpc.createUser                     sample  318747   3.010 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.376           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.990           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.494           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.748           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.579           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.310           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.445           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.231           ms/op
ClientGrpc.existUser                      sample  332569   2.885 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.537           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.412           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.641           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.547           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.545           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.491           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.417           ms/op
ClientGrpc.getUser                        sample  317872   3.021 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.580           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.998           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.547           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.850           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.604           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.331           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.094           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.036           ms/op
ClientGrpc.listUser                       sample  242957   3.953 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.108           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.805           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.907           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.612           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.111           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.075           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.313           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.395           ms/op
