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
# Warmup Iteration   1: 3.451 ops/ms
# Warmup Iteration   2: 6.894 ops/ms
# Warmup Iteration   3: 8.613 ops/ms
Iteration   1: 8.975 ops/ms
Iteration   2: 9.285 ops/ms
Iteration   3: 9.158 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.140 ±(99.9%) 2.846 ops/ms [Average]
  (min, avg, max) = (8.975, 9.140, 9.285), stdev = 0.156
  CI (99.9%): [6.294, 11.985] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.116 ops/ms
# Warmup Iteration   2: 9.543 ops/ms
# Warmup Iteration   3: 9.546 ops/ms
Iteration   1: 9.557 ops/ms
Iteration   2: 9.654 ops/ms
Iteration   3: 9.493 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.568 ±(99.9%) 1.472 ops/ms [Average]
  (min, avg, max) = (9.493, 9.568, 9.654), stdev = 0.081
  CI (99.9%): [8.096, 11.041] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.898 ops/ms
# Warmup Iteration   2: 8.830 ops/ms
# Warmup Iteration   3: 8.896 ops/ms
Iteration   1: 9.153 ops/ms
Iteration   2: 9.129 ops/ms
Iteration   3: 9.015 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.099 ±(99.9%) 1.349 ops/ms [Average]
  (min, avg, max) = (9.015, 9.099, 9.153), stdev = 0.074
  CI (99.9%): [7.750, 10.448] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.393 ops/ms
# Warmup Iteration   2: 6.458 ops/ms
# Warmup Iteration   3: 6.885 ops/ms
Iteration   1: 6.915 ops/ms
Iteration   2: 6.845 ops/ms
Iteration   3: 6.777 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.846 ±(99.9%) 1.258 ops/ms [Average]
  (min, avg, max) = (6.777, 6.846, 6.915), stdev = 0.069
  CI (99.9%): [5.588, 8.103] (assumes normal distribution)


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
# Warmup Iteration   1: 5.110 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.724 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 3.641 ±(99.9%) 0.004 ms/op
Iteration   1: 3.454 ±(99.9%) 0.004 ms/op
Iteration   2: 3.451 ±(99.9%) 0.002 ms/op
Iteration   3: 3.514 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.473 ±(99.9%) 0.647 ms/op [Average]
  (min, avg, max) = (3.451, 3.473, 3.514), stdev = 0.035
  CI (99.9%): [2.826, 4.120] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.914 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.575 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.436 ±(99.9%) 0.002 ms/op
Iteration   1: 3.312 ±(99.9%) 0.003 ms/op
Iteration   2: 3.341 ±(99.9%) 0.004 ms/op
Iteration   3: 3.333 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.329 ±(99.9%) 0.274 ms/op [Average]
  (min, avg, max) = (3.312, 3.329, 3.341), stdev = 0.015
  CI (99.9%): [3.055, 3.603] (assumes normal distribution)


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
# Warmup Iteration   1: 5.138 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.705 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.453 ±(99.9%) 0.005 ms/op
Iteration   1: 3.482 ±(99.9%) 0.005 ms/op
Iteration   2: 3.503 ±(99.9%) 0.006 ms/op
Iteration   3: 3.528 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.504 ±(99.9%) 0.427 ms/op [Average]
  (min, avg, max) = (3.482, 3.504, 3.528), stdev = 0.023
  CI (99.9%): [3.077, 3.931] (assumes normal distribution)


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
# Warmup Iteration   1: 5.540 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.941 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.596 ±(99.9%) 0.022 ms/op
Iteration   1: 4.526 ±(99.9%) 0.011 ms/op
Iteration   2: 4.511 ±(99.9%) 0.022 ms/op
Iteration   3: 4.677 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.571 ±(99.9%) 1.673 ms/op [Average]
  (min, avg, max) = (4.511, 4.571, 4.677), stdev = 0.092
  CI (99.9%): [2.898, 6.244] (assumes normal distribution)


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
# Warmup Iteration   1: 4.997 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.803 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.543 ±(99.9%) 0.008 ms/op
Iteration   1: 3.492 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.891 ms/op
                 createUser·p0.50:   3.465 ms/op
                 createUser·p0.90:   4.080 ms/op
                 createUser·p0.95:   4.407 ms/op
                 createUser·p0.99:   5.284 ms/op
                 createUser·p0.999:  7.656 ms/op
                 createUser·p0.9999: 14.738 ms/op
                 createUser·p1.00:   15.172 ms/op

Iteration   2: 3.512 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.921 ms/op
                 createUser·p0.50:   3.486 ms/op
                 createUser·p0.90:   4.059 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   5.317 ms/op
                 createUser·p0.999:  7.594 ms/op
                 createUser·p0.9999: 17.596 ms/op
                 createUser·p1.00:   18.022 ms/op

Iteration   3: 3.534 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.773 ms/op
                 createUser·p0.50:   3.498 ms/op
                 createUser·p0.90:   4.096 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   5.038 ms/op
                 createUser·p0.999:  7.897 ms/op
                 createUser·p0.9999: 22.157 ms/op
                 createUser·p1.00:   23.003 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 273345
  mean =      3.513 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6603 
    [ 2.500,  5.000) = 263256 
    [ 5.000,  7.500) = 3141 
    [ 7.500, 10.000) = 185 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.773 ms/op
     p(50.0000) =      3.482 ms/op
     p(90.0000) =      4.080 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.198 ms/op
     p(99.9000) =      7.755 ms/op
     p(99.9900) =     20.119 ms/op
     p(99.9990) =     22.890 ms/op
     p(99.9999) =     23.003 ms/op
    p(100.0000) =     23.003 ms/op


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
# Warmup Iteration   1: 4.653 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.545 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.269 ±(99.9%) 0.008 ms/op
Iteration   1: 3.376 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.698 ms/op
                 existUser·p0.50:   3.346 ms/op
                 existUser·p0.90:   4.006 ms/op
                 existUser·p0.95:   4.227 ms/op
                 existUser·p0.99:   5.063 ms/op
                 existUser·p0.999:  7.512 ms/op
                 existUser·p0.9999: 18.793 ms/op
                 existUser·p1.00:   19.005 ms/op

Iteration   2: 3.361 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.999 ms/op
                 existUser·p0.50:   3.371 ms/op
                 existUser·p0.90:   3.895 ms/op
                 existUser·p0.95:   4.141 ms/op
                 existUser·p0.99:   5.325 ms/op
                 existUser·p0.999:  9.058 ms/op
                 existUser·p0.9999: 16.054 ms/op
                 existUser·p1.00:   17.433 ms/op

Iteration   3: 3.344 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.812 ms/op
                 existUser·p0.50:   3.334 ms/op
                 existUser·p0.90:   3.781 ms/op
                 existUser·p0.95:   3.998 ms/op
                 existUser·p0.99:   5.047 ms/op
                 existUser·p0.999:  7.134 ms/op
                 existUser·p0.9999: 19.464 ms/op
                 existUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 285630
  mean =      3.360 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12519 
    [ 2.500,  5.000) = 269802 
    [ 5.000,  7.500) = 2962 
    [ 7.500, 10.000) = 206 
    [10.000, 12.500) = 10 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.698 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.153 ms/op
     p(99.0000) =      5.136 ms/op
     p(99.9000) =      7.823 ms/op
     p(99.9900) =     18.969 ms/op
     p(99.9990) =     19.497 ms/op
     p(99.9999) =     20.218 ms/op
    p(100.0000) =     20.218 ms/op


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
# Warmup Iteration   1: 5.205 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.695 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.550 ±(99.9%) 0.008 ms/op
Iteration   1: 3.555 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.005 ms/op
                 getUser·p0.50:   3.498 ms/op
                 getUser·p0.90:   4.174 ms/op
                 getUser·p0.95:   4.415 ms/op
                 getUser·p0.99:   5.571 ms/op
                 getUser·p0.999:  11.201 ms/op
                 getUser·p0.9999: 15.153 ms/op
                 getUser·p1.00:   16.204 ms/op

Iteration   2: 3.470 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.081 ms/op
                 getUser·p0.50:   3.449 ms/op
                 getUser·p0.90:   3.908 ms/op
                 getUser·p0.95:   4.100 ms/op
                 getUser·p0.99:   4.997 ms/op
                 getUser·p0.999:  7.120 ms/op
                 getUser·p0.9999: 14.689 ms/op
                 getUser·p1.00:   14.959 ms/op

Iteration   3: 3.471 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.908 ms/op
                 getUser·p0.50:   3.445 ms/op
                 getUser·p0.90:   4.096 ms/op
                 getUser·p0.95:   4.375 ms/op
                 getUser·p0.99:   5.382 ms/op
                 getUser·p0.999:  7.332 ms/op
                 getUser·p0.9999: 20.473 ms/op
                 getUser·p1.00:   20.873 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 274505
  mean =      3.498 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6563 
    [ 2.500,  5.000) = 263912 
    [ 5.000,  7.500) = 3587 
    [ 7.500, 10.000) = 235 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.908 ms/op
     p(50.0000) =      3.461 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.349 ms/op
     p(99.9000) =      8.651 ms/op
     p(99.9900) =     18.847 ms/op
     p(99.9990) =     20.702 ms/op
     p(99.9999) =     20.873 ms/op
    p(100.0000) =     20.873 ms/op


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
# Warmup Iteration   1: 5.692 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.927 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.692 ±(99.9%) 0.014 ms/op
Iteration   1: 4.473 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.468 ms/op
                 listUser·p0.50:   4.301 ms/op
                 listUser·p0.90:   5.423 ms/op
                 listUser·p0.95:   6.554 ms/op
                 listUser·p0.99:   8.274 ms/op
                 listUser·p0.999:  15.244 ms/op
                 listUser·p0.9999: 20.460 ms/op
                 listUser·p1.00:   21.430 ms/op

Iteration   2: 4.608 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.350 ms/op
                 listUser·p0.50:   4.440 ms/op
                 listUser·p0.90:   5.603 ms/op
                 listUser·p0.95:   6.488 ms/op
                 listUser·p0.99:   8.406 ms/op
                 listUser·p0.999:  17.387 ms/op
                 listUser·p0.9999: 20.257 ms/op
                 listUser·p1.00:   23.167 ms/op

Iteration   3: 4.606 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.985 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   5.448 ms/op
                 listUser·p0.95:   6.447 ms/op
                 listUser·p0.99:   8.004 ms/op
                 listUser·p0.999:  19.366 ms/op
                 listUser·p0.9999: 30.017 ms/op
                 listUser·p1.00:   30.638 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 210321
  mean =      4.562 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 555 
    [ 2.500,  5.000) = 174996 
    [ 5.000,  7.500) = 30444 
    [ 7.500, 10.000) = 3584 
    [10.000, 12.500) = 296 
    [12.500, 15.000) = 131 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.985 ms/op
     p(50.0000) =      4.399 ms/op
     p(90.0000) =      5.497 ms/op
     p(95.0000) =      6.496 ms/op
     p(99.0000) =      8.215 ms/op
     p(99.9000) =     17.062 ms/op
     p(99.9900) =     29.752 ms/op
     p(99.9990) =     30.562 ms/op
     p(99.9999) =     30.638 ms/op
    p(100.0000) =     30.638 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.140 ± 2.846  ops/ms
ClientGrpc.existUser                       thrpt       3   9.568 ± 1.472  ops/ms
ClientGrpc.getUser                         thrpt       3   9.099 ± 1.349  ops/ms
ClientGrpc.listUser                        thrpt       3   6.846 ± 1.258  ops/ms
ClientGrpc.createUser                       avgt       3   3.473 ± 0.647   ms/op
ClientGrpc.existUser                        avgt       3   3.329 ± 0.274   ms/op
ClientGrpc.getUser                          avgt       3   3.504 ± 0.427   ms/op
ClientGrpc.listUser                         avgt       3   4.571 ± 1.673   ms/op
ClientGrpc.createUser                     sample  273345   3.513 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.773           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.482           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.080           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.342           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.198           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.755           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.119           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.003           ms/op
ClientGrpc.existUser                      sample  285630   3.360 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.698           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.351           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.895           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.153           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.136           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.823           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.969           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.218           ms/op
ClientGrpc.getUser                        sample  274505   3.498 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.908           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.461           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.055           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.325           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.349           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.651           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.847           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.873           ms/op
ClientGrpc.listUser                       sample  210321   4.562 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.985           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.399           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.497           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.496           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.215           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.062           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.752           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.638           ms/op
