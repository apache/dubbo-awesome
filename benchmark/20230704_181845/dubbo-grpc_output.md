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
# Warmup Iteration   1: 4.002 ops/ms
# Warmup Iteration   2: 9.131 ops/ms
# Warmup Iteration   3: 9.908 ops/ms
Iteration   1: 10.459 ops/ms
Iteration   2: 10.626 ops/ms
Iteration   3: 10.578 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.554 ±(99.9%) 1.566 ops/ms [Average]
  (min, avg, max) = (10.459, 10.554, 10.626), stdev = 0.086
  CI (99.9%): [8.989, 12.120] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.266 ops/ms
# Warmup Iteration   2: 10.568 ops/ms
# Warmup Iteration   3: 10.839 ops/ms
Iteration   1: 11.233 ops/ms
Iteration   2: 11.225 ops/ms
Iteration   3: 11.620 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.359 ±(99.9%) 4.118 ops/ms [Average]
  (min, avg, max) = (11.225, 11.359, 11.620), stdev = 0.226
  CI (99.9%): [7.241, 15.478] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.794 ops/ms
# Warmup Iteration   2: 9.836 ops/ms
# Warmup Iteration   3: 10.340 ops/ms
Iteration   1: 10.434 ops/ms
Iteration   2: 10.458 ops/ms
Iteration   3: 10.500 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.464 ±(99.9%) 0.612 ops/ms [Average]
  (min, avg, max) = (10.434, 10.464, 10.500), stdev = 0.034
  CI (99.9%): [9.852, 11.075] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.667 ops/ms
# Warmup Iteration   2: 7.662 ops/ms
# Warmup Iteration   3: 7.995 ops/ms
Iteration   1: 7.907 ops/ms
Iteration   2: 8.107 ops/ms
Iteration   3: 8.030 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.015 ±(99.9%) 1.845 ops/ms [Average]
  (min, avg, max) = (7.907, 8.015, 8.107), stdev = 0.101
  CI (99.9%): [6.169, 9.860] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.517 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.234 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.002 ms/op
Iteration   1: 3.100 ±(99.9%) 0.002 ms/op
Iteration   2: 3.074 ±(99.9%) 0.003 ms/op
Iteration   3: 3.059 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.078 ±(99.9%) 0.380 ms/op [Average]
  (min, avg, max) = (3.059, 3.078, 3.100), stdev = 0.021
  CI (99.9%): [2.698, 3.458] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.901 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.041 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.965 ±(99.9%) 0.002 ms/op
Iteration   1: 2.939 ±(99.9%) 0.004 ms/op
Iteration   2: 2.937 ±(99.9%) 0.002 ms/op
Iteration   3: 2.939 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.938 ±(99.9%) 0.015 ms/op [Average]
  (min, avg, max) = (2.937, 2.938, 2.939), stdev = 0.001
  CI (99.9%): [2.923, 2.954] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.140 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.209 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.077 ±(99.9%) 0.022 ms/op
Iteration   1: 3.042 ±(99.9%) 0.003 ms/op
Iteration   2: 3.044 ±(99.9%) 0.005 ms/op
Iteration   3: 3.121 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.069 ±(99.9%) 0.816 ms/op [Average]
  (min, avg, max) = (3.042, 3.069, 3.121), stdev = 0.045
  CI (99.9%): [2.253, 3.886] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.600 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 4.410 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.076 ±(99.9%) 0.025 ms/op
Iteration   1: 3.932 ±(99.9%) 0.015 ms/op
Iteration   2: 4.041 ±(99.9%) 0.022 ms/op
Iteration   3: 4.022 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.998 ±(99.9%) 1.063 ms/op [Average]
  (min, avg, max) = (3.932, 3.998, 4.041), stdev = 0.058
  CI (99.9%): [2.935, 5.061] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.291 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.232 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.006 ms/op
Iteration   1: 3.038 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.546 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  7.039 ms/op
                 createUser·p0.9999: 14.277 ms/op
                 createUser·p1.00:   15.041 ms/op

Iteration   2: 3.023 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.864 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.412 ms/op
                 createUser·p0.95:   3.572 ms/op
                 createUser·p0.99:   4.100 ms/op
                 createUser·p0.999:  10.301 ms/op
                 createUser·p0.9999: 14.818 ms/op
                 createUser·p1.00:   15.122 ms/op

Iteration   3: 3.065 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.645 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.704 ms/op
                 createUser·p0.99:   4.178 ms/op
                 createUser·p0.999:  10.469 ms/op
                 createUser·p0.9999: 19.010 ms/op
                 createUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315560
  mean =      3.042 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 575 
    [ 1.250,  2.500) = 16258 
    [ 2.500,  3.750) = 285465 
    [ 3.750,  5.000) = 11867 
    [ 5.000,  6.250) = 666 
    [ 6.250,  7.500) = 292 
    [ 7.500,  8.750) = 84 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 61 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 103 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =     10.067 ms/op
     p(99.9900) =     17.542 ms/op
     p(99.9990) =     19.487 ms/op
     p(99.9999) =     19.661 ms/op
    p(100.0000) =     19.661 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.908 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.115 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.979 ±(99.9%) 0.005 ms/op
Iteration   1: 3.004 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.759 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  6.706 ms/op
                 existUser·p0.9999: 13.539 ms/op
                 existUser·p1.00:   13.779 ms/op

Iteration   2: 2.952 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.834 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  10.273 ms/op
                 existUser·p0.9999: 14.978 ms/op
                 existUser·p1.00:   15.221 ms/op

Iteration   3: 2.886 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.804 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.252 ms/op
                 existUser·p0.95:   3.375 ms/op
                 existUser·p0.99:   3.781 ms/op
                 existUser·p0.999:  6.808 ms/op
                 existUser·p0.9999: 15.824 ms/op
                 existUser·p1.00:   16.466 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325705
  mean =      2.947 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1429 
    [ 1.250,  2.500) = 28885 
    [ 2.500,  3.750) = 285816 
    [ 3.750,  5.000) = 8323 
    [ 5.000,  6.250) = 611 
    [ 6.250,  7.500) = 308 
    [ 7.500,  8.750) = 45 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 101 
    [12.500, 13.750) = 49 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.759 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.404 ms/op
     p(95.0000) =      3.604 ms/op
     p(99.0000) =      4.125 ms/op
     p(99.9000) =      7.612 ms/op
     p(99.9900) =     14.893 ms/op
     p(99.9990) =     16.232 ms/op
     p(99.9999) =     16.466 ms/op
    p(100.0000) =     16.466 ms/op


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
# Warmup Iteration   1: 4.240 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.175 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.110 ±(99.9%) 0.007 ms/op
Iteration   1: 3.122 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.798 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   3.953 ms/op
                 getUser·p0.99:   4.719 ms/op
                 getUser·p0.999:  7.409 ms/op
                 getUser·p0.9999: 15.856 ms/op
                 getUser·p1.00:   16.318 ms/op

Iteration   2: 3.085 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.786 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  7.225 ms/op
                 getUser·p0.9999: 17.453 ms/op
                 getUser·p1.00:   17.859 ms/op

Iteration   3: 3.087 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.321 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  7.307 ms/op
                 getUser·p0.9999: 20.731 ms/op
                 getUser·p1.00:   21.266 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309934
  mean =      3.098 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14839 
    [ 2.500,  5.000) = 293689 
    [ 5.000,  7.500) = 1153 
    [ 7.500, 10.000) = 61 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.321 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.854 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      7.307 ms/op
     p(99.9900) =     20.054 ms/op
     p(99.9990) =     21.132 ms/op
     p(99.9999) =     21.266 ms/op
    p(100.0000) =     21.266 ms/op


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
# Warmup Iteration   1: 5.404 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.201 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.956 ±(99.9%) 0.012 ms/op
Iteration   1: 4.062 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.360 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.849 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  14.046 ms/op
                 listUser·p0.9999: 21.279 ms/op
                 listUser·p1.00:   21.725 ms/op

Iteration   2: 4.043 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.272 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   7.102 ms/op
                 listUser·p0.999:  15.925 ms/op
                 listUser·p0.9999: 21.043 ms/op
                 listUser·p1.00:   21.496 ms/op

Iteration   3: 4.004 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.924 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   6.045 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  16.206 ms/op
                 listUser·p0.9999: 20.513 ms/op
                 listUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237729
  mean =      4.036 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3408 
    [ 2.500,  5.000) = 206589 
    [ 5.000,  7.500) = 26354 
    [ 7.500, 10.000) = 854 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 147 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.924 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      5.153 ms/op
     p(95.0000) =      5.931 ms/op
     p(99.0000) =      7.029 ms/op
     p(99.9000) =     15.860 ms/op
     p(99.9900) =     20.913 ms/op
     p(99.9990) =     21.590 ms/op
     p(99.9999) =     21.725 ms/op
    p(100.0000) =     21.725 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.554 ± 1.566  ops/ms
ClientGrpc.existUser                       thrpt       3  11.359 ± 4.118  ops/ms
ClientGrpc.getUser                         thrpt       3  10.464 ± 0.612  ops/ms
ClientGrpc.listUser                        thrpt       3   8.015 ± 1.845  ops/ms
ClientGrpc.createUser                       avgt       3   3.078 ± 0.380   ms/op
ClientGrpc.existUser                        avgt       3   2.938 ± 0.015   ms/op
ClientGrpc.getUser                          avgt       3   3.069 ± 0.816   ms/op
ClientGrpc.listUser                         avgt       3   3.998 ± 1.063   ms/op
ClientGrpc.createUser                     sample  315560   3.042 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.546           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.011           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.510           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.707           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.317           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.067           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.542           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.661           ms/op
ClientGrpc.existUser                      sample  325705   2.947 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.759           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.933           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.404           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.604           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.125           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.612           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.893           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.466           ms/op
ClientGrpc.getUser                        sample  309934   3.098 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.321           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.056           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.654           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.854           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.432           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.307           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.054           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.266           ms/op
ClientGrpc.listUser                       sample  237729   4.036 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.924           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.858           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.153           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.931           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.029           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.860           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.913           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.725           ms/op
