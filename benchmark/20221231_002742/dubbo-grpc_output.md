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
# Warmup Iteration   1: 2.384 ops/ms
# Warmup Iteration   2: 5.485 ops/ms
# Warmup Iteration   3: 7.004 ops/ms
Iteration   1: 7.331 ops/ms
Iteration   2: 7.120 ops/ms
Iteration   3: 7.345 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.265 ±(99.9%) 2.296 ops/ms [Average]
  (min, avg, max) = (7.120, 7.265, 7.345), stdev = 0.126
  CI (99.9%): [4.969, 9.561] (assumes normal distribution)


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
# Warmup Iteration   1: 4.832 ops/ms
# Warmup Iteration   2: 7.259 ops/ms
# Warmup Iteration   3: 7.473 ops/ms
Iteration   1: 7.652 ops/ms
Iteration   2: 7.622 ops/ms
Iteration   3: 7.440 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.571 ±(99.9%) 2.087 ops/ms [Average]
  (min, avg, max) = (7.440, 7.571, 7.652), stdev = 0.114
  CI (99.9%): [5.484, 9.658] (assumes normal distribution)


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
# Warmup Iteration   1: 4.281 ops/ms
# Warmup Iteration   2: 6.721 ops/ms
# Warmup Iteration   3: 7.080 ops/ms
Iteration   1: 7.245 ops/ms
Iteration   2: 7.250 ops/ms
Iteration   3: 7.461 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.318 ±(99.9%) 2.249 ops/ms [Average]
  (min, avg, max) = (7.245, 7.318, 7.461), stdev = 0.123
  CI (99.9%): [5.069, 9.567] (assumes normal distribution)


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
# Warmup Iteration   1: 3.652 ops/ms
# Warmup Iteration   2: 5.162 ops/ms
# Warmup Iteration   3: 5.701 ops/ms
Iteration   1: 5.566 ops/ms
Iteration   2: 5.541 ops/ms
Iteration   3: 5.767 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.625 ±(99.9%) 2.265 ops/ms [Average]
  (min, avg, max) = (5.541, 5.625, 5.767), stdev = 0.124
  CI (99.9%): [3.360, 7.890] (assumes normal distribution)


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
# Warmup Iteration   1: 6.324 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.420 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.403 ±(99.9%) 0.010 ms/op
Iteration   1: 4.256 ±(99.9%) 0.004 ms/op
Iteration   2: 4.347 ±(99.9%) 0.002 ms/op
Iteration   3: 4.240 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.281 ±(99.9%) 1.052 ms/op [Average]
  (min, avg, max) = (4.240, 4.281, 4.347), stdev = 0.058
  CI (99.9%): [3.229, 5.333] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.866 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.347 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.995 ±(99.9%) 0.005 ms/op
Iteration   1: 4.143 ±(99.9%) 0.003 ms/op
Iteration   2: 4.052 ±(99.9%) 0.004 ms/op
Iteration   3: 4.022 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.072 ±(99.9%) 1.148 ms/op [Average]
  (min, avg, max) = (4.022, 4.072, 4.143), stdev = 0.063
  CI (99.9%): [2.924, 5.220] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.897 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.730 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.502 ±(99.9%) 0.004 ms/op
Iteration   1: 4.468 ±(99.9%) 0.003 ms/op
Iteration   2: 4.532 ±(99.9%) 0.003 ms/op
Iteration   3: 4.429 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.476 ±(99.9%) 0.955 ms/op [Average]
  (min, avg, max) = (4.429, 4.476, 4.532), stdev = 0.052
  CI (99.9%): [3.521, 5.431] (assumes normal distribution)


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
# Warmup Iteration   1: 7.665 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 6.128 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.602 ±(99.9%) 0.013 ms/op
Iteration   1: 5.380 ±(99.9%) 0.012 ms/op
Iteration   2: 5.530 ±(99.9%) 0.009 ms/op
Iteration   3: 5.395 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.435 ±(99.9%) 1.505 ms/op [Average]
  (min, avg, max) = (5.380, 5.435, 5.530), stdev = 0.082
  CI (99.9%): [3.930, 6.940] (assumes normal distribution)


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
# Warmup Iteration   1: 6.845 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 4.688 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.612 ±(99.9%) 0.015 ms/op
Iteration   1: 4.553 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.167 ms/op
                 createUser·p0.50:   4.432 ms/op
                 createUser·p0.90:   5.865 ms/op
                 createUser·p0.95:   6.406 ms/op
                 createUser·p0.99:   8.389 ms/op
                 createUser·p0.999:  12.251 ms/op
                 createUser·p0.9999: 20.364 ms/op
                 createUser·p1.00:   21.365 ms/op

Iteration   2: 4.405 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.143 ms/op
                 createUser·p0.50:   4.268 ms/op
                 createUser·p0.90:   5.628 ms/op
                 createUser·p0.95:   6.103 ms/op
                 createUser·p0.99:   7.922 ms/op
                 createUser·p0.999:  12.406 ms/op
                 createUser·p0.9999: 21.127 ms/op
                 createUser·p1.00:   21.594 ms/op

Iteration   3: 4.366 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.151 ms/op
                 createUser·p0.50:   4.235 ms/op
                 createUser·p0.90:   5.644 ms/op
                 createUser·p0.95:   6.046 ms/op
                 createUser·p0.99:   7.668 ms/op
                 createUser·p0.999:  14.147 ms/op
                 createUser·p0.9999: 29.677 ms/op
                 createUser·p1.00:   29.786 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 216188
  mean =      4.440 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4329 
    [ 2.500,  5.000) = 157136 
    [ 5.000,  7.500) = 51446 
    [ 7.500, 10.000) = 2633 
    [10.000, 12.500) = 362 
    [12.500, 15.000) = 161 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.143 ms/op
     p(50.0000) =      4.309 ms/op
     p(90.0000) =      5.710 ms/op
     p(95.0000) =      6.185 ms/op
     p(99.0000) =      8.045 ms/op
     p(99.9000) =     13.461 ms/op
     p(99.9900) =     28.606 ms/op
     p(99.9990) =     29.786 ms/op
     p(99.9999) =     29.786 ms/op
    p(100.0000) =     29.786 ms/op


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
# Warmup Iteration   1: 6.053 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.397 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.374 ±(99.9%) 0.012 ms/op
Iteration   1: 4.046 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.053 ms/op
                 existUser·p0.50:   3.949 ms/op
                 existUser·p0.90:   5.358 ms/op
                 existUser·p0.95:   5.825 ms/op
                 existUser·p0.99:   7.692 ms/op
                 existUser·p0.999:  12.842 ms/op
                 existUser·p0.9999: 17.408 ms/op
                 existUser·p1.00:   17.924 ms/op

Iteration   2: 4.084 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.857 ms/op
                 existUser·p0.50:   3.990 ms/op
                 existUser·p0.90:   5.226 ms/op
                 existUser·p0.95:   5.685 ms/op
                 existUser·p0.99:   7.102 ms/op
                 existUser·p0.999:  10.568 ms/op
                 existUser·p0.9999: 19.830 ms/op
                 existUser·p1.00:   20.546 ms/op

Iteration   3: 4.060 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.057 ms/op
                 existUser·p0.50:   3.965 ms/op
                 existUser·p0.90:   5.202 ms/op
                 existUser·p0.95:   5.661 ms/op
                 existUser·p0.99:   7.725 ms/op
                 existUser·p0.999:  14.467 ms/op
                 existUser·p0.9999: 21.279 ms/op
                 existUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 236254
  mean =      4.063 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13498 
    [ 2.500,  5.000) = 188114 
    [ 5.000,  7.500) = 32289 
    [ 7.500, 10.000) = 1865 
    [10.000, 12.500) = 216 
    [12.500, 15.000) = 152 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.857 ms/op
     p(50.0000) =      3.969 ms/op
     p(90.0000) =      5.259 ms/op
     p(95.0000) =      5.734 ms/op
     p(99.0000) =      7.496 ms/op
     p(99.9000) =     13.009 ms/op
     p(99.9900) =     19.882 ms/op
     p(99.9990) =     21.418 ms/op
     p(99.9999) =     21.529 ms/op
    p(100.0000) =     21.529 ms/op


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
# Warmup Iteration   1: 6.168 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.632 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.555 ±(99.9%) 0.015 ms/op
Iteration   1: 4.344 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.149 ms/op
                 getUser·p0.50:   4.235 ms/op
                 getUser·p0.90:   5.472 ms/op
                 getUser·p0.95:   5.964 ms/op
                 getUser·p0.99:   7.739 ms/op
                 getUser·p0.999:  11.121 ms/op
                 getUser·p0.9999: 17.528 ms/op
                 getUser·p1.00:   18.711 ms/op

Iteration   2: 4.450 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.104 ms/op
                 getUser·p0.50:   4.334 ms/op
                 getUser·p0.90:   5.718 ms/op
                 getUser·p0.95:   6.160 ms/op
                 getUser·p0.99:   7.725 ms/op
                 getUser·p0.999:  12.457 ms/op
                 getUser·p0.9999: 17.257 ms/op
                 getUser·p1.00:   18.153 ms/op

Iteration   3: 4.497 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.225 ms/op
                 getUser·p0.50:   4.366 ms/op
                 getUser·p0.90:   5.808 ms/op
                 getUser·p0.95:   6.275 ms/op
                 getUser·p0.99:   8.265 ms/op
                 getUser·p0.999:  12.485 ms/op
                 getUser·p0.9999: 22.770 ms/op
                 getUser·p1.00:   23.593 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 216591
  mean =      4.429 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4653 
    [ 2.500,  5.000) = 159402 
    [ 5.000,  7.500) = 49635 
    [ 7.500, 10.000) = 2341 
    [10.000, 12.500) = 369 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      4.309 ms/op
     p(90.0000) =      5.677 ms/op
     p(95.0000) =      6.144 ms/op
     p(99.0000) =      7.922 ms/op
     p(99.9000) =     12.301 ms/op
     p(99.9900) =     19.508 ms/op
     p(99.9990) =     23.407 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


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
# Warmup Iteration   1: 6.947 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 6.137 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.591 ±(99.9%) 0.022 ms/op
Iteration   1: 5.459 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.458 ms/op
                 listUser·p0.50:   5.177 ms/op
                 listUser·p0.90:   7.258 ms/op
                 listUser·p0.95:   8.176 ms/op
                 listUser·p0.99:   10.244 ms/op
                 listUser·p0.999:  21.418 ms/op
                 listUser·p0.9999: 27.479 ms/op
                 listUser·p1.00:   28.672 ms/op

Iteration   2: 5.434 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   0.988 ms/op
                 listUser·p0.50:   5.161 ms/op
                 listUser·p0.90:   7.184 ms/op
                 listUser·p0.95:   8.045 ms/op
                 listUser·p0.99:   10.256 ms/op
                 listUser·p0.999:  21.538 ms/op
                 listUser·p0.9999: 26.918 ms/op
                 listUser·p1.00:   27.591 ms/op

Iteration   3: 5.583 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.083 ms/op
                 listUser·p0.50:   5.251 ms/op
                 listUser·p0.90:   7.422 ms/op
                 listUser·p0.95:   8.167 ms/op
                 listUser·p0.99:   10.404 ms/op
                 listUser·p0.999:  23.577 ms/op
                 listUser·p0.9999: 26.378 ms/op
                 listUser·p1.00:   27.132 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 174819
  mean =      5.491 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 258 
    [ 2.500,  5.000) = 72293 
    [ 5.000,  7.500) = 87409 
    [ 7.500, 10.000) = 12726 
    [10.000, 12.500) = 1471 
    [12.500, 15.000) = 347 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 102 
    [25.000, 27.500) = 67 

  Percentiles, ms/op:
      p(0.0000) =      0.988 ms/op
     p(50.0000) =      5.194 ms/op
     p(90.0000) =      7.299 ms/op
     p(95.0000) =      8.135 ms/op
     p(99.0000) =     10.322 ms/op
     p(99.9000) =     22.518 ms/op
     p(99.9900) =     26.739 ms/op
     p(99.9990) =     28.672 ms/op
     p(99.9999) =     28.672 ms/op
    p(100.0000) =     28.672 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.265 ± 2.296  ops/ms
ClientGrpc.existUser                       thrpt       3   7.571 ± 2.087  ops/ms
ClientGrpc.getUser                         thrpt       3   7.318 ± 2.249  ops/ms
ClientGrpc.listUser                        thrpt       3   5.625 ± 2.265  ops/ms
ClientGrpc.createUser                       avgt       3   4.281 ± 1.052   ms/op
ClientGrpc.existUser                        avgt       3   4.072 ± 1.148   ms/op
ClientGrpc.getUser                          avgt       3   4.476 ± 0.955   ms/op
ClientGrpc.listUser                         avgt       3   5.435 ± 1.505   ms/op
ClientGrpc.createUser                     sample  216188   4.440 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.143           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.309           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.710           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.185           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.045           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.461           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.606           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.786           ms/op
ClientGrpc.existUser                      sample  236254   4.063 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.857           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.969           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.259           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.734           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.496           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.009           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.882           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.529           ms/op
ClientGrpc.getUser                        sample  216591   4.429 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.104           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.309           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.677           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.144           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.922           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.301           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.508           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.593           ms/op
ClientGrpc.listUser                       sample  174819   5.491 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.988           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.194           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.299           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.135           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.322           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          22.518           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.739           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.672           ms/op
