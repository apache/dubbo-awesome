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
# Warmup Iteration   1: 1.897 ops/ms
# Warmup Iteration   2: 4.627 ops/ms
# Warmup Iteration   3: 6.448 ops/ms
Iteration   1: 6.528 ops/ms
Iteration   2: 6.541 ops/ms
Iteration   3: 6.654 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.574 ±(99.9%) 1.272 ops/ms [Average]
  (min, avg, max) = (6.528, 6.574, 6.654), stdev = 0.070
  CI (99.9%): [5.303, 7.846] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.851 ops/ms
# Warmup Iteration   2: 6.473 ops/ms
# Warmup Iteration   3: 6.897 ops/ms
Iteration   1: 7.396 ops/ms
Iteration   2: 7.397 ops/ms
Iteration   3: 7.398 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.397 ±(99.9%) 0.021 ops/ms [Average]
  (min, avg, max) = (7.396, 7.397, 7.398), stdev = 0.001
  CI (99.9%): [7.377, 7.418] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.677 ops/ms
# Warmup Iteration   2: 6.327 ops/ms
# Warmup Iteration   3: 6.662 ops/ms
Iteration   1: 7.167 ops/ms
Iteration   2: 7.093 ops/ms
Iteration   3: 7.079 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.113 ±(99.9%) 0.863 ops/ms [Average]
  (min, avg, max) = (7.079, 7.113, 7.167), stdev = 0.047
  CI (99.9%): [6.250, 7.976] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.444 ops/ms
# Warmup Iteration   2: 5.070 ops/ms
# Warmup Iteration   3: 5.317 ops/ms
Iteration   1: 5.437 ops/ms
Iteration   2: 5.345 ops/ms
Iteration   3: 5.329 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.370 ±(99.9%) 1.056 ops/ms [Average]
  (min, avg, max) = (5.329, 5.370, 5.437), stdev = 0.058
  CI (99.9%): [4.315, 6.426] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.144 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.988 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.853 ±(99.9%) 0.012 ms/op
Iteration   1: 4.697 ±(99.9%) 0.004 ms/op
Iteration   2: 4.705 ±(99.9%) 0.006 ms/op
Iteration   3: 4.759 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.720 ±(99.9%) 0.613 ms/op [Average]
  (min, avg, max) = (4.697, 4.720, 4.759), stdev = 0.034
  CI (99.9%): [4.107, 5.333] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.707 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.841 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.685 ±(99.9%) 0.008 ms/op
Iteration   1: 4.441 ±(99.9%) 0.003 ms/op
Iteration   2: 4.702 ±(99.9%) 0.005 ms/op
Iteration   3: 5.311 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.818 ±(99.9%) 8.151 ms/op [Average]
  (min, avg, max) = (4.441, 4.818, 5.311), stdev = 0.447
  CI (99.9%): [≈ 0, 12.968] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.896 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.990 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.656 ±(99.9%) 0.005 ms/op
Iteration   1: 4.507 ±(99.9%) 0.003 ms/op
Iteration   2: 4.535 ±(99.9%) 0.003 ms/op
Iteration   3: 4.345 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.462 ±(99.9%) 1.868 ms/op [Average]
  (min, avg, max) = (4.345, 4.462, 4.535), stdev = 0.102
  CI (99.9%): [2.594, 6.330] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 8.815 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 5.996 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.785 ±(99.9%) 0.027 ms/op
Iteration   1: 5.719 ±(99.9%) 0.024 ms/op
Iteration   2: 5.625 ±(99.9%) 0.014 ms/op
Iteration   3: 6.011 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.785 ±(99.9%) 3.674 ms/op [Average]
  (min, avg, max) = (5.625, 5.785, 6.011), stdev = 0.201
  CI (99.9%): [2.111, 9.459] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.613 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 5.145 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.722 ±(99.9%) 0.015 ms/op
Iteration   1: 4.628 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.971 ms/op
                 createUser·p0.50:   4.481 ms/op
                 createUser·p0.90:   5.874 ms/op
                 createUser·p0.95:   6.455 ms/op
                 createUser·p0.99:   8.356 ms/op
                 createUser·p0.999:  12.747 ms/op
                 createUser·p0.9999: 19.235 ms/op
                 createUser·p1.00:   19.497 ms/op

Iteration   2: 4.799 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.847 ms/op
                 createUser·p0.50:   4.604 ms/op
                 createUser·p0.90:   6.177 ms/op
                 createUser·p0.95:   6.791 ms/op
                 createUser·p0.99:   9.011 ms/op
                 createUser·p0.999:  14.882 ms/op
                 createUser·p0.9999: 17.542 ms/op
                 createUser·p1.00:   17.990 ms/op

Iteration   3: 4.947 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.051 ms/op
                 createUser·p0.50:   4.710 ms/op
                 createUser·p0.90:   6.480 ms/op
                 createUser·p0.95:   7.291 ms/op
                 createUser·p0.99:   9.798 ms/op
                 createUser·p0.999:  18.736 ms/op
                 createUser·p0.9999: 25.692 ms/op
                 createUser·p1.00:   26.083 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 200522
  mean =      4.788 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2624 
    [ 2.500,  5.000) = 128844 
    [ 5.000,  7.500) = 63203 
    [ 7.500, 10.000) = 4597 
    [10.000, 12.500) = 814 
    [12.500, 15.000) = 252 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.847 ms/op
     p(50.0000) =      4.596 ms/op
     p(90.0000) =      6.169 ms/op
     p(95.0000) =      6.857 ms/op
     p(99.0000) =      9.175 ms/op
     p(99.9000) =     14.581 ms/op
     p(99.9900) =     24.243 ms/op
     p(99.9990) =     26.050 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.475 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 4.492 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.286 ±(99.9%) 0.013 ms/op
Iteration   1: 4.090 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.952 ms/op
                 existUser·p0.50:   3.953 ms/op
                 existUser·p0.90:   5.349 ms/op
                 existUser·p0.95:   5.939 ms/op
                 existUser·p0.99:   7.660 ms/op
                 existUser·p0.999:  12.009 ms/op
                 existUser·p0.9999: 22.282 ms/op
                 existUser·p1.00:   22.544 ms/op

Iteration   2: 4.229 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.974 ms/op
                 existUser·p0.50:   4.055 ms/op
                 existUser·p0.90:   5.366 ms/op
                 existUser·p0.95:   5.841 ms/op
                 existUser·p0.99:   7.422 ms/op
                 existUser·p0.999:  12.108 ms/op
                 existUser·p0.9999: 30.849 ms/op
                 existUser·p1.00:   31.228 ms/op

Iteration   3: 4.286 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.094 ms/op
                 existUser·p0.50:   4.076 ms/op
                 existUser·p0.90:   5.661 ms/op
                 existUser·p0.95:   6.324 ms/op
                 existUser·p0.99:   8.423 ms/op
                 existUser·p0.999:  12.865 ms/op
                 existUser·p0.9999: 24.458 ms/op
                 existUser·p1.00:   25.625 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 228479
  mean =      4.200 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7606 
    [ 2.500,  5.000) = 181599 
    [ 5.000,  7.500) = 36167 
    [ 7.500, 10.000) = 2604 
    [10.000, 12.500) = 302 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.952 ms/op
     p(50.0000) =      4.026 ms/op
     p(90.0000) =      5.456 ms/op
     p(95.0000) =      6.029 ms/op
     p(99.0000) =      7.930 ms/op
     p(99.9000) =     12.100 ms/op
     p(99.9900) =     30.134 ms/op
     p(99.9990) =     31.102 ms/op
     p(99.9999) =     31.228 ms/op
    p(100.0000) =     31.228 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.147 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 5.001 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.591 ±(99.9%) 0.015 ms/op
Iteration   1: 4.705 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.188 ms/op
                 getUser·p0.50:   4.506 ms/op
                 getUser·p0.90:   6.283 ms/op
                 getUser·p0.95:   7.102 ms/op
                 getUser·p0.99:   9.388 ms/op
                 getUser·p0.999:  14.926 ms/op
                 getUser·p0.9999: 17.839 ms/op
                 getUser·p1.00:   18.186 ms/op

Iteration   2: 4.699 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.395 ms/op
                 getUser·p0.50:   4.547 ms/op
                 getUser·p0.90:   5.997 ms/op
                 getUser·p0.95:   6.627 ms/op
                 getUser·p0.99:   8.673 ms/op
                 getUser·p0.999:  12.794 ms/op
                 getUser·p0.9999: 21.115 ms/op
                 getUser·p1.00:   21.594 ms/op

Iteration   3: 4.890 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.073 ms/op
                 getUser·p0.50:   4.694 ms/op
                 getUser·p0.90:   6.373 ms/op
                 getUser·p0.95:   7.078 ms/op
                 getUser·p0.99:   9.863 ms/op
                 getUser·p0.999:  14.975 ms/op
                 getUser·p0.9999: 24.117 ms/op
                 getUser·p1.00:   24.281 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 201430
  mean =      4.763 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4740 
    [ 2.500,  5.000) = 127058 
    [ 5.000,  7.500) = 63231 
    [ 7.500, 10.000) = 5012 
    [10.000, 12.500) = 976 
    [12.500, 15.000) = 222 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.073 ms/op
     p(50.0000) =      4.579 ms/op
     p(90.0000) =      6.218 ms/op
     p(95.0000) =      6.947 ms/op
     p(99.0000) =      9.306 ms/op
     p(99.9000) =     14.895 ms/op
     p(99.9900) =     23.939 ms/op
     p(99.9990) =     24.182 ms/op
     p(99.9999) =     24.281 ms/op
    p(100.0000) =     24.281 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.668 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 6.366 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 6.063 ±(99.9%) 0.024 ms/op
Iteration   1: 6.202 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.066 ms/op
                 listUser·p0.50:   5.759 ms/op
                 listUser·p0.90:   8.471 ms/op
                 listUser·p0.95:   9.705 ms/op
                 listUser·p0.99:   12.141 ms/op
                 listUser·p0.999:  20.557 ms/op
                 listUser·p0.9999: 29.814 ms/op
                 listUser·p1.00:   31.457 ms/op

Iteration   2: 6.163 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.054 ms/op
                 listUser·p0.50:   5.743 ms/op
                 listUser·p0.90:   8.372 ms/op
                 listUser·p0.95:   9.617 ms/op
                 listUser·p0.99:   12.534 ms/op
                 listUser·p0.999:  18.224 ms/op
                 listUser·p0.9999: 21.471 ms/op
                 listUser·p1.00:   28.246 ms/op

Iteration   3: 6.159 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.612 ms/op
                 listUser·p0.50:   5.652 ms/op
                 listUser·p0.90:   8.569 ms/op
                 listUser·p0.95:   9.900 ms/op
                 listUser·p0.99:   13.173 ms/op
                 listUser·p0.999:  23.530 ms/op
                 listUser·p0.9999: 28.097 ms/op
                 listUser·p1.00:   28.606 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 155449
  mean =      6.175 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50 
    [ 2.500,  5.000) = 38775 
    [ 5.000,  7.500) = 89498 
    [ 7.500, 10.000) = 20429 
    [10.000, 12.500) = 5049 
    [12.500, 15.000) = 1000 
    [15.000, 17.500) = 355 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.612 ms/op
     p(50.0000) =      5.718 ms/op
     p(90.0000) =      8.471 ms/op
     p(95.0000) =      9.732 ms/op
     p(99.0000) =     12.648 ms/op
     p(99.9000) =     21.121 ms/op
     p(99.9900) =     29.098 ms/op
     p(99.9990) =     31.130 ms/op
     p(99.9999) =     31.457 ms/op
    p(100.0000) =     31.457 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.574 ± 1.272  ops/ms
ClientGrpc.existUser                       thrpt       3   7.397 ± 0.021  ops/ms
ClientGrpc.getUser                         thrpt       3   7.113 ± 0.863  ops/ms
ClientGrpc.listUser                        thrpt       3   5.370 ± 1.056  ops/ms
ClientGrpc.createUser                       avgt       3   4.720 ± 0.613   ms/op
ClientGrpc.existUser                        avgt       3   4.818 ± 8.151   ms/op
ClientGrpc.getUser                          avgt       3   4.462 ± 1.868   ms/op
ClientGrpc.listUser                         avgt       3   5.785 ± 3.674   ms/op
ClientGrpc.createUser                     sample  200522   4.788 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.847           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.596           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.169           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.857           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           9.175           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.581           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.243           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.083           ms/op
ClientGrpc.existUser                      sample  228479   4.200 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.952           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.026           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.456           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.029           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.930           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.100           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          30.134           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          31.228           ms/op
ClientGrpc.getUser                        sample  201430   4.763 ± 0.010   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.073           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.579           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.218           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.947           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           9.306           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.895           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.939           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.281           ms/op
ClientGrpc.listUser                       sample  155449   6.175 ± 0.016   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.612           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.718           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.471           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.732           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.648           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          21.121           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.098           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.457           ms/op
