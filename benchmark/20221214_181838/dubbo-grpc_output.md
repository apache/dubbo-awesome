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
# Warmup Iteration   1: 2.030 ops/ms
# Warmup Iteration   2: 5.608 ops/ms
# Warmup Iteration   3: 6.996 ops/ms
Iteration   1: 7.328 ops/ms
Iteration   2: 7.784 ops/ms
Iteration   3: 7.568 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.560 ±(99.9%) 4.161 ops/ms [Average]
  (min, avg, max) = (7.328, 7.560, 7.784), stdev = 0.228
  CI (99.9%): [3.399, 11.721] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.714 ops/ms
# Warmup Iteration   2: 7.302 ops/ms
# Warmup Iteration   3: 7.514 ops/ms
Iteration   1: 7.545 ops/ms
Iteration   2: 7.505 ops/ms
Iteration   3: 7.654 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.568 ±(99.9%) 1.413 ops/ms [Average]
  (min, avg, max) = (7.505, 7.568, 7.654), stdev = 0.077
  CI (99.9%): [6.155, 8.981] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.981 ops/ms
# Warmup Iteration   2: 6.739 ops/ms
# Warmup Iteration   3: 7.235 ops/ms
Iteration   1: 7.080 ops/ms
Iteration   2: 7.223 ops/ms
Iteration   3: 7.212 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.171 ±(99.9%) 1.453 ops/ms [Average]
  (min, avg, max) = (7.080, 7.171, 7.223), stdev = 0.080
  CI (99.9%): [5.718, 8.625] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 4.125 ops/ms
# Warmup Iteration   2: 5.357 ops/ms
# Warmup Iteration   3: 5.778 ops/ms
Iteration   1: 5.914 ops/ms
Iteration   2: 5.603 ops/ms
Iteration   3: 5.730 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.749 ±(99.9%) 2.855 ops/ms [Average]
  (min, avg, max) = (5.603, 5.749, 5.914), stdev = 0.156
  CI (99.9%): [2.894, 8.604] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.706 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.760 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.470 ±(99.9%) 0.014 ms/op
Iteration   1: 4.521 ±(99.9%) 0.005 ms/op
Iteration   2: 4.280 ±(99.9%) 0.005 ms/op
Iteration   3: 4.378 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.393 ±(99.9%) 2.209 ms/op [Average]
  (min, avg, max) = (4.280, 4.393, 4.521), stdev = 0.121
  CI (99.9%): [2.184, 6.601] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.040 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.347 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.320 ±(99.9%) 0.005 ms/op
Iteration   1: 4.037 ±(99.9%) 0.004 ms/op
Iteration   2: 4.251 ±(99.9%) 0.003 ms/op
Iteration   3: 4.128 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.139 ±(99.9%) 1.962 ms/op [Average]
  (min, avg, max) = (4.037, 4.139, 4.251), stdev = 0.108
  CI (99.9%): [2.177, 6.100] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.549 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.594 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.322 ±(99.9%) 0.005 ms/op
Iteration   1: 4.383 ±(99.9%) 0.003 ms/op
Iteration   2: 4.217 ±(99.9%) 0.004 ms/op
Iteration   3: 4.345 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.315 ±(99.9%) 1.582 ms/op [Average]
  (min, avg, max) = (4.217, 4.315, 4.383), stdev = 0.087
  CI (99.9%): [2.733, 5.897] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.957 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 5.845 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.499 ±(99.9%) 0.015 ms/op
Iteration   1: 5.448 ±(99.9%) 0.016 ms/op
Iteration   2: 5.379 ±(99.9%) 0.014 ms/op
Iteration   3: 5.322 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.383 ±(99.9%) 1.145 ms/op [Average]
  (min, avg, max) = (5.322, 5.383, 5.448), stdev = 0.063
  CI (99.9%): [4.238, 6.528] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.591 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.696 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.355 ±(99.9%) 0.013 ms/op
Iteration   1: 4.298 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.094 ms/op
                 createUser·p0.50:   4.186 ms/op
                 createUser·p0.90:   5.538 ms/op
                 createUser·p0.95:   6.062 ms/op
                 createUser·p0.99:   7.955 ms/op
                 createUser·p0.999:  13.673 ms/op
                 createUser·p0.9999: 18.776 ms/op
                 createUser·p1.00:   19.235 ms/op

Iteration   2: 4.511 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.439 ms/op
                 createUser·p0.50:   4.375 ms/op
                 createUser·p0.90:   5.784 ms/op
                 createUser·p0.95:   6.357 ms/op
                 createUser·p0.99:   8.569 ms/op
                 createUser·p0.999:  13.681 ms/op
                 createUser·p0.9999: 17.564 ms/op
                 createUser·p1.00:   21.332 ms/op

Iteration   3: 4.455 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.965 ms/op
                 createUser·p0.50:   4.325 ms/op
                 createUser·p0.90:   5.784 ms/op
                 createUser·p0.95:   6.283 ms/op
                 createUser·p0.99:   7.701 ms/op
                 createUser·p0.999:  14.074 ms/op
                 createUser·p0.9999: 20.507 ms/op
                 createUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 217281
  mean =      4.420 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5931 
    [ 2.500,  5.000) = 157163 
    [ 5.000,  7.500) = 51055 
    [ 7.500, 10.000) = 2370 
    [10.000, 12.500) = 443 
    [12.500, 15.000) = 148 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.439 ms/op
     p(50.0000) =      4.293 ms/op
     p(90.0000) =      5.710 ms/op
     p(95.0000) =      6.234 ms/op
     p(99.0000) =      7.995 ms/op
     p(99.9000) =     13.807 ms/op
     p(99.9900) =     19.038 ms/op
     p(99.9990) =     21.332 ms/op
     p(99.9999) =     21.496 ms/op
    p(100.0000) =     21.496 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.999 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.423 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.049 ±(99.9%) 0.013 ms/op
Iteration   1: 4.107 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.968 ms/op
                 existUser·p0.50:   3.985 ms/op
                 existUser·p0.90:   5.317 ms/op
                 existUser·p0.95:   5.841 ms/op
                 existUser·p0.99:   7.736 ms/op
                 existUser·p0.999:  12.585 ms/op
                 existUser·p0.9999: 27.139 ms/op
                 existUser·p1.00:   27.427 ms/op

Iteration   2: 3.985 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.053 ms/op
                 existUser·p0.50:   3.899 ms/op
                 existUser·p0.90:   5.136 ms/op
                 existUser·p0.95:   5.620 ms/op
                 existUser·p0.99:   7.348 ms/op
                 existUser·p0.999:  11.578 ms/op
                 existUser·p0.9999: 19.267 ms/op
                 existUser·p1.00:   19.694 ms/op

Iteration   3: 4.093 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.885 ms/op
                 existUser·p0.50:   3.981 ms/op
                 existUser·p0.90:   5.325 ms/op
                 existUser·p0.95:   5.775 ms/op
                 existUser·p0.99:   7.234 ms/op
                 existUser·p0.999:  10.860 ms/op
                 existUser·p0.9999: 25.203 ms/op
                 existUser·p1.00:   28.574 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 236403
  mean =      4.061 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13081 
    [ 2.500,  5.000) = 188662 
    [ 5.000,  7.500) = 32388 
    [ 7.500, 10.000) = 1724 
    [10.000, 12.500) = 365 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.885 ms/op
     p(50.0000) =      3.953 ms/op
     p(90.0000) =      5.259 ms/op
     p(95.0000) =      5.751 ms/op
     p(99.0000) =      7.447 ms/op
     p(99.9000) =     12.108 ms/op
     p(99.9900) =     25.145 ms/op
     p(99.9990) =     28.440 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.079 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 4.571 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.517 ±(99.9%) 0.015 ms/op
Iteration   1: 4.416 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.182 ms/op
                 getUser·p0.50:   4.260 ms/op
                 getUser·p0.90:   5.612 ms/op
                 getUser·p0.95:   6.201 ms/op
                 getUser·p0.99:   8.421 ms/op
                 getUser·p0.999:  14.667 ms/op
                 getUser·p0.9999: 16.299 ms/op
                 getUser·p1.00:   16.777 ms/op

Iteration   2: 4.472 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.096 ms/op
                 getUser·p0.50:   4.334 ms/op
                 getUser·p0.90:   5.734 ms/op
                 getUser·p0.95:   6.242 ms/op
                 getUser·p0.99:   8.151 ms/op
                 getUser·p0.999:  14.222 ms/op
                 getUser·p0.9999: 18.743 ms/op
                 getUser·p1.00:   20.972 ms/op

Iteration   3: 4.372 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.221 ms/op
                 getUser·p0.50:   4.235 ms/op
                 getUser·p0.90:   5.587 ms/op
                 getUser·p0.95:   6.103 ms/op
                 getUser·p0.99:   8.151 ms/op
                 getUser·p0.999:  11.467 ms/op
                 getUser·p0.9999: 22.381 ms/op
                 getUser·p1.00:   23.003 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 216976
  mean =      4.420 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4076 
    [ 2.500,  5.000) = 161979 
    [ 5.000,  7.500) = 47518 
    [ 7.500, 10.000) = 2761 
    [10.000, 12.500) = 363 
    [12.500, 15.000) = 142 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.096 ms/op
     p(50.0000) =      4.276 ms/op
     p(90.0000) =      5.644 ms/op
     p(95.0000) =      6.185 ms/op
     p(99.0000) =      8.249 ms/op
     p(99.9000) =     13.452 ms/op
     p(99.9900) =     19.972 ms/op
     p(99.9990) =     22.894 ms/op
     p(99.9999) =     23.003 ms/op
    p(100.0000) =     23.003 ms/op


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
# Warmup Iteration   1: 8.616 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 5.992 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.701 ±(99.9%) 0.026 ms/op
Iteration   1: 5.646 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.642 ms/op
                 listUser·p0.50:   5.267 ms/op
                 listUser·p0.90:   7.766 ms/op
                 listUser·p0.95:   8.749 ms/op
                 listUser·p0.99:   11.059 ms/op
                 listUser·p0.999:  17.072 ms/op
                 listUser·p0.9999: 23.637 ms/op
                 listUser·p1.00:   23.855 ms/op

Iteration   2: 5.628 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.608 ms/op
                 listUser·p0.50:   5.276 ms/op
                 listUser·p0.90:   7.586 ms/op
                 listUser·p0.95:   8.454 ms/op
                 listUser·p0.99:   11.043 ms/op
                 listUser·p0.999:  17.477 ms/op
                 listUser·p0.9999: 24.717 ms/op
                 listUser·p1.00:   25.068 ms/op

Iteration   3: 5.481 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.362 ms/op
                 listUser·p0.50:   5.087 ms/op
                 listUser·p0.90:   7.504 ms/op
                 listUser·p0.95:   8.602 ms/op
                 listUser·p0.99:   11.469 ms/op
                 listUser·p0.999:  20.709 ms/op
                 listUser·p0.9999: 23.790 ms/op
                 listUser·p1.00:   24.543 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 171812
  mean =      5.584 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 212 
    [ 2.500,  5.000) = 71739 
    [ 5.000,  7.500) = 81199 
    [ 7.500, 10.000) = 15241 
    [10.000, 12.500) = 2459 
    [12.500, 15.000) = 423 
    [15.000, 17.500) = 327 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.362 ms/op
     p(50.0000) =      5.210 ms/op
     p(90.0000) =      7.619 ms/op
     p(95.0000) =      8.602 ms/op
     p(99.0000) =     11.207 ms/op
     p(99.9000) =     19.306 ms/op
     p(99.9900) =     24.046 ms/op
     p(99.9990) =     24.973 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.560 ± 4.161  ops/ms
ClientGrpc.existUser                       thrpt       3   7.568 ± 1.413  ops/ms
ClientGrpc.getUser                         thrpt       3   7.171 ± 1.453  ops/ms
ClientGrpc.listUser                        thrpt       3   5.749 ± 2.855  ops/ms
ClientGrpc.createUser                       avgt       3   4.393 ± 2.209   ms/op
ClientGrpc.existUser                        avgt       3   4.139 ± 1.962   ms/op
ClientGrpc.getUser                          avgt       3   4.315 ± 1.582   ms/op
ClientGrpc.listUser                         avgt       3   5.383 ± 1.145   ms/op
ClientGrpc.createUser                     sample  217281   4.420 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.439           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.293           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.710           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.234           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.995           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.807           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.038           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.496           ms/op
ClientGrpc.existUser                      sample  236403   4.061 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.885           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.953           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.259           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.751           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.447           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.108           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.145           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.574           ms/op
ClientGrpc.getUser                        sample  216976   4.420 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.096           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.276           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.644           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.185           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.249           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.452           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.972           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.003           ms/op
ClientGrpc.listUser                       sample  171812   5.584 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.362           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.210           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.619           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.602           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.207           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.306           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.046           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.068           ms/op
