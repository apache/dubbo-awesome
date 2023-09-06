# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.236 ops/ms
# Warmup Iteration   2: 6.700 ops/ms
# Warmup Iteration   3: 8.036 ops/ms
Iteration   1: 8.510 ops/ms
Iteration   2: 8.819 ops/ms
Iteration   3: 8.732 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.687 ±(99.9%) 2.905 ops/ms [Average]
  (min, avg, max) = (8.510, 8.687, 8.819), stdev = 0.159
  CI (99.9%): [5.782, 11.592] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 6.051 ops/ms
# Warmup Iteration   2: 8.442 ops/ms
# Warmup Iteration   3: 8.904 ops/ms
Iteration   1: 9.096 ops/ms
Iteration   2: 9.191 ops/ms
Iteration   3: 9.141 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.143 ±(99.9%) 0.867 ops/ms [Average]
  (min, avg, max) = (9.096, 9.143, 9.191), stdev = 0.048
  CI (99.9%): [8.276, 10.010] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.338 ops/ms
# Warmup Iteration   2: 7.964 ops/ms
# Warmup Iteration   3: 8.366 ops/ms
Iteration   1: 8.590 ops/ms
Iteration   2: 8.631 ops/ms
Iteration   3: 8.494 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.572 ±(99.9%) 1.279 ops/ms [Average]
  (min, avg, max) = (8.494, 8.572, 8.631), stdev = 0.070
  CI (99.9%): [7.293, 9.851] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.610 ops/ms
# Warmup Iteration   2: 6.336 ops/ms
# Warmup Iteration   3: 6.622 ops/ms
Iteration   1: 6.805 ops/ms
Iteration   2: 6.684 ops/ms
Iteration   3: 6.699 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.729 ±(99.9%) 1.203 ops/ms [Average]
  (min, avg, max) = (6.684, 6.729, 6.805), stdev = 0.066
  CI (99.9%): [5.526, 7.932] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.454 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.812 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.706 ±(99.9%) 0.006 ms/op
Iteration   1: 3.605 ±(99.9%) 0.006 ms/op
Iteration   2: 3.710 ±(99.9%) 0.003 ms/op
Iteration   3: 3.736 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.684 ±(99.9%) 1.266 ms/op [Average]
  (min, avg, max) = (3.605, 3.684, 3.736), stdev = 0.069
  CI (99.9%): [2.418, 4.950] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.955 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.694 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.569 ±(99.9%) 0.004 ms/op
Iteration   1: 3.558 ±(99.9%) 0.003 ms/op
Iteration   2: 3.461 ±(99.9%) 0.004 ms/op
Iteration   3: 3.443 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.487 ±(99.9%) 1.124 ms/op [Average]
  (min, avg, max) = (3.443, 3.487, 3.558), stdev = 0.062
  CI (99.9%): [2.363, 4.611] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.396 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.000 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.811 ±(99.9%) 0.004 ms/op
Iteration   1: 3.925 ±(99.9%) 0.004 ms/op
Iteration   2: 3.893 ±(99.9%) 0.004 ms/op
Iteration   3: 3.775 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.864 ±(99.9%) 1.446 ms/op [Average]
  (min, avg, max) = (3.775, 3.864, 3.925), stdev = 0.079
  CI (99.9%): [2.418, 5.311] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.951 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.940 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.852 ±(99.9%) 0.013 ms/op
Iteration   1: 4.787 ±(99.9%) 0.014 ms/op
Iteration   2: 4.727 ±(99.9%) 0.013 ms/op
Iteration   3: 4.758 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.757 ±(99.9%) 0.540 ms/op [Average]
  (min, avg, max) = (4.727, 4.757, 4.787), stdev = 0.030
  CI (99.9%): [4.217, 5.297] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.212 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.890 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.782 ±(99.9%) 0.012 ms/op
Iteration   1: 3.719 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.844 ms/op
                 createUser·p0.50:   3.674 ms/op
                 createUser·p0.90:   4.456 ms/op
                 createUser·p0.95:   4.817 ms/op
                 createUser·p0.99:   6.078 ms/op
                 createUser·p0.999:  11.289 ms/op
                 createUser·p0.9999: 19.202 ms/op
                 createUser·p1.00:   20.021 ms/op

Iteration   2: 3.777 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.048 ms/op
                 createUser·p0.50:   3.686 ms/op
                 createUser·p0.90:   4.497 ms/op
                 createUser·p0.95:   4.792 ms/op
                 createUser·p0.99:   6.201 ms/op
                 createUser·p0.999:  11.666 ms/op
                 createUser·p0.9999: 24.692 ms/op
                 createUser·p1.00:   25.199 ms/op

Iteration   3: 3.733 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.575 ms/op
                 createUser·p0.50:   3.670 ms/op
                 createUser·p0.90:   4.424 ms/op
                 createUser·p0.95:   4.784 ms/op
                 createUser·p0.99:   6.088 ms/op
                 createUser·p0.999:  10.542 ms/op
                 createUser·p0.9999: 25.997 ms/op
                 createUser·p1.00:   26.542 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 256565
  mean =      3.743 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7025 
    [ 2.500,  5.000) = 241117 
    [ 5.000,  7.500) = 7211 
    [ 7.500, 10.000) = 818 
    [10.000, 12.500) = 201 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      0.575 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      6.119 ms/op
     p(99.9000) =     11.158 ms/op
     p(99.9900) =     25.406 ms/op
     p(99.9990) =     26.458 ms/op
     p(99.9999) =     26.542 ms/op
    p(100.0000) =     26.542 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 4.980 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.734 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.578 ±(99.9%) 0.008 ms/op
Iteration   1: 3.514 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.867 ms/op
                 existUser·p0.50:   3.478 ms/op
                 existUser·p0.90:   4.284 ms/op
                 existUser·p0.95:   4.579 ms/op
                 existUser·p0.99:   5.726 ms/op
                 existUser·p0.999:  9.060 ms/op
                 existUser·p0.9999: 21.594 ms/op
                 existUser·p1.00:   21.856 ms/op

Iteration   2: 3.505 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.908 ms/op
                 existUser·p0.50:   3.437 ms/op
                 existUser·p0.90:   4.059 ms/op
                 existUser·p0.95:   4.473 ms/op
                 existUser·p0.99:   5.751 ms/op
                 existUser·p0.999:  12.939 ms/op
                 existUser·p0.9999: 20.541 ms/op
                 existUser·p1.00:   21.791 ms/op

Iteration   3: 3.534 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.951 ms/op
                 existUser·p0.50:   3.473 ms/op
                 existUser·p0.90:   4.112 ms/op
                 existUser·p0.95:   4.497 ms/op
                 existUser·p0.99:   5.931 ms/op
                 existUser·p0.999:  11.528 ms/op
                 existUser·p0.9999: 23.295 ms/op
                 existUser·p1.00:   25.723 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 272894
  mean =      3.518 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11532 
    [ 2.500,  5.000) = 254900 
    [ 5.000,  7.500) = 5396 
    [ 7.500, 10.000) = 658 
    [10.000, 12.500) = 149 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.867 ms/op
     p(50.0000) =      3.461 ms/op
     p(90.0000) =      4.162 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      5.816 ms/op
     p(99.9000) =     12.175 ms/op
     p(99.9900) =     21.758 ms/op
     p(99.9990) =     24.138 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.535 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 3.952 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.844 ±(99.9%) 0.010 ms/op
Iteration   1: 3.815 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.972 ms/op
                 getUser·p0.50:   3.723 ms/op
                 getUser·p0.90:   4.571 ms/op
                 getUser·p0.95:   4.940 ms/op
                 getUser·p0.99:   6.537 ms/op
                 getUser·p0.999:  13.877 ms/op
                 getUser·p0.9999: 15.280 ms/op
                 getUser·p1.00:   15.532 ms/op

Iteration   2: 3.719 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.701 ms/op
                 getUser·p0.50:   3.650 ms/op
                 getUser·p0.90:   4.424 ms/op
                 getUser·p0.95:   4.801 ms/op
                 getUser·p0.99:   5.956 ms/op
                 getUser·p0.999:  11.354 ms/op
                 getUser·p0.9999: 17.263 ms/op
                 getUser·p1.00:   17.727 ms/op

Iteration   3: 3.686 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.821 ms/op
                 getUser·p0.50:   3.617 ms/op
                 getUser·p0.90:   4.415 ms/op
                 getUser·p0.95:   4.760 ms/op
                 getUser·p0.99:   5.939 ms/op
                 getUser·p0.999:  9.783 ms/op
                 getUser·p0.9999: 17.420 ms/op
                 getUser·p1.00:   18.153 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 256790
  mean =      3.739 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 129 
    [ 1.250,  2.500) = 6285 
    [ 2.500,  3.750) = 140485 
    [ 3.750,  5.000) = 100317 
    [ 5.000,  6.250) = 7337 
    [ 6.250,  7.500) = 1281 
    [ 7.500,  8.750) = 471 
    [ 8.750, 10.000) = 158 
    [10.000, 11.250) = 40 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 63 
    [15.000, 16.250) = 36 
    [16.250, 17.500) = 77 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.701 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      6.112 ms/op
     p(99.9000) =     11.676 ms/op
     p(99.9900) =     17.246 ms/op
     p(99.9990) =     17.774 ms/op
     p(99.9999) =     18.153 ms/op
    p(100.0000) =     18.153 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.737 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 5.065 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.824 ±(99.9%) 0.016 ms/op
Iteration   1: 4.839 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.274 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   6.128 ms/op
                 listUser·p0.95:   6.980 ms/op
                 listUser·p0.99:   9.011 ms/op
                 listUser·p0.999:  14.923 ms/op
                 listUser·p0.9999: 16.803 ms/op
                 listUser·p1.00:   18.678 ms/op

Iteration   2: 4.820 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.409 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   6.070 ms/op
                 listUser·p0.95:   6.832 ms/op
                 listUser·p0.99:   8.864 ms/op
                 listUser·p0.999:  15.930 ms/op
                 listUser·p0.9999: 19.345 ms/op
                 listUser·p1.00:   20.120 ms/op

Iteration   3: 4.794 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.202 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   6.185 ms/op
                 listUser·p0.95:   6.799 ms/op
                 listUser·p0.99:   8.749 ms/op
                 listUser·p0.999:  19.268 ms/op
                 listUser·p0.9999: 21.899 ms/op
                 listUser·p1.00:   22.512 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 199140
  mean =      4.818 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 596 
    [ 2.500,  5.000) = 142095 
    [ 5.000,  7.500) = 50565 
    [ 7.500, 10.000) = 4847 
    [10.000, 12.500) = 606 
    [12.500, 15.000) = 193 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.202 ms/op
     p(50.0000) =      4.596 ms/op
     p(90.0000) =      6.128 ms/op
     p(95.0000) =      6.873 ms/op
     p(99.0000) =      8.864 ms/op
     p(99.9000) =     15.759 ms/op
     p(99.9900) =     21.398 ms/op
     p(99.9990) =     22.284 ms/op
     p(99.9999) =     22.512 ms/op
    p(100.0000) =     22.512 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.687 ± 2.905  ops/ms
ClientGrpc.existUser                       thrpt       3   9.143 ± 0.867  ops/ms
ClientGrpc.getUser                         thrpt       3   8.572 ± 1.279  ops/ms
ClientGrpc.listUser                        thrpt       3   6.729 ± 1.203  ops/ms
ClientGrpc.createUser                       avgt       3   3.684 ± 1.266   ms/op
ClientGrpc.existUser                        avgt       3   3.487 ± 1.124   ms/op
ClientGrpc.getUser                          avgt       3   3.864 ± 1.446   ms/op
ClientGrpc.listUser                         avgt       3   4.757 ± 0.540   ms/op
ClientGrpc.createUser                     sample  256565   3.743 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.575           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.678           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.465           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.801           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.119           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.158           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.406           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.542           ms/op
ClientGrpc.existUser                      sample  272894   3.518 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.867           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.461           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.162           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.530           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.816           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.175           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.758           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.723           ms/op
ClientGrpc.getUser                        sample  256790   3.739 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.701           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.662           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.481           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.833           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.112           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.676           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.246           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.153           ms/op
ClientGrpc.listUser                       sample  199140   4.818 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.202           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.596           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.128           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.873           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.864           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.759           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.398           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.512           ms/op
