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
# Warmup Iteration   1: 4.551 ops/ms
# Warmup Iteration   2: 9.158 ops/ms
# Warmup Iteration   3: 9.949 ops/ms
Iteration   1: 9.964 ops/ms
Iteration   2: 10.063 ops/ms
Iteration   3: 10.192 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.073 ±(99.9%) 2.086 ops/ms [Average]
  (min, avg, max) = (9.964, 10.073, 10.192), stdev = 0.114
  CI (99.9%): [7.987, 12.159] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.581 ops/ms
# Warmup Iteration   2: 10.302 ops/ms
# Warmup Iteration   3: 10.414 ops/ms
Iteration   1: 10.338 ops/ms
Iteration   2: 10.328 ops/ms
Iteration   3: 10.491 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.386 ±(99.9%) 1.669 ops/ms [Average]
  (min, avg, max) = (10.328, 10.386, 10.491), stdev = 0.091
  CI (99.9%): [8.717, 12.055] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:50
# Fork: 1 of 1
# Warmup Iteration   1: 6.779 ops/ms
# Warmup Iteration   2: 9.865 ops/ms
# Warmup Iteration   3: 10.111 ops/ms
Iteration   1: 10.041 ops/ms
Iteration   2: 10.057 ops/ms
Iteration   3: 9.923 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.007 ±(99.9%) 1.342 ops/ms [Average]
  (min, avg, max) = (9.923, 10.007, 10.057), stdev = 0.074
  CI (99.9%): [8.665, 11.349] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.348 ops/ms
# Warmup Iteration   2: 7.652 ops/ms
# Warmup Iteration   3: 7.554 ops/ms
Iteration   1: 7.861 ops/ms
Iteration   2: 7.908 ops/ms
Iteration   3: 7.844 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.871 ±(99.9%) 0.610 ops/ms [Average]
  (min, avg, max) = (7.844, 7.871, 7.908), stdev = 0.033
  CI (99.9%): [7.261, 8.481] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.208 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.171 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.187 ±(99.9%) 0.003 ms/op
Iteration   1: 3.116 ±(99.9%) 0.002 ms/op
Iteration   2: 3.203 ±(99.9%) 0.002 ms/op
Iteration   3: 3.145 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.154 ±(99.9%) 0.808 ms/op [Average]
  (min, avg, max) = (3.116, 3.154, 3.203), stdev = 0.044
  CI (99.9%): [2.347, 3.962] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.179 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.068 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.041 ±(99.9%) 0.002 ms/op
Iteration   1: 3.034 ±(99.9%) 0.003 ms/op
Iteration   2: 3.049 ±(99.9%) 0.002 ms/op
Iteration   3: 2.995 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.026 ±(99.9%) 0.505 ms/op [Average]
  (min, avg, max) = (2.995, 3.026, 3.049), stdev = 0.028
  CI (99.9%): [2.522, 3.531] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.223 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.251 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.197 ±(99.9%) 0.003 ms/op
Iteration   1: 3.157 ±(99.9%) 0.002 ms/op
Iteration   2: 3.186 ±(99.9%) 0.003 ms/op
Iteration   3: 3.196 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.180 ±(99.9%) 0.369 ms/op [Average]
  (min, avg, max) = (3.157, 3.180, 3.196), stdev = 0.020
  CI (99.9%): [2.810, 3.549] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.517 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.235 ±(99.9%) 0.066 ms/op
# Warmup Iteration   3: 4.049 ±(99.9%) 0.016 ms/op
Iteration   1: 3.985 ±(99.9%) 0.011 ms/op
Iteration   2: 4.037 ±(99.9%) 0.005 ms/op
Iteration   3: 4.109 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.044 ±(99.9%) 1.129 ms/op [Average]
  (min, avg, max) = (3.985, 4.044, 4.109), stdev = 0.062
  CI (99.9%): [2.915, 5.172] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.982 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.236 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.177 ±(99.9%) 0.006 ms/op
Iteration   1: 3.219 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.776 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.071 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  10.513 ms/op
                 createUser·p0.9999: 13.060 ms/op
                 createUser·p1.00:   13.599 ms/op

Iteration   2: 3.247 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.943 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.985 ms/op
                 createUser·p0.95:   4.174 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  7.463 ms/op
                 createUser·p0.9999: 16.423 ms/op
                 createUser·p1.00:   16.941 ms/op

Iteration   3: 3.191 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.007 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  9.823 ms/op
                 createUser·p0.9999: 25.034 ms/op
                 createUser·p1.00:   25.559 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 298198
  mean =      3.219 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20266 
    [ 2.500,  5.000) = 276661 
    [ 5.000,  7.500) = 832 
    [ 7.500, 10.000) = 166 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.776 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.088 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      9.650 ms/op
     p(99.9900) =     23.213 ms/op
     p(99.9990) =     25.396 ms/op
     p(99.9999) =     25.559 ms/op
    p(100.0000) =     25.559 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.848 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.167 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.088 ±(99.9%) 0.006 ms/op
Iteration   1: 3.130 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.741 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.846 ms/op
                 existUser·p0.95:   4.026 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  7.247 ms/op
                 existUser·p0.9999: 19.654 ms/op
                 existUser·p1.00:   21.856 ms/op

Iteration   2: 3.031 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.578 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.724 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  7.086 ms/op
                 existUser·p0.9999: 24.438 ms/op
                 existUser·p1.00:   25.100 ms/op

Iteration   3: 3.043 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.658 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   3.887 ms/op
                 existUser·p0.99:   4.596 ms/op
                 existUser·p0.999:  11.715 ms/op
                 existUser·p0.9999: 23.478 ms/op
                 existUser·p1.00:   23.986 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 312748
  mean =      3.067 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36512 
    [ 2.500,  5.000) = 274991 
    [ 5.000,  7.500) = 752 
    [ 7.500, 10.000) = 135 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.578 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      3.940 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =     10.289 ms/op
     p(99.9900) =     23.518 ms/op
     p(99.9990) =     24.998 ms/op
     p(99.9999) =     25.100 ms/op
    p(100.0000) =     25.100 ms/op


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
# Warmup Iteration   1: 4.209 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.273 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.167 ±(99.9%) 0.006 ms/op
Iteration   1: 3.181 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.670 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.903 ms/op
                 getUser·p0.95:   4.108 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  8.191 ms/op
                 getUser·p0.9999: 12.582 ms/op
                 getUser·p1.00:   12.812 ms/op

Iteration   2: 3.172 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.857 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.899 ms/op
                 getUser·p0.95:   4.100 ms/op
                 getUser·p0.99:   4.561 ms/op
                 getUser·p0.999:  7.941 ms/op
                 getUser·p0.9999: 14.496 ms/op
                 getUser·p1.00:   14.729 ms/op

Iteration   3: 3.197 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.756 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.867 ms/op
                 getUser·p0.95:   4.026 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  6.569 ms/op
                 getUser·p0.9999: 17.301 ms/op
                 getUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 301500
  mean =      3.183 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 594 
    [ 1.250,  2.500) = 21509 
    [ 2.500,  3.750) = 234041 
    [ 3.750,  5.000) = 44154 
    [ 5.000,  6.250) = 685 
    [ 6.250,  7.500) = 210 
    [ 7.500,  8.750) = 79 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 48 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 38 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.670 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      7.545 ms/op
     p(99.9900) =     16.936 ms/op
     p(99.9990) =     17.563 ms/op
     p(99.9999) =     17.662 ms/op
    p(100.0000) =     17.662 ms/op


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
# Warmup Iteration   1: 5.363 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.226 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.104 ±(99.9%) 0.012 ms/op
Iteration   1: 4.067 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.475 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   7.077 ms/op
                 listUser·p0.999:  14.038 ms/op
                 listUser·p0.9999: 20.952 ms/op
                 listUser·p1.00:   21.365 ms/op

Iteration   2: 4.105 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.014 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.923 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  14.580 ms/op
                 listUser·p0.9999: 18.127 ms/op
                 listUser·p1.00:   19.399 ms/op

Iteration   3: 4.199 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.055 ms/op
                 listUser·p0.50:   4.006 ms/op
                 listUser·p0.90:   5.374 ms/op
                 listUser·p0.95:   5.988 ms/op
                 listUser·p0.99:   7.102 ms/op
                 listUser·p0.999:  19.066 ms/op
                 listUser·p0.9999: 23.762 ms/op
                 listUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 232811
  mean =      4.123 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2122 
    [ 2.500,  5.000) = 202371 
    [ 5.000,  7.500) = 26770 
    [ 7.500, 10.000) = 1023 
    [10.000, 12.500) = 159 
    [12.500, 15.000) = 146 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.014 ms/op
     p(50.0000) =      3.953 ms/op
     p(90.0000) =      5.235 ms/op
     p(95.0000) =      5.931 ms/op
     p(99.0000) =      7.078 ms/op
     p(99.9000) =     14.896 ms/op
     p(99.9900) =     22.222 ms/op
     p(99.9990) =     24.139 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.073 ± 2.086  ops/ms
ClientGrpc.existUser                       thrpt       3  10.386 ± 1.669  ops/ms
ClientGrpc.getUser                         thrpt       3  10.007 ± 1.342  ops/ms
ClientGrpc.listUser                        thrpt       3   7.871 ± 0.610  ops/ms
ClientGrpc.createUser                       avgt       3   3.154 ± 0.808   ms/op
ClientGrpc.existUser                        avgt       3   3.026 ± 0.505   ms/op
ClientGrpc.getUser                          avgt       3   3.180 ± 0.369   ms/op
ClientGrpc.listUser                         avgt       3   4.044 ± 1.129   ms/op
ClientGrpc.createUser                     sample  298198   3.219 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.776           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.195           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.895           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.088           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.514           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.650           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.213           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.559           ms/op
ClientGrpc.existUser                      sample  312748   3.067 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.578           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.027           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.756           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.940           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.448           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.289           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.518           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.100           ms/op
ClientGrpc.getUser                        sample  301500   3.183 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.670           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.158           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.887           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.080           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.489           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.545           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.936           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.662           ms/op
ClientGrpc.listUser                       sample  232811   4.123 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.014           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.953           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.235           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.931           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.078           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.896           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.222           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.216           ms/op
