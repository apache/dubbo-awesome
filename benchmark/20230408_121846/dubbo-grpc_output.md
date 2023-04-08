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
# Warmup Iteration   1: 3.276 ops/ms
# Warmup Iteration   2: 7.181 ops/ms
# Warmup Iteration   3: 8.321 ops/ms
Iteration   1: 8.467 ops/ms
Iteration   2: 8.799 ops/ms
Iteration   3: 8.563 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.610 ±(99.9%) 3.119 ops/ms [Average]
  (min, avg, max) = (8.467, 8.610, 8.799), stdev = 0.171
  CI (99.9%): [5.491, 11.728] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.910 ops/ms
# Warmup Iteration   2: 8.822 ops/ms
# Warmup Iteration   3: 9.164 ops/ms
Iteration   1: 9.342 ops/ms
Iteration   2: 9.294 ops/ms
Iteration   3: 9.186 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.274 ±(99.9%) 1.458 ops/ms [Average]
  (min, avg, max) = (9.186, 9.274, 9.342), stdev = 0.080
  CI (99.9%): [7.816, 10.733] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.485 ops/ms
# Warmup Iteration   2: 8.284 ops/ms
# Warmup Iteration   3: 8.604 ops/ms
Iteration   1: 8.891 ops/ms
Iteration   2: 8.932 ops/ms
Iteration   3: 8.955 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.926 ±(99.9%) 0.588 ops/ms [Average]
  (min, avg, max) = (8.891, 8.926, 8.955), stdev = 0.032
  CI (99.9%): [8.338, 9.514] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.959 ops/ms
# Warmup Iteration   2: 5.788 ops/ms
# Warmup Iteration   3: 6.694 ops/ms
Iteration   1: 6.388 ops/ms
Iteration   2: 6.677 ops/ms
Iteration   3: 6.768 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.611 ±(99.9%) 3.615 ops/ms [Average]
  (min, avg, max) = (6.388, 6.611, 6.768), stdev = 0.198
  CI (99.9%): [2.996, 10.227] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.341 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.825 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.726 ±(99.9%) 0.028 ms/op
Iteration   1: 3.602 ±(99.9%) 0.003 ms/op
Iteration   2: 3.632 ±(99.9%) 0.003 ms/op
Iteration   3: 3.707 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.647 ±(99.9%) 0.988 ms/op [Average]
  (min, avg, max) = (3.602, 3.647, 3.707), stdev = 0.054
  CI (99.9%): [2.659, 4.636] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.426 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.823 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.526 ±(99.9%) 0.003 ms/op
Iteration   1: 3.414 ±(99.9%) 0.003 ms/op
Iteration   2: 3.436 ±(99.9%) 0.003 ms/op
Iteration   3: 3.430 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.427 ±(99.9%) 0.211 ms/op [Average]
  (min, avg, max) = (3.414, 3.427, 3.436), stdev = 0.012
  CI (99.9%): [3.215, 3.638] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.358 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.808 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.756 ±(99.9%) 0.005 ms/op
Iteration   1: 3.706 ±(99.9%) 0.004 ms/op
Iteration   2: 3.671 ±(99.9%) 0.007 ms/op
Iteration   3: 3.591 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.656 ±(99.9%) 1.083 ms/op [Average]
  (min, avg, max) = (3.591, 3.656, 3.706), stdev = 0.059
  CI (99.9%): [2.573, 4.739] (assumes normal distribution)


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
# Warmup Iteration   1: 6.534 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.944 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.828 ±(99.9%) 0.021 ms/op
Iteration   1: 4.764 ±(99.9%) 0.019 ms/op
Iteration   2: 4.767 ±(99.9%) 0.011 ms/op
Iteration   3: 4.647 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.726 ±(99.9%) 1.248 ms/op [Average]
  (min, avg, max) = (4.647, 4.726, 4.767), stdev = 0.068
  CI (99.9%): [3.478, 5.974] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.394 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.913 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.495 ±(99.9%) 0.008 ms/op
Iteration   1: 3.553 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.030 ms/op
                 createUser·p0.50:   3.498 ms/op
                 createUser·p0.90:   4.116 ms/op
                 createUser·p0.95:   4.432 ms/op
                 createUser·p0.99:   5.649 ms/op
                 createUser·p0.999:  8.782 ms/op
                 createUser·p0.9999: 19.038 ms/op
                 createUser·p1.00:   19.628 ms/op

Iteration   2: 3.528 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.847 ms/op
                 createUser·p0.50:   3.494 ms/op
                 createUser·p0.90:   4.194 ms/op
                 createUser·p0.95:   4.481 ms/op
                 createUser·p0.99:   5.505 ms/op
                 createUser·p0.999:  9.990 ms/op
                 createUser·p0.9999: 21.985 ms/op
                 createUser·p1.00:   22.905 ms/op

Iteration   3: 3.593 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.770 ms/op
                 createUser·p0.50:   3.555 ms/op
                 createUser·p0.90:   4.293 ms/op
                 createUser·p0.95:   4.678 ms/op
                 createUser·p0.99:   6.119 ms/op
                 createUser·p0.999:  12.909 ms/op
                 createUser·p0.9999: 24.773 ms/op
                 createUser·p1.00:   27.001 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 269714
  mean =      3.558 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10613 
    [ 2.500,  5.000) = 253046 
    [ 5.000,  7.500) = 5300 
    [ 7.500, 10.000) = 406 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.770 ms/op
     p(50.0000) =      3.514 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =     10.762 ms/op
     p(99.9900) =     24.216 ms/op
     p(99.9990) =     25.636 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


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
# Warmup Iteration   1: 5.154 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.628 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.496 ±(99.9%) 0.009 ms/op
Iteration   1: 3.410 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.866 ms/op
                 existUser·p0.50:   3.396 ms/op
                 existUser·p0.90:   3.969 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   5.333 ms/op
                 existUser·p0.999:  8.981 ms/op
                 existUser·p0.9999: 17.130 ms/op
                 existUser·p1.00:   17.596 ms/op

Iteration   2: 3.407 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.844 ms/op
                 existUser·p0.50:   3.391 ms/op
                 existUser·p0.90:   4.043 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   5.546 ms/op
                 existUser·p0.999:  10.322 ms/op
                 existUser·p0.9999: 18.521 ms/op
                 existUser·p1.00:   19.038 ms/op

Iteration   3: 3.420 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.844 ms/op
                 existUser·p0.50:   3.396 ms/op
                 existUser·p0.90:   4.014 ms/op
                 existUser·p0.95:   4.391 ms/op
                 existUser·p0.99:   5.587 ms/op
                 existUser·p0.999:  14.057 ms/op
                 existUser·p0.9999: 27.561 ms/op
                 existUser·p1.00:   27.820 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 281194
  mean =      3.412 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15448 
    [ 2.500,  5.000) = 260304 
    [ 5.000,  7.500) = 4894 
    [ 7.500, 10.000) = 210 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.844 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =     10.401 ms/op
     p(99.9900) =     25.199 ms/op
     p(99.9990) =     27.820 ms/op
     p(99.9999) =     27.820 ms/op
    p(100.0000) =     27.820 ms/op


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
# Warmup Iteration   1: 5.615 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 3.792 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.623 ±(99.9%) 0.007 ms/op
Iteration   1: 3.577 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.980 ms/op
                 getUser·p0.50:   3.527 ms/op
                 getUser·p0.90:   4.235 ms/op
                 getUser·p0.95:   4.563 ms/op
                 getUser·p0.99:   5.685 ms/op
                 getUser·p0.999:  9.724 ms/op
                 getUser·p0.9999: 15.304 ms/op
                 getUser·p1.00:   15.614 ms/op

Iteration   2: 3.559 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.729 ms/op
                 getUser·p0.50:   3.510 ms/op
                 getUser·p0.90:   4.211 ms/op
                 getUser·p0.95:   4.555 ms/op
                 getUser·p0.99:   5.677 ms/op
                 getUser·p0.999:  8.833 ms/op
                 getUser·p0.9999: 17.434 ms/op
                 getUser·p1.00:   18.022 ms/op

Iteration   3: 3.603 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.571 ms/op
                 getUser·p0.50:   3.539 ms/op
                 getUser·p0.90:   4.202 ms/op
                 getUser·p0.95:   4.522 ms/op
                 getUser·p0.99:   5.800 ms/op
                 getUser·p0.999:  10.231 ms/op
                 getUser·p0.9999: 18.809 ms/op
                 getUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 268117
  mean =      3.580 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 108 
    [ 1.250,  2.500) = 7219 
    [ 2.500,  3.750) = 177839 
    [ 3.750,  5.000) = 76934 
    [ 5.000,  6.250) = 4381 
    [ 6.250,  7.500) = 902 
    [ 7.500,  8.750) = 420 
    [ 8.750, 10.000) = 100 
    [10.000, 11.250) = 54 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 48 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.571 ms/op
     p(50.0000) =      3.523 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =      9.189 ms/op
     p(99.9900) =     18.225 ms/op
     p(99.9990) =     18.842 ms/op
     p(99.9999) =     18.842 ms/op
    p(100.0000) =     18.842 ms/op


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
# Warmup Iteration   1: 6.668 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.979 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.988 ±(99.9%) 0.020 ms/op
Iteration   1: 4.885 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.659 ms/op
                 listUser·p0.50:   4.653 ms/op
                 listUser·p0.90:   6.160 ms/op
                 listUser·p0.95:   6.930 ms/op
                 listUser·p0.99:   8.765 ms/op
                 listUser·p0.999:  16.922 ms/op
                 listUser·p0.9999: 22.045 ms/op
                 listUser·p1.00:   23.953 ms/op

Iteration   2: 4.808 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.597 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   6.013 ms/op
                 listUser·p0.95:   6.889 ms/op
                 listUser·p0.99:   8.618 ms/op
                 listUser·p0.999:  17.662 ms/op
                 listUser·p0.9999: 28.608 ms/op
                 listUser·p1.00:   29.000 ms/op

Iteration   3: 4.702 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.354 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.833 ms/op
                 listUser·p0.95:   6.634 ms/op
                 listUser·p0.99:   8.298 ms/op
                 listUser·p0.999:  20.244 ms/op
                 listUser·p0.9999: 23.697 ms/op
                 listUser·p1.00:   24.117 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 200224
  mean =      4.797 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 336 
    [ 2.500,  5.000) = 147047 
    [ 5.000,  7.500) = 47382 
    [ 7.500, 10.000) = 4602 
    [10.000, 12.500) = 468 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.354 ms/op
     p(50.0000) =      4.579 ms/op
     p(90.0000) =      6.013 ms/op
     p(95.0000) =      6.816 ms/op
     p(99.0000) =      8.585 ms/op
     p(99.9000) =     17.662 ms/op
     p(99.9900) =     27.621 ms/op
     p(99.9990) =     28.869 ms/op
     p(99.9999) =     29.000 ms/op
    p(100.0000) =     29.000 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.610 ± 3.119  ops/ms
ClientGrpc.existUser                       thrpt       3   9.274 ± 1.458  ops/ms
ClientGrpc.getUser                         thrpt       3   8.926 ± 0.588  ops/ms
ClientGrpc.listUser                        thrpt       3   6.611 ± 3.615  ops/ms
ClientGrpc.createUser                       avgt       3   3.647 ± 0.988   ms/op
ClientGrpc.existUser                        avgt       3   3.427 ± 0.211   ms/op
ClientGrpc.getUser                          avgt       3   3.656 ± 1.083   ms/op
ClientGrpc.listUser                         avgt       3   4.726 ± 1.248   ms/op
ClientGrpc.createUser                     sample  269714   3.558 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.770           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.514           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.202           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.522           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.726           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.762           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.216           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.001           ms/op
ClientGrpc.existUser                      sample  281194   3.412 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.844           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.396           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.010           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.366           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.489           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.401           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.199           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.820           ms/op
ClientGrpc.getUser                        sample  268117   3.580 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.571           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.523           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.219           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.555           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.718           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.189           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.225           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.842           ms/op
ClientGrpc.listUser                       sample  200224   4.797 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.354           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.579           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.013           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.816           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.585           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.662           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.621           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.000           ms/op
