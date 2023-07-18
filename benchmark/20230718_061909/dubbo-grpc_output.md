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
# Warmup Iteration   1: 1.861 ops/ms
# Warmup Iteration   2: 4.928 ops/ms
# Warmup Iteration   3: 6.489 ops/ms
Iteration   1: 6.707 ops/ms
Iteration   2: 6.817 ops/ms
Iteration   3: 6.873 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.799 ±(99.9%) 1.543 ops/ms [Average]
  (min, avg, max) = (6.707, 6.799, 6.873), stdev = 0.085
  CI (99.9%): [5.256, 8.342] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.304 ops/ms
# Warmup Iteration   2: 6.912 ops/ms
# Warmup Iteration   3: 7.450 ops/ms
Iteration   1: 7.778 ops/ms
Iteration   2: 8.027 ops/ms
Iteration   3: 7.702 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.836 ±(99.9%) 3.103 ops/ms [Average]
  (min, avg, max) = (7.702, 7.836, 8.027), stdev = 0.170
  CI (99.9%): [4.733, 10.939] (assumes normal distribution)


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
# Warmup Iteration   1: 3.857 ops/ms
# Warmup Iteration   2: 6.274 ops/ms
# Warmup Iteration   3: 6.808 ops/ms
Iteration   1: 6.824 ops/ms
Iteration   2: 6.861 ops/ms
Iteration   3: 6.892 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.859 ±(99.9%) 0.623 ops/ms [Average]
  (min, avg, max) = (6.824, 6.859, 6.892), stdev = 0.034
  CI (99.9%): [6.236, 7.482] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.149 ops/ms
# Warmup Iteration   2: 4.543 ops/ms
# Warmup Iteration   3: 5.323 ops/ms
Iteration   1: 5.272 ops/ms
Iteration   2: 5.376 ops/ms
Iteration   3: 5.239 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.296 ±(99.9%) 1.304 ops/ms [Average]
  (min, avg, max) = (5.239, 5.296, 5.376), stdev = 0.071
  CI (99.9%): [3.992, 6.599] (assumes normal distribution)


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
# Warmup Iteration   1: 7.330 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 5.131 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.877 ±(99.9%) 0.004 ms/op
Iteration   1: 4.704 ±(99.9%) 0.004 ms/op
Iteration   2: 4.758 ±(99.9%) 0.005 ms/op
Iteration   3: 4.645 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.702 ±(99.9%) 1.036 ms/op [Average]
  (min, avg, max) = (4.645, 4.702, 4.758), stdev = 0.057
  CI (99.9%): [3.667, 5.738] (assumes normal distribution)


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
# Warmup Iteration   1: 6.610 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.762 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.522 ±(99.9%) 0.004 ms/op
Iteration   1: 4.470 ±(99.9%) 0.004 ms/op
Iteration   2: 4.520 ±(99.9%) 0.005 ms/op
Iteration   3: 4.357 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.449 ±(99.9%) 1.522 ms/op [Average]
  (min, avg, max) = (4.357, 4.449, 4.520), stdev = 0.083
  CI (99.9%): [2.927, 5.971] (assumes normal distribution)


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
# Warmup Iteration   1: 7.048 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 5.022 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.855 ±(99.9%) 0.003 ms/op
Iteration   1: 4.594 ±(99.9%) 0.005 ms/op
Iteration   2: 4.520 ±(99.9%) 0.004 ms/op
Iteration   3: 4.543 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.552 ±(99.9%) 0.684 ms/op [Average]
  (min, avg, max) = (4.520, 4.552, 4.594), stdev = 0.037
  CI (99.9%): [3.869, 5.236] (assumes normal distribution)


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
# Warmup Iteration   1: 8.673 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 6.671 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 6.145 ±(99.9%) 0.020 ms/op
Iteration   1: 5.769 ±(99.9%) 0.012 ms/op
Iteration   2: 5.917 ±(99.9%) 0.013 ms/op
Iteration   3: 5.931 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.872 ±(99.9%) 1.641 ms/op [Average]
  (min, avg, max) = (5.769, 5.872, 5.931), stdev = 0.090
  CI (99.9%): [4.231, 7.513] (assumes normal distribution)


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
# Warmup Iteration   1: 7.654 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 5.046 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.774 ±(99.9%) 0.017 ms/op
Iteration   1: 4.706 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.122 ms/op
                 createUser·p0.50:   4.530 ms/op
                 createUser·p0.90:   5.956 ms/op
                 createUser·p0.95:   6.570 ms/op
                 createUser·p0.99:   9.241 ms/op
                 createUser·p0.999:  13.633 ms/op
                 createUser·p0.9999: 18.770 ms/op
                 createUser·p1.00:   19.431 ms/op

Iteration   2: 4.649 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.186 ms/op
                 createUser·p0.50:   4.489 ms/op
                 createUser·p0.90:   5.964 ms/op
                 createUser·p0.95:   6.513 ms/op
                 createUser·p0.99:   9.126 ms/op
                 createUser·p0.999:  16.379 ms/op
                 createUser·p0.9999: 18.055 ms/op
                 createUser·p1.00:   19.530 ms/op

Iteration   3: 4.658 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.694 ms/op
                 createUser·p0.50:   4.456 ms/op
                 createUser·p0.90:   5.947 ms/op
                 createUser·p0.95:   6.668 ms/op
                 createUser·p0.99:   9.077 ms/op
                 createUser·p0.999:  15.570 ms/op
                 createUser·p0.9999: 26.088 ms/op
                 createUser·p1.00:   26.542 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 205471
  mean =      4.671 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3940 
    [ 2.500,  5.000) = 141358 
    [ 5.000,  7.500) = 55089 
    [ 7.500, 10.000) = 3723 
    [10.000, 12.500) = 920 
    [12.500, 15.000) = 218 
    [15.000, 17.500) = 131 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.694 ms/op
     p(50.0000) =      4.489 ms/op
     p(90.0000) =      5.956 ms/op
     p(95.0000) =      6.578 ms/op
     p(99.0000) =      9.159 ms/op
     p(99.9000) =     15.295 ms/op
     p(99.9900) =     25.440 ms/op
     p(99.9990) =     26.440 ms/op
     p(99.9999) =     26.542 ms/op
    p(100.0000) =     26.542 ms/op


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
# Warmup Iteration   1: 6.282 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.651 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.589 ±(99.9%) 0.016 ms/op
Iteration   1: 4.379 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.098 ms/op
                 existUser·p0.50:   4.219 ms/op
                 existUser·p0.90:   5.456 ms/op
                 existUser·p0.95:   5.980 ms/op
                 existUser·p0.99:   8.143 ms/op
                 existUser·p0.999:  12.942 ms/op
                 existUser·p0.9999: 22.121 ms/op
                 existUser·p1.00:   24.642 ms/op

Iteration   2: 4.205 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.669 ms/op
                 existUser·p0.50:   4.100 ms/op
                 existUser·p0.90:   5.390 ms/op
                 existUser·p0.95:   5.988 ms/op
                 existUser·p0.99:   7.930 ms/op
                 existUser·p0.999:  12.091 ms/op
                 existUser·p0.9999: 30.867 ms/op
                 existUser·p1.00:   31.228 ms/op

Iteration   3: 4.361 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.655 ms/op
                 existUser·p0.50:   4.211 ms/op
                 existUser·p0.90:   5.439 ms/op
                 existUser·p0.95:   5.947 ms/op
                 existUser·p0.99:   8.069 ms/op
                 existUser·p0.999:  12.413 ms/op
                 existUser·p0.9999: 21.921 ms/op
                 existUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 222520
  mean =      4.314 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6480 
    [ 2.500,  5.000) = 176490 
    [ 5.000,  7.500) = 36385 
    [ 7.500, 10.000) = 2393 
    [10.000, 12.500) = 528 
    [12.500, 15.000) = 147 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.655 ms/op
     p(50.0000) =      4.178 ms/op
     p(90.0000) =      5.431 ms/op
     p(95.0000) =      5.972 ms/op
     p(99.0000) =      8.053 ms/op
     p(99.9000) =     12.665 ms/op
     p(99.9900) =     30.663 ms/op
     p(99.9990) =     30.958 ms/op
     p(99.9999) =     31.228 ms/op
    p(100.0000) =     31.228 ms/op


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
# Warmup Iteration   1: 7.815 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 4.908 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.772 ±(99.9%) 0.019 ms/op
Iteration   1: 4.674 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.965 ms/op
                 getUser·p0.50:   4.530 ms/op
                 getUser·p0.90:   5.833 ms/op
                 getUser·p0.95:   6.431 ms/op
                 getUser·p0.99:   9.170 ms/op
                 getUser·p0.999:  12.845 ms/op
                 getUser·p0.9999: 25.952 ms/op
                 getUser·p1.00:   27.656 ms/op

Iteration   2: 4.575 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.046 ms/op
                 getUser·p0.50:   4.440 ms/op
                 getUser·p0.90:   5.808 ms/op
                 getUser·p0.95:   6.349 ms/op
                 getUser·p0.99:   8.487 ms/op
                 getUser·p0.999:  12.681 ms/op
                 getUser·p0.9999: 25.854 ms/op
                 getUser·p1.00:   26.214 ms/op

Iteration   3: 4.526 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.067 ms/op
                 getUser·p0.50:   4.391 ms/op
                 getUser·p0.90:   5.628 ms/op
                 getUser·p0.95:   6.259 ms/op
                 getUser·p0.99:   8.486 ms/op
                 getUser·p0.999:  16.901 ms/op
                 getUser·p0.9999: 26.802 ms/op
                 getUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 209083
  mean =      4.591 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4662 
    [ 2.500,  5.000) = 147703 
    [ 5.000,  7.500) = 52558 
    [ 7.500, 10.000) = 3117 
    [10.000, 12.500) = 756 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 61 

  Percentiles, ms/op:
      p(0.0000) =      0.965 ms/op
     p(50.0000) =      4.448 ms/op
     p(90.0000) =      5.759 ms/op
     p(95.0000) =      6.349 ms/op
     p(99.0000) =      8.700 ms/op
     p(99.9000) =     13.499 ms/op
     p(99.9900) =     26.640 ms/op
     p(99.9990) =     27.504 ms/op
     p(99.9999) =     27.656 ms/op
    p(100.0000) =     27.656 ms/op


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
# Warmup Iteration   1: 8.823 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 6.424 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.704 ±(99.9%) 0.023 ms/op
Iteration   1: 5.882 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.071 ms/op
                 listUser·p0.50:   5.538 ms/op
                 listUser·p0.90:   7.881 ms/op
                 listUser·p0.95:   8.946 ms/op
                 listUser·p0.99:   11.403 ms/op
                 listUser·p0.999:  18.392 ms/op
                 listUser·p0.9999: 21.303 ms/op
                 listUser·p1.00:   21.627 ms/op

Iteration   2: 5.939 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.911 ms/op
                 listUser·p0.50:   5.530 ms/op
                 listUser·p0.90:   8.053 ms/op
                 listUser·p0.95:   9.224 ms/op
                 listUser·p0.99:   11.977 ms/op
                 listUser·p0.999:  19.969 ms/op
                 listUser·p0.9999: 25.541 ms/op
                 listUser·p1.00:   27.001 ms/op

Iteration   3: 6.173 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.485 ms/op
                 listUser·p0.50:   5.693 ms/op
                 listUser·p0.90:   8.569 ms/op
                 listUser·p0.95:   9.650 ms/op
                 listUser·p0.99:   12.452 ms/op
                 listUser·p0.999:  23.048 ms/op
                 listUser·p0.9999: 30.531 ms/op
                 listUser·p1.00:   31.195 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 160041
  mean =      5.995 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 121 
    [ 2.500,  5.000) = 44946 
    [ 5.000,  7.500) = 90653 
    [ 7.500, 10.000) = 19146 
    [10.000, 12.500) = 3921 
    [12.500, 15.000) = 779 
    [15.000, 17.500) = 221 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.485 ms/op
     p(50.0000) =      5.579 ms/op
     p(90.0000) =      8.192 ms/op
     p(95.0000) =      9.290 ms/op
     p(99.0000) =     11.993 ms/op
     p(99.9000) =     19.299 ms/op
     p(99.9900) =     27.492 ms/op
     p(99.9990) =     31.097 ms/op
     p(99.9999) =     31.195 ms/op
    p(100.0000) =     31.195 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.799 ± 1.543  ops/ms
ClientGrpc.existUser                       thrpt       3   7.836 ± 3.103  ops/ms
ClientGrpc.getUser                         thrpt       3   6.859 ± 0.623  ops/ms
ClientGrpc.listUser                        thrpt       3   5.296 ± 1.304  ops/ms
ClientGrpc.createUser                       avgt       3   4.702 ± 1.036   ms/op
ClientGrpc.existUser                        avgt       3   4.449 ± 1.522   ms/op
ClientGrpc.getUser                          avgt       3   4.552 ± 0.684   ms/op
ClientGrpc.listUser                         avgt       3   5.872 ± 1.641   ms/op
ClientGrpc.createUser                     sample  205471   4.671 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.694           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.489           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.956           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.578           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           9.159           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          15.295           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.440           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.542           ms/op
ClientGrpc.existUser                      sample  222520   4.314 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.655           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.178           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.431           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.972           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.053           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.665           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          30.663           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          31.228           ms/op
ClientGrpc.getUser                        sample  209083   4.591 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.965           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.448           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.759           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.349           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.700           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.499           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.640           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.656           ms/op
ClientGrpc.listUser                       sample  160041   5.995 ± 0.015   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.485           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.579           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.192           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.290           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.993           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.299           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.492           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.195           ms/op
