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
# Warmup Iteration   1: 1.984 ops/ms
# Warmup Iteration   2: 4.897 ops/ms
# Warmup Iteration   3: 6.356 ops/ms
Iteration   1: 6.947 ops/ms
Iteration   2: 7.296 ops/ms
Iteration   3: 7.091 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.111 ±(99.9%) 3.196 ops/ms [Average]
  (min, avg, max) = (6.947, 7.111, 7.296), stdev = 0.175
  CI (99.9%): [3.915, 10.308] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.951 ops/ms
# Warmup Iteration   2: 6.723 ops/ms
# Warmup Iteration   3: 7.622 ops/ms
Iteration   1: 7.933 ops/ms
Iteration   2: 7.527 ops/ms
Iteration   3: 7.757 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.739 ±(99.9%) 3.715 ops/ms [Average]
  (min, avg, max) = (7.527, 7.739, 7.933), stdev = 0.204
  CI (99.9%): [4.024, 11.454] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.763 ops/ms
# Warmup Iteration   2: 6.398 ops/ms
# Warmup Iteration   3: 6.850 ops/ms
Iteration   1: 7.136 ops/ms
Iteration   2: 7.162 ops/ms
Iteration   3: 7.120 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.139 ±(99.9%) 0.395 ops/ms [Average]
  (min, avg, max) = (7.120, 7.139, 7.162), stdev = 0.022
  CI (99.9%): [6.745, 7.534] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.194 ops/ms
# Warmup Iteration   2: 4.733 ops/ms
# Warmup Iteration   3: 5.097 ops/ms
Iteration   1: 5.249 ops/ms
Iteration   2: 5.261 ops/ms
Iteration   3: 5.175 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.228 ±(99.9%) 0.850 ops/ms [Average]
  (min, avg, max) = (5.175, 5.228, 5.261), stdev = 0.047
  CI (99.9%): [4.379, 6.078] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.699 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.936 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.690 ±(99.9%) 0.012 ms/op
Iteration   1: 4.666 ±(99.9%) 0.005 ms/op
Iteration   2: 4.670 ±(99.9%) 0.006 ms/op
Iteration   3: 4.584 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.640 ±(99.9%) 0.888 ms/op [Average]
  (min, avg, max) = (4.584, 4.640, 4.670), stdev = 0.049
  CI (99.9%): [3.752, 5.528] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.948 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.755 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.521 ±(99.9%) 0.002 ms/op
Iteration   1: 4.269 ±(99.9%) 0.004 ms/op
Iteration   2: 4.085 ±(99.9%) 0.005 ms/op
Iteration   3: 4.111 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.155 ±(99.9%) 1.815 ms/op [Average]
  (min, avg, max) = (4.085, 4.155, 4.269), stdev = 0.100
  CI (99.9%): [2.340, 5.970] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 6.837 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.950 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.654 ±(99.9%) 0.005 ms/op
Iteration   1: 4.662 ±(99.9%) 0.006 ms/op
Iteration   2: 4.452 ±(99.9%) 0.004 ms/op
Iteration   3: 4.417 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.510 ±(99.9%) 2.416 ms/op [Average]
  (min, avg, max) = (4.417, 4.510, 4.662), stdev = 0.132
  CI (99.9%): [2.094, 6.927] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.315 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 6.388 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 6.287 ±(99.9%) 0.023 ms/op
Iteration   1: 5.953 ±(99.9%) 0.012 ms/op
Iteration   2: 5.856 ±(99.9%) 0.019 ms/op
Iteration   3: 5.827 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.879 ±(99.9%) 1.209 ms/op [Average]
  (min, avg, max) = (5.827, 5.879, 5.953), stdev = 0.066
  CI (99.9%): [4.670, 7.088] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.077 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 5.005 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.588 ±(99.9%) 0.017 ms/op
Iteration   1: 4.476 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.073 ms/op
                 createUser·p0.50:   4.325 ms/op
                 createUser·p0.90:   5.677 ms/op
                 createUser·p0.95:   6.373 ms/op
                 createUser·p0.99:   8.618 ms/op
                 createUser·p0.999:  11.452 ms/op
                 createUser·p0.9999: 20.770 ms/op
                 createUser·p1.00:   21.266 ms/op

Iteration   2: 4.505 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.023 ms/op
                 createUser·p0.50:   4.293 ms/op
                 createUser·p0.90:   5.775 ms/op
                 createUser·p0.95:   6.472 ms/op
                 createUser·p0.99:   8.733 ms/op
                 createUser·p0.999:  18.939 ms/op
                 createUser·p0.9999: 21.391 ms/op
                 createUser·p1.00:   21.758 ms/op

Iteration   3: 4.600 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.075 ms/op
                 createUser·p0.50:   4.424 ms/op
                 createUser·p0.90:   5.931 ms/op
                 createUser·p0.95:   6.644 ms/op
                 createUser·p0.99:   8.864 ms/op
                 createUser·p0.999:  13.008 ms/op
                 createUser·p0.9999: 21.337 ms/op
                 createUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 212117
  mean =      4.526 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3158 
    [ 2.500,  5.000) = 155768 
    [ 5.000,  7.500) = 48330 
    [ 7.500, 10.000) = 3843 
    [10.000, 12.500) = 757 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.023 ms/op
     p(50.0000) =      4.342 ms/op
     p(90.0000) =      5.800 ms/op
     p(95.0000) =      6.496 ms/op
     p(99.0000) =      8.749 ms/op
     p(99.9000) =     13.886 ms/op
     p(99.9900) =     21.234 ms/op
     p(99.9990) =     21.758 ms/op
     p(99.9999) =     21.856 ms/op
    p(100.0000) =     21.856 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.507 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.768 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.361 ±(99.9%) 0.015 ms/op
Iteration   1: 4.333 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.987 ms/op
                 existUser·p0.50:   4.162 ms/op
                 existUser·p0.90:   5.651 ms/op
                 existUser·p0.95:   6.291 ms/op
                 existUser·p0.99:   8.241 ms/op
                 existUser·p0.999:  11.649 ms/op
                 existUser·p0.9999: 16.283 ms/op
                 existUser·p1.00:   16.531 ms/op

Iteration   2: 4.349 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.908 ms/op
                 existUser·p0.50:   4.153 ms/op
                 existUser·p0.90:   5.644 ms/op
                 existUser·p0.95:   6.439 ms/op
                 existUser·p0.99:   8.897 ms/op
                 existUser·p0.999:  14.109 ms/op
                 existUser·p0.9999: 24.007 ms/op
                 existUser·p1.00:   26.345 ms/op

Iteration   3: 4.182 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.762 ms/op
                 existUser·p0.50:   4.014 ms/op
                 existUser·p0.90:   5.358 ms/op
                 existUser·p0.95:   6.119 ms/op
                 existUser·p0.99:   8.716 ms/op
                 existUser·p0.999:  14.001 ms/op
                 existUser·p0.9999: 25.440 ms/op
                 existUser·p1.00:   27.754 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 223853
  mean =      4.287 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7527 
    [ 2.500,  5.000) = 175471 
    [ 5.000,  7.500) = 36469 
    [ 7.500, 10.000) = 3465 
    [10.000, 12.500) = 594 
    [12.500, 15.000) = 191 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.762 ms/op
     p(50.0000) =      4.104 ms/op
     p(90.0000) =      5.562 ms/op
     p(95.0000) =      6.283 ms/op
     p(99.0000) =      8.602 ms/op
     p(99.9000) =     13.388 ms/op
     p(99.9900) =     24.644 ms/op
     p(99.9990) =     27.116 ms/op
     p(99.9999) =     27.754 ms/op
    p(100.0000) =     27.754 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.187 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 4.972 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.514 ±(99.9%) 0.015 ms/op
Iteration   1: 4.421 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.124 ms/op
                 getUser·p0.50:   4.252 ms/op
                 getUser·p0.90:   5.603 ms/op
                 getUser·p0.95:   6.341 ms/op
                 getUser·p0.99:   8.765 ms/op
                 getUser·p0.999:  14.336 ms/op
                 getUser·p0.9999: 16.012 ms/op
                 getUser·p1.00:   17.138 ms/op

Iteration   2: 4.642 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.196 ms/op
                 getUser·p0.50:   4.456 ms/op
                 getUser·p0.90:   6.070 ms/op
                 getUser·p0.95:   6.791 ms/op
                 getUser·p0.99:   9.470 ms/op
                 getUser·p0.999:  13.422 ms/op
                 getUser·p0.9999: 21.809 ms/op
                 getUser·p1.00:   23.265 ms/op

Iteration   3: 4.435 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.878 ms/op
                 getUser·p0.50:   4.243 ms/op
                 getUser·p0.90:   5.726 ms/op
                 getUser·p0.95:   6.488 ms/op
                 getUser·p0.99:   8.749 ms/op
                 getUser·p0.999:  12.381 ms/op
                 getUser·p0.9999: 24.246 ms/op
                 getUser·p1.00:   28.672 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 213390
  mean =      4.497 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5203 
    [ 2.500,  5.000) = 156460 
    [ 5.000,  7.500) = 46570 
    [ 7.500, 10.000) = 4020 
    [10.000, 12.500) = 832 
    [12.500, 15.000) = 162 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.878 ms/op
     p(50.0000) =      4.301 ms/op
     p(90.0000) =      5.833 ms/op
     p(95.0000) =      6.554 ms/op
     p(99.0000) =      9.011 ms/op
     p(99.9000) =     13.370 ms/op
     p(99.9900) =     23.527 ms/op
     p(99.9990) =     25.152 ms/op
     p(99.9999) =     28.672 ms/op
    p(100.0000) =     28.672 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.566 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 6.462 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 6.109 ±(99.9%) 0.027 ms/op
Iteration   1: 6.093 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.901 ms/op
                 listUser·p0.50:   5.677 ms/op
                 listUser·p0.90:   8.298 ms/op
                 listUser·p0.95:   9.486 ms/op
                 listUser·p0.99:   11.911 ms/op
                 listUser·p0.999:  28.170 ms/op
                 listUser·p0.9999: 39.666 ms/op
                 listUser·p1.00:   43.581 ms/op

Iteration   2: 5.930 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.368 ms/op
                 listUser·p0.50:   5.530 ms/op
                 listUser·p0.90:   8.053 ms/op
                 listUser·p0.95:   9.142 ms/op
                 listUser·p0.99:   12.394 ms/op
                 listUser·p0.999:  19.461 ms/op
                 listUser·p0.9999: 24.837 ms/op
                 listUser·p1.00:   25.690 ms/op

Iteration   3: 6.060 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.649 ms/op
                 listUser·p0.50:   5.620 ms/op
                 listUser·p0.90:   8.438 ms/op
                 listUser·p0.95:   9.601 ms/op
                 listUser·p0.99:   12.567 ms/op
                 listUser·p0.999:  21.994 ms/op
                 listUser·p0.9999: 25.251 ms/op
                 listUser·p1.00:   25.657 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 159323
  mean =      6.027 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 44846 
    [ 5.000, 10.000) = 108776 
    [10.000, 15.000) = 5152 
    [15.000, 20.000) = 361 
    [20.000, 25.000) = 113 
    [25.000, 30.000) = 42 
    [30.000, 35.000) = 6 
    [35.000, 40.000) = 24 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.368 ms/op
     p(50.0000) =      5.603 ms/op
     p(90.0000) =      8.258 ms/op
     p(95.0000) =      9.421 ms/op
     p(99.0000) =     12.272 ms/op
     p(99.9000) =     21.333 ms/op
     p(99.9900) =     38.544 ms/op
     p(99.9990) =     43.387 ms/op
     p(99.9999) =     43.581 ms/op
    p(100.0000) =     43.581 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.111 ± 3.196  ops/ms
ClientGrpc.existUser                       thrpt       3   7.739 ± 3.715  ops/ms
ClientGrpc.getUser                         thrpt       3   7.139 ± 0.395  ops/ms
ClientGrpc.listUser                        thrpt       3   5.228 ± 0.850  ops/ms
ClientGrpc.createUser                       avgt       3   4.640 ± 0.888   ms/op
ClientGrpc.existUser                        avgt       3   4.155 ± 1.815   ms/op
ClientGrpc.getUser                          avgt       3   4.510 ± 2.416   ms/op
ClientGrpc.listUser                         avgt       3   5.879 ± 1.209   ms/op
ClientGrpc.createUser                     sample  212117   4.526 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.023           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.342           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.800           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.496           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.749           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.886           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.234           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.856           ms/op
ClientGrpc.existUser                      sample  223853   4.287 ± 0.009   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.762           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.104           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.562           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.283           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.602           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.388           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.644           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.754           ms/op
ClientGrpc.getUser                        sample  213390   4.497 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.878           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.301           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.833           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.554           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           9.011           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.370           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.527           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.672           ms/op
ClientGrpc.listUser                       sample  159323   6.027 ± 0.016   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.368           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.603           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.258           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.421           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.272           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          21.333           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          38.544           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          43.581           ms/op
