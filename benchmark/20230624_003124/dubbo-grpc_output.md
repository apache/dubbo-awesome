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
# Warmup Iteration   1: 4.355 ops/ms
# Warmup Iteration   2: 9.003 ops/ms
# Warmup Iteration   3: 10.157 ops/ms
Iteration   1: 10.493 ops/ms
Iteration   2: 10.551 ops/ms
Iteration   3: 10.530 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.525 ±(99.9%) 0.534 ops/ms [Average]
  (min, avg, max) = (10.493, 10.525, 10.551), stdev = 0.029
  CI (99.9%): [9.991, 11.058] (assumes normal distribution)


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
# Warmup Iteration   1: 8.175 ops/ms
# Warmup Iteration   2: 10.597 ops/ms
# Warmup Iteration   3: 11.046 ops/ms
Iteration   1: 11.042 ops/ms
Iteration   2: 10.820 ops/ms
Iteration   3: 11.038 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.967 ±(99.9%) 2.322 ops/ms [Average]
  (min, avg, max) = (10.820, 10.967, 11.042), stdev = 0.127
  CI (99.9%): [8.645, 13.289] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.478 ops/ms
# Warmup Iteration   2: 10.090 ops/ms
# Warmup Iteration   3: 10.509 ops/ms
Iteration   1: 10.670 ops/ms
Iteration   2: 10.623 ops/ms
Iteration   3: 10.579 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.624 ±(99.9%) 0.831 ops/ms [Average]
  (min, avg, max) = (10.579, 10.624, 10.670), stdev = 0.046
  CI (99.9%): [9.793, 11.455] (assumes normal distribution)


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
# Warmup Iteration   1: 7.367 ops/ms
# Warmup Iteration   2: 7.598 ops/ms
# Warmup Iteration   3: 8.171 ops/ms
Iteration   1: 7.936 ops/ms
Iteration   2: 8.159 ops/ms
Iteration   3: 8.111 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.069 ±(99.9%) 2.148 ops/ms [Average]
  (min, avg, max) = (7.936, 8.069, 8.159), stdev = 0.118
  CI (99.9%): [5.921, 10.216] (assumes normal distribution)


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
# Warmup Iteration   1: 4.206 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.133 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.077 ±(99.9%) 0.003 ms/op
Iteration   1: 3.026 ±(99.9%) 0.004 ms/op
Iteration   2: 2.985 ±(99.9%) 0.003 ms/op
Iteration   3: 3.028 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.013 ±(99.9%) 0.449 ms/op [Average]
  (min, avg, max) = (2.985, 3.013, 3.028), stdev = 0.025
  CI (99.9%): [2.564, 3.462] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.879 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.984 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.904 ±(99.9%) 0.004 ms/op
Iteration   1: 2.947 ±(99.9%) 0.003 ms/op
Iteration   2: 2.886 ±(99.9%) 0.003 ms/op
Iteration   3: 2.873 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.902 ±(99.9%) 0.723 ms/op [Average]
  (min, avg, max) = (2.873, 2.902, 2.947), stdev = 0.040
  CI (99.9%): [2.179, 3.625] (assumes normal distribution)


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
# Warmup Iteration   1: 4.018 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.130 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.003 ms/op
Iteration   1: 3.049 ±(99.9%) 0.005 ms/op
Iteration   2: 2.964 ±(99.9%) 0.002 ms/op
Iteration   3: 2.994 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.002 ±(99.9%) 0.786 ms/op [Average]
  (min, avg, max) = (2.964, 3.002, 3.049), stdev = 0.043
  CI (99.9%): [2.216, 3.789] (assumes normal distribution)


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
# Warmup Iteration   1: 5.013 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.069 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.906 ±(99.9%) 0.022 ms/op
Iteration   1: 3.922 ±(99.9%) 0.007 ms/op
Iteration   2: 3.894 ±(99.9%) 0.011 ms/op
Iteration   3: 3.879 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.898 ±(99.9%) 0.397 ms/op [Average]
  (min, avg, max) = (3.879, 3.898, 3.922), stdev = 0.022
  CI (99.9%): [3.501, 4.295] (assumes normal distribution)


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
# Warmup Iteration   1: 4.162 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.178 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.008 ms/op
Iteration   1: 3.005 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.593 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  6.955 ms/op
                 createUser·p0.9999: 19.202 ms/op
                 createUser·p1.00:   20.283 ms/op

Iteration   2: 2.973 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.726 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.412 ms/op
                 createUser·p0.95:   3.584 ms/op
                 createUser·p0.99:   4.125 ms/op
                 createUser·p0.999:  6.227 ms/op
                 createUser·p0.9999: 22.519 ms/op
                 createUser·p1.00:   23.134 ms/op

Iteration   3: 3.033 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.382 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.432 ms/op
                 createUser·p0.95:   3.674 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  14.139 ms/op
                 createUser·p0.9999: 30.063 ms/op
                 createUser·p1.00:   31.982 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319762
  mean =      3.003 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22218 
    [ 2.500,  5.000) = 296326 
    [ 5.000,  7.500) = 884 
    [ 7.500, 10.000) = 46 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.382 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.654 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      7.708 ms/op
     p(99.9900) =     29.591 ms/op
     p(99.9990) =     31.040 ms/op
     p(99.9999) =     31.982 ms/op
    p(100.0000) =     31.982 ms/op


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
# Warmup Iteration   1: 3.916 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.995 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.921 ±(99.9%) 0.006 ms/op
Iteration   1: 2.901 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.525 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   4.669 ms/op
                 existUser·p0.999:  7.448 ms/op
                 existUser·p0.9999: 11.813 ms/op
                 existUser·p1.00:   12.124 ms/op

Iteration   2: 2.877 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.618 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  5.825 ms/op
                 existUser·p0.9999: 13.954 ms/op
                 existUser·p1.00:   14.418 ms/op

Iteration   3: 2.929 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.542 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.833 ms/op
                 existUser·p0.999:  10.269 ms/op
                 existUser·p0.9999: 17.108 ms/op
                 existUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330822
  mean =      2.902 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47013 
    [ 2.500,  5.000) = 281951 
    [ 5.000,  7.500) = 1462 
    [ 7.500, 10.000) = 199 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.525 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      4.637 ms/op
     p(99.9000) =      8.308 ms/op
     p(99.9900) =     14.661 ms/op
     p(99.9990) =     17.400 ms/op
     p(99.9999) =     20.021 ms/op
    p(100.0000) =     20.021 ms/op


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
# Warmup Iteration   1: 4.074 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.063 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.980 ±(99.9%) 0.006 ms/op
Iteration   1: 2.997 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.592 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.404 ms/op
                 getUser·p0.95:   3.543 ms/op
                 getUser·p0.99:   4.141 ms/op
                 getUser·p0.999:  6.247 ms/op
                 getUser·p0.9999: 16.733 ms/op
                 getUser·p1.00:   19.857 ms/op

Iteration   2: 3.029 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.695 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  9.230 ms/op
                 getUser·p0.9999: 12.909 ms/op
                 getUser·p1.00:   15.024 ms/op

Iteration   3: 2.992 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.633 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  7.248 ms/op
                 getUser·p0.9999: 14.587 ms/op
                 getUser·p1.00:   14.959 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319346
  mean =      3.006 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1078 
    [ 1.250,  2.500) = 22589 
    [ 2.500,  3.750) = 283094 
    [ 3.750,  5.000) = 11119 
    [ 5.000,  6.250) = 802 
    [ 6.250,  7.500) = 287 
    [ 7.500,  8.750) = 127 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 55 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.592 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      7.902 ms/op
     p(99.9900) =     15.860 ms/op
     p(99.9990) =     19.288 ms/op
     p(99.9999) =     19.857 ms/op
    p(100.0000) =     19.857 ms/op


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
# Warmup Iteration   1: 5.005 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.067 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.928 ±(99.9%) 0.011 ms/op
Iteration   1: 3.909 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.198 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.817 ms/op
                 listUser·p0.95:   5.679 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  13.146 ms/op
                 listUser·p0.9999: 16.752 ms/op
                 listUser·p1.00:   17.236 ms/op

Iteration   2: 3.896 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.454 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.817 ms/op
                 listUser·p0.95:   5.251 ms/op
                 listUser·p0.99:   6.472 ms/op
                 listUser·p0.999:  16.447 ms/op
                 listUser·p0.9999: 23.571 ms/op
                 listUser·p1.00:   24.281 ms/op

Iteration   3: 3.906 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.122 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.743 ms/op
                 listUser·p0.95:   5.284 ms/op
                 listUser·p0.99:   6.537 ms/op
                 listUser·p0.999:  19.595 ms/op
                 listUser·p0.9999: 21.260 ms/op
                 listUser·p1.00:   23.658 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245929
  mean =      3.904 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3159 
    [ 2.500,  5.000) = 223926 
    [ 5.000,  7.500) = 17857 
    [ 7.500, 10.000) = 578 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 111 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.454 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      5.390 ms/op
     p(99.0000) =      6.586 ms/op
     p(99.9000) =     14.020 ms/op
     p(99.9900) =     22.446 ms/op
     p(99.9990) =     24.185 ms/op
     p(99.9999) =     24.281 ms/op
    p(100.0000) =     24.281 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.525 ± 0.534  ops/ms
ClientGrpc.existUser                       thrpt       3  10.967 ± 2.322  ops/ms
ClientGrpc.getUser                         thrpt       3  10.624 ± 0.831  ops/ms
ClientGrpc.listUser                        thrpt       3   8.069 ± 2.148  ops/ms
ClientGrpc.createUser                       avgt       3   3.013 ± 0.449   ms/op
ClientGrpc.existUser                        avgt       3   2.902 ± 0.723   ms/op
ClientGrpc.getUser                          avgt       3   3.002 ± 0.786   ms/op
ClientGrpc.listUser                         avgt       3   3.898 ± 0.397   ms/op
ClientGrpc.createUser                     sample  319762   3.003 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.382           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.986           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.461           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.654           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.317           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.708           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.591           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.982           ms/op
ClientGrpc.existUser                      sample  330822   2.902 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.525           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.900           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.424           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.670           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.637           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.308           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.661           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.021           ms/op
ClientGrpc.getUser                        sample  319346   3.006 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.592           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.998           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.490           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.678           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.375           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.902           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.860           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.857           ms/op
ClientGrpc.listUser                       sample  245929   3.904 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.454           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.764           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.792           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.390           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.586           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.020           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.446           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.281           ms/op
