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
# Warmup Iteration   1: 3.163 ops/ms
# Warmup Iteration   2: 7.165 ops/ms
# Warmup Iteration   3: 8.407 ops/ms
Iteration   1: 8.867 ops/ms
Iteration   2: 9.227 ops/ms
Iteration   3: 8.873 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.989 ±(99.9%) 3.760 ops/ms [Average]
  (min, avg, max) = (8.867, 8.989, 9.227), stdev = 0.206
  CI (99.9%): [5.230, 12.749] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 6.032 ops/ms
# Warmup Iteration   2: 8.989 ops/ms
# Warmup Iteration   3: 9.823 ops/ms
Iteration   1: 9.717 ops/ms
Iteration   2: 9.796 ops/ms
Iteration   3: 9.461 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.658 ±(99.9%) 3.190 ops/ms [Average]
  (min, avg, max) = (9.461, 9.658, 9.796), stdev = 0.175
  CI (99.9%): [6.468, 12.848] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.340 ops/ms
# Warmup Iteration   2: 8.484 ops/ms
# Warmup Iteration   3: 8.918 ops/ms
Iteration   1: 9.009 ops/ms
Iteration   2: 8.955 ops/ms
Iteration   3: 9.031 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.998 ±(99.9%) 0.717 ops/ms [Average]
  (min, avg, max) = (8.955, 8.998, 9.031), stdev = 0.039
  CI (99.9%): [8.282, 9.715] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 4.369 ops/ms
# Warmup Iteration   2: 6.496 ops/ms
# Warmup Iteration   3: 6.639 ops/ms
Iteration   1: 7.112 ops/ms
Iteration   2: 6.770 ops/ms
Iteration   3: 6.873 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.918 ±(99.9%) 3.198 ops/ms [Average]
  (min, avg, max) = (6.770, 6.918, 7.112), stdev = 0.175
  CI (99.9%): [3.720, 10.116] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 5.252 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.042 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.774 ±(99.9%) 0.002 ms/op
Iteration   1: 3.738 ±(99.9%) 0.002 ms/op
Iteration   2: 3.501 ±(99.9%) 0.002 ms/op
Iteration   3: 3.793 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.677 ±(99.9%) 2.832 ms/op [Average]
  (min, avg, max) = (3.501, 3.677, 3.793), stdev = 0.155
  CI (99.9%): [0.845, 6.509] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.473 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.485 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.320 ±(99.9%) 0.002 ms/op
Iteration   1: 3.289 ±(99.9%) 0.002 ms/op
Iteration   2: 3.250 ±(99.9%) 0.002 ms/op
Iteration   3: 3.253 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.264 ±(99.9%) 0.393 ms/op [Average]
  (min, avg, max) = (3.250, 3.264, 3.289), stdev = 0.022
  CI (99.9%): [2.871, 3.657] (assumes normal distribution)


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
# Warmup Iteration   1: 5.932 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.931 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.586 ±(99.9%) 0.003 ms/op
Iteration   1: 3.566 ±(99.9%) 0.002 ms/op
Iteration   2: 3.517 ±(99.9%) 0.002 ms/op
Iteration   3: 3.656 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.580 ±(99.9%) 1.286 ms/op [Average]
  (min, avg, max) = (3.517, 3.580, 3.656), stdev = 0.071
  CI (99.9%): [2.293, 4.866] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 6.045 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 5.110 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.676 ±(99.9%) 0.021 ms/op
Iteration   1: 4.753 ±(99.9%) 0.025 ms/op
Iteration   2: 4.714 ±(99.9%) 0.014 ms/op
Iteration   3: 4.625 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.697 ±(99.9%) 1.195 ms/op [Average]
  (min, avg, max) = (4.625, 4.697, 4.753), stdev = 0.065
  CI (99.9%): [3.503, 5.892] (assumes normal distribution)


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
# Warmup Iteration   1: 5.359 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.821 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.669 ±(99.9%) 0.009 ms/op
Iteration   1: 3.561 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.024 ms/op
                 createUser·p0.50:   3.490 ms/op
                 createUser·p0.90:   4.506 ms/op
                 createUser·p0.95:   4.907 ms/op
                 createUser·p0.99:   6.046 ms/op
                 createUser·p0.999:  9.093 ms/op
                 createUser·p0.9999: 16.171 ms/op
                 createUser·p1.00:   16.482 ms/op

Iteration   2: 3.663 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.801 ms/op
                 createUser·p0.50:   3.551 ms/op
                 createUser·p0.90:   4.547 ms/op
                 createUser·p0.95:   4.907 ms/op
                 createUser·p0.99:   6.283 ms/op
                 createUser·p0.999:  14.200 ms/op
                 createUser·p0.9999: 17.254 ms/op
                 createUser·p1.00:   17.629 ms/op

Iteration   3: 3.648 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.039 ms/op
                 createUser·p0.50:   3.527 ms/op
                 createUser·p0.90:   4.555 ms/op
                 createUser·p0.95:   4.973 ms/op
                 createUser·p0.99:   6.341 ms/op
                 createUser·p0.999:  10.014 ms/op
                 createUser·p0.9999: 30.875 ms/op
                 createUser·p1.00:   31.293 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 264920
  mean =      3.623 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9079 
    [ 2.500,  5.000) = 244100 
    [ 5.000,  7.500) = 10648 
    [ 7.500, 10.000) = 691 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.801 ms/op
     p(50.0000) =      3.523 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      4.932 ms/op
     p(99.0000) =      6.218 ms/op
     p(99.9000) =     11.684 ms/op
     p(99.9900) =     29.688 ms/op
     p(99.9990) =     31.185 ms/op
     p(99.9999) =     31.293 ms/op
    p(100.0000) =     31.293 ms/op


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
# Warmup Iteration   1: 4.594 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.657 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.432 ±(99.9%) 0.008 ms/op
Iteration   1: 3.416 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.823 ms/op
                 existUser·p0.50:   3.330 ms/op
                 existUser·p0.90:   4.227 ms/op
                 existUser·p0.95:   4.555 ms/op
                 existUser·p0.99:   5.546 ms/op
                 existUser·p0.999:  12.733 ms/op
                 existUser·p0.9999: 16.703 ms/op
                 existUser·p1.00:   18.252 ms/op

Iteration   2: 3.358 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.966 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   4.084 ms/op
                 existUser·p0.95:   4.350 ms/op
                 existUser·p0.99:   5.153 ms/op
                 existUser·p0.999:  7.881 ms/op
                 existUser·p0.9999: 22.757 ms/op
                 existUser·p1.00:   26.378 ms/op

Iteration   3: 3.275 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.869 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   4.014 ms/op
                 existUser·p0.95:   4.325 ms/op
                 existUser·p0.99:   5.218 ms/op
                 existUser·p0.999:  9.826 ms/op
                 existUser·p0.9999: 18.219 ms/op
                 existUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 286481
  mean =      3.349 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15141 
    [ 2.500,  5.000) = 266866 
    [ 5.000,  7.500) = 3791 
    [ 7.500, 10.000) = 432 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.823 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      4.112 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.300 ms/op
     p(99.9000) =      9.175 ms/op
     p(99.9900) =     20.931 ms/op
     p(99.9990) =     25.946 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


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
# Warmup Iteration   1: 5.508 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.791 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.655 ±(99.9%) 0.010 ms/op
Iteration   1: 3.638 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.911 ms/op
                 getUser·p0.50:   3.523 ms/op
                 getUser·p0.90:   4.604 ms/op
                 getUser·p0.95:   5.046 ms/op
                 getUser·p0.99:   6.545 ms/op
                 getUser·p0.999:  11.518 ms/op
                 getUser·p0.9999: 15.719 ms/op
                 getUser·p1.00:   16.056 ms/op

Iteration   2: 3.683 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.986 ms/op
                 getUser·p0.50:   3.564 ms/op
                 getUser·p0.90:   4.579 ms/op
                 getUser·p0.95:   4.964 ms/op
                 getUser·p0.99:   6.234 ms/op
                 getUser·p0.999:  12.487 ms/op
                 getUser·p0.9999: 16.929 ms/op
                 getUser·p1.00:   17.465 ms/op

Iteration   3: 3.616 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.096 ms/op
                 getUser·p0.50:   3.518 ms/op
                 getUser·p0.90:   4.473 ms/op
                 getUser·p0.95:   4.841 ms/op
                 getUser·p0.99:   6.046 ms/op
                 getUser·p0.999:  8.967 ms/op
                 getUser·p0.9999: 25.859 ms/op
                 getUser·p1.00:   26.313 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 263395
  mean =      3.646 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5857 
    [ 2.500,  5.000) = 245438 
    [ 5.000,  7.500) = 10947 
    [ 7.500, 10.000) = 841 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.911 ms/op
     p(50.0000) =      3.535 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      4.948 ms/op
     p(99.0000) =      6.267 ms/op
     p(99.9000) =     10.306 ms/op
     p(99.9900) =     23.997 ms/op
     p(99.9990) =     26.247 ms/op
     p(99.9999) =     26.313 ms/op
    p(100.0000) =     26.313 ms/op


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
# Warmup Iteration   1: 6.360 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 5.057 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.810 ±(99.9%) 0.018 ms/op
Iteration   1: 4.794 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.522 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   6.308 ms/op
                 listUser·p0.95:   7.135 ms/op
                 listUser·p0.99:   9.175 ms/op
                 listUser·p0.999:  14.959 ms/op
                 listUser·p0.9999: 17.531 ms/op
                 listUser·p1.00:   19.988 ms/op

Iteration   2: 4.651 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.434 ms/op
                 listUser·p0.50:   4.399 ms/op
                 listUser·p0.90:   6.160 ms/op
                 listUser·p0.95:   6.988 ms/op
                 listUser·p0.99:   8.962 ms/op
                 listUser·p0.999:  20.560 ms/op
                 listUser·p0.9999: 26.553 ms/op
                 listUser·p1.00:   27.066 ms/op

Iteration   3: 4.633 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.227 ms/op
                 listUser·p0.50:   4.424 ms/op
                 listUser·p0.90:   5.923 ms/op
                 listUser·p0.95:   6.742 ms/op
                 listUser·p0.99:   9.011 ms/op
                 listUser·p0.999:  18.709 ms/op
                 listUser·p0.9999: 24.418 ms/op
                 listUser·p1.00:   26.903 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 204698
  mean =      4.691 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 764 
    [ 2.500,  5.000) = 147543 
    [ 5.000,  7.500) = 49899 
    [ 7.500, 10.000) = 5310 
    [10.000, 12.500) = 682 
    [12.500, 15.000) = 195 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.227 ms/op
     p(50.0000) =      4.456 ms/op
     p(90.0000) =      6.136 ms/op
     p(95.0000) =      6.971 ms/op
     p(99.0000) =      9.044 ms/op
     p(99.9000) =     16.876 ms/op
     p(99.9900) =     25.366 ms/op
     p(99.9990) =     26.901 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.989 ± 3.760  ops/ms
ClientGrpc.existUser                       thrpt       3   9.658 ± 3.190  ops/ms
ClientGrpc.getUser                         thrpt       3   8.998 ± 0.717  ops/ms
ClientGrpc.listUser                        thrpt       3   6.918 ± 3.198  ops/ms
ClientGrpc.createUser                       avgt       3   3.677 ± 2.832   ms/op
ClientGrpc.existUser                        avgt       3   3.264 ± 0.393   ms/op
ClientGrpc.getUser                          avgt       3   3.580 ± 1.286   ms/op
ClientGrpc.listUser                         avgt       3   4.697 ± 1.195   ms/op
ClientGrpc.createUser                     sample  264920   3.623 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.801           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.523           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.538           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.932           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.218           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.684           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.688           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.293           ms/op
ClientGrpc.existUser                      sample  286481   3.349 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.823           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.265           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.112           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.415           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.300           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.175           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.931           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.378           ms/op
ClientGrpc.getUser                        sample  263395   3.646 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.911           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.535           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.555           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.948           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.267           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.306           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.997           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.313           ms/op
ClientGrpc.listUser                       sample  204698   4.691 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.227           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.456           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.136           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.971           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.044           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.876           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.366           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.066           ms/op
