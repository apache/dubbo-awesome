# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.350 ops/ms
# Warmup Iteration   2: 5.802 ops/ms
# Warmup Iteration   3: 7.315 ops/ms
Iteration   1: 7.466 ops/ms
Iteration   2: 7.631 ops/ms
Iteration   3: 7.287 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.461 ±(99.9%) 3.132 ops/ms [Average]
  (min, avg, max) = (7.287, 7.461, 7.631), stdev = 0.172
  CI (99.9%): [4.329, 10.594] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.118 ops/ms
# Warmup Iteration   2: 7.276 ops/ms
# Warmup Iteration   3: 7.278 ops/ms
Iteration   1: 7.466 ops/ms
Iteration   2: 7.499 ops/ms
Iteration   3: 7.532 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.499 ±(99.9%) 0.604 ops/ms [Average]
  (min, avg, max) = (7.466, 7.499, 7.532), stdev = 0.033
  CI (99.9%): [6.895, 8.103] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.216 ops/ms
# Warmup Iteration   2: 6.850 ops/ms
# Warmup Iteration   3: 7.292 ops/ms
Iteration   1: 7.375 ops/ms
Iteration   2: 7.314 ops/ms
Iteration   3: 7.004 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.231 ±(99.9%) 3.632 ops/ms [Average]
  (min, avg, max) = (7.004, 7.231, 7.375), stdev = 0.199
  CI (99.9%): [3.599, 10.863] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.304 ops/ms
# Warmup Iteration   2: 5.403 ops/ms
# Warmup Iteration   3: 5.985 ops/ms
Iteration   1: 5.922 ops/ms
Iteration   2: 5.895 ops/ms
Iteration   3: 5.924 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.914 ±(99.9%) 0.293 ops/ms [Average]
  (min, avg, max) = (5.895, 5.914, 5.924), stdev = 0.016
  CI (99.9%): [5.621, 6.207] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.292 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.439 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.271 ±(99.9%) 0.006 ms/op
Iteration   1: 4.393 ±(99.9%) 0.003 ms/op
Iteration   2: 4.484 ±(99.9%) 0.004 ms/op
Iteration   3: 4.482 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.453 ±(99.9%) 0.947 ms/op [Average]
  (min, avg, max) = (4.393, 4.453, 4.484), stdev = 0.052
  CI (99.9%): [3.506, 5.400] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.495 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.338 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.236 ±(99.9%) 0.006 ms/op
Iteration   1: 4.119 ±(99.9%) 0.002 ms/op
Iteration   2: 4.331 ±(99.9%) 0.004 ms/op
Iteration   3: 4.363 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.271 ±(99.9%) 2.418 ms/op [Average]
  (min, avg, max) = (4.119, 4.271, 4.363), stdev = 0.133
  CI (99.9%): [1.853, 6.689] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.717 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.725 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.412 ±(99.9%) 0.004 ms/op
Iteration   1: 4.388 ±(99.9%) 0.004 ms/op
Iteration   2: 4.453 ±(99.9%) 0.003 ms/op
Iteration   3: 4.382 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.408 ±(99.9%) 0.716 ms/op [Average]
  (min, avg, max) = (4.382, 4.408, 4.453), stdev = 0.039
  CI (99.9%): [3.692, 5.124] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.657 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 5.927 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 5.412 ±(99.9%) 0.027 ms/op
Iteration   1: 5.287 ±(99.9%) 0.014 ms/op
Iteration   2: 5.459 ±(99.9%) 0.012 ms/op
Iteration   3: 5.472 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.406 ±(99.9%) 1.886 ms/op [Average]
  (min, avg, max) = (5.287, 5.406, 5.472), stdev = 0.103
  CI (99.9%): [3.519, 7.292] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.537 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.607 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.444 ±(99.9%) 0.015 ms/op
Iteration   1: 4.425 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.143 ms/op
                 createUser·p0.50:   4.317 ms/op
                 createUser·p0.90:   5.620 ms/op
                 createUser·p0.95:   6.046 ms/op
                 createUser·p0.99:   8.004 ms/op
                 createUser·p0.999:  13.620 ms/op
                 createUser·p0.9999: 33.211 ms/op
                 createUser·p1.00:   33.554 ms/op

Iteration   2: 4.446 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.053 ms/op
                 createUser·p0.50:   4.342 ms/op
                 createUser·p0.90:   5.759 ms/op
                 createUser·p0.95:   6.169 ms/op
                 createUser·p0.99:   7.815 ms/op
                 createUser·p0.999:  12.454 ms/op
                 createUser·p0.9999: 22.401 ms/op
                 createUser·p1.00:   22.905 ms/op

Iteration   3: 4.027 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.967 ms/op
                 createUser·p0.50:   3.998 ms/op
                 createUser·p0.90:   4.981 ms/op
                 createUser·p0.95:   5.456 ms/op
                 createUser·p0.99:   6.971 ms/op
                 createUser·p0.999:  9.888 ms/op
                 createUser·p0.9999: 24.153 ms/op
                 createUser·p1.00:   25.559 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 223696
  mean =      4.290 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8147 
    [ 2.500,  5.000) = 170889 
    [ 5.000,  7.500) = 42222 
    [ 7.500, 10.000) = 1932 
    [10.000, 12.500) = 270 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.967 ms/op
     p(50.0000) =      4.178 ms/op
     p(90.0000) =      5.521 ms/op
     p(95.0000) =      5.964 ms/op
     p(99.0000) =      7.643 ms/op
     p(99.9000) =     12.714 ms/op
     p(99.9900) =     24.117 ms/op
     p(99.9990) =     33.514 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.365 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.454 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.297 ±(99.9%) 0.013 ms/op
Iteration   1: 4.183 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.047 ms/op
                 existUser·p0.50:   4.067 ms/op
                 existUser·p0.90:   5.341 ms/op
                 existUser·p0.95:   5.775 ms/op
                 existUser·p0.99:   7.619 ms/op
                 existUser·p0.999:  12.755 ms/op
                 existUser·p0.9999: 22.857 ms/op
                 existUser·p1.00:   23.921 ms/op

Iteration   2: 4.079 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.423 ms/op
                 existUser·p0.50:   3.981 ms/op
                 existUser·p0.90:   5.169 ms/op
                 existUser·p0.95:   5.587 ms/op
                 existUser·p0.99:   7.505 ms/op
                 existUser·p0.999:  16.474 ms/op
                 existUser·p0.9999: 20.873 ms/op
                 existUser·p1.00:   23.724 ms/op

Iteration   3: 4.151 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.915 ms/op
                 existUser·p0.50:   4.071 ms/op
                 existUser·p0.90:   5.218 ms/op
                 existUser·p0.95:   5.554 ms/op
                 existUser·p0.99:   6.712 ms/op
                 existUser·p0.999:  12.632 ms/op
                 existUser·p0.9999: 23.983 ms/op
                 existUser·p1.00:   25.362 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 231913
  mean =      4.137 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6627 
    [ 2.500,  5.000) = 190482 
    [ 5.000,  7.500) = 32742 
    [ 7.500, 10.000) = 1412 
    [10.000, 12.500) = 353 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.423 ms/op
     p(50.0000) =      4.039 ms/op
     p(90.0000) =      5.243 ms/op
     p(95.0000) =      5.644 ms/op
     p(99.0000) =      7.274 ms/op
     p(99.9000) =     14.369 ms/op
     p(99.9900) =     23.521 ms/op
     p(99.9990) =     24.616 ms/op
     p(99.9999) =     25.362 ms/op
    p(100.0000) =     25.362 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.512 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.612 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.424 ±(99.9%) 0.013 ms/op
Iteration   1: 4.367 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.202 ms/op
                 getUser·p0.50:   4.252 ms/op
                 getUser·p0.90:   5.530 ms/op
                 getUser·p0.95:   5.939 ms/op
                 getUser·p0.99:   7.608 ms/op
                 getUser·p0.999:  11.268 ms/op
                 getUser·p0.9999: 15.860 ms/op
                 getUser·p1.00:   16.499 ms/op

Iteration   2: 4.357 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.167 ms/op
                 getUser·p0.50:   4.284 ms/op
                 getUser·p0.90:   5.538 ms/op
                 getUser·p0.95:   5.890 ms/op
                 getUser·p0.99:   7.053 ms/op
                 getUser·p0.999:  10.306 ms/op
                 getUser·p0.9999: 17.858 ms/op
                 getUser·p1.00:   18.743 ms/op

Iteration   3: 4.323 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.059 ms/op
                 getUser·p0.50:   4.235 ms/op
                 getUser·p0.90:   5.456 ms/op
                 getUser·p0.95:   5.808 ms/op
                 getUser·p0.99:   6.939 ms/op
                 getUser·p0.999:  10.343 ms/op
                 getUser·p0.9999: 19.634 ms/op
                 getUser·p1.00:   20.054 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 220729
  mean =      4.349 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3774 
    [ 2.500,  5.000) = 167911 
    [ 5.000,  7.500) = 47297 
    [ 7.500, 10.000) = 1448 
    [10.000, 12.500) = 155 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.059 ms/op
     p(50.0000) =      4.260 ms/op
     p(90.0000) =      5.505 ms/op
     p(95.0000) =      5.882 ms/op
     p(99.0000) =      7.198 ms/op
     p(99.9000) =     10.687 ms/op
     p(99.9900) =     19.069 ms/op
     p(99.9990) =     19.961 ms/op
     p(99.9999) =     20.054 ms/op
    p(100.0000) =     20.054 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.692 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 6.024 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.759 ±(99.9%) 0.027 ms/op
Iteration   1: 5.542 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.473 ms/op
                 listUser·p0.50:   5.128 ms/op
                 listUser·p0.90:   7.586 ms/op
                 listUser·p0.95:   8.520 ms/op
                 listUser·p0.99:   10.730 ms/op
                 listUser·p0.999:  24.431 ms/op
                 listUser·p0.9999: 27.795 ms/op
                 listUser·p1.00:   28.639 ms/op

Iteration   2: 5.730 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.092 ms/op
                 listUser·p0.50:   5.349 ms/op
                 listUser·p0.90:   7.823 ms/op
                 listUser·p0.95:   8.651 ms/op
                 listUser·p0.99:   10.617 ms/op
                 listUser·p0.999:  19.864 ms/op
                 listUser·p0.9999: 28.021 ms/op
                 listUser·p1.00:   30.605 ms/op

Iteration   3: 5.682 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.276 ms/op
                 listUser·p0.50:   5.243 ms/op
                 listUser·p0.90:   7.938 ms/op
                 listUser·p0.95:   8.749 ms/op
                 listUser·p0.99:   10.977 ms/op
                 listUser·p0.999:  24.445 ms/op
                 listUser·p0.9999: 38.797 ms/op
                 listUser·p1.00:   39.649 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 169892
  mean =      5.650 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 330 
    [ 2.500,  5.000) = 72314 
    [ 5.000,  7.500) = 75892 
    [ 7.500, 10.000) = 18448 
    [10.000, 12.500) = 2276 
    [12.500, 15.000) = 276 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 75 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.092 ms/op
     p(50.0000) =      5.235 ms/op
     p(90.0000) =      7.782 ms/op
     p(95.0000) =      8.651 ms/op
     p(99.0000) =     10.748 ms/op
     p(99.9000) =     24.347 ms/op
     p(99.9900) =     30.147 ms/op
     p(99.9990) =     39.329 ms/op
     p(99.9999) =     39.649 ms/op
    p(100.0000) =     39.649 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.461 ± 3.132  ops/ms
ClientGrpc.existUser                       thrpt       3   7.499 ± 0.604  ops/ms
ClientGrpc.getUser                         thrpt       3   7.231 ± 3.632  ops/ms
ClientGrpc.listUser                        thrpt       3   5.914 ± 0.293  ops/ms
ClientGrpc.createUser                       avgt       3   4.453 ± 0.947   ms/op
ClientGrpc.existUser                        avgt       3   4.271 ± 2.418   ms/op
ClientGrpc.getUser                          avgt       3   4.408 ± 0.716   ms/op
ClientGrpc.listUser                         avgt       3   5.406 ± 1.886   ms/op
ClientGrpc.createUser                     sample  223696   4.290 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.967           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.178           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.521           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.964           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.643           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.714           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.117           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.554           ms/op
ClientGrpc.existUser                      sample  231913   4.137 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.423           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.039           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.243           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.644           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.274           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          14.369           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.521           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.362           ms/op
ClientGrpc.getUser                        sample  220729   4.349 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.059           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.260           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.505           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.882           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.198           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.687           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.069           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.054           ms/op
ClientGrpc.listUser                       sample  169892   5.650 ± 0.014   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.092           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.235           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.782           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.651           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.748           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          24.347           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.147           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          39.649           ms/op
