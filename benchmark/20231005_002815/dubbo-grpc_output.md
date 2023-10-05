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
# Warmup Iteration   1: 3.143 ops/ms
# Warmup Iteration   2: 6.557 ops/ms
# Warmup Iteration   3: 7.557 ops/ms
Iteration   1: 8.074 ops/ms
Iteration   2: 8.036 ops/ms
Iteration   3: 8.226 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.112 ±(99.9%) 1.835 ops/ms [Average]
  (min, avg, max) = (8.036, 8.112, 8.226), stdev = 0.101
  CI (99.9%): [6.278, 9.947] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.744 ops/ms
# Warmup Iteration   2: 8.503 ops/ms
# Warmup Iteration   3: 8.811 ops/ms
Iteration   1: 8.680 ops/ms
Iteration   2: 9.035 ops/ms
Iteration   3: 9.165 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.960 ±(99.9%) 4.585 ops/ms [Average]
  (min, avg, max) = (8.680, 8.960, 9.165), stdev = 0.251
  CI (99.9%): [4.375, 13.545] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 5.536 ops/ms
# Warmup Iteration   2: 8.064 ops/ms
# Warmup Iteration   3: 8.359 ops/ms
Iteration   1: 8.434 ops/ms
Iteration   2: 8.299 ops/ms
Iteration   3: 8.345 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.359 ±(99.9%) 1.246 ops/ms [Average]
  (min, avg, max) = (8.299, 8.359, 8.434), stdev = 0.068
  CI (99.9%): [7.114, 9.605] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 4.078 ops/ms
# Warmup Iteration   2: 5.929 ops/ms
# Warmup Iteration   3: 6.301 ops/ms
Iteration   1: 6.325 ops/ms
Iteration   2: 6.426 ops/ms
Iteration   3: 6.462 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.404 ±(99.9%) 1.293 ops/ms [Average]
  (min, avg, max) = (6.325, 6.404, 6.462), stdev = 0.071
  CI (99.9%): [5.112, 7.697] (assumes normal distribution)


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
# Warmup Iteration   1: 5.724 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.243 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.089 ±(99.9%) 0.029 ms/op
Iteration   1: 3.949 ±(99.9%) 0.008 ms/op
Iteration   2: 3.849 ±(99.9%) 0.004 ms/op
Iteration   3: 3.911 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.903 ±(99.9%) 0.922 ms/op [Average]
  (min, avg, max) = (3.849, 3.903, 3.949), stdev = 0.051
  CI (99.9%): [2.982, 4.825] (assumes normal distribution)


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
# Warmup Iteration   1: 5.009 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.930 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.676 ±(99.9%) 0.004 ms/op
Iteration   1: 3.687 ±(99.9%) 0.004 ms/op
Iteration   2: 3.738 ±(99.9%) 0.006 ms/op
Iteration   3: 3.554 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.660 ±(99.9%) 1.729 ms/op [Average]
  (min, avg, max) = (3.554, 3.660, 3.738), stdev = 0.095
  CI (99.9%): [1.930, 5.389] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.238 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 4.139 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.916 ±(99.9%) 0.007 ms/op
Iteration   1: 3.734 ±(99.9%) 0.007 ms/op
Iteration   2: 3.755 ±(99.9%) 0.004 ms/op
Iteration   3: 3.885 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.791 ±(99.9%) 1.487 ms/op [Average]
  (min, avg, max) = (3.734, 3.791, 3.885), stdev = 0.081
  CI (99.9%): [2.305, 5.278] (assumes normal distribution)


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
# Warmup Iteration   1: 6.625 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 5.746 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.282 ±(99.9%) 0.016 ms/op
Iteration   1: 5.184 ±(99.9%) 0.018 ms/op
Iteration   2: 5.080 ±(99.9%) 0.012 ms/op
Iteration   3: 5.127 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.130 ±(99.9%) 0.950 ms/op [Average]
  (min, avg, max) = (5.080, 5.130, 5.184), stdev = 0.052
  CI (99.9%): [4.180, 6.081] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 5.636 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.126 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.988 ±(99.9%) 0.013 ms/op
Iteration   1: 3.803 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.071 ms/op
                 createUser·p0.50:   3.703 ms/op
                 createUser·p0.90:   4.645 ms/op
                 createUser·p0.95:   5.079 ms/op
                 createUser·p0.99:   6.709 ms/op
                 createUser·p0.999:  13.443 ms/op
                 createUser·p0.9999: 26.837 ms/op
                 createUser·p1.00:   30.671 ms/op

Iteration   2: 3.801 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.538 ms/op
                 createUser·p0.50:   3.686 ms/op
                 createUser·p0.90:   4.620 ms/op
                 createUser·p0.95:   5.145 ms/op
                 createUser·p0.99:   7.324 ms/op
                 createUser·p0.999:  12.108 ms/op
                 createUser·p0.9999: 16.472 ms/op
                 createUser·p1.00:   17.138 ms/op

Iteration   3: 3.873 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.628 ms/op
                 createUser·p0.50:   3.719 ms/op
                 createUser·p0.90:   4.735 ms/op
                 createUser·p0.95:   5.358 ms/op
                 createUser·p0.99:   7.889 ms/op
                 createUser·p0.999:  12.467 ms/op
                 createUser·p0.9999: 18.276 ms/op
                 createUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 250930
  mean =      3.825 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8023 
    [ 2.500,  5.000) = 227453 
    [ 5.000,  7.500) = 13220 
    [ 7.500, 10.000) = 1592 
    [10.000, 12.500) = 382 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.538 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      5.186 ms/op
     p(99.0000) =      7.280 ms/op
     p(99.9000) =     12.681 ms/op
     p(99.9900) =     25.979 ms/op
     p(99.9990) =     26.853 ms/op
     p(99.9999) =     30.671 ms/op
    p(100.0000) =     30.671 ms/op


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
# Warmup Iteration   1: 4.950 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.864 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.648 ±(99.9%) 0.011 ms/op
Iteration   1: 3.594 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.856 ms/op
                 existUser·p0.50:   3.514 ms/op
                 existUser·p0.90:   4.252 ms/op
                 existUser·p0.95:   4.645 ms/op
                 existUser·p0.99:   6.152 ms/op
                 existUser·p0.999:  10.010 ms/op
                 existUser·p0.9999: 17.537 ms/op
                 existUser·p1.00:   17.826 ms/op

Iteration   2: 3.656 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.718 ms/op
                 existUser·p0.50:   3.572 ms/op
                 existUser·p0.90:   4.456 ms/op
                 existUser·p0.95:   5.046 ms/op
                 existUser·p0.99:   7.813 ms/op
                 existUser·p0.999:  13.091 ms/op
                 existUser·p0.9999: 24.822 ms/op
                 existUser·p1.00:   25.264 ms/op

Iteration   3: 3.563 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.794 ms/op
                 existUser·p0.50:   3.523 ms/op
                 existUser·p0.90:   4.260 ms/op
                 existUser·p0.95:   4.702 ms/op
                 existUser·p0.99:   6.308 ms/op
                 existUser·p0.999:  11.769 ms/op
                 existUser·p0.9999: 20.389 ms/op
                 existUser·p1.00:   22.479 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 266418
  mean =      3.604 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14262 
    [ 2.500,  5.000) = 241668 
    [ 5.000,  7.500) = 8758 
    [ 7.500, 10.000) = 965 
    [10.000, 12.500) = 516 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.718 ms/op
     p(50.0000) =      3.535 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      6.650 ms/op
     p(99.9000) =     12.354 ms/op
     p(99.9900) =     21.049 ms/op
     p(99.9990) =     25.122 ms/op
     p(99.9999) =     25.264 ms/op
    p(100.0000) =     25.264 ms/op


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
# Warmup Iteration   1: 5.545 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.118 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.917 ±(99.9%) 0.011 ms/op
Iteration   1: 3.959 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.936 ms/op
                 getUser·p0.50:   3.834 ms/op
                 getUser·p0.90:   4.997 ms/op
                 getUser·p0.95:   5.579 ms/op
                 getUser·p0.99:   7.540 ms/op
                 getUser·p0.999:  13.431 ms/op
                 getUser·p0.9999: 16.280 ms/op
                 getUser·p1.00:   16.744 ms/op

Iteration   2: 3.884 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.814 ms/op
                 getUser·p0.50:   3.777 ms/op
                 getUser·p0.90:   4.669 ms/op
                 getUser·p0.95:   5.169 ms/op
                 getUser·p0.99:   7.299 ms/op
                 getUser·p0.999:  13.287 ms/op
                 getUser·p0.9999: 25.158 ms/op
                 getUser·p1.00:   25.494 ms/op

Iteration   3: 3.846 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.735 ms/op
                 getUser·p0.50:   3.723 ms/op
                 getUser·p0.90:   4.678 ms/op
                 getUser·p0.95:   5.308 ms/op
                 getUser·p0.99:   7.578 ms/op
                 getUser·p0.999:  14.474 ms/op
                 getUser·p0.9999: 25.788 ms/op
                 getUser·p1.00:   26.345 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 246369
  mean =      3.896 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9238 
    [ 2.500,  5.000) = 218430 
    [ 5.000,  7.500) = 16293 
    [ 7.500, 10.000) = 1480 
    [10.000, 12.500) = 517 
    [12.500, 15.000) = 253 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.735 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.374 ms/op
     p(99.0000) =      7.447 ms/op
     p(99.9000) =     13.636 ms/op
     p(99.9900) =     25.166 ms/op
     p(99.9990) =     26.313 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


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
# Warmup Iteration   1: 7.127 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 5.428 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.199 ±(99.9%) 0.023 ms/op
Iteration   1: 5.212 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   0.442 ms/op
                 listUser·p0.50:   4.776 ms/op
                 listUser·p0.90:   7.242 ms/op
                 listUser·p0.95:   8.217 ms/op
                 listUser·p0.99:   10.750 ms/op
                 listUser·p0.999:  18.973 ms/op
                 listUser·p0.9999: 28.491 ms/op
                 listUser·p1.00:   28.606 ms/op

Iteration   2: 5.179 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.210 ms/op
                 listUser·p0.50:   4.760 ms/op
                 listUser·p0.90:   7.160 ms/op
                 listUser·p0.95:   8.143 ms/op
                 listUser·p0.99:   10.781 ms/op
                 listUser·p0.999:  23.248 ms/op
                 listUser·p0.9999: 33.150 ms/op
                 listUser·p1.00:   33.325 ms/op

Iteration   3: 5.188 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.202 ms/op
                 listUser·p0.50:   4.760 ms/op
                 listUser·p0.90:   7.094 ms/op
                 listUser·p0.95:   8.102 ms/op
                 listUser·p0.99:   10.961 ms/op
                 listUser·p0.999:  27.340 ms/op
                 listUser·p0.9999: 39.027 ms/op
                 listUser·p1.00:   41.288 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 184804
  mean =      5.193 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 108699 
    [ 5.000, 10.000) = 73290 
    [10.000, 15.000) = 2212 
    [15.000, 20.000) = 357 
    [20.000, 25.000) = 105 
    [25.000, 30.000) = 53 
    [30.000, 35.000) = 51 
    [35.000, 40.000) = 36 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.442 ms/op
     p(50.0000) =      4.760 ms/op
     p(90.0000) =      7.168 ms/op
     p(95.0000) =      8.159 ms/op
     p(99.0000) =     10.846 ms/op
     p(99.9000) =     23.567 ms/op
     p(99.9900) =     37.455 ms/op
     p(99.9990) =     39.898 ms/op
     p(99.9999) =     41.288 ms/op
    p(100.0000) =     41.288 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.112 ± 1.835  ops/ms
ClientGrpc.existUser                       thrpt       3   8.960 ± 4.585  ops/ms
ClientGrpc.getUser                         thrpt       3   8.359 ± 1.246  ops/ms
ClientGrpc.listUser                        thrpt       3   6.404 ± 1.293  ops/ms
ClientGrpc.createUser                       avgt       3   3.903 ± 0.922   ms/op
ClientGrpc.existUser                        avgt       3   3.660 ± 1.729   ms/op
ClientGrpc.getUser                          avgt       3   3.791 ± 1.487   ms/op
ClientGrpc.listUser                         avgt       3   5.130 ± 0.950   ms/op
ClientGrpc.createUser                     sample  250930   3.825 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.538           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.703           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.669           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.186           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.280           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.681           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.979           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.671           ms/op
ClientGrpc.existUser                      sample  266418   3.604 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.718           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.535           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.317           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.792           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.650           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.354           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.049           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.264           ms/op
ClientGrpc.getUser                        sample  246369   3.896 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.735           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.772           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.784           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.374           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.447           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.636           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.166           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.345           ms/op
ClientGrpc.listUser                       sample  184804   5.193 ± 0.014   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.442           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.760           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.168           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.159           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.846           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          23.567           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          37.455           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          41.288           ms/op
