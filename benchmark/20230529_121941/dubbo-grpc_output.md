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
# Warmup Iteration   1: 1.977 ops/ms
# Warmup Iteration   2: 4.361 ops/ms
# Warmup Iteration   3: 6.251 ops/ms
Iteration   1: 6.476 ops/ms
Iteration   2: 6.628 ops/ms
Iteration   3: 6.675 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.593 ±(99.9%) 1.897 ops/ms [Average]
  (min, avg, max) = (6.476, 6.593, 6.675), stdev = 0.104
  CI (99.9%): [4.696, 8.490] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.021 ops/ms
# Warmup Iteration   2: 6.561 ops/ms
# Warmup Iteration   3: 6.878 ops/ms
Iteration   1: 7.236 ops/ms
Iteration   2: 7.186 ops/ms
Iteration   3: 7.454 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.292 ±(99.9%) 2.606 ops/ms [Average]
  (min, avg, max) = (7.186, 7.292, 7.454), stdev = 0.143
  CI (99.9%): [4.686, 9.898] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.440 ops/ms
# Warmup Iteration   2: 6.177 ops/ms
# Warmup Iteration   3: 6.589 ops/ms
Iteration   1: 6.469 ops/ms
Iteration   2: 6.793 ops/ms
Iteration   3: 6.858 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.707 ±(99.9%) 3.798 ops/ms [Average]
  (min, avg, max) = (6.469, 6.707, 6.858), stdev = 0.208
  CI (99.9%): [2.909, 10.504] (assumes normal distribution)


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
# Warmup Iteration   1: 3.343 ops/ms
# Warmup Iteration   2: 4.596 ops/ms
# Warmup Iteration   3: 5.093 ops/ms
Iteration   1: 5.089 ops/ms
Iteration   2: 4.980 ops/ms
Iteration   3: 4.937 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.002 ±(99.9%) 1.427 ops/ms [Average]
  (min, avg, max) = (4.937, 5.002, 5.089), stdev = 0.078
  CI (99.9%): [3.575, 6.429] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 8.121 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 5.502 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 5.035 ±(99.9%) 0.006 ms/op
Iteration   1: 4.862 ±(99.9%) 0.007 ms/op
Iteration   2: 4.997 ±(99.9%) 0.005 ms/op
Iteration   3: 5.128 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.996 ±(99.9%) 2.432 ms/op [Average]
  (min, avg, max) = (4.862, 4.996, 5.128), stdev = 0.133
  CI (99.9%): [2.563, 7.428] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 7.096 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 5.274 ±(99.9%) 0.057 ms/op
# Warmup Iteration   3: 4.766 ±(99.9%) 0.005 ms/op
Iteration   1: 4.737 ±(99.9%) 0.005 ms/op
Iteration   2: 4.708 ±(99.9%) 0.004 ms/op
Iteration   3: 4.716 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.720 ±(99.9%) 0.269 ms/op [Average]
  (min, avg, max) = (4.708, 4.720, 4.737), stdev = 0.015
  CI (99.9%): [4.451, 4.990] (assumes normal distribution)


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
# Warmup Iteration   1: 7.684 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 5.318 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.867 ±(99.9%) 0.028 ms/op
Iteration   1: 4.831 ±(99.9%) 0.006 ms/op
Iteration   2: 4.789 ±(99.9%) 0.004 ms/op
Iteration   3: 4.652 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.757 ±(99.9%) 1.704 ms/op [Average]
  (min, avg, max) = (4.652, 4.757, 4.831), stdev = 0.093
  CI (99.9%): [3.053, 6.462] (assumes normal distribution)


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
# Warmup Iteration   1: 10.443 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 6.747 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 6.290 ±(99.9%) 0.021 ms/op
Iteration   1: 6.340 ±(99.9%) 0.015 ms/op
Iteration   2: 6.383 ±(99.9%) 0.020 ms/op
Iteration   3: 6.104 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.276 ±(99.9%) 2.734 ms/op [Average]
  (min, avg, max) = (6.104, 6.276, 6.383), stdev = 0.150
  CI (99.9%): [3.541, 9.010] (assumes normal distribution)


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
# Warmup Iteration   1: 7.997 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 5.495 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.094 ±(99.9%) 0.019 ms/op
Iteration   1: 4.906 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   0.687 ms/op
                 createUser·p0.50:   4.710 ms/op
                 createUser·p0.90:   6.341 ms/op
                 createUser·p0.95:   7.143 ms/op
                 createUser·p0.99:   9.437 ms/op
                 createUser·p0.999:  15.250 ms/op
                 createUser·p0.9999: 22.512 ms/op
                 createUser·p1.00:   27.066 ms/op

Iteration   2: 4.977 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.329 ms/op
                 createUser·p0.50:   4.760 ms/op
                 createUser·p0.90:   6.611 ms/op
                 createUser·p0.95:   7.496 ms/op
                 createUser·p0.99:   9.601 ms/op
                 createUser·p0.999:  24.034 ms/op
                 createUser·p0.9999: 32.038 ms/op
                 createUser·p1.00:   32.637 ms/op

Iteration   3: 4.881 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.233 ms/op
                 createUser·p0.50:   4.661 ms/op
                 createUser·p0.90:   6.218 ms/op
                 createUser·p0.95:   7.176 ms/op
                 createUser·p0.99:   9.306 ms/op
                 createUser·p0.999:  18.610 ms/op
                 createUser·p0.9999: 35.216 ms/op
                 createUser·p1.00:   35.848 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 194999
  mean =      4.921 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4106 
    [ 2.500,  5.000) = 116912 
    [ 5.000,  7.500) = 65691 
    [ 7.500, 10.000) = 6897 
    [10.000, 12.500) = 908 
    [12.500, 15.000) = 251 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.687 ms/op
     p(50.0000) =      4.710 ms/op
     p(90.0000) =      6.398 ms/op
     p(95.0000) =      7.283 ms/op
     p(99.0000) =      9.437 ms/op
     p(99.9000) =     18.088 ms/op
     p(99.9900) =     31.883 ms/op
     p(99.9990) =     35.599 ms/op
     p(99.9999) =     35.848 ms/op
    p(100.0000) =     35.848 ms/op


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
# Warmup Iteration   1: 7.206 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 4.996 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.597 ±(99.9%) 0.018 ms/op
Iteration   1: 4.510 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.071 ms/op
                 existUser·p0.50:   4.309 ms/op
                 existUser·p0.90:   5.947 ms/op
                 existUser·p0.95:   6.791 ms/op
                 existUser·p0.99:   8.983 ms/op
                 existUser·p0.999:  14.027 ms/op
                 existUser·p0.9999: 18.049 ms/op
                 existUser·p1.00:   18.612 ms/op

Iteration   2: 4.517 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.151 ms/op
                 existUser·p0.50:   4.342 ms/op
                 existUser·p0.90:   5.751 ms/op
                 existUser·p0.95:   6.603 ms/op
                 existUser·p0.99:   8.520 ms/op
                 existUser·p0.999:  12.602 ms/op
                 existUser·p0.9999: 18.970 ms/op
                 existUser·p1.00:   19.366 ms/op

Iteration   3: 4.732 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.163 ms/op
                 existUser·p0.50:   4.514 ms/op
                 existUser·p0.90:   6.062 ms/op
                 existUser·p0.95:   6.881 ms/op
                 existUser·p0.99:   8.995 ms/op
                 existUser·p0.999:  13.619 ms/op
                 existUser·p0.9999: 25.477 ms/op
                 existUser·p1.00:   26.706 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 209297
  mean =      4.584 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5227 
    [ 2.500,  5.000) = 150818 
    [ 5.000,  7.500) = 47467 
    [ 7.500, 10.000) = 4743 
    [10.000, 12.500) = 670 
    [12.500, 15.000) = 266 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.071 ms/op
     p(50.0000) =      4.383 ms/op
     p(90.0000) =      5.939 ms/op
     p(95.0000) =      6.758 ms/op
     p(99.0000) =      8.815 ms/op
     p(99.9000) =     13.451 ms/op
     p(99.9900) =     22.285 ms/op
     p(99.9990) =     26.418 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


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
# Warmup Iteration   1: 7.941 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 5.148 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.984 ±(99.9%) 0.020 ms/op
Iteration   1: 4.816 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.225 ms/op
                 getUser·p0.50:   4.596 ms/op
                 getUser·p0.90:   6.136 ms/op
                 getUser·p0.95:   7.027 ms/op
                 getUser·p0.99:   9.699 ms/op
                 getUser·p0.999:  13.566 ms/op
                 getUser·p0.9999: 26.762 ms/op
                 getUser·p1.00:   27.001 ms/op

Iteration   2: 4.828 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.926 ms/op
                 getUser·p0.50:   4.604 ms/op
                 getUser·p0.90:   6.193 ms/op
                 getUser·p0.95:   7.143 ms/op
                 getUser·p0.99:   9.650 ms/op
                 getUser·p0.999:  15.270 ms/op
                 getUser·p0.9999: 20.972 ms/op
                 getUser·p1.00:   21.103 ms/op

Iteration   3: 4.721 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.077 ms/op
                 getUser·p0.50:   4.538 ms/op
                 getUser·p0.90:   5.997 ms/op
                 getUser·p0.95:   6.783 ms/op
                 getUser·p0.99:   9.110 ms/op
                 getUser·p0.999:  16.398 ms/op
                 getUser·p0.9999: 23.857 ms/op
                 getUser·p1.00:   26.444 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 200586
  mean =      4.788 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3539 
    [ 2.500,  5.000) = 134005 
    [ 5.000,  7.500) = 56087 
    [ 7.500, 10.000) = 5385 
    [10.000, 12.500) = 1135 
    [12.500, 15.000) = 243 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.926 ms/op
     p(50.0000) =      4.579 ms/op
     p(90.0000) =      6.111 ms/op
     p(95.0000) =      6.980 ms/op
     p(99.0000) =      9.486 ms/op
     p(99.9000) =     14.808 ms/op
     p(99.9900) =     23.977 ms/op
     p(99.9990) =     26.968 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


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
# Warmup Iteration   1: 9.785 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 6.778 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 6.228 ±(99.9%) 0.028 ms/op
Iteration   1: 6.268 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.591 ms/op
                 listUser·p0.50:   5.792 ms/op
                 listUser·p0.90:   8.667 ms/op
                 listUser·p0.95:   9.863 ms/op
                 listUser·p0.99:   12.829 ms/op
                 listUser·p0.999:  21.855 ms/op
                 listUser·p0.9999: 26.640 ms/op
                 listUser·p1.00:   26.837 ms/op

Iteration   2: 6.285 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.927 ms/op
                 listUser·p0.50:   5.833 ms/op
                 listUser·p0.90:   8.552 ms/op
                 listUser·p0.95:   9.732 ms/op
                 listUser·p0.99:   12.354 ms/op
                 listUser·p0.999:  21.143 ms/op
                 listUser·p0.9999: 29.843 ms/op
                 listUser·p1.00:   33.554 ms/op

Iteration   3: 6.303 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.663 ms/op
                 listUser·p0.50:   5.825 ms/op
                 listUser·p0.90:   8.651 ms/op
                 listUser·p0.95:   9.732 ms/op
                 listUser·p0.99:   12.976 ms/op
                 listUser·p0.999:  22.487 ms/op
                 listUser·p0.9999: 33.882 ms/op
                 listUser·p1.00:   36.438 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 152643
  mean =      6.285 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 79 
    [ 2.500,  5.000) = 32762 
    [ 5.000,  7.500) = 90899 
    [ 7.500, 10.000) = 22186 
    [10.000, 12.500) = 4967 
    [12.500, 15.000) = 1143 
    [15.000, 17.500) = 271 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 123 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.591 ms/op
     p(50.0000) =      5.816 ms/op
     p(90.0000) =      8.618 ms/op
     p(95.0000) =      9.781 ms/op
     p(99.0000) =     12.730 ms/op
     p(99.9000) =     21.791 ms/op
     p(99.9900) =     32.709 ms/op
     p(99.9990) =     36.404 ms/op
     p(99.9999) =     36.438 ms/op
    p(100.0000) =     36.438 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.593 ± 1.897  ops/ms
ClientGrpc.existUser                       thrpt       3   7.292 ± 2.606  ops/ms
ClientGrpc.getUser                         thrpt       3   6.707 ± 3.798  ops/ms
ClientGrpc.listUser                        thrpt       3   5.002 ± 1.427  ops/ms
ClientGrpc.createUser                       avgt       3   4.996 ± 2.432   ms/op
ClientGrpc.existUser                        avgt       3   4.720 ± 0.269   ms/op
ClientGrpc.getUser                          avgt       3   4.757 ± 1.704   ms/op
ClientGrpc.listUser                         avgt       3   6.276 ± 2.734   ms/op
ClientGrpc.createUser                     sample  194999   4.921 ± 0.011   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.687           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.710           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.398           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           7.283           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           9.437           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          18.088           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          31.883           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          35.848           ms/op
ClientGrpc.existUser                      sample  209297   4.584 ± 0.009   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.071           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.383           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.939           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.758           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.815           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.451           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.285           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.706           ms/op
ClientGrpc.getUser                        sample  200586   4.788 ± 0.010   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.926           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.579           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.111           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.980           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           9.486           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.808           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.977           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.001           ms/op
ClientGrpc.listUser                       sample  152643   6.285 ± 0.016   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.591           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.816           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.618           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.781           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.730           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          21.791           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.709           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          36.438           ms/op
