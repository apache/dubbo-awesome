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
# Warmup Iteration   1: 3.232 ops/ms
# Warmup Iteration   2: 7.067 ops/ms
# Warmup Iteration   3: 8.696 ops/ms
Iteration   1: 9.018 ops/ms
Iteration   2: 9.280 ops/ms
Iteration   3: 9.251 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.183 ±(99.9%) 2.621 ops/ms [Average]
  (min, avg, max) = (9.018, 9.183, 9.280), stdev = 0.144
  CI (99.9%): [6.562, 11.804] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.931 ops/ms
# Warmup Iteration   2: 9.056 ops/ms
# Warmup Iteration   3: 9.629 ops/ms
Iteration   1: 9.593 ops/ms
Iteration   2: 9.603 ops/ms
Iteration   3: 9.474 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.556 ±(99.9%) 1.310 ops/ms [Average]
  (min, avg, max) = (9.474, 9.556, 9.603), stdev = 0.072
  CI (99.9%): [8.246, 10.866] (assumes normal distribution)


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
# Warmup Iteration   1: 5.513 ops/ms
# Warmup Iteration   2: 8.756 ops/ms
# Warmup Iteration   3: 8.910 ops/ms
Iteration   1: 9.012 ops/ms
Iteration   2: 9.159 ops/ms
Iteration   3: 9.143 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.105 ±(99.9%) 1.476 ops/ms [Average]
  (min, avg, max) = (9.012, 9.105, 9.159), stdev = 0.081
  CI (99.9%): [7.628, 10.581] (assumes normal distribution)


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
# Warmup Iteration   1: 4.701 ops/ms
# Warmup Iteration   2: 6.567 ops/ms
# Warmup Iteration   3: 6.656 ops/ms
Iteration   1: 6.816 ops/ms
Iteration   2: 6.872 ops/ms
Iteration   3: 6.889 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.859 ±(99.9%) 0.696 ops/ms [Average]
  (min, avg, max) = (6.816, 6.859, 6.889), stdev = 0.038
  CI (99.9%): [6.163, 7.555] (assumes normal distribution)


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
# Warmup Iteration   1: 5.192 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.677 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.574 ±(99.9%) 0.002 ms/op
Iteration   1: 3.458 ±(99.9%) 0.003 ms/op
Iteration   2: 3.516 ±(99.9%) 0.004 ms/op
Iteration   3: 3.471 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.482 ±(99.9%) 0.557 ms/op [Average]
  (min, avg, max) = (3.458, 3.482, 3.516), stdev = 0.031
  CI (99.9%): [2.925, 4.039] (assumes normal distribution)


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
# Warmup Iteration   1: 4.773 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.565 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.393 ±(99.9%) 0.004 ms/op
Iteration   1: 3.347 ±(99.9%) 0.003 ms/op
Iteration   2: 3.392 ±(99.9%) 0.003 ms/op
Iteration   3: 3.340 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.360 ±(99.9%) 0.513 ms/op [Average]
  (min, avg, max) = (3.340, 3.360, 3.392), stdev = 0.028
  CI (99.9%): [2.847, 3.872] (assumes normal distribution)


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
# Warmup Iteration   1: 5.142 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.639 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.584 ±(99.9%) 0.003 ms/op
Iteration   1: 3.502 ±(99.9%) 0.005 ms/op
Iteration   2: 3.534 ±(99.9%) 0.002 ms/op
Iteration   3: 3.557 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.531 ±(99.9%) 0.502 ms/op [Average]
  (min, avg, max) = (3.502, 3.531, 3.557), stdev = 0.028
  CI (99.9%): [3.029, 4.033] (assumes normal distribution)


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
# Warmup Iteration   1: 7.167 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.866 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.564 ±(99.9%) 0.013 ms/op
Iteration   1: 4.673 ±(99.9%) 0.011 ms/op
Iteration   2: 4.617 ±(99.9%) 0.016 ms/op
Iteration   3: 4.547 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.612 ±(99.9%) 1.150 ms/op [Average]
  (min, avg, max) = (4.547, 4.612, 4.673), stdev = 0.063
  CI (99.9%): [3.462, 5.762] (assumes normal distribution)


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
# Warmup Iteration   1: 5.251 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.810 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.747 ±(99.9%) 0.009 ms/op
Iteration   1: 3.615 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.892 ms/op
                 createUser·p0.50:   3.547 ms/op
                 createUser·p0.90:   4.268 ms/op
                 createUser·p0.95:   4.645 ms/op
                 createUser·p0.99:   5.621 ms/op
                 createUser·p0.999:  8.264 ms/op
                 createUser·p0.9999: 20.190 ms/op
                 createUser·p1.00:   20.480 ms/op

Iteration   2: 3.527 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.081 ms/op
                 createUser·p0.50:   3.498 ms/op
                 createUser·p0.90:   3.981 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   4.915 ms/op
                 createUser·p0.999:  8.662 ms/op
                 createUser·p0.9999: 19.131 ms/op
                 createUser·p1.00:   19.399 ms/op

Iteration   3: 3.601 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.876 ms/op
                 createUser·p0.50:   3.555 ms/op
                 createUser·p0.90:   4.260 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   5.202 ms/op
                 createUser·p0.999:  8.539 ms/op
                 createUser·p0.9999: 21.627 ms/op
                 createUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 268294
  mean =      3.581 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3980 
    [ 2.500,  5.000) = 260283 
    [ 5.000,  7.500) = 3456 
    [ 7.500, 10.000) = 377 
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.876 ms/op
     p(50.0000) =      3.531 ms/op
     p(90.0000) =      4.170 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.325 ms/op
     p(99.9000) =      8.454 ms/op
     p(99.9900) =     20.753 ms/op
     p(99.9990) =     22.946 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


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
# Warmup Iteration   1: 4.726 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.553 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.361 ±(99.9%) 0.008 ms/op
Iteration   1: 3.339 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.904 ms/op
                 existUser·p0.50:   3.355 ms/op
                 existUser·p0.90:   3.981 ms/op
                 existUser·p0.95:   4.243 ms/op
                 existUser·p0.99:   5.124 ms/op
                 existUser·p0.999:  9.408 ms/op
                 existUser·p0.9999: 14.032 ms/op
                 existUser·p1.00:   18.350 ms/op

Iteration   2: 3.374 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.589 ms/op
                 existUser·p0.50:   3.363 ms/op
                 existUser·p0.90:   3.813 ms/op
                 existUser·p0.95:   4.018 ms/op
                 existUser·p0.99:   4.973 ms/op
                 existUser·p0.999:  6.948 ms/op
                 existUser·p0.9999: 16.517 ms/op
                 existUser·p1.00:   17.170 ms/op

Iteration   3: 3.415 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.931 ms/op
                 existUser·p0.50:   3.379 ms/op
                 existUser·p0.90:   4.043 ms/op
                 existUser·p0.95:   4.407 ms/op
                 existUser·p0.99:   5.341 ms/op
                 existUser·p0.999:  11.100 ms/op
                 existUser·p0.9999: 27.546 ms/op
                 existUser·p1.00:   30.147 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 284445
  mean =      3.376 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13391 
    [ 2.500,  5.000) = 267565 
    [ 5.000,  7.500) = 3093 
    [ 7.500, 10.000) = 192 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.589 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      5.177 ms/op
     p(99.9000) =      8.603 ms/op
     p(99.9900) =     27.055 ms/op
     p(99.9990) =     28.075 ms/op
     p(99.9999) =     30.147 ms/op
    p(100.0000) =     30.147 ms/op


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
# Warmup Iteration   1: 5.124 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.637 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.562 ±(99.9%) 0.009 ms/op
Iteration   1: 3.540 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.757 ms/op
                 getUser·p0.50:   3.506 ms/op
                 getUser·p0.90:   4.157 ms/op
                 getUser·p0.95:   4.522 ms/op
                 getUser·p0.99:   5.590 ms/op
                 getUser·p0.999:  8.801 ms/op
                 getUser·p0.9999: 19.595 ms/op
                 getUser·p1.00:   19.825 ms/op

Iteration   2: 3.553 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.010 ms/op
                 getUser·p0.50:   3.506 ms/op
                 getUser·p0.90:   4.055 ms/op
                 getUser·p0.95:   4.342 ms/op
                 getUser·p0.99:   5.308 ms/op
                 getUser·p0.999:  9.945 ms/op
                 getUser·p0.9999: 20.906 ms/op
                 getUser·p1.00:   22.610 ms/op

Iteration   3: 3.529 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.698 ms/op
                 getUser·p0.50:   3.510 ms/op
                 getUser·p0.90:   4.202 ms/op
                 getUser·p0.95:   4.399 ms/op
                 getUser·p0.99:   5.063 ms/op
                 getUser·p0.999:  7.212 ms/op
                 getUser·p0.9999: 21.592 ms/op
                 getUser·p1.00:   24.019 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 271100
  mean =      3.541 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8671 
    [ 2.500,  5.000) = 258222 
    [ 5.000,  7.500) = 3581 
    [ 7.500, 10.000) = 452 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.698 ms/op
     p(50.0000) =      3.510 ms/op
     p(90.0000) =      4.145 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.341 ms/op
     p(99.9000) =      8.977 ms/op
     p(99.9900) =     21.365 ms/op
     p(99.9990) =     23.743 ms/op
     p(99.9999) =     24.019 ms/op
    p(100.0000) =     24.019 ms/op


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
# Warmup Iteration   1: 5.814 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.944 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.670 ±(99.9%) 0.013 ms/op
Iteration   1: 4.639 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.996 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   5.644 ms/op
                 listUser·p0.95:   6.750 ms/op
                 listUser·p0.99:   8.307 ms/op
                 listUser·p0.999:  14.418 ms/op
                 listUser·p0.9999: 16.908 ms/op
                 listUser·p1.00:   17.236 ms/op

Iteration   2: 4.648 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.967 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.358 ms/op
                 listUser·p0.95:   6.242 ms/op
                 listUser·p0.99:   8.266 ms/op
                 listUser·p0.999:  19.995 ms/op
                 listUser·p0.9999: 25.068 ms/op
                 listUser·p1.00:   25.723 ms/op

Iteration   3: 4.600 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.229 ms/op
                 listUser·p0.50:   4.440 ms/op
                 listUser·p0.90:   5.390 ms/op
                 listUser·p0.95:   6.357 ms/op
                 listUser·p0.99:   8.053 ms/op
                 listUser·p0.999:  19.956 ms/op
                 listUser·p0.9999: 26.477 ms/op
                 listUser·p1.00:   26.706 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 207250
  mean =      4.629 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 363 
    [ 2.500,  5.000) = 172187 
    [ 5.000,  7.500) = 30514 
    [ 7.500, 10.000) = 3516 
    [10.000, 12.500) = 292 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.967 ms/op
     p(50.0000) =      4.465 ms/op
     p(90.0000) =      5.456 ms/op
     p(95.0000) =      6.496 ms/op
     p(99.0000) =      8.184 ms/op
     p(99.9000) =     17.400 ms/op
     p(99.9900) =     25.628 ms/op
     p(99.9990) =     26.671 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.183 ± 2.621  ops/ms
ClientGrpc.existUser                       thrpt       3   9.556 ± 1.310  ops/ms
ClientGrpc.getUser                         thrpt       3   9.105 ± 1.476  ops/ms
ClientGrpc.listUser                        thrpt       3   6.859 ± 0.696  ops/ms
ClientGrpc.createUser                       avgt       3   3.482 ± 0.557   ms/op
ClientGrpc.existUser                        avgt       3   3.360 ± 0.513   ms/op
ClientGrpc.getUser                          avgt       3   3.531 ± 0.502   ms/op
ClientGrpc.listUser                         avgt       3   4.612 ± 1.150   ms/op
ClientGrpc.createUser                     sample  268294   3.581 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.876           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.531           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.170           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.456           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.325           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.454           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.753           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.527           ms/op
ClientGrpc.existUser                      sample  284445   3.376 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.589           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.367           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.940           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.243           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.177           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.603           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          27.055           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          30.147           ms/op
ClientGrpc.getUser                        sample  271100   3.541 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.698           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.510           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.145           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.415           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.341           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.977           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.365           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.019           ms/op
ClientGrpc.listUser                       sample  207250   4.629 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.967           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.465           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.456           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.496           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.184           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.400           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.628           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.706           ms/op
