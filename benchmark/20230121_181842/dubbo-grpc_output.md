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
# Warmup Iteration   1: 3.536 ops/ms
# Warmup Iteration   2: 7.677 ops/ms
# Warmup Iteration   3: 8.585 ops/ms
Iteration   1: 9.166 ops/ms
Iteration   2: 8.806 ops/ms
Iteration   3: 9.098 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.023 ±(99.9%) 3.487 ops/ms [Average]
  (min, avg, max) = (8.806, 9.023, 9.166), stdev = 0.191
  CI (99.9%): [5.536, 12.511] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 6.208 ops/ms
# Warmup Iteration   2: 8.923 ops/ms
# Warmup Iteration   3: 9.367 ops/ms
Iteration   1: 9.493 ops/ms
Iteration   2: 9.301 ops/ms
Iteration   3: 9.496 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.430 ±(99.9%) 2.039 ops/ms [Average]
  (min, avg, max) = (9.301, 9.430, 9.496), stdev = 0.112
  CI (99.9%): [7.391, 11.469] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.559 ops/ms
# Warmup Iteration   2: 8.643 ops/ms
# Warmup Iteration   3: 8.716 ops/ms
Iteration   1: 8.600 ops/ms
Iteration   2: 8.947 ops/ms
Iteration   3: 9.011 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.853 ±(99.9%) 4.034 ops/ms [Average]
  (min, avg, max) = (8.600, 8.853, 9.011), stdev = 0.221
  CI (99.9%): [4.819, 12.887] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.749 ops/ms
# Warmup Iteration   2: 6.666 ops/ms
# Warmup Iteration   3: 6.745 ops/ms
Iteration   1: 7.117 ops/ms
Iteration   2: 7.026 ops/ms
Iteration   3: 6.963 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.035 ±(99.9%) 1.408 ops/ms [Average]
  (min, avg, max) = (6.963, 7.035, 7.117), stdev = 0.077
  CI (99.9%): [5.628, 8.443] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 5.180 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.780 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.537 ±(99.9%) 0.003 ms/op
Iteration   1: 3.571 ±(99.9%) 0.003 ms/op
Iteration   2: 3.702 ±(99.9%) 0.003 ms/op
Iteration   3: 3.535 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.603 ±(99.9%) 1.604 ms/op [Average]
  (min, avg, max) = (3.535, 3.603, 3.702), stdev = 0.088
  CI (99.9%): [1.999, 5.207] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.443 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.500 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.406 ±(99.9%) 0.003 ms/op
Iteration   1: 3.350 ±(99.9%) 0.002 ms/op
Iteration   2: 3.455 ±(99.9%) 0.003 ms/op
Iteration   3: 3.436 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.414 ±(99.9%) 1.016 ms/op [Average]
  (min, avg, max) = (3.350, 3.414, 3.455), stdev = 0.056
  CI (99.9%): [2.398, 4.430] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.786 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.667 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.552 ±(99.9%) 0.002 ms/op
Iteration   1: 3.516 ±(99.9%) 0.002 ms/op
Iteration   2: 3.562 ±(99.9%) 0.003 ms/op
Iteration   3: 3.544 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.541 ±(99.9%) 0.418 ms/op [Average]
  (min, avg, max) = (3.516, 3.541, 3.562), stdev = 0.023
  CI (99.9%): [3.122, 3.959] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.903 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.843 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.653 ±(99.9%) 0.015 ms/op
Iteration   1: 4.428 ±(99.9%) 0.008 ms/op
Iteration   2: 4.516 ±(99.9%) 0.013 ms/op
Iteration   3: 4.493 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.479 ±(99.9%) 0.831 ms/op [Average]
  (min, avg, max) = (4.428, 4.479, 4.516), stdev = 0.046
  CI (99.9%): [3.648, 5.310] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.995 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.653 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.594 ±(99.9%) 0.009 ms/op
Iteration   1: 3.560 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.006 ms/op
                 createUser·p0.50:   3.523 ms/op
                 createUser·p0.90:   4.399 ms/op
                 createUser·p0.95:   4.694 ms/op
                 createUser·p0.99:   5.502 ms/op
                 createUser·p0.999:  9.718 ms/op
                 createUser·p0.9999: 14.648 ms/op
                 createUser·p1.00:   15.237 ms/op

Iteration   2: 3.606 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.695 ms/op
                 createUser·p0.50:   3.572 ms/op
                 createUser·p0.90:   4.432 ms/op
                 createUser·p0.95:   4.692 ms/op
                 createUser·p0.99:   5.415 ms/op
                 createUser·p0.999:  8.421 ms/op
                 createUser·p0.9999: 18.711 ms/op
                 createUser·p1.00:   19.202 ms/op

Iteration   3: 3.569 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.643 ms/op
                 createUser·p0.50:   3.539 ms/op
                 createUser·p0.90:   4.399 ms/op
                 createUser·p0.95:   4.645 ms/op
                 createUser·p0.99:   5.325 ms/op
                 createUser·p0.999:  10.539 ms/op
                 createUser·p0.9999: 18.416 ms/op
                 createUser·p1.00:   30.015 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 268269
  mean =      3.578 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11700 
    [ 2.500,  5.000) = 250803 
    [ 5.000,  7.500) = 5199 
    [ 7.500, 10.000) = 312 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.643 ms/op
     p(50.0000) =      3.543 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      5.423 ms/op
     p(99.9000) =      9.896 ms/op
     p(99.9900) =     18.323 ms/op
     p(99.9990) =     19.045 ms/op
     p(99.9999) =     30.015 ms/op
    p(100.0000) =     30.015 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.616 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.398 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.410 ±(99.9%) 0.008 ms/op
Iteration   1: 3.543 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.919 ms/op
                 existUser·p0.50:   3.494 ms/op
                 existUser·p0.90:   4.334 ms/op
                 existUser·p0.95:   4.579 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  9.509 ms/op
                 existUser·p0.9999: 20.346 ms/op
                 existUser·p1.00:   21.070 ms/op

Iteration   2: 3.481 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.712 ms/op
                 existUser·p0.50:   3.478 ms/op
                 existUser·p0.90:   4.293 ms/op
                 existUser·p0.95:   4.514 ms/op
                 existUser·p0.99:   5.228 ms/op
                 existUser·p0.999:  10.578 ms/op
                 existUser·p0.9999: 18.180 ms/op
                 existUser·p1.00:   18.219 ms/op

Iteration   3: 3.465 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.879 ms/op
                 existUser·p0.50:   3.445 ms/op
                 existUser·p0.90:   4.309 ms/op
                 existUser·p0.95:   4.538 ms/op
                 existUser·p0.99:   5.104 ms/op
                 existUser·p0.999:  10.240 ms/op
                 existUser·p0.9999: 18.862 ms/op
                 existUser·p1.00:   19.399 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 274603
  mean =      3.496 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16236 
    [ 2.500,  5.000) = 254211 
    [ 5.000,  7.500) = 3490 
    [ 7.500, 10.000) = 382 
    [10.000, 12.500) = 138 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.712 ms/op
     p(50.0000) =      3.473 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      5.292 ms/op
     p(99.9000) =     10.240 ms/op
     p(99.9900) =     19.810 ms/op
     p(99.9990) =     20.923 ms/op
     p(99.9999) =     21.070 ms/op
    p(100.0000) =     21.070 ms/op


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
# Warmup Iteration   1: 4.923 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.811 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.597 ±(99.9%) 0.008 ms/op
Iteration   1: 3.585 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.863 ms/op
                 getUser·p0.50:   3.531 ms/op
                 getUser·p0.90:   4.383 ms/op
                 getUser·p0.95:   4.678 ms/op
                 getUser·p0.99:   5.603 ms/op
                 getUser·p0.999:  11.092 ms/op
                 getUser·p0.9999: 13.862 ms/op
                 getUser·p1.00:   14.303 ms/op

Iteration   2: 3.549 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.796 ms/op
                 getUser·p0.50:   3.518 ms/op
                 getUser·p0.90:   4.391 ms/op
                 getUser·p0.95:   4.645 ms/op
                 getUser·p0.99:   5.358 ms/op
                 getUser·p0.999:  7.344 ms/op
                 getUser·p0.9999: 19.497 ms/op
                 getUser·p1.00:   20.775 ms/op

Iteration   3: 3.596 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.922 ms/op
                 getUser·p0.50:   3.551 ms/op
                 getUser·p0.90:   4.456 ms/op
                 getUser·p0.95:   4.710 ms/op
                 getUser·p0.99:   5.431 ms/op
                 getUser·p0.999:  8.540 ms/op
                 getUser·p0.9999: 17.305 ms/op
                 getUser·p1.00:   18.153 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 268251
  mean =      3.577 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12074 
    [ 2.500,  5.000) = 250337 
    [ 5.000,  7.500) = 5356 
    [ 7.500, 10.000) = 246 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.796 ms/op
     p(50.0000) =      3.535 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.681 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =      9.126 ms/op
     p(99.9900) =     18.984 ms/op
     p(99.9990) =     19.823 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


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
# Warmup Iteration   1: 6.397 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.793 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.587 ±(99.9%) 0.015 ms/op
Iteration   1: 4.485 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.448 ms/op
                 listUser·p0.50:   4.317 ms/op
                 listUser·p0.90:   5.685 ms/op
                 listUser·p0.95:   6.423 ms/op
                 listUser·p0.99:   7.823 ms/op
                 listUser·p0.999:  14.038 ms/op
                 listUser·p0.9999: 16.900 ms/op
                 listUser·p1.00:   17.498 ms/op

Iteration   2: 4.377 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.790 ms/op
                 listUser·p0.50:   4.170 ms/op
                 listUser·p0.90:   5.726 ms/op
                 listUser·p0.95:   6.423 ms/op
                 listUser·p0.99:   8.077 ms/op
                 listUser·p0.999:  15.873 ms/op
                 listUser·p0.9999: 18.591 ms/op
                 listUser·p1.00:   19.333 ms/op

Iteration   3: 4.670 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.479 ms/op
                 listUser·p0.50:   4.440 ms/op
                 listUser·p0.90:   5.972 ms/op
                 listUser·p0.95:   6.611 ms/op
                 listUser·p0.99:   8.438 ms/op
                 listUser·p0.999:  18.789 ms/op
                 listUser·p0.9999: 21.440 ms/op
                 listUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 213021
  mean =      4.507 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1051 
    [ 2.500,  5.000) = 169932 
    [ 5.000,  7.500) = 38219 
    [ 7.500, 10.000) = 3124 
    [10.000, 12.500) = 285 
    [12.500, 15.000) = 144 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.790 ms/op
     p(50.0000) =      4.309 ms/op
     p(90.0000) =      5.808 ms/op
     p(95.0000) =      6.488 ms/op
     p(99.0000) =      8.118 ms/op
     p(99.9000) =     15.778 ms/op
     p(99.9900) =     20.546 ms/op
     p(99.9990) =     21.745 ms/op
     p(99.9999) =     21.987 ms/op
    p(100.0000) =     21.987 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.023 ± 3.487  ops/ms
ClientGrpc.existUser                       thrpt       3   9.430 ± 2.039  ops/ms
ClientGrpc.getUser                         thrpt       3   8.853 ± 4.034  ops/ms
ClientGrpc.listUser                        thrpt       3   7.035 ± 1.408  ops/ms
ClientGrpc.createUser                       avgt       3   3.603 ± 1.604   ms/op
ClientGrpc.existUser                        avgt       3   3.414 ± 1.016   ms/op
ClientGrpc.getUser                          avgt       3   3.541 ± 0.418   ms/op
ClientGrpc.listUser                         avgt       3   4.479 ± 0.831   ms/op
ClientGrpc.createUser                     sample  268269   3.578 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.643           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.543           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.407           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.669           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.423           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.896           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.323           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.015           ms/op
ClientGrpc.existUser                      sample  274603   3.496 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.712           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.473           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.309           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.547           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.292           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.240           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.810           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.070           ms/op
ClientGrpc.getUser                        sample  268251   3.577 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.796           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.535           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.415           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.681           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.456           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.126           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.984           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.775           ms/op
ClientGrpc.listUser                       sample  213021   4.507 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.790           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.309           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.808           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.488           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.118           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.778           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.546           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.987           ms/op
